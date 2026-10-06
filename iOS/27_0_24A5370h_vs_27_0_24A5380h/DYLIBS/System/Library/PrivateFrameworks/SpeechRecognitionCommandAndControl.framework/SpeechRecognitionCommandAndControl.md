## SpeechRecognitionCommandAndControl

> `/System/Library/PrivateFrameworks/SpeechRecognitionCommandAndControl.framework/SpeechRecognitionCommandAndControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1206b4` | `0x1215cc` | **`+0xf18`** |
| `__TEXT.__oslogstring` | `0x3f5a` | `0x40ca` | **`+0x170`** |
| `__AUTH_CONST.__cfstring` | `0x9780` | `0x9860` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0x2290` | `0x22f8` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0xbeac` | `0xbf14` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0x11880` | `0x118e0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x7e20` | `0x7e78` | **`+0x58`** |
| `__TEXT.__cstring` | `0x9577` | `0x95c7` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x4318` | `0x4358` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x1538` | `0x1558` | **`+0x20`** |
| `__TEXT.__const` | `0x47b4` | `0x47d4` | **`+0x20`** |
| `__DATA.__data` | `0x3258` | `0x3270` | **`+0x18`** |
| `__AUTH.__objc_data` | `0x4778` | `0x4788` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x20c0` | `0x20d0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xae8` | `0xaf8` | **`+0x10`** |
| `__TEXT.__ustring` | `0x8a` | `0x96` | **`+0xc`** |
| `__AUTH_CONST.__const` | `0x4f38` | `0x4f30` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xaa0` | `0xaa8` | **`+0x8`** |

### Other Changes

```diff

-182.0.0.0.0
+183.0.0.0.0

-  Functions: 7290
-  Symbols:   14715
-  CStrings:  1831
+  Functions: 7313
+  Symbols:   14741
+  CStrings:  1843
Symbols:
+ +[CACScreenshotGrabber copyFullscreenScreenshotSurface:]
+ -[CACBannerViewPresenter _avoidanceRegionDidChange:]
+ -[CACBannerViewPresenter dealloc]
+ -[CACBannerViewPresenter hasVerticalAvoidanceRegion]
+ -[CACBannerViewPresenter setHasVerticalAvoidanceRegion:]
+ -[CACSpokenCommandManager siriStateTransitionDebugStringFrom:to:useEmoji:]
+ -[CACSynchronousRemoteRequestResult initWithCommands:closeResult:partialResult:]
+ -[CACSynchronousRemoteRequestResult isPartialResult]
+ GCC_except_table107
+ GCC_except_table108
+ GCC_except_table117
+ GCC_except_table130
+ GCC_except_table153
+ GCC_except_table156
+ GCC_except_table159
+ GCC_except_table169
+ GCC_except_table172
+ GCC_except_table173
+ GCC_except_table179
+ GCC_except_table180
+ GCC_except_table185
+ GCC_except_table188
+ GCC_except_table204
+ GCC_except_table213
+ GCC_except_table228
+ GCC_except_table235
+ GCC_except_table251
+ GCC_except_table254
+ GCC_except_table257
+ GCC_except_table258
+ GCC_except_table262
+ GCC_except_table267
+ GCC_except_table273
+ GCC_except_table276
+ GCC_except_table277
+ GCC_except_table78
+ GCC_except_table87
+ GCC_except_table88
+ GCC_except_table92
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC19downscaleScreenshotSbvgZ
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC19downscaleScreenshotSbvpZ
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC19downscaleScreenshotSbvpZMV
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC19downscaleScreenshot_WZ
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC19downscaleScreenshot_Wz
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC22deactivateVCIKeepAliveyyF
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC22deactivateVCIKeepAliveyyFTj
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC22deactivateVCIKeepAliveyyFTo
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC22deactivateVCIKeepAliveyyFTq
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC22deactivateVCIKeepAliveyyFyyYbcfU_
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC22deactivateVCIKeepAliveyyFyyYbcfU_TA
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC25vciEnabledSettingObserver33_9480A7531EBC5C427E4D609C2C9BD5DCLLSo8NSObject_pSgvpZ
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC29activateVCIKeepAliveIfEnabledyyFTm
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC31startObservingVCIEnabledSettingyyFZ
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC31startObservingVCIEnabledSettingyyFZTf4d_n
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC31startObservingVCIEnabledSettingyyFZTj
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC31startObservingVCIEnabledSettingyyFZTo
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC31startObservingVCIEnabledSettingyyFZTq
+ _$s34SpeechRecognitionCommandAndControl21CACUIGroundingMatcherC31startObservingVCIEnabledSettingyyFZy10Foundation12NotificationVYbcfU_
+ _AVAudioSessionMediaServicesWereResetNotification
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_IVAR_$_CACBannerViewPresenter._hasVerticalAvoidanceRegion
+ _OBJC_IVAR_$_CACSynchronousRemoteRequestResult._isPartialResult
+ ___56+[CACScreenshotGrabber copyFullscreenScreenshotSurface:]_block_invoke
+ ___block_descriptor_36_e43_q24?0"SRDMatchResult"8"SRDMatchResult"16l
+ ___block_descriptor_40_e8_32bs_e24_v16?0"NSNotification"8ls32l8
+ _displayRecognizedMessageUsingAttributedString:isIntelligenceCommand:.gRecognizedAudioPlayerLock
+ _siriStateTransitionDebugStringFrom:to:useEmoji:.bits
- +[CACScreenshotGrabber copyFullscreenScreenshotSurface]
- -[CACSynchronousRemoteRequestResult initWithCommands:closeResult:]
- GCC_except_table102
- GCC_except_table103
- GCC_except_table106
- GCC_except_table115
- GCC_except_table128
- GCC_except_table151
- GCC_except_table152
- GCC_except_table157
- GCC_except_table162
- GCC_except_table165
- GCC_except_table171
- GCC_except_table177
- GCC_except_table178
- GCC_except_table183
- GCC_except_table184
- GCC_except_table202
- GCC_except_table211
- GCC_except_table226
- GCC_except_table233
- GCC_except_table249
- GCC_except_table252
- GCC_except_table255
- GCC_except_table256
- GCC_except_table260
- GCC_except_table265
- GCC_except_table271
- GCC_except_table274
- GCC_except_table275
- GCC_except_table73
- GCC_except_table80
- GCC_except_table83
- GCC_except_table90
- _CACLogSiriCoordination
- _CACLogSiriCoordination.onceToken
- _CACLogSiriCoordination.sLogSiriCoordination
- ___55+[CACScreenshotGrabber copyFullscreenScreenshotSurface]_block_invoke
- ___88+[CACSpokenCommand displayRecognizedMessageUsingAttributedString:isIntelligenceCommand:]_block_invoke_5
- ___CACLogSiriCoordination_block_invoke
- ___block_descriptor_32_e43_q24?0"SRDMatchResult"8"SRDMatchResult"16l
CStrings:
+ "%@%s: %d->%d"
+ ", "
+ "ActiveRequest"
+ "ActiveSession"
+ "Asking UIApplication to open URL %{sensitive}@"
+ "CACAvoidanceRegionDidChangeNotification"
+ "Deactivated VCI keep-alive sessions"
+ "Did not receive a completion callback within the timeout for VoiceOver announcement: %{sensitive}@"
+ "Error creating language model from text: '%{sensitive}@', %{public}@"
+ "Failed to set AVAudioSession category to Ambient: %{public}@"
+ "Search Spotlight 2.1. [trysLeft: %ld]. Found Spotlight bundleId. screenElement: %{private}@, traits: %@, value: %{sensitive}@, bundleId: %@"
+ "Search Spotlight 3. Checking for back button. labeledElementsMatchingBackButtonTrait: %{private}@, labeledButtonsMatchingTitle: %{private}@"
+ "Search Spotlight 4.1. Found text field. screenElement: %{private}@, traits: %@"
+ "Search Spotlight 5. Has search phrase: %{sensitive}@"
+ "Search Spotlight 5.1 [trysLeft: %ld]. Waiting for focus. spotlightSearchFieldFocused: %d, trait: %@, value: %{sensitive}@"
+ "Search Spotlight 5.2. Spotlight search field focused. value: %{sensitive}@, label: %{sensitive}@, numTrysLeft: %ld"
+ "Speaking"
+ "UIApplication failed to open URL %{sensitive}@"
+ "UIApplication successfully opened URL %{sensitive}@"
+ "Unexpectedly received did finish notification for unrecognized announcement. Current announcement: %{sensitive}@, notification announcement: %{sensitive}@"
+ "WasPartialResult"
+ "[handleDictation] textVariants: %{sensitive}@"
+ "isVertical"
+ "notifyObserver Siri state %{public}@ | siriGateOnActiveRequest=%d | %{public}@siriIsListening: %d->%d"
+ "siriCoordination"
+ "speechRecognitionTask:didFinishRecognition:, task ID: %@, result: %{sensitive}@"
+ "⚫️"
+ "🟢"
- "Asking UIApplication to open URL %@"
- "Did not receive a completion callback within the timeout for VoiceOver announcement: %@"
- "Error creating language model from text: '%@', %@"
- "Search Spotlight 2.1. [trysLeft: %ld]. Found Spotlight bundleId. screenElement: %@, traits: %@, value: %@, bundleId: %@"
- "Search Spotlight 3. Checking for back button. labeledElementsMatchingBackButtonTrait: %@, labeledButtonsMatchingTitle: %@"
- "Search Spotlight 4.1. Found text field. screenElement: %@, traits: %@"
- "Search Spotlight 5. Has search phrase: %@"
- "Search Spotlight 5.1 [trysLeft: %ld]. Waiting for focus. spotlightSearchFieldFocused: %d, trait: %@, value: %@"
- "Search Spotlight 5.2. Spotlight search field focused. value: %@, label: %@, numTrysLeft: %ld"
- "SiriCoordination"
- "UIApplication failed to open URL %@"
- "UIApplication successfully opened URL %@"
- "Unexpectedly received did finish notification for unrecognized announcement. Current announcement: %@, notification announcement: %@"
- "[handleDictation] textVariants: %@"
- "notifyObserver from=%llu to=%llu isActiveSession=%d isListening=%d -> siriIsListening=%d (was %d)"
- "speechRecognitionTask:didFinishRecognition:, task ID: %@, result: %@"
```
