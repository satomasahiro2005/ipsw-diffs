## PreBoard

> `/System/Library/AccessibilityBundles/PreBoard.axbundle/PreBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x9a0` | `0x9c0` | **`+0x20`** |
| `__TEXT.__text` | `0x2178` | `0x2190` | **`+0x18`** |
| `__TEXT.__cstring` | `0x6f4` | `0x707` | **`+0x13`** |
| `__TEXT.__unwind_info` | `0x140` | `0x148` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 77
-  Symbols:   238
-  CStrings:  88
+  Functions: 78
+  Symbols:   239
+  CStrings:  89
Symbols:
+ GCC_except_table36
+ GCC_except_table40
+ GCC_except_table63
+ _AXSBChargingController
- GCC_except_table35
- GCC_except_table39
- GCC_except_table62
Functions:
+ _AXSBChargingController
CStrings:
+ "chargingController"
```
