## com.apple.CloudDocs.iCloudDriveFileProvider

> `/System/Library/PrivateFrameworks/CloudDocs.framework/PlugIns/com.apple.CloudDocs.iCloudDriveFileProvider.appex/com.apple.CloudDocs.iCloudDriveFileProvider`

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
~ sub_100008ae4 : 1060 -> 1056
~ sub_100008fa0 -> sub_100008f9c : 1088 -> 1096
~ sub_100009440 -> sub_100009444 : 1076 -> 1084
~ sub_10000a80c -> sub_10000a818 : 1440 -> 1436
~ sub_10000adac -> sub_10000adb4 : 3048 -> 3036
~ sub_10000be6c -> sub_10000be68 : 1004 -> 1000
~ sub_10000c8dc -> sub_10000c8d4 : 328 -> 324
~ sub_100010154 -> sub_100010148 : 436 -> 432
~ sub_1000132b8 -> sub_1000132a8 : 520 -> 516
~ sub_1000136dc -> sub_1000136c8 : 1260 -> 1252
~ sub_10001406c -> sub_100014050 : 1088 -> 1084
~ sub_100018144 -> sub_100018124 : 952 -> 960
~ sub_10001855c -> sub_100018544 : 964 -> 972
~ sub_100019248 -> sub_100019238 : 952 -> 960
~ sub_100019660 -> sub_100019658 : 964 -> 972
~ sub_10001e0a8 : 1964 -> 1988
~ sub_10001e854 -> sub_10001e86c : 256 -> 276
~ sub_10001e954 -> sub_10001e980 : 588 -> 616
~ sub_10001ed44 -> sub_10001ed8c : 2612 -> 2684
~ sub_10001f82c -> sub_10001f8bc : 372 -> 400
~ sub_10001f9a0 -> sub_10001fa4c : 312 -> 332
~ sub_10001fad8 -> sub_10001fb98 : 416 -> 448
~ sub_10001fee0 -> sub_10001ffc0 : 960 -> 968
CStrings:
+ "br_fileProviderErrorForDownloadFlowWithIsSpeculative:"
+ "processCanUseArbitraryPersonas"
- "lookupMinFileSizeForThumbnailTransferWithReply:"
```
