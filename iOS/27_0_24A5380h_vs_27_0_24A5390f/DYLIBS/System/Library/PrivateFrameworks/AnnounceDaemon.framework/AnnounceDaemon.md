## AnnounceDaemon

> `/System/Library/PrivateFrameworks/AnnounceDaemon.framework/AnnounceDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x560dc` | `0x563f4` | **`+0x318`** |
| `__TEXT.__oslogstring` | `0x56d8` | `0x5758` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x370c` | `0x3734` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2778` | `0x2788` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x4f88` | `0x4f90` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x16c0` | `0x16c8` | **`+0x8`** |

### Other Changes

```diff

-329.0.0.0.0
+331.0.0.0.0

-  Functions: 1842
-  Symbols:   2853
-  CStrings:  795
+  Functions: 1845
+  Symbols:   2855
+  CStrings:  798
Symbols:
+ -[ANUserNotificationController _removeNotificationWithRequestID:]
+ -[ANUserNotificationController removeNotificationForAnnouncementsWithID:groupID:]
Functions:
+ -[ANUserNotificationController removeNotificationForAnnouncementsWithID:groupID:]
+ -[ANUserNotificationController _removeNotificationWithRequestID:]
~ -[ANAnnouncementManager _removeAnnouncementWithID:] : 580 -> 800
+ -[ANAnnouncementManager _removeAnnouncementWithID:].cold.1
CStrings:
+ "%@Removing user notification %@ in group %@"
+ "%@Trying to removing user notification null ID"
+ "Trying to remove notification with null group ID"
```
