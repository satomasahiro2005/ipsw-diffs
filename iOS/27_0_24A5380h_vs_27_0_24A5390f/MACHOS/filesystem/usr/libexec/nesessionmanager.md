## nesessionmanager

> `/usr/libexec/nesessionmanager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x11449` | `0x1138b` | **`-0xbe`** |
| `__TEXT.__text` | `0xb6ef8` | `0xb6e3c` | **`-0xbc`** |
| `__DATA_CONST.__const` | `0x1e88` | `0x1e48` | **`-0x40`** |
| `__TEXT.__objc_stubs` | `0x8a60` | `0x8a20` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0x23c0` | `0x2394` | **`-0x2c`** |
| `__TEXT.__objc_methname` | `0x9b50` | `0x9b2f` | **`-0x21`** |
| `__DATA.__objc_selrefs` | `0x2650` | `0x2640` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x7f0` | `0x7e8` | **`-0x8`** |

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
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2322.0.0.0.1
+2331.0.0.0.1

-  Functions: 1961
-  Symbols:   712
-  CStrings:  4307
+  Functions: 1960
+  Symbols:   711
+  CStrings:  4301
Symbols:
- _OBJC_CLASS_$_NEGuardProxyManager
CStrings:
- "%@: Deregister last Filter Session calling stopGuardProxyManager: %@"
- "%@: Started guard proxy."
- "NESessionManager: starting guard proxy manager."
- "NESessionManager: stopping guard proxy manager."
- "start"
- "stopWithCompletionHandler:"
```
