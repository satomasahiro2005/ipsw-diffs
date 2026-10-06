## PowerExceptions_ClientFramework

> `/System/Library/PrivateFrameworks/PowerExceptions_ClientFramework.framework/PowerExceptions_ClientFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10814` | `0x10850` | **`+0x3c`** |
| `__AUTH_CONST.__objc_const` | `0xf58` | `0xf88` | **`+0x30`** |
| `__TEXT.__cstring` | `0x471` | `0x4a1` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xd40` | `0xd58` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x8a0` | `0x8b0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x6a8` | `0x6b0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x8c` | `0x90` | **`+0x4`** |

### Other Changes

```diff

-145.0.0.0.0
+163.0.0.0.0

-  Functions: 423
-  Symbols:   616
-  CStrings:  185
+  Functions: 425
+  Symbols:   620
+  CStrings:  186
Symbols:
+ -[PENotificationManager notificationQueue]
+ -[PENotificationManager setNotificationQueue:]
+ _OBJC_IVAR_$_PENotificationManager._notificationQueue
+ _dispatch_queue_attr_make_with_qos_class
CStrings:
+ "5"
+ "com.apple.PowerExceptions.PENotificationManager"
- "4"
```
