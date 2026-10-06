## MediaControls

> `/System/Library/PrivateFrameworks/MediaControls.framework/MediaControls`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2044e0` | `0x208f14` | **`+0x4a34`** |
| `__AUTH_CONST.__objc_const` | `0x424c0` | `0x42c90` | **`+0x7d0`** |
| `__DATA.__bss` | `0x82b8` | `0x8608` | **`+0x350`** |
| `__AUTH.__objc_data` | `0x2ee0` | `0x3218` | **`+0x338`** |
| `__TEXT.__const` | `0xb1d4` | `0xb464` | **`+0x290`** |
| `__AUTH_CONST.__const` | `0x9cf0` | `0x9f00` | **`+0x210`** |
| `__TEXT.__swift5_reflstr` | `0x4563` | `0x4763` | **`+0x200`** |
| `__TEXT.__objc_methlist` | `0x154d4` | `0x156b4` | **`+0x1e0`** |
| `__TEXT.__swift5_fieldmd` | `0x4628` | `0x47c4` | **`+0x19c`** |
| `__TEXT.__cstring` | `0x69c4` | `0x6b34` | **`+0x170`** |
| `__DATA.__data` | `0x3e10` | `0x3f60` | **`+0x150`** |
| `__TEXT.__unwind_info` | `0x82a0` | `0x83c8` | **`+0x128`** |
| `__TEXT.__constg_swiftt` | `0x7120` | `0x722c` | **`+0x10c`** |
| `__DATA_CONST.__objc_selrefs` | `0xa3f8` | `0xa4d8` | **`+0xe0`** |
| `__AUTH.__data` | `0x10e0` | `0x1188` | **`+0xa8`** |
| `__TEXT.__swift5_typeref` | `0x321c` | `0x3280` | **`+0x64`** |
| `__TEXT.__oslogstring` | `0x8679` | `0x86b9` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1fc8` | `0x1f90` | **`-0x38`** |
| `__TEXT.__swift5_types` | `0x58c` | `0x5c4` | **`+0x38`** |
| `__DATA_CONST.__objc_classlist` | `0x970` | `0x990` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x448` | `0x468` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x11a0` | `0x11c0` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x5a8` | `0x5c0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1894` | `0x18a4` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x17b0` | `0x17c0` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x90` | `0xa0` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x25c0` | `0x25b0` | **`-0x10`** |
| `__DATA_DIRTY.__common` | `0x9d0` | `0x9c0` | **`-0x10`** |
| `__DATA_CONST.__objc_catlist` | `0xa0` | `0xa8` | **`+0x8`** |

### Other Changes

```diff

-4026.100.60.1.0
+4026.100.68.0.0

-  Functions: 13757
-  Symbols:   13663
-  CStrings:  1571
+  Functions: 13856
+  Symbols:   13703
+  CStrings:  1585
Symbols:
+ -[MRUEndpointController isCustomProtocolRoute]
+ -[MRULockscreenViewController viewDidMoveToWindow:shouldAppearOrDisappear:]
+ -[MRUMediaSuggestionsView didMoveToWindow]
+ -[MRUMediaSuggestionsView hasLimitedSize]
+ -[MRUMediaSuggestionsView setHasLimitedSize:]
+ -[MRUNowPlayingView updateForSizeClass]
+ -[MRUVolumeBackgroundView geometryProvider]
+ -[MRUVolumeBackgroundView setGeometryProvider:]
+ -[MRUVolumeBackgroundViewController contentModuleContext]
+ -[MRUVolumeBackgroundViewController setContentModuleContext:]
+ -[MRUVolumeView geometryProvider]
+ -[MRUVolumeView setGeometryProvider:]
+ -[MRUVolumeViewController contentModuleContext]
+ -[MRUVolumeViewController setContentModuleContext:]
+ _OBJC_CLASS_$_MRUCCUIGeometryUtilities
+ _OBJC_CLASS_$_NSNull
+ _OBJC_CLASS_$__TtC13MediaControls30InAppRoutePickerBackgroundView
+ _OBJC_CLASS_$__TtCC13MediaControls30InAppRoutePickerBackgroundView7DimView
+ _OBJC_CLASS_$__TtCC13MediaControls30InAppRoutePickerBackgroundView8BlurView
+ _OBJC_IVAR_$_MRUMediaSuggestionsView._hasLimitedSize
+ _OBJC_IVAR_$_MRUVolumeBackgroundView._geometryProvider
+ _OBJC_IVAR_$_MRUVolumeBackgroundViewController._contentModuleContext
+ _OBJC_IVAR_$_MRUVolumeView._geometryProvider
+ _OBJC_IVAR_$_MRUVolumeViewController._contentModuleContext
+ _OBJC_METACLASS_$_MRUCCUIGeometryUtilities
+ _OBJC_METACLASS_$__TtC13MediaControls30InAppRoutePickerBackgroundView
+ _OBJC_METACLASS_$__TtC13MediaControlsP33_79FE463E04BCE6831246FFB905280E0443InAppRoutePickerBackgroundAnimationDelegate
+ _OBJC_METACLASS_$__TtCC13MediaControls30InAppRoutePickerBackgroundView7DimView
+ _OBJC_METACLASS_$__TtCC13MediaControls30InAppRoutePickerBackgroundView8BlurView
+ __CATEGORY_INSTANCE_METHODS_UIViewController_$_MediaControls
+ __CATEGORY_UIViewController_$_MediaControls
+ __CLASS_METHODS_MRUCCUIGeometryUtilities
+ __DATA_MRUCCUIGeometryUtilities
+ __DATA__TtC13MediaControls30InAppRoutePickerBackgroundView
+ __DATA__TtC13MediaControlsP33_79FE463E04BCE6831246FFB905280E0443InAppRoutePickerBackgroundAnimationDelegate
+ __DATA__TtCC13MediaControls30InAppRoutePickerBackgroundView7DimView
+ __DATA__TtCC13MediaControls30InAppRoutePickerBackgroundView8BlurView
+ __INSTANCE_METHODS_MRUCCUIGeometryUtilities
+ __INSTANCE_METHODS__TtC13MediaControls30InAppRoutePickerBackgroundView
+ __INSTANCE_METHODS__TtC13MediaControlsP33_79FE463E04BCE6831246FFB905280E0443InAppRoutePickerBackgroundAnimationDelegate
+ __INSTANCE_METHODS__TtCC13MediaControls30InAppRoutePickerBackgroundView7DimView
+ __INSTANCE_METHODS__TtCC13MediaControls30InAppRoutePickerBackgroundView8BlurView
+ __IVARS__TtC13MediaControls30InAppRoutePickerBackgroundView
+ __IVARS__TtCC13MediaControls30InAppRoutePickerBackgroundView7DimView
+ __IVARS__TtCC13MediaControls30InAppRoutePickerBackgroundView8BlurView
+ __METACLASS_DATA_MRUCCUIGeometryUtilities
+ __METACLASS_DATA__TtC13MediaControls30InAppRoutePickerBackgroundView
+ __METACLASS_DATA__TtC13MediaControlsP33_79FE463E04BCE6831246FFB905280E0443InAppRoutePickerBackgroundAnimationDelegate
+ __METACLASS_DATA__TtCC13MediaControls30InAppRoutePickerBackgroundView7DimView
+ __METACLASS_DATA__TtCC13MediaControls30InAppRoutePickerBackgroundView8BlurView
+ __OBJC_$_INSTANCE_METHODS_UITraitCollection(MediaControls|MediaControls)
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CABackdropLayerDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CALayerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CABackdropLayerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CALayerDelegate
+ __OBJC_$_PROTOCOL_REFS_CABackdropLayerDelegate
+ __OBJC_$_PROTOCOL_REFS_CALayerDelegate
+ __OBJC_LABEL_PROTOCOL_$_CABackdropLayerDelegate
+ __OBJC_LABEL_PROTOCOL_$_CALayerDelegate
+ __OBJC_PROTOCOL_$_CABackdropLayerDelegate
+ __OBJC_PROTOCOL_$_CALayerDelegate
+ __PROTOCOLS__TtC13MediaControlsP33_79FE463E04BCE6831246FFB905280E0443InAppRoutePickerBackgroundAnimationDelegate
+ _associated conformance 13MediaControls30InAppRoutePickerBackgroundViewC5StyleO8FadeEdgeOSHAASQ
+ _kCAFilterInputSourceSublayerName
+ _kCAFilterVariableBlur
+ _symbolic So15CABackdropLayerC
+ _symbolic So15CAGradientLayerCSg
+ _symbolic _____ 13MediaControls30ControlCenterGeometryUtilitiesC
+ _symbolic _____ 13MediaControls30InAppRoutePickerBackgroundViewC
+ _symbolic _____ 13MediaControls30InAppRoutePickerBackgroundViewC03DimH0C
+ _symbolic _____ 13MediaControls30InAppRoutePickerBackgroundViewC04BlurH0C
+ _symbolic _____ 13MediaControls30InAppRoutePickerBackgroundViewC04BlurH0C4ModeO
+ _symbolic _____ 13MediaControls30InAppRoutePickerBackgroundViewC5StyleO
+ _symbolic _____ 13MediaControls30InAppRoutePickerBackgroundViewC5StyleO8FadeEdgeO
+ _symbolic _____ 13MediaControls43InAppRoutePickerBackgroundAnimationDelegate030_79FE463E04BCE6831246FFB905280K0LLC
+ _symbolic _____Sg 13MediaControls30InAppRoutePickerBackgroundViewC03DimH0C
+ _symbolic _____Sg 13MediaControls30InAppRoutePickerBackgroundViewC04BlurH0C
- -[MRUMediaSuggestionsView contentScale]
- -[MRUMediaSuggestionsView setContentScale:]
- GCC_except_table31
- _CCUIItemEdgeSize
- _CCUILayoutGutter
- _CCUILayoutShouldBePortrait
- _CCUIReferenceScreenBounds
- _CCUIScreenBounds
- _CCUISliderExpandedContentModuleHeight
- _CCUISliderExpandedContentModuleWidth
- _CCUISliderExpandedModuleContinuousCornerRadius
- _CGFloatIsValid
- _MRUDefaultExpandedWidth
- _MRUExpandedContentInsets
- _MRUExpandedTallWidth
- _MRUExpandedWideWidth
- _MRUHorizontalScreenInset
- _MRUIsSmallScreen
- _MRUIsSmallScreen.__isSmallScreen
- _MRUIsSmallScreen.onceToken
- _MRUIsSmallScreenWithScale
- _MRUIsSmallScreenWithScale.__isPhone
- _MRUIsSmallScreenWithScale.__referenceScreenBounds
- _MRUIsSmallScreenWithScale.onceToken
- _MRUVerticalScreenInset
- _OBJC_IVAR_$_MRUMediaSuggestionsView._contentScale
- _OBJC_METACLASS_$__TtC13MediaControlsP33_F10E2EE4A69D0F86BEFB6F858320AEC030InAppRoutePickerBackgroundView
- __DATA__TtC13MediaControlsP33_F10E2EE4A69D0F86BEFB6F858320AEC030InAppRoutePickerBackgroundView
- __INSTANCE_METHODS__TtC13MediaControlsP33_F10E2EE4A69D0F86BEFB6F858320AEC030InAppRoutePickerBackgroundView
- __IVARS__TtC13MediaControlsP33_F10E2EE4A69D0F86BEFB6F858320AEC030InAppRoutePickerBackgroundView
- __METACLASS_DATA__TtC13MediaControlsP33_F10E2EE4A69D0F86BEFB6F858320AEC030InAppRoutePickerBackgroundView
- __OBJC_$_CATEGORY_INSTANCE_METHODS_UITraitCollection_$_MediaControls
- __OBJC_$_PROP_LIST_UITraitCollection_$_MediaControls
- ___MRUIsSmallScreenWithScale_block_invoke
- ___MRUIsSmallScreen_block_invoke
- _symbolic _____ 13MediaControls30InAppRoutePickerBackgroundView33_F10E2EE4A69D0F86BEFB6F858320AEC0LLC
- _symbolic _____Sg_ABt 12MediaControl15RoutingControlsV022RequestAdditionalItemsB0V
CStrings:
+ "1!"
+ "B"
+ "MediaControls/InAppRoutePickerBackgroundView+BlurView.swift"
+ "[%s] backgroundStyle=%s"
+ "[%s] contentFrame=%s"
+ "[%s] mode=%s"
+ "[%s] style=%s"
+ "cayenne.backgroundBlur.allEdgesPadding"
+ "cayenne.backgroundBlur.featherMaskGaussianRadius"
+ "cayenne.backgroundBlur.featherMaskInset"
+ "cayenne.backgroundBlur.singleEdgePadding"
+ "cayenne.showsBlurMaskDebugView"
+ "cayenne.showsBlurTrackingDebugView"
+ "\x81"
+ "\x91"
- "[%s] isActive=%{bool}d"
```
