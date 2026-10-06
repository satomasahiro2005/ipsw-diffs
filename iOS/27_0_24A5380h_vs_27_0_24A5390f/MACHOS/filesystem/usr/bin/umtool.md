## umtool

> `/usr/bin/umtool`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x154ec` | `0x15504` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_1000067f4 : 12 -> 20
~ sub_100006800 -> sub_100006808 : 20 -> 12
~ sub_10000c4fc : 436 -> 460
```
