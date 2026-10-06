## askpermissiond

> `/System/Library/PrivateFrameworks/AskPermission.framework/Support/askpermissiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e1a8` | `0x4e214` | **`+0x6c`** |
| `__TEXT.__oslogstring` | `0x55ce` | `0x560b` | **`+0x3d`** |
| `__DATA_CONST.__got` | `0x520` | `0x558` | **`+0x38`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-130.0.20.0.0
+130.0.23.0.0

-  CStrings:  2084
+  CStrings:  2085
Functions:
~ sub_100038688 : 2428 -> 2364
~ sub_100039ddc -> sub_100039d9c : 1108 -> 1280
CStrings:
+ "%{public}@: Request previously resolved; completing silently"
+ "04:11:43"
+ "Jun 27 2026"
- "00:35:14"
- "Jun 16 2026"
```
