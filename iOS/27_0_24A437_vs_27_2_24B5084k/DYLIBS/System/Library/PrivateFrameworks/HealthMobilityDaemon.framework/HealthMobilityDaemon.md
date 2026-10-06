## HealthMobilityDaemon

> `/System/Library/PrivateFrameworks/HealthMobilityDaemon.framework/HealthMobilityDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7fb8` | `0x75c8` | **`-0x9f0`** |
| `__TEXT.__oslogstring` | `0x17fb` | `0x1546` | **`-0x2b5`** |
| `__TEXT.__objc_methlist` | `0xc74` | `0xbfc` | **`-0x78`** |
| `__AUTH_CONST.__objc_const` | `0x1180` | `0x11f0` | **`+0x70`** |
| `__AUTH.__objc_data` | `0xa0` | `0xf0` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x8f0` | `0x8b0` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x1a8` | `0x180` | **`-0x28`** |
| `__AUTH_CONST.__objc_intobj` | `0xc0` | `0xa8` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x268` | `0x250` | **`-0x18`** |
| `__TEXT.__cstring` | `0x4c6` | `0x4b3` | **`-0x13`** |
| `__DATA_CONST.__got` | `0x288` | `0x290` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__const` | `0x80` | `0x78` | **`-0x8`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/PrivateFrameworks/HealthFeatures.framework/HealthFeatures

-  Functions: 189
-  Symbols:   520
-  CStrings:  116
+  Functions: 179
+  Symbols:   515
+  CStrings:  104
Symbols:
+ +[HKMobilityWalkingSteadinessFeatureAvailabilityRequirements requirementSet]
+ _OBJC_CLASS_$_HKFeatureAvailabilityRequirementSet
+ _OBJC_METACLASS_$_HKMobilityWalkingSteadinessFeatureAvailabilityRequirements
+ __OBJC_$_CLASS_METHODS_HKMobilityWalkingSteadinessFeatureAvailabilityRequirements
+ __OBJC_CLASS_RO_$_HKMobilityWalkingSteadinessFeatureAvailabilityRequirements
+ __OBJC_METACLASS_RO_$_HKMobilityWalkingSteadinessFeatureAvailabilityRequirements
- -[HDMobilityWalkingSteadinessFeatureAvailabilityManager _determineIsSupportedWithOnboardingCompletions:regionCheckBlock:]
- -[HDMobilityWalkingSteadinessFeatureAvailabilityManager _localRegionCheckWithCountryCode:]
- -[HDMobilityWalkingSteadinessFeatureAvailabilityManager _onboardedCountryCodeSupportedStateWithError:]
- -[HDMobilityWalkingSteadinessFeatureAvailabilityManager _onboardingCompletionsForHighestVersionWithError:]
- -[HDMobilityWalkingSteadinessFeatureAvailabilityManager earliestDateLowestOnboardingVersionCompletedWithError:]
- -[HDMobilityWalkingSteadinessFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithCompletion:]
- -[HDMobilityWalkingSteadinessFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithError:]
- -[HDMobilityWalkingSteadinessFeatureAvailabilityManager onboardedCountryCodeSupportedStateWithError:]
- ___102-[HDMobilityWalkingSteadinessFeatureAvailabilityManager _onboardedCountryCodeSupportedStateWithError:]_block_invoke
- ___102-[HDMobilityWalkingSteadinessFeatureAvailabilityManager isCurrentOnboardingVersionCompletedWithError:]_block_invoke
- ___block_descriptor_40_e8_32s_e18_B16?0"NSString"8ls32l8
CStrings:
- "B16@?0@\"NSString\"8"
- "[%{public}@] Country code %{private}@ not supported"
- "[%{public}@] Country code %{private}@ supported"
- "[%{public}@] Error retrieving onboarding completions: %{public}@"
- "[%{public}@] Failed to fetch highest version of onboarding completed: %{public}@"
- "[%{public}@] No onboarding completion found"
- "[%{public}@] No onboarding completions meet the current requirements"
- "[%{public}@] Onboarded country code state: %{public}i"
- "[%{public}@] Onboarding completion found that does not satisfy region check"
- "[%{public}@] Onboarding completion found that satisfies region check"
- "[%{public}@] Onboarding completion found with no country code"
- "[%{public}@] Onboarding completion found with older version than current"
```
