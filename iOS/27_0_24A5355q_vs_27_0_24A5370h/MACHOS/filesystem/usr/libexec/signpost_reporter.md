## signpost_reporter

> `/usr/libexec/signpost_reporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa988` | `0xaa34` | **`+0xac`** |
| `__TEXT.__gcc_except_tab` | `0x34c` | `0x3cc` | **`+0x80`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-197.0.0.0.0
+200.0.0.0.0
Functions:
~ sub_1000015ac : 456 -> 452
~ sub_100001fbc -> sub_100001fb8 : 1276 -> 1272
~ sub_100002efc -> sub_100002ef4 : 708 -> 704
~ sub_100004ba8 -> sub_100004b9c : 2796 -> 2852
~ sub_100005c54 -> sub_100005c80 : 380 -> 392
~ sub_100005dd0 -> sub_100005e08 : 352 -> 364
~ sub_100005f30 -> sub_100005f74 : 280 -> 292
~ sub_100006048 -> sub_100006098 : 40 -> 68
~ sub_100006070 -> sub_1000060dc : 276 -> 296
~ sub_100006214 -> sub_100006294 : 5328 -> 5296
~ sub_100008f9c -> sub_100008ffc : 2036 -> 2060
~ sub_100009790 -> sub_100009808 : 772 -> 796
~ sub_10000a1a0 -> sub_10000a230 : 1420 -> 1444
~ sub_10000a9c8 -> sub_10000aa70 : 524 -> 508
~ sub_10000b040 -> sub_10000b0d8 : 360 -> 356
~ sub_10000b1a8 -> sub_10000b23c : 252 -> 276
```
