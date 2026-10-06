## CoreDuetSync

> `/System/Library/PrivateFrameworks/CoreDuetSync.framework/CoreDuetSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6300` | `0x62dc` | **`-0x24`** |

### Other Changes

```diff

-1956.0.1.0.0
+1959.0.1.0.0
Functions:
~ -[_DKSync3Coordinator multiDeviceContextStoreDevices] : 848 -> 844
~ -[_DKSync3Coordinator handleContextChangedNotification:] : 1776 -> 1772
~ -[_DKSync3Coordinator(_DKSyncRemoteContextStorageDelegate) remoteContextStorage:archivedObjectsForKeyPaths:] : 468 -> 464
~ -[_DKSync3Coordinator(_CDRemoteUserContextServer) subscribeToContextValueChangeNotificationsWithRegistration:deviceIDs:error:] : 808 -> 804
~ -[_DKSync3Coordinator(_CDRemoteUserContextServer) unsubscribeFromContextValueChangeNotificationsWithRegistration:deviceIDs:error:] : 748 -> 744
~ -[_DKSync3Coordinator(_CDRemoteUserContextServer) _fetchPropertiesOfRemoteKeyPaths:handler:] : 1524 -> 1520
~ -[_DKSync3Coordinator(_CDRemoteUserContextServer) keyPathsByDeviceIDFromRemoteKeyPaths:] : 440 -> 436
~ -[_DKSync3Coordinator(_CDRemoteUserContextServer) archivedObjectsForKeyPaths:] : 1088 -> 1084
~ -[_DKSync3Coordinator(_CDRemoteUserContextServer) peersForContextStoreDeviceIDs:] : 528 -> 524
```
