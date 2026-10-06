## hangreporter

> `/usr/libexec/hangreporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x260d0` | `0x26120` | **`+0x50`** |
| `__TEXT.__const` | `0x2b0` | `0x2e0` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x3460` | `0x3480` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xc7c` | `0xc94` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x5c82` | `0x5c9a` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1298` | `0x12a0` | **`+0x8`** |

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

-  CStrings:  2136
+  CStrings:  2137
Functions:
~ sub_100002c54 : 12160 -> 12208
~ sub_10000baa4 -> sub_10000bad4 : 7656 -> 7684
~ sub_1000116d4 -> sub_100011720 : 16 -> 12
~ sub_1000116e4 -> sub_10001172c : 12 -> 36
~ sub_1000116f0 -> sub_100011750 : 36 -> 16
~ sub_100024a5c -> sub_100024aa8 : 488 -> 492
CStrings:
+ "setDisplayKernelFrames:"
```
