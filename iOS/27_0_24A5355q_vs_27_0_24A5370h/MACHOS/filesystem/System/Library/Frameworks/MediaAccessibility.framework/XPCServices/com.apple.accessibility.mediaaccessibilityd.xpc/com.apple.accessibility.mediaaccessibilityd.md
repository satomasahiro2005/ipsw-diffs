## com.apple.accessibility.mediaaccessibilityd

> `/System/Library/Frameworks/MediaAccessibility.framework/XPCServices/com.apple.accessibility.mediaaccessibilityd.xpc/com.apple.accessibility.mediaaccessibilityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2cec` | `0x2f38` | **`+0x24c`** |
| `__TEXT.__cstring` | `0x48e` | `0x4e6` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x5ba` | `0x611` | **`+0x57`** |
| `__DATA_CONST.__cfstring` | `0x320` | `0x360` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x560` | `0x5a0` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x2c0` | `0x2e0` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-234.0.0.0.0
+236.0.0.0.0

-  Functions: 66
-  Symbols:   119
-  CStrings:  98
+  Functions: 69
+  Symbols:   123
+  CStrings:  104
Symbols:
+ _CFBooleanGetTypeID
+ _CFEqual
+ _CFNotificationCenterGetDarwinNotifyCenter
+ _CFNotificationCenterPostNotification
CStrings:
+ "MASystemIsMuted"
+ "SystemIsMuted invalid action"
+ "SystemIsMuted invalid payload"
+ "SystemIsMuted invalid value"
+ "com.apple.mediaaccessibility.systemIsMutedStatusDidChange"
+ "systemIsMuted"
```
