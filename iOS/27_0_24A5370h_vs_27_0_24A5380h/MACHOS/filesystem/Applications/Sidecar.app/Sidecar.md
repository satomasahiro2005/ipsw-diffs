## Sidecar

> `/Applications/Sidecar.app/Sidecar`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c1b4` | `0x1c1f4` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0xd90` | `0xda0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x6d0` | `0x6d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-400.37.0.0.0
+400.39.0.0.0

-  Symbols:   354
+  Symbols:   355
Symbols:
+ _swift_arrayInitWithCopy
Functions:
~ sub_1000185f0 : 384 -> 448
```
