## NeutrinoKit

> `/System/Library/PrivateFrameworks/NeutrinoKit.framework/NeutrinoKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18a20` | `0x189e4` | **`-0x3c`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0
Functions:
~ -[CALayer(NeutrinoUIDebugging) _nu_recursiveDescriptionWithLevel:result:] : 928 -> 924
~ -[NUAVPlayerController dealloc] : 324 -> 320
~ -[NUAVPlayerController prepareWithAVAsset:videoComposition:audioMix:loopsVideo:seekToTime:] : 1160 -> 1152
~ -[NUAVPlayerController updateVideoComposition:] : 524 -> 520
~ -[NUAVPlayerController updateWithVideoPrepareNodeFromVideoComposition:] : 568 -> 564
~ -[NUAVPlayerController updateAudioMix:] : 524 -> 520
~ -[NUAVPlayerController updateAppliesPerFrameHDRDisplayMetadata:] : 492 -> 488
~ -[NUAVPlayerController setLoopsVideo:] : 560 -> 552
~ -[NUAVPlayerController _removePlayerItemKVO:removeFromArray:] : 488 -> 484
~ -[NUAVPlayerController _addPlayerItemKVO:] : 520 -> 516
~ ___34-[NUTiledImageLayer _recycleTiles]_block_invoke : 272 -> 268
~ ___34-[NUTiledImageLayer snapshotImage]_block_invoke : 444 -> 440
~ +[UIView(NeutrinoAdditions) _recurseView:filter:] : 324 -> 320
```
