## FeatureFlagsSupport

> `/System/Library/PrivateFrameworks/FeatureFlagsSupport.framework/FeatureFlagsSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__unwind_info` | `0x2e8` | `0x2e0` | **`-0x8`** |

### Other Changes

```text
Functions:
~ -[FFConfiguration makeFeatureDictionaryFrom:forDomain:atDomainLevel:reportableFilename:] : 1176 -> 1172
~ -[FFConfiguration effectiveStateForFeature:domain:levelIndex:] : 376 -> 400
~ -[FFConfiguration initPrivate] : 352 -> 348
~ -[FFConfiguration clearCachedData] : 176 -> 184
~ -[FFConfiguration loadAllData] : 844 -> 832
~ -[FFConfiguration loadFeatureSetDefinitions] : 552 -> 548
~ -[FFConfiguration loadCombinedDataForLevelIndex:] : 1424 -> 1416
~ -[FFConfiguration loadFeatureSetDataForLevelIndex:] : 996 -> 992
~ -[FFConfiguration resolvedStateForDisclosure:] : 120 -> 132
~ -[FFConfiguration recalculateFeatureSetEffectsAt:] : 556 -> 552
~ -[FFConfiguration recalculateSubscriptionEffectsAt:] : 684 -> 680
~ -[FFConfiguration loadFeatureSetDefinitionsNamed:fromURL:] : 1432 -> 1424
~ -[FFConfiguration parseSubscriptionsDictionary:] : 384 -> 380
~ -[FFConfiguration isFeatureHidden:domain:] : 256 -> 280
~ -[FFConfiguration setFeaturesMatchingAttribute:levelIndex:value:] : 712 -> 708
~ -[FFConfiguration populateDictionary:withFeatures:] : 536 -> 532
~ -[FFConfiguration writeCombinedUpdatesAtLevelIndex:error:] : 556 -> 552
~ -[FFConfiguration writeDisclosureUpdatesAtlevelIndex:error:] : 492 -> 488
~ -[FFConfiguration writeFeatureSetUpdatesAtLevelIndex:withError:] : 832 -> 828
~ -[FFConfiguration writeSubscriptionUpdatesAtLevelIndex:withError:] : 676 -> 672
~ -[FFConfiguration featuresForDomainAlreadyLocked:] : 512 -> 504
~ -[FFConfiguration resetDomain:error:] : 492 -> 484
~ -[FFConfiguration sortValueForPhase:] : 112 -> 124
~ -[FFConfiguration(Disclosure) disclosureForFeature:domain:] : 320 -> 344
~ -[FFConfiguration(ProfileManagement) prepareToAddProfilePayloads] : 572 -> 568
~ _FFConfigurationValidateProfilePayload : 3252 -> 3276
~ -[FFConfiguration(ProfileManagement) commitProfilePayloadsAndReturnError:] : 2660 -> 2644
~ -[FFConfiguration(FeatureSets) featureFlagsInSet:inGroup:] : 588 -> 584
~ -[FFConfiguration(Subscriptions) removeSubscription:atLevel:] : 232 -> 228
~ -[FFConfiguration(Subscriptions) allSubscriptionsAtLevel:] : 168 -> 164
```
