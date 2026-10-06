## Books

> `/private/var/staged_system_apps/Books.app/Books`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7d1f88` | `0x7dd020` | **`+0xb098`** |
| `__TEXT.__cstring` | `0x2c328` | `0x2c948` | **`+0x620`** |
| `__TEXT.__oslogstring` | `0x203d0` | `0x20840` | **`+0x470`** |
| `__TEXT.__eh_frame` | `0x16594` | `0x169d4` | **`+0x440`** |
| `__DATA.__objc_const` | `0x56bd0` | `0x56ee0` | **`+0x310`** |
| `__TEXT.__const` | `0x40110` | `0x40420` | **`+0x310`** |
| `__DATA.__data` | `0x2ddb0` | `0x2e0b0` | **`+0x300`** |
| `__TEXT.__unwind_info` | `0x19e10` | `0x1a088` | **`+0x278`** |
| `__DATA.__objc_data` | `0x1a780` | `0x1a9c0` | **`+0x240`** |
| `__TEXT.__auth_stubs` | `0x11950` | `0x11b70` | **`+0x220`** |
| `__TEXT.__objc_methname` | `0x72247` | `0x72427` | **`+0x1e0`** |
| `__TEXT.__objc_stubs` | `0x42620` | `0x42800` | **`+0x1e0`** |
| `__TEXT.__swift5_typeref` | `0x59f06` | `0x5a0d0` | **`+0x1ca`** |
| `__DATA_CONST.__const` | `0x30558` | `0x30720` | **`+0x1c8`** |
| `__DATA.__bss` | `0x31fcc` | `0x3210c` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x2c450` | `0x2c590` | **`+0x140`** |
| `__DATA_CONST.__auth_got` | `0x8cc0` | `0x8dd0` | **`+0x110`** |
| `__TEXT.__swift5_reflstr` | `0x12ea0` | `0x12fb0` | **`+0x110`** |
| `__TEXT.__swift5_capture` | `0x9114` | `0x9220` | **`+0x10c`** |
| `__TEXT.__constg_swiftt` | `0x17a28` | `0x17b24` | **`+0xfc`** |
| `__TEXT.__swift5_fieldmd` | `0x102c4` | `0x103a8` | **`+0xe4`** |
| `__TEXT.__objc_classname` | `0xa309` | `0xa399` | **`+0x90`** |
| `__DATA.__common` | `0x10a0` | `0x1128` | **`+0x88`** |
| `__DATA_CONST.__got` | `0x5cc8` | `0x5d48` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0x15e58` | `0x15eb8` | **`+0x60`** |
| `__DATA_CONST.__auth_ptr` | `0x5f40` | `0x5f98` | **`+0x58`** |
| `__TEXT.__objc_methtype` | `0x13c84` | `0x13cc4` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x13f0` | `0x1418` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0xf0a0` | `0xf0c0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x46f8` | `0x4718` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x94c` | `0x968` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0x1718` | `0x1730` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x32f8` | `0x3310` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x990` | `0x9a4` | **`+0x14`** |
| `__DATA_CONST.__objc_doubleobj` | `0x50` | `0x60` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xf58` | `0xf68` | **`+0x10`** |
| `__DATA.__objc_stublist` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1a24` | `0x1a2c` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x24d8` | `0x24dc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-6629.0.0.0.0
+6636.0.0.0.0

+  - /System/Library/PrivateFrameworks/AppleMediaServicesUIKitInternal.framework/AppleMediaServicesUIKitInternal

-  - /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry

+  - /System/Library/PrivateFrameworks/PairedDeviceRegistry.framework/PairedDeviceRegistry

-  Functions: 39584
-  Symbols:   2103
-  CStrings:  25990
+  Functions: 39767
+  Symbols:   2105
+  CStrings:  26057
Symbols:
+ _BSUISignificantChangeGateDidResolveNotification
+ _OBJC_CLASS_$_BSUIWelcomeGDPRViewController
+ _OBJC_CLASS_$_PDRRegistry
- _OBJC_CLASS_$_NRPairedDeviceRegistry
CStrings:
+ "!opening || self.contentLoaded"
+ "%s: %ld of %ld input assetID(s) did not resolve to a library asset"
+ "%s: input assetIDs: %s"
+ "%{public}s: GDPR welcome screen check passed."
+ "%{public}s: GDPR welcome screen pending; throwing interventionRequired."
+ "-bookContentDidLoad -- contentLoaded: %{public}@ waitingForContentLoaded: %{public}@ zoomRequiresContentLoaded: %{public}@ -- nothing to do"
+ "-bookContentDidLoad -- waitingForContentLoaded: NO, showSpinner: NO -- performing _animateSecondHalf after animations complete"
+ "-bookContentDidLoad -- waitingForContentLoaded: NO, zoomRequiresContentLoaded: YES -- performing _animateFirstHalf"
+ "-bookContentDidLoad -- waitingForContentLoaded: YES, zoomRequiresContentLoaded: %{public}@"
+ "AppIntent error message returned to Siri/Shortcuts when an action requires the user to acknowledge Books's GDPR welcome screen before proceeding."
+ "AppIntents.Privacy"
+ "Ask for Approval"
+ "Ask for Approval Again"
+ "BKAppSceneManager dependency resolution"
+ "BKForceSignificantChangeOnNextLaunch"
+ "BKSignificantChangeGateHandler"
+ "Books has been updated"
+ "Books has been updated with new features and content."
+ "Books has been updated with new features and content. You'll need approval from your parent or guardian to continue using the app."
+ "Books.SignificantChangeGateViewController"
+ "Books/SignificantChangeGateViewController.swift"
+ "BooksAssetAppIntentsPerformer dependency resolution"
+ "In order to use Apple Books, open the Apple Books app and review the privacy information."
+ "Line guide button label in reader toolbar"
+ "MaxContentWaitTime (%{public}@s) expired - signaling `bookContentDidLoad`"
+ "Significant change description shown to parent during approval"
+ "Significant change waiting sheet button"
+ "Significant change waiting sheet message"
+ "Significant change waiting sheet title"
+ "Significant change warming sheet button"
+ "Significant change warming sheet message"
+ "Significant change warming sheet title"
+ "SignificantChangeGateHandler: evaluation failed: %{public}@, proceeding normally"
+ "T@\"BKSignificantChangeGateHandler\",N,R"
+ "Table of Contents menu button title"
+ "Td,N,V_spinnerStartTime"
+ "Waiting for Approval"
+ "You'll be able to use Books after your parent or guardian approves your request."
+ "_TtC5Books16FrameLockingView"
+ "_TtC5Books20BookReaderLayoutLock"
+ "_TtC5Books35SignificantChangeGateViewController"
+ "_applicationIconImageForBundleIdentifier:format:"
+ "_isEffectivelyFullScreen"
+ "_pageLabelRegion"
+ "_showSpinner:delay:completion:"
+ "_spinnerScale"
+ "_spinnerStartTime"
+ "`-[ZoomRevealOpen bookContentDidLoad]` contentLoaded: YES -- nothing to do"
+ "`-[ZoomRevealOpen bookContentDidLoad]` waitingForContentLoaded: NO -- nothing to do"
+ "actionWithTitle:image:identifier:handler:"
+ "animating second half - opening: %{public}@ contentLoaded: %{public}@"
+ "animating second half from completion of `spinnerMinDurationComplete`"
+ "appIntentsLibraryAssets(input:in:)"
+ "assetViewControllerLockContentLayoutAtSize:"
+ "assetViewControllerUnlockContentLayout"
+ "content loaded & waiting on content to load"
+ "didPresent"
+ "evaluationTask"
+ "forceShow"
+ "frameLockingView"
+ "hasMultipleColumnsSubject"
+ "initWithDefersGetStartedButton:completion:"
+ "layoutLock"
+ "lockedChild"
+ "lockedSize"
+ "opening & skipping reveal - calling animations finished"
+ "opening but content not loaded -- showing spinner for at least %{public}@s"
+ "opening: %{public}@ - waiting %{public}@s before calling secondHalfDelayComplete"
+ "presentIfNeededFrom:"
+ "presentSignificantChangeGate"
+ "presentationSourceItem"
+ "sessionIndicatorPositionObservationWatcher"
+ "setMenuRepresentation:"
+ "setModalInPresentation:"
+ "setSpinnerStartTime:"
+ "setupSpinner"
+ "spinnerMinDurationComplete"
+ "spinnerMinDurationComplete - contentLoaded: %{public}@ waitingForContentLoaded: %{public}@. Nothing else will happen in this case"
+ "spinnerStartTime"
+ "v36@0:8B16d20@?28"
- "Accessibility value for not active sleep timer"
- "TB,R,N,V_hasValidSnapshot"
- "_flushAnimationsDidFinish"
- "_hasMultipleColumns"
- "_hasValidSnapshot"
- "bookContentDidLoad -- was waiting, finishing after render commit"
- "hasValidSnapshot"
- "hostingController"
- "opening & skipping reveal - content loaded, finishing after render commit"
- "opening & skipping reveal - content not loaded, waiting up to %{public}@s"
- "opening: %{public}@ - waiting %{public}@s before calling _animateSecondHalf"
- "snapshot wait timeout (%{public}@s) expired, finishing after render commit"
- "windowHasValidSnapshot:"
```
