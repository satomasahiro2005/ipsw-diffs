## logd

> `/usr/libexec/logd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x276a4` | `0x2798c` | **`+0x2e8`** |
| `__TEXT.__cstring` | `0x4a0a` | `0x4b02` | **`+0xf8`** |
| `__TEXT.__auth_stubs` | `0x1bc0` | `0x1bd0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xde8` | `0xdf0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x698` | `0x6a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__os_assumes_log`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1966.2.1.0.0
+1966.40.15.502.2

-  Functions: 515
-  Symbols:   500
-  CStrings:  633
+  Functions: 516
+  Symbols:   501
+  CStrings:  641
Symbols:
+ _getenv_copy_np
CStrings:
+ "%s.%s"
+ "Client attempted realtime logging connection but was not trusted. PID: %d"
+ "LIBTRACE_DEBUG_LOGD_SERVICE"
+ "admin"
+ "com.apple.private.logging.realtime"
+ "events"
+ "failed to check in to %s (0x%x)"
+ "logd_session_service_name: per-session service name too long"
+ "realtime"
+ "unprivileged logd: LIBTRACE_DEBUG_LOGD_SERVICE not set"
- "failed to allocate mach port"
- "failed to checkin to com.apple.logd"
```
