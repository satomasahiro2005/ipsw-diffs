## SpringBoardHome

> `/System/Library/PrivateFrameworks/SpringBoardHome.framework/SpringBoardHome`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x393d78` | `0x395728` | **`+0x19b0`** |
| `__TEXT.__oslogstring` | `0xf710` | `0xf840` | **`+0x130`** |
| `__AUTH_CONST.__const` | `0x7960` | `0x7a30` | **`+0xd0`** |
| `__AUTH_CONST.__objc_const` | `0x59120` | `0x591b0` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0x16f8` | `0x175c` | **`+0x64`** |
| `__TEXT.__objc_methlist` | `0x3edfc` | `0x3ee5c` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0xfa60` | `0xfab8` | **`+0x58`** |
| `__TEXT.__eh_frame` | `0xeb0` | `0xed8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1cc38` | `0x1cc58` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x6664` | `0x6680` | **`+0x1c`** |
| `__AUTH_CONST.__objc_intobj` | `0x648` | `0x660` | **`+0x18`** |
| `__DATA.__data` | `0x9788` | `0x9798` | **`+0x10`** |
| `__TEXT.__const` | `0x7fd4` | `0x7fe4` | **`+0x10`** |
| `__TEXT.__cstring` | `0x18cd3` | `0x18cc3` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x3dc8` | `0x3dd4` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x2478` | `0x2480` | **`+0x8`** |

### Other Changes

```diff

-226.2.7.201.0
+226.2.9.0.0

-  Functions: 24840
-  Symbols:   33718
-  CStrings:  4598
+  Functions: 24877
+  Symbols:   33733
+  CStrings:  4601
Symbols:
+ +[SBHWidgetIconResizeViewHelper dataSourceProvidesWidgetContent:]
+ -[SBHIconManager replaceApplicationIconsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:options:]
+ -[SBHIconManager swapApplicationIconsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:]
+ -[SBHLeafIconCustomImageViewController initWithIcon:iconImageCache:location:]
+ -[SBHLeafIconCustomImageViewController location]
+ -[SBHWidgetConfigurationInteraction _finishWithCurrentConfigurationIfNotTransitioning]
+ -[SBWidgetIconResizeGestureWidgetWrapperViewController contentViewController]
+ -[SBWidgetIconResizeGestureWidgetWrapperViewController iconImageInfo]
+ -[SBWidgetIconResizeGestureWidgetWrapperViewController initWithContentViewController:iconImageInfo:]
+ GCC_except_table1121
+ GCC_except_table1124
+ GCC_except_table1140
+ GCC_except_table1147
+ _OBJC_CLASS_$__UIAppAttribution
+ _OBJC_IVAR_$_SBHLeafIconCustomImageViewController._location
+ _OBJC_IVAR_$_SBWidgetIconResizeGestureWidgetWrapperViewController._contentViewController
+ _OBJC_IVAR_$_SBWidgetIconResizeGestureWidgetWrapperViewController._iconImageInfo
+ _SBHColumnCountForGalleryPodType
+ _SBHGalleryPodsForSizeClasses
+ __OBJC_$_CLASS_METHODS_SBHWidgetIconResizeViewHelper
+ ___98-[SBHAddWidgetSheetViewController _newPadCollectionViewLayoutGallerySectionWithWidth:sizeClasses:]_block_invoke_12
+ ___98-[SBHAddWidgetSheetViewController _newPadCollectionViewLayoutGallerySectionWithWidth:sizeClasses:]_block_invoke_13
+ ___block_descriptor_56_e8_32s40s48bs_e25_v32?0"NSNumber"8Q16^B24ls32l8s48l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e50_"NSArray"16?0"<NSCollectionLayoutEnvironment>"8ls32l8s40l8s48l8
+ ___block_descriptor_96_e18_{CGSize=dd}16?0Q8l
+ ___block_descriptor_96_e8_32bs40bs48bs56bs64bs72bs80bs88bs_e41_v40?0"NSMutableArray"8Q16{CGPoint=dd}24ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8
+ ___swift_closure_destructor.95Tm
+ _symbolic ShySo18SBHApplicationIconCG
- -[SBHAddWidgetSheetViewController _podsArrayWithSizeClasses:columnCount:]
- -[SBHLeafIconCustomImageViewController imageView]
- -[SBHLeafIconCustomImageViewController initWithIcon:iconImageCache:]
- -[SBHLeafIconCustomImageViewController updateImage]
- GCC_except_table1119
- GCC_except_table1120
- GCC_except_table1138
- GCC_except_table1145
- ___98-[SBHAddWidgetSheetViewController _newPadCollectionViewLayoutGallerySectionWithWidth:sizeClasses:]_block_invoke_11
- ___block_descriptor_104_e8_32s40bs48bs_e50_"NSArray"16?0"<NSCollectionLayoutEnvironment>"8ls32l8s40l8s48l8
- ___block_descriptor_32_e20_Q24?0"NSArray"8Q16l
- ___block_descriptor_40_e8_32bs_e20_B24?0"NSArray"8Q16ls32l8
- ___block_descriptor_88_e8_32bs40bs48bs56bs64bs72bs80bs_e41_v40?0"NSMutableArray"8Q16{CGPoint=dd}24ls32l8s40l8s48l8s56l8s64l8s72l8s80l8
CStrings:
+ "<%{public}@> Resting content offset requested for invalid pageSize:%@"
+ "<%{public}@> Skipping content offset recentering; invalid pageSize:%@"
+ "<%{public}@> Skipping scroll to active widget; invalid pageSize:%@"
+ "Can't swap %s with %s because no icons for the latter exist. we need the placeholder at least."
+ "{CGSize=dd}16@?0Q8"
- "B24@?0@\"NSArray\"8Q16"
- "Q24@?0@\"NSArray\"8Q16"
```
