## HybridSearchRuntime

> `/System/Library/PrivateFrameworks/HybridSearchRuntime.framework/HybridSearchRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25ed28` | `0x27c3b4` | **`+0x1d68c`** |
| `__TEXT.__eh_frame` | `0x1f070` | `0x2032c` | **`+0x12bc`** |
| `__DATA_CONST.__got` | `0x1ce8` | `0x17c0` | **`-0x528`** |
| `__TEXT.__cstring` | `0xe891` | `0xec11` | **`+0x380`** |
| `__TEXT.__unwind_info` | `0x9698` | `0x9828` | **`+0x190`** |
| `__TEXT.__oslogstring` | `0x6ead` | `0x6fbd` | **`+0x110`** |
| `__AUTH_CONST.__objc_const` | `0x2618` | `0x26f8` | **`+0xe0`** |
| `__AUTH.__data` | `0x1a38` | `0x1ae0` | **`+0xa8`** |
| `__AUTH_CONST.__auth_got` | `0x2b40` | `0x2ba8` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0x5c02` | `0x5c66` | **`+0x64`** |
| `__TEXT.__swift_as_cont` | `0x2cc4` | `0x2d04` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x3d90` | `0x3dc8` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x38d8` | `0x3908` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x1448` | `0x1470` | **`+0x28`** |
| `__DATA.__data` | `0x2920` | `0x2940` | **`+0x20`** |
| `__TEXT.__const` | `0xbe80` | `0xbea0` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0xe88` | `0xea4` | **`+0x1c`** |
| `__TEXT.__swift_as_ret` | `0x1470` | `0x148c` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x684` | `0x69c` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x3700` | `0x3710` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x2070` | `0x2060` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2b20` | `0x2b2c` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0xe8` | `0xf0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x454` | `0x458` | **`+0x4`** |

### Other Changes

```diff

-59.0.1.0.0
+62.1.0.0.0

-  Functions: 12246
-  Symbols:   374
-  CStrings:  947
+  Functions: 12884
+  Symbols:   376
+  CStrings:  966
Symbols:
+ _OBJC_CLASS_$_CCMailAddressForm
+ _swift_stdlib_random
CStrings:
+ " (id INT64 PRIMARY KEY, version UINT16);"
+ " AS entity_type,\n       n.payload AS payload,\n       n."
+ " AS provenance_vid"
+ ". Underlying error: "
+ "176308566_add_writing_assistant_profile_domain_identifier"
+ "ALTER TABLE Documents_general ADD draftMail_isJunk BOOL;"
+ "ALTER TABLE Documents_general ADD draftMail_isTrash BOOL;"
+ "ALTER TABLE Documents_general ADD mailAttachment_isJunk BOOL;"
+ "ALTER TABLE Documents_general ADD mailAttachment_isTrash BOOL;"
+ "ALTER TABLE Documents_general ADD remoteWritingAssistantProfile_domainIdentifier STRING;"
+ "ALTER TABLE Documents_general ADD writingAssistantProfile_domainIdentifier STRING;"
+ "CALL show_tables() WHERE name='_hybridindex_metadata' RETURN name;"
+ "CREATE (n:_hybridindex_metadata {id: 0, version: $version});"
+ "Failed to seed generation version, rolling back: %{public}@"
+ "Generation version missing from the index (e.g. read-only open); falling back to the UserDefaults value"
+ "IndexingServer.generationVersion"
+ "MATCH (n:_hybridindex_metadata {id: 0}) RETURN n.version;"
+ "Seeded generation version %{public}hu"
+ "_hybridindex_metadata"
+ "generationVersion"
+ "generationVersion: unexpected value "
+ "perform(text:checkSafety:safetyThreshold:embeddingModelProperties:contextLength:allowTruncation:sendAnalyticsEvent:)"
+ "readGenerationVersion: %{public}hu"
+ "readGenerationVersion: no version row present"
+ "readGenerationVersion: table is missing; no version seeded yet"
+ "readGenerationVersion: unexpected value %{public}s"
- " AS entity_type,\n       n.payload AS payload"
- "Bumped generation version to %{public}hu"
- "FTSRetokenizeTask"
- "HybridIndex incremental FTS retokenize succeeded."
- "Start HybridIndex incremental FTS retokenize."
- "com.apple.GenerativeSearch.PeriodicTasks.FTSRetokenizeTask"
- "perform(text:checkSafety:safetyThreshold:safetyBlockingDisabled:embeddingModelProperties:contextLength:allowTruncation:sendAnalyticsEvent:)"
```
