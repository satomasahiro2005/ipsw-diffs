## lockdownd

> `/usr/libexec/lockdownd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x91ffc` | `0x91fdc` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0xc40` | `0xc38` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```text
Functions:
~ sub_100001d7c : 228 -> 232
~ sub_100002f90 -> sub_100002f94 : 508 -> 504
~ sub_100004c48 : 1112 -> 1108
~ sub_100008918 -> sub_100008914 : 776 -> 772
~ sub_100009138 -> sub_100009130 : 448 -> 444
~ sub_10000bf0c -> sub_10000bf00 : 700 -> 696
~ sub_10000d118 -> sub_10000d108 : 384 -> 388
~ sub_10000d598 -> sub_10000d58c : 152 -> 160
~ sub_10000e7f0 -> sub_10000e7ec : 404 -> 400
~ sub_100010edc -> sub_100010ed4 : 152 -> 168
~ sub_100010f74 -> sub_100010f7c : 168 -> 164
~ sub_10001101c -> sub_100011020 : 168 -> 164
~ sub_100012b88 : 1716 -> 1712
~ sub_100013f1c -> sub_100013f18 : 972 -> 968
~ sub_1000142e8 -> sub_1000142e0 : 372 -> 368
~ sub_100014fb4 -> sub_100014fa8 : 412 -> 408
~ sub_1000154ec -> sub_1000154dc : 1276 -> 1272
~ sub_100016d28 -> sub_100016d14 : 440 -> 444
~ sub_1000188d8 -> sub_1000188c8 : 972 -> 968
~ sub_100025248 -> sub_100025234 : 1388 -> 1380
~ sub_100027bb8 -> sub_100027b9c : 176 -> 180
~ sub_100027cf8 -> sub_100027ce0 : 164 -> 168
~ sub_100027d9c -> sub_100027d88 : 180 -> 184
~ sub_100027e50 -> sub_100027e40 : 216 -> 200
```
