## lskdd

> `/usr/libexec/lskdd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10a7998` | `0x10a13e0` | **`-0x65b8`** |
| `__DATA_CONST.__const` | `0x50c68` | `0x4fb98` | **`-0x10d0`** |
| `__TEXT.__const` | `0x3d47c0` | `0x3d37c0` | **`-0x1000`** |
| `__TEXT.__unwind_info` | `0xae0` | `0xa80` | **`-0x60`** |
| `__DATA.__data` | `0x28a8` | `0x2858` | **`-0x50`** |
| `__DATA.__common` | `0x94184` | `0x941a4` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 426
+  Functions: 417
```
