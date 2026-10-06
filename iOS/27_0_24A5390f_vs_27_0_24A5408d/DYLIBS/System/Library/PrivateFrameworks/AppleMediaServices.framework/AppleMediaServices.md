## AppleMediaServices

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x81f38c` | `0x81b8e0` | **`-0x3aac`** |
| `__TEXT.__eh_frame` | `0x1a0d4` | `0x19d7c` | **`-0x358`** |
| `__DATA.__bss` | `0x20050` | `0x1fe50` | **`-0x200`** |
| `__TEXT.__delay_helper` | `0x134` | `—` | **`-0x134`** |
| `__AUTH_CONST.__const` | `0x317f0` | `0x316e0` | **`-0x110`** |
| `__TEXT.__objc_methlist` | `0x24b34` | `0x24c3c` | **`+0x108`** |
| `__TEXT.__const` | `0x5b058` | `0x5af58` | **`-0x100`** |
| `__AUTH.__data` | `0x30b0` | `0x2fc8` | **`-0xe8`** |
| `__TEXT.__cstring` | `0x2e9af` | `0x2e8c8` | **`-0xe7`** |
| `__TEXT.__swift5_typeref` | `0x7df1` | `0x7d1d` | **`-0xd4`** |
| `__AUTH_CONST.__auth_got` | `0x2738` | `0x2668` | **`-0xd0`** |
| `__DATA_CONST.__objc_selrefs` | `0x10178` | `0x10240` | **`+0xc8`** |
| `__TEXT.__oslogstring` | `0x34709` | `0x347b7` | **`+0xae`** |
| `__TEXT.__lazy_helpers` | `0x4028` | `0x3f80` | **`-0xa8`** |
| `__TEXT.__swift5_fieldmd` | `0x621c` | `0x6188` | **`-0x94`** |
| `__AUTH.__objc_data` | `0xab20` | `0xab98` | **`+0x78`** |
| `__TEXT.__constg_swiftt` | `0x640c` | `0x639c` | **`-0x70`** |
| `__TEXT.__swift5_assocty` | `0x10f8` | `0x1158` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x4644` | `0x45f0` | **`-0x54`** |
| `__TEXT.__unwind_info` | `0x14730` | `0x146e0` | **`-0x50`** |
| `__DATA_CONST.__got` | `0x1ad0` | `0x1a88` | **`-0x48`** |
| `__AUTH_CONST.__cfstring` | `0x23e20` | `0x23e60` | **`+0x40`** |
| `__TEXT.__delay_stubs` | `0x40` | `—` | **`-0x40`** |
| `__AUTH_CONST.__objc_const` | `0x406a0` | `0x406d8` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x4953` | `0x4923` | **`-0x30`** |
| `__DATA.__data` | `0x83dc` | `0x83b4` | **`-0x28`** |
| `__TEXT.__swift_as_cont` | `0x14f4` | `0x14cc` | **`-0x28`** |
| `__DATA_CONST.__const` | `0xd4b8` | `0xd4d8` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0xaf4` | `0xae0` | **`-0x14`** |
| `__AUTH_CONST.__lazy_load_got` | `0x5f8` | `0x5e8` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x62e0` | `0x62f0` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x1414` | `0x1404` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x90c` | `0x8fc` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x2be8` | `0x2be0` | **`-0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x5658` | `0x5660` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x53b0` | `0x53b8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1a3c` | `0x1a40` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x784` | `0x780` | **`-0x4`** |

### Other Changes

```diff

-10.0.54.0.0
+10.0.60.2.2

-  - /System/Library/Frameworks/Vision.framework/Vision
-  - /System/Library/Frameworks/_Vision_FoundationModels.framework/_Vision_FoundationModels

-  - /usr/lib/swift/libswiftAVFoundation.dylib

-  - /usr/lib/swift/libswiftCompression.dylib

-  - /usr/lib/swift/libswiftCoreAudio.dylib

-  - /usr/lib/swift/libswiftMLCompute.dylib

-  Functions: 31099
-  Symbols:   26428
-  CStrings:  9325
+  Functions: 31050
+  Symbols:   26412
+  CStrings:  9320
Symbols:
+ +[AMSBiometrics _nonKeyHeadersWithAccount:descriptor:state:signatureResult:]
+ +[AMSBiometrics _publicKeyHeadersWithAccount:descriptor:options:signatureResult:]
+ +[AMSDefaults metricsInternalLegacyRoutingPercentage]
+ +[AMSDefaults saveSelfieDiagnostics]
+ +[AMSDefaults setMetricsInternalLegacyRoutingPercentage:]
+ +[AMSDefaults setSaveSelfieDiagnostics:]
+ +[AMSProcessInfo attributionBundleIdentifierForProxyAppBundleID:hasImpersonateEntitlement:]
+ +[AMSProcessInfo hasNetworkImpersonationEntitlement]
+ +[AMSURLSession _defaultConfiguration]
+ +[AMSURLSession sessionForAttributedBundleIdentifier:]
+ -[AMSBagNetworkTask _bagURLSession]
+ -[AMSEngagementRequest setShouldRunCampaignAttribution:]
+ -[AMSEngagementRequest shouldRunCampaignAttribution]
+ -[AMSProcessInfo networkAttributionBundleIdentifier]
+ -[NSMutableURLRequest(AppleMediaServices) _ams_removeIdentifierCookies:forAccounts:]
+ -[NSMutableURLRequest(AppleMediaServices) ams_addCookiesAsynchronouslyForAccount:clientInfo:bag:cleanupGlobalCookies:excludeAccountIdentifierCookies:]
+ -[NSMutableURLRequest(AppleMediaServices) ams_addCookiesForAccount:clientInfo:bag:cleanupGlobalCookies:excludeAccountIdentifierCookies:]
+ -[NSURLSessionConfiguration(AppleMediaServices_Project) ams_attributeNetworkingToBundleIdentifier:]
+ GCC_except_table110
+ GCC_except_table63
+ GCC_except_table92
+ _OBJC_CLASS_$_AMSLocalAuthHeaderDescriptor
+ _OBJC_CLASS_$_RBSAcquisitionCompletionAttribute
+ _OBJC_IVAR_$_AMSEngagementRequest._shouldRunCampaignAttribution
+ _OBJC_METACLASS_$_AMSLocalAuthHeaderDescriptor
+ __DATA_AMSLocalAuthHeaderDescriptor
+ __INSTANCE_METHODS_AMSLocalAuthHeaderDescriptor
+ __IVARS_AMSLocalAuthHeaderDescriptor
+ __METACLASS_DATA_AMSLocalAuthHeaderDescriptor
+ __OBJC_$_CATEGORY_NSDate_$_AppleMediaServices
+ __OBJC_$_CATEGORY_NSHTTPCookie_$_AppleMediaServices
+ __OBJC_$_CLASS_METHODS_NSDate(AppleMediaServices|AMSFormattingUtilities)
+ __OBJC_$_CLASS_METHODS_NSHTTPCookie(AppleMediaServices|AMSCookieProperties|NSSecureCoding_Temporary|AMSCookieExpiry)
+ __OBJC_$_CLASS_METHODS_NSString(AppleMediaServices|AppleMediaServices|AMSFormattingUtilities)
+ __OBJC_$_INSTANCE_METHODS_NSDate(AppleMediaServices|AMSFormattingUtilities)
+ __OBJC_$_INSTANCE_METHODS_NSHTTPCookie(AppleMediaServices|AMSCookieProperties|NSSecureCoding_Temporary|AMSCookieExpiry)
+ __OBJC_$_INSTANCE_METHODS_NSString(AppleMediaServices|AppleMediaServices|AMSFormattingUtilities)
+ __OBJC_$_PROP_LIST_NSHTTPCookie_$_AppleMediaServices
+ __OBJC_CLASS_PROTOCOLS_$_NSHTTPCookie(AppleMediaServices|AMSCookieProperties|NSSecureCoding_Temporary|AMSCookieExpiry)
+ __PROPERTIES_AMSLocalAuthHeaderDescriptor
+ ___150-[NSMutableURLRequest(AppleMediaServices) ams_addCookiesAsynchronouslyForAccount:clientInfo:bag:cleanupGlobalCookies:excludeAccountIdentifierCookies:]_block_invoke
+ ___150-[NSMutableURLRequest(AppleMediaServices) ams_addCookiesAsynchronouslyForAccount:clientInfo:bag:cleanupGlobalCookies:excludeAccountIdentifierCookies:]_block_invoke_2
+ ___block_descriptor_49_e8_32s40s_e41_"AMSPromise"24?0"NSArray"8"NSError"16ls32l8s40l8
+ ___block_descriptor_58_e8_32s40s_e29_"AMSPromise"16?0"NSArray"8ls32l8s40l8
+ ___block_descriptor_72_e8_32s40s48s56s_e32_"AMSPromise"24?08"NSError"16ls32l8s40l8s48l8s56l8
+ _associated conformance 18AppleMediaServices21LocalAuthHeaderFieldsVs10SetAlgebraAASQ
+ _associated conformance 18AppleMediaServices21LocalAuthHeaderFieldsVs10SetAlgebraAAs25ExpressibleByArrayLiteral
+ _associated conformance 18AppleMediaServices21LocalAuthHeaderFieldsVs9OptionSetAASY
+ _associated conformance 18AppleMediaServices21LocalAuthHeaderFieldsVs9OptionSetAAs0I7Algebra
+ _symbolic _____ 18AppleMediaServices21LocalAuthHeaderFieldsV
+ _symbolic _____ 18AppleMediaServices25LocalAuthHeaderDescriptorC
+ _symbolic _____XMT 18AppleMediaServices28BagUnderlyingDataPersistenceC
+ _symbolic y_____Kc 10Foundation3URLV
+ _type_layout_string 18AppleMediaServices21LocalAuthHeaderFieldsV
+ _type_layout_string So7CGPointV
- +[AMSBiometrics _nonKeyHeadersWithAccount:headerNames:state:signatureResult:]
- -[NSDictionary(AMSAccount) ams_firstName]
- -[NSDictionary(AMSAccount) ams_lastName]
- -[NSMutableURLRequest(AppleMediaServices) ams_addCookiesAsynchronouslyForAccount:clientInfo:bag:cleanupGlobalCookies:]
- -[NSMutableURLRequest(AppleMediaServices) ams_addCookiesForAccount:clientInfo:bag:cleanupGlobalCookies:]
- GCC_except_table108
- GCC_except_table62
- GCC_except_table77
- GCC_except_table90
- _CVPixelBufferGetHeight
- _CVPixelBufferGetHeight$lazyAuthGOT_IA_ad_0
- _CVPixelBufferGetHeight$lazyLoadStub
- _CVPixelBufferGetWidth
- _CVPixelBufferGetWidth$lazyAuthGOT_IA_ad_0
- _CVPixelBufferGetWidth$lazyLoadStub
- __DATA__TtC18AppleMediaServices18SelfieAgeEstimator
- __IVARS__TtC18AppleMediaServices18SelfieAgeEstimator
- __METACLASS_DATA__TtC18AppleMediaServices18SelfieAgeEstimator
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSDate_$_AMSFormattingUtilities
- __OBJC_$_CATEGORY_NSDate_$_AMSFormattingUtilities
- __OBJC_$_CATEGORY_NSHTTPCookie_$_AMSCookieExpiry
- __OBJC_$_CLASS_METHODS_NSDate(AMSFormattingUtilities|AppleMediaServices)
- __OBJC_$_CLASS_METHODS_NSHTTPCookie(AMSCookieExpiry|AppleMediaServices|AMSCookieProperties|NSSecureCoding_Temporary)
- __OBJC_$_CLASS_METHODS_NSString(AppleMediaServices|AMSFormattingUtilities|AppleMediaServices)
- __OBJC_$_INSTANCE_METHODS_NSHTTPCookie(AMSCookieExpiry|AppleMediaServices|AMSCookieProperties|NSSecureCoding_Temporary)
- __OBJC_$_INSTANCE_METHODS_NSString(AppleMediaServices|AMSFormattingUtilities|AppleMediaServices)
- __OBJC_$_PROP_LIST_NSDate_$_AMSFormattingUtilities
- __OBJC_CLASS_PROTOCOLS_$_NSHTTPCookie(AMSCookieExpiry|AppleMediaServices|AMSCookieProperties|NSSecureCoding_Temporary)
- ___118-[NSMutableURLRequest(AppleMediaServices) ams_addCookiesAsynchronouslyForAccount:clientInfo:bag:cleanupGlobalCookies:]_block_invoke
- ___118-[NSMutableURLRequest(AppleMediaServices) ams_addCookiesAsynchronouslyForAccount:clientInfo:bag:cleanupGlobalCookies:]_block_invoke_2
- ___block_descriptor_57_e8_32s40s_e29_"AMSPromise"16?0"NSArray"8ls32l8s40l8
- ___block_descriptor_64_e8_32s40s48s_e32_"AMSPromise"24?08"NSError"16ls32l8s40l8s48l8
- ___swift_memcpy16_4
- __swift_FORCE_LOAD_$_swiftAVFoundation
- __swift_FORCE_LOAD_$_swiftAVFoundation_$_AppleMediaServices
- __swift_FORCE_LOAD_$_swiftCompression
- __swift_FORCE_LOAD_$_swiftCompression_$_AppleMediaServices
- __swift_FORCE_LOAD_$_swiftCoreAudio
- __swift_FORCE_LOAD_$_swiftCoreAudio_$_AppleMediaServices
- __swift_FORCE_LOAD_$_swiftMLCompute
- __swift_FORCE_LOAD_$_swiftMLCompute_$_AppleMediaServices
- _associated conformance 18AppleMediaServices18SelfieAgeEstimatorC6ResultV10CodingKeys33_2BC3853D28E32BF2A0E39959D4E29788LLOSHAASQ
- _associated conformance 18AppleMediaServices18SelfieAgeEstimatorC6ResultV10CodingKeys33_2BC3853D28E32BF2A0E39959D4E29788LLOs0H3KeyAAs23CustomStringConvertible
- _associated conformance 18AppleMediaServices18SelfieAgeEstimatorC6ResultV10CodingKeys33_2BC3853D28E32BF2A0E39959D4E29788LLOs0H3KeyAAs28CustomDebugStringConvertible
- _dlopenHelper$_Vision_FoundationModels
- _dlopenHelperFlag$_Vision_FoundationModels
- _lazyLoadFlag$CoreVideo
- _swift_getOpaqueTypeConformance2
- _symbolic Say______pG 6Vision0A7RequestP
- _symbolic ScTyyt_____GSg s5NeverO
- _symbolic So6AMSBagC
- _symbolic _____ 18AppleMediaServices18SelfieAgeEstimatorC
- _symbolic _____ 18AppleMediaServices18SelfieAgeEstimatorC6ResultV
- _symbolic _____ 18AppleMediaServices18SelfieAgeEstimatorC6ResultV10CodingKeys33_2BC3853D28E32BF2A0E39959D4E29788LLO
- _symbolic _____ 6Vision24EstimatePersonAgeRequestC
- _symbolic _____ 6Vision7SessionC
- _symbolic _____IeyBy_ 10ObjectiveC8ObjCBoolV
- _symbolic _____Sg 18AppleMediaServices17SelfieDiagnosticsC
- _symbolic _____Sg 6Vision0A6ResultO
- _symbolic _____Sg 6Vision15FaceObservationV
- _symbolic _____Sg 6Vision15FaceObservationV0B15LivelinessScoreV
- _symbolic _____Sg 6Vision15FaceObservationV13AgeEstimationV
- _symbolic _____Sg 6Vision27DetectFaceRectanglesRequestV8RevisionO
- _symbolic ___________t 6Vision24EstimatePersonAgeRequestC AA15FaceObservationV
- _symbolic _____y_Say______pGQo_ 6Vision19ImageRequestHandlerC10performAllyQrxSlRzAA0aC0_p7ElementRtzlFQO AaEP
- _symbolic _____y_Say______pGQo_13AsyncIteratorSciQx 6Vision19ImageRequestHandlerC10performAllyQrxSlRzAA0aC0_p7ElementRtzlFQO AaEP
- _symbolic _____y_____G s22KeyedDecodingContainerV 18AppleMediaServices18SelfieAgeEstimatorC6ResultV10CodingKeys33_2BC3853D28E32BF2A0E39959D4E29788LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 18AppleMediaServices18SelfieAgeEstimatorC6ResultV10CodingKeys33_2BC3853D28E32BF2A0E39959D4E29788LLO
- _symbolic _____y______pG s23_ContiguousArrayStorageC 6Vision0D7RequestP
- _type_layout_string 18AppleMediaServices18SelfieAgeEstimatorC6ResultV
- _type_layout_string So6CGSizeV
CStrings:
+ "%{public}@Excluding account-identifier cookie from request. cookie-name = %{public}@"
+ "%{public}@Passcode availability check failed (%{public}@); loading configuration anyway."
+ "AMSMetricsInternalLegacyRoutingPercentage"
+ "AMSSaveSelfieDiagnostics"
+ "AppleMediaServices.LocalAuthHeaderDescriptor"
+ "Failed to exclude persisted bags directory from backup. error = "
+ "Passcode Purchase not available: Bag was nil"
+ "Passcode Purchase not available: Passcode key missing"
+ "Passcode Purchase not available: Passcode must be reset"
+ "com.apple.private.nsurlsession.impersonate"
+ "shouldRunCampaignAttribution"
- " liveliness confidence: "
- ", age confidence: "
- "/System/Library/Frameworks/_Vision_FoundationModels.framework/_Vision_FoundationModels"
- "Could not generate age estimate"
- "Could not generate liveliness score"
- "Failed to estimate age. Error: "
- "Initializing Selfie Age Estimator with PCC: "
- "Overriding age confidence estimate with: "
- "Overriding age estimate with: "
- "Overriding liveliness confidence estimate with: "
- "Processed frame for age estimation."
- "Received observation of unknown type"
- "SelfieAgeEstimator:"
- "SelfieAgeEstimator: ["
- "accountInfo.address.firstName"
- "accountInfo.address.lastName"
```
