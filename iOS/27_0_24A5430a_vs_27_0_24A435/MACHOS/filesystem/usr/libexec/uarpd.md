## uarpd

> `/usr/libexec/uarpd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x5580` | `0x56a0` | **`+0x120`** |
| `__TEXT.__text` | `0xa4190` | `0xa42ac` | **`+0x11c`** |
| `__TEXT.__cstring` | `0xb0dc` | `0xb112` | **`+0x36`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  5004
+  CStrings:  5013
Functions:
~ sub_1000297dc : 916 -> 1060
~ sub_100029b70 -> sub_100029c00 : 588 -> 728
CStrings:
+ "A3439"
+ "A3440"
+ "A3441"
+ "A3529"
+ "A3530"
+ "A3531"
+ "A3532"
+ "A3533"
+ "A3577"
```
