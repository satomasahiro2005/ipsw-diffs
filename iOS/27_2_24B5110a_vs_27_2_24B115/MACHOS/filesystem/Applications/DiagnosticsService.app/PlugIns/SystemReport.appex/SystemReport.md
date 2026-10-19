## SystemReport

> `/Applications/DiagnosticsService.app/PlugIns/SystemReport.appex/SystemReport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f188` | `0x1f1d8` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x56c0` | `0x5700` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3cc3` | `0x3cd4` | **`+0x11`** |
| `__TEXT.__unwind_info` | `0x6b0` | `0x6a8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  CStrings:  1735
+  CStrings:  1737
Functions:
~ sub_100017d38 : 16 -> 96
CStrings:
+ "Beta"
+ "ReleaseType"
```
