## AirPlaySupport

> `/System/Library/PrivateFrameworks/AirPlaySupport.framework/AirPlaySupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x33f56` | `0x33d5f` | **`-0x1f7`** |
| `__TEXT.__text` | `0xcc820` | `0xcc6ec` | **`-0x134`** |

### Other Changes

```diff

-1005.8.1.0.0
+1005.12.1.0.0

-  Functions: 2627
-  Symbols:   4973
-  CStrings:  4484
+  Functions: 2628
+  Symbols:   4974
+  CStrings:  4463
Symbols:
+ GCC_except_table2596
+ GCC_except_table2600
+ _APSAudioHoseMetricCollectorSetSenderRTMetrics
+ _FigSignalErrorAtGM
- GCC_except_table2595
- GCC_except_table2598
- _FigSignalErrorAt3
Functions:
~ _APSSharedRingBuffer_CreateWithBufferAndState : 820 -> 652
~ _APSSharedRingBuffer_Create : 1032 -> 980
~ _protocolDriverSenderTCP_Flush : 268 -> 244
~ _protocolDriverSenderTCP_FlushFromTime : 380 -> 356
~ _APSAudioFormatDescriptionCreateWithAudioFormatIndex : 816 -> 776
~ _APSAudioFormatDescriptionListCreate : 456 -> 432
~ _APSAPAPExtensionConvertLoudnessInfoDictLoudnessParametersToBBuf : 692 -> 536
~ _APSAudioHoseMetricCollectorCreate : 624 -> 628
~ _APSAudioHoseMetricCollectorDeregisterHose : 1460 -> 1476
+ _APSAudioHoseMetricCollectorSetSenderRTMetrics
~ __APSAudioHoseMetricCollectorFinalize : 200 -> 212
CStrings:
+ "%s signalled err=%d at <>:%d"
+ "APSAudioHoseMetricCollectorSetSenderRTMetrics"
- "%s%s%s signalled err=%d (%s) (%s) at %s:%d"
- "-108"
- "-6705"
- "-877"
- "-878"
- "-879"
- "-880"
- "APSAPAPExtensionLoudnessInfoUtils.c"
- "APSAudioFormatDescription.c"
- "APSAudioFormatDescriptionList.c"
- "APSSharedRingBuffer.c"
- "Could not allocate APSAudioFormatDescription"
- "Could not allocate APSAudioFormatDescriptionList"
- "Failed to create bufferMemObject"
- "Failed to create stateMemObject"
- "bufferMemory region maps to NULL"
- "bufferMemorySize is zero"
- "kCMBaseObjectError_AllocationFailed"
- "loudness key missing"
- "sample peak key missing"
- "stateMemObject maps to NULL"
- "stateMemoryLength < sizeof(RingState)"
- "true peak key missing"
```
