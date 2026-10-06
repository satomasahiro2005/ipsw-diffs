## nsurlsessiond

> `/usr/libexec/nsurlsessiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x82eb8` | `0x8427c` | **`+0x13c4`** |
| `__TEXT.__objc_methname` | `0xf03c` | `0xf534` | **`+0x4f8`** |
| `__DATA.__objc_const` | `0x8cf8` | `0x9000` | **`+0x308`** |
| `__TEXT.__gcc_except_tab` | `0xe5d4` | `0xe820` | **`+0x24c`** |
| `__TEXT.__cstring` | `0x3a89` | `0x3cc8` | **`+0x23f`** |
| `__TEXT.__objc_stubs` | `0xa940` | `0xab60` | **`+0x220`** |
| `__TEXT.__objc_methlist` | `0x61bc` | `0x6334` | **`+0x178`** |
| `__TEXT.__oslogstring` | `0xf76e` | `0xf8cf` | **`+0x161`** |
| `__DATA.__objc_selrefs` | `0x3718` | `0x37d0` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0x2df0` | `0x2e80` | **`+0x90`** |
| `__DATA.__data` | `0xe4c` | `0xeac` | **`+0x60`** |
| `__DATA.__objc_data` | `0x1630` | `0x1680` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x1dc0` | `0x1e00` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0xb94` | `0xbd1` | **`+0x3d`** |
| `__TEXT.__objc_methtype` | `0x2f57` | `0x2f81` | **`+0x2a`** |
| `__DATA_CONST.__const` | `0x15c0` | `0x15e8` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x6d0` | `0x6f0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x7a0` | `0x7b0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x238` | `0x240` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x130` | `0x138` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-3896.100.1.2.1
+3896.200.31.0.0

-  Functions: 2074
-  Symbols:   516
-  CStrings:  3843
+  Functions: 2102
+  Symbols:   518
+  CStrings:  3899
Symbols:
+ _NSCocoaErrorDomain
+ _OBJC_CLASS_$_AVAssetDownloadLiveActivity
CStrings:
+ "\t"
+ "%{public}@ eligible for a Live Activity"
+ "%{public}@ no Live Activity: %{public}s"
+ "@\"NDAVBackgroundSession\""
+ "AVAssetDownloadFailOnRetryableError"
+ "AVAssetDownloadLiveActivityDownload"
+ "AVAssetDownloadTaskLiveActivityEnabledKey"
+ "CREATE INDEX IF NOT EXISTS idx_session_tasks_session_bundle ON session_tasks(session_id, bundle_id);"
+ "Cancelling task %lu because the user dismissed its Live Activity"
+ "Failed to bind session limit params to the insert statement"
+ "Failed to create session_tasks index"
+ "Failed to migrate to version 4"
+ "NDAVLiveActivityDownload"
+ "REPLACE INTO sessions (bundle_id, session_id, configuration, options) \tSELECT ?, ?, ?, (SELECT options FROM sessions WHERE bundle_id = ? AND session_id = ?) \tWHERE EXISTS (SELECT 1 FROM sessions WHERE bundle_id = ? AND session_id = ?) \t\tOR (SELECT COUNT(*) FROM sessions WHERE bundle_id = ?) < ?"
+ "REPLACE INTO sessions (bundle_id, session_id, options, configuration) \tSELECT ?, ?, ?, (SELECT configuration FROM sessions WHERE bundle_id = ? AND session_id = ?) \tWHERE EXISTS (SELECT 1 FROM sessions WHERE bundle_id = ? AND session_id = ?) \t\tOR (SELECT COUNT(*) FROM sessions WHERE bundle_id = ?) < ?"
+ "Refused to persist session %@ for bundle %{public}@: session limit (%d) reached"
+ "T@\"NDAVBackgroundSession\",W,N,V_session"
+ "T@\"NSString\",C,N,V_liveActivityAssetTitle"
+ "T@\"NSString\",C,N,V_liveActivityClientBundleIdentifier"
+ "T@\"NSString\",C,N,V_liveActivityDownloadIdentifier"
+ "T@\"NSString\",R,C,N"
+ "Tq,N,V_liveActivityBytesExpectedToWrite"
+ "Tq,N,V_liveActivityBytesWritten"
+ "Tq,R,N"
+ "_identifiersToLiveActivityDownloads"
+ "_liveActivityAssetTitle"
+ "_liveActivityBytesExpectedToWrite"
+ "_liveActivityBytesWritten"
+ "_liveActivityClientBundleIdentifier"
+ "_liveActivityDownloadIdentifier"
+ "discretionary at first resume"
+ "downloadDidEnterRetry:"
+ "isLiveActivityEligibleTaskInfo:"
+ "isLiveActivityEnabled"
+ "liveActivityAssetTitle"
+ "liveActivityBytesExpectedToWrite"
+ "liveActivityBytesWritten"
+ "liveActivityClientBundleIdentifier"
+ "liveActivityDownloadForTaskIdentifier:"
+ "liveActivityDownloadIdentifier"
+ "liveActivityRequestsCancellation"
+ "liveActivityRequestsCancellationOfTaskWithIdentifier:"
+ "liveActivityTerminalStatusForClientError:"
+ "notifyProgress:"
+ "opted out by download configuration"
+ "opted out by legacy option"
+ "registerDownload:"
+ "setLiveActivityAssetTitle:"
+ "setLiveActivityBytesExpectedToWrite:"
+ "setLiveActivityBytesWritten:"
+ "setLiveActivityClientBundleIdentifier:"
+ "setLiveActivityDownloadIdentifier:"
+ "startedUserInitiated not set"
+ "unregisterDownload:terminalStatus:error:"
+ "unregisterLiveActivityForTaskWithIdentifier:terminalStatus:error:"
+ "updateLiveActivityForResumedTaskWithIdentifier:"
+ "updateLiveActivityForRetryingTaskWithIdentifier:"
+ "updateWorkState"
+ "v40@0:8Q16q24@32"
- "REPLACE INTO sessions (bundle_id, session_id, configuration, options)  values (?, ?, ?, (SELECT options FROM sessions WHERE bundle_id = ? AND session_id = ?))"
- "REPLACE INTO sessions (bundle_id, session_id, options, configuration) \tvalues (?, ?, ?, (SELECT configuration FROM sessions WHERE bundle_id = ? AND session_id = ?))"
- "setWorkState"
```
