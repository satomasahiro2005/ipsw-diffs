## CarKit

> `/System/Library/PrivateFrameworks/CarKit.framework/CarKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x61044` | `0x613c8` | **`+0x384`** |
| `__AUTH_CONST.__objc_const` | `0x100b8` | `0x10230` | **`+0x178`** |
| `__TEXT.__oslogstring` | `0x6a16` | `0x6aa6` | **`+0x90`** |
| `__AUTH_CONST.__const` | `0x1b50` | `0x1bb0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x625c` | `0x62b4` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x13b0` | `0x1400` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x3690` | `0x36c0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2018` | `0x2040` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1bb0` | `0x1bd8` | **`+0x28`** |
| `__DATA.__bss` | `0x730` | `0x740` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x860` | `0x870` | **`+0x10`** |
| `__TEXT.__const` | `0x538` | `0x548` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xac0` | `0xac8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x270` | `0x278` | **`+0x8`** |

### Other Changes

```diff

-789.1.0.0.0
+792.0.0.0.0

-  Functions: 3020
-  Symbols:   4712
-  CStrings:  1414
+  Functions: 3032
+  Symbols:   4725
+  CStrings:  1417
Symbols:
+ +[CRVehicleStatisticsPublisher publishStatistics:]
+ -[CARScreenInfo(CRDisplayScaling) displayScaleTestDescription]
+ _OBJC_CLASS_$_CRVehicleStatisticsPublisher
+ _OBJC_METACLASS_$_CRVehicleStatisticsPublisher
+ __OBJC_$_CLASS_METHODS_CRVehicleStatisticsPublisher
+ __OBJC_CLASS_RO_$_CRVehicleStatisticsPublisher
+ __OBJC_METACLASS_RO_$_CRVehicleStatisticsPublisher
+ ___50+[CRVehicleStatisticsPublisher publishStatistics:]_block_invoke
+ ___50+[CRVehicleStatisticsPublisher publishStatistics:]_block_invoke_2
+ ___50+[CRVehicleStatisticsPublisher publishStatistics:]_block_invoke_3
+ ___block_descriptor_40_e8_32s_e27_v16?0"<CRCarKitService>"8ls32l8
+ _publishStatistics:.onceToken
+ _publishStatistics:.serviceClient
CStrings:
+ "CRVehicleStatisticsPublisher: publish failed: %@"
+ "CRVehicleStatisticsPublisher: published successfully"
+ "CRVehicleStatisticsPublisher: service error: %@"
```
