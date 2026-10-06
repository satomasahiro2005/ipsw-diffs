## SIMSetupSupport

> `/System/Library/PrivateFrameworks/SIMSetupSupport.framework/SIMSetupSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe0d58` | `0xe1ce4` | **`+0xf8c`** |
| `__AUTH_CONST.__objc_const` | `0x4d458` | `0x4da98` | **`+0x640`** |
| `__AUTH_CONST.__cfstring` | `0xa8c0` | `0xab40` | **`+0x280`** |
| `__TEXT.__cstring` | `0x172cc` | `0x17485` | **`+0x1b9`** |
| `__TEXT.__objc_methlist` | `0xc284` | `0xc354` | **`+0xd0`** |
| `__DATA_DIRTY.__objc_data` | `0x50` | `0xf0` | **`+0xa0`** |
| `__AUTH.__objc_data` | `0x35c0` | `0x3570` | **`-0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x5d98` | `0x5de8` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x20e8` | `0x2128` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x8a8d` | `0x8acb` | **`+0x3e`** |
| `__TEXT.__unwind_info` | `0x2f40` | `0x2f78` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0x12dc` | `0x12f8` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0xbe0` | `0xbe8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x568` | `0x570` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x508` | `0x510` | **`+0x8`** |
| `__TEXT.__const` | `0x1f0` | `0x1f8` | **`+0x8`** |

### Other Changes

```diff

-964.0.0.0.0
+968.0.0.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 4843
-  Symbols:   7787
-  CStrings:  3085
+  Functions: 4861
+  Symbols:   7824
+  CStrings:  3108
Symbols:
+ -[SSQuickSwitchSecondaryEnrollmentFlow _buildQSMetricPayload]
+ -[SSQuickSwitchSecondaryEnrollmentFlow flowCompleted:]
+ -[TSDeviceInfoViewController _continueTapped]
+ -[TSDeviceInfoViewController detailTextForSharingIdentitySupported:nalPresent:]
+ -[TSDeviceInfoViewController didConfirmSetup]
+ -[TSDeviceInfoViewController orderedInfoKeys]
+ -[TSESIMSetupConfirmationViewController .cxx_destruct]
+ -[TSESIMSetupConfirmationViewController _continueButtonTapped]
+ -[TSESIMSetupConfirmationViewController delegate]
+ -[TSESIMSetupConfirmationViewController init]
+ -[TSESIMSetupConfirmationViewController setDelegate:]
+ -[TSESIMSetupConfirmationViewController viewDidLoad]
+ -[TSESIMSetupConfirmationViewController(TSSetupFlowItem) prepare:]
+ -[TSIdentityShareFlow viewControllerDidComplete:]
+ -[TSPRXIdentityShareViewController setShareDeviceInfoInPurpleBuddy:]
+ -[TSPRXIdentityShareViewController shareDeviceInfoInPurpleBuddy]
+ _AnalyticsSendEventLazy
+ _CTPlanTransferStatusQSReverseProvisioningSkipped
+ _OBJC_CLASS_$_TSESIMSetupConfirmationViewController
+ _OBJC_IVAR_$_SSQuickSwitchSecondaryEnrollmentFlow._metricUserChoice
+ _OBJC_IVAR_$_TSDeviceInfoViewController._continueButton
+ _OBJC_IVAR_$_TSDeviceInfoViewController._deviceInfo
+ _OBJC_IVAR_$_TSDeviceInfoViewController._didConfirmSetup
+ _OBJC_IVAR_$_TSDeviceInfoViewController._showCarrierConfirmContinue
+ _OBJC_IVAR_$_TSESIMSetupConfirmationViewController._continueButton
+ _OBJC_IVAR_$_TSESIMSetupConfirmationViewController._delegate
+ _OBJC_IVAR_$_TSPRXIdentityShareViewController._shareDeviceInfoInPurpleBuddy
+ _OBJC_METACLASS_$_TSESIMSetupConfirmationViewController
+ _TSUserInfoNalKey
+ _TSUserInfoShareDeviceInfoInSetupKey
+ __OBJC_$_INSTANCE_METHODS_TSESIMSetupConfirmationViewController(TSSetupFlowItem)
+ __OBJC_$_INSTANCE_VARIABLES_TSESIMSetupConfirmationViewController
+ __OBJC_$_PROP_LIST_TSESIMSetupConfirmationViewController
+ __OBJC_CLASS_PROTOCOLS_$_TSESIMSetupConfirmationViewController
+ __OBJC_CLASS_RO_$_TSESIMSetupConfirmationViewController
+ __OBJC_METACLASS_RO_$_TSESIMSetupConfirmationViewController
+ ___54-[SSQuickSwitchSecondaryEnrollmentFlow flowCompleted:]_block_invoke
+ ___block_descriptor_40_e8_32s_e19_"NSDictionary"8?0ls32l8
- _OBJC_IVAR_$_TSDeviceInfoViewController._sortedInfo
CStrings:
+ "@\"NSDictionary\"8@?0"
+ "CTPlanTransferStatusQSReverseProvisioningSkipped"
+ "ESIM_IN_STORE_SIGNUP_NAL_BUTTON"
+ "ESIM_IN_STORE_SIGNUP_NAL_DETAIL"
+ "ESIM_SETUP_CONFIRM_DETAIL"
+ "ESIM_SETUP_CONFIRM_TITLE"
+ "NETWORK_ACCESS_IDENTIFIER_TITLE"
+ "NalKey"
+ "ShareDeviceInfoInSetupKey"
+ "[E]Failed to query activateForEsimSetupInBuddy: %@ @%s"
+ "[I] Updating plan info: CTPlanTransferStatusQSReverseProvisioningSkipped. Current VC: %@ @%s"
+ "cancelled"
+ "com.apple.Telephony.quickSwitchEnrollmentFlow"
+ "cross_platform"
+ "in_buddy"
+ "number_qs_already_enrolled"
+ "number_qs_capable_sims"
+ "other"
+ "proximity"
+ "quickswitch"
+ "scan"
+ "transfer"
+ "unknown"
+ "user_choice"
- "[I] Updating plan info: CTPlanTransferStatusTimeoutInstallOngoing. Current VC: %@ @%s"
```
