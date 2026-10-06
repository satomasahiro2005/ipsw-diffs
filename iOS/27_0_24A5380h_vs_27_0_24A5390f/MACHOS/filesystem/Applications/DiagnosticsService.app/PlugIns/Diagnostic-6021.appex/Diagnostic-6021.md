## Diagnostic-6021

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-6021.appex/Diagnostic-6021`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e0a4` | `0x2e5a8` | **`+0x504`** |
| `__TEXT.__oslogstring` | `0x57b` | `0x5bb` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x140` | `0x160` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x12b0` | `0x12c0` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x79f` | `0x78f` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x960` | `0x968` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xcc0` | `0xcc8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1374.0.5.0.0
+1374.0.27.0.0

-  Functions: 981
+  Functions: 982

-  CStrings:  207
+  CStrings:  208
CStrings:
+ "Received a broadcast message id %u, replying to everything"
```
