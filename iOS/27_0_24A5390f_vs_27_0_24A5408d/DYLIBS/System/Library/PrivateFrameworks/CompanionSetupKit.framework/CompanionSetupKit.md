## CompanionSetupKit

> `/System/Library/PrivateFrameworks/CompanionSetupKit.framework/CompanionSetupKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x40b1bc` | `0x429090` | **`+0x1ded4`** |
| `__TEXT.__eh_frame` | `0x35618` | `0x36c38` | **`+0x1620`** |
| `__DATA.__bss` | `0x45300` | `0x46290` | **`+0xf90`** |
| `__TEXT.__const` | `0x2d240` | `0x2e090` | **`+0xe50`** |
| `__TEXT.__oslogstring` | `0x8a75` | `0x9325` | **`+0x8b0`** |
| `__AUTH_CONST.__const` | `0x18968` | `0x191e8` | **`+0x880`** |
| `__TEXT.__unwind_info` | `0x127b0` | `0x12da0` | **`+0x5f0`** |
| `__TEXT.__cstring` | `0xb93d` | `0xbe4d` | **`+0x510`** |
| `__TEXT.__swift5_reflstr` | `0x7b3e` | `0x7f9e` | **`+0x460`** |
| `__TEXT.__swift5_capture` | `0x370c` | `0x3a30` | **`+0x324`** |
| `__TEXT.__swift5_fieldmd` | `0x90ac` | `0x93b0` | **`+0x304`** |
| `__TEXT.__swift5_typeref` | `0x9880` | `0x9b3c` | **`+0x2bc`** |
| `__DATA.__data` | `0x8ab8` | `0x8cd0` | **`+0x218`** |
| `__TEXT.__constg_swiftt` | `0x6990` | `0x6b1c` | **`+0x18c`** |
| `__TEXT.__swift_as_cont` | `0x3634` | `0x37a0` | **`+0x16c`** |
| `__TEXT.__objc_methlist` | `0x108c` | `0xf8c` | **`-0x100`** |
| `__TEXT.__swift_as_entry` | `0x10ec` | `0x1184` | **`+0x98`** |
| `__AUTH.__objc_data` | `0x1c90` | `0x1d20` | **`+0x90`** |
| `__AUTH_CONST.__auth_got` | `0x2528` | `0x25b8` | **`+0x90`** |
| `__TEXT.__swift5_assocty` | `0x1510` | `0x15a0` | **`+0x90`** |
| `__TEXT.__swift_as_ret` | `0x15d4` | `0x1658` | **`+0x84`** |
| `__AUTH_CONST.__objc_const` | `0x7110` | `0x7190` | **`+0x80`** |
| `__TEXT.__swift5_proto` | `0x2290` | `0x230c` | **`+0x7c`** |
| `__DATA_CONST.__const` | `0x11e8` | `0x1250` | **`+0x68`** |
| `__TEXT.__swift5_builtin` | `0x294` | `0x2d0` | **`+0x3c`** |
| `__AUTH.__data` | `0x5520` | `0x5558` | **`+0x38`** |
| `__TEXT.__swift5_types` | `0xa90` | `0xabc` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0x1318` | `0x1338` | **`+0x20`** |
| `__TEXT.__swift5_mpenum` | `0xd0` | `0xec` | **`+0x1c`** |
| `__DATA.__common` | `0x3c8` | `0x3e0` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x118` | `0x108` | **`-0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x80` | `0x78` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x18b8` | `0x18c0` | **`+0x8`** |

### Other Changes

```diff

-524.0.38.0.0
+524.0.56.0.0

+  - /System/Library/PrivateFrameworks/AttentionAwareness.framework/AttentionAwareness

+  - /System/Library/PrivateFrameworks/MDMClientLibrary.framework/MDMClientLibrary

-  Functions: 18015
-  Symbols:   4935
-  CStrings:  2333
+  Functions: 18453
+  Symbols:   5015
+  CStrings:  2414
Symbols:
+ _IOHIDEventGetIntegerValue
+ _IOHIDEventSystemClientActivate
+ _IOHIDEventSystemClientCancel
+ _IOHIDEventSystemClientCreate
+ _IOHIDEventSystemClientRegisterEventBlock
+ _IOHIDEventSystemClientSetDispatchQueue
+ _IOHIDEventSystemClientSetMatching
+ _MCProfileListChangedNotification
+ _OBJC_CLASS_$_AWAttentionAwarenessClient
+ _OBJC_CLASS_$_AWAttentionAwarenessConfiguration
+ _OBJC_CLASS_$_MDMCloudConfiguration
+ _OBJC_CLASS_$__TtC17CompanionSetupKit23CSKStepTVProviderServer
+ _OBJC_METACLASS_$__TtC17CompanionSetupKit23CSKStepTVProviderServer
+ __DATA__TtC17CompanionSetupKit28CSKAttentionAwarenessMonitor
+ __IVARS__TtC17CompanionSetupKit28CSKAttentionAwarenessMonitor
+ __METACLASS_DATA__TtC17CompanionSetupKit28CSKAttentionAwarenessMonitor
+ __OBJC_$_INSTANCE_METHODS__TtC17CompanionSetupKit23CSKStepTVProviderServer(CompanionSetupKit)
+ __OBJC_CLASS_PROTOCOLS_$__TtC17CompanionSetupKit23CSKStepTVProviderServer(CompanionSetupKit)
+ ___swift_closure_destructor.110Tm
+ ___swift_closure_destructor.144Tm
+ ___swift_closure_destructor.160Tm
+ ___swift_closure_destructor.196Tm
+ ___swift_closure_destructor.294Tm
+ ___swift_closure_destructor.321Tm
+ ___swift_closure_destructor.396Tm
+ ___swift_closure_destructor.422Tm
+ ___swift_closure_destructor.426Tm
+ ___swift_closure_destructor.445Tm
+ ___swift_closure_destructor.468Tm
+ ___swift_memcpy312_8
+ ___swift_memcpy497_8
+ ___swift_memcpy96_8
+ ___unnamed_61
+ _associated conformance 17CompanionSetupKit21CSKCloudConfigManagerC14CoreUtilsSwift15CUEventReporterAA5EventAdEP_s23CustomStringConvertible
+ _associated conformance 17CompanionSetupKit21CSKCloudConfigManagerC14CoreUtilsSwift15CUEventReporterAAScA
+ _associated conformance 17CompanionSetupKit21CSKCloudConfigManagerC14CoreUtilsSwift15CUEventReporterAaD15CUEnvironmental
+ _associated conformance 17CompanionSetupKit21CSKSetupAppleTVServerC7CommandO38ActivationFailedAcknowledgedCodingKeys33_D80D7C23C92088CF46EDAF3CD79D0C6DLLOs0K3KeyAAs23CustomStringConvertible
+ _associated conformance 17CompanionSetupKit21CSKSetupAppleTVServerC7CommandO38ActivationFailedAcknowledgedCodingKeys33_D80D7C23C92088CF46EDAF3CD79D0C6DLLOs0K3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 17CompanionSetupKit23CSKStepWiFiPickerServerC7CommandO31Wifi5GHzConsentAnswerCodingKeys33_586B52E5DC74D75E055C7BE9E0193607LLOSHAASQ
+ _associated conformance 17CompanionSetupKit23CSKStepWiFiPickerServerC7CommandO31Wifi5GHzConsentAnswerCodingKeys33_586B52E5DC74D75E055C7BE9E0193607LLOs0N3KeyAAs23CustomStringConvertible
+ _associated conformance 17CompanionSetupKit23CSKStepWiFiPickerServerC7CommandO31Wifi5GHzConsentAnswerCodingKeys33_586B52E5DC74D75E055C7BE9E0193607LLOs0N3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 17CompanionSetupKit28CSKAttentionAwarenessMonitorC13ConfigurationV5StageVSHAASQ
+ _associated conformance 17CompanionSetupKit28CSKAttentionAwarenessMonitorC14CoreUtilsSwift15CUEventReporterAA5EventAdEP_s23CustomStringConvertible
+ _associated conformance 17CompanionSetupKit28CSKAttentionAwarenessMonitorC14CoreUtilsSwift15CUEventReporterAAScA
+ _associated conformance 17CompanionSetupKit28CSKAttentionAwarenessMonitorC14CoreUtilsSwift15CUEventReporterAaD15CUEnvironmental
+ _associated conformance So18NSNotificationNameaSHSCSQ
+ _associated conformance So18NSNotificationNameas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So18NSNotificationNameas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _associated conformance So25IOHIDEventSystemClientRefa14CoreFoundation9_CFObjectSCSH
+ _associated conformance So25IOHIDEventSystemClientRefaSHSCSQ
+ _get_enum_tag_for_layout_string 17CompanionSetupKit23CSKStepWiFiPickerServerC5EventO
+ _get_enum_tag_for_layout_string 17CompanionSetupKit23CSKStepWiFiPickerServerC7CommandO
+ _keypath_get.83Tm
+ _keypath_set.21Tm
+ _keypath_set.23Tm
+ _swift_asyncLet_begin
+ _swift_asyncLet_finish
+ _swift_asyncLet_get
+ _swift_task_immediate
+ _swift_task_isCurrentExecutorWithFlags
+ _symbolic SDySSSo26AWAttentionAwarenessClientCG
+ _symbolic SDy__________y______GG s6UInt64V ScS12ContinuationV 17CompanionSetupKit21CSKCloudConfigManagerC5EventO
+ _symbolic SDy__________y______GG s6UInt64V ScS12ContinuationV 17CompanionSetupKit28CSKAttentionAwarenessMonitorC5EventO
+ _symbolic SS11networkName_t
+ _symbolic SS5stage_t
+ _symbolic Say_____G 14CoreUtilsSwift20CUDarwinNotificationC
+ _symbolic Say_____G 17CompanionSetupKit28CSKAttentionAwarenessMonitorC13ConfigurationV5StageV
+ _symbolic Say_____G So18NSNotificationNamea
+ _symbolic Sb5allow_t
+ _symbolic ScCyyt_____GSg s5NeverO
+ _symbolic _____ 17CompanionSetupKit21CSKCloudConfigManagerC5EventO
+ _symbolic _____ 17CompanionSetupKit21CSKSetupAppleTVServerC7CommandO38ActivationFailedAcknowledgedCodingKeys33_D80D7C23C92088CF46EDAF3CD79D0C6DLLO
+ _symbolic _____ 17CompanionSetupKit23CSKStepTVProviderServerC16STBConfigurationV
+ _symbolic _____ 17CompanionSetupKit23CSKStepWiFiPickerServerC7CommandO31Wifi5GHzConsentAnswerCodingKeys33_586B52E5DC74D75E055C7BE9E0193607LLO
+ _symbolic _____ 17CompanionSetupKit28CSKAttentionAwarenessMonitorC
+ _symbolic _____ 17CompanionSetupKit28CSKAttentionAwarenessMonitorC13ConfigurationV
+ _symbolic _____ 17CompanionSetupKit28CSKAttentionAwarenessMonitorC13ConfigurationV5StageV
+ _symbolic _____ 17CompanionSetupKit28CSKAttentionAwarenessMonitorC5EventO
+ _symbolic _____ 17CompanionSetupKit36WiFi5GHzConsentStateCUEnvironmentKey33_DA57089C6A017D73FA933B97B823EA87LLV
+ _symbolic _____ 17CompanionSetupKit39WiFi5GHzConsentRequiredCUEnvironmentKey33_DA57089C6A017D73FA933B97B823EA87LLV
+ _symbolic _____ So18NSNotificationNamea
+ _symbolic _____Sg 17CompanionSetupKit21CSKCloudConfigManagerC5EventO
+ _symbolic _____Sg 17CompanionSetupKit21CSKCloudConfigManagerC5StateV
+ _symbolic _____Sg 17CompanionSetupKit28CSKAttentionAwarenessMonitorC
+ _symbolic _____Sg So25IOHIDEventSystemClientRefa
+ _symbolic _____SgXw 17CompanionSetupKit21CSKCloudConfigManagerC
+ _symbolic _____SgXw 17CompanionSetupKit28CSKAttentionAwarenessMonitorC
+ _symbolic _____SgXwz_Xx 17CompanionSetupKit18CSKStepHelloServerC
+ _symbolic _____SgXwz_Xx 17CompanionSetupKit21CSKCloudConfigManagerC
+ _symbolic _____SgXwz_Xx 17CompanionSetupKit23CSKStepTVProviderServerC
+ _symbolic _____SgXwz_Xx 17CompanionSetupKit28CSKAttentionAwarenessMonitorC
+ _symbolic _____XDXMT 17CompanionSetupKit16CSKLocaleManagerC
+ _symbolic _____XDXMT 17CompanionSetupKit23CSKStepTVProviderServerC
+ _symbolic ___________y______Gt s6UInt64V ScS12ContinuationV 17CompanionSetupKit21CSKCloudConfigManagerC5EventO
+ _symbolic _____ySSSo26AWAttentionAwarenessClientCG s18_DictionaryStorageC
+ _symbolic _____ySo21VSSetupFlowControllerCG 14CoreUtilsSwift17CUSendableWrapperV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 17CompanionSetupKit21CSKSetupAppleTVServerC7CommandO38ActivationFailedAcknowledgedCodingKeys33_D80D7C23C92088CF46EDAF3CD79D0C6DLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 17CompanionSetupKit23CSKStepWiFiPickerServerC7CommandO31Wifi5GHzConsentAnswerCodingKeys33_586B52E5DC74D75E055C7BE9E0193607LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 17CompanionSetupKit21CSKSetupAppleTVServerC7CommandO38ActivationFailedAcknowledgedCodingKeys33_D80D7C23C92088CF46EDAF3CD79D0C6DLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 17CompanionSetupKit23CSKStepWiFiPickerServerC7CommandO31Wifi5GHzConsentAnswerCodingKeys33_586B52E5DC74D75E055C7BE9E0193607LLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 17CompanionSetupKit28CSKAttentionAwarenessMonitorC13ConfigurationV5StageV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So18NSNotificationNamea
+ _symbolic _____y______G ScS12ContinuationV 17CompanionSetupKit21CSKCloudConfigManagerC5EventO
+ _symbolic _____y______Qo_ 14CoreUtilsSwift15CUEventReporterPAAE6eventsQrvpQO 17CompanionSetupKit21CSKCloudConfigManagerC
+ _symbolic _____y______Qo_ 14CoreUtilsSwift15CUEventReporterPAAE6eventsQrvpQO 17CompanionSetupKit28CSKAttentionAwarenessMonitorC
+ _symbolic _____y______Qo_13AsyncIteratorSciQx 14CoreUtilsSwift15CUEventReporterPAAE6eventsQrvpQO 17CompanionSetupKit21CSKCloudConfigManagerC
+ _symbolic _____y______Qo_13AsyncIteratorSciQx 14CoreUtilsSwift15CUEventReporterPAAE6eventsQrvpQO 17CompanionSetupKit28CSKAttentionAwarenessMonitorC
+ _symbolic _____y__________y______GG s18_DictionaryStorageC s6UInt64V ScS12ContinuationV 17CompanionSetupKit21CSKCloudConfigManagerC5EventO
+ _symbolic _____yyycG 14CoreUtilsSwift17CUSendableWrapperV
+ _symbolic _____yyycGSg 14CoreUtilsSwift17CUSendableWrapperV
+ _symbolic yyc
+ _type_layout_string 17CompanionSetupKit21CSKCloudConfigManagerC5EventO
+ _type_layout_string 17CompanionSetupKit23CSKStepTVProviderServerC16STBConfigurationV
+ _type_layout_string 17CompanionSetupKit28CSKAttentionAwarenessMonitorC13ConfigurationV
+ _type_layout_string 17CompanionSetupKit28CSKAttentionAwarenessMonitorC13ConfigurationV5StageV
+ _type_layout_string 17CompanionSetupKit28CSKAttentionAwarenessMonitorC5EventO
- _OBJC_METACLASS_$__TtC17CompanionSetupKitP33_D49B7718351E00514DFEE720B79C5E1D29CSKStepTVProviderFlowDelegate
- __DATA__TtC17CompanionSetupKitP33_D49B7718351E00514DFEE720B79C5E1D29CSKStepTVProviderFlowDelegate
- __INSTANCE_METHODS__TtC17CompanionSetupKitP33_D49B7718351E00514DFEE720B79C5E1D29CSKStepTVProviderFlowDelegate
- __IVARS__TtC17CompanionSetupKitP33_D49B7718351E00514DFEE720B79C5E1D29CSKStepTVProviderFlowDelegate
- __METACLASS_DATA__TtC17CompanionSetupKitP33_D49B7718351E00514DFEE720B79C5E1D29CSKStepTVProviderFlowDelegate
- __OBJC_$_PROP_LIST_VSIdentityProviderPickerViewController
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_VSIdentityProviderPickerViewController
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_VSIdentityProviderPickerViewController
- __OBJC_$_PROTOCOL_METHOD_TYPES_VSIdentityProviderPickerViewController
- __OBJC_$_PROTOCOL_REFS_VSIdentityProviderPickerViewController
- __OBJC_LABEL_PROTOCOL_$_VSIdentityProviderPickerViewController
- __OBJC_PROTOCOL_$_VSIdentityProviderPickerViewController
- __PROTOCOLS__TtC17CompanionSetupKitP33_D49B7718351E00514DFEE720B79C5E1D29CSKStepTVProviderFlowDelegate
- ___swift_closure_destructor.132Tm
- ___swift_closure_destructor.194Tm
- ___swift_closure_destructor.293Tm
- ___swift_closure_destructor.313Tm
- ___swift_closure_destructor.369Tm
- ___swift_closure_destructor.395Tm
- ___swift_closure_destructor.418Tm
- ___swift_closure_destructor.423Tm
- ___swift_closure_destructor.441Tm
- ___swift_closure_destructor.91Tm
- ___swift_memcpy320_8
- ___swift_memcpy505_8
- ___unnamed_59
- _flat unique So38VSIdentityProviderPickerViewController_p
- _keypath_get.82Tm
- _keypath_set.17Tm
- _keypath_set.19Tm
- _symbolic SS12providerName______Sg0A8IconDataSSSg0A15AccountUsernamet 10Foundation4DataV
- _symbolic _____ 17CompanionSetupKit29CSKStepTVProviderFlowDelegate33_D49B7718351E00514DFEE720B79C5E1DLLC
- _symbolic _____Sg 17CompanionSetupKit16CSKLocaleManagerC
- _symbolic _____Sg 17CompanionSetupKit29CSKStepTVProviderFlowDelegate33_D49B7718351E00514DFEE720B79C5E1DLLC
- _symbolic ______So16UIViewControllerCXc So38VSIdentityProviderPickerViewControllerP
- _symbolic yycSg
CStrings:
+ "### 5GHz colocated consent canceled: %@"
+ "### Add colocated 5GHz network failed: ssid=%s, error=%@"
+ "### manual activation failed: %@"
+ "### resume failed stage=%s: %@"
+ "%s picker skipped: auto-advance"
+ "%s picker skipped: managed configuration"
+ "%s picker skipped: set by lockdown"
+ "5GHz colocated consent ask: network=%s"
+ "5GHz colocated consent: allow=%{bool}d"
+ "AA event: stage=%s type=%s"
+ "AddUserV2"
+ "Added colocated 5GHz network: ssid=%s"
+ "Case 'wifi5GHzConsentAnswer' cannot be encoded because it is not defined in CodingKeys."
+ "Colocated WiFi check: isStandalone6G=false"
+ "Colocated WiFi check: no current network"
+ "Colocated WiFi check: no network name"
+ "Colocated WiFi check: no other same LAN"
+ "Colocated WiFi check: same LAN, name=%s, isStandalone6G=%{bool}d"
+ "CompanionSetupKit.CSKStepTVProviderServer"
+ "CompanionSetupKit/CSKAttentionAwarenessMonitor.swift"
+ "CompanionSetupKit/CSKCloudConfigManager.swift"
+ "HID client start"
+ "HID client stop"
+ "IR HID event: enabling non-factory remote pairing"
+ "Language step skipped"
+ "LockdownSetLanguage"
+ "LockdownSetLocale"
+ "PrimaryUsagePage"
+ "Region step skipped"
+ "STB icon download failed for %s: %@"
+ "Skipping colocated 5GHz network without consent: ssid=%s"
+ "Skipping colocated 5GHz secured network without password: ssid=%s"
+ "TFDEP detected"
+ "TFDEP detected, completing Hello"
+ "TFDEP detected, enrollment already applied via Configurator, skipping consent UI"
+ "TFDEP detected, skipping Welcome"
+ "User already declined enrollment this session"
+ "Waiting for TFDEP"
+ "WiFi5GHzConsent"
+ "WiFi5GHzConsentAnswer: allow=%{bool}d"
+ "WiFi5GHzConsentAsk: network=%s"
+ "_externalLanguageChanged()"
+ "_externalLocaleChanged()"
+ "_manualActivationFailureHandle(_:)"
+ "_wifi5GHzConsentAsk()"
+ "_wifi5GHzConsentAsk(password:)"
+ "activationFailedAcknowledged"
+ "applying language=%s region=%s"
+ "attention awareness monitor start"
+ "attention awareness monitor start skipped: all stages disabled"
+ "attention awareness monitor stop"
+ "attention event: stage=%s lost=%{bool}d"
+ "attentionLost(stage: "
+ "bluetooth scanner device found: non-factory pairing disabled, %s"
+ "com.apple.CompanionSetupKit.AppleTV.screenSaver"
+ "com.apple.CompanionSetupKit.AppleTV.sleep"
+ "flow already finished, resolving immediately"
+ "hasMDMConfiguration="
+ "isAutoAdvanceEnabled="
+ "isAwaitingDeviceConfigured="
+ "isDoingReturnToService="
+ "isProvisionallyEnrolled="
+ "isShowingActivationFailedAlert="
+ "isShowingScreenSaver="
+ "language already applied, advancing without presenting"
+ "language and region already applied, not restarting"
+ "lockdown changed language/locale externally; restarting setup"
+ "manuallySelectedRegionID"
+ "no pending TV provider command continuation for "
+ "non-tvOS path requires both language and region"
+ "nothing to apply; lockdown already wrote language + region"
+ "organizationAddress="
+ "organizationName="
+ "perform(direction:)"
+ "providerAccountUsername="
+ "region already applied, advancing without presenting"
+ "region picker skipped, applying locale: %@"
+ "reset"
+ "screenSaverTimeout"
+ "shouldShowCloudConfigUI="
+ "sleep timeout reached, sleeping system"
+ "sleepTimeout"
+ "start stages=%s"
+ "stop"
+ "unrecognized attention stage: %s"
+ "userDidSelectLanguage: id=%s"
+ "userDidSelectRegion: %s"
+ "wifi5GHzConsent: networkName="
+ "wifi5GHzConsentAnswer"
+ "wifi5GHzConsentAnswer: allow="
+ "wifi5GHzConsentAsk: networkName="
- ", providerAccountUsername: "
- "MockA2DPActivity"
- "applyLanguageAndRegion failed during MDM skip: %@"
- "locale: %s"
- "no selected language and/or region"
- "onDeviceIntelligenceCapable"
- "setting language=%s region=%s"
- "stb(providerName: "
- "updateSelectedLanguage: id=%s"
- "updateSelectedRegion: %s"
```
