## HealthRecordsUI

> `/System/Library/PrivateFrameworks/HealthRecordsUI.framework/HealthRecordsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4009b8` | `0x407e10` | **`+0x7458`** |
| `__TEXT.__cstring` | `0x11bc1` | `0x12067` | **`+0x4a6`** |
| `__TEXT.__eh_frame` | `0x123b8` | `0x12638` | **`+0x280`** |
| `__AUTH_CONST.__objc_const` | `0x1f358` | `0x1f540` | **`+0x1e8`** |
| `__AUTH_CONST.__const` | `0x159b8` | `0x15b20` | **`+0x168`** |
| `__AUTH.__objc_data` | `0xe930` | `0xea80` | **`+0x150`** |
| `__AUTH_CONST.__cfstring` | `0x2500` | `0x2640` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0xe1c8` | `0xe2c8` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x94a4` | `0x958c` | **`+0xe8`** |
| `__TEXT.__const` | `0x1b774` | `0x1b854` | **`+0xe0`** |
| `__TEXT.__swift5_capture` | `0x48c4` | `0x49a4` | **`+0xe0`** |
| `__TEXT.__swift5_reflstr` | `0x961f` | `0x96e7` | **`+0xc8`** |
| `__DATA_CONST.__objc_selrefs` | `0x5fd8` | `0x6080` | **`+0xa8`** |
| `__TEXT.__constg_swiftt` | `0x11718` | `0x117ac` | **`+0x94`** |
| `__DATA.__data` | `0x8bf8` | `0x8c70` | **`+0x78`** |
| `__AUTH_CONST.__auth_got` | `0x3990` | `0x3a00` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x97ac` | `0x981c` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x1a30` | `0x1a80` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x79f9` | `0x7a39` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x2468` | `0x2498` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x882e` | `0x8854` | **`+0x26`** |
| `__AUTH.__data` | `0xadc0` | `0xade0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x4a8` | `0x4c8` | **`+0x20`** |
| `__DATA.__bss` | `0x1fd48` | `0x1fd58` | **`+0x10`** |
| `__DATA.__common` | `0x608` | `0x618` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x5dc` | `0x5ec` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xa40` | `0xa50` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x3e4` | `0x3f0` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x420` | `0x42c` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0xc78` | `0xc80` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x4e08` | `0x4e10` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x30d8` | `0x30e0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xad8` | `0xadc` | **`+0x4`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 19924
-  Symbols:   8489
-  CStrings:  2182
+  Functions: 20013
+  Symbols:   8524
+  CStrings:  2207
Symbols:
+ -[HRAccountsTableViewController _isManuallyEnteredRecordsSection:]
+ -[HRAccountsTableViewController _reloadManuallyEnteredRecordsAvailability]
+ -[HRAccountsTableViewController hasManuallyEnteredRecords]
+ -[HRAccountsTableViewController manuallyEnteredRecordsGeneration]
+ -[HRAccountsTableViewController setHasManuallyEnteredRecords:]
+ -[HRAccountsTableViewController setManuallyEnteredRecordsGeneration:]
+ -[HRAccountsTableViewController viewWillAppear:]
+ -[WDClinicalOnboardingOAuthNavigationViewController _createLongevityHeaderView]
+ -[WDClinicalOnboardingOAuthNavigationViewController _createNoGeoMessageView]
+ -[WDClinicalOnboardingOAuthNavigationViewController _locationServicesSettingsURL]
+ -[WDClinicalOnboardingOAuthNavigationViewController textView:primaryActionForTextItem:defaultAction:]
+ -[WDClinicalOnboardingViewController _configureNoGeoMessageViewIfNeeded]
+ -[WDClinicalOnboardingViewController noGeoMessageView]
+ -[WDClinicalOnboardingViewController setNoGeoMessageView:]
+ -[WDClinicalOnboardingViewController setShowsNoGeoMessage:]
+ -[WDClinicalOnboardingViewController showsNoGeoMessage]
+ GCC_except_table3
+ GCC_except_table78
+ GCC_except_table80
+ GCC_except_table86
+ GCC_except_table96
+ _OBJC_CLASS_$_HRManuallyEnteredRecordsAvailability
+ _OBJC_IVAR_$_HRAccountsTableViewController._hasManuallyEnteredRecords
+ _OBJC_IVAR_$_HRAccountsTableViewController._manuallyEnteredRecordsGeneration
+ _OBJC_IVAR_$_WDClinicalOnboardingViewController._noGeoMessageView
+ _OBJC_IVAR_$_WDClinicalOnboardingViewController._showsNoGeoMessage
+ _OBJC_METACLASS_$_HRManuallyEnteredRecordsAvailability
+ __CLASS_METHODS_HRManuallyEnteredRecordsAvailability
+ __DATA_HRManuallyEnteredRecordsAvailability
+ __INSTANCE_METHODS_HRManuallyEnteredRecordsAvailability
+ __METACLASS_DATA_HRManuallyEnteredRecordsAvailability
+ ___74-[HRAccountsTableViewController _reloadManuallyEnteredRecordsAvailability]_block_invoke
+ ___74-[HRAccountsTableViewController _reloadManuallyEnteredRecordsAvailability]_block_invoke_2
+ ___block_descriptor_48_e8_32w_e8_v16?0q8lw32l8
+ ___block_descriptor_56_e8_32w_e5_v8?0lw32l8
+ ___swift_closure_destructor.10Tm
+ ___swift_closure_destructor.58Tm
+ ___swift_closure_destructor.97Tm
+ _symbolic _____ 15HealthRecordsUI015ManuallyEnteredB12AvailabilityC
+ _symbolic _____Ieghy_ So23HKFailableBooleanResultV
+ _symbolic _____IeyBhy_ So23HKFailableBooleanResultV
+ _symbolic _____XMT 15HealthRecordsUI015ManuallyEnteredB12AvailabilityC
- -[WDClinicalOnboardingOAuthNavigationViewController _createHealthReportHeaderView]
- GCC_except_table2
- GCC_except_table77
- GCC_except_table79
- GCC_except_table85
- GCC_except_table95
- ___swift_closure_destructor.9Tm
CStrings:
+ "%@ %@."
+ "-[HRAccountsTableViewController _reloadManuallyEnteredRecordsAvailability] requires main thread"
+ "CHR_ADD_ACCOUNT_SUBTITLE"
+ "ClinicalAccountManager:fetchNumberOfWalletCards"
+ "Failed to check for manually entered records: %{public}@"
+ "HEALTH_RECORDS_ONBOARDING_LOCATION_SERVICES_LINK_TITLE"
+ "HEALTH_RECORDS_ONBOARDING_LOCATION_SERVICES_OFF_BODY"
+ "HealthRecordsUI/LabsListDataProvider.swift"
+ "MANUALLY_ENTERED_RECORDS_TITLE"
+ "ManuallyEntered"
+ "ManuallyEnteredRecordsCell"
+ "OntologyConceptDetailLoadingViewController:medicalConcept"
+ "PDFDataProvider:fetchMedicalHistoryRecords"
+ "PDFDataProvider:fetchMedicalRecords"
+ "RecordKindDataProvider:fetchCHRCategoryRecordKinds"
+ "RecordKindDataProvider:fetchMHRCategoryRecordKinds"
+ "TimelineRecordFetcher:createObserverQuery"
+ "TimelineViewDataProvider+SCD:fetchSignedClinicalDataRecord"
+ "WDClinicalSourcesDataProvider:fetchAccountOwnerForSource"
+ "WDClinicalSourcesDataProvider:fetchSignedClinicalDataRecordWithIdentifier"
+ "healthRecords.labPanels.AdvancedHeartLabs"
+ "healthRecords.labPanels.BloodAndImmuneLabs"
+ "healthRecords.labPanels.BloodGlucose"
+ "healthRecords.labPanels.BloodLipids"
+ "healthRecords.labPanels.KidneyLabs"
+ "healthRecords.labPanels.LiverLabs"
+ "init(profile:category:accountId:conceptIdentifier:userDomainConcept:highlightedRecordId:displayingRemovedRecords:preloadedRemovedRecords:predicatePerSampleType:showExportButton:inSettings:manuallyEnteredRecordsOnly:)"
+ "v16@?0q8"
+ "\xf0\xa1"
- "FromHealthReport"
- "init(profile:category:accountId:conceptIdentifier:userDomainConcept:highlightedRecordId:displayingRemovedRecords:preloadedRemovedRecords:predicatePerSampleType:showExportButton:inSettings:)"
- "x-apple-health://browse"
- "\xf0\x91"
```
