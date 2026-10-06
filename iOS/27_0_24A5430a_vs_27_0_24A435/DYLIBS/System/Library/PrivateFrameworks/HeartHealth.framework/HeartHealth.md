## HeartHealth

> `/System/Library/PrivateFrameworks/HeartHealth.framework/HeartHealth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26e08` | `0x291c4` | **`+0x23bc`** |
| `__TEXT.__cstring` | `0x361a` | `0x381a` | **`+0x200`** |
| `__TEXT.__const` | `0x2f8` | `0x488` | **`+0x190`** |
| `__DATA.__bss` | `0x2c0` | `0x440` | **`+0x180`** |
| `__TEXT.__swift5_reflstr` | `0x57` | `0x1d1` | **`+0x17a`** |
| `__TEXT.__swift5_typeref` | `0x29` | `0x18b` | **`+0x162`** |
| `__AUTH_CONST.__const` | `0x390` | `0x4f0` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x17d4` | `0x18d4` | **`+0x100`** |
| `__DATA_CONST.__objc_selrefs` | `0x1be0` | `0x1cd0` | **`+0xf0`** |
| `__TEXT.__constg_swiftt` | `0x90` | `0x17c` | **`+0xec`** |
| `__TEXT.__unwind_info` | `0xbe0` | `0xcc8` | **`+0xe8`** |
| `__AUTH_CONST.__auth_got` | `0x4e8` | `0x5c0` | **`+0xd8`** |
| `__AUTH_CONST.__cfstring` | `0x2ce0` | `0x2d80` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x74` | `0x104` | **`+0x90`** |
| `__DATA_CONST.__got` | `0x5f0` | `0x678` | **`+0x88`** |
| `__AUTH_CONST.__objc_const` | `0x5e68` | `0x5ee8` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x2fec` | `0x305c` | **`+0x70`** |
| `__AUTH.__data` | `0xa8` | `0xf0` | **`+0x48`** |
| `__DATA.__data` | `0x928` | `0x970` | **`+0x48`** |
| `__DATA_CONST.__const` | `0xd40` | `0xd80` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x70` | `0xb0` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__swift5_assocty` | `0x18` | `0x30` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x314` | `0x320` | **`+0xc`** |
| `__TEXT.__swift5_proto` | `0x14` | `0x20` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0xc` | `0x14` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `—` | `0x4` | **`+0x4`** |

### Other Changes

```diff

+  - /usr/lib/swift/libswiftObservation.dylib

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 1227
-  Symbols:   2386
-  CStrings:  506
+  Functions: 1324
+  Symbols:   2455
+  CStrings:  517
Symbols:
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _analysisForFeatureIdentifier:featureFlagIsEnabled:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _backgroundDeliveryForFeatureIdentifier:featureFlagIsEnabled:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _basePromotionRequirementsForFeatureIdentifier:featureFlagIsEnabled:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _baseUsageWithFeatureOnRequirementIncluded:forFeatureIdentifier:featureFlagIsEnabled:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _dtdrEducationVisibilityForFeatureIdentifier:featureFlagIsEnabled:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _dtdrStatusVisibilityForFeatureIdentifier:featureFlagIsEnabled:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _featureDeviceCapabilityForFeatureIdentifier:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _featureFlagEnabledForFeatureIdentifier:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _localCountryIsSupportedRequirementForFeatureIdentifier:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _notificationSettingsVisibilityForFeatureIdentifier:featureFlagIsEnabled:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _onboardingInitiationForFeatureIdentifier:featureFlagIsEnabled:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _onboardingRecordRequirement]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _pregnancyAdjustmentEligibilityForFeatureIdentifier:featureFlagIsEnabled:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _promotionForFeatureIdentifier:featureFlagIsEnabled:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _remoteCountryIsSupportedRequirementForFeatureIdentifier:isSupportedIfCountryListMissing:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _requirementsByContextForFeatureIdentifier:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _settingsUserInteractionEnabledForFeatureIdentifier:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _settingsVisibilityWithFeatureOnboarded:forFeatureIdentifier:featureFlagIsEnabled:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _sharedFeatureIdentifier]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _usageForFeatureIdentifier:featureFlagIsEnabled:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements requirementSetForFeatureIdentifier:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements settingsUserInteractionRequirementIdentifiersForFeatureIdentifier:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements settingsVisibilityRequirementIdentifiersWithFeatureOnboarded:forFeatureIdentifier:featureFlagIsEnabled:]
+ +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements usageRequirementIdentifiersForFeatureIdentifier:featureFlagIsEnabled:]
+ +[HKHRHypertensionNotificationsSettings _countryRequirementWithIsOnboardingRecordPresent:]
+ +[HKHRHypertensionNotificationsSettings areRegionAndWatchSupportedVersionsMismatchedWithV1Evaluation:v2Evaluation:isOnboardingRecordPresent:]
+ -[HKHRHypertensionNotificationsSettings _setupVersionManagersWithIsOnboardingRecordPresent:]
+ -[HKHRHypertensionNotificationsSettings areRegionAndWatchSupportedVersionsMismatched]
+ -[HKHRHypertensionNotificationsSettings initWithIsOnboardingRecordPresent:]
+ _HKFeatureAvailabilityRequirementIdentifierCurrentCountryIsSupportedOnActiveRemoteDevice
+ _HKFeatureAvailabilityRequirementIdentifierCurrentCountryIsSupportedOnLocalDevice
+ _HKFeatureAvailabilityRequirementIdentifierFeatureFlagIsEnabled
+ _HKFeatureIdentifierHypertensionNotificationsV1
+ _HKFeatureIdentifierHypertensionNotificationsV2
+ _HKHRHypertensionNotificationsV2LocalFeatureAttributes
+ _HKHRHypertensionNotificationsV2SettingsLocstr
+ _OBJC_CLASS_$_HKFeatureStatusManager
+ _OBJC_CLASS_$_HKHealthStore
+ _OBJC_CLASS_$_HKHeartRatePreferencesConstants
+ _OBJC_IVAR_$_HKHRHypertensionNotificationsSettings._isOnboardingRecordPresent
+ _OBJC_IVAR_$_HKHRHypertensionNotificationsSettings._v1StatusManager
+ _OBJC_IVAR_$_HKHRHypertensionNotificationsSettings._v2StatusManager
+ __OBJC_$_CLASS_METHODS_HKHRHypertensionNotificationsSettings
+ ___swift_closure_destructor
+ ___swift_closure_destructorTm
+ ___swift_memcpy2_1
+ ___swift_memcpy56_8
+ __swiftEmptySetSingleton
+ _associated conformance 11HeartHealth0A15RatePreferencesVSHAASQ
+ _associated conformance 11HeartHealth0A23RatePreferencesProviderVAA0acD9ProvidingAA0acD8SequenceAaDP_Sci
+ _get_witness_table 11Observation12ObservationsVy11HeartHealth0C15RatePreferencesVs5NeverOGSciHPyHC
+ _objc_allocWithZone
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initWithCopy
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_deallocObject
+ _swift_getOpaqueTypeConformance2
+ _swift_initStackObject
+ _swift_release_x19
+ _swift_release_x22
+ _swift_release_x24
+ _swift_release_x25
+ _swift_retain_x19
+ _swift_retain_x22
+ _swift_retain_x24
+ _swift_retain_x25
+ _swift_setDeallocating
+ _symbolic $s11HeartHealth0A24RatePreferencesProvidingP
+ _symbolic 28HeartRatePreferencesSequence_____Qz 11HeartHealth0A24RatePreferencesProvidingP
+ _symbolic 28HeartRatePreferencesSequence______7ElementSciQZ 11HeartHealth0A24RatePreferencesProvidingP
+ _symbolic 28HeartRatePreferencesSequence______7FailureSciQZ 11HeartHealth0A24RatePreferencesProvidingP
+ _symbolic 7ElementSciQz
+ _symbolic 7FailureSciQz
+ _symbolic Sb
+ _symbolic ScA_pSg
+ _symbolic So8NSNumberCSg
+ _symbolic _____ 11HeartHealth0A15RatePreferencesV
+ _symbolic _____ 11HeartHealth0A23RatePreferencesProviderV
+ _symbolic _____ s5NeverO
+ _symbolic _____ySbG 15HealthUtilities21ObservableUserDefaultC
+ _symbolic _____yYbc 10Foundation4DateV
+ _symbolic _____y_____SgG 15HealthUtilities21ObservableUserDefaultC 10Foundation4DateV
+ _symbolic _____y__________G 11Observation12ObservationsV 11HeartHealth0C15RatePreferencesV s5NeverO
+ _symbolic x
+ _symbolic ySS_ShySSGtYbc
+ _type_layout_string 11HeartHealth0A15RatePreferencesV
+ _type_layout_string 11HeartHealth0A23RatePreferencesProviderV
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _analysis]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _backgroundDelivery]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _basePromotionRequirements]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _baseUsageWithFeatureOnRequirementIncluded:]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _dtdrEducationVisibility]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _dtdrStatusVisibility]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _hypertensionIdentifier]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _notificationSettingsVisibility]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _onboardingInitiation]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _pregnancyAdjustmentEligibility]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _promotion]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _settingsUserInteractionEnabled]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _settingsVisibilityWithFeatureOnboarded:]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements _usage]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements onboardingInitiationRequirementIdentifiers]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements promotionRequirementIdentifiers]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements requirementSet]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements settingsUserInteractionRequirementIdentifiers]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements settingsVisibilityRequirementIdentifiersWithFeatureOnboarded:]
- +[HKHRHypertensionNotificationsFeatureAvailabilityRequirements usageRequirementIdentifiers]
CStrings:
+ "(01)00195951129969"
+ "(01)00195951129976"
+ "+[HKHRHypertensionNotificationsSettings areRegionAndWatchSupportedVersionsMismatchedWithV1Evaluation:v2Evaluation:isOnboardingRecordPresent:]"
+ "-[HKHRHypertensionNotificationsSettings areRegionAndWatchSupportedVersionsMismatched]"
+ "2"
+ "HEART_NOTIFICATION_HYPERTENSION_NOTIFICATIONS_FOOTER_REGION_NOT_SUPPORTED_MISMATCH"
+ "HEART_NOTIFICATION_HYPERTENSION_NOTIFICATIONS_FOOTER_REGION_NOT_SUPPORTED_MISMATCH_NANO"
+ "HeartRateSettings-HypertensionNotificationsV2"
+ "[%{public}s] Failed to get v1 feature status: %{public}@"
+ "[%{public}s] Failed to get v2 feature status: %{public}@"
+ "[%{public}s] Supported Region-Watch Mismatch: v1OnlyRegionWithV2Watch: %i, v2OnlyRegionWithV1Watch: %i isOnboardingRecordPresent: %i"
+ "algorithmVersion"
+ "d2f9b521-e715-4a96-94f9-19c209511ee5"
- "(01)00195949001789"
- "(01)00195949001796"
```
