## Diagnostic-8340

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8340.appex/Diagnostic-8340`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x308c` | `0x309c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xf0` | `0xf8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1307.0.16.0.0
+1307.0.26.502.1
Symbols:
+ _initializeIOServiceConnectionWithNameAndType
- _initializeIOServiceConnectionWithName
Functions:
~ _initializeIOServiceConnectionWithName -> _initializeIOServiceConnectionWithNameAndType : 184 -> 196
~ sub_1000034ac -> sub_1000034b8 : 108 -> 112
```
