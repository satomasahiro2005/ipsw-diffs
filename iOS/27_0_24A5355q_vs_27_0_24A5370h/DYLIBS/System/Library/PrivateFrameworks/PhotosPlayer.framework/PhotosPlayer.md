## PhotosPlayer

> `/System/Library/PrivateFrameworks/PhotosPlayer.framework/PhotosPlayer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2bd20` | `0x2bccc` | **`-0x54`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0
Functions:
~ ___62-[ISWrappedMemoriesAppleMusicPlayer initWithPlayerItem:queue:]_block_invoke : 1224 -> 1220
~ -[AVPlayerItem(PhotosPlayer) is_enableColorMatching] : 244 -> 240
~ -[AVPlayerItem(PhotosPlayer) is_setAudioTracksEnabled:] : 352 -> 348
~ -[ISBasePlayer videoLayersReadyForDisplay] : 308 -> 304
~ -[ISBasePlayer enumerateOutputsWithBlock:] : 288 -> 284
~ -[ISKVOProxy startObservingTarget] : 260 -> 256
~ -[ISKVOProxy stopObservingTarget] : 276 -> 272
~ -[ISKVOProxy dealloc] : 280 -> 276
~ -[ISAnimatedImagePlayer _notifyDestinationsOfFrameChange] : 248 -> 244
~ -[ISAnimatedImagePlayer _notifyDestinationsOfAnimationStart] : 292 -> 288
~ -[ISAnimatedImagePlayer _notifyDestinationsOfAnimationEnd] : 292 -> 288
~ -[ISAnimatedImagePlayer _anyDestinationIsReady] : 268 -> 264
~ ___36-[ISObservable _applyPendingChanges]_block_invoke_2 : 276 -> 272
~ -[ISObservable _observersQueue_copyChangeObserversForWriteIfNeeded] : 360 -> 356
~ -[_ISPlayerItemChefOperation _preparePlayerItem] : 2472 -> 2460
~ -[ISPlayerView _setPlayerView:] : 688 -> 680
~ ___56-[ISScrollViewVitalityController _updateVitalityFilters]_block_invoke : 556 -> 552
~ ___54+[ISVitalitySpecificSettings settingsControllerModule]_block_invoke : 380 -> 376
```
