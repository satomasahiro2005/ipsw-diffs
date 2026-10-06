## driverkitd

> `/usr/libexec/driverkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe98d8` | `0xe9574` | **`-0x364`** |
| `__TEXT.__eh_frame` | `0x3254` | `0x3224` | **`-0x30`** |
| `__DATA.__data` | `0x6268` | `0x6290` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x2760` | `0x2740` | **`-0x20`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-510.0.0.0.0
+511.0.0.0.0

-  Functions: 3617
+  Functions: 3612
Symbols:
+ _objc_retain_x9
- _swift_release_x11
CStrings:
+ "KernelManagement_executables-511"
- "KernelManagement_executables-510"
```
