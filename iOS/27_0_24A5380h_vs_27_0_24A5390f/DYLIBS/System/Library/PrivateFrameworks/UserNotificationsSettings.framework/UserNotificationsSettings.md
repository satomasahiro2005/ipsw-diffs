## UserNotificationsSettings

> `/System/Library/PrivateFrameworks/UserNotificationsSettings.framework/UserNotificationsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6d10` | `0x6f4c` | **`+0x23c`** |
| `__TEXT.__oslogstring` | `0x776` | `0x7b5` | **`+0x3f`** |
| `__AUTH_CONST.__objc_const` | `0x1b58` | `0x1b80` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xb60` | `0xb84` | **`+0x24`** |
| `__AUTH_CONST.__const` | `0x1a0` | `0x1c0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x578` | `0x588` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x88` | `0x8c` | **`+0x4`** |
| `__TEXT.__cstring` | `0x766` | `0x767` | **`+0x1`** |

### Other Changes

```diff

-713.0.0.0.0
+717.0.0.0.0

-  Functions: 235
-  Symbols:   515
-  CStrings:  96
+  Functions: 240
+  Symbols:   520
+  CStrings:  97
Symbols:
+ -[UNUserNotificationSettingsServiceConnection _queue_registerForSettingsUpdates]
+ -[UNUserNotificationSettingsServiceConnection registerForSettingsUpdates]
+ -[UNUserNotificationSettingsServiceConnection updateNotificationSourcesWithBundleIdentifiers:reply:]
+ -[UNUserNotificationSettingsServiceConnection updateNotificationSystemSettings:reply:]
+ GCC_except_table65
+ _OBJC_IVAR_$_UNUserNotificationSettingsServiceConnection._registeredForSettingsUpdates
+ ___73-[UNUserNotificationSettingsServiceConnection registerForSettingsUpdates]_block_invoke
+ ___80-[UNUserNotificationSettingsServiceConnection _queue_registerForSettingsUpdates]_block_invoke
- -[UNUserNotificationSettingsServiceConnection updateNotificationSourcesWithBundleIdentifiers:]
- -[UNUserNotificationSettingsServiceConnection updateNotificationSystemSettings:]
- GCC_except_table61
CStrings:
+ "Registering for settings updates failed with error: %{public}@"
```
