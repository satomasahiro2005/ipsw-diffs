## PassKitUIFoundation

> `/System/Library/PrivateFrameworks/PassKitUIFoundation.framework/PassKitUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26180` | `0x26110` | **`-0x70`** |

### Other Changes

```diff

-1677.4.0.0.0
+1682.1.0.0.0
Functions:
~ -[PKPeerPayment3DTextView renderer:updateAtTime:] : 2148 -> 2140
~ ___58-[PKPeerPayment3DTextView renderer:didRenderScene:atTime:]_block_invoke : 300 -> 296
~ -[PKPeerPayment3DStore motionManager:didReceiveMotion:] : 692 -> 688
~ ___41-[PKPeerPayment3DStore nodeForCharacter:]_block_invoke : 992 -> 984
~ _PKCurrencyCodeForTransitTransactionIcon : 332 -> 328
~ -[PKAuthenticatorEvaluationContext invalidateWithIntent:] : 1816 -> 1812
~ ___57-[PKAuthenticatorEvaluationContext invalidateWithIntent:]_block_invoke.218 -> ___57-[PKAuthenticatorEvaluationContext invalidateWithIntent:]_block_invoke.233 : 252 -> 248
~ -[PKAuthenticatorEvaluationContext _createContextWithExternalizedContext:] : 928 -> 924
~ -[PKAuthenticator _swapContext:withOptions:] : 820 -> 816
~ -[PKFingerprintGlyphView init] : 3504 -> 3480
~ -[PKFingerprintGlyphView _executeTransitionCompletionHandlers:] : 288 -> 284
~ -[PKFingerprintGlyphView _setRingState:withTransitionIndex:animated:] : 1404 -> 1412
~ -[PKFingerprintGlyphView _applyColor:toShapeLayers:animated:] : 764 -> 760
~ -[PKMotionManager updateWithMotion:] : 280 -> 276
~ -[PKCategoryVisualizationCardView setMagnitudes:withStyle:] : 656 -> 652
~ -[PKGlyphView _executeTransitionCompletionHandlers:] : 288 -> 284
~ ___62-[PKGlyphView _applyEffectiveHighlightColorsToLayersAnimated:]_block_invoke_2 : 476 -> 468
~ ___59-[PKGlyphView _applyEffectivePrimaryColorToLayersAnimated:]_block_invoke_3 : 476 -> 468
~ -[PKCategoryVisualizationCardView _updateCircles] : 1184 -> 1152
~ -[PKCategoryVisualizationCardView _empty] : 528 -> 524
~ -[PKCategoryVisualizationCardView _calculateNewCirclePositions] : 832 -> 844
~ ___41-[PKCategoryVisualizationCardView _empty]_block_invoke.cold.1 : 56 -> 64
```
