## GameTrampoline

> `/Applications/GameTrampoline.app/GameTrampoline`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x156c` | `0x15b8` | **`+0x4c`** |
| `__DATA.__data` | `0xd8` | `0xe0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x40` | `0x48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
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

-  Functions: 45
-  Symbols:   120
+  Functions: 46
+  Symbols:   121
Symbols:
+ _$s7SwiftUI9EmptyViewVAA0D0AAMc
+ _$s7SwiftUI9EmptyViewVN
- _$s7SwiftUI9EmptyViewVAA0D0AAWP
Functions:
~ sub_100001484 : 12 -> 4
+ sub_100001488
```
