## PhotoAnalysis

> `/System/Library/PrivateFrameworks/PhotoAnalysis.framework/PhotoAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x283af0` | `0x283cc0` | **`+0x1d0`** |
| `__AUTH_CONST.__cfstring` | `0x8360` | `0x83e0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x105f3` | `0x10661` | **`+0x6e`** |

### Other Changes

```diff

-916.51.202.0.0
+916.57.151.0.0

-  CStrings:  3214
+  CStrings:  3218
Functions:
~ -[PHAWallpaperSuggestionAnalyticsSender wallpaperGenerationSummaryWithGeneratedSuggestionLocalIdentifiers:] : 876 -> 964
~ -[PHAWallpaperSuggestionAnalyticsSender existingWallpaperSuggestionSummary] : 1268 -> 1356
~ +[PHAWallpaperSuggestionAnalyticsSender wallpaperSuggestionStatisticsFromSuggestions:] : 556 -> 628
~ -[PHAWallpaperSuggestionAnalyticsSender ambientGenerationSummaryWithGeneratedSuggestionLocalIdentifiers:] : 684 -> 732
~ +[PHAWallpaperSuggestionAnalyticsSender ambientSuggestionStatisticsFromSuggestions:] : 408 -> 448
~ -[PHAWallpaperSuggestionAnalyticsSender existingAmbientSuggestionSummary] : 816 -> 864
~ +[PHAWallpaperSuggestionGenerationUtils isGraphDependentSubtype:] : 308 -> 336
~ -[PHAWallpaperSuggestionRefreshSession fetchSuggestionsForGalleryDonationWithSuggestionUUIDsToAvoid:] : 1268 -> 1320
CStrings:
+ "group_suggestion_count"
+ "group_suggestions_generated"
+ "top_group_suggestion_count"
+ "top_group_suggestions_generated"
```
