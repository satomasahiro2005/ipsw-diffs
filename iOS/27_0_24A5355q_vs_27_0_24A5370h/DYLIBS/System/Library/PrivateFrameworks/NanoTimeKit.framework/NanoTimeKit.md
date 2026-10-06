## NanoTimeKit

> `/System/Library/PrivateFrameworks/NanoTimeKit.framework/NanoTimeKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30102c` | `0x2f9be0` | **`-0x744c`** |
| `__AUTH_CONST.__objc_const` | `0x53fa8` | `0x53868` | **`-0x740`** |
| `__TEXT.__objc_methlist` | `0x303c8` | `0x2ff08` | **`-0x4c0`** |
| `__AUTH_CONST.__cfstring` | `0x20e00` | `0x20b20` | **`-0x2e0`** |
| `__AUTH.__objc_data` | `0xe828` | `0xe5f8` | **`-0x230`** |
| `__TEXT.__cstring` | `0x1ddee` | `0x1dbce` | **`-0x220`** |
| `__TEXT.__unwind_info` | `0xd580` | `0xd420` | **`-0x160`** |
| `__DATA_CONST.__objc_selrefs` | `0x14df8` | `0x14ca0` | **`-0x158`** |
| `__TEXT.__oslogstring` | `0x153ae` | `0x1527e` | **`-0x130`** |
| `__AUTH_CONST.__objc_intobj` | `0x4bf0` | `0x4b00` | **`-0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x59b4` | `0x5904` | **`-0xb0`** |
| `__AUTH_CONST.__const` | `0x5d38` | `0x5cb8` | **`-0x80`** |
| `__DATA_CONST.__const` | `0xbd90` | `0xbe08` | **`+0x78`** |
| `__DATA.__data` | `0x5870` | `0x5808` | **`-0x68`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x1a40` | `0x19f8` | **`-0x48`** |
| `__DATA.__objc_ivar` | `0x39e0` | `0x399c` | **`-0x44`** |
| `__DATA_CONST.__got` | `0x3298` | `0x3260` | **`-0x38`** |
| `__DATA_CONST.__objc_arraydata` | `0x2918` | `0x28e0` | **`-0x38`** |
| `__DATA_CONST.__objc_classlist` | `0x1b88` | `0x1b50` | **`-0x38`** |
| `__DATA_CONST.__objc_superrefs` | `0x1548` | `0x1510` | **`-0x38`** |
| `__TEXT.__const` | `0x5df4` | `0x5dc4` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x825` | `0x808` | **`-0x1d`** |
| `__TEXT.__swift5_fieldmd` | `0xd38` | `0xd2c` | **`-0xc`** |
| `__AUTH.__data` | `0xad8` | `0xae0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x678` | `0x670` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x128` | `0x120` | **`-0x8`** |

### Other Changes

```diff

-2483.480.0.4.0
+2483.493.1.0.0

-  Functions: 20367
-  Symbols:   34162
-  CStrings:  6419
+  Functions: 20264
+  Symbols:   33986
+  CStrings:  6384
Symbols:
+ +[CHSWidgetRenderScheme(NTKAdditions) ntk_watchFacesRenderSchemesForFace:]
+ -[NTKCFaceDetailSectionHeaderView setTopAligned:]
+ -[NTKCFaceDetailSectionHeaderView topAligned]
+ -[NTKCFaceDetailViewController complicationPickerReturnAnchor]
+ -[NTKCFaceDetailViewController setComplicationPickerReturnAnchor:]
+ -[NTKComplicationControllerDisplayProperties widgetSupportedColorSchemePolicies]
+ -[NTKFace complicationsColorRenderingUsage]
+ -[NTKFaceView activeAndVisibleDidChange]
+ -[NTKFaceView isActiveAndVisible]
+ -[NTKFaceView setActiveAndVisible:]
+ -[NTKFaceView(NTKSMetadataProviding) galleryFaceViewMetadata]
+ -[NTKMutableComplicationControllerDisplayProperties setWidgetSupportedColorSchemePolicies:]
+ -[NTKWidgetRichComplicationView _supportedColorSchemePolicies]
+ -[NTKWidgetRichComplicationView _updateColorSchemePolicies]
+ -[NTKWidgetRichComplicationView setSupportedWidgetColorSchemePolicies:]
+ -[NTKWidgetRichComplicationView supportedWidgetColorSchemePolicies]
+ GCC_except_table123
+ GCC_except_table146
+ GCC_except_table174
+ GCC_except_table206
+ GCC_except_table215
+ GCC_except_table219
+ GCC_except_table223
+ GCC_except_table248
+ GCC_except_table254
+ GCC_except_table280
+ GCC_except_table286
+ GCC_except_table296
+ GCC_except_table302
+ GCC_except_table336
+ GCC_except_table376
+ GCC_except_table383
+ GCC_except_table391
+ GCC_except_table57
+ GCC_except_table84
+ OBJC_IVAR_$_NTKComplicationControllerDisplayProperties._widgetSupportedColorSchemePolicies
+ _NTKCMeasureInsetGroupedOverflow
+ _OBJC_IVAR_$_NTKCFaceDetailSectionHeaderView._topAligned
+ _OBJC_IVAR_$_NTKCFaceDetailViewController._complicationPickerReturnAnchor
+ _OBJC_IVAR_$_NTKFaceView._activeAndVisible
+ _OBJC_IVAR_$_NTKFaceView._showContentForUnadornedSnapshot
+ _OBJC_IVAR_$_NTKFaceViewController._showContentForUnadornedSnapshot
+ _OBJC_IVAR_$_NTKWidgetRichComplicationView._supportedWidgetColorSchemePolicies
+ __OBJC_$_CLASS_METHODS_NTKFace(InternalNTKFaceInstanceDescriptorAdditions|NTKFaceInstanceDescriptorAdditions|PhotosUpgrade|FaceGalleryAdditions|KaleidoscopeAddition|ViewSupport|Companion|ExternalAssets|GalleryLiteSupport|DynamicCollectionAdditions|ArgonSupport|NTKFaceDescriptorAdditions|DailyAnalytics|Migration)
+ __OBJC_$_CLASS_METHODS_NTKFaceBundle(FaceGeneration|Internal|FaceSupport|Support|Markdown|ShareSheetCreation|DebugMenu|DynamicCollectionAdditions)
+ __OBJC_$_CLASS_METHODS_NTKFaceSnapshotter
+ __OBJC_$_INSTANCE_METHODS_NTKFace(InternalNTKFaceInstanceDescriptorAdditions|NTKFaceInstanceDescriptorAdditions|PhotosUpgrade|FaceGalleryAdditions|KaleidoscopeAddition|ViewSupport|Companion|ExternalAssets|GalleryLiteSupport|DynamicCollectionAdditions|ArgonSupport|NTKFaceDescriptorAdditions|DailyAnalytics|Migration)
+ __OBJC_$_INSTANCE_METHODS_NTKFaceBundle(FaceGeneration|Internal|FaceSupport|Support|Markdown|ShareSheetCreation|DebugMenu|DynamicCollectionAdditions)
+ __OBJC_$_INSTANCE_METHODS_NTKFaceConfiguration
+ __OBJC_$_INSTANCE_METHODS_NTKFaceView(NTKSMetadataProviding|GalleryComplicationFactoryAdditions|ComplicationColor|NTKSColorPaletteAdditions)
+ __OBJC_$_PROP_LIST_NTKFaceConfiguration
+ __OBJC_CLASS_PROTOCOLS_$_NTKFaceView(NTKSMetadataProviding|GalleryComplicationFactoryAdditions|ComplicationColor|NTKSColorPaletteAdditions)
+ ___54-[NTKComplicationControllerDisplayProperties isEqual:]_block_invoke_17
+ ___74+[CHSWidgetRenderScheme(NTKAdditions) ntk_watchFacesRenderSchemesForFace:]_block_invoke
+ ___74+[CHSWidgetRenderScheme(NTKAdditions) ntk_watchFacesRenderSchemesForFace:]_block_invoke_2
+ _ntk_watchFacesRenderSchemesForFace:.accentedOnly
+ _ntk_watchFacesRenderSchemesForFace:.fullColorOnly
+ _ntk_watchFacesRenderSchemesForFace:.onceToken
- +[NTKFace(SkeletonFaceAdditions) _inProcessSkeletonSnapshotter]
- +[NTKFaceSnapshotter(SkeletonAdditions) _useCachedSnapshots]
- +[NTKFaceSnapshotter(SkeletonAdditions) skeletonBackgroundSnapshotOptions]
- +[NTKFaceSnapshotter(SkeletonAdditions) skeletonForegroundSnapshotOptions]
- +[NTKGalleryCollection _newFacesExcludingRestrictedForDevice:]
- +[NTKGalleryCollection _newFacesForDevice:]
- +[NTKSGalleryFacePieLayer needsDisplayForKey:]
- +[NTKSGalleryFacePieView layerClass]
- +[NTKWhatsNewFacesGalleryCollection _gloryBDefaultFacesForDevice:]
- +[NTKWhatsNewFacesGalleryCollection _gloryEDefaultFacesForDevice:]
- +[NTKWhatsNewFacesGalleryCollection _gloryFDefaultFacesForDevice:]
- +[NTKWhatsNewFacesGalleryCollection _graceDefaultFacesForDevice:]
- +[NTKWhatsNewFacesGalleryCollection _legacyDefaultFacesForDevice:]
- +[NTKWhatsNewFacesGalleryCollection _pride2020DefaultFacesForDevice:]
- +[NTKWhatsNewFacesGalleryCollection _spring2020DefaultFacesForDevice:]
- +[NTKWhatsNewFacesGalleryCollection whistlerSubdialsSpring2020ComplicationTypesBySlot]
- -[NTKAnalogFaceView _finalizeForSnapshotting:]
- -[NTKCFaceDetailSectionController _groupName]
- -[NTKCFaceDetailSectionHeaderView groupName]
- -[NTKCFaceDetailSectionHeaderView setGroupName:]
- -[NTKFace(SkeletonComplicationMigration) _migrateComplicationsIfNeeded]
- -[NTKFace(SkeletonFaceAdditions) hasForegroundContent]
- -[NTKFace(SkeletonFaceAdditions) skeletonBackgroundSnapshotImageDataWithCompletion:]
- -[NTKFace(SkeletonFaceAdditions) skeletonFaceRepresentationWithCompletion:]
- -[NTKFace(SkeletonFaceAdditions) skeletonForegroundSnapshotImageDataWithCompletion:]
- -[NTKFaceBundle artistFacesForDevice:]
- -[NTKFaceBundle heroFacesForDevice:]
- -[NTKFaceBundle prideFacesForDevice:]
- -[NTKFaceBundle unityFacesForDevice:]
- -[NTKFaceConfiguration(SkeletonFaceAdditions) skeletonSlotDescriptors]
- -[NTKFaceView _applyFaceSnapshotMode]
- -[NTKFaceView _onlyShowBackgroundContent]
- -[NTKFaceView _onlyShowForegroundContent]
- -[NTKFaceView _showAllContent]
- -[NTKFaceView faceSnapshotMode]
- -[NTKFaceView setFaceSnapshotMode:]
- -[NTKFaceView(SkeletonFilterProviders) skeletonFilterProviders]
- -[NTKFaceView(SkeletonMetadataProviding) galleryFaceViewMetadata]
- -[NTKFaceViewController faceHasForegroundContent]
- -[NTKFaceViewController faceSnapshotMode]
- -[NTKFaceViewController setFaceSnapshotMode:]
- -[NTKFacesGalleryCollection .cxx_destruct]
- -[NTKFacesGalleryCollection facesForDevice:]
- -[NTKFacesGalleryCollection initWithDevice:title:faceDescriptors:]
- -[NTKFacesGalleryCollection title]
- -[NTKSGalleryFace .cxx_destruct]
- -[NTKSGalleryFace JSONObjectRepresentation]
- -[NTKSGalleryFace _applyConfiguration:allowFailure:forMigration:]
- -[NTKSGalleryFace _complicationSlotDescriptors]
- -[NTKSGalleryFace _orderedComplicationSlots]
- -[NTKSGalleryFace _shortFaceDescription]
- -[NTKSGalleryFace _updateComplicationTombstones]
- -[NTKSGalleryFace dailySnapshotKey]
- -[NTKSGalleryFace deepCopy]
- -[NTKSGalleryFace faceIdentifier]
- -[NTKSGalleryFace faceViewClass]
- -[NTKSGalleryFace faceView]
- -[NTKSGalleryFace fleshedOutFaceWithError:]
- -[NTKSGalleryFace richComplicationSlotsForDevice:]
- -[NTKSGalleryFace setComplication:forSlot:]
- -[NTKSGalleryFace snapshotFaceIdentifier]
- -[NTKSGalleryFace unsafeDailySnapshotKey]
- -[NTKSGalleryFaceEditOption dailySnapshotKey]
- -[NTKSGalleryFaceEditOption localizedNameForAction]
- -[NTKSGalleryFaceEditOption localizedName]
- -[NTKSGalleryFaceEditOption uniqueName]
- -[NTKSGalleryFacePieLayer endAngle]
- -[NTKSGalleryFacePieLayer initWithCoder:]
- -[NTKSGalleryFacePieLayer initWithLayer:]
- -[NTKSGalleryFacePieLayer init]
- -[NTKSGalleryFacePieLayer layoutSublayers]
- -[NTKSGalleryFacePieLayer setEndAngle:]
- -[NTKSGalleryFacePieLayer setFillColor:]
- -[NTKSGalleryFacePieLayer setStartAngle:]
- -[NTKSGalleryFacePieLayer startAngle]
- -[NTKSGalleryFacePieLayer updatePath]
- -[NTKSGalleryFacePieView endAngle]
- -[NTKSGalleryFacePieView setEndAngle:]
- -[NTKSGalleryFacePieView setStartAngle:]
- -[NTKSGalleryFacePieView setStrokeColor:]
- -[NTKSGalleryFacePieView setStrokeWidth:]
- -[NTKSGalleryFacePieView startAngle]
- -[NTKSGalleryFacePieView strokeColor]
- -[NTKSGalleryFacePieView strokeWidth]
- -[NTKSGalleryFaceView .cxx_destruct]
- -[NTKSGalleryFaceView _applyComplicationFontToView:inSlot:]
- -[NTKSGalleryFaceView _applyOption:forCustomEditMode:slot:]
- -[NTKSGalleryFaceView _configureComplicationView:forSlot:]
- -[NTKSGalleryFaceView _filterProviderForSlot:]
- -[NTKSGalleryFaceView _legacyShouldSwapGraphicCircularComplicationColors]
- -[NTKSGalleryFaceView _loadLayoutRules]
- -[NTKSGalleryFaceView _newImageView]
- -[NTKSGalleryFaceView _utilitySlotForSlot:]
- -[NTKSGalleryFaceView complicationFontStyleForSlot:]
- -[NTKSGalleryFaceView configureWithSkeletonFace:]
- -[NTKSGalleryFaceView createFaceColorPalette]
- -[NTKSGalleryFaceView didUpdateBezelTextForRichComplicationBezelView:]
- -[NTKSGalleryFaceView initWithFaceStyle:forDevice:clientIdentifier:]
- -[NTKSGalleryFaceView layoutSubviews]
- -[NTKWhatsNewFacesGalleryCollection facesForDevice:]
- -[NTKWhatsNewFacesGalleryCollection hasNewFaces]
- -[NTKWhatsNewFacesGalleryCollection initWithDevice:]
- -[NTKWhatsNewFacesGalleryCollection title]
- -[NTKWhatsNewFacesGalleryCollectionExcludingRestricted facesForDevice:]
- GCC_except_table126
- GCC_except_table138
- GCC_except_table148
- GCC_except_table177
- GCC_except_table209
- GCC_except_table218
- GCC_except_table222
- GCC_except_table226
- GCC_except_table256
- GCC_except_table258
- GCC_except_table290
- GCC_except_table300
- GCC_except_table306
- GCC_except_table340
- GCC_except_table372
- GCC_except_table382
- GCC_except_table390
- GCC_except_table86
- _NTKEnableMultipleGalleryFaceTags
- _NTKEnableSeparateGalleryRows
- _OBJC_CLASS_$_NTKFacesGalleryCollection
- _OBJC_CLASS_$_NTKSGalleryFace
- _OBJC_CLASS_$_NTKSGalleryFacePieLayer
- _OBJC_CLASS_$_NTKSGalleryFacePieView
- _OBJC_CLASS_$_NTKSGalleryFaceView
- _OBJC_CLASS_$_NTKWhatsNewFacesGalleryCollection
- _OBJC_CLASS_$_NTKWhatsNewFacesGalleryCollectionExcludingRestricted
- _OBJC_IVAR_$_NTKFaceView._faceSnapshotMode
- _OBJC_IVAR_$_NTKFaceViewController._faceSnapshotMode
- _OBJC_IVAR_$_NTKFacesGalleryCollection._faceDescriptors
- _OBJC_IVAR_$_NTKFacesGalleryCollection._title
- _OBJC_IVAR_$_NTKSGalleryFace._faceView
- _OBJC_IVAR_$_NTKSGalleryFacePieLayer._endAngle
- _OBJC_IVAR_$_NTKSGalleryFacePieLayer._startAngle
- _OBJC_IVAR_$_NTKSGalleryFaceView._backgroundImageView
- _OBJC_IVAR_$_NTKSGalleryFaceView._bezelOccludingView
- _OBJC_IVAR_$_NTKSGalleryFaceView._bezelTextWidth
- _OBJC_IVAR_$_NTKSGalleryFaceView._device
- _OBJC_IVAR_$_NTKSGalleryFaceView._dialDescriptor
- _OBJC_IVAR_$_NTKSGalleryFaceView._factoryDescriptor
- _OBJC_IVAR_$_NTKSGalleryFaceView._filterProviders
- _OBJC_IVAR_$_NTKSGalleryFaceView._fontStyles
- _OBJC_IVAR_$_NTKSGalleryFaceView._foregroundImageView
- _OBJC_IVAR_$_NTKSGalleryFaceView._galleryFaceColorPalette
- _OBJC_IVAR_$_NTKSGalleryFaceView._legacySwap
- _OBJC_IVAR_$_NTKSGalleryFaceView._monochromeFraction
- _OBJC_IVAR_$_NTKSGalleryFaceView._overrideFonts
- _OBJC_IVAR_$_NTKSGalleryFaceView._platterColor
- _OBJC_IVAR_$_NTKSGalleryFaceView._simpleTextColor
- _OBJC_IVAR_$_NTKSGalleryFaceView._slotLayouts
- _OBJC_IVAR_$_NTKSGalleryFaceView._tintedFraction
- _OBJC_METACLASS_$_CAShapeLayer
- _OBJC_METACLASS_$_NTKFacesGalleryCollection
- _OBJC_METACLASS_$_NTKSGalleryFace
- _OBJC_METACLASS_$_NTKSGalleryFacePieLayer
- _OBJC_METACLASS_$_NTKSGalleryFacePieView
- _OBJC_METACLASS_$_NTKSGalleryFaceView
- _OBJC_METACLASS_$_NTKWhatsNewFacesGalleryCollection
- _OBJC_METACLASS_$_NTKWhatsNewFacesGalleryCollectionExcludingRestricted
- __OBJC_$_CLASS_METHODS_NTKFace(InternalNTKFaceInstanceDescriptorAdditions|NTKFaceInstanceDescriptorAdditions|PhotosUpgrade|FaceGalleryAdditions|KaleidoscopeAddition|ViewSupport|Companion|ExternalAssets|GalleryLiteSupport|DynamicCollectionAdditions|ArgonSupport|NTKFaceDescriptorAdditions|SkeletonComplicationMigration|SkeletonFaceAdditions|DailyAnalytics|Migration)
- __OBJC_$_CLASS_METHODS_NTKFaceBundle(Internal|FaceSupport|Support|Markdown|ShareSheetCreation|DebugMenu|FaceGeneration|DynamicCollectionAdditions)
- __OBJC_$_CLASS_METHODS_NTKFaceSnapshotter(SkeletonAdditions)
- __OBJC_$_CLASS_METHODS_NTKSGalleryFacePieLayer
- __OBJC_$_CLASS_METHODS_NTKSGalleryFacePieView
- __OBJC_$_CLASS_METHODS_NTKWhatsNewFacesGalleryCollection
- __OBJC_$_INSTANCE_METHODS_NTKFace(InternalNTKFaceInstanceDescriptorAdditions|NTKFaceInstanceDescriptorAdditions|PhotosUpgrade|FaceGalleryAdditions|KaleidoscopeAddition|ViewSupport|Companion|ExternalAssets|GalleryLiteSupport|DynamicCollectionAdditions|ArgonSupport|NTKFaceDescriptorAdditions|SkeletonComplicationMigration|SkeletonFaceAdditions|DailyAnalytics|Migration)
- __OBJC_$_INSTANCE_METHODS_NTKFaceBundle(Internal|FaceSupport|Support|Markdown|ShareSheetCreation|DebugMenu|FaceGeneration|DynamicCollectionAdditions)
- __OBJC_$_INSTANCE_METHODS_NTKFaceConfiguration(SkeletonFaceAdditions)
- __OBJC_$_INSTANCE_METHODS_NTKFaceView(SkeletonFilterProviders|SkeletonMetadataProviding|GalleryComplicationFactoryAdditions|ComplicationColor|NTKSColorPaletteAdditions)
- __OBJC_$_INSTANCE_METHODS_NTKFacesGalleryCollection
- __OBJC_$_INSTANCE_METHODS_NTKSGalleryFace
- __OBJC_$_INSTANCE_METHODS_NTKSGalleryFacePieLayer
- __OBJC_$_INSTANCE_METHODS_NTKSGalleryFacePieView
- __OBJC_$_INSTANCE_METHODS_NTKSGalleryFaceView
- __OBJC_$_INSTANCE_METHODS_NTKWhatsNewFacesGalleryCollection
- __OBJC_$_INSTANCE_METHODS_NTKWhatsNewFacesGalleryCollectionExcludingRestricted
- __OBJC_$_INSTANCE_VARIABLES_NTKFacesGalleryCollection
- __OBJC_$_INSTANCE_VARIABLES_NTKSGalleryFace
- __OBJC_$_INSTANCE_VARIABLES_NTKSGalleryFacePieLayer
- __OBJC_$_INSTANCE_VARIABLES_NTKSGalleryFaceView
- __OBJC_$_PROP_LIST_NTKSGalleryFacePieLayer
- __OBJC_$_PROP_LIST_NTKSGalleryFacePieView
- __OBJC_$_PROP_LIST_NTKSGalleryFaceView
- __OBJC_$_PROP_LIST_NTKWhatsNewFacesGalleryCollection
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NTKRichComplicationBezelViewDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_NTKRichComplicationBezelViewDelegate
- __OBJC_$_PROTOCOL_REFS_NTKRichComplicationBezelViewDelegate
- __OBJC_CLASS_PROTOCOLS_$_NTKFaceView(SkeletonFilterProviders|SkeletonMetadataProviding|GalleryComplicationFactoryAdditions|ComplicationColor|NTKSColorPaletteAdditions)
- __OBJC_CLASS_PROTOCOLS_$_NTKSGalleryFaceView
- __OBJC_CLASS_RO_$_NTKFacesGalleryCollection
- __OBJC_CLASS_RO_$_NTKSGalleryFace
- __OBJC_CLASS_RO_$_NTKSGalleryFacePieLayer
- __OBJC_CLASS_RO_$_NTKSGalleryFacePieView
- __OBJC_CLASS_RO_$_NTKSGalleryFaceView
- __OBJC_CLASS_RO_$_NTKWhatsNewFacesGalleryCollection
- __OBJC_CLASS_RO_$_NTKWhatsNewFacesGalleryCollectionExcludingRestricted
- __OBJC_LABEL_PROTOCOL_$_NTKRichComplicationBezelViewDelegate
- __OBJC_METACLASS_RO_$_NTKFacesGalleryCollection
- __OBJC_METACLASS_RO_$_NTKSGalleryFace
- __OBJC_METACLASS_RO_$_NTKSGalleryFacePieLayer
- __OBJC_METACLASS_RO_$_NTKSGalleryFacePieView
- __OBJC_METACLASS_RO_$_NTKSGalleryFaceView
- __OBJC_METACLASS_RO_$_NTKWhatsNewFacesGalleryCollection
- __OBJC_METACLASS_RO_$_NTKWhatsNewFacesGalleryCollectionExcludingRestricted
- __OBJC_PROTOCOL_$_NTKRichComplicationBezelViewDelegate
- __OBJC_PROTOCOL_REFERENCE_$_NTKRichComplicationBezelView
- ___52-[NTKWhatsNewFacesGalleryCollection facesForDevice:]_block_invoke
- ___52-[NTKWhatsNewFacesGalleryCollection initWithDevice:]_block_invoke
- ___56-[NTKGreenfieldViewController _toggleRightCounterLabel:]_block_invoke
- ___60+[NTKFaceSnapshotter(SkeletonAdditions) _useCachedSnapshots]_block_invoke
- ___63+[NTKFace(SkeletonFaceAdditions) _inProcessSkeletonSnapshotter]_block_invoke
- ___66-[NTKFacesGalleryCollection initWithDevice:title:faceDescriptors:]_block_invoke
- ___71-[NTKFace(SkeletonComplicationMigration) _migrateComplicationsIfNeeded]_block_invoke
- ___71-[NTKWhatsNewFacesGalleryCollectionExcludingRestricted facesForDevice:]_block_invoke
- ___75-[NTKFace(SkeletonFaceAdditions) skeletonFaceRepresentationWithCompletion:]_block_invoke
- ___75-[NTKFace(SkeletonFaceAdditions) skeletonFaceRepresentationWithCompletion:]_block_invoke_2
- ___75-[NTKFace(SkeletonFaceAdditions) skeletonFaceRepresentationWithCompletion:]_block_invoke_3
- ___84-[NTKFace(SkeletonFaceAdditions) skeletonBackgroundSnapshotImageDataWithCompletion:]_block_invoke
- ___84-[NTKFace(SkeletonFaceAdditions) skeletonForegroundSnapshotImageDataWithCompletion:]_block_invoke
- ___97-[NTKCFaceDetailViewController faceDetailComplicationPickerViewController:didSelectComplication:]_block_invoke
- ___block_descriptor_32_e34_B24?0"NTKFace"8"NSDictionary"16l
- ___block_descriptor_56_e8_32bs40r48r_e43_v24?0"NTKFaceSnapshotResult"8"NSError"16lr40l8r48l8s32l8
- ___block_descriptor_56_e8_32s40r48r_e28_v24?0"NSData"8"NSError"16lr40l8r48l8s32l8
- ___block_descriptor_64_e8_32bs40r48r56r_e43_v24?0"NTKFaceSnapshotResult"8"NSError"16lr40l8r48l8r56l8s32l8
- ___block_descriptor_64_e8_32s40r48r56r_e70_v32?0"NSData"8"NTKFaceSnapshotResultComplicationInfo"16"NSError"24lr40l8r48l8r56l8s32l8
- ___block_descriptor_89_e8_32s40bs48r56r64r72r80r_e5_v8?0ls32l8r48l8r56l8s40l8r64l8r72l8r80l8
- __inProcessSkeletonSnapshotter.__snapshotter
- __inProcessSkeletonSnapshotter.onceToken
- __useCachedSnapshots.cacheSnapshots
- __useCachedSnapshots.onceToken
CStrings:
+ "NTKSGALLERYFACE-%@"
+ "description=NanoTimeKit-2483.493.1"
+ "q\xf01"
+ "\xf0\xf0R"
+ "\xf0\xf0\xf1"
- "ACTION_ADD"
- "Add"
- "Adding Bellona faces collection"
- "Adding Hades faces collection"
- "Adding Poodle faces collection"
- "Adding Secretariat faces collection"
- "Adding SpectrumZeus faces collection"
- "Adding Squall faces collection"
- "Adding Subdials/California/FullScreen faces collection"
- "Adding Zeus faces collection"
- "B24@?0@\"NTKFace\"8@\"NSDictionary\"16"
- "Downloading"
- "Empty frame for %@"
- "NTKSGalleryFaceCachedBackgroundSnapshots"
- "NTKSGalleryFaceErrorDomain"
- "NTK_FACE_GALLERY_TITLE_NEW_FACES_COMPANION"
- "New Watch faces"
- "SKELETON-%@"
- "Setting %@ for %@…"
- "Skeleton"
- "UIKit"
- "_bg"
- "_fg"
- "_un"
- "assertionIdentifier"
- "com.apple.NTKBellonaFaceBundle"
- "com.apple.NTKHadesFaceBundle"
- "com.apple.NTKSecretariatFaceBundle"
- "configurable_gallery"
- "description=NanoTimeKit-2483.480.0.4"
- "downloading"
- "endAngle"
- "rich_slots"
- "shortDescription"
- "sk-%@"
- "skeleton"
- "startAngle"
- "ui_consistency"
- "v32@?0@\"NSData\"8@\"NTKFaceSnapshotResultComplicationInfo\"16@\"NSError\"24"
- "\xf0\xf0B"
```
