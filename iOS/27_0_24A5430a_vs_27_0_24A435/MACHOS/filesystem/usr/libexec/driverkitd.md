## driverkitd

> `/usr/libexec/driverkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xeba10` | `0xec358` | **`+0x948`** |
| `__TEXT.__eh_frame` | `0x3374` | `0x33a4` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x27b0` | `0x27c8` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x2490` | `0x2480` | **`-0x10`** |
| `__DATA.__data` | `0x63c8` | `0x63c0` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x1250` | `0x1248` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
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

-  Functions: 3636
-  Symbols:   879
+  Functions: 3641
+  Symbols:   878
Symbols:
- _objc_retain_x9
```
