## AccessibilityTextSizeModule

> `/System/Library/ControlCenter/Bundles/AccessibilityTextSizeModule.bundle/AccessibilityTextSizeModule`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd124` | `0xd0f8` | **`-0x2c`** |
| `__AUTH_CONST.__cfstring` | `0x420` | `0x440` | **`+0x20`** |
| `__TEXT.__cstring` | `0x411` | `0x42d` | **`+0x1c`** |
| `__DATA_CONST.__objc_arraydata` | `0x60` | `0x68` | **`+0x8`** |

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0

-  CStrings:  56
+  CStrings:  57
Functions:
~ sub_23c05b000 -> sub_23d1cf000 : 632 -> 628
~ sub_23c05b874 -> sub_23d1cf870 : 336 -> 332
~ sub_23c05b9c4 -> sub_23d1cf9bc : 336 -> 332
~ sub_23c05bb68 -> sub_23d1cfb5c : 332 -> 328
~ sub_23c05bd00 -> sub_23d1cfcf0 : 1300 -> 1296
~ sub_23c05c214 -> sub_23d1d0200 : 352 -> 348
~ sub_23c05c4c4 -> sub_23d1d04ac : 376 -> 372
~ sub_23c05da00 -> sub_23d1d19e4 : 1188 -> 1176
~ sub_23c05ee18 -> sub_23d1d2df0 : 260 -> 256
~ sub_23c05f9e4 -> sub_23d1d39b8 : 1412 -> 1408
~ sub_23c05ff68 -> sub_23d1d3f38 : 76 -> 72
~ sub_23c060248 -> sub_23d1d4214 : 352 -> 348
~ sub_23c060a34 -> sub_23d1d49fc : 316 -> 312
~ sub_23c060b70 -> sub_23d1d4b34 : 320 -> 316
~ sub_23c060cb0 -> sub_23d1d4c70 : 316 -> 312
~ sub_23c064808 -> sub_23d1d87c4 : 380 -> 388
~ sub_23c0661f0 -> sub_23d1da1b4 : 256 -> 276
~ sub_23c0668f4 -> sub_23d1da8cc : 604 -> 600
CStrings:
+ "com.apple.PassbookUIService"
```
