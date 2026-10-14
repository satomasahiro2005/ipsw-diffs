## otpaird

> `/usr/libexec/otpaird`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0xfc0` | `0xfe0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x88c` | `0x8a8` | **`+0x1c`** |
| `__TEXT.__text` | `0x3ce4` | `0x3cf8` | **`+0x14`** |
| `__TEXT.__objc_methname` | `0x176d` | `0x177d` | **`+0x10`** |
| `__DATA.__objc_const` | `0xb40` | `0xb48` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x628` | `0x630` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-62460.40.74.0.0
+62460.40.78.0.0

-  Functions: 121
+  Functions: 122

-  CStrings:  410
+  CStrings:  411
Functions:
~ sub_100003c88 : 88 -> 8
+ sub_100003c90
CStrings:
+ "isHomeAccessory"
```
