## FamilyControlsAgent

> `/System/Library/Frameworks/FamilyControls.framework/FamilyControlsAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5aac0` | `0x5ab58` | **`+0x98`** |
| `__TEXT.__oslogstring` | `0x353b` | `0x355b` | **`+0x20`** |
| `__TEXT.__const` | `0x1d08` | `0x1cf8` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1244.0.0.0.0
+1245.0.0.0.0

-  Functions: 1168
+  Functions: 1169
Functions:
~ sub_1000271e8 : 1568 -> 1440
+ sub_100030cd8
CStrings:
+ "User info did not contain any bundle IDs, or this was a placeholder uninstall"
- "User info did not contain any bundle IDs"
```
