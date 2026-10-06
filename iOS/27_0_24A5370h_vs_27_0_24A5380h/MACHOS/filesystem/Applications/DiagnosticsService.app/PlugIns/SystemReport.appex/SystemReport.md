## SystemReport

> `/Applications/DiagnosticsService.app/PlugIns/SystemReport.appex/SystemReport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d6dc` | `0x1d7ac` | **`+0xd0`** |
| `__DATA_CONST.__cfstring` | `0x5000` | `0x5020` | **`+0x20`** |
| `__DATA.__bss` | `0x98` | `0x88` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x258` | `0x260` | **`+0x8`** |
| `__TEXT.__cstring` | `0x3874` | `0x387b` | **`+0x7`** |

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
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1369.0.0.0.0
+1374.0.5.0.0

-  Functions: 615
+  Functions: 614

-  CStrings:  1652
+  CStrings:  1653
CStrings:
+ "PackID"
```
