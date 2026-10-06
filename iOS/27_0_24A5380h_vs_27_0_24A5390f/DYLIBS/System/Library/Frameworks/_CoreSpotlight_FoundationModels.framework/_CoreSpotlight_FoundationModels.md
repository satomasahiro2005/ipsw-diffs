## _CoreSpotlight_FoundationModels

> `/System/Library/Frameworks/_CoreSpotlight_FoundationModels.framework/_CoreSpotlight_FoundationModels`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x424204` | `0x4253cc` | **`+0x11c8`** |
| `__TEXT.__cstring` | `0x2a6d3` | `0x2a9a3` | **`+0x2d0`** |
| `__TEXT.__const` | `0xac3f2` | `0xac512` | **`+0x120`** |
| `__AUTH.__data` | `0x9c80` | `0x9d00` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x36d58` | `0x36ce0` | **`-0x78`** |
| `__TEXT.__swift5_mpenum` | `0xbe8` | `0xbb8` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x13790` | `0x137c0` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x13820` | `0x13844` | **`+0x24`** |
| `__AUTH_CONST.__auth_got` | `0x1240` | `0x1250` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x53d7` | `0x53e7` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0xdf60` | `0xdf6c` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x868` | `0x870` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x1a164` | `0x1a16c` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x117fa` | `0x117f2` | **`-0x8`** |

### Other Changes

```diff

-2451.1.101.0.0
+2454.100.0.0.0

-  Functions: 27996
-  Symbols:   9147
-  CStrings:  2101
+  Functions: 28007
+  Symbols:   9148
+  CStrings:  2106
Symbols:
+ _symbolic SDy_____Say_____GG 13CoreSpotlight23SearchableItemAttributeV AA0cD0V
+ _symbolic Say_____G 13CoreSpotlight14SearchableItemV
+ _symbolic _____ 13CoreSpotlight14SearchableItemV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 13CoreSpotlight14SearchableItemV
- _symbolic SDy_____SaySo16CSSearchableItemCGG 13CoreSpotlight23SearchableItemAttributeV
- _symbolic So16CSSearchableItemC
- _type_layout_string 31_CoreSpotlight_FoundationModels20ScoredSearchableItemV
CStrings:
+ "  Combine via operation when both apply (e.g. paraphrase intent narrowed by a literal name): semanticSimilar AND allText."
+ "  allText — full-text search across default-indexed fields. Use when a specific word, name, or phrase MUST appear literally. To match kMDItemKeywords specifically, use a predicate node with attribute:\"kMDItemKeywords\"."
+ "  semanticSimilar — embedding similarity to a query phrase. Default for topic / paraphrase / \"about X\" / \"similar to\" intent, where the user's words may not appear verbatim in the result. Pass the user's prompt as the query string."
+ "**Free-form text:** Two nodes serve different intents — pick by what the user actually asked for."
+ "- Literal word that must appear → allText node"
+ "- Topic / paraphrase / \"about X\" / \"similar to\" → semanticSimilar node (default for free-form intent)"
+ "Content words for keyword fallback — items without embeddings match via these terms. Extract content-bearing words from the phrase, dropping particles and prepositions."
+ "User's full natural language phrase for embedding-similarity search."
- "**Full-text search:** Use allText node for free-form full-text search across all default-indexed fields (subject, body, displayName, etc. — NOT field-specific). To match kMDItemKeywords specifically, use a predicate node with attribute:\"kMDItemKeywords\"."
- "- Search terms → allText node"
- "Query text for semantic similarity (e.g., 'machine learning research', 'vacation photos', 'budget planning')."
```
