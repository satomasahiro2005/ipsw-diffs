## PencilKit

> `/System/Library/Frameworks/PencilKit.framework/PencilKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x354664` | `0x354df0` | **`+0x78c`** |
| `__TEXT.__gcc_except_tab` | `0x25338` | `0x253e0` | **`+0xa8`** |
| `__AUTH_CONST.__objc_const` | `0x48d88` | `0x48dd8` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x13530` | `0x13560` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x25fcc` | `0x25fec` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x1ef4` | `0x1f06` | **`+0x12`** |
| `__AUTH_CONST.__auth_got` | `0x1e10` | `0x1e20` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x22a0` | `0x22b0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x10738` | `0x10748` | **`+0x10`** |
| `__AUTH.__objc_data` | `0xa690` | `0xa698` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x1f24` | `0x1f2c` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2cb4` | `0x2cb8` | **`+0x4`** |

### Other Changes

```diff

-610.100.0.0.0
+613.0.0.0.0

+  - /System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices

-  Functions: 18446
-  Symbols:   33071
+  Functions: 18450
+  Symbols:   33084
Symbols:
+ -[PKDrawing _copyAndAddStroke:transform:inkTransform:ink:newParent:forceNewUUID:existingStrokesUUIDs:]
+ _$s5UIKit17UITraitDefinitionMp
+ _$s5UIKit19UITraitDisplayScaleVAA0B10DefinitionAAWP
+ _$s5UIKit19UITraitDisplayScaleVMa
+ _$s9PencilKit16LiveStrokeCanvasC10commonInit33_57D368878EAFD526011FA7F13D87E952LL10sixChannelySb_tFyACXD_So17UITraitCollectionCtcfU0_Tf4nnd_n
+ _$sSo6UIViewC5UIKitE23registerForTraitChanges_7handlerSo25UITraitChangeRegistration_pSayAC0H10Definition_pXpG_yx_So0H10CollectionCtctSo0H11EnvironmentRzlF
+ _$ss23_ContiguousArrayStorageCy5UIKit17UITraitDefinition_pXpGMR
+ _$ss23_ContiguousArrayStorageCy5UIKit17UITraitDefinition_pXpGMd
+ _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.173TQ0_
+ _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.173Tu
+ _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.200TQ0_
+ _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.200Tu
+ _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.217TQ0_
+ _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.217Tu
+ _OBJC_CLASS_$_UISplitViewController
+ _OBJC_IVAR_$_PKPaletteToolPickerClippingView._scrollingEnabled
+ _PKTopContentViewController
+ __ZL28_PKDrawingCollectStrokeUUIDsP9PKDrawingP8PKStrokeP12NSMutableSetIP6NSUUIDE
+ ___swift_closure_destructor.167Tm
+ _symbolic _____y______pXpG s23_ContiguousArrayStorageC 5UIKit17UITraitDefinitionP
- _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.172TQ0_
- _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.172Tu
- _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.199TQ0_
- _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.199Tu
- _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.216TQ0_
- _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.216Tu
- ___swift_closure_destructor.166Tm
Functions:
~ ___49-[PKMetalRendererController clearLiveBackBuffers]_block_invoke : 224 -> 248
~ -[PKDrawing _copyAndAddStrokes:transform:inkTransform:forceNewUUID:] : 484 -> 780
+ __ZL28_PKDrawingCollectStrokeUUIDsP9PKDrawingP8PKStrokeP12NSMutableSetIP6NSUUIDE
~ -[PKDrawing _copyAndAddStroke:transform:inkTransform:ink:newParent:forceNewUUID:] : 884 -> 76
+ -[PKDrawing _copyAndAddStroke:transform:inkTransform:ink:newParent:forceNewUUID:existingStrokesUUIDs:]
~ -[PKPaletteHostView _updatePaletteViewLayoutGuideInsets] : 552 -> 568
~ -[PKMetalRenderer finishRenderingNoTeardownForStroke:clippedToPixelSpaceRect:renderEncoder:] : 444 -> 488
~ -[PKMetalResourceHandler _sixChannelShaderWithKey:] : 2164 -> 2344
+ _PKTopContentViewController
~ -[PKPaletteAdditionalOptionsView initWithFrame:] : 2480 -> 2460
~ -[PKPaletteAdditionalOptionsView _pencilInteractionPrefersPencilOnlyDrawsDidChange] : 128 -> 132
~ -[PKPaletteToolPickerClippingView init] : 2436 -> 2456
~ -[PKPaletteToolPickerClippingView _updateUI] : 2084 -> 1936
~ -[PKPaletteToolPickerView updateClippingViewEdgesVisibility] : 368 -> 440
~ _$s9PencilKit16LiveStrokeCanvasC10commonInit33_57D368878EAFD526011FA7F13D87E952LL10sixChannelySb_tF : 1248 -> 1448
~ _$s9PencilKit16LiveStrokeCanvasC14sixChannelModeSbvW : 412 -> 448
~ _$s9PencilKit16LiveStrokeCanvasC12drawingBegan10inputPoint10forPreviewyAA05InputI0V_SbtF : 2668 -> 2836
~ _$s9PencilKit16LiveStrokeCanvasC31resizeBackingBuffersIfNecessary33_57D368878EAFD526011FA7F13D87E952LLyyF : 356 -> 444
+ _$s9PencilKit16LiveStrokeCanvasC10commonInit33_57D368878EAFD526011FA7F13D87E952LL10sixChannelySb_tFyACXD_So17UITraitCollectionCtcfU0_Tf4nnd_n
```
