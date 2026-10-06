## lskdd

> `/usr/libexec/lskdd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10bc9e4` | `0x10ad50c` | **`-0xf4d8`** |
| `__DATA_CONST.__const` | `0x50d78` | `0x50588` | **`-0x7f0`** |
| `__TEXT.__const` | `0x3d3af0` | `0x3d3bb0` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0xb48` | `0xb20` | **`-0x28`** |
| `__DATA.__data` | `0x2a58` | `0x2a48` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x270` | `0x280` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x148` | `0x150` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x1e8` | `0x1f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Symbols:   205
+  Symbols:   206
Symbols:
+ _objc_retain_x8
```
