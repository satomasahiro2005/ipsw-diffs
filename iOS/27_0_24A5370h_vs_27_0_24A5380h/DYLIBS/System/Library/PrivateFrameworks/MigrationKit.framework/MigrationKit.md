## MigrationKit

> `/System/Library/PrivateFrameworks/MigrationKit.framework/MigrationKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x19501` | `0x19af1` | **`+0x5f0`** |
| `__TEXT.__text` | `0x70f2b4` | `0x70ee50` | **`-0x464`** |
| `__AUTH_CONST.__const` | `0x1aa68` | `0x1ae70` | **`+0x408`** |
| `__DATA.__bss` | `0x3e9d0` | `0x3ece0` | **`+0x310`** |
| `__TEXT.__oslogstring` | `0xfd6c` | `0x1007c` | **`+0x310`** |
| `__TEXT.__unwind_info` | `0x186f0` | `0x183e0` | **`-0x310`** |
| `__AUTH_CONST.__objc_const` | `0x1bde8` | `0x1c0d8` | **`+0x2f0`** |
| `__TEXT.__eh_frame` | `0x451ec` | `0x45494` | **`+0x2a8`** |
| `__TEXT.__const` | `0x39650` | `0x39850` | **`+0x200`** |
| `__TEXT.__gcc_except_tab` | `0x14d0` | `0x169c` | **`+0x1cc`** |
| `__AUTH.__data` | `0x16db0` | `0x16f38` | **`+0x188`** |
| `__TEXT.__swift5_typeref` | `0xbf13` | `0xc091` | **`+0x17e`** |
| `__TEXT.__swift5_reflstr` | `0xcbc2` | `0xcd12` | **`+0x150`** |
| `__DATA.__data` | `0xdf08` | `0xe048` | **`+0x140`** |
| `__TEXT.__swift5_fieldmd` | `0xdd20` | `0xde18` | **`+0xf8`** |
| `__TEXT.__swift5_capture` | `0x39ac` | `0x3aa0` | **`+0xf4`** |
| `__TEXT.__constg_swiftt` | `0xee40` | `0xef04` | **`+0xc4`** |
| `__DATA_CONST.__got` | `0x2320` | `0x2390` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x3490` | `0x34d8` | **`+0x48`** |
| `__TEXT.__swift_as_cont` | `0x3c68` | `0x3cb0` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x4cf0` | `0x4d30` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x6f70` | `0x6fb0` | **`+0x40`** |
| `__DATA.__common` | `0x1b48` | `0x1b80` | **`+0x38`** |
| `__DATA_CONST.__const` | `0xb40` | `0xb68` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0xc40` | `0xc58` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x23d0` | `0x23e8` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x1a8c` | `0x1aa4` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x7d8` | `0x7ec` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0xcec` | `0xcfc` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x15c` | `0x160` | **`+0x4`** |

### Other Changes

```diff

-1413.0.0.0.0
+1421.0.0.0.0

+  - /System/Library/PrivateFrameworks/CacheDelete.framework/CacheDelete

-  Functions: 24772
-  Symbols:   10161
-  CStrings:  4271
+  Functions: 24848
+  Symbols:   10213
+  CStrings:  4321
Symbols:
+ -[MKHPMInterface forceDeviceModeWithError:]
+ -[MKMessageMigrator _importViaIMCoreSPI:]
+ -[MKMessageMigrator _importViaSMSDatabase:]
+ -[MKUSBDevice deregisterExistingMigrationInterface]
+ -[MKUSBDevice isCancelled]
+ -[MKUSBDevice usbRoleChanged:]
+ -[MKUSBMonitor startMonitoringWithError:]
+ -[MKUSBMonitor stopMonitoring]
+ _CacheDeletePurgeSpaceWithInfo
+ _MobileGestalt_get_greenTeaDeviceCapability
+ _NSURLVolumeAvailableCapacityKey
+ _OBJC_CLASS_$_MTSound
+ _OBJC_IVAR_$_MKMessageMigrator._useSPIPath
+ _OBJC_IVAR_$_MKUSBDevice._cancelled
+ _OBJC_IVAR_$_MKUSBDevice._hpmInterface
+ _OBJC_IVAR_$_MKUSBDevice._monitor
+ _OBJC_IVAR_$_MKUSBDevice._roleSemaphore
+ __DATA__TtC12MigrationKit14DatabaseHandle
+ __DATA__TtC12MigrationKit16DatabaseRegistry
+ __DATA__TtC12MigrationKit17SkippedMessageIDs
+ __IVARS__TtC12MigrationKit14DatabaseHandle
+ __IVARS__TtC12MigrationKit16DatabaseRegistry
+ __IVARS__TtC12MigrationKit17SkippedMessageIDs
+ __METACLASS_DATA__TtC12MigrationKit14DatabaseHandle
+ __METACLASS_DATA__TtC12MigrationKit16DatabaseRegistry
+ __METACLASS_DATA__TtC12MigrationKit17SkippedMessageIDs
+ __OBJC_CLASS_PROTOCOLS_$_MKUSBDevice
+ ___27-[MKMessageMigrator import]_block_invoke
+ ___30-[MKUSBMonitor stopMonitoring]_block_invoke
+ ___41-[MKUSBMonitor startMonitoringWithError:]_block_invoke
+ ___43-[MKHPMInterface forceDeviceModeWithError:]_block_invoke
+ ___43-[MKMessageMigrator _importViaSMSDatabase:]_block_invoke
+ ___block_descriptor_56_e8_32s40r48r_e5_v8?0lr40l8s32l8r48l8
+ ___swift_closure_destructor.26Tm
+ ___swift_get_extra_inhabitant_index.46Tm
+ ___swift_store_extra_inhabitant_index.47Tm
+ _get_enum_tag_for_layout_string 12MigrationKit14DatabaseHandleC5State022_5F5479FF8FD2B9769B8C9J9E51353C2ALLO
+ _symbolic $s12MigrationKit19PersistenceDatabaseP
+ _symbolic SS8existing_SS9requestedt
+ _symbolic SS_____Sg______pIeghgrzo_ s6UInt64V s5ErrorP
+ _symbolic ScCy__________G s6UInt64V s5NeverO
+ _symbolic ScTy___________pG 12MigrationKit21PlayIntegrityResponseV s5ErrorP
+ _symbolic Si___________pIeghHyrzo_ 12MigrationKit21PlayIntegrityResponseV s5ErrorP
+ _symbolic So12NSURLSessionC
+ _symbolic _____ 10Foundation10URLRequestV
+ _symbolic _____ 12MigrationKit14DatabaseHandleC
+ _symbolic _____ 12MigrationKit14DatabaseHandleC5State022_5F5479FF8FD2B9769B8C9J9E51353C2ALLO
+ _symbolic _____ 12MigrationKit16DatabaseRegistryC
+ _symbolic _____ 12MigrationKit17SkippedMessageIDsC
+ _symbolic ______pSg5actor_t 12MigrationKit19PersistenceDatabaseP
+ _symbolic ______pXp 12MigrationKit19PersistenceDatabaseP
+ _symbolic _____m 12MigrationKit13FileContentDBC
+ _symbolic _____m 12MigrationKit22HomeScreenPersistence2C
+ _symbolic _____m 12MigrationKit28AccountPersistenceModelActorC
+ _symbolic _____m 12MigrationKit32PlaceholderPersistenceModelActorC
+ _symbolic _____m 12MigrationKit32WiFiNetworkPersistenceModelActorC
+ _symbolic _____m 12MigrationKit38PhotoLibraryPersistenceAssetModelActorC
+ _symbolic _____ySDySSAAy_____SgGGG 2os21OSAllocatedUnfairLockV 12MigrationKit14DatabaseHandleC
+ _symbolic _____ySDySS_____y_____SgGG_____G s13ManagedBufferCsRi__rlE 2os21OSAllocatedUnfairLockV 12MigrationKit14DatabaseHandleC So0C14_unfair_lock_sV
+ _symbolic _____ySS_____y_____SgGG s18_DictionaryStorageC 2os21OSAllocatedUnfairLockV 12MigrationKit14DatabaseHandleC
+ _symbolic _____yShySSGG 2os21OSAllocatedUnfairLockV
+ _symbolic _____yShySSG_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic _____y_____G 12MigrationKit15InternalDefaultV s6UInt64V
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 12MigrationKit14DatabaseHandleC5State022_5F5479FF8FD2B9769B8C9N9E51353C2ALLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 9SwiftData18ModelConfigurationV
+ _symbolic _____y_____Sg_____G s13ManagedBufferCsRi__rlE 12MigrationKit14DatabaseHandleC So16os_unfair_lock_sV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 12MigrationKit14DatabaseHandleC5State022_5F5479FF8FD2B9769B8C9L9E51353C2ALLO So16os_unfair_lock_sV
+ _type_layout_string 12MigrationKit14DatabaseHandleC5State022_5F5479FF8FD2B9769B8C9J9E51353C2ALLO
- -[MKMessageMigrator _import2:]
- -[MKMessageMigrator _import:]
- ___29-[MKMessageMigrator _import:]_block_invoke
- ___swift_closure_destructor.27Tm
- ___swift_closure_destructor.28Tm
- ___swift_get_extra_inhabitant_index.56Tm
- ___swift_store_extra_inhabitant_index.57Tm
- _get_type_metadata 12MigrationKit7OrdinalV9GeneratorV noncopyable
- _get_type_metadata 15Synchronization6AtomicVySbG noncopyable
- _get_type_metadata 15Synchronization6AtomicVys6UInt64VG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic _____Sg 12MigrationKit32PlaceholderPersistenceModelActorC
- _symbolic _____Sg 9SwiftData14ModelContainerC
- _symbolic _____ySay_____G_____G s13ManagedBufferCsRi__rlE 12MigrationKit11PersistenceV So16os_unfair_lock_sV
- _symbolic _____y_____SgG 2os21OSAllocatedUnfairLockV 9SwiftData14ModelContainerC
- _symbolic _____y_____Sg_____G s13ManagedBufferCsRi__rlE 9SwiftData14ModelContainerC So16os_unfair_lock_sV
CStrings:
+ " bytes (pending="
+ ", stored accounts: "
+ "Acquired export-extension slot"
+ "Acquired import-extension slot"
+ "Andata error (HTTP "
+ "CACHE_DELETE_AMOUNT"
+ "CACHE_DELETE_URGENCY_LIMIT"
+ "CACHE_DELETE_VOLUME"
+ "Failed to decode JSON into AndataResponse: "
+ "Failed to erase database"
+ "Failed to save inserted PendingAppInstall"
+ "Force GreenTea mode"
+ "Free-space headroom (bytes) the cloud attachment downloader tries to maintain. When free space falls below the next pending attachment plus this reserve, CacheDelete is asked to purge the deficit."
+ "Import-extension slot wait cancelled"
+ "Maximum backoff delay between Andata Play Integrity request retries, in seconds"
+ "Maximum concurrent app data exporter appex instances"
+ "Maximum concurrent app data import fetches"
+ "Maximum concurrent app data importer appex instances"
+ "Maximum number of times an Andata Play Integrity request is attempted before giving up"
+ "MigrationKit/PersistenceDatabase.swift"
+ "No match found for app %{private}s"
+ "Non-Dictionary JSON server response: "
+ "Non-JSON server response: "
+ "OS migration import disabled; routing setup through Move to iOS only."
+ "Released import-extension slot"
+ "Source failed to provide creation_epoch_millis for "
+ "Source failed to provide modified_epoch_millis for "
+ "Waiting for export-extension slot"
+ "Waiting for import-extension slot"
+ "[%s] GoOffAndOnBus(empty) failed: 0x%x"
+ "[%s] SetDescription(empty) failed: 0x%x"
+ "[%s] USB monitor failed to start: %@"
+ "[%s] USB role detected: %ld"
+ "[%s] USB role swap failed: %@"
+ "[%s] USB role swap failed: HPMInterface is nil"
+ "[%s] attempting USB role swap to device"
+ "[%s] cleared stale migration interface from IORegistry"
+ "[%s] failed to create empty description"
+ "[%s] failed to undo USB role swap: %@"
+ "[%s] no stale migration interface in IORegistry; skipping off/on-bus cycle"
+ "[%s] waiting for USB cable..."
+ "_sendAndata(request:session:)"
+ "appDataMaxConcurrentExportAppex"
+ "appDataMaxConcurrentImportAppex"
+ "appDataMaxConcurrentMetadataFetches"
+ "attestationServiceMaxAttempts"
+ "attestationServiceMaxRetryDelaySeconds"
+ "cloudAttachmentCacheDeleteReserveBytes"
+ "existing requested "
+ "failed to re-open database for import."
+ "failed to run placeholder lazy migrator"
+ "os migration feature flag disabled %{public}ld"
+ "overrideGreenTea"
+ "purge check: pending="
+ "skipped accounts: "
+ "skipping attachment for excluded message. attachment_id=%s, message_id=%s"
+ "transformer failed to persist message"
+ "\xb1"
- "Failed to decode JSON into AndataResponse"
- "Failed to erase '"
- "MigrationKit/FileAttributesPersistenceModelActor.swift"
- "No match found for app"
- "Non-Dictionary JSON server response"
- "Non-JSON server response"
- "Select the apps whose data you want to transfer to the other device."
- "screenReaderSpeechRate"
```
