## CoreSpotlightAgenticCore

> `/System/Library/PrivateFrameworks/CoreSpotlightAgenticCore.framework/CoreSpotlightAgenticCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x408e2c` | `0x409688` | **`+0x85c`** |
| `__TEXT.__cstring` | `0x2a5b9` | `0x2a819` | **`+0x260`** |
| `__TEXT.__const` | `0xaa898` | `0xaa9d8` | **`+0x140`** |
| `__TEXT.__swift5_mpenum` | `0xbac` | `0xb7c` | **`-0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x12e48` | `0x12e6c` | **`+0x24`** |
| `__TEXT.__swift5_reflstr` | `0x4e66` | `0x4e76` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0x34e08` | `0x34e10` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x193bc` | `0x193c4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x131a8` | `0x131b0` | **`+0x8`** |

### Other Changes

```diff

-2451.1.101.0.0
+2454.100.0.0.0

-  Functions: 27400
+  Functions: 27404

-  CStrings:  2086
+  CStrings:  2090
CStrings:
+ "  Combine semanticSimilar AND allText when paraphrase intent is narrowed by a required literal term."
+ "  Use allText alone only when a specific word or name MUST appear literally in the result. To match kMDItemKeywords specifically, use a predicate node with attribute:\"kMDItemKeywords\"."
+ "**Free-form text:** For topic/paraphrase/\"about X\"/\"similar to\" intent, use semanticSimilar — fill `query` with the full NL phrase and `keywords` with content-bearing words (drop particles and prepositions). The keyword fallback is compiled in automatically."
+ "- Literal word that must appear → allText node"
+ "- Semantic/topic intent (\"about X\", paraphrase, \"similar to\") → semanticSimilar(query: full phrase, keywords: key terms)"
+ "Content words for keyword fallback — items without embeddings match via these terms. Extract content-bearing words from the phrase, dropping particles and prepositions."
+ "User's full natural language phrase for embedding-similarity search."
- "**Full-text search:** Use allText node for free-form full-text search across all default-indexed fields (subject, body, displayName, etc. — NOT field-specific). To match kMDItemKeywords specifically, use a predicate node with attribute:\"kMDItemKeywords\"."
- "- Search terms → allText node"
- "Query text for semantic similarity (e.g., 'machine learning research', 'vacation photos', 'budget planning')."
```
