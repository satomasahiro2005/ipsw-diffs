## TextInputUI

> `/System/Library/AccessibilityBundles/TextInputUI.axbundle/TextInputUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a10` | `0x4ba8` | **`+0x198`** |
| `__AUTH_CONST.__objc_const` | `0x1830` | `0x1950` | **`+0x120`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x10c0` | `0x1160` | **`+0xa0`** |
| `__TEXT.__cstring` | `0xe74` | `0xec6` | **`+0x52`** |
| `__TEXT.__objc_methlist` | `0x8fc` | `0x944` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x4f0` | `0x510` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x150` | `0x168` | **`+0x18`** |
| `__TEXT.__ustring` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x158` | `0x168` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x260` | `0x268` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 172
-  Symbols:   525
-  CStrings:  158
+  Functions: 176
+  Symbols:   542
+  CStrings:  163
Symbols:
+ +[TUIWritingToolCandidateCellAccessibility _accessibilityPerformValidations:]
+ +[TUIWritingToolCandidateCellAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[TUIWritingToolCandidateCellAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[TUIWritingToolCandidateCellAccessibility accessibilityAttributedLabel]
+ _OBJC_CLASS_$_NSLocale
+ _OBJC_CLASS_$_NSMutableAttributedString
+ _OBJC_CLASS_$_TUIWritingToolCandidateCellAccessibility
+ _OBJC_CLASS_$___TUIWritingToolCandidateCellAccessibility_super
+ _OBJC_METACLASS_$_TUIWritingToolCandidateCellAccessibility
+ _OBJC_METACLASS_$___TUIWritingToolCandidateCellAccessibility_super
+ _UIAccessibilitySpeechAttributeIPANotation
+ __OBJC_$_CLASS_METHODS_TUIWritingToolCandidateCellAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_TUIWritingToolCandidateCellAccessibility
+ __OBJC_CLASS_RO_$_TUIWritingToolCandidateCellAccessibility
+ __OBJC_CLASS_RO_$___TUIWritingToolCandidateCellAccessibility_super
+ __OBJC_METACLASS_RO_$_TUIWritingToolCandidateCellAccessibility
+ __OBJC_METACLASS_RO_$___TUIWritingToolCandidateCellAccessibility_super
CStrings:
+ "Proofread"
+ "TUIWritingToolCandidateCell"
+ "TUIWritingToolCandidateCellAccessibility"
+ "en"
+ "ˈpɻuːf.ɻiːd"
```
