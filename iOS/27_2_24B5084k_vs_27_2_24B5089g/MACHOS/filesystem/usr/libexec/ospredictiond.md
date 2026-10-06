## ospredictiond

> `/usr/libexec/ospredictiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x694a8` | `0x69570` | **`+0xc8`** |
| `__TEXT.__oslogstring` | `0x7540` | `0x757d` | **`+0x3d`** |
| `__DATA_CONST.__const` | `0x11c0` | `0x11e8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1500` | `0x1510` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-288.40.3.0.0
+288.40.6.0.0

-  Functions: 3340
+  Functions: 3341

-  CStrings:  4814
+  CStrings:  4815
CStrings:
+ "Dropping non-Model inactivity prediction output, reason: %ld"
```
