## com.apple.fskit.msdos

> `/System/Library/ExtensionKit/Extensions/com.apple.fskit.msdos.appex/com.apple.fskit.msdos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15444` | `0x1570c` | **`+0x2c8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-844.0.0.0.0
+845.0.0.0.0
Functions:
~ _CONV_UTF8ToUnistr255 : 1364 -> 1352
~ sub_100002de8 -> sub_100002ddc : 88 -> 96
~ _CONV_Unistr255ToUTF8 : 840 -> 884
~ _CONV_ConvertToFSM : 124 -> 120
~ _CONV_LabelUTF8ToUTF16LocalEncoding : 344 -> 328
~ sub_100003c4c -> sub_100003c60 : 5952 -> 6544
~ sub_10000538c -> sub_1000055f0 : 288 -> 284
~ sub_10000569c -> sub_1000058fc : 320 -> 316
~ _fat_init : 1008 -> 1016
~ sub_100005dec -> sub_100006050 : 156 -> 152
~ sub_100005e88 -> sub_1000060e8 : 248 -> 244
~ _fat_free_unused : 520 -> 516
~ _getstdfmt : 160 -> 200
~ sub_100008b4c -> sub_100008dcc : 1076 -> 1100
~ sub_100009104 -> sub_10000939c : 332 -> 336
~ sub_100009390 -> sub_10000962c : 244 -> 252
~ _locateFsckMessage : 160 -> 176
~ _locateNewfsMessage : 172 -> 188
~ _msdosfs_dos2unixtime : 232 -> 228
~ _msdosfs_unicode2dos : 324 -> 320
~ _msdosfs_dos2unicodefn : 316 -> 276
~ _msdosfs_unicode_to_dos_name : 960 -> 984
~ _msdosfs_apply_generation_to_short_name : 192 -> 176
~ _msdosfs_unicode2winfn : 232 -> 248
~ _msdosfs_getunicodefn : 284 -> 324
~ sub_10000e650 -> sub_10000e924 : 96 -> 88
~ sub_10000ee20 -> sub_10000f0ec : 1576 -> 1572
~ sub_10000f448 -> sub_10000f710 : 128 -> 124
~ sub_10000f970 -> sub_10000fc34 : 1752 -> 1760
~ sub_100013068 -> sub_100013334 : 2116 -> 2112
```
