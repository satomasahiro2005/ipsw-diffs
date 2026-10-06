## misd

> `/usr/libexec/misd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21bbc` | `0x21c28` | **`+0x6c`** |
| `__TEXT.__cstring` | `0xb5c4` | `0xb5f4` | **`+0x30`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-394.0.0.0.0
+396.0.0.0.0

-  CStrings:  1749
+  CStrings:  1750
Functions:
~ sub_100002c2c : 540 -> 528
~ sub_100004b88 -> sub_100004b7c : 968 -> 964
~ sub_100007808 -> sub_1000077f8 : 332 -> 352
~ sub_1000079b8 -> sub_1000079bc : 460 -> 492
~ sub_10000ebe8 -> sub_10000ec0c : 168 -> 160
~ sub_10000f994 -> sub_10000f9b0 : 372 -> 368
~ sub_100013330 -> sub_100013348 : 1428 -> 1444
~ sub_100014270 -> sub_100014298 : 188 -> 236
~ sub_100014738 -> sub_100014790 : 1136 -> 1144
~ sub_100014be4 -> sub_100014c44 : 576 -> 580
~ sub_100015cc4 -> sub_100015d28 : 1096 -> 1104
~ sub_100018180 -> sub_1000181ec : 772 -> 752
~ sub_100019ee4 -> sub_100019f3c : 816 -> 820
~ sub_10001a6ac -> sub_10001a708 : 864 -> 860
~ sub_10001c588 -> sub_10001c5e0 : 596 -> 600
~ sub_10001ec14 -> sub_10001ec70 : 272 -> 288
CStrings:
+ "%s: refcnt=%d but pdp invalid for %s; restoring"
```
