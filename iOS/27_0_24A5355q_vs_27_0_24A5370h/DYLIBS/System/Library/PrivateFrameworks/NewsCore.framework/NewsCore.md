## NewsCore

> `/System/Library/PrivateFrameworks/NewsCore.framework/NewsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4102a0` | `0x412f6c` | **`+0x2ccc`** |
| `__TEXT.__eh_frame` | `0xa65c` | `0xabe4` | **`+0x588`** |
| `__TEXT.__oslogstring` | `0x181e5` | `0x18520` | **`+0x33b`** |
| `__TEXT.__unwind_info` | `0xeec0` | `0xf008` | **`+0x148`** |
| `__AUTH.__objc_data` | `0x37d0` | `0x3880` | **`+0xb0`** |
| `__TEXT.__const` | `0xe268` | `0xe318` | **`+0xb0`** |
| `__DATA.__bss` | `0xc810` | `0xc890` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x11918` | `0x11998` | **`+0x80`** |
| `__TEXT.__cstring` | `0x554fa` | `0x5556b` | **`+0x71`** |
| `__DATA_DIRTY.__bss` | `0x9720` | `0x96b0` | **`-0x70`** |
| `__TEXT.__objc_methlist` | `0x34cac` | `0x34d14` | **`+0x68`** |
| `__TEXT.__swift5_capture` | `0xe3c` | `0xea0` | **`+0x64`** |
| `__TEXT.__swift_as_cont` | `0x5ec` | `0x640` | **`+0x54`** |
| `__TEXT.__swift5_typeref` | `0x4226` | `0x4276` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x2028` | `0x2068` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x31c20` | `0x31c60` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x149c8` | `0x14a08` | **`+0x40`** |
| `__DATA_DIRTY.__objc_data` | `0xe8f0` | `0xe8b0` | **`-0x40`** |
| `__TEXT.__swift5_reflstr` | `0x2360` | `0x2320` | **`-0x40`** |
| `__AUTH_CONST.__const` | `0xd400` | `0xd3d0` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x2c08` | `0x2c38` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x31b0` | `0x3180` | **`-0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x2ee0` | `0x2eb4` | **`-0x2c`** |
| `__TEXT.__swift_as_entry` | `0x334` | `0x35c` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x3a4` | `0x3cc` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x79570` | `0x79588` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x31c8` | `0x31dc` | **`+0x14`** |
| `__TEXT.__gcc_except_tab` | `0x49a8` | `0x49bc` | **`+0x14`** |
| `__AUTH.__data` | `0x460` | `0x470` | **`+0x10`** |
| `__DATA.__data` | `0x6510` | `0x6520` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x458c` | `0x4594` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1cb8` | `0x1cc0` | **`+0x8`** |

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0

-  Functions: 24784
-  Symbols:   37654
-  CStrings:  10506
+  Functions: 24833
+  Symbols:   37679
+  CStrings:  10518
Symbols:
+ -[FCNewsAppConfig offlineModeOfflineVerificationTimeoutInterval]
+ -[FCNewsAppConfig sportsEventLiveActivityStartTimeThreshold]
+ -[FCNewsAppConfig sportsEventOpenInTVStartTimeThreshold]
+ -[FCNewsPersonalizationTrainingFeatureFlags excludeInaccessibleArticlesFromPublisherGroupEngagement]
+ -[FCNewsPersonalizationTrainingFeatureFlags setExcludeInaccessibleArticlesFromPublisherGroupEngagement:]
+ -[FCPersonalizationScoringConfig initWithAnfMultiplier:articleLengthAggregateWeight:articleReadPenalty:articleListenedPenalty:audioMultiplierForFreeUsers:audioMultiplierForTrialUsers:audioMultiplierForPaidUsers:autofavoritedVoteCoefficient:baselineRatePrior:bundleFreeMultiplierForFreeUsers:bundleFreeMultiplierForTrialUsers:bundleFreeMultiplierForPaidUsers:bundlePaidMultiplierForFreeUsers:bundlePaidMultiplierForTrialUsers:bundlePaidMultiplierForPaidUsers:conversionCoefficientForFreeUsers:conversionCoefficientForTrialUsers:conversionCoefficientForPaidUsers:conversionCohort:ctrWithOneAutofavorited:ctrWithOneSubscribed:ctrWithSubscribedChannel:ctrWithThreeAutofavorited:ctrWithThreeSubscribed:ctrWithTwoAutofavorited:ctrWithTwoSubscribed:ctrWithZeroAutofavorited:ctrWithZeroSubscribed:decayFactor:featuredMultiplierForFreeUsers:featuredMultiplierForTrialUsers:featuredMultiplierForPaidUsers:evergreenMultiplierForFreeUsers:evergreenMultiplierForTrialUsers:evergreenMultiplierForPaidUsers:globalScoreCoefficientFree:globalScoreCoefficientPaid:globalScoreCoefficientHalfLife:globalScoreCoefficientInitialMultiplier:globalScoreDemocratizationFactor:conversionScoreDemocratizationFactor:headlineSeenPenalty:halfLifeCoefficient:userFeedbackHalfLifeCoefficient:evergreenHalfLifeCoefficient:respectHalfLifeOverride:publisherAggregateWeight:sparseTagsPenalty:subscribedChannelScoreCoefficient:subscribedTopicsScoreCoefficient:userCohort:lowFlowBoostFetchCountWeight:lowFlowBoostFetchEstimationConfig:lowFlowBoostEventEstimationConfig:nicheContentManagedTopicBoostAllTags:nicheContentDefaultFlowRate:nicheContentDefaultSubscriptionRate:nicheContentExcludeNonGroupableTopics:nicheContentShouldBoostPublisher:nicheContentTopicFlowExponent:nicheContentPublisherFlowExponent:nicheContentManagedTopicBoost:nicheContentServerFlowWeight:nicheContentTopicSubscriptionExponent:nicheContentPublisherSubscriptionExponent:nicheContentQualityThreshold:contentTriggerMaxEventCount:contentTriggerScoreExponent:contentTriggerTagWeightExponent:contentTriggerMinScoreWeight:contentTriggerMaxDampener:contentTriggerDampenerCoefficient:personalizedMultiplierBaselineMembership:personalizedMultiplierPreBaselineCurvature:personalizedMultiplierPostBaselineCurvature:personalizedMultiplierMembershipDampener:recentlyFollowedDurationThreshold:recentlyFollowedMultiplier:tabiScoreCoefficient:clientSideEngagementBoostFeaturedArticleMultiplier:clientSideEngagementBoostFeatureCandidateArticleMultiplier:clientSideEngagementBoostFreeCohortCTRCap:clientSideEngagementBoostPaidCohortCTRCap:clientSideEngagementBoostTagQualityMultiplier:clientSideEngagementBoostReduceVisibilityMultiplier:clientSideEngagementBoostANFMutiplier:dampenerEnabled:multiplierEnabled:peopleAlsoReadBaselineScore:peopleAlsoReadConditionalScoreCoefficient:peopleAlsoReadScoreCoefficient:recipeSeenPenalty:recipeViewedPenalty:]
+ -[FCTag _inflateSportsDataFromJSONDictionary:]
+ -[FCTagMetadata sportsData]
+ -[FCTelemetryBasedOfflineNetworkTransitionOperation setVerificationInProgress:]
+ -[FCTelemetryBasedOfflineNetworkTransitionOperation setVerificationTimeoutInterval:]
+ -[FCTelemetryBasedOfflineNetworkTransitionOperation verificationInProgress]
+ -[FCTelemetryBasedOfflineNetworkTransitionOperation verificationTimeoutInterval]
+ _FCBackgroundAppRefreshTaskIdentifier
+ _FCCKWidgetSectionConfigSectionFilterBriefingArticlesKey
+ _FCCKWidgetSectionConfigSectionFilterExpiredArticlesKey
+ _FCCKWidgetSectionConfigSectionFilterRecipeArticlesKey
+ _FCCKWidgetSectionConfigSectionFilterReduceVisibilityForNonFollowersKey
+ _FCNewsInternalExtrasBundle
+ _OBJC_CLASS_$_FCNetworkProbe
+ _OBJC_IVAR_$_FCNewsPersonalizationTrainingFeatureFlags._excludeInaccessibleArticlesFromPublisherGroupEngagement
+ _OBJC_IVAR_$_FCTelemetryBasedOfflineNetworkTransitionOperation._verificationInProgress
+ _OBJC_IVAR_$_FCTelemetryBasedOfflineNetworkTransitionOperation._verificationTimeoutInterval
+ _OBJC_METACLASS_$_FCNetworkProbe
+ __CLASS_METHODS_FCNetworkProbe
+ __DASLaunchReasonBackgroundRefresh
+ __DATA_FCNetworkProbe
+ __INSTANCE_METHODS_FCNetworkProbe
+ __METACLASS_DATA_FCNetworkProbe
+ __ZNSt3__110unique_ptrINS_11__hash_nodeINS_17__hash_value_typeI26NTPBKeyValuePair_ValueTypeU8__strongPU32objcproto21FCKeyValueStoreCoding10objc_classEEPvEENS_22__hash_node_destructorINS_9allocatorIS9_EEEEED1B9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ ___50-[FCURLRequestScheduler _resumeURLTaskForRequest:]_block_invoke
+ ___FCNewsInternalExtrasBundle_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e33_v32?0"NTPBArticleTopic"8Q16^B24ls32l8s40l8
+ ___block_descriptor_73_e8_32bs40r48r56r64r_e37_v16?0"FCBundleSubscriptionManager"8lr40l8r48l8r56l8r64l8s32l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72s_e17_v16?0"NSError"8ls32l8s40l8s48l8s56l8s64l8s72l8
+ ___block_descriptor_81_e8_32bs40r48r56r64r72w_e5_v8?0lw72l8r40l8r48l8r56l8r64l8s32l8
+ _associated conformance 8NewsCore12NetworkProbeC6ErrorsOSHAASQ
+ _kFCNewsPersonalizationFeatureFlagsExcludeInaccessibleArticlesFromPublisherGroupEngagementKey
+ _swift_retain_x10
+ _symbolic ScSy_____G 7Network12NWConnectionC5StateO
+ _symbolic _____ 7Network12NWConnectionC
+ _symbolic _____ 8NewsCore12NetworkProbeC
+ _symbolic _____ 8NewsCore12NetworkProbeC6ErrorsO
+ _symbolic _____Sg 7Network12NWConnectionC5StateO
+ _symbolic _____XMT 8NewsCore12NetworkProbeC
+ _symbolic ______pSgIegg_ s5ErrorP
+ _symbolic _____yScTyyt_____GSgG 2os21OSAllocatedUnfairLockV s5NeverO
+ _symbolic _____yScTyyt_____GSg_____G s13ManagedBufferCsRi__rlE s5NeverO So16os_unfair_lock_sV
+ _symbolic _____y______G ScS12ContinuationV 7Network12NWConnectionC5StateO
+ _symbolic _____y______G ScS8IteratorV 7Network12NWConnectionC5StateO
+ _symbolic _____y_______G ScS12ContinuationV11YieldResultO 7Network12NWConnectionC5StateO
+ _symbolic _____y_______G ScS12ContinuationV15BufferingPolicyO 7Network12NWConnectionC5StateO
- -[FCNewsAppConfig articleEmbeddingsScoringEnabled]
- -[FCPersonalizationScoringConfig initWithAnfMultiplier:articleLengthAggregateWeight:articleReadPenalty:articleListenedPenalty:audioMultiplierForFreeUsers:audioMultiplierForTrialUsers:audioMultiplierForPaidUsers:autofavoritedVoteCoefficient:baselineRatePrior:bundleFreeMultiplierForFreeUsers:bundleFreeMultiplierForTrialUsers:bundleFreeMultiplierForPaidUsers:bundlePaidMultiplierForFreeUsers:bundlePaidMultiplierForTrialUsers:bundlePaidMultiplierForPaidUsers:conversionCoefficientForFreeUsers:conversionCoefficientForTrialUsers:conversionCoefficientForPaidUsers:conversionCohort:ctrWithOneAutofavorited:ctrWithOneSubscribed:ctrWithSubscribedChannel:ctrWithThreeAutofavorited:ctrWithThreeSubscribed:ctrWithTwoAutofavorited:ctrWithTwoSubscribed:ctrWithZeroAutofavorited:ctrWithZeroSubscribed:decayFactor:featuredMultiplierForFreeUsers:featuredMultiplierForTrialUsers:featuredMultiplierForPaidUsers:evergreenMultiplierForFreeUsers:evergreenMultiplierForTrialUsers:evergreenMultiplierForPaidUsers:globalScoreCoefficientFree:globalScoreCoefficientPaid:globalScoreCoefficientHalfLife:globalScoreCoefficientInitialMultiplier:globalScoreDemocratizationFactor:conversionScoreDemocratizationFactor:headlineSeenPenalty:halfLifeCoefficient:userFeedbackHalfLifeCoefficient:evergreenHalfLifeCoefficient:respectHalfLifeOverride:mutedVoteCoefficient:publisherAggregateWeight:sparseTagsPenalty:subscribedChannelScoreCoefficient:subscribedTopicsScoreCoefficient:userCohort:lowFlowBoostFetchCountWeight:lowFlowBoostFetchEstimationConfig:lowFlowBoostEventEstimationConfig:nicheContentManagedTopicBoostAllTags:nicheContentDefaultFlowRate:nicheContentDefaultSubscriptionRate:nicheContentExcludeNonGroupableTopics:nicheContentShouldBoostPublisher:nicheContentTopicFlowExponent:nicheContentPublisherFlowExponent:nicheContentManagedTopicBoost:nicheContentServerFlowWeight:nicheContentTopicSubscriptionExponent:nicheContentPublisherSubscriptionExponent:nicheContentQualityThreshold:contentTriggerMaxEventCount:contentTriggerScoreExponent:contentTriggerTagWeightExponent:contentTriggerMinScoreWeight:contentTriggerMaxDampener:contentTriggerDampenerCoefficient:personalizedMultiplierBaselineMembership:personalizedMultiplierPreBaselineCurvature:personalizedMultiplierPostBaselineCurvature:personalizedMultiplierMembershipDampener:recentlyFollowedDurationThreshold:recentlyFollowedMultiplier:tabiScoreCoefficient:clientSideEngagementBoostFeaturedArticleMultiplier:clientSideEngagementBoostFeatureCandidateArticleMultiplier:clientSideEngagementBoostFreeCohortCTRCap:clientSideEngagementBoostPaidCohortCTRCap:clientSideEngagementBoostTagQualityMultiplier:clientSideEngagementBoostReduceVisibilityMultiplier:clientSideEngagementBoostANFMutiplier:dampenerEnabled:multiplierEnabled:peopleAlsoReadBaselineScore:peopleAlsoReadConditionalScoreCoefficient:peopleAlsoReadScoreCoefficient:recipeSeenPenalty:recipeViewedPenalty:]
- -[FCPersonalizationScoringConfig mutedVoteCoefficient]
- -[FCPersonalizationScoringConfig setMutedVoteCoefficient:]
- -[FCTagMetadata sportsFullName]
- -[FCTagMetadata sportsLeagueType]
- -[FCTagMetadata sportsPrimaryName]
- -[FCTagMetadata sportsSecondaryName]
- -[FCTagMetadata sportsSecondaryShortName]
- _FCOfflineModePingHostName
- _OBJC_CLASS_$_OS_os_log
- _OBJC_IVAR_$_FCPersonalizationScoringConfig._mutedVoteCoefficient
- __DASLaunchReasonBackgroundFetch
- __ZNSt3__110unique_ptrINS_11__hash_nodeINS_17__hash_value_typeI26NTPBKeyValuePair_ValueTypeU8__strongPU32objcproto21FCKeyValueStoreCoding10objc_classEEPvEENS_22__hash_node_destructorINS_9allocatorIS9_EEEEED1B9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- ___block_descriptor_81_e8_32s40bs48r56r64r72r_e37_v16?0"FCBundleSubscriptionManager"8lr48l8s32l8r56l8r64l8r72l8s40l8
- ___block_descriptor_89_e8_32s40bs48r56r64r72r80w_e5_v8?0lw80l8r48l8s32l8r56l8r64l8r72l8s40l8
- ___swift_closure_destructor.35Tm
- _associated conformance 8NewsCore41PingBasedOnlineNetworkTransitionOperationC6ErrorsOSHAASQ
- _symbolic So6FCOnceC
- _symbolic _____ 7Network7NWErrorO
- _symbolic _____ 8NewsCore41PingBasedOnlineNetworkTransitionOperationC6ErrorsO
- _symbolic _____ s6UInt16V
- _symbolic _____Sg 7Network12NWConnectionC
- _symbolic _____y_____G 15Synchronization5_CellVAARi_zrlE So16os_unfair_lock_sV
- _symbolic _____y_____SgG 2os21OSAllocatedUnfairLockV 7Network12NWConnectionC
- _symbolic _____y_____Sg_____G s13ManagedBufferCsRi__rlE 7Network12NWConnectionC So16os_unfair_lock_sV
CStrings:
+ "%@ cancelled"
+ "%@ encountered unknown default"
+ "%@ failed with %@"
+ "%@ preparing"
+ "%@ ready"
+ "%@ timed out"
+ "%@ waiting with %@"
+ "%@ was set up"
+ "; excludeInaccessibleArticlesFromPublisherGroupEngagement: %d"
+ "NTPBArticleTopic with nil tagID encountered during cohort enumeration; older clients crash on this shape (rdar://177742140). itemID=%{public}@"
+ "NetworkProbe should not be instantiated"
+ "NewsCore/NetworkProbe.swift"
+ "NewsInternalExtras"
+ "com.apple.news.appRefresh"
+ "disregarding error, since offline verification is already in progress"
+ "excludeInaccessibleArticlesFromPublisherGroupEngagement"
+ "filter_briefing_articles"
+ "filter_expired_articles"
+ "filter_recipe_articles"
+ "filter_reduce_visibility_for_non_followers"
+ "not transitioning offline because a successful network event occurred during verification"
+ "offline verification failed, transitioning to active offline after event with error %{public}@, starting at %{public}@ relative to last activation date of %{public}@, last background date of %{public}@, and last success date of %{public}@"
+ "offline verification resulted in a successful ping, staying online"
+ "offlineModeOfflineVerificationTimeoutInterval"
+ "sportsEventLiveActivityStartTimeThreshold"
+ "sportsEventOpenInTVStartTimeThreshold"
+ "verifying offline before transitioning, after event with error %{public}@, starting at %{public}@ relative to last activation date of %{public}@, last background date of %{public}@, and last success date of %{public}@"
- "articleEmbeddingsScoringEnabled"
- "mutedVoteCoefficient"
- "news.features.articleEmbeddingsScoring"
- "pinger for %@, attempt %d cancelled"
- "pinger for %@, attempt %d encountered unknown default"
- "pinger for %@, attempt %d failed with %@"
- "pinger for %@, attempt %d preparing"
- "pinger for %@, attempt %d ready"
- "pinger for %@, attempt %d waiting with %@"
- "pinger for %@, attempt %d was set up"
- "schedulePluralizedDisplayName"
- "sportsFullName"
- "sportsLeagueType"
- "sportsPrimaryName"
- "sportsSecondaryName"
```
