## com.apple.CloudDocs.iCloudDriveFileProviderManaged

> `/System/Library/PrivateFrameworks/CloudDocs.framework/PlugIns/com.apple.CloudDocs.iCloudDriveFileProviderManaged.appex/com.apple.CloudDocs.iCloudDriveFileProviderManaged`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23d38` | `0x23e20` | **`+0xe8`** |
| `__DATA.__objc_const` | `0x7db8` | `0x7d70` | **`-0x48`** |
| `__TEXT.__objc_stubs` | `0x2c40` | `0x2c80` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x10a8` | `0x10d0` | **`+0x28`** |
| `__TEXT.__objc_methname` | `0x5360` | `0x5385` | **`+0x25`** |
| `__TEXT.__auth_stubs` | `0x620` | `0x610` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x1e2c` | `0x1e1c` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x1278` | `0x1280` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x320` | `0x318` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x23b4` | `0x23b8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-5044.0.0.0.0
+5140.0.0.0.0

-  Symbols:   187
-  CStrings:  1438
+  Symbols:   186
+  CStrings:  1439
Symbols:
- _voucher_process_can_use_arbitrary_personas
Functions:
~ sub_100006c8c : 1440 -> 1436
~ sub_10000722c -> sub_100007228 : 3048 -> 3036
~ sub_1000082ec -> sub_1000082dc : 1004 -> 1000
~ sub_100008d5c -> sub_100008d48 : 328 -> 324
~ sub_10000bbfc -> sub_10000bbe4 : 436 -> 432
~ sub_10000e414 -> sub_10000e3f8 : 1964 -> 1988
~ sub_10000ebc0 -> sub_10000ebbc : 256 -> 276
~ sub_10000ecc0 -> sub_10000ecd0 : 588 -> 616
~ sub_10000f0b0 -> sub_10000f0dc : 2612 -> 2684
~ sub_10000fb98 -> sub_10000fc0c : 372 -> 400
~ sub_10000fd0c -> sub_10000fd9c : 312 -> 332
~ sub_10000fe44 -> sub_10000fee8 : 416 -> 448
~ sub_10001024c -> sub_100010310 : 960 -> 968
~ sub_100014348 -> sub_100014414 : 520 -> 516
~ sub_10001476c -> sub_100014834 : 1260 -> 1252
~ sub_1000150fc -> sub_1000151bc : 1088 -> 1084
~ sub_10001af9c -> sub_10001b058 : 952 -> 960
~ sub_10001b3b4 -> sub_10001b478 : 964 -> 972
~ sub_10001c5e8 -> sub_10001c6b4 : 952 -> 960
~ sub_10001ca00 -> sub_10001cad4 : 964 -> 972
~ sub_10001f118 -> sub_10001f1f4 : 1060 -> 1056
~ sub_10001f5d4 -> sub_10001f6ac : 1088 -> 1096
~ sub_10001fa74 -> sub_10001fb54 : 1076 -> 1084
CStrings:
+ "br_fileProviderErrorForDownloadFlowWithIsSpeculative:"
+ "processCanUseArbitraryPersonas"
- "lookupMinFileSizeForThumbnailTransferWithReply:"
```
