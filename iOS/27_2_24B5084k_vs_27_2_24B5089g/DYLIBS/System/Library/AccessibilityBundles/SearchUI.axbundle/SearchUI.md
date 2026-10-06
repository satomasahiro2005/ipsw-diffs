## SearchUI

> `/System/Library/AccessibilityBundles/SearchUI.axbundle/SearchUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa064` | `0xa164` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0x2440` | `0x24c0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x1a39` | `0x1a83` | **`+0x4a`** |
| `__DATA_CONST.__objc_selrefs` | `0x568` | `0x578` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xf64` | `0xf74` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x440` | `0x448` | **`+0x8`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  Functions: 321
-  Symbols:   848
-  CStrings:  307
+  Functions: 322
+  Symbols:   849
+  CStrings:  311
Symbols:
+ -[SearchUIButtonItemViewAccessibility _accessibilityIsCopyButtonInCopiedState]
+ GCC_except_table112
+ GCC_except_table82
+ GCC_except_table93
- GCC_except_table111
- GCC_except_table81
- GCC_except_table92
Functions:
~ +[SearchUIButtonItemViewAccessibility _accessibilityPerformValidations:] : 192 -> 276
~ -[SearchUIButtonItemViewAccessibility accessibilityLabel] : 240 -> 272
+ -[SearchUIButtonItemViewAccessibility _accessibilityIsCopyButtonInCopiedState]
CStrings:
+ "SearchUIButtonItem"
+ "SearchUICopyButtonItem"
+ "copy.button.copied.label"
+ "status"
```
