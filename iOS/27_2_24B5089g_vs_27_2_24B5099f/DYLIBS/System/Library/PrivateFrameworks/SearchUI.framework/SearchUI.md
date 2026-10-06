## SearchUI

> `/System/Library/PrivateFrameworks/SearchUI.framework/SearchUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf71c0` | `0xf74e4` | **`+0x324`** |
| `__TEXT.__gcc_except_tab` | `0xa58` | `0xad4` | **`+0x7c`** |
| `__AUTH_CONST.__objc_const` | `0x1e0e8` | `0x1e148` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x2915` | `0x2975` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x124e8` | `0x12530` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0xa2e0` | `0xa318` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x48f8` | `0x4918` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0xd00` | `0xd08` | **`+0x8`** |

### Other Changes

```diff

-685.1.3.0.0
+685.1.8.200.0

-  Functions: 7024
-  Symbols:   11517
-  CStrings:  831
+  Functions: 7033
+  Symbols:   11527
+  CStrings:  832
Symbols:
+ +[SearchUIAppIconUtilities insetFromPlatterToAppIconGrid]
+ +[SearchUIUtilities standardGridContentInset]
+ -[SearchUIGridSectionModel separatorStyleForIndex:shouldDrawTopAndBottomSeparators:]
+ -[SearchUIImage boundsTargetSizeExactly]
+ -[SearchUIImage setBoundsTargetSizeExactly:]
+ -[SearchUIResultsCollectionViewController pendingHighlightResult]
+ -[SearchUIResultsCollectionViewController setPendingHighlightResult:]
+ GCC_except_table35
+ _OBJC_IVAR_$_SearchUIImage._boundsTargetSizeExactly
+ _OBJC_IVAR_$_SearchUIResultsCollectionViewController._pendingHighlightResult
+ _TLKImageHasAlphaChannel
+ ___89-[SearchUIResultsCollectionViewController updateWithResultSections:scrollToTop:animated:]_block_invoke
+ ___block_descriptor_90_e8_32s40bs_e17_v16?0"PHAsset"8ls32l8s40l8
+ ___block_descriptor_98_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
- _UIImageHEICRepresentation
- ___75-[SearchUIOpenUserActivityHandler performCommand:triggerEvent:environment:]_block_invoke_2
- ___block_descriptor_89_e8_32s40bs_e17_v16?0"PHAsset"8ls32l8s40l8
- ___block_descriptor_97_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
CStrings:
+ "No application record for %@, refusing to open user activity with an unresolved destination"
```
