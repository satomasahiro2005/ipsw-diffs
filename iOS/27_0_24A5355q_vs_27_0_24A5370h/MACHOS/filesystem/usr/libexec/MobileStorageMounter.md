## MobileStorageMounter

> `/usr/libexec/MobileStorageMounter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0xe20` | `0xe40` | **`+0x20`** |
| `__TEXT.__text` | `0x1c854` | `0x1c83c` | **`-0x18`** |
| `__DATA_CONST.__auth_got` | `0x720` | `0x730` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1e78` | `0x1e88` | **`+0x10`** |
| `__TEXT.__const` | `0xd6d0` | `0xd6d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   294
+  Symbols:   296
Symbols:
+ _objc_retain_x26
+ _objc_retain_x28
Functions:
~ sub_100002794 : 6472 -> 6468
~ sub_100006bc0 -> sub_100006bbc : 416 -> 412
~ sub_100007f2c -> sub_100007f24 : 1008 -> 1004
~ sub_100008674 -> sub_100008668 : 824 -> 820
~ sub_10000bab4 -> sub_10000baa4 : 368 -> 364
~ sub_10000ca2c -> sub_10000ca18 : 4616 -> 4608
~ sub_10000e5e0 -> sub_10000e5c4 : 256 -> 252
~ sub_100011dd0 -> sub_100011db0 : 2468 -> 2472
~ sub_100012774 -> sub_100012758 : 3420 -> 3428
~ sub_1000147ac -> sub_100014798 : 908 -> 888
~ sub_100014b5c -> sub_100014b34 : 504 -> 500
~ sub_100015f3c -> sub_100015f10 : 252 -> 268
~ sub_1000185b4 -> sub_100018598 : 720 -> 724
~ sub_10001915c -> sub_100019144 : 432 -> 436
~ sub_10001930c -> sub_1000192f8 : 592 -> 588
```
