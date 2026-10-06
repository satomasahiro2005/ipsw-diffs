## ScreenTimeSettingsExperience

> `/System/Library/Settings/ScreenTimeSettingsExperience.settings/ScreenTimeSettingsExperience`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__eh_frame` | `0x4d8` | `0x700` | **`+0x228`** |
| `__TEXT.__swift_as_cont` | `0x24` | `0xb8` | **`+0x94`** |
| `__TEXT.__unwind_info` | `0x1e8` | `0x250` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x2c0` | `0x2e8` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `—` | `0x24` | **`+0x24`** |
| `__TEXT.__auth_stubs` | `0x750` | `0x770` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x3b0` | `0x3c0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x148` | `0x158` | **`+0x10`** |
| `__TEXT.__const` | `0x25a` | `0x26a` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xa0` | `0xb0` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x24` | `0x28` | **`+0x4`** |
| `__TEXT.__text` | `0x80a0` | `0x80a4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-82.0.100.0.0
+87.1.101.0.0

-  Functions: 98
+  Functions: 114
Symbols:
+ _objc_retain_x20
+ _objc_retain_x28
+ _swift_release_x23
+ _swift_retain_x23
+ _swift_retain_x27
- _objc_retain_x19
- _objc_retain_x25
- _swift_release_x25
- _swift_retain_x21
- _swift_retain_x25
```
