## LocalAuthenticationCore

> `/System/Library/PrivateFrameworks/LocalAuthenticationCore.framework/LocalAuthenticationCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1932d8` | `0x194d1c` | **`+0x1a44`** |
| `__AUTH_CONST.__objc_const` | `0x58cf8` | `0x590c8` | **`+0x3d0`** |
| `__TEXT.__cstring` | `0x10684` | `0x1085c` | **`+0x1d8`** |
| `__TEXT.__oslogstring` | `0xb119` | `0xaf85` | **`-0x194`** |
| `__AUTH.__objc_data` | `0x46b0` | `0x4800` | **`+0x150`** |
| `__DATA_CONST.__const` | `0x56a8` | `0x55c8` | **`-0xe0`** |
| `__TEXT.__objc_methlist` | `0xd2c0` | `0xd378` | **`+0xb8`** |
| `__AUTH.__data` | `0x2e88` | `0x2f08` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x6a70` | `0x6ae8` | **`+0x78`** |
| `__TEXT.__const` | `0xade4` | `0xae44` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x2eb0` | `0x2eec` | **`+0x3c`** |
| `__AUTH_CONST.__const` | `0x8990` | `0x89c8` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x3170` | `0x31a8` | **`+0x38`** |
| `__DATA.__data` | `0x76e8` | `0x7718` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x4970` | `0x49a0` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x40e4` | `0x4114` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x7580` | `0x75a0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x206e` | `0x208e` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x286c` | `0x2888` | **`+0x1c`** |
| `__TEXT.__swift5_capture` | `0x1ab8` | `0x1ad0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xc18` | `0xc28` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x218` | `0x208` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1560` | `0x1568` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xd28` | `0xd30` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0xa48` | `0xa50` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x4c8` | `0x4d0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x8a8` | `0x8ac` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x2c4` | `0x2c8` | **`+0x4`** |

### Other Changes

```diff

-2305.0.0.0.1
+2319.0.16.502.1

-  Functions: 10853
-  Symbols:   21917
-  CStrings:  3102
+  Functions: 10884
+  Symbols:   21975
+  CStrings:  3104
Symbols:
+ +[LACAccessControl _constraintsContainPBIOA:]
+ +[LACAccessControl checkACLRequiresApplePayBiometryToggle:]
+ +[LACAuditToken currentProcess]
+ -[LACAnalyticsData setTccFaceIDResult:]
+ -[LACAnalyticsData tccFaceIDResult]
+ _$s23LocalAuthenticationCore23LACAnalyticsTCCReporterC17analyticsReporter33_5CE2460782609C6AEC105998E22F8D06LLSo0dG0CvpWvd
+ _$s23LocalAuthenticationCore23LACAnalyticsTCCReporterC19reportBiometryCheck6resultySo0D9TCCResultV_tF
+ _$s23LocalAuthenticationCore23LACAnalyticsTCCReporterC19reportBiometryCheck6resultySo0D9TCCResultV_tFTo
+ _$s23LocalAuthenticationCore23LACAnalyticsTCCReporterCACycfC
+ _$s23LocalAuthenticationCore23LACAnalyticsTCCReporterCACycfc
+ _$s23LocalAuthenticationCore23LACAnalyticsTCCReporterCACycfcTo
+ _$s23LocalAuthenticationCore23LACAnalyticsTCCReporterCMF
+ _$s23LocalAuthenticationCore23LACAnalyticsTCCReporterCMa
+ _$s23LocalAuthenticationCore23LACAnalyticsTCCReporterCMf
+ _$s23LocalAuthenticationCore23LACAnalyticsTCCReporterCMn
+ _$s23LocalAuthenticationCore23LACAnalyticsTCCReporterCMo
+ _$s23LocalAuthenticationCore23LACAnalyticsTCCReporterCN
+ _$s23LocalAuthenticationCore23LACAnalyticsTCCReporterCfD
+ _$s23LocalAuthenticationCore23LACAnalyticsTCCReporterCfETo
+ _$s23LocalAuthenticationCore30LACCredentialAnalyticsReporterC25reportEncodingSeedAttempt2rc9signingIDyAA0dE11WriteResultO_SStF
+ _$s23LocalAuthenticationCore30LACCredentialAnalyticsReporterCAA0dE9ReportingA2aDP25reportEncodingSeedAttempt2rc9signingIDyAA0dE11WriteResultO_SStFTW
+ _$s23LocalAuthenticationCore31LACCredentialAnalyticsReportingP25reportEncodingSeedAttempt2rc9signingIDyAA0dE11WriteResultO_SStFTj
+ _$s23LocalAuthenticationCore31LACCredentialAnalyticsReportingP25reportEncodingSeedAttempt2rc9signingIDyAA0dE11WriteResultO_SStFTq
+ _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterC06reportE10Exhaustion14greediestCount10uniquePidsySi_SitF
+ _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterC06reportE10Exhaustion14greediestCount10uniquePidsySi_SitFTo
+ _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterC14reportTransferyySo0deI4TypeVF
+ _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterC14reportTransferyySo0deI4TypeVFTo
+ _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterC18reportRegistration7latency7successySi_SbtF
+ _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterC18reportRegistration7latency7successySi_SbtFTo
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC022checkOriginatorCanReadE10CredentialyySo12LACXPCClient_pKF
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC022checkOriginatorCanReadE10CredentialyySo12LACXPCClient_pKFTj
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC022checkOriginatorCanReadE10CredentialyySo12LACXPCClient_pKFTo
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC022checkOriginatorCanReadE10CredentialyySo12LACXPCClient_pKFToTm
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC022checkOriginatorCanReadE10CredentialyySo12LACXPCClient_pKFTq
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC022checkOriginatorCanReadeF10Credential33_3083616BDF280358C5BA62532A77738FLL_13credentialAgeAC12AccessResultAELLOSo12LACXPCClient_p_So8NSNumberCtFTf4nnd_n
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC023checkOriginatorCanWriteE10CredentialyySo12LACXPCClient_pKF
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC023checkOriginatorCanWriteE10CredentialyySo12LACXPCClient_pKFTj
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC023checkOriginatorCanWriteE10CredentialyySo12LACXPCClient_pKFTo
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC023checkOriginatorCanWriteE10CredentialyySo12LACXPCClient_pKFTq
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC023checkOriginatorCanWriteeF10Credential33_3083616BDF280358C5BA62532A77738FLLyAC12AccessResultAELLOSo12LACXPCClient_pFTf4nd_n
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC36checkOriginatorCanAccessEncodingSeedyySo12LACXPCClient_pKF
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC36checkOriginatorCanAccessEncodingSeedyySo12LACXPCClient_pKFTj
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC36checkOriginatorCanAccessEncodingSeedyySo12LACXPCClient_pKFTo
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC36checkOriginatorCanAccessEncodingSeedyySo12LACXPCClient_pKFTq
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC46checkOriginatorCanAccessEncodingSeedCredential33_3083616BDF280358C5BA62532A77738FLLyAC0K6ResultAELLOSo12LACXPCClient_pFTf4nd_n
+ _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC47checkOriginatorIsExemptedFromAccessRequirements33_3083616BDF280358C5BA62532A77738FLLySbSo12LACXPCClient_pFTv_r
+ _$sSDySSSo8NSObjectCGMR
+ _$sSDySSSo8NSObjectCGMd
+ _$sSS10FoundationE4data8encodingSSSgAA4DataVh_SSAAE8EncodingVtcfC
+ _$sSo20LACAnalyticsReporterC23LocalAuthenticationCoreE4send33_FD1D1E741C6745CBE5A9FD0C33C3FF87LL4name7payloadySS_SDySSypGtFZSDySSSo8NSObjectCGSgycfU_TA
+ _$sSo20LACAnalyticsReporterC23LocalAuthenticationCoreE4send33_FD1D1E741C6745CBE5A9FD0C33C3FF87LL4name7payloadySS_SDySSypGtFZTf4nnd_n
+ _$sSo20LACAnalyticsReporterC23LocalAuthenticationCoreE5queue33_FD1D1E741C6745CBE5A9FD0C33C3FF87LLSo012OS_dispatch_F0CvpZ
+ _$sSo20LACAnalyticsReporterC23LocalAuthenticationCoreE5queue33_FD1D1E741C6745CBE5A9FD0C33C3FF87LL_WZ
+ _$sSo20LACAnalyticsReporterC23LocalAuthenticationCoreE5queue33_FD1D1E741C6745CBE5A9FD0C33C3FF87LL_Wz
+ _$sSo20LACAnalyticsReporterC23LocalAuthenticationCoreE9sendEvent4name7payloadySS_SDySSypGtF
+ _$sSo20LACAnalyticsReporterC23LocalAuthenticationCoreE9sendEvent4name7payloadySS_SDySSypGtFTo
+ _$sSo20LACAnalyticsReporterC23LocalAuthenticationCoreE9sendEvent4name7payloadySS_SDySSypGtFyyYbcfU_TA
+ _$sSo20NSJSONWritingOptionsVSYSCSY8rawValue03RawD0QzvgTW
+ _$sSo20NSJSONWritingOptionsVs10SetAlgebraSCsACP6insertySb8inserted_7ElementQz17memberAfterInserttAHnFTW
+ _$sSo20NSJSONWritingOptionsVs10SetAlgebraSCsACPxycfCTW
+ _$sSo20NSJSONWritingOptionsVs9OptionSetSCsACP8rawValuex03RawF0Qz_tcfCTW
+ _$sSo31LACAnalyticsTCCReporterProviderC23LocalAuthenticationCoreE8reporterSo0A12TCCReporting_pyFZ
+ _$sSo31LACAnalyticsTCCReporterProviderC23LocalAuthenticationCoreE8reporterSo0A12TCCReporting_pyFZTo
+ _$sSo31LACAnalyticsTCCReporterProviderC23LocalAuthenticationCoreEABycfC
+ _$sSo31LACAnalyticsTCCReporterProviderC23LocalAuthenticationCoreEABycfc
+ _$sSo31LACAnalyticsTCCReporterProviderC23LocalAuthenticationCoreEABycfcTo
+ _$sSo31LACAnalyticsTCCReporterProviderCML
+ _$sSo31LACAnalyticsTCCReporterProviderCMa
+ _$sSo34LACApplePayBiometryToggleProcessorC23LocalAuthenticationCoreE14processRequest_13configuration10completionySo013LACEvaluationJ0_p_So26LACProcessingConfigurationCySo0M6ResultCYbctF
+ _$sSo34LACApplePayBiometryToggleProcessorC23LocalAuthenticationCoreE14processRequest_13configuration10completionySo013LACEvaluationJ0_p_So26LACProcessingConfigurationCySo0M6ResultCYbctF06$sSo19mP18CIeyBhy_ABIeghg_TRAKIeyBhy_Tf1nncn_nTf4ndnn_n
+ _$sSo34LACApplePayBiometryToggleProcessorC23LocalAuthenticationCoreE14processRequest_13configuration10completionySo013LACEvaluationJ0_p_So26LACProcessingConfigurationCySo0M6ResultCYbctFSDys11AnyHashableVypGyXEfU_
+ _$sSo34LACApplePayBiometryToggleProcessorC23LocalAuthenticationCoreE14processRequest_13configuration10completionySo013LACEvaluationJ0_p_So26LACProcessingConfigurationCySo0M6ResultCYbctFTo
+ _$sSo34LACApplePayBiometryToggleProcessorC23LocalAuthenticationCoreE17canProcessRequestySbSo013LACEvaluationK0_pF
+ _$sSo34LACApplePayBiometryToggleProcessorC23LocalAuthenticationCoreE17canProcessRequestySbSo013LACEvaluationK0_pFTf4nd_n
+ _$sSo34LACApplePayBiometryToggleProcessorC23LocalAuthenticationCoreE17canProcessRequestySbSo013LACEvaluationK0_pFTo
+ _$sSo34LACApplePayBiometryToggleProcessorC23LocalAuthenticationCoreEABycfC
+ _$sSo34LACApplePayBiometryToggleProcessorC23LocalAuthenticationCoreEABycfc
+ _$sSo34LACApplePayBiometryToggleProcessorC23LocalAuthenticationCoreEABycfcTo
+ _$sSo34LACApplePayBiometryToggleProcessorCML
+ _$sSo34LACApplePayBiometryToggleProcessorCMa
+ _LACAnalyticsTCCResultFromAuthorizationStatus
+ _OBJC_CLASS_$_LACAnalyticsTCCReporterProvider
+ _OBJC_CLASS_$_LACApplePayBiometryToggleProcessor
+ _OBJC_CLASS_$__TtC23LocalAuthenticationCore23LACAnalyticsTCCReporter
+ _OBJC_IVAR_$_LACAnalyticsData._tccFaceIDResult
+ _OBJC_METACLASS_$_LACAnalyticsTCCReporterProvider
+ _OBJC_METACLASS_$_LACApplePayBiometryToggleProcessor
+ _OBJC_METACLASS_$__TtC23LocalAuthenticationCore23LACAnalyticsTCCReporter
+ __CLASS_METHODS_LACAnalyticsTCCReporterProvider
+ __DATA_LACAnalyticsTCCReporterProvider
+ __DATA_LACApplePayBiometryToggleProcessor
+ __DATA__TtC23LocalAuthenticationCore23LACAnalyticsTCCReporter
+ __INSTANCE_METHODS_LACAnalyticsTCCReporterProvider
+ __INSTANCE_METHODS_LACApplePayBiometryToggleProcessor
+ __INSTANCE_METHODS__TtC23LocalAuthenticationCore23LACAnalyticsTCCReporter
+ __IVARS__TtC23LocalAuthenticationCore23LACAnalyticsTCCReporter
+ __METACLASS_DATA_LACAnalyticsTCCReporterProvider
+ __METACLASS_DATA_LACApplePayBiometryToggleProcessor
+ __METACLASS_DATA__TtC23LocalAuthenticationCore23LACAnalyticsTCCReporter
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_LACAnalyticsTCCReporting
+ __OBJC_$_PROTOCOL_METHOD_TYPES_LACAnalyticsTCCReporting
+ __OBJC_$_PROTOCOL_REFS_LACAnalyticsTCCReporting
+ __OBJC_LABEL_PROTOCOL_$_LACAnalyticsTCCReporting
+ __OBJC_PROTOCOL_$_LACAnalyticsTCCReporting
+ __PROTOCOLS_LACApplePayBiometryToggleProcessor
+ __PROTOCOLS__TtC23LocalAuthenticationCore23LACAnalyticsTCCReporter
+ _symbolic SDySSypG
+ _symbolic So20LACAnalyticsReporterCXDXMT
+ _symbolic _____ 23LocalAuthenticationCore23LACAnalyticsTCCReporterC
- +[LACCredentialSignpostEvent sharedInstance]
- -[LACCredentialSignpostEvent extractableCredentialFailedReadAttemptWithAge:signingID:]
- -[LACCredentialSignpostEvent extractableCredentialFailedWriteAttemptWithSigningID:]
- -[LACCredentialSignpostEvent extractableCredentialReadAttemptWithAge:accessAllowed:]
- -[LACCredentialSignpostEvent extractableCredentialWriteAttemptWithAccessAllowed:]
- _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC022checkOriginatorCanReadE10CredentialyySo17LACOriginatorProt_pKF
- _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC022checkOriginatorCanReadE10CredentialyySo17LACOriginatorProt_pKFTj
- _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC022checkOriginatorCanReadE10CredentialyySo17LACOriginatorProt_pKFTo
- _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC022checkOriginatorCanReadE10CredentialyySo17LACOriginatorProt_pKFToTm
- _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC022checkOriginatorCanReadE10CredentialyySo17LACOriginatorProt_pKFTq
- _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC022checkOriginatorCanReadeF10Credential33_3083616BDF280358C5BA62532A77738FLL_13credentialAgeAC12AccessResultAELLOSo17LACOriginatorProt_p_So8NSNumberCtFTf4nnd_n
- _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC023checkOriginatorCanWriteE10CredentialyySo17LACOriginatorProt_pKF
- _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC023checkOriginatorCanWriteE10CredentialyySo17LACOriginatorProt_pKFTj
- _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC023checkOriginatorCanWriteE10CredentialyySo17LACOriginatorProt_pKFTo
- _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC023checkOriginatorCanWriteE10CredentialyySo17LACOriginatorProt_pKFTq
- _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC023checkOriginatorCanWriteeF10Credential33_3083616BDF280358C5BA62532A77738FLLyAC12AccessResultAELLOSo17LACOriginatorProt_pFTf4nd_n
- _$s23LocalAuthenticationCore42LACCredentialExtractablePasswordAuthorizerC47checkOriginatorIsExemptedFromAccessRequirements33_3083616BDF280358C5BA62532A77738FLLySbSo17LACOriginatorProt_pFTv_r
- _$sSo20LACAnalyticsReporterC23LocalAuthenticationCoreE9sendEvent4name7payloadSbSS_SDySSypGtF
- _$sSo20LACAnalyticsReporterC23LocalAuthenticationCoreE9sendEvent4name7payloadSbSS_SDySSypGtFSDySSSo8NSObjectCGSgycfU_TA
- _$sSo20LACAnalyticsReporterC23LocalAuthenticationCoreE9sendEvent4name7payloadSbSS_SDySSypGtFTf4nnd_n
- _$sSo20LACAnalyticsReporterC23LocalAuthenticationCoreE9sendEvent4name7payloadSbSS_SDySSypGtFTo
- _OBJC_CLASS_$_LACCredentialSignpostEvent
- _OBJC_METACLASS_$_LACCredentialSignpostEvent
- _OUTLINED_FUNCTION_101
- __OBJC_$_CLASS_METHODS_LACCredentialSignpostEvent
- __OBJC_$_CLASS_PROP_LIST_LACCredentialSignpostEvent
- __OBJC_$_INSTANCE_METHODS_LACCredentialSignpostEvent
- __OBJC_$_PROP_LIST_LACCredentialSignpostEvent
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_LACCredentialSignpostEventProvider
- __OBJC_$_PROTOCOL_METHOD_TYPES_LACCredentialSignpostEventProvider
- __OBJC_$_PROTOCOL_REFS_LACCredentialSignpostEventProvider
- __OBJC_CLASS_PROTOCOLS_$_LACCredentialSignpostEvent
- __OBJC_CLASS_RO_$_LACCredentialSignpostEvent
- __OBJC_LABEL_PROTOCOL_$_LACCredentialSignpostEventProvider
- __OBJC_METACLASS_RO_$_LACCredentialSignpostEvent
- __OBJC_PROTOCOL_$_LACCredentialSignpostEventProvider
- ___44+[LACCredentialSignpostEvent sharedInstance]_block_invoke
- ___81-[LACCredentialSignpostEvent extractableCredentialWriteAttemptWithAccessAllowed:]_block_invoke
- ___81-[LACCredentialSignpostEvent extractableCredentialWriteAttemptWithAccessAllowed:]_block_invoke_2
- ___83-[LACCredentialSignpostEvent extractableCredentialFailedWriteAttemptWithSigningID:]_block_invoke
- ___83-[LACCredentialSignpostEvent extractableCredentialFailedWriteAttemptWithSigningID:]_block_invoke_2
- ___84-[LACCredentialSignpostEvent extractableCredentialReadAttemptWithAge:accessAllowed:]_block_invoke
- ___84-[LACCredentialSignpostEvent extractableCredentialReadAttemptWithAge:accessAllowed:]_block_invoke_2
- ___86-[LACCredentialSignpostEvent extractableCredentialFailedReadAttemptWithAge:signingID:]_block_invoke
- ___86-[LACCredentialSignpostEvent extractableCredentialFailedReadAttemptWithAge:signingID:]_block_invoke_2
- ___block_descriptor_33_e23_"LACSignpostEvent"8?0l
- ___block_descriptor_33_e5_v8?0l
- ___block_descriptor_40_e8_32s_e23_"LACSignpostEvent"8?0ls32l8
- ___block_descriptor_41_e8_32s_e23_"LACSignpostEvent"8?0ls32l8
- ___block_descriptor_41_e8_32s_e5_v8?0ls32l8
- ___block_descriptor_48_e8_32s40s_e23_"LACSignpostEvent"8?0ls32l8s40l8
CStrings:
+ "%s:%spid:%d,%s:%s%s%s%s%s%u:%s cccurve25519 failed: small-order point used%s\n"
+ "%{private}s"
+ "Accessing the credential encoding seed requires the '%s' or '%s' entitlement"
+ "Backoff event sent: action=%ld"
+ "Injected LACPolicyOptionCheckApplePayEnabled rid: %u"
+ "OneTimeSignal event sent: type=%ld, occurrences=%ld"
+ "PeriodicSignal event sent: type=%ld, min=%ld, avg=%ld, max=%ld"
+ "Recovery event sent: lockedTime=%ld, unlockMechanism=%ld"
+ "SuppressionSignal event sent: trigger=%s, strategy=%s, suppressor=%s"
+ "TriggerSignal event sent: strategy=%s, signal=%s, networkReachable=%{bool}d, keybagLocked=%{bool}d"
+ "com.apple.LocalAuthentication.Analytics"
+ "com.apple.LocalAuthentication.ContextManagement.ContextExhaustion"
+ "com.apple.LocalAuthentication.ContextManagement.Registration"
+ "com.apple.LocalAuthentication.ContextManagement.Transfer"
+ "com.apple.LocalAuthentication.Credentials.EncodingSeedAttempt"
+ "com.apple.LocalAuthentication.Credentials.EncodingSeedAttemptInternal"
+ "com.apple.LocalAuthentication.TCC.FaceID"
+ "generate_wrapping_key_curve25519"
+ "pbioa"
- " enableTelemetry=YES  age=%{public,signpost.telemetry:number1,name=age}d  ok=%{public,signpost.telemetry:number2,name=ok}d "
- " enableTelemetry=YES  age=%{public,signpost.telemetry:number1,name=age}d  sid=%{public,signpost.telemetry:string1,name=sid}@ "
- " enableTelemetry=YES  ok=%{public,signpost.telemetry:number1,name=ok}d "
- " enableTelemetry=YES  sid=%{public,signpost.telemetry:string1,name=sid}@ "
- "%s CoreAnalytics event: %{private}s, payload:%{private}s"
- "ACMCredential - ACMCredentialDataPKITokenValidated"
- "ACMCredential - ACMCredentialDataPKITokenValidated2"
- "Backoff event %s: action=%ld"
- "CredentialExtractAge"
- "CredentialExtractFailed"
- "CredentialWriteAttempt"
- "CredentialWriteFailed"
- "OneTimeSignal event %s: type=%ld, occurrences=%ld"
- "PeriodicSignal event %s: type=%ld, min=%ld, avg=%ld, max=%ld"
- "Recovery event %s: lockedTime=%ld, unlockMechanism=%ld"
- "SuppressionSignal event %s: trigger=%s, strategy=%s, suppressor=%s"
- "TriggerSignal event %s: strategy=%s, signal=%s, networkReachable=%{bool}d, keybagLocked=%{bool}d"
```
