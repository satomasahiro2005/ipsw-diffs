## AppStore

> `/private/var/staged_system_apps/AppStore.app/AppStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7479f0` | `0x75df34` | **`+0x16544`** |
| `__DATA.__objc_const` | `0x6a868` | `0x6cc00` | **`+0x2398`** |
| `__DATA_CONST.__const` | `0x24b38` | `0x25c00` | **`+0x10c8`** |
| `__TEXT.__const` | `0x34f34` | `0x35a94` | **`+0xb60`** |
| `__DATA.__data` | `0x29510` | `0x29f20` | **`+0xa10`** |
| `__DATA.__objc_data` | `0x29d18` | `0x2a5c8` | **`+0x8b0`** |
| `__TEXT.__objc_methname` | `0x1ee05` | `0x1f575` | **`+0x770`** |
| `__DATA.__bss` | `0x370d8` | `0x377e8` | **`+0x710`** |
| `__TEXT.__swift5_capture` | `0x7e34` | `0x8408` | **`+0x5d4`** |
| `__TEXT.__swift5_reflstr` | `0x17418` | `0x17988` | **`+0x570`** |
| `__TEXT.__swift5_fieldmd` | `0x121ac` | `0x12684` | **`+0x4d8`** |
| `__TEXT.__unwind_info` | `0x11d60` | `0x12160` | **`+0x400`** |
| `__TEXT.__constg_swiftt` | `0x19a70` | `0x19d48` | **`+0x2d8`** |
| `__TEXT.__objc_classname` | `0x9867` | `0x9b27` | **`+0x2c0`** |
| `__TEXT.__objc_methlist` | `0xdf24` | `0xe1c4` | **`+0x2a0`** |
| `__TEXT.__auth_stubs` | `0x167d0` | `0x16a40` | **`+0x270`** |
| `__TEXT.__objc_stubs` | `0xbb80` | `0xbdc0` | **`+0x240`** |
| `__TEXT.__swift5_typeref` | `0xf1d0` | `0xf398` | **`+0x1c8`** |
| `__DATA_CONST.__auth_got` | `0xb3f8` | `0xb530` | **`+0x138`** |
| `__DATA.__objc_selrefs` | `0x4cf0` | `0x4da0` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0x2a64` | `0x2b14` | **`+0xb0`** |
| `__DATA_CONST.__got` | `0x4d30` | `0x4dd0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x13095` | `0x13135` | **`+0xa0`** |
| `__DATA_CONST.__auth_ptr` | `0x6b58` | `0x6bd0` | **`+0x78`** |
| `__TEXT.__swift5_assocty` | `0x20a0` | `0x2110` | **`+0x70`** |
| `__DATA_CONST.__objc_classlist` | `0x13c8` | `0x1418` | **`+0x50`** |
| `__TEXT.__swift5_proto` | `0x1f9c` | `0x1fe0` | **`+0x44`** |
| `__DATA.__common` | `0x6f80` | `0x6fc0` | **`+0x40`** |
| `__TEXT.__swift5_types` | `0x1130` | `0x116c` | **`+0x3c`** |
| `__TEXT.__objc_methtype` | `0x659c` | `0x65bc` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x154` | `0x160` | **`+0xc`** |
| `__DATA.__objc_stublist` | `0x180` | `0x188` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x34` | `0x2c` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0xe0` | `0xe8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xdc` | `0xe4` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-27.0.50.0.0
+27.0.59.0.0

+  - /System/Library/Frameworks/CoreImage.framework/CoreImage

+  - /System/Library/PrivateFrameworks/ServicesIntelligence.framework/ServicesIntelligence

-  Functions: 27062
-  Symbols:   9625
-  CStrings:  7154
+  Functions: 27480
+  Symbols:   9682
+  CStrings:  7224
Symbols:
+ _$s10Foundation16AttributedStringV10charactersAC13CharacterViewVvg
+ _$s10Foundation16AttributedStringV13CharacterViewVMa
+ _$s10Foundation4UUIDV2eeoiySbAC_ACtFZ
+ _$s11AppStoreKit011DimensionalA10IconUIViewC6update14iconColorImageySo7UIImageCSg_tF
+ _$s11AppStoreKit011DimensionalA10IconUIViewCMa
+ _$s11AppStoreKit011DimensionalA10IconUIViewCMn
+ _$s11AppStoreKit10PageHeaderC5badgeSSSgvg
+ _$s11AppStoreKit10PageHeaderC5title10Foundation16AttributedStringVvg
+ _$s11AppStoreKit10PageHeaderC8subtitleSSSgvg
+ _$s11AppStoreKit10PageHeaderC9JetEngine14ComponentModelAAMc
+ _$s11AppStoreKit11ShelfHeaderC13ConfigurationV12eyebrowColor0g5ImageH005titleH00jiH00J9FontStyle08subtitleH009accessoryH016includeSeparator0O15TrailingArtwork07prefersdE0AESo7UIColorCSg_A3RSSSgA2RSbSgA2TtcfC
+ _$s11AppStoreKit11ShelfHeaderC13ConfigurationV14titleFontStyleSSSgvg
+ _$s11AppStoreKit14PageLayoutModeO8rawValueSSvg
+ _$s11AppStoreKit15AccountPageViewV11processInfo11objectGraphACSo010AMSProcessH0C_9JetEngine010BaseObjectJ0CtcfC
+ _$s11AppStoreKit15AccountPageViewVMn
+ _$s11AppStoreKit15MediaPageHeaderC13eyebrowSymbolSSSgvg
+ _$s11AppStoreKit15MediaPageHeaderC15backgroundColorSo7UIColorCSgvg
+ _$s11AppStoreKit15MediaPageHeaderC15collectionIconsSayAA7ArtworkCGSgvg
+ _$s11AppStoreKit15MediaPageHeaderC7eyebrowSSSgvg
+ _$s11AppStoreKit15MediaPageHeaderCMa
+ _$s11AppStoreKit15MediaPageHeaderCMn
+ _$s11AppStoreKit17RoundedButtonTypeOSQAAMc
+ _$s11AppStoreKit19JSFreshnessWatchdogC3bag12isOfflineBag0fH6Policy14networkInquiry7process04pushI15AdoptionEnabledAC9JetEngine0I0V_SbAA0ihJ0VSgAA07NetworkL0_pSo14AMSProcessInfoCSgSbtcfC
+ _$s11AppStoreKit20AppsAndPurchasesPageV5titleACSS_tcfC
+ _$s11AppStoreKit20PrimaryPagePrewarmerCACycfc
+ _$s11AppStoreKit20PrimaryPagePrewarmerCMa
+ _$s11AppStoreKit21PrimaryPagePrewarmingMp
+ _$s11AppStoreKit21PrimaryPagePrewarmingP07prewarmD4Data3url13isRunningPPTs8asPartOfy10Foundation3URLV_Sb9JetEngine15BaseObjectGraphCtFZTj
+ _$s11AppStoreKit24OnDemandCollectionActionC13sourceSurfaceSSSgvg
+ _$s11AppStoreKit24OnDemandCollectionActionC6adamIdAA04AdamI0Vvg
+ _$s11AppStoreKit24OnDemandCollectionActionC8seedIconAA7ArtworkCSgvg
+ _$s11AppStoreKit24OnDemandCollectionActionCMa
+ _$s11AppStoreKit24OnDemandCollectionActionCMn
+ _$s11AppStoreKit25MediumSummaryLockupLayoutV7MetricsV11artworkSize0I6Margin18titleNumberOfLines0L15SubtitleSpacing011offerButtonK00rsJ00rS5Space13layoutMarginsAeA11ConditionalVySo18UITraitEnvironment_pSo6CGSizeVG_AOySoAP_p12CoreGraphics7CGFloatVGSiAV5JetUI12AnyDimension_pA2RSo12UIEdgeInsetsVtcfC
+ _$s11AppStoreKit25MediumSummaryLockupLayoutV7MetricsV16offerButtonSpaceSo6CGSizeVvs
+ _$s11AppStoreKit28OnDemandCollectionPageIntentV2id6adamIdACs11AnyHashableV_AA04AdamK0VtcfC
+ _$s11AppStoreKit28OnDemandCollectionPageIntentV9JetEngine0H5ModelAAMc
+ _$s11AppStoreKit28OnDemandCollectionPageIntentVMa
+ _$s11AppStoreKit32AccountPageHostingViewControllerC11objectGraph7contentAC9JetEngine010BaseObjectJ0C_AA0deG0VyXEtcfc
+ _$s11AppStoreKit32BreakoutDetailsDisplayPropertiesV14DetailPositionOSQAAMc
+ _$s11AppStoreKit33TodayDiffablePageContentPresenterCAA07PrimaryF10PrewarmingAAWP
+ _$s11AppStoreKit33TodayDiffablePageContentPresenterCMa
+ _$s11AppStoreKit35GenericDiffablePageContentPresenterCAA07PrimaryF10PrewarmingAAWP
+ _$s11AppStoreKit35GenericDiffablePageContentPresenterCMa
+ _$s11AppStoreKit5ShelfC11ContentTypeO28onDemandCollectionPageHeaderyA2EmFWC
+ _$s12CoreGraphics7CGFloatV10FoundationE26_forceBridgeFromObjectiveC_6resultySo8NSNumberC_ACSgztFZ
+ _$s12CoreGraphics7CGFloatV10FoundationE34_conditionallyBridgeFromObjectiveC_6resultSbSo8NSNumberC_ACSgztFZ
+ _$s12CoreGraphics7CGFloatV10FoundationE36_unconditionallyBridgeFromObjectiveCyACSo8NSNumberCSgFZ
+ _$s17PromotedContentUI14AppStoreModuleC5getAd6config20appRequestMetaFields6adamId02adkM0_AA0deK4TaskCAA0dE6ConfigV_SDyS2SGSgSSSgANyAA0deH0C_AJtctF
+ _$s17PromotedContentUI19AppSearchAdLocationV13searchResultsACvgZ
+ _$s17PromotedContentUI19AppSearchAdLocationVMa
+ _$s17PromotedContentUI24AppSearchAdRequestFieldsV10storefront6locale8location10pageLayoutACSSSg_SSAA0deF8LocationVAHtcfC
+ _$s17PromotedContentUI25AppStoreAdRequestFieldKeyO10pageLayoutSSvgZ
+ _$s20ServicesIntelligence0aB8ProviderC26prepareLocationIfAvailibleyyYaF
+ _$s20ServicesIntelligence0aB8ProviderC26prepareLocationIfAvailibleyyYaFTu
+ _$s20ServicesIntelligence0aB8ProviderC6sharedACvgZ
+ _$s20ServicesIntelligence0aB8ProviderCMa
+ _$s5UIKit15UIMutableTraitsP11AppStoreKitE14pageLayoutModeAD04PagehI0Ovg
+ _$s5UIKit16UITraitOverridesV8containsySbAA0B10Definition_pXpF
+ _$s9JetEngine19AppMetricsPresenterC15didBecomeActiveyyF
+ _$s9JetEngine19AppMetricsPresenterC15didResignActiveyyF
+ _$s9JetEngine19AppMetricsPresenterC8pipelineAcA0D8PipelineV_tcfc
+ _$s9JetEngine19AppMetricsPresenterCMa
+ _$sSS10FoundationE11_charactersSSAA16AttributedStringV13CharacterViewV_tcfC
+ _$sSd9hashValueSivg
+ _$sSo16CGMutablePathRefa12CoreGraphicsE4move2to9transformySo7CGPointV_So17CGAffineTransformVtF
+ _$sSo16CGMutablePathRefa12CoreGraphicsE7addLine2to9transformySo7CGPointV_So17CGAffineTransformVtF
+ _$sSo8UIButtonC5UIKitE13ConfigurationV17borderedProminentAEyFZ
+ _CGPathCreateMutable
+ _OBJC_CLASS_$_CADisplayLink
+ _OBJC_CLASS_$_CIContext
+ _OBJC_CLASS_$_CIImage
+ _OBJC_CLASS_$_UIDeferredMenuElement
+ _UIFontDescriptorTraitsAttribute
+ _UIFontWeightTrait
+ _cos
+ _kCAAnimationPaced
+ _kCAFilterLightenBlendMode
+ _kCAGravityResize
+ _kCIContextUseSoftwareRenderer
+ _swift_retain_x12
- _$s11AppStoreKit0A16ExitMetricsEventO8makeData9JetEngine0eH0VyFZ
- _$s11AppStoreKit0A17EnterMetricsEventO8makeData9enterKind9JetEngine0eH0VAC0dJ0O_tFZ
- _$s11AppStoreKit11ShelfHeaderC13ConfigurationV12eyebrowColor0g5ImageH005titleH00jiH008subtitleH009accessoryH016includeSeparator0M15TrailingArtwork07prefersdE0AESo7UIColorCSg_A5QSbSgA2RtcfC
- _$s11AppStoreKit14ResizingConfigV19ReflectionDirectionOSQAAMc
- _$s11AppStoreKit14UpsellBreakoutC5videoAA5VideoCSgvg
- _$s11AppStoreKit17AccountV2PageViewV11processInfo11objectGraphACSo010AMSProcessI0C_9JetEngine010BaseObjectK0CtcfC
- _$s11AppStoreKit17AccountV2PageViewVMn
- _$s11AppStoreKit19JSFreshnessWatchdogC3bag12isOfflineBag0fH6Policy14networkInquiry7processAC9JetEngine0I0V_SbAA0ihJ0VSgAA07NetworkL0_pSo14AMSProcessInfoCSgtcfC
- _$s11AppStoreKit25MediumSummaryLockupLayoutV7MetricsV11artworkSize0I6Margin18titleNumberOfLines0L15SubtitleSpacing011offerButtonK00rsJ013layoutMarginsAeA11ConditionalVySo18UITraitEnvironment_pSo6CGSizeVG_ANySoAO_p12CoreGraphics7CGFloatVGSiAU5JetUI12AnyDimension_pAQSo12UIEdgeInsetsVtcfC
- _$s11AppStoreKit32AccountPageHostingViewControllerC11objectGraph7contentAC9JetEngine010BaseObjectJ0C_AA0d2V2eG0VyXEtcfc
- _$s17PromotedContentUI14AppStoreModuleC5getAd6config20appRequestMetaFields6adamId_AA0deK4TaskCAA0dE6ConfigV_SDyS2SGSgSSSgyAA0deH0C_AItctF
- _$s17PromotedContentUI24AppSearchAdRequestFieldsV10storefront6localeACSSSg_SStcfC
- _$s5UIKit15UIMutableTraitsPAAE19horizontalSizeClassSo015UIUserInterfaceeF0Vvs
- _$s7SwiftUI9UnitPointV2eeoiySbAC_ACtFZ
- _$s7SwiftUI9UnitPointVMn
- _$s9JetEngine7PromiseC6always2on7performyAA13TaskScheduler_p_yACyxGctF
- _$sSi10FoundationE26_forceBridgeFromObjectiveC_6resultySo8NSNumberC_SiSgztFZ
- _$sSi10FoundationE34_conditionallyBridgeFromObjectiveC_6resultSbSo8NSNumberC_SiSgztFZ
- _$sSi10FoundationE36_unconditionallyBridgeFromObjectiveCySiSo8NSNumberCSgFZ
- _$sSi9hashValueSivg
- _CGRectUnion
- _OBJC_CLASS_$_UIImpactFeedbackGenerator
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "$__lazy_storage_$_cancelButton"
+ "$__lazy_storage_$_dimmingView"
+ "$__lazy_storage_$_rightColumnScrollView"
+ "$__lazy_storage_$_textStack"
+ "$__lazy_storage_$_tryAgainButton"
+ "AppStore.BlurView"
+ "AppStore.OnDemandCollectionCancelAnimation"
+ "AppStore.OnDemandCollectionLoadingViewController"
+ "AppStore.OnDemandCollectionOpenAnimation"
+ "AppStore.OnDemandCollectionPresentingTransitioningDelegate"
+ "AppStore.OnDemandCollectionRevealAnimation"
+ "AppStore.OnDemandCollectionRevealTransitioningDelegate"
+ "AppStore/MixedMediaView+BlurView.swift"
+ "AppStore/OnDemandCollectionGradientView.swift"
+ "AppStore/OnDemandCollectionLoadingViewController.swift"
+ "AppStore/OnDemandCollectionMediaPageHeaderCell.swift"
+ "AppsAndPurchases.PageTitle"
+ "Card Size Category"
+ "Compact Extra Wide"
+ "Enable the the on screen copy feed url button for quick access"
+ "Force every Today card into one size category; sizes that can't fit this width are disabled"
+ "OnDemandCollectionMediaPageHeaderCell does not support orthogonal rendering"
+ "OnDemandCollectionPageIntent"
+ "ProductPage.Section.OnDemandCollections.Button.Cancel"
+ "ProductPage.Section.OnDemandCollections.Button.TryAgain"
+ "ProductPage.Section.OnDemandCollections.Error.Retryable"
+ "ProductPage.Section.OnDemandCollections.Loading.Caption"
+ "TodaySettings.cardSizeCategorySelector"
+ "_TtC8AppStore30OnDemandCollectionGradientView"
+ "_TtC8AppStore31OnDemandCollectionFeatheredMask"
+ "_TtC8AppStore31OnDemandCollectionOpenAnimation"
+ "_TtC8AppStore33OnDemandCollectionCancelAnimation"
+ "_TtC8AppStore33OnDemandCollectionRevealAnimation"
+ "_TtC8AppStore36OnDemandCollectionAuroraGradientView"
+ "_TtC8AppStore37OnDemandCollectionMediaPageHeaderCell"
+ "_TtC8AppStore39OnDemandCollectionLoadingViewController"
+ "_TtC8AppStore44OnDemandCollectionDiffablePageViewController"
+ "_TtC8AppStore45OnDemandCollectionRevealTransitioningDelegate"
+ "_TtC8AppStore47OnDemandCollectionLoadingPresentationController"
+ "_TtC8AppStore49OnDemandCollectionPresentingTransitioningDelegate"
+ "_TtC8AppStore54OnDemandCollectionPageHeaderCollectionElementsObserver"
+ "_TtCC8AppStore14MixedMediaView8BlurView"
+ "addKeyframeWithRelativeStartTime:relativeDuration:animations:"
+ "addToRunLoop:forMode:"
+ "additionalMask"
+ "additionalMaskGradientLayer"
+ "animateKeyframesWithDuration:delay:options:animations:completion:"
+ "animationsPaused"
+ "appPromotionArticle"
+ "autoDispatchesIntent"
+ "backdropColors"
+ "backgroundFill"
+ "backgroundFillLayer"
+ "blobLayers"
+ "blobs"
+ "bottomFadeOverlay"
+ "bottomFadeStart"
+ "captionContainer"
+ "captionSheenGradient"
+ "captionSheenLabel"
+ "cardSizeCategoryButton"
+ "centerXAnchor"
+ "centerYAnchor"
+ "circleCenter"
+ "circleCompletion"
+ "circleDuration"
+ "circleFrom"
+ "circleStart"
+ "circleTo"
+ "collectionPageNavigationController"
+ "constraintGreaterThanOrEqualToAnchor:constant:"
+ "constraintLessThanOrEqualToAnchor:constant:"
+ "copyFeedPreviewButton"
+ "createCGImage:fromRect:"
+ "didTapCancel"
+ "didTapTryAgain"
+ "displayLink"
+ "displayLinkWithTarget:selector:"
+ "document.on.document"
+ "elementWithUncachedProvider:"
+ "errorLabel"
+ "exclamationmark.triangle"
+ "extent"
+ "featheredMask"
+ "fill"
+ "fillsWidth"
+ "getHue:saturation:brightness:alpha:"
+ "handlePressDown"
+ "handlePressUp"
+ "hasDispatchedDiscoverIntent"
+ "headerCell"
+ "highlight"
+ "highlightCenterYFactor"
+ "highlightLayer"
+ "iPad layouts only"
+ "iconFetchKey"
+ "iconHandlerKey"
+ "imageByApplyingGaussianBlurWithSigma:"
+ "imageByCroppingToRect:"
+ "imageWithTintColor:renderingMode:"
+ "initWithDisplayP3Red:green:blue:alpha:"
+ "initWithHue:saturation:brightness:alpha:"
+ "initWithOptions:"
+ "lastLaidOutSize"
+ "loadingViewController"
+ "maskContainer"
+ "maskLayers"
+ "onCancel"
+ "onDemandCollection"
+ "onHeaderDisplayed"
+ "onRetry"
+ "preferredFormat"
+ "primaryMaskGradientLayer"
+ "retainedTransitioningDelegate"
+ "revealTransitioningDelegate"
+ "secondarySystemFillColor"
+ "seedIcon"
+ "seedIconImage"
+ "setFill"
+ "sourceLayer"
+ "sourceSurface"
+ "storedArtworkLoader"
+ "storefront"
+ "tick"
+ "tickConcentric"
+ "updateShortcutItems"
+ "v16@?0@?<v@?@\"NSArray\">8"
+ "widthAnchor"
- "$__lazy_storage_$_debugPreviewUrlGestureRecognizer"
- "AppStore.BlurArea"
- "AppStore.BlurCoordinatorView"
- "AppStore/MixedMediaView+BlurAreaView.swift"
- "AppStore/MixedMediaView+BlurCoordinatorView.swift"
- "Enable the ability to toggle between all the different size classes that will fit on the current device"
- "Long press today page title to copy feed preview url to clipboard"
- "Metrics Exit Event"
- "Select Size Class"
- "Size Class 1 (320pt)"
- "Size Class 1 (320pt), iPhone"
- "Size Class 1 (374pt)"
- "Size Class 1 (374pt), iPhone"
- "Size Class 2 (375pt)"
- "Size Class 2 (375pt), iPhone"
- "Size Class 2 (460pt), iPhone"
- "Size Class 2 (500pt)"
- "Size Class 3 (501pt)"
- "Size Class 3 (704pt)"
- "Size Class 4 Large (773pt)"
- "Size Class 4 Large (981pt)"
- "Size Class 4 Small (705pt)"
- "Size Class 4 Small (772pt)"
- "Size Class 5 (1194pt)"
- "Size Class 5 (982pt)"
- "Size Class 6 (1195pt)"
- "Size Class 6 (1499pt)"
- "Size Class 7 (1500pt)"
- "Size Class 7 (2499pt)"
- "Size Class 8 (2500pt)"
- "Size Class 8 (Full Width)"
- "Size Class Toggle"
- "TodaySettings.sizeClassSelector"
- "_TtC8AppStore26AppEnterExitEventWatchdoge"
- "_TtCC8AppStore14MixedMediaView19BlurCoordinatorView"
- "_TtCC8AppStore14MixedMediaView8BlurArea"
- "beginBackgroundTaskWithName:expirationHandler:"
- "blurCoordinatorView"
- "darkening"
- "debugSizeClass"
- "didLongPressTitleWithGestureRecognizer:"
- "didTapVideo"
- "endBackgroundTask:"
- "eventWatchdoge"
- "foregroundBlurArea"
- "gestureRecognizers"
- "gradientMask"
- "hasEverEntered"
- "hasSentExit"
- "impactOccurred"
- "maskGradientLayer"
- "prepare"
- "rectangle.3.offgrid"
- "reflectionBlur"
- "reflectionBlurArea"
- "screen"
- "sizeClassToggleButton"
- "todayGridDeviceType"
```
