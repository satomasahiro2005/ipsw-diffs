## SCSharingReminders

> `/System/Library/PrivateFrameworks/SCSharingReminders.framework/SCSharingReminders`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb480` | `0xb458` | **`-0x28`** |

### Other Changes

```diff

-654.0.0.0.0
+653.0.1.0.0
Functions:
~ -[SCSharingReminderCache addSharingReminders:] : 524 -> 520
~ -[SCSharingReminderCache removeSharingReminders:wereDelivered:] : 976 -> 968
~ -[SCSharingReminderCache removeRemindersWithIdentifiers:] : 504 -> 500
~ -[SCSharingReminderCache remindersDueBy:] : 392 -> 388
~ -[SCSharingReminderCache ignoredIdentifiers] : 360 -> 356
~ -[SCSharingReminderManager handleSignals:completion:] : 832 -> 828
~ ___67+[SCUtils registerNeededNotificationsForManager:completionHandler:]_block_invoke : 348 -> 344
~ ___60-[SCLockdownService fetchWifiSyncIdentifiersWithCompletion:]_block_invoke : 428 -> 424
~ ___50-[SCLockdownService hostForIdentifier:completion:]_block_invoke : 640 -> 636
```
