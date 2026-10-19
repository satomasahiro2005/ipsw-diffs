## hangreporter

> `/usr/libexec/hangreporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26bac` | `0x26be4` | **`+0x38`** |
| `__TEXT.__const` | `0x2b0` | `0x2e0` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x3460` | `0x3480` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xcc4` | `0xcdc` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x5c96` | `0x5cae` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x12a0` | `0x12a8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  2141
+  CStrings:  2142
Functions:
~ sub_100002c54 : 12832 -> 12860
~ sub_10000bd44 -> sub_10000bd60 : 7656 -> 7684
CStrings:
+ "setDisplayKernelFrames:"
```
