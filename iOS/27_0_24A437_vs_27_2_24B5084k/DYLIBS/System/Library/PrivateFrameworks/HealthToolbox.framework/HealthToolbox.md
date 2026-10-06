## HealthToolbox

> `/System/Library/PrivateFrameworks/HealthToolbox.framework/HealthToolbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62eec` | `0x64da0` | **`+0x1eb4`** |
| `__TEXT.__oslogstring` | `0x18c2` | `0x1cf2` | **`+0x430`** |
| `__AUTH_CONST.__objc_const` | `0xb050` | `0xb2b8` | **`+0x268`** |
| `__TEXT.__cstring` | `0x7881` | `0x7a21` | **`+0x1a0`** |
| `__AUTH_CONST.__cfstring` | `0x5440` | `0x55a0` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `0x6f18` | `0x6fe8` | **`+0xd0`** |
| `__AUTH.__objc_data` | `0x2300` | `0x23a0` | **`+0xa0`** |
| `__DATA.__data` | `0xff0` | `0x1050` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x4830` | `0x4868` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0xc00` | `0xc34` | **`+0x34`** |
| `__TEXT.__unwind_info` | `0x19d8` | `0x1a08` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x68c` | `0x6ac` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1938` | `0x1948` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x3e8` | `0x3f8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x710` | `0x708` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xc70` | `0xc68` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x150` | `0x158` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x288` | `0x290` | **`+0x8`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

-  - /System/Library/PrivateFrameworks/ActivityRingsUI.framework/ActivityRingsUI

-  - /System/Library/PrivateFrameworks/FitnessUI.framework/FitnessUI

+  - /System/Library/PrivateFrameworks/HealthFoundationUI.framework/HealthFoundationUI

+  - /usr/lib/swift/libswiftAVFoundation.dylib

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

-  Functions: 2350
-  Symbols:   4517
-  CStrings:  1069
+  Functions: 2380
+  Symbols:   4547
+  CStrings:  1095
Symbols:
+ -[WDBilateralQuantityListDataProvider initWithDisplayType:profile:]
+ -[WDBilateralQuantityListDataProvider sampleTypes]
+ -[WDBilateralQuantityListDataProvider textForObject:]
+ -[WDBilateralQuantityListDataProvider titleForSection:]
+ -[WDBuddyFlowUserInfoViewController buddyFlowUserInfoDidUpdateValue:]
+ -[WDDisplayTypeDataSourcesTableViewController _createHeaderView]
+ -[WDExportManager exportError]
+ -[WDExportManager setExportError:]
+ -[WDHealthReportListDataProvider sampleTypes]
+ -[WDHealthReportListDataProvider textForObject:]
+ -[WDOverheadSquatListDataProvider sampleTypes]
+ -[WDOverheadSquatListDataProvider textForObject:]
+ -[WDProfileTableViewCell _setupDescriptionConstraints]
+ -[WDProfileTableViewCell _syncDisplayValueText]
+ -[WDProfileTableViewCell _updateDescriptionLayout]
+ -[WDProfileTableViewCell descriptionText]
+ -[WDProfileTableViewCell setDescriptionText:]
+ GCC_except_table36
+ GCC_except_table42
+ GCC_except_table63
+ GCC_except_table70
+ GCC_except_table85
+ GCC_except_table96
+ _OBJC_CLASS_$_HKBilateralQuantityType
+ _OBJC_CLASS_$_WDBilateralQuantityListDataProvider
+ _OBJC_CLASS_$_WDHealthReportListDataProvider
+ _OBJC_CLASS_$_WDOverheadSquatListDataProvider
+ _OBJC_IVAR_$_WDExportManager._exportError
+ _OBJC_IVAR_$_WDProfileTableViewCell._accessibilitySizeDescriptionConstraints
+ _OBJC_IVAR_$_WDProfileTableViewCell._activeDescriptionConstraints
+ _OBJC_IVAR_$_WDProfileTableViewCell._descriptionLabel
+ _OBJC_IVAR_$_WDProfileTableViewCell._descriptionText
+ _OBJC_IVAR_$_WDProfileTableViewCell._displayNameCenterYConstraint
+ _OBJC_IVAR_$_WDProfileTableViewCell._displayValueCenterYConstraint
+ _OBJC_IVAR_$_WDProfileTableViewCell._normalSizeDescriptionConstraints
+ _OBJC_METACLASS_$_WDBilateralQuantityListDataProvider
+ _OBJC_METACLASS_$_WDHealthReportListDataProvider
+ _OBJC_METACLASS_$_WDOverheadSquatListDataProvider
+ __OBJC_$_INSTANCE_METHODS_WDBilateralQuantityListDataProvider
+ __OBJC_$_INSTANCE_METHODS_WDHealthReportListDataProvider
+ __OBJC_$_INSTANCE_METHODS_WDOverheadSquatListDataProvider
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_WDBuddyFlowUserInfoDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_WDBuddyFlowUserInfoDelegate
+ __OBJC_$_PROTOCOL_REFS_WDBuddyFlowUserInfoDelegate
+ __OBJC_CLASS_RO_$_WDBilateralQuantityListDataProvider
+ __OBJC_CLASS_RO_$_WDHealthReportListDataProvider
+ __OBJC_CLASS_RO_$_WDOverheadSquatListDataProvider
+ __OBJC_LABEL_PROTOCOL_$_WDBuddyFlowUserInfoDelegate
+ __OBJC_METACLASS_RO_$_WDBilateralQuantityListDataProvider
+ __OBJC_METACLASS_RO_$_WDHealthReportListDataProvider
+ __OBJC_METACLASS_RO_$_WDOverheadSquatListDataProvider
+ __OBJC_PROTOCOL_$_WDBuddyFlowUserInfoDelegate
+ ___61-[WDBuddyFlowUserInfoViewController _saveDataWithCompletion:]_block_invoke_3
+ ___block_descriptor_56_e8_32s40s48s_e56_v36?0"HKWorkoutRouteQuery"8"NSArray"16B24"NSError"28ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40r48r56r_e47_v32?0"HKSampleQuery"8"NSArray"16"NSError"24lr40l8r48l8r56l8s32l8
+ ___block_descriptor_64_e8_32s40s48s56s_e28_v24?0"NSData"8"NSError"16ls32l8s40l8s48l8s56l8
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftAVFoundation_$_HealthToolbox
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftCoreMIDI_$_HealthToolbox
- +[HBXFitnessManager divingFitnessNonGradientTextColor]
- +[HBXFitnessManager fitnessIconFor:]
- +[HBXFitnessManager fitnessNonGradientTextColor]
- GCC_except_table35
- GCC_except_table41
- GCC_except_table62
- GCC_except_table69
- GCC_except_table83
- GCC_except_table95
- _FIUIStaticWorkoutIconImage
- _OBJC_CLASS_$_ARUIMetricColors
- _OBJC_CLASS_$_FIUIWorkoutActivityType
- _OBJC_CLASS_$_HBXFitnessManager
- _OBJC_METACLASS_$_HBXFitnessManager
- _OUTLINED_FUNCTION_5
- __OBJC_$_CLASS_METHODS_HBXFitnessManager
- __OBJC_CLASS_RO_$_HBXFitnessManager
- __OBJC_METACLASS_RO_$_HBXFitnessManager
- ___36-[WDExportManager _writeWorkoutType]_block_invoke_2
- ___38-[WDExportManager _writeAudiogramType]_block_invoke_2
- ___38-[WDExportManager _writeCategoryType:]_block_invoke_2
- ___40-[WDExportManager _writeDataForVisionRx]_block_invoke_2
- ___41-[WDExportManager _writeCorrelationType:]_block_invoke_2
- ___41-[WDExportManager _writeHRVAndTachograms]_block_invoke_2
- ___41-[WDExportManager _writePrescriptionType]_block_invoke_2
- ___42-[WDExportManager _writeActivitySummaries]_block_invoke_2
- ___58-[WDExportManager _writeWorkoutRouteForWorkout:semaphore:]_block_invoke_2
- ___block_descriptor_48_e8_32s40s_e56_v36?0"HKWorkoutRouteQuery"8"NSArray"16B24"NSError"28ls32l8s40l8
- ___block_descriptor_56_e8_32s40r48r_e47_v32?0"HKSampleQuery"8"NSArray"16"NSError"24lr40l8r48l8s32l8
- ___block_descriptor_56_e8_32s40s48s_e28_v24?0"NSData"8"NSError"16ls32l8s40l8s48l8
CStrings:
+ "Attempt to create a bilateral quantity list provider with a non-bilateral quantity data group"
+ "BILATERAL_LEFT_FORMAT_%@"
+ "BILATERAL_NO_DATA"
+ "BILATERAL_RIGHT_FORMAT_%@"
+ "Error appending workout route locations to GPX: %{public}@"
+ "Failed to close archive for export data: %{public}@"
+ "Failed to fetch attachments for vision prescription: %{public}@"
+ "Failed to fetch data for vision prescription attachment %{public}@: %{public}@"
+ "Failed to generate archive for export data: %{public}@"
+ "Failed to write vision prescription attachment data to file: %{public}@"
+ "HealthRecords.healthplugin"
+ "HealthUI-Localizable-Mulberry"
+ "PRESENCE_NOT_PRESENT"
+ "PRESENCE_PRESENT"
+ "Query for activity summaries failed during export attempt: %{public}@"
+ "Query for audiogram samples failed during export attempt: %{public}@"
+ "Query for category type %{public}@ failed during export attempt: %{public}@"
+ "Query for correlation type %{public}@ failed during export attempt: %{public}@"
+ "Query for heart rate variability samples failed during export attempt: %{public}@"
+ "Query for vision prescription samples failed during export attempt: %{public}@"
+ "Query for workout effort score samples failed during export attempt: %{public}@"
+ "Query for workout route samples failed during export attempt: %{public}@"
+ "Query for workout samples failed during export attempt: %{public}@"
+ "Unable to write health record document to file."
+ "Unable to write health record document to file: %{public}@"
+ "Unable to write vision prescription attachment data to file."
```
