## PencilKit

> `/System/Library/Frameworks/PencilKit.framework/PencilKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x354df0` | `0x355ab8` | **`+0xcc8`** |
| `__TEXT.__gcc_except_tab` | `0x253e0` | `0x254b8` | **`+0xd8`** |
| `__TEXT.__objc_methlist` | `0x25fec` | `0x2606c` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0xe720` | `0xe780` | **`+0x60`** |
| `__TEXT.__cstring` | `0xf918` | `0xf962` | **`+0x4a`** |
| `__DATA_CONST.__objc_selrefs` | `0x13560` | `0x135a8` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x10748` | `0x10778` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x22b0` | `0x22c8` | **`+0x18`** |

### Other Changes

```diff

-613.0.0.0.0
+616.0.0.0.0

-  Functions: 18450
-  Symbols:   33084
-  CStrings:  3592
+  Functions: 18461
+  Symbols:   33098
+  CStrings:  3595
Symbols:
+ -[PKDrawing(Slicing) sliceWithEraseStroke:honoringErasable:]
+ -[PKDrawingPaletteView _setUpdateLinkActive:]
+ -[PKGroupQuery isAnyStrokeInMathGroup:]
+ -[PKImageView setBounds:]
+ -[PKMetalRenderer copyFromAddMultiplyLayersUsingRenderEncoder:clearIfMissing:setupClipping:]
+ -[PKPaletteHostView _compactHorizontalEdgePosition]
+ -[PKPaletteHostView _fixToHorizontalEdge:]
+ -[PKPaletteHostView _updateConstraintsToFixToHorizontalEdge:]
+ -[PKPaletteToolPickerAndColorPickerView _compactToolsContainerMaximumWidth]
+ -[PKPaletteToolPickerAndColorPickerView didMoveToWindow]
+ -[PKPaletteToolPickerAndColorPickerView safeAreaInsetsDidChange]
+ -[PKRecognitionController isAnyStrokeInMathGroup:]
+ -[PKRecognitionSessionManager isAnyStrokeInMathGroup:]
+ -[PKStroke _isErasable]
+ -[PKTiledView onScreenRotationForDrawing:]
+ -[_PKInkThicknessButton _applyColorsForSelected:highlighted:animated:]
+ GCC_except_table309
+ GCC_except_table311
+ GCC_except_table318
+ GCC_except_table331
+ GCC_except_table334
+ GCC_except_table337
+ GCC_except_table341
+ GCC_except_table344
+ GCC_except_table351
+ GCC_except_table353
+ GCC_except_table357
+ GCC_except_table361
+ GCC_except_table369
+ GCC_except_table376
+ GCC_except_table380
+ GCC_except_table385
+ GCC_except_table389
+ GCC_except_table392
+ GCC_except_table399
+ GCC_except_table406
+ GCC_except_table412
+ GCC_except_table479
+ _$sSo19PKStrokeRenderStateC9PencilKitEyAbC0A0V0bC0VcfC
+ _OBJC_CLASS_$_CATransition
+ _PKPaletteContentTopInset
+ ___52-[PKTiledCanvasView eraseStrokesForPoint:prevPoint:]_block_invoke
+ ___60-[PKDrawing(Slicing) sliceWithEraseStroke:honoringErasable:]_block_invoke
+ ___60-[PKDrawing(Slicing) sliceWithEraseStroke:honoringErasable:]_block_invoke_2
+ _kCAMediaTimingFunctionDefault
+ _kCATransitionFade
- -[PKMetalRenderer copyFromAddMultiplyLayersUsingRenderEncoder:clearIfMissing:]
- -[PKPaletteHostView _fixToBottomEdge]
- -[PKPaletteHostView _updateConstraintsToFixToBottomEdge]
- GCC_except_table304
- GCC_except_table310
- GCC_except_table313
- GCC_except_table321
- GCC_except_table332
- GCC_except_table336
- GCC_except_table340
- GCC_except_table342
- GCC_except_table349
- GCC_except_table352
- GCC_except_table354
- GCC_except_table359
- GCC_except_table366
- GCC_except_table372
- GCC_except_table377
- GCC_except_table381
- GCC_except_table386
- GCC_except_table390
- GCC_except_table394
- GCC_except_table400
- GCC_except_table408
- GCC_except_table478
- _$s9PencilKit8PKStrokeV11RenderStateV012asObjCRenderE0So0cdE0CyF
- _PKIsPhoneLandscape
- ___43-[PKDrawing(Slicing) sliceWithEraseStroke:]_block_invoke
- ___43-[PKDrawing(Slicing) sliceWithEraseStroke:]_block_invoke_2
- ___46-[_PKInkThicknessButton setSelected:animated:]_block_invoke
- ___52-[_PKInkThicknessButton _animateToHighlightedState:]_block_invoke
- ___52-[_PKInkThicknessButton _animateToHighlightedState:]_block_invoke_2
CStrings:
+ "PaperKit.WritingToolsTextInputView"
+ "backgroundColorFade"
+ "tintColorCrossfade"
```
