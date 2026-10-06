## com.apple.mobilemail.appremoval

> `/System/Library/AppRemovalServices/com.apple.mobilemail.appremoval.xpc/com.apple.mobilemail.appremoval`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x1e0` | `0x1d0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x100` | `0xf8` | **`-0x8`** |
| `__TEXT.__text` | `0x1068` | `0x1060` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3891.100.17.2.4
+3893.100.7.0.0

-  Symbols:   58
+  Symbols:   57
Symbols:
- _objc_retain_x20
Functions:
~ sub_100000f5c : 1044 -> 1040
~ sub_100001414 -> sub_100001410 : 964 -> 960
```
