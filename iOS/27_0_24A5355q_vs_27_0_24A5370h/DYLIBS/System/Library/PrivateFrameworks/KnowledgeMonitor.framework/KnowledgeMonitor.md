## KnowledgeMonitor

> `/System/Library/PrivateFrameworks/KnowledgeMonitor.framework/KnowledgeMonitor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e204` | `0x2e1a0` | **`-0x64`** |

### Other Changes

```text
Functions:
~ -[_DKApplicationMonitor(BMFrontBoardDisplayElement) donateElementsFromDisplayLayout:withContext:] : 2428 -> 2412
~ -[_DKAssertionsPreventingRestartMonitor areAssertionsPreventingRestart] : 1348 -> 1344
~ -[_DKNowPlayingMonitor _metadataFromInfo:outputDevices:] : 1776 -> 1772
~ ___25-[_DKMotionMonitor start]_block_invoke : 280 -> 276
~ ___26-[_DKMotionMonitor update]_block_invoke_2 : 1000 -> 996
~ ___51-[_DKComplicationMonitor fetchActiveComplications:]_block_invoke : 652 -> 648
~ -[_DKDoNotDisturbMonitor stateService:didReceiveDoNotDisturbStateUpdate:] : 1008 -> 1004
~ +[_DKNowPlayingMonitor _bmEventWithDKEvent:outputDevices:biomeEventMetadata:excludeFromSuggestions:] : 2136 -> 2132
~ -[_DKUserIsFirstBacklightOnAfterWakeupMonitor didQualifyingScreenLockEndInEligibilityPeriod] : 828 -> 824
~ +[_DKAppInstallMonitor _metadataFromProxy:didInstall:] : 716 -> 712
~ ___58-[_DKAppInstallMonitor _applicationsDidChange:didInstall:]_block_invoke : 1568 -> 1560
~ -[_DKBluetoothMonitor updateCurrentBatteryLevels] : 680 -> 672
~ ___32-[_DKBluetoothMonitor loadState]_block_invoke : 2144 -> 2132
~ -[_DKNetworkQualityMonitor predictionTimelineFromNOIPredictions:] : 672 -> 668
~ -[_DKNetworkQualityMonitor didStartTrackingNOI:] : 648 -> 644
~ -[_DKNetworkQualityMonitor didStopTrackingNOI:] : 428 -> 424
~ -[_DKNetworkQualityMonitor didStopTrackingAllNOIs:] : 308 -> 304
~ ___28-[_DKCalendarMonitor update]_block_invoke : 532 -> 528
```
