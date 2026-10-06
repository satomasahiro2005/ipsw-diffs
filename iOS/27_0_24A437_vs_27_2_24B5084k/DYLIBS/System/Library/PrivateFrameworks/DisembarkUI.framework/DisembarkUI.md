## DisembarkUI

> `/System/Library/PrivateFrameworks/DisembarkUI.framework/DisembarkUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20ac0` | `0x228e0` | **`+0x1e20`** |
| `__AUTH_CONST.__objc_const` | `0x50a8` | `0x5408` | **`+0x360`** |
| `__TEXT.__cstring` | `0x1ea4` | `0x2088` | **`+0x1e4`** |
| `__TEXT.__objc_methlist` | `0x2a38` | `0x2bd0` | **`+0x198`** |
| `__AUTH.__objc_data` | `0xf98` | `0x10c8` | **`+0x130`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b20` | `0x1c50` | **`+0x130`** |
| `__AUTH_CONST.__cfstring` | `0x16c0` | `0x17e0` | **`+0x120`** |
| `__AUTH_CONST.__const` | `0x3e0` | `0x4d0` | **`+0xf0`** |
| `__TEXT.__oslogstring` | `0x1101` | `0x11cf` | **`+0xce`** |
| `__DATA.__data` | `0xaf0` | `0xb80` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x850` | `0x8e0` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x1070` | `0x10d0` | **`+0x60`** |
| `__AUTH.__data` | `0x140` | `0x190` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x1c0` | `0x202` | **`+0x42`** |
| `__DATA_CONST.__got` | `0x4c8` | `0x508` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0xf0` | `0x12c` | **`+0x3c`** |
| `__DATA.__objc_ivar` | `0x2d4` | `0x2f8` | **`+0x24`** |
| `__TEXT.__const` | `0x194` | `0x1b4` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x5d8` | `0x5f0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x180` | `0x198` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x2a4` | `0x2b8` | **`+0x14`** |
| `__DATA_CONST.__objc_protolist` | `0xf0` | `0xf8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xc0` | `0xc8` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x180` | `0x188` | **`+0x8`** |

### Other Changes

```diff

-285.0.0.0.0
+285.1.3.0.0

+  - /System/Library/Frameworks/QuartzCore.framework/QuartzCore

+  - /System/Library/PrivateFrameworks/OSEligibility.framework/OSEligibility

-  Functions: 988
-  Symbols:   1932
-  CStrings:  384
+  Functions: 1055
+  Symbols:   2006
+  CStrings:  403
Symbols:
+ -[DKAnalyticsHandler pendingSanitizeStorageEligible]
+ -[DKAnalyticsHandler pendingSanitizeStorageSelected]
+ -[DKAnalyticsHandler setPendingSanitizeStorageEligible:]
+ -[DKAnalyticsHandler setPendingSanitizeStorageSelected:]
+ -[DKEraseFlow _allowAppSwitching]
+ -[DKEraseFlow _disallowAppSwitching]
+ -[DKEraseFlow _isAppSwitchingAllowedForState:]
+ -[DKEraseFlow captureButtonSuppressionAssertion]
+ -[DKEraseFlow sanitizeStorage]
+ -[DKEraseFlow setCaptureButtonSuppressionAssertion:]
+ -[DKEraseFlow setSanitizeStorage:]
+ -[DKIntroViewController _createSanitizeStorageLearnMoreController]
+ -[DKIntroViewController _createSanitizeStorageRowView]
+ -[DKIntroViewController _presentSanitizeStorageConfirmation:]
+ -[DKIntroViewController sanitizeStorageLearnMoreController]
+ -[DKIntroViewController sanitizeStorageRowView]
+ -[DKIntroViewController setSanitizeStorageLearnMoreController:]
+ -[DKIntroViewController setSanitizeStorageRowView:]
+ -[DKNotableUserData isEligibleForStorageSanitize]
+ -[DKNotableUserData partnerFinancingInformation]
+ -[DKNotableUserData setIsEligibleForStorageSanitize:]
+ -[DKNotableUserData setPartnerFinancingInformation:]
+ -[DKNotableUserDataProvider sanitizeStorageProvider]
+ -[DKNotableUserDataProvider setSanitizeStorageProvider:]
+ -[DKPartnerFinancingConfirmationController initWithPartnerFinancingInformation:canMakePhoneCalls:continueBlock:notNowBlock:]
+ -[DKPartnerFinancingConfirmationController partnerFinancingInformation]
+ -[DKPartnerFinancingConfirmationController setPartnerFinancingInformation:]
+ -[DKSanitizeStorageManager _determineSanitizeStorageEligibility]
+ -[DKSanitizeStorageManager initWithEligibility:]
+ -[DKSanitizeStorageManager init]
+ -[DKSanitizeStorageManager isEligible]
+ -[DKSanitizeStorageManager sanitizeStorageEligible]
+ -[DKSanitizeStorageManager setSanitizeStorageEligible:]
+ _OBJC_CLASS_$_DKPartnerFinancingInformation
+ _OBJC_CLASS_$_DKSanitizeStorageManager
+ _OBJC_CLASS_$_DKSanitizeStorageRowView
+ _OBJC_CLASS_$_OBPrivacyLinkController
+ _OBJC_CLASS_$_OSEligibilityQuery
+ _OBJC_CLASS_$_UISwitch
+ _OBJC_IVAR_$_DKAnalyticsHandler._pendingSanitizeStorageEligible
+ _OBJC_IVAR_$_DKAnalyticsHandler._pendingSanitizeStorageSelected
+ _OBJC_IVAR_$_DKEraseFlow._captureButtonSuppressionAssertion
+ _OBJC_IVAR_$_DKEraseFlow._sanitizeStorage
+ _OBJC_IVAR_$_DKIntroViewController._sanitizeStorageLearnMoreController
+ _OBJC_IVAR_$_DKIntroViewController._sanitizeStorageRowView
+ _OBJC_IVAR_$_DKNotableUserData._isEligibleForStorageSanitize
+ _OBJC_IVAR_$_DKNotableUserData._partnerFinancingInformation
+ _OBJC_IVAR_$_DKNotableUserDataProvider._sanitizeStorageProvider
+ _OBJC_IVAR_$_DKPartnerFinancingConfirmationController._partnerFinancingInformation
+ _OBJC_IVAR_$_DKSanitizeStorageManager._sanitizeStorageEligible
+ _OBJC_METACLASS_$_DKPartnerFinancingInformation
+ _OBJC_METACLASS_$_DKSanitizeStorageManager
+ _OBJC_METACLASS_$_DKSanitizeStorageRowView
+ __DATA_DKPartnerFinancingInformation
+ __DATA_DKSanitizeStorageRowView
+ __INSTANCE_METHODS_DKPartnerFinancingInformation
+ __INSTANCE_METHODS_DKSanitizeStorageRowView
+ __IVARS_DKPartnerFinancingInformation
+ __IVARS_DKSanitizeStorageRowView
+ __METACLASS_DATA_DKPartnerFinancingInformation
+ __METACLASS_DATA_DKSanitizeStorageRowView
+ __OBJC_$_INSTANCE_METHODS_DKSanitizeStorageManager
+ __OBJC_$_INSTANCE_VARIABLES_DKSanitizeStorageManager
+ __OBJC_$_PROP_LIST_DKSanitizeStorageManager
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_DKSanitizeStorageProvider
+ __OBJC_$_PROTOCOL_METHOD_TYPES_DKSanitizeStorageProvider
+ __OBJC_$_PROTOCOL_REFS_DKSanitizeStorageProvider
+ __OBJC_CLASS_PROTOCOLS_$_DKSanitizeStorageManager
+ __OBJC_CLASS_RO_$_DKSanitizeStorageManager
+ __OBJC_LABEL_PROTOCOL_$_DKSanitizeStorageProvider
+ __OBJC_METACLASS_RO_$_DKSanitizeStorageManager
+ __OBJC_PROTOCOL_$_DKSanitizeStorageProvider
+ __PROPERTIES_DKPartnerFinancingInformation
+ __PROPERTIES_DKSanitizeStorageRowView
+ ___54-[DKIntroViewController _createSanitizeStorageRowView]_block_invoke
+ ___54-[DKIntroViewController _createSanitizeStorageRowView]_block_invoke_2
+ ___61-[DKIntroViewController _presentSanitizeStorageConfirmation:]_block_invoke
+ ___61-[DKIntroViewController _presentSanitizeStorageConfirmation:]_block_invoke_2
+ ___block_descriptor_32_e11_v16?0B8B12l
+ ___block_descriptor_40_e8_32s_e11_v16?0B8B12ls32l8
+ ___block_descriptor_48_e8_32s40bs_e39_v16?0"DKPartnerFinancingInformation"8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e27_v16?0"DKNotableUserData"8ls32l8s40l8s48l8
+ _kCACornerCurveContinuous
+ _keypath_get_selector_switchToggled
+ _swift_getWitnessTable
+ _swift_retain
+ _swift_retain_x1
+ _symbolic SbytIegnr_
+ _symbolic So29DKPartnerFinancingInformationCSgIegg_
+ _symbolic So29DKPartnerFinancingInformationCSgIeyBy_
- -[DKEraseFlow _allowHomeButton]
- -[DKEraseFlow _disallowHomeButton]
- -[DKEraseFlow _isHomeButtonAllowedForState:]
- -[DKNotableUserData isPartnerFinancingEnabled]
- -[DKNotableUserData setIsPartnerFinancingEnabled:]
- -[DKPartnerFinancingConfirmationController initWithPartnerFinancingProvider:canMakePhoneCalls:continueBlock:notNowBlock:]
- -[DKPartnerFinancingConfirmationController partnerFinancingProvider]
- -[DKPartnerFinancingConfirmationController setPartnerFinancingProvider:]
- _OBJC_IVAR_$_DKNotableUserData._isPartnerFinancingEnabled
- _OBJC_IVAR_$_DKPartnerFinancingConfirmationController._partnerFinancingProvider
- __IVARS_DKPartnerFinancingManager
- __OBJC_$_PROP_LIST_DKPartnerFinancingProvider
- __PROPERTIES_DKPartnerFinancingManager
- ___block_descriptor_32_e8_v12?0B8l
- ___block_descriptor_49_e8_32s40bs_e27_v16?0"DKNotableUserData"8ls32l8s40l8
- _symbolic So25DKPartnerFinancingManagerC
CStrings:
+ "&"
+ "Allowing capture button use..."
+ "Device eligibility for sanitization: %lu"
+ "Disallowing capture button use..."
+ "DisembarkUI"
+ "DisembarkUI/DKSanitizeStorageRowView.swift"
+ "DisembarkUIModule.DKSanitizeStorageRowView"
+ "DisembarkUI_Private.DKPartnerFinancingInformation"
+ "Failed to determine Sanitize Storage eligibility: %@"
+ "No logo found for: "
+ "OverwriteStorageLearnMore"
+ "SANITIZE_STORAGE"
+ "SANITIZE_STORAGE_CONFIRMATION_ALERT_BUTTON"
+ "SANITIZE_STORAGE_CONFIRMATION_ALERT_MESSAGE"
+ "SANITIZE_STORAGE_CONFIRMATION_ALERT_TITLE"
+ "Somehow attempting to show the partner financing controller with no partner financing information loaded."
+ "Successfully prepared partner financing information"
+ "bundle"
+ "init()"
+ "init(frame:)"
+ "sanitizeStorageEligible"
+ "sanitizeStorageSelected"
+ "self.sanitizeStorageProvider"
+ "v16@?0@\"DKPartnerFinancingInformation\"8"
- "\t"
- " and phone number: "
- "%"
- "Got an app managed features configuration with company: "
- "Missing company name or phone number for partner financing"
```
