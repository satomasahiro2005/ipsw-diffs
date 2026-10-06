## CoverageSettings

> `/System/Library/PreferenceBundles/CoverageSettings.bundle/CoverageSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ff0` | `0x1c5c` | **`-0x394`** |
| `__DATA_CONST.__const` | `0x1d0` | `0x150` | **`-0x80`** |
| `__TEXT.__const` | `0x168` | `0x132` | **`-0x36`** |
| `__TEXT.__eh_frame` | `0xc0` | `0x98` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x120` | `0xf8` | **`-0x28`** |
| `__TEXT.__swift5_capture` | `0x40` | `0x20` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0xa8` | `0x8c` | **`-0x1c`** |
| `__TEXT.__auth_stubs` | `0x4d0` | `0x4c0` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3c` | `0x2c` | **`-0x10`** |
| `__DATA.__bss` | `0x108` | `0x100` | **`-0x8`** |
| `__DATA.__data` | `0xf8` | `0x100` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x270` | `0x268` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0xe2` | `0xdb` | **`-0x7`** |
| `__TEXT.__swift5_types` | `0xc` | `0x8` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-602.0.0.0.0
+616.0.0.0.0

-  Functions: 56
+  Functions: 41
Symbols:
+ _swift_deletedMethodError
- _objc_retain_x23
```
