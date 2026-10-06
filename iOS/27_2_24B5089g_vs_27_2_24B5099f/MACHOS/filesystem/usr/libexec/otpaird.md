## otpaird

> `/usr/libexec/otpaird`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3cb4` | `0x3ce4` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0xfa0` | `0xfc0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1762` | `0x176d` | **`+0xb`** |
| `__DATA.__objc_selrefs` | `0x620` | `0x628` | **`+0x8`** |
| `__TEXT.__const` | `0x70` | `0x68` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-62460.40.56.502.1
+62460.40.74.0.0

-  CStrings:  409
+  CStrings:  410
Functions:
~ sub_100000fd0 : 508 -> 556
CStrings:
+ "setFlowID:"
```
