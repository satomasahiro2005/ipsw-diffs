## CloudKit

> `/System/Library/Frameworks/CloudKit.framework/CloudKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x365c84` | `0x366fa0` | **`+0x131c`** |
| `__AUTH_CONST.__const` | `0x12d18` | `0x12520` | **`-0x7f8`** |
| `__TEXT.__eh_frame` | `0x10114` | `0x10654` | **`+0x540`** |
| `__TEXT.__cstring` | `0x207c5` | `0x20b69` | **`+0x3a4`** |
| `__AUTH.__objc_data` | `0x6448` | `0x6790` | **`+0x348`** |
| `__DATA_DIRTY.__objc_data` | `0x4a58` | `0x4710` | **`-0x348`** |
| `__TEXT.__swift5_capture` | `0x40bc` | `0x3d80` | **`-0x33c`** |
| `__DATA.__bss` | `0xe648` | `0xe948` | **`+0x300`** |
| `__TEXT.__const` | `0xe1f0` | `0xe490` | **`+0x2a0`** |
| `__TEXT.__unwind_info` | `0x10fb0` | `0x11110` | **`+0x160`** |
| `__AUTH_CONST.__cfstring` | `0x1dd60` | `0x1de80` | **`+0x120`** |
| `__TEXT.__swift_as_entry` | `0x690` | `0x764` | **`+0xd4`** |
| `__TEXT.__swift_as_ret` | `0x7b0` | `0x884` | **`+0xd4`** |
| `__TEXT.__swift5_typeref` | `0x6c32` | `0x6bce` | **`-0x64`** |
| `__TEXT.__swift_as_cont` | `0xed0` | `0xe74` | **`-0x5c`** |
| `__DATA_CONST.__const` | `0x6f08` | `0x6f58` | **`+0x50`** |
| `__DATA.__data` | `0x63b0` | `0x6380` | **`-0x30`** |
| `__DATA_DIRTY.__data` | `0x500` | `0x4d0` | **`-0x30`** |
| `__TEXT.__swift5_assocty` | `0x598` | `0x5c8` | **`+0x30`** |
| `__AUTH.__data` | `0x18e0` | `0x1900` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x2904` | `0x2924` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x251c` | `0x2538` | **`+0x1c`** |
| `__TEXT.__oslogstring` | `0x16f36` | `0x16f51` | **`+0x1b`** |
| `__DATA_CONST.__got` | `0x1988` | `0x19a0` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x840` | `0x858` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x1b8` | `0x1cc` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0xbf58` | `0xbf68` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x21854` | `0x21864` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2540` | `0x2548` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xaba8` | `0xabb0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x350` | `0x354` | **`+0x4`** |

### Other Changes

```diff

-2710.112.0.0.0
+2710.114.0.0.0

-  Functions: 24304
+  Functions: 24303

-  CStrings:  6190
+  CStrings:  6219
Symbols:
+ _CKStringForQueuePriority
+ _swift_task_localValuePop
+ _swift_task_localValuePush
- _$ss9TaskLocalC9withValue_9operation9isolation4file4lineqd__x_qd__yYaKXEScA_pSgYiSSSutYaKlF
- _$ss9TaskLocalC9withValue_9operation9isolation4file4lineqd__x_qd__yYaKXEScA_pSgYiSSSutYaKlFTu
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "%@ (%@)"
+ "%@ called on an already finished coalescer."
+ "%s scheduling another sync after this scheduled sync due to hasPendingUntrackedChanges"
+ "A valid value was not found"
+ "Error waiting for complete: %@"
+ "Error while clearing asset cache, check your syslog %@"
+ "Expected 2 arguments for function distanceToLocation:fromLocation: %@"
+ "Found nil account instance, which indicates the adopter probably has neither com.apple.accounts.appleaccount.fullaccess entitlement nor com.apple.private.accounts.allaccounts entitlement"
+ "High"
+ "Low"
+ "Normal"
+ "Operation %{public}@ will use QoS %{public}@, queuePriority %{public}@"
+ "Participant vetting initiated"
+ "Participant vetting initiated with error: %@"
+ "Returning a nil result from a non-compact map function"
+ "SyncEngine Asset Sync Task"
+ "SyncEngine Asset Sync Task Cancellation Handler"
+ "SyncEngine Configuring Notification Listener"
+ "SyncEngine Delayed Init"
+ "SyncEngine Notification Handler: "
+ "SyncEngine Notification Handler: .CKIdentityUpdate"
+ "SyncEngine Perform Cancellable Sync Task"
+ "SyncEngine Schedule Sync Coalescer"
+ "SyncEngine Start"
+ "SyncEngine State Changed Handler"
+ "SyncEngine State Update Coalescer"
+ "SyncEngine Update Account Info"
+ "SyncEngine cancelOperations wrapper"
+ "SyncEngine fetchChanges wrapper"
+ "SyncEngine fetchChanges(options:) wrapper"
+ "SyncEngine modifyPendingChanges wrapper"
+ "SyncEngine modifyPendingChanges(zoneIDsArray:) wrapper"
+ "SyncEngine sendChanges wrapper"
+ "SyncEngine sendChanges(options:) wrapper"
+ "SyncEngine systemSharingUIDidSaveShare Handler"
+ "Testing mishap, CKPersona's personaManager was an unknown type during adoption"
+ "Unknown error unarchiving CKPackage"
+ "VeryHigh"
+ "VeryLow"
+ "Warn: That size was ridiculous: %lu. Refusing to create a string that long."
+ "You cannot get a one-time URL for a participant until it's been saved to the server"
+ "default"
+ "explicit"
+ "preferredEncryptionType must be CKMMCSEncryptionTypeV1 or CKMMCSEncryptionTypeV2"
+ "queuePriority"
- "%@ called on an already finished coalescer. Ignored."
- "%s scheduling another sync after this scheduled sync due to pending work"
- "A value valid was not found"
- "Error waiting for complete"
- "Error while clearing record cache, check your syslog %@"
- "Expected expected 2 arguments for function distanceToLocation:fromLocation: %@"
- "Found nil account instance, which indicates the adopter probably has neither com.apple.accounts.appleaccount.fullaccess entitlement or com.apple.private.accounts.allaccounts entitlement"
- "Operation %{public}@ will use QoS %{public}@"
- "Participant vetting initialiated"
- "Participant vetting initialiated with error: %@"
- "Returning a non-nil result from a non-compact map function"
- "Subscriptions must not have a nil or valid record type"
- "Testing mishap, CKPerson's personaManager was an unknown type during adoption"
- "Warn: That size was ridiculous: %lu. Refusing to create a string that log."
- "You cannot get a one-time URL for a participant until the share it's been saved to the server"
- "preferredExceptionType must be CKMMCSEncryptionTypeV1 or CKMMCSEncryptionTypeV2"
```
