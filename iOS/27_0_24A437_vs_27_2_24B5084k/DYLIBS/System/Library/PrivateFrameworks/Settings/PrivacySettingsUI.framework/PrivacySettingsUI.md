## PrivacySettingsUI

> `/System/Library/PrivateFrameworks/Settings/PrivacySettingsUI.framework/PrivacySettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x67720` | `0x69b40` | **`+0x2420`** |
| `__TEXT.__cstring` | `0x8334` | `0x85d4` | **`+0x2a0`** |
| `__AUTH_CONST.__objc_const` | `0x65e8` | `0x6850` | **`+0x268`** |
| `__AUTH_CONST.__cfstring` | `0x6f80` | `0x71e0` | **`+0x260`** |
| `__TEXT.__oslogstring` | `0x2c60` | `0x2e70` | **`+0x210`** |
| `__TEXT.__objc_methlist` | `0x428c` | `0x442c` | **`+0x1a0`** |
| `__DATA_CONST.__objc_selrefs` | `0x3380` | `0x3460` | **`+0xe0`** |
| `__AUTH.__objc_data` | `0x1780` | `0x1820` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x1838` | `0x18b0` | **`+0x78`** |
| `__TEXT.__gcc_except_tab` | `0x12b0` | `0x130c` | **`+0x5c`** |
| `__AUTH_CONST.__const` | `0xa70` | `0xab0` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x470` | `0x490` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1b28` | `0x1b48` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xa80` | `0xa98` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xac8` | `0xad8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x240` | `0x250` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x1d8` | `0x1e8` | **`+0x10`** |
| `__TEXT.__const` | `0x524` | `0x534` | **`+0x10`** |
| `__DATA.__data` | `0x5f8` | `0x600` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x53a` | `0x542` | **`+0x8`** |

### Other Changes

```diff

-2027.0.6.104.0
+2027.1.5.1.100

-  Functions: 2131
-  Symbols:   3702
-  CStrings:  1408
+  Functions: 2176
+  Symbols:   3773
+  CStrings:  1441
Symbols:
+ +[PUIMotionSensorsAppPickerController installedApplicationsExcludingBundleIDs:]
+ -[PUIMotionFitnessController dealloc]
+ -[PUIMotionFitnessController reloadRestrictedAccessSpecifiers]
+ -[PUIMotionFitnessController restrictedAccessGroupSpecifiers]
+ -[PUIMotionFitnessController startObservingMotionSensorsEligibilityChanges]
+ -[PUIMotionFitnessController stopObservingMotionSensorsEligibilityChanges]
+ -[PUIMotionFitnessController viewWillAppear:]
+ -[PUIMotionFitnessController viewWillDisappear:]
+ -[PUIMotionSensorsAppPickerController .cxx_destruct]
+ -[PUIMotionSensorsAppPickerController allApps]
+ -[PUIMotionSensorsAppPickerController cancelButtonTapped]
+ -[PUIMotionSensorsAppPickerController completionHandler]
+ -[PUIMotionSensorsAppPickerController doneButtonTapped]
+ -[PUIMotionSensorsAppPickerController initWithExcludedBundleIDs:]
+ -[PUIMotionSensorsAppPickerController selectedBundleIDs]
+ -[PUIMotionSensorsAppPickerController setAllApps:]
+ -[PUIMotionSensorsAppPickerController setCompletionHandler:]
+ -[PUIMotionSensorsAppPickerController setSelectedBundleIDs:]
+ -[PUIMotionSensorsAppPickerController tableView:cellForRowAtIndexPath:]
+ -[PUIMotionSensorsAppPickerController tableView:didSelectRowAtIndexPath:]
+ -[PUIMotionSensorsAppPickerController tableView:numberOfRowsInSection:]
+ -[PUIMotionSensorsRestrictController dealloc]
+ -[PUIMotionSensorsRestrictController presentRestrictedAppPicker]
+ -[PUIMotionSensorsRestrictController reloadRestrictedApps]
+ -[PUIMotionSensorsRestrictController restrictedAppBundleIDs]
+ -[PUIMotionSensorsRestrictController specifiers]
+ -[PUIMotionSensorsRestrictController startObservingAccessChanges]
+ -[PUIMotionSensorsRestrictController stopObservingAccessChanges]
+ -[PUIMotionSensorsRestrictController tableView:canEditRowAtIndexPath:]
+ -[PUIMotionSensorsRestrictController tableView:commitEditingStyle:forRowAtIndexPath:]
+ -[PUIMotionSensorsRestrictController viewDidLoad]
+ -[PUIMotionSensorsRestrictController viewWillAppear:]
+ -[PUIMotionSensorsRestrictController viewWillDisappear:]
+ _OBJC_CLASS_$_PUIMotionSensorsAppPickerController
+ _OBJC_CLASS_$_PUIMotionSensorsRestrictController
+ _OBJC_CLASS_$_UITableViewCell
+ _OBJC_CLASS_$_UITableViewController
+ _OBJC_IVAR_$_PUIMotionFitnessController._eligibilityChangedNotifyToken
+ _OBJC_IVAR_$_PUIMotionFitnessController._observingMotionSensorsEligibilityChanges
+ _OBJC_IVAR_$_PUIMotionSensorsAppPickerController._allApps
+ _OBJC_IVAR_$_PUIMotionSensorsAppPickerController._completionHandler
+ _OBJC_IVAR_$_PUIMotionSensorsAppPickerController._selectedBundleIDs
+ _OBJC_IVAR_$_PUIMotionSensorsRestrictController._accessChangedNotifyToken
+ _OBJC_IVAR_$_PUIMotionSensorsRestrictController._ignoringNextAccessChangedNotification
+ _OBJC_IVAR_$_PUIMotionSensorsRestrictController._observingAccessChanges
+ _OBJC_METACLASS_$_PUIMotionSensorsAppPickerController
+ _OBJC_METACLASS_$_PUIMotionSensorsRestrictController
+ _OBJC_METACLASS_$_UITableViewController
+ _PUIIsDataLinkingTerminologyEligible
+ _TCCAccessResetForBundleId
+ __OBJC_$_CLASS_METHODS_PUIMotionSensorsAppPickerController
+ __OBJC_$_INSTANCE_METHODS_PUIMotionSensorsAppPickerController
+ __OBJC_$_INSTANCE_METHODS_PUIMotionSensorsRestrictController
+ __OBJC_$_INSTANCE_VARIABLES_PUIMotionSensorsAppPickerController
+ __OBJC_$_INSTANCE_VARIABLES_PUIMotionSensorsRestrictController
+ __OBJC_$_PROP_LIST_PUIMotionSensorsAppPickerController
+ __OBJC_CLASS_RO_$_PUIMotionSensorsAppPickerController
+ __OBJC_CLASS_RO_$_PUIMotionSensorsRestrictController
+ __OBJC_METACLASS_RO_$_PUIMotionSensorsAppPickerController
+ __OBJC_METACLASS_RO_$_PUIMotionSensorsRestrictController
+ ___48-[PUIMotionSensorsRestrictController specifiers]_block_invoke
+ ___55-[PUIMotionSensorsAppPickerController doneButtonTapped]_block_invoke
+ ___64-[PUIMotionSensorsRestrictController presentRestrictedAppPicker]_block_invoke
+ ___65-[PUIMotionSensorsAppPickerController initWithExcludedBundleIDs:]_block_invoke
+ ___65-[PUIMotionSensorsAppPickerController initWithExcludedBundleIDs:]_block_invoke_2
+ ___65-[PUIMotionSensorsRestrictController startObservingAccessChanges]_block_invoke
+ ___75-[PUIMotionFitnessController startObservingMotionSensorsEligibilityChanges]_block_invoke
+ ___79+[PUIMotionSensorsAppPickerController installedApplicationsExcludingBundleIDs:]_block_invoke
+ ___79+[PUIMotionSensorsAppPickerController installedApplicationsExcludingBundleIDs:]_block_invoke_2
+ ___block_descriptor_32_e51_q24?0"LSApplicationProxy"8"LSApplicationProxy"16l
+ _kTCCServiceMotionSensors
+ _symbolic _____Sg 12FindMyLocate12ClientTargetV
- -[PUIMotionFitnessController _appSpecifiers]
CStrings:
+ "### Failed to determine Motion Sensors restrict eligibility: %d"
+ "### Failed to register for Motion Sensors eligibility change notifications: %u"
+ "%s: cannot determine OGANESSON eligibility, error: %d"
+ "ALLOW_ASK_ALT"
+ "APP_TRACKING_HEADER_TEXT_ALT"
+ "AUTOMATED_FEEDBACK"
+ "AUTOMATED_FEEDBACK_FOOTER"
+ "AUTOMATED_FEEDBACK_GROUP"
+ "AUTOMATED_FEEDBACK_LINK"
+ "DISABLE_ALLOW_ASK_LEAVE_APPS_ON_ALT"
+ "DISABLE_ALLOW_ASK_MESSAGE_ALT"
+ "DISABLE_ALLOW_ASK_TURN_OFF_APPS_ALT"
+ "DLT: Cannot determine eligibility due to error: %d"
+ "DLT: Unable to determine eligibility "
+ "DLT: User is eligible"
+ "DLT: User is not eligible"
+ "MOTION_SENSORS_DATA_TITLE"
+ "MOTION_SENSORS_PICKER_TITLE"
+ "MOTION_SENSORS_RESTRICT_EXPLANATION_GROUP"
+ "MOTION_SENSORS_RESTRICT_FOOTER"
+ "MOTION_SENSORS_RESTRICT_GROUP"
+ "MotionSensors failed to register for access-changed notifications: %u"
+ "MotionSensors failed to write restriction for bundle ID: %@"
+ "MotionSensors restrict list skipping unresolved bundle ID: %@"
+ "PUIMotionSensorsAppBundleIDKey"
+ "PUIMotionSensorsAppPickerCell"
+ "TRACKERS_ALT"
+ "TRACKING_HEADER_ALT"
+ "automatedFeedbackLinkTapped"
+ "com.apple.os-eligibility-domain.change.cicindela"
+ "com.apple.tcc.access.changed"
+ "isGreenTeaSKU_block_invoke"
+ "q24@?0@\"LSApplicationProxy\"8@\"LSApplicationProxy\"16"
+ "telephony"
- "green-tea"
```
