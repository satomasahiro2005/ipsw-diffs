## PoirotBlocks

> `/System/Library/PrivateFrameworks/PoirotBlocks.framework/PoirotBlocks`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb284c` | `0xb7238` | **`+0x49ec`** |
| `__DATA.__bss` | `0xe680` | `0xe800` | **`+0x180`** |
| `__AUTH.__data` | `0x1a48` | `0x1b80` | **`+0x138`** |
| `__TEXT.__oslogstring` | `0x278` | `0x38a` | **`+0x112`** |
| `__TEXT.__eh_frame` | `0x6e64` | `0x6f6c` | **`+0x108`** |
| `__AUTH_CONST.__objc_const` | `0x29e0` | `0x2ad8` | **`+0xf8`** |
| `__TEXT.__cstring` | `0x1e5b` | `0x1f1b` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x3304` | `0x338c` | **`+0x88`** |
| `__AUTH_CONST.__const` | `0x6ae9` | `0x6b69` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x2ab0` | `0x2b30` | **`+0x80`** |
| `__TEXT.__const` | `0xb3e0` | `0xb458` | **`+0x78`** |
| `__AUTH_CONST.__auth_got` | `0x14f0` | `0x1548` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x28fb` | `0x2949` | **`+0x4e`** |
| `__DATA.__data` | `0x1830` | `0x1860` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x2040` | `0x2068` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x2fa8` | `0x2fc0` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0x2084` | `0x2094` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x8f4` | `0x900` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x148` | `0x150` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x338` | `0x340` | **`+0x8`** |

### Other Changes

```diff

-3600.35.1.0.0
+3605.9.1.0.0

-  Functions: 3842
-  Symbols:   1404
-  CStrings:  237
+  Functions: 3877
+  Symbols:   1412
+  CStrings:  244
Symbols:
+ __DATA__TtC12PoirotBlocks30SyntaxCheckingUserDefinedBlock
+ __IVARS__TtC12PoirotBlocks30SyntaxCheckingUserDefinedBlock
+ __METACLASS_DATA__TtC12PoirotBlocks30SyntaxCheckingUserDefinedBlock
+ _associated conformance 12PoirotBlocks19DataSourceReferenceVSHAASQ
+ _swift_getTupleTypeMetadata
+ _symbolic SS4name_SS15selectStatementSS11messageName_____Sg8manifestt 17PoirotSchematizer14SchemaManifestV
+ _symbolic _____ 12PoirotBlocks19DataSourceReferenceV
+ _symbolic _____ 12PoirotBlocks30SyntaxCheckingUserDefinedBlockC
+ _symbolic ______Say_____Gt 12PoirotBlocks19DataSourceReferenceV 0A4UDFs6ColumnV
+ _symbolic _____y_____Say_____GG s18_DictionaryStorageC 12PoirotBlocks19DataSourceReferenceV 0C4UDFs6ColumnV
+ _symbolic _____y______Say_____GtG s23_ContiguousArrayStorageC 12PoirotBlocks19DataSourceReferenceV 0D4UDFs6ColumnV
+ _type_layout_string 12PoirotBlocks19DataSourceReferenceV
- _symbolic SS_Say_____Gt 10PoirotUDFs6ColumnV
- _symbolic Say_____G 12PoirotBlocks22AttachedDatabaseConfigV
- _symbolic _____ySSSay_____GG s18_DictionaryStorageC 10PoirotUDFs6ColumnV
- _symbolic _____ySS_Say_____GtG s23_ContiguousArrayStorageC 10PoirotUDFs6ColumnV
CStrings:
+ "Attached SQLite table '"
+ "Attached database '%{public}s' at %{public}s reported %{public}ld table(s): %{public}s"
+ "Failed to inspect schema of attached database '%{public}s' at %{public}s: %{public}s"
+ "PRAGMA table_info("
+ "SELECT name FROM sqlite_master\nWHERE type = 'table' AND name NOT LIKE 'sqlite\\_%' ESCAPE '\\'"
+ "Temporary view: could not resolve columns from message '%{public}s': %{public}s"
+ "name selectStatement messageName manifest "
```
