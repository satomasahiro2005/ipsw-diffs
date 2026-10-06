## HybridSearchResultRanker

> `/System/Library/PrivateFrameworks/HybridSearchResultRanker.framework/HybridSearchResultRanker`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xba9c0` | `0xbb36c` | **`+0x9ac`** |
| `__TEXT.__oslogstring` | `0x3bc6` | `0x3c96` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x1db4` | `0x1e74` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x6888` | `0x6940` | **`+0xb8`** |
| `__TEXT.__swift5_reflstr` | `0x1e66` | `0x1ec6` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x1490` | `0x14c0` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x22a4` | `0x22c8` | **`+0x24`** |
| `__TEXT.__const` | `0x43c8` | `0x43d8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1eb8` | `0x1ea8` | **`-0x10`** |
| `__AUTH.__data` | `0xde8` | `0xdf0` | **`+0x8`** |

### Other Changes

```diff

-67.0.0.0.0
+73.2.0.0.0

-  Functions: 4146
+  Functions: 4164

-  CStrings:  277
+  CStrings:  283
CStrings:
+ "CLIFF DETECTION SKIPPED: contact-resolution boost active — all %ld candidates are tophits"
+ "MailL2RankingContactResolutionBoostEnabled"
+ "MailL2RankingTophitCandidatePoolMultiplier"
+ "contact-resolution boost"
+ "contact_resolution_boost"
+ "unwanted_category"
+ "╟───────────────────────────────────────────────────────────────\n║ Total L1 Results (all scopes): %ld\n╠═══════════════════════════════════════════════════════════════\n║ Ranking Configuration:\n║   L2 Ranking: %s\n║   Temporal: %s\n║   Query Match: %s\n║   Engagement: %s\n║   Structural: %s\n║   Quality: %s\n║   Body Matching: %s\n║   Person Query Ranking: %s\n║   Contact Resolution Boost: %s\n║   Time-Sensitive Query Boost: %s\n╚═══════════════════════════════════════════════════════════════"
+ "╟───────────────────────────────────────────────────────────────\n║ Total L1 Results: %ld\n║ Query Limit: %ld\n║ Query Tophit Limit: %ld\n╠═══════════════════════════════════════════════════════════════\n║ Ranking Configuration:\n║   L2 Ranking: %s\n║   Temporal: %s\n║   Query Match: %s\n║   Engagement: %s\n║   Structural: %s\n║   Quality: %s\n║   Body Matching: %s\n║   Person Query Ranking: %s\n║   Contact Resolution Boost: %s\n║   Time-Sensitive Query Boost: %s\n╚═══════════════════════════════════════════════════════════════"
+ "╠═══════════════════════════════════════════════════════════════\n║ Ranking Configuration:\n║   L2 Ranking: %s\n║   Temporal: %s\n║   Query Match: %s\n║   Engagement: %s\n║   Structural: %s\n║   Quality: %s\n║   Body Matching: %s\n║   Person Query Ranking: %s\n║   Contact Resolution Boost: %s\n║   Time-Sensitive Query Boost: %s\n╚═══════════════════════════════════════════════════════════════"
- "╟───────────────────────────────────────────────────────────────\n║ Total L1 Results (all scopes): %ld\n╠═══════════════════════════════════════════════════════════════\n║ Ranking Configuration:\n║   L2 Ranking: %s\n║   Temporal: %s\n║   Query Match: %s\n║   Engagement: %s\n║   Structural: %s\n║   Quality: %s\n║   Body Matching: %s\n║   Person Query Ranking: %s\n║   Time-Sensitive Query Boost: %s\n╚═══════════════════════════════════════════════════════════════"
- "╟───────────────────────────────────────────────────────────────\n║ Total L1 Results: %ld\n║ Query Limit: %ld\n║ Query Tophit Limit: %ld\n╠═══════════════════════════════════════════════════════════════\n║ Ranking Configuration:\n║   L2 Ranking: %s\n║   Temporal: %s\n║   Query Match: %s\n║   Engagement: %s\n║   Structural: %s\n║   Quality: %s\n║   Body Matching: %s\n║   Person Query Ranking: %s\n║   Time-Sensitive Query Boost: %s\n╚═══════════════════════════════════════════════════════════════"
- "╠═══════════════════════════════════════════════════════════════\n║ Ranking Configuration:\n║   L2 Ranking: %s\n║   Temporal: %s\n║   Query Match: %s\n║   Engagement: %s\n║   Structural: %s\n║   Quality: %s\n║   Body Matching: %s\n║   Person Query Ranking: %s\n║   Time-Sensitive Query Boost: %s\n╚═══════════════════════════════════════════════════════════════"
```
