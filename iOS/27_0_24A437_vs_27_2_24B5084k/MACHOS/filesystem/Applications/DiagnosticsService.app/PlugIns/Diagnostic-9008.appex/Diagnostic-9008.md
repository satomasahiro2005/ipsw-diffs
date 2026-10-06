## Diagnostic-9008

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9008.appex/Diagnostic-9008`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x1f20` | `0x1ec0` | **`-0x60`** |
| `__TEXT.__text` | `0xba3c` | `0xb9f0` | **`-0x4c`** |
| `__DATA_CONST.__cfstring` | `0x7e0` | `0x7a0` | **`-0x40`** |
| `__TEXT.__cstring` | `0x89d` | `0x87d` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x850` | `0x840` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x438` | `0x430` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1307.2.4.0.0
+1307.40.46.0.0

-  Symbols:   194
-  CStrings:  663
+  Symbols:   193
+  CStrings:  661
Symbols:
- _MGGetBoolAnswer
Functions:
~ sub_100005f98 : 352 -> 276
CStrings:
- "InDiagnosticsMode"
- "InternalBuild"
```
