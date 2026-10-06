## AppManagedFeatures

> `/System/Library/Frameworks/AppManagedFeatures.framework/AppManagedFeatures`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x91f98` | `0x6dd10` | **`-0x24288`** |
| `__TEXT.__eh_frame` | `0xae68` | `0x73a0` | **`-0x3ac8`** |
| `__TEXT.__const` | `0x8370` | `0x6c40` | **`-0x1730`** |
| `__TEXT.__unwind_info` | `0x35c0` | `0x24e8` | **`-0x10d8`** |
| `__DATA.__bss` | `0x7600` | `0x7180` | **`-0x480`** |
| `__TEXT.__swift_as_cont` | `0xaf4` | `0x6f8` | **`-0x3fc`** |
| `__TEXT.__swift5_typeref` | `0x1a3b` | `0x16d9` | **`-0x362`** |
| `__TEXT.__swift_as_ret` | `0x780` | `0x454` | **`-0x32c`** |
| `__TEXT.__cstring` | `0x2153` | `0x2443` | **`+0x2f0`** |
| `__TEXT.__swift_as_entry` | `0x550` | `0x30c` | **`-0x244`** |
| `__TEXT.__constg_swiftt` | `0x133c` | `0x112c` | **`-0x210`** |
| `__TEXT.__swift5_acfuncs` | `0x640` | `0x460` | **`-0x1e0`** |
| `__TEXT.__objc_methlist` | `0xb4` | `0x19c` | **`+0xe8`** |
| `__AUTH_CONST.__const` | `0x3210` | `0x3130` | **`-0xe0`** |
| `__DATA_DIRTY.__objc_data` | `0xc8` | `—` | **`-0xc8`** |
| `__DATA_CONST.__objc_selrefs` | `0x130` | `0x1c8` | **`+0x98`** |
| `__AUTH.__data` | `0x788` | `0x6f8` | **`-0x90`** |
| `__TEXT.__swift5_reflstr` | `0xe4c` | `0xdcc` | **`-0x80`** |
| `__AUTH.__objc_data` | `0x190` | `0x140` | **`-0x50`** |
| `__TEXT.__swift5_fieldmd` | `0xf88` | `0xf44` | **`-0x44`** |
| `__AUTH_CONST.__auth_got` | `0x950` | `0x910` | **`-0x40`** |
| `__DATA_DIRTY.__data` | `0xe8` | `0xb0` | **`-0x38`** |
| `__TEXT.__swift5_assocty` | `0x2e0` | `0x2a8` | **`-0x38`** |
| `__AUTH_CONST.__objc_const` | `0x840` | `0x870` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x1d0` | `0x1a4` | **`-0x2c`** |
| `__DATA.__data` | `0xd40` | `0xd68` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x130` | `0x108` | **`-0x28`** |
| `__TEXT.__swift5_proto` | `0x3cc` | `0x3a8` | **`-0x24`** |
| `__DATA_CONST.__objc_protolist` | `0x8` | `0x28` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__DATA_CONST.__objc_protorefs` | `0x8` | `0x18` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x5e1` | `0x5d8` | **`-0x9`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x30` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x20` | `0x1c` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x124` | `0x120` | **`-0x4`** |

### Other Changes

```diff

-43.0.0.0.0
+46.0.1.0.0

-  Functions: 2522
-  Symbols:   656
-  CStrings:  231
+  Functions: 2049
+  Symbols:   636
+  CStrings:  254
Symbols:
+ __DATA__TtC18AppManagedFeatures10OSActivity
+ __IVARS__TtC18AppManagedFeatures10OSActivity
+ __METACLASS_DATA__TtC18AppManagedFeatures10OSActivity
+ __OBJC_$_PROP_LIST_NSObject
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSObject
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSObject
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSObject
+ __OBJC_$_PROTOCOL_REFS_OS_os_activity
+ __OBJC_LABEL_PROTOCOL_$_NSObject
+ __OBJC_LABEL_PROTOCOL_$_OS_os_activity
+ __OBJC_PROTOCOL_$_NSObject
+ __OBJC_PROTOCOL_$_OS_os_activity
+ __os_activity_create
+ _dlsym
+ _flat unique So14OS_os_activity_p
+ _os_activity_scope_enter
+ _os_activity_scope_leave
+ _swift_beginAccess
+ _swift_endAccess
+ _swift_getForeignTypeMetadata
+ _symbolic _____ 18AppManagedFeatures10OSActivityC
+ _symbolic _____ So25os_activity_scope_state_sV
+ _symbolic _____Sg_ABt 18AppManagedFeatures18ManagementProviderV
+ _symbolic ______AAt s6UInt64V
+ _symbolic ______p So14OS_os_activityP
+ _type_layout_string So25os_activity_scope_state_sV
- _OBJC_CLASS_$_NSObject
- _OBJC_CLASS_$__TtC18AppManagedFeatures20ActivationController
- _OBJC_METACLASS_$__TtC18AppManagedFeatures20ActivationController
- __DATA__TtC18AppManagedFeatures17TestingController
- __DATA__TtC18AppManagedFeatures20ActivationController
- __INSTANCE_METHODS__TtC18AppManagedFeatures20ActivationController
- __IVARS__TtC18AppManagedFeatures17$LegacyActivating
- __IVARS__TtC18AppManagedFeatures17TestingController
- __IVARS__TtC18AppManagedFeatures20ActivationController
- __METACLASS_DATA__TtC18AppManagedFeatures17TestingController
- __METACLASS_DATA__TtC18AppManagedFeatures20ActivationController
- ___unnamed_5
- __os_signpost_emit_with_name_impl
- _associated conformance 18AppManagedFeatures17$LegacyActivatingCyxG11Distributed01_F9ActorStubAaE0fG0
- _associated conformance 18AppManagedFeatures17$LegacyActivatingCyxG11Distributed0F5ActorAA0G6SystemAeFP_AE0fgH0
- _associated conformance 18AppManagedFeatures17$LegacyActivatingCyxG11Distributed0F5ActorAASH
- _associated conformance 18AppManagedFeatures17$LegacyActivatingCyxG11Distributed0F5ActorAAs12Identifiable
- _associated conformance 18AppManagedFeatures17$LegacyActivatingCyxGSHAASQ
- _associated conformance 18AppManagedFeatures17$LegacyActivatingCyxGs12IdentifiableAA2IDsAEP_SH
- _objc_retain_x23
- _swift_deletedAsyncMethodErrorTu
- _symbolic $s18AppManagedFeatures16LegacyActivatingP
- _symbolic SSx_____y__________G______p_____Rz_____RzlIetMHgTgrzo_ 18AppManagedFeatures13CodableResultO AA13EmptyResponseV AA0abC5ErrorO s0H0P AA10ActivatingP 11Distributed01_J9ActorStubP
- _symbolic SSx_____y__________G______p_____RzlIetWHgTgrzo_ 18AppManagedFeatures13CodableResultO AA13EmptyResponseV AA0abC5ErrorO s0H0P AA10ActivatingP
- _symbolic SaySSGA2Ax_____y__________G______p_____Rz_____RzlIetMHgTgTgTgrzo_ 18AppManagedFeatures13CodableResultO AA13EmptyResponseV AA0abC5ErrorO s0H0P AA8TestableP 11Distributed01_J9ActorStubP
- _symbolic SaySSGA2Ax_____y__________G______p_____RzlIetWHgTgTgTgrzo_ 18AppManagedFeatures13CodableResultO AA13EmptyResponseV AA0abC5ErrorO s0H0P AA8TestableP
- _symbolic _____ 18AppManagedFeatures17$LegacyActivatingC
- _symbolic _____ 18AppManagedFeatures17TestingControllerC
- _symbolic _____ 18AppManagedFeatures20ActivationControllerC
- _symbolic _____Sgx_____y__________G______p_____Rz_____RzlIetMHnTgrzo_ 18AppManagedFeatures18ManagementProviderV AA13CodableResultO AA13EmptyResponseV AA0abC5ErrorO s0J0P AA8TestableP 11Distributed01_L9ActorStubP
- _symbolic _____Sgx_____y__________G______p_____Rz_____RzlIetMHnTgrzo_ 18AppManagedFeatures25SoftwareUpdateRequirementV AA13CodableResultO AA13EmptyResponseV AA0abC5ErrorO s0K0P AA8TestableP 11Distributed01_M9ActorStubP
- _symbolic _____Sgx_____y__________G______p_____RzlIetWHnTgrzo_ 18AppManagedFeatures18ManagementProviderV AA13CodableResultO AA13EmptyResponseV AA0abC5ErrorO s0J0P AA8TestableP
- _symbolic _____Sgx_____y__________G______p_____RzlIetWHnTgrzo_ 18AppManagedFeatures25SoftwareUpdateRequirementV AA13CodableResultO AA13EmptyResponseV AA0abC5ErrorO s0K0P AA8TestableP
- _symbolic ______p 18AppManagedFeatures16LegacyActivatingP
- _symbolic ______pSg 18AppManagedFeatures8TestableP
- _symbolic _____ySSG 11Distributed18RemoteCallArgumentV
- _symbolic _____ySaySSGG 11Distributed18RemoteCallArgumentV
- _symbolic _____y_____G 18AppManagedFeatures17$LegacyActivatingC 14XPCDistributed9XPCSystemC
- _symbolic _____y_____SgG 11Distributed18RemoteCallArgumentV 18AppManagedFeatures18ManagementProviderV
- _symbolic _____y______pG 18AppManagedFeatures15ProxyControllerC AA16LegacyActivatingP
- _symbolic x_____ySSSg_____G______p_____Rz_____RzlIetMHgrzo_ 18AppManagedFeatures13CodableResultO AA0abC5ErrorO s0F0P AA10ActivatingP 11Distributed01_H9ActorStubP
- _symbolic x_____ySSSg_____G______p_____RzlIetWHgrzo_ 18AppManagedFeatures13CodableResultO AA0abC5ErrorO s0F0P AA10ActivatingP
- _symbolic x_____ySb_____G______p_____Rz_____RzlIetMHgrzo_ 18AppManagedFeatures13CodableResultO AA0abC5ErrorO s0F0P AA8TestableP 11Distributed01_H9ActorStubP
- _symbolic x_____ySb_____G______p_____RzlIetWHgrzo_ 18AppManagedFeatures13CodableResultO AA0abC5ErrorO s0F0P AA8TestableP
- _symbolic x_____y_____Sg_____G______p_____Rz_____RzlIetMHgrzo_ 18AppManagedFeatures13CodableResultO AA25SoftwareUpdateRequirementV AA0abC5ErrorO s0I0P AA8TestableP 11Distributed01_K9ActorStubP
- _symbolic x_____y_____Sg_____G______p_____RzlIetWHgrzo_ 18AppManagedFeatures13CodableResultO AA25SoftwareUpdateRequirementV AA0abC5ErrorO s0I0P AA8TestableP
CStrings:
+ "Activate"
+ "AppManagedFeatures/OSActivity.swift"
+ "Archived Configuration"
+ "Configuration"
+ "Deactivate"
+ "Failed to create OS Activity"
+ "FetchManagementProvider"
+ "NSContactsUsageDescription"
+ "NSHealthClinicalHealthRecordsShareUsageDescription"
+ "NSHealthShareUsageDescription"
+ "NSHealthUpdateUsageDescription"
+ "NSHomeKitUsageDescription"
+ "NSMicrophoneUsageDescription"
+ "NSMotionUsageDescription"
+ "NSPhotoLibraryAddUsageDescription"
+ "NSPhotoLibraryUsageDescription"
+ "NSSpeechRecognitionUsageDescription"
+ "NSUserTrackingUsageDescription"
+ "PrepareForBuddyEnrollment"
+ "Production configurations cannot be modified on customer builds."
+ "Remove Configuration"
+ "Reseller ID cannot be empty."
+ "Set Configuration"
+ "TestingManager clearDEPServerConfigurationOverride()"
+ "TestingManager clearPushToken"
+ "TestingManager depServerConfigurationOverride()"
+ "TestingManager disableAllSystemTasks()"
+ "TestingManager enableBootstrapTask()"
+ "TestingManager forcedExtensionBundleIdentifier()"
+ "TestingManager pushToken"
+ "TestingManager removeArchivedManagementProvider()"
+ "TestingManager set(testingOptions:)"
+ "TestingManager setDEPServerConfigurationOverride(_:)"
+ "TestingManager setForcedExtension(bundleIdentifier:)"
+ "TestingManager testingOptions()"
+ "The caller is not the current managent provider app and cannot use AppManagedFeatures."
+ "The provider app should not have a watch extension."
+ "This function is not available on a customer device."
+ "TriggerCheckIn"
+ "_os_activity_current"
+ "isLocked"
+ "isLocked called"
+ "lock"
+ "providerAppContainsWatchExtension"
+ "resellerID"
+ "setSoftwareUpdateRequirement"
+ "setSoftwareUpdateRequirement called with OS: %{public}s"
+ "settings-navigation://com.apple.Settings.General/APP_MANAGED_FEATURES"
+ "shouldLaunchSetupAssistant()"
+ "softwareUpdateRequirement"
+ "unlock"
- "AppManagedFeatures-isLocked"
- "AppManagedFeatures-setSoftwareUpdateRequirement"
- "AppManagedFeatures-softwareUpdateRequirement"
- "AppManagedFeatures/TestingController.swift"
- "Developer mode is not active. This operation requires developer mode."
- "Proxy was expected but was not found"
- "[Error] Interval already ended"
- "activateDeveloperMode(bundleID:)"
- "archiveManagementProvider()"
- "com.apple.private.safefinancing"
- "com.apple.private.safefinancing.testing"
- "com.apple.safefinancing.activation"
- "com.apple.safefinancing.testing"
- "deactivateDeveloperMode()"
- "denyAdditionalApplicationsWithBundleIdentifiers"
- "developerModeBundleID()"
- "excludingApplicationsWithBundleIdentifiers"
- "heartbeatInterval()"
- "internalDeactivate()"
- "internalLock(excludingApplicationsWithBundleIdentifiers:denyAdditionalApplicationsWithBundleIdentifers:)"
- "internalSetSoftwareUpdateRequirement(_:)"
- "internalSoftwareUpdateRequirement()"
- "isLocked called."
- "requireSoftwareUpdate called with OS: %{public}s"
- "retrieveAndStoreCloudConfiguration()"
- "retrieveAndStoreConfiguration()"
- "setHeartbeat(interval:)"
- "settings-navigation://com.apple.Settings.General/SAFE_FINANCING"
```
