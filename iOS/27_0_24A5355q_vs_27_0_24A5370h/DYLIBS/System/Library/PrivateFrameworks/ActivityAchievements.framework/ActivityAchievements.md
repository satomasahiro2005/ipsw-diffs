## ActivityAchievements

> `/System/Library/PrivateFrameworks/ActivityAchievements.framework/ActivityAchievements`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d05c` | `0x3cfb0` | **`-0xac`** |

### Other Changes

```diff

-2027.0.18.0.0
+2027.0.20.0.0
Functions:
~ _ACHCodableFromAchievement : 1680 -> 1676
~ _ACHTemplateAlertDatesStringFromDates : 344 -> 340
~ -[ACHAchievement initWithCodable:] : 1660 -> 1656
~ _ACHTemplateAlertDatesFromString : 348 -> 344
~ -[ACHVisibilityEvaluator unearnedAchievementIsVisibleNow:activityMoveMode:experienceType:isFitnessPlusSubscriber:isWheelchairUser:] : 1584 -> 1580
~ -[ACHAchievementLocalizationProvider _localizedStringWithKey:withAchievement:experienceType:] : 604 -> 600
~ -[ACHCodableAchievement writeTo:] : 1600 -> 1588
~ _RemoteAchievementTemplateFromTemplateAssetAndBuildVersion : 1588 -> 1584
~ -[ACHAchievementLocalizationProvider _pluralizeLocalizedString:withAchievement:] : 1296 -> 1284
~ -[ACHAchievementLocalizationProvider _replacePlaceholdersInString:withAchievement:] : 1056 -> 1060
~ -[ACHCodableAchievementAnniversaryRequest writeTo:] : 316 -> 312
~ -[ACHCodableAchievementAnniversaryRequest copyWithZone:] : 364 -> 360
~ -[ACHCodableAchievementAnniversaryRequest mergeFrom:] : 308 -> 304
~ -[ACHCodableTemplateArray dictionaryRepresentation] : 404 -> 400
~ -[ACHCodableTemplateArray writeTo:] : 276 -> 272
~ -[ACHCodableTemplateArray copyWithZone:] : 316 -> 312
~ -[ACHCodableTemplateArray mergeFrom:] : 260 -> 256
~ -[ACHCodableTemplateNameArray writeTo:] : 276 -> 272
~ -[ACHCodableTemplateNameArray copyWithZone:] : 316 -> 312
~ -[ACHCodableTemplateNameArray mergeFrom:] : 260 -> 256
~ -[ACHCodableAchievementProgressUpdateArray dictionaryRepresentation] : 404 -> 400
~ -[ACHCodableAchievementProgressUpdateArray writeTo:] : 276 -> 272
~ -[ACHCodableAchievementProgressUpdateArray copyWithZone:] : 316 -> 312
~ -[ACHCodableAchievementProgressUpdateArray mergeFrom:] : 260 -> 256
~ -[ACHCodableAchievementArray dictionaryRepresentation] : 404 -> 400
~ -[ACHCodableAchievementArray writeTo:] : 276 -> 272
~ -[ACHCodableAchievementArray copyWithZone:] : 316 -> 312
~ -[ACHCodableAchievementArray mergeFrom:] : 260 -> 256
~ -[ACHCodableEarnedInstanceArray dictionaryRepresentation] : 404 -> 400
~ -[ACHCodableEarnedInstanceArray writeTo:] : 276 -> 272
~ -[ACHCodableEarnedInstanceArray copyWithZone:] : 316 -> 312
~ -[ACHCodableEarnedInstanceArray mergeFrom:] : 260 -> 256
~ -[ACHAwardsClient fetchEarnedInstancesForDateInterval:error:] : 816 -> 812
~ -[ACHCodableAchievement dictionaryRepresentation] : 2036 -> 2032
~ -[ACHCodableAchievement copyWithZone:] : 1904 -> 1892
~ -[ACHCodableAchievement mergeFrom:] : 1808 -> 1796
~ _ACHMonthlyChallengeAchievementFromAchievementsForDate : 464 -> 460
```
