## MobileStorageMounter

> `/usr/libexec/MobileStorageMounter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c83c` | `0x1c858` | **`+0x1c`** |
| `__TEXT.__auth_stubs` | `0xe40` | `0xe30` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x730` | `0x728` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x198` | `0x1a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   296
+  Symbols:   295
Symbols:
- _objc_retain_x26
Functions:
~ sub_100011db0 : 2472 -> 2500
```
