## AppSystemSettingsUI

> `/System/Library/PrivateFrameworks/AppSystemSettingsUI.framework/AppSystemSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x45f28` | `0x46864` | **`+0x93c`** |
| `__TEXT.__cstring` | `0x33cc` | `0x32fc` | **`-0xd0`** |
| `__TEXT.__swift5_typeref` | `0x20f8` | `0x205e` | **`-0x9a`** |
| `__AUTH_CONST.__const` | `0xfe8` | `0x1078` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0xcc0` | `0xd38` | **`+0x78`** |
| `__DATA_CONST.__const` | `0x4d0` | `0x540` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x11c0` | `0x1200` | **`+0x40`** |
| `__TEXT.__const` | `0x1b98` | `0x1bd8` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xf28` | `0xf68` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x45c` | `0x490` | **`+0x34`** |
| `__TEXT.__oslogstring` | `0xb55` | `0xb85` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x334` | `0x360` | **`+0x2c`** |
| `__AUTH_CONST.__objc_const` | `0x1e88` | `0x1ea8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xfcc` | `0xfec` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x607` | `0x627` | **`+0x20`** |
| `__DATA.__bss` | `0x9d0` | `0x9e0` | **`+0x10`** |
| `__DATA.__data` | `0x9e8` | `0x9f8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x8a8` | `0x8b8` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x7a0` | `0x790` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x49c` | `0x4a8` | **`+0xc`** |
| `__AUTH.__data` | `0x2d0` | `0x2d8` | **`+0x8`** |
| `__AUTH.__objc_data` | `0x6e0` | `0x6e8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x88` | `0x8c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x3c` | `0x40` | **`+0x4`** |

### Other Changes

```diff

-2027.0.4.0.0
+2027.0.7.0.0

+  - /System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeCore

-  Functions: 1247
-  Symbols:   1266
-  CStrings:  426
+  Functions: 1268
+  Symbols:   1277
+  CStrings:  423
Symbols:
+ -[AUSystemSettingsSpecifiersProvider _disableFamilyControlsForRecord:]
+ -[AUSystemSettingsSpecifiersProvider _disableFamilyControlsWithScreenTimePinPrompt:]
+ -[AUSystemSettingsSpecifiersProvider _shouldPromptScreentimePasscodeForRecord:]
+ GCC_except_table101
+ GCC_except_table117
+ GCC_except_table122
+ GCC_except_table53
+ GCC_except_table66
+ GCC_except_table83
+ GCC_except_table84
+ _OBJC_CLASS_$_STCommunicationClient
+ _OBJC_CLASS_$_STManagementState
+ ___70-[AUSystemSettingsSpecifiersProvider _disableFamilyControlsForRecord:]_block_invoke
+ ___84-[AUSystemSettingsSpecifiersProvider _disableFamilyControlsWithScreenTimePinPrompt:]_block_invoke
+ ___84-[AUSystemSettingsSpecifiersProvider _disableFamilyControlsWithScreenTimePinPrompt:]_block_invoke_2
+ ___84-[AUSystemSettingsSpecifiersProvider _disableFamilyControlsWithScreenTimePinPrompt:]_block_invoke_3
+ ___block_descriptor_32_e20_v20?0B8"NSError"12l
+ ___block_descriptor_56_e8_32s40s48w_e44_v24?0"STAuthenticationResult"8"NSError"16ls32l8s40l8w48l8
+ ___block_descriptor_56_e8_32s40s48w_e5_v8?0ls32l8s40l8w48l8
+ _get_witness_table qd0__7SwiftUI4ViewHD5_AaBPAAE5alert_11isPresented7actions7messageQrqd___AA7BindingVySbGqd_0_yXEqd_1_yXEtSyRd__AaBRd_0_AaBRd_1_r1_lFQOyAcAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAA15ModifiedContentVyAA6ToggleVyAA05TupleO0VyAA4TextV_AUSgQPGGAA32_EnvironmentKeyTransformModifierVySbGG_SbQo__10Foundation4UUIDVSgQo__SbSgQo__So29CTLazuliRegistrationStateTypeVSgQo__A5_Qo__SSASyAA6ButtonVyAUG_A16_QPGAUQo_HO
+ _keypath_set.16Tm
+ _symbolic _____y_____y_____y_____y_____y_____y_____y_____y_____y______ADSgQPGG_____ySbGG_SbQo_______SgQo__SbSgQo_______SgQo__AMQo__SSACy_____yADG_AVQPGADQo_ 7SwiftUI4ViewPAAE5alert_11isPresented7actions7messageQrqd___AA7BindingVySbGqd_0_yXEqd_1_yXEtSyRd__AaBRd_0_AaBRd_1_r1_lFQO AcAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA15ModifiedContentV AA6ToggleV AA05TupleO0V AA4TextV AA32_EnvironmentKeyTransformModifierV 10Foundation4UUIDV So29CTLazuliRegistrationStateTypeV AA6ButtonV
- GCC_except_table111
- GCC_except_table116
- GCC_except_table60
- GCC_except_table77
- GCC_except_table78
- GCC_except_table95
- ___76-[AUSystemSettingsSpecifiersProvider setFamilyControlsEnabled:forSpecifier:]_block_invoke_2
- _get_witness_table qd0__7SwiftUI4ViewHD5_AaBPAAE5alert_11isPresented7actions7messageQrqd___AA7BindingVySbGqd_0_yXEqd_1_yXEtSyRd__AaBRd_0_AaBRd_1_r1_lFQOyAcAEAD_AefGQrqd___AJqd_0_yXEqd_1_yXEtSyRd__AaBRd_0_AaBRd_1_r1_lFQOyAcAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAA15ModifiedContentVyAA6ToggleVyAA05TupleO0VyAA4TextV_AUSgQPGGAA32_EnvironmentKeyTransformModifierVySbGG_SbQo__10Foundation4UUIDVSgQo__SbSgQo__So29CTLazuliRegistrationStateTypeVSgQo__A5_Qo__SSAA6ButtonVyAUGAUQo__SSASyA16__A16_QPGAUQo_HO
- _keypath_set.15Tm
- _symbolic _____y_____y_____y_____y_____y_____y_____y_____y_____y______ADSgQPGG_____ySbGG_SbQo_______SgQo__SbSgQo_______SgQo__AMQo__SS_____yADGADQo_ 7SwiftUI4ViewPAAE5alert_11isPresented7actions7messageQrqd___AA7BindingVySbGqd_0_yXEqd_1_yXEtSyRd__AaBRd_0_AaBRd_1_r1_lFQO AcAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA15ModifiedContentV AA6ToggleV AA05TupleO0V AA4TextV AA32_EnvironmentKeyTransformModifierV 10Foundation4UUIDV So29CTLazuliRegistrationStateTypeV AA6ButtonV
- _symbolic _____y_____y_____y_____y_____y_____y_____y_____y_____y_____y______ADSgQPGG_____ySbGG_SbQo_______SgQo__SbSgQo_______SgQo__AMQo__SS_____yADGADQo__SSACyAV_AVQPGADQo_ 7SwiftUI4ViewPAAE5alert_11isPresented7actions7messageQrqd___AA7BindingVySbGqd_0_yXEqd_1_yXEtSyRd__AaBRd_0_AaBRd_1_r1_lFQO AcAEAD_AefGQrqd___AJqd_0_yXEqd_1_yXEtSyRd__AaBRd_0_AaBRd_1_r1_lFQO AcAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQO AcAEAklM_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA15ModifiedContentV AA6ToggleV AA05TupleO0V AA4TextV AA32_EnvironmentKeyTransformModifierV 10Foundation4UUIDV So29CTLazuliRegistrationStateTypeV AA6ButtonV
CStrings:
+ "getSystemConfiguration failed for slot %ld: %@"
+ "v24@?0@\"STAuthenticationResult\"8@\"NSError\"16"
- "An error occurred while activating RCS. Please contact your carrier support to resolve the issue."
- "RCS Activation Failed"
- "RCS_ACTIVATION_FAILED_ALERT_MESSAGE"
- "RCS_ACTIVATION_FAILED_ALERT_OK"
- "RCS_ACTIVATION_FAILED_ALERT_TITLE"
```
