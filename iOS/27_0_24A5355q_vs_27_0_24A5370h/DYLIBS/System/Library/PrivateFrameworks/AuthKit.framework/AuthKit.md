## AuthKit

> `/System/Library/PrivateFrameworks/AuthKit.framework/AuthKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1afe9c` | `0x19f4d0` | **`-0x109cc`** |
| `__TEXT.__const` | `0xc8d3` | `0xd30` | **`-0xbba3`** |
| `__DATA_CONST.__const` | `0xbaf0` | `0x78a8` | **`-0x4248`** |
| `__TEXT.__cstring` | `0x1334f` | `0x12f02` | **`-0x44d`** |
| `__AUTH_CONST.__cfstring` | `0x14220` | `0x13f20` | **`-0x300`** |
| `__TEXT.__unwind_info` | `0x4a70` | `0x4830` | **`-0x240`** |
| `__TEXT.__oslogstring` | `0x15a62` | `0x158a1` | **`-0x1c1`** |
| `__TEXT.__gcc_except_tab` | `0x672c` | `0x65c4` | **`-0x168`** |
| `__AUTH_CONST.__auth_got` | `0x668` | `0x518` | **`-0x150`** |
| `__AUTH_CONST.__const` | `0x14e0` | `0x13e0` | **`-0x100`** |
| `__TEXT.__dlopen_cstrs` | `0x31b` | `0x267` | **`-0xb4`** |
| `__TEXT.__objc_methlist` | `0x1054c` | `0x1049c` | **`-0xb0`** |
| `__DATA.__bss` | `0x738` | `0x6d0` | **`-0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x81e0` | `0x8178` | **`-0x68`** |
| `__AUTH_CONST.__objc_const` | `0x2e4e8` | `0x2e488` | **`-0x60`** |
| `__AUTH.__objc_data` | `0x3480` | `0x34d0` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x19a0` | `0x1950` | **`-0x50`** |
| `__AUTH_CONST.__objc_intobj` | `0x318` | `0x300` | **`-0x18`** |
| `__DATA.__data` | `0x1b78` | `0x1b70` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x4d0` | `0x4c8` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__ustring`

### Other Changes

```diff

-550.0.0.0.0
+552.0.0.0.0

-  Functions: 6286
-  Symbols:   12995
-  CStrings:  4678
+  Functions: 6091
+  Symbols:   12279
+  CStrings:  4613
Symbols:
+ +[AKDisplayNameFormatter displayNameForAccount:]
+ +[AKDisplayNameFormatter displayNameWithGivenName:familyName:]
+ -[AKAppleIDAuthenticationContext _didCollectUserCredentials]
+ -[AKAppleIDAuthenticationContext set_didCollectUserCredentials:]
+ -[AKAppleIDAuthenticationContext(Accounts) aidaAccount:]
+ -[AKAppleIDAuthenticationContext(Accounts) iCloudAccount:]
+ -[AKAppleIDPasskeyAuthenticationController syncPasskeyCredentialNameForAccount:userHandle:expectedName:completion:]
+ -[AKBasicServerRequest setTelemetryFlowID:]
+ -[AKBasicServerRequest telemetryFlowID]
+ -[AKCLIServerUIFlowController .cxx_destruct]
+ -[AKCLIServerUIFlowController _beginCLIServerUIFlowWithModel:completion:]
+ -[AKCLIServerUIFlowController _logResponse:]
+ -[AKCLIServerUIFlowController _nextStepForResponse:]
+ -[AKCLIServerUIFlowController _processNextStep:response:model:completion:]
+ -[AKCLIServerUIFlowController _processResponse:model:withCompletion:]
+ -[AKCLIServerUIFlowController beginCLIServerUIFlowWithModel:completion:]
+ -[AKCLIServerUIFlowController setSupportedCLIServerUIFlowSteps:]
+ -[AKCLIServerUIFlowController supportedCLIServerUIFlowSteps]
+ -[AKCLIServerUIFlowModel .cxx_destruct]
+ -[AKCLIServerUIFlowModel cliUtilities]
+ -[AKCLIServerUIFlowModel configuration]
+ -[AKCLIServerUIFlowModel context]
+ -[AKCLIServerUIFlowModel initWithContext:configuration:utilities:]
+ -[AKCLIServerUIFlowModel setCliUtilities:]
+ -[AKCLIServerUIFlowModel setConfiguration:]
+ -[AKCLIServerUIFlowModel setContext:]
+ -[AKCLIServerUIFlowResponse .cxx_destruct]
+ -[AKCLIServerUIFlowResponse data]
+ -[AKCLIServerUIFlowResponse httpResponse]
+ -[AKCLIServerUIFlowResponse initWithData:httpResponse:]
+ -[AKCLIServerUIFlowResponse(XMLExtraction) logXMLWithStepName:]
+ -[AKCLIServerUIFlowResponse(XMLExtraction) submitURLExcludingDismiss:]
+ GCC_except_table104
+ GCC_except_table105
+ GCC_except_table112
+ GCC_except_table115
+ GCC_except_table116
+ GCC_except_table144
+ GCC_except_table145
+ GCC_except_table154
+ GCC_except_table171
+ GCC_except_table187
+ GCC_except_table193
+ GCC_except_table195
+ GCC_except_table204
+ GCC_except_table208
+ GCC_except_table212
+ GCC_except_table214
+ GCC_except_table222
+ GCC_except_table223
+ GCC_except_table257
+ GCC_except_table258
+ GCC_except_table259
+ GCC_except_table261
+ GCC_except_table265
+ GCC_except_table267
+ GCC_except_table287
+ GCC_except_table288
+ GCC_except_table306
+ GCC_except_table309
+ GCC_except_table312
+ GCC_except_table327
+ GCC_except_table328
+ GCC_except_table329
+ GCC_except_table330
+ GCC_except_table331
+ GCC_except_table361
+ GCC_except_table367
+ GCC_except_table370
+ GCC_except_table371
+ GCC_except_table51
+ GCC_except_table54
+ GCC_except_table69
+ _AKAppleIDPasskeyDataUserHandleKey
+ _AKAppleIDPasskeyDataUserNameKey
+ _AKAuthKitUIMacMachService
+ _AKCredentialCollectionIsLoud
+ _AKURLBagKeyPDPLogFeature
+ _OBJC_CLASS_$_AKCLIServerUIFlowController
+ _OBJC_CLASS_$_AKCLIServerUIFlowModel
+ _OBJC_CLASS_$_AKCLIServerUIFlowResponse
+ _OBJC_CLASS_$_AKDisplayNameFormatter
+ _OBJC_CLASS_$_NSPersonNameComponents
+ _OBJC_CLASS_$_NSPersonNameComponentsFormatter
+ _OBJC_IVAR_$_AKAppleIDAuthenticationContext.__didCollectUserCredentials
+ _OBJC_IVAR_$_AKBasicServerRequest._telemetryFlowID
+ _OBJC_IVAR_$_AKCLIServerUIFlowController._supportedCLIServerUIFlowSteps
+ _OBJC_IVAR_$_AKCLIServerUIFlowModel._cliUtilities
+ _OBJC_IVAR_$_AKCLIServerUIFlowModel._configuration
+ _OBJC_IVAR_$_AKCLIServerUIFlowModel._context
+ _OBJC_IVAR_$_AKCLIServerUIFlowResponse._data
+ _OBJC_IVAR_$_AKCLIServerUIFlowResponse._httpResponse
+ _OBJC_METACLASS_$_AKCLIServerUIFlowController
+ _OBJC_METACLASS_$_AKCLIServerUIFlowModel
+ _OBJC_METACLASS_$_AKCLIServerUIFlowResponse
+ _OBJC_METACLASS_$_AKDisplayNameFormatter
+ __OBJC_$_CLASS_METHODS_AKDisplayNameFormatter
+ __OBJC_$_INSTANCE_METHODS_AKCLIServerUIFlowController
+ __OBJC_$_INSTANCE_METHODS_AKCLIServerUIFlowModel
+ __OBJC_$_INSTANCE_METHODS_AKCLIServerUIFlowResponse(XMLExtraction)
+ __OBJC_$_INSTANCE_VARIABLES_AKCLIServerUIFlowController
+ __OBJC_$_INSTANCE_VARIABLES_AKCLIServerUIFlowModel
+ __OBJC_$_INSTANCE_VARIABLES_AKCLIServerUIFlowResponse
+ __OBJC_$_PROP_LIST_AKCLIServerUIFlowController
+ __OBJC_$_PROP_LIST_AKCLIServerUIFlowModel
+ __OBJC_$_PROP_LIST_AKCLIServerUIFlowResponse
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AKCLIServerUIFlowStep
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AKCLIServerUIFlowStep
+ __OBJC_$_PROTOCOL_REFS_AKCLIServerUIFlowStep
+ __OBJC_CLASS_RO_$_AKCLIServerUIFlowController
+ __OBJC_CLASS_RO_$_AKCLIServerUIFlowModel
+ __OBJC_CLASS_RO_$_AKCLIServerUIFlowResponse
+ __OBJC_CLASS_RO_$_AKDisplayNameFormatter
+ __OBJC_LABEL_PROTOCOL_$_AKCLIServerUIFlowStep
+ __OBJC_METACLASS_RO_$_AKCLIServerUIFlowController
+ __OBJC_METACLASS_RO_$_AKCLIServerUIFlowModel
+ __OBJC_METACLASS_RO_$_AKCLIServerUIFlowResponse
+ __OBJC_METACLASS_RO_$_AKDisplayNameFormatter
+ __OBJC_PROTOCOL_$_AKCLIServerUIFlowStep
+ ___115-[AKAppleIDPasskeyAuthenticationController syncPasskeyCredentialNameForAccount:userHandle:expectedName:completion:]_block_invoke
+ ___73-[AKCLIServerUIFlowController _beginCLIServerUIFlowWithModel:completion:]_block_invoke
+ ___74-[AKCLIServerUIFlowController _processNextStep:response:model:completion:]_block_invoke
+ ___88-[AKChildAccountCreationCLIServerUIHandler beginWithData:httpResponse:model:completion:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e56_v32?0"NSHTTPURLResponse"8"NSDictionary"16"NSError"24ls40l8s32l8
+ ___block_descriptor_56_e8_32s40bs48w_e46_v32?0"NSData"8"NSURLResponse"16"NSError"24lw48l8s40l8s32l8
+ ___block_descriptor_72_e8_32s40s48s56bs64w_e5_v8?0lw64l8s56l8s32l8s40l8s48l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72bs_e17_v16?0"NSArray"8ls32l8s72l8s40l8s48l8s56l8s64l8
+ _kAKBasicServerRequestTelemetryFlowID
- +[AKAttestationSigner sharedSigner]
- -[AKAccountManager updatePasskeyCredentialsWithAltDSID:username:]
- -[AKAccountRecoveryModel .cxx_destruct]
- -[AKAccountRecoveryModel cliUtilities]
- -[AKAccountRecoveryModel configuration]
- -[AKAccountRecoveryModel context]
- -[AKAccountRecoveryModel initWithContext:configuration:utilities:]
- -[AKAccountRecoveryModel setCliUtilities:]
- -[AKAccountRecoveryModel setConfiguration:]
- -[AKAccountRecoveryModel setContext:]
- -[AKAccountRecoveryResponse .cxx_destruct]
- -[AKAccountRecoveryResponse data]
- -[AKAccountRecoveryResponse httpResponse]
- -[AKAccountRecoveryResponse initWithData:httpResponse:]
- -[AKAccountRecoveryResponse(XMLExtraction) logXMLWithStepName:]
- -[AKAccountRecoveryResponse(XMLExtraction) submitURLExcludingDismiss:]
- -[AKAppleIDRecoveryController .cxx_destruct]
- -[AKAppleIDRecoveryController _beginAccountRecoveryWithModel:completion:]
- -[AKAppleIDRecoveryController _logResponse:]
- -[AKAppleIDRecoveryController _nextStepForResponse:]
- -[AKAppleIDRecoveryController _processNextStep:response:model:completion:]
- -[AKAppleIDRecoveryController _processResponse:model:withCompletion:]
- -[AKAppleIDRecoveryController beginAccountRecoveryWithModel:completion:]
- -[AKAppleIDRecoveryController setSupportedRecoverySteps:]
- -[AKAppleIDRecoveryController supportedRecoverySteps]
- -[AKAppleIDServerResourceLoadDelegate _signRequestWithBAAHeaders:]
- -[AKAppleIDSigningController signaturesForData:options:completion:]
- -[AKAppleIDSigningController(Convenience) _additionalAttestationHeadersForRequest:options:completion:]
- -[AKAppleIDSigningController(Convenience) _parseDERCertificatesFromChain:error:]
- -[AKAppleIDSigningController(Convenience) signWithBAAHeaders:completion:]
- -[AKAttestationSigner .cxx_destruct]
- -[AKAttestationSigner _attestationWithCertificates:error:]
- -[AKAttestationSigner _baaSignatureForData:completion:]
- -[AKAttestationSigner _baaSignaturesForData:completion:]
- -[AKAttestationSigner _signatureForData:withReferenceKey:error:]
- -[AKAttestationSigner init]
- -[AKAttestationSigner signatureForData:options:completion:]
- -[AKAttestationSigner signaturesForData:options:completion:]
- -[AKChildAccountCreationCLIServerUIHandler .cxx_destruct]
- -[AKChildAccountCreationCLIServerUIHandler _nextStepForResponse:]
- -[AKChildAccountCreationCLIServerUIHandler _processResponse:model:completion:]
- -[AKChildAccountCreationCLIServerUIHandler setSteps:]
- -[AKChildAccountCreationCLIServerUIHandler steps]
- -[AKFeatureManager isAuthenticationTelemetryEnabled]
- -[AKFeatureManager isServerBackoffEnabled]
- -[AKURLBag isBaaEnabledForKey:]
- GCC_except_table100
- GCC_except_table111
- GCC_except_table139
- GCC_except_table140
- GCC_except_table142
- GCC_except_table143
- GCC_except_table149
- GCC_except_table165
- GCC_except_table172
- GCC_except_table176
- GCC_except_table178
- GCC_except_table186
- GCC_except_table189
- GCC_except_table198
- GCC_except_table200
- GCC_except_table209
- GCC_except_table210
- GCC_except_table217
- GCC_except_table218
- GCC_except_table229
- GCC_except_table230
- GCC_except_table236
- GCC_except_table238
- GCC_except_table262
- GCC_except_table282
- GCC_except_table283
- GCC_except_table301
- GCC_except_table304
- GCC_except_table307
- GCC_except_table315
- GCC_except_table316
- GCC_except_table317
- GCC_except_table318
- GCC_except_table319
- GCC_except_table356
- GCC_except_table365
- GCC_except_table381
- GCC_except_table382
- GCC_except_table383
- GCC_except_table384
- GCC_except_table385
- GCC_except_table64
- GCC_except_table99
- _ACRTRootPublicKey
- _ACRTRoot_public_key
- _AKAttestationSignerKeychainAccessGroup
- _AKAttestationSignerKeychainLabel
- _AKAttestationSignerValidity
- _AKAttestationUseDeviceCheckKeychainAccess
- _ApplePlatformBackportECCRootCAG1
- _ApplePlatformBackportECCRootCAG1PublicKey
- _ApplePlatformBackportECCRootCAG1SKID
- _ApplePlatformBackportECCRootCAG1SPKI
- _ApplePlatformBackportECCRootCAG1_public_key
- _ApplePlatformBackportECCRootCAG1_skid
- _ApplePlatformBackportECCRootCAG1_spki
- _ApplePlatformBackportRSARootCAG1
- _ApplePlatformBackportRSARootCAG1PublicKey
- _ApplePlatformBackportRSARootCAG1SKID
- _ApplePlatformBackportRSARootCAG1SPKI
- _ApplePlatformBackportRSARootCAG1_public_key
- _ApplePlatformBackportRSARootCAG1_skid
- _ApplePlatformBackportRSARootCAG1_spki
- _ApplePlatformBootstrapECCRootCAG1
- _ApplePlatformBootstrapECCRootCAG1PublicKey
- _ApplePlatformBootstrapECCRootCAG1SKID
- _ApplePlatformBootstrapECCRootCAG1SPKI
- _ApplePlatformBootstrapECCRootCAG1_public_key
- _ApplePlatformBootstrapECCRootCAG1_skid
- _ApplePlatformBootstrapECCRootCAG1_spki
- _ApplePlatformCodeSigningECCRootCAG1
- _ApplePlatformCodeSigningECCRootCAG1PublicKey
- _ApplePlatformCodeSigningECCRootCAG1SKID
- _ApplePlatformCodeSigningECCRootCAG1SPKI
- _ApplePlatformCodeSigningECCRootCAG1_public_key
- _ApplePlatformCodeSigningECCRootCAG1_skid
- _ApplePlatformCodeSigningECCRootCAG1_spki
- _ApplePlatformCodeSigningMLDSA_RSARootCAG1
- _ApplePlatformCodeSigningMLDSA_RSARootCAG1PublicKey
- _ApplePlatformCodeSigningMLDSA_RSARootCAG1SKID
- _ApplePlatformCodeSigningMLDSA_RSARootCAG1SPKI
- _ApplePlatformCodeSigningMLDSA_RSARootCAG1_public_key
- _ApplePlatformCodeSigningMLDSA_RSARootCAG1_skid
- _ApplePlatformCodeSigningMLDSA_RSARootCAG1_spki
- _ApplePlatformCodeSigningRSARootCAG1
- _ApplePlatformCodeSigningRSARootCAG1PublicKey
- _ApplePlatformCodeSigningRSARootCAG1SKID
- _ApplePlatformCodeSigningRSARootCAG1SPKI
- _ApplePlatformCodeSigningRSARootCAG1_public_key
- _ApplePlatformCodeSigningRSARootCAG1_skid
- _ApplePlatformCodeSigningRSARootCAG1_spki
- _ApplePlatformDeveloperECCRootCAG1
- _ApplePlatformDeveloperECCRootCAG1PublicKey
- _ApplePlatformDeveloperECCRootCAG1SKID
- _ApplePlatformDeveloperECCRootCAG1SPKI
- _ApplePlatformDeveloperECCRootCAG1_public_key
- _ApplePlatformDeveloperECCRootCAG1_skid
- _ApplePlatformDeveloperECCRootCAG1_spki
- _ApplePlatformDeveloperRSARootCAG1
- _ApplePlatformDeveloperRSARootCAG1PublicKey
- _ApplePlatformDeveloperRSARootCAG1SKID
- _ApplePlatformDeveloperRSARootCAG1SPKI
- _ApplePlatformDeveloperRSARootCAG1_public_key
- _ApplePlatformDeveloperRSARootCAG1_skid
- _ApplePlatformDeveloperRSARootCAG1_spki
- _ApplePlatformECCRootCAG1
- _ApplePlatformECCRootCAG1PublicKey
- _ApplePlatformECCRootCAG1SKID
- _ApplePlatformECCRootCAG1SPKI
- _ApplePlatformECCRootCAG1_public_key
- _ApplePlatformECCRootCAG1_skid
- _ApplePlatformECCRootCAG1_spki
- _ApplePlatformMultipurposeECCRootCAG1
- _ApplePlatformMultipurposeECCRootCAG1PublicKey
- _ApplePlatformMultipurposeECCRootCAG1SKID
- _ApplePlatformMultipurposeECCRootCAG1SPKI
- _ApplePlatformMultipurposeECCRootCAG1_public_key
- _ApplePlatformMultipurposeECCRootCAG1_skid
- _ApplePlatformMultipurposeECCRootCAG1_spki
- _ApplePlatformMultipurposeRSARootCAG1
- _ApplePlatformMultipurposeRSARootCAG1PublicKey
- _ApplePlatformMultipurposeRSARootCAG1SKID
- _ApplePlatformMultipurposeRSARootCAG1SPKI
- _ApplePlatformMultipurposeRSARootCAG1_public_key
- _ApplePlatformMultipurposeRSARootCAG1_skid
- _ApplePlatformMultipurposeRSARootCAG1_spki
- _ApplePlatformRSARootCAG1
- _ApplePlatformRSARootCAG1PublicKey
- _ApplePlatformRSARootCAG1SKID
- _ApplePlatformRSARootCAG1SPKI
- _ApplePlatformRSARootCAG1_public_key
- _ApplePlatformRSARootCAG1_skid
- _ApplePlatformRSARootCAG1_spki
- _ApplePlatformTLSECCRootCAG1
- _ApplePlatformTLSECCRootCAG1PublicKey
- _ApplePlatformTLSECCRootCAG1SKID
- _ApplePlatformTLSECCRootCAG1SPKI
- _ApplePlatformTLSECCRootCAG1_public_key
- _ApplePlatformTLSECCRootCAG1_skid
- _ApplePlatformTLSECCRootCAG1_spki
- _ApplePlatformTLSRSARootCAG1
- _ApplePlatformTLSRSARootCAG1PublicKey
- _ApplePlatformTLSRSARootCAG1SKID
- _ApplePlatformTLSRSARootCAG1SPKI
- _ApplePlatformTLSRSARootCAG1_public_key
- _ApplePlatformTLSRSARootCAG1_skid
- _ApplePlatformTLSRSARootCAG1_spki
- _AppleRootCA
- _AppleRootCAG2
- _AppleRootCAG2SPKI
- _AppleRootCAG2_skid
- _AppleRootCAG2_spki
- _AppleRootCAG3
- _AppleRootCAG3SPKI
- _AppleRootCAG3_skid
- _AppleRootCAG3_spki
- _AppleRootCASPKI
- _AppleRootCA_skid
- _AppleRootCA_spki
- _AppleRootFlags
- _AppleRootSPKIs
- _AppleRoots
- _BAARoots
- _BASepAppRoot
- _BASepAppRootPublicKey
- _BASepAppRootSKID
- _BASepAppRootSPKI
- _BASepAppRoot_public_key
- _BASepAppRoot_skid
- _BASepAppRoot_spki
- _BASystemRoot
- _BASystemRootPublicKey
- _BASystemRootSKID
- _BASystemRootSPKI
- _BASystemRoot_public_key
- _BASystemRoot_skid
- _BASystemRoot_spki
- _BAUserRoot
- _BAUserRootPublicKey
- _BAUserRootSKID
- _BAUserRootSPKI
- _BAUserRoot_public_key
- _BAUserRoot_skid
- _BAUserRoot_spki
- _BlockedYonkersSPKI
- _BlockedYonkers_spki
- _CMSAttributeParseAppleHashAgility
- _CMSAttributeParseAppleHashAgilityV2
- _CMSAttributeParseContentType
- _CMSAttributeParseMessageDigest
- _CMSAttributeParseSMIMECapabilities
- _CMSAttributeParseSigningTime
- _CMSBuildPath
- _CMSGetCertificateUsingIssuerSerialNumber
- _CMSParseContentInfoSignedData
- _CMSParseContentInfoSignedDataWithOptions
- _CMSParseEncapsulatedContent
- _CMSParseImplicitCertificateSet
- _CMSParseSignedData
- _CMSParseSignerInfos
- _CMSVerify
- _CMSVerifyAndReturnSignedData
- _CMSVerifySignedData
- _CMSVerifySignedDataWithLeaf
- _CTCompareGeneralNameToHostname
- _CTCopyUID
- _CTEvaluateAcrt
- _CTEvaluateAppleSSL
- _CTEvaluateAppleSSLWithOptionalTemporalCheck
- _CTEvaluateCertifiedChip
- _CTEvaluateCertsForPolicy
- _CTEvaluateICDPFederation
- _CTEvaluateKDLSignatureCMS
- _CTEvaluateKeyTransparency
- _CTEvaluatePragueSignatureCMS
- _CTEvaluateSEK
- _CTEvaluateSatori
- _CTEvaluateSavageCerts
- _CTEvaluateSavageCertsWithUID
- _CTEvaluateSensorCerts
- _CTEvaluateUcrt
- _CTEvaluateUcrtTestRoot
- _CTEvaluateVLTileSigning
- _CTEvaluateYonkersCerts
- _CTGetAKIDFromCertificate
- _CTGetICDPFederationType
- _CTGetSEKType
- _CTGetSKIDFromCertificate
- _CTOctetServerAuthEKU
- _CTOidAlgorithmProtection
- _CTOidAppleAAICA
- _CTOidAppleAAICAG3
- _CTOidAppleASICA4
- _CTOidAppleCertifiedChipCA
- _CTOidAppleCertifiedChipLeaf
- _CTOidAppleCloudManaged
- _CTOidAppleCodeSigningCA
- _CTOidAppleComponentAuth
- _CTOidAppleDeveloperID
- _CTOidAppleDeveloperIDCA
- _CTOidAppleDeviceAttestationDeviceOSInformation
- _CTOidAppleDeviceAttestationHardwareProperties
- _CTOidAppleDeviceAttestationIdentity
- _CTOidAppleDeviceAttestationKeyUsageProperties
- _CTOidAppleDeviceAttestationNonce
- _CTOidAppleExtensionArc
- _CTOidAppleGenericSSLMarker
- _CTOidAppleHashAgility
- _CTOidAppleHashAgilityV2
- _CTOidAppleHaven
- _CTOidAppleImg4Manifest
- _CTOidAppleKextDenyListSigning
- _CTOidAppleKeyTransparencyLeaf
- _CTOidAppleMFI4Properties
- _CTOidAppleMFIAuthv3
- _CTOidAppleMFISWAuth
- _CTOidAppleMacAppStore
- _CTOidAppleMacAppStoreDev
- _CTOidAppleMacDeveloper
- _CTOidAppleMacPlatform
- _CTOidAppleMacPlatformQA
- _CTOidAppleMacSubmission
- _CTOidApplePragueSigning
- _CTOidAppleProvisioningProfileSigner
- _CTOidAppleSatoriExternalEncryption
- _CTOidAppleServerAuthCA
- _CTOidAppleServerAuthExtensionPrefix
- _CTOidAppleServerAuthExtensionPrefixLen
- _CTOidAppleServerAuthExtensionPrefixString
- _CTOidAppleTVOSAppStoreDev
- _CTOidAppleTVOSAppStoreProd
- _CTOidAppleTestFlightDev
- _CTOidAppleTestFlightProd
- _CTOidAppleUniqueDeviceIdentifiers
- _CTOidAppleVLTilesSigning
- _CTOidAppleWWDRCA
- _CTOidAppleXROSAppStoreDev
- _CTOidAppleXROSAppStoreProd
- _CTOidAppleiPhoneAppStoreDev
- _CTOidAppleiPhoneAppStoreProd
- _CTOidAppleiPhoneCA
- _CTOidAppleiPhoneDeveloper
- _CTOidAppleiPhoneDistribution
- _CTOidAppleiPhoneVPNAppDev
- _CTOidAppleiPhoneVPNAppProd
- _CTOidAuthorityKeyID
- _CTOidBasicConstraints
- _CTOidCommonName
- _CTOidContentType
- _CTOidExtendedKeyUsage
- _CTOidItemAppleDeviceAttestationDeviceOSInformation
- _CTOidItemAppleDeviceAttestationHardwareProperties
- _CTOidItemAppleDeviceAttestationKeyUsageProperties
- _CTOidItemAppleDeviceAttestationNonce
- _CTOidItemAppleImg4Manifest
- _CTOidKeyUsage
- _CTOidMessageDigest
- _CTOidSECP256r1
- _CTOidSECP384r1
- _CTOidSECP521r1
- _CTOidSMIMECapabilities
- _CTOidServerAuthEKU
- _CTOidSha1
- _CTOidSha224
- _CTOidSha256
- _CTOidSha384
- _CTOidSha512
- _CTOidSigningTime
- _CTOidSubjectAltName
- _CTOidSubjectKeyID
- _CTParseCertificateSet
- _CTParseExtensionValue
- _CTParseKey
- _CTVerifyAppleMarkerExtension
- _CTVerifyHostname
- _CodeSigningCAName
- _CodeSigningCAName_str
- _DevICDPFederationRoot152PublicKey
- _DevICDPFederationRoot152SKID
- _DevICDPFederationRoot152_public_key
- _DevICDPFederationRoot152_skid
- _DevICDPFederationRoot4PublicKey
- _DevICDPFederationRoot4SKID
- _DevICDPFederationRoot4_public_key
- _DevICDPFederationRoot4_skid
- _ICDPFederationRoot101PublicKey
- _ICDPFederationRoot101SKID
- _ICDPFederationRoot101_public_key
- _ICDPFederationRoot101_skid
- _ICDPFederationRoot102PublicKey
- _ICDPFederationRoot102SKID
- _ICDPFederationRoot102_public_key
- _ICDPFederationRoot102_skid
- _ICDPFederationRoot103PublicKey
- _ICDPFederationRoot103SKID
- _ICDPFederationRoot103_public_key
- _ICDPFederationRoot103_skid
- _ICDPFederationRoot310PublicKey
- _ICDPFederationRoot310SKID
- _ICDPFederationRoot310_public_key
- _ICDPFederationRoot310_skid
- _ICDPFederationRoot500PublicKey
- _ICDPFederationRoot500SKID
- _ICDPFederationRoot500_public_key
- _ICDPFederationRoot500_skid
- _MFICommonNamePrefix
- _MFICommonNamePrefix_str
- _MFi4AccessoryCAName
- _MFi4AccessoryCAName_str
- _MFi4AttestationCAName
- _MFi4AttestationCAName_str
- _MFi4ProvisioningCAName
- _MFi4ProvisioningCAName_str
- _MFi4ProvisioningHostNamePrefix
- _MFi4ProvisioningHostNamePrefix_str
- _MFi4RootPublicKey
- _MFi4RootSKID
- _MFi4RootSPKI
- _MFi4Root_public_key
- _MFi4Root_skid
- _MFi4Root_spki
- _OBJC_CLASS_$_AKAccountRecoveryModel
- _OBJC_CLASS_$_AKAccountRecoveryResponse
- _OBJC_CLASS_$_AKAppleIDRecoveryController
- _OBJC_CLASS_$_AKAttestationSigner
- _OBJC_IVAR_$_AKAccountRecoveryModel._cliUtilities
- _OBJC_IVAR_$_AKAccountRecoveryModel._configuration
- _OBJC_IVAR_$_AKAccountRecoveryModel._context
- _OBJC_IVAR_$_AKAccountRecoveryResponse._data
- _OBJC_IVAR_$_AKAccountRecoveryResponse._httpResponse
- _OBJC_IVAR_$_AKAppleIDRecoveryController._supportedRecoverySteps
- _OBJC_IVAR_$_AKAttestationSigner._attestationQueue
- _OBJC_IVAR_$_AKChildAccountCreationCLIServerUIHandler._steps
- _OBJC_METACLASS_$_AKAccountRecoveryModel
- _OBJC_METACLASS_$_AKAccountRecoveryResponse
- _OBJC_METACLASS_$_AKAppleIDRecoveryController
- _OBJC_METACLASS_$_AKAttestationSigner
- _SDeviceIdentityCreateHostSignature
- _SDeviceIdentityIssueClientCertificateWithCompletion
- _SEKProdRootPublicKey
- _SEKProdRootSKID
- _SEKProdRoot_public_key
- _SEKProdRoot_skid
- _SEKTestRootPublicKey
- _SEKTestRootSKID
- _SEKTestRoot_public_key
- _SEKTestRoot_skid
- _SecCertificateCopyData
- _TestApplePlatformBackportECCRootCAG1
- _TestApplePlatformBackportECCRootCAG1PublicKey
- _TestApplePlatformBackportECCRootCAG1SKID
- _TestApplePlatformBackportECCRootCAG1SPKI
- _TestApplePlatformBackportECCRootCAG1_public_key
- _TestApplePlatformBackportECCRootCAG1_skid
- _TestApplePlatformBackportECCRootCAG1_spki
- _TestApplePlatformBackportRSARootCAG1
- _TestApplePlatformBackportRSARootCAG1PublicKey
- _TestApplePlatformBackportRSARootCAG1SKID
- _TestApplePlatformBackportRSARootCAG1SPKI
- _TestApplePlatformBackportRSARootCAG1_public_key
- _TestApplePlatformBackportRSARootCAG1_skid
- _TestApplePlatformBackportRSARootCAG1_spki
- _TestApplePlatformBootstrapECCRootCAG1
- _TestApplePlatformBootstrapECCRootCAG1PublicKey
- _TestApplePlatformBootstrapECCRootCAG1SKID
- _TestApplePlatformBootstrapECCRootCAG1SPKI
- _TestApplePlatformBootstrapECCRootCAG1_public_key
- _TestApplePlatformBootstrapECCRootCAG1_skid
- _TestApplePlatformBootstrapECCRootCAG1_spki
- _TestApplePlatformCodeSigningECCRootCAG1
- _TestApplePlatformCodeSigningECCRootCAG1PublicKey
- _TestApplePlatformCodeSigningECCRootCAG1SKID
- _TestApplePlatformCodeSigningECCRootCAG1SPKI
- _TestApplePlatformCodeSigningECCRootCAG1_public_key
- _TestApplePlatformCodeSigningECCRootCAG1_skid
- _TestApplePlatformCodeSigningECCRootCAG1_spki
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1PublicKey
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1SKID
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1SPKI
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_HW
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_HWPublicKey
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_HWSKID
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_HWSPKI
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_HW_public_key
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_HW_skid
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_HW_spki
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_draft13
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_draft13PublicKey
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_draft13SKID
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_draft13SPKI
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_draft13_public_key
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_draft13_skid
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_draft13_spki
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_public_key
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_skid
- _TestApplePlatformCodeSigningMLDSA_RSARootCAG1_spki
- _TestApplePlatformCodeSigningRSARootCAG1
- _TestApplePlatformCodeSigningRSARootCAG1PublicKey
- _TestApplePlatformCodeSigningRSARootCAG1SKID
- _TestApplePlatformCodeSigningRSARootCAG1SPKI
- _TestApplePlatformCodeSigningRSARootCAG1_public_key
- _TestApplePlatformCodeSigningRSARootCAG1_skid
- _TestApplePlatformCodeSigningRSARootCAG1_spki
- _TestApplePlatformDeveloperECCRootCAG1
- _TestApplePlatformDeveloperECCRootCAG1PublicKey
- _TestApplePlatformDeveloperECCRootCAG1SKID
- _TestApplePlatformDeveloperECCRootCAG1SPKI
- _TestApplePlatformDeveloperECCRootCAG1_public_key
- _TestApplePlatformDeveloperECCRootCAG1_skid
- _TestApplePlatformDeveloperECCRootCAG1_spki
- _TestApplePlatformDeveloperRSARootCAG1
- _TestApplePlatformDeveloperRSARootCAG1PublicKey
- _TestApplePlatformDeveloperRSARootCAG1SKID
- _TestApplePlatformDeveloperRSARootCAG1SPKI
- _TestApplePlatformDeveloperRSARootCAG1_public_key
- _TestApplePlatformDeveloperRSARootCAG1_skid
- _TestApplePlatformDeveloperRSARootCAG1_spki
- _TestApplePlatformECCRootCAG1
- _TestApplePlatformECCRootCAG1PublicKey
- _TestApplePlatformECCRootCAG1SKID
- _TestApplePlatformECCRootCAG1SPKI
- _TestApplePlatformECCRootCAG1_public_key
- _TestApplePlatformECCRootCAG1_skid
- _TestApplePlatformECCRootCAG1_spki
- _TestApplePlatformMultipurposeECCRootCAG1
- _TestApplePlatformMultipurposeECCRootCAG1PublicKey
- _TestApplePlatformMultipurposeECCRootCAG1SKID
- _TestApplePlatformMultipurposeECCRootCAG1SPKI
- _TestApplePlatformMultipurposeECCRootCAG1_public_key
- _TestApplePlatformMultipurposeECCRootCAG1_skid
- _TestApplePlatformMultipurposeECCRootCAG1_spki
- _TestApplePlatformMultipurposeRSARootCAG1
- _TestApplePlatformMultipurposeRSARootCAG1PublicKey
- _TestApplePlatformMultipurposeRSARootCAG1SKID
- _TestApplePlatformMultipurposeRSARootCAG1SPKI
- _TestApplePlatformMultipurposeRSARootCAG1_public_key
- _TestApplePlatformMultipurposeRSARootCAG1_skid
- _TestApplePlatformMultipurposeRSARootCAG1_spki
- _TestApplePlatformRSARootCAG1
- _TestApplePlatformRSARootCAG1PublicKey
- _TestApplePlatformRSARootCAG1SKID
- _TestApplePlatformRSARootCAG1SPKI
- _TestApplePlatformRSARootCAG1_public_key
- _TestApplePlatformRSARootCAG1_skid
- _TestApplePlatformRSARootCAG1_spki
- _TestApplePlatformTLSECCRootCAG1
- _TestApplePlatformTLSECCRootCAG1PublicKey
- _TestApplePlatformTLSECCRootCAG1SKID
- _TestApplePlatformTLSECCRootCAG1SPKI
- _TestApplePlatformTLSECCRootCAG1_public_key
- _TestApplePlatformTLSECCRootCAG1_skid
- _TestApplePlatformTLSECCRootCAG1_spki
- _TestApplePlatformTLSRSARootCAG1
- _TestApplePlatformTLSRSARootCAG1PublicKey
- _TestApplePlatformTLSRSARootCAG1SKID
- _TestApplePlatformTLSRSARootCAG1SPKI
- _TestApplePlatformTLSRSARootCAG1_public_key
- _TestApplePlatformTLSRSARootCAG1_skid
- _TestApplePlatformTLSRSARootCAG1_spki
- _TestAppleRootCA
- _TestAppleRootCAG2
- _TestAppleRootCAG2SPKI
- _TestAppleRootCAG2_skid
- _TestAppleRootCAG2_spki
- _TestAppleRootCAG3
- _TestAppleRootCAG3SPKI
- _TestAppleRootCAG3_skid
- _TestAppleRootCAG3_spki
- _TestAppleRootCASPKI
- _TestAppleRootCA_skid
- _TestAppleRootCA_spki
- _TestAppleRootECC
- _TestAppleRootECCSPKI
- _TestAppleRootECC_skid
- _TestAppleRootECC_spki
- _UcrtRootPublicKey
- _UcrtRootSPKI
- _UcrtRoot_public_key
- _UcrtRoot_spki
- _X509CertificateCheckSignature
- _X509CertificateCheckSignatureDigest
- _X509CertificateCheckSignatureWithPublicKey
- _X509CertificateGetNotAfter
- _X509CertificateGetNotBefore
- _X509CertificateIsValid
- _X509CertificateParse
- _X509CertificateParseGeneralNamesContent
- _X509CertificateParseImplicit
- _X509CertificateParseKey
- _X509CertificateParseSPKI
- _X509CertificateParseValidity
- _X509CertificateParseWithExtension
- _X509CertificateSubjectNameGetCommonName
- _X509CertificateValidAtTime
- _X509CertificateVerifyOnlyOneAppleExtension
- _X509ChainBuildPath
- _X509ChainBuildPathPartial
- _X509ChainCheckPath
- _X509ChainCheckPathWithOptions
- _X509ChainGetAppleRootUsingKeyIdentifier
- _X509ChainGetBAARootUsingKeyIdentifier
- _X509ChainGetCertificateUsingKeyIdentifier
- _X509ChainParseCertificateSet
- _X509ChainResetChain
- _X509ExtensionParseAppleExtension
- _X509ExtensionParseAuthorityKeyIdentifier
- _X509ExtensionParseBasicConstraints
- _X509ExtensionParseCertifiedChipIntermediate
- _X509ExtensionParseComponentAuth
- _X509ExtensionParseDeviceAttestationIdentity
- _X509ExtensionParseExtendedKeyUsage
- _X509ExtensionParseGenericSSLMarker
- _X509ExtensionParseKeyTransparencyLeaf
- _X509ExtensionParseKeyUsage
- _X509ExtensionParseMFI4Properties
- _X509ExtensionParseMFISWAuth
- _X509ExtensionParseServerAuthMarker
- _X509ExtensionParseSubjectAltName
- _X509ExtensionParseSubjectKeyIdentifier
- _X509MatchSignatureAlgorithm
- _X509PolicyACRT
- _X509PolicyCheckForBlockedKeys
- _X509PolicyICDPFederation
- _X509PolicySEK
- _X509PolicySatori
- _X509PolicySavage
- _X509PolicySensor
- _X509PolicySetFlagsForCommonNames
- _X509PolicySetFlagsForMFI
- _X509PolicySetFlagsForRoots
- _X509PolicySetFlagsForTestAnchor
- _X509PolicyUcrt
- _X509PolicyVLTile
- _X509PolicyYonkers
- _X509TimeConvert
- __AKAttestationErrorCreate
- __AKAttestationErrorCreateWithUnderlyingError
- __AKAttestationOptionsFromOptions
- __AKAttestationValidityDefaultMinutes
- __AKSigningSessionConfigurationKeyBAAInterval
- __AKSigningSessionHeaderKeyBAAAttestation
- __AKSigningSessionHeaderKeyBAAAvailability
- __AKSigningSessionHeaderKeyBAAClientInfoSignature
- __AKSigningSessionHeaderKeyBAAClientTime
- __AKSigningSessionHeaderKeyBAADeviceIdSignature
- __AKSigningSessionHeaderKeyBAAError
- __AKSigningSessionHeaderKeyBAALocalUUIDSignature
- __AKSigningSessionHeaderKeyBAAPayloadHash
- __AKSigningSessionHeaderKeyBAAProvisioningIdSignature
- __AKSigningSessionHeaderKeyBAASignature
- __AKSigningSessionHeaderKeyBAASignedPayloadHash
- __AKSigningSessionHeaderKeyBAAUnerlyingErrors
- __AKSigningSessionHeaderKeyHostBAAAttestation
- __AKSigningSessionHeaderKeyHostBAAError
- __AKSigningSessionHeaderKeyHostBAASignedPayloadHash
- __AKSigningSessionProxyHeaderKeyBAAAttestation
- __AKSigningSessionProxyHeaderKeyBAAClientInfoSignature
- __AKSigningSessionProxyHeaderKeyBAAError
- __AKSigningSessionProxyHeaderKeyBAASignature
- __OBJC_$_CLASS_METHODS_AKAttestationSigner
- __OBJC_$_CLASS_PROP_LIST_AKAttestationSigner
- __OBJC_$_INSTANCE_METHODS_AKAccountRecoveryModel
- __OBJC_$_INSTANCE_METHODS_AKAccountRecoveryResponse(XMLExtraction)
- __OBJC_$_INSTANCE_METHODS_AKAppleIDRecoveryController
- __OBJC_$_INSTANCE_METHODS_AKAttestationSigner
- __OBJC_$_INSTANCE_VARIABLES_AKAccountRecoveryModel
- __OBJC_$_INSTANCE_VARIABLES_AKAccountRecoveryResponse
- __OBJC_$_INSTANCE_VARIABLES_AKAppleIDRecoveryController
- __OBJC_$_INSTANCE_VARIABLES_AKAttestationSigner
- __OBJC_$_INSTANCE_VARIABLES_AKChildAccountCreationCLIServerUIHandler
- __OBJC_$_PROP_LIST_AKAccountRecoveryModel
- __OBJC_$_PROP_LIST_AKAccountRecoveryResponse
- __OBJC_$_PROP_LIST_AKAppleIDRecoveryController
- __OBJC_$_PROP_LIST_AKChildAccountCreationCLIServerUIHandler
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_AKAccountRecoveryStep
- __OBJC_$_PROTOCOL_METHOD_TYPES_AKAccountRecoveryStep
- __OBJC_$_PROTOCOL_REFS_AKAccountRecoveryStep
- __OBJC_CLASS_RO_$_AKAccountRecoveryModel
- __OBJC_CLASS_RO_$_AKAccountRecoveryResponse
- __OBJC_CLASS_RO_$_AKAppleIDRecoveryController
- __OBJC_CLASS_RO_$_AKAttestationSigner
- __OBJC_LABEL_PROTOCOL_$_AKAccountRecoveryStep
- __OBJC_METACLASS_RO_$_AKAccountRecoveryModel
- __OBJC_METACLASS_RO_$_AKAccountRecoveryResponse
- __OBJC_METACLASS_RO_$_AKAppleIDRecoveryController
- __OBJC_METACLASS_RO_$_AKAttestationSigner
- __OBJC_PROTOCOL_$_AKAccountRecoveryStep
- ___102-[AKAppleIDSigningController(Convenience) _additionalAttestationHeadersForRequest:options:completion:]_block_invoke
- ___102-[AKAppleIDSigningController(Convenience) _additionalAttestationHeadersForRequest:options:completion:]_block_invoke_2
- ___35+[AKAttestationSigner sharedSigner]_block_invoke
- ___55-[AKAttestationSigner _baaSignatureForData:completion:]_block_invoke
- ___56-[AKAttestationSigner _baaSignaturesForData:completion:]_block_invoke
- ___58-[AKAttestationSigner _attestationWithCertificates:error:]_block_invoke
- ___59-[AKAttestationSigner signatureForData:options:completion:]_block_invoke
- ___60-[AKAttestationSigner signaturesForData:options:completion:]_block_invoke
- ___65-[AKAccountManager updatePasskeyCredentialsWithAltDSID:username:]_block_invoke
- ___66-[AKAppleIDServerResourceLoadDelegate _signRequestWithBAAHeaders:]_block_invoke
- ___67-[AKAppleIDSigningController signaturesForData:options:completion:]_block_invoke
- ___67-[AKAppleIDSigningController signaturesForData:options:completion:]_block_invoke_2
- ___73-[AKAppleIDRecoveryController _beginAccountRecoveryWithModel:completion:]_block_invoke
- ___73-[AKAppleIDSigningController(Convenience) signWithBAAHeaders:completion:]_block_invoke
- ___73-[AKAppleIDSigningController(Convenience) signWithBAAHeaders:completion:]_block_invoke_2
- ___74-[AKAppleIDRecoveryController _processNextStep:response:model:completion:]_block_invoke
- ___78-[AKChildAccountCreationCLIServerUIHandler _processResponse:model:completion:]_block_invoke
- ___79-[AKAppleIDSigningController(Convenience) signingHeadersForRequest:completion:]_block_invoke_2
- ___79-[AKAppleIDSigningController(Convenience) signingHeadersForRequest:completion:]_block_invoke_3
- ___block_descriptor_32_e18_"NSString"16?08l
- ___block_descriptor_32_e39_"NSString"24?0"NSString"8"NSData"16l
- ___block_descriptor_40_e8_32bs_e39_v32?0"NSData"8"NSData"16"NSError"24ls32l8
- ___block_descriptor_40_e8_32bs_e45_v32?0"NSDictionary"8"NSData"16"NSError"24ls32l8
- ___block_descriptor_48_e8_32s40bs_e45_v32?0"NSDictionary"8"NSData"16"NSError"24ls32l8s40l8
- ___block_descriptor_48_e8_32s40s_e20_v20?0B8"NSError"12ls32l8s40l8
- ___block_descriptor_48_e8_32s40s_e34_v24?0"NSDictionary"8"NSError"16ls32l8s40l8
- ___block_descriptor_56_e8_32s40bs48w_e45_v32?0"NSDictionary"8"NSData"16"NSError"24lw48l8s32l8s40l8
- ___block_descriptor_56_e8_32s40r_e41_"NSData"32?0"NSString"8"NSData"16^B24ls32l8r40l8
- ___block_descriptor_56_e8_32s40s48bs_e43_v32?0^{__SecKey=}8"NSArray"16"NSError"24ls32l8s40l8s48l8
- ___block_descriptor_56_e8_32s40s48bs_e70_v44?0B8"NSData"12"NSHTTPURLResponse"20"NSDictionary"28"NSError"36ls48l8s32l8s40l8
- ___block_descriptor_56_e8_32s40s48w_e34_v24?0"NSDictionary"8"NSError"16lw48l8s32l8s40l8
- ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
- ___block_descriptor_72_e8_32s40s48s56s64s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
- ___block_descriptor_80_e8_32s40s48s56s64bs72w_e34_v24?0"NSDictionary"8"NSError"16lw72l8s32l8s40l8s48l8s64l8s56l8
- ___block_descriptor_80_e8_32s40s48s56s64r72w_e5_v8?0lr64l8s32l8s40l8s48l8w72l8s56l8
- ___block_descriptor_88_e8_32s40s48s56s64s72bs80w_e29_v16?0"NSMutableDictionary"8ls32l8s40l8s48l8w80l8s56l8s64l8s72l8
- ___block_descriptor_88_e8_32s40s48s56s64s72s80bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s80l8s72l8
- ___getDeviceIdentityCreateHostSignatureSymbolLoc_block_invoke
- ___getDeviceIdentityIssueClientCertificateWithCompletionSymbolLoc_block_invoke
- ___getkMAOptionsBAAKeychainAccessGroupSymbolLoc_block_invoke
- ___getkMAOptionsBAAKeychainLabelSymbolLoc_block_invoke
- ___getkMAOptionsBAAOIDDeviceOSInformationSymbolLoc_block_invoke
- ___getkMAOptionsBAAOIDSToIncludeSymbolLoc_block_invoke
- ___getkMAOptionsBAAOIDUCRTDeviceIdentifiersSymbolLoc_block_invoke
- ___getkMAOptionsBAAValiditySymbolLoc_block_invoke
- ___memcpy_chk
- _algorithmIsPQCComposite
- _asciiNibbleToByte
- _bzero
- _ccder_blob_check_null
- _ccder_blob_decode_AlgorithmIdentifierNULL
- _ccder_blob_decode_GeneralName
- _ccder_blob_decode_Time
- _ccder_blob_decode_ber_len
- _ccder_blob_decode_ber_tl
- _ccder_blob_decode_bitstring
- _ccder_blob_decode_eoc
- _ccder_blob_decode_tag
- _ccder_blob_decode_tl
- _ccder_blob_decode_uint64
- _ccder_blob_eat_ber_inner
- _ccder_blob_encode_tl
- _ccder_decode_rsa_pub_n
- _ccder_sizeof_len
- _ccder_sizeof_tag
- _ccdigest
- _ccdigest_init
- _ccdigest_update
- _ccec_compressed_x962_export_pub
- _ccec_compressed_x962_export_pub_size
- _ccec_compressed_x962_import_pub
- _ccec_cp_256
- _ccec_cp_384
- _ccec_cp_521
- _ccec_cp_for_oid
- _ccec_export_pub
- _ccec_import_pub
- _ccec_keysize_is_supported
- _ccec_verify
- _ccec_verify_composite
- _ccec_x963_import_pub_size
- _cchybridsig_import_pubkey
- _cchybridsig_lamps13_mldsa87_rsa3072_pub_ctx_init
- _cchybridsig_mldsa87_rsa3072_pub_ctx_init
- _cchybridsig_verify_prehashed_with_context
- _ccrsa_import_pub
- _ccrsa_verify_pkcs1v15_allowshortsigs
- _ccsha1_di
- _ccsha224_di
- _ccsha256_di
- _ccsha384_di
- _ccsha512_di
- _cczp_bitlen
- _compare_octet_string
- _compare_octet_string_partial
- _compare_octet_string_raw
- _compressECPublicKey
- _decompressECPublicKey
- _der_get_boolean
- _difftime
- _digests
- _ecAlgs
- _ecPublicKey
- _ecPublicKey_oid
- _find_digest
- _find_digestOID_for_signingOID
- _find_digest_by_type
- _getDeviceIdentityCreateHostSignatureSymbolLoc
- _getDeviceIdentityCreateHostSignatureSymbolLoc.ptr
- _getDeviceIdentityIssueClientCertificateWithCompletionSymbolLoc
- _getDeviceIdentityIssueClientCertificateWithCompletionSymbolLoc.ptr
- _getkMAOptionsBAAKeychainAccessGroup
- _getkMAOptionsBAAKeychainAccessGroupSymbolLoc
- _getkMAOptionsBAAKeychainAccessGroupSymbolLoc.ptr
- _getkMAOptionsBAAKeychainLabel
- _getkMAOptionsBAAKeychainLabelSymbolLoc
- _getkMAOptionsBAAKeychainLabelSymbolLoc.ptr
- _getkMAOptionsBAAOIDDeviceOSInformation
- _getkMAOptionsBAAOIDDeviceOSInformationSymbolLoc
- _getkMAOptionsBAAOIDDeviceOSInformationSymbolLoc.ptr
- _getkMAOptionsBAAOIDSToInclude
- _getkMAOptionsBAAOIDSToIncludeSymbolLoc
- _getkMAOptionsBAAOIDSToIncludeSymbolLoc.ptr
- _getkMAOptionsBAAOIDUCRTDeviceIdentifiers
- _getkMAOptionsBAAOIDUCRTDeviceIdentifiersSymbolLoc
- _getkMAOptionsBAAOIDUCRTDeviceIdentifiersSymbolLoc.ptr
- _getkMAOptionsBAAValidity
- _getkMAOptionsBAAValiditySymbolLoc
- _getkMAOptionsBAAValiditySymbolLoc.ptr
- _iPhoneCAName
- _iPhoneCAName_str
- _icdpFederationAnchors
- _memcmp
- _null_octet
- _numAppleProdRoots
- _numAppleRoots
- _numBAARoots
- _numICDPRoots
- _oidForPubKeyLength
- _pkcs7_data_oid
- _pkcs7_data_oid_str
- _pkcs7_signedData_oid
- _pkcs7_signedData_oid_str
- _powersOfTen
- _pqcCompositeAlgs
- _rsaAlgs
- _rsaEncryption
- _rsaEncryption_oid
- _secp256r1_encoded_oid
- _secp384r1_encoded_oid
- _secp521r1_encoded_oid
- _sha1WithECDSA_oid
- _sha1WithRSA_oid
- _sha256WithECDSA_oid
- _sha256WithRSA_oid
- _sha384WithECDSA_oid
- _sha384WithRSA_oid
- _sha512WithECDSA_oid
- _sha512WithMLDSA87_RSA3072_draft13
- _sha512WithMLDSA87_RSA3072_draft7
- _sha512WithRSA_oid
- _strptime
- _time
- _timegm
- _validateOIDs
- _validateSignatureEC
- _validateSignaturePQCComposite
- _validateSignatureRSA
- _validateSignerInfo
- _validateSignerInfoAndChain
CStrings:
+ "<%@: %p; altDSID=%@, urlBagKey=%@, requestBody=%@, expectedResponseFormat=%lu, requestBodyFormat=%lu, telemetryFlowID=%@>"
+ "AAAFoundationBackoff"
+ "AKCredentialCollectionIsLoud"
+ "Adult age verification status spyglass required - setting AKOSEOptionRequireAdultAgeVerificationStatusSpyglass flag"
+ "Begin flow step: %@"
+ "Exception caught when fetching lastEventTimestamp property: %@"
+ "Failed to sync passkey - Missing parameters (account/userHandle/expectedName)"
+ "Failed to sync passkey - Missing username"
+ "Failed to sync passkey - getPasskeysDataForRelyingParty: unavailable"
+ "Finished flow for - %@"
+ "Finished flow step: %@"
+ "Found matching flow step: %@"
+ "No altDSID or username passed on context, unable to find AIDA account"
+ "No altDSID or username passed on context, unable to find iCloud account"
+ "No existing AIDA account for altDSID %{mask.hash}@"
+ "No existing AIDA account for username %{mask.hash}@"
+ "No existing iCloud account for altDSID %{mask.hash}@"
+ "No existing iCloud account for username %{mask.hash}@"
+ "No matching flow step found"
+ "No matching passkey for userHandle: %{mask.hash}@ - sync no-op"
+ "PDPLogFeature"
+ "Passkey username already matches for userHandle: %{mask.hash}@ - sync no-op"
+ "Passkey username drift detected for userHandle: %{mask.hash}@ - issuing rename"
+ "Server backoff disabled by URL bag."
+ "Unexpected non-HTTP response type: %@"
+ "XML parse failed: %@"
+ "_WKLocalAuthenticatorCredentialNameKey"
+ "_WKLocalAuthenticatorCredentialUserHandleKey"
+ "com.apple.ak.auth.authKitUIMacService"
+ "getPasskeysDataForRelyingParty returned nil results"
- "%@%@"
- "%F"
- "%Y%m%d%H%M%SZ"
- "%y%m%d%H%M%SZ"
- "2006-05-31"
- "<%@: %p; altDSID=%@, urlBagKey=%@, requestBody=%@, expectedResponseFormat=%lu, requestBodyFormat=%lu>"
- "@\"NSData\"32@?0@\"NSString\"8@\"NSData\"16^B24"
- "@\"NSString\"16@?0@8"
- "@\"NSString\"24@?0@\"NSString\"8@\"NSData\"16"
- "AKAttestationSigner signatureForData: - No data, nothing to sign."
- "AKAttestationSigner signaturesForData: - No data, nothing to sign."
- "AKAttestationSignerValidity"
- "AKAttestationUseDeviceCheckKeychainAccess"
- "Added additional BAA headers for request - %@"
- "Attestation error %@"
- "Attestation signature headers %@"
- "Authentication Telemetry"
- "AuthenticationTelemetry"
- "BAA is not enabled for URL key - %{public}@"
- "Begin account recovery step: %@"
- "DeviceIdentity not available"
- "DeviceIdentityCreateHostSignature"
- "DeviceIdentityIssueClientCertificateWithCompletion"
- "Failed to BAA, error: %@"
- "Failed to BAA, failed to generate signature: %@"
- "Failed to BAA, failed to generate signature: unknown error!"
- "Failed to BAA, failed to serialize: %@"
- "Failed to BAA, unknown error!"
- "Failed to fetch absinthe headers, error: %@"
- "Failed to fetch attestation headers, error: %@"
- "Failed to fetch host attestation headers, error: %@"
- "Failed to generate signatures, bailing!"
- "Failed to parse certificate set. rc=%d, numCerts=%zu"
- "Failed to process host certificate chain, error: %@"
- "Failed to update passkey credential after username change: %{private}@"
- "Finished account recovery step: %@"
- "Finished recovery flow for - %@"
- "Found matching recovery step: %@"
- "Invalid certData"
- "No baaInterval"
- "No matching child account step"
- "No matching recovery step found"
- "Received signed host data and certificate chain"
- "Repair UCRT"
- "Requesting additional Attestation for header"
- "Savage - Factory"
- "Server backoff feature is disabled."
- "Server delegate missing bagUrlKey, cannot determine if BAA attestation is needed"
- "ServerBackoff"
- "Signing request with BAA headers for key - %{public}@"
- "StepLoop_Incoming"
- "Successfully updated passkey credential after username change for altDSID: %{mask.hash}@"
- "UNMATCHED_RESPONSE"
- "Unknown absinthe error"
- "Unknown attestation error"
- "Updating passkey credentials for altDSID: %{mask.hash}@ with username: %@"
- "We have additional absinthe headers %@"
- "We have attesation headers: %@"
- "X-Apple-Baa"
- "X-Apple-Baa-Avail"
- "X-Apple-Baa-E"
- "X-Apple-Baa-S"
- "X-Apple-Baa-UE"
- "X-Apple-Host-Baa"
- "X-Apple-Host-Baa-E"
- "X-Apple-I-Baa-S"
- "X-Apple-I-Host-Baa-S"
- "X-Apple-I-MD-LU-S"
- "X-Apple-I-Payload-Hash"
- "X-Apple-I-Provisioning-Device-Id-S"
- "X-Apple-Proxied-Baa"
- "X-Apple-Proxied-Baa-E"
- "X-Apple-Proxied-Baa-S"
- "X-MMe-Client-Info-S"
- "X-MMe-Proxied-Client-Info-S"
- "X-Mme-Device-Id-S"
- "Yonkers - Factory"
- "[ChildAccountCreation] No matching step found for server response"
- "authkit/signatures-for-data"
- "baa-interval"
- "certs"
- "com.apple.akd"
- "com.apple.authkit.ATTQ"
- "hostCertificateChain: %@"
- "kMAOptionsBAAKeychainAccessGroup"
- "kMAOptionsBAAKeychainLabel"
- "kMAOptionsBAAOIDDeviceOSInformation"
- "kMAOptionsBAAOIDSToInclude"
- "kMAOptionsBAAOIDUCRTDeviceIdentifiers"
- "kMAOptionsBAAValidity"
- "returing %lu additional headers"
- "ucrt"
- "v32@?0@\"NSData\"8@\"NSData\"16@\"NSError\"24"
- "v32@?0@\"NSDictionary\"8@\"NSData\"16@\"NSError\"24"
- "v32@?0^{__SecKey=}8@\"NSArray\"16@\"NSError\"24"
```
