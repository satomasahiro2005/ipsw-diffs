## hybridsearchd

> `/usr/libexec/hybridsearchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x750` | `0x760` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x3b0` | `0x3b8` | **`+0x8`** |
| `__TEXT.__text` | `0x3868` | `0x3870` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-57.0.1.0.0
+59.0.1.0.0

-  - /System/Library/PrivateFrameworks/GenerativeSearch.framework/GenerativeSearch
+  - /System/Library/PrivateFrameworks/HybridSearch.framework/HybridSearch
Functions:
~ sub_1000034e4 -> sub_1000034dc : 124 -> 132
```
