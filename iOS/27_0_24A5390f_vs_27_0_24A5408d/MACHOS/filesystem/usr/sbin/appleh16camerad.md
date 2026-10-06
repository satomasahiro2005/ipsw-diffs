## appleh16camerad

> `/usr/sbin/appleh16camerad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x371da0` | `0x380da0` | **`+0xf000`** |
| `__TEXT.__text` | `0x844f0` | `0x84844` | **`+0x354`** |
| `__TEXT.__cstring` | `0x8afe` | `0x8b96` | **`+0x98`** |
| `__TEXT.__oslogstring` | `0x5e43` | `0x5ec3` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0x3360` | `0x33a0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0xb6d0` | `0xb710` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x1fb0` | `0x1fd0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x20e8` | `0x2104` | **`+0x1c`** |
| `__DATA_CONST.__auth_got` | `0xfe8` | `0xff8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1580` | `0x1590` | **`+0x10`** |
| `__DATA.__bss` | `0xa9` | `0xb8` | **`+0xf`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-6.14.1.0.0
+6.18.0.0.0

-  Functions: 1692
-  Symbols:   901
-  CStrings:  2029
+  Functions: 1698
+  Symbols:   903
+  CStrings:  2035
Symbols:
+ _CFPreferencesGetAppBooleanValue
+ _xpc_connection_copy_entitlement_value
CStrings:
+ "/usr/local/share/firmware/isp/2226_01XX.dat"
+ "/usr/local/share/firmware/isp/2226_02XX.dat"
+ "6.18"
+ "Audit: XPC peer missing %{public}s (pid %{private}d) — would reject\n"
+ "EnforceClientEntitlement"
+ "Rejecting XPC peer missing %{public}s (pid %{private}d)\n"
+ "com.apple.private.appleh16camerad.client"
- "6.14.1"
```
