## AppPredictionClient

> `/System/Library/PrivateFrameworks/AppPredictionClient.framework/AppPredictionClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18d2f0` | `0x190d8c` | **`+0x3a9c`** |
| `__TEXT.__cstring` | `0x1c4ba` | `0x1c96f` | **`+0x4b5`** |
| `__TEXT.__oslogstring` | `0x17c32` | `0x180dc` | **`+0x4aa`** |
| `__TEXT.__objc_methlist` | `0x18f7c` | `0x190bc` | **`+0x140`** |
| `__DATA_CONST.__objc_selrefs` | `0xa120` | `0xa200` | **`+0xe0`** |
| `__AUTH_CONST.__objc_const` | `0x461d8` | `0x462b0` | **`+0xd8`** |
| `__AUTH_CONST.__cfstring` | `0x155c0` | `0x15680` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x2b00` | `0x2ba0` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x63f0` | `0x6490` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x6908` | `0x6998` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0x2038` | `0x20ac` | **`+0x74`** |
| `__DATA.__bss` | `0x418` | `0x448` | **`+0x30`** |
| `__AUTH_CONST.__objc_dictobj` | `0x168` | `0x190` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0xb28` | `0xb48` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1718` | `0x1730` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1ca4` | `0x1cb8` | **`+0x14`** |

### Other Changes

```diff

-675.0.2.0.0
+677.0.2.0.0

-  Functions: 10928
-  Symbols:   16833
-  CStrings:  4841
+  Functions: 10981
+  Symbols:   16896
+  CStrings:  4876
Symbols:
+ +[ATXDefaultHomeScreenItemManager _widgetIdentifiersNotAllowedForClient:]
+ +[ATXDefaultHomeScreenItemManager _widgetIdentifiersNotAllowedOnTvOS]
+ +[ATXDefaultHomeScreenItemProducerUtilities remoteWidgetsFromPairedDeviceRanking:size:personalityToDescriptorDictionary:]
+ +[ATXDefaultHomeScreenItemProducerUtilities widgetsByInterleavingWidgets:withWidgets:limit:usedPersonalities:usedAppBundleIds:]
+ -[ATXDefaultHomeScreenItemManager _pairedDeviceRankedWidgetsForClientIdentity:]
+ -[ATXDefaultHomeScreenItemManagerTransfer _deviceIdentifierForRelationshipIdentifier:]
+ -[ATXDefaultHomeScreenItemManagerTransfer _fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]
+ -[ATXDefaultHomeScreenItemManagerTransfer _hasPairedDeviceImportForVariant:]
+ -[ATXDefaultHomeScreenItemManagerTransfer _pairedDevicePathForVariant:sourceDeviceIdentifier:]
+ -[ATXDefaultHomeScreenItemManagerTransfer importedWidgetSmartStacksByPathForVariant:]
+ -[ATXDefaultHomeScreenItemManagerTransfer pairedDeviceWidgetSmartStackForVariant:relationshipIdentifier:maximumAge:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _blendedStacksForSize:requiredWidgetPersonalitiesPerStack:rankedWidgets:usedWidgetPersonalities:maxNumberOfWidgetsPerStack:denyListOfExtensions:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _generatedStacksWithRequest:includeRequiredWidgets:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _pairedDeviceRemoteWidgetsForSize:denyListOfExtensions:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _stacksByFillingWithPairedDeviceThirdPartyWidgets:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _tvOSRequiredWidgetsKeyForOnboarding:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer pairedDeviceRankedWidgets]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer setPairedDeviceRankedWidgets:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer usageRankedStacksWithRequest:]
+ -[ATXDefaultHomeScreenItemProducer _onboardingStacksProducerForSmartStackRequest:]
+ -[ATXDefaultHomeScreenItemProducer pairedDeviceRankedWidgets]
+ -[ATXDefaultHomeScreenItemProducer setPairedDeviceRankedWidgets:]
+ -[ATXDefaultHomeScreenItemProducer usageRankedStacksWithRequest:]
+ -[ATXDefaultWidgetSuggesterClient fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]
+ -[ATXWidgetSmartStackResponse setSourceDeviceIdentifier:]
+ -[ATXWidgetSmartStackResponse sourceDeviceIdentifier]
+ _ATXCanonicalContainerBundleIdForWidgetDedup
+ _ATXCanonicalContainerBundleIdForWidgetDedup.aliases
+ _ATXCanonicalContainerBundleIdForWidgetDedup.onceToken
+ _OBJC_CLASS_$_CHSRemoteDeviceService
+ _OBJC_CLASS_$_NSOrderedSet
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemManagerTransfer._pairedDevicePathPrefix
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemManagerTransfer._widgetSuggesterClient
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemOnboardingStacksProducer._pairedDeviceRankedWidgets
+ _OBJC_IVAR_$_ATXDefaultHomeScreenItemProducer._pairedDeviceRankedWidgets
+ _OBJC_IVAR_$_ATXWidgetSmartStackResponse._sourceDeviceIdentifier
+ ___103-[ATXDefaultHomeScreenItemOnboardingStacksProducer _generatedStacksWithRequest:includeRequiredWidgets:]_block_invoke
+ ___105-[ATXDefaultWidgetSuggesterClient fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]_block_invoke
+ ___107-[ATXDefaultHomeScreenItemOnboardingStacksProducer _pairedDeviceRemoteWidgetsForSize:denyListOfExtensions:]_block_invoke
+ ___114-[ATXDefaultHomeScreenItemManagerTransfer _fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]_block_invoke
+ ___153-[ATXDefaultHomeScreenItemOnboardingStacksProducer _dayZeroStacksFromRequiredPersonalitiesPerStack:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]_block_invoke
+ ___153-[ATXDefaultHomeScreenItemOnboardingStacksProducer _dayZeroStacksFromRequiredPersonalitiesPerStack:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]_block_invoke_2
+ ___196-[ATXDefaultHomeScreenItemOnboardingStacksProducer _blendedStacksForSize:requiredWidgetPersonalitiesPerStack:rankedWidgets:usedWidgetPersonalities:maxNumberOfWidgetsPerStack:denyListOfExtensions:]_block_invoke
+ ___196-[ATXDefaultHomeScreenItemOnboardingStacksProducer _blendedStacksForSize:requiredWidgetPersonalitiesPerStack:rankedWidgets:usedWidgetPersonalities:maxNumberOfWidgetsPerStack:denyListOfExtensions:]_block_invoke_2
+ ___55-[ATXDefaultHomeScreenItemProducer _personalizedUpdate]_block_invoke
+ ___86-[ATXDefaultHomeScreenItemManagerTransfer _deviceIdentifierForRelationshipIdentifier:]_block_invoke
+ ___86-[ATXDefaultHomeScreenItemManagerTransfer _deviceIdentifierForRelationshipIdentifier:]_block_invoke_2
+ ___ATXCanonicalContainerBundleIdForWidgetDedup_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e49_v24?0"ATXWidgetSmartStackResponse"8"NSError"16ls40l8s32l8
+ ___block_descriptor_48_e8_32s40r_e29_v16?0"NSMutableDictionary"8lr40l8s32l8
+ ___block_descriptor_48_e8_32s40s_e29_v16?0"NSMutableDictionary"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s_e30_B16?0"ATXWidgetPersonality"8ls32l8
+ ___pairedDeviceIdentifiersByRelationship_block_invoke
+ ___sharedWidgetSuggesterClient_block_invoke
+ _cachePath
+ _canonicalDeviceIdentifier
+ _isNilOrArrayOfWidgets
+ _isWellFormedSmartStackResponse
+ _kATXPairedDeviceWidgetRankingMaximumAge
+ _pairedDeviceIdentifiersByRelationship
+ _pairedDeviceIdentifiersByRelationship.lock
+ _pairedDeviceIdentifiersByRelationship.onceToken
+ _sharedWidgetSuggesterClient.client
+ _sharedWidgetSuggesterClient.onceToken
- ___79-[ATXDefaultHomeScreenItemOnboardingStacksProducer generatedStacksWithRequest:]_block_invoke
CStrings:
+ "%s: %lu third-party widgets available from the paired device's ranking"
+ "%s: Couldn't reach duetexpertd (%@), generating smart stacks in process"
+ "%s: Couldn't read import at %@: %@"
+ "%s: Importing %lu smart stacks from source device %@"
+ "%s: No descriptor available for required personalities %{public}@"
+ "%s: No paired device for relationship %@"
+ "%s: No usable stacks from paired device %@ (error: %@)"
+ "%s: Not importing malformed smart stacks"
+ "%s: Number of Stacks being requested %lu, including required widgets: %{BOOL}d"
+ "%s: Requesting smart stacks from duetexpertd for Client: %@"
+ "%s: Skipping remote widget %{public}@:%{public}@ because a local version exists for %{public}@:%{public}@"
+ "%s: blending %lu of the paired device's %lu ranked widgets"
+ "%s: blending %lu of the paired device's %lu ranked widgets into gallery widgets"
+ "%s: generating usage ranked stacks for Client. numDescriptors:%lu, descriptorCacheSize:%lu, appsWithLaunches:%lu"
+ "%s: stack has %lu of %lu widgets; the paired device has no more third-party widgets to fill it"
+ "(unstamped)"
+ "-[ATXDefaultHomeScreenItemManagerTransfer _fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]"
+ "-[ATXDefaultHomeScreenItemManagerTransfer _fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]_block_invoke"
+ "-[ATXDefaultHomeScreenItemManagerTransfer importWidgetSmartStackWithRequest:response:completionHandler:]"
+ "-[ATXDefaultHomeScreenItemManagerTransfer importedWidgetSmartStacksByPathForVariant:]"
+ "-[ATXDefaultHomeScreenItemManagerTransfer pairedDeviceWidgetSmartStackForVariant:relationshipIdentifier:maximumAge:]"
+ "-[ATXDefaultHomeScreenItemOnboardingStacksProducer _blendedStacksForSize:requiredWidgetPersonalitiesPerStack:rankedWidgets:usedWidgetPersonalities:maxNumberOfWidgetsPerStack:denyListOfExtensions:]"
+ "-[ATXDefaultHomeScreenItemOnboardingStacksProducer _generatedStacksWithRequest:includeRequiredWidgets:]"
+ "-[ATXDefaultHomeScreenItemOnboardingStacksProducer _stacksByFillingWithPairedDeviceThirdPartyWidgets:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]"
+ "-[ATXDefaultHomeScreenItemProducer usageRankedStacksWithRequest:]"
+ "ATXDefaultWidgetSuggesterClient: XPC error; could not generate smart stacks for paired tvOS device via duetexpertd: %@"
+ "Smart stacks to import are malformed"
+ "com.apple.iCal"
+ "dayZero:%{BOOL}d pairedDevice:%{BOOL}d"
+ "denyListWidgetsTvOS"
+ "onboardingDefaultStackTvOS"
+ "smartStackDenyListAssetLookup"
+ "smartStackDescriptorCacheAccess"
+ "smartStackPairedDeviceRanking"
+ "smartStackProtectedAppsLookup"
+ "sourceDeviceIdentifier"
+ "v16@?0@\"NSMutableDictionary\"8"
+ "v24@?0@\"ATXWidgetSmartStackResponse\"8@\"NSError\"16"
+ "widgets:%lu"
- "%s: Number of Stacks being requested %lu"
- "%s: Skipping remote widget because local version exists for %@:%@"
- "-[ATXDefaultHomeScreenItemOnboardingStacksProducer generatedStacksWithRequest:]"
- "dayZero:%{BOOL}d"
```
