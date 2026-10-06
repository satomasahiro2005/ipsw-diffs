## HealthSettings

> `/System/Library/PreferenceBundles/HealthSettings.bundle/HealthSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x32f8` | `0x3ac8` | **`+0x7d0`** |
| `__TEXT.__eh_frame` | `0xa0` | `0x230` | **`+0x190`** |
| `__TEXT.__unwind_info` | `0x108` | `0x150` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x550` | `0x570` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x120` | `0x100` | **`-0x20`** |
| `__DATA.__data` | `0x178` | `0x168` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x2b0` | `0x2c0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x158` | `0x148` | **`-0x10`** |
| `__TEXT.__const` | `0x1da` | `0x1ea` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x4` | `0x14` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0xdc` | `0xce` | **`-0xe`** |
| `__TEXT.__swift_as_ret` | `—` | `0xc` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x48` | `0x40` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x4` | `0xc` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

-  Functions: 63
+  Functions: 70

-  CStrings:  20
+  CStrings:  19
Symbols:
+ _objc_release_x24
+ _objc_retain_x24
+ _swift_release_x20
+ _swift_release_x21
+ _swift_release_x27
- _OBJC_CLASS_$_HKHealthSettingsProfile
- _objc_release_x22
- _objc_retain_x21
- _swift_release
- _swift_release_x28
CStrings:
- "sharedProfile"
```
