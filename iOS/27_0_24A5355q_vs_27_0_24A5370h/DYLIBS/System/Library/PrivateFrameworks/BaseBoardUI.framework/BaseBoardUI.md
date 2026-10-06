## BaseBoardUI

> `/System/Library/PrivateFrameworks/BaseBoardUI.framework/BaseBoardUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18d98` | `0x18f38` | **`+0x1a0`** |
| `__TEXT.__gcc_except_tab` | `0x2e38` | `0x2e78` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x5d0` | `0x5f8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x15c8` | `0x15e8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xe38` | `0xe48` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x458` | `0x460` | **`+0x8`** |
| `__TEXT.__const` | `0x3d8` | `0x3e0` | **`+0x8`** |

### Other Changes

```diff

-821.0.0.0.0
+825.0.0.0.0

-  Functions: 527
-  Symbols:   1318
+  Functions: 528
+  Symbols:   1319
Symbols:
+ _OBJC_CLASS_$_NSProcessInfo
+ ___79-[BSUIAnimationFactory _animateWithAdditionalDelay:options:actions:completion:]_block_invoke_2
+ ___block_descriptor_48_ea8_32s40bs_e8_v12?0B8ls32l8s40l8
- GCC_except_table28
- GCC_except_table40
Functions:
~ -[BSUIOrientationTransformWrapperView _updateGeometry] : 692 -> 688
~ +[BSUIAnimationFactory animateWithFactory:additionalDelay:options:actions:completion:] : 648 -> 948
~ -[BSUICAPackageView initWithURL:] : 932 -> 928
~ -[BSUIMappedImageCache debugDescriptionWithMultilinePrefix:] : 596 -> 592
~ ___43-[BSUIMappedImageCache _warmupImageForKey:]_block_invoke : 548 -> 544
~ ___56-[BSUIPartialStylingLabelView _updateLabelsWithRawText:]_block_invoke : 528 -> 524
+ ___79-[BSUIAnimationFactory _animateWithAdditionalDelay:options:actions:completion:]_block_invoke_2
~ -[BSUIOrientationTransformWrapperView hitTest:withEvent:] : 448 -> 444
~ __setLayerFilters : 1248 -> 1244
```
