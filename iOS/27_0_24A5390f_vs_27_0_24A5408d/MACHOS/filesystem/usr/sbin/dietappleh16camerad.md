## dietappleh16camerad

> `/usr/sbin/dietappleh16camerad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x371bc0` | `0x380bc0` | **`+0xf000`** |
| `__TEXT.__text` | `0x1ab20` | `0x1ae30` | **`+0x310`** |
| `__TEXT.__cstring` | `0x31d5` | `0x3287` | **`+0xb2`** |
| `__TEXT.__oslogstring` | `0x212f` | `0x21af` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0x1420` | `0x1460` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x9b28` | `0x9b68` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0xe90` | `0xed0` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x758` | `0x778` | **`+0x20`** |
| `__DATA.__bss` | `0x48` | `0x58` | **`+0x10`** |
| `__TEXT.__const` | `0x15b0` | `0x15c0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x530` | `0x540` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x140` | `0x148` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`

### Other Changes

```diff

-6.14.1.0.0
+6.18.0.0.0

-  Functions: 388
-  Symbols:   284
-  CStrings:  622
+  Functions: 393
+  Symbols:   289
+  CStrings:  629
Symbols:
+ _CFPreferencesGetAppBooleanValue
+ __xpc_type_bool
+ _dispatch_once
+ _xpc_bool_get_value
+ _xpc_connection_copy_entitlement_value
CStrings:
+ "/usr/local/share/firmware/isp/2226_01XX.dat"
+ "/usr/local/share/firmware/isp/2226_02XX.dat"
+ "6.18"
+ "Audit: XPC peer missing %{public}s (pid %{private}d) — would reject\n"
+ "EnforceClientEntitlement"
+ "Rejecting XPC peer missing %{public}s (pid %{private}d)\n"
+ "com.apple.appleh16camerad"
+ "com.apple.private.appleh16camerad.client"
- "6.14.1"
```
