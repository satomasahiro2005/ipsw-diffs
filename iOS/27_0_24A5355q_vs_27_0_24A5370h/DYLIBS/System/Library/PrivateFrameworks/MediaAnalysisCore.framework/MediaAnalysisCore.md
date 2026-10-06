## MediaAnalysisCore

> `/System/Library/PrivateFrameworks/MediaAnalysisCore.framework/MediaAnalysisCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7c14` | `0x7be8` | **`-0x2c`** |

### Other Changes

```diff

-435.60.2.11.2
+435.65.2.0.0
Functions:
~ -[AVURLAsset(MediaAnalysisCore) vcp_firstEnabledTrackWithMediaType:] : 764 -> 760
~ -[MADPreprocessingNode childNodeWithVideoProcessor:] : 380 -> 376
~ -[MADSubsamplingNode childNodeWithPixelFormat:outputWidth:outputHeight:cropRect:] : 732 -> 728
~ -[MADVideoProcessorNode cancel] : 300 -> 296
~ ___35-[MADVideoProcessorNode pushInput:]_block_invoke : 552 -> 548
~ -[MADVideoProcessorNode finalizeProcessing] : 324 -> 320
~ -[MADVideoProcessorSession nodeWithSubsamplingOptions:] : 792 -> 788
~ ___46-[MADVideoProcessorSession hasVideoProcessor:]_block_invoke : 276 -> 272
~ -[MADVideoProcessorSession pushSampleBuffer:] : 508 -> 504
~ -[MADVideoProcessorSession finalizeProcessing] : 412 -> 408
~ -[MADVideoProcessorSession cancel] : 320 -> 316
```
