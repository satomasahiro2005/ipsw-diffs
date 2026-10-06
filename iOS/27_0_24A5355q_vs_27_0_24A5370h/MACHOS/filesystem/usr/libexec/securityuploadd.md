## securityuploadd

> `/usr/libexec/securityuploadd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12e58` | `0x12df8` | **`-0x60`** |
| `__TEXT.__cstring` | `0xf9c` | `0xf99` | **`-0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-62426.0.0.0.4
+62460.0.22.0.0
Functions:
~ sub_100003704 : 260 -> 256
~ sub_100003bbc -> sub_100003bb8 : 1000 -> 988
~ sub_100004918 -> sub_100004908 : 2092 -> 2088
~ sub_1000054f0 -> sub_1000054dc : 380 -> 376
~ sub_1000059e0 -> sub_1000059c8 : 704 -> 700
~ sub_100005ea0 -> sub_100005e84 : 692 -> 684
~ sub_1000066f8 -> sub_1000066d4 : 1144 -> 1136
~ sub_100007334 -> sub_100007308 : 408 -> 404
~ sub_10000776c -> sub_10000773c : 724 -> 720
~ sub_1000085a8 -> sub_100008574 : 280 -> 276
~ sub_100008d24 -> sub_100008cec : 508 -> 504
~ sub_100009590 -> sub_100009554 : 576 -> 572
~ sub_100009e7c -> sub_100009e3c : 1896 -> 1892
~ sub_10000a5e4 -> sub_10000a5a0 : 280 -> 276
~ sub_10000a9f4 -> sub_10000a9ac : 564 -> 560
~ sub_10000ac28 -> sub_10000abdc : 420 -> 416
~ sub_10000aefc -> sub_10000aeac : 804 -> 800
~ sub_10000b220 -> sub_10000b1cc : 808 -> 804
~ sub_10000b704 -> sub_10000b6ac : 432 -> 428
~ sub_10000b8b4 -> sub_10000b858 : 856 -> 852
~ sub_10000bc20 -> sub_10000bbc0 : 912 -> 908
~ sub_10000c004 -> sub_10000bfa0 : 656 -> 652
~ sub_10000cfd8 -> sub_10000cf70 : 956 -> 952
~ sub_100011664 -> sub_1000115f8 : 476 -> 480
~ sub_10001190c -> sub_1000118a4 : 280 -> 276
~ sub_1000123d8 -> sub_10001236c : 256 -> 264
~ sub_10001353c -> sub_1000134d8 : 128 -> 136
~ sub_1000135bc -> sub_100013560 : 664 -> 660
CStrings:
+ "62460.0.22"
- "62426.0.0.0.4"
```
