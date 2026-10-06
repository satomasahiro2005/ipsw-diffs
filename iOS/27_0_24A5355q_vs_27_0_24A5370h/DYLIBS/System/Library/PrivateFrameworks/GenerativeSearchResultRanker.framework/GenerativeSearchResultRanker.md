## GenerativeSearchResultRanker

> `/System/Library/PrivateFrameworks/GenerativeSearchResultRanker.framework/GenerativeSearchResultRanker`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9e4bc` | `0xab460` | **`+0xcfa4`** |
| `__AUTH_CONST.__const` | `0x5bd0` | `0x6450` | **`+0x880`** |
| `__TEXT.__swift5_reflstr` | `0x17eb` | `0x1cab` | **`+0x4c0`** |
| `__DATA.__bss` | `0x3dc0` | `0x4150` | **`+0x390`** |
| `__TEXT.__const` | `0x3e30` | `0x41b0` | **`+0x380`** |
| `__TEXT.__swift5_fieldmd` | `0x1e0c` | `0x2158` | **`+0x34c`** |
| `__TEXT.__swift5_capture` | `0x112c` | `0x1380` | **`+0x254`** |
| `__TEXT.__oslogstring` | `0x3876` | `0x3ab6` | **`+0x240`** |
| `__TEXT.__unwind_info` | `0x1a18` | `0x1c50` | **`+0x238`** |
| `__TEXT.__swift5_typeref` | `0x1da6` | `0x1f6a` | **`+0x1c4`** |
| `__TEXT.__eh_frame` | `0x3b30` | `0x3ce8` | **`+0x1b8`** |
| `__AUTH_CONST.__auth_got` | `0x1078` | `0x11e0` | **`+0x168`** |
| `__TEXT.__cstring` | `0x1af4` | `0x1c04` | **`+0x110`** |
| `__DATA.__data` | `0xe70` | `0xf10` | **`+0xa0`** |
| `__AUTH.__data` | `0xb90` | `0xc18` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0xe8` | `0x170` | **`+0x88`** |
| `__TEXT.__constg_swiftt` | `0xdcc` | `0xe50` | **`+0x84`** |
| `__TEXT.__swift5_proto` | `0x1f4` | `0x210` | **`+0x1c`** |
| `__DATA_DIRTY.__data` | `0x410` | `0x420` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x18c` | `0x19c` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0xdc` | `0xe8` | **`+0xc`** |
| `__DATA.__common` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xf8` | `0x100` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x1b4` | `0x1b8` | **`+0x4`** |

### Other Changes

```diff

-53.0.0.0.0
+57.0.1.0.0

+  - /System/Library/PrivateFrameworks/BiomeLibrary.framework/BiomeLibrary

-  Functions: 3521
-  Symbols:   172
-  CStrings:  255
+  Functions: 3842
+  Symbols:   189
+  CStrings:  265
Symbols:
+ _BiomeLibrary
+ _OBJC_CLASS_$_BML1Score
+ _OBJC_CLASS_$_BML2Score
+ _OBJC_CLASS_$_BMMailRankerEvent
+ _OBJC_CLASS_$_BMMessageFeatures
+ _OBJC_CLASS_$_BMQueryMatchInfo
+ _OBJC_CLASS_$_BMRankedMailItem
+ _OBJC_CLASS_$_BMResultsRankedGLP
+ _OBJC_CLASS_$_NSNumber
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _free
+ _objc_retain_x21
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_coroFrameAlloc
+ _swift_task_create
CStrings:
+ "(not all persons)"
+ "@[^@\\s]+\\.[a-z]{3,}$"
+ "MailCoreRanker.featureExtraction"
+ "MailDomainCrossTypeRanker.emitBiomeSignals"
+ "MailL2RankingAmbiguousDateFilterDemotionEnabled"
+ "MailL2RankingMatchTypeDemotionMultiplier"
+ "TOPHIT DIVERSIFICATION SKIPPED: %s"
+ "date or person annotations in query"
+ "domain_match_type_demote"
+ "expectedSessionIds"
+ "isFlagged filter"
+ "items=%ld"
+ "match_type_demotion"
+ "╔═══════════════════════════════════════════════════════════════\n║ L2 RANKING CONTEXT\n╠═══════════════════════════════════════════════════════════════\n║ Original Query: \"%s\"\n║ Original Search Terms: %s\n║ Query Token Sets: %s\n║ Query Filter Attributes: %s\n║ Parsed Date Ranges: %s\n║ QueryParserOutput: %s\n║ PersonQueryInfo: %s\n║ SearchEntryPoint: %s\n║ UserProvidedFilter: %s\n╚═══════════════════════════════════════════════════════════════"
+ "╟───────────────────────────────────────────────────────────────\n║ Total L1 Results (all scopes): %ld\n╠═══════════════════════════════════════════════════════════════\n║ Ranking Configuration:\n║   L2 Ranking: %s\n║   Temporal: %s\n║   Query Match: %s\n║   Engagement: %s\n║   Structural: %s\n║   Quality: %s\n║   Body Matching: %s\n║   Person Query Ranking: %s\n╚═══════════════════════════════════════════════════════════════"
- "GenerativeSearchResultRanker/MailFeatures.swift"
- "TOPHIT DIVERSIFICATION SKIPPED: date or person annotations in query"
- "^[A-Za-z0-9._%+\\-]+@[A-Za-z0-9.\\-]+\\.[A-Za-z]{2,}$"
- "skipped (date or person annotations in query)"
- "╟───────────────────────────────────────────────────────────────\n║ Total L1 Results (all scopes): %ld\n╠═══════════════════════════════════════════════════════════════\n║ Ranking Configuration:\n║   L2 Ranking: %s\n║   Temporal: %s\n║   Query Match: %s\n║   Engagement: %s\n║   Structural: %s\n║   Quality: %s\n║   Body Matching: %s\n║   Person Query Ranking: %s\n╟───────────────────────────────────────────────────────────────\n║ SearchEntryPoint: %s\n║ UserProvidedFilter: %s\n║ QueryParserOutput: %s\n╚═══════════════════════════════════════════════════════════════"
```
