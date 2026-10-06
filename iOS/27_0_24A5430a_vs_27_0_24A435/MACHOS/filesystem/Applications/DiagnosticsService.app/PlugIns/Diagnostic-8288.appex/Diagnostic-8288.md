## Diagnostic-8288

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8288.appex/Diagnostic-8288`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x2300` | `0x2340` | **`+0x40`** |
| `__TEXT.__text` | `0xe04c` | `0xe074` | **`+0x28`** |
| `__TEXT.__cstring` | `0x329d` | `0x32a5` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  393
+  CStrings:  395
Functions:
~ sub_10000e304 : 1692 -> 1732
CStrings:
+ "V63"
+ "V64"
```
