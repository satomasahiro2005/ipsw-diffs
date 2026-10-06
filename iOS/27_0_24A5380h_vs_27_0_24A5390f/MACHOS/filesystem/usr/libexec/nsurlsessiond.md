## nsurlsessiond

> `/usr/libexec/nsurlsessiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x82e20` | `0x82f18` | **`+0xf8`** |
| `__TEXT.__unwind_info` | `0x2de0` | `0x2de8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3890.100.1.0.0
+3892.100.1.0.0

-  Functions: 2071
+  Functions: 2073
Functions:
~ sub_10003c4cc : 12 -> 124
+ sub_10003c548
+ sub_10005160c
```
