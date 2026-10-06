## ControlCenterUI

> `/System/Library/AccessibilityBundles/ControlCenterUI.axbundle/ControlCenterUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20c8` | `0x2160` | **`+0x98`** |
| `__TEXT.__cstring` | `0x9ce` | `0x9f1` | **`+0x23`** |
| `__AUTH_CONST.__cfstring` | `0xb00` | `0xb20` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x220` | `0x228` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x40` | `0x48` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x408` | `0x410` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x160` | `0x168` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 82
-  Symbols:   271
-  CStrings:  103
+  Functions: 83
+  Symbols:   272
+  CStrings:  104
Symbols:
+ -[CCUIIconListViewAccessibility accessibilityElementsHidden]
+ GCC_except_table39
+ GCC_except_table72
+ GCC_except_table75
- GCC_except_table38
- GCC_except_table71
- GCC_except_table74
Functions:
~ +[CCUIIconListViewAccessibility _accessibilityPerformValidations:] : 180 -> 212
+ -[CCUIIconListViewAccessibility accessibilityElementsHidden]
CStrings:
+ "layoutDelegate.currentIconListView"
```
