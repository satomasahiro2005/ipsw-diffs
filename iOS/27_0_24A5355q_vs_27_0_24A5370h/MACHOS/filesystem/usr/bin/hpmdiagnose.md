## hpmdiagnose

> `/usr/bin/hpmdiagnose`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1009c` | `0x100fc` | **`+0x60`** |

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

-647.0.0.0.0
+648.0.0.0.0
Functions:
~ sub_100000cc0 : 1616 -> 1608
~ sub_100001310 -> sub_100001308 : 376 -> 372
~ sub_100001734 -> sub_100001728 : 560 -> 556
~ sub_100001964 -> sub_100001954 : 2120 -> 2116
~ sub_1000034f0 -> sub_1000034dc : 5084 -> 5100
~ sub_1000048cc -> sub_1000048c8 : 1584 -> 1628
~ sub_10000840c -> sub_100008434 : 236 -> 256
~ sub_1000085d0 -> sub_10000860c : 196 -> 212
~ sub_1000089c8 -> sub_100008a14 : 304 -> 300
~ sub_100008af8 -> sub_100008b40 : 304 -> 300
~ sub_100009cb4 -> sub_100009cf8 : 240 -> 268
~ sub_10000c1ac -> sub_10000c20c : 280 -> 276
~ sub_10000c35c -> sub_10000c3b8 : 512 -> 508
~ sub_10000c55c -> sub_10000c5b4 : 512 -> 508
~ sub_10000c75c -> sub_10000c7b0 : 272 -> 268
~ sub_10000c86c -> sub_10000c8bc : 272 -> 268
~ sub_10000c97c -> sub_10000c9c8 : 272 -> 268
~ sub_10000cf90 -> sub_10000cfd8 : 196 -> 192
~ sub_10000d298 -> sub_10000d2dc : 788 -> 796
~ sub_10000e8c0 -> sub_10000e90c : 320 -> 316
~ sub_10000ee68 -> sub_10000eeb0 : 304 -> 300
~ sub_10000ef98 -> sub_10000efdc : 304 -> 300
~ sub_10000f398 -> sub_10000f3d8 : 560 -> 556
~ sub_10000f62c -> sub_10000f668 : 256 -> 252
~ sub_1000103dc -> sub_100010414 : 364 -> 384
~ sub_1000106b0 -> sub_1000106fc : 1196 -> 1192
~ sub_100010bd4 -> sub_100010c1c : 300 -> 324
```
