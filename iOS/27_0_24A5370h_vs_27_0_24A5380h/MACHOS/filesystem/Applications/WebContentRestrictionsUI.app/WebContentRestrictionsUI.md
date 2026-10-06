## WebContentRestrictionsUI

> `/Applications/WebContentRestrictionsUI.app/WebContentRestrictionsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x69fc` | `0x6a60` | **`+0x64`** |
| `__TEXT.__objc_methname` | `0xe1a` | `0xe47` | **`+0x2d`** |
| `__TEXT.__objc_stubs` | `0xfc0` | `0xfe0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x4f8` | `0x500` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x20c` | `0x214` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-64.0.0.0.0
+67.0.0.0.0

-  CStrings:  280
+  CStrings:  281
Functions:
~ sub_100001854 : 180 -> 224
~ sub_100002cb4 -> sub_100002ce0 : 4500 -> 4556
CStrings:
+ "prominentGlassButtonConfiguration"
+ "systemBackgroundColor"
- "clearColor"
```
