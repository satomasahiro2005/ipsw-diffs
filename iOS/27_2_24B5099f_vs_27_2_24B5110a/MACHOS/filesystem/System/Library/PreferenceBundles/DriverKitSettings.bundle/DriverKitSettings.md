## DriverKitSettings

> `/System/Library/PreferenceBundles/DriverKitSettings.bundle/DriverKitSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3158` | `0x3234` | **`+0xdc`** |
| `__DATA.__data` | `0x1a8` | `0x1b8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x600` | `0x5f0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x160` | `0x170` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x308` | `0x300` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-  Functions: 100
-  Symbols:   103
+  Functions: 101
+  Symbols:   102
Symbols:
+ _swift_retain_x25
- _swift_release_x26
- _swift_retain_x26
```
