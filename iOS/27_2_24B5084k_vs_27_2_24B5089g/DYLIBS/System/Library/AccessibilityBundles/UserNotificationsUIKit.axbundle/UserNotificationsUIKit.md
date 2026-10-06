## UserNotificationsUIKit

> `/System/Library/AccessibilityBundles/UserNotificationsUIKit.axbundle/UserNotificationsUIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0xb9` | `0xfd` | **`+0x44`** |
| `__TEXT.__text` | `0xe088` | `0xe0a0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x288` | `0x274` | **`-0x14`** |
| `__TEXT.__unwind_info` | `0x5e0` | `0x5d8` | **`-0x8`** |
| `__TEXT.__cstring` | `0x2916` | `0x2919` | **`+0x3`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  Symbols:   1011
-  CStrings:  415
+  Symbols:   1010
+  CStrings:  416
Symbols:
+ -[NCNotificationListCellAccessibility _axNotificationContentLabel]
+ ___57-[NCNotificationListCellAccessibility accessibilityLabel]_block_invoke
- -[NCNotificationListCellAccessibility _accessibilityOpenAction]
- GCC_except_table192
- ___63-[NCNotificationListCellAccessibility _accessibilityOpenAction]_block_invoke
Functions:
~ +[NCNotificationListCellAccessibility _accessibilityPerformValidations:] : 1388 -> 1412
~ -[NCNotificationListCellAccessibility accessibilityActivate] : 556 -> 588
~ ___60-[NCNotificationListCellAccessibility accessibilityActivate]_block_invoke_2 : 16 -> 12
~ -[NCNotificationListCellAccessibility accessibilityLabel] : 988 -> 344
~ -[NCNotificationListCellAccessibility accessibilityIdentifier] -> ___57-[NCNotificationListCellAccessibility accessibilityLabel]_block_invoke : 120 -> 8
~ -[NCNotificationListCellAccessibility _accessibilityOpenAction] -> -[NCNotificationListCellAccessibility _axNotificationContentLabel] : 300 -> 988
~ ___63-[NCNotificationListCellAccessibility _accessibilityOpenAction]_block_invoke -> -[NCNotificationListCellAccessibility accessibilityIdentifier] : 80 -> 120
CStrings:
+ "Notification cell label empty on read; forcing static content setup"
+ "_staticContentProviderLoadingIfNecessary"
- "defaultActionForNotificationListCell:"
```
