## FontThumbnailExtension

> `/System/Library/ExtensionKit/Extensions/FontThumbnailExtension.appex/FontThumbnailExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1de0` | `0x1e04` | **`+0x24`** |
| `__TEXT.__auth_stubs` | `0x600` | `0x610` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x300` | `0x308` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
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

-215.0.0.0.0
+216.0.0.0.0

-  Symbols:   91
+  Symbols:   92
Symbols:
+ _objc_retain_x9
Functions:
~ sub_100002594 : 256 -> 276
~ sub_1000026fc -> sub_100002710 : 244 -> 252
~ sub_100002a6c -> sub_100002a88 : 180 -> 188
```
