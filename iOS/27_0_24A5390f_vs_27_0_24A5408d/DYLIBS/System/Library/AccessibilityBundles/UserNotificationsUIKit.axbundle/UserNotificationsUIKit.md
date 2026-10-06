## UserNotificationsUIKit

> `/System/Library/AccessibilityBundles/UserNotificationsUIKit.axbundle/UserNotificationsUIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdf5c` | `0xe0e8` | **`+0x18c`** |
| `__TEXT.__cstring` | `0x28d5` | `0x2916` | **`+0x41`** |
| `__AUTH_CONST.__cfstring` | `0x2ec0` | `0x2ee0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x274` | `0x288` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0x5c8` | `0x5d8` | **`+0x10`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 421
-  Symbols:   1009
-  CStrings:  414
+  Functions: 423
+  Symbols:   1012
+  CStrings:  415
Symbols:
+ GCC_except_table190
+ GCC_except_table192
+ GCC_except_table199
+ GCC_except_table236
+ GCC_except_table238
+ GCC_except_table317
+ GCC_except_table320
+ GCC_except_table323
+ GCC_except_table343
+ GCC_except_table348
+ GCC_except_table356
+ GCC_except_table358
+ GCC_except_table380
+ ___65-[NCNotificationListCellAccessibility axCustomActionsForActions:]_block_invoke_3
+ ___68-[NCNotificationViewControllerAccessibility _axAnnounceNotification]_block_invoke
- GCC_except_table189
- GCC_except_table191
- GCC_except_table198
- GCC_except_table235
- GCC_except_table237
- GCC_except_table316
- GCC_except_table319
- GCC_except_table322
- GCC_except_table342
- GCC_except_table347
- GCC_except_table355
- GCC_except_table357
Functions:
~ +[NCNotificationListCellAccessibility _accessibilityPerformValidations:] : 1380 -> 1388
~ ___65-[NCNotificationListCellAccessibility axCustomActionsForActions:]_block_invoke_2 : 132 -> 236
+ ___65-[NCNotificationListCellAccessibility axCustomActionsForActions:]_block_invoke_3
~ -[NCNotificationViewControllerAccessibility _axAnnounceNotification] : 440 -> 592
+ ___68-[NCNotificationViewControllerAccessibility _axAnnounceNotification]_block_invoke
CStrings:
+ "Notification announcement finish never arrived; releasing banner"
```
