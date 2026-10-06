## DMCEnrollmentProvider

> `/System/Library/PrivateFrameworks/DMCEnrollmentProvider.framework/DMCEnrollmentProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4d678` | `0x4dd4c` | **`+0x6d4`** |
| `__TEXT.__cstring` | `0x2e68` | `0x2f58` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0x2f40` | `0x3020` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0x10f0` | `0x1168` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x6e44` | `0x6eb4` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x107f8` | `0x10838` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x47f8` | `0x4838` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x730` | `0x76c` | **`+0x3c`** |
| `__DATA_CONST.__got` | `0xea8` | `0xed8` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x243f` | `0x245f` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x14f0` | `0x1510` | **`+0x20`** |

### Other Changes

```diff

-105.0.0.0.0
+107.0.0.0.0

+  - /System/Library/PrivateFrameworks/EmbeddedDataReset.framework/EmbeddedDataReset

-  Functions: 2137
-  Symbols:   4111
-  CStrings:  618
+  Functions: 2144
+  Symbols:   4128
+  CStrings:  628
Symbols:
+ +[DMCBYODEnrollmentFlowUIPresenter(Private) fakeAppleAccountWithAuthenticationResults:personaID:store:]
+ +[DMCBYODEnrollmentFlowUIPresenter(Private) fakeiTunesAccountWithAuthenticationResults:personaID:store:]
+ -[DMCBYODEnrollmentFlowUIPresenter(Test) presentUnenrollmentActivityPageIsAppleMAID:isProvisional:]
+ -[DMCEnrollmentFlowManagedConfigurationHelper eraseDeviceWithCompletionHandler:]
+ -[DMCEnrollmentFlowManagedConfigurationHelper isORGOEnrolled]
+ -[DMCEnrollmentFlowManagedConfigurationHelper isProvisionallyEnrolled]
+ -[DMCUnenrollmentFlowUIPresenter _showEraseDeviceConfirmationWithCompletionHandler:]
+ -[DMCUnenrollmentFlowUIPresenter presentUnenrollmentActivityPageIsAppleMAID:isProvisional:]
+ -[DMCUnenrollmentFlowUIPresenter requestUserConfirmationIsAppleMAID:isProvisionallyEnrolled:completionHandler:]
+ GCC_except_table57
+ GCC_except_table82
+ _AAAccountClassPrimary
+ _OBJC_CLASS_$_DDRResetOptions
+ _OBJC_CLASS_$_DDRResetRequest
+ _OBJC_CLASS_$_DDRResetService
+ __OBJC_$_CLASS_METHODS_DMCBYODEnrollmentFlowUIPresenter(Private|Test)
+ __OBJC_$_INSTANCE_METHODS_DMCBYODEnrollmentFlowUIPresenter(Private|Test)
+ __OBJC_CLASS_PROTOCOLS_$_DMCBYODEnrollmentFlowUIPresenter(Private|Test)
+ ___111-[DMCUnenrollmentFlowUIPresenter requestUserConfirmationIsAppleMAID:isProvisionallyEnrolled:completionHandler:]_block_invoke
+ ___111-[DMCUnenrollmentFlowUIPresenter requestUserConfirmationIsAppleMAID:isProvisionallyEnrolled:completionHandler:]_block_invoke_2
+ ___111-[DMCUnenrollmentFlowUIPresenter requestUserConfirmationIsAppleMAID:isProvisionallyEnrolled:completionHandler:]_block_invoke_3
+ ___80-[DMCEnrollmentFlowManagedConfigurationHelper eraseDeviceWithCompletionHandler:]_block_invoke
+ ___84-[DMCUnenrollmentFlowUIPresenter _showEraseDeviceConfirmationWithCompletionHandler:]_block_invoke
+ ___84-[DMCUnenrollmentFlowUIPresenter _showEraseDeviceConfirmationWithCompletionHandler:]_block_invoke_2
+ ___91-[DMCUnenrollmentFlowUIPresenter presentUnenrollmentActivityPageIsAppleMAID:isProvisional:]_block_invoke
+ ___block_descriptor_41_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_42_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_49_e8_32s40bs_e23_v16?0"UIAlertAction"8ls32l8s40l8
+ ___block_descriptor_50_e8_32s40bs_e5_v8?0ls40l8s32l8
+ _kMDMEnrollmentModeORGODevice
+ _kMDMEnrollmentModeORGOUser
- -[DMCBYODEnrollmentFlowUIPresenter _fakeAppleAccountWithAuthenticationResults:personaID:store:]
- -[DMCBYODEnrollmentFlowUIPresenter _fakeiTunesAccountWithAuthenticationResults:personaID:store:]
- -[DMCBYODEnrollmentFlowUIPresenter(Test) presentUnenrollmentActivityPageIsAppleMAID:]
- -[DMCUnenrollmentFlowUIPresenter presentUnenrollmentActivityPageIsAppleMAID:]
- -[DMCUnenrollmentFlowUIPresenter requestUserConfirmationIsAppleMAID:completionHandler:]
- GCC_except_table53
- GCC_except_table78
- __OBJC_$_INSTANCE_METHODS_DMCBYODEnrollmentFlowUIPresenter(Test)
- __OBJC_CLASS_PROTOCOLS_$_DMCBYODEnrollmentFlowUIPresenter(Test)
- ___77-[DMCUnenrollmentFlowUIPresenter presentUnenrollmentActivityPageIsAppleMAID:]_block_invoke
- ___87-[DMCUnenrollmentFlowUIPresenter requestUserConfirmationIsAppleMAID:completionHandler:]_block_invoke
- ___87-[DMCUnenrollmentFlowUIPresenter requestUserConfirmationIsAppleMAID:completionHandler:]_block_invoke_2
- ___87-[DMCUnenrollmentFlowUIPresenter requestUserConfirmationIsAppleMAID:completionHandler:]_block_invoke_3
- ___block_descriptor_49_e8_32s40bs_e5_v8?0ls40l8s32l8
CStrings:
+ "%s primary: %@ %@"
+ "%s rm: %@ %@"
+ "-[DMCMDMSignoutSpecifierProvider _specifierForMDMProfileWasTapped:]"
+ "DMC_CONSENT_NOTICES_%lu"
+ "DMC_ERASE"
+ "DMC_ERASE_DEVICE_BODY"
+ "DMC_ERASE_DEVICE_TITLE"
+ "DMC_LEAVING_REMOTE_MANAGEMENT_DESCRIPTION"
+ "DMC_SIGN_OUT_PROVISIONAL_WARNING"
+ "Provisional enrollment sign out"
+ "primaryAccount"
- "DMC_CONSENT_NOTICES_%@"
```
