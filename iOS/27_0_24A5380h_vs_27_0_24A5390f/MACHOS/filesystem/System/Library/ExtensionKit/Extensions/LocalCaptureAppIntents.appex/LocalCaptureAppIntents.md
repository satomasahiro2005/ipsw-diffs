## LocalCaptureAppIntents

> `/System/Library/ExtensionKit/Extensions/LocalCaptureAppIntents.appex/LocalCaptureAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3314` | `0x33c8` | **`+0xb4`** |
| `__TEXT.__eh_frame` | `0x178` | `0x1a8` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x450` | `0x460` | **`+0x10`** |
| `__TEXT.__const` | `0x994` | `0x9a4` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x228` | `0x230` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x460` | `0x468` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x70` | `0x78` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x208` | `0x210` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x24` | `0x28` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x10` | `0x14` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-740.53.1.0.0
+740.57.1.0.0

-  Functions: 141
+  Functions: 143
Functions:
~ sub_100001994 : 192 -> 176
+ sub_100001a44
+ sub_1000032e8
```
