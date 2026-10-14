## Batteries

> `/Applications/Batteries.app/Batteries`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c8` | `0x414` | **`+0x4c`** |
| `__DATA.__data` | `0xb8` | `0xc0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x10` | `0x18` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 19
-  Symbols:   57
+  Functions: 20
+  Symbols:   58
Symbols:
+ _$s7SwiftUI9EmptyViewVAA0D0AAMc
+ _$s7SwiftUI9EmptyViewVN
- _$s7SwiftUI9EmptyViewVAA0D0AAWP
Functions:
~ sub_100001044 : 12 -> 4
+ sub_100001048
```
