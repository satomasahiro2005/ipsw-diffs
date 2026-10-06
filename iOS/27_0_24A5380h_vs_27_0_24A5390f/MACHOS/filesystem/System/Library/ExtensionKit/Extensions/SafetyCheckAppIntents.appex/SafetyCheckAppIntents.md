## SafetyCheckAppIntents

> `/System/Library/ExtensionKit/Extensions/SafetyCheckAppIntents.appex/SafetyCheckAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f6c` | `0x501c` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0x230` | `0x258` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x630` | `0x640` | **`+0x10`** |
| `__TEXT.__const` | `0xa64` | `0xa74` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x320` | `0x328` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x4c8` | `0x4d0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xa0` | `0xa8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x278` | `0x280` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x30` | `0x34` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x20` | `0x24` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-  Functions: 174
+  Functions: 175
Functions:
~ sub_1000039c4 : 192 -> 176
+ sub_100003a74
```
