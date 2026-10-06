## teslad

> `/usr/libexec/teslad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe9e8` | `0xea14` | **`+0x2c`** |
| `__DATA_CONST.__cfstring` | `0x1de0` | `0x1e00` | **`+0x20`** |
| `__TEXT.__cstring` | `0x13a4` | `0x13ba` | **`+0x16`** |
| `__DATA_CONST.__const` | `0x838` | `0x840` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-113.0.2.0.0
+113.2.5.0.0

-  CStrings:  970
+  CStrings:  971
Functions:
~ sub_100008f50 : 268 -> 312
CStrings:
+ "product_build_version"
```
