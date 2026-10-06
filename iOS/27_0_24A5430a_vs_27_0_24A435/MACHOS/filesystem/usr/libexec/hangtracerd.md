## hangtracerd

> `/usr/libexec/hangtracerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x400` | `0x430` | **`+0x30`** |
| `__TEXT.__text` | `0x36f50` | `0x36f48` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_100002e68 : 4540 -> 4504
~ sub_10000be1c -> sub_10000bdf8 : 1396 -> 1392
~ sub_1000116c4 -> sub_10001169c : 8984 -> 9016
```
