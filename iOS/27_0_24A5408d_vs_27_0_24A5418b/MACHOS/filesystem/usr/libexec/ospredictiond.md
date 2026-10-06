## ospredictiond

> `/usr/libexec/ospredictiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68734` | `0x68834` | **`+0x100`** |
| `__TEXT.__objc_stubs` | `0x9860` | `0x98c0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x153ba` | `0x153ff` | **`+0x45`** |
| `__TEXT.__objc_methlist` | `0x9350` | `0x9388` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x1160` | `0x1180` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x3d60` | `0x3d78` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x14d0` | `0x14e8` | **`+0x18`** |
| `__DATA.__bss` | `0x1f0` | `0x200` | **`+0x10`** |
| `__TEXT.__cstring` | `0x55a7` | `0x55b4` | **`+0xd`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-286.0.0.0.0
+286.2.1.0.0

-  Functions: 3324
+  Functions: 3330

-  CStrings:  4789
+  CStrings:  4793
CStrings:
+ "ambientLight"
+ "perDisplayAmbientLightLevel"
+ "systemAmbientLightLevel"
+ "usePerDisplayLux"
```
