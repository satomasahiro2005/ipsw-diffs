## SystemWake

> `/System/Library/PrivateFrameworks/SystemWake.framework/SystemWake`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb81c` | `0xb814` | **`-0x8`** |

### Other Changes

```diff

-821.0.0.0.0
+825.0.0.0.0
Functions:
~ -[SWSystemSleepMonitor systemPowerChanged:notificationID:] : 1540 -> 1528
~ -[SWActiveSystemActivityRegistry notifyObserversWithBlock:] : 360 -> 356
~ -[SWSystemSleepMonitor setSleepSlate:forPowerManagementNotificationID:notificationTimestamp:] : 1180 -> 1192
~ -[SWSystemSleepMonitor observersOfSelector:performObserverBlock:completion:] : 1252 -> 1248
```
