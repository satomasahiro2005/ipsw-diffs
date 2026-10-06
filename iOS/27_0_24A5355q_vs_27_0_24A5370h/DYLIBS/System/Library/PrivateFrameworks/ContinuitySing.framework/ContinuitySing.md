## ContinuitySing

> `/System/Library/PrivateFrameworks/ContinuitySing.framework/ContinuitySing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c680` | `0x5c600` | **`-0x80`** |
| `__TEXT.__unwind_info` | `0x1820` | `0x1828` | **`+0x8`** |

### Other Changes

```diff

-748.0.0.122.2
+753.0.0.122.3
Functions:
~ -[CSMiniPlayerView _addSubviewsForAutolayout:] : 224 -> 220
~ -[CSPlaybackManager _handleNewPlaybackState:] : 372 -> 368
~ -[CSTrackQueuedMessage initWithMessage:] : 588 -> 584
~ -[CSTrackQueuedMessage dictionaryRepresentation] : 436 -> 432
~ ___32-[CSRemoteRequestClient dealloc]_block_invoke : 276 -> 272
~ -[CSRemoteRequestClient _activateMessageClientIfNeeded:] : 1064 -> 1060
~ -[CSRemoteRequestClient _resolvePendingActivationCompletionsWithError:] : 252 -> 248
~ -[CSQueueAttributionManager retrieveAttributionsForQueueIdentifiers:withResultHandler:] : 588 -> 584
~ ___87-[CSQueueAttributionManager retrieveAttributionsForQueueIdentifiers:withResultHandler:]_block_invoke_2 : 344 -> 340
~ +[CSShieldManager appendSingSessionTypeToMusicURL:] : 500 -> 496
~ -[CSShieldManager setPresentationErrorDetails:] : 552 -> 548
~ -[CSShieldManager _bootstrapFromSingQRCodeURL:] : 900 -> 896
~ -[CSShieldManager _teardownShieldWithError:] : 328 -> 324
~ ___36-[CSShieldManager _notifyDisconnect]_block_invoke : 252 -> 248
~ -[CSShieldManager _finishLoading] : 264 -> 260
~ -[CSShieldManager _updateSessionState:] : 648 -> 644
~ -[CSErrorDetails _generateTechnicalDescription] : 588 -> 584
~ ___43-[CSShieldViewController _endLoadingScreen]_block_invoke : 288 -> 284
~ -[CSShieldViewController mediaPicker:didPickMediaItems:] : 580 -> 576
~ -[CSPairingServer appendPairingCodeToURL:] : 528 -> 524
~ -[CSMessage initWithMessage:] : 480 -> 476
~ ___41-[CSQueueViewController updateDataSource]_block_invoke : 460 -> 456
~ ___41-[CSQueueViewController updateDataSource]_block_invoke_4 : 540 -> 536
~ ___35-[CSPairingMessagingClient dealloc]_block_invoke : 276 -> 272
~ ___64-[CSPairingMessagingClient _serviceActivationHandlersWithError:]_block_invoke : 212 -> 208
~ -[CSPairingMessagingClient deviceForMediaRouteIdentifier:] : 384 -> 380
~ -[CSPairingMessagingClient deviceForRemoteDisplayIdentifier:] : 268 -> 264
~ ___76-[CSPairingMessagingClient _completePendingGroupSessionTokenRequests:error:]_block_invoke_2 : 212 -> 208
~ -[PRXCardContentViewController(AccessibilityIdentifier) setAccessibilityIdentifier:forAction:] : 516 -> 512
~ -[CSSessionStateUpdate initWithMessage:] : 784 -> 780
~ -[CSSessionStateUpdate dictionaryRepresentation] : 584 -> 580
~ sub_2525bb5cc -> sub_2538ef550 : 500 -> 504
~ sub_2525c1c54 -> sub_2538f5bdc : 280 -> 276
~ sub_2525c35f0 -> sub_2538f7574 : 1344 -> 1356
~ sub_2525c3d98 -> sub_2538f7d28 : 2388 -> 2396
~ sub_2525c6630 -> sub_2538fa5c8 : 368 -> 360
~ sub_2525cbec8 -> sub_2538ffe58 : 512 -> 516
~ sub_2525d254c -> sub_2539064e0 : 480 -> 484
~ sub_2525d5168 -> sub_253909100 : 404 -> 416
~ sub_2525d52fc -> sub_2539092a0 : 488 -> 504
~ sub_2525d60fc -> sub_25390a0b0 : 1724 -> 1748
~ sub_2525d740c -> sub_25390b3d8 : 344 -> 340
~ sub_2525d7564 -> sub_25390b52c : 152 -> 164
~ sub_2525d75fc -> sub_25390b5d0 : 112 -> 124
~ sub_2525d7e84 -> sub_25390be64 : 2152 -> 2032
~ sub_2525da57c -> sub_25390e4e4 : 368 -> 360
~ sub_2525da744 -> sub_25390e6a4 : 252 -> 276
~ sub_2525daa4c -> sub_25390e9c4 : 1128 -> 1136
```
