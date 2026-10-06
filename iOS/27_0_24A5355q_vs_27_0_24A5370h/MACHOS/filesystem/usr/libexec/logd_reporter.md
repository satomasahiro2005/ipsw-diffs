## logd_reporter

> `/usr/libexec/logd_reporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e78` | `0x3e4c` | **`-0x2c`** |
| `__TEXT.__const` | `0xa8` | `0xb0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1952.0.0.0.0
+1958.0.0.0.1
Symbols:
+ _objc_retain_x27
- _objc_retain_x24
Functions:
~ sub_100001ad4 : 752 -> 748
~ sub_100002760 -> sub_10000275c : 5600 -> 5560
```
