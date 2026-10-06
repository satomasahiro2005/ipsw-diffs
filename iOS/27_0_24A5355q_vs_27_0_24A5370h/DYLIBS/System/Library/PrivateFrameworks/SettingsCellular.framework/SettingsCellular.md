## SettingsCellular

> `/System/Library/PrivateFrameworks/SettingsCellular.framework/SettingsCellular`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa614` | `0xa5d8` | **`-0x3c`** |

### Other Changes

```diff

-737.0.0.0.0
+744.0.0.0.0
Functions:
~ -[PSCellularManagementCache managedCellDataAppBundleIDs] : 416 -> 412
~ -[PSDataUsageStatisticsCache bundleIDsForAppType:] : 772 -> 768
~ -[PSDataUsageStatisticsCache displayNamesForBundleIDs:appType:] : 904 -> 900
~ -[PSDataUsageStatisticsCache hotspotClientIDsForPeriod:] : 844 -> 840
~ -[PSDataUsageStatisticsCache displayNameForHotspotClientID:] : 724 -> 720
~ -[PSDataUsageStatisticsCache usageForHotspotClientID:inPeriod:] : 896 -> 892
~ -[PSDataUsageStatisticsCache usageForBundleID:inPeriod:] : 1388 -> 1368
~ -[PSSimStatusCache fetchSimStatusHasCacheLock:] : 700 -> 696
~ -[PSSimStatusCache fetchSimHardwareInfoHasCacheLock:] : 740 -> 736
~ -[PSSimStatusCache updateIsAnySimPresent] : 624 -> 620
~ +[SettingsCellularSharedUtils logSpecifiers:origin:] : 528 -> 524
```
