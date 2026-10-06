## MenstrualCyclesAppPlugin

> `/System/Library/Health/FeedItemPlugins/MenstrualCyclesAppPlugin.healthplugin/MenstrualCyclesAppPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x58857c` | `0x588dc4` | **`+0x848`** |
| `__AUTH_CONST.__const` | `0x19c38` | `0x19ff0` | **`+0x3b8`** |
| `__TEXT.__const` | `0x266a4` | `0x268f4` | **`+0x250`** |
| `__DATA.__bss` | `0x219e8` | `0x21b98` | **`+0x1b0`** |
| `__TEXT.__cstring` | `0x1a688` | `0x1a828` | **`+0x1a0`** |
| `__DATA.__data` | `0xb4d8` | `0xb3d8` | **`-0x100`** |
| `__TEXT.__oslogstring` | `0xcf2c` | `0xce2c` | **`-0x100`** |
| `__TEXT.__eh_frame` | `0xf5d4` | `0xf6b4` | **`+0xe0`** |
| `__TEXT.__swift5_capture` | `0x51d4` | `0x52a4` | **`+0xd0`** |
| `__AUTH.__objc_data` | `0xefd8` | `0xef28` | **`-0xb0`** |
| `__AUTH_CONST.__objc_const` | `0x1b820` | `0x1b8d0` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0xb0d8` | `0xb060` | **`-0x78`** |
| `__AUTH.__data` | `0xcee8` | `0xce78` | **`-0x70`** |
| `__TEXT.__swift5_reflstr` | `0x11902` | `0x11892` | **`-0x70`** |
| `__AUTH_CONST.__auth_got` | `0x5cf0` | `0x5d40` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x11b60` | `0x11b20` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0xec50` | `0xec10` | **`-0x40`** |
| `__DATA.__common` | `0xb40` | `0xb08` | **`-0x38`** |
| `__TEXT.__swift5_fieldmd` | `0xe344` | `0xe36c` | **`+0x28`** |
| `__TEXT.__swift5_assocty` | `0x1e98` | `0x1e80` | **`-0x18`** |
| `__DATA_DIRTY.__data` | `0x75e8` | `0x75f8` | **`+0x10`** |
| `__DATA_DIRTY.__objc_data` | `0x2f88` | `0x2f98` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x1808` | `0x1818` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3378` | `0x3380` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xc40` | `0xc48` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x34f8` | `0x3500` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0x4c0` | `0x4b8` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x5894` | `0x588c` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0xa04` | `0xa0c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xea4` | `0xea8` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x4b8` | `0x4bc` | **`+0x4`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 20529
-  Symbols:   763
-  CStrings:  3137
+  Functions: 20513
+  Symbols:   764
+  CStrings:  3140
Symbols:
+ _OBJC_CLASS_$_UITabBarController
+ _UIViewControllerInteractionActivityTrackingDisabled
- _HKMCPerimenopauseContentEligibilityMinimumAge
CStrings:
+ "AddMenopauseStageExecutor:queryPerimenopauseFlaggedDeviations"
+ "CycleAnalysisObserverShim:startObserving"
+ "CycleChartPDFModel:makePDFModel"
+ "CycleFactorsDaySummaryCollectionViewController:requestAnalysisUpdate"
+ "CycleFactorsHistoryCollectionViewController:requestAnalysisUpdate"
+ "CycleFactorsHistoryCollectionViewController:startHistoricalFactorsQuery"
+ "CycleTrackingFavorites"
+ "DashboardVisibilityFavoritesDataSourceObservers"
+ "DashboardVisibilityToggleSection"
+ "MenopauseSymptomsPDFModel:query"
+ "MenstrualCyclesAppPlugin.CycleTrackingFavoritesVisibilityDataSource"
+ "MenstrualCyclesAppPlugin/CycleFactorsReminderGeneratorPipeline.swift"
+ "MenstrualCyclesAppPlugin/SleepingWristTemperatureBaselineRelativeDataSource.swift"
+ "MenstrualCyclesAppPlugin/SleepingWristTemperatureHelpTileGenerator.swift"
+ "SensorFeatureStatusModel:init"
- "MenstrualCyclesAppPlugin.FavoriteStateDataSource"
- "MenstrualCyclesAppPlugin/MenopauseDefinitionBodyView.swift"
- "MoreDataSource_Favorites"
- "MoreDataSource_FavoritesDescription"
- "[%{public}s).%{public}s] (shownWithHighPriority) %s"
- "[%{public}s).%{public}s] Some health profile information missing"
- "[%{public}s] (shownWithHighPriority) %s"
- "[%{public}s] Some health profile information missing"
- "female and within age range"
- "init(managedObjectContext:pinnedContentManager:predicate:cellClass:)"
- "init(managedObjectContext:pinnedContentManagerProvider:predicate:cellClass:)"
- "translateToFeedItemShouldDisplay(analysis:isOnboardingCompleted:userCharacteristics:)"
```
