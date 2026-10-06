## FreeformSharingExtension

> `/private/var/staged_system_apps/Freeform.app/PlugIns/FreeformSharingExtension.appex/FreeformSharingExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x87cf8` | `0x87ccc` | **`-0x2c`** |
| `__TEXT.__cstring` | `0x2901` | `0x2921` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x160b` | `0x162b` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x1bdc` | `0x1bf4` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x2340` | `0x2350` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x11b0` | `0x11b8` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x3a88` | `0x3a80` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-646.0.0.202.4
+649.0.0.0.3

-  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  CStrings:  1139
+  CStrings:  1140
Symbols:
+ _objc_retain_x10
- __swift_FORCE_LOAD_$_swiftNaturalLanguage
Functions:
~ sub_100003928 -> sub_1000038d8 : 1856 -> 1852
~ sub_100004228 -> sub_1000041d4 : 1136 -> 1132
~ sub_100005aa0 -> sub_100005a48 : 280 -> 276
~ sub_100005bb8 -> sub_100005b5c : 288 -> 284
~ sub_100005d34 -> sub_100005cd4 : 624 -> 620
~ sub_100006000 -> sub_100005f9c : 508 -> 504
~ sub_10000bddc -> sub_10000bd74 : 788 -> 784
~ sub_100011ab8 -> sub_100011a4c : 996 -> 1000
~ sub_10001224c -> sub_1000121e4 : 1152 -> 1148
~ sub_100012bf4 -> sub_100012b88 : 3816 -> 3792
~ sub_100013adc -> sub_100013a58 : 800 -> 804
~ sub_10001689c -> sub_10001681c : 140 -> 148
~ sub_100017fac -> sub_100017f34 : 1608 -> 1624
~ sub_10001a3fc -> sub_10001a394 : 104 -> 96
~ sub_100028dec -> sub_100028d7c : 136 -> 144
~ sub_100028e74 -> sub_100028e0c : 220 -> 232
~ sub_100028f50 -> sub_100028ef4 : 540 -> 552
~ sub_1000293f0 -> sub_1000293a0 : 292 -> 312
~ sub_100029514 -> sub_1000294d8 : 2420 -> 2408
~ sub_10002d708 -> sub_10002d6c0 : 2756 -> 2764
~ sub_10002e1cc -> sub_10002e18c : 1344 -> 1356
~ sub_10002e70c -> sub_10002e6d8 : 1024 -> 1048
~ sub_10002edac -> sub_10002ed90 : 936 -> 932
~ sub_10002fc8c -> sub_10002fc6c : 692 -> 700
~ sub_100033a30 -> sub_100033a18 : 684 -> 692
~ sub_100033cdc -> sub_100033ccc : 1016 -> 1028
~ sub_1000340d4 -> sub_1000340d0 : 1172 -> 1176
~ sub_100034568 : 1128 -> 1140
~ sub_1000349d0 -> sub_1000349dc : 1032 -> 1048
~ sub_100034dd8 -> sub_100034df4 : 1184 -> 1200
~ sub_100035278 -> sub_1000352a4 : 1144 -> 1176
~ sub_1000362a8 -> sub_1000362f4 : 480 -> 484
~ sub_100045c10 -> sub_100045c60 : 80 -> 76
~ sub_100046088 -> sub_1000460d4 : 1172 -> 1144
~ sub_10004651c -> sub_10004654c : 648 -> 652
~ sub_1000467a4 -> sub_1000467d8 : 196 -> 212
~ sub_100048c6c -> sub_100048cb0 : 476 -> 480
~ sub_10004af14 -> sub_10004af5c : 21188 -> 20768
~ sub_100052b2c -> sub_1000529d0 : 2308 -> 2352
~ sub_1000548e4 -> sub_1000547b4 : 472 -> 480
~ sub_100054b50 -> sub_100054a28 : 648 -> 668
~ sub_100054dd8 -> sub_100054cc4 : 88 -> 92
~ sub_100054e34 -> sub_100054d24 : 1708 -> 1756
~ sub_1000554e0 -> sub_100055400 : 3472 -> 3500
~ sub_10005653c -> sub_100056478 : 3000 -> 3032
~ sub_1000575a8 -> sub_100057504 : 1772 -> 1848
~ sub_100059f90 -> sub_100059f38 : 10332 -> 10392
~ sub_10005c7ec -> sub_10005c7d0 : 1480 -> 1500
~ sub_10005e0dc -> sub_10005e0d4 : 4084 -> 4092
~ sub_100060660 : 160 -> 168
~ sub_100061518 -> sub_100061520 : 500 -> 512
~ sub_10006170c -> sub_100061720 : 504 -> 512
~ sub_100061904 -> sub_100061920 : 116 -> 132
~ sub_1000629f8 -> sub_100062a24 : 2224 -> 2220
~ sub_1000633a4 -> sub_1000633cc : 1804 -> 1796
~ sub_100063ab0 -> sub_100063ad0 : 1788 -> 1780
~ sub_100065f0c -> sub_100065f24 : 7372 -> 7300
~ sub_100068a6c -> sub_100068a3c : 1772 -> 1784
~ sub_10006f4e4 -> sub_10006f4c0 : 5596 -> 5640
~ sub_100070ac0 -> sub_100070ac8 : 400 -> 420
~ sub_1000774fc -> sub_100077518 : 312 -> 316
~ sub_100078d2c -> sub_100078d4c : 2916 -> 2956
~ sub_100079b24 -> sub_100079b6c : 3948 -> 3840
~ sub_10007aa90 -> sub_10007aa6c : 6456 -> 6248
~ sub_10007c3c8 -> sub_10007c2d4 : 1448 -> 1444
~ sub_10007c970 -> sub_10007c878 : 2620 -> 2688
~ sub_10007d3ac -> sub_10007d2f8 : 684 -> 704
~ sub_10007d658 -> sub_10007d5b8 : 2880 -> 2884
~ sub_10007e198 -> sub_10007e0fc : 2840 -> 2824
~ sub_1000851bc -> sub_100085110 : 620 -> 632
~ sub_10008706c -> sub_100086fcc : 468 -> 472
~ sub_100087c64 -> sub_100087bc8 : 116 -> 124
~ sub_100087cd8 -> sub_100087c44 : 148 -> 156
~ sub_100088130 -> sub_1000880a4 : 136 -> 152
CStrings:
+ "hasUnnavigableAncestor"
```
