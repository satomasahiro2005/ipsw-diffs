## TextInputUI

> `/System/Library/AccessibilityBundles/TextInputUI.axbundle/TextInputUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x49c8` | `0x4a10` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x10a0` | `0x10c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0xe5f` | `0xe74` | **`+0x15`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  CStrings:  157
+  CStrings:  158
Functions:
~ -[TUICandidateGridAccessibility _accessibilityScannerGroupElements] : 2224 -> 2216
~ -[TUICandidateSortControlAccessibility layoutSubviews] : 344 -> 340
~ -[TUICandidateViewAccessibility _accessibilityScannerGroupElements] : 1088 -> 1080
~ -[TUIPredictionViewCellAccessibility accessibilityTraits] : 136 -> 152
~ +[TUIProactiveCandidateCellAccessibility _accessibilityPerformValidations:] : 64 -> 120
~ -[TUISystemInputAssistantViewAccessibility _accessibilityScannerGroupElements] : 692 -> 688
~ +[TUICandidateCellAccessibility _accessibilityPerformValidations:] : 260 -> 284
CStrings:
+ "TUICandidateBaseCell"
```
