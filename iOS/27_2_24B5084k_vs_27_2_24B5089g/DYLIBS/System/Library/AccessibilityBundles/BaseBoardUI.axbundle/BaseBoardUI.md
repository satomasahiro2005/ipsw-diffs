## BaseBoardUI

> `/System/Library/AccessibilityBundles/BaseBoardUI.axbundle/BaseBoardUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x708` | `0x80c` | **`+0x104`** |
| `__AUTH_CONST.__cfstring` | `0x2e0` | `0x340` | **`+0x60`** |
| `__TEXT.__cstring` | `0x20f` | `0x241` | **`+0x32`** |
| `__DATA_CONST.__objc_selrefs` | `0xf0` | `0x108` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x90` | `0x98` | **`+0x8`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  Symbols:   103
-  CStrings:  32
+  Symbols:   104
+  CStrings:  35
Symbols:
+ _objc_retain_x19
Functions:
~ +[BSUIEmojiLabelViewAccessibility _accessibilityPerformValidations:] : 32 -> 152
~ -[BSUIEmojiLabelViewAccessibility accessibilityLabel] : 12 -> 152
CStrings:
+ "BSUIPartialStylingLabelView"
+ "attributedText"
+ "string"
```
