## UserNotificationsSettings

> `/System/Library/PrivateFrameworks/UserNotificationsSettings.framework/UserNotificationsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f4c` | `0x73fc` | **`+0x4b0`** |
| `__TEXT.__oslogstring` | `0x7b5` | `0x886` | **`+0xd1`** |
| `__DATA_CONST.__const` | `0x410` | `0x438` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xb84` | `0xba0` | **`+0x1c`** |
| `__AUTH_CONST.__objc_const` | `0x1b80` | `0x1b88` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x588` | `0x590` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2a0` | `0x2a8` | **`+0x8`** |

### Other Changes

```diff

-720.0.0.0.0
+720.2.6.0.0

-  Functions: 240
-  Symbols:   520
-  CStrings:  97
+  Functions: 246
+  Symbols:   525
+  CStrings:  100
Symbols:
+ -[UNNotificationSettingsCenter copyNotificationSettingsFromSourceIdentifier:toSourceIdentifier:withCompletionHandler:]
+ -[UNUserNotificationSettingsServiceConnection copyNotificationSettingsFromSourceIdentifier:toSourceIdentifier:withCompletionHandler:]
+ GCC_except_table69
+ ___133-[UNUserNotificationSettingsServiceConnection copyNotificationSettingsFromSourceIdentifier:toSourceIdentifier:withCompletionHandler:]_block_invoke
+ ___133-[UNUserNotificationSettingsServiceConnection copyNotificationSettingsFromSourceIdentifier:toSourceIdentifier:withCompletionHandler:]_block_invoke_2
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
- GCC_except_table65
CStrings:
+ "Copy notification settings (sync) failed with error: %{public}@"
+ "Copy notification settings from source %{public}@ to %{public}@ (sync)"
+ "Copy notification settings to %{public}@ completed with success: %{BOOL}d"
```
