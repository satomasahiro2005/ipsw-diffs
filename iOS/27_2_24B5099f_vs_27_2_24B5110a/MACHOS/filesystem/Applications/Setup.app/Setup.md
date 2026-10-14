## Setup

> `/Applications/Setup.app/Setup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24ce00` | `0x25cd64` | **`+0xff64`** |
| `__DATA.__objc_const` | `0x496d0` | `0x4a288` | **`+0xbb8`** |
| `__TEXT.__oslogstring` | `0x150ac` | `0x159c9` | **`+0x91d`** |
| `__TEXT.__eh_frame` | `0x4348` | `0x4c50` | **`+0x908`** |
| `__TEXT.__objc_methname` | `0x40a7e` | `0x41276` | **`+0x7f8`** |
| `__DATA.__bss` | `0x22a8` | `0x28c8` | **`+0x620`** |
| `__DATA_CONST.__const` | `0x8778` | `0x8cd8` | **`+0x560`** |
| `__TEXT.__objc_stubs` | `0x293c0` | `0x29860` | **`+0x4a0`** |
| `__TEXT.__const` | `0x3658` | `0x3ad8` | **`+0x480`** |
| `__TEXT.__unwind_info` | `0x9e10` | `0xa228` | **`+0x418`** |
| `__TEXT.__objc_methlist` | `0x1dc20` | `0x1e028` | **`+0x408`** |
| `__TEXT.__cstring` | `0xfcfb` | `0x1009b` | **`+0x3a0`** |
| `__DATA.__data` | `0x7a38` | `0x7be8` | **`+0x1b0`** |
| `__DATA.__objc_data` | `0xcae8` | `0xcc78` | **`+0x190`** |
| `__TEXT.__constg_swiftt` | `0x3a2c` | `0x3bb8` | **`+0x18c`** |
| `__TEXT.__swift5_reflstr` | `0x1d09` | `0x1e89` | **`+0x180`** |
| `__TEXT.__objc_methtype` | `0xcad0` | `0xcc4d` | **`+0x17d`** |
| `__DATA.__objc_selrefs` | `0xcd00` | `0xce60` | **`+0x160`** |
| `__DATA_CONST.__cfstring` | `0xb440` | `0xb5a0` | **`+0x160`** |
| `__TEXT.__swift5_fieldmd` | `0x1a38` | `0x1b90` | **`+0x158`** |
| `__TEXT.__swift5_typeref` | `0x2796` | `0x28d6` | **`+0x140`** |
| `__TEXT.__dlopen_cstrs` | `0x179c` | `0x1888` | **`+0xec`** |
| `__TEXT.__auth_stubs` | `0x28f0` | `0x29b0` | **`+0xc0`** |
| `__TEXT.__swift5_capture` | `0x11e0` | `0x129c` | **`+0xbc`** |
| `__TEXT.__objc_classname` | `0x5c0c` | `0x5cac` | **`+0xa0`** |
| `__DATA_CONST.__auth_got` | `0x1490` | `0x14f0` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x4e2c` | `0x4e78` | **`+0x4c`** |
| `__TEXT.__swift_as_cont` | `0x298` | `0x2dc` | **`+0x44`** |
| `__DATA_CONST.__auth_ptr` | `0x518` | `0x550` | **`+0x38`** |
| `__TEXT.__swift5_proto` | `0x128` | `0x15c` | **`+0x34`** |
| `__DATA.__objc_ivar` | `0x1d40` | `0x1d70` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x198` | `0x1c8` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x198` | `0x1c4` | **`+0x2c`** |
| `__TEXT.__swift_as_entry` | `0x19c` | `0x1c4` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x1f8` | `0x214` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x1c38` | `0x1c50` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xe10` | `0xe28` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x154` | `0x168` | **`+0x14`** |
| `__DATA_CONST.__objc_superrefs` | `0x808` | `0x818` | **`+0x10`** |
| `__DATA.__common` | `0x60` | `0x68` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x868` | `0x870` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x2c8` | `0x2d0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x3c` | `0x40` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_floatobj`
- `__DATA_CONST.__objc_intobj`

### Other Changes

```diff

-5411.2.2.0.0
+5411.2.4.0.0

-  Functions: 12342
-  Symbols:   1530
-  CStrings:  14882
+  Functions: 12637
+  Symbols:   1548
+  CStrings:  15017
Symbols:
+ _$s20AppManagedFeaturesUI28EnrollmentControllerProviderC22softwareUpdateRequiredSbvgTj
+ _$s2os6LoggerV9subsystem8categoryACSS_SStcfC
+ _$sSKsSS7ElementRtzrlE6joined9separatorS2S_tF
+ _$sSayxGSKsMc
+ _$ss15ContiguousArrayV28_allocateBufferUninitialized15minimumCapacitys01_abD0VyxGSi_tFZ
+ _$ss21_findStringSwitchCase5cases6stringSiSays06StaticB0VG_SStF
+ _$ss22_minimumMergeRunLengthyS2iF
+ _$ss5ErrorP19_getEmbeddedNSErroryXlSgyFTq
+ _$ss5ErrorP5_codeSivgTq
+ _$ss5ErrorP7_domainSSvgTq
+ _$ss5ErrorP9_userInfoyXlSgvgTq
+ _$ss5ErrorPsE19_getEmbeddedNSErroryXlSgyF
+ _$ss5ErrorPsE5_codeSivg
+ _$ss5ErrorPsE7_domainSSvg
+ _$ss5ErrorPsE9_userInfoyXlSgvg
+ _$sytWV
+ _objc_release_x11
+ _objc_retain_x9
CStrings:
+ "$__lazy_storage_$_deviceTermsProvider"
+ "%{public}@ Buddy Checkpoint -\n\tcurrentState: %{public}@ (%ld)\n\tscanError: %{public}@\n\tpresentedDescriptor: %{public}@\n\tdownload: %{public}@ (%p)\n\nExtended initialization finished. Should present update: %{BOOL}d (update found: %{BOOL}d, scan error: %{public}@)"
+ "%{public}@ Buddy Checkpoint -\n\tcurrentState: %{public}@ (%ld)\n\tscanError: %{public}@\n\tpresentedDescriptor: %{public}@\n\tdownload: %{public}@ (%p)\n\nSUUI Partner Financing Controller finished the extended initialization successfully: %{BOOL}d"
+ "@\"<BuddyCombinedTermsProvider>\"24@0:8q16"
+ "@\"<BuddyTermsManaging>\""
+ "@\"<BuddyTermsManaging>\"16@0:8"
+ "@\"NSSet\"16@0:8"
+ "@\"NSSet\"8@?0"
+ "@\"SUUISetupAssistantAppManagedFeaturesUpdateController\""
+ "AccountTerms"
+ "BuddyCombinedTermsProviderErrorDomain"
+ "BuddyPartnerFinancingUpdateController"
+ "BuddyPartnerFinancingUpdateController.m"
+ "BuddyServicesTermsProvider"
+ "BuddyTermsManager"
+ "Class getSUUISetupAssistantAppManagedFeaturesUpdateControllerClass(void)_block_invoke"
+ "DebugRestoreFailure"
+ "DebugRestoreFailureErrorCode"
+ "DebugRestoreStateFile"
+ "Failed to write restore state to %{public}@: %{public}@"
+ "ForceTermsToPresent"
+ "ForceTermsWarranty"
+ "Forced restore failure (%@)"
+ "Forcing -_attemptRestore to fail (useLatestSnapshot=%d)"
+ "Forcing restore to fail in progress for snapshot %ld: %{public}@"
+ "Forcing restore to fail to start for snapshot %ld: %{public}@"
+ "Ignoring invalid restore state file %{public}@: %{public}@ (%{public}@)"
+ "Ignoring unknown %@ value: %@"
+ "Oct  4 2026"
+ "On-device terms forced by override, the device terms server is unavailable"
+ "OnDevice"
+ "Partner Financing checking for software update."
+ "Partner Financing found an applicable forced update; presenting the software update pane."
+ "PartnerFinancing"
+ "Persisting restore state from %{public}@: %{public}@"
+ "Requesting terms for entries %s, preferPassword = %{bool}d"
+ "SU update operation attempt of type \"%{public}@\" has failed, cancelling Partner Financing update launch: %{public}@"
+ "SUUISetupAssistantAppManagedFeaturesUpdateController"
+ "Services terms forced by override"
+ "Services terms need verifying"
+ "Services terms verified"
+ "Setup.BuddyTermsManager"
+ "Setup.BuddyUnavailableTermsProvider"
+ "Skipping app states comparison for Rapid Return to Service"
+ "SoftwareLicense"
+ "T@\"<BuddyTermsManaging>\",&,N"
+ "T@\"<BuddyTermsManaging>\",&,N,V_termsManager"
+ "T@\"<BuddyTermsManaging>\",?,&,N"
+ "T@\"BuddyTermsManager\",N,R"
+ "T@\"NSNumber\",N,&,VacceptedSoftwareLicenseVersion"
+ "T@\"NSSet\",C,N,V_requestedTerms"
+ "T@\"NSSet\",N,C"
+ "T@\"NSSet\",N,R"
+ "T@\"NSSet\",R,N"
+ "T@?,C,N,V_doneHandler"
+ "T@?,C,N,V_presentWiFiPaneHandler"
+ "T@?,C,N,V_requiredDeviceTermsEntries"
+ "Terms response carried no data"
+ "Terms: acknowledged software license agreement version %{public}@"
+ "Terms: acknowledged warranty"
+ "Terms: acknowledging account terms with the server"
+ "Terms: error attempting to remove license sentinel: %@"
+ "Terms: failed to confirm account terms agreement: %@"
+ "Terms: failed to remove license sentinel file: %@"
+ "Terms: fetching the terms sheet for %{public}@"
+ "Terms: iCloud sign-in did not succeed, not acknowledging requested %{public}s"
+ "Terms: missing agreeURL, cannot confirm account terms agreement with the server"
+ "Terms: no primary account, cannot confirm account terms agreement with the server"
+ "Terms: no terms sheet to present for %{public}@: %{public}@"
+ "Terms: presenting %{public}s terms (%{public}s), requesting %{public}s%{public}s"
+ "Terms: presenting the on-device terms, %{public}s the warranty"
+ "Terms: presenting the terms sheet for %{public}@"
+ "Terms: server has nothing to present for %{public}s"
+ "Terms: sign-in requested %{public}s, account reports software license agreement version %{public}s"
+ "Terms: skipped by cloud config, acknowledging the on-disk software license agreement version %{public}lu and the warranty"
+ "Terms: user agreed to the on-device terms %{public}s the warranty"
+ "Terms: user agreed to the terms sheet for %{public}s, SLA version %{public}s"
+ "Terms: user declined the on-device terms"
+ "Terms: user declined the terms sheet for %{public}@, which blocks continuing"
+ "Terms: user declined the terms sheet for %{public}s, continuing without acknowledging it"
+ "Terms: warranty already acknowledged"
+ "Tq,N,V_termsToPresent"
+ "Wrote restore state to %{public}@: %{public}@"
+ "[%@]"
+ "_TtC5Setup27BuddyTermsUnderlyingHandler"
+ "_TtC5Setup29BuddyUnavailableTermsProvider"
+ "_TtP5Setup18BuddyTermsManaging_"
+ "_agreedSLAVersionForAccount:"
+ "_classListForTerms:"
+ "_debugRestoreFailureError"
+ "_debugRestoreFailureMode"
+ "_debugRestoreStateFileURL"
+ "_doneHandler"
+ "_forceRestoreFailureIfNeededForSnapshotID:"
+ "_loadDebugRestoreStateFileIfNeededIntoPreferences:"
+ "_presentWiFiPaneHandler"
+ "_requestedTerms"
+ "_requiredDeviceTermsEntries"
+ "_termsManager"
+ "_termsToPresent"
+ "_updateAgreedTerms:cloudSucceeded:"
+ "_writeDebugRestoreStateFileForRestorable:allowCellularNetwork:"
+ "acceptedSoftwareLicenseVersion"
+ "attempt"
+ "checkForMandatoryUpdateRequiringUpdate:completion:"
+ "determineTermsToPresentWithInitialRunCompleted:completion:"
+ "dictionaryWithContentsOfURL:error:"
+ "doneHandler"
+ "hasPrimaryAccount"
+ "initWithRequiredDeviceTermsEntries:"
+ "initWithUnsignedInteger:"
+ "isRapidReturnToService"
+ "makeDeviceTermsProvider"
+ "makePartnerFinancingUpdateController"
+ "makeServicesTermsProvider"
+ "needsToVerifyTermsWithCompletionHandler:"
+ "no primary account"
+ "performTermsRequest(for:preferPassword:)"
+ "presentWiFiPaneHandler"
+ "readOverride"
+ "recordOnDeviceTermsAgreedWithLicenseVersion:includingWarranty:"
+ "recordServerHasNoTermsToPresentForTermsEntries:"
+ "recordSignInWithRequestedTerms:slaVersion:cloudSucceeded:"
+ "recordTermsAgreedForTermsEntries:slaVersion:agreeURL:"
+ "recordTermsDeclinedForTermsEntries:"
+ "recordTermsSkippedByCloudConfig"
+ "requestedTerms"
+ "requiredDeviceTermsEntries"
+ "scanForForcedUpdate(_:)"
+ "setAcceptedSoftwareLicenseVersion:"
+ "setByAddingObject:"
+ "setDoneHandler:"
+ "setPresentWiFiPaneHandler:"
+ "setRequestedTerms:"
+ "setRequiredDeviceTermsEntries:"
+ "setTermsEntries:"
+ "setTermsManager:"
+ "setTermsSeenThisSession:"
+ "setTermsToPresent:"
+ "shouldDoRapidReturnToService"
+ "software license agreement never accepted"
+ "softwareLicenseOutstanding"
+ "softwareUpdateRequired but no applicable update found, proceeding to enrollment."
+ "terms already presented this session"
+ "termsEntries"
+ "termsFinishedForSession"
+ "termsManager"
+ "termsProviderForTerms:"
+ "termsSeenThisSession"
+ "termsToPresent"
+ "underlying"
+ "updateController"
+ "v24@0:8@\"<BuddyTermsManaging>\"16"
+ "v24@0:8@\"NSSet\"16"
+ "v28@0:8B16@?<v@?q>20"
+ "v36@0:8@\"NSSet\"16@\"NSNumber\"24B32"
+ "v40@0:8@\"NSSet\"16@\"NSNumber\"24@\"NSString\"32"
+ "with"
+ "without"
+ "writeToDebugRestoreStateFileIfNeeded"
+ "writeToURL:error:"
- "$"
- "@\"<BuddyCombinedTermsProvider>\"16@0:8"
- "BuddyServicesTermsFlow"
- "BuddyServicesTermsFlow: servicesTermsProvider does not conform to BuddyCombinedTermsProviderProtocol; falling back to the default combined terms provider"
- "Combined terms controller is somehow the incorrect type"
- "Did agree to server terms"
- "Failed to confirm Services terms agreement: %@"
- "Failed to remove license sentinel file: %{public}@"
- "Missing agreeURL or account, cannot confirm Services terms agreement with the server"
- "Requesting terms for entries [.entryiCloud], preferPassword = %{bool}d"
- "Sep 26 2026"
- "ServicesTermsFlow needs to run: %{bool}d"
- "ServicesTermsFlow needs to verify terms: %{bool}d"
- "Skipping services terms because this is initial run buddy"
- "T@\"<BuddyCombinedTermsProvider>\",&,N"
- "T@\"<BuddyCombinedTermsProvider>\",?,&,N"
- "Terms and Conditions pane skipped by cloud config, removing license and warranty sentinels"
- "User agreed to terms"
- "User disagreed to terms"
- "_TtC5Setup26BuddyServicesTermsProvider"
- "_updateAgreedTerms:"
- "agreementRecorder"
- "didAgree"
- "didAgreeToServerTerms"
- "recordUserAgreementWithURL:"
- "v24@0:8@\"<BuddyCombinedTermsProvider>\"16"
```
