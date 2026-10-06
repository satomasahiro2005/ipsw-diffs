## searchdiagnose

> `/usr/bin/searchdiagnose`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28afc` | `0x28c8c` | **`+0x190`** |
| `__TEXT.__auth_stubs` | `0x1580` | `0x1590` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xac8` | `0xad0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
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
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2444.104.0.0.0
+2448.100.0.0.0

-  Symbols:   591
+  Symbols:   592
Symbols:
+ _swift_release_x9
+ _swift_retain_x27
- _objc_retain_x22
Functions:
~ sub_100002e38 : 5776 -> 5772
~ sub_100004658 -> sub_100004654 : 280 -> 296
~ sub_100004770 -> sub_10000477c : 256 -> 264
~ sub_100005024 -> sub_100005038 : 344 -> 348
~ sub_1000052fc -> sub_100005314 : 768 -> 756
~ sub_1000055fc -> sub_100005608 : 1592 -> 1556
~ sub_100005c34 -> sub_100005c1c : 436 -> 444
~ sub_100005de8 -> sub_100005dd8 : 308 -> 316
~ sub_100005f1c -> sub_100005f14 : 628 -> 648
~ sub_100006190 -> sub_10000619c : 628 -> 648
~ sub_100006404 -> sub_100006424 : 540 -> 544
~ sub_100006620 -> sub_100006644 : 1160 -> 1184
~ sub_100008554 -> sub_100008590 : 5628 -> 5616
~ sub_100009b50 -> sub_100009b80 : 2080 -> 2116
~ sub_10000a370 -> sub_10000a3c4 : 2244 -> 2284
~ sub_10000cbb8 -> sub_10000cc34 : 5312 -> 5364
~ sub_10000e078 -> sub_10000e128 : 5332 -> 5464
~ sub_10000f980 -> sub_10000fab4 : 124 -> 132
~ sub_100013960 -> sub_100013a9c : 3556 -> 3552
~ sub_100014bf8 -> sub_100014d30 : 1592 -> 1556
~ sub_100015230 -> sub_100015344 : 1288 -> 1232
~ sub_100015738 -> sub_100015814 : 436 -> 444
~ sub_1000158ec -> sub_1000159d0 : 280 -> 292
~ sub_100015a04 -> sub_100015af4 : 628 -> 648
~ sub_100015c78 -> sub_100015d7c : 640 -> 660
~ sub_100015ef8 -> sub_100016010 : 1160 -> 1184
~ sub_100016380 -> sub_1000164b0 : 724 -> 728
~ sub_100017064 -> sub_100017198 : 2012 -> 1996
~ sub_100019238 -> sub_10001935c : 1320 -> 1328
~ sub_10001b194 -> sub_10001b2c0 : 172 -> 176
~ sub_10001eb78 -> sub_10001eca8 : 304 -> 300
~ sub_10001efd8 -> sub_10001f104 : 256 -> 276
~ sub_100021a1c -> sub_100021b5c : 1300 -> 1328
~ sub_100022658 -> sub_1000227b4 : 948 -> 960
~ sub_1000255ac -> sub_100025714 : 800 -> 812
~ sub_100027e8c -> sub_100028000 : 280 -> 276
~ sub_100028470 -> sub_1000285e0 : 344 -> 348
~ sub_1000288e8 -> sub_100028a5c : 352 -> 348
~ sub_100028be8 -> sub_100028d58 : 228 -> 240
~ sub_100028ccc -> sub_100028e48 : 236 -> 256
~ sub_100028db8 -> sub_100028f48 : 272 -> 276
~ sub_100028ec8 -> sub_10002905c : 584 -> 580
```
