## VisionAppIntents

> `/System/Library/ExtensionKit/Extensions/VisionAppIntents.appex/VisionAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2077c` | `0x2087c` | **`+0x100`** |
| `__TEXT.__auth_stubs` | `0x1190` | `0x11a0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x8d0` | `0x8d8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5b8` | `0x5b0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-10.0.33.0.0
+10.0.34.0.0

-  Symbols:   157
+  Symbols:   158
Symbols:
+ _objc_retain_x21
Functions:
~ sub_100002c78 : 1160 -> 1156
~ sub_10000323c -> sub_100003238 : 776 -> 772
~ sub_100005bd0 -> sub_100005bc8 : 4484 -> 4496
~ sub_100006ef8 -> sub_100006efc : 4444 -> 4456
~ sub_100008054 -> sub_100008064 : 4980 -> 4992
~ sub_10000952c -> sub_100009548 : 3740 -> 3752
~ sub_10000a3c8 -> sub_10000a3f0 : 3604 -> 3616
~ sub_10000b340 -> sub_10000b374 : 3696 -> 3708
~ sub_10000c1b0 -> sub_10000c1f0 : 3576 -> 3588
~ sub_10000e8a8 -> sub_10000e8f4 : 480 -> 484
~ sub_10000ea88 -> sub_10000ead8 : 492 -> 496
~ sub_10000f718 -> sub_10000f76c : 552 -> 556
~ sub_10000f940 -> sub_10000f998 : 1144 -> 1132
~ sub_10000fdb8 -> sub_10000fe04 : 372 -> 384
~ sub_10000ff2c -> sub_10000ff84 : 688 -> 708
~ sub_1000101dc -> sub_100010248 : 864 -> 868
~ sub_1000108d4 -> sub_100010944 : 2220 -> 2212
~ sub_100014b6c -> sub_100014bd4 : 496 -> 500
~ sub_100014e64 -> sub_100014ed0 : 476 -> 480
~ sub_1000153d4 -> sub_100015444 : 888 -> 892
~ sub_10001574c -> sub_1000157c0 : 1072 -> 1068
~ sub_100015b7c -> sub_100015bec : 3808 -> 3820
~ sub_1000171d8 -> sub_100017254 : 872 -> 880
~ sub_100017540 -> sub_1000175c4 : 1556 -> 1568
~ sub_1000187c0 -> sub_100018850 : 4732 -> 4724
~ sub_100019cac -> sub_100019d34 : 4136 -> 4144
~ sub_10001ae94 -> sub_10001af24 : 4100 -> 4108
~ sub_10001c030 -> sub_10001c0c8 : 3200 -> 3216
~ sub_10001ccb0 -> sub_10001cd58 : 3324 -> 3348
~ sub_10001d9ac -> sub_10001da6c : 2356 -> 2368
~ sub_10001e2e0 -> sub_10001e3ac : 2448 -> 2460
~ sub_10001fc50 -> sub_10001fd28 : 236 -> 256
~ sub_10001fd3c -> sub_10001fe28 : 228 -> 248
```
