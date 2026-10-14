## ControlCenterSettings

> `/System/Library/PreferenceBundles/ControlCenterSettings.bundle/ControlCenterSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9c00` | `0x9dac` | **`+0x1ac`** |
| `__DATA.__data` | `0x608` | `0x630` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x300` | `0x320` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xf00` | `0xef0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x788` | `0x780` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x230` | `0x238` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-704.2.3.0.0
+704.2.4.100.0

-  Functions: 244
-  Symbols:   164
+  Functions: 249
+  Symbols:   163
Symbols:
- _swift_retain_x24
```
