## SensingAlgsService

> `/System/Library/PrivateFrameworks/SensingAlgsService.framework/SensingAlgsService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20988` | `0x20db8` | **`+0x430`** |
| `__TEXT.__oslogstring` | `0x16a8` | `0x17b4` | **`+0x10c`** |
| `__TEXT.__eh_frame` | `—` | `0x38` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0xab0` | `0xad0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x7e0` | `0x7f0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x598` | `0x5a0` | **`+0x8`** |
| `__TEXT.__cstring` | `0x3e1` | `0x3dd` | **`-0x4`** |

### Other Changes

```diff

-66.2.0.0.0
+68.0.0.0.0

-  Functions: 778
-  Symbols:   1409
-  CStrings:  152
+  Functions: 780
+  Symbols:   1408
+  CStrings:  155
Symbols:
+ -[SASInterfaceTouch isInAnyActivePlan]
+ GCC_except_table124
+ GCC_except_table132
+ __ZN14SABinaryParser13parseInfoDataEPFbPvhjhhEPFbS0_PKcEPFbS0_bEPFbS0_RK20_SABinaryInjExtPointEPFbS0_SB_tjPKhE
- GCC_except_table122
- GCC_except_table131
- _OUTLINED_FUNCTION_40
- _OUTLINED_FUNCTION_41
- __ZN14SABinaryParser13parseInfoDataEPFbPvhjhhEPFbS0_PKcEPFbS0_bEPFbS0_RK20_SABinaryInjExtPointE
CStrings:
+ "21.0.0 (clang-2100.3.23.3) [+internal-os]"
+ "24A366"
+ "HysteresisFilterStep:  Resetting hysteresis filter. Priors: before_touching=%d, start_touching=%d, stop_touching=%d, slid_while_engaged=%d"
+ "MultiEventGenerationStep: Event mask changed=0x%x, setting valid"
+ "MultiEventGenerationStep: Phase changed %d -> %d, setting valid"
+ "SensingAlgsService-68~21"
- "21.0.0 (clang-2100.3.19.4) [+internal-os]"
- "24A5352s"
- "SensingAlgsService-66.2~38"
```
