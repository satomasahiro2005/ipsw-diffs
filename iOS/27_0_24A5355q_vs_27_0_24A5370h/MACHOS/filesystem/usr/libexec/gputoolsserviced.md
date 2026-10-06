## gputoolsserviced

> `/usr/libexec/gputoolsserviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33108` | `0x33024` | **`-0xe4`** |
| `__TEXT.__unwind_info` | `0xa20` | `0xa18` | **`-0x8`** |
| `__TEXT.__objc_methname` | `0x775a` | `0x7756` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2027.0.28.0.0
+2027.0.31.0.0
Functions:
~ sub_100005a20 : 732 -> 724
~ sub_1000064bc -> sub_1000064b4 : 904 -> 896
~ sub_100006f98 -> sub_100006f88 : 1140 -> 1136
~ sub_10000746c -> sub_100007458 : 32 -> 28
~ sub_100007774 -> sub_10000775c : 280 -> 276
~ sub_10000818c -> sub_100008170 : 160 -> 164
~ sub_100008344 -> sub_10000832c : 152 -> 160
~ sub_1000085bc -> sub_1000085ac : 124 -> 116
~ sub_1000091c0 -> sub_1000091a8 : 10588 -> 10580
~ sub_10000bdac -> sub_10000bd8c : 200 -> 188
~ sub_10000be74 -> sub_10000be48 : 176 -> 172
~ sub_10000c204 -> sub_10000c1d4 : 184 -> 188
~ sub_10000c3e0 -> sub_10000c3b4 : 364 -> 372
~ sub_10000e258 -> sub_10000e234 : 68 -> 72
~ sub_10000f8d4 -> sub_10000f8b4 : 656 -> 652
~ sub_100010320 -> sub_1000102fc : 612 -> 608
~ sub_100010584 -> sub_10001055c : 432 -> 428
~ sub_1000111a0 -> sub_100011174 : 692 -> 676
~ sub_100012d68 -> sub_100012d2c : 376 -> 372
~ sub_100013318 -> sub_1000132d8 : 3472 -> 3452
~ sub_100014e74 -> sub_100014e20 : 1312 -> 1308
~ sub_100016174 -> sub_10001611c : 668 -> 660
~ sub_100016410 -> sub_1000163b0 : 308 -> 304
~ sub_1000165e4 -> sub_100016580 : 316 -> 312
~ sub_1000167d4 -> sub_10001676c : 680 -> 676
~ sub_100016e18 -> sub_100016dac : 1004 -> 996
~ sub_1000178a0 -> sub_10001782c : 412 -> 408
~ sub_100017a3c -> sub_1000179c4 : 360 -> 356
~ sub_100017ba4 -> sub_100017b28 : 360 -> 356
~ sub_10001a5b4 -> sub_10001a534 : 492 -> 488
~ sub_10001ac3c -> sub_10001abb8 : 116 -> 108
~ sub_10001ad4c -> sub_10001acc0 : 8 -> 12
~ sub_10001ad54 -> sub_10001accc : 12 -> 8
~ sub_10001ea88 -> sub_10001e9fc : 764 -> 760
~ sub_10001edc8 -> sub_10001ed38 : 668 -> 664
~ sub_10001f2d0 -> sub_10001f23c : 604 -> 600
~ sub_1000202b8 -> sub_100020220 : 432 -> 428
~ sub_100020d5c -> sub_100020cc0 : 956 -> 952
~ sub_1000214c8 -> sub_100021428 : 828 -> 820
~ sub_100021a48 -> sub_1000219a0 : 2224 -> 2220
~ sub_10002348c -> sub_1000233e0 : 524 -> 532
~ sub_10002507c -> sub_100024fd8 : 1300 -> 1296
~ sub_10002c5e0 -> sub_10002c538 : 344 -> 340
~ sub_10002d584 -> sub_10002d4d8 : 4564 -> 4516
~ sub_100032ad0 -> sub_1000329f4 : 1092 -> 1084
CStrings:
+ "T@\"NSObject<OS_xpc_object>\",&"
+ "T@\"NSObject<OS_xpc_object>\",&,V_error"
- "T@\"NSObject<OS_xpc_object>\",&,N"
- "T@\"NSObject<OS_xpc_object>\",&,N,V_error"
```
