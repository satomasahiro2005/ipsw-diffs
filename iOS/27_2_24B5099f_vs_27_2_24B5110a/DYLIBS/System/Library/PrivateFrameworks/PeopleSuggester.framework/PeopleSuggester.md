## PeopleSuggester

> `/System/Library/PrivateFrameworks/PeopleSuggester.framework/PeopleSuggester`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x1124c` | `0x1122c` | **`-0x20`** |
| `__TEXT.__text` | `0x1292c0` | `0x1292b4` | **`-0xc`** |
| `__DATA_CONST.__got` | `0xa50` | `0xa48` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x7150` | `0x7148` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x35d8` | `0x35d0` | **`-0x8`** |

### Other Changes

```diff

-1976.0.0.0.0
+1977.0.0.0.0

-  - /System/Library/PrivateFrameworks/ProactiveEventTracker.framework/ProactiveEventTracker

-  Symbols:   7994
+  Symbols:   7993
Symbols:
- _OBJC_CLASS_$_PETEventTracker2
Functions:
~ -[_PSInteractionsStatistics(StaticFeatures) computeTimeSinceLastPhoneCallWithConversationId:interactionRecord:] : 364 -> 380
~ -[_PSInteractionsStatistics(StaticFeatures) computeTimeSinceLastIncomingInteractionForConversationId:interactionRecord:] : 240 -> 264
~ -[_PSInteractionsStatistics loadFeaturesAndPropertiesFromContactCatalog] : 4144 -> 4136
~ ___61-[_PSEnsembleModel sendDataToPETAsync:withConfig:andContext:]_block_invoke : 180 -> 136
CStrings:
+ "Loaded contact catalog: %lu conversations, %lu features, %lu properties, %lu personId sets, %lu bundleId counts, %lu visual identifiers, latencyMs=%.2f"
+ "_PSEnsemble: sent data to Biome"
- "Loaded contact catalog: %lu conversations, %lu features, %lu properties, %lu personId sets, %lu bundleId counts, %lu visual identifiers (skipped %lu timeSince* features), latencyMs=%.2f"
- "_PSEnsemble: sent data to PET"
```
