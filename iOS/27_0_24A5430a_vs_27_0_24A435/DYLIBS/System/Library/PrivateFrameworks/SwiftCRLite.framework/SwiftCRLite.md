## SwiftCRLite

> `/System/Library/PrivateFrameworks/SwiftCRLite.framework/SwiftCRLite`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb6a34` | `0xbb16c` | **`+0x4738`** |
| `__TEXT.__eh_frame` | `0x5024` | `0x549c` | **`+0x478`** |
| `__DATA.__bss` | `0xae10` | `0xb210` | **`+0x400`** |
| `__TEXT.__cstring` | `0x40fc` | `0x44bc` | **`+0x3c0`** |
| `__AUTH_CONST.__const` | `0x5d69` | `0x6011` | **`+0x2a8`** |
| `__TEXT.__const` | `0x9354` | `0x9594` | **`+0x240`** |
| `__TEXT.__swift5_fieldmd` | `0x2c3c` | `0x2d88` | **`+0x14c`** |
| `__TEXT.__oslogstring` | `0x181e` | `0x195e` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0x2680` | `0x27b8` | **`+0x138`** |
| `__TEXT.__swift5_reflstr` | `0x1e8c` | `0x1f3c` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0x1c08` | `0x1c68` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x1ebd` | `0x1f15` | **`+0x58`** |
| `__DATA.__data` | `0x11e0` | `0x1218` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x474` | `0x4a0` | **`+0x2c`** |
| `__TEXT.__swift5_proto` | `0x6dc` | `0x6fc` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x54c` | `0x564` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x3e0` | `0x3f8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x4a8` | `0x4b0` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x2008` | `0x2010` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x698` | `0x6a0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x278` | `0x280` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xa8` | `0xb0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x80` | `0x84` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xa8` | `0xac` | **`+0x4`** |

### Other Changes

```diff

-  Functions: 3422
-  Symbols:   1358
-  CStrings:  543
+  Functions: 3511
+  Symbols:   1368
+  CStrings:  576
Symbols:
+ -[SwiftCRLiteClient isPhotoRevoked:error:]
+ ___swift_closure_destructor.56Tm
+ _associated conformance 11SwiftCRLite11PRLMetaDataV10CodingKeys33_E6FBEEB7D9D657A6F6332D4066B56307LLOSHAASQ
+ _associated conformance 11SwiftCRLite11PRLMetaDataV10CodingKeys33_E6FBEEB7D9D657A6F6332D4066B56307LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 11SwiftCRLite11PRLMetaDataV10CodingKeys33_E6FBEEB7D9D657A6F6332D4066B56307LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _symbolic Si8expected_Si6actualt
+ _symbolic _____ 11SwiftCRLite11PRLMetaDataV
+ _symbolic _____ 11SwiftCRLite11PRLMetaDataV10CodingKeys33_E6FBEEB7D9D657A6F6332D4066B56307LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 11SwiftCRLite11PRLMetaDataV10CodingKeys33_E6FBEEB7D9D657A6F6332D4066B56307LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 11SwiftCRLite11PRLMetaDataV10CodingKeys33_E6FBEEB7D9D657A6F6332D4066B56307LLO
+ _type_layout_string 11SwiftCRLite11PRLMetaDataV
- ___swift_closure_destructor.47Tm
CStrings:
+ "    CREATE TABLE IF NOT EXISTS prl(\n       photo_id BLOB PRIMARY KEY NOT NULL\n    );"
+ "DELETE FROM prl WHERE photo_id = ?"
+ "DELETE FROM prl;"
+ "DROP TABLE IF EXISTS prl;"
+ "INSERT INTO main.prl SELECT * FROM "
+ "INSERT OR REPLACE INTO prl (photo_id) VALUES (?)"
+ "PRL data"
+ "PRL data length"
+ "PRL data length missing"
+ "PRL data missing"
+ "PRL entry"
+ "PRL entry count"
+ "PRL entry count mismatch: expected "
+ "PRL entry count missing"
+ "PRL entry data missing"
+ "PRL is deprecated and no longer maintained. Software upgrade required."
+ "PRL metadata"
+ "PRL metadata length"
+ "PRL metadata length missing"
+ "PRL metadata missing"
+ "PRL query failed, treating photo as not revoked: %@"
+ "PRL version is unsupported (expected 1): %ld"
+ "PRL: Full update, clearing existing PRL data"
+ "PRL: Inserting %ld revoked photo IDs"
+ "PRL: Received deprecated flag - PRL is no longer maintained"
+ "PRL: Successfully stored %ld entries%s"
+ "SELECT 1 FROM prl WHERE photo_id = ? LIMIT 1"
+ "SELECT ival FROM admin WHERE key = ? LIMIT 1"
+ "SELECT photo_id FROM prl LIMIT ?"
+ "expected actual "
+ "fullPRLUpdate"
+ "numEntries"
+ "prl_deprecated"
```
