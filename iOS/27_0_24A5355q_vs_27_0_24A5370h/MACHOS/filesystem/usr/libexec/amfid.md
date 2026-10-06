## amfid

> `/usr/libexec/amfid`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21180` | `0x211c0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x2087` | `0x2090` | **`+0x9`** |

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
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1166.0.0.0.0
+1171.0.3.0.0
Symbols:
+ _swift_retain_x27
- _swift_retain_x23
Functions:
~ sub_100003b0c : 1172 -> 1164
~ sub_100007be4 -> sub_100007bdc : 2008 -> 2004
~ sub_1000083bc -> sub_1000083b0 : 1704 -> 1692
~ sub_10000af38 -> sub_10000af20 : 52 -> 56
~ sub_10000e63c -> sub_10000e628 : 700 -> 684
~ sub_100010294 -> sub_100010270 : 1456 -> 1444
~ sub_100010894 -> sub_100010864 : 864 -> 872
~ sub_1000119c4 -> sub_10001199c : 764 -> 768
~ sub_1000148b8 -> sub_100014894 : 280 -> 276
~ sub_10001526c -> sub_100015244 : 252 -> 276
~ sub_100015814 -> sub_100015804 : 908 -> 896
~ sub_100015cf8 -> sub_100015cdc : 2160 -> 2176
~ sub_100016840 -> sub_100016834 : 1128 -> 1184
~ sub_1000175e4 -> sub_100017610 : 2036 -> 2032
~ sub_100017dd8 -> sub_100017e00 : 1012 -> 1000
~ sub_100018994 -> sub_1000189b0 : 804 -> 792
~ sub_10001a064 -> sub_10001a074 : 904 -> 912
~ sub_10001a5f8 -> sub_10001a610 : 128 -> 140
~ sub_10001b594 -> sub_10001b5b8 : 708 -> 756
~ sub_10001e8dc -> sub_10001e930 : 3360 -> 3332
~ sub_10001f8bc -> sub_10001f8f4 : 1404 -> 1400
~ sub_10001fe38 -> sub_10001fe6c : 504 -> 496
~ sub_100020030 -> sub_10002005c : 468 -> 464
~ sub_100020204 -> sub_10002022c : 392 -> 400
~ sub_10002038c -> sub_1000203bc : 648 -> 652
~ sub_1000216bc -> sub_1000216f0 : 520 -> 532
CStrings:
+ "Error draining certificate entry fields"
- "Expected OCTET STRING for akid"
```
