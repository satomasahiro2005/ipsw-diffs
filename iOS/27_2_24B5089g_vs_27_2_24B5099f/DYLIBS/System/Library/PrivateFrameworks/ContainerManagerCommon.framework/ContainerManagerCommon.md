## ContainerManagerCommon

> `/System/Library/PrivateFrameworks/ContainerManagerCommon.framework/ContainerManagerCommon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x108550` | `0x10b69c` | **`+0x314c`** |
| `__TEXT.__oslogstring` | `0xfec7` | `0x10329` | **`+0x462`** |
| `__AUTH_CONST.__objc_const` | `0x17a98` | `0x17da0` | **`+0x308`** |
| `__TEXT.__objc_methlist` | `0xb454` | `0xb634` | **`+0x1e0`** |
| `__DATA_DIRTY.__objc_data` | `0x3020` | `0x3198` | **`+0x178`** |
| `__DATA.__bss` | `0xf78` | `0xe38` | **`-0x140`** |
| `__DATA_DIRTY.__bss` | `0x6b0` | `0x7f0` | **`+0x140`** |
| `__DATA_DIRTY.__data` | `0x448` | `0x568` | **`+0x120`** |
| `__AUTH.__objc_data` | `0xfb0` | `0xea8` | **`-0x108`** |
| `__TEXT.__cstring` | `0xa053` | `0xa13c` | **`+0xe9`** |
| `__DATA_CONST.__objc_selrefs` | `0x3968` | `0x3a28` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0x9dc` | `0xa74` | **`+0x98`** |
| `__DATA_CONST.__const` | `0x18e0` | `0x1960` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x2740` | `0x27a0` | **`+0x60`** |
| `__AUTH.__data` | `0x208` | `0x1b8` | **`-0x50`** |
| `__AUTH_CONST.__cfstring` | `0x4e40` | `0x4e60` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1430` | `0x1448` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xc4c` | `0xc5c` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x610` | `0x620` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2550` | `0x255c` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x540` | `0x548` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x5e0` | `0x5e8` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x1a8` | `0x1b0` | **`+0x8`** |

### Other Changes

```diff

-833.40.16.0.0
+833.40.18.0.1

-  Functions: 3885
-  Symbols:   7047
-  CStrings:  2138
+  Functions: 3932
+  Symbols:   7095
+  CStrings:  2155
Symbols:
+ +[MCMContainerCacheEntry metadataReadErrorIsInconclusive:]
+ +[MCMContainerFactory lookupErrorPermitsCreation:]
+ -[MCMCommandQuery coexistingInstances]
+ -[MCMContainerCache _missingContainerErrorForClassCache:]
+ -[MCMContainerCache _unreadableContainerError]
+ -[MCMContainerCache entryForContainerIdentity:classCache:mutationAllowed:coexistingInstances:error:]
+ -[MCMContainerClassCache _concurrent_slowGenerateCacheEntryWithFileHandle:URL:identifier:uuid:schemaVersion:posixOwnership:instanceUUID:containerPath:out_deferred:]
+ -[MCMContainerClassCache _noteUnreadableContainer]
+ -[MCMContainerClassCache _resetUnreadableContainers]
+ -[MCMContainerClassCache hasUnreadableContainers]
+ -[MCMContainerConfiguration exclusiveInstance]
+ -[MCMContainerFactory containerForContainerIdentity:createIfNecessary:coexistingInstances:error:]
+ -[MCMContainerMigrator _performBlockOnceUnlockedSinceBoot:]
+ -[MCMContainerMigrator _repairMetadataDataProtectionWithContainerConfig:context:]
+ -[MCMContainerMigrator queueUnlockDeferredMigrationsWithContext:]
+ -[MCMXPCMessageQuery coexistingInstances]
+ GCC_except_table1013
+ GCC_except_table1047
+ GCC_except_table1049
+ GCC_except_table1105
+ GCC_except_table1118
+ GCC_except_table1168
+ GCC_except_table1185
+ GCC_except_table1191
+ GCC_except_table1196
+ GCC_except_table1199
+ GCC_except_table1209
+ GCC_except_table1211
+ GCC_except_table1214
+ GCC_except_table1222
+ GCC_except_table1224
+ GCC_except_table1230
+ GCC_except_table1233
+ GCC_except_table1235
+ GCC_except_table1243
+ GCC_except_table1262
+ GCC_except_table1264
+ GCC_except_table1319
+ GCC_except_table1329
+ GCC_except_table1360
+ GCC_except_table1601
+ GCC_except_table1754
+ GCC_except_table1758
+ GCC_except_table1912
+ GCC_except_table1918
+ GCC_except_table2022
+ GCC_except_table2160
+ GCC_except_table2303
+ GCC_except_table2320
+ GCC_except_table2321
+ GCC_except_table2386
+ GCC_except_table2440
+ GCC_except_table2456
+ GCC_except_table2477
+ GCC_except_table2546
+ GCC_except_table2558
+ GCC_except_table2627
+ GCC_except_table2639
+ GCC_except_table2664
+ GCC_except_table2687
+ GCC_except_table2697
+ GCC_except_table2722
+ GCC_except_table2725
+ GCC_except_table2728
+ GCC_except_table2733
+ GCC_except_table2784
+ GCC_except_table2788
+ GCC_except_table2955
+ GCC_except_table2959
+ GCC_except_table3039
+ GCC_except_table879
+ GCC_except_table957
+ _MCMCompareDataProtectionClassTarget
+ _MCMGetDataProtectionClass
+ _MCMMigrationTypeRepairMetadataDataProtection
+ _MCMSetDataProtectionClass
+ _MKBDeviceUnlockedSinceBoot
+ _OBJC_CLASS_$_MCMMetadataDataProtectionRepair
+ _OBJC_IVAR_$_MCMCommandQuery._coexistingInstances
+ _OBJC_IVAR_$_MCMContainerClassCache._lock_unreadableCount
+ _OBJC_IVAR_$_MCMContainerConfiguration._exclusiveInstance
+ _OBJC_IVAR_$_MCMXPCMessageQuery._coexistingInstances
+ _OBJC_METACLASS_$_MCMMetadataDataProtectionRepair
+ __DATA_MCMMetadataDataProtectionRepair
+ __INSTANCE_METHODS_MCMMetadataDataProtectionRepair
+ __IVARS_MCMMetadataDataProtectionRepair
+ __METACLASS_DATA_MCMMetadataDataProtectionRepair
+ __OBJC_$_CLASS_METHODS_MCMContainerFactory
+ __OBJC_$_PROP_LIST_MCMMetadataDataProtectionRepair
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MCMMetadataDataProtectionRepair
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MCMMetadataDataProtectionRepair
+ __OBJC_$_PROTOCOL_REFS_MCMMetadataDataProtectionRepair
+ __OBJC_LABEL_PROTOCOL_$_MCMMetadataDataProtectionRepair
+ __OBJC_PROTOCOL_$_MCMMetadataDataProtectionRepair
+ __PROPERTIES_MCMMetadataDataProtectionRepair
+ __PROTOCOLS_MCMMetadataDataProtectionRepair
+ ___59-[MCMContainerMigrator _performBlockOnceUnlockedSinceBoot:]_block_invoke
+ ___59-[MCMContainerMigrator _performBlockOnceUnlockedSinceBoot:]_block_invoke_2
+ ___59-[MCMContainerMigrator _performBlockOnceUnlockedSinceBoot:]_block_invoke_3
+ ___59-[MCMContainerMigrator _performBlockOnceUnlockedSinceBoot:]_block_invoke_4
+ ___65-[MCMContainerMigrator queueUnlockDeferredMigrationsWithContext:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e8_v12?0i8ls32l8
+ ___block_descriptor_64_e8_32bs40r48r56r_e5_v8?0lr40l8r48l8r56l8s32l8
+ ___block_descriptor_64_e8_32s40bs48r56r_e5_v8?0lr48l8s32l8s40l8r56l8
+ _notify_cancel
- -[MCMContainerClassCache _concurrent_slowGenerateCacheEntryWithFileHandle:URL:identifier:uuid:schemaVersion:posixOwnership:instanceUUID:containerPath:]
- GCC_except_table1009
- GCC_except_table1043
- GCC_except_table1045
- GCC_except_table1101
- GCC_except_table1110
- GCC_except_table1164
- GCC_except_table1181
- GCC_except_table1183
- GCC_except_table1192
- GCC_except_table1195
- GCC_except_table1201
- GCC_except_table1203
- GCC_except_table1210
- GCC_except_table1212
- GCC_except_table1218
- GCC_except_table1226
- GCC_except_table1229
- GCC_except_table1231
- GCC_except_table1239
- GCC_except_table1254
- GCC_except_table1260
- GCC_except_table1315
- GCC_except_table1325
- GCC_except_table1356
- GCC_except_table1597
- GCC_except_table1747
- GCC_except_table1751
- GCC_except_table1905
- GCC_except_table1911
- GCC_except_table2014
- GCC_except_table2151
- GCC_except_table2294
- GCC_except_table2311
- GCC_except_table2312
- GCC_except_table2377
- GCC_except_table2423
- GCC_except_table2439
- GCC_except_table2460
- GCC_except_table2529
- GCC_except_table2541
- GCC_except_table2610
- GCC_except_table2620
- GCC_except_table2645
- GCC_except_table2668
- GCC_except_table2678
- GCC_except_table2703
- GCC_except_table2706
- GCC_except_table2709
- GCC_except_table2714
- GCC_except_table2762
- GCC_except_table2766
- GCC_except_table2933
- GCC_except_table2937
- GCC_except_table3017
- GCC_except_table878
- GCC_except_table956
CStrings:
+ "20:19:01"
+ "<Metadata DP Repair: classes = "
+ "ContainerManagerCommon_Internal.MCMMetadataDataProtectionRepair"
+ "Could not list containers to repair metadata data protection; path = 🔒%{private}s, error = %@"
+ "Could not read migration status; skipping metadata data protection repair"
+ "Could not register for keybag notifications; first unlock = %u, lock status = %u"
+ "Could not restore class D on container metadata; path = 🔒%{private}s, error = %@"
+ "Deferring container whose metadata cannot be read yet; path = %@, error = %@"
+ "Metadata data protection repair [%@] complete; examined = %ld, repaired = %ld"
+ "Metadata data protection repair [%@] incomplete; error = %@"
+ "MobileContainerManager-833.40.18.0.1~21"
+ "Re-running a recorded metadata data protection repair [%@]; a scan deferred at least one container"
+ "Refusing to claim an un-instanced container while [%@] holds a container whose metadata cannot be read; requested = [%@]"
+ "Refusing to delete a mismatched instance while [%@] holds a container whose metadata cannot be read; requested = [%@], existing = [%@]"
+ "RepairMetadataDataProtection"
+ "Reporting a lookup miss in [%@] as unavailable rather than absent; the class holds a container whose metadata cannot be read"
+ "Restored class D on container metadata; path = 🔒%{private}s"
+ "Sep 27 2026"
+ "com.apple.mobile.keybagd.first_unlock"
+ "com.apple.mobile.keybagd.lock_status"
- "04:59:36"
- "MobileContainerManager-833.40.16~79"
- "Sep 12 2026"
```
