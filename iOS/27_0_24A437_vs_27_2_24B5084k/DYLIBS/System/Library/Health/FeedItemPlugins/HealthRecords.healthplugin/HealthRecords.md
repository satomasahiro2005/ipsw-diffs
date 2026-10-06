## HealthRecords

> `/System/Library/Health/FeedItemPlugins/HealthRecords.healthplugin/HealthRecords`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13d31c` | `0x177138` | **`+0x39e1c`** |
| `__TEXT.__const` | `0xa6c8` | `0xbf18` | **`+0x1850`** |
| `__DATA_CONST.__got` | `0x0` | `0x17c0` | **`+0x17c0`** |
| `__DATA.__bss` | `0xa300` | `0xb7b8` | **`+0x14b8`** |
| `__TEXT.__eh_frame` | `0x7068` | `0x7f84` | **`+0xf1c`** |
| `__AUTH_CONST.__const` | `0x4c40` | `0x5ac8` | **`+0xe88`** |
| `__DATA.__data` | `0x1688` | `0x2510` | **`+0xe88`** |
| `__AUTH_CONST.__auth_got` | `0x24a8` | `0x3320` | **`+0xe78`** |
| `__TEXT.__cstring` | `0x268e` | `0x32e3` | **`+0xc55`** |
| `__TEXT.__unwind_info` | `0x4330` | `0x4da0` | **`+0xa70`** |
| `__TEXT.__swift5_typeref` | `0x1cfc` | `0x26ea` | **`+0x9ee`** |
| `__TEXT.__constg_swiftt` | `0x3570` | `0x3f0c` | **`+0x99c`** |
| `__AUTH.__data` | `0x1480` | `0x1cf8` | **`+0x878`** |
| `__AUTH_CONST.__objc_const` | `0x3d48` | `0x4440` | **`+0x6f8`** |
| `__TEXT.__swift5_fieldmd` | `0x29f4` | `0x3094` | **`+0x6a0`** |
| `__TEXT.__swift5_reflstr` | `0x21a4` | `0x27f4` | **`+0x650`** |
| `__DATA_DIRTY.__bss` | `0x7d00` | `0x8200` | **`+0x500`** |
| `__AUTH.__objc_data` | `0x1230` | `0x14d8` | **`+0x2a8`** |
| `__TEXT.__swift5_capture` | `0x9e0` | `0xc64` | **`+0x284`** |
| `__TEXT.__swift5_assocty` | `0x698` | `0x918` | **`+0x280`** |
| `__TEXT.__oslogstring` | `0x3e19` | `0x3fb9` | **`+0x1a0`** |
| `__DATA_CONST.__objc_selrefs` | `0xf18` | `0x1090` | **`+0x178`** |
| `__TEXT.__swift5_proto` | `0x910` | `0x9e8` | **`+0xd8`** |
| `__DATA_DIRTY.__data` | `0x4758` | `0x4818` | **`+0xc0`** |
| `__TEXT.__swift5_types` | `0x334` | `0x3b8` | **`+0x84`** |
| `__DATA.__common` | `0x148` | `0x1b0` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x6ec` | `0x754` | **`+0x68`** |
| `__TEXT.__swift_as_cont` | `0x590` | `0x5e4` | **`+0x54`** |
| `__DATA_CONST.__const` | `0x118` | `0x158` | **`+0x40`** |
| `__TEXT.__swift_as_entry` | `0x1b0` | `0x1e8` | **`+0x38`** |
| `__TEXT.__swift_as_ret` | `0x26c` | `0x2a4` | **`+0x38`** |
| `__DATA_CONST.__objc_classlist` | `0x180` | `0x1a8` | **`+0x28`** |
| `__DATA_DIRTY.__objc_data` | `0xe68` | `0xe88` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0xc8` | `0xdc` | **`+0x14`** |
| `__DATA_CONST.__objc_protolist` | `0x60` | `0x70` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x24` | `0x34` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x30` | `0x38` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0x298` | `0x2a0` | **`+0x8`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/PrivateFrameworks/HealthContent.framework/HealthContent

+  - /System/Library/PrivateFrameworks/HealthFoundationUI.framework/HealthFoundationUI
+  - /System/Library/PrivateFrameworks/HealthHistory.framework/HealthHistory

+  - /System/Library/PrivateFrameworks/HealthReportCoreUI.framework/HealthReportCoreUI

+  - /usr/lib/swift/libswiftObservation.dylib

-  Functions: 5214
-  Symbols:   364
-  CStrings:  488
+  Functions: 6195
+  Symbols:   410
+  CStrings:  571
Symbols:
+ _CGRectGetMaxX
+ _CGRectGetMaxY
+ _CGRectGetMidX
+ _CGRectGetMinX
+ _CGRectGetMinY
+ _HKFormatAttributedValueAndUnit
+ _HKFormatValueAndUnit
+ _HKLocalizedStringForDateAndTemplate
+ _HKMedicalHistoryAllergyRecordTypeIdentifierMedicalHistoryAllergyRecord
+ _HKMedicalHistoryHealthConcernRecordTypeIdentifierMedicalHistoryHealthConcernRecord
+ _HKMedicalHistoryImmunizationRecordTypeIdentifierMedicalHistoryImmunizationRecord
+ _HKMedicalHistoryProcedureRecordTypeIdentifierMedicalHistoryProcedureRecord
+ _HKMedicalHistoryQuantitativeLabResultRecordTypeIdentifierMedicalHistoryQuantitativeLabResultRecord
+ _HKQuantityTypeIdentifierBodyMass
+ _NSFontAttributeName
+ _OBJC_CLASS_$_HKMedicalHistoryQuantitativeLabResultRecord
+ _OBJC_CLASS_$_HKObserverQuery
+ _OBJC_CLASS_$_HKQuantity
+ _OBJC_CLASS_$_HKUnit
+ _OBJC_CLASS_$_NSAttributedString
+ _OBJC_CLASS_$_NSCollectionLayoutSection
+ _OBJC_CLASS_$_NSDateFormatter
+ _OBJC_CLASS_$_UIActivityIndicatorView
+ _UIFontTextStyleCallout
+ _UIFontTextStyleTitle1
+ _UIFontWeightRegular
+ __availability_version_check
+ _dispatch_once_f
+ _dlsym
+ _fclose
+ _fopen
+ _fread
+ _fseek
+ _ftell
+ _malloc
+ _objc_retain_x10
+ _objc_retain_x11
+ _rewind
+ _sscanf
+ _swift_getKeyPath
+ _swift_getOpaqueTypeConformance2
+ _swift_getOpaqueTypeMetadata2
+ _swift_getTupleTypeMetadata
+ _swift_makeBoxUnique
+ _swift_retain_x9
+ _swift_storeEnumTagMultiPayload
+ _swift_task_deinitOnExecutor
- _objc_retain_x12
CStrings:
+ "%d.%d.%d"
+ "/System/Library/CoreServices/SystemVersion.plist"
+ "BODY_COMPOSITION_ESCALATION_DESCRIPTION"
+ "CFDataCreateWithBytesNoCopy"
+ "CFDictionaryGetValue"
+ "CFGetTypeID"
+ "CFPropertyListCreateFromXMLData"
+ "CFPropertyListCreateWithData"
+ "CFRelease"
+ "CFStringCreateWithCStringNoCopy"
+ "CFStringGetCString"
+ "CFStringGetTypeID"
+ "CONTRIBUTING_DATUM_ABOUT_MEASURE_SECTION_TITLE"
+ "CONTRIBUTING_DATUM_ABOUT_RANGES_SECTION_TITLE"
+ "CONTRIBUTING_DATUM_HEALTH_RANGE_BODY"
+ "CONTRIBUTING_DATUM_HEALTH_RANGE_TITLE"
+ "CONTRIBUTING_DATUM_IN_RANGE"
+ "CONTRIBUTING_DATUM_LAB_RANGE_BODY"
+ "CONTRIBUTING_DATUM_LAB_RANGE_TITLE"
+ "CONTRIBUTING_DATUM_NO_DATA"
+ "CONTRIBUTING_DATUM_NO_LAB_RANGE_BODY"
+ "CONTRIBUTING_DATUM_NO_LAB_RANGE_TITLE"
+ "CONTRIBUTING_DATUM_OUT_OF_RANGE"
+ "CONTRIBUTING_DATUM_RANGE_SELECTOR_LABEL"
+ "CONTRIBUTING_DATUM_SHOW_ALL_DATA"
+ "CONTRIBUTING_DATUM_YOUR_LEVEL"
+ "Cell.DataTypeDetail."
+ "Cell.DataTypeDetail.ContributingDatumAboutMeasure"
+ "Cell.DataTypeDetail.ContributingDatumAboutRanges"
+ "Cell.DataTypeDetail.ContributingDatumShowAllDataItem"
+ "Cell.DataTypeDetail.ContributingDatumValue"
+ "Cell.DataTypeDetail.ContributingDatumValueHealthRange"
+ "Cell.DataTypeDetail.ContributingDatumValueRangeSelector"
+ "ContributingDatumAboutMeasure"
+ "ContributingDatumAboutMeasureSection"
+ "ContributingDatumAboutRanges"
+ "ContributingDatumAboutRanges_"
+ "ContributingDatumShowAllData"
+ "ContributingDatumShowAllData_"
+ "ContributingDatumValue"
+ "ContributingDatumValueSection"
+ "ContributingDatumValue_"
+ "ContributingDatumValue_HealthRange"
+ "ContributingDatumValue_RangeSelector"
+ "DerivedLabInputsSection_"
+ "DerivedLabInputs_"
+ "Guidance.DiscussWithYourDoctorAtNextAppointment.Body"
+ "Guidance.DiscussWithYourDoctorAtNextAppointment.Title"
+ "Guidance.DiscussWithYourDoctorIfUnexpected.Body"
+ "Guidance.DiscussWithYourDoctorIfUnexpected.Title"
+ "HOMAIRDataTypeDetailConfigurationProvider"
+ "HOMA_IR_FASTING_LABS_SECTION_TITLE"
+ "HealthRecords.ContributingDatumAboutMeasureDataSource"
+ "HealthRecords.ContributingDatumValueDataSource"
+ "HealthRecords.DerivedLabInputsDataSource"
+ "HealthRecords.HOMAIRDetailLoadingViewController"
+ "HealthRecords/ContributingDatumAboutRangesComponent.swift"
+ "HealthRecords/ContributingDatumClassificationScaleView.swift"
+ "HealthRecords/ContributingDatumLevelBubble.swift"
+ "HealthRecords/ContributingDatumRangePill.swift"
+ "HealthRecords/ContributingDatumRangeSelector.swift"
+ "HealthRecords/ContributingDatumReferenceRangeView.swift"
+ "HealthRecords/ContributingDatumValueComponent.swift"
+ "HealthRecords/DerivedLabInputsComponent.swift"
+ "HealthRecords/HOMAIRDetailLoadingViewController.swift"
+ "HealthRecords/HealthRecordsHealthPluginDelegate+EscalationViewProviding.swift"
+ "HealthRecords/MedicalHistoryDataListViewController.swift"
+ "LAB_RESULT_ESCALATION_DESCRIPTION"
+ "MHRChangeInputSignal"
+ "ProductVersion"
+ "Summaries.healthplugin"
+ "View.task @ HealthRecords/ContributingDatumRangeSelector.swift:"
+ "[%s] Could not query support state: %s"
+ "[%s] Decoded 0 of %ld models; leaving existing feed items in place"
+ "[%s] Failed to fetch the classification scale: %s"
+ "[%s] Failed to load blood glucose classification: %s"
+ "[%s] Preserving %ld feed item(s) whose models failed to decode"
+ "[%s] Skipping concept after fetch failure: %s"
+ "[%s] Unable to resolve HKHealthStore"
+ "[%s] oneTimeShare kind decoded without APPLE_FEATURE_HEALTH_KTC"
+ "[MHRChangeInputSignal] Began observation of MHR changes for %ld types"
+ "[MHRChangeInputSignal] Beginning observation from existing anchor (changeCount: %ld)"
+ "[MHRChangeInputSignal] Beginning observation with new anchor"
+ "[MHRChangeInputSignal] MHR change detected at %f (count: %ld)"
+ "[MHRChangeInputSignal] Observer query error: %s"
+ "[MHRChangeInputSignal] Stopped observation of MHR changes"
+ "continuousShare"
+ "init(arrangedSections:identifier:)"
+ "init(nibName:bundle:)"
+ "isDeterminate"
+ "kCFAllocatorNull"
+ "kind"
+ "mhrChangeTimestamp"
+ "offset element "
+ "oneTimeShare"
+ "r"
+ "title"
- "HealthRecords/BrowseItem.swift"
- "HealthRecords/HealthRecordsPluginAppDelegate+URLHandling.swift"
- "Unable to cast to HKMedicalUserDomainConcept, cannot show detail view"
- "[%s] Began observation of account state changes"
- "[%s] Beginning observation from existing anchor: %s"
- "[%s] Error encoding removed category data: %s"
- "[%s] Error encoding settings data: %s"
- "[%s] Firing initial anchor update to bootstrap generation (timestamp: %f)"
- "[%s] Stopped observation of account state changes"
- "[%s] account state changed at %f: %ld"
- "fetchAllNonStaleAccounts()"
- "healthRecordsSupportedTimestamp"
- "shouldShow supportsHealthRecords "
- "shouldShowHealthRecordsSection()"
```
