## UserNotificationsServer

> `/System/Library/PrivateFrameworks/UserNotificationsServer.framework/UserNotificationsServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b988` | `0x3c354` | **`+0x9cc`** |
| `__AUTH_CONST.__objc_const` | `0x5dd0` | `0x5f28` | **`+0x158`** |
| `__DATA_CONST.__const` | `0x1210` | `0x12b0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1628` | `0x16b8` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x2454` | `0x24d4` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x2bb0` | `0x2c08` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x120` | `0x170` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xdc8` | `0xdf8` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x228` | `0x23c` | **`+0x14`** |
| `__TEXT.__gcc_except_tab` | `0x660` | `0x654` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x980` | `0x988` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x100` | `0x108` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x88` | `0x90` | **`+0x8`** |

### Other Changes

```diff

-713.0.0.0.0
+717.0.0.0.0

-  Functions: 1119
-  Symbols:   2000
-  CStrings:  524
+  Functions: 1138
+  Symbols:   2035
+  CStrings:  527
Symbols:
+ -[UNSSettingsUpdateCoalescer .cxx_destruct]
+ -[UNSSettingsUpdateCoalescer _queue_ackRestoringOnFailure:]
+ -[UNSSettingsUpdateCoalescer _queue_drain]
+ -[UNSSettingsUpdateCoalescer connection]
+ -[UNSSettingsUpdateCoalescer enqueueSourceIdentifiers:]
+ -[UNSSettingsUpdateCoalescer enqueueSystemSettings:]
+ -[UNSSettingsUpdateCoalescer initWithConnection:]
+ -[UNSUserNotificationServerSettingsConnectionListener registerForSettingsUpdates]
+ GCC_except_table23
+ GCC_except_table24
+ _OBJC_CLASS_$_UNSSettingsUpdateCoalescer
+ _OBJC_IVAR_$_UNSSettingsUpdateCoalescer._connection
+ _OBJC_IVAR_$_UNSSettingsUpdateCoalescer._inFlight
+ _OBJC_IVAR_$_UNSSettingsUpdateCoalescer._pendingSourceIdentifiers
+ _OBJC_IVAR_$_UNSSettingsUpdateCoalescer._pendingSystemSettings
+ _OBJC_IVAR_$_UNSSettingsUpdateCoalescer._queue
+ _OBJC_IVAR_$_UNSUserNotificationServerSettingsConnectionListener._clients
+ _OBJC_METACLASS_$_UNSSettingsUpdateCoalescer
+ __OBJC_$_INSTANCE_METHODS_UNSSettingsUpdateCoalescer
+ __OBJC_$_INSTANCE_VARIABLES_UNSSettingsUpdateCoalescer
+ __OBJC_$_PROP_LIST_UNSSettingsUpdateCoalescer
+ __OBJC_CLASS_RO_$_UNSSettingsUpdateCoalescer
+ __OBJC_METACLASS_RO_$_UNSSettingsUpdateCoalescer
+ ___42-[UNSSettingsUpdateCoalescer _queue_drain]_block_invoke
+ ___42-[UNSSettingsUpdateCoalescer _queue_drain]_block_invoke_2
+ ___42-[UNSSettingsUpdateCoalescer _queue_drain]_block_invoke_3
+ ___42-[UNSSettingsUpdateCoalescer _queue_drain]_block_invoke_4
+ ___42-[UNSSettingsUpdateCoalescer _queue_drain]_block_invoke_5
+ ___42-[UNSSettingsUpdateCoalescer _queue_drain]_block_invoke_6
+ ___52-[UNSSettingsUpdateCoalescer enqueueSystemSettings:]_block_invoke
+ ___55-[UNSSettingsUpdateCoalescer enqueueSourceIdentifiers:]_block_invoke
+ ___59-[UNSSettingsUpdateCoalescer _queue_ackRestoringOnFailure:]_block_invoke
+ ___59-[UNSSettingsUpdateCoalescer _queue_ackRestoringOnFailure:]_block_invoke_2
+ ___90-[UNSUserNotificationServerSettingsConnectionListener _handleClientConnectionInvalidated:]_block_invoke
+ ___block_descriptor_40_e8_32s_e36_v16?0"UNSSettingsUpdateCoalescer"8ls32l8
+ ___block_descriptor_40_e8_32s_e43_B32?0"UNSSettingsUpdateCoalescer"8Q16^B24ls32l8
+ ___block_descriptor_57_e8_32bs40r48w_e5_v8?0lr40l8w48l8s32l8
+ ___block_descriptor_64_e8_32s40bs48r56w_e8_v12?0B8ls32l8r48l8w56l8s40l8
- GCC_except_table20
- GCC_except_table22
- _OBJC_IVAR_$_UNSUserNotificationServerSettingsConnectionListener._connections
CStrings:
+ "B32@?0@\"UNSSettingsUpdateCoalescer\"8Q16^B24"
+ "com.apple.usernotifications.UNSSettingsUpdateCoalescer"
+ "v16@?0@\"UNSSettingsUpdateCoalescer\"8"
```
