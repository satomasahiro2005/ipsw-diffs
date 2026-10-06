## Tungsten

> `/System/Library/PrivateFrameworks/Tungsten.framework/Tungsten`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfb564` | `0xfb7ec` | **`+0x288`** |
| `__DATA_CONST.__objc_selrefs` | `0x7ea8` | `0x7ec0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x11c08` | `0x11c20` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xe60` | `0xe70` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x22c40` | `0x22c48` | **`+0x8`** |
| `__TEXT.__cstring` | `0xd758` | `0xd75b` | **`+0x3`** |

### Other Changes

```diff

-910.21.101.0.0
+910.27.103.0.0

-  Functions: 6739
-  Symbols:   11622
+  Functions: 6740
+  Symbols:   11623
Symbols:
+ -[PXGView px_backgroundColor]
+ GCC_except_table5270
+ GCC_except_table5291
+ GCC_except_table5326
+ GCC_except_table5360
+ GCC_except_table5579
+ GCC_except_table5581
+ GCC_except_table5585
+ GCC_except_table5588
+ GCC_except_table5597
+ GCC_except_table5612
+ GCC_except_table5614
+ GCC_except_table5616
+ GCC_except_table5618
+ GCC_except_table5624
+ GCC_except_table5629
+ GCC_except_table5634
+ GCC_except_table5641
+ GCC_except_table5644
+ GCC_except_table5654
+ GCC_except_table5664
+ GCC_except_table5668
+ GCC_except_table5677
+ GCC_except_table5682
+ GCC_except_table5686
+ GCC_except_table5688
+ GCC_except_table5692
+ GCC_except_table5700
+ GCC_except_table5712
+ GCC_except_table5719
+ GCC_except_table5721
+ GCC_except_table5782
+ GCC_except_table5791
+ ___block_descriptor_124_e8_32s40s48s56s64s72s_e204_v200?0I8q12B20{_PXLayoutGeometry=q{CGPoint=dd}{CGSize=dd}{CGAffineTransform=dddddd}fq{CGRect={CGPoint=dd}{CGSize=dd}}{CGSize=dd}}24^{?={?=ddd}}176^{?=f{?=(?={?=ffff}[4f])}ffffSCf{?=[4]}}184^{?=CCfqSC}192ls32l8s40l8s48l8s56l8s64l8s72l8
+ ___block_descriptor_57_e8_32s40s_e101_v40?0{_PXGSpriteIndexRange=II}8^{?={?=ddd}}16^{?=f{?=(?={?=ffff}[4f])}ffffSCf{?=[4]}}24^{?=CCfqSC}32ls32l8s40l8
- GCC_except_table5269
- GCC_except_table5290
- GCC_except_table5324
- GCC_except_table5359
- GCC_except_table5577
- GCC_except_table5580
- GCC_except_table5582
- GCC_except_table5586
- GCC_except_table5589
- GCC_except_table5598
- GCC_except_table5613
- GCC_except_table5615
- GCC_except_table5617
- GCC_except_table5622
- GCC_except_table5625
- GCC_except_table5630
- GCC_except_table5635
- GCC_except_table5642
- GCC_except_table5652
- GCC_except_table5655
- GCC_except_table5665
- GCC_except_table5676
- GCC_except_table5678
- GCC_except_table5685
- GCC_except_table5687
- GCC_except_table5690
- GCC_except_table5697
- GCC_except_table5705
- GCC_except_table5714
- GCC_except_table5720
- GCC_except_table5781
- GCC_except_table5790
- ___block_descriptor_116_e8_32s40s48s56s64s_e201_v196?0I8q12{_PXLayoutGeometry=q{CGPoint=dd}{CGSize=dd}{CGAffineTransform=dddddd}fq{CGRect={CGPoint=dd}{CGSize=dd}}{CGSize=dd}}20^{?={?=ddd}}172^{?=f{?=(?={?=ffff}[4f])}ffffSCf{?=[4]}}180^{?=CCfqSC}188ls32l8s40l8s48l8s56l8s64l8
- ___block_descriptor_48_e8_32s_e101_v40?0{_PXGSpriteIndexRange=II}8^{?={?=ddd}}16^{?=f{?=(?={?=ffff}[4f])}ffffSCf{?=[4]}}24^{?=CCfqSC}32ls32l8
Functions:
~ -[PXGSublayoutDataStore enumerateSublayoutsInRange:options:usingBlock:] : 296 -> 284
~ ___165-[PXGLayout copyLayoutForSpritesInRange:applySpriteTransforms:parentTransform:parentAlpha:parentClippingRect:parentSublayoutOrigin:entities:geometries:styles:infos:]_block_invoke : 1596 -> 1576
~ -[PXGSublayoutDataStore enumerateSublayoutGeometriesInRange:options:usingBlock:] : 368 -> 352
~ ___36-[PXGGridLayout _updateSpriteStyles]_block_invoke_3 : 988 -> 968
~ -[PXGGridLayout _updateSpriteStyles] : 1176 -> 1276
~ -[PXGImageRequestQueue enqueueRequestsWithSpriteIndexRange:textureRequestIDs:displayAssetFetchResult:observer:presentationStyles:targetSize:screenScale:screenMaxHeadroom:adjustment:intent:useLowMemoryDecode:applyCleanApertureCrop:normalizedCropRect:mediaProvider:] : 444 -> 432
~ -[PXGGeneratedLayout _updateSprites] : 1512 -> 1564
~ ___36-[PXGGeneratedLayout _updateSprites]_block_invoke : 516 -> 576
~ ___36-[PXGGeneratedLayout _updateSprites]_block_invoke_2 : 580 -> 584
~ ___36-[PXGGeneratedLayout _updateSprites]_block_invoke_4 : 292 -> 296
~ _PXGAssertErrValidGeometries : 788 -> 808
~ _PXGAssertErrValidInfos : 656 -> 628
~ _PXGAssertErrValidStyles : 1444 -> 2188
~ -[PXGDecoratingLayout init] : 396 -> 388
~ -[PXGSpriteDataStore diagnosticDescription] : 512 -> 508
~ -[PXGItemsLayout setDelegate:] : 524 -> 564
~ -[PXGAnimator computeAnimationStateForTime:inputSpriteDataStore:inputChangeDetails:inputLayout:viewportShift:animationPresentationSpriteDataStore:animationTargetSpriteDataStore:animationChangeDetails:animationLayout:] : 12292 -> 12160
~ ___217-[PXGAnimator computeAnimationStateForTime:inputSpriteDataStore:inputChangeDetails:inputLayout:viewportShift:animationPresentationSpriteDataStore:animationTargetSpriteDataStore:animationChangeDetails:animationLayout:]_block_invoke_4 : 1632 -> 1540
~ ___217-[PXGAnimator computeAnimationStateForTime:inputSpriteDataStore:inputChangeDetails:inputLayout:viewportShift:animationPresentationSpriteDataStore:animationTargetSpriteDataStore:animationChangeDetails:animationLayout:]_block_invoke_10 : 1044 -> 948
~ ___217-[PXGAnimator computeAnimationStateForTime:inputSpriteDataStore:inputChangeDetails:inputLayout:viewportShift:animationPresentationSpriteDataStore:animationTargetSpriteDataStore:animationChangeDetails:animationLayout:]_block_invoke_13 : 880 -> 828
+ -[PXGView px_backgroundColor]
~ ___36-[PXGGridLayout _updateSpriteStyles]_block_invoke_4 : 136 -> 248
CStrings:
+ "v200@?0I8q12B20{_PXLayoutGeometry=q{CGPoint=dd}{CGSize=dd}{CGAffineTransform=dddddd}fq{CGRect={CGPoint=dd}{CGSize=dd}}{CGSize=dd}}24^{?={?=ddd}}176^{?=f{?=(?={?=ffff}[4f])}ffffSCf{?=[4]}}184^{?=CCfqSC}192"
- "v196@?0I8q12{_PXLayoutGeometry=q{CGPoint=dd}{CGSize=dd}{CGAffineTransform=dddddd}fq{CGRect={CGPoint=dd}{CGSize=dd}}{CGSize=dd}}20^{?={?=ddd}}172^{?=f{?=(?={?=ffff}[4f])}ffffSCf{?=[4]}}180^{?=CCfqSC}188"
```
