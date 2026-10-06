## demod_helper

> `/usr/libexec/demod_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x6487` | `0x6465` | **`-0x22`** |
| `__DATA_CONST.__cfstring` | `0x50e0` | `0x50c0` | **`-0x20`** |
| `__TEXT.__text` | `0x2e81c` | `0x2e80c` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1871.0.29.0.0
+1871.0.42.0.0

-  CStrings:  2175
+  CStrings:  2174
Functions:
~ sub_10000742c : 668 -> 652
CStrings:
- "/private/var/mobile/Library/Biome"
```
