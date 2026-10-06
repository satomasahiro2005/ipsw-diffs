## Pegasus

> `/System/Library/PrivateFrameworks/Pegasus.framework/Pegasus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43028` | `0x42fd8` | **`-0x50`** |

### Other Changes

```text
Functions:
~ -[PGPictureInPictureController pictureInPictureInterruptionBeganWithReason:attribution:] : 572 -> 568
~ -[PGPictureInPictureProxy _sourceScene] : 372 -> 368
~ -[PGPlaybackState isEquivalentToPlaybackState:] : 636 -> 632
~ -[UIView(PGVibrancyEffects) PG_recursivelyDisallowGroupBlending] : 272 -> 268
~ +[PGPictureInPictureApplication pictureInPictureApplicationWithProcessIdentifier:] : 376 -> 372
~ -[PGPictureInPictureController _remoteObjectForTestApplicationWithBundleIdentifier:] : 356 -> 352
~ -[PGPictureInPictureController pictureInPictureInterruptionEndedWithReason:attribution:] : 780 -> 776
~ -[PGPictureInPictureController existingPictureInPictureApplicationForBundleIdentifier:] : 344 -> 340
~ -[PGPictureInPictureController activeSceneSessionIdentifiersByApplication] : 484 -> 480
~ -[PGPictureInPictureController _updateAllRemoteObjectsForPIPPossibleAndExemptAttributions] : 1428 -> 1420
~ -[PGPictureInPictureController pictureInPictureRemoteObject:willShowPictureInPictureViewController:] : 1436 -> 1432
~ -[PGCABackdropLayerView _enumerateDependents:] : 296 -> 292
~ -[PGControlsView initWithFrame:viewModel:] : 1624 -> 1620
~ -[PGControlsView updateControlsAlpha] : 708 -> 700
~ -[PGControlsView layoutSubviews] : 5832 -> 5828
~ -[PGPlaybackState diffFromPlaybackState:] : 676 -> 672
~ -[PGPictureInPictureProxy _resetInternalState] : 732 -> 728
~ ___41-[PGPictureInPictureProxy handleCommand:]_block_invoke : 1540 -> 1536
```
