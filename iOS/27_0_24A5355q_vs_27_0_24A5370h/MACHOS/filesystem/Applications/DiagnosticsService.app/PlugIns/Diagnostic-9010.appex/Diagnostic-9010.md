## Diagnostic-9010

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9010.appex/Diagnostic-9010`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c8c` | `0x2e90` | **`+0x204`** |
| `__TEXT.__objc_stubs` | `0xc20` | `0xc60` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x2c` | `0x64` | **`+0x38`** |
| `__DATA_CONST.__cfstring` | `0x3e0` | `0x400` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x2d0` | `0x2f0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0xdaa` | `0xdc4` | **`+0x1a`** |
| `__DATA.__objc_selrefs` | `0x450` | `0x460` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x178` | `0x188` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xf0` | `0x100` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xc0` | `0xc8` | **`+0x8`** |
| `__TEXT.__cstring` | `0x36c` | `0x374` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1291.0.0.502.1
+1307.0.16.0.0

-  Functions: 60
-  Symbols:   93
-  CStrings:  262
+  Functions: 61
+  Symbols:   96
+  CStrings:  265
Symbols:
+ __dispatch_main_q
+ _dispatch_after
+ _dispatch_time
CStrings:
+ "RECOVER"
+ "mutableCopy"
+ "removeObject:"
```
