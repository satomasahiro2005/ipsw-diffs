## UserNotificationsUIKit

> `/System/Library/AccessibilityBundles/UserNotificationsUIKit.axbundle/UserNotificationsUIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xde68` | `0xdf5c` | **`+0xf4`** |
| `__TEXT.__cstring` | `0x28ae` | `0x28d5` | **`+0x27`** |
| `__AUTH_CONST.__cfstring` | `0x2ea0` | `0x2ec0` | **`+0x20`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 420
-  Symbols:   1008
-  CStrings:  413
+  Functions: 421
+  Symbols:   1009
+  CStrings:  414
Symbols:
+ GCC_except_table235
+ GCC_except_table237
+ GCC_except_table316
+ GCC_except_table319
+ GCC_except_table322
+ GCC_except_table342
+ GCC_except_table347
+ GCC_except_table355
+ GCC_except_table357
+ ___60-[NCNotificationListCellAccessibility accessibilityActivate]_block_invoke_3
- GCC_except_table234
- GCC_except_table236
- GCC_except_table315
- GCC_except_table318
- GCC_except_table321
- GCC_except_table341
- GCC_except_table346
- GCC_except_table354
- GCC_except_table356
Functions:
~ +[NCNotificationListCellAccessibility _accessibilityPerformValidations:] : 1300 -> 1380
~ -[NCNotificationListCellAccessibility accessibilityActivate] : 416 -> 556
~ ___60-[NCNotificationListCellAccessibility accessibilityActivate]_block_invoke_2 : 12 -> 16
+ ___60-[NCNotificationListCellAccessibility accessibilityActivate]_block_invoke_3
CStrings:
+ "handleTapOnNotificationViewController:"
```
