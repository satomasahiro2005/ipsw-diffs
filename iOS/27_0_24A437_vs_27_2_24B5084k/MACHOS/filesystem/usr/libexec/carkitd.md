## carkitd

> `/usr/libexec/carkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x94f00` | `0x95abc` | **`+0xbbc`** |
| `__TEXT.__oslogstring` | `0x11581` | `0x11a11` | **`+0x490`** |
| `__TEXT.__objc_methname` | `0x18a84` | `0x18de4` | **`+0x360`** |
| `__TEXT.__objc_stubs` | `0x11620` | `0x118a0` | **`+0x280`** |
| `__DATA.__objc_const` | `0x147f8` | `0x14990` | **`+0x198`** |
| `__TEXT.__cstring` | `0x67d2` | `0x6912` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x7b9c` | `0x7cac` | **`+0x110`** |
| `__DATA.__objc_selrefs` | `0x50a8` | `0x5168` | **`+0xc0`** |
| `__DATA_CONST.__cfstring` | `0x8000` | `0x80a0` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x1960` | `0x19fc` | **`+0x9c`** |
| `__DATA_CONST.__const` | `0x3770` | `0x36f8` | **`-0x78`** |
| `__DATA.__objc_data` | `0x1d08` | `0x1d58` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x498e` | `0x49be` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x18d0` | `0x18f0` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x110b` | `0x112b` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x930` | `0x948` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x7cc` | `0x7e0` | **`+0x14`** |
| `__DATA_CONST.__auth_got` | `0xc78` | `0xc88` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x2a8` | `0x2b0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1e0` | `0x1e8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2208` | `0x2200` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-799.3.0.0.0
+807.2.0.0.0

-  Functions: 3427
-  Symbols:   746
-  CStrings:  6822
+  Functions: 3447
+  Symbols:   748
+  CStrings:  6881
Symbols:
+ _glob
+ _globfree
CStrings:
+ "@\"CRTapToRadarBannerController\""
+ "CRTapToRadarBannerController"
+ "CarPlay Tap-to-Radar banner: Cancel tapped"
+ "CarPlay Tap-to-Radar banner: Dictate tapped"
+ "CarPlay Tap-to-Radar banner: Done tapped"
+ "CarPlaySnoops"
+ "Collected %lu CarPlay snoop file(s) for diagnostics"
+ "Derived an empty connection UUID from endpoint UUID: %{public}@"
+ "Dictation Disabled By CAREnableDictationInternal"
+ "Dictation Error"
+ "Dictation Not Enabled In Keyboard Settings"
+ "Dictation banner idle timeout; dismissing without a draft."
+ "Dictation banner: Cancel (discard) — aborting diagnostics draft."
+ "Dictation banner: Dictate (start recording)."
+ "Dictation banner: Done (finish)."
+ "Dictation cancelled; aborting diagnostics draft."
+ "Dictation is not available; continuing without transcription"
+ "Dictation is not enabled in keyboard settings; continuing without transcription"
+ "Dictation recording reached max duration; stopping."
+ "Endpoint UUID is not composite, cannot derive connection UUID: %{public}@"
+ "Failed to copy diagnostic attachment %@: %@"
+ "Failed to create CarPlay snoops folder %@: %@"
+ "Failed to expand CarPlay snoop glob %@: %d"
+ "No CarPlay snoop collection path available for this session"
+ "Requesting CarPlay Tap-to-Radar action banner (hide)"
+ "Requesting CarPlay Tap-to-Radar action banner (show)"
+ "Requesting CarPlay Tap-to-Radar error banner"
+ "Requesting CarPlay draft-created banner"
+ "Requesting CarPlay fetching-vehicle-logs banner (hide)"
+ "Requesting CarPlay fetching-vehicle-logs banner (show)"
+ "T@\"CRTapToRadarBannerController\",&,N,V_tapToRadarBannerController"
+ "T@\"NSString\",C,N,V_pendingDictationIssue"
+ "T@?,C,N,V_cancelHandler"
+ "T@?,C,N,V_dictateHandler"
+ "T@?,C,N,V_dictationBannerCompletion"
+ "T@?,C,N,V_doneHandler"
+ "Vehicle %@ is not paired for wireless: no Bluetooth address on stored vehicle or on connected accessory %@"
+ "Vehicle log archive request completed (url: %@)"
+ "_armDictationTimerWithInterval:selector:"
+ "_beginDictation"
+ "_cancelHandler"
+ "_collectCarPlaySnoopsForSession:intoDiagnosticData:"
+ "_dictateHandler"
+ "_dictationBannerCompletion"
+ "_dictationIdleTimeoutReached"
+ "_dictationRecordingMaxDurationReached"
+ "_doneHandler"
+ "_finishDictationWithTranscription:cancelled:"
+ "_mainQueue_presentDictationBanner"
+ "_pendingDictationIssue"
+ "_tapToRadarBannerController"
+ "absent, defaulting to NO"
+ "cancelHandler"
+ "carPlaySnoopCollectionPath"
+ "com.apple.carkit.taptoradarbanner.action.cancel"
+ "com.apple.carkit.taptoradarbanner.action.dictate"
+ "com.apple.carkit.taptoradarbanner.action.done"
+ "com.apple.carkit.taptoradarbanner.draftcreated"
+ "com.apple.carkit.taptoradarbanner.error"
+ "com.apple.carkit.taptoradarbanner.fetching.hide"
+ "com.apple.carkit.taptoradarbanner.fetching.show"
+ "com.apple.carkit.taptoradarbanner.hide"
+ "com.apple.carkit.taptoradarbanner.show"
+ "componentsSeparatedByString:"
+ "copyAttachment:asFilename:intoDirectory:"
+ "descriptionForScreenType"
+ "dictateHandler"
+ "dictationBannerCompletion"
+ "doneHandler"
+ "fetchTapToRadarDraftBannerInfoWithReply:"
+ "fileSystemRepresentation"
+ "fileURLWithFileSystemRepresentation:isDirectory:relativeToURL:"
+ "hideBanner"
+ "hideFetchingLogsBanner"
+ "initWithSession:channelType:channelID:withoutReply:sendAsIs:qualityOfService:streamPriority:sendSocketBufferSize:"
+ "no attachment URL, filename, or directory"
+ "pendingDictationIssue"
+ "present but NO"
+ "setCancelHandler:"
+ "setDictateHandler:"
+ "setDictationBannerCompletion:"
+ "setDoneHandler:"
+ "setPendingDictationIssue:"
+ "setTapToRadarBannerController:"
+ "showBanner"
+ "showDraftCreatedBanner"
+ "showErrorBanner"
+ "showFetchingLogsBanner"
+ "starting wireless session with mutual auth disabled (%{public}@ %{public}@); HU may reject the session. startSessionProperties keys: %{public}@"
+ "tapToRadarBannerController"
+ "v20@?0@\"NSString\"8B16"
+ "v24@0:8@?<v@?q@\"NSString\"@\"NSError\">16"
+ "v32@0:8d16:24"
+ "\x91"
- "@\"CRDiagnosticsBulletin\""
- "@40@0:8@16d24@?32"
- "Diagnostics bulletin created with recordID %@"
- "Diagnostics bulletin not presented: CARUserAlerts unavailable"
- "Dictation Error. "
- "Dictation Not Enabled In Settings"
- "Dictation dismissed"
- "Dictation in Progress. Tap to Stop"
- "Dictation in-progress banner reached max duration; stopping dictation."
- "Dictation is not available"
- "Dictation is not enabled in keyboard settings"
- "Dictation will begin"
- "ERROR: Failed to create a draft!"
- "Fetching vehicle logs, please wait..."
- "Number of Drafts Scheduled: %ld"
- "Please make sure you have Dictation enabled."
- "Presenting diagnostics bulletin: %@, timeout: %f"
- "Primary"
- "Secondary"
- "T@\"CRDiagnosticsBulletin\",W,N,V_dictationInProgressBulletin"
- "Tap to Dictate Issue"
- "User stopped dictation."
- "Vehicle %@ is not paired for wireless"
- "Vehicle logs gathered"
- "_beginDictationWithCompletion:"
- "_dictationInProgressBulletin"
- "_dictationInProgressMaxDurationReached"
- "_mainQueue_displayDraftCountBanner"
- "_mainQueue_displayDraftErrorBanner"
- "_mainQueue_displayFetchingVehicleLogsBannerWithCompletion:"
- "_mainQueue_presentCarAlertWithTitle:dismissTime:completion:"
- "_mainQueue_presentDictationInProgressBanner"
- "dictationInProgressBulletin"
- "qA"
- "setDictationInProgressBulletin:"
```
