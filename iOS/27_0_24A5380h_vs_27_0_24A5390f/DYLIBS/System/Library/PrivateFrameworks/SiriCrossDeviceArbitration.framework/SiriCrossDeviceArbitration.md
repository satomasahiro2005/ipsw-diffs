## SiriCrossDeviceArbitration

> `/System/Library/PrivateFrameworks/SiriCrossDeviceArbitration.framework/SiriCrossDeviceArbitration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xaf0` | `—` | **`-0xaf0`** |
| `__DATA_DIRTY.__objc_data` | `0x1e0` | `0xcd0` | **`+0xaf0`** |
| `__TEXT.__text` | `0x2f744` | `0x2f8b8` | **`+0x174`** |
| `__TEXT.__oslogstring` | `0x54d8` | `0x55b0` | **`+0xd8`** |
| `__TEXT.__objc_methlist` | `0x30fc` | `0x310c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1e08` | `0x1e10` | **`+0x8`** |

### Other Changes

```diff

-3600.49.8.0.0
+3600.49.11.0.0

-  Functions: 1240
-  Symbols:   2313
-  CStrings:  1051
+  Functions: 1241
+  Symbols:   2314
+  CStrings:  1054
Symbols:
+ +[SCDAUtilities deviceClassCanMakeEmergencyCall:]
+ GCC_except_table1218
+ GCC_except_table1224
- GCC_except_table1216
- GCC_except_table1223
Functions:
~ -[SCDAGoodnessScoreEvaluator _bumpGoodnessScore:lastActivationTime:mediaPlaybackInterruptedTime:recentlyWonBySmallAmount:] : 672 -> 888
~ -[SCDACoordinator _startAdvertisingFromInTaskVoiceTrigger] : 408 -> 416
~ ___41-[SCDACoordinator _shouldHandleEmergency]_block_invoke : 36 -> 68
~ ___48-[SCDACoordinator heySiri:foundDevice:withInfo:]_block_invoke : 1616 -> 1720
+ +[SCDAUtilities deviceClassCanMakeEmergencyCall:]
CStrings:
+ "%s #scda Odeon: media-playback boost suppressed (TV-state tier covers playback)"
+ "%s #scda Odeon: media-playback boost suppressed (interrupted)"
+ "%s BTLE not emergency-capable, returning to NoActivity instead of waiting"
```
