## rtcreportingd

> `/usr/libexec/rtcreportingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70344` | `0x704d4` | **`+0x190`** |
| `__TEXT.__eh_frame` | `0x5af8` | `0x5b40` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x2240` | `0x2250` | **`+0x10`** |
| `__TEXT.__const` | `0x446a` | `0x445a` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x1128` | `0x1130` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x22d8` | `0x22e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 3206
-  Symbols:   817
+  Functions: 3211
+  Symbols:   818
Symbols:
+ _swift_release_x11
```
