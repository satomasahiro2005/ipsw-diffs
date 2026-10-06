## Eyedropper

> `/System/Library/PrivateFrameworks/Eyedropper.framework/Eyedropper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6740` | `0x66c4` | **`-0x7c`** |

### Other Changes

```diff

-  Symbols:   495
+  Symbols:   496
Symbols:
+ _objc_retain_x24
Functions:
~ -[EDAppDelegate performOnAllWindows:] : 408 -> 404
~ -[EDAppDelegate _enumerateRemoteClientsUsingBlock:] : 364 -> 360
~ -[EDAppDelegate _updateDynamicRangeSamplingModesFromClientSettings] : 336 -> 332
~ ___49-[EDAppDelegate beginShowingEyeDropper:settings:]_block_invoke : 888 -> 876
~ ___40-[EDAppDelegate cancelShowingEyeDropper]_block_invoke : 300 -> 296
~ ___32-[EDAppDelegate floatEyeDropper]_block_invoke : 804 -> 800
~ -[EDAppDelegate dismissEyedropper] : 844 -> 832
~ -[EDLensView updateLensViewWithEvent:] : 332 -> 328
~ -[EDColorAnalyzer removeSimilarColors:minDistance:] : 888 -> 880
~ -[EDColorAnalyzer kmeansColorsForColors:clusters:] : 2116 -> 2096
~ -[EDColorAnalyzer colorsInSurface:offset:clipToCircle:clipedToRect:] : 908 -> 864
~ -[EDColorAnalyzer colorAtCenterOfHDRSurface:SDRSurface:offset:] : 632 -> 628
```
