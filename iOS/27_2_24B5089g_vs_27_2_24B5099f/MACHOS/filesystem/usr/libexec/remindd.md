## remindd

> `/usr/libexec/remindd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x823e24` | `0x825cf0` | **`+0x1ecc`** |
| `__TEXT.__oslogstring` | `0x621f0` | `0x62830` | **`+0x640`** |
| `__TEXT.__objc_stubs` | `0x1bc80` | `0x1bf40` | **`+0x2c0`** |
| `__TEXT.__objc_methname` | `0x28611` | `0x28891` | **`+0x280`** |
| `__TEXT.__swift5_typeref` | `0x145d0` | `0x1446a` | **`-0x166`** |
| `__DATA.__objc_selrefs` | `0x7d00` | `0x7db8` | **`+0xb8`** |
| `__TEXT.__cstring` | `0x18d97` | `0x18e47` | **`+0xb0`** |
| `__TEXT.__objc_methtype` | `0x43f7` | `0x4347` | **`-0xb0`** |
| `__DATA_CONST.__const` | `0x266c0` | `0x26760` | **`+0xa0`** |
| `__DATA.__data` | `0x1f5d0` | `0x1f560` | **`-0x70`** |
| `__TEXT.__objc_methlist` | `0xac28` | `0xac90` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x10580` | `0x105e8` | **`+0x68`** |
| `__DATA_CONST.__cfstring` | `0x5220` | `0x5280` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x1fd80` | `0x1fdd0` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x20f0` | `0x213c` | **`+0x4c`** |
| `__TEXT.__auth_stubs` | `0x8ce0` | `0x8d10` | **`+0x30`** |
| `__TEXT.__const` | `0x295b8` | `0x29588` | **`-0x30`** |
| `__DATA_CONST.__auth_got` | `0x4680` | `0x4698` | **`+0x18`** |
| `__DATA.__bss` | `0x23830` | `0x23840` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x35a0` | `0x35b0` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x6406` | `0x63f6` | **`-0x10`** |
| `__DATA.__objc_const` | `0x1dfc8` | `0x1dfd0` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x6458` | `0x6460` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4077.0.0.0.0
+4079.0.0.0.0

+  - /System/Library/PrivateFrameworks/BackgroundSystemTasks.framework/BackgroundSystemTasks

-  Functions: 22842
-  Symbols:   4300
-  CStrings:  11855
+  Functions: 22874
+  Symbols:   4305
+  CStrings:  11910
Symbols:
+ _$s10Foundation4DateV2geoiySbAC_ACtFZ
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _OBJC_CLASS_$_BGNonRepeatingSystemTaskRequest
+ _OBJC_CLASS_$_BGSystemTaskScheduler
+ _dispatch_queue_attr_make_with_qos_class
CStrings:
+ "ICCC post-setup: BST already pending, skipping"
+ "ICCC post-setup: BST already registered, skipping"
+ "ICCC post-setup: BST complete {syncSucceeded: %d, attempt: %ld}"
+ "ICCC post-setup: BST expiration handler fired"
+ "ICCC post-setup: BST expired, requesting DAS retry {attempt: %ld}"
+ "ICCC post-setup: BST fired (attempt %ld)"
+ "ICCC post-setup: BST not registered, skipping submit"
+ "ICCC post-setup: BST submit failed: %{public}@"
+ "ICCC post-setup: BST submitted (retry %ld/%ld)"
+ "ICCC post-setup: feature flag disabled, skipping BST submit"
+ "ICCC post-setup: not ready, requesting DAS retry %ld/%ld"
+ "ICCC post-setup: safety timeout — completion did not fire, expiring task"
+ "ICCC post-setup: setTaskExpiredWithRetryAfter failed: %{public}@"
+ "ICPostSetupSyncRetryCount"
+ "backgroundSystemTaskPostBuddySync"
+ "ckDeleteZone recovery: cloudContext is nil, skipping forced sync"
+ "ckDeleteZone recovery: forced sync completed successfully"
+ "ckDeleteZone recovery: forced sync failed: %{public}@"
+ "ckDeleteZone recovery: triggering forced sync <rdar://186377395>"
+ "com.apple.remindd.post-setup-sync"
+ "handlePostSetupSyncTask:"
+ "integerForKey:"
+ "post-buddy sync: account update complete {didUpdateAccounts: %{bool}d}"
+ "post-buddy sync: accountUtils is nil, cannot trigger migration"
+ "post-buddy sync: cloudContext is nil, skipping forced sync"
+ "post-buddy sync: failed: %{public}@"
+ "post-buddy sync: forced sync completed successfully"
+ "post-buddy sync: forced sync failed: %{public}@"
+ "post-buddy sync: triggering forced sync"
+ "post-buddy sync: triggering updateAccountsAndFetchMigrationState <rdar://185902817>"
+ "postSetupSyncActionForDidUpdateAccounts:expired:retryCount:maxRetries:"
+ "postSetupSyncRetryCount"
+ "q40@0:8B16B20q24q32"
+ "registerForTaskWithIdentifier:usingQueue:launchHandler:"
+ "registerPostSetupSyncTask"
+ "setExpirationHandler:"
+ "setInteger:forKey:"
+ "setPostSetupSyncRetryCount:"
+ "setRequiresBuddyComplete:"
+ "setRequiresNetworkConnectivity:"
+ "setRequiresProtectionClass:"
+ "setScheduleAfter:"
+ "setTaskCompleted"
+ "setTaskExpiredWithRetryAfter:error:"
+ "setTrySchedulingBefore:"
+ "sharedScheduler"
+ "submitPostBuddySyncTask:"
+ "submitPostBuddySyncTask: cloudContext is nil"
+ "submitPostBuddySyncTask: submitPostSetupSyncTaskIfNeeded dispatched"
+ "submitPostSetupSyncTaskIfNeeded"
+ "submitTaskRequest:error:"
+ "taskRequestForIdentifier:"
+ "triggerPostBuddySyncForAccountMigrationWithCompletion:"
+ "unitTest_postSetupSyncActionForDidUpdateAccounts:expired:retryCount:maxRetries:"
+ "v16@?0@\"BGNonRepeatingSystemTask\"8"
```
