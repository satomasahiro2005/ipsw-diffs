## ContainerManagerCommon

> `/System/Library/PrivateFrameworks/ContainerManagerCommon.framework/ContainerManagerCommon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1059a4` | `0x108550` | **`+0x2bac`** |
| `__TEXT.__cstring` | `0x9bc4` | `0xa053` | **`+0x48f`** |
| `__AUTH_CONST.__objc_const` | `0x178d8` | `0x17a98` | **`+0x1c0`** |
| `__TEXT.__oslogstring` | `0xfd87` | `0xfec7` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0xb3ac` | `0xb454` | **`+0xa8`** |
| `__TEXT.__eh_frame` | `0x958` | `0x9dc` | **`+0x84`** |
| `__AUTH.__objc_data` | `0xf40` | `0xfb0` | **`+0x70`** |
| `__DATA.__data` | `0x3d50` | `0x3db0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x26e0` | `0x2740` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x13e0` | `0x1430` | **`+0x50`** |
| `__TEXT.__const` | `0x15e0` | `0x1620` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x85b` | `0x889` | **`+0x2e`** |
| `__AUTH.__data` | `0x1e8` | `0x208` | **`+0x20`** |
| `__AUTH_CONST.__cfstring` | `0x4e20` | `0x4e40` | **`+0x20`** |
| `__DATA.__bss` | `0xf58` | `0xf78` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x520` | `0x540` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x2544` | `0x2550` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x5d8` | `0x5e0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3960` | `0x3968` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xc48` | `0xc4c` | **`+0x4`** |

### Other Changes

```diff

-833.40.14.0.0
+833.40.16.0.0

-  Functions: 3856
-  Symbols:   7041
-  CStrings:  2108
+  Functions: 3885
+  Symbols:   7047
+  CStrings:  2138
Symbols:
+ +[MCMContainerCacheEntry(xattr) _identityRecordFromLegacyXattrsForFileHandle:usesInstanceUUID:]
+ +[MCMContainerCacheEntry(xattr) _removeLegacyIdentityXattrsForFileHandle:]
+ +[MCMContainerCacheEntry(xattr) identityRecordForFileHandle:usesInstanceUUID:]
+ +[MCMContainerCacheEntry(xattr) identityRecordForURL:usesInstanceUUID:]
+ +[MCMContainerCacheEntry(xattr) removeIdentityRecordForURL:]
+ +[MCMContainerCacheEntry(xattr) setIdentityRecord:forFileHandle:]
+ +[MCMContainerCacheEntry(xattr) setIdentityRecord:forURL:]
+ -[MCMContainerConfiguration supportsTransient]
+ GCC_except_table1009
+ GCC_except_table1043
+ GCC_except_table1045
+ GCC_except_table1101
+ GCC_except_table1110
+ GCC_except_table1114
+ GCC_except_table1164
+ GCC_except_table1181
+ GCC_except_table1183
+ GCC_except_table1187
+ GCC_except_table1192
+ GCC_except_table1195
+ GCC_except_table1201
+ GCC_except_table1203
+ GCC_except_table1205
+ GCC_except_table1207
+ GCC_except_table1210
+ GCC_except_table1212
+ GCC_except_table1216
+ GCC_except_table1218
+ GCC_except_table1220
+ GCC_except_table1226
+ GCC_except_table1229
+ GCC_except_table1231
+ GCC_except_table1239
+ GCC_except_table1254
+ GCC_except_table1258
+ GCC_except_table1260
+ GCC_except_table1315
+ GCC_except_table1325
+ GCC_except_table1356
+ GCC_except_table1597
+ GCC_except_table1747
+ GCC_except_table1751
+ GCC_except_table1905
+ GCC_except_table1911
+ GCC_except_table2014
+ GCC_except_table2151
+ GCC_except_table2294
+ GCC_except_table2312
+ GCC_except_table2377
+ GCC_except_table2423
+ GCC_except_table2439
+ GCC_except_table2460
+ GCC_except_table2529
+ GCC_except_table2541
+ GCC_except_table2610
+ GCC_except_table2620
+ GCC_except_table2645
+ GCC_except_table2668
+ GCC_except_table2678
+ GCC_except_table2703
+ GCC_except_table2706
+ GCC_except_table2709
+ GCC_except_table2714
+ GCC_except_table2762
+ GCC_except_table2766
+ GCC_except_table2933
+ GCC_except_table2937
+ GCC_except_table3017
+ GCC_except_table878
+ GCC_except_table956
+ _OBJC_CLASS_$_MCMContainerIdentityRecord
+ _OBJC_IVAR_$_MCMContainerConfiguration._supportsTransient
+ _OBJC_METACLASS_$_MCMContainerIdentityRecord
+ __DATA_MCMContainerIdentityRecord
+ __INSTANCE_METHODS_MCMContainerIdentityRecord
+ __IVARS_MCMContainerIdentityRecord
+ __METACLASS_DATA_MCMContainerIdentityRecord
+ __PROPERTIES_MCMContainerIdentityRecord
+ _memchr
+ _symbolic SRy_____G s5UInt8V
+ _symbolic SS_ypt
+ _symbolic So6NSUUIDCSg
+ _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
+ _uuid_parse
- +[MCMContainerCacheEntry(xattr) UUIDForFileHandle:]
- +[MCMContainerCacheEntry(xattr) UUIDForURL:]
- +[MCMContainerCacheEntry(xattr) identifierForFileHandle:]
- +[MCMContainerCacheEntry(xattr) identifierForURL:]
- +[MCMContainerCacheEntry(xattr) instanceUUIDForFileHandle:]
- +[MCMContainerCacheEntry(xattr) instanceUUIDForURL:]
- +[MCMContainerCacheEntry(xattr) schemaVersionForFileHandle:]
- +[MCMContainerCacheEntry(xattr) schemaVersionForURL:]
- +[MCMContainerCacheEntry(xattr) setIdentifier:forFileHandle:]
- +[MCMContainerCacheEntry(xattr) setIdentifier:forURL:]
- +[MCMContainerCacheEntry(xattr) setInstanceUUID:forFileHandle:]
- +[MCMContainerCacheEntry(xattr) setInstanceUUID:forURL:]
- +[MCMContainerCacheEntry(xattr) setSchemaVersion:forFileHandle:]
- +[MCMContainerCacheEntry(xattr) setSchemaVersion:forURL:]
- +[MCMContainerCacheEntry(xattr) setUUID:forFileHandle:]
- +[MCMContainerCacheEntry(xattr) setUUID:forURL:]
- GCC_except_table1008
- GCC_except_table1042
- GCC_except_table1044
- GCC_except_table1100
- GCC_except_table1109
- GCC_except_table1113
- GCC_except_table1163
- GCC_except_table1180
- GCC_except_table1182
- GCC_except_table1186
- GCC_except_table1191
- GCC_except_table1194
- GCC_except_table1200
- GCC_except_table1202
- GCC_except_table1204
- GCC_except_table1206
- GCC_except_table1209
- GCC_except_table1211
- GCC_except_table1215
- GCC_except_table1217
- GCC_except_table1219
- GCC_except_table1225
- GCC_except_table1228
- GCC_except_table1230
- GCC_except_table1238
- GCC_except_table1253
- GCC_except_table1257
- GCC_except_table1259
- GCC_except_table1314
- GCC_except_table1324
- GCC_except_table1355
- GCC_except_table1596
- GCC_except_table1746
- GCC_except_table1750
- GCC_except_table1904
- GCC_except_table1910
- GCC_except_table2013
- GCC_except_table2150
- GCC_except_table2293
- GCC_except_table2310
- GCC_except_table2376
- GCC_except_table2422
- GCC_except_table2438
- GCC_except_table2459
- GCC_except_table2528
- GCC_except_table2540
- GCC_except_table2609
- GCC_except_table2619
- GCC_except_table2644
- GCC_except_table2667
- GCC_except_table2677
- GCC_except_table2702
- GCC_except_table2705
- GCC_except_table2708
- GCC_except_table2713
- GCC_except_table2761
- GCC_except_table2765
- GCC_except_table2932
- GCC_except_table2936
- GCC_except_table3016
- GCC_except_table877
- GCC_except_table955
CStrings:
+ " UTF-8 bytes, outside [1, "
+ " bytes, over the "
+ " exceeds its field"
+ ", instanceUUID = "
+ ", schemaVersion = "
+ "00000000-0000-0000-0000-000000000000"
+ "04:59:36"
+ "<MCMContainerIdentityRecord: identifier = "
+ "Attempting to recover from corrupt metadata for [%@]; identifier = [🔒%{private}@], uuid = %@, schemaVersion = %@"
+ "Cache entry failed verification, identifier doesn't match; cacheEntry = %@, current identifier = [🔒%{private}@]"
+ "Container did not have a usable identity record ([🔒%{private}@]|%@|%@|%@), reading plist (slow); path = %@"
+ "Container owned by non-existent user ([🔒%{private}@]|%@|%@|%@), deleting; path = %@, error = %@"
+ "ContainerManagerCommon_Internal.MCMContainerIdentityRecord"
+ "Could not clear superseded xattr [%@]; error = %@"
+ "Could not clear xattr identity from [🔒%{private}@]; error = %@"
+ "Could not read superseded identity xattr [%@]; error = %@"
+ "Failed to encode identity record [%@]; error = %@"
+ "Failed to read xattr identity; error = %@"
+ "Failed to set xattr identity; error = %@"
+ "Identifier is not an acceptable value to record"
+ "Identity record does not begin with ["
+ "Identity record has no newline introducing the identifier"
+ "Identity record identifier is "
+ "Identity record identifier is not an acceptable "
+ "Identity record identifier is not valid UTF-8"
+ "Identity record identifier label is missing at offset "
+ "Identity record instance-uuid field is unterminated"
+ "Identity record instance-uuid is neither ["
+ "Identity record instance-uuid label is malformed"
+ "Identity record length "
+ "Identity record on [🔒%{private}@] did not validate, falling back; error = %@"
+ "Identity record schema field is malformed"
+ "Identity record uuid field is malformed"
+ "Identity record version "
+ "Identity record version field is malformed"
+ "MobileContainerManager-833.40.16~79"
+ "Rejecting transient query; container class does not support transient containers; containerClass = %{public}@"
+ "Sep 12 2026"
+ "Upgrading superseded per-field identity xattrs to a single identity record; record = %@"
+ "com.apple.containermanager.identity"
+ "identifier: "
+ "instance-uuid: "
+ "schema: "
+ "uuid: "
+ "v: "
- "00:56:24"
- "Attempting to recover from corrupt metadata for [%@]; identifier = %@, uuid = %@, schemaVersion = %@"
- "Cache entry failed verification, identifier doesn't match; cacheEntry = %@, current identifier = %@"
- "Container did not have xattr (%@|%@|%@|%@), reading plist (slow); path = %@"
- "Container owned by non-existent user (%@|%@|%@|%@), deleting; path = %@, error = %@"
- "Failed to get xattr identifier; error = %@"
- "Failed to get xattr instance uuid; error = %@"
- "Failed to get xattr schemaVersion; error = %@"
- "Failed to get xattr uuid; error = %@"
- "Failed to set xattr identifier; error = %@"
- "Failed to set xattr instance uuid; error = %@"
- "Failed to set xattr schemaVersion; error = %@"
- "Failed to set xattr uuid; error = %@"
- "MobileContainerManager-833.40.14~50"
- "Sep  4 2026"
```
