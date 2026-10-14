## WirelessProximity

> `/System/Library/PrivateFrameworks/WirelessProximity.framework/WirelessProximity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x343b4` | `0x34400` | **`+0x4c`** |
| `__AUTH_CONST.__objc_const` | `0x3278` | `0x3288` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1788` | `0x1790` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2c9c` | `0x2ca4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1628` | `0x1630` | **`+0x8`** |

### Other Changes

```diff

-2701.7.0.0.0
+2701.7.1.0.0

-  Functions: 2005
-  Symbols:   1902
+  Functions: 2006
+  Symbols:   1903
Symbols:
+ +[WPClient isHomeAccessory]
+ GCC_except_table107
+ GCC_except_table114
+ GCC_except_table118
+ GCC_except_table122
+ GCC_except_table126
+ GCC_except_table131
+ GCC_except_table136
+ GCC_except_table141
+ GCC_except_table146
+ GCC_except_table151
+ GCC_except_table155
+ GCC_except_table159
+ GCC_except_table172
+ GCC_except_table178
+ GCC_except_table183
+ GCC_except_table188
+ GCC_except_table193
+ GCC_except_table198
+ GCC_except_table204
+ GCC_except_table209
+ GCC_except_table214
+ GCC_except_table24
+ GCC_except_table47
+ GCC_except_table66
+ GCC_except_table72
+ GCC_except_table78
+ GCC_except_table82
+ GCC_except_table90
+ GCC_except_table94
+ GCC_except_table98
+ __isHomeAccessory
- GCC_except_table106
- GCC_except_table113
- GCC_except_table117
- GCC_except_table121
- GCC_except_table125
- GCC_except_table130
- GCC_except_table135
- GCC_except_table140
- GCC_except_table145
- GCC_except_table150
- GCC_except_table154
- GCC_except_table158
- GCC_except_table171
- GCC_except_table177
- GCC_except_table182
- GCC_except_table187
- GCC_except_table192
- GCC_except_table197
- GCC_except_table203
- GCC_except_table208
- GCC_except_table213
- GCC_except_table23
- GCC_except_table41
- GCC_except_table46
- GCC_except_table65
- GCC_except_table71
- GCC_except_table77
- GCC_except_table81
- GCC_except_table89
- GCC_except_table93
- GCC_except_table97
Functions:
~ -[WPHeySiri startAdvertisingWithData:] : 508 -> 520
~ -[WPClient startAdvertising:] : 976 -> 984
+ +[WPClient isHomeAccessory]
~ +[WPClient initialize] : 160 -> 180
~ -[WPHeySiri startScanning:] : 956 -> 980
```
