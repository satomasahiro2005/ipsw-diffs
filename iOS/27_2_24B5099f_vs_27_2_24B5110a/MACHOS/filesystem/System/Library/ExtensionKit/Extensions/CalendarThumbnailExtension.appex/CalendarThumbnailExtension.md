## CalendarThumbnailExtension

> `/System/Library/ExtensionKit/Extensions/CalendarThumbnailExtension.appex/CalendarThumbnailExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6d88` | `0x6e34` | **`+0xac`** |
| `__DATA.__data` | `0x318` | `0x328` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xb80` | `0xb90` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x5c8` | `0x5d0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x120` | `0x128` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1a0` | `0x1a8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 133
-  Symbols:   102
+  Functions: 135
+  Symbols:   103
Symbols:
+ _swift_release_x22
+ _swift_retain_x27
- _swift_retain_x28
Functions:
~ sub_100002f3c : 3624 -> 3628
+ sub_100007bb8
+ sub_100008200
```
