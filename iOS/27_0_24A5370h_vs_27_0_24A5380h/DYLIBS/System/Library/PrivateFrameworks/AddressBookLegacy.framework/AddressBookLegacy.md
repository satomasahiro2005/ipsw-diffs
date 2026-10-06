## AddressBookLegacy

> `/System/Library/PrivateFrameworks/AddressBookLegacy.framework/AddressBookLegacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7787c` | `0x77c20` | **`+0x3a4`** |
| `__AUTH.__objc_data` | `0xaf0` | `0xbe0` | **`+0xf0`** |
| `__DATA_DIRTY.__objc_data` | `0x500` | `0x410` | **`-0xf0`** |
| `__TEXT.__oslogstring` | `0x2d38` | `0x2d7f` | **`+0x47`** |
| `__DATA_DIRTY.__data` | `0x128` | `0x168` | **`+0x40`** |
| `__TEXT.__cstring` | `0x26e78` | `0x26eb5` | **`+0x3d`** |
| `__AUTH_CONST.__const` | `0xee0` | `0xf00` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2838` | `0x2858` | **`+0x20`** |
| `__DATA.__bss` | `0x3a8` | `0x3c0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1138` | `0x1148` | **`+0x10`** |
| `__TEXT.__const` | `0x361` | `0x371` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1a78` | `0x1a88` | **`+0x10`** |
| `__DATA.__common` | `0x8` | `0x4` | **`-0x4`** |

### Other Changes

```diff

-12874.100.1.0.0
+12875.100.2.0.0

-  Functions: 2616
-  Symbols:   4424
-  CStrings:  2539
+  Functions: 2620
+  Symbols:   4434
+  CStrings:  2542
Symbols:
+ ____distributedNotificationDebouncerQueue_block_invoke
+ ____scheduleDistributedNotificationWindow_block_invoke
+ ___block_descriptor_56_e5_v8?0l
+ ___distributedNotificationSerial
+ __distributedNotificationDebouncerQueue.onceToken
+ __distributedNotificationDebouncerQueue.queue
+ __handleDistributedNotificationEvent
+ __scheduleDistributedNotificationWindow
+ _dispatch_after
+ _dispatch_time
+ _distributedNotificationWindowInitial
- _OUTLINED_FUNCTION_21
CStrings:
+ "com.apple.AddressBookLegacy.DistributedNotificationDebouncer"
+ "debouncer %04llx posted %{public}@"
+ "debouncer %04llx request %{public}@"
```
