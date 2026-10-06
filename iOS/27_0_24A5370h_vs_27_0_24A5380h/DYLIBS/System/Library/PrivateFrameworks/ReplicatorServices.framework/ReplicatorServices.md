## ReplicatorServices

> `/System/Library/PrivateFrameworks/ReplicatorServices.framework/ReplicatorServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1147bc` | `0x1190a0` | **`+0x48e4`** |
| `__DATA_DIRTY.__data` | `0x2650` | `0x3d00` | **`+0x16b0`** |
| `__AUTH.__data` | `0x1b48` | `0x958` | **`-0x11f0`** |
| `__DATA.__bss` | `0x10c80` | `0x10280` | **`-0xa00`** |
| `__DATA_DIRTY.__bss` | `0x4e80` | `0x5880` | **`+0xa00`** |
| `__DATA.__data` | `0x2218` | `0x1d88` | **`-0x490`** |
| `__TEXT.__oslogstring` | `0x3a10` | `0x3db0` | **`+0x3a0`** |
| `__TEXT.__eh_frame` | `0x7620` | `0x7878` | **`+0x258`** |
| `__TEXT.__cstring` | `0x1c43` | `0x1da3` | **`+0x160`** |
| `__TEXT.__unwind_info` | `0x3c00` | `0x3d50` | **`+0x150`** |
| `__AUTH.__objc_data` | `0x850` | `0x780` | **`-0xd0`** |
| `__DATA_DIRTY.__objc_data` | `0x8d8` | `0x9a8` | **`+0xd0`** |
| `__TEXT.__const` | `0xc6a8` | `0xc728` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x367c` | `0x36ec` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x10e8` | `0x1088` | **`-0x60`** |
| `__DATA.__common` | `0x80` | `0x68` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x530` | `0x548` | **`+0x18`** |
| `__DATA_DIRTY.__common` | `0x60` | `0x78` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x2a5c` | `0x2a74` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x3504` | `0x34ee` | **`-0x16`** |
| `__TEXT.__swift5_reflstr` | `0x19f3` | `0x1a03` | **`+0x10`** |

### Other Changes

```diff

-168.0.0.0.0
+172.0.0.0.0

-  Functions: 5424
-  Symbols:   1714
-  CStrings:  475
+  Functions: 5461
+  Symbols:   1711
+  CStrings:  499
Symbols:
+ _symbolic SDy_____SDy__________GG 16ReplicatorEngine27ZoneVersionRelationshipTypeO AA0C0C2IDC 10Foundation4UUIDV
+ _symbolic ______SDy__________Gt 16ReplicatorEngine27ZoneVersionRelationshipTypeO AA0C0C2IDC 10Foundation4UUIDV
+ _symbolic _____y_____SDy__________GG s18_DictionaryStorageC 16ReplicatorEngine27ZoneVersionRelationshipTypeO AC0E0C2IDC 10Foundation4UUIDV
- _swift_willThrowTypedImpl
- _symbolic SDy_____SDy_____AAGG 10Foundation4UUIDV 16ReplicatorEngine4ZoneC2IDC
- _symbolic Say_____G 16ReplicatorEngine6RecordV2IDC
- _symbolic ______SDy_____AAGt 10Foundation4UUIDV 16ReplicatorEngine4ZoneC2IDC
- _symbolic _____y_____SDy_____ABGG s18_DictionaryStorageC 10Foundation4UUIDV 16ReplicatorEngine4ZoneC2IDC
- _symbolic _____y___________G SD5IndexV 16ReplicatorEngine6RecordV2IDC AC0D8MetadataC
CStrings:
+ "\n    FROM\n        "
+ "    SELECT\n        "
+ " IS NOT NULL\nORDER BY\n    "
+ ")\n    ORDER BY\n        "
+ ") >\n            ("
+ ",\n    \"BadVersion\",\n    123,\n    \"BadDestinationID\",\n    123,\n    123\n);"
+ "Could not check if relationship has metadata in database: %{public}@"
+ "Could not enumerate record metadata in database: %{public}@"
+ "Could not fetch earliest expiration date from database: %{public}@"
+ "Could not fetch expired record IDs from database: %{public}@"
+ "Could not fetch metadata count from database: %{public}@"
+ "Could not fetch zone IDs from database: %{public}@"
+ "Could not remove locally-owned record metadata from database: %{public}@"
+ "Could not remove record metadata zone from database: %{public}@"
+ "Could not remove remotely-owned record metadata from database: %{public}@"
+ "Could not retrieve expiration date"
+ "Encountered malformed zone ID"
+ "Metadata enumeration failed: not making forward progress; attempting slow path recovery"
+ "No expiration date found"
+ "No metadata count found in result"
+ "No metadata count result found"
+ "RemovingLocallyOwnedRecords"
+ "RemovingRemotelyOwnedRecords"
+ "SELECT COUNT(*) AS MetadataCount\nFROM\n    "
```
