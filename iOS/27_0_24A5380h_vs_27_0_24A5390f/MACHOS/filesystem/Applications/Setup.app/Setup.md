## Setup

> `/Applications/Setup.app/Setup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x257900` | `0x243658` | **`-0x142a8`** |
| `__TEXT.__eh_frame` | `0x4fc8` | `0x40e0` | **`-0xee8`** |
| `__DATA.__objc_const` | `0x4a648` | `0x49878` | **`-0xdd0`** |
| `__DATA_CONST.__const` | `0x9050` | `0x8288` | **`-0xdc8`** |
| `__DATA.__objc_data` | `0xd320` | `0xc778` | **`-0xba8`** |
| `__TEXT.__constg_swiftt` | `0x4260` | `0x3780` | **`-0xae0`** |
| `__DATA.__data` | `0x81c8` | `0x77e0` | **`-0x9e8`** |
| `__TEXT.__objc_methname` | `0x40dfe` | `0x4044e` | **`-0x9b0`** |
| `__TEXT.__const` | `0x3bc0` | `0x3360` | **`-0x860`** |
| `__TEXT.__swift5_typeref` | `0x2b62` | `0x2558` | **`-0x60a`** |
| `__TEXT.__unwind_info` | `0xa190` | `0x9c00` | **`-0x590`** |
| `__TEXT.__swift5_reflstr` | `0x1fe9` | `0x1ab9` | **`-0x530`** |
| `__TEXT.__swift5_fieldmd` | `0x1dc8` | `0x18b4` | **`-0x514`** |
| `__TEXT.__swift5_capture` | `0x155c` | `0x10b0` | **`-0x4ac`** |
| `__TEXT.__objc_stubs` | `0x29440` | `0x29060` | **`-0x3e0`** |
| `__TEXT.__objc_classname` | `0x5f4d` | `0x5b88` | **`-0x3c5`** |
| `__TEXT.__gcc_except_tab` | `0x4ad4` | `0x4e84` | **`+0x3b0`** |
| `__TEXT.__objc_methlist` | `0x1dde8` | `0x1daa8` | **`-0x340`** |
| `__TEXT.__auth_stubs` | `0x2a70` | `0x2890` | **`-0x1e0`** |
| `__DATA.__bss` | `0x2170` | `0x1fa8` | **`-0x1c8`** |
| `__TEXT.__oslogstring` | `0x14a40` | `0x148ae` | **`-0x192`** |
| `__DATA.__objc_selrefs` | `0xcd90` | `0xcc30` | **`-0x160`** |
| `__TEXT.__cstring` | `0xfd1b` | `0xfbdb` | **`-0x140`** |
| `__TEXT.__objc_methtype` | `0xcb2f` | `0xca28` | **`-0x107`** |
| `__DATA_CONST.__auth_got` | `0x1550` | `0x1460` | **`-0xf0`** |
| `__TEXT.__dlopen_cstrs` | `0x16ee` | `0x179c` | **`+0xae`** |
| `__DATA_CONST.__auth_ptr` | `0x550` | `0x4c8` | **`-0x88`** |
| `__TEXT.__swift_as_cont` | `0x2f4` | `0x278` | **`-0x7c`** |
| `__DATA_CONST.__got` | `0x1c70` | `0x1c00` | **`-0x70`** |
| `__DATA_CONST.__objc_classlist` | `0xe60` | `0xe08` | **`-0x58`** |
| `__TEXT.__swift_as_entry` | `0x1e4` | `0x18c` | **`-0x58`** |
| `__DATA_CONST.__objc_protolist` | `0x8a8` | `0x860` | **`-0x48`** |
| `__TEXT.__swift5_types` | `0x224` | `0x1e0` | **`-0x44`** |
| `__TEXT.__swift_as_ret` | `0x1cc` | `0x188` | **`-0x44`** |
| `__DATA_CONST.__objc_protorefs` | `0x2f0` | `0x2c0` | **`-0x30`** |
| `__TEXT.__swift5_builtin` | `0x140` | `0x118` | **`-0x28`** |
| `__TEXT.__swift5_proto` | `0x134` | `0x10c` | **`-0x28`** |
| `__DATA_CONST.__cfstring` | `0xb4c0` | `0xb4e0` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x510` | `0x528` | **`+0x18`** |
| `__TEXT.__swift5_mpenum` | `0x10` | `—` | **`-0x10`** |
| `__TEXT.__swift5_protos` | `0x48` | `0x38` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x1d44` | `0x1d4c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_floatobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`

### Other Changes

```diff

-5407.0.0.0.0
+5409.0.0.0.0

-  Functions: 12599
-  Symbols:   1569
-  CStrings:  14924
+  Functions: 12136
+  Symbols:   1518
+  CStrings:  14794
Symbols:
+ _$s10Foundation6LocaleVMn
+ _$sSy10FoundationE7compare_7options5range6localeSo18NSComparisonResultVqd___So22NSStringCompareOptionsVSnySS5IndexVGSgAA6LocaleVSgtSyRd__lF
+ _OBJC_CLASS_$_UITraitHorizontalSizeClass
+ _OBJC_CLASS_$_UITraitUserInterfaceIdiom
+ _OBJC_CLASS_$_UITraitVerticalSizeClass
- _$s10Foundation3URLV6stringACSgSSh_tcfC
- _$s10Foundation3URLVMn
- _$s23SetupAssistantSupportUI18NewFeaturesContextC11descriptionSSvg
- _$s23SetupAssistantSupportUI18NewFeaturesContextC2eeoiySbAC_ACtFZ
- _$s23SetupAssistantSupportUI18NewFeaturesContextC8bodyTextSSSgvg
- _$s23SetupAssistantSupportUI18NewFeaturesContextC8durationSdvg
- _$s23SetupAssistantSupportUI18NewFeaturesContextC9titleTextSSSgvg
- _$s23SetupAssistantSupportUI18NewFeaturesContextCMa
- _$s23SetupAssistantSupportUI18NewFeaturesContextCMn
- _$s23SetupAssistantSupportUI18NewFeaturesContextCSQAAMc
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerC04loadeF8ContextsSayAA0eF7ContextCGyYaKF
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerC04loadeF8ContextsSayAA0eF7ContextCGyYaKFTu
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerC04playeF7ContentyyKF
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerC05pauseeF7Content2atyAA0eF7ContextCSg_tKF
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerC11removeAssetyyYaKFZ
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerC11removeAssetyyYaKFZTu
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerC13flashControls8durationySd_tF
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerC20isUsingReducedMotionSbyF
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerC21embedInViewControlleryySo06UIViewK0CF
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerC21overrideAssetLocation10Foundation3URLVSgvsTj
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerC23retrieveAssetFromServeryyYaKFZ
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerC23retrieveAssetFromServeryyYaKFZTu
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerC4skip2toyAA0eF7ContextC_tYaKF
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerC4skip2toyAA0eF7ContextC_tYaKFTu
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerC6playerSo6UIViewCvgTj
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerC8delegateAA0eF8Delegate_pSgvsTj
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerCACycfc
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerCMa
- _$s23SetupAssistantSupportUI18NewFeaturesHandlerCMn
- _$s23SetupAssistantSupportUI19NewFeaturesDelegateMp
- _$s23SetupAssistantSupportUI19NewFeaturesDelegateP03newF15ContentDidBeginyyFTq
- _$s23SetupAssistantSupportUI19NewFeaturesDelegateP03newF15ContentDidPauseyyFTq
- _$s23SetupAssistantSupportUI19NewFeaturesDelegateP03newF18ContentDidCompleteyyFTq
- _$s23SetupAssistantSupportUI19NewFeaturesDelegateP03newF20ContentDidTransition2to8durationyAA0eF7ContextC_SdtFTq
- _$s7Combine10PublishersO4ScanVMn
- _$s7Combine10PublishersO4ScanVy_xq_GAA9PublisherAAMc
- _$s7Combine12AnyPublisherVMn
- _$s7Combine12AnyPublisherVyxq_GAA0C0AAMc
- _$s7Combine19CurrentValueSubjectC4sendyyxF
- _$s7Combine9PublisherPAAE010eraseToAnyB0AA0eB0Vy6OutputQz7FailureQzGyF
- _$s7Combine9PublisherPAAE4scanyAA10PublishersO4ScanVy_xqd__Gqd___qd__qd___6OutputQztctlF
- _$s7Combine9PublisherPAAs5NeverO7FailureRtzrlE4sink12receiveValueAA14AnyCancellableCy6OutputQzc_tF
- _$sSd5write2toyxz_ts16TextOutputStreamRzlF
- _$sSo8NSNumberC10FoundationE12floatLiteralABSd_tcfC
- _CGAffineTransformInvert
- _OBJC_CLASS_$_CAGradientLayer
- _OBJC_CLASS_$_OBButtonTray
- _OBJC_CLASS_$_UIPageControlTimerProgress
- _OBJC_CLASS_$_UIPanGestureRecognizer
- _OBJC_CLASS_$_UIScrollView
- _OBJC_CLASS_$__UIScrollPocketInteraction
- _UIAccessibilityAnnouncementNotification
- _UIAccessibilityPostNotification
- _kCCSkipKeyOSShowcase
- _swift_cvw_enumFn_getEnumTag
- _swift_retain_x9
CStrings:
+ "AVGQFirstSupportedReleaseVersion"
+ "AVGestaltGetStringAnswerWithDefault"
+ "BuddyShareDeviceIdentifiersController"
+ "BuddyShareDeviceIdentifiersController.m"
+ "Jul  9 2026"
+ "NSString *BYAVGestaltGetStringAnswerWithDefault(__strong AVGestaltStringQuestion, NSString *__strong)"
+ "NSString *getAVGQFirstSupportedReleaseVersion(void)"
+ "NSString *getTSUserInfoShareDeviceInfoInSetupKey(void)"
+ "ShareDeviceIdentifiers: Failed to create TSSIMSetupFlow"
+ "ShareDeviceIdentifiers: TSSIMSetupFlow returned a view controller; presenting pane"
+ "ShareDeviceIdentifiers: TSSIMSetupFlow returned no view controller; skipping pane"
+ "Skip camera button setup for hardware introduced in iOS %s or later"
+ "Somehow have empty first supported OS release"
+ "Somehow have nil first supported OS release"
+ "T@\"NSString\",R,C,N,V_firstSupportedOSReleaseVersionForThisDevice"
+ "TSUserInfoShareDeviceInfoInSetupKey"
+ "_firstSupportedOSReleaseVersionForThisDevice"
+ "decimalDigitCharacterSet"
+ "firstSupportedOSReleaseVersionForThisDevice"
+ "grammarCheckingType"
+ "preferredContentSizeForView:"
+ "rangeOfCharacterFromSet:"
+ "setGrammarCheckingType:"
+ "softlink:o:path:/System/Library/PrivateFrameworks/AVFCapture.framework/AVFCapture"
+ "void *AVFCaptureLibrary(void)"
- "$__lazy_storage_$_isLargeScreen"
- "/tmp/testNewFeatureVideos.mp4"
- "@\"<_TtP5Setup26NewFeaturesFlowManagerType_>\""
- "@\"BYNetworkMonitor\""
- "@\"_TtC5Setup27NewFeaturesFlowAssetManager\""
- "AVMobileGlassControlsViewController"
- "AVMobileGlassTransportControlsView"
- "B32@0:8@\"UIPageControlTimerProgress\"16q24"
- "BFFSecondPartyProgressIndicatorDisplayable"
- "Did you forget to set currentTextView?"
- "Download new features assets"
- "Error preparing New Features view model: %@"
- "Fade in is not implemented"
- "Failed to download assets: %@"
- "Failed to find player glass control layer."
- "Failed to find transport control layer."
- "Failed to pause"
- "Failed to play new features content: %@"
- "Failed to remove assets: %@"
- "Failed to skip to chapter %s: %@"
- "Failed to sleep: %@"
- "Hiding transport control layer."
- "Ignore chapter selection as we're currently transitioning"
- "Jun 27 2026"
- "NEW_FEATURE_VIDEOS_CONTINUE"
- "NEW_FEATURE_VIDEOS_SKIP"
- "New Feature video was skipped, updating chronicle record."
- "No text to set; Unacceptable!"
- "Pause new features"
- "Remove new features assets"
- "Request to remove new feature assets completed successfully..."
- "Reset new features"
- "Screen size is %dx%d"
- "Selecting chapter at index: %ld"
- "Setup.NewFeaturesFlowAssetManager"
- "Setup.NewFeaturesFlowManager"
- "Setup.NewFeaturesViewController"
- "Setup.iPadNewFeaturesViewController"
- "Setup/NewFeaturesViewController.swift"
- "Showing debug video"
- "T@\"<_TtP5Setup26NewFeaturesFlowManagerType_>\",N,R,Vmanager"
- "T@\"BYNetworkMonitor\",N,R,VnetworkMonitor"
- "T@\"_TtC5Setup27NewFeaturesFlowAssetManager\",&,N,V_mobileAssetsNewFeaturesAssetManager"
- "TB,N,VisAnimating"
- "Transition FadeTextIn: "
- "Transition Slide: "
- "UIPageControlProgressDelegate"
- "UIPageControlTimerProgressDelegate"
- "_TtC5Setup19NewFeaturesFlowItem"
- "_TtC5Setup20NewFeaturesViewModel"
- "_TtC5Setup22NewFeaturesFlowManager"
- "_TtC5Setup25NewFeaturesViewController"
- "_TtC5Setup27NewFeaturesFlowAssetManager"
- "_TtC5SetupP33_815782AA972C2E4207EC20C3BE273F6B12GradientView"
- "_TtC5SetupP33_815782AA972C2E4207EC20C3BE273F6B18NewFeatureTextView"
- "_TtC5SetupP33_815782AA972C2E4207EC20C3BE273F6B29iPadNewFeaturesViewController"
- "_TtC5SetupP33_815782AA972C2E4207EC20C3BE273F6B31iPhoneNewFeaturesViewController"
- "_TtC5SetupP33_D7AF63800C0C948197A2791571DA9AAB23TestNewFeaturesResource"
- "_TtC5SetupP33_D7AF63800C0C948197A2791571DA9AAB39iPadNewFeatureContextTransitionProvider"
- "_TtC5SetupP33_D7AF63800C0C948197A2791571DA9AAB41iPhoneNewFeatureContextTransitionProvider"
- "_TtP5Setup22ManagesNewFeatureAsset_"
- "_TtP5Setup26NewFeaturesFlowManagerType_"
- "_mobileAssetsNewFeaturesAssetManager"
- "_pocketInsets"
- "_scrollToTopIfPossible:"
- "_setPocketInsets:"
- "addInteraction:"
- "allChapters"
- "allContexts"
- "applicationDidBecomeActiveObservationToken"
- "applicationDidEnterBackgroundObservationToken"
- "backButtonTappedWithSender:"
- "bodyLabel"
- "containerScrollView"
- "contentInset"
- "continueButtonContainer"
- "currentChapter"
- "currentContext"
- "currentNetworkType"
- "currentPage"
- "currentPageIndicator"
- "currentTextScrollView"
- "currentTextView"
- "didHideTransportControlLayer"
- "downloadAssetsWhenNetworkIsAvailable"
- "embeddedController"
- "f32@0:8@\"UIPageControlProgress\"16q24"
- "f32@0:8@16q24"
- "gradientLayer"
- "gradientView"
- "handlePanGesture:"
- "headerViewBottomToTableViewTopPadding"
- "initWithChronicle:runState:"
- "initWithManager:networkMonitor:"
- "initWithPreferredDuration:"
- "initWithScrollView:edge:style:"
- "isAnimating"
- "isPlayingState"
- "isUsingReducedMotion"
- "isUsingReducedMotionSettings"
- "labelsContainer"
- "lastSeenVersion"
- "main-screen-height"
- "main-screen-width"
- "mask"
- "mobileAssetsNewFeaturesAssetManager"
- "needsToRun"
- "networkMonitor"
- "newFeaturesFlowHandler"
- "pageControlProgress"
- "pageControlProgress:initialProgressForPage:"
- "pageControlProgressVisibilityDidChange:"
- "pageControlTimerProgress:shouldAdvanceToPage:"
- "pageControlTimerProgressDidChange:"
- "pageControlValueDidChangeWithSender:"
- "panGestureRecognizer"
- "pauseTimer"
- "playerGradientView"
- "playerView"
- "preferredContentSize"
- "recordFlowWasSkippedIfNeeded"
- "removeAssetsWithCompletionHandler:"
- "resumeTimer"
- "setAccessibilityElementsHidden:"
- "setAllowsContinuousInteraction:"
- "setColors:"
- "setCurrentProgress:"
- "setDuration:forPage:"
- "setEndPoint:"
- "setIsAnimating:"
- "setLocations:"
- "setMask:"
- "setMobileAssetsNewFeaturesAssetManager:"
- "setPreferredDuration:"
- "setProductVersion:forFeature:"
- "setStartPoint:"
- "shouldRemoveTransportControl"
- "shouldRenderUIElements"
- "shouldShowSkipButton"
- "shouldUseReducedMotionAnimations"
- "skipButtonTappedWithSender:"
- "startIndeterminateProgressIndicator"
- "stopIndeterminateProgressIndicator"
- "sublayers"
- "textContainer"
- "textWithAnimation"
- "transitionData"
- "transitionProvider"
- "translationInView:"
- "updatePresentedKey:"
- "updateText(chapterIndex:_:description:transition:)"
- "v24@0:8@\"UIPageControlProgress\"16"
- "v24@0:8@\"UIPageControlTimerProgress\"16"
- "velocityInView:"
- "viewTransition"
```
