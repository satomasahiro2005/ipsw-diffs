## seserviced

> `/usr/libexec/seserviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x45f3bc` | `0x4630ac` | **`+0x3cf0`** |
| `__DATA.__bss` | `0x10b10` | `0x10e90` | **`+0x380`** |
| `__TEXT.__eh_frame` | `0x15668` | `0x159e8` | **`+0x380`** |
| `__TEXT.__const` | `0x13008` | `0x13218` | **`+0x210`** |
| `__DATA_CONST.__const` | `0x14948` | `0x14b18` | **`+0x1d0`** |
| `__TEXT.__unwind_info` | `0xa480` | `0xa5d8` | **`+0x158`** |
| `__TEXT.__oslogstring` | `0x30f87` | `0x310b6` | **`+0x12f`** |
| `__TEXT.__swift5_typeref` | `0x53e0` | `0x5358` | **`-0x88`** |
| `__TEXT.__swift5_fieldmd` | `0x5d90` | `0x5e10` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x611a` | `0x619a` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x593c` | `0x5994` | **`+0x58`** |
| `__TEXT.__objc_methname` | `0x191fd` | `0x1924d` | **`+0x50`** |
| `__DATA.__objc_const` | `0x18b88` | `0x18bc8` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0xeb0` | `0xedc` | **`+0x2c`** |
| `__TEXT.__auth_stubs` | `0x50d0` | `0x50f0` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x3270` | `0x328c` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0x938` | `0x954` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x1fc0` | `0x1fd8` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x810` | `0x828` | **`+0x18`** |
| `__TEXT.__cstring` | `0x22046` | `0x22033` | **`-0x13`** |
| `__DATA.__data` | `0xdb64` | `0xdb74` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2880` | `0x2890` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x7d6d` | `0x7d7d` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0xf58` | `0xf50` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x70bc` | `0x70c4` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x5dc` | `0x5e4` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x5f8` | `0x5f0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-70.31.1.0.0
+70.34.0.0.0

-  Functions: 12614
-  Symbols:   2537
-  CStrings:  11453
+  Functions: 12670
+  Symbols:   2541
+  CStrings:  11464
Symbols:
+ _$s9SEService28SESThirdPartyServiceReporterV10sendReport_10reportTypeAC8ResponseV10Foundation4DataV_AC0gI6HeaderOtYaAC9ErrorCodeOYKF
+ _$s9SEService28SESThirdPartyServiceReporterV10sendReport_10reportTypeAC8ResponseV10Foundation4DataV_AC0gI6HeaderOtYaAC9ErrorCodeOYKFTu
+ _$s9SEService28SESThirdPartyServiceReporterV14performRequest3url6method4body17additionalHeaders8withIDMS10Foundation4DataVAJ3URLV_SSALSgSDyS2SGSbtYaAC9ErrorCodeOYKF
+ _$s9SEService28SESThirdPartyServiceReporterV14performRequest3url6method4body17additionalHeaders8withIDMS10Foundation4DataVAJ3URLV_SSALSgSDyS2SGSbtYaAC9ErrorCodeOYKFTu
+ _$s9SEService28SESThirdPartyServiceReporterV15provisioningURL10Foundation0G0Vvg
+ _$s9SEService28SESThirdPartyServiceReporterV16ReportTypeHeaderO12presentmentsyA2EmFWC
+ _$s9SEService28SESThirdPartyServiceReporterV16ReportTypeHeaderOMa
+ _$s9SEService28SESThirdPartyServiceReporterV16productConfigURL3for6teamId10Foundation0H0VAG4UUIDV_SStF
+ _$s9SEService28SESThirdPartyServiceReporterV18reportHeartbeatURL10Foundation0H0Vvg
+ _$s9SEService28SESThirdPartyServiceReporterV19secureElementKeyingA2C06SecuregH0O_tYaAC9ErrorCodeOYKcfC
+ _$s9SEService28SESThirdPartyServiceReporterV19secureElementKeyingA2C06SecuregH0O_tYaAC9ErrorCodeOYKcfCTu
+ _$s9SEService28SESThirdPartyServiceReporterV21installationStatusURL3for10Foundation0H0VAF4UUIDV_tF
+ _$s9SEService28SESThirdPartyServiceReporterV8ResponseVMa
+ _$s9SEService28SESThirdPartyServiceReporterV9ErrorCodeO04httpF0yAESi_tcAEmFWC
+ _$s9SEService28SESThirdPartyServiceReporterV9serverURL09reportingG0AC10Foundation0G0V_AHtcfC
+ _$s9SEService28SESThirdPartyServiceReporterVMa
+ _$s9SEService28SESThirdPartyServiceReporterVMn
+ _swift_retain_x11
+ _swift_retain_x12
- _$s10Foundation10URLRequestV3urlAA3URLVSgvg
- _$s10Foundation10URLRequestV8setValue_18forHTTPHeaderFieldySSSg_SStF
- _$s9SEService11SESDataTaskC7perform7request8withIDMS10Foundation4DataVAG10URLRequestV_SbtYaKF
- _$s9SEService11SESDataTaskC7perform7request8withIDMS10Foundation4DataVAG10URLRequestV_SbtYaKFTu
- _$s9SEService28SESThirdPartyServiceReporterV13ConfigurationO15provisioningURL10Foundation0H0Vvg
- _$s9SEService28SESThirdPartyServiceReporterV13ConfigurationO16productConfigURL3for6teamId10Foundation0I0VAI4UUIDV_SStF
- _$s9SEService28SESThirdPartyServiceReporterV13ConfigurationO18reportHeartbeatURL10Foundation0I0Vvg
- _$s9SEService28SESThirdPartyServiceReporterV13ConfigurationO19secureElementKeyingAeC06SecurehI0O_tYaAC9ErrorCodeOYKcfC
- _$s9SEService28SESThirdPartyServiceReporterV13ConfigurationO19secureElementKeyingAeC06SecurehI0O_tYaAC9ErrorCodeOYKcfCTu
- _$s9SEService28SESThirdPartyServiceReporterV13ConfigurationO20reportPresentmentURL10Foundation0I0Vvg
- _$s9SEService28SESThirdPartyServiceReporterV13ConfigurationO21installationStatusURL3for10Foundation0I0VAH4UUIDV_tF
- _$s9SEService28SESThirdPartyServiceReporterV13ConfigurationO9serverURL09reportingH0AE10Foundation0H0V_AJtcfC
- _$s9SEService28SESThirdPartyServiceReporterV13ConfigurationOMa
- _$s9SEService28SESThirdPartyServiceReporterV13ConfigurationOMn
- _$sSD4KeysVMn
CStrings:
+ "%s : %i : Invalid scheduling strategy override: %ld, using default TimeBased"
+ "%s : %i : Unknown scheduling strategy type: %ld, falling back to TimeBased"
+ "%s : %i : Using scheduling strategy override: %ld"
+ "%s: Nil reporter"
+ "%{public}s: Network error %{public}@"
+ "-[KmlPendingPairingNotificationScheduler activeStrategyType]"
+ "Cleaning up %ld connections for service %{public}s"
+ "Creating request body for credential %s with configUUID %s"
+ "Failed to decode response JSON %s"
+ "Invalid Ranging Session event %{public}s"
+ "Invalid encrypted payload %s"
+ "Invalid event %{public}s"
+ "JSONSerialization error %{public}s encountered while serializing createAppletInstanceRequest"
+ "Malformed response - hex fields could not be decoded"
+ "PTA/Sunsprite is newer than iOS -- deleting applets"
+ "PTA/Sunsprite is newer than iOS but not deleting applets due to debug option"
+ "Q24@0:8@16"
+ "RewrappedBlob"
+ "Successfully created request body to provision credential %s with config %s"
+ "Sunsprite Version 0x%04x"
+ "_caTransportTypesForRevocationOfEndPoint:"
+ "authenticatedHeaders: Nil SEID"
+ "createCredential: Network error %{public}@ encountered while performing URL request to %{public}s"
+ "createCredential: Nil reporter"
+ "createCredential: Sending request to %{public}s"
+ "failed to serialize state for %{public}s: %{public}@"
+ "getCredentialMetadata: Network error %{public}@ for %{public}s"
+ "getCredentialMetadata: Nil reporter"
+ "getCredentialMetadata: Unknown product config %{public}s for %{public}s"
+ "getInstallationStatus: Network error %{public}@ for %{public}s"
+ "getInstallationStatus: Nil reporter"
+ "iOS (27.0) - SecureElementService-70.34"
+ "notifyClientOnDisconnection"
+ "pendingPairingNotificationSchedulingStrategyOverride"
+ "reporter"
+ "reporterInitializerTask"
+ "sendDailyPresentmentReports: Nil reporter"
- "%s : %i : Unknown scheduling strategy type: %ld, falling back to Immediate"
- "%s: Nil network configuration"
- "%{public}s: Data task wrapper error %{public}s"
- "Creating URL Request for credential %s with configUUID %s"
- "Error %s when signing report"
- "Failed to decode JSON object %s"
- "JSONObjectWithData:options:error:"
- "JSONSerialization error %s encountered while serializing createAppletInstanceRequest"
- "Missing or malformed response %s"
- "Nil network configuration when creatingCreationURLRequest"
- "PTA is newer than iOS -- deleting applets"
- "PTA is newer than iOS but not deleting applets due to debug option"
- "Successfully created URLRequest to provision credential %s with config %s"
- "createCredential: Data task wrapper error %{public}s encountered while performing URL request to %{public}s"
- "createCredential: Sending request to %s"
- "getCredentialMetadata: Data task wrapper error %{public}s encountered while performing URL request to %{public}s"
- "getCredentialMetadata: Nil network configuration"
- "getInstallationStatus: Data task wrapper error %{public}s encountered while performing URL request to %{public}s"
- "getInstallationStatus: Nil network configuration"
- "iOS (27.0) - SecureElementService-70.31.1"
- "networkConfiguration"
- "pendingPairingNotificationSchedulingStrategy"
- "sendDailyPresentmentReports: Nil network configuration"
- "seserviced/Alisha.swift"
- "seserviced/AlishaPairing.swift"
- "seserviced/AlishaRKE.swift"
```
