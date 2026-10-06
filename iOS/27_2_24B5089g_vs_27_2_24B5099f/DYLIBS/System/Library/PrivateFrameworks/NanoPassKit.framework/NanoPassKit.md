## NanoPassKit

> `/System/Library/PrivateFrameworks/NanoPassKit.framework/NanoPassKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1eb730` | `0x1eca98` | **`+0x1368`** |
| `__TEXT.__oslogstring` | `0x22b59` | `0x22f76` | **`+0x41d`** |
| `__TEXT.__cstring` | `0x12d24` | `0x12fb4` | **`+0x290`** |
| `__AUTH_CONST.__objc_const` | `0x37168` | `0x37290` | **`+0x128`** |
| `__TEXT.__objc_methlist` | `0x20098` | `0x20140` | **`+0xa8`** |
| `__DATA_CONST.__const` | `0x4020` | `0x40c0` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x8f78` | `0x8fd8` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x8ac0` | `0x8b10` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x74e8` | `0x7528` | **`+0x40`** |
| `__AUTH_CONST.__objc_intobj` | `0xa8` | `0x78` | **`-0x30`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x60` | `0x48` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0x3850` | `0x3864` | **`+0x14`** |
| `__DATA_CONST.__objc_arraydata` | `0x28` | `0x18` | **`-0x10`** |
| `__TEXT.__const` | `0x300` | `0x310` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x16d0` | `0x16dc` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0xf88` | `0xf90` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xf28` | `0xf30` | **`+0x8`** |

### Other Changes

```diff

-1354.0.0.0.0
+1355.1.0.0.0

-  Functions: 11948
-  Symbols:   18695
-  CStrings:  3763
+  Functions: 11964
+  Symbols:   18728
+  CStrings:  3781
Symbols:
+ +[NPKPassSyncState(SyncVersion) minRemoteDevicePassSyncStateVersionSupportForDevice:]
+ +[NPKPassSyncState(SyncVersion) setMinRemoteDevicePassSyncStateVersionSupport:forDevice:]
+ -[NPKCompanionAgentConnection _applyPropertiesToPass:forDevice:]
+ -[NPKPassLibrarySyncState initWithVersionStates:]
+ -[NPKPassLibrarySyncState uniqueIDsOfPassesSyncedByAlternateMethodWithVersion:]
+ -[NPKPassLibraryVersionState .cxx_destruct]
+ -[NPKPassLibraryVersionState alternateMethodUniqueIDs]
+ -[NPKPassLibraryVersionState initWithSyncState:alternateMethodUniqueIDs:]
+ -[NPKPassLibraryVersionState syncState]
+ -[NPKPassSyncEngine initWithRole:syncStateVersion:]
+ -[NPKPassSyncEngine removeOutOfScopeItemsWithUniqueIDs:]
+ -[NPKPassSyncEngine setSyncStateVersion:]
+ -[NPKPassSyncEngine syncStateVersion]
+ -[NPKPassSyncService _remoteDeviceSyncStateVersion]
+ -[NPKPassSyncService _shouldHandleMessageNamed:fromID:]
+ -[NPKPassSyncService associatedPassDataRequested:service:account:fromID:context:]
+ -[NPKPassSyncService catalogChanged:service:account:fromID:context:]
+ -[NPKPassSyncService passSettingsChanged:service:account:fromID:context:]
+ -[NPKPassSyncService passSyncEngine:didUpdateSyncStateVersion:]
+ -[NPKPassSyncService passSyncEngineEncounteredUnexpectedEvent:]
+ -[NPKPassSyncService proposedReconciledState:service:account:fromID:context:]
+ -[NPKPassSyncService reconciledStateAccepted:service:account:fromID:context:]
+ -[NPKPassSyncService reconciledStateUnrecognized:service:account:fromID:context:]
+ -[NPKPassSyncService syncStateChangeProcessed:service:account:fromID:context:]
+ -[NPKPassSyncService syncStateChanged:service:account:fromID:context:]
+ -[NPKPassSyncState passSyncStateByRemovingPassesWithUniqueIDs:]
+ GCC_except_table164
+ GCC_except_table169
+ GCC_except_table234
+ GCC_except_table236
+ _NPKIDSSenderIdentifierBelongsToDifferentDevice
+ _NPKPassIsSyncedByAlternateMethodWithStateVersion
+ _NPKShouldUseStandaloneSyncForPassWithPairedDevice
+ _OBJC_CLASS_$_NPKPassLibraryVersionState
+ _OBJC_IVAR_$_NPKPassLibrarySyncState._versionStates
+ _OBJC_IVAR_$_NPKPassLibraryVersionState._alternateMethodUniqueIDs
+ _OBJC_IVAR_$_NPKPassLibraryVersionState._syncState
+ _OBJC_IVAR_$_NPKPassSyncEngine._syncStateVersion
+ _OBJC_METACLASS_$_NPKPassLibraryVersionState
+ __OBJC_$_CLASS_PROP_LIST_NPKPassSyncState
+ __OBJC_$_INSTANCE_METHODS_NPKPassLibraryVersionState
+ __OBJC_$_INSTANCE_VARIABLES_NPKPassLibraryVersionState
+ __OBJC_$_PROP_LIST_NPKPassLibraryVersionState
+ __OBJC_CLASS_RO_$_NPKPassLibraryVersionState
+ __OBJC_METACLASS_RO_$_NPKPassLibraryVersionState
+ ___58-[NPKPassLibrarySyncState initWithStateVersionSyncStates:]_block_invoke
+ ___63-[NPKPassSyncService passSyncEngineEncounteredUnexpectedEvent:]_block_invoke
+ ___block_descriptor_40_e8_32s_e43_v32?0"NSNumber"8"NPKPassSyncState"16^B24ls32l8
+ ___block_descriptor_48_e8_32s40s_e39_v32?0"NSNumber"8"NSMutableSet"16^B24ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e23_v16?0"PKPaymentPass"8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e23_v24?0B8f12"NSError"16ls32l8s40l8s48l8s56l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e8_v12?0B8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_64_e8_32s40s48s56s_e8_v12?0B8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_66_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_74_e8_32s40s48s56s64s_e20_v24?0"PKPass"8^B16ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_98_e8_32s40s48s56s64s72s80r88r_e25_v32?0"NSNumber"8Q16^B24ls32l8r80l8s40l8r88l8s48l8s56l8s64l8s72l8
- +[NPKPassSyncState(SyncVersion) _currentActiveDevice]
- +[NPKPassSyncState(SyncVersion) _deviceDomainAccessor]
- +[NPKPassSyncState(SyncVersion) minRemoteDevicePassSyncStateVersionSupport]
- +[NPKPassSyncState(SyncVersion) setMinRemoteDevicePassSyncStateVersionSupport:]
- -[NPKCompanionAgentConnection _applyPropertiesToPass:]
- -[NPKPassSyncEngine initWithRole:]
- -[NPKPassSyncService associatedPassDataRequested:]
- -[NPKPassSyncService catalogChanged:]
- -[NPKPassSyncService passSettingsChanged:]
- -[NPKPassSyncService proposedReconciledState:]
- -[NPKPassSyncService reconciledStateAccepted:]
- -[NPKPassSyncService reconciledStateUnrecognized:]
- -[NPKPassSyncService syncStateChangeProcessed:]
- -[NPKPassSyncService syncStateChanged:]
- GCC_except_table163
- GCC_except_table84
- _NPKShouldUseStandaloneSyncForPass
- _OBJC_IVAR_$_NPKPassLibrarySyncState._syncStates
- ___block_descriptor_40_e8_32s_e39_v32?0"NSNumber"8"NSMutableSet"16^B24ls32l8
- ___block_descriptor_56_e8_32s40s48bs_e23_v16?0"PKPaymentPass"8ls32l8s40l8s48l8
- ___block_descriptor_56_e8_32s40s48s_e8_v12?0B8ls32l8s40l8s48l8
- ___block_descriptor_58_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
- ___block_descriptor_66_e8_32s40s48s56s_e20_v24?0"PKPass"8^B16ls32l8s40l8s48l8s56l8
- ___block_descriptor_90_e8_32s40s48s56s64s72r80r_e25_v32?0"NSNumber"8Q16^B24ls32l8r72l8s40l8r80l8s48l8s56l8s64l8
CStrings:
+ "-[NPKPassSyncService associatedPassDataRequested:service:account:fromID:context:]"
+ "-[NPKPassSyncService catalogChanged:service:account:fromID:context:]"
+ "-[NPKPassSyncService passSettingsChanged:service:account:fromID:context:]"
+ "-[NPKPassSyncService proposedReconciledState:service:account:fromID:context:]"
+ "-[NPKPassSyncService reconciledStateAccepted:service:account:fromID:context:]"
+ "-[NPKPassSyncService reconciledStateUnrecognized:service:account:fromID:context:]"
+ "-[NPKPassSyncService syncStateChangeProcessed:service:account:fromID:context:]"
+ "-[NPKPassSyncService syncStateChanged:service:account:fromID:context:]"
+ "Error: Pass sync service: could not unarchive pass sync engine from %lu bytes at %{private}@; starting from an empty sync state"
+ "Error: Pass sync service: dropping %s from %{private}@, which is a different paired device from the one this service syncs with"
+ "Error: Pass sync service: initialized without a paired device; falling back to the active device's sync engine archive"
+ "Error: Pass sync service: resolving remote device sync state version without a paired device; falling back to version 0!"
+ "Notice: Pass sync service: read pass sync engine archive of %lu bytes with reconciled state hash %@ covering %lu item(s)"
+ "Notice: Pass sync service: sync engine encountered an unexpected event; scheduling delayed sync"
+ "Warning: IDS sender %{private}@ resolves to paired device %@, which is not %@"
+ "Warning: Pass sync service: Unable to read pass sync engine archive. This is expected in the case of a fresh device install.\n\tPath: %{private}@\n\tError: %@"
+ "Warning: Sync state engine (%@): Not accepting reconciled state (hash %@); candidate hash %@ version %lu, library version %lu"
+ "Warning: Sync state engine (%@): removing out-of-scope items without syncing their removal\n\treconciled: %@\n\tbackup: %@\n\tcandidate: %@"
+ "Warning: Unable to resolve an IDS identifier for %@; not attributing IDS sender %{private}@ to another device"
+ "v32@?0@\"NSNumber\"8@\"NPKPassSyncState\"16^B24"
- "Warning: Pass sync service: Unable to read pass sync engine archive. This is expected in the case of a fresh device install.\n\tError: %@"
- "Warning: Sync state engine (%@): Did not recognize hash (%@) in reconciled state accepted message; reconciled state hash is %@"
```
