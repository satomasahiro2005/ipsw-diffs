## Diagnostic-9006

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-9006.appex/Diagnostic-9006`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f10` | `0x3eec` | **`-0x24`** |
| `__DATA_CONST.__cfstring` | `0x520` | `0x500` | **`-0x20`** |
| `__TEXT.__cstring` | `0x3f2` | `0x3eb` | **`-0x7`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1291.0.0.502.1
+1307.0.16.0.0

-  CStrings:  487
+  CStrings:  486
Functions:
~ sub_1000018d0 : 5052 -> 5024
~ sub_100002c8c -> sub_100002c70 : 2172 -> 2164
CStrings:
- "faceid"
```
