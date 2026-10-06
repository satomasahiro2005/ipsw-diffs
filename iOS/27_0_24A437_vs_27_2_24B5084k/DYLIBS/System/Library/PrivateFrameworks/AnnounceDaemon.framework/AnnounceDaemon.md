## AnnounceDaemon

> `/System/Library/PrivateFrameworks/AnnounceDaemon.framework/AnnounceDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x563dc` | `0x564c4` | **`+0xe8`** |
| `__TEXT.__oslogstring` | `0x5758` | `0x57b8` | **`+0x60`** |

### Other Changes

```diff

-331.0.0.0.0
+336.0.0.1.1

-  CStrings:  798
+  CStrings:  800
Functions:
~ -[ANAnnouncementCoordinator(ANAnnouncementManagement_Internal) updateLastPlayedDateForAnnouncement:endpointID:] : 172 -> 292
~ -[ANAnnouncementCoordinator(ANAnnouncementManagement_Internal) updatePlayingState:forAnnouncement:endpointID:] : 188 -> 300
CStrings:
+ "Skip updating last played date for endpoint %@"
+ "Skip updating playing state for endpoint %@"
```
