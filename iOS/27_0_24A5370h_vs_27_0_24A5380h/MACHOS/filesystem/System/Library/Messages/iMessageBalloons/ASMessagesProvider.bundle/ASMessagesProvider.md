## ASMessagesProvider

> `/System/Library/Messages/iMessageBalloons/ASMessagesProvider.bundle/ASMessagesProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7177e4` | `0x72ca08` | **`+0x15224`** |
| `__DATA.__objc_const` | `0x696a0` | `0x6bb30` | **`+0x2490`** |
| `__DATA_CONST.__const` | `0x236e8` | `0x246b8` | **`+0xfd0`** |
| `__DATA.__data` | `0x28a38` | `0x294f8` | **`+0xac0`** |
| `__TEXT.__const` | `0x37624` | `0x380b4` | **`+0xa90`** |
| `__DATA.__objc_data` | `0x29c88` | `0x2a540` | **`+0x8b8`** |
| `__TEXT.__objc_methname` | `0x1efc5` | `0x1f6f5` | **`+0x730`** |
| `__DATA.__bss` | `0x36048` | `0x366d8` | **`+0x690`** |
| `__TEXT.__swift5_capture` | `0x7894` | `0x7e4c` | **`+0x5b8`** |
| `__TEXT.__swift5_reflstr` | `0x172aa` | `0x1783a` | **`+0x590`** |
| `__TEXT.__swift5_fieldmd` | `0x11f3c` | `0x1242c` | **`+0x4f0`** |
| `__TEXT.__unwind_info` | `0x11eb0` | `0x12298` | **`+0x3e8`** |
| `__TEXT.__objc_classname` | `0xb372` | `0xb6d2` | **`+0x360`** |
| `__TEXT.__constg_swiftt` | `0x1979c` | `0x19ad4` | **`+0x338`** |
| `__TEXT.__objc_methlist` | `0xe234` | `0xe4ac` | **`+0x278`** |
| `__TEXT.__objc_stubs` | `0xb2e0` | `0xb520` | **`+0x240`** |
| `__TEXT.__auth_stubs` | `0x158e0` | `0x15a80` | **`+0x1a0`** |
| `__TEXT.__swift5_typeref` | `0xf238` | `0xf3b6` | **`+0x17e`** |
| `__TEXT.__cstring` | `0x13169` | `0x13249` | **`+0xe0`** |
| `__DATA_CONST.__auth_got` | `0xac80` | `0xad50` | **`+0xd0`** |
| `__DATA.__objc_selrefs` | `0x4c30` | `0x4cd8` | **`+0xa8`** |
| `__DATA_CONST.__got` | `0x49c0` | `0x4a38` | **`+0x78`** |
| `__DATA_CONST.__auth_ptr` | `0x6740` | `0x67b0` | **`+0x70`** |
| `__DATA_CONST.__objc_classlist` | `0x1378` | `0x13d0` | **`+0x58`** |
| `__DATA.__common` | `0x6f58` | `0x6fa8` | **`+0x50`** |
| `__TEXT.__swift5_assocty` | `0x1fe8` | `0x2038` | **`+0x50`** |
| `__TEXT.__swift5_proto` | `0x1f14` | `0x1f54` | **`+0x40`** |
| `__TEXT.__swift5_types` | `0x10dc` | `0x1118` | **`+0x3c`** |
| `__TEXT.__objc_methtype` | `0x62f0` | `0x6310` | **`+0x20`** |
| `__DATA.__objc_stublist` | `0x180` | `0x188` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x34` | `0x2c` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_builtin`
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

-  Functions: 26555
-  Symbols:   869
-  CStrings:  7017
+  Functions: 26958
+  Symbols:   881
+  CStrings:  7088
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
+ "ASMessagesProvider.BlurView"
+ "ASMessagesProvider.OnDemandCollectionCancelAnimation"
+ "ASMessagesProvider.OnDemandCollectionLoadingViewController"
+ "ASMessagesProvider.OnDemandCollectionOpenAnimation"
+ "ASMessagesProvider.OnDemandCollectionPresentingTransitioningDelegate"
+ "ASMessagesProvider.OnDemandCollectionRevealAnimation"
+ "ASMessagesProvider.OnDemandCollectionRevealTransitioningDelegate"
+ "ASMessagesProvider/MixedMediaView+BlurView.swift"
+ "ASMessagesProvider/OnDemandCollectionGradientView.swift"
+ "ASMessagesProvider/OnDemandCollectionLoadingViewController.swift"
+ "ASMessagesProvider/OnDemandCollectionMediaPageHeaderCell.swift"
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
+ "_TtC18ASMessagesProvider30OnDemandCollectionGradientView"
+ "_TtC18ASMessagesProvider31OnDemandCollectionFeatheredMask"
+ "_TtC18ASMessagesProvider31OnDemandCollectionOpenAnimation"
+ "_TtC18ASMessagesProvider33OnDemandCollectionCancelAnimation"
+ "_TtC18ASMessagesProvider33OnDemandCollectionRevealAnimation"
+ "_TtC18ASMessagesProvider36OnDemandCollectionAuroraGradientView"
+ "_TtC18ASMessagesProvider37OnDemandCollectionMediaPageHeaderCell"
+ "_TtC18ASMessagesProvider39OnDemandCollectionLoadingViewController"
+ "_TtC18ASMessagesProvider44OnDemandCollectionDiffablePageViewController"
+ "_TtC18ASMessagesProvider45OnDemandCollectionRevealTransitioningDelegate"
+ "_TtC18ASMessagesProvider47OnDemandCollectionLoadingPresentationController"
+ "_TtC18ASMessagesProvider49OnDemandCollectionPresentingTransitioningDelegate"
+ "_TtC18ASMessagesProvider54OnDemandCollectionPageHeaderCollectionElementsObserver"
+ "_TtCC18ASMessagesProvider14MixedMediaView8BlurView"
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
- "ASMessagesProvider.BlurArea"
- "ASMessagesProvider.BlurCoordinatorView"
- "ASMessagesProvider/MixedMediaView+BlurAreaView.swift"
- "ASMessagesProvider/MixedMediaView+BlurCoordinatorView.swift"
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
- "_TtCC18ASMessagesProvider14MixedMediaView19BlurCoordinatorView"
- "_TtCC18ASMessagesProvider14MixedMediaView8BlurArea"
- "beginBackgroundTaskWithName:expirationHandler:"
- "blurCoordinatorView"
- "darkening"
- "debugSizeClass"
- "didLongPressTitleWithGestureRecognizer:"
- "didTapVideo"
- "endBackgroundTask:"
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
