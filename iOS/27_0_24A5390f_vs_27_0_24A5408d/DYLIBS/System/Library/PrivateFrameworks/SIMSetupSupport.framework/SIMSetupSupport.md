## SIMSetupSupport

> `/System/Library/PrivateFrameworks/SIMSetupSupport.framework/SIMSetupSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe1ce4` | `0xe337c` | **`+0x1698`** |
| `__AUTH_CONST.__objc_const` | `0x4da98` | `0x4e0c8` | **`+0x630`** |
| `__TEXT.__cstring` | `0x17485` | `0x175c9` | **`+0x144`** |
| `__TEXT.__objc_methlist` | `0xc354` | `0xc474` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x3570` | `0x35c0` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x5de8` | `0x5e38` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x20e8` | `0x2120` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x2f78` | `0x2fa8` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x8acb` | `0x8af5` | **`+0x2a`** |
| `__AUTH_CONST.__cfstring` | `0xab40` | `0xab20` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x12f8` | `0x130c` | **`+0x14`** |
| `__DATA_CONST.__got` | `0xbe8` | `0xbf0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x570` | `0x578` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x510` | `0x518` | **`+0x8`** |
| `__TEXT.__const` | `0x1f8` | `0x1f0` | **`-0x8`** |

### Other Changes

```diff

-968.0.0.0.0
+973.0.0.0.0

-  Functions: 4861
-  Symbols:   7824
-  CStrings:  3108
+  Functions: 4889
+  Symbols:   7864
+  CStrings:  3110
Symbols:
+ +[SSQuickSwitchWaitSourceConsentViewController getTitleAndDetailsForPlanInfos:quickSwitchFlowType:]
+ +[TSUtilities filterQSAccountsWithRestrictedTransferPlan:quickSwitchToTransferPlanMap:]
+ -[SSPRXQuickSwitchPrimarySettingUpViewController initWithQuickSwitchFlowType:stage:secondary:]
+ -[SSPRXQuickSwitchPrimarySettingUpViewController secondary]
+ -[SSPRXQuickSwitchPrimarySettingUpViewController setSecondary:]
+ -[SSPRXQuickSwitchPrimarySettingUpViewController setStage:]
+ -[SSPRXQuickSwitchPrimarySettingUpViewController stage]
+ -[SSQuickSwitchLocalSignOutContent _confirmMessage]
+ -[SSQuickSwitchSecondarySharingViewController tableView:estimatedHeightForRowAtIndexPath:]
+ -[SSQuickSwitchSecondarySharingViewController tableView:heightForRowAtIndexPath:]
+ -[SSQuickSwitchWaitSourceConsentViewController initWithPlanInfos:quickSwitchFlowType:]
+ -[TSCellularPlanActivatingFlow _maybeDismissInteractiveUI:]
+ -[TSCellularPlanActivatingFlow flowCompleted:]
+ -[TSPRXSIMConfigMismatchViewController .cxx_destruct]
+ -[TSPRXSIMConfigMismatchViewController _updateLayoutConstraint]
+ -[TSPRXSIMConfigMismatchViewController delegate]
+ -[TSPRXSIMConfigMismatchViewController goToSettingsAction]
+ -[TSPRXSIMConfigMismatchViewController setDelegate:]
+ -[TSPRXSIMConfigMismatchViewController setGoToSettingsAction:]
+ -[TSPRXSIMConfigMismatchViewController setTriangleImageView:]
+ -[TSPRXSIMConfigMismatchViewController triangleImageView]
+ -[TSPRXSIMConfigMismatchViewController viewDidLoad]
+ -[TSProximitySourceTransferFlow _handlePlanDisabledInCurrentSimConfig]
+ -[TSProximitySourceTransferFlow isPlanDisabledInCurrentSimConfig]
+ -[TSProximitySourceTransferFlow setIsPlanDisabledInCurrentSimConfig:]
+ GCC_except_table134
+ GCC_except_table138
+ GCC_except_table144
+ GCC_except_table152
+ GCC_except_table153
+ GCC_except_table160
+ GCC_except_table168
+ GCC_except_table205
+ GCC_except_table213
+ GCC_except_table215
+ GCC_except_table217
+ _OBJC_CLASS_$_TSPRXSIMConfigMismatchViewController
+ _OBJC_IVAR_$_SSPRXQuickSwitchPrimarySettingUpViewController._secondary
+ _OBJC_IVAR_$_SSPRXQuickSwitchPrimarySettingUpViewController._stage
+ _OBJC_IVAR_$_TSPRXSIMConfigMismatchViewController._delegate
+ _OBJC_IVAR_$_TSPRXSIMConfigMismatchViewController._goToSettingsAction
+ _OBJC_IVAR_$_TSPRXSIMConfigMismatchViewController._triangleImageView
+ _OBJC_IVAR_$_TSProximitySourceTransferFlow._isPlanDisabledInCurrentSimConfig
+ _OBJC_METACLASS_$_TSPRXSIMConfigMismatchViewController
+ __OBJC_$_CLASS_METHODS_SSQuickSwitchWaitSourceConsentViewController
+ __OBJC_$_INSTANCE_METHODS_TSPRXSIMConfigMismatchViewController
+ __OBJC_$_INSTANCE_VARIABLES_TSPRXSIMConfigMismatchViewController
+ __OBJC_$_PROP_LIST_TSPRXSIMConfigMismatchViewController
+ __OBJC_CLASS_PROTOCOLS_$_TSPRXSIMConfigMismatchViewController
+ __OBJC_CLASS_RO_$_TSPRXSIMConfigMismatchViewController
+ __OBJC_METACLASS_RO_$_TSPRXSIMConfigMismatchViewController
+ ___103-[TSCellularPlanActivatingFlow(CoreTelephonyClientCellularPlanManagementDelegate) transferEventUpdate:]_block_invoke
+ ___51-[TSPRXSIMConfigMismatchViewController viewDidLoad]_block_invoke
+ ___70-[TSProximitySourceTransferFlow _handlePlanDisabledInCurrentSimConfig]_block_invoke
+ ___87+[TSUtilities filterQSAccountsWithRestrictedTransferPlan:quickSwitchToTransferPlanMap:]_block_invoke
- -[SSQuickSwitchLocalSignOutContent _confirmTitle]
- -[SSQuickSwitchSecondarySharingViewController _heightAnchorConstant]
- -[SSQuickSwitchWaitSourceConsentViewController initWithPlanInfos:]
- GCC_except_table130
- GCC_except_table136
- GCC_except_table141
- GCC_except_table149
- GCC_except_table150
- GCC_except_table157
- GCC_except_table165
- GCC_except_table199
- GCC_except_table210
- GCC_except_table212
- GCC_except_table214
- _OBJC_IVAR_$_SSQuickSwitchSecondarySharingViewController._tableHeightAnchor
CStrings:
+ "-[TSProximitySourceTransferFlow _handlePlanDisabledInCurrentSimConfig]"
+ "-[TSProximitySourceTransferFlow _handlePlanDisabledInCurrentSimConfig]_block_invoke"
+ "FindMyWipe: no Secondary SIMs paired with %@ @%s"
+ "FindMyWipe: no number sharing infos @%s"
+ "INTERMEDIATE_TRANSFER_PLAN_ITEM_SUBTITLE_BUDDY"
+ "INTERMEDIATE_TRANSFER_PLAN_ITEM_SUBTITLE_BUDDY_@"
+ "IPHONE_HANDOFF"
+ "NETWORK_ACCESS_LABEL_TITLE"
+ "PLAN_DISABLED_IN_CURRENT_SIM_CONFIG_DETAIL_SOURCE"
+ "PLAN_DISABLED_IN_CURRENT_SIM_CONFIG_DETAIL_TARGET"
+ "PLAN_DISABLED_IN_CURRENT_SIM_CONFIG_TITLE_SOURCE"
+ "PLAN_DISABLED_IN_CURRENT_SIM_CONFIG_TITLE_TARGET"
+ "QS_COMPLETE_TITLE"
+ "QS_DEVICE_PICKER_OPTION_SUBTITLE_%@"
+ "QS_DEVICE_PICKER_OPTION_TITLE_%@"
+ "QS_ENROLLED_ESIM_TRANSFER_ALERT_BODY_%@"
+ "QS_ENROLLED_ESIM_TRANSFER_ALERT_TITLE"
+ "QS_ENROLLED_TRANSFER_ESIM_DETAILS_SINGLE_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_CONFIRM_MESSAGE_%@_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_CONFIRM_MESSAGE_FALLBACK_DEVICE_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_CONFIRM_MESSAGE_FALLBACK_PHONE_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_CONFIRM_MESSAGE_FALLBACK_PHONE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_CONFIRM_MESSAGE_PLURAL_%@_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_CONFIRM_MESSAGE_PLURAL_FALLBACK_DEVICES_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_CONFIRM_MESSAGE_PLURAL_FALLBACK_DEVICE_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_CONFIRM_MESSAGE_PLURAL_FALLBACK_PHONE_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_CONFIRM_MESSAGE_PLURAL_FALLBACK_PHONE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_CONFIRM_MESSAGE_PLURAL_FALLBACK_PHONE_FALLBACK_DEVICES"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_SECONDARY_ADVICE_MIXED"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_SECONDARY_ADVICE_MIXED_PLURAL"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_MESSAGE_%@"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_MESSAGE_FALLBACK_PHONE"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_MESSAGE_PLURAL_%@"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_MESSAGE_PLURAL_FALLBACK_PHONE"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_TITLE"
+ "QS_PROGRESS_PREPARING"
+ "QS_PROGRESS_SETTING_UP"
+ "QS_PROGRESS_TRANSFERRING"
+ "QS_PRX_OLD_TRANSFER_SUCCESS_BODY_%@_%@_%@"
+ "QS_PRX_OLD_TRANSFER_SUCCESS_BODY_NO_COMPANION_%@_%@"
+ "QS_PRX_OLD_TRANSFER_SUCCESS_BODY_NO_NUMBER_%@_%@"
+ "QS_PRX_OLD_TRANSFER_SUCCESS_BODY_NO_NUMBER_NO_COMPANION_%@"
+ "QS_SECURE_INTENT_ENROLL_BODY"
+ "QS_SECURE_INTENT_ENROLL_TITLE"
+ "QS_SECURE_INTENT_TRANSFER_BODY"
+ "QS_SECURE_INTENT_TRANSFER_TITLE"
+ "QS_SETTING_UP_DETAILS_%@"
+ "QS_SHARE_ESIM_OPTION_TITLE"
+ "QS_TRANSFERRING_ESIM_DETAILS"
+ "QS_TRANSFERRING_ESIM_DETAILS_%@"
+ "QS_TRANSFERRING_ESIM_TITLE"
+ "QS_TRANSFER_NEW_SUCCESS_BODY_%@_%@"
+ "QS_TRANSFER_NEW_SUCCESS_BODY_NO_COMPANION_%@"
+ "QS_TRANSFER_NEW_SUCCESS_BODY_NO_NUMBER_%@"
+ "QS_TRANSFER_NEW_SUCCESS_BODY_NO_NUMBER_NO_COMPANION"
+ "QS_WAIT_SOURCE_CONSENT_DEVICENAME_DETAILS_%@"
+ "QS_WAIT_SOURCE_CONSENT_DEVICENAME_TITLE_%@"
+ "QS_WAIT_SOURCE_CONSENT_ENROLL_DETAILS"
+ "QS_WAIT_SOURCE_CONSENT_ENROLL_DEVICENAME_DETAILS_%@"
+ "QUICK_SWITCH_OLD_TRANSFER_SUCCESS_TITLE"
+ "TRANSFER_PLAN_ITEM_TITLE_WHEN_QS_OPTION_PRESENT"
+ "[E]FindMyWipe: failed to get number sharing info: %@ @%s"
+ "[E]cannot transfer plan - source device is in an incompatible SIM configuration @%s"
- "AUTOMATIC_NUMBER_SWITCHING"
- "FindMyWipe: no Secondary SIMs on this device for serial %@ @%s"
- "FindMyWipe: no number sharing infos for serial %@ @%s"
- "NETWORK_ACCESS_IDENTIFIER_TITLE"
- "QS_ACTIVATING_DETAILS"
- "QS_ACTIVATING_TITLE"
- "QS_COMPANION_ESIM_TRANSFER_ALERT_BODY_%@_%@"
- "QS_COMPANION_ESIM_TRANSFER_ALERT_BODY_NO_PHONENUMBER_%@"
- "QS_COMPANION_ESIM_TRANSFER_ALERT_TITLE"
- "QS_DEVICE_PICKER_MAIN_TEXT_%@"
- "QS_DEVICE_PICKER_SUB_TEXT_COMPANION_ESIM_%@"
- "QS_DEVICE_PICKER_SUB_TEXT_MAIN_ESIM_%@"
- "QS_IN_PROGRESS"
- "QS_LIFECYCLE_EACS_DELETE_ESIM_PRIMARY_IMPACT_PLURAL_FALLBACK_DEVICES_%@"
- "QS_LIFECYCLE_EACS_DELETE_ESIM_PRIMARY_IMPACT_PLURAL_FALLBACK_PHONE_FALLBACK_DEVICES"
- "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_MESSAGE_WIFI"
- "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_MESSAGE_WLAN"
- "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_TITLE_%@"
- "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_TITLE_FALLBACK_PHONE"
- "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_TITLE_PLURAL_%@"
- "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_TITLE_PLURAL_FALLBACK_PHONE"
- "QS_MAIN_ESIM_TRANSFER_ALERT_BODY_%@_%@"
- "QS_MAIN_ESIM_TRANSFER_ALERT_BODY_NO_PHONENUMBER_%@"
- "QS_MAIN_ESIM_TRANSFER_ALERT_TITLE"
- "QS_PLAN_DISABLED_IN_CURRENT_SIM_CONFIG_DETAIL"
- "QS_PLAN_DISABLED_IN_CURRENT_SIM_CONFIG_TITLE"
- "QS_PRIMARY_SETTING_UP_TITLE"
- "QS_PRX_TRANSFERRING_DETAILS"
- "QS_PRX_TRANSFERRING_TITLE"
- "QS_PRX_TRANSFER_SUCCESS_COMPANION_SUBTITLE_%@_%@_%@"
- "QS_PRX_TRANSFER_SUCCESS_COMPANION_SUBTITLE_NO_MAIN_%@_%@"
- "QS_PRX_TRANSFER_SUCCESS_COMPANION_SUBTITLE_NO_MAIN_NO_NUMBER_%@"
- "QS_PRX_TRANSFER_SUCCESS_COMPANION_SUBTITLE_NO_NUMBER_%@_%@"
- "QS_PRX_TRANSFER_SUCCESS_MAIN_SUBTITLE_%@_%@_%@"
- "QS_PRX_TRANSFER_SUCCESS_MAIN_SUBTITLE_NO_COMPANION_%@_%@"
- "QS_PRX_TRANSFER_SUCCESS_MAIN_SUBTITLE_NO_COMPANION_NO_NUMBER_%@"
- "QS_PRX_TRANSFER_SUCCESS_MAIN_SUBTITLE_NO_NUMBER_%@_%@"
- "QS_SHARE_ESIM_DETAILS_QS_ALREADY_ENROLLED_%@"
- "QS_SHARE_ESIM_DETAILS_QS_ALREADY_ENROLLED_NO_NUMBER"
- "QS_SHARE_ESIM_TITLE"
- "QS_SHARE_PHONE_NUMBER_SINGLE_PRIMARY_DETAIL_%@_%@_%@"
- "QS_SHARE_PHONE_NUMBER_SINGLE_SECONDARY_DETAIL_%@_%@_%@"
- "QS_TRANSFERRING_DETAILS"
- "QS_TRANSFERRING_TITLE"
- "QS_TRANSFER_COMPANION_COMPLETE_DETAIL_%@"
- "QS_TRANSFER_COMPANION_COMPLETE_DETAIL_NO_NUMBER"
- "QS_TRANSFER_ESIM_DETAILS_%@"
- "QS_TRANSFER_ESIM_DETAILS_NO_NUMBER"
- "QS_TRANSFER_IN_PROGRESS"
- "QS_TRANSFER_MAIN_COMPLETE_DETAIL_%@"
- "QS_TRANSFER_MAIN_COMPLETE_DETAIL_NO_NUMBER"
- "QUICK_SWITCH_CONFIRM_TITLE"
- "QUICK_SWITCH_DOUBLE_CLICK_SIDE_BUTTON"
- "QUICK_SWITCH_PRIMARY_COMPLETE_SUCCESS_TITLE"
- "QUICK_SWITCH_PRIMARY_SHARING_SUBTITLE"
- "QUICK_SWITCH_PRIMARY_TRANSFER_SUCCESS_TITLE"
- "QUICK_SWITCH_SHARING_IN_PROGRESS"
- "QUICK_SWITCH_SLIDING_CONFIRM_TITLE"
- "QUICK_SWITCH_TRANSFER_SUBTITLE_NO_NUMBER"
- "Your carrier"
- "[E]FindMyWipe: failed to get number sharing info for serial %@: %@ @%s"
```
