## ProductPageExtension

> `/System/Library/ExtensionKit/Extensions/ProductPageExtension.appex/ProductPageExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x71d924` | `0x7332d0` | **`+0x159ac`** |
| `__DATA.__objc_const` | `0x68d98` | `0x6b248` | **`+0x24b0`** |
| `__DATA_CONST.__const` | `0x23268` | `0x24288` | **`+0x1020`** |
| `__TEXT.__const` | `0x36e64` | `0x37ad4` | **`+0xc70`** |
| `__DATA.__data` | `0x28ac8` | `0x295d8` | **`+0xb10`** |
| `__DATA.__bss` | `0x35230` | `0x35bc0` | **`+0x990`** |
| `__DATA.__objc_data` | `0x29c20` | `0x2a500` | **`+0x8e0`** |
| `__TEXT.__objc_methname` | `0x1da95` | `0x1e205` | **`+0x770`** |
| `__TEXT.__swift5_capture` | `0x78e0` | `0x7eac` | **`+0x5cc`** |
| `__TEXT.__swift5_reflstr` | `0x17369` | `0x17919` | **`+0x5b0`** |
| `__TEXT.__swift5_fieldmd` | `0x11f2c` | `0x12444` | **`+0x518`** |
| `__TEXT.__unwind_info` | `0x11dc0` | `0x121c8` | **`+0x408`** |
| `__TEXT.__objc_classname` | `0xb784` | `0xbb04` | **`+0x380`** |
| `__TEXT.__constg_swiftt` | `0x19728` | `0x19aa0` | **`+0x378`** |
| `__TEXT.__objc_stubs` | `0xb240` | `0xb4c0` | **`+0x280`** |
| `__TEXT.__objc_methlist` | `0xd924` | `0xdb9c` | **`+0x278`** |
| `__TEXT.__auth_stubs` | `0x15b10` | `0x15cf0` | **`+0x1e0`** |
| `__TEXT.__swift5_typeref` | `0xf14a` | `0xf2ec` | **`+0x1a2`** |
| `__TEXT.__cstring` | `0x138f5` | `0x13a05` | **`+0x110`** |
| `__DATA_CONST.__auth_got` | `0xad98` | `0xae88` | **`+0xf0`** |
| `__DATA.__objc_selrefs` | `0x47c0` | `0x4878` | **`+0xb8`** |
| `__DATA_CONST.__got` | `0x4a00` | `0x4a90` | **`+0x90`** |
| `__DATA_CONST.__auth_ptr` | `0x6718` | `0x6798` | **`+0x80`** |
| `__TEXT.__swift5_assocty` | `0x1ee0` | `0x1f60` | **`+0x80`** |
| `__DATA_CONST.__objc_classlist` | `0x1378` | `0x13d0` | **`+0x58`** |
| `__TEXT.__swift5_proto` | `0x1eb4` | `0x1f0c` | **`+0x58`** |
| `__DATA.__common` | `0x6f18` | `0x6f68` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x5674` | `0x56b4` | **`+0x40`** |
| `__TEXT.__swift5_types` | `0x10b4` | `0x10f4` | **`+0x40`** |
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

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 26489
-  Symbols:   870
-  CStrings:  6807
+  Functions: 26903
+  Symbols:   882
+  CStrings:  6881
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
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
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
+ "ProductPageExtension.BlurView"
+ "ProductPageExtension.OnDemandCollectionCancelAnimation"
+ "ProductPageExtension.OnDemandCollectionLoadingViewController"
+ "ProductPageExtension.OnDemandCollectionOpenAnimation"
+ "ProductPageExtension.OnDemandCollectionPresentingTransitioningDelegate"
+ "ProductPageExtension.OnDemandCollectionRevealAnimation"
+ "ProductPageExtension.OnDemandCollectionRevealTransitioningDelegate"
+ "ProductPageExtension/MixedMediaView+BlurView.swift"
+ "ProductPageExtension/OnDemandCollectionGradientView.swift"
+ "ProductPageExtension/OnDemandCollectionLoadingViewController.swift"
+ "ProductPageExtension/OnDemandCollectionMediaPageHeaderCell.swift"
+ "TodaySettings.cardSizeCategorySelector"
+ "_TtC20ProductPageExtension30OnDemandCollectionGradientView"
+ "_TtC20ProductPageExtension31OnDemandCollectionFeatheredMask"
+ "_TtC20ProductPageExtension31OnDemandCollectionOpenAnimation"
+ "_TtC20ProductPageExtension33OnDemandCollectionCancelAnimation"
+ "_TtC20ProductPageExtension33OnDemandCollectionRevealAnimation"
+ "_TtC20ProductPageExtension36OnDemandCollectionAuroraGradientView"
+ "_TtC20ProductPageExtension37OnDemandCollectionMediaPageHeaderCell"
+ "_TtC20ProductPageExtension39OnDemandCollectionLoadingViewController"
+ "_TtC20ProductPageExtension44OnDemandCollectionDiffablePageViewController"
+ "_TtC20ProductPageExtension45OnDemandCollectionRevealTransitioningDelegate"
+ "_TtC20ProductPageExtension47OnDemandCollectionLoadingPresentationController"
+ "_TtC20ProductPageExtension49OnDemandCollectionPresentingTransitioningDelegate"
+ "_TtC20ProductPageExtension54OnDemandCollectionPageHeaderCollectionElementsObserver"
+ "_TtCC20ProductPageExtension14MixedMediaView8BlurView"
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
- "ProductPageExtension.BlurArea"
- "ProductPageExtension.BlurCoordinatorView"
- "ProductPageExtension/MixedMediaView+BlurAreaView.swift"
- "ProductPageExtension/MixedMediaView+BlurCoordinatorView.swift"
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
- "_TtCC20ProductPageExtension14MixedMediaView19BlurCoordinatorView"
- "_TtCC20ProductPageExtension14MixedMediaView8BlurArea"
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
