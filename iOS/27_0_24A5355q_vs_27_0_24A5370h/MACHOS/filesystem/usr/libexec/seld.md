## seld

> `/usr/libexec/seld`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27448` | `0x273b8` | **`-0x90`** |
| `__TEXT.__const` | `0x1b8` | `0x1b0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-370.33.1.0.0
+370.37.0.0.0
Functions:
~ sub_100001694 : 3072 -> 3048
~ sub_100002294 -> sub_10000227c : 1512 -> 1500
~ sub_10000287c -> sub_100002858 : 2260 -> 2256
~ sub_1000032e4 -> sub_1000032bc : 1208 -> 1204
~ sub_1000039b4 -> sub_100003988 : 832 -> 828
~ sub_100007968 -> sub_100007938 : 2644 -> 2680
~ sub_100008cd8 -> sub_100008ccc : 2024 -> 2020
~ sub_10000db88 -> sub_10000db78 : 504 -> 500
~ sub_1000106f4 -> sub_1000106e0 : 776 -> 772
~ sub_100011f64 -> sub_100011f4c : 1124 -> 1116
~ sub_1000144a8 -> sub_100014488 : 1168 -> 1164
~ sub_100014938 -> sub_100014914 : 7292 -> 7296
~ sub_100018fb8 -> sub_100018f98 : 1504 -> 1500
~ sub_10001a3f4 -> sub_10001a3d0 : 3812 -> 3808
~ sub_10001b484 -> sub_10001b45c : 812 -> 808
~ sub_10001dc40 -> sub_10001dc14 : 300 -> 296
~ sub_10001dd6c -> sub_10001dd3c : 292 -> 288
~ sub_10001de90 -> sub_10001de5c : 496 -> 492
~ sub_10001e080 -> sub_10001e048 : 684 -> 676
~ sub_10001f3b8 -> sub_10001f378 : 4340 -> 4320
~ sub_1000204ac -> sub_100020458 : 1380 -> 1376
~ sub_100020b68 -> sub_100020b10 : 560 -> 556
~ sub_100020d98 -> sub_100020d3c : 4744 -> 4740
~ sub_100022b78 -> sub_100022b18 : 3496 -> 3492
~ sub_100023ad4 -> sub_100023a70 : 804 -> 792
~ sub_100023df8 -> sub_100023d88 : 788 -> 784
~ sub_10002454c -> sub_1000244d8 : 1336 -> 1328
~ sub_100025690 -> sub_100025614 : 632 -> 628
~ sub_10002596c -> sub_1000258ec : 2388 -> 2380
~ sub_100026480 -> sub_1000263f8 : 580 -> 576
~ sub_100027584 -> sub_1000274f8 : 2188 -> 2184
```
