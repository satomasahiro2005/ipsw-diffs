## FitnessCoachingServices

> `/System/Library/PrivateFrameworks/FitnessCoachingServices.framework/FitnessCoachingServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xba4c4` | `0xcde4c` | **`+0x13988`** |
| `__AUTH_CONST.__const` | `0x4ec8` | `0x69d0` | **`+0x1b08`** |
| `__TEXT.__eh_frame` | `0xb278` | `0xcab0` | **`+0x1838`** |
| `__TEXT.__unwind_info` | `0x3330` | `0x3e38` | **`+0xb08`** |
| `__TEXT.__const` | `0x5efc` | `0x681c` | **`+0x920`** |
| `__TEXT.__swift5_capture` | `0xf0c` | `0x1664` | **`+0x758`** |
| `__AUTH_CONST.__objc_const` | `0x5ba8` | `0x6018` | **`+0x470`** |
| `__TEXT.__cstring` | `0x39b1` | `0x3d51` | **`+0x3a0`** |
| `__TEXT.__swift_as_cont` | `0xb58` | `0xea0` | **`+0x348`** |
| `__AUTH.__data` | `0x28` | `0x300` | **`+0x2d8`** |
| `__TEXT.__constg_swiftt` | `0x254c` | `0x2794` | **`+0x248`** |
| `__TEXT.__swift5_reflstr` | `0x23c8` | `0x25d8` | **`+0x210`** |
| `__TEXT.__swift5_fieldmd` | `0x2094` | `0x2258` | **`+0x1c4`** |
| `__TEXT.__swift5_typeref` | `0x2443` | `0x25eb` | **`+0x1a8`** |
| `__TEXT.__swift_as_entry` | `0x430` | `0x544` | **`+0x114`** |
| `__TEXT.__swift_as_ret` | `0x5ac` | `0x6c0` | **`+0x114`** |
| `__AUTH_CONST.__auth_got` | `0x12f0` | `0x13e8` | **`+0xf8`** |
| `__TEXT.__oslogstring` | `0x34d4` | `0x35c4` | **`+0xf0`** |
| `__DATA_DIRTY.__data` | `0x29b0` | `0x2900` | **`-0xb0`** |
| `__DATA.__bss` | `0x2200` | `0x2280` | **`+0x80`** |
| `__DATA_CONST.__got` | `0xa58` | `0xac8` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x1f0` | `0x240` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x2e8` | `0x298` | **`-0x50`** |
| `__TEXT.__objc_methlist` | `0x544` | `0x594` | **`+0x50`** |
| `__DATA.__data` | `0x7d8` | `0x820` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x9a0` | `0x9e8` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x328` | `0x350` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0xd60` | `0xd80` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x140` | `0x158` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x25c` | `0x270` | **`+0x14`** |
| `__TEXT.__swift5_protos` | `0x138` | `0x148` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x1dc` | `0x1ec` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xc` | `0x10` | **`+0x4`** |

### Other Changes

```diff

-2027.0.13.0.0
+2027.1.14.0.0

+  - /System/Library/PrivateFrameworks/SeymourAssetCore.framework/SeymourAssetCore

+  - /usr/lib/swift/libswiftGLKit.dylib

+  - /usr/lib/swift/libswiftMetalKit.dylib
+  - /usr/lib/swift/libswiftModelIO.dylib

+  - /usr/lib/swift/libswiftSceneKit.dylib

-  Functions: 2764
-  Symbols:   1302
-  CStrings:  512
+  Functions: 3201
+  Symbols:   1353
+  CStrings:  523
Symbols:
+ -[FCSFitnessCoachingAchievementEvaluator .cxx_destruct]
+ -[FCSFitnessCoachingAchievementEvaluator _firstAchievementFromAchievements:passingMilestoneTest:completion:]
+ -[FCSFitnessCoachingAchievementEvaluator _firstAchievementMatchingLifetimeGoalsWithNames:amongstAchievements:experienceType:reachedMilestoneCompletion:]
+ -[FCSFitnessCoachingAchievementEvaluator dataSource]
+ -[FCSFitnessCoachingAchievementEvaluator evaluateYesterdayAchievements:isStandaloneMode:]
+ -[FCSFitnessCoachingAchievementEvaluator initWithDataSource:]
+ -[FCSFitnessCoachingAchievementEvaluator progressAchievementAndMilestoneWithCurrentDate:calendar:experienceType:isStandaloneMode:completion:]
+ -[FCSFitnessCoachingAchievementEvaluator progressAchievementAndMilestoneWithMonthlyChallengeAchievement:achievementsMap:currentDate:calendar:experienceType:isStandaloneMode:completion:]
+ -[FCSFitnessCoachingAchievementEvaluator progressLocalizationKeyForAchievement:progressMilestone:experienceType:]
+ -[FCSFitnessCoachingAchievementEvaluator progressLocalizationKeyPrefixForAchievement:progressMilestone:]
+ -[FCSFitnessCoachingAchievementEvaluator setDataSource:]
+ -[FCSFitnessCoachingAchievementEvaluator setLocalizationKeyOverride:]
+ -[FCSFitnessCoachingAchievementEvaluator todayLocalizationKeyForAchievement:experienceType:]
+ -[FCSFitnessCoachingAchievementEvaluator todayLocalizationKeyPrefixForAchievement:]
+ -[FCSFitnessCoachingAchievementEvaluator yesterdayLocalizationKeyForAchievement:experienceType:]
+ -[FCSFitnessCoachingAchievementEvaluator yesterdayLocalizationKeyPrefixForAchievement:]
+ _ACHFirstAndBestSupportedActivityTypes
+ _BestWorkoutDistanceTemplateForWorkoutActivityType
+ _BestWorkoutElevationGainedTemplateForWorkoutActivityType
+ _BestWorkoutEnergyBurnedTemplateForWorkoutActivityType
+ _FCSAchievementLocalizationBundle
+ _FCSAchievementProgressHalfway
+ _FCSAchievementProgressOneDayAway
+ _FCSAchievementProgressQuarterIn
+ _FCSAchievementProgressThreeDaysAway
+ _FCSAchievementProgressThreeQuartersIn
+ _FCSProgressAchievementLocalizationPrefixFormatString
+ _FCSTodayEarnedAchievementLocalizationPrefixFormatString
+ _FCSYesterdayEarnedAchievementLocalizationPrefixFormatString
+ _FirstWorkoutTemplateForWorkoutActivityType
+ _OBJC_CLASS_$_FCSFitnessCoachingAchievementEvaluator
+ _OBJC_CLASS_$__HKActivityStatisticsStandHourInfo
+ _OBJC_IVAR_$_FCSFitnessCoachingAchievementEvaluator._dataSource
+ _OBJC_IVAR_$_FCSFitnessCoachingAchievementEvaluator._progressLocalizationKeyOverride
+ _OBJC_IVAR_$_FCSFitnessCoachingAchievementEvaluator._todayLocalizationKeyOverride
+ _OBJC_IVAR_$_FCSFitnessCoachingAchievementEvaluator._yesterdayLocalizationKeyOverride
+ _OBJC_METACLASS_$_FCSFitnessCoachingAchievementEvaluator
+ __DATA__TtC23FitnessCoachingServices25FitnessCoachingRuleEngine
+ __DATA__TtC23FitnessCoachingServices25HealthAppDashboardService
+ __DATA__TtC23FitnessCoachingServices26HealthAppDashboardListener
+ __IVARS__TtC23FitnessCoachingServices25FitnessCoachingRuleEngine
+ __IVARS__TtC23FitnessCoachingServices25HealthAppDashboardService
+ __IVARS__TtC23FitnessCoachingServices26HealthAppDashboardListener
+ __METACLASS_DATA__TtC23FitnessCoachingServices25FitnessCoachingRuleEngine
+ __METACLASS_DATA__TtC23FitnessCoachingServices25HealthAppDashboardService
+ __METACLASS_DATA__TtC23FitnessCoachingServices26HealthAppDashboardListener
+ __OBJC_$_INSTANCE_METHODS_FCSFitnessCoachingAchievementEvaluator
+ __OBJC_$_INSTANCE_VARIABLES_FCSFitnessCoachingAchievementEvaluator
+ __OBJC_$_PROP_LIST_FCSFitnessCoachingAchievementEvaluator
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_FCSFitnessCoachingAchievementEvaluatorDataSource
+ __OBJC_$_PROTOCOL_METHOD_TYPES_FCSFitnessCoachingAchievementEvaluatorDataSource
+ __OBJC_$_PROTOCOL_REFS_FCSFitnessCoachingAchievementEvaluatorDataSource
+ __OBJC_CLASS_RO_$_FCSFitnessCoachingAchievementEvaluator
+ __OBJC_LABEL_PROTOCOL_$_FCSFitnessCoachingAchievementEvaluatorDataSource
+ __OBJC_METACLASS_RO_$_FCSFitnessCoachingAchievementEvaluator
+ __OBJC_PROTOCOL_$_FCSFitnessCoachingAchievementEvaluatorDataSource
+ ___141-[FCSFitnessCoachingAchievementEvaluator progressAchievementAndMilestoneWithCurrentDate:calendar:experienceType:isStandaloneMode:completion:]_block_invoke
+ ___141-[FCSFitnessCoachingAchievementEvaluator progressAchievementAndMilestoneWithCurrentDate:calendar:experienceType:isStandaloneMode:completion:]_block_invoke_2
+ ___152-[FCSFitnessCoachingAchievementEvaluator _firstAchievementMatchingLifetimeGoalsWithNames:amongstAchievements:experienceType:reachedMilestoneCompletion:]_block_invoke
+ ___152-[FCSFitnessCoachingAchievementEvaluator _firstAchievementMatchingLifetimeGoalsWithNames:amongstAchievements:experienceType:reachedMilestoneCompletion:]_block_invoke_2
+ ___185-[FCSFitnessCoachingAchievementEvaluator progressAchievementAndMilestoneWithMonthlyChallengeAchievement:achievementsMap:currentDate:calendar:experienceType:isStandaloneMode:completion:]_block_invoke
+ ___185-[FCSFitnessCoachingAchievementEvaluator progressAchievementAndMilestoneWithMonthlyChallengeAchievement:achievementsMap:currentDate:calendar:experienceType:isStandaloneMode:completion:]_block_invoke_2
+ ___185-[FCSFitnessCoachingAchievementEvaluator progressAchievementAndMilestoneWithMonthlyChallengeAchievement:achievementsMap:currentDate:calendar:experienceType:isStandaloneMode:completion:]_block_invoke_3
+ ___185-[FCSFitnessCoachingAchievementEvaluator progressAchievementAndMilestoneWithMonthlyChallengeAchievement:achievementsMap:currentDate:calendar:experienceType:isStandaloneMode:completion:]_block_invoke_4
+ ___185-[FCSFitnessCoachingAchievementEvaluator progressAchievementAndMilestoneWithMonthlyChallengeAchievement:achievementsMap:currentDate:calendar:experienceType:isStandaloneMode:completion:]_block_invoke_5
+ ___89-[FCSFitnessCoachingAchievementEvaluator evaluateYesterdayAchievements:isStandaloneMode:]_block_invoke
+ ___89-[FCSFitnessCoachingAchievementEvaluator evaluateYesterdayAchievements:isStandaloneMode:]_block_invoke_2
+ ___89-[FCSFitnessCoachingAchievementEvaluator evaluateYesterdayAchievements:isStandaloneMode:]_block_invoke_3
+ ___swift_closure_destructor.11Tm
+ ___swift_closure_destructor.14Tm
+ ___swift_closure_destructor.16Tm
+ ___swift_closure_destructor.34Tm
+ ___swift_exist.box.addr_destructor.7Tm
+ ___swift_memcpy2016_8
+ __swift_FORCE_LOAD_$_swiftGLKit
+ __swift_FORCE_LOAD_$_swiftGLKit_$_FitnessCoachingServices
+ __swift_FORCE_LOAD_$_swiftMetalKit
+ __swift_FORCE_LOAD_$_swiftMetalKit_$_FitnessCoachingServices
+ __swift_FORCE_LOAD_$_swiftModelIO
+ __swift_FORCE_LOAD_$_swiftModelIO_$_FitnessCoachingServices
+ __swift_FORCE_LOAD_$_swiftSceneKit
+ __swift_FORCE_LOAD_$_swiftSceneKit_$_FitnessCoachingServices
+ _objc_retainAutoreleaseReturnValue
+ _objc_retain_x10
+ _symbolic $s23FitnessCoachingServices0aB18RuleEngineProtocolP
+ _symbolic $s23FitnessCoachingServices0aB20AchievementProvidingP
+ _symbolic $s23FitnessCoachingServices27HealthAppDashboardListeningP
+ _symbolic $s23FitnessCoachingServices33HealthAppDashboardServiceProtocolP
+ _symbolic $s23FitnessCoachingServices40HealthAppDashboardServiceFactoryProtocolP
+ _symbolic SaySo34_HKActivityStatisticsStandHourInfoCG
+ _symbolic Say_____GSg______pIegHozo_ 15FitnessCoaching0aB11ContentTypeO s5ErrorP
+ _symbolic So11ACHTemplateCSg
+ _symbolic So17HKActivitySummaryCSg
+ _symbolic So17HKActivitySummaryCSg09yesterdayB0_AC05todayB0t
+ _symbolic So38FCSFitnessCoachingAchievementEvaluatorC
+ _symbolic _____ 15FitnessCoaching24HealthDashboardLocalizerC
+ _symbolic _____ 23FitnessCoachingServices0aB10RuleEngineC
+ _symbolic _____ 23FitnessCoachingServices0aB19AchievementProviderV
+ _symbolic _____ 23FitnessCoachingServices25HealthAppDashboardServiceC
+ _symbolic _____ 23FitnessCoachingServices26HealthAppDashboardListenerC
+ _symbolic _____ 23FitnessCoachingServices32HealthAppDashboardServiceFactoryV
+ _symbolic _____Sg 15FitnessCoaching0aB11ContentTypeO
+ _symbolic _____SgXw 23FitnessCoachingServices26HealthAppDashboardListenerC
+ _symbolic _____XDXMT 23FitnessCoachingServices25HealthAppDashboardServiceC
+ _symbolic ______p 15FitnessCoaching27StandHourStatisticsQueryingP
+ _symbolic ______p 23FitnessCoachingServices0aB18RuleEngineProtocolP
+ _symbolic ______p 23FitnessCoachingServices0aB20AchievementProvidingP
+ _symbolic ______p 23FitnessCoachingServices27HealthAppDashboardListeningP
+ _symbolic ______p 23FitnessCoachingServices40HealthAppDashboardServiceFactoryProtocolP
+ _symbolic _____ySay_____GSgyYaKcG s23_ContiguousArrayStorageC 15FitnessCoaching0dE11ContentTypeO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 15FitnessCoaching0dE11ContentTypeO
+ _symbolic yyc
+ _type_layout_string 23FitnessCoachingServices0aB19AchievementProviderV
+ _type_layout_string 23FitnessCoachingServices32HealthAppDashboardServiceFactoryV
- -[FCSFirstGlanceAchievementEvaluator .cxx_destruct]
- -[FCSFirstGlanceAchievementEvaluator _firstAchievementFromAchievements:passingMilestoneTest:completion:]
- -[FCSFirstGlanceAchievementEvaluator _firstAchievementMatchingLifetimeGoalsWithNames:amongstAchievements:experienceType:reachedMilestoneCompletion:]
- -[FCSFirstGlanceAchievementEvaluator dataSource]
- -[FCSFirstGlanceAchievementEvaluator evaluateYesterdayAchievements:isStandaloneMode:]
- -[FCSFirstGlanceAchievementEvaluator initWithDataSource:]
- -[FCSFirstGlanceAchievementEvaluator progressAchievementAndMilestoneWithCurrentDate:calendar:experienceType:isStandaloneMode:completion:]
- -[FCSFirstGlanceAchievementEvaluator progressAchievementAndMilestoneWithMonthlyChallengeAchievement:achievementsMap:currentDate:calendar:experienceType:isStandaloneMode:completion:]
- -[FCSFirstGlanceAchievementEvaluator progressLocalizationKeyForAchievement:progressMilestone:experienceType:]
- -[FCSFirstGlanceAchievementEvaluator setDataSource:]
- -[FCSFirstGlanceAchievementEvaluator setLocalizationKeyOverride:]
- -[FCSFirstGlanceAchievementEvaluator yesterdayLocalizationKeyForAchievement:experienceType:]
- _FCSFirstGlanceAchievementLocalizationBundle
- _FCSFirstGlanceAchievementProgressHalfway
- _FCSFirstGlanceAchievementProgressOneDayAway
- _FCSFirstGlanceAchievementProgressQuarterIn
- _FCSFirstGlanceAchievementProgressThreeDaysAway
- _FCSFirstGlanceAchievementProgressThreeQuartersIn
- _FCSFirstGlanceProgressAchievementLocalizationPrefixFormatString
- _FCSFirstGlanceYesterdayEarnedAchievementLocalizationPrefixFormatString
- _OBJC_CLASS_$_FCSFirstGlanceAchievementEvaluator
- _OBJC_IVAR_$_FCSFirstGlanceAchievementEvaluator._dataSource
- _OBJC_IVAR_$_FCSFirstGlanceAchievementEvaluator._progressLocalizationKeyOverride
- _OBJC_IVAR_$_FCSFirstGlanceAchievementEvaluator._yesterdayLocalizationKeyOverride
- _OBJC_METACLASS_$_FCSFirstGlanceAchievementEvaluator
- __OBJC_$_INSTANCE_METHODS_FCSFirstGlanceAchievementEvaluator
- __OBJC_$_INSTANCE_VARIABLES_FCSFirstGlanceAchievementEvaluator
- __OBJC_$_PROP_LIST_FCSFirstGlanceAchievementEvaluator
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_FCSFirstGlanceAchievementEvaluatorDataSource
- __OBJC_$_PROTOCOL_METHOD_TYPES_FCSFirstGlanceAchievementEvaluatorDataSource
- __OBJC_$_PROTOCOL_REFS_FCSFirstGlanceAchievementEvaluatorDataSource
- __OBJC_CLASS_RO_$_FCSFirstGlanceAchievementEvaluator
- __OBJC_LABEL_PROTOCOL_$_FCSFirstGlanceAchievementEvaluatorDataSource
- __OBJC_METACLASS_RO_$_FCSFirstGlanceAchievementEvaluator
- __OBJC_PROTOCOL_$_FCSFirstGlanceAchievementEvaluatorDataSource
- ___137-[FCSFirstGlanceAchievementEvaluator progressAchievementAndMilestoneWithCurrentDate:calendar:experienceType:isStandaloneMode:completion:]_block_invoke
- ___137-[FCSFirstGlanceAchievementEvaluator progressAchievementAndMilestoneWithCurrentDate:calendar:experienceType:isStandaloneMode:completion:]_block_invoke_2
- ___148-[FCSFirstGlanceAchievementEvaluator _firstAchievementMatchingLifetimeGoalsWithNames:amongstAchievements:experienceType:reachedMilestoneCompletion:]_block_invoke
- ___148-[FCSFirstGlanceAchievementEvaluator _firstAchievementMatchingLifetimeGoalsWithNames:amongstAchievements:experienceType:reachedMilestoneCompletion:]_block_invoke_2
- ___181-[FCSFirstGlanceAchievementEvaluator progressAchievementAndMilestoneWithMonthlyChallengeAchievement:achievementsMap:currentDate:calendar:experienceType:isStandaloneMode:completion:]_block_invoke
- ___181-[FCSFirstGlanceAchievementEvaluator progressAchievementAndMilestoneWithMonthlyChallengeAchievement:achievementsMap:currentDate:calendar:experienceType:isStandaloneMode:completion:]_block_invoke_2
- ___181-[FCSFirstGlanceAchievementEvaluator progressAchievementAndMilestoneWithMonthlyChallengeAchievement:achievementsMap:currentDate:calendar:experienceType:isStandaloneMode:completion:]_block_invoke_3
- ___181-[FCSFirstGlanceAchievementEvaluator progressAchievementAndMilestoneWithMonthlyChallengeAchievement:achievementsMap:currentDate:calendar:experienceType:isStandaloneMode:completion:]_block_invoke_4
- ___181-[FCSFirstGlanceAchievementEvaluator progressAchievementAndMilestoneWithMonthlyChallengeAchievement:achievementsMap:currentDate:calendar:experienceType:isStandaloneMode:completion:]_block_invoke_5
- ___85-[FCSFirstGlanceAchievementEvaluator evaluateYesterdayAchievements:isStandaloneMode:]_block_invoke
- ___85-[FCSFirstGlanceAchievementEvaluator evaluateYesterdayAchievements:isStandaloneMode:]_block_invoke_2
- ___85-[FCSFirstGlanceAchievementEvaluator evaluateYesterdayAchievements:isStandaloneMode:]_block_invoke_3
- ___swift_closure_destructor.12Tm
- ___swift_closure_destructor.23Tm
- ___swift_closure_destructor.26Tm
- ___swift_closure_destructor.29Tm
- ___swift_memcpy1936_8
- _symbolic $s23FitnessCoachingServices31FirstGlanceAchievementProvidingP
- _symbolic Say_____GSg______pIegHozo_ 15FitnessCoaching15FirstGlanceTypeO s5ErrorP
- _symbolic So17HKActivitySummaryCSg09yesterdayB0_t
- _symbolic So34FCSFirstGlanceAchievementEvaluatorC
- _symbolic _____ 23FitnessCoachingServices30FirstGlanceAchievementProviderV
- _symbolic _____Sg 15FitnessCoaching15FirstGlanceTypeO
- _symbolic ______p 23FitnessCoachingServices28LegacyWeeklySummaryProvidingP
- _symbolic ______p 23FitnessCoachingServices31FirstGlanceAchievementProvidingP
- _symbolic _____ySay_____GSgyYaKcG s23_ContiguousArrayStorageC 15FitnessCoaching15FirstGlanceTypeO
- _symbolic _____y_____G s23_ContiguousArrayStorageC 15FitnessCoaching15FirstGlanceTypeO
- _type_layout_string 23FitnessCoachingServices30FirstGlanceAchievementProviderV
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/FitnessCoaching/FitnessCoachingServices/FirstGlance/FitnessCoachingRuleEngine.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/FitnessCoaching/FitnessCoachingServices/HealthAppDashboard/HealthAppDashboardListener.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/FitnessCoaching/FitnessCoachingServices/HealthAppDashboard/HealthAppDashboardService.swift"
+ "1"
+ "ACHIEVEMENT_ACHIEVED_ALERT_DESCRIPTION"
+ "Built health app dashboard content: %s"
+ "Typical day stand hour infos requested before activation"
+ "TypicalDay model unavailable: %s"
+ "Unable to resolve studio workout artwork: %@"
+ "Unknown dayPhase: %s"
+ "buildHealthAppDashboardContent(dayPhase:)"
+ "requestDashboardContent(dayPhase:)"
+ "ringStatusRule(ring:)"
+ "ringsAheadRule()"
+ "yesterdayClosedOneRingRule()"
- "!"
- "modifiedDefaultType()"
- "simplifiedDefaultType()"
- "yesterdayClosedOneRing()"
```
