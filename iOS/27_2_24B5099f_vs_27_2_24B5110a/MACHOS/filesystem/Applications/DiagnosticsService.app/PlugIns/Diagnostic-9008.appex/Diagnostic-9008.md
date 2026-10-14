## Diagnostic-9008

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9008.appex/Diagnostic-9008`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb9f0` | `0xba44` | **`+0x54`** |
| `__DATA.__data` | `0x400` | `0x408` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1e0` | `0x1e8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x320` | `0x328` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1307.40.64.0.0
+1307.40.66.0.0

-  Functions: 301
+  Functions: 302
Functions:
~ sub_10000b9e0 : 140 -> 84
+ sub_10000ba34
```
