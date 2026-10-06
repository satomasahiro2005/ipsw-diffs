## UserNotifications

> `/System/Library/Frameworks/UserNotifications.framework/UserNotifications`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f710` | `0x2f830` | **`+0x120`** |
| `__AUTH_CONST.__objc_const` | `0xa7a8` | `0xa7d8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x37d8` | `0x37f8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c90` | `0x1ca8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xd78` | `0xd80` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x354` | `0x358` | **`+0x4`** |

### Other Changes

```diff

-717.0.0.0.0
+720.0.0.0.0

-  Functions: 1365
-  Symbols:   2322
+  Functions: 1369
+  Symbols:   2327
Symbols:
+ -[UNUserNotificationServiceConnection serverReconnectAttempts]
+ -[UNUserNotificationServiceConnection setHandlesNotificationResponses:forBundleIdentifier:]
+ -[UNUserNotificationServiceConnection setServerReconnectAttempts:]
+ GCC_except_table180
+ _OBJC_IVAR_$_UNUserNotificationServiceConnection._serverReconnectAttempts
+ ___91-[UNUserNotificationServiceConnection setHandlesNotificationResponses:forBundleIdentifier:]_block_invoke
- GCC_except_table178
```
