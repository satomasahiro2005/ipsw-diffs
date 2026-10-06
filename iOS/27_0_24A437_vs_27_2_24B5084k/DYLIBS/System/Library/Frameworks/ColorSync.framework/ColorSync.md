## ColorSync

> `/System/Library/Frameworks/ColorSync.framework/ColorSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68abc` | `0x6a128` | **`+0x166c`** |
| `__AUTH_CONST.__cfstring` | `0x4de0` | `0x4d20` | **`-0xc0`** |
| `__TEXT.__cstring` | `0x7144` | `0x7099` | **`-0xab`** |
| `__TEXT.__unwind_info` | `0x12b8` | `0x12e8` | **`+0x30`** |
| `__TEXT.__const` | `0x122910` | `0x122908` | **`-0x8`** |

### Other Changes

```diff

-3929.0.0.0.0
+3929.1.3.0.0

-  Functions: 1729
-  Symbols:   3085
-  CStrings:  905
+  Functions: 1746
+  Symbols:   3102
+  CStrings:  899
Symbols:
+ GCC_except_table1000
+ GCC_except_table1017
+ GCC_except_table1025
+ GCC_except_table1028
+ GCC_except_table1034
+ GCC_except_table1117
+ GCC_except_table1134
+ GCC_except_table1179
+ GCC_except_table1182
+ GCC_except_table1187
+ GCC_except_table1188
+ GCC_except_table1189
+ GCC_except_table1197
+ GCC_except_table1236
+ GCC_except_table1238
+ GCC_except_table1239
+ GCC_except_table1246
+ GCC_except_table1248
+ GCC_except_table1251
+ GCC_except_table1298
+ GCC_except_table1302
+ GCC_except_table1303
+ GCC_except_table1304
+ GCC_except_table1321
+ GCC_except_table1355
+ GCC_except_table1363
+ GCC_except_table1368
+ GCC_except_table1369
+ GCC_except_table1370
+ GCC_except_table1372
+ GCC_except_table1373
+ GCC_except_table1374
+ GCC_except_table1375
+ GCC_except_table1376
+ GCC_except_table1384
+ GCC_except_table298
+ GCC_except_table302
+ GCC_except_table339
+ GCC_except_table344
+ GCC_except_table348
+ GCC_except_table392
+ GCC_except_table394
+ GCC_except_table786
+ GCC_except_table787
+ GCC_except_table790
+ GCC_except_table791
+ GCC_except_table805
+ GCC_except_table808
+ GCC_except_table809
+ GCC_except_table811
+ GCC_except_table828
+ GCC_except_table830
+ GCC_except_table831
+ GCC_except_table841
+ GCC_except_table842
+ GCC_except_table869
+ GCC_except_table891
+ GCC_except_table893
+ GCC_except_table987
+ _AppleCMMEvaluateProfileGamma
+ _ColorSyncProfileCreateHDRProfileDescription
+ _ColorSyncProfileGetContentHeadroom
+ _ColorSyncProfileGetFlexGTCHeadroom
+ _ColorSyncProfileGetISO5AverageLightLevel
+ _ColorSyncProfileGetISO5Headroom
+ _ColorSyncProfileGetMetaAndHAGCMD5
+ _applyHAGCurveDescriptionAndHeader
+ _bt2020_normalized_float_from_dictionary
+ _create_content_light_level_dict
+ _create_content_reference_white_dict
+ _create_copy_with_hagc_reference_white_patched
+ _create_iso5_dicts_from_headroom_reference_white_pair
+ _create_iso5_meta_tag_data
+ _get_D50_XYZ_for_cicp_primaries
+ _headroom_reference_white_pair_from_hagc
+ _headroom_reference_white_pair_from_iso5_metadata
+ _kColorSyncDerivedISO5Metadata
+ _reference_white_from_iso5_metadata
+ _strip_flexGTC_tag_in_place
- GCC_except_table1009
- GCC_except_table1012
- GCC_except_table1018
- GCC_except_table1101
- GCC_except_table1118
- GCC_except_table1163
- GCC_except_table1166
- GCC_except_table1171
- GCC_except_table1172
- GCC_except_table1173
- GCC_except_table1181
- GCC_except_table1220
- GCC_except_table1222
- GCC_except_table1223
- GCC_except_table1230
- GCC_except_table1232
- GCC_except_table1235
- GCC_except_table1282
- GCC_except_table1286
- GCC_except_table1287
- GCC_except_table1288
- GCC_except_table1305
- GCC_except_table1338
- GCC_except_table1339
- GCC_except_table1340
- GCC_except_table1347
- GCC_except_table1352
- GCC_except_table1353
- GCC_except_table1357
- GCC_except_table1358
- GCC_except_table1359
- GCC_except_table1367
- GCC_except_table166
- GCC_except_table282
- GCC_except_table286
- GCC_except_table323
- GCC_except_table328
- GCC_except_table332
- GCC_except_table376
- GCC_except_table378
- GCC_except_table770
- GCC_except_table771
- GCC_except_table774
- GCC_except_table775
- GCC_except_table776
- GCC_except_table777
- GCC_except_table789
- GCC_except_table795
- GCC_except_table812
- GCC_except_table814
- GCC_except_table815
- GCC_except_table825
- GCC_except_table826
- GCC_except_table853
- GCC_except_table875
- GCC_except_table877
- GCC_except_table971
- GCC_except_table984
- GCC_except_table985
- _create_name_from_cicp_and_md5
- _get_hagc_data_md5
- _kColorSyncMetadataDisplayName
CStrings:
+ "HDR Metadata"
+ "com.apple.cmm.DerivedISO5Metadata"
- "Adaptive Gain Curve"
- "Adaptive Soft Clip Curve"
- "Content Color Volume"
- "Content HDR Reference White Luminance"
- "Content Light Level"
- "Headroom Adaptive Gain Curve"
- "Mastering Display Color Volume"
- "com.apple.cmm.MetadataDisplayName"
```
