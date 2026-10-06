## PersonalizationPortraitInternals

> `/System/Library/PrivateFrameworks/PersonalizationPortraitInternals.framework/PersonalizationPortraitInternals`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x194dc8` | `0x19552c` | **`+0x764`** |
| `__AUTH.__objc_data` | `0x1658` | `0x1370` | **`-0x2e8`** |
| `__DATA_DIRTY.__objc_data` | `0x5800` | `0x5ae8` | **`+0x2e8`** |
| `__TEXT.__cstring` | `0x16b22` | `0x16d42` | **`+0x220`** |
| `__DATA_DIRTY.__bss` | `0x620` | `0x740` | **`+0x120`** |
| `__DATA.__bss` | `0x410` | `0x2f8` | **`-0x118`** |
| `__DATA_DIRTY.__data` | `0x398` | `0x4a8` | **`+0x110`** |
| `__DATA.__data` | `0x1850` | `0x1780` | **`-0xd0`** |
| `__AUTH_CONST.__auth_got` | `0xe60` | `0xf20` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0x280` | `0x2c8` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x1940` | `0x1978` | **`+0x38`** |
| `__AUTH.__data` | `0x28` | `—` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x5608` | `0x5630` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x8848` | `0x8838` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x5f2` | `0x5fa` | **`+0x8`** |

### Other Changes

```diff

-1334.0.1.0.0
+1337.0.0.0.0

-  - /System/Library/Frameworks/UIKit.framework/UIKit

-  - /System/Library/PrivateFrameworks/CorePhoneNumbers.framework/CorePhoneNumbers

+  - /System/Library/PrivateFrameworks/GRDBInternal.framework/GRDBInternal

+  - /System/Library/PrivateFrameworks/IntelligencePlatform.framework/IntelligencePlatform

-  - /System/Library/PrivateFrameworks/SiriRemembers.framework/SiriRemembers

-  - /usr/lib/swift/libswiftSpatial.dylib

-  Functions: 8850
+  Functions: 8855

-  CStrings:  4412
+  CStrings:  4415
Symbols:
+ _sqlite3_column_type
+ _swift_retain_x22
+ _swift_unexpectedError
+ _symbolic ______pSg 12GRDBInternal10RowAdapterP
+ _symbolic _____y______pSgG s23_ContiguousArrayStorageC 12GRDBInternal24DatabaseValueConvertibleP
- __swift_FORCE_LOAD_$_swiftSpatial
- __swift_FORCE_LOAD_$_swiftSpatial_$_PersonalizationPortraitInternals
- __swift_FORCE_LOAD_$_swiftUIKit
- __swift_FORCE_LOAD_$_swiftUIKit_$_PersonalizationPortraitInternals
- _symbolic SS3key______5valuet 13SiriRemembers12HistoryStatsV
CStrings:
+ "GRDBInternal/Row.swift"
+ "SELECT entities.id AS entityId,\n       CAST(MAX(interactions.startDate) AS REAL) AS recency\nFROM interactions\nJOIN interactionEntities ON interactions.rowid = interactionEntities.interactionRowid\nJOIN entities             ON entities.rowid    = interactionEntities.entityRowid\nWHERE entities.type = ?\n  AND entities.id IN (SELECT value FROM json_each(?))\n  AND interactions.isLocal = 1\n  AND interactions.domain = ?\nGROUP BY entities.id"
+ "com.apple.proactive.suggestions.SocialHighlights"
```
