## powerexperienced

> `/usr/libexec/powerexperienced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bf34` | `0x1c0a8` | **`+0x174`** |
| `__DATA_CONST.__cfstring` | `0x14a0` | `0x14e0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x13bb` | `0x13d1` | **`+0x16`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  1489
+  CStrings:  1491
Functions:
~ sub_100002b4c : 2192 -> 2332
~ sub_100008fc0 -> sub_10000904c : 940 -> 1120
~ sub_100010f04 -> sub_100011044 : 484 -> 536
CStrings:
+ "HomeAcc"
+ "HomeAccessory"
```
