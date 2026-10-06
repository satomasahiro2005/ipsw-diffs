## HealthRecordsExtraction

> `/System/Library/PrivateFrameworks/HealthRecordsExtraction.framework/HealthRecordsExtraction`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15781c` | `0x1581d0` | **`+0x9b4`** |
| `__TEXT.__cstring` | `0xc98c` | `0xcaac` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x2891` | `0x28c1` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xba0` | `0xbc8` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x773c` | `0x771c` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x4908` | `0x48f0` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1430` | `0x1438` | **`+0x8`** |
| `__DATA.__data` | `0x2e78` | `0x2e80` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x19a0` | `0x19a8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x2f8` | `0x2f4` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x188` | `0x184` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x210` | `0x20c` | **`-0x4`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 6179
-  Symbols:   2245
-  CStrings:  1330
+  Functions: 6177
+  Symbols:   2246
+  CStrings:  1336
Symbols:
+ __swift_stdlib_bridgeErrorToNSError
CStrings:
+ "%s failed to extract raw text: %@"
+ "%s: no text is left after trimming whitespace"
+ "CodeableConceptLookupService:hre_displayStringFromOntology"
+ "HealthRecordAttachmentsIndexer:medicalRecords"
+ "HealthRecordAttachmentsIndexer:startObservingForIndexableItemChanges"
+ "PDFDocument could not open the data"
+ "[%s] Failed to pull text from attachment %s, will ignore. Error: %s"
+ "data is not valid UTF-8"
- "[%s] Failed to generate index string for docx data: %s"
- "[%s] Failed to generate index string for html data: %s"
```
