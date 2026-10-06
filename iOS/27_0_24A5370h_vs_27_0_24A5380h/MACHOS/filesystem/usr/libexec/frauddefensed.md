## frauddefensed

> `/usr/libexec/frauddefensed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd2bac` | `0xd2dc4` | **`+0x218`** |
| `__TEXT.__const` | `0x799c` | `0x79cc` | **`+0x30`** |
| `__TEXT.__cstring` | `0x9e9b` | `0x9ecb` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x3598` | `0x35c0` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0xa540` | `0xa520` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x99c` | `0x994` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-92.0.0.0.0
+94.0.0.0.0

-  Functions: 3371
+  Functions: 3369

-  CStrings:  1044
+  CStrings:  1045
CStrings:
+ "Task was cancelled. { taskIdentifier="
```
