## networkserviceproxy

> `/usr/libexec/networkserviceproxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc1d28` | `0xc1da4` | **`+0x7c`** |
| `__TEXT.__oslogstring` | `0x117ab` | `0x1176c` | **`-0x3f`** |
| `__TEXT.__gcc_except_tab` | `0x3858` | `0x388c` | **`+0x34`** |
| `__TEXT.__cstring` | `0xdf35` | `0xdf5b` | **`+0x26`** |
| `__DATA_CONST.__objc_intobj` | `0x6d8` | `0x6f0` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-985.0.0.0.0
+990.0.0.0.0

-  CStrings:  6328
+  CStrings:  6327
Functions:
~ sub_100017898 : 3116 -> 3040
~ sub_10004b3f4 -> sub_10004b3a8 : 568 -> 560
~ sub_100054f8c -> sub_100054f38 : 1736 -> 1788
~ sub_1000ad3c0 -> sub_1000ad3a0 : 5668 -> 5824
CStrings:
+ "Ignoring proxy match dictionary, not applicable for seed"
+ "Seed"
+ "https://mask-api.icloud.com/v6_2/fetchConfigFile"
- "Ignoring proxy match dictionary, not applicable for internal"
- "Ignoring proxy match dictionary, not applicable for public"
- "Internal"
- "Public"
```
