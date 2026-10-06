## PhotosImagingFoundation

> `/System/Library/PrivateFrameworks/PhotosImagingFoundation.framework/PhotosImagingFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20f68` | `0x20eb4` | **`-0xb4`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt12out_of_rangeC1B9fqe220106EPKc
+ __ZNSt3__112__hash_tableIN2PA10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEE16__copy_constructB9fqe220106EPNS_16__hash_node_baseIPNS_11__hash_nodeIS2_PvEEEE
+ __ZNSt3__112__hash_tableIN2PA10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEE16__copy_constructB9fqe220106EPNS_16__hash_node_baseIPNS_11__hash_nodeIS2_PvEEEESE_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIN2PA4RectEEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__120__throw_out_of_rangeB9fqe220106EPKc
+ __ZNSt3__16vectorIN2PA4RectENS_9allocatorIS2_EEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIN2PA4RectENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIN2PA4RectENS_9allocatorIS2_EEE20__throw_out_of_rangeB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ __ZZNSt3__112__hash_tableIN2PA10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEE16__emplace_uniqueB9fqe220106IJRKS2_EEENS_4pairINS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlSA_SA_E_clESA_SA_
+ __ZZNSt3__112__hash_tableIN2PA10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEE16__emplace_uniqueB9fqe220106IJS2_EEENS_4pairINS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlRKS2_OS2_E_clESL_SM_
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt12out_of_rangeC1B9fqe220100EPKc
- __ZNSt3__112__hash_tableIN2PA10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEE16__copy_constructB9fqe220100EPNS_16__hash_node_baseIPNS_11__hash_nodeIS2_PvEEEE
- __ZNSt3__112__hash_tableIN2PA10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEE16__copy_constructB9fqe220100EPNS_16__hash_node_baseIPNS_11__hash_nodeIS2_PvEEEESE_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIN2PA4RectEEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__120__throw_out_of_rangeB9fqe220100EPKc
- __ZNSt3__16vectorIN2PA4RectENS_9allocatorIS2_EEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIN2PA4RectENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIN2PA4RectENS_9allocatorIS2_EEE20__throw_out_of_rangeB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- __ZZNSt3__112__hash_tableIN2PA10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEE16__emplace_uniqueB9fqe220100IJRKS2_EEENS_4pairINS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlSA_SA_E_clESA_SA_
- __ZZNSt3__112__hash_tableIN2PA10RegionRectENS1_8RectHashENS1_11RectEqualToENS_9allocatorIS2_EEE16__emplace_uniqueB9fqe220100IJS2_EEENS_4pairINS_15__hash_iteratorIPNS_11__hash_nodeIS2_PvEEEEbEEDpOT_ENKUlRKS2_OS2_E_clESL_SM_
Functions:
~ -[IPAOrientationOperator description] : 204 -> 200
~ -[IPAVideoPlaybackSettings(Time) descriptionByInsertingOrReplacingOperation:] : 1156 -> 1152
~ _PFRectMakeBoundingRect : 92 -> 96
~ +[IPAAdjustmentVersion validatePlatformString:] : 324 -> 320
~ -[IPAVideoPlaybackSettings initWithOperations:naturalDuration:] : 636 -> 632
~ +[IPAVideoPlaybackSettings playbackSettingsForAdjustments:] : 728 -> 724
~ -[IPAVideoPlaybackSettings archivalRepresentation] : 428 -> 424
~ -[IPAEditDescription firstIndexOfOperationWithIdentifier:] : 372 -> 368
~ -[IPAEditDescription indexOfOperationWithUUID:] : 372 -> 368
~ +[IPAEditDescription insertIndexForOperationWithIdentifier:inArray:withOrdering:] : 500 -> 496
~ +[IPAEditDescription sortOperations:withOrdering:] : 908 -> 904
~ -[IPAEditDescription forEachImmutableOperation:] : 288 -> 284
~ -[IPAEditDescription descriptionByRemovingOperation:] : 404 -> 400
~ -[IPAEditDescription descriptionWithOperationsUpToUUID:] : 468 -> 464
~ +[IPAEditDescription(TypeChecking) containsValidOperations:] : 312 -> 308
~ -[IPAPhotoAdjustmentStack maskUUIDs] : 360 -> 356
~ -[IPAChecksum initWithString:] : 328 -> 332
~ -[IPAChecksum string] : 200 -> 208
~ __ZN2PA8Matrix4d6invertEv : 1148 -> 1060
~ -[IPAAggregateLargestImageSizePolicy isBestFitPolicy] : 260 -> 256
~ -[IPAAggregateLargestImageSizePolicy transformSize:] : 400 -> 396
~ -[IPAAggregateLargestImageSizePolicy transformScaleForSize:] : 364 -> 360
~ _IPAOrientationName : 32 -> 28
~ -[IPAGeometryOperatorSequence transformForGeometry:] : 832 -> 828
~ -[IPAPerspectiveOperator transformForGeometry:] : 3264 -> 3276
~ -[IPAVideoAdjustmentStackSerializer_v10 dataFromVideoAdjustmentStack:error:] : 1096 -> 1084
~ -[IPAVideoAdjustmentStackSerializer_v10 videoAdjustmentStackFromData:error:] : 812 -> 808
~ -[IPAPhotoAdjustmentStackSerializer_v10 dataFromPhotoAdjustmentStack:error:] : 1396 -> 1392
~ -[IPAPhotoAdjustmentStackSerializer_v10 photoAdjustmentStackFromData:error:] : 1520 -> 1516
~ -[IPAImageTransformSequence canAlignToPixelsExactly] : 292 -> 288
~ -[IPAImageTransformSequence mapPoint:] : 316 -> 312
~ -[IPAImageTransformSequence inverseTransform] : 408 -> 404
~ -[IPAAdjustmentStack debugDescription] : 528 -> 524
```
