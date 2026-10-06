## swift-inspect

> `/usr/bin/swift-inspect`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x953ac` | `0x95cc4` | **`+0x918`** |
| `__DATA_CONST.__auth_ptr` | `0xf08` | `0xf10` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-6.4.0.19.103
+6.4.0.23.102

-  Functions: 3132
+  Functions: 3133
Symbols:
+ _swift_release_x12
- _swift_release_x11
```
