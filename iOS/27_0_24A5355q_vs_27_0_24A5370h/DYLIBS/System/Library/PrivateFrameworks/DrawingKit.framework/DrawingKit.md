## DrawingKit

> `/System/Library/PrivateFrameworks/DrawingKit.framework/DrawingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12918` | `0x12884` | **`-0x94`** |
| `__TEXT.__unwind_info` | `0x828` | `0x830` | **`+0x8`** |

### Other Changes

```diff

-577.0.0.0.0
+579.0.0.0.0
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorI11VertexGroupEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorI4PageEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorI6VertexEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIDv2_fEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorINS_4pairIDv2_fS3_EEEENS_16allocator_traitsIS5_EEEENS_19__allocation_resultINT0_7pointerENS9_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorI11VertexGroupNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorI4PageNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorI6VertexNS_9allocatorIS1_EEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorI6VertexNS_9allocatorIS1_EEE16__init_with_sizeB9fqe220106INS_11__wrap_iterIPS1_EES8_EEvT_T0_m
+ __ZNSt3__16vectorI6VertexNS_9allocatorIS1_EEE16__init_with_sizeB9fqe220106IPS1_S6_EEvT_T0_m
+ __ZNSt3__16vectorI6VertexNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIDv2_fNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorINS_4pairIDv2_fS2_EENS_9allocatorIS3_EEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorI11VertexGroupEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorI4PageEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorI6VertexEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIDv2_fEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorINS_4pairIDv2_fS3_EEEENS_16allocator_traitsIS5_EEEENS_19__allocation_resultINT0_7pointerENS9_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorI11VertexGroupNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorI4PageNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorI6VertexNS_9allocatorIS1_EEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorI6VertexNS_9allocatorIS1_EEE16__init_with_sizeB9fqe220100INS_11__wrap_iterIPS1_EES8_EEvT_T0_m
- __ZNSt3__16vectorI6VertexNS_9allocatorIS1_EEE16__init_with_sizeB9fqe220100IPS1_S6_EEvT_T0_m
- __ZNSt3__16vectorI6VertexNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIDv2_fNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorINS_4pairIDv2_fS2_EENS_9allocatorIS3_EEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
Functions:
~ -[DKInkRendererCG drawRect:] : 944 -> 936
~ +[HWEncoding encodeBrushStrokesAsData:inCanvasBounds:inStrokesFrame:] : 932 -> 944
~ +[HWEncoding decodedBrushStrokesWithData:inCanvasBounds:inStrokesFrame:strokeDataFieldCount:count:] : 948 -> 896
~ +[DKPointSmoothing _interpolateFromPoint:toPoint:withControlPoint:atUnitScale:emissionHandler:] : 380 -> 376
~ -[DKInkView _renderEmittedPoints:count:] : 804 -> 820
~ -[DKInkView _setDrawingOnRendererWithBleedAnimation:] : 1892 -> 1884
~ -[DKInkView _replayAnimationTick:] : 412 -> 408
~ -[DKInkView handleCoalescedTouches:forTouch:average:] : 316 -> 312
~ -[DKDrawing totalPoints] : 284 -> 280
~ -[DKDrawing encodeBrushStrokesForArchiving] : 468 -> 464
~ -[DKDrawing decodedBrushStrokesWithArchiverEncodedBrushStrokes:] : 472 -> 468
~ +[DKDrawing resizeDrawing:toFitInBounds:] : 876 -> 868
~ -[DKDrawingStroke _encodePointsDrawingPointData:] : 280 -> 272
~ -[DKDrawingStroke _decodeDKEncodedDrawingPointDataAsArray:count:] : 236 -> 256
~ -[DKOpenGLRenderer initializeFrameBuffers] : 484 -> 476
~ -[DKOpenGLRenderer appendVertexHistoryElement] : 144 -> 152
~ -[DKOpenGLRenderer update] : 516 -> 512
~ -[DKOpenGLRenderer renderToDryPaintBuffer] : 440 -> 428
~ -[DKOpenGLRenderer renderToComposite:] : 548 -> 500
~ -[DKOpenGLRenderer drawComposite] : 500 -> 496
~ -[DKOpenGLRenderer clearDryPaintBuffer] : 212 -> 208
~ -[DKOpenGLRenderer clearComposite] : 212 -> 200
~ +[DKGLUtilities setProjectionMatrixForWidth:height:flipped:matrix:] : 200 -> 196
~ +[DKGLUtilities translateMatrix:byX:Y:result:] : 152 -> 148
~ ___81+[DKInkThumbnailRenderer _interpolateDrawing:inSize:displayScale:ellipseHandler:]_block_invoke : 92 -> 96
```
