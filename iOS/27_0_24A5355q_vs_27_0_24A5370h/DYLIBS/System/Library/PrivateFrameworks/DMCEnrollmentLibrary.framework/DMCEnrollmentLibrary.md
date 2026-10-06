## DMCEnrollmentLibrary

> `/System/Library/PrivateFrameworks/DMCEnrollmentLibrary.framework/DMCEnrollmentLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2adb0` | `0x2b834` | **`+0xa84`** |
| `__TEXT.__oslogstring` | `0x44d5` | `0x469e` | **`+0x1c9`** |
| `__AUTH_CONST.__cfstring` | `0x18c0` | `0x1960` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x2671` | `0x270d` | **`+0x9c`** |
| `__AUTH_CONST.__objc_const` | `0x1fa0` | `0x2030` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x1c8c` | `0x1d0c` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x1cc8` | `0x1d38` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x810` | `0x84c` | **`+0x3c`** |
| `__DATA_CONST.__const` | `0x1318` | `0x1350` | **`+0x38`** |
| `__AUTH_CONST.__objc_intobj` | `0xae0` | `0xb10` | **`+0x30`** |
| `__DATA_CONST.__objc_arraydata` | `0x528` | `0x550` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x948` | `0x968` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x4c8` | `0x4e0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x198` | `0x1a4` | **`+0xc`** |

### Other Changes

```diff

-105.0.0.0.0
+107.0.0.0.0

-  Functions: 832
-  Symbols:   1464
-  CStrings:  600
+  Functions: 848
+  Symbols:   1484
+  CStrings:  614
Symbols:
+ -[DMCEnrollmentFlowController _fetchEnrollmentProfileFromServiceURL:authTokens:machineInfo:anchorCertificateRefs:enrollmentMethod:prefetchedProfileData:isReturnToService:]
+ -[DMCEnrollmentFlowController _initiateDEPPushTokenSyncIfNeededWithCloudConfig:]
+ -[DMCEnrollmentFlowController prefetchedProfileData]
+ -[DMCEnrollmentFlowController setPrefetchedProfileData:]
+ -[DMCMigrationFlowController _createMigrationCanceledError]
+ -[DMCServiceDiscoveryHelper _checkForESSODetailsInHTTPResponse:completionHandler:]
+ -[DMCUnenrollmentFlowController _askForUserConfirmationIsProvisionallyEnrolled:isAppleMAID:]
+ -[DMCUnenrollmentFlowController _eraseDevice]
+ -[DMCUnenrollmentFlowController _resetToInitialSteps]
+ -[DMCUnenrollmentFlowController _unassignFromDEP]
+ -[DMCUnenrollmentFlowController _uninstallEnrollmentProfileWithIdentifier:personaID:altDSID:isAppleMAID:isProvisionallyEnrolled:unenrollmentType:]
+ -[DMCUnenrollmentFlowController isProvisionallyEnrolled]
+ -[DMCUnenrollmentFlowController isSilent]
+ -[DMCUnenrollmentFlowController setIsProvisionallyEnrolled:]
+ -[DMCUnenrollmentFlowController setIsSilent:]
+ -[DMCUnenrollmentFlowController(Sequence) _provisionalUnenrollmentSteps]
+ -[DMCUnenrollmentFlowController(Sequence) _unenrollmentStepsWithSilent:isProvisional:]
+ GCC_except_table21
+ _OBJC_IVAR_$_DMCEnrollmentFlowController._prefetchedProfileData
+ _OBJC_IVAR_$_DMCUnenrollmentFlowController._isProvisionallyEnrolled
+ _OBJC_IVAR_$_DMCUnenrollmentFlowController._isSilent
+ ___146-[DMCUnenrollmentFlowController _uninstallEnrollmentProfileWithIdentifier:personaID:altDSID:isAppleMAID:isProvisionallyEnrolled:unenrollmentType:]_block_invoke
+ ___146-[DMCUnenrollmentFlowController _uninstallEnrollmentProfileWithIdentifier:personaID:altDSID:isAppleMAID:isProvisionallyEnrolled:unenrollmentType:]_block_invoke_2
+ ___171-[DMCEnrollmentFlowController _fetchEnrollmentProfileFromServiceURL:authTokens:machineInfo:anchorCertificateRefs:enrollmentMethod:prefetchedProfileData:isReturnToService:]_block_invoke
+ ___171-[DMCEnrollmentFlowController _fetchEnrollmentProfileFromServiceURL:authTokens:machineInfo:anchorCertificateRefs:enrollmentMethod:prefetchedProfileData:isReturnToService:]_block_invoke_2
+ ___45-[DMCUnenrollmentFlowController _eraseDevice]_block_invoke
+ ___45-[DMCUnenrollmentFlowController _eraseDevice]_block_invoke_2
+ ___49-[DMCUnenrollmentFlowController _unassignFromDEP]_block_invoke
+ ___49-[DMCUnenrollmentFlowController _unassignFromDEP]_block_invoke_2
+ ___80-[DMCEnrollmentFlowController _initiateDEPPushTokenSyncIfNeededWithCloudConfig:]_block_invoke
+ ___80-[DMCEnrollmentFlowController _initiateDEPPushTokenSyncIfNeededWithCloudConfig:]_block_invoke_2
+ ___82-[DMCServiceDiscoveryHelper _checkForESSODetailsInHTTPResponse:completionHandler:]_block_invoke
+ ___92-[DMCUnenrollmentFlowController _askForUserConfirmationIsProvisionallyEnrolled:isAppleMAID:]_block_invoke
+ ___92-[DMCUnenrollmentFlowController _askForUserConfirmationIsProvisionallyEnrolled:isAppleMAID:]_block_invoke_2
+ ___block_descriptor_40_e8_32bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8
+ ___block_descriptor_40_e8_32bs_e65_v48?0Q8"NSDictionary"16"NSDictionary"24"NSData"32"NSError"40ls32l8
+ ___block_descriptor_41_e8_32s_e17_v16?0"NSError"8ls32l8
+ ___block_descriptor_49_e8_32w_e65_v48?0Q8"NSDictionary"16"NSDictionary"24"NSData"32"NSError"40lw32l8
+ ___block_descriptor_89_e8_32s40s48s56s64s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
- -[DMCEnrollmentFlowController _fetchEnrollmentProfileFromServiceURL:authTokens:machineInfo:anchorCertificateRefs:enrollmentMethod:isReturnToService:]
- -[DMCEnrollmentFlowController _initiateDEPPushTokenSync]
- -[DMCServiceDiscoveryHelper _checkForESSOWithMethod:authParams:httpResponse:completionHandler:]
- -[DMCUnenrollmentFlowController _askForUserConfirmationIsAppleMAID:]
- -[DMCUnenrollmentFlowController _resetToInitialStepsWithSilent:]
- -[DMCUnenrollmentFlowController _uninstallEnrollmentProfileWithIdentifier:personaID:altDSID:isAppleMAID:unenrollmentType:]
- ___122-[DMCUnenrollmentFlowController _uninstallEnrollmentProfileWithIdentifier:personaID:altDSID:isAppleMAID:unenrollmentType:]_block_invoke
- ___122-[DMCUnenrollmentFlowController _uninstallEnrollmentProfileWithIdentifier:personaID:altDSID:isAppleMAID:unenrollmentType:]_block_invoke_2
- ___149-[DMCEnrollmentFlowController _fetchEnrollmentProfileFromServiceURL:authTokens:machineInfo:anchorCertificateRefs:enrollmentMethod:isReturnToService:]_block_invoke
- ___149-[DMCEnrollmentFlowController _fetchEnrollmentProfileFromServiceURL:authTokens:machineInfo:anchorCertificateRefs:enrollmentMethod:isReturnToService:]_block_invoke_2
- ___56-[DMCEnrollmentFlowController _initiateDEPPushTokenSync]_block_invoke
- ___56-[DMCEnrollmentFlowController _initiateDEPPushTokenSync]_block_invoke_2
- ___68-[DMCUnenrollmentFlowController _askForUserConfirmationIsAppleMAID:]_block_invoke
- ___68-[DMCUnenrollmentFlowController _askForUserConfirmationIsAppleMAID:]_block_invoke_2
- ___95-[DMCServiceDiscoveryHelper _checkForESSOWithMethod:authParams:httpResponse:completionHandler:]_block_invoke
- ___block_descriptor_40_e8_32bs_e54_v40?0Q8"NSDictionary"16"NSDictionary"24"NSError"32ls32l8
- ___block_descriptor_41_e8_32s_e34_v24?0"NSDictionary"8"NSError"16ls32l8
- ___block_descriptor_49_e8_32w_e54_v40?0Q8"NSDictionary"16"NSDictionary"24"NSError"32lw32l8
- ___block_descriptor_81_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
CStrings:
+ "-[DMCEnrollmentFlowController _fetchEnrollmentProfileFromServiceURL:authTokens:machineInfo:anchorCertificateRefs:enrollmentMethod:prefetchedProfileData:isReturnToService:]_block_invoke_2"
+ "-[DMCUnenrollmentFlowController _askForUserConfirmationIsProvisionallyEnrolled:isAppleMAID:]_block_invoke_2"
+ "Cloud config is not from DEP, skip push token sync"
+ "DMC_PROVISIONAL_ENROLLMENT_EXPIRED"
+ "Device erase failed: %{public}@"
+ "EraseDevice"
+ "Erasing device for provisional unenrollment..."
+ "Failed to unenroll from DEP: %{public}@"
+ "MDM_MIGRATION_ERROR_CANCELED"
+ "No need to sync push token without cloud config"
+ "Profile removal failed (provisional): %{public}@. Continuing to erase..."
+ "Provisional enrollment has expired!"
+ "Reusing pre-fetched enrollment profile from auth-type discovery (%lu bytes)"
+ "UnassignFromDEP"
+ "Unenrolled from DEP. Removing existing MDM profile..."
+ "device"
+ "v48@?0Q8@\"NSDictionary\"16@\"NSDictionary\"24@\"NSData\"32@\"NSError\"40"
- "-[DMCEnrollmentFlowController _fetchEnrollmentProfileFromServiceURL:authTokens:machineInfo:anchorCertificateRefs:enrollmentMethod:isReturnToService:]_block_invoke_2"
- "-[DMCUnenrollmentFlowController _askForUserConfirmationIsAppleMAID:]_block_invoke_2"
- "v40@?0Q8@\"NSDictionary\"16@\"NSDictionary\"24@\"NSError\"32"
```
