## brctl

> `/usr/bin/brctl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13d54` | `0x13d40` | **`-0x14`** |
| `__TEXT.__const` | `0xf0` | `0xf8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-5168.0.55.0.0
+5168.40.149.0.1
Functions:
~ sub_100006c84 : 348 -> 344
~ sub_100006de0 -> sub_100006ddc : 1180 -> 1176
~ sub_10000c3f8 -> sub_10000c3f0 : 2380 -> 2376
~ sub_1000154fc -> sub_1000154f0 : 184 -> 180
~ sub_100015724 -> sub_100015714 : 184 -> 180
```
