## PairedSync

> `/System/Library/PrivateFrameworks/PairedSync.framework/PairedSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10994` | `0x10944` | **`-0x50`** |

### Other Changes

```text
Functions:
~ -[PSYInitialSyncStateObserver _queue_initializeIfNotInitialized] : 608 -> 604
~ -[PSYInitialSyncStateObserver _queue_updateSyncStates:notifyDelegateOfChanges:] : 1872 -> 1856
~ -[PSYSyncCoordinator syncSessionForOptions:supportsMigrationSync:] : 652 -> 648
~ +[PSYPlistFilter isPlistObject:] : 300 -> 296
~ +[PSYPlistFilter filteredPlistDictionary:] : 576 -> 572
~ +[PSYPlistFilter filteredPlistArray:] : 504 -> 500
~ +[PSYActivityInfo activityWithPlist:] : 1300 -> 1292
~ -[PSYSyncSession firstIncompleteActivity] : 284 -> 280
~ -[PSYSyncSession runningActivities] : 320 -> 316
~ -[PSYSyncSession incompleteActivities] : 320 -> 316
~ -[PSYSyncSession completedActivities] : 320 -> 316
~ -[PSYSyncSession completedActivityLabelsSet] : 352 -> 348
~ -[PSYSyncSession activityForService:] : 360 -> 356
~ -[PSYSyncSession syncSessionByUpdatingActivities:] : 304 -> 300
~ -[PSYSyncSession sessionProgress] : 388 -> 384
~ -[PSYSyncSession description] : 1036 -> 1032
```
