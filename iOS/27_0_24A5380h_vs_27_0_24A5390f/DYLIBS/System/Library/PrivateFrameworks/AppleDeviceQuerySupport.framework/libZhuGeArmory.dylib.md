## libZhuGeArmory.dylib

> `/System/Library/PrivateFrameworks/AppleDeviceQuerySupport.framework/libZhuGeArmory.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23f90` | `0x242c0` | **`+0x330`** |
| `__TEXT.__cstring` | `0xaa01` | `0xab56` | **`+0x155`** |
| `__AUTH_CONST.__cfstring` | `0x8320` | `0x83e0` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x868` | `0x888` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x834` | `0x84c` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x508` | `0x518` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3f0` | `0x3f8` | **`+0x8`** |

### Other Changes

```diff

-459.0.7.0.0
+459.0.14.0.0

+  - /usr/lib/libTelephonyUtilDynamic.dylib

-  Functions: 350
-  Symbols:   734
-  CStrings:  1254
+  Functions: 352
+  Symbols:   738
+  CStrings:  1261
Symbols:
+ +[ZhuGeBasebandArmory isAppleBaseband]
+ +[ZhuGeBasebandArmory queryCHUnitSimMuxDualPhysicalStateWithError:]
+ GCC_except_table31
+ GCC_except_table35
+ _TelephonyRadiosGetRadioVendor
+ _strtoimax
- GCC_except_table29
- GCC_except_table33
Functions:
+ +[ZhuGeBasebandArmory queryCHUnitSimMuxDualPhysicalStateWithError:]
+ +[ZhuGeBasebandArmory isAppleBaseband]
~ +[ZhuGeKeysActionArmory queryIOProperty:fromCriteria:withError:] : 8064 -> 8192
CStrings:
+ "\"%@\" is not a valid integer"
+ "+[ZhuGeBasebandArmory queryCHUnitSimMuxDualPhysicalStateWithError:]"
+ "Device does not support dynamic configuration"
+ "Failed to query isEuiccActive: %@"
+ "Failed to query supportsDynamicSIMConfiguration: %@"
+ "SIM_MUX verified: Device is in P+E configuration (expected P+P)"
+ "SIM_MUX verified: Device is in P+P configuration"
```
