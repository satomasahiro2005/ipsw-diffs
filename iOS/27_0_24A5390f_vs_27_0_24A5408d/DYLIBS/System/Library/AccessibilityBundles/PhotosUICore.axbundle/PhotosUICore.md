## PhotosUICore

> `/System/Library/AccessibilityBundles/PhotosUICore.axbundle/PhotosUICore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18260` | `0x1893c` | **`+0x6dc`** |
| `__TEXT.__oslogstring` | `0x17` | `0x273` | **`+0x25c`** |
| `__AUTH_CONST.__cfstring` | `0x49c0` | `0x4a20` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x67c` | `0x6c4` | **`+0x48`** |
| `__TEXT.__cstring` | `0x39d3` | `0x3a00` | **`+0x2d`** |
| `__DATA_CONST.__const` | `0x7c8` | `0x7f0` | **`+0x28`** |
| `__TEXT.__const` | `0x48` | `0x60` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x2858` | `0x2870` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1238` | `0x1248` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x8c0` | `0x8d0` | **`+0x10`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 763
-  Symbols:   1757
-  CStrings:  648
+  Functions: 766
+  Symbols:   1765
+  CStrings:  657
Symbols:
+ -[AXPhotosGroupAccessibilityElement _axStoryCurrentPhotoLabel]
+ -[AXPhotosGroupAccessibilityElement _axVisibleStoryClipLayoutInDescendants]
+ GCC_except_table119
+ GCC_except_table121
+ GCC_except_table181
+ GCC_except_table256
+ GCC_except_table257
+ GCC_except_table265
+ GCC_except_table271
+ GCC_except_table273
+ GCC_except_table286
+ GCC_except_table287
+ GCC_except_table414
+ GCC_except_table491
+ GCC_except_table499
+ GCC_except_table516
+ GCC_except_table524
+ GCC_except_table525
+ GCC_except_table526
+ GCC_except_table537
+ GCC_except_table538
+ GCC_except_table539
+ GCC_except_table548
+ GCC_except_table549
+ GCC_except_table550
+ GCC_except_table585
+ GCC_except_table587
+ GCC_except_table648
+ GCC_except_table692
+ GCC_except_table697
+ GCC_except_table751
+ GCC_except_table80
+ _AXAIWhiteGloveLoggingEnabled
+ _AXLogAppAccessibility
+ ___75-[AXPhotosGroupAccessibilityElement _axVisibleStoryClipLayoutInDescendants]_block_invoke
+ ___block_descriptor_40_e8_32r_e50_v32?0"AXPhotosGroupAccessibilityElement"8Q16^B24lr32l8
+ __os_log_impl
- GCC_except_table116
- GCC_except_table118
- GCC_except_table178
- GCC_except_table253
- GCC_except_table254
- GCC_except_table262
- GCC_except_table268
- GCC_except_table270
- GCC_except_table283
- GCC_except_table284
- GCC_except_table411
- GCC_except_table488
- GCC_except_table496
- GCC_except_table513
- GCC_except_table520
- GCC_except_table521
- GCC_except_table522
- GCC_except_table532
- GCC_except_table534
- GCC_except_table536
- GCC_except_table543
- GCC_except_table545
- GCC_except_table547
- GCC_except_table582
- GCC_except_table584
- GCC_except_table645
- GCC_except_table689
- GCC_except_table694
- GCC_except_table748
CStrings:
+ "displayAsset"
+ "isSegmentVisible"
+ "memories.photo"
+ "rdar://167604996 PXUIAssetBadgeView accessibilityLabel fallback super label=%{public}@"
+ "rdar://167604996 PXUIAssetBadgeView accessibilityLabel from _topLeftPrimaryGroup label=%{public}@"
+ "rdar://167604996 PXUIAssetBadgeView accessibilityTraits style=%ld traits=0x%llx isSharing=%d"
+ "rdar://167604996 PXUIAssetBadgeView accessibilityValue enter badges=0x%llx style=%ld livePhoto=%d autoloop=%d toggleable=%d toggledOn=%d toggledOff=%d"
+ "rdar://167604996 PXUIAssetBadgeView accessibilityValue exit value=%{public}@"
+ "rdar://167604996 PXUIAssetBadgeView isAccessibilityElement badges=0x%llx style=%ld isAXElement=%d"
```
