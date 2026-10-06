## DASDaemon

> `/System/Library/PrivateFrameworks/DASDaemon.framework/DASDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8ce8` | `0x8cac` | **`-0x3c`** |

### Other Changes

```diff

-2463.0.0.502.1
+2467.0.9.0.0

-  Symbols:   263
+  Symbols:   265
Symbols:
+ _objc_retain_x27
+ _objc_retain_x28
Functions:
~ -[_DASLogExtractor getScheduledBlocksOfMessages:forActivity:] : 640 -> 636
~ -[_DASLogExtractor getScheduledBlocksOfBARMessages:forApplication:] : 608 -> 604
~ -[_DASLogExtractor getMessagesBeforeRunning:forActivity:] : 596 -> 592
~ -[_DASLogExtractor getAllBARActivityNames:] : 560 -> 556
~ -[_DASLogExtractor getAllPushLaunchActivityNames:] : 696 -> 712
~ -[_DASLogExtractor getMessagesWhenAppBackgroundSwitch:forApplication:switchTo:] : 432 -> 428
~ -[_DASLogExtractor getMessagesForAllBARTasks:] : 668 -> 656
~ -[_DASLogExtractor getMessagesForBARLifecycle:forApplication:queryStatus:taskType:] : 672 -> 668
~ -[_DASLogExtractor getActivityStartBeforeDate:forActivity:] : 516 -> 512
~ -[_DASLogExtractor didActivityRun:forActivity:] : 304 -> 300
~ -[_DASLogExtractor getMessagesAfterRunning:forActivity:] : 520 -> 516
~ -[_DASLogExtractor didActivityFinish:forActivity:] : 368 -> 364
~ -[_DASLogExtractor didActivityFinish:forBARActivity:] : 372 -> 368
~ -[_DASLogExtractor getMessagesActivityFinish:forActivity:isCompleted:] : 412 -> 408
~ -[_DASLogExtractor didBARFinish:forApplication:] : 304 -> 300
~ -[_DASLogExtractor summarizeRuntimeOverMessages:forActivity:] : 888 -> 884
~ -[_DASLogExtractor getPolicyDenialReasonsFromMessage:] : 696 -> 692
~ -[_DASLogExtractor getpolicyToIntervals:] : 2380 -> 2356
~ -[_DASLogExtractor descriptionOfPolicyToIntervalsMap:] : 1208 -> 1200
~ -[_DASLogExtractor getIncompatibilityReasons:forActivity:] : 1048 -> 1044
~ -[_DASLogExtractor descriptionOfIncompatibilityDenials:] : 536 -> 532
~ -[_DASLogExtractor getInstancesOfHigherThreshold:forActivity:] : 864 -> 852
~ -[_DASLogExtractor descriptionOfHigherThresholds:] : 512 -> 508
~ -[_DASLogExtractor summarizePolicyDenialsOverMessages:maxDuration:] : 1008 -> 1004
~ -[_DASLogExtractor getSummaryFromLogs:forActivity:detail:] : 1732 -> 1740
~ -[_DASLogExtractor getBARSummaryFromLogs:forApplication:detail:] : 4480 -> 4528
~ -[_DASLogExtractor addConditionToHistory:fromMessage:atTimestamp:compactRepresentation:] : 864 -> 860
~ -[_DASLogExtractor sysConditionsLog:startDate:endDate:] : 1836 -> 1840
```
