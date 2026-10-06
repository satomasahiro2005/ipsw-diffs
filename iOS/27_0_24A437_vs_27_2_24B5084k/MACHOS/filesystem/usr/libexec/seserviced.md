## seserviced

> `/usr/libexec/seserviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4890e8` | `0x4a2fc0` | **`+0x19ed8`** |
| `__DATA.__bss` | `0x14000` | `0x15d10` | **`+0x1d10`** |
| `__TEXT.__const` | `0x15038` | `0x16310` | **`+0x12d8`** |
| `__TEXT.__oslogstring` | `0x320f9` | `0x32d68` | **`+0xc6f`** |
| `__DATA_CONST.__const` | `0x15bc8` | `0x16618` | **`+0xa50`** |
| `__TEXT.__eh_frame` | `0x1609c` | `0x16abc` | **`+0xa20`** |
| `__TEXT.__cstring` | `0x22a31` | `0x23076` | **`+0x645`** |
| `__TEXT.__unwind_info` | `0xabf8` | `0xaff8` | **`+0x400`** |
| `__DATA.__data` | `0xe534` | `0xe904` | **`+0x3d0`** |
| `__TEXT.__swift5_typeref` | `0x5990` | `0x5d3c` | **`+0x3ac`** |
| `__TEXT.__swift5_fieldmd` | `0x63fc` | `0x6754` | **`+0x358`** |
| `__TEXT.__constg_swiftt` | `0x5e88` | `0x61ac` | **`+0x324`** |
| `__TEXT.__auth_stubs` | `0x5100` | `0x53e0` | **`+0x2e0`** |
| `__DATA.__objc_const` | `0x19208` | `0x19420` | **`+0x218`** |
| `__DATA_CONST.__auth_got` | `0x2898` | `0x2a08` | **`+0x170`** |
| `__TEXT.__swift5_reflstr` | `0x652a` | `0x668a` | **`+0x160`** |
| `__TEXT.__objc_methname` | `0x196ed` | `0x197fd` | **`+0x110`** |
| `__TEXT.__swift5_proto` | `0xae0` | `0xbcc` | **`+0xec`** |
| `__TEXT.__swift5_capture` | `0x33c4` | `0x34ac` | **`+0xe8`** |
| `__DATA_CONST.__cfstring` | `0x8ac0` | `0x8b80` | **`+0xc0`** |
| `__TEXT.__objc_stubs` | `0xe8a0` | `0xe800` | **`-0xa0`** |
| `__TEXT.__swift_as_cont` | `0xf1c` | `0xf88` | **`+0x6c`** |
| `__DATA_CONST.__auth_ptr` | `0xfe8` | `0x1048` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x2120` | `0x2178` | **`+0x58`** |
| `__TEXT.__swift5_types` | `0x664` | `0x6b8` | **`+0x54`** |
| `__TEXT.__objc_classname` | `0x3168` | `0x3198` | **`+0x30`** |
| `__DATA.__objc_data` | `0x6c08` | `0x6c30` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x4b30` | `0x4b08` | **`-0x28`** |
| `__TEXT.__swift5_builtin` | `0x3e8` | `0x410` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0x500` | `0x528` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x604` | `0x62c` | **`+0x28`** |
| `__TEXT.__swift5_assocty` | `0x840` | `0x828` | **`-0x18`** |
| `__TEXT.__objc_methtype` | `0x7fe6` | `0x7ffd` | **`+0x17`** |
| `__TEXT.__objc_methlist` | `0x71a4` | `0x71b4` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0xcc` | `0xdc` | **`+0x10`** |
| `__DATA.__common` | `0x838` | `0x840` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x888` | `0x890` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xcf8` | `0xcfc` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x68` | `0x6c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-70.39.1.0.0
+71.7.0.0.0

-  - /System/Library/PrivateFrameworks/AppletTranslationFramework.framework/AppletTranslationFramework

-  Functions: 13194
-  Symbols:   2554
-  CStrings:  11639
+  Functions: 13504
+  Symbols:   2613
+  CStrings:  11722
Symbols:
+ _$s3XPC11XPCListenerC11targetQueue7options22incomingSessionHandlerACSo17OS_dispatch_queueCSg_AC21InitializationOptionsVAC08IncomingG7RequestC8DecisionVAMctcfc
+ _$s3XPC11XPCListenerC22IncomingSessionRequestC6reject6reasonAE8DecisionVSS_tFTj
+ _$s9SESShared14JPKI_CONSTANTSV15SW_DATA_INVALIDs6UInt16VvgZ
+ _$s9SESShared14JPKI_CONSTANTSV15SW_WRONG_LENGTHs6UInt16VvgZ
+ _$s9SESShared14JPKI_CONSTANTSV19CA_SIGNED_CERT_SIZESivgZ
+ _$s9SESShared14JPKI_CONSTANTSV19SW_PIN_FAILED_RANGESNys6UInt16VGvgZ
+ _$s9SESShared14JPKI_CONSTANTSV21SW_NO_REMAINING_TRIESs6UInt16VvgZ
+ _$s9SESShared14JPKI_CONSTANTSV21USER_CERT_INFO_OFFSETSivgZ
+ _$s9SESShared14JPKI_CONSTANTSV24SIGNING_CERT_INFO_OFFSETSivgZ
+ _$s9SESShared14JPKI_CONSTANTSV27SW_CONDITIONS_NOT_SATISFIEDs6UInt16VvgZ
+ _$s9SESShared14JPKI_CONSTANTSV29SW_PIN_RETRIES_REMAINING_MASKs6UInt16VvgZ
+ _$s9SESShared14JPKI_CONSTANTSV31SW_INVALID_PIN_LENGTH_EXCEPTIONs6UInt16VvgZ
+ _$s9SESShared14JPKI_CONSTANTSV32AVAILABILITY_INFO_INSTALLED_MASKs5UInt8VvgZ
+ _$s9SESShared8fileIEFsO12userCert_IEFyA2CmFWC
+ _$s9SESShared8fileIEFsO15signingCert_IEFyA2CmFWC
+ _$s9SESShared8fileIEFsO20availabilityInfo_IEFyA2CmFWC
+ _$s9SESShared8fileIEFsO22signCertSigningKey_IEFyA2CmFWC
+ _$s9SESShared8fileIEFsO22userCertSigningKey_IEFyA2CmFWC
+ _$s9SESShared8fileIEFsO7pin_IEFyA2CmFWC
+ _$s9SESShared8fileIEFsO7pwd_IEFyA2CmFWC
+ _$s9SESShared8fileIEFsO8rawValues5UInt8Vvg
+ _$s9SESShared8fileIEFsOMa
+ _$s9SEService10SESnapshotC12CanFitResultO13FailureReasonV3codAGvgZ
+ _$s9SEService10SESnapshotC12CanFitResultO13FailureReasonV3corAGvgZ
+ _$s9SEService10SESnapshotC12CanFitResultO13FailureReasonV7indicesAGvgZ
+ _$s9SEService10SESnapshotC12CanFitResultO13FailureReasonVMn
+ _$s9SEService10SESnapshotC12CanFitResultO13FailureReasonVs10SetAlgebraAAMc
+ _$s9SEService10TCCContextCAA12TCCProvidingAAWP
+ _$s9SEService12SESAppRecordV11isInstalledSbvg
+ _$s9SEService12SESAppRecordV13applicationIdSSvg
+ _$s9SEService12SESAppRecordV13localizedNameSSvg
+ _$s9SEService12SESAppRecordV17InstallationStateO12notInstalledyA2EmFWC
+ _$s9SEService12SESAppRecordV17InstallationStateO2eeoiySbAE_AEtFZ
+ _$s9SEService12SESAppRecordV17InstallationStateO9installedyA2EmFWC
+ _$s9SEService12SESAppRecordV17InstallationStateOMa
+ _$s9SEService12SESAppRecordV17InstallationStateOSQAAMc
+ _$s9SEService12SESAppRecordVMa
+ _$s9SEService12SESAppRecordVMn
+ _$s9SEService12TCCProvidingMp
+ _$s9SEService12TCCProvidingP14checkTCCAccess2to3forAA10TCCContextC0D0OAH10TCCServiceO_SStFTj
+ _$s9SEService12TCCProvidingP20getTCCKnownBundleIds3for6filterShySSGAA10TCCContextC10TCCServiceO_SbAI9TCCAccessOcSgtFTj
+ _$s9SEService12TCCProvidingPAAE20getTCCKnownBundleIds3forShySSGAA10TCCContextC10TCCServiceO_tF
+ _$s9SEService13LSAppProviderVAA0B9ProvidingAAWP
+ _$s9SEService13LSAppProviderVACycfC
+ _$s9SEService13LSAppProviderVMa
+ _$s9SEService13SERXPCRequestO19reportCanFitFailureyAcA10SESnapshotC0dE6ResultO0F6ReasonV_AA14CredentialTypeO12DiscriminantOtcACmFWC
+ _$s9SEService14CredentialTypeO12DiscriminantO8rawValueSivg
+ _$s9SEService14CredentialTypeO12DiscriminantOMa
+ _$s9SEService14CredentialTypeO12DiscriminantOMn
+ _$s9SEService14LSAppProvidingMp
+ _$s9SEService14LSAppProvidingP14hasEntitlement_11forBundleIdSbSS_SStFTj
+ _$s9SEService14LSAppProvidingP18installedBundleIdsShySSGyFTj
+ _$s9SEService14LSAppProvidingP3app11forBundleIdAA12SESAppRecordVSgSS_tFTj
+ _$s9SEService14LSAppProvidingPAAE11isInstalled_16allowPlaceholderSbSS_SbtF
+ _$s9SEService14LSAppProvidingPAAE17installationState11forBundleIdAA12SESAppRecordV012InstallationE0OSS_tF
+ _$s9SEService24SEStorageManagementSheetV22ProposedCredentialTypeO08snapshotfG0AA0fG0OSgvg
+ _$sSJ8isLetterSbvg
+ _$sSJ8isNumberSbvg
+ _$sSS17UnicodeScalarViewV13_foreignIndex5afterSS0E0VAF_tF
+ _$sShMa
+ _$sSo7NSErrorC9SESSharedE3msg8wrappingABSS_s5Error_pSgtcfC
+ _$sSs5index5afterSS5IndexVAD_tF
+ _$sSs8distance4from2toSiSS5IndexV_AEtF
+ _$sSsySJSS5IndexVcig
+ _$ss11_StringGutsV18foreignScalarAlignySS5IndexVAEF
+ _$ss11_StringGutsV27foreignErrorCorrectedScalar10startingAts7UnicodeO0F0V_Si12scalarLengthtSS5IndexV_tF
+ _swift_getExistentialTypeMetadata
- _$s9SEService10TCCContextC14checkTCCAccess2to3forAC0D0OAC10TCCServiceO_SStF
- _$s9SEService10TCCContextC20getTCCKnownBundleIds3for6filterShySSGAC10TCCServiceO_SbAC9TCCAccessOcSgtF
- _$s9SEService10TCCContextCMn
- _ATLECP2InfoKey
- _ATLPassInformationAliroGroupResolvingKeys
- _ATLPassInformationAssociatedReaderIdentifiers
- _ATLPassInformationKeyReaderIdentifier
- _ATLPassInformationReaderPriority
CStrings:
+ "%s : %i : (%{public}@) Ending reportEndpointStatistics test after %llu ms"
+ "%s : %i : (%{public}@) Starting reportEndpointStatistics test"
+ "%s : %i : Attempting to create duplicate pending pairing for source (type %{public}ld): %{private}@"
+ "%s : %i : Failed to register debug stats reporting trigger: %u"
+ "%s : %i : No message identifier and missing spotlight identifier components"
+ "%s : %i : Processed source identifier list is full (%lu), dropping new source"
+ "%s : %i : Processed source identifier list is full (%lu), ignoring because of UD"
+ "%s : %i : Registered debug stats reporting trigger (%{public}s)"
+ "%s : %i : Removing expired processed source identifier: %{private}@"
+ "%s : %i : Source (type %{public}ld) was already processed, ignoring because of UD: %{private}@"
+ "%s : %i : Source (type %{public}ld) was already processed, skipping: %{private}@"
+ "%s Error %@ while checking canFitWithReason; failing without presenting"
+ "%s Error %@ while preparing snapshot for storage management presentation"
+ "%s SE storage shortfall cannot be alleviated by the UI (%s); failing without presenting"
+ "%s: Application %s has no entity; nothing to carry over to %s"
+ "%s: Credential %s no longer exists; nothing to remove"
+ "+[KmlEndpointManager registerDebugStatsReportingTrigger]_block_invoke"
+ "+[KmlEndpointManager registerDebugStatsReportingTrigger]_block_invoke_2"
+ "+[KmlEndpointManager reportEndpointStatistics:identifier:ignoreFirstUnlockGate:]"
+ "+[KmlEndpointManager reportEndpointStatistics:identifier:ignoreFirstUnlockGate:]_block_invoke"
+ "-[KmlBiomeSubscriptionManager cleanupExpiredProcessedSourceIdentifiers]"
+ "-[KmlBiomeSubscriptionManager simulateIncomingProvisioningWithOPURL:pairingPasswordExpiration:vehicleName:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:]"
+ "-[KmlXpcService(PendingPairing) createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:callback:]"
+ "-[KmlXpcService(PendingPairing) createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:callback:]"
+ "<none>"
+ "Adding new app entity for appId %s -- bundleIdentifier populated on the app's first launch"
+ "Adding new app entity for appId %s as the migration destination"
+ "An app migration is already in progress"
+ "App migration %s -> %s: %ld credential(s) could not be reassigned"
+ "App migration %s -> %s: migrating %ld credential(s)"
+ "App migration %s -> %s: no SEC credentials to migrate"
+ "App migration XPC error: "
+ "App migration already in progress; rejecting request %{public}s"
+ "App migration could not reassign "
+ "App migration could not resolve an application identity for "
+ "App migration encountered an internal error: "
+ "App migration failed to serialize/deserialize a message: "
+ "App migration failed: "
+ "App migration: %s is not an eligible default contactless app candidate; leaving default to reconciliation fallback"
+ "App migration: %s is not the default contactless app; leaving default unchanged"
+ "App migration: MFD of %ld credential(s) did not delete; leaving to reconciliation once %s is uninstalled"
+ "App migration: MFD of %ld credential(s) failed: %s; leaving to reconciliation once %s is uninstalled"
+ "App migration: destination %s is not granted SEC TCC; credentials will not be reassigned to it"
+ "App migration: destination %s lacks the default-app-configurable entitlement; leaving default unchanged"
+ "App migration: failed to reassign credential %s: %s"
+ "App migration: inline removal of %s from credential %s failed: %s; leaving to reconciliation once %s is uninstalled"
+ "App migration: marking %ld sole-owner credential(s) for deletion"
+ "App migration: no default contactless app set; nothing to transfer"
+ "App migration: reassigned credential %s to %s"
+ "App migration: removed %s from co-owned credential %s"
+ "App migration: source and destination are both %s; nothing to migrate"
+ "App migration: transferred default contactless app from %s to %s (domain %lu)"
+ "AppMigrationXPCRequest "
+ "Client is not entitled for app migration"
+ "Client is not entitled to perform app migration"
+ "Debug client appId %s bundleId %s teamId %s"
+ "Debug client info %s has no team identifier prefix; assuming it is a bundle identifier"
+ "Detached task cancelled in %{public}s (%{public}s:%{public}lu)%{public}s"
+ "Detached task threw in %{public}s (%{public}s:%{public}lu)%{public}s: %{public}s"
+ "ECP2Info"
+ "Error preparing snapshot: "
+ "Failed to create XPCListener for service %{public}s: %{public}s"
+ "Ignoring unknown tag value %u for reader descriptor"
+ "Incomplete reader descriptor %{public}s"
+ "MFD %ld credential(s) %s, reason: %{public}s"
+ "Malformed reader descriptor data %{public}s"
+ "Product ID %{public}s, vendor ID %{public}s, firmware version %{public}s"
+ "SECAppMigrationXPCServer was deallocated"
+ "SER: request %{public}u failed with internal error: %{public}@"
+ "SER: request %{public}u failed: %{public}s"
+ "Skipping Container: %s module %s under SD %s"
+ "Skipping ELF: %s filtered module %s under SD %s"
+ "Skipping Instance: %s filtered module %s under SD %s"
+ "Successfully carried over application %s to %s (%s)"
+ "Unknown event TLV with tag 0x%x"
+ "Unknown one-way request type"
+ "Unsupported customer build on internal device"
+ "Vv112@0:8@\"NSURL\"16@\"NSDate\"24@\"NSString\"32@\"NSDate\"40@\"NSString\"48@\"NSString\"56@\"NSString\"64@\"NSString\"72@\"NSDate\"80@\"NSString\"88B96B100@?<v@?@\"NSString\">104"
+ "Vv112@0:8@16@24@32@40@48@56@64@72@80@88B96B100@?104"
+ "Vv148@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32Q40@\"NSString\"48@\"NSString\"56@\"NSDate\"64@\"NSString\"72@\"NSDate\"80@\"NSString\"88@\"NSString\"96@\"NSString\"104@\"NSString\"112@\"NSDate\"120@\"NSString\"128B136@?<v@?@\"NSString\">140"
+ "Vv148@0:8@16@24@32Q40@48@56@64@72@80@88@96@104@112@120@128B136@?140"
+ "[sourceIdentifier: %@, messageIdentifier: %@, source: %@, receivedDate: %@, language: %@]"
+ "_TtC10seserviced24SECAppMigrationXPCServer"
+ "_messageIdentifier"
+ "_processedSourceIdentifiers"
+ "_sourceIdentifier"
+ "_useMockSnapshot"
+ "accessValidator"
+ "aliroGroupResolvingKeys"
+ "all owner apps had SEC TCC access revoked"
+ "all owner apps uninstalled"
+ "associatedReaderIdentifiers"
+ "cleanupExpiredProcessedSourceIdentifiers"
+ "clearPreArmState"
+ "com.apple.private.seserviced.appmigration"
+ "com.apple.sesd.seReservations.canFitFailure"
+ "com.apple.seserviced.private.appmigration"
+ "computeShouldShowPanes: %s has no installed LaunchServices record"
+ "createCredential install-complete delay"
+ "createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:callback:"
+ "createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:callback:"
+ "defaultAppCandidates: %s has no installed LaunchServices record"
+ "destinationBundleId"
+ "eligibility"
+ "eligibilityProvider"
+ "iOS (27.2) - SecureElementService-71.7"
+ "ignoreProcessedSourceIdentifierCheck"
+ "initWithOwnerPairingUrl:carBrand:alreadyProvisioned:carModel:carIdentifier:pairingCode:userIdentifier:provisioningCodeExpiration:spotlightUniqueIdentifier:spotlightDomainIdentifier:spotlightBundleIdentifier:dateSent:cccManufacturer:cccBrand:supportedTransports:sourceLanguage:messageIdentifier:"
+ "isMigrationInProgress"
+ "loadProcessedSourceIdentifiers"
+ "lsAppProvider"
+ "markForDeletion(_:)"
+ "messageIdentifier"
+ "migrateApplicationEntity(from:to:bundleId:)"
+ "migrationInProgress"
+ "reconcileDatabaseAndTCCAccess(tcc:lsAppProvider:)"
+ "removeApplications(_:from:)"
+ "replaceApplication(from:to:in:)"
+ "saveProcessedSourceIdentifiers"
+ "sdsWithDroppedChildren"
+ "seserviced.debug.report.endpoint.statistics"
+ "seserviced/SECServer+ClientInfo.swift"
+ "seserviced/SECUserSession.swift"
+ "simulateIncomingProvisioningWithOPURL:pairingPasswordExpiration:vehicleName:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:"
+ "storage.mock.snapshot"
+ "tcc"
+ "updatePreArmStateFor:"
+ "user initiated deletion"
+ "v92@0:8@16@24@32@40@48@56@64@72@80B88"
- "%s : %i : Attempting to create duplicate pending pairing for spotlightId: %@"
- "%s : %i : Missing spotlight identifier components"
- "%s : %i : Processed spotlight ID list is full (%lu), dropping new email"
- "%s : %i : Processed spotlight ID list is full (%lu), ignoring because of UD"
- "%s : %i : Removing expired processed spotlight ID: %@"
- "%s : %i : Spotlight ID %@ was already processed, ignoring because of UD"
- "%s : %i : Spotlight ID %@ was already processed, skipping"
- "+[KmlEndpointManager reportEndpointStatistics:identifier:]"
- "+[KmlEndpointManager reportEndpointStatistics:identifier:]_block_invoke"
- "-[KmlBiomeSubscriptionManager cleanupExpiredProcessedSpotlightIds]"
- "-[KmlBiomeSubscriptionManager simulateIncomingProvisioningWithOPURL:pairingPasswordExpiration:vehicleName:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:]"
- "-[KmlXpcService(PendingPairing) createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:callback:]"
- "-[KmlXpcService(PendingPairing) createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:callback:]"
- "Current Default Application with bundleID %s is installed with installType %lu"
- "Current Default Application with bundleID %s is not installed, LSApplicationRecord init error %s"
- "Ignoring unknown tag value %u for message in exchange"
- "Logging for peer Product ID %s, vendor ID %s, firmware version %s"
- "Unknown/Unsupported event TLV with tag: %u"
- "Vv104@0:8@\"NSURL\"16@\"NSDate\"24@\"NSString\"32@\"NSDate\"40@\"NSString\"48@\"NSString\"56@\"NSString\"64@\"NSDate\"72@\"NSString\"80B88B92@?<v@?@\"NSString\">96"
- "Vv104@0:8@16@24@32@40@48@56@64@72@80B88B92@?96"
- "Vv140@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32Q40@\"NSString\"48@\"NSString\"56@\"NSDate\"64@\"NSString\"72@\"NSDate\"80@\"NSString\"88@\"NSString\"96@\"NSString\"104@\"NSDate\"112@\"NSString\"120B128@?<v@?@\"NSString\">132"
- "Vv140@0:8@16@24@32Q40@48@56@64@72@80@88@96@104@112@120B128@?132"
- "[spotlightIdentifier: %@, source: %@, receivedDate: %@, language: %@]"
- "_processedSpotlightIds"
- "_spotlightIdentifier"
- "applicationState"
- "cleanupExpiredProcessedSpotlightIds"
- "computeShouldShowPanes: Error %s when initializing LSApplicationRecord for %s"
- "createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:callback:"
- "createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:callback:"
- "defaultAppCandidates: Error %s when initializing LSApplicationRecord for %s"
- "enumeratorWithOptions:"
- "iOS (27.0) - SecureElementService-70.39.1"
- "ignoreProcessedSpotlightIdCheck"
- "initWithOwnerPairingUrl:carBrand:alreadyProvisioned:carModel:carIdentifier:pairingCode:userIdentifier:provisioningCodeExpiration:spotlightUniqueIdentifier:spotlightDomainIdentifier:spotlightBundleIdentifier:dateSent:cccManufacturer:cccBrand:supportedTransports:sourceLanguage:"
- "installType"
- "isInstalled"
- "loadProcessedSpotlightIds"
- "nextObject"
- "objectForKey:ofClass:"
- "reconcileDatabaseAndTCCAccess()"
- "saveProcessedSpotlightIds"
- "simulateIncomingProvisioningWithOPURL:pairingPasswordExpiration:vehicleName:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:"
- "spotlightIdentifier"
- "updatePreArmState:for:"
- "v84@0:8@16@24@32@40@48@56@64@72B80"
```
