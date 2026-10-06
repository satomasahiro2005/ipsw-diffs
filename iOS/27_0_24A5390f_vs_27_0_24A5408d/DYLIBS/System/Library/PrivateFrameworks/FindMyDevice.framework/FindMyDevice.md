## FindMyDevice

> `/System/Library/PrivateFrameworks/FindMyDevice.framework/FindMyDevice`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a318` | `0x2b07c` | **`+0xd64`** |
| `__TEXT.__oslogstring` | `0x2f7b` | `0x310c` | **`+0x191`** |
| `__DATA_CONST.__const` | `0x1300` | `0x13f0` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x46c7` | `0x4797` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0xc38` | `0xc58` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x3e0` | `0x3f0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x1d0` | **`+0x8`** |

### Other Changes

```diff

-482.30.6.14.8
+482.30.6.14.20

-  Functions: 1480
-  Symbols:   2369
-  CStrings:  925
+  Functions: 1493
+  Symbols:   2381
+  CStrings:  936
Symbols:
+ GCC_except_table38
+ GCC_except_table41
+ GCC_except_table46
+ GCC_except_table49
+ _OUTLINED_FUNCTION_8
+ _OUTLINED_FUNCTION_9
+ ___FMDErrorCompletionDeliveredOnce_block_invoke
+ ___FMDMakeExactlyOnceGate_block_invoke
+ ___block_descriptor_48_e8_32bs40bs_e20_v24?0Q8"NSError"16ls32l8s40l8
+ ___block_descriptor_48_e8_32bs40bs_e28_v24?0"NSData"8"NSError"16ls32l8s40l8
+ ___block_descriptor_48_e8_32bs40bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8s40l8
+ ___block_descriptor_48_e8_32bs40bs_e43_v24?0"FMDActivationLockInfo"8"NSError"16ls32l8s40l8
+ ___block_descriptor_48_e8_32s40r_e5_B8?0ls32l8r40l8
+ ___block_descriptor_56_e8_32bs40bs_e17_v16?0"NSError"8ls32l8s40l8
+ _objc_sync_enter
+ _objc_sync_exit
- GCC_except_table37
- GCC_except_table40
- GCC_except_table45
- GCC_except_table48
CStrings:
+ "%s: dropping second completion delivery (error: %@)"
+ "B8@?0"
+ "activationLockInfoFromDeviceWithCompletion: dropping second completion delivery (error: %@)"
+ "clearOfflineFindingInfoWithCompletion:"
+ "didAddLocalFindableAccessory:completion:"
+ "didRemoveLocalFindableAccessory:completion:"
+ "fetchOfflineFindingInfoWithCompletion: dropping second completion delivery (error: %@)"
+ "fmipStateWithCompletion: dropping second completion delivery (state: %ld, error: %@)"
+ "signatureHeadersWithData:completion: dropping second completion delivery (error: %@)"
+ "storeOfflineFindingInfo:completion:"
+ "v24@?0@\"FMDActivationLockInfo\"8@\"NSError\"16"
```
