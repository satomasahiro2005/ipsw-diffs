## CoreData

> `/System/Library/Frameworks/CoreData.framework/CoreData`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x331154` | `0x33173c` | **`+0x5e8`** |
| `__TEXT.__gcc_except_tab` | `0x187c8` | `0x1883c` | **`+0x74`** |
| `__DATA_CONST.__const` | `0x4be8` | `0x4c38` | **`+0x50`** |
| `__TEXT.__cstring` | `0x3bf28` | `0x3bf73` | **`+0x4b`** |
| `__AUTH_CONST.__objc_const` | `0x25dc8` | `0x25df8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x77d8` | `0x7808` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x108d8` | `0x108f8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x6240` | `0x6258` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x36910` | `0x36900` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x1898` | `0x189c` | **`+0x4`** |

### Other Changes

```diff

-1627.0.0.0.0
+1629.1.0.0.0

-  Functions: 9338
-  Symbols:   17613
-  CStrings:  8339
+  Functions: 9344
+  Symbols:   17623
+  CStrings:  8340
Symbols:
+ -[NSCoreDataCoreSpotlightDelegate _handleSpotlightWipeTimeoutError:]
+ -[NSPersistentCloudKitContainerOptions initWithContainer:scheduler:]
+ -[NSPersistentCloudKitContainerOptions setTestSchedulerOverride:]
+ -[NSPersistentCloudKitContainerOptions testSchedulerOverride]
+ GCC_except_table88
+ _$s8CoreData13CDSwiftResultV8populate4from5using14columnMetadata16compositeIndices14requestContext11moidFactory03oidO0ySo18FetchResultsRow_stVz_So0Q10EntityPlanazSayAA06ColumnI0VGs15ContiguousArrayVySiGSo017NSSQLFetchRequestM0CSo17NSManagedObjectIDCs5Int64VXEAYA_cSo11NSSQLEntityCXEtF49$ss5Int64VSo17NSManagedObjectIDCIegnr_AbDIegyo_TRA_AYIegnr_105$sSo11NSSQLEntityCxq_Ri_zRi0_zRi__Ri0__r0_lys5Int64VSo17NSManagedObjectIDCIsegnr_Iegnr_AbdFIegyo_Ieggo_TRA1_xq_Ri_zRi0_zRi__Ri0__r0_lyA_AYIsegnr_Iegnr_Tf1nnnnnEEn_n
+ _OBJC_IVAR_$_NSPersistentCloudKitContainerOptions._testSchedulerOverride
+ ___77-[NSCoreDataCoreSpotlightDelegate _resetSpotlightIndexWithCompletionHandler:]_block_invoke
+ ___77-[NSCoreDataCoreSpotlightDelegate deleteSpotlightIndexWithCompletionHandler:]_block_invoke_3
+ ___block_descriptor_48_e8_32b40r_e17_v16?0"NSError"8lr40l8s32l8
+ ___block_descriptor_56_e8_32o40b48r_e5_v8?0ls40l8r48l8s32l8
- _$s8CoreData13CDSwiftResultV8populate4from5using14columnMetadata16compositeIndices14requestContext11moidFactory03oidO0ySo18FetchResultsRow_stVz_So0Q10EntityPlanazSayAA06ColumnI0VGs15ContiguousArrayVySiGSo017NSSQLFetchRequestM0CSo17NSManagedObjectIDCs5Int64VXEAYA_cSo11NSSQLEntityCXEtF49$ss5Int64VSo17NSManagedObjectIDCIegnr_AbDIegyo_TRA_AYIegnr_105$sSo11NSSQLEntityCxq_Ri_zRi0_zRi__Ri0__r0_lys5Int64VSo17NSManagedObjectIDCIsegnr_Iegnr_AbdFIegyo_Ieggo_TRA1_xq_Ri_zRi0_zRi__Ri0__r0_lyA_AYIsegnr_Iegnr_Tf1nnnnnccn_n
CStrings:
+ "CDCS pre-reindex wipe reported error; continuing to reindex anyway (index %@): %@"
+ "CREATE TRIGGER IF NOT EXISTS %@_DELETE AFTER DELETE ON %@ FOR EACH ROW BEGIN DELETE FROM %@ WHERE rowid = OLD.Z_PK; END"
+ "CREATE TRIGGER IF NOT EXISTS %@_UPDATE AFTER UPDATE ON %@ FOR EACH ROW BEGIN DELETE FROM %@ WHERE rowid = OLD.Z_PK; INSERT INTO %@ (rowid, %@) VALUES (NEW.Z_PK, %@); END"
+ "CREATE VIRTUAL TABLE IF NOT EXISTS %@ USING fts5(%@, content='', contentless_delete=1, tokenize = '_CoreDataTokenizer')"
+ "CoreData: error: CDCS pre-reindex wipe reported error; continuing to reindex anyway (index %@): %@\n"
+ "CoreData: error: Timed out waiting for pre-reindex domain wipe to complete (index %@)\n"
+ "CoreData: error: disconnectAllConnections reconnect failed with exception: %@\n"
+ "INSERT INTO %@ (rowid, %@) SELECT Z_PK, %@ FROM %@"
+ "Timed out waiting for CoreSpotlight domain wipe"
+ "Timed out waiting for pre-reindex domain wipe to complete (index %@)"
+ "com.apple.coredata.tokenizer.default.v2"
+ "disconnectAllConnections reconnect failed with exception: %@"
- "%@OLD.%@"
- "CDCS pre-reindex wipe reported error; continuing to reindex anyway (index %@)"
- "CREATE TRIGGER IF NOT EXISTS %@_DELETE AFTER DELETE ON %@ FOR EACH ROW BEGIN INSERT INTO %@(%@, rowid, %@) VALUES('delete', OLD.Z_PK, %@); END"
- "CREATE TRIGGER IF NOT EXISTS %@_UPDATE AFTER UPDATE ON %@ FOR EACH ROW BEGIN INSERT INTO %@(%@, rowid, %@) VALUES('delete', OLD.Z_PK, %@); INSERT INTO %@ (rowid, %@) VALUES (NEW.Z_PK, %@); END"
- "CREATE VIRTUAL TABLE IF NOT EXISTS %@ USING fts5(%@, content='%@', content_rowid='Z_PK', tokenize = '_CoreDataTokenizer')"
- "CoreData: error: CDCS pre-reindex wipe reported error; continuing to reindex anyway (index %@)\n"
- "CoreData: error: Error while resetting the client spotlight index before re-index, %@.\n"
- "CoreData: warning: CDCS pre-reindex wipe reported error; continuing to reindex anyway (index %@)\n"
- "Error while resetting the client spotlight index before re-index, %@."
- "INSERT INTO %@(%@) VALUES('rebuild')"
- "com.apple.coredata.tokenizer.default.v1"
```
