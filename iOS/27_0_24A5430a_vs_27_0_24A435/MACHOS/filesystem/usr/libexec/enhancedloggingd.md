## enhancedloggingd

> `/usr/libexec/enhancedloggingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb4114` | `0xb417c` | **`+0x68`** |
| `__TEXT.__objc_stubs` | `0x33a0` | `0x3380` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x4b6d` | `0x4b5d` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x1018` | `0x1010` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x9d8` | `0x9d0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   985
-  CStrings:  1411
+  Symbols:   984
+  CStrings:  1410
Symbols:
+ _swift_release_x11
- _AKSeedBuildHeaderKey
- _swift_release_x10
Functions:
~ sub_10002e350 : 752 -> 756
~ sub_100036d30 -> sub_100036d34 : 724 -> 732
~ sub_100037014 -> sub_100037020 : 5712 -> 5716
~ sub_100038be8 -> sub_100038bf8 : 1340 -> 1344
~ sub_100039124 -> sub_100039138 : 3964 -> 3980
~ sub_10003a0a0 -> sub_10003a0c4 : 636 -> 648
~ sub_10003ad80 -> sub_10003adb0 : 1024 -> 1028
~ sub_10003b4c4 -> sub_10003b4f8 : 724 -> 732
~ sub_10003b798 -> sub_10003b7d4 : 2252 -> 2304
~ sub_10004999c -> sub_100049a0c : 3568 -> 3444
~ sub_100062fe0 -> sub_100062fd4 : 1476 -> 1480
~ sub_100075590 -> sub_100075588 : 1052 -> 1060
~ sub_100077af0 : 748 -> 752
~ sub_1000783e0 -> sub_1000783e4 : 360 -> 364
~ sub_100078548 -> sub_100078550 : 340 -> 344
~ sub_10007869c -> sub_1000786a8 : 648 -> 652
~ sub_100078938 -> sub_100078948 : 344 -> 348
~ sub_100078a90 -> sub_100078aa4 : 356 -> 360
~ sub_100078d6c -> sub_100078d84 : 380 -> 384
~ sub_10007928c -> sub_1000792a8 : 444 -> 448
~ sub_10007944c -> sub_10007946c : 376 -> 380
~ sub_10007f270 -> sub_10007f294 : 7268 -> 7320
~ sub_1000954b4 -> sub_10009550c : 992 -> 984
~ sub_100098a78 -> sub_100098ac8 : 664 -> 668
~ sub_100099d2c -> sub_100099d80 : 708 -> 712
~ sub_10009a8dc -> sub_10009a934 : 2972 -> 2976
~ sub_10009b478 -> sub_10009b4d4 : 2960 -> 2964
~ sub_1000a9574 -> sub_1000a95d4 : 680 -> 684
~ sub_1000a981c -> sub_1000a9880 : 692 -> 696
CStrings:
- "shouldHideSeedBuildHeader"
```
