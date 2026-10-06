## CoreData

> `/System/Library/Frameworks/CoreData.framework/CoreData`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x331c7c` | `0x331668` | **`-0x614`** |
| `__AUTH.__objc_data` | `0x32d8` | `0x2e78` | **`-0x460`** |
| `__DATA_DIRTY.__objc_data` | `0x63c8` | `0x6828` | **`+0x460`** |
| `__TEXT.__cstring` | `0x3bfde` | `0x3c105` | **`+0x127`** |
| `__TEXT.__gcc_except_tab` | `0x1883c` | `0x188cc` | **`+0x90`** |
| `__AUTH.__data` | `0x238` | `0x1e8` | **`-0x50`** |
| `__DATA_DIRTY.__bss` | `0x6c0` | `0x6e8` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1fde0` | `0x1fe00` | **`+0x20`** |
| `__DATA.__bss` | `0x16d0` | `0x16b0` | **`-0x20`** |
| `__DATA_DIRTY.__data` | `0x5a0` | `0x5b0` | **`+0x10`** |
| `__TEXT.__const` | `0x2e30` | `0x2e20` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x12d0` | `0x12c6` | **`-0xa`** |
| `__DATA.__common` | `0x650` | `0x658` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x7808` | `0x7800` | **`-0x8`** |

### Other Changes

```diff

-1632.0.0.0.0
+1633.0.0.0.0

-  Functions: 9351
-  Symbols:   17632
-  CStrings:  8341
+  Functions: 9347
+  Symbols:   17626
+  CStrings:  8342
Symbols:
+ _$s8CoreData13CDSwiftResultV8populate4from5using14columnMetadata14requestContext11moidFactory03oidM0ySo18FetchResultsRow_stVz_So0O10EntityPlanazSayAA06ColumnI0VGSo017NSSQLFetchRequestK0CSo17NSManagedObjectIDCs5Int64VXEAuWcSo11NSSQLEntityCXEtF014$ss5Int64VSo17xY20IDCIegnr_AbDIegyo_TRAwUIegnr_056$sSo11NSSQLEntityCxq_Ri_zRi0_zRi__Ri0__r0_lys5Int64VSo17xY34IDCIsegnr_Iegnr_AbdFIegyo_Ieggo_TRAYxq_Ri_zRi0_zRi__Ri0__r0_lyAwUIsegnr_Iegnr_Tf1nnnnEEn_n
+ _$s8CoreData13CDSwiftResultV8populate4from5using14columnMetadata14requestContext11moidFactory03oidM0ySo18FetchResultsRow_stVz_So0O10EntityPlanazSayAA06ColumnI0VGSo017NSSQLFetchRequestK0CSo17NSManagedObjectIDCs5Int64VXEAuWcSo11NSSQLEntityCXEtFys4SpanVySo0ouT0aGXEfU_
+ _$sSD8IteratorV8_VariantOySSSo21NSPropertyDescriptionC__GWOe
- _$s8CoreData13CDSwiftResultV8populate4from5using14columnMetadata16compositeIndices14requestContext11moidFactory03oidO0ySo18FetchResultsRow_stVz_So0Q10EntityPlanazSayAA06ColumnI0VGs15ContiguousArrayVySiGSo017NSSQLFetchRequestM0CSo17NSManagedObjectIDCs5Int64VXEAYA_cSo11NSSQLEntityCXEtF49$ss5Int64VSo17NSManagedObjectIDCIegnr_AbDIegyo_TRA_AYIegnr_105$sSo11NSSQLEntityCxq_Ri_zRi0_zRi__Ri0__r0_lys5Int64VSo17NSManagedObjectIDCIsegnr_Iegnr_AbdFIegyo_Ieggo_TRA1_xq_Ri_zRi0_zRi__Ri0__r0_lyA_AYIsegnr_Iegnr_Tf1nnnnnEEn_n
- _$s8CoreData13CDSwiftResultV8populate4from5using14columnMetadata16compositeIndices14requestContext11moidFactory03oidO0ySo18FetchResultsRow_stVz_So0Q10EntityPlanazSayAA06ColumnI0VGs15ContiguousArrayVySiGSo017NSSQLFetchRequestM0CSo17NSManagedObjectIDCs5Int64VXEAYA_cSo11NSSQLEntityCXEtFys4SpanVySo0qwV0aGXEfU_
- _$sSTsE21_copySequenceContents12initializing8IteratorQz_SitSry7ElementQzG_tFShySiG_Tg5
- _$sSh8_VariantV6insertySb8inserted_x17memberAfterInserttxnFSi_Tg5
- _$ss10_NativeSetV9insertNew_2at8isUniqueyxn_s10_HashTableV6BucketVSbtFSi_Tg5
- _$ss11_SetStorageCySiGMR
- _$ss11_SetStorageCySiGMd
- _$ss22_ContiguousArrayBufferV19_uninitializedCount15minimumCapacityAByxGSi_SitcfCSi_Tt1g5
- _symbolic _____ySiG s11_SetStorageC
CStrings:
+ "WITH VTABS AS (SELECT NAME FROM SQLITE_MASTER WHERE TYPE = \"table\" AND SQL LIKE 'CREATE VIRTUAL TABLE%') SELECT TBL_NAME, SQL FROM SQLITE_MASTER WHERE TYPE = \"table\" AND SQL NOT LIKE 'CREATE VIRTUAL TABLE%' AND NOT EXISTS (SELECT 1 FROM VTABS WHERE TBL_NAME LIKE VTABS.NAME || '\\_%' ESCAPE '\\')"
```
