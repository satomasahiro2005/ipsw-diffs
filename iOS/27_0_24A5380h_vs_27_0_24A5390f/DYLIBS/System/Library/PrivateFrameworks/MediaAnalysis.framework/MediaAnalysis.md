## MediaAnalysis

> `/System/Library/PrivateFrameworks/MediaAnalysis.framework/MediaAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c5d80` | `0x4c7ab4` | **`+0x1d34`** |
| `__AUTH_CONST.__cfstring` | `0x1df20` | `0x1e560` | **`+0x640`** |
| `__TEXT.__cstring` | `0x2c083` | `0x2c473` | **`+0x3f0`** |
| `__DATA_CONST.__const` | `0x7938` | `0x7bd0` | **`+0x298`** |
| `__TEXT.__gcc_except_tab` | `0x67440` | `0x676c8` | **`+0x288`** |
| `__AUTH_CONST.__objc_const` | `0x41790` | `0x41a10` | **`+0x280`** |
| `__TEXT.__oslogstring` | `0x3240b` | `0x325eb` | **`+0x1e0`** |
| `__AUTH.__objc_data` | `0x1b0` | `0x2f0` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x22a70` | `0x22b78` | **`+0x108`** |
| `__TEXT.__unwind_info` | `0x13e58` | `0x13f08` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0xefd8` | `0xf040` | **`+0x68`** |
| `__TEXT.__const` | `0x165c8` | `0x16618` | **`+0x50`** |
| `__DATA.__bss` | `0x34b9` | `0x34e9` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x2528` | `0x2558` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x75a8` | `0x75c8` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x1598` | `0x15b8` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x958` | `0x938` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2558` | `0x2570` | **`+0x18`** |
| `__AUTH_CONST.__objc_arrayobj` | `0xcd8` | `0xcf0` | **`+0x18`** |
| `__DATA.__data` | `0x1ff4` | `0x200c` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x9ee` | `0x9dc` | **`-0x12`** |
| `__DATA.__objc_ivar` | `0x3684` | `0x368c` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x12b8` | `0x12c0` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x2c0` | `0x2b8` | **`-0x8`** |
| `__DATA_DIRTY.__objc_data` | `0xdc20` | `0xdc28` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x728` | `0x730` | **`+0x8`** |

### Other Changes

```diff

-435.69.2.0.0
+435.73.2.0.0

-  Functions: 20070
-  Symbols:   28402
-  CStrings:  8846
+  Functions: 20099
+  Symbols:   28485
+  CStrings:  8909
Symbols:
+ +[MADHKSVComplexityRouter _comboStringWithPersonPresent:petPresent:vehiclePresent:packagePresent:]
+ +[MADHKSVComplexityRouter routerVersion]
+ +[MADHKSVComplexityRouter routingThreshold]
+ +[MADHKSVComplexityRouter scoreWithPersonPresent:petPresent:vehiclePresent:packagePresent:detectionCount:]
+ +[MADHKSVComplexityRouter shouldRouteToProWithPersonPresent:petPresent:vehiclePresent:packagePresent:detectionCount:]
+ +[MADTextEmbeddingMD8SafariDefaultResource sharedResourceWithComputeUnits:]
+ +[MADTextEmbeddingMD8SafariExtendedResource extendedContextLength]
+ +[MADTextEmbeddingMD8SafariExtendedResource sharedResourceWithComputeUnits:]
+ +[MADTextEmbeddingMD8SafariResource revision]
+ +[PHAsset(MediaAnalysis) mad_timedFetchAssetsForEvent:analyticsManager:fetchBlock:]
+ +[PHAsset(MediaAnalysis) mad_timedFetchAssetsForEvent:fetchBlock:]
+ -[MADContentClassificationAnalyzer requiredSceneIdentifiersForIdentifier:]
+ -[MADTextEmbeddingMD8SafariResource tokenEmbeddingType]
+ -[MADTextEmbeddingMD8SafariResource version]
+ -[PHAsset(MediaAnalysisTUProcessing) mad_TUIdentificationDocumentKindHintFromContentClassification]
+ -[VCPHomeKitAnalysisService dealloc]
+ -[VCPHomeKitAnalysisSession dealloc]
+ -[VCPMediaAnalysisService dealloc]
+ GCC_except_table252
+ GCC_except_table255
+ GCC_except_table264
+ GCC_except_table265
+ GCC_except_table274
+ GCC_except_table282
+ GCC_except_table292
+ GCC_except_table300
+ GCC_except_table301
+ GCC_except_table309
+ GCC_except_table310
+ GCC_except_table315
+ GCC_except_table319
+ GCC_except_table326
+ GCC_except_table327
+ GCC_except_table332
+ GCC_except_table336
+ GCC_except_table341
+ GCC_except_table344
+ GCC_except_table345
+ GCC_except_table350
+ GCC_except_table353
+ GCC_except_table354
+ GCC_except_table359
+ GCC_except_table362
+ GCC_except_table363
+ GCC_except_table368
+ GCC_except_table371
+ GCC_except_table372
+ GCC_except_table377
+ GCC_except_table381
+ GCC_except_table386
+ GCC_except_table389
+ GCC_except_table390
+ GCC_except_table395
+ GCC_except_table398
+ GCC_except_table399
+ GCC_except_table404
+ GCC_except_table407
+ GCC_except_table408
+ GCC_except_table413
+ GCC_except_table416
+ GCC_except_table419
+ GCC_except_table422
+ GCC_except_table423
+ GCC_except_table428
+ GCC_except_table431
+ GCC_except_table432
+ GCC_except_table435
+ GCC_except_table439
+ GCC_except_table440
+ GCC_except_table451
+ GCC_except_table456
+ GCC_except_table459
+ GCC_except_table460
+ GCC_except_table465
+ GCC_except_table468
+ GCC_except_table471
+ GCC_except_table474
+ GCC_except_table477
+ GCC_except_table478
+ GCC_except_table489
+ GCC_except_table494
+ GCC_except_table497
+ GCC_except_table498
+ GCC_except_table503
+ GCC_except_table506
+ GCC_except_table507
+ GCC_except_table511
+ GCC_except_table514
+ GCC_except_table518
+ _OBJC_CLASS_$_MADHKSVComplexityRouter
+ _OBJC_CLASS_$_MADSafariTextEmbeddingAdapter
+ _OBJC_CLASS_$_MADTextEmbeddingMD8SafariDefaultResource
+ _OBJC_CLASS_$_MADTextEmbeddingMD8SafariExtendedResource
+ _OBJC_CLASS_$_MADTextEmbeddingMD8SafariResource
+ _OBJC_IVAR_$_MADContentClassificationAnalyzer._requirementsByIdentifier
+ _OBJC_IVAR_$_MADSharedTextEncoder._safariAdapter
+ _OBJC_IVAR_$_VCPImageCaptionAnalyzer._captionHandler
+ _OBJC_METACLASS_$_MADHKSVComplexityRouter
+ _OBJC_METACLASS_$_MADTextEmbeddingMD8SafariDefaultResource
+ _OBJC_METACLASS_$_MADTextEmbeddingMD8SafariExtendedResource
+ _OBJC_METACLASS_$_MADTextEmbeddingMD8SafariResource
+ _VCPAnalyticsEvent17184AssetTransientFailure
+ _VCPAnalyticsEvent17185AssetIndefiniteFailure
+ _VCPAnalyticsField17184AssetFailureActivityID
+ _VCPAnalyticsField17184AssetFailureAssetType
+ _VCPAnalyticsField17184AssetFailureAttemptCount
+ _VCPAnalyticsField17184AssetFailureCurrentErrorCode
+ _VCPAnalyticsField17184AssetFailureCurrentErrorLine
+ _VCPAnalyticsField17184AssetFailureDownloadDurationMilliseconds
+ _VCPAnalyticsField17184AssetFailureDownloadPerformed
+ _VCPAnalyticsField17184AssetFailureErrorCode
+ _VCPAnalyticsField17184AssetFailureErrorLine
+ _VCPAnalyticsField17184AssetFailureExpectedBackoffSeconds
+ _VCPAnalyticsField17184AssetFailureExpectedCurrentBackoffSeconds
+ _VCPAnalyticsField17184AssetFailureProcessingDurationMilliseconds
+ _VCPAnalyticsField17184AssetFailureProcessingStatus
+ _VCPAnalyticsField17184AssetFailureSecondsSinceBoot
+ _VCPAnalyticsField17184AssetFailureSecondsSinceLastAttempt
+ _VCPAnalyticsField17184AssetFailureSecondsSinceOSUpdate
+ _VCPAnalyticsField17184AssetFailureSecondsSinceVersionUpdate
+ _VCPAnalyticsField17246HKSVProcessingDetectionCategoryMask
+ _VCPAnalyticsField17246HKSVProcessingPersonalizationStatus
+ _VCPAnalyticsField17246HKSVProcessingRoutedEndpoint
+ _VCPAnalyticsField17246HKSVProcessingRouterScoreMilli
+ _VCPAnalyticsField17246HKSVProcessingRouterVersion
+ _VCPAnalyticsFieldAssetFetchTimeInSeconds
+ _VCPAnalyticsFieldTotalTaskTimeInSeconds
+ __OBJC_$_CLASS_METHODS_MADHKSVComplexityRouter
+ __OBJC_$_CLASS_METHODS_MADTextEmbeddingMD8SafariDefaultResource
+ __OBJC_$_CLASS_METHODS_MADTextEmbeddingMD8SafariExtendedResource
+ __OBJC_$_CLASS_METHODS_MADTextEmbeddingMD8SafariResource
+ __OBJC_$_INSTANCE_METHODS_MADTextEmbeddingMD8SafariResource
+ __OBJC_CLASS_RO_$_MADHKSVComplexityRouter
+ __OBJC_CLASS_RO_$_MADTextEmbeddingMD8SafariDefaultResource
+ __OBJC_CLASS_RO_$_MADTextEmbeddingMD8SafariExtendedResource
+ __OBJC_CLASS_RO_$_MADTextEmbeddingMD8SafariResource
+ __OBJC_METACLASS_RO_$_MADHKSVComplexityRouter
+ __OBJC_METACLASS_RO_$_MADTextEmbeddingMD8SafariDefaultResource
+ __OBJC_METACLASS_RO_$_MADTextEmbeddingMD8SafariExtendedResource
+ __OBJC_METACLASS_RO_$_MADTextEmbeddingMD8SafariResource
+ __ZL12kComboLevels
+ __ZL15kFeatureWeights
+ __ZZ43+[MADHKSVComplexityRouter routingThreshold]E9onceToken
+ __ZZ43+[MADHKSVComplexityRouter routingThreshold]E9threshold
+ ___43+[MADHKSVComplexityRouter routingThreshold]_block_invoke
+ ___66-[MADContentClassificationAnalyzer _initializeReferenceEmbeddings]_block_invoke
+ ___74-[MADContentClassificationAnalyzer requiredSceneIdentifiersForIdentifier:]_block_invoke
+ ___75+[MADTextEmbeddingMD8SafariDefaultResource sharedResourceWithComputeUnits:]_block_invoke
+ ___76+[MADTextEmbeddingMD8SafariExtendedResource sharedResourceWithComputeUnits:]_block_invoke
+ ___block_descriptor_40_e47_"MADTextEmbeddingMD8SafariDefaultResource"8?0l
+ ___block_descriptor_40_e48_"MADTextEmbeddingMD8SafariExtendedResource"8?0l
+ ___swift_deallocate_boxed_opaque_existential_1
+ _kContentClassificationKey_Predicate
+ _kContentClassificationKey_PredicateRequire
+ _malloc_zone_pressure_relief
+ _swift_getAssociatedTypeWitness
+ _symbolic _____ 13MediaAnalysis20MADModelCatalogModelC
+ _symbolic ______p 12ModelCatalog0B8ResourceP
+ _symbolic ______pSg 12ModelCatalog0B8ResourceP
- GCC_except_table241
- GCC_except_table244
- GCC_except_table257
- GCC_except_table260
- GCC_except_table263
- GCC_except_table266
- GCC_except_table275
- GCC_except_table281
- GCC_except_table284
- GCC_except_table290
- GCC_except_table296
- GCC_except_table299
- GCC_except_table302
- GCC_except_table305
- GCC_except_table311
- GCC_except_table314
- GCC_except_table317
- GCC_except_table325
- GCC_except_table328
- GCC_except_table331
- GCC_except_table334
- GCC_except_table337
- GCC_except_table340
- GCC_except_table343
- GCC_except_table346
- GCC_except_table349
- GCC_except_table352
- GCC_except_table355
- GCC_except_table358
- GCC_except_table361
- GCC_except_table364
- GCC_except_table367
- GCC_except_table370
- GCC_except_table373
- GCC_except_table376
- GCC_except_table379
- GCC_except_table388
- GCC_except_table391
- GCC_except_table394
- GCC_except_table400
- GCC_except_table403
- GCC_except_table406
- GCC_except_table412
- GCC_except_table415
- GCC_except_table418
- GCC_except_table421
- GCC_except_table424
- GCC_except_table427
- GCC_except_table430
- GCC_except_table433
- GCC_except_table436
- GCC_except_table437
- GCC_except_table441
- GCC_except_table444
- GCC_except_table455
- GCC_except_table458
- GCC_except_table461
- GCC_except_table464
- GCC_except_table467
- GCC_except_table470
- GCC_except_table473
- GCC_except_table476
- GCC_except_table479
- GCC_except_table480
- GCC_except_table493
- GCC_except_table496
- GCC_except_table499
- GCC_except_table502
- GCC_except_table505
- GCC_except_table508
- GCC_except_table509
- GCC_except_table513
- _OBJC_IVAR_$_VCPImageCaptionAnalyzer._captionHandlerRef
- _symbolic _____ 13MediaAnalysis25_MADObjCModelCatalogModelC
- _symbolic _____y__________G 12ModelCatalog0B5AssetV AA010LLMAdapterC8MetadataV AA0dC8ContentsV
- _symbolic _____y__________G 12ModelCatalog0B5AssetV AA021EmbeddingPreprocessorC8MetadataV AA0deC8ContentsV
CStrings:
+ "+"
+ "@\"MADTextEmbeddingMD8SafariDefaultResource\"8@?0"
+ "@\"MADTextEmbeddingMD8SafariExtendedResource\"8@?0"
+ "AttemptCount"
+ "Could not retrieve adapter ID"
+ "Could not retrieve adapter asset resource"
+ "Could not retrieve adapter catalog resource"
+ "Could not retrieve bridge ID"
+ "Could not retrieve bridge asset resource"
+ "Could not retrieve bridge catalog resource"
+ "CurrentErrorCode"
+ "CurrentErrorLine"
+ "DetectionCategoryMask"
+ "DownloadDuration"
+ "DownloadPerformed"
+ "ErrorLine"
+ "ExpectedBackoffTime"
+ "ExpectedCurrentBackoffTime"
+ "Failed to create Safari text embedding adapter"
+ "HKSVComplexityRoutingThreshold"
+ "HKSVComplexityRoutingThreshold = %.4f (set by user)"
+ "MD8 encoder did not produce spatial_embed for Safari adapter"
+ "OCR_Archive"
+ "OCR_Decode"
+ "OCR_Recognize"
+ "PEC_Decode"
+ "PEC_Parse"
+ "PEC_Server"
+ "Package"
+ "Package+Person"
+ "Package+Person+Vehicle"
+ "Person+Pet"
+ "Person+Vehicle"
+ "PersonalizationStatus"
+ "ProcessingDuration"
+ "RoutedEndpoint"
+ "RouterScoreMilli"
+ "RouterVersion"
+ "Safari adapter inference failed (%d)"
+ "TU_Archive"
+ "TU_Decode"
+ "TU_Gating"
+ "TU_OCRRead"
+ "TU_Process"
+ "TextUnderstanding"
+ "TimeSinceBoot"
+ "TimeSinceLastAttempt"
+ "TimeSinceOSUpdate"
+ "TimeSinceVersionUpdate"
+ "TotalAssetFetchTimeInSeconds"
+ "TotalTaskTimeInSeconds"
+ "Unsupported bridge type requested"
+ "Vehicle"
+ "VisualSearch_Decode"
+ "VisualSearch_Parse"
+ "VisualSearch_Sticker"
+ "[ImageCaption] CVNLPCaptionCopyForCVPixelBuffer failed: %@"
+ "com.apple.mediaanalysisd.AssetIndefiniteFailure"
+ "com.apple.mediaanalysisd.AssetTransientFailure"
+ "failed to read assetVersion"
+ "getAdapterVersionNumber() failed with: %@"
+ "getAdapterVersionNumber() succeeded, versionNumber: %s"
+ "getBridgeURL() failed with: %@"
+ "getBridgeURL() succeeded, baseURL: %s"
+ "none"
+ "predicate"
+ "require"
- "PhotosLibraryUnderstanding adaptor fetch failed with: %@"
- "adaptor fetchAsset succeeded, baseURL: %s, assetVersion: %s"
- "fetchAsset failed with: %@"
- "fetchAsset succeeded, baseURL: %s"
```
