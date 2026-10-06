## AccessoryInteraction

> `/System/Library/PrivateFrameworks/AccessoryInteraction.framework/AccessoryInteraction`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x923f8` | `0x923f4` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-32.0.0.0.0
+33.0.0.0.0

-  Functions: 2660
-  Symbols:   3711
+  Functions: 2662
+  Symbols:   3713
Symbols:
+ _SPSimpleBeaconNameString
+ _SPUnknownBeaconNameString
CStrings:
+ "{\"msg%{public}.0s\":\"#durian #maint done\", \"item\":%{private, location:escape_only}@, \"name\":%{private, location:escape_only}@, \"reason\":%{public, location:escape_only}@, \"category\":%{public}d, \"left\":%{public}d, \"duration\":%{public}d}"
+ "{\"msg%{public}.0s\":\"#durian #maint list\", \"item\":%{private, location:escape_only}@, \"full\":%{private, location:escape_only}@, \"name\":%{private, location:escape_only}@, \"group\":%{private, location:escape_only}@, \"hele\":%{public}hhd}"
+ "{\"msg%{public}.0s\":\"#durian #maint skip\", \"item\":%{private, location:escape_only}@, \"full\":%{private, location:escape_only}@, \"name\":%{private, location:escape_only}@, \"ownership\":%{private}d}"
+ "{\"msg%{public}.0s\":\"#durian fetch unknown found\", \"item\":%{private, location:escape_only}@, \"name\":%{private, location:escape_only}@, \"isConnected\":%{public, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#durian fetchall found\", \"item\":%{private, location:escape_only}@, \"name\":%{private, location:escape_only}@, \"isConnected\":%{public, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#durian fetchall remove\", \"item\":%{private, location:escape_only}@, \"name\":%{private, location:escape_only}@, \"isConnected\":%{public, location:escape_only}s, \"isTaskQueueEmpty\":%{public, location:escape_only}s, \"pendingDisconnect\":%{public, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#durian removing unowned device\", \"item\":%{private, location:escape_only}@, \"name\":%{private, location:escape_only}@, \"isConnected\":%{public, location:escape_only}s, \"isTaskQueueEmpty\":%{public, location:escape_only}s, \"pendingDisconnect\":%{public, location:escape_only}s}"
- "{\"msg%{public}.0s\":\"#durian #maint done\", \"item\":%{private, location:escape_only}@, \"name\":%{public, location:escape_only}@, \"reason\":%{public, location:escape_only}@, \"category\":%{public}d, \"left\":%{public}d, \"duration\":%{public}d}"
- "{\"msg%{public}.0s\":\"#durian #maint list\", \"item\":%{private, location:escape_only}@, \"full\":%{private, location:escape_only}@, \"name\":%{public, location:escape_only}@, \"group\":%{private, location:escape_only}@, \"hele\":%{public}hhd}"
- "{\"msg%{public}.0s\":\"#durian #maint skip\", \"item\":%{private, location:escape_only}@, \"full\":%{private, location:escape_only}@, \"name\":%{public, location:escape_only}@, \"ownership\":%{private}d}"
- "{\"msg%{public}.0s\":\"#durian fetch unknown found\", \"item\":%{private, location:escape_only}@, \"name\":%{public, location:escape_only}@, \"isConnected\":%{public, location:escape_only}s}"
- "{\"msg%{public}.0s\":\"#durian fetchall found\", \"item\":%{private, location:escape_only}@, \"name\":%{public, location:escape_only}@, \"isConnected\":%{public, location:escape_only}s}"
- "{\"msg%{public}.0s\":\"#durian fetchall remove\", \"item\":%{private, location:escape_only}@, \"name\":%{public, location:escape_only}@, \"isConnected\":%{public, location:escape_only}s, \"isTaskQueueEmpty\":%{public, location:escape_only}s, \"pendingDisconnect\":%{public, location:escape_only}s}"
- "{\"msg%{public}.0s\":\"#durian removing unowned device\", \"item\":%{private, location:escape_only}@, \"name\":%{public, location:escape_only}@, \"isConnected\":%{public, location:escape_only}s, \"isTaskQueueEmpty\":%{public, location:escape_only}s, \"pendingDisconnect\":%{public, location:escape_only}s}"
```
