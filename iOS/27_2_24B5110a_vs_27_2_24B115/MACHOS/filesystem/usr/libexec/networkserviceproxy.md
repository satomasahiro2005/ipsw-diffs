## networkserviceproxy

> `/usr/libexec/networkserviceproxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc20e8` | `0xc213c` | **`+0x54`** |
| `__TEXT.__oslogstring` | `0x11846` | `0x11885` | **`+0x3f`** |
| `__DATA_CONST.__cfstring` | `0x8ce0` | `0x8d00` | **`+0x20`** |
| `__TEXT.__cstring` | `0xdfe1` | `0xdfec` | **`+0xb`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  6336
+  CStrings:  6338
Functions:
~ sub_1000174fc : 3040 -> 3116
~ sub_10004b00c -> sub_10004b058 : 560 -> 568
CStrings:
+ "Ignoring proxy match dictionary, not applicable for internal"
+ "Ignoring proxy match dictionary, not applicable for public"
+ "Internal"
+ "Public"
- "Ignoring proxy match dictionary, not applicable for seed"
- "Seed"
```
