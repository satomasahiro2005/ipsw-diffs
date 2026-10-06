## SpringBoard

> `/System/Library/PrivateFrameworks/SpringBoard.framework/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xadcd24` | `0xae8878` | **`+0xbb54`** |
| `__AUTH_CONST.__objc_const` | `0x27ec00` | `0x2824c8` | **`+0x38c8`** |
| `__TEXT.__objc_methlist` | `0xbade0` | `0xbbbf8` | **`+0xe18`** |
| `__TEXT.__oslogstring` | `0x60ffc` | `0x61caf` | **`+0xcb3`** |
| `__TEXT.__cstring` | `0x82bdc` | `0x83663` | **`+0xa87`** |
| `__AUTH_CONST.__cfstring` | `0x728c0` | `0x73160` | **`+0x8a0`** |
| `__TEXT.__unwind_info` | `0x2d748` | `0x2de40` | **`+0x6f8`** |
| `__DATA_CONST.__objc_selrefs` | `0x4d578` | `0x4daf0` | **`+0x578`** |
| `__TEXT.__gcc_except_tab` | `0x17e20` | `0x181c0` | **`+0x3a0`** |
| `__AUTH.__objc_data` | `0xf6e0` | `0xfa00` | **`+0x320`** |
| `__DATA_CONST.__const` | `0x1d280` | `0x1d550` | **`+0x2d0`** |
| `__TEXT.__const` | `0x11470` | `0x11250` | **`-0x220`** |
| `__DATA.__data` | `0x20930` | `0x20b10` | **`+0x1e0`** |
| `__DATA.__objc_ivar` | `0xf808` | `0xf960` | **`+0x158`** |
| `__AUTH_CONST.__const` | `0x10918` | `0x109f8` | **`+0xe0`** |
| `__DATA_CONST.__got` | `0xa7e8` | `0xa860` | **`+0x78`** |
| `__TEXT.__dlopen_cstrs` | `0x313` | `0x373` | **`+0x60`** |
| `__DATA_DIRTY.__objc_data` | `0x24f90` | `0x24f40` | **`-0x50`** |
| `__DATA_CONST.__objc_classlist` | `0x53d8` | `0x5420` | **`+0x48`** |
| `__DATA_CONST.__objc_superrefs` | `0x3fd0` | `0x4010` | **`+0x40`** |
| `__AUTH_CONST.__objc_intobj` | `0x2c58` | `0x2c88` | **`+0x30`** |
| `__DATA_CONST.__objc_protolist` | `0x2a58` | `0x2a80` | **`+0x28`** |
| `__DATA.__bss` | `0xb00` | `0xb20` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x18b0` | `0x18c0` | **`+0x10`** |

### Other Changes

```diff

-4615.3.107.0.0
+4621.0.0.0.0

+  - /System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels

-  - /System/Library/PrivateFrameworks/SpringBoardDisplayServices.framework/SpringBoardDisplayServices

-  Functions: 72355
-  Symbols:   117573
-  CStrings:  23052
+  Functions: 72722
+  Symbols:   118107
+  CStrings:  23169
Symbols:
+ +[SBAppLayout genericAppLayout]
+ +[SBAppResizeWorkspaceTransaction transformDisplayConfiguration:bounds:]
+ +[SBAssistantIslandWorkspace _enhancedSiriAvailabilityDidChange]
+ +[SBCoverSheetGrabberWindow _traitsArbiterOrientationActuationRole]
+ +[SBFocusModeBaseAlwaysOnPolicy policyIdentifier]
+ +[SBFocusModeSleepSuppressionPolicy policyIdentifier]
+ +[SBSceneBarPositionResolverSceneExtension hostComponents]
+ +[SBSceneBarPositionResolverUtility applyBarPositionResolversToScene:positionResolver:alignmentResolver:sizeClassResolver:]
+ +[SBSceneBarPositionResolverUtility barAlignmentsResolverForWindowControlsLayout:supportsSolariumSafeAreas:screenType:]
+ +[SBSceneBarPositionResolverUtility barSizeClassResolverForScreenType:isPhone:]
+ +[SBSceneDestructionConfirmationOverlayViewProvider _providersByHandle]
+ +[SBSceneDestructionConfirmationOverlayViewProvider providerForSceneHandle:]
+ -[FBSScene(SBHostProxyClientComponent) initialDisplayConfiguration]
+ -[FBSScene(SBHostProxyClientComponent) updateDisplayConfiguration:]
+ -[FBScene(SafeAreaResolverExtensionDelegate) sb_safeAreaResolverExtensionDelegate]
+ -[FBScene(SafeAreaResolverExtensionDelegate) sb_setSafeAreaResolverExtensionDelegate:]
+ -[SBAccessibilityUIServerUISceneController .cxx_destruct]
+ -[SBAccessibilityUIServerUISceneController _isDefaultPresenterDelegate]
+ -[SBAccessibilityUIServerUISceneController scenePresenter:didPresentScene:]
+ -[SBAccessibilityUIServerUISceneController scenePresenter:willDismissScene:]
+ -[SBActivityAmbientViewController _invalidateBacklightSceneHostEnvironments]
+ -[SBActivityAmbientViewController sceneHostEnvironmentEntriesForBacklightSession]
+ -[SBAmbientIdleTimerController backlightController:didTransitionToBacklightState:source:]
+ -[SBAmbientIdleTimerController initWithWindowScene:backlightController:]
+ -[SBAmbientPresentationController shouldSuppressNotificationBanner]
+ -[SBAppResizingCoordinator _setLastInteractedResizableSceneHandle:provider:]
+ -[SBAppRestrictionsHostComponent preflightSceneHandle]
+ -[SBAppRestrictionsHostComponent shouldApplySafeAreaForScene:]
+ -[SBAssistantIslandStageCoordinator _containerBoundsForWindowScene:containerOrientation:]
+ -[SBAssistantIslandStageCoordinator _idleTimerBehavior]
+ -[SBAssistantIslandStageCoordinator _idleTimerCoordinator]
+ -[SBAssistantIslandStageCoordinator _recheckIdleTimerBehaviorForReason:]
+ -[SBAssistantIslandStageCoordinator _setIdleTimerCoordinator:]
+ -[SBAssistantIslandStageCoordinator _windowSceneWithActivelyDrivingStageController]
+ -[SBAssistantIslandStageCoordinator coordinatorRequestedIdleTimerBehavior:]
+ -[SBAssistantIslandStageCoordinator hasIdleTimerBehaviors]
+ -[SBAssistantIslandStageCoordinator idleTimerDuration]
+ -[SBAssistantIslandStageCoordinator idleTimerMode]
+ -[SBAssistantIslandStageCoordinator idleWarnMode]
+ -[SBAssistantIslandStageCoordinator stageControllerActiveStateDidChange:]
+ -[SBAssistantIslandStageGestureManager _isTouchOverBanner:]
+ -[SBAssistantIslandStageGestureManager _windowSceneDidUpdateReachabilityController:]
+ -[SBAssistantIslandStageGestureManager dealloc]
+ -[SBAssistantIslandStageGestureManager handleReachabilityModeActivated]
+ -[SBAssistantIslandStageGestureManager handleReachabilityModeDeactivated]
+ -[SBBannerCustomTransitioningDelegate .cxx_destruct]
+ -[SBBannerCustomTransitioningDelegate finalAnimationDidCommitHandler]
+ -[SBBannerCustomTransitioningDelegate setFinalAnimationDidCommitHandler:]
+ -[SBBannerManager _beginPresentInsetSuspensionWithCoordinator:]
+ -[SBBannerManager _endPresentInsetSuspension]
+ -[SBBannerManager _invalidateOrDeferPreferredMinimumTopInset]
+ -[SBBannerManager _invalidatePreferredMinimumTopInset]
+ -[SBBannerTransitionSettings customBannerTransitionStyleGlass_dismissGestureOvershootInsetMinScale]
+ -[SBBannerTransitionSettings customBannerTransitionStyleGlass_dismissGestureOvershootMaxX]
+ -[SBBannerTransitionSettings customBannerTransitionStyleGlass_dismissGestureOvershootReferenceInset]
+ -[SBBannerTransitionSettings customBannerTransitionStyleGlass_dismissGestureOvershootSpringX]
+ -[SBBannerTransitionSettings customBannerTransitionStyleGlass_dismissGestureOvershootVelocityScaleX]
+ -[SBBannerTransitionSettings customBannerTransitionStyleGlass_dismissGestureOvershootVelocityScaleY]
+ -[SBBannerTransitionSettings customBannerTransitionStyleGlass_dismissGestureOvershootX]
+ -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_dismissGestureOvershootInsetMinScale:]
+ -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_dismissGestureOvershootMaxX:]
+ -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_dismissGestureOvershootReferenceInset:]
+ -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_dismissGestureOvershootSpringX:]
+ -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_dismissGestureOvershootVelocityScaleX:]
+ -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_dismissGestureOvershootVelocityScaleY:]
+ -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_dismissGestureOvershootX:]
+ -[SBChargingAlertElement .cxx_destruct]
+ -[SBChargingAlertElement _applyLayoutForLimitedSize:]
+ -[SBChargingAlertElement _buildContentViews]
+ -[SBChargingAlertElement _buildLeadingView]
+ -[SBChargingAlertElement _buildMinimalView]
+ -[SBChargingAlertElement _buildTrailingView]
+ -[SBChargingAlertElement _canShowWhileLocked]
+ -[SBChargingAlertElement _layoutMetrics]
+ -[SBChargingAlertElement _trailingViewWidth]
+ -[SBChargingAlertElement _updateBatteryContent]
+ -[SBChargingAlertElement _updateMinimalViewWithDelayToState:]
+ -[SBChargingAlertElement alertHost]
+ -[SBChargingAlertElement batteryPercentage]
+ -[SBChargingAlertElement clientIdentifier]
+ -[SBChargingAlertElement defaultLeadingConstraints]
+ -[SBChargingAlertElement defaultTrailingConstraints]
+ -[SBChargingAlertElement description]
+ -[SBChargingAlertElement elementDescription]
+ -[SBChargingAlertElement elementHost]
+ -[SBChargingAlertElement elementIdentifier]
+ -[SBChargingAlertElement element]
+ -[SBChargingAlertElement handleElementViewEvent:]
+ -[SBChargingAlertElement hasAlertBehavior]
+ -[SBChargingAlertElement initWithIdentifier:batteryPercentage:lowPowerModeEnabled:]
+ -[SBChargingAlertElement isDisplayedWithLimitedSize]
+ -[SBChargingAlertElement isLowPowerModeEnabled]
+ -[SBChargingAlertElement isProvidedViewConcentric:inLayoutMode:]
+ -[SBChargingAlertElement keyColor]
+ -[SBChargingAlertElement layoutHost]
+ -[SBChargingAlertElement layoutMode]
+ -[SBChargingAlertElement leadingBatteryIconPackageView]
+ -[SBChargingAlertElement leadingLabel]
+ -[SBChargingAlertElement leadingView]
+ -[SBChargingAlertElement limitedSizeLeadingConstraints]
+ -[SBChargingAlertElement limitedSizeTrailingConstraints]
+ -[SBChargingAlertElement maximumSupportedLayoutMode]
+ -[SBChargingAlertElement minimalBatteryIconPackageView]
+ -[SBChargingAlertElement minimalView]
+ -[SBChargingAlertElement minimumSupportedLayoutMode]
+ -[SBChargingAlertElement platformElementHost]
+ -[SBChargingAlertElement preferredEdgeOutsetsForLayoutMode:suggestedOutsets:maximumOutsets:]
+ -[SBChargingAlertElement preferredLayoutMode]
+ -[SBChargingAlertElement setAlertHost:]
+ -[SBChargingAlertElement setBatteryPercentage:]
+ -[SBChargingAlertElement setDefaultLeadingConstraints:]
+ -[SBChargingAlertElement setDefaultTrailingConstraints:]
+ -[SBChargingAlertElement setDisplayedWithLimitedSize:]
+ -[SBChargingAlertElement setElementHost:]
+ -[SBChargingAlertElement setLayoutHost:]
+ -[SBChargingAlertElement setLayoutMode:reason:]
+ -[SBChargingAlertElement setLeadingBatteryIconPackageView:]
+ -[SBChargingAlertElement setLeadingLabel:]
+ -[SBChargingAlertElement setLimitedSizeLeadingConstraints:]
+ -[SBChargingAlertElement setLimitedSizeTrailingConstraints:]
+ -[SBChargingAlertElement setLowPowerModeEnabled:]
+ -[SBChargingAlertElement setMaximumSupportedLayoutMode:]
+ -[SBChargingAlertElement setMinimalBatteryIconPackageView:]
+ -[SBChargingAlertElement setMinimumSupportedLayoutMode:]
+ -[SBChargingAlertElement setPlatformElementHost:]
+ -[SBChargingAlertElement setPreferredLayoutMode:]
+ -[SBChargingAlertElement setTrailingBatteryIconPackageView:]
+ -[SBChargingAlertElement setTrailingBatteryLabel:]
+ -[SBChargingAlertElement shouldSuppressElementWhileProximityReaderPresent]
+ -[SBChargingAlertElement trailingBatteryIconPackageView]
+ -[SBChargingAlertElement trailingBatteryLabel]
+ -[SBChargingAlertElement trailingView]
+ -[SBChargingAlertElement viewProvider]
+ -[SBCompanionScenePresentation updateContextWithSceneSettings:]
+ -[SBCoverSheetDimmingView updateAlpha:hidingMask:forPresentationValue:]
+ -[SBCoverSheetPositionView minimumDismissScale]
+ -[SBCoverSheetPositionView positionContentForTouchAtLocation:withVelocity:progress:transformMode:forPresentationValue:]
+ -[SBCoverSheetPositionView setMinimumDismissScale:]
+ -[SBCoverSheetPresentationManager _cornerPocketAvailable]
+ -[SBCoverSheetPresentationManager _setupModeDidChange]
+ -[SBCoverSheetPresentationManager _updateDismissalTransformMode]
+ -[SBCoverSheetSlidingViewController _animateToLocation:mode:animatingAlongsideProgress:completion:]
+ -[SBCoverSheetSlidingViewController _animateToLocation:mode:completion:]
+ -[SBCoverSheetSlidingViewController _clockMorphResolvedStatusBarStyle]
+ -[SBCoverSheetSlidingViewController _clockMorphStringForDate:]
+ -[SBCoverSheetSlidingViewController _coversheetClockMetricsForProgress:outCenter:]
+ -[SBCoverSheetSlidingViewController _createClockMorphIfNeeded]
+ -[SBCoverSheetSlidingViewController _crossFadeTickForPresentationValue:]
+ -[SBCoverSheetSlidingViewController _relinquishBackgrounds]
+ -[SBCoverSheetSlidingViewController _removeClockMorph]
+ -[SBCoverSheetSlidingViewController _reparentBackgroundsForScalingDismiss]
+ -[SBCoverSheetSlidingViewController _retargetActiveTransitionAnimationOnProperty:toValue:reason:]
+ -[SBCoverSheetSlidingViewController _setLockScreenContentForState:animated:]
+ -[SBCoverSheetSlidingViewController _storePresentDismissStartPositionTransitioningFromAppeared:]
+ -[SBCoverSheetSlidingViewController _updateClockMorphForDate:]
+ -[SBCoverSheetSlidingViewController _updateClockMorphForProgress:forPresentationValue:]
+ -[SBCoverSheetSlidingViewController _updateMinimumDismissScaleForClockMorph]
+ -[SBCoverSheetSlidingViewController activeTransitionInternalRetargetSetter]
+ -[SBCoverSheetSlidingViewController activeTransitionSubcompletionGenerator]
+ -[SBCoverSheetSlidingViewController clockMorphCrossFadeFluidSettings]
+ -[SBCoverSheetSlidingViewController clockMorphCrossFadeProperty]
+ -[SBCoverSheetSlidingViewController clockMorphDateProvider]
+ -[SBCoverSheetSlidingViewController clockMorphLabel]
+ -[SBCoverSheetSlidingViewController clockMorphMinuteUpdateToken]
+ -[SBCoverSheetSlidingViewController didCommitContentTransition]
+ -[SBCoverSheetSlidingViewController inAppStatusBarHiddenAssertion]
+ -[SBCoverSheetSlidingViewController lockScreenContentVisible]
+ -[SBCoverSheetSlidingViewController presentDismissStartPosition]
+ -[SBCoverSheetSlidingViewController setActiveTransitionInternalRetargetSetter:]
+ -[SBCoverSheetSlidingViewController setActiveTransitionSubcompletionGenerator:]
+ -[SBCoverSheetSlidingViewController setClockMorphCrossFadeFluidSettings:]
+ -[SBCoverSheetSlidingViewController setClockMorphCrossFadeProperty:]
+ -[SBCoverSheetSlidingViewController setClockMorphDateProvider:]
+ -[SBCoverSheetSlidingViewController setClockMorphLabel:]
+ -[SBCoverSheetSlidingViewController setClockMorphMinuteUpdateToken:]
+ -[SBCoverSheetSlidingViewController setDidCommitContentTransition:]
+ -[SBCoverSheetSlidingViewController setInAppStatusBarHiddenAssertion:]
+ -[SBCoverSheetSlidingViewController setLockScreenContentVisible:]
+ -[SBCoverSheetSlidingViewController setPresentDismissStartPosition:]
+ -[SBCoverSheetSlidingViewController setYPositionProperty:]
+ -[SBCoverSheetSlidingViewController yPositionProperty]
+ -[SBDashBoardCameraPageViewController _ensureZStackParticipantForced:]
+ -[SBDashBoardSecureCaptureExtensionHostableEntity _updateKeyboardFocusDeferringRuleForReason:]
+ -[SBDashBoardSecureCaptureExtensionHostableEntity scene:clientDidConnect:]
+ -[SBDashBoardSecureCaptureExtensionHostableEntity sceneDidInvalidate:]
+ -[SBDashBoardStatusBarController initWithWindowScene:]
+ -[SBDeviceApplicationSceneClassicWrapperView _updateClassicLetterboxTouchRegion]
+ -[SBDeviceApplicationSceneHandle _extensionOnlySetPreflightSceneHandle:]
+ -[SBDeviceApplicationSceneHandle preflightSceneHandle]
+ -[SBDeviceApplicationSceneViewController _createPreflightOverlayViewProviderIfNecessary]
+ -[SBDeviceApplicationSceneViewController _createWindowAssociatedSceneOverlayViewProvidersIfNecessary]
+ -[SBDeviceApplicationSceneViewController sceneHandle:didUpdatePreflightSceneHandle:]
+ -[SBFluidSwitcherViewController(Common) _iconManager]
+ -[SBFocusModeAlwaysOnPolicy _didChangeActive:dndState:suspensionState:]
+ -[SBFocusModeBaseAlwaysOnPolicy .cxx_destruct]
+ -[SBFocusModeBaseAlwaysOnPolicy _didChangeActive:dndState:suspensionState:]
+ -[SBFocusModeBaseAlwaysOnPolicy _shouldActivateForDNDState:]
+ -[SBFocusModeBaseAlwaysOnPolicy _updateWithDNDState:]
+ -[SBFocusModeBaseAlwaysOnPolicy _updateWithSuspensionState:]
+ -[SBFocusModeBaseAlwaysOnPolicy _updateWithSuspensionState:dndState:]
+ -[SBFocusModeBaseAlwaysOnPolicy acquirePolicySuspensionAssertionForReason:]
+ -[SBFocusModeBaseAlwaysOnPolicy activateAlwaysOnPolicy]
+ -[SBFocusModeBaseAlwaysOnPolicy analyticsPolicyName]
+ -[SBFocusModeBaseAlwaysOnPolicy analyticsPolicyValue]
+ -[SBFocusModeBaseAlwaysOnPolicy doNotDisturbStateMonitor:didUpdateToState:]
+ -[SBFocusModeBaseAlwaysOnPolicy isAlwaysOnPolicyActive]
+ -[SBFocusModeBaseAlwaysOnPolicy settings:changedValueForKey:]
+ -[SBFocusModeSleepSuppressionPolicy .cxx_destruct]
+ -[SBFocusModeSleepSuppressionPolicy _didChangeActive:dndState:suspensionState:]
+ -[SBFocusModeSleepSuppressionPolicy activateAlwaysOnPolicy]
+ -[SBFocusModeSleepSuppressionPolicy analyticsPolicyName]
+ -[SBGlassBannerTransitionAnimator .cxx_destruct]
+ -[SBGlassBannerTransitionAnimator _clockFollowsAppOrientationForContext:]
+ -[SBGlassBannerTransitionAnimator _clockStatusBarForManager:clockFrame:]
+ -[SBGlassBannerTransitionAnimator _tearDownSwoopTrackers]
+ -[SBGlassBannerTransitionAnimator _topSafeAreaInsetForContext:]
+ -[SBGlassBannerTransitionAnimator dealloc]
+ -[SBGlassBannerTransitionAnimator finalAnimationDidCommitHandler]
+ -[SBGlassBannerTransitionAnimator setFinalAnimationDidCommitHandler:]
+ -[SBHIDUISensorModeController initWithSensorService:mirrorSensorService:]
+ -[SBHomeScreenController homeScreenIconStyleConfigurationForSiri]
+ -[SBHomeScreenController isHomeScreenScaling]
+ -[SBHomeScreenController libraryViewControllerShouldPinFeatherBlurToScreenPosition:]
+ -[SBHomeScreenController setHomeScreenScaling:]
+ -[SBHomeScreenController todayViewControllerShouldPinFeatherBlurToScreenPosition:]
+ -[SBHomeScreenOverlayController isOverlayDisappearing]
+ -[SBHomeScreenOverlayController setOverlayDisappearing:]
+ -[SBHomeScreenService redo]
+ -[SBHomeScreenService undo]
+ -[SBHostProxyClientComponent _updateDisplayConfiguration:]
+ -[SBHostProxyClientComponent initialDisplayConfiguration]
+ -[SBInputUISceneController _currentWindowScene]
+ -[SBInputUISceneController _targetInputUISceneController]
+ -[SBLegacyTodayViewSpotlightPresentableViewController _shouldPinFeatherBlurToScreenPosition]
+ -[SBLegacyTodayViewSpotlightPresentableViewController noteFeatherBlurPinningDidChange]
+ -[SBLockElementViewProvider _setUnlockMode:]
+ -[SBLockElementViewProvider _unlockMode]
+ -[SBLowBatteryAlertElement .cxx_destruct]
+ -[SBLowBatteryAlertElement _extendDismissalTimer]
+ -[SBLowBatteryAlertElement _prefersLargeScreenMetrics]
+ -[SBLowBatteryAlertElement _primaryTextFontSize]
+ -[SBLowBatteryAlertElement _secondaryTextColorForStyle]
+ -[SBLowBatteryAlertElement _secondaryTextForStyle]
+ -[SBLowBatteryAlertElement _updateBatteryContent]
+ -[SBLowBatteryAlertElement _updateLowPowerMode]
+ -[SBLowBatteryAlertElement action]
+ -[SBLowBatteryAlertElement batteryPercentage]
+ -[SBLowBatteryAlertElement customEdgeSpacing]
+ -[SBLowBatteryAlertElement dealloc]
+ -[SBLowBatteryAlertElement dismissalTimer]
+ -[SBLowBatteryAlertElement dodgeSensorAreaOnIntrinsicContentSize]
+ -[SBLowBatteryAlertElement handleElementViewEvent:]
+ -[SBLowBatteryAlertElement horizontalSpacingBetweenLeadingAndCenter]
+ -[SBLowBatteryAlertElement horizontalSpacingBetweenTrailingAndCenter]
+ -[SBLowBatteryAlertElement initWithIdentifier:style:batteryPercentage:lowPowerModeEnabled:action:]
+ -[SBLowBatteryAlertElement isLowPowerModeEnabled]
+ -[SBLowBatteryAlertElement keyColor]
+ -[SBLowBatteryAlertElement minimalBatteryIconPackageView]
+ -[SBLowBatteryAlertElement preferredAlertingDuration:]
+ -[SBLowBatteryAlertElement secondaryContent]
+ -[SBLowBatteryAlertElement setAction:]
+ -[SBLowBatteryAlertElement setBatteryPercentage:]
+ -[SBLowBatteryAlertElement setDismissalTimer:]
+ -[SBLowBatteryAlertElement setLowPowerModeEnabled:]
+ -[SBLowBatteryAlertElement setMinimalBatteryIconPackageView:]
+ -[SBLowBatteryAlertElement setSecondaryContent:]
+ -[SBLowBatteryAlertElement setStyle:]
+ -[SBLowBatteryAlertElement setTrailingLowBatteryStyleIconPackageView:]
+ -[SBLowBatteryAlertElement shouldSuppressElementWhileProximityReaderPresent]
+ -[SBLowBatteryAlertElement style]
+ -[SBLowBatteryAlertElement supportsLimitedSize]
+ -[SBLowBatteryAlertElement trailingLowBatteryStyleIconPackageView]
+ -[SBLowBatteryAlertElement verticalItemSpacing]
+ -[SBLowBatteryAlertElement verticalSpacingBetweenPrimaryAndSecondary]
+ -[SBMenuBarManager _cleanupMenuBarActivationViewForAppStatusBar:]
+ -[SBMenuBarManager _setupTransitionHelperStatusBarIfNeededForTransitioningToPresented:]
+ -[SBMenuBarManager _updateMenuBarActivationViewsWithApplicationName:]
+ -[SBMenuBarManager appStatusBarTapActivationGesture]
+ -[SBMenuBarManager appStatusBarThatContainsActivationView]
+ -[SBMenuBarManager currentMenuBarRecipientScene]
+ -[SBMenuBarManager isMenuBarDismissing]
+ -[SBMenuBarManager menuBarActivationViewInAppStatusBar]
+ -[SBMenuBarManager menuBarActivationViewInSystemStatusBar]
+ -[SBMenuBarManager setAppStatusBarTapActivationGesture:]
+ -[SBMenuBarManager setAppStatusBarThatContainsActivationView:]
+ -[SBMenuBarManager setCurrentMenuBarRecipientScene:]
+ -[SBMenuBarManager setMenuBarActivationViewInAppStatusBar:]
+ -[SBMenuBarManager setMenuBarActivationViewInSystemStatusBar:]
+ -[SBMenuBarManager setMenuBarDismissing:]
+ -[SBMenuBarManager setSystemStatusBarTapActivationGesture:]
+ -[SBMenuBarManager setTransitionOnlyHelperStatusBar:]
+ -[SBMenuBarManager statusBarPartForMenuBarWithDesiredVisibility:atLevel:]
+ -[SBMenuBarManager systemStatusBarTapActivationGesture]
+ -[SBMenuBarManager transitionOnlyHelperStatusBar]
+ -[SBMousePointerManager multiDisplayUserInteractionCoordinator:updatedActiveWindowScene:]
+ -[SBNonInteractiveDisplayController scene:didUpdateSettings:]
+ -[SBNotificationBannerDestination _shouldAmbientSuppressBannerForNotificationRequest:]
+ -[SBNotificationCarPlayDestination _carPlayLaunchPolicyForNotificationRequest:]
+ -[SBNotificationCarPlayDestination _removeNotificationRequestFromPendingAVSessionWithIdentifier:]
+ -[SBNotificationCarPlayDestination _shouldDeactivateSiriSessionForNotificationRequest:bannerRevocationReason:]
+ -[SBNotificationCarPlayDestination presentableDidAppearAsBanner:]
+ -[SBPhysicalButtonSceneOverrideManager initWithSceneManager:volumeControl:]
+ -[SBRecordingIndicatorManager _invalidateWithReason:]
+ -[SBRecordingIndicatorManager invalidate]
+ -[SBRecordingIndicatorViewController _invalidate]
+ -[SBRecordingIndicatorViewController invalidate]
+ -[SBSAContainerViewDescription _setElevationStyle:]
+ -[SBSAContainerViewDescription elevationStyle]
+ -[SBSAContainerViewDescriptionMutator elevationStyle]
+ -[SBSAContainerViewDescriptionMutator setElevationStyle:]
+ -[SBSafeAreaResolverHostComponent delegate]
+ -[SBSafeAreaResolverHostComponent setDelegate:]
+ -[SBSceneBarPositionResolverHostComponent _isEligibleHostedScene:]
+ -[SBSceneBarPositionResolverHostComponent _reevaluateBarPositionForScene:]
+ -[SBSceneBarPositionResolverHostComponent scene:didUpdateSettings:]
+ -[SBSceneBarPositionResolverHostComponent setScene:]
+ -[SBSceneDestructionConfirmationOverlayViewProvider .cxx_destruct]
+ -[SBSceneDestructionConfirmationOverlayViewProvider _activateIfPossible]
+ -[SBSceneDestructionConfirmationOverlayViewProvider _closureConfirmation]
+ -[SBSceneDestructionConfirmationOverlayViewProvider _finalizeSceneSessionWithActionIdentifier:completion:]
+ -[SBSceneDestructionConfirmationOverlayViewProvider _realOverlayViewController]
+ -[SBSceneDestructionConfirmationOverlayViewProvider _tearDownConfirmationViewController]
+ -[SBSceneDestructionConfirmationOverlayViewProvider confirmationViewController:didFinishWithResult:chosenAction:]
+ -[SBSceneDestructionConfirmationOverlayViewProvider confirmationViewControllerDidFinishDismissAnimation:]
+ -[SBSceneDestructionConfirmationOverlayViewProvider confirmationViewController]
+ -[SBSceneDestructionConfirmationOverlayViewProvider contentWantsSimplifiedOrientationBehavior]
+ -[SBSceneDestructionConfirmationOverlayViewProvider dealloc]
+ -[SBSceneDestructionConfirmationOverlayViewProvider initWithSceneHandle:delegate:]
+ -[SBSceneDestructionConfirmationOverlayViewProvider invalidate]
+ -[SBSceneDestructionConfirmationOverlayViewProvider pendingCompletionHandler]
+ -[SBSceneDestructionConfirmationOverlayViewProvider priority]
+ -[SBSceneDestructionConfirmationOverlayViewProvider requestConfirmationWithCompletionHandler:]
+ -[SBSceneDestructionConfirmationOverlayViewProvider sceneHandle:didCreateScene:]
+ -[SBSceneDestructionConfirmationOverlayViewProvider setConfirmationViewController:]
+ -[SBSceneDestructionConfirmationOverlayViewProvider setPendingCompletionHandler:]
+ -[SBSceneDestructionConfirmationOverlayViewProvider shouldSuppressKeyboard]
+ -[SBSceneDestructionConfirmationOverlayViewProvider wantsResignActiveAssertion]
+ -[SBSceneDestructionConfirmationViewController .cxx_destruct]
+ -[SBSceneDestructionConfirmationViewController _dismissAlertAndFadeDimming]
+ -[SBSceneDestructionConfirmationViewController _finishWithResult:chosenAction:]
+ -[SBSceneDestructionConfirmationViewController _handleDimmingTap:]
+ -[SBSceneDestructionConfirmationViewController _presentConfirmationAlert]
+ -[SBSceneDestructionConfirmationViewController configuration]
+ -[SBSceneDestructionConfirmationViewController confirmationDelegate]
+ -[SBSceneDestructionConfirmationViewController hasPresented]
+ -[SBSceneDestructionConfirmationViewController initWithConfiguration:delegate:]
+ -[SBSceneDestructionConfirmationViewController setConfiguration:]
+ -[SBSceneDestructionConfirmationViewController setConfirmationDelegate:]
+ -[SBSceneDestructionConfirmationViewController setPresented:]
+ -[SBSceneDestructionConfirmationViewController viewDidAppear:]
+ -[SBSceneRegionsUpdater _statusBarOcclusionFrame]
+ -[SBSceneRegionsUpdater statusBarManager:didUpdateAvoidanceFrameForStatusBar:withAnimationSettings:]
+ -[SBSceneRegionsUpdater statusBarManager:didUpdateOcclusionFrameForStatusBar:]
+ -[SBScreenSharingOverlayUISceneController _applyRootWindowTransform]
+ -[SBSpotlightDelegateManager latestSpotlightRemoteViewController]
+ -[SBSpotlightDelegateManager latestSpotlightScene]
+ -[SBSpotlightDelegateManager setLatestSpotlightRemoteViewController:]
+ -[SBSpotlightDelegateManager setLatestSpotlightScene:]
+ -[SBSwitcherController _handleReturnToPreviousSizeCommand:]
+ -[SBSwitcherController systemStatusBarForAppEnvironment]
+ -[SBSystemApertureContainerView _updateElevatedGainMapRenderingConfiguration]
+ -[SBSystemApertureContainerView elevationStyle]
+ -[SBSystemApertureContainerView setElevationStyle:]
+ -[SBSystemApertureContainerView(PreferencesStackSupport) backgroundGroupingView]
+ -[SBSystemApertureContainerView(PreferencesStackSupport) elevatedSubBackgroundGroupingView]
+ -[SBSystemApertureContainerView(PreferencesStackSupport) subBackgroundGroupingView]
+ -[SBSystemApertureCurtainViewController highLevelBackgroundParent]
+ -[SBSystemApertureCurtainViewController highLevelSubBackgroundParent]
+ -[SBSystemApertureSettings landscapeUsesPortraitElementPositioning]
+ -[SBSystemApertureSettings setLandscapeUsesPortraitElementPositioning:]
+ -[SBSystemApertureViewController parentViewForElevatedSubBackgroundForSystemApertureContainerView:]
+ -[SBSystemApertureViewController portalFrameReferenceCoordinateSpace]
+ -[SBSystemUISceneDefaultPresenter _presentScene:onWindowScene:viewController:]
+ -[SBSystemUISceneDefaultPresenter _presentScene:onWindowScene:viewController:viewControllerBuilderBlock:]
+ -[SBTodayViewController noteFeatherBlurPinningDidChange]
+ -[SBTodayViewController spotlightPresenterShouldPinFeatherBlurToScreenPosition:]
+ -[SBTodayViewSpotlightPresenter _shouldPinFeatherBlurToScreenPosition]
+ -[SBTodayViewSpotlightPresenter legacyTodayViewSpotlightPresentableViewControllerShouldPinFeatherBlurToScreenPosition:]
+ -[SBTodayViewSpotlightPresenter noteFeatherBlurPinningDidChange]
+ -[SBTouchRegionManager _queue_classicLetterboxInnerFrameForElement:]
+ -[SBTouchRegionManager _queue_layoutHasClassicLetterboxedElement:]
+ -[SBTouchRegionManager setClassicLetterboxInnerFrame:forSceneIdentifier:]
+ -[SBUntrustedURLLaunchThrottle .cxx_destruct]
+ -[SBUntrustedURLLaunchThrottle _shouldThrottleRequestForRequestedBundleID:atTime:]
+ -[SBUntrustedURLLaunchThrottle init]
+ -[SBUntrustedURLLaunchThrottle shouldThrottleRequestForRequestedBundleID:options:]
+ -[SBUserAgent deviceIsThermallyBlocked]
+ -[SpringBoard _handleReturnToPreviousSizeCommand:]
+ GCC_except_table114
+ GCC_except_table141
+ GCC_except_table187
+ GCC_except_table201
+ GCC_except_table243
+ GCC_except_table285
+ GCC_except_table298
+ GCC_except_table313
+ GCC_except_table384
+ GCC_except_table386
+ GCC_except_table399
+ GCC_except_table445
+ GCC_except_table548
+ GCC_except_table571
+ GCC_except_table573
+ _BSActionErrorDomain
+ _MobileInBoxUpdateLibraryCore.frameworkLibrary
+ _OBJC_CLASS_$_GMAvailabilityWrapper
+ _OBJC_CLASS_$_SASBookendAnimationConfiguration
+ _OBJC_CLASS_$_SBChargingAlertElement
+ _OBJC_CLASS_$_SBFBacklightSceneHostEnvironmentProviderEntry
+ _OBJC_CLASS_$_SBFocusModeBaseAlwaysOnPolicy
+ _OBJC_CLASS_$_SBFocusModeSleepSuppressionPolicy
+ _OBJC_CLASS_$_SBLowBatteryAlertElement
+ _OBJC_CLASS_$_SBSUIAXUIServerReachabilityDisablingSceneExtension
+ _OBJC_CLASS_$_SBSceneBarPositionResolverHostComponent
+ _OBJC_CLASS_$_SBSceneBarPositionResolverSceneExtension
+ _OBJC_CLASS_$_SBSceneBarPositionResolverUtility
+ _OBJC_CLASS_$_SBSceneDestructionConfirmationOverlayViewProvider
+ _OBJC_CLASS_$_SBSceneDestructionConfirmationViewController
+ _OBJC_CLASS_$_SBUntrustedURLLaunchThrottle
+ _OBJC_CLASS_$_STStatusBarDataEntry
+ _OBJC_CLASS_$_UISUserInterfaceStyleMode
+ _OBJC_CLASS_$__UIFinalizeSceneSessionAction
+ _OBJC_IVAR_$_SBAccessibilityUIServerUISceneController._reachabilityDisablingFeaturePolicyComponent
+ _OBJC_IVAR_$_SBAmbientIdleTimerController._backlightController
+ _OBJC_IVAR_$_SBAmbientIdleTimerController._onAC
+ _OBJC_IVAR_$_SBAppResizingCoordinator._lastInteractedResizableSceneHandleProvider
+ _OBJC_IVAR_$_SBAssistantIslandStageCoordinator._idleTimerCoordinator
+ _OBJC_IVAR_$_SBAssistantIslandStageCoordinator._lastPushedHasIdleTimerBehaviors
+ _OBJC_IVAR_$_SBAssistantIslandStageGestureManager._defaultPresentGestureEdgeRegionSize
+ _OBJC_IVAR_$_SBBannerCustomTransitioningDelegate._finalAnimationDidCommitHandler
+ _OBJC_IVAR_$_SBBannerManager._insetSuspendedForPresent
+ _OBJC_IVAR_$_SBBannerManager._pendingMinimumTopInsetInvalidation
+ _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_dismissGestureOvershootInsetMinScale
+ _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_dismissGestureOvershootMaxX
+ _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_dismissGestureOvershootReferenceInset
+ _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_dismissGestureOvershootSpringX
+ _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_dismissGestureOvershootVelocityScaleX
+ _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_dismissGestureOvershootVelocityScaleY
+ _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_dismissGestureOvershootX
+ _OBJC_IVAR_$_SBChargingAlertElement._alertHost
+ _OBJC_IVAR_$_SBChargingAlertElement._batteryPercentage
+ _OBJC_IVAR_$_SBChargingAlertElement._clientIdentifier
+ _OBJC_IVAR_$_SBChargingAlertElement._defaultLeadingConstraints
+ _OBJC_IVAR_$_SBChargingAlertElement._defaultTrailingConstraints
+ _OBJC_IVAR_$_SBChargingAlertElement._displayedWithLimitedSize
+ _OBJC_IVAR_$_SBChargingAlertElement._elementHost
+ _OBJC_IVAR_$_SBChargingAlertElement._elementIdentifier
+ _OBJC_IVAR_$_SBChargingAlertElement._keyColor
+ _OBJC_IVAR_$_SBChargingAlertElement._layoutHost
+ _OBJC_IVAR_$_SBChargingAlertElement._layoutMode
+ _OBJC_IVAR_$_SBChargingAlertElement._leadingBatteryIconPackageView
+ _OBJC_IVAR_$_SBChargingAlertElement._leadingLabel
+ _OBJC_IVAR_$_SBChargingAlertElement._leadingView
+ _OBJC_IVAR_$_SBChargingAlertElement._limitedSizeLeadingConstraints
+ _OBJC_IVAR_$_SBChargingAlertElement._limitedSizeTrailingConstraints
+ _OBJC_IVAR_$_SBChargingAlertElement._lowPowerModeEnabled
+ _OBJC_IVAR_$_SBChargingAlertElement._maximumSupportedLayoutMode
+ _OBJC_IVAR_$_SBChargingAlertElement._minimalBatteryIconPackageView
+ _OBJC_IVAR_$_SBChargingAlertElement._minimalView
+ _OBJC_IVAR_$_SBChargingAlertElement._minimumSupportedLayoutMode
+ _OBJC_IVAR_$_SBChargingAlertElement._platformElementHost
+ _OBJC_IVAR_$_SBChargingAlertElement._preferredLayoutMode
+ _OBJC_IVAR_$_SBChargingAlertElement._trailingBatteryIconPackageView
+ _OBJC_IVAR_$_SBChargingAlertElement._trailingBatteryLabel
+ _OBJC_IVAR_$_SBChargingAlertElement._trailingView
+ _OBJC_IVAR_$_SBCoverSheetPositionView._minimumDismissScale
+ _OBJC_IVAR_$_SBCoverSheetSlidingViewController._activeTransitionInternalRetargetSetter
+ _OBJC_IVAR_$_SBCoverSheetSlidingViewController._activeTransitionSubcompletionGenerator
+ _OBJC_IVAR_$_SBCoverSheetSlidingViewController._clockMorphCrossFadeFluidSettings
+ _OBJC_IVAR_$_SBCoverSheetSlidingViewController._clockMorphCrossFadeProperty
+ _OBJC_IVAR_$_SBCoverSheetSlidingViewController._clockMorphDateProvider
+ _OBJC_IVAR_$_SBCoverSheetSlidingViewController._clockMorphLabel
+ _OBJC_IVAR_$_SBCoverSheetSlidingViewController._clockMorphMinuteUpdateToken
+ _OBJC_IVAR_$_SBCoverSheetSlidingViewController._didCommitContentTransition
+ _OBJC_IVAR_$_SBCoverSheetSlidingViewController._inAppStatusBarHiddenAssertion
+ _OBJC_IVAR_$_SBCoverSheetSlidingViewController._lockScreenContentVisible
+ _OBJC_IVAR_$_SBCoverSheetSlidingViewController._pendingHostingAssertion
+ _OBJC_IVAR_$_SBCoverSheetSlidingViewController._presentDismissStartPosition
+ _OBJC_IVAR_$_SBCoverSheetSlidingViewController._yPositionProperty
+ _OBJC_IVAR_$_SBDashBoardSecureCaptureExtensionHostableEntity._extensionScene
+ _OBJC_IVAR_$_SBDashBoardSecureCaptureExtensionHostableEntity._extensionSceneHostingWindowScene
+ _OBJC_IVAR_$_SBDashBoardSecureCaptureExtensionHostableEntity._keyboardFocusDeferringRule
+ _OBJC_IVAR_$_SBDashBoardStatusBarController._hideMenuBarStatusBarPartAssertion
+ _OBJC_IVAR_$_SBDashBoardStatusBarController._statusBarsToVisibilityAssertions
+ _OBJC_IVAR_$_SBDashBoardStatusBarController._windowScene
+ _OBJC_IVAR_$_SBDeviceApplicationSceneHandle._preflightSceneHandle
+ _OBJC_IVAR_$_SBDeviceApplicationSceneViewController._preflightOverlayViewProvider
+ _OBJC_IVAR_$_SBDeviceApplicationSceneViewController._windowAssociatedOverlayViewProviders
+ _OBJC_IVAR_$_SBFocusModeBaseAlwaysOnPolicy._active
+ _OBJC_IVAR_$_SBFocusModeBaseAlwaysOnPolicy._alwaysOnPolicyActive
+ _OBJC_IVAR_$_SBFocusModeBaseAlwaysOnPolicy._dndStateMonitor
+ _OBJC_IVAR_$_SBFocusModeBaseAlwaysOnPolicy._policySettings
+ _OBJC_IVAR_$_SBFocusModeBaseAlwaysOnPolicy._suspensionAssertions
+ _OBJC_IVAR_$_SBFocusModeSleepSuppressionPolicy._sleepSuppressionAssertion
+ _OBJC_IVAR_$_SBGlassBannerTransitionAnimator._dismissFxCallback
+ _OBJC_IVAR_$_SBGlassBannerTransitionAnimator._dismissFxProgress
+ _OBJC_IVAR_$_SBGlassBannerTransitionAnimator._finalAnimationDidCommitHandler
+ _OBJC_IVAR_$_SBGlassBannerTransitionAnimator._swoopTrailCallback
+ _OBJC_IVAR_$_SBGlassBannerTransitionAnimator._swoopTrailProgress
+ _OBJC_IVAR_$_SBHIDUISensorModeController._mirrorProximityDetectionModeAssertion
+ _OBJC_IVAR_$_SBHIDUISensorModeController._mirrorSensorModeAssertion
+ _OBJC_IVAR_$_SBHIDUISensorModeController._mirrorSensorService
+ _OBJC_IVAR_$_SBHomeScreenController._homeScreenScaling
+ _OBJC_IVAR_$_SBHomeScreenOverlayController._overlayDisappearing
+ _OBJC_IVAR_$_SBHostProxyClientComponent._initialDisplayConfiguration
+ _OBJC_IVAR_$_SBLowBatteryAlertElement._action
+ _OBJC_IVAR_$_SBLowBatteryAlertElement._batteryPercentage
+ _OBJC_IVAR_$_SBLowBatteryAlertElement._dismissalTimer
+ _OBJC_IVAR_$_SBLowBatteryAlertElement._keyColor
+ _OBJC_IVAR_$_SBLowBatteryAlertElement._lowPowerModeEnabled
+ _OBJC_IVAR_$_SBLowBatteryAlertElement._minimalBatteryIconPackageView
+ _OBJC_IVAR_$_SBLowBatteryAlertElement._secondaryContent
+ _OBJC_IVAR_$_SBLowBatteryAlertElement._style
+ _OBJC_IVAR_$_SBLowBatteryAlertElement._trailingLowBatteryStyleIconPackageView
+ _OBJC_IVAR_$_SBMainWorkspace._untrustedURLLaunchThrottle
+ _OBJC_IVAR_$_SBMenuBarManager.__useStatusBarDataForMenu
+ _OBJC_IVAR_$_SBMenuBarManager._appStatusBarTapActivationGesture
+ _OBJC_IVAR_$_SBMenuBarManager._appStatusBarThatContainsActivationView
+ _OBJC_IVAR_$_SBMenuBarManager._currentMenuBarRecipientScene
+ _OBJC_IVAR_$_SBMenuBarManager._menuBarActivationViewInAppStatusBar
+ _OBJC_IVAR_$_SBMenuBarManager._menuBarActivationViewInSystemStatusBar
+ _OBJC_IVAR_$_SBMenuBarManager._menuBarDismissing
+ _OBJC_IVAR_$_SBMenuBarManager._systemStatusBarTapActivationGesture
+ _OBJC_IVAR_$_SBMenuBarManager._transitionOnlyHelperStatusBar
+ _OBJC_IVAR_$_SBMousePointerManager._didAddActiveDisplayObserver
+ _OBJC_IVAR_$_SBRecordingIndicatorManager._invalidated
+ _OBJC_IVAR_$_SBRecordingIndicatorViewController._invalidated
+ _OBJC_IVAR_$_SBSAContainerViewDescription._elevationStyle
+ _OBJC_IVAR_$_SBSARenderingAndCloningPreferencesProvider._previousIndicatorContainerElevationStyle
+ _OBJC_IVAR_$_SBSafeAreaResolverHostComponent._delegate
+ _OBJC_IVAR_$_SBSceneDestructionConfirmationOverlayViewProvider._confirmationViewController
+ _OBJC_IVAR_$_SBSceneDestructionConfirmationOverlayViewProvider._pendingCompletionHandler
+ _OBJC_IVAR_$_SBSceneDestructionConfirmationViewController._configuration
+ _OBJC_IVAR_$_SBSceneDestructionConfirmationViewController._confirmationDelegate
+ _OBJC_IVAR_$_SBSceneDestructionConfirmationViewController._presented
+ _OBJC_IVAR_$_SBScreenSharingOverlayUISceneController._appliedRootWindowTransform
+ _OBJC_IVAR_$_SBSpotlightDelegateManager._latestSpotlightRemoteViewController
+ _OBJC_IVAR_$_SBSpotlightDelegateManager._latestSpotlightScene
+ _OBJC_IVAR_$_SBSystemApertureContainerView._elevatedGainMapView
+ _OBJC_IVAR_$_SBSystemApertureContainerView._elevatedSubBackgroundGroupingView
+ _OBJC_IVAR_$_SBSystemApertureContainerView._elevationStyle
+ _OBJC_IVAR_$_SBSystemApertureCurtainViewController._highLevelBackgroundParent
+ _OBJC_IVAR_$_SBSystemApertureCurtainViewController._highLevelSubBackgroundParent
+ _OBJC_IVAR_$_SBSystemApertureSettings._landscapeUsesPortraitElementPositioning
+ _OBJC_IVAR_$_SBTouchRegionManager._queue_classicLetterboxInnerFramesByIdentifier
+ _OBJC_IVAR_$_SBUntrustedURLLaunchThrottle._entries
+ _OBJC_METACLASS_$_SBChargingAlertElement
+ _OBJC_METACLASS_$_SBFocusModeBaseAlwaysOnPolicy
+ _OBJC_METACLASS_$_SBFocusModeSleepSuppressionPolicy
+ _OBJC_METACLASS_$_SBLowBatteryAlertElement
+ _OBJC_METACLASS_$_SBSceneBarPositionResolverHostComponent
+ _OBJC_METACLASS_$_SBSceneBarPositionResolverSceneExtension
+ _OBJC_METACLASS_$_SBSceneBarPositionResolverUtility
+ _OBJC_METACLASS_$_SBSceneDestructionConfirmationOverlayViewProvider
+ _OBJC_METACLASS_$_SBSceneDestructionConfirmationViewController
+ _OBJC_METACLASS_$_SBUntrustedURLLaunchThrottle
+ _SBAssistantIslandWorkspaceEnhancedSiriInputDidChange
+ _SBFAlwaysOnDisplayPolicyIdentifierFocusModeSleepSuppression
+ _SBLogAppRestrictionsOverlay
+ _SBPowerBatteryStateForConditions
+ _SBPowerKeyColorForBatteryState
+ _SBPowerUpdateBatteryFillForPackageView
+ _SBPowerUpdateMinimalBatteryPercentageTextLayer
+ _SBSAPinViewToOtherView
+ _SBSceneDestructionConfirmationErrorDomain
+ _SBSceneDestructionConfirmationUserCancelledError
+ _SBStringFromSystemApertureContainerElevationStyle
+ _SBTraitsParticipantRoleCoverSheetGrabber
+ _SBWindowSceneDidUpdateReachabilityControllerNotification
+ _SBWorkspaceDestroyApplicationSceneHandlesWithConfirmation
+ _UISUserInterfaceStyleModeValueIsAutomatic
+ _UIViewGlassGetTintAmount
+ __OBJC_$_CLASS_METHODS_SBAppResizeWorkspaceTransaction
+ __OBJC_$_CLASS_METHODS_SBChainableModifier(RuntimeProviding|WindowingModifier|SwitcherModifier)
+ __OBJC_$_CLASS_METHODS_SBFocusModeBaseAlwaysOnPolicy
+ __OBJC_$_CLASS_METHODS_SBFocusModeSleepSuppressionPolicy
+ __OBJC_$_CLASS_METHODS_SBSceneBarPositionResolverSceneExtension
+ __OBJC_$_CLASS_METHODS_SBSceneBarPositionResolverUtility
+ __OBJC_$_CLASS_METHODS_SBSceneDestructionConfirmationOverlayViewProvider
+ __OBJC_$_CLASS_PROP_LIST_SBFocusModeBaseAlwaysOnPolicy
+ __OBJC_$_INSTANCE_METHODS_FBScene(SBVisibilitySceneExtension_ForSceneManager|SBSUIHomeScreenIconStyle|LocalSynchronous|CompanionSceneHost|CompanionSceneHost_Internal|CompanionSceneHost_Testing|SBWindowSceneAccessorySceneProvider|SBProductivityGestureDestination|SafeAreaResolverExtensionDelegate|SBDynamicMemoryControllingHost|SBHostedScenePolicy)
+ __OBJC_$_INSTANCE_METHODS_SBChainableModifier(RuntimeProviding|WindowingModifier|SwitcherModifier)
+ __OBJC_$_INSTANCE_METHODS_SBChainableModifierEvent(SBWindowingModifierActivity|SBSwitcherModifierEvent)
+ __OBJC_$_INSTANCE_METHODS_SBChargingAlertElement
+ __OBJC_$_INSTANCE_METHODS_SBFocusModeBaseAlwaysOnPolicy
+ __OBJC_$_INSTANCE_METHODS_SBFocusModeSleepSuppressionPolicy
+ __OBJC_$_INSTANCE_METHODS_SBLowBatteryAlertElement
+ __OBJC_$_INSTANCE_METHODS_SBSceneBarPositionResolverHostComponent
+ __OBJC_$_INSTANCE_METHODS_SBSceneDestructionConfirmationOverlayViewProvider
+ __OBJC_$_INSTANCE_METHODS_SBSceneDestructionConfirmationViewController
+ __OBJC_$_INSTANCE_METHODS_SBUntrustedURLLaunchThrottle
+ __OBJC_$_INSTANCE_METHODS_SBWindowingModifierActivity(TransitionEvent|StripChangedModifierActivity|GestureEvent)
+ __OBJC_$_INSTANCE_VARIABLES_SBAccessibilityUIServerUISceneController
+ __OBJC_$_INSTANCE_VARIABLES_SBChargingAlertElement
+ __OBJC_$_INSTANCE_VARIABLES_SBFocusModeBaseAlwaysOnPolicy
+ __OBJC_$_INSTANCE_VARIABLES_SBFocusModeSleepSuppressionPolicy
+ __OBJC_$_INSTANCE_VARIABLES_SBLowBatteryAlertElement
+ __OBJC_$_INSTANCE_VARIABLES_SBSceneDestructionConfirmationOverlayViewProvider
+ __OBJC_$_INSTANCE_VARIABLES_SBSceneDestructionConfirmationViewController
+ __OBJC_$_INSTANCE_VARIABLES_SBUntrustedURLLaunchThrottle
+ __OBJC_$_PROP_LIST_SBChargingAlertElement
+ __OBJC_$_PROP_LIST_SBFocusModeBaseAlwaysOnPolicy
+ __OBJC_$_PROP_LIST_SBLowBatteryAlertElement
+ __OBJC_$_PROP_LIST_SBSceneDestructionConfirmationOverlayViewProvider
+ __OBJC_$_PROP_LIST_SBSceneDestructionConfirmationViewController
+ __OBJC_$_PROP_LIST_SBSceneRegionsUpdater
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SBHLibraryViewControllerDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SBHTodayViewControllerDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SBLegacyTodayViewSpotlightPresentableViewControllerDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SBTodayViewSpotlightPresenterDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT__UISceneAccessoryContainerHostObserver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT__UISceneAccessoryInterestHostObserver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SBFBacklightSceneHostEnvironmentProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SBSafeAreaResolverExtensionDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SBSceneDestructionConfirmationViewControllerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SBFBacklightSceneHostEnvironmentProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SBSafeAreaResolverExtensionDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SBSceneDestructionConfirmationViewControllerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES__UISceneAccessoryContainerHostObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES__UISceneAccessoryInterestHostObserver
+ __OBJC_$_PROTOCOL_REFS_SBFBacklightSceneHostEnvironmentProviding
+ __OBJC_$_PROTOCOL_REFS_SBLegacyTodayViewSpotlightPresentableViewControllerDelegate
+ __OBJC_$_PROTOCOL_REFS_SBSafeAreaResolverExtensionDelegate
+ __OBJC_$_PROTOCOL_REFS_SBSceneDestructionConfirmationViewControllerDelegate
+ __OBJC_$_PROTOCOL_REFS__UISceneAccessoryContainerHostObserver
+ __OBJC_$_PROTOCOL_REFS__UISceneAccessoryInterestHostObserver
+ __OBJC_CLASS_PROTOCOLS_$_FBScene(SBVisibilitySceneExtension_ForSceneManager|SBSUIHomeScreenIconStyle|LocalSynchronous|CompanionSceneHost|CompanionSceneHost_Internal|CompanionSceneHost_Testing|SBWindowSceneAccessorySceneProvider|SBProductivityGestureDestination|SafeAreaResolverExtensionDelegate|SBDynamicMemoryControllingHost|SBHostedScenePolicy)
+ __OBJC_CLASS_PROTOCOLS_$_SBChargingAlertElement
+ __OBJC_CLASS_PROTOCOLS_$_SBFocusModeBaseAlwaysOnPolicy
+ __OBJC_CLASS_PROTOCOLS_$_SBLowBatteryAlertElement
+ __OBJC_CLASS_PROTOCOLS_$_SBSceneDestructionConfirmationOverlayViewProvider
+ __OBJC_CLASS_PROTOCOLS_$_SBSceneRegionsUpdater
+ __OBJC_CLASS_RO_$_SBChargingAlertElement
+ __OBJC_CLASS_RO_$_SBFocusModeBaseAlwaysOnPolicy
+ __OBJC_CLASS_RO_$_SBFocusModeSleepSuppressionPolicy
+ __OBJC_CLASS_RO_$_SBLowBatteryAlertElement
+ __OBJC_CLASS_RO_$_SBSceneBarPositionResolverHostComponent
+ __OBJC_CLASS_RO_$_SBSceneBarPositionResolverSceneExtension
+ __OBJC_CLASS_RO_$_SBSceneBarPositionResolverUtility
+ __OBJC_CLASS_RO_$_SBSceneDestructionConfirmationOverlayViewProvider
+ __OBJC_CLASS_RO_$_SBSceneDestructionConfirmationViewController
+ __OBJC_CLASS_RO_$_SBUntrustedURLLaunchThrottle
+ __OBJC_LABEL_PROTOCOL_$_SBFBacklightSceneHostEnvironmentProviding
+ __OBJC_LABEL_PROTOCOL_$_SBSafeAreaResolverExtensionDelegate
+ __OBJC_LABEL_PROTOCOL_$_SBSceneDestructionConfirmationViewControllerDelegate
+ __OBJC_LABEL_PROTOCOL_$__UISceneAccessoryContainerHostObserver
+ __OBJC_LABEL_PROTOCOL_$__UISceneAccessoryInterestHostObserver
+ __OBJC_METACLASS_RO_$_SBChargingAlertElement
+ __OBJC_METACLASS_RO_$_SBFocusModeBaseAlwaysOnPolicy
+ __OBJC_METACLASS_RO_$_SBFocusModeSleepSuppressionPolicy
+ __OBJC_METACLASS_RO_$_SBLowBatteryAlertElement
+ __OBJC_METACLASS_RO_$_SBSceneBarPositionResolverHostComponent
+ __OBJC_METACLASS_RO_$_SBSceneBarPositionResolverSceneExtension
+ __OBJC_METACLASS_RO_$_SBSceneBarPositionResolverUtility
+ __OBJC_METACLASS_RO_$_SBSceneDestructionConfirmationOverlayViewProvider
+ __OBJC_METACLASS_RO_$_SBSceneDestructionConfirmationViewController
+ __OBJC_METACLASS_RO_$_SBUntrustedURLLaunchThrottle
+ __OBJC_PROTOCOL_$_SBFBacklightSceneHostEnvironmentProviding
+ __OBJC_PROTOCOL_$_SBSafeAreaResolverExtensionDelegate
+ __OBJC_PROTOCOL_$_SBSceneDestructionConfirmationViewControllerDelegate
+ __OBJC_PROTOCOL_$__UISceneAccessoryContainerHostObserver
+ __OBJC_PROTOCOL_$__UISceneAccessoryInterestHostObserver
+ __SBGlassBannerAnimateLayerProperty
+ __ZNSt3__114__split_bufferINS_6vectorI11BezierCurveNS_9allocatorIS2_EEEERNS3_IS5_EEE17__destruct_at_endB9fqn220106EPS5_
+ __ZNSt3__114__split_bufferINS_6vectorI9PathPointNS_9allocatorIS2_EEEERNS3_IS5_EEE17__destruct_at_endB9fqn220106EPS5_
+ __ZNSt3__119__allocate_at_leastB9fqn220106INS_9allocatorI11BezierCurveEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqn220106INS_9allocatorI9PathPointEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqn220106INS_9allocatorINS_6vectorI11BezierCurveNS1_IS3_EEEEEENS_16allocator_traitsIS6_EEEENS_19__allocation_resultINT0_7pointerENSA_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqn220106INS_9allocatorINS_6vectorI9PathPointNS1_IS3_EEEEEENS_16allocator_traitsIS6_EEEENS_19__allocation_resultINT0_7pointerENSA_9size_typeEEERT_m
+ __ZNSt3__16vectorI11BezierCurveNS_9allocatorIS1_EEE11__vallocateB9fqn220106Em
+ __ZNSt3__16vectorI11BezierCurveNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorI11BezierCurveNS_9allocatorIS1_EEEC2B9fqn220106ERKS4_
+ __ZNSt3__16vectorI9PathPointNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorINS0_I11BezierCurveNS_9allocatorIS1_EEEENS2_IS4_EEE16__destroy_vectorclB9fqn220106Ev
+ __ZNSt3__16vectorINS0_I11BezierCurveNS_9allocatorIS1_EEEENS2_IS4_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorINS0_I11BezierCurveNS_9allocatorIS1_EEEENS2_IS4_EEE5clearB9fqn220106Ev
+ __ZNSt3__16vectorINS0_I9PathPointNS_9allocatorIS1_EEEENS2_IS4_EEE16__destroy_vectorclB9fqn220106Ev
+ __ZNSt3__16vectorINS0_I9PathPointNS_9allocatorIS1_EEEENS2_IS4_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorINS0_I9PathPointNS_9allocatorIS1_EEEENS2_IS4_EEE5clearB9fqn220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqn220106v
+ ___106-[SBSceneDestructionConfirmationOverlayViewProvider _finalizeSceneSessionWithActionIdentifier:completion:]_block_invoke
+ ___113-[SBSceneDestructionConfirmationOverlayViewProvider confirmationViewController:didFinishWithResult:chosenAction:]_block_invoke
+ ___31+[SBAppLayout genericAppLayout]_block_invoke
+ ___33-[SpringBoard scenesPassingTest:]_block_invoke_2
+ ___35-[SpringBoard sceneWithIdentifier:]_block_invoke_3
+ ___38-[SpringBoard sceneFromIdentityToken:]_block_invoke_3
+ ___40-[SBSAContainerViewDescription isEqual:]_block_invoke_13
+ ___47-[SBLowBatteryAlertElement _updateLowPowerMode]_block_invoke
+ ___49-[SBLowBatteryAlertElement _extendDismissalTimer]_block_invoke
+ ___55-[SBFocusModeBaseAlwaysOnPolicy activateAlwaysOnPolicy]_block_invoke
+ ___56-[SBGlassBannerTransitionAnimator prepareForTransition:]_block_invoke_2
+ ___56-[SBGlassBannerTransitionAnimator prepareForTransition:]_block_invoke_3
+ ___56-[SBGlassBannerTransitionAnimator prepareForTransition:]_block_invoke_4
+ ___56-[SBGlassBannerTransitionAnimator prepareForTransition:]_block_invoke_5
+ ___57-[SBDestroySceneActionHostComponent scene:handleActions:]_block_invoke_2
+ ___58-[SBHostProxyClientComponent _updateDisplayConfiguration:]_block_invoke
+ ___58-[SpringBoard sceneFromIdentityTokenStringRepresentation:]_block_invoke_2
+ ___59-[SBCompanionScenePresentationContext mutableCopyWithZone:]_block_invoke
+ ___61-[SBChargingAlertElement _updateMinimalViewWithDelayToState:]_block_invoke
+ ___61-[SBNonInteractiveDisplayController scene:didUpdateSettings:]_block_invoke
+ ___61-[SBNonInteractiveDisplayController scene:didUpdateSettings:]_block_invoke_2
+ ___62-[SBBannerManager postPresentable:withOptions:userInfo:error:]_block_invoke
+ ___62-[SBCoverSheetSlidingViewController _createClockMorphIfNeeded]_block_invoke
+ ___62-[SBSceneDestructionConfirmationViewController viewDidAppear:]_block_invoke
+ ___63-[SBBannerManager _beginPresentInsetSuspensionWithCoordinator:]_block_invoke
+ ___63-[SBCompanionScenePresentation updateContextWithSceneSettings:]_block_invoke
+ ___63-[SBCoverSheetSlidingViewController _createPropertiesWithView:]_block_invoke_5
+ ___63-[SBCoverSheetSlidingViewController _createPropertiesWithView:]_block_invoke_6
+ ___63-[SBGlassBannerTransitionAnimator performActionsForTransition:]_block_invoke_18
+ ___63-[SBGlassBannerTransitionAnimator performActionsForTransition:]_block_invoke_19
+ ___63-[SBGlassBannerTransitionAnimator performActionsForTransition:]_block_invoke_20
+ ___63-[SBGlassBannerTransitionAnimator performActionsForTransition:]_block_invoke_21
+ ___63-[SBGlassBannerTransitionAnimator performActionsForTransition:]_block_invoke_22
+ ___63-[SBGlassBannerTransitionAnimator performActionsForTransition:]_block_invoke_23
+ ___63-[SBGlassBannerTransitionAnimator performActionsForTransition:]_block_invoke_24
+ ___63-[SBGlassBannerTransitionAnimator performActionsForTransition:]_block_invoke_25
+ ___63-[SBGlassBannerTransitionAnimator performActionsForTransition:]_block_invoke_26
+ ___63-[SBGlassBannerTransitionAnimator performActionsForTransition:]_block_invoke_27
+ ___63-[SBGlassBannerTransitionAnimator performActionsForTransition:]_block_invoke_28
+ ___63-[SBSceneDestructionConfirmationOverlayViewProvider invalidate]_block_invoke
+ ___64+[SBAssistantIslandWorkspace _enhancedSiriAvailabilityDidChange]_block_invoke
+ ___65-[SBSystemUISceneDefaultPresenter sceneDidChangeDisplayIdentity:]_block_invoke_2
+ ___67-[SBSceneBarPositionResolverHostComponent scene:didUpdateSettings:]_block_invoke
+ ___68-[SBScreenSharingOverlayUISceneController _applyRootWindowTransform]_block_invoke
+ ___68-[SBScreenSharingOverlayUISceneController _applyRootWindowTransform]_block_invoke_2
+ ___68-[SBScreenSharingOverlayUISceneController _applyRootWindowTransform]_block_invoke_3
+ ___69-[SBMenuBarManager _updateMenuBarActivationViewsWithApplicationName:]_block_invoke
+ ___69-[SBMenuBarManager _updateMenuBarActivationViewsWithApplicationName:]_block_invoke_2
+ ___69-[SBMenuBarManager _updateMenuBarActivationViewsWithApplicationName:]_block_invoke_3
+ ___69-[SBMenuBarManager _updateMenuBarActivationViewsWithApplicationName:]_block_invoke_4
+ ___71+[SBSceneDestructionConfirmationOverlayViewProvider _providersByHandle]_block_invoke
+ ___72-[SBDeviceApplicationSceneHandle _extensionOnlySetPreflightSceneHandle:]_block_invoke
+ ___72-[SBGlassBannerTransitionAnimator _clockStatusBarForManager:clockFrame:]_block_invoke
+ ___73-[SBHIDUISensorModeController initWithSensorService:mirrorSensorService:]_block_invoke
+ ___73-[SBHIDUISensorModeController initWithSensorService:mirrorSensorService:]_block_invoke_2
+ ___73-[SBHIDUISensorModeController initWithSensorService:mirrorSensorService:]_block_invoke_3
+ ___73-[SBHIDUISensorModeController initWithSensorService:mirrorSensorService:]_block_invoke_4
+ ___73-[SBSceneDestructionConfirmationViewController _presentConfirmationAlert]_block_invoke
+ ___73-[SBSceneDestructionConfirmationViewController _presentConfirmationAlert]_block_invoke_2
+ ___73-[SBSceneDestructionConfirmationViewController _presentConfirmationAlert]_block_invoke_3
+ ___73-[SBSceneDestructionConfirmationViewController _presentConfirmationAlert]_block_invoke_4
+ ___73-[SBSceneDestructionConfirmationViewController _presentConfirmationAlert]_block_invoke_5
+ ___73-[SBTouchRegionManager setClassicLetterboxInnerFrame:forSceneIdentifier:]_block_invoke
+ ___73-[SBTouchRegionManager setClassicLetterboxInnerFrame:forSceneIdentifier:]_block_invoke_2
+ ___73-[SBTouchRegionManager setClassicLetterboxInnerFrame:forSceneIdentifier:]_block_invoke_3
+ ___75-[SBSceneDestructionConfirmationViewController _dismissAlertAndFadeDimming]_block_invoke
+ ___75-[SBSceneDestructionConfirmationViewController _dismissAlertAndFadeDimming]_block_invoke_2
+ ___76-[SBCoverSheetSlidingViewController _setLockScreenContentForState:animated:]_block_invoke
+ ___92-[SBHomeScreenController(AppearanceControlling) setHomeScreenScale:behaviorMode:completion:]_block_invoke_2
+ ___97-[SBCoverSheetSlidingViewController _retargetActiveTransitionAnimationOnProperty:toValue:reason:]_block_invoke
+ ___97-[SBNotificationCarPlayDestination _removeNotificationRequestFromPendingAVSessionWithIdentifier:]_block_invoke
+ ___99-[SBCoverSheetSlidingViewController _animateToLocation:mode:animatingAlongsideProgress:completion:]_block_invoke
+ ___99-[SBCoverSheetSlidingViewController _animateToLocation:mode:animatingAlongsideProgress:completion:]_block_invoke_2
+ ___99-[SBCoverSheetSlidingViewController _animateToLocation:mode:animatingAlongsideProgress:completion:]_block_invoke_3
+ ___99-[SBCoverSheetSlidingViewController _animateToLocation:mode:animatingAlongsideProgress:completion:]_block_invoke_4
+ ___99-[SBCoverSheetSlidingViewController _animateToLocation:mode:animatingAlongsideProgress:completion:]_block_invoke_5
+ ___99-[SBCoverSheetSlidingViewController _animateToLocation:mode:animatingAlongsideProgress:completion:]_block_invoke_6
+ ___MobileInBoxUpdateLibraryCore_block_invoke
+ ___SBWorkspaceDestroyApplicationSceneHandlesWithConfirmation_block_invoke
+ ___SBWorkspaceDestroyApplicationSceneHandlesWithConfirmation_block_invoke_2
+ ___SBWorkspaceDestroyApplicationSceneHandlesWithConfirmation_block_invoke_3
+ ___SBWorkspaceDestroyApplicationSceneHandlesWithConfirmation_block_invoke_4
+ ____SBGlassBannerAnimateLayerProperty_block_invoke
+ ____SBGlassBannerAnimateLayerProperty_block_invoke_2
+ ___block_descriptor_104_e8_32s40s48bs56bs64r_e8_v16?0d8lr64l8s32l8s40l8s48l8s56l8
+ ___block_descriptor_104_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_128_e8_32s40s48s56bs64bs72r80r_e8_v16?0d8lr72l8s32l8s40l8s56l8r80l8s48l8s64l8
+ ___block_descriptor_136_e8_32s40r_e8_v16?08ls32l8r40l8
+ ___block_descriptor_136_e8_32s40s48s56s64s72bs80bs88bs96bs_e5_v8?0ls32l8s40l8s72l8s48l8s80l8s56l8s88l8s64l8s96l8
+ ___block_descriptor_144_e8_32s40s48s56s64s72bs80bs88bs96bs104bs_e5_v8?0ls32l8s40l8s72l8s48l8s80l8s56l8s88l8s64l8s96l8s104l8
+ ___block_descriptor_152_e8_32s40s48s56s64s72bs80bs88bs96bs104r_e8_v16?0d8lr104l8s32l8s40l8s72l8s48l8s80l8s56l8s88l8s64l8s96l8
+ ___block_descriptor_160_e8_32s40s48s56s64s72bs80bs88bs96bs104bs112r_e8_v16?0d8lr112l8s32l8s40l8s72l8s48l8s80l8s56l8s88l8s64l8s96l8s104l8
+ ___block_descriptor_178_e8_32s40s48s56s64s72s80s88s96s104s112s120s_e33_v16?0?<?<v?BB>?"NSString">8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8s120l8
+ ___block_descriptor_32_e14_"NSError"8?0l
+ ___block_descriptor_40_e8_32w_e16_v16?0"NSDate"8lw32l8
+ ___block_descriptor_40_e8_32w_e23_v16?0"UIAlertAction"8lw32l8
+ ___block_descriptor_48_e8_32r40r_e21_v16?0"UIStatusBar"8lr32l8r40l8
+ ___block_descriptor_49_e8_32s40bs_e11_v16?0B8B12ls32l8s40l8
+ ___block_descriptor_49_e8_32s40s_e21_v16?0"UIStatusBar"8ls32l8s40l8
+ ___block_descriptor_49_e8_32s40w_e23_v16?0"UIAlertAction"8lw40l8s32l8
+ ___block_descriptor_56_e8_32s40s48s_e17_v16?0"NSError"8ls32l8s40l8s48l8
+ ___block_descriptor_58_e8_32s_e8_v16?0d8ls32l8
+ ___block_descriptor_64_e8_32bs40r48r56w_e11_v16?0B8B12lw56l8r40l8r48l8s32l8
+ ___block_descriptor_64_e8_32s40s48bs56r_e17_v16?0"NSError"8lr56l8s48l8s32l8s40l8
+ ___block_descriptor_72_e8_32bs40bs48r56r64r_e17_v16?0"NSError"8lr48l8r56l8r64l8s32l8s40l8
+ ___block_descriptor_72_e8_32s40bs48bs_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40bs_e5_v8?0ls32l8s40l8
+ ___block_descriptor_88_e8_32s40s48bs56bs_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_96_e8_32s40bs48r56r_e33_v16?0?<?<v?BB>?"NSString">8lr48l8s32l8r56l8s40l8
+ ___getMIBUClientClass_block_invoke
+ __effectiveProgressForDismissProgress
+ __providersByHandle.once
+ __providersByHandle.table
+ _audit_stringMobileInBoxUpdate
+ _genericAppLayout.__genericAppLayout
+ _genericAppLayout.onceToken
+ _getMIBUClientClass.softClass
+ _kCAContextCanRenderAboveBlankingContext
+ _kMIBUClientPersonalizationNameKey
- +[SBAssistantIslandWorkspace _assistantAvailabilityDidChange:]
- +[SBGlassBannerTransitionAnimator _pendingSwoopTrailBlocksByView]
- +[SBGlassBannerTransitionAnimator cancelInFlightTransitionForView:]
- -[SBAmbientIdleTimerController initWithWindowScene:]
- -[SBAppResizingCoordinator _setLastInteractedResizableSceneHandle:]
- -[SBBannerTransitionSettings customBannerTransitionStyleGlass_dismissGestureOvershootVelocityScale]
- -[SBBannerTransitionSettings setCustomBannerTransitionStyleGlass_dismissGestureOvershootVelocityScale:]
- -[SBCoverSheetPositionView positionContentForTouchAtLocation:withVelocity:transformMode:forPresentationValue:]
- -[SBCoverSheetSlidingViewController _createDismissTimeOverlayIfNeeded]
- -[SBCoverSheetSlidingViewController _removeDismissTimeOverlay]
- -[SBCoverSheetSlidingViewController _updateDismissTimeOverlayForProgress:forPresentationValue:]
- -[SBCoverSheetSlidingViewController dismissTimeOverlayLabel]
- -[SBCoverSheetSlidingViewController gestureStartXPosition]
- -[SBCoverSheetSlidingViewController setDismissTimeOverlayLabel:]
- -[SBCoverSheetSlidingViewController setGestureStartXPosition:]
- -[SBDashBoardCameraPageViewController _ensureZStackParticipant]
- -[SBDashBoardStatusBarController initWithWindowSceneStatusBarManager:]
- -[SBDeviceApplicationAppRestrictionSceneOverlayViewProvider contentWantsSimplifiedOrientationBehavior]
- -[SBDeviceApplicationSceneViewController _createSceneOverlayViewProvidersIfNecessary]
- -[SBFocusModeAlwaysOnPolicy _setDisableAlwaysOn:dndState:suspensionAssertionState:]
- -[SBFocusModeAlwaysOnPolicy _shouldDisableAlwaysOnForDNDState:]
- -[SBFocusModeAlwaysOnPolicy _updateDisablingAssertionWithDNDState:]
- -[SBFocusModeAlwaysOnPolicy _updateDisablingAssertionWithSuspensionState:]
- -[SBFocusModeAlwaysOnPolicy _updateDisablingAssertionWithSuspensionState:dndState:]
- -[SBFocusModeAlwaysOnPolicy acquirePolicySuspensionAssertionForReason:]
- -[SBFocusModeAlwaysOnPolicy analyticsPolicyValue]
- -[SBFocusModeAlwaysOnPolicy doNotDisturbStateMonitor:didUpdateToState:]
- -[SBFocusModeAlwaysOnPolicy isAlwaysOnPolicyActive]
- -[SBFocusModeAlwaysOnPolicy settings:changedValueForKey:]
- -[SBGlassBannerTransitionAnimator _animateLayerPropertyOnView:keyPath:toValue:withSettings:mode:completion:]
- -[SBGlassBannerTransitionAnimator _cancelPendingSwoopTrails]
- -[SBGlassBannerTransitionAnimator _hasTopSafeAreaInsetForContext:]
- -[SBGlassBannerTransitionAnimator _scheduleSwoopTrailAfterFraction:ofSettings:block:]
- -[SBHomeScreenController iconManagerAppliesListsFixedIconLocationBehaviorOnlyToNewLists:]
- -[SBInputUISceneController _currentDisplayConfiguration]
- -[SBLockElementViewProvider _appliedSecureState]
- -[SBLockElementViewProvider _canApplyRequestedState:]
- -[SBLockElementViewProvider _currentSecureState]
- -[SBLockElementViewProvider _deferSecureState:completion:]
- -[SBLockElementViewProvider _deferredSecureState]
- -[SBLockElementViewProvider _nextSecureStateForState:]
- -[SBLockElementViewProvider _nextSecureStateForState:from:]
- -[SBLockElementViewProvider _notifiedSecureState]
- -[SBLockElementViewProvider _reconcileAppliedSecureState]
- -[SBLockElementViewProvider _reconcileDeferredSecureState]
- -[SBLockElementViewProvider _reconcileNotifiedSecureState]
- -[SBLockElementViewProvider _reconcileRequestedSecureState]
- -[SBLockElementViewProvider _requestSecureState:]
- -[SBLockElementViewProvider _requestSecureState:completion:]
- -[SBLockElementViewProvider _requestedSecureState]
- -[SBLockElementViewProvider _resolvedEventForState:]
- -[SBLockElementViewProvider _secureStateContainsSecureFrames:]
- -[SBLockElementViewProvider _secureStateIsLarge:]
- -[SBLockElementViewProvider _treatCustomAsLarge]
- -[SBLockElementViewProvider elementAssertion]
- -[SBLockElementViewProvider requiredPriorityAssertion]
- -[SBLockElementViewProvider setElementAssertion:]
- -[SBLockElementViewProvider setRequiredPriorityAssertion:]
- -[SBLockElementViewProvider setVisibleAssertion:]
- -[SBLockElementViewProvider visibleAssertion]
- -[SBMainWorkspace _shouldThrottleUntrustedURLLaunchForApplication:options:]
- -[SBMainWorkspace _untrustedURLLaunchRequestWindowEntryForBundleID:atTime:]
- -[SBMenuBarManager _cleanupMenuBarActivationView]
- -[SBMenuBarManager _setupTransitionSystemStatusBarIfNeededForTransitioningToPresented:]
- -[SBMenuBarManager _updateMenuBarActivationViewWithApplicationName:]
- -[SBMenuBarManager menuBarActivationView]
- -[SBMenuBarManager setMenuBarActivationView:]
- -[SBMenuBarManager setPresentGestureRecognizer:]
- -[SBMenuBarManager setStatusBarThatContainsActivationView:]
- -[SBMenuBarManager setTransitionOnlySystemStatusBar:]
- -[SBMenuBarManager statusBarThatContainsActivationView]
- -[SBMenuBarManager transitionOnlySystemStatusBar]
- -[SBPhysicalButtonSceneOverrideManager initWithSceneManager:]
- -[SBPowerAlertElement .cxx_destruct]
- -[SBPowerAlertElement _batteryFillWidthForBatteryPercentage:]
- -[SBPowerAlertElement _extendDismissalTimer]
- -[SBPowerAlertElement _layoutMetrics]
- -[SBPowerAlertElement _primaryTextFontSize]
- -[SBPowerAlertElement _screenType]
- -[SBPowerAlertElement _secondaryTextColorForStyle]
- -[SBPowerAlertElement _secondaryTextForStyle]
- -[SBPowerAlertElement _trailingViewWidth]
- -[SBPowerAlertElement _updateBatteryContent]
- -[SBPowerAlertElement _updateBatteryIconFillAreaForPackageView:withBatteryPercentage:]
- -[SBPowerAlertElement _updateLowPowerMode]
- -[SBPowerAlertElement _updateMinimalViewToState:withDelay:]
- -[SBPowerAlertElement action]
- -[SBPowerAlertElement batteryPercentage]
- -[SBPowerAlertElement customEdgeSpacing]
- -[SBPowerAlertElement dealloc]
- -[SBPowerAlertElement dismissalTimer]
- -[SBPowerAlertElement dodgeSensorAreaOnIntrinsicContentSize]
- -[SBPowerAlertElement handleElementViewEvent:]
- -[SBPowerAlertElement horizontalSpacingBetweenLeadingAndCenter]
- -[SBPowerAlertElement horizontalSpacingBetweenTrailingAndCenter]
- -[SBPowerAlertElement initWithIdentifier:style:batteryPercentage:lowPowerModeEnabled:action:]
- -[SBPowerAlertElement isLowPowerModeEnabled]
- -[SBPowerAlertElement isProvidedViewConcentric:inLayoutMode:]
- -[SBPowerAlertElement keyColor]
- -[SBPowerAlertElement leadingLabel]
- -[SBPowerAlertElement minimalBatteryIconPackageView]
- -[SBPowerAlertElement preferredAlertingDuration:]
- -[SBPowerAlertElement preferredEdgeOutsetsForLayoutMode:suggestedOutsets:maximumOutsets:]
- -[SBPowerAlertElement secondaryContent]
- -[SBPowerAlertElement setAction:]
- -[SBPowerAlertElement setBatteryPercentage:]
- -[SBPowerAlertElement setDismissalTimer:]
- -[SBPowerAlertElement setLeadingLabel:]
- -[SBPowerAlertElement setLowPowerModeEnabled:]
- -[SBPowerAlertElement setMinimalBatteryIconPackageView:]
- -[SBPowerAlertElement setSecondaryContent:]
- -[SBPowerAlertElement setStyle:]
- -[SBPowerAlertElement setTrailingBatteryIconPackageView:]
- -[SBPowerAlertElement setTrailingBatteryLabel:]
- -[SBPowerAlertElement setTrailingLowBatteryStyleIconPackageView:]
- -[SBPowerAlertElement shouldSuppressElementWhileProximityReaderPresent]
- -[SBPowerAlertElement style]
- -[SBPowerAlertElement supportsLimitedSize]
- -[SBPowerAlertElement trailingBatteryIconPackageView]
- -[SBPowerAlertElement trailingBatteryLabel]
- -[SBPowerAlertElement trailingLowBatteryStyleIconPackageView]
- -[SBPowerAlertElement verticalItemSpacing]
- -[SBPowerAlertElement verticalSpacingBetweenPrimaryAndSecondary]
- -[SBScreenSharingOverlayUISceneController _applyRootWindowTransform:]
- -[SBSystemApertureViewController indicatorSourceViewFrameReferenceCoordinateSpace]
- -[SBSystemUISceneDefaultPresenter _moveScene:fromWindowScene:toWindowScene:]
- GCC_except_table130
- GCC_except_table136
- GCC_except_table153
- GCC_except_table155
- GCC_except_table171
- GCC_except_table240
- GCC_except_table259
- GCC_except_table263
- GCC_except_table283
- GCC_except_table311
- GCC_except_table317
- GCC_except_table398
- GCC_except_table427
- GCC_except_table431
- GCC_except_table545
- GCC_except_table555
- GCC_except_table568
- GCC_except_table570
- _AFIsLinwoodEnabledAndAvailable
- _OBJC_CLASS_$_SBHLightSourceManager
- _OBJC_CLASS_$_SBHSheenEffectView
- _OBJC_CLASS_$_SBHTraitIconEffect
- _OBJC_CLASS_$_SBPowerAlertElement
- _OBJC_IVAR_$_SBBannerTransitionSettings._customBannerTransitionStyleGlass_dismissGestureOvershootVelocityScale
- _OBJC_IVAR_$_SBCoverSheetSlidingViewController._dismissTimeOverlayLabel
- _OBJC_IVAR_$_SBCoverSheetSlidingViewController._gestureStartXPosition
- _OBJC_IVAR_$_SBDashBoardStatusBarController._statusBarsToVisbilityAssertions
- _OBJC_IVAR_$_SBDeviceApplicationSceneViewController._overlayViewProviders
- _OBJC_IVAR_$_SBFocusModeAlwaysOnPolicy._alwaysOnPolicyActive
- _OBJC_IVAR_$_SBFocusModeAlwaysOnPolicy._disableAlwaysOn
- _OBJC_IVAR_$_SBFocusModeAlwaysOnPolicy._dndStateMonitor
- _OBJC_IVAR_$_SBFocusModeAlwaysOnPolicy._policySettings
- _OBJC_IVAR_$_SBFocusModeAlwaysOnPolicy._suspensionAssertions
- _OBJC_IVAR_$_SBLockElementViewProvider._appliedSecureState
- _OBJC_IVAR_$_SBLockElementViewProvider._currentSecureState
- _OBJC_IVAR_$_SBLockElementViewProvider._deferredSecureState
- _OBJC_IVAR_$_SBLockElementViewProvider._deferredStateCompletions
- _OBJC_IVAR_$_SBLockElementViewProvider._elementAssertion
- _OBJC_IVAR_$_SBLockElementViewProvider._notifiedSecureState
- _OBJC_IVAR_$_SBLockElementViewProvider._requestedSecureState
- _OBJC_IVAR_$_SBLockElementViewProvider._requiredPriorityAssertion
- _OBJC_IVAR_$_SBLockElementViewProvider._stateCompletions
- _OBJC_IVAR_$_SBLockElementViewProvider._visibleAssertion
- _OBJC_IVAR_$_SBMainWorkspace._untrustedURLLaunchRequestWindowEntries
- _OBJC_IVAR_$_SBMenuBarManager._menuBarActivationView
- _OBJC_IVAR_$_SBMenuBarManager._presentGestureRecognizer
- _OBJC_IVAR_$_SBMenuBarManager._statusBarThatContainsActivationView
- _OBJC_IVAR_$_SBMenuBarManager._transitionOnlySystemStatusBar
- _OBJC_IVAR_$_SBPowerAlertElement._action
- _OBJC_IVAR_$_SBPowerAlertElement._batteryPercentage
- _OBJC_IVAR_$_SBPowerAlertElement._dismissalTimer
- _OBJC_IVAR_$_SBPowerAlertElement._keyColor
- _OBJC_IVAR_$_SBPowerAlertElement._leadingLabel
- _OBJC_IVAR_$_SBPowerAlertElement._lowPowerModeEnabled
- _OBJC_IVAR_$_SBPowerAlertElement._minimalBatteryIconPackageView
- _OBJC_IVAR_$_SBPowerAlertElement._secondaryContent
- _OBJC_IVAR_$_SBPowerAlertElement._style
- _OBJC_IVAR_$_SBPowerAlertElement._trailingBatteryIconPackageView
- _OBJC_IVAR_$_SBPowerAlertElement._trailingBatteryLabel
- _OBJC_IVAR_$_SBPowerAlertElement._trailingLowBatteryStyleIconPackageView
- _OBJC_IVAR_$_SBScreenSharingOverlayUISceneController._previousRootWindowTransform
- _OBJC_METACLASS_$_SBPowerAlertElement
- _SBHFeatureEnabled
- _STUIStatusBarPartIdentifierCenter
- __OBJC_$_CLASS_METHODS_SBChainableModifier(RuntimeProviding|SwitcherModifier|WindowingModifier)
- __OBJC_$_CLASS_PROP_LIST_SBFocusModeAlwaysOnPolicy
- __OBJC_$_INSTANCE_METHODS_FBScene(SBVisibilitySceneExtension_ForSceneManager|SBSUIHomeScreenIconStyle|LocalSynchronous|CompanionSceneHost|CompanionSceneHost_Internal|CompanionSceneHost_Testing|SBWindowSceneAccessorySceneProvider|SBProductivityGestureDestination|SBDynamicMemoryControllingHost|SBHostedScenePolicy)
- __OBJC_$_INSTANCE_METHODS_SBChainableModifier(RuntimeProviding|SwitcherModifier|WindowingModifier)
- __OBJC_$_INSTANCE_METHODS_SBChainableModifierEvent(SBSwitcherModifierEvent|SBWindowingModifierActivity)
- __OBJC_$_INSTANCE_METHODS_SBPowerAlertElement
- __OBJC_$_INSTANCE_METHODS_SBWindowingModifierActivity(TransitionEvent|GestureEvent|StripChangedModifierActivity)
- __OBJC_$_INSTANCE_VARIABLES_SBPowerAlertElement
- __OBJC_$_PROP_LIST_SBFocusModeAlwaysOnPolicy
- __OBJC_$_PROP_LIST_SBPowerAlertElement
- __OBJC_CLASS_PROTOCOLS_$_FBScene(SBVisibilitySceneExtension_ForSceneManager|SBSUIHomeScreenIconStyle|LocalSynchronous|CompanionSceneHost|CompanionSceneHost_Internal|CompanionSceneHost_Testing|SBWindowSceneAccessorySceneProvider|SBProductivityGestureDestination|SBDynamicMemoryControllingHost|SBHostedScenePolicy)
- __OBJC_CLASS_PROTOCOLS_$_SBFocusModeAlwaysOnPolicy
- __OBJC_CLASS_PROTOCOLS_$_SBPowerAlertElement
- __OBJC_CLASS_RO_$_SBPowerAlertElement
- __OBJC_METACLASS_RO_$_SBPowerAlertElement
- __SBSystemApertureViewControllerPinViewToOtherView
- __ZNSt3__114__split_bufferINS_6vectorI11BezierCurveNS_9allocatorIS2_EEEERNS3_IS5_EEE17__destruct_at_endB9fqn220100EPS5_
- __ZNSt3__114__split_bufferINS_6vectorI9PathPointNS_9allocatorIS2_EEEERNS3_IS5_EEE17__destruct_at_endB9fqn220100EPS5_
- __ZNSt3__119__allocate_at_leastB9fqn220100INS_9allocatorI11BezierCurveEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqn220100INS_9allocatorI9PathPointEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqn220100INS_9allocatorINS_6vectorI11BezierCurveNS1_IS3_EEEEEENS_16allocator_traitsIS6_EEEENS_19__allocation_resultINT0_7pointerENSA_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqn220100INS_9allocatorINS_6vectorI9PathPointNS1_IS3_EEEEEENS_16allocator_traitsIS6_EEEENS_19__allocation_resultINT0_7pointerENSA_9size_typeEEERT_m
- __ZNSt3__16vectorI11BezierCurveNS_9allocatorIS1_EEE11__vallocateB9fqn220100Em
- __ZNSt3__16vectorI11BezierCurveNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorI11BezierCurveNS_9allocatorIS1_EEEC2B9fqn220100ERKS4_
- __ZNSt3__16vectorI9PathPointNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorINS0_I11BezierCurveNS_9allocatorIS1_EEEENS2_IS4_EEE16__destroy_vectorclB9fqn220100Ev
- __ZNSt3__16vectorINS0_I11BezierCurveNS_9allocatorIS1_EEEENS2_IS4_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorINS0_I11BezierCurveNS_9allocatorIS1_EEEENS2_IS4_EEE5clearB9fqn220100Ev
- __ZNSt3__16vectorINS0_I9PathPointNS_9allocatorIS1_EEEENS2_IS4_EEE16__destroy_vectorclB9fqn220100Ev
- __ZNSt3__16vectorINS0_I9PathPointNS_9allocatorIS1_EEEENS2_IS4_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorINS0_I9PathPointNS_9allocatorIS1_EEEENS2_IS4_EEE5clearB9fqn220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqn220100v
- ___106-[SBHomeScreenOverlayController animatePresentationProgress:withGestureLiftOffVelocity:completionHandler:]_block_invoke_2
- ___108-[SBGlassBannerTransitionAnimator _animateLayerPropertyOnView:keyPath:toValue:withSettings:mode:completion:]_block_invoke
- ___108-[SBGlassBannerTransitionAnimator _animateLayerPropertyOnView:keyPath:toValue:withSettings:mode:completion:]_block_invoke_2
- ___108-[SBHomeScreenOverlayController setPresentationProgress:fromLeading:interactive:animated:completionHandler:]_block_invoke_3
- ___42-[SBPowerAlertElement _updateLowPowerMode]_block_invoke
- ___44-[SBPowerAlertElement _extendDismissalTimer]_block_invoke
- ___49-[SBApplicationSceneUpdateTransaction _willBegin]_block_invoke_4
- ___49-[SBApplicationSceneUpdateTransaction _willBegin]_block_invoke_5
- ___49-[SBApplicationSceneUpdateTransaction _willBegin]_block_invoke_6
- ___51-[SBFocusModeAlwaysOnPolicy activateAlwaysOnPolicy]_block_invoke
- ___53-[SBHIDUISensorModeController initWithSensorService:]_block_invoke
- ___53-[SBHIDUISensorModeController initWithSensorService:]_block_invoke_2
- ___53-[SBHIDUISensorModeController initWithSensorService:]_block_invoke_3
- ___53-[SBHIDUISensorModeController initWithSensorService:]_block_invoke_4
- ___59-[SBLockElementViewProvider _reconcileRequestedSecureState]_block_invoke
- ___59-[SBLockElementViewProvider _reconcileRequestedSecureState]_block_invoke_2
- ___59-[SBLockElementViewProvider _reconcileRequestedSecureState]_block_invoke_3
- ___59-[SBLockElementViewProvider _reconcileRequestedSecureState]_block_invoke_4
- ___59-[SBPowerAlertElement _updateMinimalViewToState:withDelay:]_block_invoke
- ___62+[SBAssistantIslandWorkspace _assistantAvailabilityDidChange:]_block_invoke
- ___65+[SBGlassBannerTransitionAnimator _pendingSwoopTrailBlocksByView]_block_invoke
- ___68-[SBMenuBarManager _updateMenuBarActivationViewWithApplicationName:]_block_invoke
- ___68-[SBMenuBarManager _updateMenuBarActivationViewWithApplicationName:]_block_invoke_2
- ___69-[SBScreenSharingOverlayUISceneController _applyRootWindowTransform:]_block_invoke
- ___69-[SBScreenSharingOverlayUISceneController _applyRootWindowTransform:]_block_invoke_2
- ___69-[SBScreenSharingOverlayUISceneController _applyRootWindowTransform:]_block_invoke_3
- ___70-[SBApplicationRestrictionController _updateRestrictionsAndForcePost:]_block_invoke_2
- ___79-[SBCoverSheetSlidingViewController _dismissGestureBeganWithGestureRecognizer:]_block_invoke
- ___85-[SBGlassBannerTransitionAnimator _scheduleSwoopTrailAfterFraction:ofSettings:block:]_block_invoke
- ___90-[SBCoverSheetSlidingViewController _presentOrDismissGestureChangedWithGestureRecognizer:]_block_invoke_2
- ___block_descriptor_128_e8_32s40r_e8_v16?08ls32l8r40l8
- ___block_descriptor_136_e8_32s40s48s56s64s72s80bs88bs96bs_e5_v8?0ls32l8s40l8s48l8s80l8s56l8s88l8s64l8s96l8s72l8
- ___block_descriptor_144_e8_32s40s48s56s64s72s80bs88bs96bs104bs_e5_v8?0ls32l8s40l8s48l8s80l8s56l8s88l8s64l8s96l8s72l8s104l8
- ___block_descriptor_186_e8_32s40s48s56s64s72s80s88s96s104s112s120r128r_e33_v16?0?<?<v?BB>?"NSString">8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8r120l8s112l8r128l8
- ___block_descriptor_48_e8_32r40r_e37_v24?0"SBFFluidBehaviorSettings"8d16lr32l8r40l8
- ___block_descriptor_48_e8_32s40s_e21_v16?0"UIStatusBar"8ls32l8s40l8
- ___block_descriptor_64_e50_v16?0"SBRecordingIndicatorVisualRepresentation"8l
- ___block_descriptor_74_e8_32s_e8_v16?0d8ls32l8
- ___block_descriptor_88_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
- __pendingSwoopTrailBlocksByView.map
- __pendingSwoopTrailBlocksByView.onceToken
- _dispatch_block_testcancel
CStrings:
+ "#AnnounceID Lookup by identifier: input=%{public}@, found=%{public}@, queue=%{public}@"
+ "#AnnounceID Raw identifiers in callback: %{public}@"
+ "#AnnounceID Registering Siri observer with notificationIdentifier digest: %{public}@"
+ "#Preprocessing #CarPlay Banner appeared but is not the announcing request; leaving dismiss timer in place"
+ "#Preprocessing #CarPlay Banner appeared for the request currently announcing; sending didBeginAnnounceForNotificationRequest"
+ "#Preprocessing #CarPlay Preprocessing isn't enabled. PresentableDidAppearAsBanner is a no-op"
+ "%@ must override +policyIdentifier"
+ "%@ must override -analyticsPolicyName"
+ "%@:%p '%@' called afer invalidation"
+ "%@:%p was not invalidated before dealloc"
+ "%{public}@ updated restrictionReason: %lu"
+ "(NOT FOUND)"
+ "(nil)"
+ "-[SBAppResizingCoordinator _setLastInteractedResizableSceneHandle:provider:]"
+ "-[SBHomeScreenService redo]"
+ "-[SBHomeScreenService undo]"
+ "-[SBManagedDisplayWindowSceneDelegate _configureForConnectingWindowScene:windowSceneContext:]_block_invoke"
+ "-[SBUserAgent deviceIsThermallyBlocked]"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SpringBoard/SBDashBoardStatusBarController.m"
+ "; associatedSystemApertureElementID: %@; contentScale: %@; contentBounds: %@; contentCenter: %@; keyLineMode: %@; keyLineTintColor: %@; sampledBackgroundLuminanceLevel: %@; shadowStyle: %@, renderingConfiguration: %@; elevationStyle: %@; isContentClippingEnabled: %@; isUserInteractionEnabled: %@;"
+ "<unknown_requested_bundle_id>"
+ "@\"NSError\"8@?0"
+ "A scene destruction confirmation is already in flight"
+ "Acquiring focus-mode sleep suppression assertion for state %@ (suspended: %{BOOL}u)"
+ "AssistantIslandStageActiveStateChanged"
+ "AssistantIslandStageInvalidated"
+ "AssistantIslandStageWindowSceneInvalidated"
+ "BA1"
+ "Banner for notification %{public}@ was dropped. suppressed: %d application: %d, do not disturb: %d screen time: %d ambient: %d"
+ "ButtonShapesEnabled"
+ "Can receive request %{public}@ in ambient : %{BOOL}d [ ambientSuppress:%{BOOL}d ; critical:%{BOOL}d ; emergency:%{BOOL}d ]"
+ "CarPlay scrubbing already-started notification request %{public}@ from pending AV session list (would duplicate-announce on voice prompt restore)"
+ "Class getMIBUClientClass(void)_block_invoke"
+ "Close Window?"
+ "Destruction completed with result: %{bool}u; error: %{public}@"
+ "Elevated"
+ "Error trying to fetch personalization info: %@"
+ "Error while transforming display configuration: %{public}@"
+ "Failed to instantiate MIBUClient to check for personalization data"
+ "Focus Mode Sleep Suppression"
+ "Glass Dismiss Gesture Overshoot Inset Min Scale"
+ "Glass Dismiss Gesture Overshoot Reference Inset"
+ "Glass Dismiss Gesture Overshoot Spring X"
+ "Glass Dismiss Gesture Overshoot X (base)"
+ "Glass Dismiss Gesture Overshoot X (max)"
+ "Glass Dismiss Gesture Velocity Scale X"
+ "Glass Dismiss Gesture Velocity Scale Y"
+ "Hosting display disconnected"
+ "Ignoring update as restricted identifier sets haven't changed. restrictedIdentifiers: %{public}@; partiallyRestrictedIdentifiers: %{public}@"
+ "Invalidating today-view display layout element"
+ "Kill request for %{public}@ result: %{bool}u"
+ "Landscape Element Layout"
+ "Landscape Uses Portrait Positioning"
+ "MIBUClient"
+ "Mirrored"
+ "MobileInBoxUpdate personalization info: %{private}@"
+ "New list of restricted identifiers: %{public}@"
+ "RETURN_TO_PREVIOUS_SIZE_DISCOVERABILITY"
+ "Registered today-view display layout element: level=%ld role=%ld frame=%@"
+ "Releasing focus-mode sleep suppression assertion for state %@ (suspended: %{BOOL}u)"
+ "Requesting destruction of scene handles with intent %{public}@: %{public}@"
+ "Requesting graceful kill for: %{public}@"
+ "SB transaction (mirror)"
+ "SBChargingAlertElement.m"
+ "SBCoverSheetGrabberWindow"
+ "SBDashBoardSetupView.m"
+ "SBFocusModeBaseAlwaysOnPolicy.m"
+ "SBIconVisibilityDefaultVisibleHardwareModels"
+ "SBSceneDestructionConfirmationErrorDomain"
+ "SBTraitsParticipantRoleCoverSheetGrabber"
+ "SBWindowSceneDidUpdateReachabilityControllerNotification"
+ "Skipped kill loop as we have nothing to kill"
+ "Throttled untrusted URL request from origin=%{public}@, requestedBundleID=%{public}@"
+ "Today overlay dismiss animation completion: finished=NO at progress=0"
+ "Today overlay firing synchronous bs_beginAppearanceTransition:NO; oldProgress=%f appearState=%ld"
+ "UIViewGlassBuddyTintAmount"
+ "UIViewGlassEverEditedInBuddy"
+ "UIViewGlassEverEditedInSettings"
+ "UIViewGlassTintAmount"
+ "Updating %{public}@ via proxy with displayConfiguration: %{public}@"
+ "Updating indicator container elevation style from: %{public}@ to: %{public}@"
+ "User cancelled scene destruction confirmation"
+ "[%{public}@] %{public}@ after-preflight update completed: %{public}@"
+ "[%{public}@] %{public}@ after-preflight update failed: taking our ball and going home(screen): %@"
+ "[%{public}@] %{public}@ not running preflight as not restricted"
+ "[%{public}@] %{public}@ our scene entity isn't in the previousLayoutState, so not bothering with going home"
+ "[%{public}@] %{public}@ requiresPreflight: %{bool}u"
+ "[%{public}@] %{public}@ running preflight"
+ "[%{public}@] %{public}@ skipping preflight as the source says so: %{public}@"
+ "[%{public}@] Display configuration changed to %@"
+ "[%{public}@] created vc for overlay: %p"
+ "[%{public}@] didAddScene"
+ "[%{public}@] init with scene"
+ "[%{public}@] init without scene; waiting for scene manager"
+ "[%{public}@] requiresPreflight = NO; waiting for preflight callback"
+ "[%{public}@] requiresPreflight = YES; attempting activation"
+ "[%{public}@] requiresPreflight changed to NO; attempting deactivation"
+ "[%{public}@] requiresPreflight changed to YES; attempting activation"
+ "[%{public}@] tearing down vc for overlay: %p"
+ "_previousIndicatorContainerElevationStyle"
+ "_recheckIdleTimerBehaviorForReason: %d->%d, reason: %{public}@"
+ "_recheckIdleTimerBehaviorForReason: no transition (hasIdleTimerBehaviors=%d, reason: %{public}@)"
+ "_recheckIdleTimerBehaviorForReason: skipping — no idleTimerCoordinator wired (reason: %{public}@)"
+ "_updateKeyboardFocusDeferringRule(%{public}@) outcome:(unwanted, destroyed)"
+ "_updateKeyboardFocusDeferringRule(%{public}@) outcome:(wanted, but focusTarget is nil) scene:%{public}@"
+ "_updateKeyboardFocusDeferringRule(%{public}@) outcome:(wanted, created) target:%{public}@"
+ "after-preflight update completed: %@"
+ "already called '%@'"
+ "already set up a recordingIndicatorManager for context %@ of scene %@"
+ "buddyTint"
+ "clientDidConnect"
+ "com.apple.SpringBoard.SBSystemApertureViewController.highLevelMatchMoveAnimation"
+ "com.apple.UIKit"
+ "com.apple.gms.availability.notification"
+ "com.apple.os-eligibility-domain.change.greymatter"
+ "com.apple.springboard.statusBarOcclusion"
+ "currentTint"
+ "customBannerTransitionStyleGlass_dismissGestureOvershootInsetMinScale"
+ "customBannerTransitionStyleGlass_dismissGestureOvershootMaxX"
+ "customBannerTransitionStyleGlass_dismissGestureOvershootReferenceInset"
+ "customBannerTransitionStyleGlass_dismissGestureOvershootSpringX"
+ "customBannerTransitionStyleGlass_dismissGestureOvershootVelocityScaleX"
+ "customBannerTransitionStyleGlass_dismissGestureOvershootVelocityScaleY"
+ "customBannerTransitionStyleGlass_dismissGestureOvershootX"
+ "didCreateScene"
+ "didDestroyScene"
+ "didMoveToWindow"
+ "everEditedInBuddy"
+ "everEditedInSettings"
+ "existingViewController != nil || viewControllerBuilderBlock != nil"
+ "explicit-invalidate"
+ "focusModeSleepSuppression"
+ "glassTintAmount"
+ "ignoring nil lastInteractedScene transition, as we're latched to: %p"
+ "increaseContrast"
+ "interfaceStyle"
+ "landscapeUsesPortraitElementPositioning"
+ "leading+center"
+ "leading+center+trailing"
+ "localWindowsGraphForFocusedContextID[%{public}@] targetWindow[%{public}@] targetRootWindow[%{public}@] targetPresentationStyle[%{public}ld]"
+ "menuBarEntry"
+ "mirrorSensorService"
+ "q1\xa1"
+ "reduceTransparency"
+ "response not possible"
+ "sceneDidInvalidate"
+ "showBorders"
+ "softlink:o:path:/System/Library/PrivateFrameworks/MobileInBoxUpdate.framework/MobileInBoxUpdate"
+ "void *MobileInBoxUpdateLibrary(void)"
+ "volumeControl"
+ "\x92"
+ "\xf0\xf0\xb1$"
- "\n!"
- "\r3\xf0!1"
- "-[SBAppResizingCoordinator _setLastInteractedResizableSceneHandle:]"
- "; associatedSystemApertureElementID: %@; contentScale: %@; contentBounds: %@; contentCenter: %@; keyLineMode: %@; keyLineTintColor: %@; sampledBackgroundLuminanceLevel: %@; shadowStyle: %@, renderingConfiguration: %@; isContentClippingEnabled: %@; isUserInteractionEnabled: %@;"
- "A1\xa1"
- "Applied requested state: %@ -> %@"
- "Applied state finished: %@ -> %@"
- "Banner for notification %{public}@ was dropped. suppressed: %d application: %d, do not disturb: %d screen time: %d"
- "Calistoga"
- "Can receive request %{public}@ in ambient : %{BOOL}d [ requestSuppress:%{BOOL}d ; ambientSuppress:%{BOOL}d ; critical:%{BOOL}d ; emergency:%{BOOL}d ]"
- "Cannot add scene[%@] to presentation binder with a different display identity"
- "Cannot apply requested state: %@ (waiting for '%@ -> %@' to finish)"
- "Cannot apply requested state: %@ (waiting for '%@ -> %@' to start)"
- "Cannot remove scene[%@] from presentation binder with a different display identity"
- "Deferring requested secure state: %@ (still waiting for secure state: %@)"
- "ErrorScaled"
- "Glass Dismiss Gesture Velocity Scale"
- "New list of restricted identifiers: %@"
- "Promoting deferred secure state: %@ -> %@"
- "Requesting secure state: %@ -> %@"
- "SearchFailed"
- "Searching"
- "Throttled untrusted URL request from %{public}@"
- "UnlockedScaled"
- "UnlockedScaledSecure"
- "UnlockedSecure"
- "com.apple.SpringBoard.SBSystemApertureViewController.curtainIndicatorMatchMoveAnimation"
- "customBannerTransitionStyleGlass_dismissGestureOvershootVelocityScale"
- "failed to get status bar for menu bar dismissal transition"
- "localWindowsGraphForFocusedContextID[%{public}@] targetWindow[%{public}@] targetRootWindow[%{public}@]"
- "unkown"
- "v24@?0@\"SBFFluidBehaviorSettings\"8d16"
- "\x82"
- "\xf0\xf0\x81$"
- "\xf0\xf1"
```
