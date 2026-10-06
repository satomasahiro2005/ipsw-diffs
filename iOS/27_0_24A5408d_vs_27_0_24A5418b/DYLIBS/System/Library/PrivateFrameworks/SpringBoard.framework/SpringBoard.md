## SpringBoard

> `/System/Library/PrivateFrameworks/SpringBoard.framework/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb07b50` | `0xb09db4` | **`+0x2264`** |
| `__TEXT.__objc_methlist` | `0xbd8d0` | `0xbdb30` | **`+0x260`** |
| `__TEXT.__cstring` | `0x84d46` | `0x84f3f` | **`+0x1f9`** |
| `__AUTH_CONST.__cfstring` | `0x744e0` | `0x746a0` | **`+0x1c0`** |
| `__AUTH_CONST.__objc_const` | `0x287848` | `0x2879f0` | **`+0x1a8`** |
| `__TEXT.__gcc_except_tab` | `0x184fc` | `0x18640` | **`+0x144`** |
| `__DATA_CONST.__objc_selrefs` | `0x4e7d0` | `0x4e8b0` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x64e36` | `0x64eda` | **`+0xa4`** |
| `__AUTH.__objc_data` | `0xe3d0` | `0xe470` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x2e4d8` | `0x2e530` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x1d940` | `0x1d990` | **`+0x50`** |
| `__TEXT.__const` | `0x112c0` | `0x11270` | **`-0x50`** |
| `__DATA.__objc_ivar` | `0xfc10` | `0xfc5c` | **`+0x4c`** |
| `__DATA_CONST.__got` | `0xa8f0` | `0xa900` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x54c0` | `0x54d0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x4080` | `0x4088` | **`+0x8`** |

### Other Changes

```diff

-4636.102.1.0.0
+4636.110.0.0.0

-  Functions: 73431
-  Symbols:   119179
-  CStrings:  23474
+  Functions: 73495
+  Symbols:   119269
+  CStrings:  23492
Symbols:
+ +[SBRecordingIndicatorAboveBlankingWindow _isSecure]
+ +[_SBRecordingIndicatorGainMapView layerClass]
+ -[SBAssistantIslandInteractiveGestureTransaction _homeScreenAnimator]
+ -[SBAssistantIslandInteractiveGestureTransaction _setLockScreenScale:withDuration:behaviorMode:completion:]
+ -[SBAssistantIslandSettings .cxx_destruct]
+ -[SBAssistantIslandSettings homeScreenScaleAnimationSettings]
+ -[SBAssistantIslandSettings homeScreenScaleRubberbandingMax]
+ -[SBAssistantIslandSettings homeScreenScaleRubberbandingMin]
+ -[SBAssistantIslandSettings homeScreenScaleRubberbandingRange]
+ -[SBAssistantIslandSettings isHomeScreenScaleEnabled]
+ -[SBAssistantIslandSettings maxTranslationForHomeScreenScale]
+ -[SBAssistantIslandSettings setHomeScreenScaleAnimationSettings:]
+ -[SBAssistantIslandSettings setHomeScreenScaleEnabled:]
+ -[SBAssistantIslandSettings setHomeScreenScaleRubberbandingMax:]
+ -[SBAssistantIslandSettings setHomeScreenScaleRubberbandingMin:]
+ -[SBAssistantIslandSettings setHomeScreenScaleRubberbandingRange:]
+ -[SBAssistantIslandSettings setMaxTranslationForHomeScreenScale:]
+ -[SBAssistantIslandStageController ambientModeEntered]
+ -[SBAssistantIslandStageController setAmbientModeEntered:]
+ -[SBAssistantIslandStageCoordinator _allowsResidentInactiveStages]
+ -[SBAssistantIslandStageCoordinator _isReduceMotionEnabled]
+ -[SBAssistantIslandStageCoordinator _reduceMotionStatusDidChange:]
+ -[SBAssistantIslandStageCoordinator _tearDownAllStageControllers]
+ -[SBBannerTransitionSettings coverSheetGrabberWidthPad]
+ -[SBBannerTransitionSettings coverSheetGrabberWidthPhone]
+ -[SBBannerTransitionSettings customBannerTransitionStyleGlass_cornerTransition_dismissing_positionX]
+ -[SBBannerTransitionSettings customBannerTransitionStyleGlass_cornerTransition_dismissing_positionY]
+ -[SBBannerTransitionSettings customBannerTransitionStyleGlass_cornerTransition_presenting_positionX]
+ -[SBBannerTransitionSettings customBannerTransitionStyleGlass_cornerTransition_presenting_positionY]
+ -[SBBannerTransitionSettings customBannerTransitionStyleGlass_dismissAlphaFraction]
+ -[SBBannerTransitionSettings setCoverSheetGrabberWidthPad:]
+ -[SBBannerTransitionSettings setCoverSheetGrabberWidthPhone:]
+ -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_cornerTransition_dismissing_positionX:]
+ -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_cornerTransition_dismissing_positionY:]
+ -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_cornerTransition_presenting_positionX:]
+ -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_cornerTransition_presenting_positionY:]
+ -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_dismissAlphaFraction:]
+ -[SBCoverSheetGrabberViewController _grabberWidthForAnchorFrame:]
+ -[SBHomeScreenController isHomeScreenScaleOwnedByPulldownGesture]
+ -[SBHomeScreenController(AppearanceControlling) setHomeScreenScale:settings:behaviorMode:completion:]
+ -[SBLockElementViewProvider setEarlyMatchingFeedback:]
+ -[SBLockScreenManager _isEarlyMatchingFeedbackEligibleDevice]
+ -[SBLockScreenManager _shouldShowEarlyMatchingFeedbackForThermalState]
+ -[SBLockScreenManager liftToWakeController:didObserveTransition:deviceOrientation:]
+ -[SBRecordingIndicatorAboveBlankingWindow _configureContextOptions:]
+ -[SBRecordingIndicatorAboveBlankingWindow _ignoresHitTest]
+ -[SBRecordingIndicatorAboveBlankingWindow canBecomeKeyWindow]
+ -[SBRecordingIndicatorAboveBlankingWindow hitTest:withEvent:]
+ -[SBRecordingIndicatorAboveBlankingWindow initWithDisplayConfiguration:level:]
+ -[SBRecordingIndicatorContainerView layoutSubviews]
+ -[SBRecordingIndicatorLayer initWithIndicatorType:]
+ -[SBRecordingIndicatorLayer initWithLayer:]
+ -[SBRecordingIndicatorSecureLayer _applySecureIndicatorLayerIndicatorType]
+ -[SBRecordingIndicatorSecureLayer initWithIndicatorType:]
+ -[SBRecordingIndicatorSettings debugHighLevelDotBorderEnabled]
+ -[SBRecordingIndicatorSettings setDebugHighLevelDotBorderEnabled:]
+ -[SBRecordingIndicatorSystemApertureElement _positionMicroRegionIndicatorFromContainerView:containerPoint:]
+ -[SBRecordingIndicatorView _rebuildIndicatorLayerWithIndicatorType:]
+ -[SBRecordingIndicatorView _shouldAnimatePropertyWithKey:]
+ -[SBRecordingIndicatorView _updateDebugBorder]
+ -[SBRecordingIndicatorView isHighLevel]
+ -[SBRecordingIndicatorView setHighLevel:]
+ -[SBRecordingIndicatorViewController _highLevelRootAlpha]
+ -[SBRecordingIndicatorViewController _sensorRegionFrameInBounds:scale:]
+ -[SBRecordingIndicatorViewController _setHighLevelAlpha:forIndicator:]
+ -[SBRecordingIndicatorViewController _setHighLevelBounds:forIndicator:]
+ -[SBRecordingIndicatorViewController _setHighLevelCenter:forIndicator:]
+ -[SBRecordingIndicatorViewController _setHighLevelRootAlpha:]
+ -[SBRecordingIndicatorViewController _usesHighLevelWindow]
+ -[SBRecordingIndicatorVisualRepresentation _updateHighLevelLayerIndicatorType:]
+ -[SBRecordingIndicatorVisualRepresentation highLevelView]
+ -[SBRecordingIndicatorVisualRepresentation initWithViewType:usesHighLevelView:]
+ -[SBRemoteTransientOverlayHostContentAdapter setShouldUseResizableViewControllerAlways:]
+ -[SBRemoteTransientOverlayHostContentAdapter shouldUseResizableViewControllerAlways]
+ -[SBRemoteTransientOverlayViewController prepareForActivationWithContext:presentationMode:presentEmbedded:shouldUseResizableViewControllerAlways:windowScene:completion:]
+ -[SBScreenBrightnessHostComponent init]
+ -[SBSecureIndicatorBacklightCoordinator _acquirePreventSystemSleepAssertionIfNecessary]
+ -[SBSecureIndicatorBacklightCoordinator _createOrResetPreventSystemSleepAssertion]
+ -[SBSecureIndicatorBacklightCoordinator _releasePreventSystemSleepAssertion]
+ -[SBSecureIndicatorBacklightCoordinator _scheduleReleaseOfPreventSystemSleepAssertion]
+ -[SBSecureIndicatorBacklightCoordinator backlightController:willTransitionToBacklightState:source:]
+ -[SBSecureIndicatorBacklightCoordinator minimumOnTimeCoordinator]
+ -[SBSecureIndicatorBacklightCoordinator preventSystemSleepAssertionID]
+ -[SBSecureIndicatorBacklightCoordinator preventSystemSleepAssertionName]
+ -[SBSecureIndicatorBacklightCoordinator releasePreventSystemSleepAssertionTimer]
+ -[SBSecureIndicatorBacklightCoordinator setPreventSystemSleepAssertionID:]
+ -[SBSecureIndicatorBacklightCoordinator setPreventSystemSleepAssertionName:]
+ -[SBSecureIndicatorBacklightCoordinator setReleasePreventSystemSleepAssertionTimer:]
+ -[SBUserInterfaceStyleSceneUpdater initWithContinuityUserInterfaceStyleProvider:]
+ -[_SBRecordingIndicatorGainMapView gainMapLayer]
+ GCC_except_table403
+ GCC_except_table557
+ GCC_except_table567
+ GCC_except_table582
+ _OBJC_CLASS_$_SBRecordingIndicatorAboveBlankingWindow
+ _OBJC_CLASS_$__SBRecordingIndicatorGainMapView
+ _OBJC_IVAR_$_SBAssistantIslandInteractiveGestureTransaction._assistantIslandSettings
+ _OBJC_IVAR_$_SBAssistantIslandInteractiveGestureTransaction._windowScene
+ _OBJC_IVAR_$_SBAssistantIslandSettings._homeScreenScaleAnimationSettings
+ _OBJC_IVAR_$_SBAssistantIslandSettings._homeScreenScaleEnabled
+ _OBJC_IVAR_$_SBAssistantIslandSettings._homeScreenScaleRubberbandingMax
+ _OBJC_IVAR_$_SBAssistantIslandSettings._homeScreenScaleRubberbandingMin
+ _OBJC_IVAR_$_SBAssistantIslandSettings._homeScreenScaleRubberbandingRange
+ _OBJC_IVAR_$_SBAssistantIslandSettings._maxTranslationForHomeScreenScale
+ _OBJC_IVAR_$_SBAssistantIslandStageController._ambientModeEntered
+ _OBJC_IVAR_$_SBBannerTransitionSettings._coverSheetGrabberWidthPad
+ _OBJC_IVAR_$_SBBannerTransitionSettings._coverSheetGrabberWidthPhone
+ _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_cornerTransition_dismissing_positionX
+ _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_cornerTransition_dismissing_positionY
+ _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_cornerTransition_presenting_positionX
+ _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_cornerTransition_presenting_positionY
+ _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_dismissAlphaFraction
+ _OBJC_IVAR_$_SBLockElementViewProvider._earlyMatchingFeedback
+ _OBJC_IVAR_$_SBLockScreenManager._liftToWakeController
+ _OBJC_IVAR_$_SBRecordingIndicatorSettings._debugHighLevelDotBorderEnabled
+ _OBJC_IVAR_$_SBRecordingIndicatorView._highLevel
+ _OBJC_IVAR_$_SBRecordingIndicatorViewController._defaultGainMapDefeatingView
+ _OBJC_IVAR_$_SBRecordingIndicatorViewController._highLevelWindow
+ _OBJC_IVAR_$_SBRecordingIndicatorVisualRepresentation._highLevelView
+ _OBJC_IVAR_$_SBRemoteTransientOverlayHostContentAdapter._shouldUseResizableViewControllerAlways
+ _OBJC_IVAR_$_SBScreenBrightnessHostComponent._lastNotifiedBrightnessLock
+ _OBJC_IVAR_$_SBScreenBrightnessHostComponent._lock_lastNotifiedBrightness
+ _OBJC_IVAR_$_SBSecureIndicatorBacklightCoordinator._preventSystemSleepAssertionID
+ _OBJC_IVAR_$_SBSecureIndicatorBacklightCoordinator._preventSystemSleepAssertionName
+ _OBJC_IVAR_$_SBSecureIndicatorBacklightCoordinator._releasePreventSystemSleepAssertionTimer
+ _OBJC_METACLASS_$_SBRecordingIndicatorAboveBlankingWindow
+ _OBJC_METACLASS_$__SBRecordingIndicatorGainMapView
+ _OUTLINED_FUNCTION_36
+ _OUTLINED_FUNCTION_37
+ __OBJC_$_CLASS_METHODS_SBRecordingIndicatorAboveBlankingWindow
+ __OBJC_$_CLASS_METHODS__SBRecordingIndicatorGainMapView
+ __OBJC_$_INSTANCE_METHODS_SBRecordingIndicatorAboveBlankingWindow
+ __OBJC_$_INSTANCE_METHODS_SBSwitcherModifier(SharedModifierUtilities|WindowingModifier)
+ __OBJC_$_INSTANCE_METHODS__SBRecordingIndicatorGainMapView
+ __OBJC_CLASS_RO_$_SBRecordingIndicatorAboveBlankingWindow
+ __OBJC_CLASS_RO_$__SBRecordingIndicatorGainMapView
+ __OBJC_METACLASS_RO_$_SBRecordingIndicatorAboveBlankingWindow
+ __OBJC_METACLASS_RO_$__SBRecordingIndicatorGainMapView
+ ___101-[SBHomeScreenController(AppearanceControlling) setHomeScreenScale:settings:behaviorMode:completion:]_block_invoke
+ ___101-[SBHomeScreenController(AppearanceControlling) setHomeScreenScale:settings:behaviorMode:completion:]_block_invoke_2
+ ___107-[SBAssistantIslandInteractiveGestureTransaction _setLockScreenScale:withDuration:behaviorMode:completion:]_block_invoke
+ ___130+[SBRemoteTransientOverlayHostContentAdapter requestContentAdaptersForAlertDefinition:sceneWorkspaceController:connectionHandler:]_block_invoke_4
+ ___61-[SBLockScreenManager _isEarlyMatchingFeedbackEligibleDevice]_block_invoke
+ ___66-[SBAssistantIslandStageCoordinator _reduceMotionStatusDidChange:]_block_invoke
+ ___86-[SBSecureIndicatorBacklightCoordinator _scheduleReleaseOfPreventSystemSleepAssertion]_block_invoke
+ ___block_descriptor_104_e8_32s40bs48bs56r64r_e8_v16?0d8ls40l8r56l8s32l8r64l8s48l8
+ ___block_descriptor_40_e8_32r_e49_v32?0"SBTransientOverlayViewController"8Q16^B24lr32l8
+ ___block_descriptor_56_e8_32s40s48s_e50_v16?0"SBRecordingIndicatorVisualRepresentation"8ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40r48r56w_e11_v16?0B8B12ls32l8w56l8r40l8r48l8
+ ___block_descriptor_72_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_80_e8_32s40s48bs56r_e5_v8?0lr56l8s32l8s40l8s48l8
+ ___block_descriptor_88_e8_32s40s48s56r64r72r_e5_v8?0lr56l8r64l8r72l8s32l8s40l8s48l8
+ __isEarlyMatchingFeedbackEligibleDevice.eligible
+ __isEarlyMatchingFeedbackEligibleDevice.onceToken
- -[SBAssistantIslandStagePlaceholderController setWasInitiallyRunning:]
- -[SBAssistantIslandStagePlaceholderController wasInitiallyRunning]
- -[SBBannerTransitionSettings customBannerTransitionStyleGlass_cornerTransition_positionX]
- -[SBBannerTransitionSettings customBannerTransitionStyleGlass_cornerTransition_positionY]
- -[SBBannerTransitionSettings customBannerTransitionStyleGlass_dismissGestureOvershootInsetMinScale]
- -[SBBannerTransitionSettings customBannerTransitionStyleGlass_dismissGestureOvershootReferenceInset]
- -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_cornerTransition_positionX:]
- -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_cornerTransition_positionY:]
- -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_dismissGestureOvershootInsetMinScale:]
- -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_dismissGestureOvershootReferenceInset:]
- -[SBHomeScreenController(AppearanceControlling) setHomeScreenScale:behaviorMode:completion:]
- -[SBLockScreenManager _isThermalCriticalGlyphBloomEligibleDevice]
- -[SBLockScreenManager _shouldBloomForThermalCriticalUnlock]
- -[SBLockScreenManager _thermalConditionDidChange:]
- -[SBRecordingIndicatorLayer setIndicatorType:]
- -[SBRecordingIndicatorManager _createOrResetPreventSystemSleepAssertion]
- -[SBRecordingIndicatorManager _releasePreventSystemSleepAssertion]
- -[SBRecordingIndicatorManager _scheduleReleaseOfPreventSystemSleepAssertion]
- -[SBRecordingIndicatorManager preventSystemSleepAssertionID]
- -[SBRecordingIndicatorManager preventSystemSleepAssertionName]
- -[SBRecordingIndicatorManager releasePreventSystemSleepAssertionTimer]
- -[SBRecordingIndicatorManager setPreventSystemSleepAssertionID:]
- -[SBRecordingIndicatorManager setPreventSystemSleepAssertionName:]
- -[SBRecordingIndicatorManager setReleasePreventSystemSleepAssertionTimer:]
- -[SBRecordingIndicatorSecureLayer _commonInit]
- -[SBRecordingIndicatorSecureLayer _resetSecureIndicatorLayerIndicatorType]
- -[SBRecordingIndicatorSecureLayer initWithCoder:]
- -[SBRecordingIndicatorSecureLayer init]
- -[SBRecordingIndicatorSecureLayer setIndicatorType:]
- -[SBRecordingIndicatorView _rebuildIndicatorLayer]
- -[SBRecordingIndicatorVisualRepresentation initWithViewType:]
- -[SBRemoteTransientOverlayHostContentAdapter setShouldUseResizableViewController:]
- -[SBRemoteTransientOverlayHostContentAdapter shouldUseResizableViewController]
- -[SBRemoteTransientOverlayViewController prepareForActivationWithContext:presentationMode:presentEmbedded:shouldUseResizableViewController:windowScene:completion:]
- -[SBUserInterfaceStyleSceneUpdater init]
- GCC_except_table178
- GCC_except_table259
- GCC_except_table265
- GCC_except_table566
- GCC_except_table579
- GCC_except_table581
- _OBJC_IVAR_$_SBAssistantIslandStagePlaceholderController._wasInitiallyRunning
- _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_cornerTransition_positionX
- _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_cornerTransition_positionY
- _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_dismissGestureOvershootInsetMinScale
- _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_dismissGestureOvershootReferenceInset
- _OBJC_IVAR_$_SBRecordingIndicatorManager._preventSystemSleepAssertionID
- _OBJC_IVAR_$_SBRecordingIndicatorManager._preventSystemSleepAssertionName
- _OBJC_IVAR_$_SBRecordingIndicatorManager._releasePreventSystemSleepAssertionTimer
- _OBJC_IVAR_$_SBRemoteTransientOverlayHostContentAdapter._shouldUseResizableViewController
- _OBJC_IVAR_$_SBScreenBrightnessHostComponent._lastNotifiedBrightness
- __OBJC_$_INSTANCE_METHODS_SBSwitcherModifier(WindowingModifier|SharedModifierUtilities)
- __OBJC_$_PROP_LIST_SAUIContentTransitioning
- ___65-[SBLockScreenManager _isThermalCriticalGlyphBloomEligibleDevice]_block_invoke
- ___76-[SBRecordingIndicatorManager _scheduleReleaseOfPreventSystemSleepAssertion]_block_invoke
- ___92-[SBHomeScreenController(AppearanceControlling) setHomeScreenScale:behaviorMode:completion:]_block_invoke
- ___92-[SBHomeScreenController(AppearanceControlling) setHomeScreenScale:behaviorMode:completion:]_block_invoke_2
- ___block_descriptor_48_e8_32s40s_e50_v16?0"SBRecordingIndicatorVisualRepresentation"8ls32l8s40l8
- ___block_descriptor_56_e8_32s40r48w_e11_v16?0B8B12ls32l8w48l8r40l8
- ___block_descriptor_64_e8_32bs40r48r_e8_v16?0d8lr40l8r48l8s32l8
- ___block_descriptor_72_e8_32s40s48r56r64r_e5_v8?0lr48l8r56l8r64l8s32l8s40l8
- ___block_descriptor_80_e8_32s40bs48r56r_e5_v8?0lr48l8s32l8r56l8s40l8
- __isThermalCriticalGlyphBloomEligibleDevice.eligible
- __isThermalCriticalGlyphBloomEligibleDevice.onceToken
CStrings:
+ "Debug High-Level Dot Border"
+ "Glass Corner Dismiss - position.x"
+ "Glass Corner Dismiss - position.y"
+ "Glass Corner Present - position.x"
+ "Glass Corner Present - position.y"
+ "Glass Dismiss Alpha Fraction"
+ "Grabber Width - Pad"
+ "Grabber Width - Phone"
+ "Home Screen Dimming Opacity Animation Settings"
+ "[Recording Indicator] creating secure indicator layer for view-dot with %@"
+ "com.apple.AuthenticationServicesUI"
+ "com.apple.LocalAuthenticationUIService"
+ "coverSheetGrabberWidthPad"
+ "coverSheetGrabberWidthPhone"
+ "customBannerTransitionStyleGlass_cornerTransition_dismissing_positionX"
+ "customBannerTransitionStyleGlass_cornerTransition_dismissing_positionY"
+ "customBannerTransitionStyleGlass_cornerTransition_presenting_positionX"
+ "customBannerTransitionStyleGlass_cornerTransition_presenting_positionY"
+ "customBannerTransitionStyleGlass_dismissAlphaFraction"
+ "debugHighLevelDotBorderEnabled"
+ "fetchOrCreateNewStageController: refusing to reuse resident inactive stage %{public}@ because it was used for standby"
+ "fetchOrCreateNewStageController: refusing to reuse resident inactive stage %{public}@ because resident inactive stages are disallowed"
+ "homeScreenDimmingOpacityAnimationSettings"
+ "homeScreenScaleEnabled"
+ "reduce motion"
+ "v32@?0@\"SBTransientOverlayViewController\"8Q16^B24"
+ "\xf0\x81"
+ "\xf0\xf0\xc1"
- "Glass Corner - position.x"
- "Glass Corner - position.y"
- "Glass Dismiss Gesture Overshoot Inset Min Scale"
- "Glass Dismiss Gesture Overshoot Reference Inset"
- "Removing stage controller %{public}@ in window scene: %{public}@ because the device locked"
- "[Recording Indicator] updating secure indicator type for view-dot to %@"
- "customBannerTransitionStyleGlass_cornerTransition_positionX"
- "customBannerTransitionStyleGlass_cornerTransition_positionY"
- "customBannerTransitionStyleGlass_dismissGestureOvershootInsetMinScale"
- "customBannerTransitionStyleGlass_dismissGestureOvershootReferenceInset"
```
