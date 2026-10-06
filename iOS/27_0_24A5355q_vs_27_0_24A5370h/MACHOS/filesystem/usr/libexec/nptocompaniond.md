## nptocompaniond

> `/usr/libexec/nptocompaniond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x58c1` | `0x5911` | **`+0x50`** |
| `__TEXT.__text` | `0x6871c` | `0x68760` | **`+0x44`** |
| `__TEXT.__objc_stubs` | `0x4660` | `0x46a0` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x15b8` | `0x15c8` | **`+0x10`** |
| `__TEXT.__const` | `0x2570` | `0x2580` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x26e8` | `0x26e0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1990` | `0x1988` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2024.100.11.0.0
+2024.100.12.0.0

-  CStrings:  1696
+  CStrings:  1698
Functions:
~ sub_1000023c0 : 736 -> 732
~ sub_100004708 -> sub_100004704 : 3396 -> 3372
~ sub_10000708c -> sub_100007070 : 1060 -> 1056
~ sub_100008000 -> sub_100007fe0 : 2112 -> 2108
~ sub_100009194 -> sub_100009170 : 4932 -> 4928
~ sub_10000acf0 -> sub_10000acc8 : 424 -> 420
~ sub_10000b834 -> sub_10000b808 : 536 -> 532
~ sub_10000ba4c -> sub_10000ba1c : 1216 -> 1212
~ sub_10000bf0c -> sub_10000bed8 : 608 -> 604
~ sub_10000c840 -> sub_10000c808 : 1000 -> 992
~ sub_10000d09c -> sub_10000d05c : 1372 -> 1368
~ sub_10000dffc -> sub_10000dfb8 : 256 -> 264
~ sub_10000e2fc -> sub_10000e2c0 : 116 -> 132
~ sub_100012e2c -> sub_100012e00 : 280 -> 276
~ sub_1000136a8 -> sub_100013678 : 456 -> 460
~ sub_1000138a8 -> sub_10001387c : 280 -> 292
~ sub_1000139c0 -> sub_1000139a0 : 460 -> 464
~ sub_100015f38 -> sub_100015f1c : 1356 -> 1364
~ sub_100016fa0 -> sub_100016f8c : 1288 -> 1296
~ sub_100017da8 -> sub_100017d9c : 344 -> 340
~ sub_100018028 -> sub_100018018 : 420 -> 640
~ sub_1000185f0 -> sub_1000186bc : 152 -> 164
~ sub_10001e4b4 -> sub_10001e58c : 484 -> 476
~ sub_10002381c -> sub_1000238ec : 664 -> 656
~ sub_100023d00 -> sub_100023dc8 : 448 -> 440
~ sub_100023fbc -> sub_10002407c : 504 -> 496
~ sub_1000242bc -> sub_100024374 : 440 -> 432
~ sub_100024eb0 -> sub_100024f60 : 284 -> 280
~ sub_1000264e4 -> sub_100026590 : 644 -> 640
~ sub_10002847c -> sub_100028524 : 280 -> 276
~ sub_100028594 -> sub_100028638 : 356 -> 352
~ sub_1000286f8 -> sub_100028798 : 804 -> 796
~ sub_100028b28 -> sub_100028bc0 : 412 -> 408
~ sub_10002a7d4 -> sub_10002a868 : 1056 -> 1048
~ sub_10002abf4 -> sub_10002ac80 : 508 -> 504
~ sub_10002b714 -> sub_10002b79c : 204 -> 200
~ sub_10002caa8 -> sub_10002cb2c : 716 -> 712
~ sub_100030e78 -> sub_100030ef8 : 404 -> 400
~ sub_10003120c -> sub_100031288 : 276 -> 272
~ sub_1000313c4 -> sub_10003143c : 316 -> 312
~ sub_10003159c -> sub_100031610 : 260 -> 256
~ sub_100031858 -> sub_1000318c8 : 420 -> 416
~ sub_10003fa68 -> sub_10003fad4 : 108 -> 104
~ sub_100040998 -> sub_100040a00 : 668 -> 664
~ sub_100043280 -> sub_1000432e4 : 576 -> 580
~ sub_100051b74 -> sub_100051bdc : 340 -> 336
~ sub_100051f70 -> sub_100051fd4 : 140 -> 152
~ sub_100053934 -> sub_1000539a4 : 316 -> 312
~ sub_100057768 -> sub_1000577d4 : 528 -> 516
~ sub_100058e64 -> sub_100058ec4 : 92 -> 100
~ sub_100058ec0 -> sub_100058f28 : 592 -> 608
~ sub_10005913c -> sub_1000591b4 : 220 -> 228
~ sub_10005c888 -> sub_10005c908 : 44 -> 36
~ sub_10005c928 -> sub_10005c9a0 : 24 -> 20
~ sub_10005c96c -> sub_10005c9e0 : 28 -> 24
~ sub_10005d2b8 -> sub_10005d328 : 668 -> 652
~ sub_10005e370 -> sub_10005e3d0 : 896 -> 888
~ sub_10005efa0 -> sub_10005eff8 : 576 -> 572
~ sub_10005f24c -> sub_10005f2a0 : 652 -> 636
~ sub_10005f8e4 -> sub_10005f928 : 300 -> 316
~ sub_100060048 -> sub_10006009c : 928 -> 920
~ sub_100063b00 -> sub_100063b4c : 380 -> 376
~ sub_100063c7c -> sub_100063cc4 : 416 -> 408
~ sub_100063e1c -> sub_100063e5c : 392 -> 384
~ sub_100064198 -> sub_1000641d0 : 140 -> 148
~ sub_100067260 -> sub_1000672a0 : 140 -> 148
~ sub_1000688a4 -> sub_1000688ec : 2640 -> 2632
~ sub_100069ee4 -> sub_100069f24 : 476 -> 480
CStrings:
+ "andPredicateWithSubpredicates:"
+ "predicateForAllFeaturedStateEnabledSuggestionTypesForWidget"
```
