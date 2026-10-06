## appstored

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/Support/appstored`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x562928` | `0x56395c` | **`+0x1034`** |
| `__TEXT.__gcc_except_tab` | `0x909c` | `0x8e28` | **`-0x274`** |
| `__TEXT.__oslogstring` | `0x3c376` | `0x3c4c0` | **`+0x14a`** |
| `__TEXT.__eh_frame` | `0xe588` | `0xe6c8` | **`+0x140`** |
| `__DATA.__objc_const` | `0x35880` | `0x35748` | **`-0x138`** |
| `__DATA_CONST.__const` | `0x2a538` | `0x2a478` | **`-0xc0`** |
| `__TEXT.__objc_stubs` | `0x14920` | `0x149c0` | **`+0xa0`** |
| `__TEXT.__ustring` | `—` | `0x94` | **`+0x94`** |
| `__DATA.__data` | `0x8418` | `0x8478` | **`+0x60`** |
| `__TEXT.__cstring` | `0x20b87` | `0x20b2b` | **`-0x5c`** |
| `__DATA.__objc_data` | `0x10e08` | `0x10db8` | **`-0x50`** |
| `__TEXT.__swift5_capture` | `0x3008` | `0x3054` | **`+0x4c`** |
| `__DATA_CONST.__cfstring` | `0x1af20` | `0x1aee0` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0x1e24c` | `0x1e28c` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x4594` | `0x45d0` | **`+0x3c`** |
| `__TEXT.__const` | `0x26738` | `0x26768` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x6910` | `0x6938` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xbc80` | `0xbc60` | **`-0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x1b78` | `0x1b90` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xdf84` | `0xdf6c` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x23e8` | `0x23d4` | **`-0x14`** |
| `__TEXT.__objc_classname` | `0x53e3` | `0x53d2` | **`-0x11`** |
| `__DATA_CONST.__got` | `0x19e8` | `0x19f8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x4b40` | `0x4b50` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x2160` | `0x2170` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x90df` | `0x90ec` | **`+0xd`** |
| `__TEXT.__swift_as_cont` | `0xaac` | `0xab8` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x708` | `0x714` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x25b0` | `0x25b8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x16a8` | `0x16a0` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xd60` | `0xd58` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x5a4` | `0x5a8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`

### Other Changes

```diff

-13.0.33.0.0
+13.0.36.0.0

-  - /usr/lib/swift/libswiftAVFoundation.dylib

-  - /usr/lib/swift/libswiftMLCompute.dylib

-  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Functions: 14165
+  Functions: 14186

-  CStrings:  15107
+  CStrings:  15112
Symbols:
+ _$sSh10FoundationE36_unconditionallyBridgeFromObjectiveCyShyxGSo5NSSetCSgFZ
+ _$sShyxGSTsMc
+ _OBJC_CLASS_$_AMSPushRegisterTask
- __swift_FORCE_LOAD_$_swiftAVFoundation
- __swift_FORCE_LOAD_$_swiftMLCompute
- __swift_FORCE_LOAD_$_swiftNaturalLanguage
CStrings:
+ "00:42:09"
+ "ACTIVE_RESTORE_MESSAGE"
+ "ACTIVE_RESTORE_OK_BUTTON"
+ "ACTIVE_RESTORE_TITLE"
+ "Jun 16 2026"
+ "LBJfwOEzExRxzlAnSuI7eg"
+ "Rejected ODR source URL from manifest for asset pack [%{public}@]: %{public}@"
+ "URLByStandardizingPath"
+ "Unable to authenticate — no personal purchaser account associated with %@"
+ "[%@] Attempting to prioritize and display a dialog if needed"
+ "[%@] Bundle not in active set — preparing dialog"
+ "[%@] No personal purchaser account for app (bundleID: %{public}@, DSID: %lld), skipping authentication"
+ "[%@] Post-poll activeBundleIDs: [%{public}s]"
+ "[%@] Rejecting out-of-bundle ODR source URL: %{public}@"
+ "[%@] Resource not found within bundle (error: %{public}@)"
+ "[%@] Resource recomposed within bundle: %{public}@"
+ "[%@] Skipping active restore dialog — bundle is in active set"
+ "[%@] Source URL no longer within bundle at copy time; aborting."
+ "[%@] Updating app install and bootstrap if needed"
+ "[%@]: No valid source URL for download, failing request."
+ "[%{public}s] Activity already scheduled; updating request"
+ "[%{public}s] Activity not scheduled; submitting request"
+ "[%{public}s] Attempt to resubmit failed: %{public}@"
+ "[%{public}s] Completing task"
+ "[%{public}s] Error occurred attempting to reschedule task: %{public}@"
+ "[%{public}s] Error occurred attempting to update task request; will request upon task completion (error: %{public}@)"
+ "_TtCFC9appstored21OffloadingCoordinator13purgeAppsSyncFTGSaCSo12PurgeableApp_16desiredPurgeSizeVs5Int6411offloadOnlySb6logKeyCS_6LogKey6clientSS_CSo20ASDPurgeAppsResponseL_9ResultBox"
+ "activeRestoreDialogs"
+ "http"
+ "initWithAccount:token:environment:bag:"
+ "isEqualToArray:"
+ "pathComponents"
+ "performTask"
+ "prioritizeAndDisplayActiveRestoreDialogIfNeeded(bundleID:logKey:completion:)"
+ "prioritizeAndDisplayActiveRestoreDialogIfNeededWithBundleID:logKey:completion:"
+ "resumeScheduling:error:"
+ "v16@?0@\"NSSet\"8"
- "21:16:57"
- "ACTIVE_RESTORE_CONTINUE_BUTTON"
- "ACTIVE_RESTORE_DELETE_BUTTON"
- "ACTIVE_RESTORE_DELETE_MESSAGE"
- "ACTIVE_RESTORE_TITLE_"
- "Failed to create register request."
- "May 31 2026"
- "Push register request failed."
- "Push register request received no response."
- "PushRegisterTask"
- "[%@] Could not find URL for registering push token"
- "[%@] Deletion complete"
- "[%@] Deletion failed with error: %@"
- "[%@] Did not receive response from register push call"
- "[%@] Failed register push token call with error: %{public}@"
- "[%@] Failed register push token call with unknown error and status code: %{public}ld"
- "[%@] Failed to create push register request."
- "[%@] Handle active restoring dialog failed with error: %{public}@"
- "[%@] Prompting the user whether or not to delete restore"
- "[%@] Resource was located at URL: %{public}@"
- "[%@] Resource was not found with error: %{public}@"
- "[%@] Skipping push register since there is no account."
- "[%@] Successfully registered push token"
- "[%@] User chose to delete"
- "[%{public}s] Activity already scheduled, updating criteria"
- "[%{public}s] Activity not scheduled, submitting criteria"
- "_TtCFC9appstored21OffloadingCoordinator9purgeAppsFTGSaCSo12PurgeableApp_16desiredPurgeSizeVs5Int6411offloadOnlySb6logKeyCS_6LogKey6clientSS_CSo20ASDPurgeAppsResponseL_9ResultBox"
- "dataUsingEncoding:allowLossyConversion:"
- "device-name-data"
- "displayDeleteActiveRestoreDialogWithBundleID:logKey:completion:"
- "lockedRestores"
- "push-notifications/register-success"
```
