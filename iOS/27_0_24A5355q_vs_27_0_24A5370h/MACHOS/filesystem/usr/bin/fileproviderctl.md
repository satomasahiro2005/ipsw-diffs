## fileproviderctl

> `/usr/bin/fileproviderctl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xff54` | `0xff44` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4780.0.0.502.1
+4838.0.29.502.2
Functions:
~ sub_1000020f4 : 316 -> 312
~ sub_1000027c8 -> sub_1000027c4 : 756 -> 752
~ sub_100003b2c -> sub_100003b24 : 700 -> 696
~ sub_10000451c -> sub_100004510 : 1012 -> 1036
~ sub_100005774 -> sub_100005780 : 264 -> 276
~ sub_10000587c -> sub_100005894 : 628 -> 624
~ sub_1000062ec -> sub_100006300 : 664 -> 660
~ sub_10000771c -> sub_10000772c : 564 -> 560
~ sub_100007ad8 -> sub_100007ae4 : 2400 -> 2384
~ sub_10000855c -> sub_100008558 : 460 -> 456
~ sub_100008728 -> sub_100008720 : 1440 -> 1452
~ sub_100008d38 -> sub_100008d3c : 1508 -> 1496
~ sub_10000a84c -> sub_10000a844 : 204 -> 208
~ sub_10000a918 -> sub_10000a914 : 312 -> 316
~ sub_10000b4d0 : 588 -> 584
~ sub_10000b9dc -> sub_10000b9d8 : 2012 -> 1980
~ sub_10000c804 -> sub_10000c7e0 : 220 -> 236
~ sub_10000d274 -> sub_10000d260 : 1452 -> 1448
~ sub_10000e494 -> sub_10000e47c : 788 -> 784
~ sub_100010468 -> sub_10001044c : 256 -> 276
~ sub_100010fa4 -> sub_100010f9c : 1088 -> 1080
```
