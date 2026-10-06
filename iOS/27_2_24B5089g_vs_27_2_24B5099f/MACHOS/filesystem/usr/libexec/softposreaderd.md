## softposreaderd

> `/usr/libexec/softposreaderd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41cb58` | `0x41cc68` | **`+0x110`** |
| `__TEXT.__eh_frame` | `0xcb80` | `0xcbd8` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0xd12e` | `0xd11e` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x4e78` | `0x4e80` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
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

-51.4.0.0.0
+51.5.0.0.0

-  Functions: 6169
+  Functions: 6171
CStrings:
+ "%s.%s: no controllerInfo (XPC failure)"
- "%s.%s: no controllerInfo; assuming antenna present"
```
