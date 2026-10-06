## DoNotDisturbAppIntents

> `/System/Library/ExtensionKit/Extensions/DoNotDisturbAppIntents.appex/DoNotDisturbAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc048` | `0xc0f8` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0x778` | `0x7a0` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0xab0` | `0xac0` | **`+0x10`** |
| `__TEXT.__const` | `0xbd8` | `0xbe8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x560` | `0x568` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x488` | `0x490` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x128` | `0x130` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3a0` | `0x3a8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x4c` | `0x50` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x50` | `0x54` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-506.0.0.0.0
+508.0.0.0.0

-  Functions: 232
+  Functions: 233
Functions:
~ sub_100003d44 : 192 -> 176
+ sub_100003df4
```
