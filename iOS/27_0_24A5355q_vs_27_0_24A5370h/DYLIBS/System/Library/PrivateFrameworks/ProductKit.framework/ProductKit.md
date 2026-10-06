## ProductKit

> `/System/Library/PrivateFrameworks/ProductKit.framework/ProductKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6c604` | `0x6c698` | **`+0x94`** |
| `__TEXT.__unwind_info` | `0x1d00` | `0x1cf8` | **`-0x8`** |

### Other Changes

```diff

-146.100.2.0.0
+148.100.1.0.0
Functions:
~ _PKPlaybackTimeRangesFromFeaturesTimeURL : 524 -> 520
~ -[PKMediaPlayerView stop] : 512 -> 508
~ -[PKMediaPlayerView removeAllQueuedItems] : 268 -> 264
~ -[PKMediaPlayerView breakFirstEnqueuedLoop] : 400 -> 396
~ -[PKMediaPlayerView enqueueItemsFromMediaItem:afterItem:] : 736 -> 732
~ -[PKMediaPlayerView dequeueNonPlayingItemsFromMediaItem:] : 620 -> 616
~ -[PKMediaPlayerView observeValueForKeyPath:ofObject:change:context:] : 864 -> 860
~ -[PKMediaPlayerView setUpTimeRangeNotificationsForItem:] : 824 -> 820
~ ___43-[PKMediaPlayerView playerItemDidReachEnd:]_block_invoke : 492 -> 488
~ sub_29357a868 -> sub_29494c844 : 956 -> 976
~ sub_2935819ac -> sub_29495399c : 1416 -> 1324
~ sub_293586f00 -> sub_294958e94 : 24 -> 20
~ sub_293586f18 -> sub_294958ea8 : 84 -> 80
~ sub_293586f6c -> sub_294958ef8 : 60 -> 56
~ sub_293586fa8 -> sub_294958f30 : 80 -> 76
~ sub_293587000 -> sub_294958f84 : 28 -> 24
~ sub_2935875a8 -> sub_294959528 : 60 -> 56
~ sub_29358cc00 -> sub_29495eb7c : 2756 -> 2760
~ sub_2935951c4 -> sub_294967144 : 1384 -> 1408
~ sub_29359579c -> sub_294967734 : 3228 -> 3252
~ sub_2935a124c -> sub_2949731fc : 528 -> 532
~ sub_2935a92e4 -> sub_29497b298 : 588 -> 584
~ sub_2935abd60 -> sub_29497dd10 : 696 -> 708
~ sub_2935af094 -> sub_294981050 : 1128 -> 1144
~ sub_2935afea0 -> sub_294981e6c : 1080 -> 1092
~ sub_2935b251c -> sub_2949844f4 : 476 -> 480
~ sub_2935b2e40 -> sub_294984e1c : 268 -> 272
~ sub_2935b4358 -> sub_294986338 : 280 -> 276
~ sub_2935ba560 -> sub_29498c53c : 1556 -> 1600
~ sub_2935bd9a8 -> sub_29498f9b0 : 772 -> 796
~ sub_2935bde88 -> sub_29498fea8 : 1032 -> 1056
~ sub_2935bebb4 -> sub_294990bec : 1420 -> 1444
~ sub_2935bf390 -> sub_2949913e0 : 524 -> 508
~ sub_2935c02a4 -> sub_2949922e4 : 668 -> 672
~ sub_2935c1088 -> sub_2949930cc : 1220 -> 1228
~ sub_2935c83a8 -> sub_29499a3f4 : 1104 -> 1120
~ sub_2935c9c48 -> sub_29499bca4 : 256 -> 276
~ sub_2935cfc88 -> sub_2949a1cf8 : 788 -> 784
~ sub_2935d1bb0 -> sub_2949a3c1c : 432 -> 440
~ sub_2935d42f4 -> sub_2949a6368 : 2236 -> 2208
~ sub_2935d5c6c -> sub_2949a7cc4 : 216 -> 212
~ sub_2935d5d44 -> sub_2949a7d98 : 1004 -> 1000
~ sub_2935d6ef0 -> sub_2949a8f40 : 304 -> 308
~ sub_2935d8360 -> sub_2949aa3b4 : 472 -> 476
~ sub_2935d8910 -> sub_2949aa968 : 256 -> 276
~ sub_2935d8a24 -> sub_2949aaa90 : 228 -> 248
~ sub_2935d919c -> sub_2949ab21c : 248 -> 272
~ sub_2935d9294 -> sub_2949ab32c : 440 -> 436
```
