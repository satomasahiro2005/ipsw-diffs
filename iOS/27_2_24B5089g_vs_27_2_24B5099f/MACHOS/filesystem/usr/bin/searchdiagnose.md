## searchdiagnose

> `/usr/bin/searchdiagnose`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29650` | `0x29680` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x18a4` | `0x18cc` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x9c0` | `0x9c8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2465.1.3.0.0
+2465.1.7.0.0
Functions:
~ sub_100005198 : 124 -> 128
~ sub_100015408 -> sub_10001540c : 124 -> 128
~ sub_100015484 -> sub_10001548c : 108 -> 112
~ sub_100028f0c -> sub_100028f18 : 32 -> 68
```
