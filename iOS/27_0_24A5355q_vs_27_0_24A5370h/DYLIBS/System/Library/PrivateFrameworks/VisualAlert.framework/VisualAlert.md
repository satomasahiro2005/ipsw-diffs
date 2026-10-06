## VisualAlert

> `/System/Library/PrivateFrameworks/VisualAlert.framework/VisualAlert`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xad00` | `0xb134` | **`+0x434`** |
| `__TEXT.__cstring` | `0x1b06` | `0x1b99` | **`+0x93`** |
| `__AUTH_CONST.__cfstring` | `0x14e0` | `0x1540` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x188` | `0x1c0` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0xf58` | `0xf78` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x130` | `0x148` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x758` | `0x770` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x894` | `0x8a4` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x8c` | `0x90` | **`+0x4`** |

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0

-  Functions: 196
-  Symbols:   498
-  CStrings:  203
+  Functions: 197
+  Symbols:   503
+  CStrings:  206
Symbols:
+ -[AXVisualAlertManager _handleSilentModeChanged:]
+ GCC_except_table158
+ GCC_except_table164
+ GCC_except_table63
+ GCC_except_table66
+ GCC_except_table80
+ GCC_except_table99
+ _AVSystemController_SilentModeEnabledDidChangeNotification
+ _AVSystemController_SilentModeEnabledDidChangeNotificationParameter
+ _AVSystemController_SubscribeToNotificationsAttribute
+ _OBJC_IVAR_$_AXVisualAlertManager._isSilentMode
- GCC_except_table157
- GCC_except_table163
- GCC_except_table61
- GCC_except_table65
- GCC_except_table78
- GCC_except_table98
CStrings:
+ "Ending visual alert because silent mode was enabled"
+ "Failed to subscribe to AVSystemController silent mode notification: %@"
+ "Silent mode changed: %d"
```
