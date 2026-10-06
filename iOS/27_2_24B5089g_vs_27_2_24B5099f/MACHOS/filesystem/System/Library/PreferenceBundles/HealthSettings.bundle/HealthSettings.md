## HealthSettings

> `/System/Library/PreferenceBundles/HealthSettings.bundle/HealthSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x570` | `0x580` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2c0` | `0x2c8` | **`+0x8`** |
| `__TEXT.__swift5_reflstr` | `0xbc` | `0xb5` | **`-0x7`** |
| `__TEXT.__text` | `0x3ac8` | `0x3ac4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

+  - /System/Library/PrivateFrameworks/HealthPlans.framework/HealthPlans
Symbols:
+ _swift_retain_x27
- _objc_retain_x27
Functions:
~ sub_3c78 -> sub_3cd8 : 792 -> 788
```
