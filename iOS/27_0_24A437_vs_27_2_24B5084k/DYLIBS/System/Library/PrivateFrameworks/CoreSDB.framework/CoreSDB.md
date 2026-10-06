## CoreSDB

> `/System/Library/PrivateFrameworks/CoreSDB.framework/CoreSDB`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe7d8` | `0xe240` | **`-0x598`** |
| `__DATA_CONST.__objc_selrefs` | `0x160` | `0xf8` | **`-0x68`** |
| `__TEXT.__cstring` | `0x135e` | `0x1316` | **`-0x48`** |
| `__AUTH_CONST.__cfstring` | `0xb20` | `0xae0` | **`-0x40`** |
| `__DATA.__data` | `0x40` | `—` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x159a` | `0x156f` | **`-0x2b`** |
| `__DATA_CONST.__const` | `0x130` | `0x108` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x588` | `0x560` | **`-0x28`** |
| `__TEXT.__gcc_except_tab` | `0x810` | `0x7f0` | **`-0x20`** |
| `__DATA.__bss` | `0x2c` | `0x20` | **`-0xc`** |
| `__DATA_DIRTY.__bss` | `0x5c` | `0x54` | **`-0x8`** |

### Other Changes

```diff

-211.100.3.0.0
+211.200.1.0.0

-  Functions: 364
-  Symbols:   425
-  CStrings:  292
+  Functions: 360
+  Symbols:   413
+  CStrings:  288
Symbols:
- _CC_MD5
- _CFNotificationCenterAddObserver
- _CFNotificationCenterGetDarwinNotifyCenter
- _CFNotificationCenterPostNotificationWithOptions
- _OBJC_CLASS_$_IMPair
- _OBJC_CLASS_$_NSMutableDictionary
- _OBJC_CLASS_$_NSMutableSet
- __dispatch_main_q
- _objc_alloc_init
- _objc_autoreleasePoolPop
- _objc_autoreleasePoolPush
- _objc_release_x22
CStrings:
- "%02x"
- "Calling reconnect block for identifier: %@"
- "com.apple.coresdb.mandatory_db_reconnect_required."
- "v32@?0@8@16^B24"
```
