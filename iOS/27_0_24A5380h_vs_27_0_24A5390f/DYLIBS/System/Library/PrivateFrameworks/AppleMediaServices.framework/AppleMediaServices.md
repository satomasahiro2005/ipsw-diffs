## AppleMediaServices

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x81c848` | `0x81f38c` | **`+0x2b44`** |
| `__TEXT.__unwind_info` | `0x142c0` | `0x14730` | **`+0x470`** |
| `__AUTH_CONST.__objc_const` | `0x40300` | `0x406a0` | **`+0x3a0`** |
| `__TEXT.__oslogstring` | `0x34463` | `0x34709` | **`+0x2a6`** |
| `__TEXT.__objc_methlist` | `0x248dc` | `0x24b34` | **`+0x258`** |
| `__AUTH_CONST.__cfstring` | `0x23c20` | `0x23e20` | **`+0x200`** |
| `__AUTH_CONST.__const` | `0x31640` | `0x317f0` | **`+0x1b0`** |
| `__TEXT.__eh_frame` | `0x1a250` | `0x1a0d4` | **`-0x17c`** |
| `__TEXT.__cstring` | `0x2e878` | `0x2e9af` | **`+0x137`** |
| `__DATA_CONST.__objc_selrefs` | `0x10070` | `0x10178` | **`+0x108`** |
| `__DATA_CONST.__const` | `0xd3c0` | `0xd4b8` | **`+0xf8`** |
| `__AUTH.__objc_data` | `0xaa98` | `0xab20` | **`+0x88`** |
| `__DATA.__data` | `0x8354` | `0x83dc` | **`+0x88`** |
| `__TEXT.__swift5_capture` | `0x46b8` | `0x4644` | **`-0x74`** |
| `__TEXT.__gcc_except_tab` | `0x536c` | `0x53b0` | **`+0x44`** |
| `__TEXT.__swift5_reflstr` | `0x4993` | `0x4953` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x2710` | `0x2738` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x1a14` | `0x1a3c` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x7dcb` | `0x7df1` | **`+0x26`** |
| `__DATA_DIRTY.__data` | `0x2c08` | `0x2be8` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x1514` | `0x14f4` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x63f8` | `0x640c` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x1610` | `0x1620` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x62d0` | `0x62e0` | **`+0x10`** |
| `__TEXT.__const` | `0x5b048` | `0x5b058` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0xb04` | `0xaf4` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x918` | `0x90c` | **`-0xc`** |
| `__AUTH.__data` | `0x30a8` | `0x30b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1ac8` | `0x1ad0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x498` | `0x4a0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xd20` | `0xd28` | **`+0x8`** |
| `__DATA.__common` | `0xb68` | `0xb64` | **`-0x4`** |

### Other Changes

```diff

-10.0.50.0.0
+10.0.54.0.0

-  Functions: 31053
-  Symbols:   26348
-  CStrings:  9301
+  Functions: 31099
+  Symbols:   26428
+  CStrings:  9325
Symbols:
+ +[ACAccount(AppleMediaServices) _ams_storageForDomain:]
+ +[AMSBagNetworkTask _expirationDateForInterval:now:]
+ +[AMSBagNetworkTask _selectedStorefrontForResponseStorefront:queryItems:]
+ +[AMSBagNetworkTask _shouldRetryForStorefrontChangeWithRequestStorefront:responseStorefront:]
+ +[AMSBiometrics _nonKeyHeadersWithAccount:headerNames:state:signatureResult:]
+ +[AMSBiometrics _stateValueForHeaderNames:account:]
+ +[AMSBiometrics identitySource]
+ +[AMSBiometrics setIdentitySource:]
+ +[AMSCardEnrollment shouldSkipCardEnrollmentForWalletBiometricsCheck:walletBiometricsEnabled:]
+ +[AMSFinancePaymentSheetResponse _credentialAccountForPaymentAccount:]
+ +[AMSFinancePaymentSheetResponse _mergedStyleDictionaryFromOuter:inner:]
+ +[AMSKeychainOptions _attestationStyleForBiometricsEnabled:passcodeEnabled:]
+ +[AMSMediaTokenService _signingErrorFromResult:encodingError:]
+ +[AMSProcessInfo _bundleFactsForIdentifier:]
+ +[AMSProcessInfo _cacheBundleFacts:forIdentifier:]
+ +[AMSProcessInfo _cachedBundleFactsForIdentifier:]
+ +[AMSProcessInfo _computeCurrentProcessBundleFacts]
+ +[AMSProcessInfo _currentProcessBundleFacts]
+ +[AMSProcessInfo _launchServicesBundleFactsForIdentifier:]
+ +[AMSURLSession _shouldCancelInFlightTaskForError:]
+ +[NSHTTPCookie(AMSCookieExpiry) ams_isExpiredForCookieExpiry:asOf:]
+ -[ACAccount(AppleMediaServices) ams_didAcknowledgeBundleHolderPrivacyAcknowledgementOnDeviceInStorageDomain:]
+ -[ACAccount(AppleMediaServices) ams_setDidAcknowledgeBundleHolderPrivacyAcknowledgementOnDevice:inStorageDomain:]
+ -[ACAccount(AppleMediaServices) ams_setSimpleProfileIdentifiers:]
+ -[ACAccount(AppleMediaServices) ams_simpleProfileIdentifiers]
+ -[AMSBagNetworkTask _promiseResultForURLResult:error:queryItems:responseStorefront:account:]
+ -[AMSDialogRequest account]
+ -[AMSDialogRequest setAccount:]
+ -[AMSLiveBiometricIdentitySource identities]
+ -[AMSMediaTokenService invalidateMediaTokenPromise:]
+ -[AMSMediaTokenService invalidateMediaTokenPromise]
+ -[AMSMediaTokenService invalidatePATMediaTokenPromise]
+ -[AMSMediaTokenService setCachedMediaTokenPromise:patBasedToken:]
+ -[AMSPaymentSheetPerformanceMetrics pageUserInteractiveTime]
+ -[AMSPaymentSheetPerformanceMetrics setPageUserInteractiveTime:]
+ -[AMSProcessInfo _ensureAllPropertiesResolved]
+ -[AMSProcessInfo _equalityFieldsSnapshot]
+ -[AMSProcessInfo _resolveMappedPropertiesIfNeededLocked]
+ -[AMSProcessInfo _resolveRecordPropertiesIfNeededLocked]
+ -[AMSProcessInfoBundleFacts .cxx_destruct]
+ -[AMSProcessInfoBundleFacts bundleURL]
+ -[AMSProcessInfoBundleFacts bundleVersion]
+ -[AMSProcessInfoBundleFacts clientVersion]
+ -[AMSProcessInfoBundleFacts executableName]
+ -[AMSProcessInfoBundleFacts initWithBundleURL:executableName:localizedName:bundleVersion:clientVersion:]
+ -[AMSProcessInfoBundleFacts localizedName]
+ -[AMSURLTaskInfo buyParamsSnapshot]
+ -[AMSURLTaskInfo setBuyParamsSnapshot:]
+ GCC_except_table100
+ GCC_except_table108
+ GCC_except_table141
+ GCC_except_table148
+ GCC_except_table176
+ GCC_except_table62
+ GCC_except_table77
+ GCC_except_table83
+ GCC_except_table88
+ GCC_except_table90
+ GCC_except_table91
+ GCC_except_table94
+ GCC_except_table97
+ _AMSErrorUserInfoKeyFPDIStage
+ _AMSMetricsLoggingSubsystemMediaTokenService
+ _CFBundleCopyExecutableURL
+ _CFBundleGetIdentifier
+ _OBJC_CLASS_$_AMSByteCountRounding
+ _OBJC_CLASS_$_AMSLiveBiometricIdentitySource
+ _OBJC_CLASS_$_AMSProcessInfoBundleFacts
+ _OBJC_IVAR_$_AMSDialogRequest._account
+ _OBJC_IVAR_$_AMSPaymentSheetPerformanceMetrics._pageUserInteractiveTime
+ _OBJC_IVAR_$_AMSProcessInfo._mappedPropertiesResolved
+ _OBJC_IVAR_$_AMSProcessInfo._recordPropertiesResolved
+ _OBJC_IVAR_$_AMSProcessInfoBundleFacts._bundleURL
+ _OBJC_IVAR_$_AMSProcessInfoBundleFacts._bundleVersion
+ _OBJC_IVAR_$_AMSProcessInfoBundleFacts._clientVersion
+ _OBJC_IVAR_$_AMSProcessInfoBundleFacts._executableName
+ _OBJC_IVAR_$_AMSProcessInfoBundleFacts._localizedName
+ _OBJC_IVAR_$_AMSURLTaskInfo._buyParamsSnapshot
+ _OBJC_METACLASS_$_AMSByteCountRounding
+ _OBJC_METACLASS_$_AMSLiveBiometricIdentitySource
+ _OBJC_METACLASS_$_AMSProcessInfoBundleFacts
+ __CLASS_METHODS_AMSByteCountRounding
+ __DATA_AMSByteCountRounding
+ __INSTANCE_METHODS_AMSByteCountRounding
+ __METACLASS_DATA_AMSByteCountRounding
+ __OBJC_$_INSTANCE_METHODS_AMSLiveBiometricIdentitySource
+ __OBJC_$_INSTANCE_METHODS_AMSProcessInfoBundleFacts
+ __OBJC_$_INSTANCE_VARIABLES_AMSProcessInfoBundleFacts
+ __OBJC_$_PROP_LIST_AMSLiveBiometricIdentitySource
+ __OBJC_$_PROP_LIST_AMSProcessInfoBundleFacts
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AMSBiometricIdentitySource
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AMSBiometricIdentitySource
+ __OBJC_$_PROTOCOL_REFS_AMSBiometricIdentitySource
+ __OBJC_CLASS_PROTOCOLS_$_AMSLiveBiometricIdentitySource
+ __OBJC_CLASS_RO_$_AMSLiveBiometricIdentitySource
+ __OBJC_CLASS_RO_$_AMSProcessInfoBundleFacts
+ __OBJC_LABEL_PROTOCOL_$_AMSBiometricIdentitySource
+ __OBJC_METACLASS_RO_$_AMSLiveBiometricIdentitySource
+ __OBJC_METACLASS_RO_$_AMSProcessInfoBundleFacts
+ __OBJC_PROTOCOL_$_AMSBiometricIdentitySource
+ ___109-[ACAccount(AppleMediaServices) ams_didAcknowledgeBundleHolderPrivacyAcknowledgementOnDeviceInStorageDomain:]_block_invoke
+ ___44+[AMSProcessInfo _currentProcessBundleFacts]_block_invoke
+ ___50+[AMSProcessInfo _cacheBundleFacts:forIdentifier:]_block_invoke
+ ___50+[AMSProcessInfo _cachedBundleFactsForIdentifier:]_block_invoke
+ ___51-[AMSEngagementClientData _enumerateAppsWithBlock:]_block_invoke_2
+ ___52-[AMSMediaTokenService invalidateMediaTokenPromise:]_block_invoke
+ ___58+[AMSProcessInfo _launchServicesBundleFactsForIdentifier:]_block_invoke
+ ___58+[AMSProcessInfo _launchServicesBundleFactsForIdentifier:]_block_invoke_2
+ ___62+[AMSMediaTokenService _signingErrorFromResult:encodingError:]_block_invoke
+ ___67+[AMSBiometrics headersPromiseWithAccount:options:signatureResult:]_block_invoke_2
+ ___67+[AMSBiometrics headersPromiseWithAccount:options:signatureResult:]_block_invoke_3
+ ___67+[AMSBiometrics headersPromiseWithAccount:options:signatureResult:]_block_invoke_4
+ ___block_descriptor_40_e8_32bs_e47_v32?0"NSString"8"AMSEngagementAppData"16^B24ls32l8
+ ___block_descriptor_41_e8_32w_e43_v24?0"AMSAuthenticateResult"8"NSError"16lw32l8
+ ___block_descriptor_48_e8_32s40s_e21_v16?0"AMSLRUCache"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e40_"AMSPromise"16?0"AMSKeychainOptions"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e51_"AMSBinaryPromise"24?0"AMSOptional"8"NSError"16ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e60_"AMSPromise"24?0"AMSURLRequestEncoderResult"8"NSError"16ls32l8s40l8
+ ___block_descriptor_49_e8_32s40s_e31_v24?0"ACAccount"8"NSError"16ls32l8s40l8
+ ___block_descriptor_49_e8_32s40s_e44_v24?0"AMSAuthKitUpdateResult"8"NSError"16ls32l8s40l8
+ ___block_descriptor_57_e8_32s40s48s_e30_v16?0"AMSAuthKitUpdateTask"8ls32l8s40l8s48l8
+ ___block_descriptor_80_e8_32s40s48s56s64r_e15_v32?08Q16^B24lr64l8s32l8s40l8s48l8s56l8
+ ___block_descriptor_80_e8_32s40s48s56s64s_e35_"AMSPromise"16?0"AMSURLRequest"8ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_80_e8_32s40s48s56s64s_e46_"AMSPromise"24?0"AMSURLResult"8"NSError"16ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_89_e8_32s40s48s56s64s72s_e41_"AMSPromise"24?0"NSArray"8"NSError"16ls32l8s40l8s48l8s56l8s64l8s72l8
+ _flat unique So23AMSLocalAuthHeaderNames_p
+ _symbolic _____ 18AppleMediaServices20AssetsJetpackFetcherO
+ _symbolic ______p 18AppleMediaServices20LocalAuthHeaderNamesP
- +[ACAccount(AppleMediaServices) _ams_storage]
- +[AMSBiometrics _nonKeyHeadersWithAccount:headerNames:signatureResult:]
- +[AMSMetricsLoadURLEvent _roundTransferBytesToNearestTens:]
- +[AMSProcessInfo _cacheProcessInfo:]
- +[AMSProcessInfo _cachedProcessInfoForIdentifier:]
- +[AMSProcessInfo copyPropertiesFrom:to:]
- +[NSHTTPCookie(AMSCookieExpiry) ams_isExpiredCookieExpiresValue:asOfDate:]
- -[AMSMediaTokenService invalidatePATMediaToken]
- -[AMSMediaTokenService setCachedMediaToken:patBasedToken:]
- -[AMSProcessInfo _setComputedPropertiesForBundleIdentifier:]
- GCC_except_table107
- GCC_except_table138
- GCC_except_table173
- GCC_except_table40
- GCC_except_table89
- GCC_except_table92
- GCC_except_table98
- _OBJC_CLASS_$__TtC18AppleMediaServices20AssetsJetpackFetcher
- _OBJC_METACLASS_$__TtC18AppleMediaServices20AssetsJetpackFetcher
- __CLASS_METHODS__TtC18AppleMediaServices20AssetsJetpackFetcher
- __CLASS_PROPERTIES__TtC18AppleMediaServices20AssetsJetpackFetcher
- __DATA__TtC18AppleMediaServices20AssetsJetpackFetcher
- __IVARS__TtC18AppleMediaServices20AssetsJetpackFetcher
- __METACLASS_DATA__TtC18AppleMediaServices20AssetsJetpackFetcher
- __OBJC_$_INSTANCE_METHODS__TtC18AppleMediaServices20AssetsJetpackFetcher(AppleMediaServices)
- __OBJC_CLASS_PROTOCOLS_$__TtC18AppleMediaServices20AssetsJetpackFetcher(AppleMediaServices)
- ___35-[AMSMockNetworkProxy startLoading]_block_invoke_3
- ___36+[AMSProcessInfo _cacheProcessInfo:]_block_invoke
- ___42+[AMSProcessInfo _accessProcessInfoCache:]_block_invoke_2
- ___42+[AMSProcessInfo _accessProcessInfoCache:]_block_invoke_3
- ___50+[AMSProcessInfo _cachedProcessInfoForIdentifier:]_block_invoke
- ___54-[ACAccount(AppleMediaServices) ams_hasSimpleProfiles]_block_invoke
- ___60-[AMSProcessInfo _setComputedPropertiesForBundleIdentifier:]_block_invoke
- ___60-[AMSProcessInfo _setComputedPropertiesForBundleIdentifier:]_block_invoke_2
- ___67+[AMSBiometrics headersPromiseWithAccount:options:signatureResult:]_block_invoke
- ___67-[AMSMediaTokenService _tokenRequestPromiseWithPrivateAccessToken:]_block_invoke_3
- ___72-[AMSBagNetworkTask _performFetchWithAttemptedCount:account:storefront:]_block_invoke_4
- ___93-[ACAccount(AppleMediaServices) ams_didAcknowledgeBundleHolderPrivacyAcknowledgementOnDevice]_block_invoke
- ___block_descriptor_40_e8_32s_e21_v16?0"AMSLRUCache"8ls32l8
- ___block_descriptor_40_e8_32s_e60_"AMSPromise"24?0"AMSURLRequestEncoderResult"8"NSError"16ls32l8
- ___block_descriptor_40_e8_32w_e43_v24?0"AMSAuthenticateResult"8"NSError"16lw32l8
- ___block_descriptor_48_e8_32s40s_e44_v24?0"AMSAuthKitUpdateResult"8"NSError"16ls32l8s40l8
- ___block_descriptor_56_e8_32s40s48s_e30_v16?0"AMSAuthKitUpdateTask"8ls32l8s40l8s48l8
- ___block_descriptor_72_e8_32s40s48s56r_e15_v32?08Q16^B24lr56l8s32l8s40l8s48l8
- ___block_descriptor_72_e8_32s40s48s56s_e34_"AMSPromise"16?0"AMSURLResult"8ls32l8s40l8s48l8s56l8
- ___block_descriptor_88_e8_32s40s48s56s64s72s_e41_"AMSPromise"24?0"NSArray"8"NSError"16ls32l8s40l8s48l8s56l8s64l8s72l8
- _kCFBundleIdentifierKey
- _symbolic _____ 18AppleMediaServices20AssetsJetpackFetcherC
CStrings:
+ " | selectedProfile = %@"
+ "!\xa1"
+ "%{public}@: Could not find network override for %{public}@"
+ "%{public}@: Failed to invalidate PAT media token. Error: %{public}@"
+ "%{public}@: [%{public}@] Failed to invalidate media token. Error: %{public}@"
+ "%{public}@: [%{public}@] Failed to read cached media token for invalidation. Error: %{public}@"
+ "%{public}@: [%{public}@] Silent-enrollment payment session failed. error: %{public}@"
+ "%{public}@Account flags decryption failed in daemon. Treating as stale key and triggering repair. error = %{public}@"
+ "%{public}@Account flags decryption failed locally. Falling back to XPC. error = %{public}@"
+ "%{public}@Failed to add FPDI signing headers. stage = %{public}@, error = %{public}@"
+ "%{public}@Storing password onto a Simple Profile. This is likely a bug. account = %{public}@ | password = %{public}@"
+ "%{public}@Successfully retrieved account flags via XPC fallback after crypto error."
+ "@\"AMSBinaryPromise\"24@?0@\"AMSOptional\"8@\"NSError\"16"
+ "@\"AMSPromise\"16@?0@\"AMSKeychainOptions\"8"
+ "AMSError-%@"
+ "AMSFPDIStage"
+ "AMSMockNetworkProxy: no override for %@"
+ "AssetsJetpackFetcher:"
+ "AssetsJetpackFetcher: ["
+ "MediaTokenService"
+ "MissingSignature"
+ "PAT"
+ "Payment services merchant URL was nil"
+ "Unexpected status code: "
+ "amsErrorCode"
+ "fpdiRetryCount"
+ "fpdiStage"
+ "fpdiStatus"
+ "httpMethod"
+ "kAccountIdentifier"
+ "kCodingKeyAccountIdentifier"
+ "pageUserInteractiveTime"
+ "profileIdentifiers"
+ "requestHost"
+ "requestPathHash"
- " | selected = %@"
- "!\x91"
- "%{public}@: [%{public}@] Account flags decryption failed with crypto error (possible stale key). Deleting property. error = %{public}@"
- "%{public}@Failed to add FPDI signing headers. error = %{public}@"
- "Failed download with error: "
- "Failed to fetch and cache assets Jetpack with error = "
- "Fetching Jetpack..."
- "Jetpack successfully fetched and written to "
- "Maximum number of attempts exceeded."
- "SigningHeaders"
- "com.apple.AMSProcessInfo"
```
