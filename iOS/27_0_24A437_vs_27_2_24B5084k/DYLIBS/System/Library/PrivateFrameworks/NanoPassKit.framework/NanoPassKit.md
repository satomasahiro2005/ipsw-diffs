## NanoPassKit

> `/System/Library/PrivateFrameworks/NanoPassKit.framework/NanoPassKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ea8bc` | `0x1eb5a4` | **`+0xce8`** |
| `__TEXT.__oslogstring` | `0x22879` | `0x22b0f` | **`+0x296`** |
| `__AUTH_CONST.__objc_const` | `0x36f20` | `0x37168` | **`+0x248`** |
| `__TEXT.__objc_methlist` | `0x1ffa8` | `0x20098` | **`+0xf0`** |
| `__AUTH.__objc_data` | `0x8d90` | `0x8e30` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x8f00` | `0x8f78` | **`+0x78`** |
| `__TEXT.__cstring` | `0x12cd4` | `0x12d24` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x7498` | `0x74e8` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0x16b8` | `0x16d0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x3808` | `0x3820` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xf78` | `0xf88` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0xf20` | `0xf28` | **`+0x8`** |

### Other Changes

```diff

-1347.0.0.0.0
+1353.0.0.0.0

-  Functions: 11919
-  Symbols:   18649
-  CStrings:  3754
+  Functions: 11947
+  Symbols:   18696
+  CStrings:  3762
Symbols:
+ +[NPKPassLibrarySyncState _shouldAddPass:withDeviceIsTinker:supportHealthPass:stateVersion:hasValidSignature:]
+ -[NPKPassLibrarySyncState initWithPasses:device:signatureValidationCache:]
+ -[NPKPassSignatureValidationCache .cxx_destruct]
+ -[NPKPassSignatureValidationCache hasValidSignatureForPass:manifestHash:]
+ -[NPKPassSignatureValidationCache init]
+ -[NPKPassSignatureValidationCache invalidatePassWithUniqueID:]
+ -[NPKPassSignatureValidationCacheEntry .cxx_destruct]
+ -[NPKPassSignatureValidationCacheEntry contentToken]
+ -[NPKPassSignatureValidationCacheEntry hasValidSignature]
+ -[NPKPassSignatureValidationCacheEntry setContentToken:]
+ -[NPKPassSignatureValidationCacheEntry setHasValidSignature:]
+ -[NPKPassSyncService initWithPassSyncEngineRole:pairedDevice:]
+ -[NPKPassSyncService pairedDevice]
+ -[NPKPassSyncService passSyncEngineArchivePath]
+ -[NPKPassSyncService setPassSyncEngineArchivePath:]
+ -[NPKPassSyncStateItem isValidForSync]
+ -[NPKPassSyncStateItem syncValidationDescription]
+ GCC_except_table163
+ GCC_except_table164
+ GCC_except_table166
+ GCC_except_table167
+ GCC_except_table207
+ GCC_except_table234
+ GCC_except_table84
+ _NPKHomeDirectorySubpath
+ _NPKHomeDirectorySubpathForDevice
+ _NPKPassHasValidSignatureForStandaloneSync
+ _NPKPassNeedsSignatureValidationForStandaloneSync
+ _NPKPassSyncEngineArchivePathForDevice
+ _NPKPaymentWebServiceBackgroundContextPathForDevice
+ _NPKPeerPaymentAccountPathForDevice
+ _NPKPeerPaymentWebServiceContextPathForDevice
+ _NPKShouldUseStandaloneSyncForPassWithDeviceAndSignatureValidity
+ _NPKStorePathForPaymentPassWithUniqueIDForDevice
+ _NPKStorePathForPaymentPassWithUniqueIDInDirectory
+ _NPKValidatePassSignatureForStandaloneSync
+ _OBJC_CLASS_$_NPKPassSignatureValidationCache
+ _OBJC_CLASS_$_NPKPassSignatureValidationCacheEntry
+ _OBJC_IVAR_$_NPKPassSignatureValidationCache._entriesByUniqueID
+ _OBJC_IVAR_$_NPKPassSignatureValidationCache._lock
+ _OBJC_IVAR_$_NPKPassSignatureValidationCacheEntry._contentToken
+ _OBJC_IVAR_$_NPKPassSignatureValidationCacheEntry._hasValidSignature
+ _OBJC_IVAR_$_NPKPassSyncService._pairedDevice
+ _OBJC_IVAR_$_NPKPassSyncService._passSyncEngineArchivePath
+ _OBJC_METACLASS_$_NPKPassSignatureValidationCache
+ _OBJC_METACLASS_$_NPKPassSignatureValidationCacheEntry
+ __OBJC_$_INSTANCE_METHODS_NPKPassSignatureValidationCache
+ __OBJC_$_INSTANCE_METHODS_NPKPassSignatureValidationCacheEntry
+ __OBJC_$_INSTANCE_VARIABLES_NPKPassSignatureValidationCache
+ __OBJC_$_INSTANCE_VARIABLES_NPKPassSignatureValidationCacheEntry
+ __OBJC_$_PROP_LIST_NPKPassSignatureValidationCacheEntry
+ __OBJC_CLASS_RO_$_NPKPassSignatureValidationCache
+ __OBJC_CLASS_RO_$_NPKPassSignatureValidationCacheEntry
+ __OBJC_METACLASS_RO_$_NPKPassSignatureValidationCache
+ __OBJC_METACLASS_RO_$_NPKPassSignatureValidationCacheEntry
+ ___34-[NPKPassSyncState initWithCoder:]_block_invoke
+ ___62-[NPKPassSyncService initWithPassSyncEngineRole:pairedDevice:]_block_invoke
+ ___74-[NPKPassLibrarySyncState initWithPasses:device:signatureValidationCache:]_block_invoke
+ ___74-[NPKPassLibrarySyncState initWithPasses:device:signatureValidationCache:]_block_invoke_2
+ ___74-[NPKPassLibrarySyncState initWithPasses:device:signatureValidationCache:]_block_invoke_3
+ ___block_descriptor_66_e8_32s40s48s56s_e20_v24?0"PKPass"8^B16ls32l8s40l8s48l8s56l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72bs_e47_v24?0"NPKIDVRemoteDeviceSession"8"NSError"16ls32l8s72l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_90_e8_32s40s48s56s64s72r80r_e25_v32?0"NSNumber"8Q16^B24ls32l8r72l8s40l8r80l8s48l8s56l8s64l8
- +[NPKPassLibrarySyncState _shouldAddPass:withDeviceIsTinker:supportHealthPass:stateVersion:]
- GCC_except_table157
- GCC_except_table158
- GCC_except_table159
- GCC_except_table160
- GCC_except_table195
- GCC_except_table225
- GCC_except_table227
- _NPKRasterizedPassCachePath
- ___49-[NPKPassLibrarySyncState initWithPasses:device:]_block_invoke
- ___49-[NPKPassLibrarySyncState initWithPasses:device:]_block_invoke_2
- ___49-[NPKPassLibrarySyncState initWithPasses:device:]_block_invoke_3
- ___49-[NPKPassSyncService initWithPassSyncEngineRole:]_block_invoke
- ___block_descriptor_58_e8_32s40s48s_e20_v24?0"PKPass"8^B16ls32l8s40l8s48l8
- ___block_descriptor_66_e8_32s40s48s56s_e25_v32?0"NSNumber"8Q16^B24ls32l8s40l8s48l8s56l8
- ___block_descriptor_72_e8_32s40s48s56s64bs_e47_v24?0"NPKIDVRemoteDeviceSession"8"NSError"16ls32l8s40l8s48l8s56l8s64l8
CStrings:
+ "Error: %s failed to obtain a session for the target device with identifier %@, error:%@"
+ "Error: Dropping archived sync state item with incomplete fields (%@)"
+ "Error: Not adding or updating sync state item with incomplete fields (%@)"
+ "Error: Skipping pass with incomplete sync fields (%@)"
+ "Error: Skipping proto conversion for sync state item with nil required field (%@)"
+ "NPKPassNeedsSignatureValidationForStandaloneSync"
+ "NPKShouldUseStandaloneSyncForPassWithDeviceAndSignatureValidity"
+ "Notice: No store path for pass with unique ID %@ (no active paired device); skipping data accessor setup."
+ "Notice: No store path for pass: %@ (no active paired device); skipping data accessor update."
+ "Notice: Not opening pass database: no home directory (no current paired device)"
+ "Notice: Updated home directory: %{private}@ for pairing ID: %{private}@"
+ "passTypeIdentifier: %@, serialNumber: %@, manifestHash: %@"
- "IdentityStreamlinedPresentment"
- "NPKShouldUseStandaloneSyncForPassWithDevice"
- "Notice: Updated Home directory:%@ for deviceParingID:%@"
- "RasterizedPasses"
```
