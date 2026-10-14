## GAXApp

> `/Applications/GAXApp.app/GAXApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x444` | `0x490` | **`+0x4c`** |
| `__DATA.__data` | `0xb8` | `0xc0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x90` | `0x98` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1067.3.3.0.0
+1067.3.4.0.0

-  Functions: 20
-  Symbols:   57
+  Functions: 21
+  Symbols:   58
Symbols:
+ _$s7SwiftUI4TextVAA4ViewAAMc
+ _$s7SwiftUI4TextVN
- _$s7SwiftUI4TextVAA4ViewAAWP
Functions:
~ sub_100001054 : 12 -> 4
+ sub_100001058
```
