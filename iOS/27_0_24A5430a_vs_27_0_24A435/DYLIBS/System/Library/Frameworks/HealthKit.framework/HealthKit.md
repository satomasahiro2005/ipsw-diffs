## HealthKit

> `/System/Library/Frameworks/HealthKit.framework/HealthKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f82ac` | `0x3f8d30` | **`+0xa84`** |
| `__TEXT.__cstring` | `0x37d12` | `0x380c2` | **`+0x3b0`** |
| `__AUTH_CONST.__objc_const` | `0x53528` | `0x53780` | **`+0x258`** |
| `__AUTH_CONST.__cfstring` | `0x338a0` | `0x33ae0` | **`+0x240`** |
| `__TEXT.__objc_methlist` | `0x317c4` | `0x318fc` | **`+0x138`** |
| `__TEXT.__swift5_reflstr` | `0x36bb` | `0x37cb` | **`+0x110`** |
| `__AUTH.__objc_data` | `0xf2c8` | `0xf368` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x13de9` | `0x13e69` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x12070` | `0x120e0` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x3f80` | `0x3ff0` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x13458` | `0x134a8` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x10478` | `0x104a8` | **`+0x30`** |
| `__DATA_CONST.__objc_arraydata` | `0x69e0` | `0x6a00` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x768` | `0x780` | **`+0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0x46b0` | `0x46c8` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x5320` | `0x5338` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x2f88` | `0x2f9c` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x1bd0` | `0x1be0` | **`+0x10`** |
| `__TEXT.__const` | `0x16218c` | `0x16219c` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1e08` | `0x1e10` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x17a8` | `0x17b0` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 29661
-  Symbols:   35805
-  CStrings:  9196
+  Functions: 29686
+  Symbols:   35859
+  CStrings:  9230
Symbols:
+ +[HKFeatureAvailabilityRequirementEntitlement userDefaultsHeartRatePreferencesDomainReadAccessEntitlement]
+ +[HKFeatureAvailabilityRequirementGreenLightMeasurementsAreEnabled requirementIdentifier]
+ +[HKFeatureAvailabilityRequirements greenLightMeasurementsAreEnabled]
+ +[HKHeartRatePreferencesConstants domain]
+ +[HKHeartRatePreferencesConstants enableGreenLightMeasurementsDuringTheaterModeKey]
+ +[HKHeartRatePreferencesConstants enableGreenLightMeasurementsKey]
+ +[HKHeartRatePreferencesConstants lastModifiedPreferencesDateKey]
+ +[HKUserDefaultsDataSource heartRatePreferencesDataSource]
+ -[HKFeatureAvailabilityRequirementEvaluationDataSource heartRatePreferencesDataSource]
+ -[HKFeatureAvailabilityRequirementEvaluationDataSource initWithHealthDataSource:bluetoothDeviceDataSource:privacyPreferencesDataSource:heartRatePreferencesDataSource:respiratoryPreferencesDataSource:ageGatingDataSource:userNotificationSettingsDataSource:wristDetectionSettingDataSource:devicePairingAndSwitchingNotificationDataSource:darwinNotificationDataSource:watchLowPowerModeDataSource:currentCountryCodeProvider:requirementSatisfactionOverridesDataSource:currentDateDataSource:OSEligibilityDataSource:watchAppInstallationDataSource:onboardingRecordFallbackProvider:userNotificationsDataSource:authorizationRecordDataSource:]
+ -[HKFeatureAvailabilityRequirementEvaluationDataSource initWithHealthDataSource:featureAvailabilityProvidingDataSource:featureStatusProvidingDataSource:bluetoothDeviceDataSource:privacyPreferencesDataSource:heartRatePreferencesDataSource:respiratoryPreferencesDataSource:ageGatingDataSource:userNotificationSettingsDataSource:wristDetectionSettingDataSource:devicePairingAndSwitchingNotificationDataSource:darwinNotificationDataSource:watchLowPowerModeDataSource:currentCountryCodeProvider:requirementSatisfactionOverridesDataSource:currentDateDataSource:OSEligibilityDataSource:watchAppInstallationDataSource:onboardingRecordFallbackProvider:userNotificationsDataSource:healthDataRequirementDataSource:importExclusionDeviceDataSource:authorizationRecordDataSource:]
+ -[HKFeatureAvailabilityRequirementGreenLightMeasurementsAreEnabled defaultBoolValueWhenKeyIsMissing]
+ -[HKFeatureAvailabilityRequirementGreenLightMeasurementsAreEnabled init]
+ -[HKFeatureAvailabilityRequirementGreenLightMeasurementsAreEnabled isSatisfiedForBoolValue:]
+ -[HKFeatureAvailabilityRequirementGreenLightMeasurementsAreEnabled requiredEntitlements]
+ -[HKFeatureAvailabilityRequirementGreenLightMeasurementsAreEnabled requirementDescription]
+ -[HKFeatureAvailabilityRequirementGreenLightMeasurementsAreEnabled whichUserDefaultsDataSourceInDataSource:]
+ -[_HKFeatureFlags allDayHRV]
+ -[_HKFeatureFlags allDayHeartRate]
+ -[_HKFeatureFlags hermitV2]
+ -[_HKFeatureFlags liveHeartRateComplications]
+ -[_HKFeatureFlags setAllDayHRV:]
+ -[_HKFeatureFlags setAllDayHeartRate:]
+ -[_HKFeatureFlags setHermitV2:]
+ -[_HKFeatureFlags setLiveHeartRateComplications:]
+ GCC_except_table183
+ GCC_except_table186
+ GCC_except_table188
+ _HKFeatureAvailabilityContextReadiness
+ _HKFeatureAvailabilityRequirementIdentifierGreenLightMeasurementsAreEnabled
+ _HKFeatureIdentifierHypertensionNotificationsV1
+ _HKFeatureIdentifierHypertensionNotificationsV2
+ _HKLocalDeviceHardwareSupportsContinuousHeartRate
+ _HKQuantityTypeIdentifierHeartRateVariabilityRMSSD
+ _OBJC_CLASS_$_HKFeatureAvailabilityRequirementGreenLightMeasurementsAreEnabled
+ _OBJC_CLASS_$_HKHeartRatePreferencesConstants
+ _OBJC_IVAR_$_HKFeatureAvailabilityRequirementEvaluationDataSource._heartRatePreferencesDataSource
+ _OBJC_IVAR_$__HKFeatureFlags._allDayHRV
+ _OBJC_IVAR_$__HKFeatureFlags._allDayHeartRate
+ _OBJC_IVAR_$__HKFeatureFlags._hermitV2
+ _OBJC_IVAR_$__HKFeatureFlags._liveHeartRateComplications
+ _OBJC_METACLASS_$_HKFeatureAvailabilityRequirementGreenLightMeasurementsAreEnabled
+ _OBJC_METACLASS_$_HKHeartRatePreferencesConstants
+ __HKWorkoutPowerModeTypeUsesBufferedSensorBehavior
+ __OBJC_$_CLASS_METHODS_HKFeatureAvailabilityRequirementGreenLightMeasurementsAreEnabled
+ __OBJC_$_CLASS_METHODS_HKHeartRatePreferencesConstants
+ __OBJC_$_CLASS_PROP_LIST_HKHeartRatePreferencesConstants
+ __OBJC_$_INSTANCE_METHODS_HKFeatureAvailabilityRequirementGreenLightMeasurementsAreEnabled
+ __OBJC_CLASS_RO_$_HKFeatureAvailabilityRequirementGreenLightMeasurementsAreEnabled
+ __OBJC_CLASS_RO_$_HKHeartRatePreferencesConstants
+ __OBJC_METACLASS_RO_$_HKFeatureAvailabilityRequirementGreenLightMeasurementsAreEnabled
+ __OBJC_METACLASS_RO_$_HKHeartRatePreferencesConstants
+ ___27-[_HKFeatureFlags hermitV2]_block_invoke
+ ___28-[_HKFeatureFlags allDayHRV]_block_invoke
+ ___34-[_HKFeatureFlags allDayHeartRate]_block_invoke
+ ___45-[_HKFeatureFlags liveHeartRateComplications]_block_invoke
+ _kHKInternalSettingsKeyFakeLiveHeartRates
- -[HKFeatureAvailabilityRequirementEvaluationDataSource initWithHealthDataSource:bluetoothDeviceDataSource:privacyPreferencesDataSource:respiratoryPreferencesDataSource:ageGatingDataSource:userNotificationSettingsDataSource:wristDetectionSettingDataSource:devicePairingAndSwitchingNotificationDataSource:darwinNotificationDataSource:watchLowPowerModeDataSource:currentCountryCodeProvider:requirementSatisfactionOverridesDataSource:currentDateDataSource:OSEligibilityDataSource:watchAppInstallationDataSource:onboardingRecordFallbackProvider:userNotificationsDataSource:authorizationRecordDataSource:]
- -[HKFeatureAvailabilityRequirementEvaluationDataSource initWithHealthDataSource:featureAvailabilityProvidingDataSource:featureStatusProvidingDataSource:bluetoothDeviceDataSource:privacyPreferencesDataSource:respiratoryPreferencesDataSource:ageGatingDataSource:userNotificationSettingsDataSource:wristDetectionSettingDataSource:devicePairingAndSwitchingNotificationDataSource:darwinNotificationDataSource:watchLowPowerModeDataSource:currentCountryCodeProvider:requirementSatisfactionOverridesDataSource:currentDateDataSource:OSEligibilityDataSource:watchAppInstallationDataSource:onboardingRecordFallbackProvider:userNotificationsDataSource:healthDataRequirementDataSource:importExclusionDeviceDataSource:authorizationRecordDataSource:]
- GCC_except_table96
CStrings:
+ "AllDayHRV"
+ "AllDayHeartRate"
+ "DaytimeMetricsInHealth"
+ "DaytimeMetricsIncludeFutureData"
+ "Device1,8240"
+ "Device1,8242"
+ "Device1,8245"
+ "Device1,8246"
+ "Device1,8247"
+ "Device1,8248"
+ "DeviceSupportsContinuousHeartRate"
+ "DeviceSupportsContinuousHeartRateOverride"
+ "EnableGreenLightMeasurements"
+ "EnableGreenLightMeasurementsDuringTheaterMode"
+ "FakeLiveHeartRates"
+ "Green Light Measurements must be enabled in Heart Rate preferences"
+ "GreenLightMeasurementsAreEnabled"
+ "HEART_RATE_VARIABILITY_RMSSD"
+ "HEART_RATE_VARIABILITY_SDNN"
+ "HKQuantityTypeIdentifierHeartRateVariabilityRMSSD"
+ "Hypertension Notifications 1.0"
+ "Hypertension Notifications 2.0"
+ "HypertensionNotificationsV1"
+ "HypertensionNotificationsV2"
+ "LastModifiedPreferencesDate"
+ "Localizable-AllDayHRV"
+ "Readiness"
+ "VitalsEnhancementsAlternatingExperienceVersion"
+ "VitalsEnhancementsExerciseCessation"
+ "VitalsEnhancementsUseSDNN"
+ "com.apple.HeartRate.preferences"
+ "heartRateStreamingChart"
+ "hermit1"
+ "hermit2"
+ "hermitV2"
+ "liveHeartRateComplications"
- "HEART_RATE_VARIABILITY"
- "\xf0!"
```
