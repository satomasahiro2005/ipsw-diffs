## CIVisionFilters

> `/System/Library/CoreImage/CIVisionFilters.cifilter/CIVisionFilters`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1de0` | `0x1fcc` | **`+0x1ec`** |
| `__TEXT.__auth_stubs` | `0x440` | `0x450` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x230` | `0x238` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1657.0.0.0.0
+1660.0.0.0.0

-  Symbols:   112
+  Symbols:   113
Symbols:
+ _objc_retain_x19
+ _objc_retain_x20
- _objc_retain_x21
Functions:
~ sub_2048 : 1152 -> 1644
```
