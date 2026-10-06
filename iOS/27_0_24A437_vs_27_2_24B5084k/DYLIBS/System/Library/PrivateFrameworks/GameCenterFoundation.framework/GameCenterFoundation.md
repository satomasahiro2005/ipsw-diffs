## GameCenterFoundation

> `/System/Library/PrivateFrameworks/GameCenterFoundation.framework/GameCenterFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x172f00` | `0x177630` | **`+0x4730`** |
| `__AUTH_CONST.__objc_const` | `0x245c8` | `0x24cd8` | **`+0x710`** |
| `__TEXT.__objc_methlist` | `0x121fc` | `0x12614` | **`+0x418`** |
| `__TEXT.__cstring` | `0x18ff0` | `0x19190` | **`+0x1a0`** |
| `__TEXT.__unwind_info` | `0x67d8` | `0x6928` | **`+0x150`** |
| `__AUTH.__objc_data` | `0x2b40` | `0x2c30` | **`+0xf0`** |
| `__TEXT.__oslogstring` | `0xdebb` | `0xdf4b` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0x12a0` | `0x12dc` | **`+0x3c`** |
| `__DATA_CONST.__const` | `0x61b0` | `0x61d8` | **`+0x28`** |
| `__DATA_CONST.__objc_superrefs` | `0x4f0` | `0x518` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0xfb0` | `0xfd4` | **`+0x24`** |
| `__AUTH_CONST.__const` | `0x6d08` | `0x6d28` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1108` | `0x1120` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x810` | `0x828` | **`+0x18`** |
| `__DATA.__bss` | `0x82e0` | `0x82f0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x8578` | `0x8588` | **`+0x10`** |

### Other Changes

```diff

-821.0.25.0.0
+821.1.8.0.0

-  Functions: 11229
-  Symbols:   12321
-  CStrings:  4204
+  Functions: 11343
+  Symbols:   12465
+  CStrings:  4213
Symbols:
+ +[GCFAchievement descriptionForAchievement:achievementDescriptions:]
+ +[GCFAchievement instanceMethodSignatureForSelector:]
+ +[GCFAchievement instancesRespondToSelector:]
+ +[GCFAchievement loadAchievementWithID:forGame:players:complete:]
+ +[GCFAchievement loadAchievementsForGameV2:player:includeUnreported:includeHidden:withCompletionHandler:]
+ +[GCFAchievement loadAchievementsForGameV2:players:includeUnreported:includeHidden:withCompletionHandler:]
+ +[GCFAchievement loadAchievementsWithCompletionHandler:]
+ +[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]
+ +[GCFAchievement reportAchievements:withCompletionHandler:]
+ +[GCFAchievement resetAchievementsWithCompletionHandler:]
+ +[GCFAchievement shouldShowBannerOnReport:achievementDescription:reportedAchievements:]
+ +[GCFAchievement shouldShowBannerOnReport:achievementDescription:reportedAchievements:uiFrameworkMethodsRequired:]
+ +[GCFAchievement shouldShowBannerOnReport:reportedAchievements:]
+ +[GCFAchievement shouldShowBannerOnReport:reportedAchievements:uiFrameworkMethodsRequired:]
+ +[GCFAchievement showBannerIsSupported]
+ +[GCFAchievement supportsSecureCoding]
+ +[GCFAchievementDescription _achievementDescriptionFromGame:propertyListDictionary:]
+ +[GCFAchievementDescription _loadLocalAchievementDescriptionsForGame:]
+ +[GCFAchievementDescription instanceMethodSignatureForSelector:]
+ +[GCFAchievementDescription instancesRespondToSelector:]
+ +[GCFAchievementDescription loadAchievementDescriptionsForGame:withCompletionHandler:]
+ +[GCFAchievementDescription loadAchievementDescriptionsWithCompletionHandler:]
+ +[GCFAchievementDescription supportsSecureCoding]
+ -[GCFAchievement .cxx_destruct]
+ -[GCFAchievement copyWithZone:]
+ -[GCFAchievement description]
+ -[GCFAchievement encodeWithCoder:]
+ -[GCFAchievement forwardingTargetForSelector:]
+ -[GCFAchievement game]
+ -[GCFAchievement hash]
+ -[GCFAchievement initWithCoder:]
+ -[GCFAchievement initWithIdentifier:]
+ -[GCFAchievement initWithIdentifier:forPlayer:]
+ -[GCFAchievement initWithIdentifier:player:]
+ -[GCFAchievement initWithIdentifier:player:percentComplete:lastReportedDate:]
+ -[GCFAchievement initWithInternalRepresentation:]
+ -[GCFAchievement initWithInternalRepresentation:playerID:]
+ -[GCFAchievement init]
+ -[GCFAchievement internal]
+ -[GCFAchievement isCompleted]
+ -[GCFAchievement isEqual:]
+ -[GCFAchievement methodSignatureForSelector:]
+ -[GCFAchievement playerID]
+ -[GCFAchievement player]
+ -[GCFAchievement reportAchievementWithCompletionHandler:]
+ -[GCFAchievement respondsToSelector:]
+ -[GCFAchievement setGame:]
+ -[GCFAchievement setInternal:]
+ -[GCFAchievement setShowsCompletionBanner:]
+ -[GCFAchievement setValue:forUndefinedKey:]
+ -[GCFAchievement showsCompletionBanner]
+ -[GCFAchievement valueForUndefinedKey:]
+ -[GCFAchievement(GCFAchievementDescription) _achievementDescription]
+ -[GCFAchievementDescription .cxx_destruct]
+ -[GCFAchievementDescription description]
+ -[GCFAchievementDescription encodeWithCoder:]
+ -[GCFAchievementDescription forwardingTargetForSelector:]
+ -[GCFAchievementDescription game]
+ -[GCFAchievementDescription hash]
+ -[GCFAchievementDescription imageNameForIcon]
+ -[GCFAchievementDescription image]
+ -[GCFAchievementDescription initWithCoder:]
+ -[GCFAchievementDescription initWithInternalRepresentation:]
+ -[GCFAchievementDescription init]
+ -[GCFAchievementDescription internal]
+ -[GCFAchievementDescription isEqual:]
+ -[GCFAchievementDescription methodSignatureForSelector:]
+ -[GCFAchievementDescription respondsToSelector:]
+ -[GCFAchievementDescription setImage:]
+ -[GCFAchievementDescription setInternal:]
+ -[GCFAchievementDescription setValue:forUndefinedKey:]
+ -[GCFAchievementDescription valueForUndefinedKey:]
+ -[GCFLocalizedAchievementDescription .cxx_destruct]
+ -[GCFLocalizedAchievementDescription _localizedStringFromKey:]
+ -[GCFLocalizedAchievementDescription achievedDescription]
+ -[GCFLocalizedAchievementDescription game]
+ -[GCFLocalizedAchievementDescription iconImageName]
+ -[GCFLocalizedAchievementDescription imageNameForIcon]
+ -[GCFLocalizedAchievementDescription setGame:]
+ -[GCFLocalizedAchievementDescription setIconImageName:]
+ -[GCFLocalizedAchievementDescription title]
+ -[GCFLocalizedAchievementDescription unachievedDescription]
+ -[GKAchievementChallenge gcfAchievement]
+ -[GKAchievementChallenge setGcfAchievement:]
+ OBJC_IVAR_$_GCFLocalizedAchievementDescription._game
+ OBJC_IVAR_$_GCFLocalizedAchievementDescription._iconImageName
+ _OBJC_CLASS_$_GCFAchievement
+ _OBJC_CLASS_$_GCFAchievementDescription
+ _OBJC_CLASS_$_GCFLocalizedAchievementDescription
+ _OBJC_IVAR_$_GCFAchievement._game
+ _OBJC_IVAR_$_GCFAchievement._internal
+ _OBJC_IVAR_$_GCFAchievement._player
+ _OBJC_IVAR_$_GCFAchievement._showsCompletionBanner
+ _OBJC_IVAR_$_GCFAchievementDescription._image
+ _OBJC_IVAR_$_GCFAchievementDescription._internal
+ _OBJC_IVAR_$_GKAchievementChallenge._gcfAchievement
+ _OBJC_IVAR_$_GKAchievementChallenge._publicAchievement
+ _OBJC_METACLASS_$_GCFAchievement
+ _OBJC_METACLASS_$_GCFAchievementDescription
+ _OBJC_METACLASS_$_GCFLocalizedAchievementDescription
+ __OBJC_$_CLASS_METHODS_GCFAchievement
+ __OBJC_$_CLASS_METHODS_GCFAchievementDescription
+ __OBJC_$_CLASS_PROP_LIST_GCFAchievement
+ __OBJC_$_CLASS_PROP_LIST_GCFAchievementDescription
+ __OBJC_$_INSTANCE_METHODS_GCFAchievement(GCFAchievementDescription)
+ __OBJC_$_INSTANCE_METHODS_GCFAchievementDescription
+ __OBJC_$_INSTANCE_METHODS_GCFLocalizedAchievementDescription
+ __OBJC_$_INSTANCE_VARIABLES_GCFAchievement
+ __OBJC_$_INSTANCE_VARIABLES_GCFAchievementDescription
+ __OBJC_$_INSTANCE_VARIABLES_GCFLocalizedAchievementDescription
+ __OBJC_$_PROP_LIST_GCFAchievement
+ __OBJC_$_PROP_LIST_GCFAchievementDescription
+ __OBJC_$_PROP_LIST_GCFLocalizedAchievementDescription
+ __OBJC_CLASS_PROTOCOLS_$_GCFAchievement
+ __OBJC_CLASS_PROTOCOLS_$_GCFAchievementDescription
+ __OBJC_CLASS_RO_$_GCFAchievement
+ __OBJC_CLASS_RO_$_GCFAchievementDescription
+ __OBJC_CLASS_RO_$_GCFLocalizedAchievementDescription
+ __OBJC_METACLASS_RO_$_GCFAchievement
+ __OBJC_METACLASS_RO_$_GCFAchievementDescription
+ __OBJC_METACLASS_RO_$_GCFLocalizedAchievementDescription
+ ___105+[GCFAchievement loadAchievementsForGameV2:player:includeUnreported:includeHidden:withCompletionHandler:]_block_invoke
+ ___106+[GCFAchievement loadAchievementsForGameV2:players:includeUnreported:includeHidden:withCompletionHandler:]_block_invoke
+ ___106+[GCFAchievement loadAchievementsForGameV2:players:includeUnreported:includeHidden:withCompletionHandler:]_block_invoke_2
+ ___106+[GCFAchievement loadAchievementsForGameV2:players:includeUnreported:includeHidden:withCompletionHandler:]_block_invoke_3
+ ___106+[GCFAchievement loadAchievementsForGameV2:players:includeUnreported:includeHidden:withCompletionHandler:]_block_invoke_4
+ ___106+[GCFAchievement loadAchievementsForGameV2:players:includeUnreported:includeHidden:withCompletionHandler:]_block_invoke_5
+ ___107+[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]_block_invoke
+ ___107+[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]_block_invoke_2
+ ___107+[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]_block_invoke_3
+ ___107+[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]_block_invoke_4
+ ___107+[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]_block_invoke_5
+ ___107+[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]_block_invoke_6
+ ___107+[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]_block_invoke_7
+ ___114+[GCFAchievement shouldShowBannerOnReport:achievementDescription:reportedAchievements:uiFrameworkMethodsRequired:]_block_invoke
+ ___39+[GCFAchievement showBannerIsSupported]_block_invoke
+ ___56+[GCFAchievement loadAchievementsWithCompletionHandler:]_block_invoke
+ ___57+[GCFAchievement resetAchievementsWithCompletionHandler:]_block_invoke
+ ___65+[GCFAchievement loadAchievementWithID:forGame:players:complete:]_block_invoke
+ ___65+[GCFAchievement loadAchievementWithID:forGame:players:complete:]_block_invoke_2
+ ___65+[GCFAchievement loadAchievementWithID:forGame:players:complete:]_block_invoke_3
+ ___70+[GCFAchievementDescription _loadLocalAchievementDescriptionsForGame:]_block_invoke
+ ___78+[GCFAchievementDescription loadAchievementDescriptionsWithCompletionHandler:]_block_invoke
+ ___86+[GCFAchievementDescription loadAchievementDescriptionsForGame:withCompletionHandler:]_block_invoke
+ ___86+[GCFAchievementDescription loadAchievementDescriptionsForGame:withCompletionHandler:]_block_invoke_2
+ ___block_descriptor_49_e8_32s40r_e31_v32?0"GCFAchievement"8Q16^B24ls32l8r40l8
- -[GKAchievementChallenge setAchievement:]
- _OBJC_IVAR_$_GKAchievementChallenge._achievement
CStrings:
+ "+[GCFAchievement loadAchievementWithID:forGame:players:complete:]"
+ "+[GCFAchievement loadAchievementsForGameV2:players:includeUnreported:includeHidden:withCompletionHandler:]"
+ "+[GCFAchievement reportAchievements:whileScreeningChallenges:withEligibleChallenges:withCompletionHandler:]"
+ "-[GCFAchievement initWithIdentifier:forPlayer:]"
+ "-[GCFAchievement playerID]"
+ "<GCFAchievement %p> has a nil or invalid internal player, will return a nil player"
+ "GCFAchievement.m"
+ "[%@]Not eligible for onboarding UI -- excluded bundle identifier."
+ "v32@?0@\"GCFAchievement\"8Q16^B24"
```
