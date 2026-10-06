## PeopleSuggester

> `/System/Library/PrivateFrameworks/PeopleSuggester.framework/PeopleSuggester`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1db0` | `—` | **`-0x1db0`** |
| `__DATA_DIRTY.__objc_data` | `0x1950` | `0x3700` | **`+0x1db0`** |
| `__DATA.__data` | `0x428` | `—` | **`-0x428`** |
| `__DATA_DIRTY.__data` | `—` | `0x428` | **`+0x428`** |
| `__TEXT.__text` | `0x1291b4` | `0x1292c0` | **`+0x10c`** |
| `__AUTH_CONST.__auth_got` | `0x800` | `0x808` | **`+0x8`** |

### Other Changes

```diff

-1975.0.0.0.0
+1976.0.0.0.0

-  Symbols:   7993
+  Symbols:   7994
Symbols:
+ __CDStringByConvertingPhoneNumberStringToASCII
Functions:
~ -[_PSContactCache getContactForHandle:handleType:] : 1136 -> 1156
~ -[_PSEnsembleModel suggestionsFromSuggestionProxies:supportedBundleIDs:contactKeysToFetch:meContactIdentifier:maxSuggestions:predictionContext:] : 15060 -> 15156
~ -[_PSEnsembleModel psr_suggestionsFromSuggestionProxies:interactionsStatistics:maxSuggestions:predictionContext:] : 1960 -> 1988
~ ___37-[_PSFamilyRecommender currentFamily]_block_invoke : 1444 -> 1472
~ -[_PSContactResolver resolveContactIdentifier:] : 812 -> 828
~ -[_PSContactResolver resolveContactIfPossibleFromContactIdentifierString:pickFirstOfMultiple:] : 280 -> 308
~ +[_PSContactResolver normalizedHandlesDictionaryFromHandles:] : 416 -> 448
~ -[_PSContactCatalog resolveVisualIdentifiersForHandles:catalogContactData:keepGoing:] : 8932 -> 8952
```
