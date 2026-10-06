## VSAppIntents

> `/System/Library/ExtensionKit/Extensions/VSAppIntents.appex/VSAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5814` | `0x58c4` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0x3e0` | `0x408` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x7b0` | `0x7c0` | **`+0x10`** |
| `__TEXT.__const` | `0x888` | `0x898` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x438` | `0x440` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xf8` | `0x100` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x298` | `0x2a0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x40` | `0x44` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x2c` | `0x30` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-609.0.0.0.0
+609.0.2.0.0

-  Functions: 167
+  Functions: 168
Functions:
~ sub_100003a4c : 192 -> 176
+ sub_100003afc
```
