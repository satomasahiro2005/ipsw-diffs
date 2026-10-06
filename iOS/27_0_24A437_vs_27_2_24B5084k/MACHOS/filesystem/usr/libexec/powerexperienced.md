## powerexperienced

> `/usr/libexec/powerexperienced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c2cc` | `0x1bd58` | **`-0x574`** |
| `__TEXT.__oslogstring` | `0x3455` | `0x3356` | **`-0xff`** |
| `__TEXT.__objc_methname` | `0x4508` | `0x443b` | **`-0xcd`** |
| `__TEXT.__objc_stubs` | `0x3ca0` | `0x3c00` | **`-0xa0`** |
| `__TEXT.__dlopen_cstrs` | `0x8d` | `—` | **`-0x8d`** |
| `__TEXT.__auth_stubs` | `0x730` | `0x6c0` | **`-0x70`** |
| `__TEXT.__cstring` | `0x13e4` | `0x1375` | **`-0x6f`** |
| `__DATA.__objc_const` | `0x5a40` | `0x59e0` | **`-0x60`** |
| `__DATA_CONST.__cfstring` | `0x1400` | `0x1440` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x940` | `0x900` | **`-0x40`** |
| `__DATA_CONST.__auth_got` | `0x3a8` | `0x370` | **`-0x38`** |
| `__DATA.__objc_selrefs` | `0x1260` | `0x1238` | **`-0x28`** |
| `__TEXT.__objc_methlist` | `0x25c4` | `0x259c` | **`-0x28`** |
| `__DATA.__bss` | `0x290` | `0x278` | **`-0x18`** |
| `__TEXT.__objc_methtype` | `0x8eb` | `0x8d3` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0x5c` | `0x4c` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x7d0` | `0x7c0` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x290` | `0x288` | **`-0x8`** |
| `__TEXT.__const` | `0x158` | `0x150` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-176.0.0.0.0
+180.0.0.0.0

-  - /System/Library/PrivateFrameworks/SoftLinking.framework/SoftLinking

-  Functions: 889
-  Symbols:   178
-  CStrings:  1502
+  Functions: 878
+  Symbols:   171
+  CStrings:  1484
Symbols:
- __Block_object_dispose
- __sl_dlopen
- _abort_report_np
- _dlopen_preflight
- _free
- _objc_getClass
- _objc_retain_x9
CStrings:
+ "HardwarePlatform"
+ "Trial: Setting TrialID: %lld with CLPC"
+ "Trial:Error setting clpc trial value %@"
+ "kHardwarePlatformContext"
+ "resetForTesting"
+ "waitForPendingEvaluation"
- "%s"
- "/AppleInternal/Library/Frameworks/PerformanceControlKitInternal.framework/PerformanceControlKitInternal"
- "@\"<CLPCInternalAccess>\""
- "CLPCInternalInterface"
- "Charging, not in use and TP Light. ChargingTPLight"
- "Error creating CLPC Internal User Client %@"
- "Error setting clpc trial value %@"
- "Initialized internal CLPC Policy Interface"
- "PerformanceControlKitInternal not available"
- "T@\"<CLPCInternalAccess>\",&,V_clpcInternalAccessClient"
- "TB,V_isInternal"
- "Trial:No trial value for CLPC tuning option. Resetting to default"
- "Unable to find class %s"
- "Updating CLPCInternal client RPC buffer size to 16k"
- "_clpcInternalAccessClient"
- "_isInternal"
- "clpcInternalAccessClient"
- "isChargingTPLite"
- "isInternal"
- "numberWithUnsignedInt:"
- "setClpcInternalAccessClient:"
- "setIsInternal:"
- "setRPCBufferSize:"
- "softlink:o:path:/System/Library/../../AppleInternal/Library/Frameworks/PerformanceControlKitInternal.framework/PerformanceControlKitInternal"
```
