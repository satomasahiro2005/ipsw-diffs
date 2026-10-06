## nesessionmanager

> `/usr/libexec/nesessionmanager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb6ce0` | `0xb6ef8` | **`+0x218`** |
| `__TEXT.__oslogstring` | `0x1138b` | `0x11449` | **`+0xbe`** |
| `__DATA_CONST.__got` | `0x798` | `0x7f0` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x1e48` | `0x1e88` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x8a20` | `0x8a60` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x2394` | `0x23c0` | **`+0x2c`** |
| `__TEXT.__objc_methname` | `0x9b2f` | `0x9b50` | **`+0x21`** |
| `__DATA.__objc_selrefs` | `0x2640` | `0x2650` | **`+0x10`** |
| `__TEXT.__cstring` | `0x5a86` | `0x5a93` | **`+0xd`** |
| `__TEXT.__unwind_info` | `0x1730` | `0x1738` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2315.0.0.0.2
+2322.0.0.0.1

-  Functions: 1958
-  Symbols:   711
-  CStrings:  4301
+  Functions: 1961
+  Symbols:   712
+  CStrings:  4307
Symbols:
+ _OBJC_CLASS_$_NEGuardProxyManager
CStrings:
+ "%@: Deregister last Filter Session calling stopGuardProxyManager: %@"
+ "%@: Started guard proxy."
+ "NESessionManager: starting guard proxy manager."
+ "NESessionManager: stopping guard proxy manager."
+ "missionCritical-9500"
+ "start"
+ "stopWithCompletionHandler:"
- "mc-9500"
```
