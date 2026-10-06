## Diagnostic-8276

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8276.appex/Diagnostic-8276`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x3620` | `0x3660` | **`+0x40`** |
| `__TEXT.__text` | `0x1c1c4` | `0x1c1e8` | **`+0x24`** |
| `__TEXT.__cstring` | `0x4724` | `0x472c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  1079
+  CStrings:  1081
Functions:
~ sub_100011e9c : 1980 -> 2020
~ sub_100014e90 -> sub_100014eb8 : 11980 -> 11976
CStrings:
+ "V63"
+ "V64"
```
