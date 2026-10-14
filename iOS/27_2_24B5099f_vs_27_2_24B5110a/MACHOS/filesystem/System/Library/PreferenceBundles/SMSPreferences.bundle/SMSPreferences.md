## SMSPreferences

> `/System/Library/PreferenceBundles/SMSPreferences.bundle/SMSPreferences`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68ec` | `0x6a6c` | **`+0x180`** |
| `__DATA.__data` | `0x358` | `0x380` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x900` | `0x920` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x488` | `0x498` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1b8` | `0x1c8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1d8` | `0x1e8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-  Functions: 142
-  Symbols:   124
+  Functions: 146
+  Symbols:   126
Symbols:
+ _objc_retain_x19
+ _swift_release_x23
```
