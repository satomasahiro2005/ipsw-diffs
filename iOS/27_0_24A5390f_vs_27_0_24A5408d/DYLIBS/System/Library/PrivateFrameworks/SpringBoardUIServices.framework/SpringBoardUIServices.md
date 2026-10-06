## SpringBoardUIServices

> `/System/Library/PrivateFrameworks/SpringBoardUIServices.framework/SpringBoardUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2350` | `0xa2c10` | **`+0x8c0`** |
| `__TEXT.__objc_methlist` | `0xe694` | `0xe8b4` | **`+0x220`** |
| `__AUTH_CONST.__objc_const` | `0x2d970` | `0x2daa0` | **`+0x130`** |
| `__DATA_CONST.__objc_selrefs` | `0x7c58` | `0x7cc8` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x3268` | `0x32d8` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x50a0` | `0x50f0` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x47c5` | `0x4802` | **`+0x3d`** |
| `__DATA.__objc_ivar` | `0xd30` | `0xd3c` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x10c0` | `0x10c8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x988` | `0x990` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x5f0` | `0x5f8` | **`+0x8`** |
| `__TEXT.__cstring` | `0xabf2` | `0xabf9` | **`+0x7`** |

### Other Changes

```diff

-4630.1.102.0.0
+4636.102.1.0.0

-  Functions: 4763
-  Symbols:   9377
-  CStrings:  1818
+  Functions: 4807
+  Symbols:   9435
+  CStrings:  1822
Symbols:
+ +[SBUILiveActivityMetrics _metrics]
+ -[SBSUIHandleDeviceLockSceneAction abortForUsageViolation:]
+ -[SBSUIHardwareButtonEventSceneAction abortForUsageViolation:]
+ -[SBSUIInCallDestroySceneAction abortForUsageViolation:]
+ -[SBSUIInCallRequestKeyboardFocusAction abortForUsageViolation:]
+ -[SBSUIInCallRequestPresentationModeAction abortForUsageViolation:]
+ -[SBSUIInCallShowNoticeForSystemControlsAction abortForUsageViolation:]
+ -[SBSUIInCallSilenceRingtoneAction abortForUsageViolation:]
+ -[SBSUIUserSwipedToKillAction abortForUsageViolation:]
+ -[SBUIBackgroundActivityAction abortForUsageViolation:]
+ -[SBUIBackgroundContentTouchAction abortForUsageViolation:]
+ -[SBUIButtonAction abortForUsageViolation:]
+ -[SBUIInputControlButtonAction abortForUsageViolation:]
+ -[SBUIInputControlDisableSystemGesturesAction abortForUsageViolation:]
+ -[SBUIPresentableButtonEventsAction abortForUsageViolation:]
+ -[SBUIPresentableCancelSystemDragAction abortForUsageViolation:]
+ -[SBUIPresentableHomeAffordanceThresholdAction abortForUsageViolation:]
+ -[SBUIPresentableSupportsCancellingSystemDragAction abortForUsageViolation:]
+ -[SBUIPresentableWantsHomeGestureAction abortForUsageViolation:]
+ -[SBUIRemoteAlertButtonAction abortForUsageViolation:]
+ -[SBUISActivityMetrics .cxx_destruct]
+ -[SBUISActivityMetrics _jindoMetricsProvider]
+ -[SBUISActivityMetrics _limitedWidthSystemApertureMetrics]
+ -[SBUISActivityMetrics _lockScreenNotificationListItemMetricsWithScaleFactor:screen:]
+ -[SBUISActivityMetrics _requiresPortraitLayout]
+ -[SBUISActivityMetrics _screen]
+ -[SBUISActivityMetrics _systemApertureMetricsWithJindoMetricsProvider:limitedInWidth:]
+ -[SBUISActivityMetrics _systemApertureMetrics]
+ -[SBUISActivityMetrics activeLayoutDirection]
+ -[SBUISActivityMetrics allowsPortraitInAmbient]
+ -[SBUISActivityMetrics ambientCompactDefaultMetrics]
+ -[SBUISActivityMetrics ambientDefaultMetrics]
+ -[SBUISActivityMetrics ambientWidgetMetrics]
+ -[SBUISActivityMetrics defaultMetrics]
+ -[SBUISActivityMetrics initWithWindowScene:allowsPortraitInAmbient:activeLayoutDirection:]
+ -[SBUISActivityMetrics modalFullScreenMetrics]
+ -[SBUISActivityMetrics windowScene]
+ -[SBUISFloatingDockRemoteContentAction abortForUsageViolation:]
+ -[SBUISystemApertureAlertingAction abortForUsageViolation:]
+ -[SBUISystemApertureElementSource _requiresSceneAlignedGeometry]
+ -[SBUISystemApertureElementSource _sceneAlignedAnchorFrame:]
+ -[SBUISystemApertureElementSource _sceneAlignedContainerViewFrame]
+ -[SBUISystemApertureLayoutMetrics maximumLimitedLeadingTrailingViewAndPaddingSize]
+ -[SBUISystemApertureSceneAction abortForUsageViolation:]
+ -[SBUISystemApertureSceneResizeAction abortForUsageViolation:]
+ -[_SBUISystemApertureTransientLocalSceneResizeAction abortForUsageViolation:]
+ -[_SBUISystemApertureUserInitiatedSceneResizeAction abortForUsageViolation:]
+ GCC_except_table16
+ GCC_except_table166
+ GCC_except_table168
+ _BSSizeSwap
+ _OBJC_CLASS_$_SBUISActivityMetrics
+ _OBJC_IVAR_$_SBUISActivityMetrics._activeLayoutDirection
+ _OBJC_IVAR_$_SBUISActivityMetrics._allowsPortraitInAmbient
+ _OBJC_IVAR_$_SBUISActivityMetrics._windowScene
+ _OBJC_METACLASS_$_SBUISActivityMetrics
+ __OBJC_$_INSTANCE_METHODS_SBSUIInCallShowNoticeForSystemControlsAction
+ __OBJC_$_INSTANCE_METHODS_SBSUIInCallSilenceRingtoneAction
+ __OBJC_$_INSTANCE_METHODS_SBUIPresentableCancelSystemDragAction
+ __OBJC_$_INSTANCE_METHODS_SBUIPresentableSupportsCancellingSystemDragAction
+ __OBJC_$_INSTANCE_METHODS_SBUISActivityMetrics
+ __OBJC_$_INSTANCE_VARIABLES_SBUISActivityMetrics
+ __OBJC_$_PROP_LIST_SBUISActivityMetrics
+ __OBJC_CLASS_RO_$_SBUISActivityMetrics
+ __OBJC_METACLASS_RO_$_SBUISActivityMetrics
- +[SBUILiveActivityMetrics _limitedWidthSystemApertureMetrics]
- +[SBUILiveActivityMetrics _systemApertureMetricsWithJindoMetricsProvider:maximumLeadingTrailingViewSize:uniformEdgeInsets:]
- +[SBUILiveActivityMetrics _systemApertureMetrics]
- +[SBUILiveActivityMetrics lockScreenNotificationListItemMetricsWithScaleFactor:]
- GCC_except_table11
- GCC_except_table163
- GCC_except_table165
CStrings:
+ "%@"
+ "Not updating strict coverage required for non-mesa device"
+ "SBUISActivityMetrics.m"
+ "adi"
+ "debug"
- "SBUILiveActivityMetrics.m"
```
