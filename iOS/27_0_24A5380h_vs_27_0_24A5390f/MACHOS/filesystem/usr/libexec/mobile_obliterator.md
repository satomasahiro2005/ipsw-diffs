## mobile_obliterator

> `/usr/libexec/mobile_obliterator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x20e0` | `0x2140` | **`+0x60`** |
| `__TEXT.__cstring` | `0xacf5` | `0xad42` | **`+0x4d`** |
| `__TEXT.__text` | `0x1b77c` | `0x1b76c` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-400.0.0.0.0
+402.0.0.0.0

-  CStrings:  1404
+  CStrings:  1407
Functions:
~ sub_1000025b4 : 29504 -> 29488
CStrings:
+ "MobileActivation/dcrt"
+ "removeExcept /dcrt.der/ /sdcrt.der/"
+ "removeExcept /log/"
```
