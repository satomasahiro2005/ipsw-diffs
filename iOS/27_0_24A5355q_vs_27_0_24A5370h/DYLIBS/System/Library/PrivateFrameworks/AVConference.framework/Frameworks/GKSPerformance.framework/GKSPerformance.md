## GKSPerformance

> `/System/Library/PrivateFrameworks/AVConference.framework/Frameworks/GKSPerformance.framework/GKSPerformance`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xad84` | `0xad48` | **`-0x3c`** |

### Other Changes

```diff

-2235.48.1.0.0
+2235.52.1.11.1
Functions:
~ -[AWDHistogram reduceFrequencyByFactor:] : 56 -> 52
~ -[AWDHistogram print] : 228 -> 220
~ -[AWDHistogram newArray] : 144 -> 140
~ -[AWDHistogram array] : 132 -> 128
~ -[AWDStats generateAggregatedCallStats:] : 2580 -> 2576
~ -[AWDStats reset] : 500 -> 496
~ -[AWDStats printHistograms] : 288 -> 284
~ -[AWDStats updateLocalPrimaryInterface:] : 160 -> 152
~ -[AudioTierHistogram newReport] : 692 -> 684
~ -[AWDAdaptor computeMean:] : 368 -> 364
~ -[AWDAdaptor computeMax:] : 352 -> 348
~ -[AWDAdaptor allocHistogramForValues:withBinBoundaries:] : 912 -> 908
~ -[AWDAdaptor transformHistogram:ofSize:] : 140 -> 136
~ -[AWDAdaptor sendAnalyticsAudioDistortionStatisticsEvent:] : 948 -> 960
~ -[AWDAdaptor sendAnalyticsAudioDistortionSummaryEvent:] : 1516 -> 1512
~ -[AWDAdaptor newDistortionCounters:] : 528 -> 524
```
