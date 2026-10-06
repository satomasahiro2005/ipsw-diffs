## NTKUltraBezel

> `/System/Library/PrivateFrameworks/NTKUltraBezel.framework/NTKUltraBezel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x114ec` | `0x117ac` | **`+0x2c0`** |
| `__TEXT.__const` | `0x472` | `0x502` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x18f8` | `0x1920` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xe60` | `0xe84` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0xbd8` | `0xbe8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x468` | `0x470` | **`+0x8`** |

### Other Changes

```diff

-2483.503.0.0.0
+2483.512.0.0.0

-  Functions: 411
-  Symbols:   830
+  Functions: 413
+  Symbols:   832
Symbols:
+ -[NTKFoghornCompassDataSource usesTrueNorth]
+ -[NTKFoghornFaceBezelView(UIColor) _setHarmoniaMultiColors]
Functions:
+ -[NTKFoghornCompassDataSource usesTrueNorth]
~ +[NTKFoghornFaceBezelView(UIColor) _primaryColorForBezelStyle:] : 328 -> 336
+ -[NTKFoghornFaceBezelView(UIColor) _setHarmoniaMultiColors]
~ -[NTKFoghornFaceBezelView(UIColor) setColorsForBezelStyle:] : 100 -> 116
```
