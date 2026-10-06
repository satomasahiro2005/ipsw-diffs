## HealthMobility

> `/System/Library/PrivateFrameworks/HealthMobility.framework/HealthMobility`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x75e0` | `0x5b8c` | **`-0x1a54`** |
| `__DATA_CONST.__objc_selrefs` | `0x900` | `0x750` | **`-0x1b0`** |
| `__TEXT.__objc_methlist` | `0xc74` | `0xb3c` | **`-0x138`** |
| `__AUTH_CONST.__objc_const` | `0x16f8` | `0x15d8` | **`-0x120`** |
| `__DATA_CONST.__got` | `0x190` | `0x108` | **`-0x88`** |
| `__AUTH_CONST.__const` | `0xc0` | `0x40` | **`-0x80`** |
| `__TEXT.__cstring` | `0xe30` | `0xdcc` | **`-0x64`** |
| `__AUTH.__objc_data` | `0x280` | `0x230` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x230` | `0x1e0` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x2b8` | `0x270` | **`-0x48`** |
| `__DATA_CONST.__const` | `0x480` | `0x440` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x40b` | `0x3ce` | **`-0x3d`** |
| `__DATA_CONST.__objc_classlist` | `0x78` | `0x68` | **`-0x10`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

-  Functions: 254
-  Symbols:   624
-  CStrings:  140
+  Functions: 226
+  Symbols:   565
+  CStrings:  137
Symbols:
- +[HKMobilityNotificationRequestManager postWalkingSteadinessNotificationWithHealthStore:category:completion:]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _advertisableFeature]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _backgroundDelivery]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _classification]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _eventSubmission]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _featureIdentifier]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _notInPregnancyMode]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _notOnboardedHealthChecklist]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _notificationSettingsVisibility]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _onboardedHealthChecklist]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _onboardingInitiation]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _pregnancyAdjustmentEligibility]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _promotionFeatureTag]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _promotion]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _requirementIdentifiersForRequirements:]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements backgroundDeliveryIdentifiers]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements classificationGeneration]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements eventSubmission]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements notInPregnancyModeRequirementIdentifiers]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements notificationSettingsVisibility]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements onboardingInitiationRequirementIdentifiers]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements promotionFeatureTagRequirementIdentifiers]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements promotionRequirementIdentifiers]
- +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements requirementSet]
- _HKFeatureAvailabilityContextAdvertisableFeature
- _HKFeatureAvailabilityContextBackgroundDelivery
- _HKFeatureAvailabilityContextOmitPregnancyContent
- _HKFeatureAvailabilityContextOnboardingInitiation
- _HKFeatureAvailabilityContextOnboardingPromotion
- _HKFeatureAvailabilityContextPregnancyAdjustmentEligibility
- _HKFeatureAvailabilityRequirementIdentifierFeatureIsOn
- _HKFeatureAvailabilityRequirementIdentifierOnboardingNotAcknowledged
- _HKFeatureAvailabilityRequirementIdentifierOnboardingRecordIsPresent
- _HKFeatureIdentifierWalkingSteadinessClassifications
- _OBJC_CLASS_$_HKFeatureAvailabilityRequirementSet
- _OBJC_CLASS_$_HKFeatureAvailabilityRequirements
- _OBJC_CLASS_$_HKFeatureStatusManager
- _OBJC_CLASS_$_HKMobilityNotificationRequestManager
- _OBJC_CLASS_$_HKMobilityWalkingSteadinessFeatureAvailabilityRequirements
- _OBJC_CLASS_$_HKNotificationStore
- _OBJC_CLASS_$_NSDictionary
- _OBJC_METACLASS_$_HKMobilityNotificationRequestManager
- _OBJC_METACLASS_$_HKMobilityWalkingSteadinessFeatureAvailabilityRequirements
- __OBJC_$_CLASS_METHODS_HKMobilityNotificationRequestManager
- __OBJC_$_CLASS_METHODS_HKMobilityWalkingSteadinessFeatureAvailabilityRequirements
- __OBJC_CLASS_RO_$_HKMobilityNotificationRequestManager
- __OBJC_CLASS_RO_$_HKMobilityWalkingSteadinessFeatureAvailabilityRequirements
- __OBJC_METACLASS_RO_$_HKMobilityNotificationRequestManager
- __OBJC_METACLASS_RO_$_HKMobilityWalkingSteadinessFeatureAvailabilityRequirements
- ___101+[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _requirementIdentifiersForRequirements:]_block_invoke
- ___82+[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _advertisableFeature]_block_invoke
- ___93+[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _notificationSettingsVisibility]_block_invoke
- ___93+[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements _pregnancyAdjustmentEligibility]_block_invoke
- ___block_descriptor_32_e44_B16?0"<HKFeatureAvailabilityRequirement>"8l
- ___block_descriptor_32_e54_"NSString"16?0"<HKFeatureAvailabilityRequirement>"8l
- _kHKAgeGatingKeyEnableWalkingSteadiness
- _kHKHealthAppBundleIdentifier
- _objc_release_x27
- _objc_release_x28
CStrings:
- "@\"NSString\"16@?0@\"<HKFeatureAvailabilityRequirement>\"8"
- "B16@?0@\"<HKFeatureAvailabilityRequirement>\"8"
- "[%{public}@]: Unable to get featureStatus. error: %{public}@"
```
