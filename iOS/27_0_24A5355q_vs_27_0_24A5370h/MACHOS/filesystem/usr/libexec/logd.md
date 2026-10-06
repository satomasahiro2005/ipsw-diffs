## logd

> `/usr/libexec/logd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26fc4` | `0x2737c` | **`+0x3b8`** |
| `__TEXT.__cstring` | `0x47e1` | `0x4895` | **`+0xb4`** |
| `__TEXT.__auth_stubs` | `0x1b60` | `0x1b90` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2398` | `0x2378` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0xdb8` | `0xdd0` | **`+0x18`** |
| `__TEXT.__const` | `0x2b8` | `0x2a8` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x688` | `0x690` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__os_assumes_log`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1952.0.0.0.0
+1958.0.0.0.1

-  Functions: 515
-  Symbols:   493
-  CStrings:  616
+  Functions: 514
+  Symbols:   496
+  CStrings:  624
Symbols:
+ _bind
+ _socket
+ _umask
CStrings:
+ "/dev"
+ "/var/run"
+ "/var/run/syslog"
+ "Binding to debug socket: %s"
+ "Failed bind to syslog socket: %s"
+ "Failed to open syslog socket: %s"
+ "Failed unlink syslog socket: %s"
+ "LIBTRACE_DEBUG_UNPRIVILEGED"
+ "failed to allocate mach port"
- "Failed to open syslog socket: %d"
```
