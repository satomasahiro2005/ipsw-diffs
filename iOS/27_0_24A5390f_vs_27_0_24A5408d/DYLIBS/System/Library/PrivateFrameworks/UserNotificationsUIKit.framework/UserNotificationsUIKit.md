## UserNotificationsUIKit

> `/System/Library/PrivateFrameworks/UserNotificationsUIKit.framework/UserNotificationsUIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c001c` | `0x1bd718` | **`-0x2904`** |
| `__AUTH_CONST.__const` | `0x51e8` | `0x4e08` | **`-0x3e0`** |
| `__AUTH_CONST.__objc_const` | `0x26bc8` | `0x269d8` | **`-0x1f0`** |
| `__DATA_DIRTY.__objc_data` | `0x3bc0` | `0x3a10` | **`-0x1b0`** |
| `__TEXT.__swift5_reflstr` | `0x12c1` | `0x1111` | **`-0x1b0`** |
| `__TEXT.__oslogstring` | `0x100b9` | `0x10239` | **`+0x180`** |
| `__TEXT.__constg_swiftt` | `0x1cd8` | `0x1bdc` | **`-0xfc`** |
| `__TEXT.__swift5_capture` | `0xd34` | `0xc44` | **`-0xf0`** |
| `__TEXT.__swift5_fieldmd` | `0x11ac` | `0x10e8` | **`-0xc4`** |
| `__DATA.__data` | `0x5248` | `0x51b0` | **`-0x98`** |
| `__TEXT.__eh_frame` | `0xd30` | `0xca8` | **`-0x88`** |
| `__DATA_DIRTY.__bss` | `0x1a88` | `0x1a08` | **`-0x80`** |
| `__AUTH_CONST.__auth_got` | `0x15a0` | `0x1528` | **`-0x78`** |
| `__TEXT.__unwind_info` | `0x7420` | `0x73a8` | **`-0x78`** |
| `__DATA_DIRTY.__data` | `0x16f0` | `0x1690` | **`-0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0xcb10` | `0xcb60` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x1acac` | `0x1ac5c` | **`-0x50`** |
| `__AUTH.__objc_data` | `0x24d8` | `0x2490` | **`-0x48`** |
| `__DATA_CONST.__got` | `0x18a8` | `0x1860` | **`-0x48`** |
| `__TEXT.__swift5_typeref` | `0x3d26` | `0x3ce2` | **`-0x44`** |
| `__AUTH_CONST.__cfstring` | `0x7ee0` | `0x7f20` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x1770` | `0x1798` | **`+0x28`** |
| `__TEXT.__cstring` | `0x9fcd` | `0x9fed` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x2d3c` | `0x2d54` | **`+0x18`** |
| `__DATA.__bss` | `0x14c8` | `0x14d8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x808` | `0x7f8` | **`-0x10`** |
| `__TEXT.__const` | `0x43e4` | `0x43d4` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x570` | `0x568` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x180` | `0x17c` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x12c` | `0x128` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x50` | `0x4c` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x2c` | `0x28` | **`-0x4`** |

### Other Changes

```diff

-1070.0.0.0.0
+1076.1.0.0.0

-  Functions: 10966
-  Symbols:   14408
-  CStrings:  2162
+  Functions: 10909
+  Symbols:   14419
+  CStrings:  2169
Symbols:
+ -[NCClickInteractionPresenter _handleActivation:]
+ -[NCClickInteractionPresenter activationAction]
+ -[NCClickInteractionPresenter activationTarget]
+ -[NCClickInteractionPresenter gestureRecognizer:shouldRecognizeSimultaneouslyWithGestureRecognizer:]
+ -[NCClickInteractionPresenter longPress]
+ -[NCClickInteractionPresenter setActivationAction:]
+ -[NCClickInteractionPresenter setActivationTarget:]
+ -[NCClickInteractionPresenter setLongPress:]
+ -[NCClickInteractionPresenter setTap:]
+ -[NCClickInteractionPresenter tap]
+ -[NCNotificationListCell actionButtonsBackgroundConfiguration]
+ -[NCNotificationOptionsMenu _contextMenuInteraction:styleForMenuWithConfiguration:]
+ -[NCNotificationOptionsMenu initWithNotificationRequest:presentingView:settingsDelegate:optionsForSection:shouldMenuOverlapSource:]
+ -[NCNotificationOptionsMenu setShouldMenuOverlapSource:]
+ -[NCNotificationOptionsMenu shouldMenuOverlapSource]
+ -[NCNotificationRootList beginContainerResize]
+ -[NCNotificationRootList endContainerResize]
+ -[NCNotificationSeamlessContentView _executeDeferredViewRemovals]
+ -[NCNotificationSeamlessContentView _fadeOutDeferredRemovalViews]
+ -[NCNotificationSeamlessContentView deferFadeOutAndRemovalOfView:]
+ -[NCNotificationStructuredListViewController _beginContainerResizeForReason:]
+ -[NCNotificationStructuredListViewController _endContainerResizeForReason:]
+ -[NCNotificationStructuredListViewController _presentOptionsMenuForNotificationRequest:withPresentingView:optionsForSection:shouldMenuOverlapSource:]
+ -[NCNotificationStructuredListViewController activeResizeReasons]
+ -[NCNotificationStructuredListViewController beginContainerResize]
+ -[NCNotificationStructuredListViewController endContainerResize]
+ -[NCNotificationStructuredListViewController setActiveResizeReasons:]
+ GCC_except_table101
+ GCC_except_table110
+ GCC_except_table113
+ GCC_except_table117
+ GCC_except_table118
+ GCC_except_table124
+ GCC_except_table137
+ GCC_except_table144
+ GCC_except_table177
+ GCC_except_table184
+ GCC_except_table187
+ GCC_except_table199
+ GCC_except_table204
+ GCC_except_table209
+ GCC_except_table231
+ GCC_except_table301
+ GCC_except_table68
+ GCC_except_table84
+ GCC_except_table89
+ GCC_except_table94
+ GCC_except_table97
+ _OBJC_CLASS_$__UIContextMenuStyle
+ _OBJC_IVAR_$_NCAppPickerViewHeader._warningHiddenConstraints
+ _OBJC_IVAR_$_NCAppPickerViewHeader._warningVisibleConstraints
+ _OBJC_IVAR_$_NCClickInteractionPresenter._activationAction
+ _OBJC_IVAR_$_NCClickInteractionPresenter._activationTarget
+ _OBJC_IVAR_$_NCClickInteractionPresenter._longPress
+ _OBJC_IVAR_$_NCClickInteractionPresenter._tap
+ _OBJC_IVAR_$_NCNotificationContentConfiguration._frameWidth
+ _OBJC_IVAR_$_NCNotificationOptionsMenu._shouldMenuOverlapSource
+ _OBJC_IVAR_$_NCNotificationSeamlessContentView._deferredRemovalViews
+ _OBJC_IVAR_$_NCNotificationStructuredListViewController._activeResizeReasons
+ __MergedGlobals
+ __NCIsRPBuild
+ ___51-[NCNotificationSeamlessContentView layoutSubviews]_block_invoke
+ ___51-[NCNotificationSeamlessContentView setFooterText:]_block_invoke
+ ___69-[NCNotificationSeamlessContentView setFooterSummaryAttributionText:]_block_invoke
+ ___76-[NCNotificationSeamlessContentView _configureImportantTextLabelIfNecessary]_block_invoke
+ ___81-[NCNotificationSeamlessContentView _layoutSubviewInBounds:measuringOnly:traits:]_block_invoke_20
+ ___81-[NCNotificationSeamlessContentView _layoutSubviewInBounds:measuringOnly:traits:]_block_invoke_21
+ ___81-[NCNotificationSeamlessContentView _layoutSubviewInBounds:measuringOnly:traits:]_block_invoke_22
+ ___NCPlatterActionButtonsAlwaysMorphMenus_block_invoke
+ ___block_descriptor_40_e8_32s_e49_v16?0?<v?"NCNotificationListCell""UIView"B>8ls32l8
+ ___block_descriptor_43_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_46_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_48_e8_32s40w_e49_v16?0?<v?"NCNotificationListCell""UIView"B>8lw40l8s32l8
+ ___block_descriptor_49_e8_32s40bs_e5_v8?0ls32l8s40l8
+ ___block_descriptor_49_e8_32s40s_e46_v28?0"NCNotificationListCell"8"UIView"16B24ls32l8s40l8
- +[NCMaterialCrossFadingView layerClass]
- -[NCMaterialCrossFadingView init]
- -[NCNotificationListCell removeLightEffectsIfNeeded]
- -[NCNotificationListSupplementaryHostingView removeLightEffectsIfNeeded]
- -[NCNotificationListSupplementaryHostingViewController removeLightEffectsIfNeeded]
- -[NCNotificationLongLookView removeLightEffectsIfNeeded]
- -[NCNotificationOptionsMenu contextMenuInteraction:configuration:highlightPreviewForItemWithIdentifier:]
- -[NCNotificationOptionsMenu initWithNotificationRequest:presentingView:settingsDelegate:optionsForSection:]
- -[NCNotificationShortLookView removeLightEffectsIfNeeded]
- -[NCNotificationShortLookView updateLightEffectToFillLightEnabled:edgeLightEnabled:duration:delay:]
- -[NCNotificationShortLookViewController _intelligenceLightAnimationIfNeeded]
- -[NCNotificationShortLookViewController handleWake:]
- -[NCNotificationStructuredListViewController _presentOptionsMenuForNotificationRequest:withPresentingView:optionsForSection:]
- -[NCNotificationStructuredSectionList _highlightsList]
- -[NCNotificationSummaryPlatterContainingView removeLightEffectsIfNeeded]
- -[NCNotificationViewController removeLightEffectsIfNeeded]
- GCC_except_table102
- GCC_except_table104
- GCC_except_table106
- GCC_except_table109
- GCC_except_table112
- GCC_except_table116
- GCC_except_table125
- GCC_except_table139
- GCC_except_table147
- GCC_except_table178
- GCC_except_table185
- GCC_except_table200
- GCC_except_table203
- GCC_except_table205
- GCC_except_table232
- GCC_except_table299
- GCC_except_table63
- GCC_except_table69
- GCC_except_table88
- GCC_except_table93
- GCC_except_table98
- _OBJC_CLASS_$_NCIntelligenceLightHandle
- _OBJC_CLASS_$_NCMaterialCrossFadingView
- _OBJC_CLASS_$__UIIntelligenceContentLightEffect
- _OBJC_CLASS_$__UIIntelligenceLightSourceDescriptor
- _OBJC_METACLASS_$_NCIntelligenceLightHandle
- _OBJC_METACLASS_$_NCMaterialCrossFadingView
- __DATA_NCIntelligenceLightHandle
- __INSTANCE_METHODS_NCIntelligenceLightHandle
- __IVARS_NCIntelligenceLightHandle
- __METACLASS_DATA_NCIntelligenceLightHandle
- __OBJC_$_CLASS_METHODS_NCMaterialCrossFadingView
- __OBJC_$_INSTANCE_METHODS_NCMaterialCrossFadingView
- __OBJC_CLASS_RO_$_NCMaterialCrossFadingView
- __OBJC_METACLASS_RO_$_NCMaterialCrossFadingView
- __PROPERTIES_NCIntelligenceLightHandle
- ___block_descriptor_40_e8_32s_e48_v16?0?<v?"NCNotificationListCell""UIView">8ls32l8
- ___block_descriptor_44_e8_32s_e5_v8?0ls32l8
- ___block_descriptor_45_e8_32s_e5_v8?0ls32l8
- ___block_descriptor_48_e8_32s40bs_e5_v8?0ls32l8s40l8
- ___block_descriptor_48_e8_32s40w_e48_v16?0?<v?"NCNotificationListCell""UIView">8lw40l8s32l8
- ___block_descriptor_49_e8_32s40s_e43_v24?0"NCNotificationListCell"8"UIView"16ls32l8s40l8
- _swift_retain_x8
- _symbolic So13NCPlatterViewCSgXw
- _symbolic So13NCPlatterViewCSgXwz_Xx
- _symbolic _____ 22UserNotificationsUIKit21HighlightsOverlayViewC17LightEffectsStateO
- _symbolic _____Sg 22UserNotificationsUIKit21HighlightsOverlayViewC17LightEffectsStateO
- _symbolic _____Sg 5UIKit6_GlassV24_IntelligenceLightHandleC
CStrings:
+ "%{public}@ activated due to tap: %{BOOL}d, longPress: %{BOOL}d"
+ "NCPlatterActionButtonsAlwaysMorphMenus"
+ "Notification list bounds view width changed to %.1f — invalidating cached size"
+ "Notification list container resize began (width=%{public}f)"
+ "Notification list container resize began — reason=%lu active=%lu"
+ "Notification list container resize ended (width=%{public}f, isWidthChanged=%{bool,public}d)"
+ "Notification list container resize ended — reason=%lu active=%lu"
+ "Notification list detaching from window — beginning re-parent container resize"
+ "Notification list frame view width changed to %.1f — invalidating cached size"
+ "Notification list moved to window %{public}@ (width=%.1f)"
+ "Notification list: skipping page recompute while a width resize is in progress (reason=%{public}s)"
+ "frameWidth"
+ "v16@?0@?<v@?@\"NCNotificationListCell\"@\"UIView\"B>8"
+ "v28@?0@\"NCNotificationListCell\"8@\"UIView\"16B24"
+ "verifyScrollPositionValid"
+ "\xf0\xe1"
- "HighlightsLightEffects"
- "HighlightsList light effect changing to: (fill: %{bool,public}d, edge: %{bool,public}d), reason: layout"
- "HighlightsList light effect changing to: (fill: %{bool,public}d, edge: %{bool,public}d, shouldAnimate: %{bool,public}d, reason: stateChange"
- "HighlightsList light effect changing to: 1, reason: wake"
- "HighlightsList light effect changing to: 2, reason: wake"
- "PriortyNotificationBackground"
- "v16@?0@?<v@?@\"NCNotificationListCell\"@\"UIView\">8"
- "v24@?0@\"NCNotificationListCell\"8@\"UIView\"16"
- "\xf0\xc1"
```
