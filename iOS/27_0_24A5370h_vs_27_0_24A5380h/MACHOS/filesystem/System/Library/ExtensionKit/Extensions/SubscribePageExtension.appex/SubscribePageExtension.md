## SubscribePageExtension

> `/System/Library/ExtensionKit/Extensions/SubscribePageExtension.appex/SubscribePageExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70072c` | `0x715a04` | **`+0x152d8`** |
| `__DATA.__objc_const` | `0x69948` | `0x6bdd8` | **`+0x2490`** |
| `__DATA_CONST.__const` | `0x23140` | `0x24160` | **`+0x1020`** |
| `__TEXT.__const` | `0x36b64` | `0x377a4` | **`+0xc40`** |
| `__DATA.__data` | `0x28360` | `0x28e70` | **`+0xb10`** |
| `__DATA.__bss` | `0x35028` | `0x359b8` | **`+0x990`** |
| `__DATA.__objc_data` | `0x29a48` | `0x2a300` | **`+0x8b8`** |
| `__TEXT.__objc_methname` | `0x1d345` | `0x1db55` | **`+0x810`** |
| `__TEXT.__swift5_capture` | `0x77a0` | `0x7d6c` | **`+0x5cc`** |
| `__TEXT.__swift5_reflstr` | `0x16de5` | `0x17375` | **`+0x590`** |
| `__TEXT.__swift5_fieldmd` | `0x11ce0` | `0x121ec` | **`+0x50c`** |
| `__TEXT.__unwind_info` | `0x11ce8` | `0x120f0` | **`+0x408`** |
| `__TEXT.__objc_classname` | `0xbce6` | `0xc076` | **`+0x390`** |
| `__TEXT.__constg_swiftt` | `0x19218` | `0x19570` | **`+0x358`** |
| `__TEXT.__objc_methlist` | `0xd9b4` | `0xdc2c` | **`+0x278`** |
| `__TEXT.__objc_stubs` | `0xaf00` | `0xb160` | **`+0x260`** |
| `__TEXT.__auth_stubs` | `0x152b0` | `0x15450` | **`+0x1a0`** |
| `__TEXT.__swift5_typeref` | `0xef50` | `0xf0e4` | **`+0x194`** |
| `__TEXT.__cstring` | `0x10c69` | `0x10d79` | **`+0x110`** |
| `__DATA_CONST.__auth_got` | `0xa968` | `0xaa38` | **`+0xd0`** |
| `__DATA.__objc_selrefs` | `0x4690` | `0x4748` | **`+0xb8`** |
| `__DATA_CONST.__got` | `0x47d0` | `0x4860` | **`+0x90`** |
| `__TEXT.__swift5_assocty` | `0x1ec0` | `0x1f40` | **`+0x80`** |
| `__DATA_CONST.__auth_ptr` | `0x65b8` | `0x6628` | **`+0x70`** |
| `__DATA.__common` | `0x6e90` | `0x6ef0` | **`+0x60`** |
| `__DATA_CONST.__objc_classlist` | `0x1370` | `0x13c8` | **`+0x58`** |
| `__TEXT.__swift5_proto` | `0x1e90` | `0x1ee8` | **`+0x58`** |
| `__TEXT.__swift5_types` | `0x10a8` | `0x10e8` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x5664` | `0x5694` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0x3c0` | `0x3d4` | **`+0x14`** |
| `__DATA.__objc_stublist` | `0x180` | `0x188` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x34` | `0x2c` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-27.0.50.0.0
+27.0.59.0.0

+  - /System/Library/Frameworks/CoreImage.framework/CoreImage

-  Functions: 26342
-  Symbols:   860
-  CStrings:  6680
+  Functions: 26751
+  Symbols:   870
+  CStrings:  6754
Symbols:
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
- _CGRectUnion
- _OBJC_CLASS_$_UIImpactFeedbackGenerator
- _swift_willThrowTypedImpl
CStrings:
+ "$__lazy_storage_$_cancelButton"
+ "$__lazy_storage_$_dimmingView"
+ "$__lazy_storage_$_rightColumnScrollView"
+ "$__lazy_storage_$_textStack"
+ "$__lazy_storage_$_tryAgainButton"
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
+ "SubscribePageExtension.BlurView"
+ "SubscribePageExtension.OnDemandCollectionCancelAnimation"
+ "SubscribePageExtension.OnDemandCollectionLoadingViewController"
+ "SubscribePageExtension.OnDemandCollectionOpenAnimation"
+ "SubscribePageExtension.OnDemandCollectionPresentingTransitioningDelegate"
+ "SubscribePageExtension.OnDemandCollectionRevealAnimation"
+ "SubscribePageExtension.OnDemandCollectionRevealTransitioningDelegate"
+ "SubscribePageExtension/MixedMediaView+BlurView.swift"
+ "SubscribePageExtension/OnDemandCollectionGradientView.swift"
+ "SubscribePageExtension/OnDemandCollectionLoadingViewController.swift"
+ "SubscribePageExtension/OnDemandCollectionMediaPageHeaderCell.swift"
+ "TodaySettings.cardSizeCategorySelector"
+ "_TtC22SubscribePageExtension30OnDemandCollectionGradientView"
+ "_TtC22SubscribePageExtension31OnDemandCollectionFeatheredMask"
+ "_TtC22SubscribePageExtension31OnDemandCollectionOpenAnimation"
+ "_TtC22SubscribePageExtension33OnDemandCollectionCancelAnimation"
+ "_TtC22SubscribePageExtension33OnDemandCollectionRevealAnimation"
+ "_TtC22SubscribePageExtension36OnDemandCollectionAuroraGradientView"
+ "_TtC22SubscribePageExtension37OnDemandCollectionMediaPageHeaderCell"
+ "_TtC22SubscribePageExtension39OnDemandCollectionLoadingViewController"
+ "_TtC22SubscribePageExtension44OnDemandCollectionDiffablePageViewController"
+ "_TtC22SubscribePageExtension45OnDemandCollectionRevealTransitioningDelegate"
+ "_TtC22SubscribePageExtension47OnDemandCollectionLoadingPresentationController"
+ "_TtC22SubscribePageExtension49OnDemandCollectionPresentingTransitioningDelegate"
+ "_TtC22SubscribePageExtension54OnDemandCollectionPageHeaderCollectionElementsObserver"
+ "_TtCC22SubscribePageExtension14MixedMediaView8BlurView"
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
+ "tick"
+ "tickConcentric"
+ "v16@?0@?<v@?@\"NSArray\">8"
+ "widthAnchor"
- "$__lazy_storage_$_debugPreviewUrlGestureRecognizer"
- "Enable the ability to toggle between all the different size classes that will fit on the current device"
- "Long press today page title to copy feed preview url to clipboard"
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
- "SubscribePageExtension.BlurArea"
- "SubscribePageExtension.BlurCoordinatorView"
- "SubscribePageExtension/MixedMediaView+BlurAreaView.swift"
- "SubscribePageExtension/MixedMediaView+BlurCoordinatorView.swift"
- "TodaySettings.sizeClassSelector"
- "_TtCC22SubscribePageExtension14MixedMediaView19BlurCoordinatorView"
- "_TtCC22SubscribePageExtension14MixedMediaView8BlurArea"
- "blurCoordinatorView"
- "darkening"
- "debugSizeClass"
- "didLongPressTitleWithGestureRecognizer:"
- "didTapVideo"
- "foregroundBlurArea"
- "gestureRecognizers"
- "gradientMask"
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
