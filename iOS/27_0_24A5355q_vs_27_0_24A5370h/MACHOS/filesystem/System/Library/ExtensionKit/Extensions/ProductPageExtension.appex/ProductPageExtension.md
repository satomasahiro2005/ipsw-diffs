## ProductPageExtension

> `/System/Library/ExtensionKit/Extensions/ProductPageExtension.appex/ProductPageExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70fd68` | `0x71d924` | **`+0xdbbc`** |
| `__DATA.__objc_const` | `0x68660` | `0x68d98` | **`+0x738`** |
| `__DATA_CONST.__const` | `0x22cd8` | `0x23268` | **`+0x590`** |
| `__TEXT.__const` | `0x36904` | `0x36e64` | **`+0x560`** |
| `__DATA.__objc_data` | `0x297d0` | `0x29c20` | **`+0x450`** |
| `__DATA.__data` | `0x28708` | `0x28ac8` | **`+0x3c0`** |
| `__TEXT.__swift5_typeref` | `0xee44` | `0xf14a` | **`+0x306`** |
| `__TEXT.__swift5_fieldmd` | `0x11c50` | `0x11f2c` | **`+0x2dc`** |
| `__DATA.__bss` | `0x34f90` | `0x35230` | **`+0x2a0`** |
| `__TEXT.__swift5_reflstr` | `0x170c9` | `0x17369` | **`+0x2a0`** |
| `__TEXT.__swift5_capture` | `0x76c0` | `0x78e0` | **`+0x220`** |
| `__TEXT.__eh_frame` | `0x2804` | `0x2a04` | **`+0x200`** |
| `__TEXT.__objc_methname` | `0x1d8a5` | `0x1da95` | **`+0x1f0`** |
| `__TEXT.__unwind_info` | `0x11bd0` | `0x11dc0` | **`+0x1f0`** |
| `__TEXT.__constg_swiftt` | `0x19550` | `0x19728` | **`+0x1d8`** |
| `__TEXT.__auth_stubs` | `0x15a00` | `0x15b10` | **`+0x110`** |
| `__TEXT.__objc_classname` | `0xb6a4` | `0xb784` | **`+0xe0`** |
| `__DATA_CONST.__auth_ptr` | `0x6688` | `0x6718` | **`+0x90`** |
| `__DATA_CONST.__auth_got` | `0xad10` | `0xad98` | **`+0x88`** |
| `__TEXT.__objc_methlist` | `0xd8a4` | `0xd924` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0xb1e0` | `0xb240` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x49c0` | `0x4a00` | **`+0x40`** |
| `__TEXT.__swift5_builtin` | `0x398` | `0x3c0` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x108c` | `0x10b4` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x1358` | `0x1378` | **`+0x20`** |
| `__TEXT.__cstring` | `0x138d5` | `0x138f5` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x1e9c` | `0x1eb4` | **`+0x18`** |
| `__TEXT.__swift5_mpenum` | `0x24` | `0x34` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x140` | `0x150` | **`+0x10`** |
| `__DATA.__common` | `0x6f20` | `0x6f18` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0x47b8` | `0x47c0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x1dc` | `0x1e4` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xd0` | `0xd8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xd0` | `0xd8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`

### Other Changes

```diff

-27.0.41.0.0
+27.0.50.0.0

+  - /System/Library/PrivateFrameworks/ContactsUICore.framework/ContactsUICore

-  - /System/Library/PrivateFrameworks/HealthExperienceUI.framework/HealthExperienceUI

-  Functions: 26313
-  Symbols:   869
-  CStrings:  6776
+  Functions: 26489
+  Symbols:   870
+  CStrings:  6807
Symbols:
+ _CGRectUnion
+ _OBJC_CLASS_$_NSHashTable
- _swift_retain_x12
CStrings:
+ "ProductPageExtension.BlurArea"
+ "ProductPageExtension.BlurCoordinatorView"
+ "ProductPageExtension.EditorialArtworkMirrorView"
+ "ProductPageExtension.EditorialVideoMirrorView"
+ "ProductPageExtension.Key"
+ "ProductPageExtension/EditorialArtworkMirrorView.swift"
+ "ProductPageExtension/EditorialArtworkView.swift"
+ "ProductPageExtension/EditorialVideoMirrorView.swift"
+ "ProductPageExtension/EditorialVideoView.swift"
+ "ProductPageExtension/MixedMediaView+BlurAreaView.swift"
+ "ProductPageExtension/MixedMediaView+BlurCoordinatorView.swift"
+ "ProductPageExtension/TodayCardEditorialArtworkView.swift"
+ "ProductPageExtension/TodayCardEditorialVideoView.swift"
+ "Size Class 2 (500pt)"
+ "Size Class 3 (501pt)"
+ "_TtC20ProductPageExtension18EditorialMediaView"
+ "_TtC20ProductPageExtension18EditorialVideoView"
+ "_TtC20ProductPageExtension20EditorialArtworkView"
+ "_TtC20ProductPageExtension22ProductMediaImageCache"
+ "_TtC20ProductPageExtension24EditorialVideoMirrorView"
+ "_TtC20ProductPageExtension26EditorialArtworkMirrorView"
+ "_TtC20ProductPageExtension27TodayCardEditorialVideoView"
+ "_TtC20ProductPageExtension29TodayCardEditorialArtworkView"
+ "_TtCC20ProductPageExtension14MixedMediaView19BlurCoordinatorView"
+ "_TtCC20ProductPageExtension14MixedMediaView8BlurArea"
+ "_TtCC20ProductPageExtension22ProductMediaImageCache3Key"
+ "_setMinimizeRestoreBehavior:"
+ "_setTitleMinimumMargins:"
+ "addObject:"
+ "allObjects"
+ "aspectRatio"
+ "blurCoordinatorView"
+ "containerHeightOverride"
+ "containerWidthOverride"
+ "crop"
+ "currentFetchHandlerKey"
+ "customBottomMargin"
+ "customTopMargin"
+ "darkening"
+ "editorialArtworkMirrorView"
+ "editorialVideoMirrorView"
+ "editorialVideoView"
+ "engine"
+ "externalMirrors"
+ "fillsBounds"
+ "foregroundBlur"
+ "foregroundBlurArea"
+ "gradientMask"
+ "imageLoadTask"
+ "inlineMediaWrapper"
+ "isAutoRefetchPaused"
+ "isTopBackgroundEffectViewHidden"
+ "lastFetchedBreakpoint"
+ "lastFetchedSize"
+ "lastSelectedTabIdentifier"
+ "maskGradientLayer"
+ "mirrorViews"
+ "otherViewToExchangeVideoContainerWith"
+ "overlayGradientLayer"
+ "overrideTraits"
+ "pagingAnimator"
+ "pendingFetch"
+ "plusDarkerGradientLayer"
+ "refetchAction"
+ "reflectionBlur"
+ "reflectionBlurArea"
+ "removeObject:"
+ "setAutomaticallyAdjustsScrollIndicatorInsets:"
+ "setBarMinimizeBehavior:"
+ "shouldApplyForegroundLegibilityBlur"
+ "shouldShowBottomKeylineForAboveUber"
+ "spec"
+ "template"
+ "topBackgroundEffectView"
+ "videoPlayerDelegates"
+ "visibleSupplementaryViewsOfKind:"
+ "weakObjectsHashTable"
- "ProductPageExtension.MirrorBlurView"
- "ProductPageExtension.ModuleOverlayGradientBlurView"
- "ProductPageExtension.RevealingImageMirrorView"
- "ProductPageExtension.RevealingVideoMirrorView"
- "ProductPageExtension.UpsellBreakoutSizingTraitEnvironment"
- "ProductPageExtension/MixedMediaView+MirrorBlurView.swift"
- "ProductPageExtension/ModuleOverlayGradientBlurView.swift"
- "ProductPageExtension/RevealingImageView.swift"
- "ProductPageExtension/RevealingMediaViewFrameBuilder.swift"
- "ProductPageExtension/RevealingVideoMirrorView.swift"
- "ProductPageExtension/RevealingVideoView.swift"
- "Size Class 2 (460pt)"
- "Size Class 3 (461pt)"
- "T@\"UITraitCollection\",N,&,VtraitCollection"
- "Uknown layout size"
- "_TtC20ProductPageExtension18RevealingImageView"
- "_TtC20ProductPageExtension18RevealingVideoView"
- "_TtC20ProductPageExtension24RevealingImageMirrorView"
- "_TtC20ProductPageExtension24RevealingVideoMirrorView"
- "_TtC20ProductPageExtension29ModuleOverlayGradientBlurView"
- "_TtC20ProductPageExtensionP33_18AA49E3A0089529D9EAA38FB165277F36UpsellBreakoutSizingTraitEnvironment"
- "_TtCC20ProductPageExtension14MixedMediaView14MirrorBlurView"
- "_isAnimatingScroll"
- "_setContentOffset:animated:animationCurve:animationAdjustsForContentOffsetDelta:animation:"
- "_setMinimizeBehavior:"
- "accessibilityIgnoresInvertColors"
- "artworkLayoutWithMetrics"
- "currentArtworkHandlerKey"
- "direction"
- "durationForEpsilon:"
- "effectVisibilityThreshold"
- "gradientMaskThreshold"
- "isBackgroundEffectViewHidden"
- "isFixingContentOffset"
- "mirrorBlurView"
- "mirrorDelegate"
- "moduleGradientView"
- "otherVideoViewToExchangeVideoContainerWith"
- "plusDarkerView"
- "previousLayoutWidth"
- "revealingImageView"
- "revealingVideoView"
- "setContentVerticalAlignment:"
- "setTraitCollection:"
- "verticalScrollIndicatorInsets"
- "videoPlayerDelegate"
```
