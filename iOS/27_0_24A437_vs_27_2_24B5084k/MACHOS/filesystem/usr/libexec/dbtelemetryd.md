## dbtelemetryd

> `/usr/libexec/dbtelemetryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x61a4` | `0x6834` | **`+0x690`** |
| `__TEXT.__cstring` | `0x167` | `0x1d1` | **`+0x6a`** |
| `__TEXT.__auth_stubs` | `0xa10` | `0xa30` | **`+0x20`** |
| `__DATA.__data` | `0x200` | `0x210` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x510` | `0x520` | **`+0x10`** |
| `__TEXT.__const` | `0x2f2` | `0x302` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-6.0.0.0.0
+7.0.0.0.0

-  Functions: 115
-  Symbols:   263
-  CStrings:  47
+  Functions: 116
+  Symbols:   265
+  CStrings:  49
Symbols:
+ _objc_retain
+ _os_variant_has_internal_content
CStrings:
+ "com.apple.libsqlite3.firstparty.sqltelemetry.sqlerrors.fullinternal"
+ "com.apple.sqlite"
```
