## bootpd

> `/usr/libexec/bootpd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10f24` | `0x10fa4` | **`+0x80`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-551.0.0.0.0
+553.0.0.0.0
Functions:
~ sub_100001920 : 152 -> 156
~ sub_1000019b8 -> sub_1000019bc : 6876 -> 6864
~ sub_1000037b8 -> sub_1000037b0 : 708 -> 724
~ sub_100003df4 -> sub_100003dfc : 2036 -> 2044
~ sub_100004c18 -> sub_100004c28 : 1520 -> 1524
~ sub_100005208 -> sub_10000521c : 280 -> 308
~ sub_100005df8 -> sub_100005e28 : 7528 -> 7544
~ sub_100007dac -> sub_100007dec : 132 -> 124
~ sub_100007e30 -> sub_100007e68 : 112 -> 128
~ sub_1000083ac -> sub_1000083f4 : 284 -> 280
~ sub_100008aec -> sub_100008b30 : 976 -> 972
~ sub_10000903c -> sub_10000907c : 276 -> 272
~ sub_100009168 -> sub_1000091a4 : 148 -> 152
~ sub_100009208 -> sub_100009248 : 256 -> 260
~ sub_100009994 -> sub_1000099d8 : 876 -> 872
~ sub_100009d08 -> sub_100009d48 : 1672 -> 1700
~ sub_10000a618 -> sub_10000a674 : 864 -> 880
~ sub_10000aa50 -> sub_10000aabc : 172 -> 164
~ sub_10000acd8 -> sub_10000ad3c : 688 -> 700
~ sub_10000b03c -> sub_10000b0ac : 812 -> 788
~ sub_10000be00 -> sub_10000be58 : 132 -> 140
~ sub_10000bee8 -> sub_10000bf48 : 1740 -> 1768
~ sub_10000c5b4 -> sub_10000c630 : 132 -> 136
~ sub_10000cbf8 -> sub_10000cc78 : 408 -> 424
~ sub_10000ce08 -> sub_10000ce98 : 136 -> 140
~ sub_10000d440 -> sub_10000d4d4 : 196 -> 192
~ _identifierToStringWithBuffer : 260 -> 256
~ _SubnetGetOptionPtrAndLength : 92 -> 96
~ _SubnetListCreateWithArray : 1776 -> 1788
~ _SubnetListPrintCFString : 696 -> 692
~ sub_10000ece0 -> sub_10000ed78 : 324 -> 316
~ sub_10000f460 -> sub_10000f4f0 : 392 -> 388
~ sub_10000f6a4 -> sub_10000f730 : 424 -> 420
~ sub_10000f84c -> sub_10000f8d4 : 228 -> 224
~ sub_10000f930 -> sub_10000f9b4 : 248 -> 252
~ sub_10000fa28 -> sub_10000fab0 : 192 -> 180
~ sub_10000fb2c -> sub_10000fba8 : 108 -> 96
~ sub_10000fb98 -> sub_10000fc08 : 152 -> 164
~ sub_10000fc30 -> sub_10000fcac : 120 -> 124
~ sub_10000fca8 -> sub_10000fd28 : 152 -> 164
~ sub_10000fd40 -> sub_10000fdcc : 112 -> 108
~ sub_10000fe6c -> sub_10000fef4 : 256 -> 248
~ sub_10000ff6c -> sub_10000ffec : 152 -> 164
~ sub_100010860 -> sub_1000108ec : 488 -> 484
~ _inetroute_list_print_cfstr : 272 -> 264
```
