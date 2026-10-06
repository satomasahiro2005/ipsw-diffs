## riskdatad

> `/usr/libexec/riskdatad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33e28` | `0x3bd94` | **`+0x7f6c`** |
| `__TEXT.__eh_frame` | `0x2de0` | `0x3188` | **`+0x3a8`** |
| `__DATA_CONST.__const` | `0xb08` | `0xe40` | **`+0x338`** |
| `__TEXT.__auth_stubs` | `0x1a60` | `0x1ce0` | **`+0x280`** |
| `__TEXT.__cstring` | `0x6a0` | `0x890` | **`+0x1f0`** |
| `__TEXT.__const` | `0x21d8` | `0x2378` | **`+0x1a0`** |
| `__TEXT.__unwind_info` | `0xe88` | `0xfd8` | **`+0x150`** |
| `__DATA_CONST.__auth_got` | `0xd38` | `0xe78` | **`+0x140`** |
| `__DATA.__data` | `0x1198` | `0x1298` | **`+0x100`** |
| `__TEXT.__swift5_capture` | `0x210` | `0x2fc` | **`+0xec`** |
| `__TEXT.__objc_stubs` | `0x3e0` | `0x4c0` | **`+0xe0`** |
| `__TEXT.__swift5_typeref` | `0x9d6` | `0xaac` | **`+0xd6`** |
| `__DATA_CONST.__got` | `0x550` | `0x618` | **`+0xc8`** |
| `__TEXT.__objc_methname` | `0x6f1` | `0x791` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x5f0` | `0x680` | **`+0x90`** |
| `__TEXT.__swift_as_cont` | `0x338` | `0x37c` | **`+0x44`** |
| `__DATA.__objc_selrefs` | `0x1b8` | `0x1f0` | **`+0x38`** |
| `__DATA_CONST.__auth_ptr` | `0x490` | `0x4c8` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x66c` | `0x6a4` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x32e` | `0x35e` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x17c` | `0x1a8` | **`+0x2c`** |
| `__TEXT.__swift_as_entry` | `0x15c` | `0x180` | **`+0x24`** |
| `__TEXT.__swift5_acfuncs` | `0x12c` | `0x140` | **`+0x14`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-27.0.35.2.0
+27.0.44.0.0

+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

+  - /System/Library/PrivateFrameworks/RegulatoryDomain.framework/RegulatoryDomain

-  Functions: 848
-  Symbols:   727
-  CStrings:  204
+  Functions: 954
+  Symbols:   796
+  CStrings:  228
Symbols:
+ _$s10Foundation4DataV19base64EncodedString7optionsSSSo27NSDataBase64EncodingOptionsV_tF
+ _$s17CoreODIEssentials0A9ODIConfigV19tIRestrictedRegionsSaySSGSgvg
+ _$s17CoreODIEssentials0A9ODIConfigVMa
+ _$s17CoreODIEssentials0A9ODILoggerV4info_8categoryySS_2os6LoggerVAAE11LogCategoryOtF
+ _$s17CoreODIEssentials10CallerInfoV12isForegroundSbvg
+ _$s17CoreODIEssentials10CallerInfoV7isAppleSbvg
+ _$s17CoreODIEssentials12DIPCertUsageO17trustInsightsProdyA2CmFWC
+ _$s17CoreODIEssentials12DIPCertUsageO20trustInsightsSandboxyA2CmFWC
+ _$s17CoreODIEssentials12DIPCertUsageO23assessmentServerSigningyA2CmFWC
+ _$s17CoreODIEssentials12DIPCertUsageOMa
+ _$s17CoreODIEssentials12DIPCertUsageOMn
+ _$s17CoreODIEssentials13COSEValidatorO12parsePayload4from10certUsages10Foundation4DataVAI_SayAA12DIPCertUsageOGtKFZ
+ _$s17CoreODIEssentials13ConfigManagerC6configAA0A9ODIConfigVvgTjTu
+ _$s17CoreODIEssentials13ConfigManagerC6sharedACvgZ
+ _$s17CoreODIEssentials13ConfigManagerCMa
+ _$s17CoreODIEssentials17ODIAccountManagerC6sharedAA0cD8Protocol_pvgZ
+ _$s17CoreODIEssentials17ODIAccountManagerCMa
+ _$s17CoreODIEssentials18ODISessionInternalC13getAssessmentSSyYaFTjTu
+ _$s17CoreODIEssentials18ODISessionInternalC15provideFeedback2onySS_tYaFTjTu
+ _$s17CoreODIEssentials18ODISessionInternalC15provideFeedback7outcomeySo14ODIOutcomeTypeV_tYaFTjTu
+ _$s17CoreODIEssentials18ODISessionInternalC17serviceIdentifier11forDSIDType9startDate14locationBundle011andLocationlF0ACSgSo20ODIServiceProviderIda_So11ODITypeOfIDV10Foundation0J0VSo8NSBundleCSgSSSgtcfC
+ _$s17CoreODIEssentials18ODISessionInternalC17serviceIdentifier7versionACSgSo20ODIServiceProviderIda_SStcfC
+ _$s17CoreODIEssentials18ODISessionInternalC17validateForDeinityyYaFTjTu
+ _$s17CoreODIEssentials18ODISessionInternalC19getAssessmentResultAA013ODIAssessmentG0OyYaFTjTu
+ _$s17CoreODIEssentials18ODISessionInternalC22trustedInsightsVersionSSvgTj
+ _$s17CoreODIEssentials18ODISessionInternalC32setPartialAssessmentUpdateTargetyy0A3ODI010ODIPartialG9Updatable_pFTj
+ _$s17CoreODIEssentials18ODISessionInternalC6update10attributesySDySo15ODIAttributeKeya0A3ODI18AnyODIKnownBindingVG_tYaFTjTu
+ _$s17CoreODIEssentials18ODISessionInternalCMa
+ _$s17CoreODIEssentials18ODISessionInternalCMn
+ _$s17CoreODIEssentials18ODISessionInternalCScAAAMc
+ _$s17CoreODIEssentials21ForegroundAppsMonitorC6sharedACvgZ
+ _$s17CoreODIEssentials21ForegroundAppsMonitorCMa
+ _$s17CoreODIEssentials25ODIAccountManagerProtocolP17iTunesAccountDSIDSSyYaKFTj
+ _$s17CoreODIEssentials25ODIAccountManagerProtocolP17iTunesAccountDSIDSSyYaKFTjTu
+ _$s7CoreODI12ConsentStateV6RecordV010PermissionD0O03minF5LevelyA2G_AGtFZ
+ _$s7CoreODI12ConsentStateV6RecordV010PermissionD0O12notPermittedyA2GmFWC
+ _$s7CoreODI12ConsentStateV6RecordV010PermissionD0O15permittedByUseryA2GmFWC
+ _$s7CoreODI12ConsentStateV6RecordV010PermissionD0O19permittedByCooldownyA2GmFWC
+ _$s7CoreODI12ConsentStateV6RecordV010PermissionD0OMa
+ _$s7CoreODI12ConsentStateV6RecordV010PermissionD0OMn
+ _$s7CoreODI12ConsentStateV6RecordV11isPermitted18orInCoolDownWindowAE010PermissionD0OSd_tF
+ _$s7CoreODI13ConsentUpdateV11toggleStateSbSgvg
+ _$s7CoreODI13ConsentUpdateV6OriginO8rawValueSivg
+ _$s7CoreODI13ConsentUpdateV6OriginOMa
+ _$s7CoreODI13ConsentUpdateV6OriginOMn
+ _$s7CoreODI13ConsentUpdateV6originAC6OriginOSgvg
+ _$s7CoreODI13ConsentUpdateV8bundleId10toggleName0G5State6originACSSSg_SSSbSgAC6OriginOSgtcfC
+ _$s7CoreODI16InsightResultDTOV4typeSSvg
+ _$s7CoreODI16InsightResultDTOV5valueSSSgvg
+ _$s7CoreODI16InsightResultDTOV7versionSSvg
+ _$s7CoreODI16InsightResultDTOVMa
+ _$s7CoreODI16InsightResultDTOVMn
+ _$s7CoreODI16InsightResultDTOVSEAAMc
+ _$s7CoreODI16InsightResultDTOVSeAAMc
+ _$s7CoreODI18AnyODIKnownBindingVMa
+ _$s7CoreODI18AnyODIKnownBindingVMn
+ _$s7CoreODI18AnyODIKnownBindingVSEAAMc
+ _$s7CoreODI18AnyODIKnownBindingVSeAAMc
+ _$s7CoreODI18EvaluationErrorDTOO32evaluationResultSignatureInvalidyA2CmFWC
+ _$s7CoreODI18InsightResponseDTOV14assessmentData016signedAssessmentG09isSandbox6teamIdAC10Foundation0G0V_AJSbSStcfC
+ _$s7CoreODI18OnDeviceAPIServiceP17submitConsumption14conversationId8statuses8insightsySS_SayAA07InsightG3DTOVGSayAA0l6ResultM0VGtYaFTq
+ _$s7CoreODI18OnDeviceAPIServiceP17submitConsumption14conversationId8statuses8insightsySS_SayAA07InsightG3DTOVGSayAA0l6ResultM0VGtYaKFTqTE
+ _$s7CoreODI21InsightConsumptionDTOV8feedbackSSvg
+ _$s7CoreODI22OnDeviceConsentServiceP17isPermittedRegionSbyYaFTq
+ _$s7CoreODI22OnDeviceConsentServiceP17isPermittedRegionSbyYaKFTqTE
+ _$s7CoreODI23RestrictedRegionMonitorC5ErrorO010restrictedD0yA2EmFWC
+ _$s7CoreODI23RestrictedRegionMonitorC5ErrorOMa
+ _$s7CoreODI23RestrictedRegionMonitorC5ErrorOsAdAMc
+ _$s7CoreODI26InsightAuthorizationStatusO16authorizedByUseryA2CmFWC
+ _$s7CoreODI26InsightAuthorizationStatusO20authorizedByCooldownyA2CmFWC
+ _$s7CoreODI26InsightAuthorizationStatusO8rawValueSivg
+ _$s7CoreODI26InsightAuthorizationStatusOSQAAMc
+ _$s7CoreODI26OnDeviceSPISessionProtocolP16updateAttributes8bindingsySDySo15ODIAttributeKeyaAA18AnyODIKnownBindingVG_tYaFTq
+ _$s7CoreODI26OnDeviceSPISessionProtocolP16updateAttributes8bindingsySDySo15ODIAttributeKeyaAA18AnyODIKnownBindingVG_tYaKFTqTE
+ _$sSD10FoundationE19_bridgeToObjectiveCSo12NSDictionaryCyF
+ _$sSD11descriptionSSvg
+ _$sSKsSS7ElementRtzrlE6joined9separatorS2S_tF
+ _$sSQ2eeoiySbx_xtFZTj
+ _$sSa10FoundationE36_unconditionallyBridgeFromObjectiveCySayxGSo7NSArrayCSgFZ
+ _$sSayxGSKsMc
+ _$sSbSEsWP
+ _$sSbSesWP
+ _$sSh15minimumCapacityShyxGSi_tcfC
+ _$sSo8NSStringC10FoundationE13stringLiteralABs12StaticStringV_tcfC
+ _$ss11_SetStorageC4copy8originalAByxGs05__RawaB0C_tFZ
+ _$ss11_SetStorageC6resize8original8capacity4moveAByxGs05__RawaB0C_SiSbtFZ
+ _$ss11_SetStorageCMn
+ _$ss50ELEMENT_TYPE_OF_SET_VIOLATES_HASHABLE_REQUIREMENTSys5NeverOypXpF
+ _AnalyticsSendEventLazy
+ _OBJC_CLASS_$_LSBundleRecord
+ _OBJC_CLASS_$_NSNumber
+ _OBJC_CLASS_$_NSObject
+ _OBJC_CLASS_$_NSString
+ _OBJC_CLASS_$_RDEstimate
+ _objc_autoreleaseReturnValue
+ _objc_release_x1
+ _objc_retain_x22
+ _objc_retain_x23
+ _objc_retain_x26
+ _swift_initStackObject
+ _swift_release_x9
+ _swift_retain_x25
+ _swift_setDeallocating
- _$s17CoreODIEssentials13COSEValidatorO12parsePayload4from10Foundation4DataVAH_tKFZ
- _$s17CoreODIEssentials18AnyODIKnownBindingVMa
- _$s17CoreODIEssentials18AnyODIKnownBindingVMn
- _$s17CoreODIEssentials18AnyODIKnownBindingVSEAAMc
- _$s17CoreODIEssentials18AnyODIKnownBindingVSeAAMc
- _$s7CoreODI12ConsentStateV6RecordV11isPermitted18orInCoolDownWindowSbSd_tF
- _$s7CoreODI13ConsentUpdateV11toggleStateSbvg
- _$s7CoreODI13ConsentUpdateV8bundleId10toggleName0G5StateACSSSg_SSSbtcfC
- _$s7CoreODI18InsightResponseDTOV14assessmentData9isSandbox6teamIdAC10Foundation0G0V_SbSStcfC
- _$s7CoreODI18ODISessionInternalC13getAssessmentSSyYaFTjTu
- _$s7CoreODI18ODISessionInternalC15provideFeedback2onySS_tYaFTjTu
- _$s7CoreODI18ODISessionInternalC15provideFeedback7outcomeySo14ODIOutcomeTypeV_tYaFTjTu
- _$s7CoreODI18ODISessionInternalC17serviceIdentifier11forDSIDType9startDate14locationBundle011andLocationlF0ACSgSo20ODIServiceProviderIda_So11ODITypeOfIDV10Foundation0J0VSo8NSBundleCSgSSSgtcfC
- _$s7CoreODI18ODISessionInternalC17serviceIdentifier7versionACSgSo20ODIServiceProviderIda_SStcfC
- _$s7CoreODI18ODISessionInternalC17validateForDeinityyFTj
- _$s7CoreODI18ODISessionInternalC19getAssessmentResult0A13ODIEssentials013ODIAssessmentG0OyYaFTjTu
- _$s7CoreODI18ODISessionInternalC22trustedInsightsVersionSSvgTj
- _$s7CoreODI18ODISessionInternalC32setPartialAssessmentUpdateTargetyyAA010ODIPartialG9Updatable_pFTj
- _$s7CoreODI18ODISessionInternalC6update10attributesySDySo15ODIAttributeKeya0A13ODIEssentials18AnyODIKnownBindingVG_tYaFTjTu
- _$s7CoreODI18ODISessionInternalCMa
- _$s7CoreODI18ODISessionInternalCMn
- _$s7CoreODI18ODISessionInternalCScAAAMc
- _$s7CoreODI18OnDeviceAPIServiceP17submitConsumption14conversationId8statusesySS_SayAA07InsightG3DTOVGtYaFTq
- _$s7CoreODI18OnDeviceAPIServiceP17submitConsumption14conversationId8statusesySS_SayAA07InsightG3DTOVGtYaKFTqTE
- _$s7CoreODI23RestrictedRegionMonitorC11isPermittedSbyYaF
- _$s7CoreODI23RestrictedRegionMonitorC11isPermittedSbyYaFTu
- _$s7CoreODI23RestrictedRegionMonitorC18verifyUnrestrictedyyYaKF
- _$s7CoreODI23RestrictedRegionMonitorC18verifyUnrestrictedyyYaKFTu
- _$s7CoreODI23RestrictedRegionMonitorC6sharedACvgZ
- _$s7CoreODI23RestrictedRegionMonitorCMa
- _$s7CoreODI26InsightAuthorizationStatusO10authorizedyA2CmFWC
- _$s7CoreODI26OnDeviceSPISessionProtocolP16updateAttributes8bindingsySDySo15ODIAttributeKeya0A13ODIEssentials18AnyODIKnownBindingVG_tYaFTq
- _$s7CoreODI26OnDeviceSPISessionProtocolP16updateAttributes8bindingsySDySo15ODIAttributeKeya0A13ODIEssentials18AnyODIKnownBindingVG_tYaKFTqTE
- _swift_release_x28
CStrings:
+ "@\"NSDictionary\"8@?0"
+ "Failed to parse the received payload: %@"
+ "Global"
+ "Raw insights received: %s"
+ "Sending CoreAnalytics event for authorizationRequested: "
+ "Sending CoreAnalytics event for consentUpdated: %s"
+ "Sending CoreAnalytics event for usageFeedback: "
+ "appNotInForeground"
+ "authorizationStatus"
+ "authorizedByCooldown"
+ "bundleRecordWithBundleIdentifier:allowPlaceholder:error:"
+ "com.apple.TrustInsights.authorizationRequested"
+ "com.apple.TrustInsights.consentUpdated"
+ "com.apple.TrustInsights.usageFeedback"
+ "consumptionStatus"
+ "countryCode"
+ "currentEstimates"
+ "developerType"
+ "initWithBool:"
+ "initWithInteger:"
+ "regionNotPermitted"
+ "submitConsumptionError"
+ "teamIdentifier"
+ "unexpectedCurrentAuthorizationState"
```
