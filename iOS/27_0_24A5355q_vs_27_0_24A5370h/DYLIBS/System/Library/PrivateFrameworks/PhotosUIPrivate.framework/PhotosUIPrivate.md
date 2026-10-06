## PhotosUIPrivate

> `/System/Library/PrivateFrameworks/PhotosUIPrivate.framework/PhotosUIPrivate`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x578eb4` | `0x579388` | **`+0x4d4`** |
| `__DATA.__bss` | `0x18020` | `0x18380` | **`+0x360`** |
| `__TEXT.__cstring` | `0x343a7` | `0x345c8` | **`+0x221`** |
| `__AUTH_CONST.__auth_got` | `0x5138` | `0x5350` | **`+0x218`** |
| `__TEXT.__const` | `0x19080` | `0x19260` | **`+0x1e0`** |
| `__AUTH_CONST.__const` | `0x172d0` | `0x17160` | **`-0x170`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a1c0` | `0x2a328` | **`+0x168`** |
| `__TEXT.__oslogstring` | `0x1490f` | `0x14a64` | **`+0x155`** |
| `__TEXT.__eh_frame` | `0x7358` | `0x7230` | **`-0x128`** |
| `__AUTH.__data` | `0x4f18` | `0x4e28` | **`-0xf0`** |
| `__TEXT.__swift5_reflstr` | `0x8137` | `0x8217` | **`+0xe0`** |
| `__AUTH_CONST.__objc_const` | `0x84c50` | `0x84d20` | **`+0xd0`** |
| `__TEXT.__objc_methlist` | `0x4fe44` | `0x4ff14` | **`+0xd0`** |
| `__TEXT.__swift5_capture` | `0x4b84` | `0x4abc` | **`-0xc8`** |
| `__DATA_CONST.__objc_arraydata` | `0x1618` | `0x1580` | **`-0x98`** |
| `__TEXT.__constg_swiftt` | `0xa9ac` | `0xa920` | **`-0x8c`** |
| `__AUTH_CONST.__cfstring` | `0x26620` | `0x266a0` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x16092` | `0x16012` | **`-0x80`** |
| `__TEXT.__swift5_assocty` | `0x1870` | `0x18e8` | **`+0x78`** |
| `__DATA.__data` | `0x14018` | `0x14078` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x5548` | `0x5578` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x86cc` | `0x86fc` | **`+0x30`** |
| `__AUTH_CONST.__objc_dictobj` | `0x3c0` | `0x398` | **`-0x28`** |
| `__AUTH.__objc_data` | `0x18f08` | `0x18ee8` | **`-0x20`** |
| `__DATA_CONST.__const` | `0xc3d0` | `0xc3f0` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x6e70` | `0x6e5c` | **`-0x14`** |
| `__TEXT.__swift5_proto` | `0xbf4` | `0xc08` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0x5c68` | `0x5c70` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1e20` | `0x1e18` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x1438` | `0x1440` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x510` | `0x518` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x10e0` | `0x10d8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x17de8` | `0x17df0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x74` | `0x70` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x758` | `0x754` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x25c` | `0x260` | **`+0x4`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Functions: 41281
-  Symbols:   48913
-  CStrings:  7963
+  Functions: 41291
+  Symbols:   48939
+  CStrings:  7977
Symbols:
+ +[PUGenEditOverlayEffectSettings settingsControllerModule]
+ +[PUGenEditOverlayEffectSettings sharedInstance]
+ -[PUBrowsingVideoPlayer _prepareVideoOutputsForContentChange]
+ -[PUCleanupToolController _handleNonRenderCompletion]
+ -[PUCleanupToolController _shouldRestrictUI]
+ -[PUCleanupToolController _showInteractionModeUI]
+ -[PUCleanupToolController requiresRestrictedUI]
+ -[PUCleanupToolController setRequiresRestrictedUI:]
+ -[PUCropToolController _hasExpandedCanvasExtent]
+ -[PUCropToolController _updateDebugCompositeImageOutlineViewPath]
+ -[PUCropToolController isAssetSafeForGenerativeEditsDidChange]
+ -[PUCropToolController setShowOutfillStatusView:]
+ -[PUCropToolController showOutfillStatusView]
+ -[PUCropToolController wantsZoomAndPanEnabled]
+ -[PUGenEditOverlayEffectSettings outfillLoading_bias]
+ -[PUGenEditOverlayEffectSettings outfillLoading_blurRadius]
+ -[PUGenEditOverlayEffectSettings outfillLoading_chromaticFringingIntensity]
+ -[PUGenEditOverlayEffectSettings outfillLoading_distortionGrainScale]
+ -[PUGenEditOverlayEffectSettings outfillLoading_distortionStrength]
+ -[PUGenEditOverlayEffectSettings outfillLoading_maskBlurRadius]
+ -[PUGenEditOverlayEffectSettings outfillLoading_maskInsetPerBlurRadius]
+ -[PUGenEditOverlayEffectSettings outfillLoading_maskMeshAmplitude]
+ -[PUGenEditOverlayEffectSettings outfillLoading_maskMeshSpeed]
+ -[PUGenEditOverlayEffectSettings outfillLoading_mirrorExtensionScale]
+ -[PUGenEditOverlayEffectSettings outfillLoading_saturation]
+ -[PUGenEditOverlayEffectSettings outfillLoading_speed]
+ -[PUGenEditOverlayEffectSettings outfillLoading_transitionDuration]
+ -[PUGenEditOverlayEffectSettings outfillPlaceholder_bias]
+ -[PUGenEditOverlayEffectSettings outfillPlaceholder_blurRadius]
+ -[PUGenEditOverlayEffectSettings outfillPlaceholder_chromaticFringingIntensity]
+ -[PUGenEditOverlayEffectSettings outfillPlaceholder_distortionGrainScale]
+ -[PUGenEditOverlayEffectSettings outfillPlaceholder_distortionStrength]
+ -[PUGenEditOverlayEffectSettings outfillPlaceholder_maskBlurRadius]
+ -[PUGenEditOverlayEffectSettings outfillPlaceholder_maskInsetPerBlurRadius]
+ -[PUGenEditOverlayEffectSettings outfillPlaceholder_maskMeshAmplitude]
+ -[PUGenEditOverlayEffectSettings outfillPlaceholder_maskMeshSpeed]
+ -[PUGenEditOverlayEffectSettings outfillPlaceholder_mirrorExtensionScale]
+ -[PUGenEditOverlayEffectSettings outfillPlaceholder_saturation]
+ -[PUGenEditOverlayEffectSettings outfillPlaceholder_speed]
+ -[PUGenEditOverlayEffectSettings outfillPlaceholder_transitionDuration]
+ -[PUGenEditOverlayEffectSettings parentSettings]
+ -[PUGenEditOverlayEffectSettings reframePreview_bias]
+ -[PUGenEditOverlayEffectSettings reframePreview_blurRadius]
+ -[PUGenEditOverlayEffectSettings reframePreview_chromaticFringingIntensity]
+ -[PUGenEditOverlayEffectSettings reframePreview_distortionGrainScale]
+ -[PUGenEditOverlayEffectSettings reframePreview_distortionStrength]
+ -[PUGenEditOverlayEffectSettings reframePreview_maskBlurRadius]
+ -[PUGenEditOverlayEffectSettings reframePreview_maskInsetPerBlurRadius]
+ -[PUGenEditOverlayEffectSettings reframePreview_maskMeshAmplitude]
+ -[PUGenEditOverlayEffectSettings reframePreview_maskMeshSpeed]
+ -[PUGenEditOverlayEffectSettings reframePreview_mirrorExtensionScale]
+ -[PUGenEditOverlayEffectSettings reframePreview_saturation]
+ -[PUGenEditOverlayEffectSettings reframePreview_speed]
+ -[PUGenEditOverlayEffectSettings reframePreview_transitionDuration]
+ -[PUGenEditOverlayEffectSettings reframeProcessing_bias]
+ -[PUGenEditOverlayEffectSettings reframeProcessing_blurRadius]
+ -[PUGenEditOverlayEffectSettings reframeProcessing_chromaticFringingIntensity]
+ -[PUGenEditOverlayEffectSettings reframeProcessing_distortionGrainScale]
+ -[PUGenEditOverlayEffectSettings reframeProcessing_distortionStrength]
+ -[PUGenEditOverlayEffectSettings reframeProcessing_maskBlurRadius]
+ -[PUGenEditOverlayEffectSettings reframeProcessing_maskInsetPerBlurRadius]
+ -[PUGenEditOverlayEffectSettings reframeProcessing_maskMeshAmplitude]
+ -[PUGenEditOverlayEffectSettings reframeProcessing_maskMeshSpeed]
+ -[PUGenEditOverlayEffectSettings reframeProcessing_mirrorExtensionScale]
+ -[PUGenEditOverlayEffectSettings reframeProcessing_saturation]
+ -[PUGenEditOverlayEffectSettings reframeProcessing_speed]
+ -[PUGenEditOverlayEffectSettings reframeProcessing_transitionDuration]
+ -[PUGenEditOverlayEffectSettings renderAtPointResolution]
+ -[PUGenEditOverlayEffectSettings setDefaultValues]
+ -[PUGenEditOverlayEffectSettings setOutfillLoading_bias:]
+ -[PUGenEditOverlayEffectSettings setOutfillLoading_blurRadius:]
+ -[PUGenEditOverlayEffectSettings setOutfillLoading_chromaticFringingIntensity:]
+ -[PUGenEditOverlayEffectSettings setOutfillLoading_distortionGrainScale:]
+ -[PUGenEditOverlayEffectSettings setOutfillLoading_distortionStrength:]
+ -[PUGenEditOverlayEffectSettings setOutfillLoading_maskBlurRadius:]
+ -[PUGenEditOverlayEffectSettings setOutfillLoading_maskInsetPerBlurRadius:]
+ -[PUGenEditOverlayEffectSettings setOutfillLoading_maskMeshAmplitude:]
+ -[PUGenEditOverlayEffectSettings setOutfillLoading_maskMeshSpeed:]
+ -[PUGenEditOverlayEffectSettings setOutfillLoading_mirrorExtensionScale:]
+ -[PUGenEditOverlayEffectSettings setOutfillLoading_saturation:]
+ -[PUGenEditOverlayEffectSettings setOutfillLoading_speed:]
+ -[PUGenEditOverlayEffectSettings setOutfillLoading_transitionDuration:]
+ -[PUGenEditOverlayEffectSettings setOutfillPlaceholder_bias:]
+ -[PUGenEditOverlayEffectSettings setOutfillPlaceholder_blurRadius:]
+ -[PUGenEditOverlayEffectSettings setOutfillPlaceholder_chromaticFringingIntensity:]
+ -[PUGenEditOverlayEffectSettings setOutfillPlaceholder_distortionGrainScale:]
+ -[PUGenEditOverlayEffectSettings setOutfillPlaceholder_distortionStrength:]
+ -[PUGenEditOverlayEffectSettings setOutfillPlaceholder_maskBlurRadius:]
+ -[PUGenEditOverlayEffectSettings setOutfillPlaceholder_maskInsetPerBlurRadius:]
+ -[PUGenEditOverlayEffectSettings setOutfillPlaceholder_maskMeshAmplitude:]
+ -[PUGenEditOverlayEffectSettings setOutfillPlaceholder_maskMeshSpeed:]
+ -[PUGenEditOverlayEffectSettings setOutfillPlaceholder_mirrorExtensionScale:]
+ -[PUGenEditOverlayEffectSettings setOutfillPlaceholder_saturation:]
+ -[PUGenEditOverlayEffectSettings setOutfillPlaceholder_speed:]
+ -[PUGenEditOverlayEffectSettings setOutfillPlaceholder_transitionDuration:]
+ -[PUGenEditOverlayEffectSettings setReframePreview_bias:]
+ -[PUGenEditOverlayEffectSettings setReframePreview_blurRadius:]
+ -[PUGenEditOverlayEffectSettings setReframePreview_chromaticFringingIntensity:]
+ -[PUGenEditOverlayEffectSettings setReframePreview_distortionGrainScale:]
+ -[PUGenEditOverlayEffectSettings setReframePreview_distortionStrength:]
+ -[PUGenEditOverlayEffectSettings setReframePreview_maskBlurRadius:]
+ -[PUGenEditOverlayEffectSettings setReframePreview_maskInsetPerBlurRadius:]
+ -[PUGenEditOverlayEffectSettings setReframePreview_maskMeshAmplitude:]
+ -[PUGenEditOverlayEffectSettings setReframePreview_maskMeshSpeed:]
+ -[PUGenEditOverlayEffectSettings setReframePreview_mirrorExtensionScale:]
+ -[PUGenEditOverlayEffectSettings setReframePreview_saturation:]
+ -[PUGenEditOverlayEffectSettings setReframePreview_speed:]
+ -[PUGenEditOverlayEffectSettings setReframePreview_transitionDuration:]
+ -[PUGenEditOverlayEffectSettings setReframeProcessing_bias:]
+ -[PUGenEditOverlayEffectSettings setReframeProcessing_blurRadius:]
+ -[PUGenEditOverlayEffectSettings setReframeProcessing_chromaticFringingIntensity:]
+ -[PUGenEditOverlayEffectSettings setReframeProcessing_distortionGrainScale:]
+ -[PUGenEditOverlayEffectSettings setReframeProcessing_distortionStrength:]
+ -[PUGenEditOverlayEffectSettings setReframeProcessing_maskBlurRadius:]
+ -[PUGenEditOverlayEffectSettings setReframeProcessing_maskInsetPerBlurRadius:]
+ -[PUGenEditOverlayEffectSettings setReframeProcessing_maskMeshAmplitude:]
+ -[PUGenEditOverlayEffectSettings setReframeProcessing_maskMeshSpeed:]
+ -[PUGenEditOverlayEffectSettings setReframeProcessing_mirrorExtensionScale:]
+ -[PUGenEditOverlayEffectSettings setReframeProcessing_saturation:]
+ -[PUGenEditOverlayEffectSettings setReframeProcessing_speed:]
+ -[PUGenEditOverlayEffectSettings setReframeProcessing_transitionDuration:]
+ -[PUGenEditOverlayEffectSettings setRenderAtPointResolution:]
+ -[PUGenEditOverlayEffectSettings setShowConfigurationPanel:]
+ -[PUGenEditOverlayEffectSettings showConfigurationPanel]
+ -[PUOneUpViewController _userDidTakeScreenshot:]
+ -[PUOneUpViewController presentedFromSharedAlbumActivity]
+ -[PUOneUpViewController providerForDeferredMenuElement:]
+ -[PUOneUpViewController setPresentedFromSharedAlbumActivity:]
+ -[PUPXPhotoKitAddToSharedAlbumActionPerformer shouldExitSelectModeForState:]
+ -[PUPhotoEditProtoSettings cropCompositeImageOutline]
+ -[PUPhotoEditProtoSettings genEditOverlayEffectSettings]
+ -[PUPhotoEditProtoSettings setCropCompositeImageOutline:]
+ -[PUPhotoEditProtoSettings setGenEditOverlayEffectSettings:]
+ -[PUPhotoEditProtoSettings setUseEditAIHDRModularPipeline:]
+ -[PUPhotoEditProtoSettings useEditAIHDRModularPipeline]
+ -[PUPhotoEditToolController isAssetSafeForGenerativeEditsDidChange]
+ -[PUPhotoEditViewController _emitClearedGenerationForActiveAIToolsIfNeeded]
+ -[PUPhotoEditViewController aiToolsActiveAtExitStart]
+ -[PUPhotoEditViewController setAiToolsActiveAtExitStart:]
+ -[PUPhotoEditViewController toolControllerIsAssetSafeForGenerativeEdit:]
+ -[PUPickerConfiguration excludesSelectionIndicator]
+ -[PUPickerConfiguration isAlbumAndSharedAlbumPicker]
+ -[PUTilingView appliesTileTransform3DViaView]
+ -[PUTilingView configureAppliesTileTransform3DViaView]
+ -[PUTilingView setAppliesTileTransform3DViaView:]
+ -[UIViewController(PhotosUI) _pu_performBarsVisibilityUpdatesWithAnimationSettings:]
+ GCC_except_table10150
+ GCC_except_table10167
+ GCC_except_table10178
+ GCC_except_table10179
+ GCC_except_table10209
+ GCC_except_table10277
+ GCC_except_table10319
+ GCC_except_table10326
+ GCC_except_table10330
+ GCC_except_table10336
+ GCC_except_table10433
+ GCC_except_table10491
+ GCC_except_table10524
+ GCC_except_table10787
+ GCC_except_table10789
+ GCC_except_table10906
+ GCC_except_table11015
+ GCC_except_table11177
+ GCC_except_table11218
+ GCC_except_table11246
+ GCC_except_table11293
+ GCC_except_table11294
+ GCC_except_table11296
+ GCC_except_table11297
+ GCC_except_table11300
+ GCC_except_table11304
+ GCC_except_table11325
+ GCC_except_table11634
+ GCC_except_table11664
+ GCC_except_table11674
+ GCC_except_table11743
+ GCC_except_table12085
+ GCC_except_table12086
+ GCC_except_table12143
+ GCC_except_table12431
+ GCC_except_table12448
+ GCC_except_table12461
+ GCC_except_table12475
+ GCC_except_table12495
+ GCC_except_table12544
+ GCC_except_table12695
+ GCC_except_table12713
+ GCC_except_table12721
+ GCC_except_table12724
+ GCC_except_table12735
+ GCC_except_table12786
+ GCC_except_table12799
+ GCC_except_table12838
+ GCC_except_table12871
+ GCC_except_table12887
+ GCC_except_table12889
+ GCC_except_table12925
+ GCC_except_table13015
+ GCC_except_table13020
+ GCC_except_table13288
+ GCC_except_table13363
+ GCC_except_table13377
+ GCC_except_table13384
+ GCC_except_table13400
+ GCC_except_table13401
+ GCC_except_table13404
+ GCC_except_table13411
+ GCC_except_table13525
+ GCC_except_table13527
+ GCC_except_table13589
+ GCC_except_table13631
+ GCC_except_table13691
+ GCC_except_table13716
+ GCC_except_table13732
+ GCC_except_table13747
+ GCC_except_table13771
+ GCC_except_table13799
+ GCC_except_table13811
+ GCC_except_table13821
+ GCC_except_table13831
+ GCC_except_table13844
+ GCC_except_table13854
+ GCC_except_table13865
+ GCC_except_table13885
+ GCC_except_table13897
+ GCC_except_table13902
+ GCC_except_table13904
+ GCC_except_table13909
+ GCC_except_table13910
+ GCC_except_table13911
+ GCC_except_table13931
+ GCC_except_table13978
+ GCC_except_table14202
+ GCC_except_table14342
+ GCC_except_table14444
+ GCC_except_table14448
+ GCC_except_table14459
+ GCC_except_table14483
+ GCC_except_table14494
+ GCC_except_table14496
+ GCC_except_table14943
+ GCC_except_table1515
+ GCC_except_table15376
+ GCC_except_table15386
+ GCC_except_table15389
+ GCC_except_table15392
+ GCC_except_table15400
+ GCC_except_table15435
+ GCC_except_table15470
+ GCC_except_table1550
+ GCC_except_table15549
+ GCC_except_table1560
+ GCC_except_table15627
+ GCC_except_table15633
+ GCC_except_table15637
+ GCC_except_table15676
+ GCC_except_table15734
+ GCC_except_table15739
+ GCC_except_table15741
+ GCC_except_table15774
+ GCC_except_table15786
+ GCC_except_table15794
+ GCC_except_table15796
+ GCC_except_table15800
+ GCC_except_table15803
+ GCC_except_table15807
+ GCC_except_table15810
+ GCC_except_table15812
+ GCC_except_table15814
+ GCC_except_table15819
+ GCC_except_table15838
+ GCC_except_table15849
+ GCC_except_table15860
+ GCC_except_table15871
+ GCC_except_table15919
+ GCC_except_table15992
+ GCC_except_table15996
+ GCC_except_table16109
+ GCC_except_table16112
+ GCC_except_table16118
+ GCC_except_table16150
+ GCC_except_table16167
+ GCC_except_table16225
+ GCC_except_table16255
+ GCC_except_table16312
+ GCC_except_table16348
+ GCC_except_table16430
+ GCC_except_table16431
+ GCC_except_table16448
+ GCC_except_table16457
+ GCC_except_table16464
+ GCC_except_table16471
+ GCC_except_table16477
+ GCC_except_table16487
+ GCC_except_table16494
+ GCC_except_table16678
+ GCC_except_table16689
+ GCC_except_table16692
+ GCC_except_table16694
+ GCC_except_table16701
+ GCC_except_table16703
+ GCC_except_table16705
+ GCC_except_table16723
+ GCC_except_table16790
+ GCC_except_table16796
+ GCC_except_table16824
+ GCC_except_table16829
+ GCC_except_table17025
+ GCC_except_table17050
+ GCC_except_table17213
+ GCC_except_table17320
+ GCC_except_table17321
+ GCC_except_table17442
+ GCC_except_table17476
+ GCC_except_table17518
+ GCC_except_table17523
+ GCC_except_table17552
+ GCC_except_table17554
+ GCC_except_table17556
+ GCC_except_table17700
+ GCC_except_table17703
+ GCC_except_table17712
+ GCC_except_table17899
+ GCC_except_table17900
+ GCC_except_table17934
+ GCC_except_table17953
+ GCC_except_table17955
+ GCC_except_table18020
+ GCC_except_table18093
+ GCC_except_table18110
+ GCC_except_table18111
+ GCC_except_table18114
+ GCC_except_table18121
+ GCC_except_table18122
+ GCC_except_table18130
+ GCC_except_table18143
+ GCC_except_table18151
+ GCC_except_table18162
+ GCC_except_table18308
+ GCC_except_table18310
+ GCC_except_table18312
+ GCC_except_table18320
+ GCC_except_table18610
+ GCC_except_table18611
+ GCC_except_table18630
+ GCC_except_table18632
+ GCC_except_table18662
+ GCC_except_table18673
+ GCC_except_table1869
+ GCC_except_table18696
+ GCC_except_table18697
+ GCC_except_table18701
+ GCC_except_table18710
+ GCC_except_table18720
+ GCC_except_table18838
+ GCC_except_table18850
+ GCC_except_table18898
+ GCC_except_table18923
+ GCC_except_table18926
+ GCC_except_table18928
+ GCC_except_table18929
+ GCC_except_table18930
+ GCC_except_table18931
+ GCC_except_table18936
+ GCC_except_table19019
+ GCC_except_table19026
+ GCC_except_table19122
+ GCC_except_table19180
+ GCC_except_table19235
+ GCC_except_table19395
+ GCC_except_table19412
+ GCC_except_table19590
+ GCC_except_table1968
+ GCC_except_table19756
+ GCC_except_table19844
+ GCC_except_table19868
+ GCC_except_table20276
+ GCC_except_table20280
+ GCC_except_table20289
+ GCC_except_table20293
+ GCC_except_table20311
+ GCC_except_table20322
+ GCC_except_table20372
+ GCC_except_table20421
+ GCC_except_table20672
+ GCC_except_table20820
+ GCC_except_table20825
+ GCC_except_table20968
+ GCC_except_table20978
+ GCC_except_table20980
+ GCC_except_table21023
+ GCC_except_table21077
+ GCC_except_table21078
+ GCC_except_table21168
+ GCC_except_table21359
+ GCC_except_table21363
+ GCC_except_table21442
+ GCC_except_table21443
+ GCC_except_table21451
+ GCC_except_table21530
+ GCC_except_table21564
+ GCC_except_table21646
+ GCC_except_table21647
+ GCC_except_table21701
+ GCC_except_table2177
+ GCC_except_table2180
+ GCC_except_table21827
+ GCC_except_table2189
+ GCC_except_table22022
+ GCC_except_table22023
+ GCC_except_table22040
+ GCC_except_table22044
+ GCC_except_table22067
+ GCC_except_table22179
+ GCC_except_table2240
+ GCC_except_table22498
+ GCC_except_table22539
+ GCC_except_table2258
+ GCC_except_table22632
+ GCC_except_table22656
+ GCC_except_table22671
+ GCC_except_table22791
+ GCC_except_table22827
+ GCC_except_table22830
+ GCC_except_table22832
+ GCC_except_table22837
+ GCC_except_table22869
+ GCC_except_table22875
+ GCC_except_table22940
+ GCC_except_table22956
+ GCC_except_table2303
+ GCC_except_table2311
+ GCC_except_table2315
+ GCC_except_table23226
+ GCC_except_table23232
+ GCC_except_table23239
+ GCC_except_table23240
+ GCC_except_table23242
+ GCC_except_table23243
+ GCC_except_table23245
+ GCC_except_table2327
+ GCC_except_table23347
+ GCC_except_table23449
+ GCC_except_table23486
+ GCC_except_table2350
+ GCC_except_table23548
+ GCC_except_table23561
+ GCC_except_table23649
+ GCC_except_table23656
+ GCC_except_table23658
+ GCC_except_table23660
+ GCC_except_table2367
+ GCC_except_table23679
+ GCC_except_table23684
+ GCC_except_table2369
+ GCC_except_table23690
+ GCC_except_table23706
+ GCC_except_table2373
+ GCC_except_table2375
+ GCC_except_table23889
+ GCC_except_table23912
+ GCC_except_table23923
+ GCC_except_table24028
+ GCC_except_table2404
+ GCC_except_table24083
+ GCC_except_table24090
+ GCC_except_table24094
+ GCC_except_table24108
+ GCC_except_table24111
+ GCC_except_table24242
+ GCC_except_table24270
+ GCC_except_table24287
+ GCC_except_table24337
+ GCC_except_table24385
+ GCC_except_table2441
+ GCC_except_table24494
+ GCC_except_table24563
+ GCC_except_table24573
+ GCC_except_table24581
+ GCC_except_table24822
+ GCC_except_table24838
+ GCC_except_table2766
+ GCC_except_table2822
+ GCC_except_table2826
+ GCC_except_table2829
+ GCC_except_table2917
+ GCC_except_table2921
+ GCC_except_table2942
+ GCC_except_table2951
+ GCC_except_table3003
+ GCC_except_table3061
+ GCC_except_table3064
+ GCC_except_table3274
+ GCC_except_table3306
+ GCC_except_table3329
+ GCC_except_table3352
+ GCC_except_table3355
+ GCC_except_table3797
+ GCC_except_table3800
+ GCC_except_table3806
+ GCC_except_table3935
+ GCC_except_table3983
+ GCC_except_table4003
+ GCC_except_table4041
+ GCC_except_table4044
+ GCC_except_table4049
+ GCC_except_table4126
+ GCC_except_table4128
+ GCC_except_table4261
+ GCC_except_table4378
+ GCC_except_table4390
+ GCC_except_table4454
+ GCC_except_table4481
+ GCC_except_table5787
+ GCC_except_table5845
+ GCC_except_table5847
+ GCC_except_table5857
+ GCC_except_table5889
+ GCC_except_table5913
+ GCC_except_table5939
+ GCC_except_table5962
+ GCC_except_table5996
+ GCC_except_table6007
+ GCC_except_table6283
+ GCC_except_table6287
+ GCC_except_table6288
+ GCC_except_table6292
+ GCC_except_table6293
+ GCC_except_table6299
+ GCC_except_table6431
+ GCC_except_table6479
+ GCC_except_table6483
+ GCC_except_table6486
+ GCC_except_table6503
+ GCC_except_table6591
+ GCC_except_table6622
+ GCC_except_table6629
+ GCC_except_table6697
+ GCC_except_table6728
+ GCC_except_table6833
+ GCC_except_table6837
+ GCC_except_table6840
+ GCC_except_table6843
+ GCC_except_table6910
+ GCC_except_table6922
+ GCC_except_table6932
+ GCC_except_table6936
+ GCC_except_table7075
+ GCC_except_table7085
+ GCC_except_table7094
+ GCC_except_table7102
+ GCC_except_table7176
+ GCC_except_table7230
+ GCC_except_table7238
+ GCC_except_table7379
+ GCC_except_table7395
+ GCC_except_table7436
+ GCC_except_table7441
+ GCC_except_table7449
+ GCC_except_table7454
+ GCC_except_table7459
+ GCC_except_table7488
+ GCC_except_table7609
+ GCC_except_table7610
+ GCC_except_table8014
+ GCC_except_table8087
+ GCC_except_table8199
+ GCC_except_table8206
+ GCC_except_table8212
+ GCC_except_table8277
+ GCC_except_table8307
+ GCC_except_table8308
+ GCC_except_table8462
+ GCC_except_table8639
+ GCC_except_table8647
+ GCC_except_table8648
+ GCC_except_table8656
+ GCC_except_table8669
+ GCC_except_table8681
+ GCC_except_table8687
+ GCC_except_table8706
+ GCC_except_table8710
+ GCC_except_table8736
+ GCC_except_table8788
+ GCC_except_table8916
+ GCC_except_table9000
+ GCC_except_table9005
+ GCC_except_table9048
+ GCC_except_table9132
+ GCC_except_table9144
+ GCC_except_table9184
+ GCC_except_table9209
+ GCC_except_table9253
+ GCC_except_table9280
+ GCC_except_table9294
+ GCC_except_table9301
+ GCC_except_table9341
+ GCC_except_table9354
+ GCC_except_table9356
+ GCC_except_table9360
+ GCC_except_table9361
+ GCC_except_table9427
+ GCC_except_table9430
+ GCC_except_table9568
+ GCC_except_table9573
+ GCC_except_table9575
+ GCC_except_table9624
+ GCC_except_table9698
+ GCC_except_table9707
+ GCC_except_table9857
+ GCC_except_table9909
+ GCC_except_table9957
+ GCC_except_table9961
+ GCC_except_table9965
+ GCC_except_table9983
+ _OBJC_CLASS_$_PEEditAIAvailability
+ _OBJC_CLASS_$_PEEditAIDiagnosticsRegistration
+ _OBJC_CLASS_$_PUGenEditOverlayEffectSettings
+ _OBJC_CLASS_$_PXSplitViewController
+ _OBJC_CLASS_$_UIDeferredMenuElementProvider
+ _OBJC_CLASS_$_UIViewLayoutRegion
+ _OBJC_IVAR_$_PUCleanupToolController._requiresRestrictedUI
+ _OBJC_IVAR_$_PUCropToolController._showOutfillStatusView
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillLoading_bias
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillLoading_blurRadius
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillLoading_chromaticFringingIntensity
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillLoading_distortionGrainScale
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillLoading_distortionStrength
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillLoading_maskBlurRadius
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillLoading_maskInsetPerBlurRadius
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillLoading_maskMeshAmplitude
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillLoading_maskMeshSpeed
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillLoading_mirrorExtensionScale
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillLoading_saturation
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillLoading_speed
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillLoading_transitionDuration
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillPlaceholder_bias
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillPlaceholder_blurRadius
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillPlaceholder_chromaticFringingIntensity
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillPlaceholder_distortionGrainScale
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillPlaceholder_distortionStrength
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillPlaceholder_maskBlurRadius
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillPlaceholder_maskInsetPerBlurRadius
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillPlaceholder_maskMeshAmplitude
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillPlaceholder_maskMeshSpeed
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillPlaceholder_mirrorExtensionScale
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillPlaceholder_saturation
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillPlaceholder_speed
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._outfillPlaceholder_transitionDuration
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframePreview_bias
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframePreview_blurRadius
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframePreview_chromaticFringingIntensity
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframePreview_distortionGrainScale
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframePreview_distortionStrength
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframePreview_maskBlurRadius
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframePreview_maskInsetPerBlurRadius
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframePreview_maskMeshAmplitude
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframePreview_maskMeshSpeed
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframePreview_mirrorExtensionScale
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframePreview_saturation
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframePreview_speed
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframePreview_transitionDuration
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframeProcessing_bias
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframeProcessing_blurRadius
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframeProcessing_chromaticFringingIntensity
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframeProcessing_distortionGrainScale
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframeProcessing_distortionStrength
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframeProcessing_maskBlurRadius
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframeProcessing_maskInsetPerBlurRadius
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframeProcessing_maskMeshAmplitude
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframeProcessing_maskMeshSpeed
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframeProcessing_mirrorExtensionScale
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframeProcessing_saturation
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframeProcessing_speed
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._reframeProcessing_transitionDuration
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._renderAtPointResolution
+ _OBJC_IVAR_$_PUGenEditOverlayEffectSettings._showConfigurationPanel
+ _OBJC_IVAR_$_PUOneUpViewController._presentedFromSharedAlbumActivity
+ _OBJC_IVAR_$_PUPhotoEditProtoSettings._cropCompositeImageOutline
+ _OBJC_IVAR_$_PUPhotoEditProtoSettings._genEditOverlayEffectSettings
+ _OBJC_IVAR_$_PUPhotoEditProtoSettings._useEditAIHDRModularPipeline
+ _OBJC_IVAR_$_PUPhotoEditViewController._aiToolsActiveAtExitStart
+ _OBJC_IVAR_$_PUTilingView._appliesTileTransform3DViaView
+ _OBJC_IVAR_$_PUVideoTileViewController._videoSnapshotView
+ _OBJC_METACLASS_$_PUGenEditOverlayEffectSettings
+ _PHErrorIsCorruptImage
+ _PHErrorIsMediaServerDisconnected
+ _PXAssetActionTypeInternalFileRadar
+ _PXImageMenuStarRatingDeferredElementIdentifier
+ _PXSharedAlbumCommentSFSymbolName
+ _PXSizeGetArea
+ _UIApplicationUserDidTakeScreenshotNotification
+ __OBJC_$_CLASS_METHODS_PUGenEditOverlayEffectSettings
+ __OBJC_$_INSTANCE_METHODS_PUCleanupMaskEffectSettings(PhotosUIPrivate)
+ __OBJC_$_INSTANCE_METHODS_PUGenEditOverlayEffectSettings(PhotosUIPrivate)
+ __OBJC_$_INSTANCE_METHODS__TtC15PhotosUIPrivateP33_BF474F55E25F5DA22E917DBD5509DD5926PUAIToolCollectionViewCell(PhotosUIPrivate)
+ __OBJC_$_INSTANCE_VARIABLES_PUGenEditOverlayEffectSettings
+ __OBJC_$_PROP_LIST_PUGenEditOverlayEffectSettings
+ __OBJC_$_PROP_LIST_UIInteraction
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_UIInteraction
+ __OBJC_$_PROTOCOL_METHOD_TYPES_UIInteraction
+ __OBJC_$_PROTOCOL_REFS_UIInteraction
+ __OBJC_CLASS_RO_$_PUGenEditOverlayEffectSettings
+ __OBJC_LABEL_PROTOCOL_$_UIInteraction
+ __OBJC_METACLASS_RO_$_PUGenEditOverlayEffectSettings
+ __OBJC_PROTOCOL_$_UIInteraction
+ ___42-[PUCropToolController _hideMaskedContent]_block_invoke
+ ___48+[PUGenEditOverlayEffectSettings sharedInstance]_block_invoke
+ ___49-[PUCropToolController outfillCloseButtonTapped:]_block_invoke_2
+ ___49-[PUCropToolController setShowOutfillStatusView:]_block_invoke
+ ___56-[PUOneUpViewController providerForDeferredMenuElement:]_block_invoke
+ ___62-[PUCropToolController _showMaskedContentAndCancelDelayedHide]_block_invoke
+ ___71-[PUPXPhotoKitSaveVideoFrameActionPerformer performUserInteractionTask]_block_invoke_4
+ ___77-[PUCropToolController _handleDidCreateEditedImage:inputExtent:canvasExtent:]_block_invoke
+ ___block_descriptor_113_e8_32s40s48s56s64s72s80s88s96s104r_e20_v16?0"NUResponse"8ls32l8s40l8r104l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8
+ ___block_descriptor_48_e8_32s40s_e20_v24?0q8"NSError"16ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48r56r_e64_v56?0^{CGImage=}8{CGRect={CGPoint=dd}{CGSize=dd}}16"NSError"48lr48l8r56l8s32l8s40l8
+ ___block_descriptor_64_e8_32s40s48r56w_e44_v24?0"PEOutfillRequestResult"8"NSError"16lr48l8w56l8s32l8s40l8
+ ___swift_closure_destructor.130Tm
+ ___swift_closure_destructor.136Tm
+ ___swift_closure_destructor.14Tm
+ ___swift_closure_destructor.179Tm
+ ___swift_closure_destructor.192Tm
+ ___swift_closure_destructor.193Tm
+ ___swift_closure_destructor.3Tm
+ ___swift_closure_destructor.52Tm
+ ___swift_closure_destructor.63Tm
+ ___swift_closure_destructor.71Tm
+ ___swift_closure_destructor.91Tm
+ _associated conformance 15PhotosUIPrivate26GenEditOverlaySettingsView33_A7313E62D829B22283FD0E586959657ELLV5PhaseOSHAASQ
+ _associated conformance 15PhotosUIPrivate26GenEditOverlaySettingsView33_A7313E62D829B22283FD0E586959657ELLV5PhaseOs12CaseIterableAA8AllCasessAGP_Sl
+ _associated conformance 15PhotosUIPrivate26GenEditOverlaySettingsView33_A7313E62D829B22283FD0E586959657ELLV7SwiftUI0G0AA4BodyAeFP_AeF
+ _associated conformance So34PUAssetExplorerReviewScreenOptionsVs10SetAlgebraSCSQ
+ _associated conformance So34PUAssetExplorerReviewScreenOptionsVs10SetAlgebraSCs25ExpressibleByArrayLiteral
+ _associated conformance So34PUAssetExplorerReviewScreenOptionsVs9OptionSetSCSY
+ _associated conformance So34PUAssetExplorerReviewScreenOptionsVs9OptionSetSCs0G7Algebra
+ _flat unique So13UIInteraction_p
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA13_VariadicViewO4TreeVy_AA11_LayoutRootVyAA03AnyH0VGAA05TupleD0VyACyACyAA0F0PAAE9animation_4bodyQrAA9AnimationVSg_qd__AA011PlaceholderdF0VyxGXEtAaORd__lFQOyACyACyACyACy12PhotosUIEdit14PhotoStyleDPadVAA20_GeometryGroupEffectVGAA012_AspectRatioH0VGAA06_FrameH0VGAA32_EnvironmentKeyTransformModifierVySbGG_ACyAWyA12_GAA08_OpacityW0VGQo_AA16_OverlayModifierVyACyApAEAQ_ARQrAU_qd__AXXEtAaORd__lFQOyACyACyAA4TextVA15_GAA010_FixedSizeH0VG_ACyAWyA25_GA15_GQo_AA07_OffsetW0VGSgGGAA21_TraitWritingModifierVyAA14ZIndexTraitKeyVGG_ACyACyACyACyAA0V0VyAA012_ConditionalD0VyACyAY0rS13PaletteSliderVA7_GSgAA6VStackVyAY16ExpandableSliderVGGSgGA30_GA36_yAA18TransitionTraitKeyVGGA39_GAA25_AppearanceActionModifierVGAA6SpacerVSgQPGGAA05_FlexzH0VGAaOHPA70_AaOHPAlA01_ef1_fI0HPyHC_A69_AaOHPA40_AaOHPA34_AaOHPqd0__AaOHD3_A17_HO_A33_AA0F8ModifierHPyHCHC_A39_AAA75_HPyHCHC_A65_AaOHPA62_AaOHPA61_AaOHPA57_AaOHPA56_AaOHPA55_AaOHpA54_AaOHPA48_AaOHpA47_AaOHPA46_AaOHPyHC_A7_AAA75_HPyHCHC_HC_A53_AaOHPyHCHC_HC_HC_A30_AAA75_HPyHCHC_A60_AAA75_HPyHCHC_A39_AAA75_HPyHCHC_A64_AAA75_HPyHCHCA68_AaOHpA67_AaOHPyHC_HCHX_HCHC_A72_AAA75_HPyHCHC
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonG0Rd__lFQOyAA0I0VyACyACyACyACyAA4TextVAA14_PaddingLayoutVGAMGAA19_BackgroundModifierVyAA06_ShapeE0VyAA7CapsuleVAA5ColorVGGGAA01_doN0VyAUGGG_AA05PlainiG0VQo_AA023AccessibilityAttachmentN0VGAaDHPqd0__AaDHD3_A6_HO_A8_AA0eN0HPyHCHC
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA6VStackVyAA05TupleD0VyAA6SpacerV_AA4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAkAEAlmN_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAkAEAlmN_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAkAEAlmN_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAkAEAlmN_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAkAEAlmN_Qrqd___Sbyqd___qd__tctSQRd__lFQOyACy12PhotosUIEdit014PEEditAIStatusH0VAA30_SafeAreaRegionsIgnoringLayoutVG_AO016SpatialReframingH5ModelC9EditStateOQo__AO0V7ReframeVQo__SbQo__SbQo__SSSgQo__SbQo_AISgQPGGAA08_PaddingU0VGAaJHPA8_AaJHPyHC_A10_AA0H8ModifierHPyHCHC
+ _get_witness_table 7SwiftUI15NavigationStackVyAA0C4PathVAA4ViewPAAE7toolbar7contentQrqd__yXE_tAA14ToolbarContentRd__lFQOyAgAE29navigationBarTitleDisplayModeyQrAA0cL4ItemV0mnO0OFQOyAgAE0kM0yQrAA18LocalizedStringKeyVFQOyAA4FormVyAA05TupleJ0VyAA7SectionVyAA05EmptyF0VAgAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAgAE11pickerStyleyQrqd__AA11PickerStyleRd__lFQOyAA6PickerVyAA4TextVSiAA7ForEachVySay15PhotosUIPrivate022GenEditOverlaySettingsF033_A7313E62D829B22283FD0E586959657ELLV5PhaseOGSiAgAE3tag_15includeOptionalQrqd___SbtSHRd__lFQOyA7__SiQo_GG_AA15MenuPickerStyleVQo__SiQo_AZG_AA6IDViewVyA10_012GenEditPhaseV0A12_LLVSiGAXyAZA10_14SettingsToggleA12_LLVAZGQPGG_Qo__Qo__AA0iP0VyytAA6ButtonVyA7_GGQo_GAaFHPyHC
+ _get_witness_table qd__7SwiftUI4ViewHD2_AaBP12PhotosUICoreE22pxReadingAvailableSize2toQrAA7BindingVySo6CGSizeVSgG_tFQOyAA15ModifiedContentVyAA6VStackVyAA05TupleN0VyANyAA6HStackVyARyANyAA4TextVAA31AccessibilityAttachmentModifierVG_AA6SpacerVAA012_ConditionalN0VyAcAE11buttonStyleyQrqd__AA015PrimitiveButtonY0Rd__lFQOyAA6ButtonVyAVG_AA011PlainButtonY0VQo_AA14NavigationLinkVyAV0D9UIPrivate022StoryMusicEditorSeeAllC0VGGQPGGAA14_PaddingLayoutVG_AA06ScrollC6ReaderVyATyARyANyA12_034StoryMusicEditorSongsCollectionRowC0V12ScrollButton33_0D9C64AB384EB33A96CC36AB145A83A5LLVA20_GSg_ANyAcAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQOyAcAEA31_A32_A33__Qrqd___SbyyctSQRd__lFQOyAcAE16scrollIndicators_4axesQrAA25ScrollIndicatorVisibilityV_AA4AxisO3SetVtFQOyAcAE20scrollTargetBehavioryQrqd__AA20ScrollTargetBehaviorRd__lFQOyAcAE14contentMargins__3forQrAA4EdgeOA40_V_12CoreGraphics7CGFloatVSgAA0N15MarginPlacementVtFQOyAA06ScrollC0VyAcAE18scrollTargetLayout9isEnabledQrSb_tFQOyAA04LazyQ0VyAA7ForEachVySnySiGSiANyANyANyAPyA62_ys10ArraySliceVyA12_09StorySongC5ModelCGSSAcAEA2_yQrqd__AAA3_Rd__lFQOyA5_yA12_023StoryMusicEditorSongRowC0VG_A8_Qo_GGAA12_FrameLayoutVGAA017_AppearanceActionU0VGA79_GGG_Qo_G_Qo__AA0C27AlignedScrollTargetBehaviorVQo__Qo__SSSgQo__A91_Qo_A79_GA30_QPGGGSgQPGGA79_G_Qo_HO
+ _symbolic Say_____G 15PhotosUIPrivate26GenEditOverlaySettingsView33_A7313E62D829B22283FD0E586959657ELLV5PhaseO
+ _symbolic Say_____SgG So10CGImageRefa
+ _symbolic So30PUGenEditOverlayEffectSettingsC
+ _symbolic _____ 15PhotosUIPrivate26GenEditOverlaySettingsView33_A7313E62D829B22283FD0E586959657ELLV
+ _symbolic _____ 15PhotosUIPrivate26GenEditOverlaySettingsView33_A7313E62D829B22283FD0E586959657ELLV5PhaseO
+ _symbolic ___________y_____y_____y_____y_____y_____y_____y__________G______Qo_______Qo__SbQo__SbQo__SSSgQo__SbQo_AASgt 7SwiftUI6SpacerV AA4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AeAEAfgH_Qrqd___Sbyqd___qd__tctSQRd__lFQO AeAEAfgH_Qrqd___Sbyqd___qd__tctSQRd__lFQO AeAEAfgH_Qrqd___Sbyqd___qd__tctSQRd__lFQO AeAEAfgH_Qrqd___Sbyqd___qd__tctSQRd__lFQO AeAEAfgH_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA15ModifiedContentV 12PhotosUIEdit014PEEditAIStatusD0V AA30_SafeAreaRegionsIgnoringLayoutV AK016SpatialReframingD5ModelC9EditStateO AK0T7ReframeV
+ _symbolic ______p So13UIInteractionP
+ _symbolic _____yAAyAAyAAy_____y_____yAAy__________GSg_____y_____GGSgG_____G_____y_____GGAPy_____GG_____G 7SwiftUI15ModifiedContentV AA5GroupV AA012_ConditionalD0V 12PhotosUIEdit23PhotoStylePaletteSliderV AA12_FrameLayoutV AA6VStackV AH010ExpandableL0V AA13_OffsetEffectV AA21_TraitWritingModifierV AA010TransitionS3KeyV AA06ZIndexsW0V AA017_AppearanceActionU0V
+ _symbolic _____yAAyAAy_____y_____yAAy__________GSg_____y_____GGSgG_____G_____y_____GGAPy_____GG 7SwiftUI15ModifiedContentV AA5GroupV AA012_ConditionalD0V 12PhotosUIEdit23PhotoStylePaletteSliderV AA12_FrameLayoutV AA6VStackV AH010ExpandableL0V AA13_OffsetEffectV AA21_TraitWritingModifierV AA010TransitionS3KeyV AA06ZIndexsW0V
+ _symbolic _____yAAy_____yAAyAAyAAyAAy__________G_____G_____G_____ySbGG_AAy_____yAKG_____GQo______yAAy_____yAAyAAy_____ANG_____G_AAyALyAUGANGQo______GSgGG_____y_____GG_AAyAAyAAyAAy_____y_____yAAy_____AGGSg_____y_____GGSgGAYGA2_y_____GGA4_G_____G_____Sgt 7SwiftUI15ModifiedContentV AA4ViewPAAE9animation_4bodyQrAA9AnimationVSg_qd__AA011PlaceholderdE0VyxGXEtAaDRd__lFQO 12PhotosUIEdit14PhotoStyleDPadV AA20_GeometryGroupEffectV AA18_AspectRatioLayoutV AA06_FrameT0V AA32_EnvironmentKeyTransformModifierV AL AA08_OpacityQ0V AA08_OverlayY0V AeAEAF_AGQrAJ_qd__AMXEtAaDRd__lFQO AA4TextV AA010_FixedSizeT0V AA07_OffsetQ0V AA013_TraitWritingY0V AA011ZIndexTraitW0V AA0P0V AA012_ConditionalD0V AN0lM13PaletteSliderV AA6VStackV AN16ExpandableSliderV AA015TransitionTraitW0V AA017_AppearanceActionY0V AA6SpacerV
+ _symbolic _____yAAy_____y_____yAAy__________GSg_____y_____GGSgG_____G_____y_____GG 7SwiftUI15ModifiedContentV AA5GroupV AA012_ConditionalD0V 12PhotosUIEdit23PhotoStylePaletteSliderV AA12_FrameLayoutV AA6VStackV AH010ExpandableL0V AA13_OffsetEffectV AA21_TraitWritingModifierV AA010TransitionS3KeyV
+ _symbolic _____ySay_____GSi_____y______SiQo_G 7SwiftUI7ForEachV 15PhotosUIPrivate26GenEditOverlaySettingsView33_A7313E62D829B22283FD0E586959657ELLV5PhaseO AA0K0PAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA4TextV
+ _symbolic _____y_____G 7SwiftUI19UIHostingControllerC 15PhotosUIPrivate26GenEditOverlaySettingsView33_A7313E62D829B22283FD0E586959657ELLV
+ _symbolic _____y_____G 7SwiftUI19UIHostingControllerC AA7AnyViewV
+ _symbolic _____y_____G 7SwiftUI6VStackV 12PhotosUIEdit16ExpandableSliderV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So6CGSizeV
+ _symbolic _____y_____GSg 7SwiftUI19UIHostingControllerC AA7AnyViewV
+ _symbolic _____y_____Si_____ySay_____GSi_____yAB_SiQo_GG 7SwiftUI6PickerV AA4TextV AA7ForEachV 15PhotosUIPrivate26GenEditOverlaySettingsView33_A7313E62D829B22283FD0E586959657ELLV5PhaseO AA0M0PAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO
+ _symbolic _____y__________G 7SwiftUI15ModifiedContentV AA4TextV AA31AccessibilityAttachmentModifierV
+ _symbolic _____y__________G___________y_____y_____yABG______Qo______yAB_____GGt 7SwiftUI15ModifiedContentV AA4TextV AA31AccessibilityAttachmentModifierV AA6SpacerV AA012_ConditionalD0V AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonM0Rd__lFQO AA0O0V AA05PlainoM0V AA14NavigationLinkV 15PhotosUIPrivate022StoryMusicEditorSeeAllK0V
+ _symbolic _____y___________y___________y_____y_____y_____y_____y_____y_____y__________G______Qo_______Qo__SbQo__SbQo__SSSgQo__SbQo_ADSgQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA6SpacerV AA0D0PAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AmAEAnoP_Qrqd___Sbyqd___qd__tctSQRd__lFQO AmAEAnoP_Qrqd___Sbyqd___qd__tctSQRd__lFQO AmAEAnoP_Qrqd___Sbyqd___qd__tctSQRd__lFQO AmAEAnoP_Qrqd___Sbyqd___qd__tctSQRd__lFQO AmAEAnoP_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA08ModifiedI0V 12PhotosUIEdit014PEEditAIStatusD0V AA024_SafeAreaRegionsIgnoringG0V AS016SpatialReframingD5ModelC9EditStateO AS0X7ReframeV
+ _symbolic _____y___________y_____y__________G___________y_____y_____yAEG______Qo______yAE_____GGQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA08ModifiedI0V AA4TextV AA31AccessibilityAttachmentModifierV AA6SpacerV AA012_ConditionalI0V AA0D0PAAE11buttonStyleyQrqd__AA015PrimitiveButtonR0Rd__lFQO AA0T0V AA05PlaintR0V AA14NavigationLinkV 15PhotosUIPrivate022StoryMusicEditorSeeAllD0V
+ _symbolic _____y___________y_____y_____yACyADy__________G___________y_____y_____yAFG______Qo______yAF_____GGQPGG_____G______yAEyACyADy_____AUGSg_ADy_____y_____y_____y_____y_____y_____y_____y_____y_____ySnySiGSiADyADyADy_____yA1_y_____y_____GSS_____yAKy_____G_AMQo_GG_____G_____GA14_GGG_Qo_G_Qo_______Qo__Qo__SSSgQo__A25_Qo_A14_GAZQPGGGSgQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA08ModifiedI0V AA6HStackV AA4TextV AA31AccessibilityAttachmentModifierV AA6SpacerV AA012_ConditionalI0V AA0D0PAAE11buttonStyleyQrqd__AA015PrimitiveButtonS0Rd__lFQO AA0U0V AA05PlainuS0V AA14NavigationLinkV 15PhotosUIPrivate022StoryMusicEditorSeeAllD0V AA08_PaddingG0V AA06ScrollD6ReaderV A4_034StoryMusicEditorSongsCollectionRowD0V06ScrollU033_0D9C64AB384EB33A96CC36AB145A83A5LLV AwAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQO AwAEA16_A17_A18__Qrqd___SbyyctSQRd__lFQO AwAE16scrollIndicators_4axesQrAA25ScrollIndicatorVisibilityV_AA4AxisO3SetVtFQO AwAE20scrollTargetBehavioryQrqd__AA20ScrollTargetBehaviorRd__lFQO AwAE14contentMargins__3forQrAA4EdgeOA25_V_12CoreGraphics7CGFloatVSgAA0I15MarginPlacementVtFQO AA06ScrollD0V AwAE012scrollTargetG09isEnabledQrSb_tFQO AA04LazyK0V AA7ForEachV AA0F0V s10ArraySliceV A4_09StorySongD5ModelC AwAEAXyQrqd__AaYRd__lFQO A4_023StoryMusicEditorSongRowD0V AA06_FrameG0V AA017_AppearanceActionO0V AA0D27AlignedScrollTargetBehaviorV
+ _symbolic _____y__________y_____y_____y_____Si_____ySay_____GSi_____yAD_SiQo_GG______Qo__SiQo_ABG 7SwiftUI7SectionV AA9EmptyViewV AA0E0PAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AgAE11pickerStyleyQrqd__AA06PickerK0Rd__lFQO AA0L0V AA4TextV AA7ForEachV 15PhotosUIPrivate022GenEditOverlaySettingsE033_A7313E62D829B22283FD0E586959657ELLV5PhaseO AgAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA04MenulK0V
+ _symbolic _____y__________y_____y_____y_____Si_____ySay_____GSi_____yAD_SiQo_GG______Qo__SiQo_ABG______y_____SiGAAyAB_____ABGt 7SwiftUI7SectionV AA9EmptyViewV AA0E0PAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AgAE11pickerStyleyQrqd__AA06PickerK0Rd__lFQO AA0L0V AA4TextV AA7ForEachV 15PhotosUIPrivate022GenEditOverlaySettingsE033_A7313E62D829B22283FD0E586959657ELLV5PhaseO AgAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA04MenulK0V AA6IDViewV AS0rs5PhaseC0AULLV AS0U6ToggleAULLV
+ _symbolic _____y__________y_____y_____y_____y_____y_____y__________y_____y_____y_____Si_____ySay_____GSi_____yAH_SiQo_GG______Qo__SiQo_AFG______y_____SiGAEyAF_____AFGQPGG_Qo__Qo_______yyt_____yAHGGQo_G 7SwiftUI15NavigationStackV AA0C4PathV AA4ViewPAAE7toolbar7contentQrqd__yXE_tAA14ToolbarContentRd__lFQO AgAE29navigationBarTitleDisplayModeyQrAA0cL4ItemV0mnO0OFQO AgAE0kM0yQrAA18LocalizedStringKeyVFQO AA4FormV AA05TupleJ0V AA7SectionV AA05EmptyF0V AgAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AgAE11pickerStyleyQrqd__AA11PickerStyleRd__lFQO AA6PickerV AA4TextV AA7ForEachV 15PhotosUIPrivate022GenEditOverlaySettingsF033_A7313E62D829B22283FD0E586959657ELLV5PhaseO AgAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA15MenuPickerStyleV AA6IDViewV A10_012GenEditPhaseV0A12_LLV A10_14SettingsToggleA12_LLV AA0iP0V AA6ButtonV
+ _symbolic _____y______y_____G_____y_____yAFy_____yAFyAFyAFyAFy__________G_____G_____G_____ySbGG_AFy_____yAPG_____GQo______yAFy_____yAFyAFy_____ASG_____G_AFyAQyAZGASGQo______GSgGG_____y_____GG_AFyAFyAFyAFy_____y_____yAFy_____ALGSg_____y_____GGSgGA2_GA7_y_____GGA9_G_____G_____SgQPGG 7SwiftUI13_VariadicViewO4TreeV AA11_LayoutRootV AA03AnyF0V AA12TupleContentV AA08ModifiedJ0V AA0D0PAAE9animation_4bodyQrAA9AnimationVSg_qd__AA011PlaceholderjD0VyxGXEtAaNRd__lFQO 12PhotosUIEdit14PhotoStyleDPadV AA20_GeometryGroupEffectV AA012_AspectRatioF0V AA06_FrameF0V AA32_EnvironmentKeyTransformModifierV AV AA08_OpacityW0V AA16_OverlayModifierV AoAEAP_AQQrAT_qd__AWXEtAaNRd__lFQO AA4TextV AA010_FixedSizeF0V AA07_OffsetW0V AA21_TraitWritingModifierV AA14ZIndexTraitKeyV AA0V0V AA012_ConditionalJ0V AX0rS13PaletteSliderV AA6VStackV AX16ExpandableSliderV AA18TransitionTraitKeyV AA25_AppearanceActionModifierV AA6SpacerV
+ _symbolic _____y_____yABy_____yAByAByAByABy__________G_____G_____G_____ySbGG_ABy_____yALG_____GQo______yABy_____yAByABy_____AOG_____G_AByAMyAVGAOGQo______GSgGG_____y_____GG_AByAByAByABy_____y_____yABy_____AHGSg_____y_____GGSgGAZGA3_y_____GGA5_G_____G_____SgQPG 7SwiftUI12TupleContentV AA08ModifiedD0V AA4ViewPAAE9animation_4bodyQrAA9AnimationVSg_qd__AA011PlaceholderdF0VyxGXEtAaFRd__lFQO 12PhotosUIEdit14PhotoStyleDPadV AA20_GeometryGroupEffectV AA18_AspectRatioLayoutV AA06_FrameU0V AA32_EnvironmentKeyTransformModifierV AN AA08_OpacityR0V AA08_OverlayZ0V AgAEAH_AIQrAL_qd__AOXEtAaFRd__lFQO AA4TextV AA010_FixedSizeU0V AA07_OffsetR0V AA013_TraitWritingZ0V AA011ZIndexTraitX0V AA0Q0V AA012_ConditionalD0V AP0mN13PaletteSliderV AA6VStackV AP16ExpandableSliderV AA015TransitionTraitX0V AA017_AppearanceActionZ0V AA6SpacerV
+ _symbolic _____y_____y_____Si_____ySay_____GSi_____yAB_SiQo_GG______Qo_ 7SwiftUI4ViewPAAE11pickerStyleyQrqd__AA06PickerE0Rd__lFQO AA0F0V AA4TextV AA7ForEachV 15PhotosUIPrivate022GenEditOverlaySettingsC033_A7313E62D829B22283FD0E586959657ELLV5PhaseO AcAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA04MenufE0V
+ _symbolic _____y_____y__________GSg_____y_____GG 7SwiftUI19_ConditionalContentV AA08ModifiedD0V 12PhotosUIEdit23PhotoStylePaletteSliderV AA12_FrameLayoutV AA6VStackV AF010ExpandableK0V
+ _symbolic _____y_____y__________GSg_____y_____GGSg 7SwiftUI19_ConditionalContentV AA08ModifiedD0V 12PhotosUIEdit23PhotoStylePaletteSliderV AA12_FrameLayoutV AA6VStackV AF010ExpandableK0V
+ _symbolic _____y_____y__________GSg_____y_____G_G 7SwiftUI19_ConditionalContentV7StorageO AA08ModifiedD0V 12PhotosUIEdit23PhotoStylePaletteSliderV AA12_FrameLayoutV AA6VStackV AH010ExpandableL0V
+ _symbolic _____y_____y___________y_____y_____y_____y_____y_____y_____y__________G______Qo_______Qo__SbQo__SbQo__SSSgQo__SbQo_ACSgQPGG 7SwiftUI6VStackV AA12TupleContentV AA6SpacerV AA4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AiAEAjkL_Qrqd___Sbyqd___qd__tctSQRd__lFQO AiAEAjkL_Qrqd___Sbyqd___qd__tctSQRd__lFQO AiAEAjkL_Qrqd___Sbyqd___qd__tctSQRd__lFQO AiAEAjkL_Qrqd___Sbyqd___qd__tctSQRd__lFQO AiAEAjkL_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA08ModifiedE0V 12PhotosUIEdit014PEEditAIStatusG0V AA30_SafeAreaRegionsIgnoringLayoutV AO016SpatialReframingG5ModelC9EditStateO AO0V7ReframeV
+ _symbolic _____y_____y__________y_____y_____y_____Si_____ySay_____GSi_____yAE_SiQo_GG______Qo__SiQo_ACG______y_____SiGAByAC_____ACGQPG 7SwiftUI12TupleContentV AA7SectionV AA9EmptyViewV AA0G0PAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AiAE11pickerStyleyQrqd__AA06PickerM0Rd__lFQO AA0N0V AA4TextV AA7ForEachV 15PhotosUIPrivate022GenEditOverlaySettingsG033_A7313E62D829B22283FD0E586959657ELLV5PhaseO AiAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA04MenunM0V AA6IDViewV AU0tu5PhaseE0AWLLV AU0W6ToggleAWLLV
+ _symbolic _____y_____y______y_____G_____yAAyAAy_____yAAyAAyAAyAAy__________G_____G_____G_____ySbGG_AAy_____yAPG_____GQo______yAAy_____yAAyAAy_____ASG_____G_AAyAQyAZGASGQo______GSgGG_____y_____GG_AAyAAyAAyAAy_____y_____yAAy_____ALGSg_____y_____GGSgGA2_GA7_y_____GGA9_G_____G_____SgQPGG_____G 7SwiftUI15ModifiedContentV AA13_VariadicViewO4TreeV AA11_LayoutRootV AA03AnyH0V AA05TupleD0V AA0F0PAAE9animation_4bodyQrAA9AnimationVSg_qd__AA011PlaceholderdF0VyxGXEtAaNRd__lFQO 12PhotosUIEdit14PhotoStyleDPadV AA20_GeometryGroupEffectV AA012_AspectRatioH0V AA06_FrameH0V AA32_EnvironmentKeyTransformModifierV AV AA08_OpacityW0V AA16_OverlayModifierV AoAEAP_AQQrAT_qd__AWXEtAaNRd__lFQO AA4TextV AA010_FixedSizeH0V AA07_OffsetW0V AA21_TraitWritingModifierV AA14ZIndexTraitKeyV AA0V0V AA012_ConditionalD0V AX0rS13PaletteSliderV AA6VStackV AX16ExpandableSliderV AA18TransitionTraitKeyV AA25_AppearanceActionModifierV AA6SpacerV AA05_FlexzH0V
+ _symbolic _____y_____y_____yAAyAAyAAyAAy__________GADG_____y_____y__________GGG_____yAIGGG______Qo______G 7SwiftUI15ModifiedContentV AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonG0Rd__lFQO AA0I0V AA4TextV AA14_PaddingLayoutV AA19_BackgroundModifierV AA06_ShapeE0V AA7CapsuleV AA5ColorV AA01_doN0V AA05PlainiG0V AA023AccessibilityAttachmentN0V
+ _symbolic _____y_____y_____yAAy__________GSg_____y_____GGSgG_____G 7SwiftUI15ModifiedContentV AA5GroupV AA012_ConditionalD0V 12PhotosUIEdit23PhotoStylePaletteSliderV AA12_FrameLayoutV AA6VStackV AH010ExpandableL0V AA13_OffsetEffectV
+ _symbolic _____y_____y_____yAAy__________G___________y_____y_____yADG______Qo______yAD_____GGQPGG_____G 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA4TextV AA31AccessibilityAttachmentModifierV AA6SpacerV AA012_ConditionalD0V AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonO0Rd__lFQO AA0Q0V AA05PlainqO0V AA14NavigationLinkV 15PhotosUIPrivate022StoryMusicEditorSeeAllM0V AA14_PaddingLayoutV
+ _symbolic _____y_____y_____yAAy__________G___________y_____y_____yADG______Qo______yAD_____GGQPGG_____G______yAByACyAAy_____ASGSg_AAy_____y_____y_____y_____y_____y_____y_____y_____y_____ySnySiGSiAAyAAyAAy_____yA_y_____y_____GSS_____yAIy_____G_AKQo_GG_____G_____GA12_GGG_Qo_G_Qo_______Qo__Qo__SSSgQo__A23_Qo_A12_GAXQPGGGSgt 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA4TextV AA31AccessibilityAttachmentModifierV AA6SpacerV AA012_ConditionalD0V AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonO0Rd__lFQO AA0Q0V AA05PlainqO0V AA14NavigationLinkV 15PhotosUIPrivate022StoryMusicEditorSeeAllM0V AA14_PaddingLayoutV AA06ScrollM6ReaderV AZ0wxy18SongsCollectionRowM0V06ScrollQ033_0D9C64AB384EB33A96CC36AB145A83A5LLV AqAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQO AqAEA10_A11_A12__Qrqd___SbyyctSQRd__lFQO AqAE16scrollIndicators_4axesQrAA25ScrollIndicatorVisibilityV_AA4AxisO3SetVtFQO AqAE20scrollTargetBehavioryQrqd__AA20ScrollTargetBehaviorRd__lFQO AqAE14contentMargins__3forQrAA4EdgeOA19_V_12CoreGraphics7CGFloatVSgAA0D15MarginPlacementVtFQO AA06ScrollM0V AqAE18scrollTargetLayout9isEnabledQrSb_tFQO AA04LazyE0V AA7ForEachV AA6VStackV s10ArraySliceV AZ0w4SongM5ModelC AqAEARyQrqd__AaSRd__lFQO AZ0wxy7SongRowM0V AA12_FrameLayoutV AA017_AppearanceActionJ0V AA0M27AlignedScrollTargetBehaviorV
+ _symbolic _____y_____y_____yAAy_____yACyAAy__________G___________y_____y_____yAEG______Qo______yAE_____GGQPGG_____G______yADyACyAAy_____ATGSg_AAy_____y_____y_____y_____y_____y_____y_____y_____y_____ySnySiGSiAAyAAyAAyAByA0_y_____y_____GSS_____yAJy_____G_ALQo_GG_____G_____GA12_GGG_Qo_G_Qo_______Qo__Qo__SSSgQo__A23_Qo_A12_GAYQPGGGSgQPGGA12_G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA6HStackV AA4TextV AA31AccessibilityAttachmentModifierV AA6SpacerV AA012_ConditionalD0V AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonP0Rd__lFQO AA0R0V AA05PlainrP0V AA14NavigationLinkV 15PhotosUIPrivate022StoryMusicEditorSeeAllN0V AA14_PaddingLayoutV AA06ScrollN6ReaderV A0_0xyz18SongsCollectionRowN0V06ScrollR033_0D9C64AB384EB33A96CC36AB145A83A5LLV AsAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQO AsAEA12_A13_A14__Qrqd___SbyyctSQRd__lFQO AsAE16scrollIndicators_4axesQrAA25ScrollIndicatorVisibilityV_AA4AxisO3SetVtFQO AsAE20scrollTargetBehavioryQrqd__AA20ScrollTargetBehaviorRd__lFQO AsAE14contentMargins__3forQrAA4EdgeOA21_V_12CoreGraphics7CGFloatVSgAA0D15MarginPlacementVtFQO AA06ScrollN0V AsAE18scrollTargetLayout9isEnabledQrSb_tFQO AA04LazyG0V AA7ForEachV s10ArraySliceV A0_0x4SongN5ModelC AsAEATyQrqd__AaURd__lFQO A0_0xyz7SongRowN0V AA12_FrameLayoutV AA017_AppearanceActionK0V AA0N27AlignedScrollTargetBehaviorV
+ _symbolic _____y_____y_____y_____Si_____ySay_____GSi_____yAB_SiQo_GG______Qo__SiQo_ 7SwiftUI4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAE11pickerStyleyQrqd__AA06PickerI0Rd__lFQO AA0J0V AA4TextV AA7ForEachV 15PhotosUIPrivate022GenEditOverlaySettingsC033_A7313E62D829B22283FD0E586959657ELLV5PhaseO AcAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA04MenujI0V
+ _symbolic _____y_____y_____y__________GSg_____y_____GGSgG 7SwiftUI5GroupV AA19_ConditionalContentV AA08ModifiedE0V 12PhotosUIEdit23PhotoStylePaletteSliderV AA12_FrameLayoutV AA6VStackV AH010ExpandableL0V
+ _symbolic _____y_____y_____y__________G___________y_____y_____yADG______Qo______yAD_____GGQPGG 7SwiftUI6HStackV AA12TupleContentV AA08ModifiedE0V AA4TextV AA31AccessibilityAttachmentModifierV AA6SpacerV AA012_ConditionalE0V AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonO0Rd__lFQO AA0Q0V AA05PlainqO0V AA14NavigationLinkV 15PhotosUIPrivate022StoryMusicEditorSeeAllM0V
+ _symbolic _____y_____y_____y___________y_____y_____y_____y_____y_____yAAy__________G______Qo_______Qo__SbQo__SbQo__SSSgQo__SbQo_ADSgQPGG_____G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA6SpacerV AA4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AkAEAlmN_Qrqd___Sbyqd___qd__tctSQRd__lFQO AkAEAlmN_Qrqd___Sbyqd___qd__tctSQRd__lFQO AkAEAlmN_Qrqd___Sbyqd___qd__tctSQRd__lFQO AkAEAlmN_Qrqd___Sbyqd___qd__tctSQRd__lFQO AkAEAlmN_Qrqd___Sbyqd___qd__tctSQRd__lFQO 12PhotosUIEdit014PEEditAIStatusH0V AA30_SafeAreaRegionsIgnoringLayoutV AO016SpatialReframingH5ModelC9EditStateO AO0V7ReframeV AA08_PaddingU0V
+ _symbolic _____y_____y_____y__________y_____y_____y_____Si_____ySay_____GSi_____yAF_SiQo_GG______Qo__SiQo_ADG______y_____SiGACyAD_____ADGQPGG 7SwiftUI4FormV AA12TupleContentV AA7SectionV AA9EmptyViewV AA0H0PAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AkAE11pickerStyleyQrqd__AA06PickerN0Rd__lFQO AA0O0V AA4TextV AA7ForEachV 15PhotosUIPrivate022GenEditOverlaySettingsH033_A7313E62D829B22283FD0E586959657ELLV5PhaseO AkAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA04MenuoN0V AA6IDViewV AW0uv5PhaseF0AYLLV AW0X6ToggleAYLLV
+ _symbolic _____y_____y_____y_____yAAy_____yACyAAy__________G___________y_____y_____yAEG______Qo______yAE_____GGQPGG_____G______yADyACyAAy_____ATGSg_AAy_____y_____y_____y_____y_____y_____y_____y_____y_____ySnySiGSiAAyAAyAAyAByA0_y_____y_____GSS_____yAJy_____G_ALQo_GG_____G_____GA12_GGG_Qo_G_Qo_______Qo__Qo__SSSgQo__A23_Qo_A12_GAYQPGGGSgQPGGA12_G_Qo_ 7SwiftUI4ViewP12PhotosUICoreE22pxReadingAvailableSize2toQrAA7BindingVySo6CGSizeVSgG_tFQO AA15ModifiedContentV AA6VStackV AA05TupleN0V AA6HStackV AA4TextV AA31AccessibilityAttachmentModifierV AA6SpacerV AA012_ConditionalN0V AcAE11buttonStyleyQrqd__AA015PrimitiveButtonY0Rd__lFQO AA6ButtonV AA011PlainButtonY0V AA14NavigationLinkV 0D9UIPrivate022StoryMusicEditorSeeAllC0V AA14_PaddingLayoutV AA06ScrollC6ReaderV A9_034StoryMusicEditorSongsCollectionRowC0V12ScrollButton33_0D9C64AB384EB33A96CC36AB145A83A5LLV AcAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQO AcAEA21_A22_A23__Qrqd___SbyyctSQRd__lFQO AcAE16scrollIndicators_4axesQrAA25ScrollIndicatorVisibilityV_AA4AxisO3SetVtFQO AcAE20scrollTargetBehavioryQrqd__AA20ScrollTargetBehaviorRd__lFQO AcAE14contentMargins__3forQrAA4EdgeOA30_V_12CoreGraphics7CGFloatVSgAA0N15MarginPlacementVtFQO AA06ScrollC0V AcAE18scrollTargetLayout9isEnabledQrSb_tFQO AA04LazyQ0V AA7ForEachV s10ArraySliceV A9_09StorySongC5ModelC AcAEA1_yQrqd__AAA2_Rd__lFQO A9_023StoryMusicEditorSongRowC0V AA12_FrameLayoutV AA017_AppearanceActionU0V AA0C27AlignedScrollTargetBehaviorV
+ _symbolic _____y_____y_____y_____yAByACy__________G___________y_____y_____yAEG______Qo______yAE_____GGQPGG_____G______yADyAByACy_____ATGSg_ACy_____y_____y_____y_____y_____y_____y_____y_____y_____ySnySiGSiACyACyACyAAyA0_y_____y_____GSS_____yAJy_____G_ALQo_GG_____G_____GA12_GGG_Qo_G_Qo_______Qo__Qo__SSSgQo__A23_Qo_A12_GAYQPGGGSgQPGG 7SwiftUI6VStackV AA12TupleContentV AA08ModifiedE0V AA6HStackV AA4TextV AA31AccessibilityAttachmentModifierV AA6SpacerV AA012_ConditionalE0V AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonP0Rd__lFQO AA0R0V AA05PlainrP0V AA14NavigationLinkV 15PhotosUIPrivate022StoryMusicEditorSeeAllN0V AA14_PaddingLayoutV AA06ScrollN6ReaderV A0_0xyz18SongsCollectionRowN0V06ScrollR033_0D9C64AB384EB33A96CC36AB145A83A5LLV AsAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQO AsAEA12_A13_A14__Qrqd___SbyyctSQRd__lFQO AsAE16scrollIndicators_4axesQrAA25ScrollIndicatorVisibilityV_AA4AxisO3SetVtFQO AsAE20scrollTargetBehavioryQrqd__AA20ScrollTargetBehaviorRd__lFQO AsAE14contentMargins__3forQrAA4EdgeOA21_V_12CoreGraphics7CGFloatVSgAA0E15MarginPlacementVtFQO AA06ScrollN0V AsAE18scrollTargetLayout9isEnabledQrSb_tFQO AA04LazyG0V AA7ForEachV s10ArraySliceV A0_0x4SongN5ModelC AsAEATyQrqd__AaURd__lFQO A0_0xyz7SongRowN0V AA12_FrameLayoutV AA017_AppearanceActionK0V AA0N27AlignedScrollTargetBehaviorV
+ _symbolic _____y_____y_____y_____y__________y_____y_____y_____Si_____ySay_____GSi_____yAF_SiQo_GG______Qo__SiQo_ADG______y_____SiGACyAD_____ADGQPGG_Qo_ 7SwiftUI4ViewPAAE15navigationTitleyQrAA18LocalizedStringKeyVFQO AA4FormV AA12TupleContentV AA7SectionV AA05EmptyC0V AcAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAE11pickerStyleyQrqd__AA06PickerS0Rd__lFQO AA0T0V AA4TextV AA7ForEachV 15PhotosUIPrivate022GenEditOverlaySettingsC033_A7313E62D829B22283FD0E586959657ELLV5PhaseO AcAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA04MenutS0V AA6IDViewV AZ0z9EditPhaseL0A0_LLV AZ14SettingsToggleA0_LLV
+ _symbolic _____y_____y_____y_____y_____y__________y_____y_____y_____Si_____ySay_____GSi_____yAF_SiQo_GG______Qo__SiQo_ADG______y_____SiGACyAD_____ADGQPGG_Qo__Qo_ 7SwiftUI4ViewPAAE29navigationBarTitleDisplayModeyQrAA010NavigationE4ItemV0fgH0OFQO AcAE0dF0yQrAA18LocalizedStringKeyVFQO AA4FormV AA12TupleContentV AA7SectionV AA05EmptyC0V AcAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAE11pickerStyleyQrqd__AA06PickerX0Rd__lFQO AA0Y0V AA4TextV AA7ForEachV 15PhotosUIPrivate022GenEditOverlaySettingsC033_A7313E62D829B22283FD0E586959657ELLV5PhaseO AcAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA04MenuyX0V AA6IDViewV A3_012GenEditPhaseQ0A5_LLV A3_14SettingsToggleA5_LLV
+ _symbolic _____y_____y_____y_____y_____y_____y__________G______Qo_______Qo__SbQo__SbQo__SSSgQo_ 7SwiftUI4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAdeF_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAdeF_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAdeF_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAdeF_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA15ModifiedContentV 12PhotosUIEdit014PEEditAIStatusC0V AA30_SafeAreaRegionsIgnoringLayoutV AI016SpatialReframingC5ModelC9EditStateO AI0S7ReframeV
+ _symbolic _____y_____y_____y_____y_____y_____y__________y_____y_____y_____Si_____ySay_____GSi_____yAF_SiQo_GG______Qo__SiQo_ADG______y_____SiGACyAD_____ADGQPGG_Qo__Qo_______yyt_____yAFGGQo_ 7SwiftUI4ViewPAAE7toolbar7contentQrqd__yXE_tAA14ToolbarContentRd__lFQO AcAE29navigationBarTitleDisplayModeyQrAA010NavigationI4ItemV0jkL0OFQO AcAE0hJ0yQrAA18LocalizedStringKeyVFQO AA4FormV AA05TupleG0V AA7SectionV AA05EmptyC0V AcAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAE11pickerStyleyQrqd__AA11PickerStyleRd__lFQO AA6PickerV AA4TextV AA7ForEachV 15PhotosUIPrivate022GenEditOverlaySettingsC033_A7313E62D829B22283FD0E586959657ELLV5PhaseO AcAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA15MenuPickerStyleV AA6IDViewV A6_012GenEditPhaseT0A8_LLV A6_14SettingsToggleA8_LLV AA0fN0V AA6ButtonV
+ _symbolic _____y_____y_____y_____y_____y_____y_____y__________G______Qo_______Qo__SbQo__SbQo__SSSgQo__SbQo_ 7SwiftUI4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAdeF_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAdeF_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAdeF_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAdeF_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAdeF_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA15ModifiedContentV 12PhotosUIEdit014PEEditAIStatusC0V AA30_SafeAreaRegionsIgnoringLayoutV AI016SpatialReframingC5ModelC9EditStateO AI0S7ReframeV
+ _type_layout_string 15PhotosUIPrivate17PickerOptionsViewV
- +[PUOutfillEffectSettings settingsControllerModule]
- +[PUOutfillEffectSettings sharedInstance]
- +[PUReframeEffectSettings settingsControllerModule]
- +[PUReframeEffectSettings sharedInstance]
- -[PUCropToolController outfillCanvasConstraints]
- -[PUCropToolController setOutfillCanvasConstraints:]
- -[PUCropToolController setShowOutfillExtendButton:]
- -[PUCropToolController showOutfillExtendButton]
- -[PUNavigationTransition setWasStatusBarHiddenBeforeTransition:]
- -[PUNavigationTransition wasStatusBarHiddenBeforeTransition]
- -[PUOutfillEffectSettings loading_bias]
- -[PUOutfillEffectSettings loading_blurRadius]
- -[PUOutfillEffectSettings loading_chromaticFringingIntensity]
- -[PUOutfillEffectSettings loading_distortionGrainScale]
- -[PUOutfillEffectSettings loading_distortionStrength]
- -[PUOutfillEffectSettings loading_maskBlurRadius]
- -[PUOutfillEffectSettings loading_maskInsetPerBlurRadius]
- -[PUOutfillEffectSettings loading_maskMeshAmplitude]
- -[PUOutfillEffectSettings loading_maskMeshSpeed]
- -[PUOutfillEffectSettings loading_mirrorExtensionScale]
- -[PUOutfillEffectSettings loading_saturation]
- -[PUOutfillEffectSettings loading_speed]
- -[PUOutfillEffectSettings loading_transitionDuration]
- -[PUOutfillEffectSettings parentSettings]
- -[PUOutfillEffectSettings placeholder_bias]
- -[PUOutfillEffectSettings placeholder_blurRadius]
- -[PUOutfillEffectSettings placeholder_chromaticFringingIntensity]
- -[PUOutfillEffectSettings placeholder_distortionGrainScale]
- -[PUOutfillEffectSettings placeholder_distortionStrength]
- -[PUOutfillEffectSettings placeholder_maskBlurRadius]
- -[PUOutfillEffectSettings placeholder_maskInsetPerBlurRadius]
- -[PUOutfillEffectSettings placeholder_maskMeshAmplitude]
- -[PUOutfillEffectSettings placeholder_maskMeshSpeed]
- -[PUOutfillEffectSettings placeholder_mirrorExtensionScale]
- -[PUOutfillEffectSettings placeholder_saturation]
- -[PUOutfillEffectSettings placeholder_speed]
- -[PUOutfillEffectSettings placeholder_transitionDuration]
- -[PUOutfillEffectSettings renderAtPointResolution]
- -[PUOutfillEffectSettings setDefaultValues]
- -[PUOutfillEffectSettings setLoading_bias:]
- -[PUOutfillEffectSettings setLoading_blurRadius:]
- -[PUOutfillEffectSettings setLoading_chromaticFringingIntensity:]
- -[PUOutfillEffectSettings setLoading_distortionGrainScale:]
- -[PUOutfillEffectSettings setLoading_distortionStrength:]
- -[PUOutfillEffectSettings setLoading_maskBlurRadius:]
- -[PUOutfillEffectSettings setLoading_maskInsetPerBlurRadius:]
- -[PUOutfillEffectSettings setLoading_maskMeshAmplitude:]
- -[PUOutfillEffectSettings setLoading_maskMeshSpeed:]
- -[PUOutfillEffectSettings setLoading_mirrorExtensionScale:]
- -[PUOutfillEffectSettings setLoading_saturation:]
- -[PUOutfillEffectSettings setLoading_speed:]
- -[PUOutfillEffectSettings setLoading_transitionDuration:]
- -[PUOutfillEffectSettings setPlaceholder_bias:]
- -[PUOutfillEffectSettings setPlaceholder_blurRadius:]
- -[PUOutfillEffectSettings setPlaceholder_chromaticFringingIntensity:]
- -[PUOutfillEffectSettings setPlaceholder_distortionGrainScale:]
- -[PUOutfillEffectSettings setPlaceholder_distortionStrength:]
- -[PUOutfillEffectSettings setPlaceholder_maskBlurRadius:]
- -[PUOutfillEffectSettings setPlaceholder_maskInsetPerBlurRadius:]
- -[PUOutfillEffectSettings setPlaceholder_maskMeshAmplitude:]
- -[PUOutfillEffectSettings setPlaceholder_maskMeshSpeed:]
- -[PUOutfillEffectSettings setPlaceholder_mirrorExtensionScale:]
- -[PUOutfillEffectSettings setPlaceholder_saturation:]
- -[PUOutfillEffectSettings setPlaceholder_speed:]
- -[PUOutfillEffectSettings setPlaceholder_transitionDuration:]
- -[PUOutfillEffectSettings setRenderAtPointResolution:]
- -[PUOutfillEffectSettings setShowConfigurationPanel:]
- -[PUOutfillEffectSettings showConfigurationPanel]
- -[PUPXBarAppearanceImplementationDelegate barAppearanceIsStatusBarVisible:]
- -[PUPhotoEditProtoSettings outfillEffectSettings]
- -[PUPhotoEditProtoSettings reframeEffectSettings]
- -[PUPhotoEditProtoSettings setOutfillEffectSettings:]
- -[PUPhotoEditProtoSettings setReframeEffectSettings:]
- -[PUPhotoEditViewController nuAsset]
- -[PUPhotoEditViewController setNuAsset:]
- -[PUReframeEffectSettings parentSettings]
- -[PUReframeEffectSettings preview_bias]
- -[PUReframeEffectSettings preview_blurRadius]
- -[PUReframeEffectSettings preview_chromaticFringingIntensity]
- -[PUReframeEffectSettings preview_distortionGrainScale]
- -[PUReframeEffectSettings preview_distortionStrength]
- -[PUReframeEffectSettings preview_maskBlurRadius]
- -[PUReframeEffectSettings preview_maskMeshAmplitude]
- -[PUReframeEffectSettings preview_maskMeshSpeed]
- -[PUReframeEffectSettings preview_mirrorExtensionScale]
- -[PUReframeEffectSettings preview_saturation]
- -[PUReframeEffectSettings preview_speed]
- -[PUReframeEffectSettings preview_transitionDuration]
- -[PUReframeEffectSettings processing_bias]
- -[PUReframeEffectSettings processing_blurRadius]
- -[PUReframeEffectSettings processing_chromaticFringingIntensity]
- -[PUReframeEffectSettings processing_distortionGrainScale]
- -[PUReframeEffectSettings processing_distortionStrength]
- -[PUReframeEffectSettings processing_maskBlurRadius]
- -[PUReframeEffectSettings processing_maskMeshAmplitude]
- -[PUReframeEffectSettings processing_maskMeshSpeed]
- -[PUReframeEffectSettings processing_mirrorExtensionScale]
- -[PUReframeEffectSettings processing_saturation]
- -[PUReframeEffectSettings processing_speed]
- -[PUReframeEffectSettings processing_transitionDuration]
- -[PUReframeEffectSettings renderAtPointResolution]
- -[PUReframeEffectSettings setDefaultValues]
- -[PUReframeEffectSettings setPreview_bias:]
- -[PUReframeEffectSettings setPreview_blurRadius:]
- -[PUReframeEffectSettings setPreview_chromaticFringingIntensity:]
- -[PUReframeEffectSettings setPreview_distortionGrainScale:]
- -[PUReframeEffectSettings setPreview_distortionStrength:]
- -[PUReframeEffectSettings setPreview_maskBlurRadius:]
- -[PUReframeEffectSettings setPreview_maskMeshAmplitude:]
- -[PUReframeEffectSettings setPreview_maskMeshSpeed:]
- -[PUReframeEffectSettings setPreview_mirrorExtensionScale:]
- -[PUReframeEffectSettings setPreview_saturation:]
- -[PUReframeEffectSettings setPreview_speed:]
- -[PUReframeEffectSettings setPreview_transitionDuration:]
- -[PUReframeEffectSettings setProcessing_bias:]
- -[PUReframeEffectSettings setProcessing_blurRadius:]
- -[PUReframeEffectSettings setProcessing_chromaticFringingIntensity:]
- -[PUReframeEffectSettings setProcessing_distortionGrainScale:]
- -[PUReframeEffectSettings setProcessing_distortionStrength:]
- -[PUReframeEffectSettings setProcessing_maskBlurRadius:]
- -[PUReframeEffectSettings setProcessing_maskMeshAmplitude:]
- -[PUReframeEffectSettings setProcessing_maskMeshSpeed:]
- -[PUReframeEffectSettings setProcessing_mirrorExtensionScale:]
- -[PUReframeEffectSettings setProcessing_saturation:]
- -[PUReframeEffectSettings setProcessing_speed:]
- -[PUReframeEffectSettings setProcessing_transitionDuration:]
- -[PUReframeEffectSettings setRenderAtPointResolution:]
- -[PUReframeEffectSettings setShowConfigurationPanel:]
- -[PUReframeEffectSettings showConfigurationPanel]
- -[PUSidebarViewController splitViewControllerWillCollapse:]
- -[PUSidebarViewController splitViewControllerWillExpand:]
- -[PUTabbedLibrarySettings setSidebarHideNavBackButtonForSelectedItem:]
- -[PUTabbedLibrarySettings sidebarHideNavBackButtonForSelectedItem]
- -[PUTabbedLibrarySettings wantsSplitViewController]
- -[UIViewController(PhotosUI) _pu_performBarsVisibilityUpdatesWithAnimationSettings:isStatusBarHidden:]
- GCC_except_table10141
- GCC_except_table10158
- GCC_except_table10169
- GCC_except_table10170
- GCC_except_table10200
- GCC_except_table10268
- GCC_except_table10308
- GCC_except_table10310
- GCC_except_table10321
- GCC_except_table10327
- GCC_except_table10424
- GCC_except_table10482
- GCC_except_table10515
- GCC_except_table10776
- GCC_except_table10778
- GCC_except_table10895
- GCC_except_table11006
- GCC_except_table11168
- GCC_except_table11209
- GCC_except_table11237
- GCC_except_table11284
- GCC_except_table11285
- GCC_except_table11287
- GCC_except_table11288
- GCC_except_table11291
- GCC_except_table11295
- GCC_except_table11316
- GCC_except_table11630
- GCC_except_table11660
- GCC_except_table11666
- GCC_except_table11739
- GCC_except_table12081
- GCC_except_table12082
- GCC_except_table12135
- GCC_except_table12425
- GCC_except_table12442
- GCC_except_table12455
- GCC_except_table12469
- GCC_except_table12489
- GCC_except_table12538
- GCC_except_table12689
- GCC_except_table12707
- GCC_except_table12712
- GCC_except_table12715
- GCC_except_table12729
- GCC_except_table12791
- GCC_except_table12830
- GCC_except_table12863
- GCC_except_table12879
- GCC_except_table12881
- GCC_except_table12916
- GCC_except_table13006
- GCC_except_table13011
- GCC_except_table13279
- GCC_except_table13354
- GCC_except_table13368
- GCC_except_table13375
- GCC_except_table13391
- GCC_except_table13392
- GCC_except_table13395
- GCC_except_table13402
- GCC_except_table13516
- GCC_except_table13518
- GCC_except_table13581
- GCC_except_table13623
- GCC_except_table13683
- GCC_except_table13708
- GCC_except_table13724
- GCC_except_table13739
- GCC_except_table13762
- GCC_except_table13790
- GCC_except_table13802
- GCC_except_table13812
- GCC_except_table13822
- GCC_except_table13835
- GCC_except_table13845
- GCC_except_table13856
- GCC_except_table13875
- GCC_except_table13887
- GCC_except_table13892
- GCC_except_table13894
- GCC_except_table13899
- GCC_except_table13900
- GCC_except_table13901
- GCC_except_table13921
- GCC_except_table13968
- GCC_except_table14192
- GCC_except_table14332
- GCC_except_table14434
- GCC_except_table14438
- GCC_except_table14449
- GCC_except_table14473
- GCC_except_table14476
- GCC_except_table14484
- GCC_except_table14931
- GCC_except_table1516
- GCC_except_table15364
- GCC_except_table15365
- GCC_except_table15374
- GCC_except_table15380
- GCC_except_table15388
- GCC_except_table15423
- GCC_except_table15458
- GCC_except_table1551
- GCC_except_table15536
- GCC_except_table1561
- GCC_except_table15613
- GCC_except_table15619
- GCC_except_table15623
- GCC_except_table15662
- GCC_except_table15711
- GCC_except_table15719
- GCC_except_table15724
- GCC_except_table15759
- GCC_except_table15771
- GCC_except_table15779
- GCC_except_table15781
- GCC_except_table15785
- GCC_except_table15788
- GCC_except_table15792
- GCC_except_table15795
- GCC_except_table15797
- GCC_except_table15799
- GCC_except_table15804
- GCC_except_table15823
- GCC_except_table15830
- GCC_except_table15834
- GCC_except_table15856
- GCC_except_table15904
- GCC_except_table15977
- GCC_except_table15981
- GCC_except_table16094
- GCC_except_table16097
- GCC_except_table16103
- GCC_except_table16135
- GCC_except_table16152
- GCC_except_table16210
- GCC_except_table16240
- GCC_except_table16297
- GCC_except_table16318
- GCC_except_table16415
- GCC_except_table16416
- GCC_except_table16433
- GCC_except_table16442
- GCC_except_table16449
- GCC_except_table16456
- GCC_except_table16462
- GCC_except_table16472
- GCC_except_table16479
- GCC_except_table16663
- GCC_except_table16674
- GCC_except_table16677
- GCC_except_table16679
- GCC_except_table16686
- GCC_except_table16688
- GCC_except_table16690
- GCC_except_table16693
- GCC_except_table16775
- GCC_except_table16781
- GCC_except_table16809
- GCC_except_table16814
- GCC_except_table17010
- GCC_except_table17035
- GCC_except_table17198
- GCC_except_table17305
- GCC_except_table17306
- GCC_except_table17427
- GCC_except_table17461
- GCC_except_table17503
- GCC_except_table17508
- GCC_except_table17537
- GCC_except_table17539
- GCC_except_table17541
- GCC_except_table17685
- GCC_except_table17688
- GCC_except_table17697
- GCC_except_table17884
- GCC_except_table17885
- GCC_except_table17919
- GCC_except_table17938
- GCC_except_table17940
- GCC_except_table18005
- GCC_except_table18078
- GCC_except_table18095
- GCC_except_table18096
- GCC_except_table18099
- GCC_except_table18106
- GCC_except_table18107
- GCC_except_table18115
- GCC_except_table18128
- GCC_except_table18136
- GCC_except_table18147
- GCC_except_table18293
- GCC_except_table18295
- GCC_except_table18297
- GCC_except_table18305
- GCC_except_table18595
- GCC_except_table18596
- GCC_except_table18615
- GCC_except_table18617
- GCC_except_table18647
- GCC_except_table18658
- GCC_except_table18666
- GCC_except_table18682
- GCC_except_table18686
- GCC_except_table18695
- GCC_except_table1870
- GCC_except_table18705
- GCC_except_table18823
- GCC_except_table18835
- GCC_except_table18883
- GCC_except_table18893
- GCC_except_table18911
- GCC_except_table18913
- GCC_except_table18914
- GCC_except_table18915
- GCC_except_table18916
- GCC_except_table18921
- GCC_except_table19004
- GCC_except_table19011
- GCC_except_table19092
- GCC_except_table19165
- GCC_except_table19220
- GCC_except_table19380
- GCC_except_table19397
- GCC_except_table19575
- GCC_except_table1969
- GCC_except_table19741
- GCC_except_table19829
- GCC_except_table19853
- GCC_except_table20261
- GCC_except_table20265
- GCC_except_table20274
- GCC_except_table20278
- GCC_except_table20296
- GCC_except_table20307
- GCC_except_table20357
- GCC_except_table20406
- GCC_except_table20657
- GCC_except_table20805
- GCC_except_table20810
- GCC_except_table20953
- GCC_except_table20963
- GCC_except_table20965
- GCC_except_table21008
- GCC_except_table21062
- GCC_except_table21063
- GCC_except_table21153
- GCC_except_table21344
- GCC_except_table21348
- GCC_except_table21427
- GCC_except_table21428
- GCC_except_table21436
- GCC_except_table21515
- GCC_except_table21549
- GCC_except_table21631
- GCC_except_table21632
- GCC_except_table21686
- GCC_except_table2179
- GCC_except_table2181
- GCC_except_table21812
- GCC_except_table2190
- GCC_except_table22007
- GCC_except_table22008
- GCC_except_table22025
- GCC_except_table22029
- GCC_except_table22052
- GCC_except_table22167
- GCC_except_table2241
- GCC_except_table22486
- GCC_except_table22527
- GCC_except_table2259
- GCC_except_table22620
- GCC_except_table22644
- GCC_except_table22659
- GCC_except_table22777
- GCC_except_table22813
- GCC_except_table22816
- GCC_except_table22818
- GCC_except_table22823
- GCC_except_table22854
- GCC_except_table22860
- GCC_except_table22925
- GCC_except_table22941
- GCC_except_table2304
- GCC_except_table2314
- GCC_except_table2316
- GCC_except_table23211
- GCC_except_table23215
- GCC_except_table23217
- GCC_except_table23224
- GCC_except_table23225
- GCC_except_table23227
- GCC_except_table23228
- GCC_except_table2328
- GCC_except_table23332
- GCC_except_table23434
- GCC_except_table23471
- GCC_except_table2351
- GCC_except_table23533
- GCC_except_table23546
- GCC_except_table23634
- GCC_except_table23641
- GCC_except_table23643
- GCC_except_table23645
- GCC_except_table23664
- GCC_except_table23669
- GCC_except_table23675
- GCC_except_table2368
- GCC_except_table23691
- GCC_except_table2370
- GCC_except_table2374
- GCC_except_table2376
- GCC_except_table23874
- GCC_except_table23897
- GCC_except_table23908
- GCC_except_table24013
- GCC_except_table2405
- GCC_except_table24068
- GCC_except_table24075
- GCC_except_table24079
- GCC_except_table24093
- GCC_except_table24096
- GCC_except_table24227
- GCC_except_table24255
- GCC_except_table24272
- GCC_except_table24322
- GCC_except_table24370
- GCC_except_table2442
- GCC_except_table24479
- GCC_except_table24548
- GCC_except_table24558
- GCC_except_table24566
- GCC_except_table24807
- GCC_except_table24823
- GCC_except_table2767
- GCC_except_table2823
- GCC_except_table2827
- GCC_except_table2830
- GCC_except_table2918
- GCC_except_table2922
- GCC_except_table2944
- GCC_except_table2952
- GCC_except_table3004
- GCC_except_table3062
- GCC_except_table3065
- GCC_except_table3275
- GCC_except_table3307
- GCC_except_table3330
- GCC_except_table3353
- GCC_except_table3356
- GCC_except_table3798
- GCC_except_table3801
- GCC_except_table3807
- GCC_except_table3936
- GCC_except_table3984
- GCC_except_table4004
- GCC_except_table4042
- GCC_except_table4047
- GCC_except_table4050
- GCC_except_table4127
- GCC_except_table4129
- GCC_except_table4262
- GCC_except_table4379
- GCC_except_table4392
- GCC_except_table4455
- GCC_except_table4482
- GCC_except_table5788
- GCC_except_table5844
- GCC_except_table5846
- GCC_except_table5855
- GCC_except_table5883
- GCC_except_table5910
- GCC_except_table5934
- GCC_except_table5957
- GCC_except_table5991
- GCC_except_table6001
- GCC_except_table6275
- GCC_except_table6276
- GCC_except_table6279
- GCC_except_table6280
- GCC_except_table6285
- GCC_except_table6291
- GCC_except_table6470
- GCC_except_table6474
- GCC_except_table6477
- GCC_except_table6494
- GCC_except_table6582
- GCC_except_table6613
- GCC_except_table6619
- GCC_except_table6686
- GCC_except_table6717
- GCC_except_table6822
- GCC_except_table6826
- GCC_except_table6829
- GCC_except_table6832
- GCC_except_table6899
- GCC_except_table6911
- GCC_except_table6921
- GCC_except_table6925
- GCC_except_table7064
- GCC_except_table7074
- GCC_except_table7083
- GCC_except_table7091
- GCC_except_table7165
- GCC_except_table7219
- GCC_except_table7227
- GCC_except_table7368
- GCC_except_table7384
- GCC_except_table7419
- GCC_except_table7425
- GCC_except_table7438
- GCC_except_table7443
- GCC_except_table7448
- GCC_except_table7477
- GCC_except_table7598
- GCC_except_table7599
- GCC_except_table8003
- GCC_except_table8076
- GCC_except_table8188
- GCC_except_table8195
- GCC_except_table8201
- GCC_except_table8266
- GCC_except_table8296
- GCC_except_table8297
- GCC_except_table8451
- GCC_except_table8628
- GCC_except_table8636
- GCC_except_table8637
- GCC_except_table8645
- GCC_except_table8658
- GCC_except_table8670
- GCC_except_table8676
- GCC_except_table8695
- GCC_except_table8699
- GCC_except_table8725
- GCC_except_table8777
- GCC_except_table8905
- GCC_except_table8989
- GCC_except_table8994
- GCC_except_table9037
- GCC_except_table9121
- GCC_except_table9133
- GCC_except_table9173
- GCC_except_table9198
- GCC_except_table9242
- GCC_except_table9269
- GCC_except_table9283
- GCC_except_table9290
- GCC_except_table9330
- GCC_except_table9343
- GCC_except_table9345
- GCC_except_table9349
- GCC_except_table9350
- GCC_except_table9416
- GCC_except_table9419
- GCC_except_table9557
- GCC_except_table9562
- GCC_except_table9564
- GCC_except_table9613
- GCC_except_table9687
- GCC_except_table9696
- GCC_except_table9846
- GCC_except_table9898
- GCC_except_table9946
- GCC_except_table9950
- GCC_except_table9954
- GCC_except_table9972
- _OBJC_CLASS_$_PUOutfillEffectSettings
- _OBJC_CLASS_$_PUReframeEffectSettings
- _OBJC_IVAR_$_PUCropToolController._outfillCanvasConstraints
- _OBJC_IVAR_$_PUCropToolController._showOutfillExtendButton
- _OBJC_IVAR_$_PUNavigationTransition._wasStatusBarHiddenBeforeTransition
- _OBJC_IVAR_$_PUOutfillEffectSettings._loading_bias
- _OBJC_IVAR_$_PUOutfillEffectSettings._loading_blurRadius
- _OBJC_IVAR_$_PUOutfillEffectSettings._loading_chromaticFringingIntensity
- _OBJC_IVAR_$_PUOutfillEffectSettings._loading_distortionGrainScale
- _OBJC_IVAR_$_PUOutfillEffectSettings._loading_distortionStrength
- _OBJC_IVAR_$_PUOutfillEffectSettings._loading_maskBlurRadius
- _OBJC_IVAR_$_PUOutfillEffectSettings._loading_maskInsetPerBlurRadius
- _OBJC_IVAR_$_PUOutfillEffectSettings._loading_maskMeshAmplitude
- _OBJC_IVAR_$_PUOutfillEffectSettings._loading_maskMeshSpeed
- _OBJC_IVAR_$_PUOutfillEffectSettings._loading_mirrorExtensionScale
- _OBJC_IVAR_$_PUOutfillEffectSettings._loading_saturation
- _OBJC_IVAR_$_PUOutfillEffectSettings._loading_speed
- _OBJC_IVAR_$_PUOutfillEffectSettings._loading_transitionDuration
- _OBJC_IVAR_$_PUOutfillEffectSettings._placeholder_bias
- _OBJC_IVAR_$_PUOutfillEffectSettings._placeholder_blurRadius
- _OBJC_IVAR_$_PUOutfillEffectSettings._placeholder_chromaticFringingIntensity
- _OBJC_IVAR_$_PUOutfillEffectSettings._placeholder_distortionGrainScale
- _OBJC_IVAR_$_PUOutfillEffectSettings._placeholder_distortionStrength
- _OBJC_IVAR_$_PUOutfillEffectSettings._placeholder_maskBlurRadius
- _OBJC_IVAR_$_PUOutfillEffectSettings._placeholder_maskInsetPerBlurRadius
- _OBJC_IVAR_$_PUOutfillEffectSettings._placeholder_maskMeshAmplitude
- _OBJC_IVAR_$_PUOutfillEffectSettings._placeholder_maskMeshSpeed
- _OBJC_IVAR_$_PUOutfillEffectSettings._placeholder_mirrorExtensionScale
- _OBJC_IVAR_$_PUOutfillEffectSettings._placeholder_saturation
- _OBJC_IVAR_$_PUOutfillEffectSettings._placeholder_speed
- _OBJC_IVAR_$_PUOutfillEffectSettings._placeholder_transitionDuration
- _OBJC_IVAR_$_PUOutfillEffectSettings._renderAtPointResolution
- _OBJC_IVAR_$_PUOutfillEffectSettings._showConfigurationPanel
- _OBJC_IVAR_$_PUPhotoEditProtoSettings._outfillEffectSettings
- _OBJC_IVAR_$_PUPhotoEditProtoSettings._reframeEffectSettings
- _OBJC_IVAR_$_PUPhotoEditViewController._nuAsset
- _OBJC_IVAR_$_PUReframeEffectSettings._preview_bias
- _OBJC_IVAR_$_PUReframeEffectSettings._preview_blurRadius
- _OBJC_IVAR_$_PUReframeEffectSettings._preview_chromaticFringingIntensity
- _OBJC_IVAR_$_PUReframeEffectSettings._preview_distortionGrainScale
- _OBJC_IVAR_$_PUReframeEffectSettings._preview_distortionStrength
- _OBJC_IVAR_$_PUReframeEffectSettings._preview_maskBlurRadius
- _OBJC_IVAR_$_PUReframeEffectSettings._preview_maskMeshAmplitude
- _OBJC_IVAR_$_PUReframeEffectSettings._preview_maskMeshSpeed
- _OBJC_IVAR_$_PUReframeEffectSettings._preview_mirrorExtensionScale
- _OBJC_IVAR_$_PUReframeEffectSettings._preview_saturation
- _OBJC_IVAR_$_PUReframeEffectSettings._preview_speed
- _OBJC_IVAR_$_PUReframeEffectSettings._preview_transitionDuration
- _OBJC_IVAR_$_PUReframeEffectSettings._processing_bias
- _OBJC_IVAR_$_PUReframeEffectSettings._processing_blurRadius
- _OBJC_IVAR_$_PUReframeEffectSettings._processing_chromaticFringingIntensity
- _OBJC_IVAR_$_PUReframeEffectSettings._processing_distortionGrainScale
- _OBJC_IVAR_$_PUReframeEffectSettings._processing_distortionStrength
- _OBJC_IVAR_$_PUReframeEffectSettings._processing_maskBlurRadius
- _OBJC_IVAR_$_PUReframeEffectSettings._processing_maskMeshAmplitude
- _OBJC_IVAR_$_PUReframeEffectSettings._processing_maskMeshSpeed
- _OBJC_IVAR_$_PUReframeEffectSettings._processing_mirrorExtensionScale
- _OBJC_IVAR_$_PUReframeEffectSettings._processing_saturation
- _OBJC_IVAR_$_PUReframeEffectSettings._processing_speed
- _OBJC_IVAR_$_PUReframeEffectSettings._processing_transitionDuration
- _OBJC_IVAR_$_PUReframeEffectSettings._renderAtPointResolution
- _OBJC_IVAR_$_PUReframeEffectSettings._showConfigurationPanel
- _OBJC_IVAR_$_PUTabbedLibrarySettings._sidebarHideNavBackButtonForSelectedItem
- _OBJC_METACLASS_$_PUOutfillEffectSettings
- _OBJC_METACLASS_$_PUReframeEffectSettings
- _PXAssetActionTypeInternalFileRadarForSharedLibrary
- _PXSolariumMetricsEnabled
- _UIIntegralTransform
- __INSTANCE_METHODS__TtC15PhotosUIPrivateP33_BF474F55E25F5DA22E917DBD5509DD5926PUAIToolCollectionViewCell
- __OBJC_$_CLASS_METHODS_PUOutfillEffectSettings
- __OBJC_$_CLASS_METHODS_PUReframeEffectSettings
- __OBJC_$_INSTANCE_METHODS_PUCleanupMaskEffectSettings
- __OBJC_$_INSTANCE_METHODS_PUOutfillEffectSettings
- __OBJC_$_INSTANCE_METHODS_PUPXBarAppearanceImplementationDelegate
- __OBJC_$_INSTANCE_METHODS_PUReframeEffectSettings
- __OBJC_$_INSTANCE_VARIABLES_PUOutfillEffectSettings
- __OBJC_$_INSTANCE_VARIABLES_PUReframeEffectSettings
- __OBJC_$_PROP_LIST_PUOutfillEffectSettings
- __OBJC_$_PROP_LIST_PUReframeEffectSettings
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_PXSplitViewControllerChangeObserver
- __OBJC_$_PROTOCOL_METHOD_TYPES_PXSplitViewControllerChangeObserver
- __OBJC_$_PROTOCOL_REFS_PXSplitViewControllerChangeObserver
- __OBJC_CLASS_RO_$_PUOutfillEffectSettings
- __OBJC_CLASS_RO_$_PUReframeEffectSettings
- __OBJC_LABEL_PROTOCOL_$_PXSplitViewControllerChangeObserver
- __OBJC_METACLASS_RO_$_PUOutfillEffectSettings
- __OBJC_METACLASS_RO_$_PUReframeEffectSettings
- __OBJC_PROTOCOL_$_PXSplitViewControllerChangeObserver
- __PROPERTIES__TtC15PhotosUIPrivateP33_BF474F55E25F5DA22E917DBD5509DD5926PUAIToolCollectionViewCell
- ___100-[PUTabbedLibraryViewController ppt_runTabSwitchingTestWithName:options:delegate:completionHandler:]_block_invoke
- ___41+[PUOutfillEffectSettings sharedInstance]_block_invoke
- ___41+[PUReframeEffectSettings sharedInstance]_block_invoke
- ___51-[PUCropToolController setShowOutfillExtendButton:]_block_invoke
- ___block_descriptor_105_e8_32s40s48s56s64s72s80s88s96s_e20_v16?0"NUResponse"8ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8
- ___block_descriptor_56_e8_32s40r48r_e64_v56?0^{CGImage=}8{CGRect={CGPoint=dd}{CGSize=dd}}16"NSError"48lr40l8r48l8s32l8
- ___block_descriptor_56_e8_32s40s48w_e44_v24?0"PEOutfillRequestResult"8"NSError"16lw48l8s32l8s40l8
- ___swift_closure_destructor.133Tm
- ___swift_closure_destructor.139Tm
- ___swift_closure_destructor.182Tm
- ___swift_closure_destructor.194Tm
- ___swift_closure_destructor.26Tm
- ___swift_closure_destructor.59Tm
- ___swift_closure_destructor.62Tm
- ___swift_closure_destructor.66Tm
- ___swift_closure_destructor.74Tm
- ___swift_closure_destructor.94Tm
- ___swift_get_extra_inhabitant_index.8Tm
- ___swift_store_extra_inhabitant_index.9Tm
- _associated conformance 15PhotosUIPrivate12SubtoolState33_BF474F55E25F5DA22E917DBD5509DD59LLOSHAASQ
- _associated conformance 15PhotosUIPrivate19OutfillSettingsView33_A7313E62D829B22283FD0E586959657ELLV7SwiftUI0E0AA4BodyAeFP_AeF
- _associated conformance 15PhotosUIPrivate19ReframeSettingsView33_A7313E62D829B22283FD0E586959657ELLV7SwiftUI0E0AA4BodyAeFP_AeF
- _get_witness_table 7SwiftUI15ModifiedContentVyAA13_VariadicViewO4TreeVy_AA11_LayoutRootVyAA03AnyH0VGAA05TupleD0VyACyACyAA0F0PAAE9animation_4bodyQrAA9AnimationVSg_qd__AA011PlaceholderdF0VyxGXEtAaORd__lFQOyACyACyACyACy12PhotosUIEdit14PhotoStyleDPadVAA20_GeometryGroupEffectVGAA012_AspectRatioH0VGAA06_FrameH0VGAA32_EnvironmentKeyTransformModifierVySbGG_ACyAWyA12_GAA08_OpacityW0VGQo_AA16_OverlayModifierVyACyApAEAQ_ARQrAU_qd__AXXEtAaORd__lFQOyACyACyAA4TextVA15_GAA010_FixedSizeH0VG_ACyAWyA25_GA15_GQo_AA07_OffsetW0VGSgGGAA21_TraitWritingModifierVyAA14ZIndexTraitKeyVGG_ACyACyACyACyAA0V0VyAA012_ConditionalD0VyACyAY0rS13PaletteSliderVA7_GSgAA6VStackVyACyACyACyACyAA9RectangleVAA15_HiddenModifierVGA7_GAA01_D13ShapeModifierVyA52_6_InsetVGGA19_yACyAY16ExpandableSliderVA7_GGGGGSgGA30_GA36_yAA18TransitionTraitKeyVGGA39_GAA25_AppearanceActionModifierVGAA6SpacerVSgQPGGAA05_FlexzH0VGAaOHPA85_AaOHPAlA01_ef1_fI0HPyHC_A84_AaOHPA40_AaOHPA34_AaOHPqd0__AaOHD3_A17_HO_A33_AA0F8ModifierHPyHCHC_A39_AAA90_HPyHCHC_A80_AaOHPA77_AaOHPA76_AaOHPA72_AaOHPA71_AaOHPA70_AaOHpA69_AaOHPA48_AaOHpA47_AaOHPA46_AaOHPyHC_A7_AAA90_HPyHCHC_HC_A68_AaOHPyHCHC_HC_HC_A30_AAA90_HPyHCHC_A75_AAA90_HPyHCHC_A39_AAA90_HPyHCHC_A79_AAA90_HPyHCHCA83_AaOHpA82_AaOHPyHC_HCHX_HCHC_A87_AAA90_HPyHCHC
- _get_witness_table 7SwiftUI15ModifiedContentVyAA6VStackVyAA05TupleD0VyAA6SpacerV_AA4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAkAEAlmN_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAkAEAlmN_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAkAEAlmN_Qrqd___Sbyqd___qd__tctSQRd__lFQOyACy12PhotosUIEdit014PEEditAIStatusH0VAA30_SafeAreaRegionsIgnoringLayoutVG_AO016SpatialReframingH5ModelC9EditStateOQo__AO0V7ReframeVQo__SbQo__SbQo_AISgQPGGAA08_PaddingU0VGAaJHPA5_AaJHPyHC_A7_AA0H8ModifierHPyHCHC
- _get_witness_table 7SwiftUI15NavigationStackVyAA0C4PathVAA4ViewPAAE7toolbar7contentQrqd__yXE_tAA14ToolbarContentRd__lFQOyAgAE29navigationBarTitleDisplayModeyQrAA0cL4ItemV0mnO0OFQOyAgAE0kM0yQrAA18LocalizedStringKeyVFQOyAA4FormVyAA05TupleJ0VyAA7SectionVyAA05EmptyF0VAgAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAgAE11pickerStyleyQrqd__AA11PickerStyleRd__lFQOyAA6PickerVyAA4TextVSiAVyAgAE3tag_15includeOptionalQrqd___SbtSHRd__lFQOyA7__SiQo__A10_QPGG_AA20SegmentedPickerStyleVQo__SiQo_AZG_AA6IDViewVy15PhotosUIPrivate012GenEditPhaseV033_A7313E62D829B22283FD0E586959657ELLVSiGAXyAZA20_14SettingsToggleA22_LLVAZGQPGG_Qo__Qo__AA0iP0VyytAA6ButtonVyA7_GGQo_GAaFHPyHC
- _get_witness_table qd0__7SwiftUI4ViewHD3_AaBPAAE11buttonStyleyQrqd__AA015PrimitiveButtonE0Rd__lFQOyAA0G0VyAA15ModifiedContentVyAIyAIyAIyAA4TextVAA14_PaddingLayoutVGAMGAA19_BackgroundModifierVyAA06_ShapeC0VyAA7CapsuleVAA5ColorVGGGAA01_ioN0VyAUGGG_AA05PlaingE0VQo_HO
- _get_witness_table qd__7SwiftUI4ViewHD2_AaBP12PhotosUICoreE22pxReadingAvailableSize2toQrAA7BindingVySo6CGSizeVSgG_tFQOyAA15ModifiedContentVyAA6VStackVyAA05TupleN0VyANyAA6HStackVyARyAA4TextV_AA6SpacerVAA012_ConditionalN0VyAcAE11buttonStyleyQrqd__AA015PrimitiveButtonV0Rd__lFQOyAA0X0VyAVG_AA05PlainxV0VQo_AA14NavigationLinkVyAV0D9UIPrivate022StoryMusicEditorSeeAllC0VGGQPGGAA14_PaddingLayoutVG_AA06ScrollC6ReaderVyATyARyANyA9_034StoryMusicEditorSongsCollectionRowC0V06ScrollX033_0D9C64AB384EB33A96CC36AB145A83A5LLVA17_GSg_ANyAcAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQOyAcAEA28_A29_A30__Qrqd___SbyyctSQRd__lFQOyAcAE16scrollIndicators_4axesQrAA25ScrollIndicatorVisibilityV_AA4AxisO3SetVtFQOyAcAE20scrollTargetBehavioryQrqd__AA20ScrollTargetBehaviorRd__lFQOyAcAE14contentMargins__3forQrAA4EdgeOA37_V_12CoreGraphics7CGFloatVSgAA0N15MarginPlacementVtFQOyAA06ScrollC0VyAcAE18scrollTargetLayout9isEnabledQrSb_tFQOyAA04LazyQ0VyAA7ForEachVySnySiGSiANyANyANyAPyA59_ys10ArraySliceVyA9_09StorySongC5ModelCGSSAcAEA_yQrqd__AAA0_Rd__lFQOyA2_yA9_023StoryMusicEditorSongRowC0VG_A5_Qo_GGAA12_FrameLayoutVGAA25_AppearanceActionModifierVGA76_GGG_Qo_G_Qo__AA0C27AlignedScrollTargetBehaviorVQo__Qo__SSSgQo__A88_Qo_A76_GA27_QPGGGSgQPGGA76_G_Qo_HO
- _symbolic $s15PhotosUIPrivate22GenEditSafetyDependentP
- _symbolic So23PUOutfillEffectSettingsC
- _symbolic So23PUReframeEffectSettingsC
- _symbolic _____ 15PhotosUIPrivate12SubtoolState33_BF474F55E25F5DA22E917DBD5509DD59LLO
- _symbolic _____ 15PhotosUIPrivate19OutfillSettingsView33_A7313E62D829B22283FD0E586959657ELLV
- _symbolic _____ 15PhotosUIPrivate19ReframeSettingsView33_A7313E62D829B22283FD0E586959657ELLV
- _symbolic _____ 17PhotosSwiftUICore24GenerativeEditEffectViewC5StateO
- _symbolic _____Sg s5Int64V
- _symbolic ________________y_____y_____yAAG______Qo______yAA_____GGt 7SwiftUI4TextV AA6SpacerV AA19_ConditionalContentV AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonI0Rd__lFQO AA0K0V AA05PlainkI0V AA14NavigationLinkV 15PhotosUIPrivate022StoryMusicEditorSeeAllG0V
- _symbolic ___________y_____y_____y_____y_____y__________G______Qo_______Qo__SbQo__SbQo_AASgt 7SwiftUI6SpacerV AA4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AeAEAfgH_Qrqd___Sbyqd___qd__tctSQRd__lFQO AeAEAfgH_Qrqd___Sbyqd___qd__tctSQRd__lFQO AeAEAfgH_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA15ModifiedContentV 12PhotosUIEdit014PEEditAIStatusD0V AA30_SafeAreaRegionsIgnoringLayoutV AK016SpatialReframingD5ModelC9EditStateO AK0T7ReframeV
- _symbolic ______p 15PhotosUIPrivate22GenEditSafetyDependentP
- _symbolic _____yAAyAAyAAy_____y_____yAAy__________GSg_____yAAyAAyAAyAAy__________GAEG_____y_____GG_____yAAy_____AEGGGGGSgG_____G_____y_____GGA0_y_____GG_____G 7SwiftUI15ModifiedContentV AA5GroupV AA012_ConditionalD0V 12PhotosUIEdit23PhotoStylePaletteSliderV AA12_FrameLayoutV AA6VStackV AA9RectangleV AA15_HiddenModifierV AA01_d5ShapeR0V AP6_InsetV AA08_OverlayR0V AH010ExpandableL0V AA13_OffsetEffectV AA013_TraitWritingR0V AA010TransitionY3KeyV AA06ZIndexY3KeyV AA017_AppearanceActionR0V
- _symbolic _____yAAyAAy_____y_____yAAy__________GSg_____yAAyAAyAAyAAy__________GAEG_____y_____GG_____yAAy_____AEGGGGGSgG_____G_____y_____GGA0_y_____GG 7SwiftUI15ModifiedContentV AA5GroupV AA012_ConditionalD0V 12PhotosUIEdit23PhotoStylePaletteSliderV AA12_FrameLayoutV AA6VStackV AA9RectangleV AA15_HiddenModifierV AA01_d5ShapeR0V AP6_InsetV AA08_OverlayR0V AH010ExpandableL0V AA13_OffsetEffectV AA013_TraitWritingR0V AA010TransitionY3KeyV AA06ZIndexY3KeyV
- _symbolic _____yAAy_____yAAyAAyAAyAAy__________G_____G_____G_____ySbGG_AAy_____yAKG_____GQo______yAAy_____yAAyAAy_____ANG_____G_AAyALyAUGANGQo______GSgGG_____y_____GG_AAyAAyAAyAAy_____y_____yAAy_____AGGSg_____yAAyAAyAAyAAy__________GAGG_____y_____GGAQyAAy_____AGGGGGGSgGAYGA2_y_____GGA4_G_____G_____Sgt 7SwiftUI15ModifiedContentV AA4ViewPAAE9animation_4bodyQrAA9AnimationVSg_qd__AA011PlaceholderdE0VyxGXEtAaDRd__lFQO 12PhotosUIEdit14PhotoStyleDPadV AA20_GeometryGroupEffectV AA18_AspectRatioLayoutV AA06_FrameT0V AA32_EnvironmentKeyTransformModifierV AL AA08_OpacityQ0V AA08_OverlayY0V AeAEAF_AGQrAJ_qd__AMXEtAaDRd__lFQO AA4TextV AA010_FixedSizeT0V AA07_OffsetQ0V AA013_TraitWritingY0V AA011ZIndexTraitW0V AA0P0V AA012_ConditionalD0V AN0lM13PaletteSliderV AA6VStackV AA9RectangleV AA07_HiddenY0V AA01_d5ShapeY0V A20_6_InsetV AN16ExpandableSliderV AA015TransitionTraitW0V AA017_AppearanceActionY0V AA6SpacerV
- _symbolic _____yAAy_____y_____yAAy__________GSg_____yAAyAAyAAyAAy__________GAEG_____y_____GG_____yAAy_____AEGGGGGSgG_____G_____y_____GG 7SwiftUI15ModifiedContentV AA5GroupV AA012_ConditionalD0V 12PhotosUIEdit23PhotoStylePaletteSliderV AA12_FrameLayoutV AA6VStackV AA9RectangleV AA15_HiddenModifierV AA01_d5ShapeR0V AP6_InsetV AA08_OverlayR0V AH010ExpandableL0V AA13_OffsetEffectV AA013_TraitWritingR0V AA010TransitionY3KeyV
- _symbolic _____ySbG 7SwiftUI11EnvironmentV
- _symbolic _____y_____G 7SwiftUI19UIHostingControllerC 15PhotosUIPrivate19OutfillSettingsView33_A7313E62D829B22283FD0E586959657ELLV
- _symbolic _____y_____G 7SwiftUI19UIHostingControllerC 15PhotosUIPrivate19ReframeSettingsView33_A7313E62D829B22283FD0E586959657ELLV
- _symbolic _____y_____Si_____y_____yAB_SiQo__ADQPGG 7SwiftUI6PickerV AA4TextV AA12TupleContentV AA4ViewPAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO
- _symbolic _____y______SiQo__ABt 7SwiftUI4ViewPAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA4TextV
- _symbolic _____y___________y________________y_____y_____yADG______Qo______yAD_____GGQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA4TextV AA6SpacerV AA012_ConditionalI0V AA0D0PAAE11buttonStyleyQrqd__AA015PrimitiveButtonN0Rd__lFQO AA0P0V AA05PlainpN0V AA14NavigationLinkV 15PhotosUIPrivate022StoryMusicEditorSeeAllD0V
- _symbolic _____y___________y___________y_____y_____y_____y_____y__________G______Qo_______Qo__SbQo__SbQo_ADSgQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA6SpacerV AA0D0PAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AmAEAnoP_Qrqd___Sbyqd___qd__tctSQRd__lFQO AmAEAnoP_Qrqd___Sbyqd___qd__tctSQRd__lFQO AmAEAnoP_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA08ModifiedI0V 12PhotosUIEdit014PEEditAIStatusD0V AA024_SafeAreaRegionsIgnoringG0V AS016SpatialReframingD5ModelC9EditStateO AS0X7ReframeV
- _symbolic _____y___________y_____y_____yACy________________y_____y_____yAFG______Qo______yAF_____GGQPGG_____G______yAEyACyADy_____ASGSg_ADy_____y_____y_____y_____y_____y_____y_____y_____y_____ySnySiGSiADyADyADy_____yA_y_____y_____GSS_____yAIy_____G_AKQo_GG_____G_____GA12_GGG_Qo_G_Qo_______Qo__Qo__SSSgQo__A23_Qo_A12_GAXQPGGGSgQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA08ModifiedI0V AA6HStackV AA4TextV AA6SpacerV AA012_ConditionalI0V AA0D0PAAE11buttonStyleyQrqd__AA015PrimitiveButtonP0Rd__lFQO AA0R0V AA05PlainrP0V AA14NavigationLinkV 15PhotosUIPrivate022StoryMusicEditorSeeAllD0V AA08_PaddingG0V AA06ScrollD6ReaderV A2_0xyz18SongsCollectionRowD0V06ScrollR033_0D9C64AB384EB33A96CC36AB145A83A5LLV AuAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQO AuAEA14_A15_A16__Qrqd___SbyyctSQRd__lFQO AuAE16scrollIndicators_4axesQrAA25ScrollIndicatorVisibilityV_AA4AxisO3SetVtFQO AuAE20scrollTargetBehavioryQrqd__AA20ScrollTargetBehaviorRd__lFQO AuAE14contentMargins__3forQrAA4EdgeOA23_V_12CoreGraphics7CGFloatVSgAA0I15MarginPlacementVtFQO AA06ScrollD0V AuAE012scrollTargetG09isEnabledQrSb_tFQO AA04LazyK0V AA7ForEachV AA0F0V s10ArraySliceV A2_0x4SongD5ModelC AuAEAVyQrqd__AaWRd__lFQO A2_0xyz7SongRowD0V AA06_FrameG0V AA25_AppearanceActionModifierV AA0D27AlignedScrollTargetBehaviorV
- _symbolic _____y__________y_____y_____y_____Si_____y_____yAD_SiQo__AFQPGG______Qo__SiQo_ABG 7SwiftUI7SectionV AA9EmptyViewV AA0E0PAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AgAE11pickerStyleyQrqd__AA06PickerK0Rd__lFQO AA0L0V AA4TextV AA12TupleContentV AgAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA09SegmentedlK0V
- _symbolic _____y__________y_____y_____y_____Si_____y_____yAD_SiQo__AFQPGG______Qo__SiQo_ABG______y_____SiGAAyAB_____ABGt 7SwiftUI7SectionV AA9EmptyViewV AA0E0PAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AgAE11pickerStyleyQrqd__AA06PickerK0Rd__lFQO AA0L0V AA4TextV AA12TupleContentV AgAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA09SegmentedlK0V AA6IDViewV 15PhotosUIPrivate012GenEditPhaseC033_A7313E62D829B22283FD0E586959657ELLV AY14SettingsToggleA_LLV
- _symbolic _____y__________y_____y_____y_____y_____y_____y__________y_____y_____y_____SiADy_____yAH_SiQo__AIQPGG______Qo__SiQo_AFG______y_____SiGAEyAF_____AFGQPGG_Qo__Qo_______yyt_____yAHGGQo_G 7SwiftUI15NavigationStackV AA0C4PathV AA4ViewPAAE7toolbar7contentQrqd__yXE_tAA14ToolbarContentRd__lFQO AgAE29navigationBarTitleDisplayModeyQrAA0cL4ItemV0mnO0OFQO AgAE0kM0yQrAA18LocalizedStringKeyVFQO AA4FormV AA05TupleJ0V AA7SectionV AA05EmptyF0V AgAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AgAE11pickerStyleyQrqd__AA11PickerStyleRd__lFQO AA6PickerV AA4TextV AgAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA20SegmentedPickerStyleV AA6IDViewV 15PhotosUIPrivate012GenEditPhaseV033_A7313E62D829B22283FD0E586959657ELLV A14_14SettingsToggleA16_LLV AA0iP0V AA6ButtonV
- _symbolic _____y______y_____G_____y_____yAFy_____yAFyAFyAFyAFy__________G_____G_____G_____ySbGG_AFy_____yAPG_____GQo______yAFy_____yAFyAFy_____ASG_____G_AFyAQyAZGASGQo______GSgGG_____y_____GG_AFyAFyAFyAFy_____y_____yAFy_____ALGSg_____yAFyAFyAFyAFy__________GALG_____y_____GGAVyAFy_____ALGGGGGSgGA2_GA7_y_____GGA9_G_____G_____SgQPGG 7SwiftUI13_VariadicViewO4TreeV AA11_LayoutRootV AA03AnyF0V AA12TupleContentV AA08ModifiedJ0V AA0D0PAAE9animation_4bodyQrAA9AnimationVSg_qd__AA011PlaceholderjD0VyxGXEtAaNRd__lFQO 12PhotosUIEdit14PhotoStyleDPadV AA20_GeometryGroupEffectV AA012_AspectRatioF0V AA06_FrameF0V AA32_EnvironmentKeyTransformModifierV AV AA08_OpacityW0V AA16_OverlayModifierV AoAEAP_AQQrAT_qd__AWXEtAaNRd__lFQO AA4TextV AA010_FixedSizeF0V AA07_OffsetW0V AA21_TraitWritingModifierV AA14ZIndexTraitKeyV AA0V0V AA012_ConditionalJ0V AX0rS13PaletteSliderV AA6VStackV AA9RectangleV AA15_HiddenModifierV AA01_J13ShapeModifierV A30_6_InsetV AX16ExpandableSliderV AA18TransitionTraitKeyV AA25_AppearanceActionModifierV AA6SpacerV
- _symbolic _____y_____yAByAByABy__________G_____G_____y_____GG_____yABy_____AFGGGG 7SwiftUI6VStackV AA15ModifiedContentV AA9RectangleV AA15_HiddenModifierV AA12_FrameLayoutV AA01_e5ShapeH0V AG6_InsetV AA08_OverlayH0V 12PhotosUIEdit16ExpandableSliderV
- _symbolic _____y_____yABy_____yAByAByAByABy__________G_____G_____G_____ySbGG_ABy_____yALG_____GQo______yABy_____yAByABy_____AOG_____G_AByAMyAVGAOGQo______GSgGG_____y_____GG_AByAByAByABy_____y_____yABy_____AHGSg_____yAByAByAByABy__________GAHG_____y_____GGARyABy_____AHGGGGGSgGAZGA3_y_____GGA5_G_____G_____SgQPG 7SwiftUI12TupleContentV AA08ModifiedD0V AA4ViewPAAE9animation_4bodyQrAA9AnimationVSg_qd__AA011PlaceholderdF0VyxGXEtAaFRd__lFQO 12PhotosUIEdit14PhotoStyleDPadV AA20_GeometryGroupEffectV AA18_AspectRatioLayoutV AA06_FrameU0V AA32_EnvironmentKeyTransformModifierV AN AA08_OpacityR0V AA08_OverlayZ0V AgAEAH_AIQrAL_qd__AOXEtAaFRd__lFQO AA4TextV AA010_FixedSizeU0V AA07_OffsetR0V AA013_TraitWritingZ0V AA011ZIndexTraitX0V AA0Q0V AA012_ConditionalD0V AP0mN13PaletteSliderV AA6VStackV AA9RectangleV AA07_HiddenZ0V AA01_d5ShapeZ0V A22_6_InsetV AP16ExpandableSliderV AA015TransitionTraitX0V AA017_AppearanceActionZ0V AA6SpacerV
- _symbolic _____y_____y_____Si_____y_____yAB_SiQo__ADQPGG______Qo_ 7SwiftUI4ViewPAAE11pickerStyleyQrqd__AA06PickerE0Rd__lFQO AA0F0V AA4TextV AA12TupleContentV AcAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA09SegmentedfE0V
- _symbolic _____y_____y______SiQo__ACQPG 7SwiftUI12TupleContentV AA4ViewPAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA4TextV
- _symbolic _____y_____y__________GSg_____yAByAByAByABy__________GADG_____y_____GG_____yABy_____ADGGGGG 7SwiftUI19_ConditionalContentV AA08ModifiedD0V 12PhotosUIEdit23PhotoStylePaletteSliderV AA12_FrameLayoutV AA6VStackV AA9RectangleV AA15_HiddenModifierV AA01_d5ShapeQ0V AN6_InsetV AA08_OverlayQ0V AF010ExpandableK0V
- _symbolic _____y_____y__________GSg_____yAByAByAByABy__________GADG_____y_____GG_____yABy_____ADGGGGGSg 7SwiftUI19_ConditionalContentV AA08ModifiedD0V 12PhotosUIEdit23PhotoStylePaletteSliderV AA12_FrameLayoutV AA6VStackV AA9RectangleV AA15_HiddenModifierV AA01_d5ShapeQ0V AN6_InsetV AA08_OverlayQ0V AF010ExpandableK0V
- _symbolic _____y_____y__________GSg_____yAByAByAByABy__________GADG_____y_____GG_____yABy_____ADGGGG_G 7SwiftUI19_ConditionalContentV7StorageO AA08ModifiedD0V 12PhotosUIEdit23PhotoStylePaletteSliderV AA12_FrameLayoutV AA6VStackV AA9RectangleV AA15_HiddenModifierV AA01_d5ShapeR0V AP6_InsetV AA08_OverlayR0V AH010ExpandableL0V
- _symbolic _____y_____y________________y_____y_____yACG______Qo______yAC_____GGQPGG 7SwiftUI6HStackV AA12TupleContentV AA4TextV AA6SpacerV AA012_ConditionalE0V AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonK0Rd__lFQO AA0M0V AA05PlainmK0V AA14NavigationLinkV 15PhotosUIPrivate022StoryMusicEditorSeeAllI0V
- _symbolic _____y_____y___________y_____y_____y_____y_____y__________G______Qo_______Qo__SbQo__SbQo_ACSgQPGG 7SwiftUI6VStackV AA12TupleContentV AA6SpacerV AA4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AiAEAjkL_Qrqd___Sbyqd___qd__tctSQRd__lFQO AiAEAjkL_Qrqd___Sbyqd___qd__tctSQRd__lFQO AiAEAjkL_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA08ModifiedE0V 12PhotosUIEdit014PEEditAIStatusG0V AA30_SafeAreaRegionsIgnoringLayoutV AO016SpatialReframingG5ModelC9EditStateO AO0V7ReframeV
- _symbolic _____y_____y__________y_____y_____y_____SiAAy_____yAE_SiQo__AFQPGG______Qo__SiQo_ACG______y_____SiGAByAC_____ACGQPG 7SwiftUI12TupleContentV AA7SectionV AA9EmptyViewV AA0G0PAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AiAE11pickerStyleyQrqd__AA06PickerM0Rd__lFQO AA0N0V AA4TextV AiAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA09SegmentednM0V AA6IDViewV 15PhotosUIPrivate012GenEditPhaseE033_A7313E62D829B22283FD0E586959657ELLV AY14SettingsToggleA_LLV
- _symbolic _____y_____y______y_____G_____yAAyAAy_____yAAyAAyAAyAAy__________G_____G_____G_____ySbGG_AAy_____yAPG_____GQo______yAAy_____yAAyAAy_____ASG_____G_AAyAQyAZGASGQo______GSgGG_____y_____GG_AAyAAyAAyAAy_____y_____yAAy_____ALGSg_____yAAyAAyAAyAAy__________GALG_____y_____GGAVyAAy_____ALGGGGGSgGA2_GA7_y_____GGA9_G_____G_____SgQPGG_____G 7SwiftUI15ModifiedContentV AA13_VariadicViewO4TreeV AA11_LayoutRootV AA03AnyH0V AA05TupleD0V AA0F0PAAE9animation_4bodyQrAA9AnimationVSg_qd__AA011PlaceholderdF0VyxGXEtAaNRd__lFQO 12PhotosUIEdit14PhotoStyleDPadV AA20_GeometryGroupEffectV AA012_AspectRatioH0V AA06_FrameH0V AA32_EnvironmentKeyTransformModifierV AV AA08_OpacityW0V AA16_OverlayModifierV AoAEAP_AQQrAT_qd__AWXEtAaNRd__lFQO AA4TextV AA010_FixedSizeH0V AA07_OffsetW0V AA21_TraitWritingModifierV AA14ZIndexTraitKeyV AA0V0V AA012_ConditionalD0V AX0rS13PaletteSliderV AA6VStackV AA9RectangleV AA15_HiddenModifierV AA01_D13ShapeModifierV A30_6_InsetV AX16ExpandableSliderV AA18TransitionTraitKeyV AA25_AppearanceActionModifierV AA6SpacerV AA05_FlexzH0V
- _symbolic _____y_____y_____yAAy__________GSg_____yAAyAAyAAyAAy__________GAEG_____y_____GG_____yAAy_____AEGGGGGSgG_____G 7SwiftUI15ModifiedContentV AA5GroupV AA012_ConditionalD0V 12PhotosUIEdit23PhotoStylePaletteSliderV AA12_FrameLayoutV AA6VStackV AA9RectangleV AA15_HiddenModifierV AA01_d5ShapeR0V AP6_InsetV AA08_OverlayR0V AH010ExpandableL0V AA13_OffsetEffectV
- _symbolic _____y_____y_____yAAy_____yACy________________y_____y_____yAEG______Qo______yAE_____GGQPGG_____G______yADyACyAAy_____ARGSg_AAy_____y_____y_____y_____y_____y_____y_____y_____y_____ySnySiGSiAAyAAyAAyAByAZy_____y_____GSS_____yAHy_____G_AJQo_GG_____G_____GA10_GGG_Qo_G_Qo_______Qo__Qo__SSSgQo__A21_Qo_A10_GAWQPGGGSgQPGGA10_G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA6HStackV AA4TextV AA6SpacerV AA012_ConditionalD0V AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonM0Rd__lFQO AA0O0V AA05PlainoM0V AA14NavigationLinkV 15PhotosUIPrivate022StoryMusicEditorSeeAllK0V AA14_PaddingLayoutV AA06ScrollK6ReaderV AZ0uvw18SongsCollectionRowK0V06ScrollO033_0D9C64AB384EB33A96CC36AB145A83A5LLV AqAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQO AqAEA10_A11_A12__Qrqd___SbyyctSQRd__lFQO AqAE16scrollIndicators_4axesQrAA25ScrollIndicatorVisibilityV_AA4AxisO3SetVtFQO AqAE20scrollTargetBehavioryQrqd__AA20ScrollTargetBehaviorRd__lFQO AqAE14contentMargins__3forQrAA4EdgeOA19_V_12CoreGraphics7CGFloatVSgAA0D15MarginPlacementVtFQO AA06ScrollK0V AqAE18scrollTargetLayout9isEnabledQrSb_tFQO AA04LazyG0V AA7ForEachV s10ArraySliceV AZ0u4SongK5ModelC AqAEARyQrqd__AaSRd__lFQO AZ0uvw7SongRowK0V AA12_FrameLayoutV AA25_AppearanceActionModifierV AA0K27AlignedScrollTargetBehaviorV
- _symbolic _____y_____y_____y_____Si_____y_____yAB_SiQo__ADQPGG______Qo__SiQo_ 7SwiftUI4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAE11pickerStyleyQrqd__AA06PickerI0Rd__lFQO AA0J0V AA4TextV AA12TupleContentV AcAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA09SegmentedjI0V
- _symbolic _____y_____y_____y__________GSg_____yACyACyACyACy__________GAEG_____y_____GG_____yACy_____AEGGGGGSgG 7SwiftUI5GroupV AA19_ConditionalContentV AA08ModifiedE0V 12PhotosUIEdit23PhotoStylePaletteSliderV AA12_FrameLayoutV AA6VStackV AA9RectangleV AA15_HiddenModifierV AA01_e5ShapeR0V AP6_InsetV AA08_OverlayR0V AH010ExpandableL0V
- _symbolic _____y_____y_____y________________y_____y_____yADG______Qo______yAD_____GGQPGG_____G 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA4TextV AA6SpacerV AA012_ConditionalD0V AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonL0Rd__lFQO AA0N0V AA05PlainnL0V AA14NavigationLinkV 15PhotosUIPrivate022StoryMusicEditorSeeAllJ0V AA14_PaddingLayoutV
- _symbolic _____y_____y_____y________________y_____y_____yADG______Qo______yAD_____GGQPGG_____G______yAByACyAAy_____AQGSg_AAy_____y_____y_____y_____y_____y_____y_____y_____y_____ySnySiGSiAAyAAyAAy_____yAYy_____y_____GSS_____yAGy_____G_AIQo_GG_____G_____GA10_GGG_Qo_G_Qo_______Qo__Qo__SSSgQo__A21_Qo_A10_GAVQPGGGSgt 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA4TextV AA6SpacerV AA012_ConditionalD0V AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonL0Rd__lFQO AA0N0V AA05PlainnL0V AA14NavigationLinkV 15PhotosUIPrivate022StoryMusicEditorSeeAllJ0V AA14_PaddingLayoutV AA06ScrollJ6ReaderV AX0tuv18SongsCollectionRowJ0V06ScrollN033_0D9C64AB384EB33A96CC36AB145A83A5LLV AoAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQO AoAEA8_A9_A10__Qrqd___SbyyctSQRd__lFQO AoAE16scrollIndicators_4axesQrAA25ScrollIndicatorVisibilityV_AA4AxisO3SetVtFQO AoAE20scrollTargetBehavioryQrqd__AA20ScrollTargetBehaviorRd__lFQO AoAE14contentMargins__3forQrAA4EdgeOA17_V_12CoreGraphics7CGFloatVSgAA0D15MarginPlacementVtFQO AA06ScrollJ0V AoAE012scrollTargetZ09isEnabledQrSb_tFQO AA04LazyE0V AA7ForEachV AA6VStackV s10ArraySliceV AX0t4SongJ5ModelC AoAEAPyQrqd__AaQRd__lFQO AX0tuv7SongRowJ0V AA06_FrameZ0V AA25_AppearanceActionModifierV AA0J27AlignedScrollTargetBehaviorV
- _symbolic _____y_____y_____y___________y_____y_____y_____yAAy__________G______Qo_______Qo__SbQo__SbQo_ADSgQPGG_____G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA6SpacerV AA4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AkAEAlmN_Qrqd___Sbyqd___qd__tctSQRd__lFQO AkAEAlmN_Qrqd___Sbyqd___qd__tctSQRd__lFQO AkAEAlmN_Qrqd___Sbyqd___qd__tctSQRd__lFQO 12PhotosUIEdit014PEEditAIStatusH0V AA30_SafeAreaRegionsIgnoringLayoutV AO016SpatialReframingH5ModelC9EditStateO AO0V7ReframeV AA08_PaddingU0V
- _symbolic _____y_____y_____y__________y_____y_____y_____SiABy_____yAF_SiQo__AGQPGG______Qo__SiQo_ADG______y_____SiGACyAD_____ADGQPGG 7SwiftUI4FormV AA12TupleContentV AA7SectionV AA9EmptyViewV AA0H0PAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AkAE11pickerStyleyQrqd__AA06PickerN0Rd__lFQO AA0O0V AA4TextV AkAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA09SegmentedoN0V AA6IDViewV 15PhotosUIPrivate012GenEditPhaseF033_A7313E62D829B22283FD0E586959657ELLV A_14SettingsToggleA1_LLV
- _symbolic _____y_____y_____y_____yAAy_____yACy________________y_____y_____yAEG______Qo______yAE_____GGQPGG_____G______yADyACyAAy_____ARGSg_AAy_____y_____y_____y_____y_____y_____y_____y_____y_____ySnySiGSiAAyAAyAAyAByAZy_____y_____GSS_____yAHy_____G_AJQo_GG_____G_____GA10_GGG_Qo_G_Qo_______Qo__Qo__SSSgQo__A21_Qo_A10_GAWQPGGGSgQPGGA10_G_Qo_ 7SwiftUI4ViewP12PhotosUICoreE22pxReadingAvailableSize2toQrAA7BindingVySo6CGSizeVSgG_tFQO AA15ModifiedContentV AA6VStackV AA05TupleN0V AA6HStackV AA4TextV AA6SpacerV AA012_ConditionalN0V AcAE11buttonStyleyQrqd__AA015PrimitiveButtonV0Rd__lFQO AA0X0V AA05PlainxV0V AA14NavigationLinkV 0D9UIPrivate022StoryMusicEditorSeeAllC0V AA14_PaddingLayoutV AA06ScrollC6ReaderV A7_034StoryMusicEditorSongsCollectionRowC0V06ScrollX033_0D9C64AB384EB33A96CC36AB145A83A5LLV AcAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQO AcAEA19_A20_A21__Qrqd___SbyyctSQRd__lFQO AcAE16scrollIndicators_4axesQrAA25ScrollIndicatorVisibilityV_AA4AxisO3SetVtFQO AcAE20scrollTargetBehavioryQrqd__AA20ScrollTargetBehaviorRd__lFQO AcAE14contentMargins__3forQrAA4EdgeOA28_V_12CoreGraphics7CGFloatVSgAA0N15MarginPlacementVtFQO AA06ScrollC0V AcAE18scrollTargetLayout9isEnabledQrSb_tFQO AA04LazyQ0V AA7ForEachV s10ArraySliceV A7_09StorySongC5ModelC AcAEA_yQrqd__AAA0_Rd__lFQO A7_023StoryMusicEditorSongRowC0V AA12_FrameLayoutV AA25_AppearanceActionModifierV AA0C27AlignedScrollTargetBehaviorV
- _symbolic _____y_____y_____y_____yABy________________y_____y_____yAEG______Qo______yAE_____GGQPGG_____G______yADyAByACy_____ARGSg_ACy_____y_____y_____y_____y_____y_____y_____y_____y_____ySnySiGSiACyACyACyAAyAZy_____y_____GSS_____yAHy_____G_AJQo_GG_____G_____GA10_GGG_Qo_G_Qo_______Qo__Qo__SSSgQo__A21_Qo_A10_GAWQPGGGSgQPGG 7SwiftUI6VStackV AA12TupleContentV AA08ModifiedE0V AA6HStackV AA4TextV AA6SpacerV AA012_ConditionalE0V AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonM0Rd__lFQO AA0O0V AA05PlainoM0V AA14NavigationLinkV 15PhotosUIPrivate022StoryMusicEditorSeeAllK0V AA14_PaddingLayoutV AA06ScrollK6ReaderV AZ0uvw18SongsCollectionRowK0V06ScrollO033_0D9C64AB384EB33A96CC36AB145A83A5LLV AqAE8onChange2of7initial_Qrqd___SbyyctSQRd__lFQO AqAEA10_A11_A12__Qrqd___SbyyctSQRd__lFQO AqAE16scrollIndicators_4axesQrAA25ScrollIndicatorVisibilityV_AA4AxisO3SetVtFQO AqAE20scrollTargetBehavioryQrqd__AA20ScrollTargetBehaviorRd__lFQO AqAE14contentMargins__3forQrAA4EdgeOA19_V_12CoreGraphics7CGFloatVSgAA0E15MarginPlacementVtFQO AA06ScrollK0V AqAE18scrollTargetLayout9isEnabledQrSb_tFQO AA04LazyG0V AA7ForEachV s10ArraySliceV AZ0u4SongK5ModelC AqAEARyQrqd__AaSRd__lFQO AZ0uvw7SongRowK0V AA12_FrameLayoutV AA25_AppearanceActionModifierV AA0K27AlignedScrollTargetBehaviorV
- _symbolic _____y_____y_____y_____y__________y_____y_____y_____SiABy_____yAF_SiQo__AGQPGG______Qo__SiQo_ADG______y_____SiGACyAD_____ADGQPGG_Qo_ 7SwiftUI4ViewPAAE15navigationTitleyQrAA18LocalizedStringKeyVFQO AA4FormV AA12TupleContentV AA7SectionV AA05EmptyC0V AcAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAE11pickerStyleyQrqd__AA06PickerS0Rd__lFQO AA0T0V AA4TextV AcAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA09SegmentedtS0V AA6IDViewV 15PhotosUIPrivate012GenEditPhaseL033_A7313E62D829B22283FD0E586959657ELLV A2_14SettingsToggleA4_LLV
- _symbolic _____y_____y_____y_____y_____y__________y_____y_____y_____SiABy_____yAF_SiQo__AGQPGG______Qo__SiQo_ADG______y_____SiGACyAD_____ADGQPGG_Qo__Qo_ 7SwiftUI4ViewPAAE29navigationBarTitleDisplayModeyQrAA010NavigationE4ItemV0fgH0OFQO AcAE0dF0yQrAA18LocalizedStringKeyVFQO AA4FormV AA12TupleContentV AA7SectionV AA05EmptyC0V AcAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAE11pickerStyleyQrqd__AA06PickerX0Rd__lFQO AA0Y0V AA4TextV AcAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA09SegmentedyX0V AA6IDViewV 15PhotosUIPrivate012GenEditPhaseQ033_A7313E62D829B22283FD0E586959657ELLV A7_14SettingsToggleA9_LLV
- _symbolic _____y_____y_____y_____y_____y_____y__________y_____y_____y_____SiABy_____yAF_SiQo__AGQPGG______Qo__SiQo_ADG______y_____SiGACyAD_____ADGQPGG_Qo__Qo_______yyt_____yAFGGQo_ 7SwiftUI4ViewPAAE7toolbar7contentQrqd__yXE_tAA14ToolbarContentRd__lFQO AcAE29navigationBarTitleDisplayModeyQrAA010NavigationI4ItemV0jkL0OFQO AcAE0hJ0yQrAA18LocalizedStringKeyVFQO AA4FormV AA05TupleG0V AA7SectionV AA05EmptyC0V AcAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAE11pickerStyleyQrqd__AA11PickerStyleRd__lFQO AA6PickerV AA4TextV AcAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AA20SegmentedPickerStyleV AA6IDViewV 15PhotosUIPrivate012GenEditPhaseT033_A7313E62D829B22283FD0E586959657ELLV A10_14SettingsToggleA12_LLV AA0fN0V AA6ButtonV
CStrings:
+ "%@/%@: %@"
+ "BuildVersion"
+ "CONTEXT_MENU_MOVE_TO_PERSONAL_LIBRARY_TITLE"
+ "CONTEXT_MENU_MOVE_TO_SHARED_LIBRARY_TITLE"
+ "CONTEXT_MENU_MOVE_TO_SUBMENU_TITLE"
+ "Composite Image Outline"
+ "EditAI HDR Modular Pipeline"
+ "GenEdit Overlay Effect"
+ "HWModelStr"
+ "Local generative edit safety analysis failed: %@"
+ "Outfill: Loading"
+ "Outfill: Loading Phase"
+ "Outfill: Placeholder"
+ "Outfill: Placeholder Phase"
+ "PEOutfillActivateButtonTitle"
+ "PERemoveIntelligentEditsButton"
+ "PUVideoComplementItemSource has nil imagePath for Copy activity; videoComplement=%{public}@"
+ "PUVideoComplementItemSource has nil imagePath for thumbnail; videoComplement=%{public}@"
+ "Reframe: Preview"
+ "Reframe: Preview Phase"
+ "Reframe: Processing"
+ "Reframe: Processing Phase"
+ "SWITCH_TO_ONE_UP_AX_LABEL"
+ "SpatialPhotoReframeEnableDebugMode"
+ "[Item: %{public}@] No preferred DVP file representation"
+ "[Item: %{public}@] ShareSheet: Failed to generate sandbox token for still image URL when excludeLiveness=YES, cannot suppress Live Photo bundle: %@"
+ "cropCompositeImageOutline"
+ "outfillLoading_bias"
+ "outfillLoading_blurRadius"
+ "outfillLoading_chromaticFringingIntensity"
+ "outfillLoading_distortionGrainScale"
+ "outfillLoading_distortionStrength"
+ "outfillLoading_mirrorExtensionScale"
+ "outfillLoading_saturation"
+ "outfillLoading_speed"
+ "outfillPlaceholder_"
+ "outfillPlaceholder_bias"
+ "outfillPlaceholder_blurRadius"
+ "outfillPlaceholder_chromaticFringingIntensity"
+ "outfillPlaceholder_distortionGrainScale"
+ "outfillPlaceholder_distortionStrength"
+ "outfillPlaceholder_mirrorExtensionScale"
+ "outfillPlaceholder_saturation"
+ "outfillPlaceholder_speed"
+ "reframePreview_bias"
+ "reframePreview_blurRadius"
+ "reframePreview_chromaticFringingIntensity"
+ "reframePreview_distortionGrainScale"
+ "reframePreview_distortionStrength"
+ "reframePreview_mirrorExtensionScale"
+ "reframePreview_saturation"
+ "reframePreview_speed"
+ "reframeProcessing_"
+ "reframeProcessing_bias"
+ "reframeProcessing_blurRadius"
+ "reframeProcessing_chromaticFringingIntensity"
+ "reframeProcessing_distortionGrainScale"
+ "reframeProcessing_distortionStrength"
+ "reframeProcessing_mirrorExtensionScale"
+ "reframeProcessing_saturation"
+ "reframeProcessing_speed"
+ "shield"
+ "t"
+ "useEditAIHDRModularPipeline"
+ "viewfinder"
+ "\xd2"
+ "\xf0\xf0\x91\xf0a"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf02\xf0\xd5"
- "\t interfaceOrientation: %@"
- "CIPhotoEffectMono"
- "Extend Edges"
- "Hide Nav Back button for selected item"
- "Loading Phase"
- "Outfill Effect"
- "Placeholder Phase"
- "Preview Phase"
- "Processing Phase"
- "Reframe Effect"
- "Review Screen File Size"
- "Split View"
- "bubble.left"
- "exclamationmark.triangle"
- "loadScrubberBaseThumbnail failed when rendering square thumbnails: %@"
- "loading_bias"
- "loading_blurRadius"
- "loading_chromaticFringingIntensity"
- "loading_distortionGrainScale"
- "loading_distortionStrength"
- "loading_mirrorExtensionScale"
- "loading_saturation"
- "loading_speed"
- "placeholder_bias"
- "placeholder_blurRadius"
- "placeholder_chromaticFringingIntensity"
- "placeholder_distortionGrainScale"
- "placeholder_distortionStrength"
- "placeholder_mirrorExtensionScale"
- "placeholder_saturation"
- "placeholder_speed"
- "preview_bias"
- "preview_blurRadius"
- "preview_chromaticFringingIntensity"
- "preview_distortionGrainScale"
- "preview_distortionStrength"
- "preview_mirrorExtensionScale"
- "preview_saturation"
- "preview_speed"
- "processing_bias"
- "processing_blurRadius"
- "processing_chromaticFringingIntensity"
- "processing_distortionGrainScale"
- "processing_distortionStrength"
- "processing_mirrorExtensionScale"
- "processing_saturation"
- "processing_speed"
- "sidebarNavigationController.topViewController"
- "splitViewController.sidebarViewController"
- "wantsSplitViewController"
- "wantsSplitViewController == YES"
- "\xd3"
- "\xf0\xf0\x81\xf0a"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf02\xf0\xe5"
```
