## HeartHealthDaemon

> `/System/Library/PrivateFrameworks/HeartHealthDaemon.framework/HeartHealthDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x64e34` | `0x64174` | **`-0xcc0`** |
| `__AUTH_CONST.__objc_const` | `0x9b78` | `0x99a0` | **`-0x1d8`** |
| `__TEXT.__oslogstring` | `0xc29e` | `0xc175` | **`-0x129`** |
| `__TEXT.__objc_methlist` | `0x4fec` | `0x4ecc` | **`-0x120`** |
| `__DATA.__data` | `0x1e20` | `0x1d60` | **`-0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x35a8` | `0x3520` | **`-0x88`** |
| `__AUTH.__objc_data` | `0x8b8` | `0x868` | **`-0x50`** |
| `__TEXT.__cstring` | `0x5622` | `0x55d2` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x1988` | `0x1940` | **`-0x48`** |
| `__TEXT.__unwind_info` | `0x16b0` | `0x1678` | **`-0x38`** |
| `__AUTH_CONST.__objc_intobj` | `0xde0` | `0xdb0` | **`-0x30`** |
| `__AUTH_CONST.__cfstring` | `0x4620` | `0x4600` | **`-0x20`** |
| `__AUTH_CONST.__const` | `0x640` | `0x620` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xed0` | `0xeb8` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x63c` | `0x62c` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x280` | `0x270` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x308` | `0x300` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x48` | `0x40` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x290` | `0x288` | **`-0x8`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  Functions: 2081
-  Symbols:   4081
-  CStrings:  1327
+  Functions: 2062
+  Symbols:   4038
+  CStrings:  1320
Symbols:
+ -[HDHRBloodPressureJournalPeriodicScheduler _enqueueSchedulingOnMaintenanceOperationWithPeriodicActivity:completion:]
+ -[HDHRHypertensionNotificationsRescindedAlertManager _activeRemoteCountryRequirementIdentifier]
+ -[HDHRHypertensionNotificationsRescindedAlertManager _localCountryRequirementIdentifier]
+ GCC_except_table19
+ GCC_except_table26
+ GCC_except_table30
+ GCC_except_table34
+ _OBJC_CLASS_$_HDMetadataManager
+ ___117-[HDHRBloodPressureJournalPeriodicScheduler _enqueueSchedulingOnMaintenanceOperationWithPeriodicActivity:completion:]_block_invoke
+ ___117-[HDHRBloodPressureJournalPeriodicScheduler _enqueueSchedulingOnMaintenanceOperationWithPeriodicActivity:completion:]_block_invoke_2
- -[HDHRBloodPressureJournalPeriodicScheduler _enqueueSchedulingOnMaintenanceOperationWithCompletion:]
- -[HDHRIrregularRhythmNotificationsFeatureAvailabilityManager highestAvailableOnboardedAlgorithmVersionWithError:]
- -[HDHeartDaemonExtension daemonDidReceiveRapportEvent:completion:]
- -[HDRemoteHeartRateStreamClient .cxx_destruct]
- -[HDRemoteHeartRateStreamClient _connection]
- -[HDRemoteHeartRateStreamClient _lock_setupConnection]
- -[HDRemoteHeartRateStreamClient activateConnectionIfNecessary]
- -[HDRemoteHeartRateStreamClient connectionInterrupted]
- -[HDRemoteHeartRateStreamClient connectionInvalidated]
- -[HDRemoteHeartRateStreamClient dealloc]
- -[HDRemoteHeartRateStreamClient exportedInterface]
- -[HDRemoteHeartRateStreamClient initWithConnectionProvider:]
- -[HDRemoteHeartRateStreamClient initWithEndPoint:]
- -[HDRemoteHeartRateStreamClient init]
- -[HDRemoteHeartRateStreamClient invalidateConnection]
- -[HDRemoteHeartRateStreamClient isConnectionActive]
- -[HDRemoteHeartRateStreamClient prepareToProvideHeartRateWithCompletion:]
- -[HDRemoteHeartRateStreamClient remoteInterface]
- _HKFeatureAvailabilityRequirementIdentifierFeatureFlagIsEnabled
- _OBJC_CLASS_$_HDRemoteHeartRateStreamClient
- _OBJC_CLASS_$_NSNotificationCenter
- _OBJC_CLASS_$_NSXPCInterface
- _OBJC_CLASS_$__HKXPCConnection
- _OBJC_IVAR_$_HDRemoteHeartRateStreamClient._connectionProvider
- _OBJC_IVAR_$_HDRemoteHeartRateStreamClient._connectionToService
- _OBJC_IVAR_$_HDRemoteHeartRateStreamClient._lock
- _OBJC_IVAR_$_HDRemoteHeartRateStreamClient._running
- _OBJC_METACLASS_$_HDRemoteHeartRateStreamClient
- __OBJC_$_INSTANCE_METHODS_HDRemoteHeartRateStreamClient
- __OBJC_$_INSTANCE_VARIABLES_HDRemoteHeartRateStreamClient
- __OBJC_$_PROP_LIST_HDRemoteHeartRateStreamClient
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_HKRemoteHeartRateStreamServiceInterface
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT__HKXPCExportable
- __OBJC_$_PROTOCOL_INSTANCE_METHODS__HKXPCExportable
- __OBJC_$_PROTOCOL_METHOD_TYPES_HKRemoteHeartRateStreamServiceInterface
- __OBJC_$_PROTOCOL_METHOD_TYPES__HKXPCExportable
- __OBJC_$_PROTOCOL_REFS_HKRemoteHeartRateStreamServiceInterface
- __OBJC_$_PROTOCOL_REFS__HKXPCExportable
- __OBJC_CLASS_PROTOCOLS_$_HDRemoteHeartRateStreamClient
- __OBJC_CLASS_RO_$_HDRemoteHeartRateStreamClient
- __OBJC_LABEL_PROTOCOL_$_HKRemoteHeartRateStreamServiceInterface
- __OBJC_LABEL_PROTOCOL_$__HKXPCExportable
- __OBJC_METACLASS_RO_$_HDRemoteHeartRateStreamClient
- __OBJC_PROTOCOL_$_HKRemoteHeartRateStreamServiceInterface
- __OBJC_PROTOCOL_$__HKXPCExportable
- __OBJC_PROTOCOL_REFERENCE_$_HKRemoteHeartRateStreamServiceInterface
- ___100-[HDHRBloodPressureJournalPeriodicScheduler _enqueueSchedulingOnMaintenanceOperationWithCompletion:]_block_invoke
- ___100-[HDHRBloodPressureJournalPeriodicScheduler _enqueueSchedulingOnMaintenanceOperationWithCompletion:]_block_invoke_2
- ___37-[HDRemoteHeartRateStreamClient init]_block_invoke
- ___50-[HDRemoteHeartRateStreamClient initWithEndPoint:]_block_invoke
- ___73-[HDRemoteHeartRateStreamClient prepareToProvideHeartRateWithCompletion:]_block_invoke
- ___block_descriptor_32_e23_"_HKXPCConnection"8?0l
- ___block_descriptor_40_e8_32s_e23_"_HKXPCConnection"8?0ls32l8
CStrings:
- "@\"_HKXPCConnection\"8@?0"
- "[%{public}@] Connection Interrupted : %{public}@"
- "[%{public}@] Connection Invalidated : %{public}@"
- "[%{public}@] No need to activate. Connection already activated %@"
- "[%{public}@] Unable to determine current algorithm version, defaulting to 1.0: %{public}@"
- "[%{public}@] daemonDidReceiveRapportEvent."
- "com.apple.health.RemoteHeartRateStreamService"
```
