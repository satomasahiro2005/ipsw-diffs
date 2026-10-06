## Diagnostic-8201

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8201.appex/Diagnostic-8201`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x223d0` | `0x223e0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff
Symbols:
+ _initializeIOServiceConnectionWithNameAndType
- _initializeIOServiceConnectionWithName
Functions:
~ _initializeIOServiceConnectionWithName -> _initializeIOServiceConnectionWithNameAndType : 184 -> 196
~ sub_100017f48 -> sub_100017f54 : 108 -> 112
```
