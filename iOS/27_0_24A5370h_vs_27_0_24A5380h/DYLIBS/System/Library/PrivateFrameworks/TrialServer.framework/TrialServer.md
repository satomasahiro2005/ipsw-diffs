## TrialServer

> `/System/Library/PrivateFrameworks/TrialServer.framework/TrialServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15e124` | `0x151730` | **`-0xc9f4`** |
| `__DATA.__bss` | `0x10a0` | `0x118` | **`-0xf88`** |
| `__AUTH_CONST.__auth_got` | `0xf40` | `0x0` | **`-0xf40`** |
| `__TEXT.__const` | `0x18ec` | `0xeec` | **`-0xa00`** |
| `__TEXT.__cstring` | `0x16dfb` | `0x1698c` | **`-0x46f`** |
| `__AUTH_CONST.__const` | `0x1708` | `0x1320` | **`-0x3e8`** |
| `__TEXT.__unwind_info` | `0x4650` | `0x4378` | **`-0x2d8`** |
| `__TEXT.__eh_frame` | `0x2d0` | `—` | **`-0x2d0`** |
| `__TEXT.__constg_swiftt` | `0x2c4` | `0x38` | **`-0x28c`** |
| `__TEXT.__swift5_typeref` | `0x260` | `0x14` | **`-0x24c`** |
| `__DATA.__data` | `0x2d7c` | `0x2b40` | **`-0x23c`** |
| `__AUTH_CONST.__cfstring` | `0xeca0` | `0xeea0` | **`+0x200`** |
| `__TEXT.__oslogstring` | `0x1e04e` | `0x1de95` | **`-0x1b9`** |
| `__AUTH.__data` | `0x880` | `0x6e0` | **`-0x1a0`** |
| `__AUTH.__objc_data` | `0x14d0` | `0x1398` | **`-0x138`** |
| `__AUTH_CONST.__objc_const` | `0x18418` | `0x182e0` | **`-0x138`** |
| `__DATA_CONST.__got` | `0x1578` | `0x1440` | **`-0x138`** |
| `__TEXT.__delay_helper` | `0x794` | `0x8cc` | **`+0x138`** |
| `__TEXT.__swift5_fieldmd` | `0x10c` | `0x10` | **`-0xfc`** |
| `__TEXT.__swift5_assocty` | `0x90` | `—` | **`-0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x65f8` | `0x6570` | **`-0x88`** |
| `__TEXT.__swift5_proto` | `0x7c` | `—` | **`-0x7c`** |
| `__TEXT.__swift5_reflstr` | `0x6a` | `—` | **`-0x6a`** |
| `__DATA_CONST.__const` | `0x68d8` | `0x6940` | **`+0x68`** |
| `__TEXT.__swift5_builtin` | `0x64` | `—` | **`-0x64`** |
| `__TEXT.__objc_methlist` | `0xc814` | `0xc7b4` | **`-0x60`** |
| `__TEXT.__swift5_capture` | `0x50` | `—` | **`-0x50`** |
| `__TEXT.__swift5_types` | `0x40` | `0x4` | **`-0x3c`** |
| `__TEXT.__gcc_except_tab` | `0x7ebc` | `0x7ee8` | **`+0x2c`** |
| `__DATA_CONST.__objc_classlist` | `0x9d0` | `0x9c0` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x280` | `0x270` | **`-0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x60` | `0x50` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x3c8` | `0x3d8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x960` | `0x968` | **`+0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0x1f8` | `0x1fc` | **`+0x4`** |

### Other Changes

```diff

-505.0.0.0.0
+507.0.0.0.0

-  - /System/Library/Frameworks/CryptoKit.framework/CryptoKit

-  - /System/Library/PrivateFrameworks/CryptoKitPrivate.framework/CryptoKitPrivate

+  - /System/Library/PrivateFrameworks/TrialEncryption.framework/TrialEncryption

-  - /usr/lib/swift/libswiftos.dylib
-  Functions: 5242
-  Symbols:   9533
-  CStrings:  4255
+  Functions: 4979
+  Symbols:   9386
+  CStrings:  4228
Symbols:
+ +[TRITaskUtils updateRolloutHistoryDatabaseWithAllocationStatus:forRollout:ramp:deployment:fps:namespaces:telemetryMetric:categoricalReason:rolloutRecord:isBecomingObsolete:context:]
+ -[TRIBAACertManager _issueAndWaitForCerts:semaphore:]
+ -[TRIBAACertManager initWithBase64Encoder:timeProvider:deviceIdentityProvider:semaphoreTimeoutNanos:]
+ -[TRIDecryptNotificationsTask _addMetric:]
+ -[TRIDecryptNotificationsTask _emitWKMSAndBAAMetricsForError:]
+ -[TRIDecryptNotificationsTask dimensions]
+ -[TRIDecryptNotificationsTask metrics]
+ -[TRIDecryptNotificationsTask trialSystemTelemetry]
+ -[TRIRealDeviceIdentityProvider _buildOptions]
+ -[TRIRealDeviceIdentityProvider isSupported]
+ -[TRIRealDeviceIdentityProvider issueCertificateOnQueue:completion:]
+ _OBJC_CLASS_$_TRICryptoKitBridge$loadHelper_x8
+ _OBJC_CLASS_$_TRICryptoKitBridge$loadHelper_x8$for$+[TRIAES256GCMCrypto _decryptDataWithCryptoKit:withKey:aad:error:]+0
+ _OBJC_CLASS_$_TRIRealDeviceIdentityProvider
+ _OBJC_CLASS_$_TRISelfSignedCertificateGenerator$loadHelper_x8
+ _OBJC_CLASS_$__TtC11TrialServer30TRIDecryptionOutcomeClassifier
+ _OBJC_IVAR_$_TRIBAACertManager._deviceIdentityProvider
+ _OBJC_IVAR_$_TRIBAACertManager._semaphoreTimeoutNanos
+ _OBJC_METACLASS_$_TRIRealDeviceIdentityProvider
+ _OBJC_METACLASS_$__TtC11TrialServer30TRIDecryptionOutcomeClassifier
+ _TRIMetricName_E2EEBAACertOutcome
+ _TRIMetricName_E2EEDecryptOutcome
+ _TRIMetricName_E2EEDecryptRetryCount
+ _TRIMetricName_E2EEDedupHit
+ _TRIMetricName_E2EEWKMSFetchOutcome
+ _TRIPlplistEligibleExperimentStatuses
+ __CLASS_METHODS__TtC11TrialServer30TRIDecryptionOutcomeClassifier
+ __DATA__TtC11TrialServer30TRIDecryptionOutcomeClassifier
+ __INSTANCE_METHODS__TtC11TrialServer30TRIDecryptionOutcomeClassifier
+ __METACLASS_DATA__TtC11TrialServer30TRIDecryptionOutcomeClassifier
+ __OBJC_$_INSTANCE_METHODS_TRIRealDeviceIdentityProvider
+ __OBJC_$_PROP_LIST_TRIRealDeviceIdentityProvider
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_TRIDeviceIdentityProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_TRIDeviceIdentityProviding
+ __OBJC_$_PROTOCOL_REFS_TRIDeviceIdentityProviding
+ __OBJC_CLASS_PROTOCOLS_$_TRIRealDeviceIdentityProvider
+ __OBJC_CLASS_RO_$_TRIRealDeviceIdentityProvider
+ __OBJC_LABEL_PROTOCOL_$_TRIDeviceIdentityProviding
+ __OBJC_METACLASS_RO_$_TRIRealDeviceIdentityProvider
+ __OBJC_PROTOCOL_$_TRIDeviceIdentityProviding
+ ___53-[TRIBAACertManager _issueAndWaitForCerts:semaphore:]_block_invoke
+ ___53-[TRIBAACertManager _issueAndWaitForCerts:semaphore:]_block_invoke_2
+ ___TRIPlplistEligibleExperimentStatuses_block_invoke
+ ___block_descriptor_48_e8_32s40s_e43_v32?0^{__SecKey=}8"NSArray"16"NSError"24ls32l8s40l8
+ ___block_descriptor_56_e8_32s40r48r_e5_v8?0lr40l8s32l8r48l8
+ ___block_descriptor_72_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ __readRetryCount
+ _dlopenHelper$TrialEncryption
+ _dlopenHelperFlag$TrialEncryption
+ _kAssistantPublicPreferenceDomain
+ _kTRIBAACertNetworkTimeoutInterval
+ _kTRIBAACertValidityDays
+ _kTRIBAAKeychainAccessGroup
+ _kTRIBAAKeychainLabel
+ _symbolic _____ 11TrialServer30TRIDecryptionOutcomeClassifierC
- -[TRIBAACertManager _issueAndWaitForCerts:semaphore:resultKey:result:]
- _NSURLAuthenticationMethodClientCertificate
- _NSURLAuthenticationMethodServerTrust
- _OBJC_CLASS_$_NSHTTPURLResponse
- _OBJC_CLASS_$_NSURLCredential
- _OBJC_CLASS_$_NSURLSession
- _OBJC_CLASS_$_NSURLSessionConfiguration
- _OBJC_CLASS_$_OS_os_log
- _OBJC_CLASS_$__TtCs12_SwiftObject
- _OBJC_METACLASS_$_TRICryptoKitBridge
- _OBJC_METACLASS_$_TRISelfSignedCertificateGenerator
- _OBJC_METACLASS_$__TtC11TrialServerP33_0ABDD8BE8CF1C9FE456BEA393458657724TRIBAAClientCertDelegate
- _OBJC_METACLASS_$__TtCs12_SwiftObject
- _SecIdentityCreate
- _SecKeyCopyExternalRepresentation
- _SecRandomCopyBytes
- __Block_copy
- __Block_release
- __CLASS_METHODS_TRICryptoKitBridge
- __CLASS_METHODS_TRISelfSignedCertificateGenerator
- __CLASS_PROPERTIES_TRICryptoKitBridge
- __DATA_TRICryptoKitBridge
- __DATA_TRISelfSignedCertificateGenerator
- __DATA__TtC11TrialServerP33_0ABDD8BE8CF1C9FE456BEA393458657718TRIWKMSClientProxy
- __DATA__TtC11TrialServerP33_0ABDD8BE8CF1C9FE456BEA393458657724TRIBAAClientCertDelegate
- __INSTANCE_METHODS_TRICryptoKitBridge
- __INSTANCE_METHODS_TRISelfSignedCertificateGenerator
- __INSTANCE_METHODS__TtC11TrialServerP33_0ABDD8BE8CF1C9FE456BEA393458657724TRIBAAClientCertDelegate
- __IVARS__TtC11TrialServerP33_0ABDD8BE8CF1C9FE456BEA393458657718TRIWKMSClientProxy
- __IVARS__TtC11TrialServerP33_0ABDD8BE8CF1C9FE456BEA393458657724TRIBAAClientCertDelegate
- __METACLASS_DATA_TRICryptoKitBridge
- __METACLASS_DATA_TRISelfSignedCertificateGenerator
- __METACLASS_DATA__TtC11TrialServerP33_0ABDD8BE8CF1C9FE456BEA393458657718TRIWKMSClientProxy
- __METACLASS_DATA__TtC11TrialServerP33_0ABDD8BE8CF1C9FE456BEA393458657724TRIBAAClientCertDelegate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSURLSessionDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_NSURLSessionDelegate
- __OBJC_$_PROTOCOL_REFS_NSURLSessionDelegate
- __OBJC_LABEL_PROTOCOL_$_NSURLSessionDelegate
- __OBJC_PROTOCOL_$_NSURLSessionDelegate
- __PROTOCOLS__TtC11TrialServerP33_0ABDD8BE8CF1C9FE456BEA393458657724TRIBAAClientCertDelegate
- ___70-[TRIBAACertManager _issueAndWaitForCerts:semaphore:resultKey:result:]_block_invoke
- ___70-[TRIBAACertManager _issueAndWaitForCerts:semaphore:resultKey:result:]_block_invoke_2
- ___block_descriptor_64_e8_32s40s48r56r_e5_v8?0ls32l8s40l8r48l8r56l8
- ___block_descriptor_64_e8_32s40s_e43_v32?0^{__SecKey=}8"NSArray"16"NSError"24ls32l8s40l8
- ___block_descriptor_88_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
- ___chkstk_darwin
- ___swift__destructor
- ___swift_allocate_boxed_opaque_existential_0Tm
- ___swift_closure_destructor
- ___swift_deallocate_boxed_opaque_existential_1
- ___swift_destroy_boxed_opaque_existential_1
- ___swift_instantiateConcreteTypeFromMangledNameAbstractV2
- ___swift_instantiateConcreteTypeFromMangledNameV2
- ___swift_memcpy1_1
- ___swift_memcpy32_8
- ___swift_noop_void_return
- ___swift_project_boxed_opaque_existential_1
- __swiftEmptyArrayStorage
- __swiftEmptyDictionarySingleton
- __swiftImmortalRefCount
- __swift_FORCE_LOAD_$_swiftos
- __swift_FORCE_LOAD_$_swiftos_$_TrialServer
- __swift_stdlib_malloc_size
- __swift_stdlib_reportUnimplementedInitializer
- _associated conformance 11TrialServer12TRIHPKEErrorO10Foundation15_BridgedNSErrorAA8RawValueSY_s17FixedWidthInteger
- _associated conformance 11TrialServer12TRIHPKEErrorO10Foundation15_BridgedNSErrorAASH
- _associated conformance 11TrialServer12TRIHPKEErrorO10Foundation15_BridgedNSErrorAASY
- _associated conformance 11TrialServer12TRIHPKEErrorO10Foundation15_BridgedNSErrorAaD26_ObjectiveCBridgeableError
- _associated conformance 11TrialServer12TRIHPKEErrorO10Foundation26_ObjectiveCBridgeableErrorAAs0G0
- _associated conformance 11TrialServer12TRIHPKEErrorOSHAASQ
- _associated conformance 11TrialServer12TRIWKMSErrorO10Foundation15_BridgedNSErrorAA8RawValueSY_s17FixedWidthInteger
- _associated conformance 11TrialServer12TRIWKMSErrorO10Foundation15_BridgedNSErrorAASH
- _associated conformance 11TrialServer12TRIWKMSErrorO10Foundation15_BridgedNSErrorAASY
- _associated conformance 11TrialServer12TRIWKMSErrorO10Foundation15_BridgedNSErrorAaD26_ObjectiveCBridgeableError
- _associated conformance 11TrialServer12TRIWKMSErrorO10Foundation26_ObjectiveCBridgeableErrorAAs0G0
- _associated conformance 11TrialServer12TRIWKMSErrorOSHAASQ
- _associated conformance 11TrialServer18TRICryptoKitBridgeC14WKMSAuthMethodOSHAASQ
- _associated conformance 11TrialServer18TRICryptoKitBridgeC9ErrorCodeOSHAASQ
- _associated conformance 11TrialServer20TRIWKMSFetchResponseV10CodingKeysOSHAASQ
- _associated conformance 11TrialServer20TRIWKMSFetchResponseV10CodingKeysOs0E3KeyAAs23CustomStringConvertible
- _associated conformance 11TrialServer20TRIWKMSFetchResponseV10CodingKeysOs0E3KeyAAs28CustomDebugStringConvertible
- _associated conformance 11TrialServer23TRICryptoKitBridgeErrorO10Foundation021_ObjectiveCBridgeableF0AAs0F0
- _associated conformance 11TrialServer23TRICryptoKitBridgeErrorO10Foundation15_BridgedNSErrorAA8RawValueSY_s17FixedWidthInteger
- _associated conformance 11TrialServer23TRICryptoKitBridgeErrorO10Foundation15_BridgedNSErrorAASH
- _associated conformance 11TrialServer23TRICryptoKitBridgeErrorO10Foundation15_BridgedNSErrorAASY
- _associated conformance 11TrialServer23TRICryptoKitBridgeErrorO10Foundation15_BridgedNSErrorAaD021_ObjectiveCBridgeableF0
- _associated conformance 11TrialServer23TRICryptoKitBridgeErrorOSHAASQ
- _block_copy_helper
- _block_descriptor
- _block_destroy_helper
- _kCFAllocatorDefault
- _kSecAttrKeyClassPrivate
- _kSecRandomDefault
- _malloc_size
- _memcpy
- _memmove
- _objc_allocWithZone
- _swift_allocBox
- _swift_allocError
- _swift_allocObject
- _swift_arrayDestroy
- _swift_arrayInitWithCopy
- _swift_beginAccess
- _swift_bridgeObjectRelease_n
- _swift_bridgeObjectRetain
- _swift_cvw_assignWithCopy
- _swift_cvw_assignWithTake
- _swift_cvw_destroy
- _swift_cvw_initStructMetadataWithLayoutString
- _swift_cvw_initWithCopy
- _swift_cvw_initWithTake
- _swift_cvw_initializeBufferWithCopyOfBuffer
- _swift_deallocClassInstance
- _swift_deallocObject
- _swift_deletedMethodError
- _swift_dynamicCastObjCClass
- _swift_errorRelease
- _swift_errorRetain
- _swift_getEnumTagSinglePayloadGeneric
- _swift_getErrorValue
- _swift_getForeignTypeMetadata
- _swift_getSingletonMetadata
- _swift_getTypeByMangledNameInContext2
- _swift_getTypeByMangledNameInContextInMetadataState2
- _swift_getWitnessTable
- _swift_initStackObject
- _swift_isUniquelyReferenced_nonNull_native
- _swift_once
- _swift_release
- _swift_release_x1
- _swift_release_x19
- _swift_release_x20
- _swift_release_x21
- _swift_release_x22
- _swift_release_x23
- _swift_release_x24
- _swift_release_x25
- _swift_release_x26
- _swift_release_x27
- _swift_release_x28
- _swift_release_x8
- _swift_retain
- _swift_retain_x2
- _swift_retain_x20
- _swift_retain_x21
- _swift_retain_x22
- _swift_retain_x23
- _swift_retain_x25
- _swift_retain_x26
- _swift_retain_x27
- _swift_retain_x28
- _swift_setDeallocating
- _swift_slowDealloc
- _swift_storeEnumTagSinglePayloadGeneric
- _swift_willThrow
- _swift_willThrowTypedImpl
- _symbolic $sSY
- _symbolic SS
- _symbolic SSSg
- _symbolic SS_SSt
- _symbolic SS_ypt
- _symbolic SaySSG
- _symbolic Say_____G So17SecCertificateRefa
- _symbolic Si
- _symbolic Siz_Xx
- _symbolic So21OS_dispatch_semaphoreC
- _symbolic _____ 10Foundation4DateV
- _symbolic _____ 11TrialServer12TRIHPKEErrorO
- _symbolic _____ 11TrialServer12TRIWKMSErrorO
- _symbolic _____ 11TrialServer18TRICryptoKitBridgeC
- _symbolic _____ 11TrialServer18TRICryptoKitBridgeC14WKMSAuthMethodO
- _symbolic _____ 11TrialServer18TRICryptoKitBridgeC9ErrorCodeO
- _symbolic _____ 11TrialServer18TRIWKMSClientProxy33_0ABDD8BE8CF1C9FE456BEA3934586577LLC
- _symbolic _____ 11TrialServer20TRIWKMSFetchResponseV
- _symbolic _____ 11TrialServer20TRIWKMSFetchResponseV10CodingKeysO
- _symbolic _____ 11TrialServer23TRICryptoKitBridgeErrorO
- _symbolic _____ 11TrialServer24TRIBAAClientCertDelegate33_0ABDD8BE8CF1C9FE456BEA3934586577LLC
- _symbolic _____ 11TrialServer33TRISelfSignedCertificateGeneratorC
- _symbolic _____ 11TrialServer33TRISelfSignedCertificateGeneratorC14ValidityPeriod33_24C6F6E46695326F2D621F8BBF8B1D7FLLV
- _symbolic _____ So9SecKeyRefa
- _symbolic _____Sg 10Foundation3URLV
- _symbolic _____Sg 10Foundation4DataV
- _symbolic _____Sg 10Foundation8TimeZoneV
- _symbolic _____Sg 9CryptoKit3AESO3GCMO5NonceV
- _symbolic _____Sgz_Xx 10Foundation4DataV
- _symbolic _____XDXMT 11TrialServer18TRIWKMSClientProxy33_0ABDD8BE8CF1C9FE456BEA3934586577LLC
- _symbolic ______p 10Foundation15ContiguousBytesP
- _symbolic ______p s5ErrorP
- _symbolic ______pSg s5ErrorP
- _symbolic ______pSgz_Xx s5ErrorP
- _symbolic _____ySSG s23_ContiguousArrayStorageC
- _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
- _symbolic _____ySSypG s18_DictionaryStorageC
- _symbolic _____ySsG s23_ContiguousArrayStorageC
- _symbolic _____y_____G s22KeyedDecodingContainerV 11TrialServer20TRIWKMSFetchResponseV10CodingKeysO
- _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
- _symbolic _____y_____G s23_ContiguousArrayStorageC s6UInt64V
- _symbolic _____y______pG s23_ContiguousArrayStorageC s7CVarArgP
- _symbolic _____yyXlG s23_ContiguousArrayStorageC
- _symbolic _____yypG s23_ContiguousArrayStorageC
- _symbolic _____yyp_yptG s23_ContiguousArrayStorageC
- _type_layout_string 11TrialServer20TRIWKMSFetchResponseV
CStrings:
+ "/System/Library/PrivateFrameworks/TrialEncryption.framework/TrialEncryption"
+ "Experiment update date is before the original start date. Overwriting the end date. ID: %{public}@"
+ "Jun 26 2026"
+ "TRIBAACertManager: Calling DeviceIdentity to issue certificate"
+ "TrialXP-507"
+ "com.apple.assistant.public"
+ "decrypt_failed"
+ "decryption-auth-unavailable"
+ "decryption-baa-cert-generation-failed"
+ "decryption-failed"
+ "decryption-invalid-auth-data"
+ "decryption-missing-auth-data"
+ "decryption-unknown-error"
+ "decryption-wkms-key-fetch-failed"
+ "device_not_activated"
+ "e2ee_baa_cert_outcome"
+ "e2ee_decrypt_outcome"
+ "e2ee_decrypt_retry_count"
+ "e2ee_dedup_hit"
+ "e2ee_wkms_fetch_outcome"
+ "keychain_unavailable_transient"
+ "missing_entitlement"
+ "network_transient"
+ "success"
+ "wkms_fetch_failed"
- "1$"
- "AES-GCM decryption failed"
- "AES-GCM encryption failed"
- "AES-GCM encryption failed: combined data unavailable"
- "Certificate chain is empty"
- "Ciphertext too short"
- "Created SecIdentity for TLS client authentication using SecIdentityCreate (no keychain query)"
- "CryptoKit fallback doesn't support non-empty AAD, use CommonCrypto"
- "Data too short for HPKE ciphertext"
- "Error domain: %{public}@, code: %ld"
- "Failed to create DeviceIdentity options"
- "Failed to create SecCertificate from data"
- "Failed to create SecIdentity: %{public}@"
- "Failed to decode base64 ciphertext"
- "Failed to decode base64 key"
- "Failed to decode base64 leaf certificate"
- "Failed to decode base64 private key"
- "Failed to decode base64 wrapped key"
- "HPKE unwrap failed"
- "HPKE unwrap failed: invalid private key"
- "HTTP error: status code %d"
- "Invalid base64 for encapsulated key"
- "Invalid base64 for wrapped key"
- "Invalid key length"
- "Jun 12 2026"
- "Network error: %{public}@"
- "SecIdentityCreate returned nil"
- "Starting WKMS fetch with %{public}@ authentication"
- "Successfully unwrapped key from WKMS using %{public}@"
- "TRIBAACertManager: BAA is supported but certificate generation returned incomplete results - reliability issue"
- "TRIBAACertManager: Calling DeviceIdentityIssueClientCertificateWithCompletion"
- "TRIBAACertManager: Certificate generation returned incomplete results due to transient error. Error: %@ (domain: %@, code: %ld)"
- "TRIBAACertManager: DeviceIdentity returned NULL referenceKey"
- "TRIBAACertManager: DeviceIdentity returned empty or nil certificate array"
- "TRIBAACertManager: Error userInfo: %@"
- "TRIBAACertManager: Platform not supported for BAA certificate generation"
- "TRICryptoKitBridgeActualLength"
- "TRICryptoKitBridgeErrorReason"
- "TRICryptoKitBridgeExpectedLength"
- "TRICryptoKitBridgeExpectedMinLength"
- "TrialServer.TRIBAAClientCertDelegate"
- "TrialServer.TRICryptoKitBridgeError"
- "TrialServer.TRIHPKEError"
- "TrialServer.TRIWKMSError"
- "TrialXP-505"
- "WKMS fetch with %{public}@ failed: %{public}@"
- "application/json"
- "com.apple.TrialServer.CryptoKitBridge"
- "enc-request"
- "https://assets-external.sd.apple.com/"
- "init()"
- "wrapped-key"
```
