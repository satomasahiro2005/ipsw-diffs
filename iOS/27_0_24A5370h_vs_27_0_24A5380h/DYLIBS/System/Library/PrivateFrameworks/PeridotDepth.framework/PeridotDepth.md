## PeridotDepth

> `/System/Library/PrivateFrameworks/PeridotDepth.framework/PeridotDepth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x143a8c` | `0x143440` | **`-0x64c`** |
| `__DATA_DIRTY.__bss` | `0x260` | `0x2a0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x7ce4` | `0x7d14` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1b48` | `0x1b70` | **`+0x28`** |
| `__DATA.__bss` | `0x28a9c8` | `0x28a9b8` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x133c` | `0x134c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xf20` | `0xf28` | **`+0x8`** |

### Other Changes

```diff

-51.1.0.0.0
+52.0.1.0.0

-  Functions: 1507
-  Symbols:   2957
+  Functions: 1508
+  Symbols:   2956
Symbols:
+ +[PDPeridotCameraSystemCalibrationData getNominalWideToPeridotExtrinsics:forDeviceName:]
+ GCC_except_table1102
+ GCC_except_table1109
+ GCC_except_table1164
+ GCC_except_table1169
+ GCC_except_table1172
+ GCC_except_table1176
+ GCC_except_table1223
+ GCC_except_table1229
+ GCC_except_table1231
+ GCC_except_table727
+ GCC_except_table731
+ __ZGVZN7peridot5calib33getNominalWideToPeridotExtrinsicsERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEPbE4cos3
+ __ZGVZN7peridot5calib33getNominalWideToPeridotExtrinsicsERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEPbE4sin3
+ __ZGVZN7peridot5calib33getNominalWideToPeridotExtrinsicsERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEPbE5R_V5x
+ __ZGVZN7peridot5calib33getNominalWideToPeridotExtrinsicsERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEPbE5R_y_3
+ __ZGVZN7peridot5calib33getNominalWideToPeridotExtrinsicsERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEPbE6R_z_90
+ __ZN7peridot5calib33getNominalWideToPeridotExtrinsicsERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEPb
+ __ZZN7peridot5calib33getNominalWideToPeridotExtrinsicsERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEPbE4cos3
+ __ZZN7peridot5calib33getNominalWideToPeridotExtrinsicsERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEPbE4sin3
+ __ZZN7peridot5calib33getNominalWideToPeridotExtrinsicsERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEPbE5R_V5x
+ __ZZN7peridot5calib33getNominalWideToPeridotExtrinsicsERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEPbE5R_y_3
+ __ZZN7peridot5calib33getNominalWideToPeridotExtrinsicsERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEPbE6R_z_90
- GCC_except_table1106
- GCC_except_table1163
- GCC_except_table1168
- GCC_except_table1171
- GCC_except_table1174
- GCC_except_table1222
- GCC_except_table1228
- GCC_except_table1230
- GCC_except_table725
- GCC_except_table729
- __ZGVZL20getNominalExtrinsicsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEE10R_y_minus3
- __ZGVZL20getNominalExtrinsicsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEE11R_z_minus90
- __ZGVZL20getNominalExtrinsicsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEE4cos3
- __ZGVZL20getNominalExtrinsicsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEE4sin3
- __ZGVZL20getNominalExtrinsicsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEE5R_V5x
- __ZGVZL20getNominalExtrinsicsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEE5R_V6x
- __ZGVZL20getNominalExtrinsicsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEE5R_y_3
- __ZGVZL20getNominalExtrinsicsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEE6R_z_90
- __ZL20getNominalExtrinsicsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE
- __ZZL20getNominalExtrinsicsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEE4cos3
- __ZZL20getNominalExtrinsicsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEE4sin3
- __ZZL20getNominalExtrinsicsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEE5R_V5x
- __ZZL20getNominalExtrinsicsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEE5R_y_3
- __ZZL20getNominalExtrinsicsRKNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEE6R_z_90
```
