## HealthKit

> `/System/Library/Frameworks/HealthKit.framework/HealthKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0xd491c` | `0xd59cc` | **`+0x10b0`** |
| `__TEXT.__text` | `0x42bdbc` | `0x42cd8c` | **`+0xfd0`** |
| `__TEXT.__cstring` | `0x38892` | `0x38b52` | **`+0x2c0`** |
| `__AUTH_CONST.__cfstring` | `0x345a0` | `0x34720` | **`+0x180`** |
| `__AUTH_CONST.__objc_const` | `0x567f0` | `0x56948` | **`+0x158`** |
| `__TEXT.__oslogstring` | `0xdb53` | `0xdca3` | **`+0x150`** |
| `__DATA.__data` | `0x10330` | `0x10470` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x32fb4` | `0x3306c` | **`+0xb8`** |
| `__TEXT.__gcc_except_tab` | `0x40d8` | `0x4158` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x14d81` | `0x14d11` | **`-0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x124f8` | `0x12558` | **`+0x60`** |
| `__AUTH.__objc_data` | `0xfe30` | `0xfe80` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x14228` | `0x14270` | **`+0x48`** |
| `__DATA_CONST.__const` | `0xffc0` | `0xfff0` | **`+0x30`** |
| `__DATA_DIRTY.__bss` | `0xd78` | `0xd98` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1f00` | `0x1f18` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x1098` | `0x1080` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x20a8` | `0x20b8` | **`+0x10`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x160` | `0x150` | **`-0x10`** |
| `__DATA.__bss` | `0x347a0` | `0x34790` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x318` | `0x308` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x3c7b` | `0x3c6b` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1d10` | `0x1d18` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x848` | `0x850` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x316c` | `0x3170` | **`+0x4`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 30859
-  Symbols:   37030
-  CStrings:  9024
+  Functions: 30872
+  Symbols:   37055
+  CStrings:  9043
Symbols:
+ +[HKCardioFitnessClassificationUtilities _displayVO2MaxUpperBoundForBiologicalSex:]
+ +[_HKPredicateValidator validateAndAllowEvaluation:error:]
+ -[HKPairedDeviceAppInstallationManager isAppListUnavailableForError:]
+ -[HKSourceRevision _initWithSource:version:productType:operatingSystemVersion:systemBuild:]
+ -[HKSourceRevision _systemBuild]
+ -[HKWatchAppInstallationManager isAppListUnavailableForError:]
+ -[_HKPredicateValidator visitExpression:error:]
+ -[_HKPredicateValidator visitOperatorType:error:]
+ -[_HKPredicateValidator visitPredicate:error:]
+ _HKIsSupportedFilterOperatorType
+ _NSLocaleMeasurementSystem
+ _NSLocaleMeasurementSystemMetric
+ _OBJC_CLASS_$__HKPredicateValidator
+ _OBJC_IVAR_$_HKSourceRevision._systemBuild
+ _OBJC_METACLASS_$__HKPredicateValidator
+ __OBJC_$_CLASS_METHODS__HKPredicateValidator
+ __OBJC_$_INSTANCE_METHODS__HKPredicateValidator
+ __OBJC_$_PROP_LIST__HKPredicateValidator
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSPredicateValidating
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSPredicateValidating
+ __OBJC_$_PROTOCOL_REFS_NSPredicateValidating
+ __OBJC_CLASS_PROTOCOLS_$__HKPredicateValidator
+ __OBJC_CLASS_RO_$__HKPredicateValidator
+ __OBJC_LABEL_PROTOCOL_$_NSPredicateValidating
+ __OBJC_METACLASS_RO_$__HKPredicateValidator
+ __OBJC_PROTOCOL_$_NSPredicateValidating
+ ____queryCoreMotionCoefficientRows_block_invoke
+ ___block_descriptor_40_e8_32r_e29_v24?0"NSArray"8"NSError"16lr32l8
+ _kHKAppleIntelligenceAvailabilitySimulation
+ _kHKAppleIntelligenceConfigurationHeldEnabledState
- _HKCardioFitnessDisplayVO2MaxUpperBound
- __ZZL36_HKMulberryEnabledForCustomerVariantvE17isCustomerVariant
- __ZZL36_HKMulberryEnabledForCustomerVariantvE9onceToken
- ____ZL36_HKMulberryEnabledForCustomerVariantv_block_invoke
- _kHKInternalSettingsShowLabKitInBrowse
CStrings:
+ "%{public}@: Error retrieving cardio fitness threshold coefficients from Core Motion: %{public}@"
+ "%{public}@: Unrecognized cardio fitness threshold coefficients from Core Motion"
+ "&IncludeDevicePrefixInTitle=1"
+ "<%@ name:%@, bundle:%@, version:%@, productType:%@, operatingSystemVersion:%@, systemBuild:%@>"
+ "Failed to decode sort constraint: %{public}@"
+ "HKBloodPressureClassificationPregnancyModelProviding.pregnancyModel()"
+ "HKHeartRateRecoveryQueryUtility:_heartRatesPostWorkout"
+ "HKHeartRateVariabilityUtilities:queryForParentSequenceOfHRV"
+ "HKMultiTypeSampleIterator:_queryForNextPageIfNecessaryWithError"
+ "HKQueryUtilities:countStatisticsQuery:%@"
+ "HKSampleQueryUtility:setupQueryWithCompletionHandler"
+ "HKSleepDaySummaryCollectionQuery:init"
+ "HKWorkoutRouteStore:_fetchAllLocationsFromSeriesSample"
+ "SleepOrchestration"
+ "Unsupported expression: %@"
+ "Unsupported operator: %@"
+ "Unsupported predicate: %@"
+ "Zone boundaries are incompatible with the quantity type"
+ "[%{public}@]: Reporting %{public}@ as not installed, because the watch's app list could not be read: %{public}@"
+ "kHKAppleIntelligenceAvailabilitySimulation"
+ "kHKAppleIntelligenceConfigurationHeldEnabledState"
+ "systemBuild"
- "<%@ name:%@, bundle:%@, version:%@, productType:%@, operatingSystemVersion:%@>"
- "ShowLabKitInBrowse"
- "VitalsEnhancementsExerciseCessation"
```
