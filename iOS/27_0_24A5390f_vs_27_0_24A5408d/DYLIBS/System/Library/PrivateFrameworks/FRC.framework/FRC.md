## FRC

> `/System/Library/PrivateFrameworks/FRC.framework/FRC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x400fc` | `0x40244` | **`+0x148`** |
| `__TEXT.__cstring` | `0x65fb` | `0x660c` | **`+0x11`** |

### Other Changes

```diff

-258.0.0.0.0
+259.0.0.0.0

-  CStrings:  842
+  CStrings:  843
Functions:
~ sub_261c436ac -> sub_2617656ac : 64 -> 68
~ -[DualOpticalFlowE5 opticalFlowFirstFrame:secondFrame:flowForward:flowBackward:reUseFlow:] : 408 -> 476
~ _FRCGetUsageFromSize : 1164 -> 1188
~ -[FRCFrameInterpolator interpolateBetweenFirstFrame:secondFrame:timeScales:outputSize:outputPixelFormat:withError:] : 2528 -> 2592
~ _getConfigurationName : 792 -> 804
~ -[OpticalFlow opticalFlowFirstFrame:secondFrame:flow:callback:] : 316 -> 360
~ -[OpticalFlow opticalFlowFirstFrame:secondFrame:flowForward:flowBackward:reUseFlow:] : 348 -> 416
~ -[NeuFlow opticalFlowFirstFrame:secondFrame:flow:callback:] : 836 -> 880
CStrings:
+ "landscape256x192"
```
