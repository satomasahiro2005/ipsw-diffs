## FollowUp

> `/System/Library/Settings/FollowUp.settings/FollowUp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ab0` | `0x2b58` | **`+0xa8`** |
| `__DATA.__data` | `0x370` | `0x380` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xd8` | `0xe8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x150` | `0x158` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 62
+  Functions: 64
Functions:
~ sub_3a70 : 140 -> 84
+ sub_3ac4
+ sub_3bb4
```
