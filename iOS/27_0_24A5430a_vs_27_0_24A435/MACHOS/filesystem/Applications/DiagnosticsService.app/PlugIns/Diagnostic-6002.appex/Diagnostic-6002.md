## Diagnostic-6002

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-6002.appex/Diagnostic-6002`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x37a0` | `0x37e0` | **`+0x40`** |
| `__TEXT.__text` | `0x1cfe0` | `0x1d004` | **`+0x24`** |
| `__TEXT.__cstring` | `0x49dd` | `0x49e5` | **`+0x8`** |

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

-  CStrings:  1106
+  CStrings:  1108
Functions:
~ sub_1000138f4 : 1980 -> 2020
~ sub_1000168e8 -> sub_100016910 : 11980 -> 11976
CStrings:
+ "V63"
+ "V64"
```
