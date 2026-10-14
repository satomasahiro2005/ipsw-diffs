## DeviceDiscoveryUISettings

> `/System/Library/Settings/DeviceDiscoveryUISettings.settings/DeviceDiscoveryUISettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x150a8` | `0x15254` | **`+0x1ac`** |
| `__DATA.__data` | `0x590` | `0x5b0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x200` | `0x210` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xd50` | `0xd60` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4b8` | `0x4c8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x6b0` | `0x6b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2131.21.21.0.0
+2131.21.31.2.4

-  Functions: 338
-  Symbols:   152
+  Functions: 342
+  Symbols:   153
Symbols:
+ _swift_release_x27
```
