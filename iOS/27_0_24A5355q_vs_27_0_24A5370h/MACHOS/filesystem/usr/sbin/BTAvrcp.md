## BTAvrcp

> `/usr/sbin/BTAvrcp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdbb4` | `0xdb9c` | **`-0x18`** |

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

```diff

-2700.30.2.0.0
+2700.34.0.0.0
Functions:
~ sub_100002b00 : 532 -> 528
~ sub_100008b64 -> sub_100008b60 : 404 -> 400
~ sub_10000a72c -> sub_10000a724 : 372 -> 368
~ sub_10000adac -> sub_10000ada0 : 428 -> 424
~ sub_10000b0bc -> sub_10000b0ac : 356 -> 352
~ sub_10000e284 -> sub_10000e270 : 280 -> 276
```
