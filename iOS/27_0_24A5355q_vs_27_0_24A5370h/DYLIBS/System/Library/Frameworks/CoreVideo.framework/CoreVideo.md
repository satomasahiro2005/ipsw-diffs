## CoreVideo

> `/System/Library/Frameworks/CoreVideo.framework/CoreVideo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6e1d0` | `0x6e464` | **`+0x294`** |
| `__AUTH.__thread_vars` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1d10` | `0x1d18` | **`+0x8`** |
| `__AUTH.__thread_bss` | `—` | `0x4` | **`+0x4`** |

### Other Changes

```diff

-758.21.0.0.0
+758.23.0.0.0

-  Functions: 3620
-  Symbols:   8134
+  Functions: 3621
+  Symbols:   8138
Symbols:
+ __ZTW27tCVBunchPairReadLockCounter
+ __tlv_bootstrap
+ _tCVBunchPairReadLockCounter
+ _tCVBunchPairReadLockCounter$tlv$init
Functions:
~ _checkIOOrEXSurfaceAndCreatePixelBufferBacking : 3400 -> 3352
~ __ZN20CVPixelBufferBacking61performStandardMemoryLayoutAndCopyIOSurfaceCreationPropertiesEPvhPK13__CFAllocatorPK14__CFDictionaryS6_S6_S6_mmmmmmmmmmPS0_PmS8_S8_S8_S8_PP11__IOSurfaceSA_P10__CVBufferPjS8_S7_PS6_ : 11720 -> 11268
~ __ZL23setComponentsPropertiesPK14__CFDictionaryPS_mmS2_ : 1276 -> 1272
~ __ZN20CVPixelBufferBacking30initWithPixelBufferDescriptionEmmPvmmmPS0_PmS2_S2_PFvS0_PKvEPFvS0_S4_mmPS4_ES0_PK14__CFDictionarySC_P11__IOSurfaceSE_P10__CVBufferS2_Pi : 2708 -> 2728
~ __ZN13CVPixelBuffer15copyAttachmentsE16CVAttachmentMode : 528 -> 544
~ __ZN20CVPixelBufferBacking8finalizeEv : 824 -> 836
~ _CVDictionarySetSInt32Array : 204 -> 216
~ __ZL59shouldThisDeviceIncludeVariantCategoryIndexConditionCheckermPK40CVPixelFormatCompressionTypeAndFootprintPK35CVPixelFormatTiledAddressFormatTypePFhS_E : 152 -> 160
~ __ZN17CVPixelBufferPool21setMinimumBufferCountElPKvbPK13__CFAllocator : 384 -> 392
~ __ZN11CVBunchPair27exitBackingsCriticalSectionEv : 8 -> 96
~ __ZN17CVPixelBufferPool21getMinimumBufferCountEPKv : 120 -> 124
~ __ZN11CVBunchPair32enterBackingsCriticalReadSectionEv : 8 -> 88
~ __ZN18CVLockingBunchPair27exitBackingsCriticalSectionEv : 136 -> 132
~ __ZN13CVPixelBuffer14getAttachmentsE16CVAttachmentMode : 548 -> 564
~ __ZN8CVBuffer13getAttachmentEPK10__CFStringP16CVAttachmentMode : 148 -> 144
~ __ZN8CVBuffer14copyAttachmentEPK10__CFStringP16CVAttachmentMode : 156 -> 152
~ __ZL28cvCFAppendCompactDescriptionP10__CFStringPKv : 724 -> 756
~ __Z21CVCreateHexDumpStringPKhm : 120 -> 136
~ __Z67CVCreateIOSurfacePropertyDictionaryFromCVBufferAttachmentDictionaryPK14__CFDictionary : 140 -> 160
~ __ZL15fillExtended128PvmmmmmmmS_ : 308 -> 324
~ __ZL14fillExtended64PvmmmmmmmS_ : 284 -> 300
~ __CVXFillExtended48 : 468 -> 508
~ __CVXFillExtended80 : 452 -> 484
~ __ZL14fillExtended32PvmmmmmmmS_ : 284 -> 300
~ __CVXFillExtended24 : 444 -> 480
~ __ZL14fillExtended16PvmmmmmmmS_ : 284 -> 300
~ __CVXFillExtended2vuy : 484 -> 516
~ __CVXFillExtendedyuvs : 484 -> 520
~ __CVXFillExtendedx22p : 472 -> 504
~ __CVXFillExtendedv216 : 472 -> 504
~ __CVXFillExtendedv210 : 1600 -> 1652
~ __CVXFillExtendedSpecial1 : 476 -> 496
~ __CVXFillExtendedSpecial3 : 488 -> 544
~ _ConvertFromEncodingRange : 260 -> 252
~ __ZN35CVPixelBufferOpenGLESTextureBacking13finishTextureEv : 140 -> 160
~ __ZN35CVPixelBufferOpenGLESTextureBacking11testTextureEv : 176 -> 192
+ __ZTW27tCVBunchPairReadLockCounter
~ __ZN8CVBuffer13hasAttachmentEPK10__CFString : 120 -> 116
~ __ZN13CVPixelBuffer10dumpToQTESEPc : 1012 -> 996
~ __ZN13CVPixelBuffer13drawColorBarsEv : 6360 -> 6600
~ _CVPixelBufferCreateResolvedAttributesDictionary : 7432 -> 7440
~ _CVPixelFormatTypeCopyFourCharCodeString : 184 -> 192
~ __ZN16CVDataBufferPool21setMinimumBufferCountElPKvbPK13__CFAllocator : 384 -> 392
~ __ZN16CVDataBufferPool21getMinimumBufferCountEPKv : 120 -> 124
~ _$s9CoreVideo18CVImageFieldDetailO8rawValueSSvg : 28 -> 24
~ _$s9CoreVideo18CVImageFieldDetailOSYAASY8rawValue03RawG0QzvgTW : 64 -> 60
~ _$s9CoreVideo18CVImageYCbCrMatrixO8rawValueSSvg : 28 -> 24
~ _$s9CoreVideo21CVImageColorPrimariesO8rawValueSSvg : 28 -> 24
~ _$s9CoreVideo23CVImageTransferFunctionO8rawValueSSvg : 28 -> 24
~ _$s9CoreVideo18CVImageChromaFieldV14SampleLocationO8rawValueSSvg : 28 -> 24
~ _$s9CoreVideo18CVImageChromaFieldV0D11SubsamplingO8rawValueSSvg : 28 -> 24
~ _$s9CoreVideo18CVImageChromaFieldV0D11SubsamplingOSYAASY8rawValue03RawH0QzvgTW : 64 -> 60
~ _$s9CoreVideo18CVImageChromaFieldV0D11SubsamplingOSHAASH4hash4intoys6HasherVz_tFTW : 104 -> 100
~ _$s9CoreVideo33CVImageStereoDisplayMaskRectangleV26makeFromRawAttachmentValueyACSgAA012CVAttachmentjL0VFZ : 1328 -> 1324
~ _$s9CoreVideo33CVImageStereoDisplayMaskRectangleV32rawAttachmentValueRepresentationAA015CVAttachmentRawJ0Vvg : 748 -> 752
~ _$sSasSQRzlE2eeoiySbSayxG_ABtFZ9CoreVideo33CVImageStereoDisplayMaskRectangleV9EdgePointV_Tt1g5 : 120 -> 132
~ _$s9CoreVideo33CVImageStereoDisplayMaskRectangleV4hash4intoys6HasherVz_tF : 232 -> 264
~ _$s9CoreVideo24CVPixelFormatDescriptionV8rawValueAA17TypedCFDictionaryVvg : 544 -> 540
~ _$s9CoreVideo24CVPixelFormatDescriptionV8RegistryC18formatDescriptionsSayACGvg : 2844 -> 2804
~ _$ss10SetAlgebraPs7ElementQz012ArrayLiteralC0RtzrlE05arrayE0xAFd_tcfC9CoreVideo24CVPixelFormatDescriptionV10ComponentsV_Tg5Tm : 196 -> 188
~ _$s9CoreVideo24CVPixelFormatDescriptionV14ComponentRangeO6update5attrsyAA17TypedCFDictionaryVz_tF : 104 -> 100
~ _$s9CoreVideo24CVPixelFormatDescriptionV18PlaneConfigurationO5attrsAESgAA17TypedCFDictionaryV_tcfC : 1100 -> 1080
~ _$s9CoreVideo24CVPixelFormatDescriptionV18PlaneConfigurationO6update5attrsyAA17TypedCFDictionaryVz_tF : 648 -> 680
~ _$s9CoreVideo24CVPixelFormatDescriptionV18PlaneConfigurationO2eeoiySbAE_AEtFZTf4nnd_n : 996 -> 1012
~ _$s9CoreVideo24CVPixelFormatDescriptionVwst : 124 -> 120
~ _$s9CoreVideo17TypedCFDictionaryV17dictionaryLiteralACSo11CFStringRefa_AA30CVAttachmentValueRepresentable_pSgtd_tcfC : 684 -> 680
~ _$s9CoreVideo17TypedCFDictionaryVs30ExpressibleByDictionaryLiteralAAsADP010dictionaryH0x3KeyQz_5ValueQztd_tcfCTW : 696 -> 688
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSo11CFStringRefa_yXlTt0g5Tf4g_n : 244 -> 252
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSo11CFStringRefa_9CoreVideo30CVAttachmentValueRepresentable_pSgTt0g5Tf4g_n : 272 -> 292
~ _$s9CoreVideo20CVMutablePixelBufferV32accessUnsafeMutableRawPlaneBytesyxxSayAA07CVPixeleJ10PropertiesV10properties_Sw5bytestGKYTXEKlF : 504 -> 484
~ _$s9CoreVideo20CVAttachmentRawValueV17dictionaryLiteralACSS_AA0cE13Representable_pSgtd_tcfC : 748 -> 756
~ _$sSD9CoreVideoAA30CVAttachmentValueRepresentableRzAaBR_rlE021makeFromRawAttachmentD0ySDyxq_GSgAA0chD0VFZ : 3008 -> 3024
~ _$s9CoreVideo23CVPixelBufferAttributesV16pixelFormatTypesSayAA0cG4TypeVGSgvsTm : 344 -> 336
~ _$s9CoreVideo23CVPixelBufferAttributesV7mergingACSgSayACG_tcfCTm : 356 -> 360
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_s8Sendable_pTt0g5Tf4g_n : 256 -> 276
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCs11AnyHashableV_ypTt0g5Tf4g_n : 256 -> 264
~ _$s9CoreVideo31CVPixelBufferCreationAttributesVwst : 160 -> 148
~ _$sSo11CVBufferRefa9CoreVideoE18CreationAttributesVwst : 156 -> 148
~ _$s9CoreVideo34CVAttachmentCompositeKeyDefinitionVyACyxq_GSo11CFStringRefad_tcfC : 440 -> 448
~ _$s9CoreVideo34CVAttachmentCompositeKeyDefinitionV2eeoiySbACyxq_G_AEtFZ : 144 -> 152
~ _$s9CoreVideo34CVAttachmentCompositeKeyDefinitionV4hash4intoys6HasherVz_tF : 92 -> 100
~ _$s9CoreVideo18CVAttachmentAccessV13dynamicMemberqd_0_Sgs7KeyPathCyxmAA0c9CompositeG10DefinitionVyqd__qd_0_GG_tcAA0C14ModePreferenceRd__AA0C18ValueRepresentableRd_0_r0_luis : 748 -> 756
~ _$s9CoreVideo21CVAttachmentContainerV9rawValues4modeSDySSAA0C8RawValueVGSo0C4ModeV_tF : 176 -> 172
~ _$s9CoreVideo21CVAttachmentContainerV13dynamicMemberqd_0_Sgs7KeyPathCyxmAA0cG10DefinitionVyqd__qd_0_GG_tcAA0C14ModePreferenceRd__AA0C18ValueRepresentableRd_0_r0_luipAA0cG11DefinitionsRzAaLRd__AaMRd_0_r_0_lACyxGxqd__qd_0_TK : 104 -> 108
~ _$s9CoreVideo21CVAttachmentContainerV13dynamicMemberqd_0_Sgs7KeyPathCyxmAA0cG10DefinitionVyqd__qd_0_GG_tcAA0C14ModePreferenceRd__AA0C18ValueRepresentableRd_0_r0_luipAA0cG11DefinitionsRzAaLRd__AaMRd_0_r_0_lACyxGxqd__qd_0_Tk : 132 -> 136
~ _$s9CoreVideo21CVAttachmentContainerV13dynamicMemberqd_0_s7KeyPathCyxmAA0cG21DefinitionWithDefaultVyqd__qd_0_GG_tcAA0C14ModePreferenceRd__AA0C18ValueRepresentableRd_0_SQRd_0_s8SendableRd_0_r0_luipAA0cG11DefinitionsRzAaKRd__AaLRd_0_SQRd_0_sAMRd_0_r_0_lACyxGxqd__qd_0_TK : 104 -> 108
~ _$s9CoreVideo21CVAttachmentContainerV13dynamicMemberqd_0_s7KeyPathCyxmAA0cG21DefinitionWithDefaultVyqd__qd_0_GG_tcAA0C14ModePreferenceRd__AA0C18ValueRepresentableRd_0_SQRd_0_s8SendableRd_0_r0_luipAA0cG11DefinitionsRzAaKRd__AaLRd_0_SQRd_0_sAMRd_0_r_0_lACyxGxqd__qd_0_Tk : 240 -> 244
~ _$s9CoreVideo21CVAttachmentContainerV13dynamicMemberqd_0_Sgs7KeyPathCyxmAA0c9CompositeG10DefinitionVyqd__qd_0_GG_tcAA0C14ModePreferenceRd__AA0C18ValueRepresentableRd_0_r0_luipAA0cG11DefinitionsRzAaLRd__AaMRd_0_r_0_lACyxGxqd__qd_0_Tk : 256 -> 260
~ _$s9CoreVideo21CVAttachmentContainerV13dynamicMemberqd_0_Sgs7KeyPathCyxmAA0c9CompositeG10DefinitionVyqd__qd_0_GG_tcAA0C14ModePreferenceRd__AA0C18ValueRepresentableRd_0_r0_luis : 596 -> 612
~ _$ss17_NativeDictionaryV20_copyOrMoveAndResize8capacity12moveElementsySi_SbtFSS_9CoreVideo20CVAttachmentRawValueVTg5 : 712 -> 704
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_9CoreVideo30CVAttachmentValueRepresentable_pTt0gq5Tf4g_n : 260 -> 284
~ _$ss17_NativeDictionaryV5merge20trappingOnDuplicatesyqd__n_tSTRd__x_q_t7ElementRtd__lFSS_9CoreVideo20CVAttachmentRawValueVSaySS_AItGTg5Tf4gn_n : 516 -> 520
~ _$s9CoreVideo26CVPixelBufferRepresentablePAARi_zrlE25accessUnsafeRawPlaneBytesyqd__qd__SayAA0cdI10PropertiesV10properties_SW5bytestGKYTXEKlFqd__0D0QzKYTXEfU_TA : 484 -> 488
~ _$s9CoreVideo20CVSenselArrayPatternO8rawValueSivg : 24 -> 20
~ _$s9CoreVideo20CVSenselArrayPatternOSYAASY8rawValue03RawG0QzvgTW : 28 -> 24
~ _$s9CoreVideo20CVSenselArrayPatternOSHAASH9hashValueSivgTW : 84 -> 80
~ _$s9CoreVideo20CVSenselArrayPatternOSHAASH4hash4intoys6HasherVz_tFTW : 60 -> 56
~ _$s9CoreVideo20CVSenselArrayPatternOSHAASH13_rawHashValue4seedS2i_tFTW : 80 -> 76
~ __ZL63calculateSparseHistogramAndSizeOfCompressedTileDataUsageOfPlaneP10__CVBuffermmmmmPmS1_b : 2688 -> 2720
```
