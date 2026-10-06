## ControlCenterUI

> `/System/Library/AccessibilityBundles/ControlCenterUI.axbundle/ControlCenterUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2160` | `0x21b0` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0xb20` | `0xb40` | **`+0x20`** |
| `__TEXT.__cstring` | `0x9f1` | `0xa04` | **`+0x13`** |
| `__DATA_CONST.__objc_selrefs` | `0x228` | `0x230` | **`+0x8`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  Symbols:   272
-  CStrings:  104
+  Symbols:   274
+  CStrings:  105
Symbols:
+ _objc_release_x24
+ _objc_release_x25
Functions:
~ -[CCUIHeaderPocketViewAccessibility accessibilityElements] : 300 -> 380
CStrings:
+ "secondaryStatusBar"
```
