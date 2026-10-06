## servicesintelligenced

> `/System/Library/PrivateFrameworks/ServicesIntelligence.framework/servicesintelligenced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xea00` | `0x1275c` | **`+0x3d5c`** |
| `__TEXT.__oslogstring` | `0x8ac` | `0xd6c` | **`+0x4c0`** |
| `__TEXT.__eh_frame` | `0xb80` | `0xe38` | **`+0x2b8`** |
| `__TEXT.__objc_stubs` | `0x200` | `0x380` | **`+0x180`** |
| `__TEXT.__objc_methname` | `0x367` | `0x487` | **`+0x120`** |
| `__DATA_CONST.__const` | `0x628` | `0x740` | **`+0x118`** |
| `__TEXT.__cstring` | `0x5b8` | `0x688` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x400` | `0x498` | **`+0x98`** |
| `__TEXT.__auth_stubs` | `0xaf0` | `0xb80` | **`+0x90`** |
| `__DATA.__objc_selrefs` | `0x120` | `0x180` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x170` | `0x1c8` | **`+0x58`** |
| `__DATA_CONST.__auth_got` | `0x580` | `0x5c8` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x158` | `0x190` | **`+0x38`** |
| `__TEXT.__const` | `0x29a` | `0x2ca` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0xb8` | `0xe0` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x74` | `0x98` | **`+0x24`** |
| `__TEXT.__swift_as_entry` | `0x44` | `0x54` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1.60.0.0.0
+1.65.0.0.0

-  Functions: 230
-  Symbols:   258
-  CStrings:  135
+  Functions: 269
+  Symbols:   274
+  CStrings:  166
Symbols:
+ _$s10Foundation22_convertNSErrorToErrorys0E0_pSo0C0CSgF
+ _$s20ServicesIntelligence0aB8ProviderC17refreshDomainData6domain14requestContextyAA0E0O_AA07RequestI0VSgtYaKF
+ _$s20ServicesIntelligence0aB8ProviderC17refreshDomainData6domain14requestContextyAA0E0O_AA07RequestI0VSgtYaKFTu
+ _$s20ServicesIntelligence0aB8ProviderC26refreshTopicMappingsViaPIR14requestContextyAA07RequestJ0VSg_tYaF
+ _$s20ServicesIntelligence0aB8ProviderC26refreshTopicMappingsViaPIR14requestContextyAA07RequestJ0VSg_tYaFTu
+ _$s20ServicesIntelligence0aB8ProviderC27deferredClassBDatabaseCount14requestContextSiAA07RequestI0VSg_tYaF
+ _$s20ServicesIntelligence0aB8ProviderC27deferredClassBDatabaseCount14requestContextSiAA07RequestI0VSg_tYaFTu
+ _$s20ServicesIntelligence0aB8ProviderC30recoverDeferredClassBDatabases14requestContextSiAA07RequestI0VSg_tYaF
+ _$s20ServicesIntelligence0aB8ProviderC30recoverDeferredClassBDatabases14requestContextSiAA07RequestI0VSg_tYaFTu
+ _$s20ServicesIntelligence0aB8ProviderC32isSemanticProfileWorkloadAllowedSbyYaF
+ _$s20ServicesIntelligence0aB8ProviderC32isSemanticProfileWorkloadAllowedSbyYaFTu
+ _$s20ServicesIntelligence6DomainO4appsyA2CmFWC
+ _$s20ServicesIntelligence6DomainOMa
+ _OBJC_CLASS_$_BGRepeatingSystemTaskRequest
+ ___stack_chk_fail
+ ___stack_chk_guard
+ _objc_release_x28
+ _objc_retain_x20
+ _swift_release_x21
+ _swift_release_x28
+ _swift_retain_x19
+ _swift_retain_x25
- _$s20ServicesIntelligence0aB8ProviderC20refreshTopicMappings14requestContextyAA07RequestH0VSg_tYaKF
- _$s20ServicesIntelligence0aB8ProviderC20refreshTopicMappings14requestContextyAA07RequestH0VSg_tYaKFTu
- _$s20ServicesIntelligence10FitnessXPCC6ServerC3runyyFTj
- _$s20ServicesIntelligence10FitnessXPCC6ServerC6sharedAEvgZ
- _$s20ServicesIntelligence10FitnessXPCC6ServerCMa
- _swift_retain_x23
CStrings:
+ ".refreshDomainData"
+ ".refreshTopicMappingsViaPIR"
+ "[%s] Account not eligible (storefront / personalization / u18); skipping semantic profile workload"
+ "[Daemon][cancelClassBRecoveryTask] Cancelled Class B recovery task — nothing left to recover"
+ "[Daemon][cancelClassBRecoveryTask] Failed to cancel Class B recovery task: %@"
+ "[Daemon][class-b-db-recovery] All recovered — parked task"
+ "[Daemon][class-b-db-recovery] Background task fired"
+ "[Daemon][class-b-db-recovery] Failed to park task, completing instead: %@"
+ "[Daemon][class-b-db-recovery] Recovery attempt complete, %ld still deferred"
+ "[Daemon][class-b-db-recovery] Shadow task completed"
+ "[Daemon][class-b-db-recovery] Shadow task started"
+ "[Daemon][listenForLaunchEvents] Registering handler for Class B DB recovery task"
+ "[Daemon][reconcileClassBRecoveryTask] Class B recovery task already submitted; ensured scheduling (%ld deferred)"
+ "[Daemon][reconcileClassBRecoveryTask] Failed to submit Class B recovery task: %@"
+ "[Daemon][reconcileClassBRecoveryTask] Submitted Class B recovery task (%ld deferred)"
+ "[Daemon][refreshDomainData] complete"
+ "[Daemon][refreshDomainData] failed: %@"
+ "[Daemon][refreshDomainData] start"
+ "[Daemon][refreshTopicMappingsViaPIR] complete"
+ "[Daemon][refreshTopicMappingsViaPIR] start"
+ "cancelTaskRequestWithIdentifier:error:"
+ "com.apple.servicesintelligenced.class-b-db-recovery"
+ "com.apple.servicesintelligenced.launchevents.classBRecovery"
+ "executeSemanticProfileWorkload(label:)"
+ "initWithIdentifier:"
+ "resumeScheduling:error:"
+ "setInterval:"
+ "setMinDurationBetweenInstances:"
+ "setPriority:"
+ "setRequiresExternalPower:"
+ "setRequiresNetworkConnectivity:"
+ "setRequiresProtectionClass:"
+ "setTaskExpiredWithRetryAfter:error:"
+ "submitTaskRequest:error:"
+ "taskRequestForIdentifier:"
- ".refreshTopicMappings"
- "[Daemon][refreshTopicMappings] complete"
- "[Daemon][refreshTopicMappings] failed: %@"
- "[Daemon][refreshTopicMappings] start"
```
