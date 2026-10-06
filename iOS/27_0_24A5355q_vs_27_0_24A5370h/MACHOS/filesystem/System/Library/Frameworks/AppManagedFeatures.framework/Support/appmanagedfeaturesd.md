## appmanagedfeaturesd

> `/System/Library/Frameworks/AppManagedFeatures.framework/Support/appmanagedfeaturesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80a4c` | `0x6f770` | **`-0x112dc`** |
| `__TEXT.__eh_frame` | `0x68f8` | `0x58f8` | **`-0x1000`** |
| `__TEXT.__const` | `0x39ac` | `0x2eac` | **`-0xb00`** |
| `__TEXT.__unwind_info` | `0x1fd0` | `0x1858` | **`-0x778`** |
| `__TEXT.__cstring` | `0x15fc` | `0x1071` | **`-0x58b`** |
| `__DATA_CONST.__const` | `0x1d60` | `0x17e0` | **`-0x580`** |
| `__TEXT.__oslogstring` | `0x4183` | `0x3d43` | **`-0x440`** |
| `__DATA.__data` | `0x15b0` | `0x13c8` | **`-0x1e8`** |
| `__TEXT.__swift5_typeref` | `0xcb1` | `0xb3f` | **`-0x172`** |
| `__TEXT.__objc_stubs` | `0x1000` | `0x1140` | **`+0x140`** |
| `__TEXT.__swift_as_cont` | `0x5e4` | `0x4d4` | **`-0x110`** |
| `__TEXT.__swift5_capture` | `0x66c` | `0x578` | **`-0xf4`** |
| `__DATA.__objc_const` | `0xad0` | `0x9e0` | **`-0xf0`** |
| `__TEXT.__swift5_acfuncs` | `0x320` | `0x230` | **`-0xf0`** |
| `__TEXT.__constg_swiftt` | `0x930` | `0x844` | **`-0xec`** |
| `__TEXT.__swift_as_ret` | `0x3cc` | `0x2f4` | **`-0xd8`** |
| `__TEXT.__objc_methname` | `0x11fd` | `0x12cd` | **`+0xd0`** |
| `__DATA_CONST.__auth_ptr` | `0x7a0` | `0x6e0` | **`-0xc0`** |
| `__TEXT.__swift_as_entry` | `0x360` | `0x2a0` | **`-0xc0`** |
| `__TEXT.__auth_stubs` | `0x1eb0` | `0x1f40` | **`+0x90`** |
| `__DATA.__bss` | `0x1f00` | `0x1e80` | **`-0x80`** |
| `__DATA.__objc_selrefs` | `0x518` | `0x568` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0xf60` | `0xfa8` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x540` | `0x4fc` | **`-0x44`** |
| `__TEXT.__objc_classname` | `0x2ba` | `0x27a` | **`-0x40`** |
| `__TEXT.__objc_methtype` | `0x5c6` | `0x596` | **`-0x30`** |
| `__TEXT.__swift5_builtin` | `0x3c` | `0x28` | **`-0x14`** |
| `__DATA_CONST.__objc_protolist` | `0x48` | `0x38` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x507` | `0x4f7` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x748` | `0x750` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x50` | `0x48` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x28` | `0x20` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x78` | `0x70` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0xf8` | `0xf4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-43.0.0.0.0
+46.0.1.0.0

+  - /System/Library/PrivateFrameworks/InstallCoordination.framework/InstallCoordination

-  Functions: 1537
-  Symbols:   943
-  CStrings:  686
+  Functions: 1352
+  Symbols:   927
+  CStrings:  634
Symbols:
+ _$s10Foundation22_convertErrorToNSErrorySo0E0Cs0C0_pF
+ _$s10Foundation6LocaleV10identifierACSS_tcfC
+ _$s10Foundation6LocaleV19_bridgeToObjectiveCSo8NSLocaleCyF
+ _$s10Foundation6LocaleVMa
+ _$s10Foundation8TimeZoneV10identifierACSgSSh_tcfC
+ _$s10Foundation8TimeZoneVMn
+ _$s14XPCDistributed9XPCSystemC29currentRemoteInvocationOriginAC7SessionC0D9InterfaceVSgyFZ
+ _$s14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceVMa
+ _$s14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceVMn
+ _$s18AppManagedFeatures0abC5ErrorO12notAvailableyA2CmFWC
+ _$s18AppManagedFeatures0abC5ErrorO13notAuthorizedyA2CmFWC
+ _$s18AppManagedFeatures0abC5ErrorO29prohibitedWatchExtensionFoundyA2CmFWC
+ _$s18AppManagedFeatures0abC9ConstantsO15isInternalBuildSbvgZ
+ _$s18AppManagedFeatures0abC9ConstantsO23ProhibitedInfoPlistKeysO3allShySSGvgZ
+ _$s18AppManagedFeatures10OSActivityC5namedACs12StaticStringV_tcfc
+ _$s18AppManagedFeatures10OSActivityC5startyyFTj
+ _$s18AppManagedFeatures10OSActivityCMa
+ _$s18AppManagedFeatures16EligibilityCheckV16isDeviceEligibleSbyFZ
+ _$s18AppManagedFeatures18ConfigurationErrorO23reservedDeveloperAdamIDyA2CmFWC
+ _$s18AppManagedFeatures18ConfigurationErrorOMa
+ _$sSa11descriptionSSvg
+ _$sSh10FoundationE36_unconditionallyBridgeFromObjectiveCyShyxGSo5NSSetCSgFZ
+ _$sSh8IteratorV6_cocoaAByx_Gs10__CocoaSetVAACn_tcfC
+ _$sSis23CustomStringConvertiblesWP
+ _$ss15ContiguousArrayV28_allocateBufferUninitialized15minimumCapacitys01_abD0VyxGSi_tFZ
+ _$ss22_minimumMergeRunLengthyS2iF
+ _IXErrorDomain
+ _NSLocalizedDescriptionKey
+ _NSUnderlyingErrorKey
+ _OBJC_CLASS_$_IXAppInstallCoordinator
+ _OBJC_CLASS_$_IXApplicationIdentity
+ _OBJC_CLASS_$_NSDateFormatter
+ _swift_release_x3
+ _swift_retain_x27
+ _swift_retain_x28
+ _swift_willThrowTypedImpl
- _$s14XPCDistributed9XPCSystemC7SessionC14LocalInterfaceV022activateThenWithRemoteE07performx6result_AG15ActivationTokenV5tokentxAE0iE0VYaXE_tYas8SendableRzlF
- _$s14XPCDistributed9XPCSystemC7SessionC14LocalInterfaceV022activateThenWithRemoteE07performx6result_AG15ActivationTokenV5tokentxAE0iE0VYaXE_tYas8SendableRzlFTu
- _$s14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV7sessionAEvg
- _$s14XPCDistributed9XPCSystemC7SessionC19waitForCancellationyyYaF
- _$s14XPCDistributed9XPCSystemC7SessionC19waitForCancellationyyYaFTu
- _$s14XPCDistributed9XPCSystemC7SessionC6cancel7becauseySS_tF
- _$s18AppManagedFeatures0abC9ConstantsO12EntitlementsO13legacyTestingyA2EmFWC
- _$s18AppManagedFeatures0abC9ConstantsO12EntitlementsO16legacyActivationyA2EmFWC
- _$s18AppManagedFeatures0abC9ConstantsO15PlaceholderURLsO13developerLogoyA2EmFWC
- _$s18AppManagedFeatures0abC9ConstantsO15PlaceholderURLsO8rawValueSSvg
- _$s18AppManagedFeatures0abC9ConstantsO15PlaceholderURLsOMa
- _$s18AppManagedFeatures0abC9ConstantsO16MachServiceNamesO013legacyTestingF4NameyA2EmFWC
- _$s18AppManagedFeatures0abC9ConstantsO16MachServiceNamesO016legacyActivationF4NameyA2EmFWC
- _$s18AppManagedFeatures0abC9ConstantsO23ProhibitedInfoPlistKeysO8locationSaySSGvgZ
- _$s18AppManagedFeatures10ActivatingP21activateDeveloperMode8bundleIDAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGSS_tYaFTq
- _$s18AppManagedFeatures10ActivatingP21activateDeveloperMode8bundleIDAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGSS_tYaKFTqTE
- _$s18AppManagedFeatures10ActivatingP21developerModeBundleIDAA13CodableResultOySSSgAA0abC5ErrorOGyYaFTq
- _$s18AppManagedFeatures10ActivatingP21developerModeBundleIDAA13CodableResultOySSSgAA0abC5ErrorOGyYaKFTqTE
- _$s18AppManagedFeatures10ActivatingP23deactivateDeveloperModeAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGyYaFTq
- _$s18AppManagedFeatures10ActivatingP23deactivateDeveloperModeAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGyYaKFTqTE
- _$s18AppManagedFeatures10ActivatingP29retrieveAndStoreConfigurationAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGyYaFTq
- _$s18AppManagedFeatures10ActivatingP29retrieveAndStoreConfigurationAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGyYaKFTqTE
- _$s18AppManagedFeatures16LegacyActivatingMp
- _$s18AppManagedFeatures16LegacyActivatingPAA0E0Tb
- _$s18AppManagedFeatures16LegacyActivatingPAA11ConfiguringTb
- _$s18AppManagedFeatures17$LegacyActivatingCMn
- _$s18AppManagedFeatures17$LegacyActivatingCyxG11Distributed01_F9ActorStubAAMc
- _$s18AppManagedFeatures18ManagementProviderV17developerBundleID7logoURL8longName4name012organizationH011phoneNumberACSS_10Foundation0J0VS4StKcfC
- _$s18AppManagedFeatures8TestableP12internalLock42excludingApplicationsWithBundleIdentifiers014denyAdditionalhijK00G10WebDomainsAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGSaySSG_A2OtYaFTq
- _$s18AppManagedFeatures8TestableP12internalLock42excludingApplicationsWithBundleIdentifiers014denyAdditionalhijK00G10WebDomainsAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGSaySSG_A2OtYaKFTqTE
- _$s18AppManagedFeatures8TestableP14internalUnlockAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGyYaFTq
- _$s18AppManagedFeatures8TestableP14internalUnlockAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGyYaKFTqTE
- _$s18AppManagedFeatures8TestableP16internalIsLockedAA13CodableResultOySbAA0abC5ErrorOGyYaFTq
- _$s18AppManagedFeatures8TestableP16internalIsLockedAA13CodableResultOySbAA0abC5ErrorOGyYaKFTqTE
- _$s18AppManagedFeatures8TestableP18internalDeactivateAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGyYaFTq
- _$s18AppManagedFeatures8TestableP18internalDeactivateAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGyYaKFTqTE
- _$s18AppManagedFeatures8TestableP21setManagementProvideryAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGAA0fG0VSgYaFTq
- _$s18AppManagedFeatures8TestableP21setManagementProvideryAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGAA0fG0VSgYaKFTqTE
- _$s18AppManagedFeatures8TestableP25archiveManagementProviderAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGyYaFTq
- _$s18AppManagedFeatures8TestableP25archiveManagementProviderAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGyYaKFTqTE
- _$s18AppManagedFeatures8TestableP33internalSoftwareUpdateRequirementAA13CodableResultOyAA0fgH0VSgAA0abC5ErrorOGyYaFTq
- _$s18AppManagedFeatures8TestableP33internalSoftwareUpdateRequirementAA13CodableResultOyAA0fgH0VSgAA0abC5ErrorOGyYaKFTqTE
- _$s18AppManagedFeatures8TestableP36internalSetSoftwareUpdateRequirementyAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGAA0ghI0VSgYaFTq
- _$s18AppManagedFeatures8TestableP36internalSetSoftwareUpdateRequirementyAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGAA0ghI0VSgYaKFTqTE
- _$sSayxGSEsSERzlMc
- _$sSayxGSesSeRzlMc
- __os_activity_create
- _dlsym
- _os_activity_scope_enter
- _os_activity_scope_leave
- _os_variant_allows_internal_security_policies
- _swift_retain_x8
CStrings:
+ "Caller is not authorized."
+ "Caller is not the provider bundle id"
+ "Caller is the provider bundle id"
+ "CancelRestoringCoordinator"
+ "Cancelled existing coordinator for %{public}s"
+ "Cancelling coordinator for %{public}s failed: %{public}@"
+ "Cancelling coordinator for %{public}s..."
+ "Device has no PF bit and is not in PF DEP. We will not send pushtoken to DEP."
+ "Failed to cancel existing coordinator for %{public}s: %{public}@"
+ "Failed to create IXApplicationIdentity for %{public}s"
+ "No existing coordinator for %{public}s, proceeding"
+ "Provider app %{public}s contains a legacy WatchKit extension"
+ "Provider app %{public}s declares prohibited TCC keys: %{public}s"
+ "Provider app %{public}s has watch counterpart(s): %{public}s"
+ "Provider app does not have watch extension/counterpart"
+ "SetSoftwareUpdateRequirementFlow"
+ "The DEP provided cloud configuration has an adamID of zero. This is a non-customer, devloper configuration. The cloud configuration will be ignored."
+ "The device does not have a PF activation bit. We will not check DEP for removal of PF activaiton."
+ "Validating provider app for prohibited watch extension/counterpart: %{public}s"
+ "applicationExtensionRecords"
+ "appmanagedfeaturesd is taking over installation of mandatory app "
+ "appmanagedfeaturesd-isLocked"
+ "appmanagedfeaturesd-setSoftwareUpdateRequirement"
+ "appmanagedfeaturesd-softwareUpdateRequirement"
+ "cancelCoordinatorForAppWithIdentity:withReason:client:error:"
+ "com.apple.appmanagedfeaturesd"
+ "com.apple.watchkit"
+ "counterpartIdentifiers"
+ "extensionPointRecord"
+ "identifier"
+ "initWithDomain:code:userInfo:"
+ "objectForKey:"
+ "setDateFormat:"
+ "setDenySiri3489:"
+ "setLocale:"
+ "softwareUpdateRequirementFlow"
+ "userInfo"
- " Developer Testing"
- "Activate"
- "ActivateDeveloperMode"
- "Activating developer mode via activation service for bundleID: %{public}s"
- "Archive Management Provider"
- "Archived Configuration"
- "Archived existing local configuration."
- "Caller is not the financing provider app"
- "Cannot activate developer mode: a configuration already exists. Deactivate or remove the existing configuration before activating developer mode."
- "Cannot activate developer mode: bundleID is empty"
- "Configuration"
- "DeactivateDeveloperMode"
- "Deactivating developer mode via activation service"
- "Deactivating device via testing service"
- "Developer Provider"
- "Developer mode deactivated successfully"
- "Developer mode is active but developerBundleID is nil in daemon defaults"
- "Failed to archive management provider: %{public}@"
- "Failed to read provider during developerModeBundleID: %{public}@"
- "Failed to write management provider to file: %{public}@"
- "Internal isLocked"
- "Legacy Activation"
- "Legacy DEP check-in handler called! It will not be rescheduled."
- "Legacy DEPCheckIn"
- "Legacy Heartbeat"
- "Legacy Push Token Update handler called! It will not be rescheduled."
- "Legacy PushTokenUpdate"
- "Lock"
- "Lock device called via Testing Service"
- "No configuration fetched from the server."
- "No financing provider found, nothing to do."
- "No local configuration to archive."
- "OS_os_activity"
- "PrepareForBuddyEnrollment"
- "Provider app %{public}s declares prohibited TCC key: %{public}s"
- "Remove Archived Management Provider"
- "Remove Configuration"
- "Restrictions Service XPC listener failed: %{public}@"
- "Restrictions XPC System"
- "RetrieveCloudConfigurationAndStore"
- "SafeFinancing Error during deactivation: %{public}@"
- "SafeFinancing Error during developer mode activation: %{public}@"
- "SafeFinancing Error during developer mode deactivation: %{public}@"
- "SafeFinancing Error while enabling limited mode: %{public}@"
- "SafeFinancing Error while reading software update requirement: %{public}@"
- "SafeFinancing Error while setting software update requirement: %{public}@"
- "Set Configuration"
- "Successfully archived management provider"
- "Successfully stored a cloud configuration."
- "TestingService Lock"
- "TestingService Unlock"
- "TestingService clearDEPServerConfigurationOverride()"
- "TestingService clearPushToken"
- "TestingService depServerConfigurationOverride()"
- "TestingService disableAllSystemTasks()"
- "TestingService enableBootstrapTask()"
- "TestingService pushToken"
- "TestingService set(testingOptions:)"
- "TestingService setDEPServerConfigurationOverride(_:)"
- "TestingService setForcedExtension(bundleIdentifier:)"
- "TestingService setSoftwareUpdateRequirement"
- "TestingService softwareUpdateRequirement"
- "TestingService testingOptions()"
- "There was an unknown error setting limited mode on the device: %{public}@"
- "TriggerCheckIn"
- "Unknown error during developer mode activation: %{public}@"
- "Unknown error during developer mode deactivation: %{public}@"
- "Unlock"
- "Unlock device called via Testing Service"
- "_TtC19appmanagedfeaturesd10OSActivity"
- "_os_activity_current"
- "activity"
- "activityState"
- "appmanagedfeaturesd-deactivate-developer-mode"
- "com.apple.safefinancing.depcheckin"
- "com.apple.safefinancing.heartbeat"
- "com.apple.safefinancing.pushtoken.update"
- "deactivateDeveloperMode called but developer mode is not active"
- "deleteStore"
- "denyAdditionalApplicationsWithBundleIdentifiers"
- "excludingApplicationsWithBundleIdentifiers"
- "excludingWebDomains"
- "fetchManagementProvider"
- "isLocked"
- "isLocked device called via testing Service"
- "setSoftwareUpdateRequirement"
- "setSoftwareUpdateRequirement called via TestingService"
- "softwareUpdateRequirement"
- "softwareUpdateRequirement called via TestingService"
```
