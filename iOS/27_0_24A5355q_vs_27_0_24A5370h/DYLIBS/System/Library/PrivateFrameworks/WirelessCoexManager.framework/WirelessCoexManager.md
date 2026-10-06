## WirelessCoexManager

> `/System/Library/PrivateFrameworks/WirelessCoexManager.framework/WirelessCoexManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa950` | `0xa854` | **`-0xfc`** |

### Other Changes

```diff

-1930.3.0.0.0
+1933.0.0.0.0
Functions:
~ -[WRM_UCMInterface registerClient:queue:] : 780 -> 772
~ -[WRM_UCMInterface setAWDLEnabled:] : 468 -> 460
~ -[WRMBasebandMetricsInterface getWiFiBWEstimationMetrics:] : 320 -> 312
~ -[WRMBasebandMetricsInterface getNRPhyMetrics:] : 320 -> 312
~ -[WRMBasebandMetricsInterface getCellularDataMetrics:] : 320 -> 312
~ -[WRMBasebandMetricsInterface getQSHMetrics:] : 428 -> 420
~ ___53-[WRM_iRATInterface subscribeBtLqmScoreNotification:]_block_invoke : 340 -> 332
~ ___56-[WRM_iRATInterface getVoiceLqmValue:completionHandler:]_block_invoke : 576 -> 568
~ ___58-[WRM_iRATInterface subscribeProximityLinkRecommendation:]_block_invoke : 816 -> 808
~ ___50-[WRM_iRATInterface getLinkRecommendationMetrics:]_block_invoke : 400 -> 392
~ ___67-[WRM_iRATInterface getProximityLinkRecommendation:recommendation:]_block_invoke : 488 -> 480
~ ___58-[WRM_iRATInterface statusUpdateAppLinkPreference:status:]_block_invoke : 356 -> 348
~ ___47-[WRM_iRATInterface getStreamingInfo:linkType:]_block_invoke : 620 -> 612
~ ___54-[WRM_iRATInterface getMLPredictedThroughput:options:]_block_invoke : 756 -> 748
~ ___50-[WRM_iRATInterface assertCommCenterBaseBandMode:]_block_invoke : 340 -> 332
~ ___41-[WRM_iRATInterface setTelephonyEnabled:]_block_invoke : 340 -> 332
~ ___47-[WRM_iRATInterface subscribeAppType:observer:]_block_invoke : 660 -> 652
~ ___56-[WRM_iRATInterface subscribeMultipleAppTypes:observer:]_block_invoke : 1144 -> 1124
~ ___64-[WRM_iRATInterface statusUpdateAppType:linkType:serviceStatus:]_block_invoke : 456 -> 448
~ ___66-[WRM_iRATInterface _expediteBBAssertionBGAppActive_sync:handler:]_block_invoke : 692 -> 684
~ ___63-[WRMClientInterface registerClient:queue:notificationHandler:]_block_invoke : 568 -> 560
~ ___58-[WRM_UCMInterface subscribeBtConnectedLinksNotification:]_block_invoke : 336 -> 328
~ -[WRM_UCMInterface setCriticalAirPlayEnabled:estimatedDuration:criticalityPercentage:] : 500 -> 492
~ -[WRM_UCMInterface setNANEnabled:] : 476 -> 468
~ -[WRM_UCMInterface setNANRealTimeEnabled:] : 472 -> 464
~ -[WRM_UCMInterface getInstantLoad] : 688 -> 680
~ -[WRM_UCMInterface stopTimer] : 776 -> 768
~ -[WRM_UCMInterface startTimer:] : 820 -> 812
~ ___58-[WRM_UCMInterface getWirelessFrequencyBandUpdatesForMIC:]_block_invoke : 532 -> 524
~ -[WRM_UCMInterface getWirelessULFrequencyBandUpdates:] : 1068 -> 1060
```
