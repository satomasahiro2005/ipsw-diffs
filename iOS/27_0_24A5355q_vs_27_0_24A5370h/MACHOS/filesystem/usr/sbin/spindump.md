## spindump

> `/usr/sbin/spindump`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb7584` | `0xb76d0` | **`+0x14c`** |
| `__TEXT.__gcc_except_tab` | `0x2f20` | `0x2f24` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-435.0.0.0.0
+440.0.0.0.0
Functions:
~ sub_100001440 : 170300 -> 170444
~ sub_1000358f8 -> sub_100035988 : 5972 -> 6032
~ sub_100037378 -> sub_100037444 : 644 -> 640
~ sub_1000375fc -> sub_1000376c4 : 60 -> 56
~ sub_10003a570 -> sub_10003a634 : 18840 -> 18820
~ sub_10003ef20 -> sub_10003efd0 : 1700 -> 1696
~ sub_100041928 -> sub_1000419d4 : 912 -> 904
~ sub_100041db4 -> sub_100041e58 : 3672 -> 3668
~ sub_100042c0c -> sub_100042cac : 636 -> 632
~ sub_100042e88 -> sub_100042f24 : 9960 -> 9956
~ sub_100047d34 -> sub_100047dcc : 11656 -> 11644
~ sub_10005d210 -> sub_10005d29c : 19304 -> 19300
~ sub_100067d38 -> sub_100067dc0 : 14820 -> 14816
~ sub_100071378 -> sub_1000713fc : 188 -> 184
~ sub_100073f5c -> sub_100073fdc : 12160 -> 12332
~ sub_1000785b4 -> sub_1000786e0 : 2604 -> 2600
~ sub_100078fe0 -> sub_100079108 : 3224 -> 3228
~ sub_10007a048 -> sub_10007a174 : 3736 -> 3732
~ sub_10007c848 -> sub_10007c970 : 3072 -> 3068
~ sub_10007e154 -> sub_10007e278 : 240 -> 244
~ sub_10007ea44 -> sub_10007eb6c : 1536 -> 1532
~ sub_10009137c -> sub_1000914a0 : 1004 -> 1008
~ sub_100091768 -> sub_100091890 : 1296 -> 1292
~ sub_100091ec0 -> sub_100091fe4 : 3172 -> 3160
~ sub_1000931bc -> sub_1000932d4 : 32704 -> 32780
~ sub_10009b740 -> sub_10009b8a4 : 7380 -> 7372
~ sub_10009e98c -> sub_10009eae8 : 1176 -> 1172
~ sub_10009f1e0 -> sub_10009f338 : 1012 -> 1004
~ sub_1000b62e0 -> sub_1000b6430 : 468 -> 464
```
