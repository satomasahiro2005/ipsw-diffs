## UserNotificationsSettings

> `/System/Library/PrivateFrameworks/UserNotificationsSettings.framework/UserNotificationsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6d24` | `0x6d10` | **`-0x14`** |

### Other Changes

```diff

-703.0.0.0.0
+708.0.0.0.0
Functions:
~ -[UNNotificationSystemSettings _stringForScheduledDeliveryTimes:] : 504 -> 500
~ ___102-[UNNotificationSettingsCenter settingsServiceConnection:didUpdateNotificationSourcesWithIdentifiers:]_block_invoke : 296 -> 292
~ ___94-[UNNotificationSettingsCenter settingsServiceConnection:didUpdateNotificationSystemSettings:]_block_invoke : 296 -> 292
~ -[UNUserNotificationSettingsServiceConnection updateNotificationSourcesWithBundleIdentifiers:] : 272 -> 268
~ -[UNUserNotificationSettingsServiceConnection updateNotificationSystemSettings:] : 272 -> 268
```
