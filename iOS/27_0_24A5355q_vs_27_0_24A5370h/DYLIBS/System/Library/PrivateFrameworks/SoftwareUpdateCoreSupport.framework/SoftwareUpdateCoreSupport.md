## SoftwareUpdateCoreSupport

> `/System/Library/PrivateFrameworks/SoftwareUpdateCoreSupport.framework/SoftwareUpdateCoreSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33468` | `0x33c90` | **`+0x828`** |
| `__TEXT.__cstring` | `0x7f9b` | `0x82e7` | **`+0x34c`** |
| `__AUTH_CONST.__cfstring` | `0x7fc0` | `0x8280` | **`+0x2c0`** |
| `__TEXT.__gcc_except_tab` | `0x5b8` | `0x674` | **`+0xbc`** |
| `__DATA_CONST.__objc_selrefs` | `0x2450` | `0x24c0` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0xc00` | `0xc70` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x51de` | `0x5248` | **`+0x6a`** |
| `__AUTH_CONST.__objc_const` | `0x4a58` | `0x4ab8` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x34e4` | `0x3544` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x12f0` | `0x1348` | **`+0x58`** |
| `__DATA.__objc_ivar` | `0x458` | `0x460` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2a0` | `0x2a8` | **`+0x8`** |

### Other Changes

```diff

-2717.0.0.0.0
+2718.0.2.0.0

-  Functions: 1258
-  Symbols:   2201
-  CStrings:  1279
+  Functions: 1269
+  Symbols:   2220
+  CStrings:  1304
Symbols:
+ -[SUCoreDevice _synchronizedAdjustTargetingSystemVolume:]
+ -[SUCoreDevice _synchronizedHasSemiSplatActive]
+ -[SUCoreDevice _synchronizedHasSplatOnlyUpdateInstalled]
+ -[SUCorePersistedState decodeClassNameMappings]
+ -[SUCorePersistedState encodeClassNameMappings]
+ -[SUCorePersistedState setClass:forClassName:]
+ -[SUCorePersistedState setClassName:forClass:]
+ -[SUCorePersistedState setDecodeClassNameMappings:]
+ -[SUCorePersistedState setEncodeClassNameMappings:]
+ GCC_except_table38
+ GCC_except_table39
+ GCC_except_table50
+ _NSKeyedArchiveRootObjectKey
+ _OBJC_IVAR_$_SUCorePersistedState._decodeClassNameMappings
+ _OBJC_IVAR_$_SUCorePersistedState._encodeClassNameMappings
+ ___78-[SUCorePersistedState persistSecureCodedObject:forKey:forType:shouldPersist:]_block_invoke
+ ___78-[SUCorePersistedState secureCodedObjectForKey:ofClass:encodeClasses:forType:]_block_invoke
+ ___block_descriptor_40_e8_32s_e25_v32?0"NSString"8#16^B24ls32l8
+ ___block_descriptor_48_e8_32s40s_e35_v32?0"NSString"8"NSString"16^B24ls32l8s40l8
+ _kSUCoreControllerNoPrecisePreSUStagingReason
- -[SUCoreDevice _hasSplatOnlyUpdateInstalled]
CStrings:
+ "PSUS"
+ "SUCorePersistedState"
+ "[PERSISTED_STATE] encode class name mapping skipped: class %{public}@ not found for coded name %{public}@"
+ "encode class name mapping failed: class %@ not found for coded name %@"
+ "kSUCoreErrorPSUSDisabledByMSUDefault"
+ "kSUCoreErrorPSUSDisabledByPolicy"
+ "kSUCoreErrorPSUSDisabledByServer"
+ "kSUCoreErrorPSUSDisabledForClient"
+ "kSUCoreErrorPSUSDisabledForSFRUpdate"
+ "kSUCoreErrorPSUSDisabledForSplatUpdate"
+ "kSUCoreErrorPSUSDisabledInBaseSystem"
+ "kSUCoreErrorPSUSDisabledInNeRD"
+ "kSUCoreErrorPSUSInvalidResults"
+ "kSUCoreErrorPSUSNotSupported"
+ "kSUCoreErrorPSUSNothingToStage"
+ "kSUCoreErrorPSUSOptionalDisabledByPolicy"
+ "kSUCoreErrorPSUSOptionalDisabledByServer"
+ "kSUCoreErrorPSUSOptionalNoSpaceAllowed"
+ "kSUCoreErrorPSUSOptionalNonUserInitiatedDownloadNotAllowed"
+ "kSUCoreErrorPrecisePSUSDisabledByPolicy"
+ "kSUCoreErrorPrecisePSUSNoConfigFound"
+ "noPrecisePreSUStagingReason"
+ "unknown archiving exception"
+ "v32@?0@\"NSString\"8#16^B24"
+ "v32@?0@\"NSString\"8@\"NSString\"16^B24"
```
