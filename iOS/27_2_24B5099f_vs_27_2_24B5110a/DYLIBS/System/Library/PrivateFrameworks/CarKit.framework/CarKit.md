## CarKit

> `/System/Library/PrivateFrameworks/CarKit.framework/CarKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62928` | `0x62bd8` | **`+0x2b0`** |
| `__TEXT.__oslogstring` | `0x6c26` | `0x6c96` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x20a0` | `0x20c8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x3750` | `0x3770` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x63ec` | `0x6404` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x880` | `0x888` | **`+0x8`** |

### Other Changes

```diff

-807.4.0.0.0
+807.4.1.0.0

-  Functions: 3058
-  Symbols:   4757
-  CStrings:  1434
+  Functions: 3060
+  Symbols:   4761
+  CStrings:  1436
Symbols:
+ +[CRVehicleVideoSettings _analyticsEntriesFromData:]
+ _OBJC_CLASS_$_NSJSONSerialization
+ __OBJC_$_CLASS_METHODS_CRVehicleVideoSettings
+ ___block_descriptor_48_e8_32s40bs_e28_v24?0"NSData"8"NSError"16ls40l8s32l8
Functions:
~ ___59-[CRVehicleVideoSettings fetchAnalyticsDataWithCompletion:]_block_invoke : 188 -> 192
~ ___59-[CRVehicleVideoSettings fetchAnalyticsDataWithCompletion:]_block_invoke_2 : 320 -> 236
+ +[CRVehicleVideoSettings _analyticsEntriesFromData:]
+ +[CRVehicleVideoSettings _analyticsEntriesFromData:].cold.1
CStrings:
+ "couldn't expand analytics into entries, returning single blob: %{public}@"
+ "couldn't serialize analytics entry: %{public}@"
```
