## NewsToday

> `/System/Library/PrivateFrameworks/NewsToday.framework/NewsToday`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x45904` | `0x460c0` | **`+0x7bc`** |
| `__TEXT.__oslogstring` | `0x16f0` | `0x17e0` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x8f85` | `0x9025` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x17f0` | `0x1888` | **`+0x98`** |
| `__AUTH_CONST.__objc_const` | `0xdf20` | `0xdf80` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x4e0` | `0x490` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x1068` | `0x10b8` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d98` | `0x3dc8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x6504` | `0x652c` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0xda8` | `0xdc8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xea8` | `0xeb8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x5c4` | `0x5cc` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xa80` | `0xa88` | **`+0x8`** |

### Other Changes

```diff

-5920.0.0.0.0
+5923.0.0.0.0

-  Functions: 2009
-  Symbols:   3255
-  CStrings:  820
+  Functions: 2016
+  Symbols:   3268
+  CStrings:  825
Symbols:
+ -[NTForYouSectionFetchDescriptor initWithForYouConfiguration:appConfiguration:topStoriesChannelID:localNewsTagID:localNewsSelectionCriteria:hiddenFeedIDs:allowPaidBundleFeed:mutedTagIDs:purchasedTagIDs:rankedAllSubscribedTagIDs:paidAccessChecker:groupingService:]
+ -[NTForYouSectionFetchDescriptor localNewsSelectionCriteria]
+ -[NTLocalNewsPromotionTransformation initWithLocalNewsTagID:localNewsPromotionIndex:localNewsSelectionCriteria:baseTransformation:]
+ -[NTLocalNewsPromotionTransformation localNewsSelectionCriteria]
+ -[NTNewsTodayResultOperation _assembleQueueDescriptorsWithConfig:allowOnlyWatchEligibleSections:respectsWidgetVisibleSectionsLimit:personalizationTreatment:aggregateStore:appConfiguration:todayData:localNewsSelectionCriteria:completion:]
+ -[NTNewsTodayResultOperation _resolveLocalNewsSelectionCriteriaWithAppConfig:]
+ -[NTQueueConfigSectionQueueDescriptor initWithQueueConfig:appConfiguration:todayData:localNewsSelectionCriteria:inFavoritesOnlyMode:respectsWidgetVisibleSectionsLimit:groupingService:]
+ -[NTSectionConfigSectionDescriptor initWithSectionConfig:appConfiguration:topStoriesChannelID:hiddenFeedIDs:allowPaidBundleFeed:todayData:localNewsSelectionCriteria:supplementalFeedFilterOptions:groupingService:]
+ _FCURLForLocalNewsSelectionCriteria
+ _OBJC_CLASS_$_FCFeedTransformationLowQualityContentFilter
+ _OBJC_CLASS_$_FCFileCoordinatedLocalNewsSelectionCriteriaDropbox
+ _OBJC_CLASS_$_FCLocalNewsSelectionCriteria
+ _OBJC_IVAR_$_NTForYouSectionFetchDescriptor._localNewsSelectionCriteria
+ _OBJC_IVAR_$_NTLocalNewsPromotionTransformation._localNewsSelectionCriteria
+ ___184-[NTQueueConfigSectionQueueDescriptor initWithQueueConfig:appConfiguration:todayData:localNewsSelectionCriteria:inFavoritesOnlyMode:respectsWidgetVisibleSectionsLimit:groupingService:]_block_invoke
+ ___237-[NTNewsTodayResultOperation _assembleQueueDescriptorsWithConfig:allowOnlyWatchEligibleSections:respectsWidgetVisibleSectionsLimit:personalizationTreatment:aggregateStore:appConfiguration:todayData:localNewsSelectionCriteria:completion:]_block_invoke
+ ___237-[NTNewsTodayResultOperation _assembleQueueDescriptorsWithConfig:allowOnlyWatchEligibleSections:respectsWidgetVisibleSectionsLimit:personalizationTreatment:aggregateStore:appConfiguration:todayData:localNewsSelectionCriteria:completion:]_block_invoke_2
+ ___237-[NTNewsTodayResultOperation _assembleQueueDescriptorsWithConfig:allowOnlyWatchEligibleSections:respectsWidgetVisibleSectionsLimit:personalizationTreatment:aggregateStore:appConfiguration:todayData:localNewsSelectionCriteria:completion:]_block_invoke_3
+ ___237-[NTNewsTodayResultOperation _assembleQueueDescriptorsWithConfig:allowOnlyWatchEligibleSections:respectsWidgetVisibleSectionsLimit:personalizationTreatment:aggregateStore:appConfiguration:todayData:localNewsSelectionCriteria:completion:]_block_invoke_4
+ ___57-[NTLocalNewsPromotionTransformation transformFeedItems:]_block_invoke_3
+ ___78-[NTNewsTodayResultOperation _resolveLocalNewsSelectionCriteriaWithAppConfig:]_block_invoke
+ ___block_descriptor_32_e24_"NSSet"16?0"NSArray"8l
+ ___block_descriptor_40_e8_32s_e5_B8?0ls32l8
+ ___block_descriptor_48_e8_32s40s_e36_B16?0"<NTFeedTransformationItem>"8ls32l8s40l8
+ ___block_descriptor_65_e8_32s40s48s56s_e66_"NTSectionConfigSectionDescriptor"16?0"NTPBTodaySectionConfig"8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_66_e8_32s40s48s56s_e58_"<NTSectionQueueDescriptor>"16?0"NTPBTodayQueueConfig"8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_72_e8_32s40s48s56s_e5_B8?0ls32l8s40l8s48l8s56l8
- -[NTForYouSectionFetchDescriptor initWithForYouConfiguration:appConfiguration:topStoriesChannelID:localNewsTagID:hiddenFeedIDs:allowPaidBundleFeed:mutedTagIDs:purchasedTagIDs:rankedAllSubscribedTagIDs:paidAccessChecker:groupingService:]
- -[NTLocalNewsPromotionTransformation initWithLocalNewsTagID:localNewsPromotionIndex:baseTransformation:]
- -[NTNewsTodayResultOperation _assembleQueueDescriptorsWithConfig:allowOnlyWatchEligibleSections:respectsWidgetVisibleSectionsLimit:personalizationTreatment:aggregateStore:appConfiguration:todayData:completion:]
- -[NTQueueConfigSectionQueueDescriptor initWithQueueConfig:appConfiguration:todayData:inFavoritesOnlyMode:respectsWidgetVisibleSectionsLimit:groupingService:]
- -[NTSectionConfigSectionDescriptor initWithSectionConfig:appConfiguration:topStoriesChannelID:hiddenFeedIDs:allowPaidBundleFeed:todayData:supplementalFeedFilterOptions:groupingService:]
- ___157-[NTQueueConfigSectionQueueDescriptor initWithQueueConfig:appConfiguration:todayData:inFavoritesOnlyMode:respectsWidgetVisibleSectionsLimit:groupingService:]_block_invoke
- ___210-[NTNewsTodayResultOperation _assembleQueueDescriptorsWithConfig:allowOnlyWatchEligibleSections:respectsWidgetVisibleSectionsLimit:personalizationTreatment:aggregateStore:appConfiguration:todayData:completion:]_block_invoke
- ___210-[NTNewsTodayResultOperation _assembleQueueDescriptorsWithConfig:allowOnlyWatchEligibleSections:respectsWidgetVisibleSectionsLimit:personalizationTreatment:aggregateStore:appConfiguration:todayData:completion:]_block_invoke_2
- ___210-[NTNewsTodayResultOperation _assembleQueueDescriptorsWithConfig:allowOnlyWatchEligibleSections:respectsWidgetVisibleSectionsLimit:personalizationTreatment:aggregateStore:appConfiguration:todayData:completion:]_block_invoke_3
- ___210-[NTNewsTodayResultOperation _assembleQueueDescriptorsWithConfig:allowOnlyWatchEligibleSections:respectsWidgetVisibleSectionsLimit:personalizationTreatment:aggregateStore:appConfiguration:todayData:completion:]_block_invoke_4
- ___57-[NTLocalNewsPromotionTransformation transformFeedItems:]_block_invoke_2
- ___block_descriptor_57_e8_32s40s48s_e66_"NTSectionConfigSectionDescriptor"16?0"NTPBTodaySectionConfig"8ls32l8s40l8s48l8
- ___block_descriptor_58_e8_32s40s48s_e58_"<NTSectionQueueDescriptor>"16?0"NTPBTodayQueueConfig"8ls32l8s40l8s48l8
- _swift_willThrowTypedImpl
CStrings:
+ "-[NTForYouSectionFetchDescriptor initWithForYouConfiguration:appConfiguration:topStoriesChannelID:localNewsTagID:localNewsSelectionCriteria:hiddenFeedIDs:allowPaidBundleFeed:mutedTagIDs:purchasedTagIDs:rankedAllSubscribedTagIDs:paidAccessChecker:groupingService:]"
+ "-[NTLocalNewsPromotionTransformation initWithLocalNewsTagID:localNewsPromotionIndex:localNewsSelectionCriteria:baseTransformation:]"
+ "-[NTNewsTodayResultOperation _assembleQueueDescriptorsWithConfig:allowOnlyWatchEligibleSections:respectsWidgetVisibleSectionsLimit:personalizationTreatment:aggregateStore:appConfiguration:todayData:localNewsSelectionCriteria:completion:]"
+ "-[NTQueueConfigSectionQueueDescriptor initWithQueueConfig:appConfiguration:todayData:localNewsSelectionCriteria:inFavoritesOnlyMode:respectsWidgetVisibleSectionsLimit:groupingService:]"
+ "-[NTSectionConfigSectionDescriptor initWithSectionConfig:appConfiguration:topStoriesChannelID:hiddenFeedIDs:allowPaidBundleFeed:todayData:localNewsSelectionCriteria:supplementalFeedFilterOptions:groupingService:]"
+ "@\"NSSet\"16@?0@\"NSArray\"8"
+ "B8@?0"
+ "allowing local news candidate %{public}@ because we have no selection criteria"
+ "rejecting local news candidate %{public}@ because it has no feed transformation item"
+ "rejecting local news candidate %{public}@ for reason: %{public}@"
+ "returning For You without regard for local news because we could not find any eligible articles for the local news channel"
- "-[NTForYouSectionFetchDescriptor initWithForYouConfiguration:appConfiguration:topStoriesChannelID:localNewsTagID:hiddenFeedIDs:allowPaidBundleFeed:mutedTagIDs:purchasedTagIDs:rankedAllSubscribedTagIDs:paidAccessChecker:groupingService:]"
- "-[NTLocalNewsPromotionTransformation initWithLocalNewsTagID:localNewsPromotionIndex:baseTransformation:]"
- "-[NTNewsTodayResultOperation _assembleQueueDescriptorsWithConfig:allowOnlyWatchEligibleSections:respectsWidgetVisibleSectionsLimit:personalizationTreatment:aggregateStore:appConfiguration:todayData:completion:]"
- "-[NTQueueConfigSectionQueueDescriptor initWithQueueConfig:appConfiguration:todayData:inFavoritesOnlyMode:respectsWidgetVisibleSectionsLimit:groupingService:]"
- "-[NTSectionConfigSectionDescriptor initWithSectionConfig:appConfiguration:topStoriesChannelID:hiddenFeedIDs:allowPaidBundleFeed:todayData:supplementalFeedFilterOptions:groupingService:]"
- "returning For You without regard for local news because we could not find any articles for the local news channel"
```
