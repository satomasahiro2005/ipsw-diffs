## EdgeLight

> `/System/Library/PrivateFrameworks/EdgeLight.framework/EdgeLight`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e64` | `0x4e80` | **`+0x1c`** |

### Other Changes

```diff

-546.0.0.0.0
+551.0.0.0.0
Functions:
~ -[PTEffectFaceLuxEstimation initWithMetalContext:] : 368 -> 364
~ -[PTEffectRingLightEstimation estimateScreenNits:] : 1420 -> 1416
~ -[PTEffectRingLightEstimation makeJSONFriendly:] : 724 -> 716
~ +[PTEffectUtil closestAspectRatio:] : 196 -> 200
~ _PTAEStatsThumbnailToRGB : 568 -> 600
~ _PTAEStatsThumbnailToLuma : 440 -> 448
~ _PTAEStatsLargestFaceRectIndex : 80 -> 72
~ _PTAEStatsContainsPoint : 84 -> 92
```
