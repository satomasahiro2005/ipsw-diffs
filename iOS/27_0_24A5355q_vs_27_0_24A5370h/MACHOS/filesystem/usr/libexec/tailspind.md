## tailspind

> `/usr/libexec/tailspind`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe684` | `0xe668` | **`-0x1c`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-262.0.0.0.0
+264.0.0.0.0
Functions:
~ sub_100004104 : 2596 -> 2588
~ sub_100008458 -> sub_100008450 : 1232 -> 1224
~ sub_10000c8b8 -> sub_10000c8a8 : 2288 -> 2280
~ sub_10000d7a8 -> sub_10000d790 : 1280 -> 1276
```
