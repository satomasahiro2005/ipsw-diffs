## NetworkStatistics

> `/System/Library/PrivateFrameworks/NetworkStatistics.framework/NetworkStatistics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ff88` | `0x2ff28` | **`-0x60`** |

### Other Changes

```diff

-278.0.0.0.0
+279.0.0.0.0
Functions:
~ ___35-[NWAppStateHandler trackerForPid:]_block_invoke : 304 -> 300
~ -[NWStatsEntityMapperStaticAssignment init] : 428 -> 424
~ -[NWStatisticsManager handleReadEvent] : 320 -> 332
~ -[NWStatsManager _setThresholds:] : 696 -> 692
~ -[NWStatsManager _handleMessage:length:] : 2796 -> 2792
~ -[NWStatsManager _migrationCleanupTimerFired] : 968 -> 952
~ -[NWStatsTCPSnapshot TCPState] : 236 -> 224
~ -[NWStatisticsManager handleMessage:length:] : 1760 -> 1756
~ -[NWStatisticsManager removeSourceInternal:isFromClient:] : 464 -> 460
~ -[NWSTCPSnapshot TCPState] : 232 -> 220
~ _maskLeadingBitsCount : 220 -> 228
~ _xprint_sockaddr : 696 -> 692
~ ___NStatGetLog_block_invoke : 896 -> 892
~ -[NWStatisticsManager handleSystemInformationCounts:] : 480 -> 492
~ -[NWStatsEntityMapCache pruneCache] : 704 -> 692
~ -[NWStatsEntityMapCache setEntry:forUUID:] : 580 -> 576
~ -[NWStatsEntityMapCache stateDictionary] : 428 -> 424
~ -[NWStatsTargetSelector initWithMultipleSelections:] : 320 -> 316
~ -[NWStatsManager _handleCounts:] : 444 -> 440
~ -[NWStatsManager _noteInterfaceSrcRef:forInterface:threshold:] : 672 -> 668
~ -[NWStatsManager _setThreshold:onInterface:] : 640 -> 636
~ -[NWStatsManager dumpState] : 1888 -> 1876
~ +[NWStatsManager dumpKernelMetrics:] : 708 -> 704
~ -[NWStatsManager _evictMigrationGroupIfNeeded] : 852 -> 844
~ -[NWStatsQUICSnapshot QUICState] : 228 -> 216
~ -[NWStatsSnapshot extensionDictionaries] : 388 -> 384
~ -[NWStatsUDPSnapshot isConnected] : 8 -> 28
```
