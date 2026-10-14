## UserNotificationsUIKit

> `/System/Library/AccessibilityBundles/UserNotificationsUIKit.axbundle/UserNotificationsUIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe0a0` | `0xe58c` | **`+0x4ec`** |
| `__TEXT.__cstring` | `0x2919` | `0x29a9` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x2ee0` | `0x2f60` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0xfd` | `0x176` | **`+0x79`** |
| `__DATA_CONST.__const` | `0x488` | `0x4d8` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x8b0` | `0x8e8` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x274` | `0x2a0` | **`+0x2c`** |
| `__TEXT.__unwind_info` | `0x5d8` | `0x5f8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1354` | `0x136c` | **`+0x18`** |

### Other Changes

```diff

-3050.3.5.0.0
+3050.3.8.0.0

-  Functions: 423
-  Symbols:   1010
-  CStrings:  416
+  Functions: 429
+  Symbols:   1021
+  CStrings:  421
Symbols:
+ -[NCNotificationListCellAccessibility _axActionPresentsOptionsMenu:]
+ -[NCNotificationListCellAccessibility _axPresentOptionsMenuForAction:]
+ GCC_except_table180
+ GCC_except_table185
+ GCC_except_table196
+ GCC_except_table205
+ GCC_except_table242
+ GCC_except_table244
+ GCC_except_table326
+ GCC_except_table329
+ GCC_except_table349
+ GCC_except_table354
+ GCC_except_table362
+ GCC_except_table364
+ GCC_except_table386
+ ___65-[NCNotificationListCellAccessibility axCustomActionsForActions:]_block_invoke_4
+ ___65-[NCNotificationListCellAccessibility axCustomActionsForActions:]_block_invoke_5
+ ___70-[NCNotificationListCellAccessibility _axPresentOptionsMenuForAction:]_block_invoke
+ ___70-[NCNotificationListCellAccessibility _axPresentOptionsMenuForAction:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40s_e37_B16?0"UIAccessibilityCustomAction"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40w_e5_v8?0lw40l8s32l8
+ __os_log_error_impl
- GCC_except_table190
- GCC_except_table199
- GCC_except_table236
- GCC_except_table238
- GCC_except_table317
- GCC_except_table320
- GCC_except_table343
- GCC_except_table348
- GCC_except_table356
- GCC_except_table358
- GCC_except_table380
CStrings:
+ "VoiceOver could not locate the notification options menu button after revealing supplementary actions; hiding them again"
+ "_nc_menuDescriptor"
+ "hideActionButtonsAnimated:fastAnimation:completion:"
+ "revealSupplementaryActionsWithCompletion:"
+ "senderForActionWithIdentifier:"
```
