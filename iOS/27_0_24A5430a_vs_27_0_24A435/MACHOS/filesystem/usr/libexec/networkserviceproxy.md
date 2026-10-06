## networkserviceproxy

> `/usr/libexec/networkserviceproxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc1cd4` | `0xc1d28` | **`+0x54`** |
| `__TEXT.__oslogstring` | `0x1176c` | `0x117ab` | **`+0x3f`** |
| `__DATA_CONST.__cfstring` | `0x8c20` | `0x8c40` | **`+0x20`** |
| `__TEXT.__cstring` | `0xdf2a` | `0xdf35` | **`+0xb`** |

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

-  CStrings:  6326
+  CStrings:  6328
Functions:
~ sub_100017898 : 3040 -> 3116
~ sub_10004b3a8 -> sub_10004b3f4 : 560 -> 568
CStrings:
+ "Ignoring proxy match dictionary, not applicable for internal"
+ "Ignoring proxy match dictionary, not applicable for public"
+ "Internal"
+ "Public"
- "Ignoring proxy match dictionary, not applicable for seed"
- "Seed"
```
