## assessmentagent

> `/usr/libexec/assessmentagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9ccf0` | `0x9cd3c` | **`+0x4c`** |
| `__TEXT.__auth_stubs` | `0x2140` | `0x2130` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x10b0` | `0x10a8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
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

-  Symbols:   959
+  Symbols:   958
Symbols:
- _swift_release_x9
Functions:
~ sub_1000256d4 : 148 -> 152
~ sub_100030914 -> sub_100030918 : 496 -> 500
~ sub_10003dc8c -> sub_10003dc94 : 528 -> 532
~ sub_100041330 -> sub_10004133c : 1640 -> 1644
~ sub_100049a2c -> sub_100049a3c : 3516 -> 3520
~ sub_100057374 -> sub_100057388 : 352 -> 364
~ sub_1000574d4 -> sub_1000574f4 : 208 -> 212
~ sub_1000575a4 -> sub_1000575c8 : 704 -> 696
~ sub_10005a820 -> sub_10005a83c : 1892 -> 1896
~ sub_10005c210 -> sub_10005c230 : 580 -> 584
~ sub_10005da8c -> sub_10005dab0 : 552 -> 556
~ sub_10005dcb4 -> sub_10005dcdc : 652 -> 656
~ sub_1000811d4 -> sub_100081200 : 524 -> 528
~ sub_100088438 -> sub_100088468 : 720 -> 728
~ sub_100088fbc -> sub_100088ff4 : 980 -> 992
~ sub_10008a274 -> sub_10008a2b8 : 352 -> 356
~ sub_10008adf4 -> sub_10008ae3c : 344 -> 348
~ sub_10008f2cc -> sub_10008f318 : 3452 -> 3420
~ sub_100092ad4 -> sub_100092b00 : 176 -> 180
~ sub_100092bf0 -> sub_100092c20 : 180 -> 184
~ sub_100092d3c -> sub_100092d70 : 188 -> 192
~ sub_100097220 -> sub_100097258 : 2520 -> 2524
~ sub_100098048 -> sub_100098084 : 4016 -> 4024
~ sub_100099228 -> sub_10009926c : 680 -> 684
~ sub_10009bb54 -> sub_10009bb9c : 2780 -> 2784
```
