## AppleMediaServices

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x813518` | `0x81c848` | **`+0x9330`** |
| `__TEXT.__oslogstring` | `0x3390d` | `0x34463` | **`+0xb56`** |
| `__TEXT.__cstring` | `0x2e231` | `0x2e878` | **`+0x647`** |
| `__DATA.__bss` | `0x1fbc0` | `0x20050` | **`+0x490`** |
| `__AUTH_CONST.__objc_const` | `0x3fed8` | `0x40300` | **`+0x428`** |
| `__AUTH.__objc_data` | `0xa750` | `0xaa98` | **`+0x348`** |
| `__AUTH_CONST.__const` | `0x31340` | `0x31640` | **`+0x300`** |
| `__TEXT.__objc_methlist` | `0x245e4` | `0x248dc` | **`+0x2f8`** |
| `__TEXT.__eh_frame` | `0x19f80` | `0x1a250` | **`+0x2d0`** |
| `__DATA_DIRTY.__data` | `0x2948` | `0x2c08` | **`+0x2c0`** |
| `__DATA_DIRTY.__objc_data` | `0x5900` | `0x5658` | **`-0x2a8`** |
| `__AUTH_CONST.__cfstring` | `0x23980` | `0x23c20` | **`+0x2a0`** |
| `__DATA_CONST.__objc_selrefs` | `0xfe60` | `0x10070` | **`+0x210`** |
| `__TEXT.__gcc_except_tab` | `0x5188` | `0x536c` | **`+0x1e4`** |
| `__DATA_CONST.__const` | `0xd1f8` | `0xd3c0` | **`+0x1c8`** |
| `__TEXT.__unwind_info` | `0x14488` | `0x142c0` | **`-0x1c8`** |
| `__TEXT.__const` | `0x5ae98` | `0x5b048` | **`+0x1b0`** |
| `__AUTH.__data` | `0x3208` | `0x30a8` | **`-0x160`** |
| `__DATA.__data` | `0x8428` | `0x8354` | **`-0xd4`** |
| `__TEXT.__dlopen_cstrs` | `0x8e2` | `0x990` | **`+0xae`** |
| `__TEXT.__swift5_capture` | `0x4628` | `0x46b8` | **`+0x90`** |
| `__DATA_CONST.__got` | `0x1a40` | `0x1ac8` | **`+0x88`** |
| `__TEXT.__swift5_fieldmd` | `0x619c` | `0x621c` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x63b0` | `0x63f8` | **`+0x48`** |
| `__DATA_DIRTY.__bss` | `0x6310` | `0x62d0` | **`-0x40`** |
| `__TEXT.__swift5_reflstr` | `0x4953` | `0x4993` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x7d93` | `0x7dcb` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0x1548` | `0x1514` | **`-0x34`** |
| `__TEXT.__swift5_proto` | `0x13f4` | `0x1414` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0xae4` | `0xb04` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x8fc` | `0x918` | **`+0x1c`** |
| `__AUTH_CONST.__objc_intobj` | `0xcd8` | `0xcf0` | **`+0x18`** |
| `__DATA_DIRTY.__objc_ivar` | `0x6f8` | `0x710` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1a00` | `0x1a14` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x2700` | `0x2710` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1600` | `0x1610` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0xd10` | `0xd20` | **`+0x10`** |
| `__DATA.__common` | `0xb70` | `0xb68` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x90` | `0x98` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x77c` | `0x784` | **`+0x8`** |

### Other Changes

```diff

-10.0.45.0.0
+10.0.50.0.0

-  Functions: 30886
-  Symbols:   26218
-  CStrings:  9224
+  Functions: 31053
+  Symbols:   26348
+  CStrings:  9301
Symbols:
+ +[AMSBiometrics shouldRemoveBOPHeadersForAccount:]
+ +[AMSDefaults manualCaptureOverride]
+ +[AMSDefaults setManualCaptureOverride:]
+ +[AMSIDCardTask _dataFromIDCardForMinimumAge:nonce:allowedDocuments:]
+ +[AMSIDCardTask _descriptorForMinimumAge:allowedDocuments:]
+ +[AMSIDCardTask _documentTypeAllowed:allowedDocuments:]
+ +[AMSIDCardTask _hasEligibleDocumentForMinimumAge:nonce:allowedDocuments:]
+ +[AMSIDCardTask _identityController]
+ +[AMSIDCardTask _identityRequestWithDescriptor:nonce:]
+ +[AMSIDCardTask _nonceFromString:]
+ +[AMSOpenURL openSensitiveURL:]
+ +[AMSPromiseResult diagnoseResult:error:]
+ +[AMSPromiseResult(Routing) fallbackError]
+ +[AMSPushHandler accountIsEligibleForPushNotifications:accountStore:bag:]
+ +[AMSSecureThreeDomainInterruptionResult _stringForStatus:]
+ +[NSDate(AMSFormattingUtilities) ams_dateFromIMFFixDateString:]
+ +[NSDate(AMSFormattingUtilities) ams_dateFromISO8601String:]
+ +[NSDate(AMSFormattingUtilities) ams_dateFromLocalTimeZoneString:]
+ +[NSHTTPCookie(AMSCookieExpiry) ams_countOfExpiredCookieProperties:asOfDate:]
+ +[NSHTTPCookie(AMSCookieExpiry) ams_isExpiredCookieExpiresValue:asOfDate:]
+ -[AMSAccountCachedServerData repairAccountFlagsForAccountID:completionHandler:]
+ -[AMSBagNetworkDataSource _invalidateData]
+ -[AMSBagNetworkDataSource _itfeUpdateNotification]
+ -[AMSBagNetworkDataSource itfeNotificationObserver]
+ -[AMSBagNetworkDataSource setItfeNotificationObserver:]
+ -[AMSBiometricsTokenUpdateTask setShouldUpdateDeviceState:]
+ -[AMSBiometricsTokenUpdateTask shouldUpdateDeviceState]
+ -[AMSIDCardTask .cxx_destruct]
+ -[AMSIDCardTask _performHasEligibleDocumentInDaemon]
+ -[AMSIDCardTask _performTaskInDaemon]
+ -[AMSIDCardTask allowedDocuments]
+ -[AMSIDCardTask hasEligibleDocument]
+ -[AMSIDCardTask initWithMinAge:nonce:allowedDocuments:]
+ -[AMSIDCardTask minAge]
+ -[AMSIDCardTask nonce]
+ -[AMSIDCardTask perform]
+ -[AMSIDCardTask setAllowedDocuments:]
+ -[AMSIDCardTask setMinAge:]
+ -[AMSIDCardTask setNonce:]
+ -[AMSMarketingItemTaskURLBuilder _countryCodePromiseFromBag:]
+ -[AMSMarketingItemTaskURLBuilder _formattedURLPathWithURLPath:countryCode:]
+ -[AMSMarketingItemTaskURLBuilder _languageTagPromiseFromBag:fallback:]
+ -[AMSMarketingItemTaskURLBuilder _realmOverridesPromiseFromBag:]
+ -[AMSMarketingItemTaskURLBuilder _stringPromiseForKey:fromBag:]
+ -[AMSMarketingItemTaskURLBuilder _urlPathPromiseFromBag:]
+ -[AMSMarketingItemTaskURLBuilder _urlWithServiceType:placement:hydrateRelatedContents:offerHints:additionalParameters:urlPath:countryCode:languageTag:realmOverrides:]
+ -[AMSProcessInfo bundleVersion]
+ -[AMSPromiseResult snapshotResult:error:]
+ -[AMSPromiseResult(Routing) getResult:error:]
+ -[AMSPromiseResult(Routing) immutableResult]
+ -[AMSScreenTimeSettingsTask .cxx_destruct]
+ -[AMSScreenTimeSettingsTask _performTaskInDaemon]
+ -[AMSScreenTimeSettingsTask _performTaskInProcess]
+ -[AMSScreenTimeSettingsTask communicationSafetyState]
+ -[AMSScreenTimeSettingsTask initWithCommunicationSafetyState:webContentFilterState:]
+ -[AMSScreenTimeSettingsTask perform]
+ -[AMSScreenTimeSettingsTask setCommunicationSafetyState:]
+ -[AMSScreenTimeSettingsTask setWebContentFilterState:]
+ -[AMSScreenTimeSettingsTask webContentFilterState]
+ -[AMSSecureThreeDomainInterruptionResult _decodePayload]
+ -[AMSSecureThreeDomainInterruptionResult reasonMessage]
+ -[AMSSecureThreeDomainInterruptionResult secure3dSessionId]
+ -[AMSSecureThreeDomainInterruptionResult status]
+ -[AMSURLAction(Bridging) ams_setUpdatedBody:]
+ -[AMSURLTaskInfo(Bridging) ams_originalRequestHTTPBody]
+ -[NSDate(AMSFormattingUtilities) ams_formattedRepresentationWithTimeFunction:bufferSize:format:useColonInTZOffset:useFractionalSeconds:]
+ -[NSDate(AMSFormattingUtilities) ams_imfFixDateRepresentation]
+ -[NSDate(AMSFormattingUtilities) ams_iso8601LocalRepresentationWithTimeZoneFormatPreference:useFractionalSeconds:useZForUTC:]
+ -[NSDate(AMSFormattingUtilities) ams_iso8601LocalRepresentation]
+ -[NSDate(AMSFormattingUtilities) ams_iso8601UTCRepresentationWithTimeZoneFormatPreference:]
+ -[NSDate(AMSFormattingUtilities) ams_iso8601UTCRepresentation]
+ -[NSDate(AMSFormattingUtilities) ams_localTimeZoneStringRepresentation]
+ -[NSString(AMSFormattingUtilities) ams_doubleNumberValue]
+ -[NSString(AMSFormattingUtilities) ams_longLongNumberValue]
+ GCC_except_table40
+ GCC_except_table80
+ GCC_except_table82
+ _AMSBagKeyPushNotificationsShouldRegisterForManagedAccounts
+ _AMSDeviceOfferFollowUpDescription
+ _AMSHumanReadableDescriptionForPaymentSheetCancellationType
+ _AMSLocalAuthTokenUpdateOptionKeyShouldPerformPreflightAuthentication
+ _AMSLocalAuthTokenUpdateOptionKeyShouldUpdateDeviceState
+ _OBJC_CLASS_$_AMSIDCardTask
+ _OBJC_CLASS_$_AMSScreenTimeSettingsTask
+ _OBJC_IVAR_$_AMSBagNetworkDataSource._itfeNotificationObserver
+ _OBJC_IVAR_$_AMSProcessInfo._bundleVersion
+ _OBJC_IVAR_$_AMSSecureThreeDomainInterruptionResult._reasonMessage
+ _OBJC_IVAR_$_AMSSecureThreeDomainInterruptionResult._secure3dSessionId
+ _OBJC_IVAR_$_AMSSecureThreeDomainInterruptionResult._status
+ _OBJC_METACLASS_$_AMSIDCardTask
+ _OBJC_METACLASS_$_AMSScreenTimeSettingsTask
+ _OUTLINED_FUNCTION_259
+ __DefaultRuneLocale
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSDate_$_AMSFormattingUtilities
+ __OBJC_$_CATEGORY_NSDate_$_AMSFormattingUtilities
+ __OBJC_$_CATEGORY_NSHTTPCookie_$_AMSCookieExpiry
+ __OBJC_$_CLASS_METHODS_AMSIDCardTask
+ __OBJC_$_CLASS_METHODS_AMSPromiseResult(Routing)
+ __OBJC_$_CLASS_METHODS_AMSSecureThreeDomainInterruptionResult
+ __OBJC_$_CLASS_METHODS_NSDate(AMSFormattingUtilities|AppleMediaServices)
+ __OBJC_$_CLASS_METHODS_NSHTTPCookie(AMSCookieExpiry|AppleMediaServices|AMSCookieProperties|NSSecureCoding_Temporary)
+ __OBJC_$_CLASS_METHODS_NSString(AppleMediaServices|AMSFormattingUtilities|AppleMediaServices)
+ __OBJC_$_INSTANCE_METHODS_AMSIDCardTask
+ __OBJC_$_INSTANCE_METHODS_AMSPromiseResult(Routing)
+ __OBJC_$_INSTANCE_METHODS_AMSScreenTimeSettingsTask
+ __OBJC_$_INSTANCE_METHODS_AMSURLAction(Bridging)
+ __OBJC_$_INSTANCE_METHODS_AMSURLTaskInfo(Bridging)
+ __OBJC_$_INSTANCE_METHODS_NSHTTPCookie(AMSCookieExpiry|AppleMediaServices|AMSCookieProperties|NSSecureCoding_Temporary)
+ __OBJC_$_INSTANCE_METHODS_NSString(AppleMediaServices|AMSFormattingUtilities|AppleMediaServices)
+ __OBJC_$_INSTANCE_VARIABLES_AMSIDCardTask
+ __OBJC_$_INSTANCE_VARIABLES_AMSScreenTimeSettingsTask
+ __OBJC_$_PROP_LIST_AMSIDCardTask
+ __OBJC_$_PROP_LIST_AMSScreenTimeSettingsTask
+ __OBJC_$_PROP_LIST_NSDate_$_AMSFormattingUtilities
+ __OBJC_CLASS_PROTOCOLS_$_NSHTTPCookie(AMSCookieExpiry|AppleMediaServices|AMSCookieProperties|NSSecureCoding_Temporary)
+ __OBJC_CLASS_RO_$_AMSIDCardTask
+ __OBJC_CLASS_RO_$_AMSScreenTimeSettingsTask
+ __OBJC_METACLASS_RO_$_AMSIDCardTask
+ __OBJC_METACLASS_RO_$_AMSScreenTimeSettingsTask
+ ___101-[AMSBagNetworkDataSource initWithProfile:profileVersion:processInfo:accountProvider:loadURLOverlay:]_block_invoke_3
+ ___101-[AMSBagNetworkDataSource initWithProfile:profileVersion:processInfo:accountProvider:loadURLOverlay:]_block_invoke_4
+ ___166-[AMSMarketingItemTaskURLBuilder _urlWithServiceType:placement:hydrateRelatedContents:offerHints:additionalParameters:urlPath:countryCode:languageTag:realmOverrides:]_block_invoke
+ ___24-[AMSIDCardTask perform]_block_invoke
+ ___24-[AMSIDCardTask perform]_block_invoke_2
+ ___36-[AMSIDCardTask hasEligibleDocument]_block_invoke
+ ___36-[AMSScreenTimeSettingsTask perform]_block_invoke
+ ___37-[AMSIDCardTask _performTaskInDaemon]_block_invoke
+ ___37-[AMSIDCardTask _performTaskInDaemon]_block_invoke_2
+ ___42-[AMSBagNetworkDataSource _invalidateData]_block_invoke
+ ___49-[AMSScreenTimeSettingsTask _performTaskInDaemon]_block_invoke
+ ___49-[AMSScreenTimeSettingsTask _performTaskInDaemon]_block_invoke_2
+ ___50-[AMSScreenTimeSettingsTask _performTaskInProcess]_block_invoke
+ ___50-[AMSScreenTimeSettingsTask _performTaskInProcess]_block_invoke_2
+ ___52-[AMSIDCardTask _performHasEligibleDocumentInDaemon]_block_invoke
+ ___52-[AMSIDCardTask _performHasEligibleDocumentInDaemon]_block_invoke_2
+ ___63-[AMSMarketingItemTaskURLBuilder _stringPromiseForKey:fromBag:]_block_invoke
+ ___64-[AMSMarketingItemTaskURLBuilder _realmOverridesPromiseFromBag:]_block_invoke
+ ___69+[AMSIDCardTask _dataFromIDCardForMinimumAge:nonce:allowedDocuments:]_block_invoke
+ ___69+[AMSIDCardTask _dataFromIDCardForMinimumAge:nonce:allowedDocuments:]_block_invoke_2
+ ___69+[AMSPushHandler accountIsEligibleForPushNotifications:accountStore:]_block_invoke
+ ___70-[AMSMarketingItemTaskURLBuilder _languageTagPromiseFromBag:fallback:]_block_invoke
+ ___73+[AMSPushHandler accountIsEligibleForPushNotifications:accountStore:bag:]_block_invoke
+ ___73+[AMSPushHandler accountIsEligibleForPushNotifications:accountStore:bag:]_block_invoke_2
+ ___74+[AMSIDCardTask _hasEligibleDocumentForMinimumAge:nonce:allowedDocuments:]_block_invoke
+ ___ScreenTimeCoreLibraryCore_block_invoke
+ ___block_descriptor_32_e32_"AMSPromise"16?0"AMSBoolean"8l
+ ___block_descriptor_40_e8_32s_e32_v24?0"AMSBoolean"8"NSError"16ls32l8
+ ___block_descriptor_40_e8_32s_e59_"AMSBinaryPromise"24?0"AMSEngagementResult"8"NSError"16ls32l8
+ ___block_descriptor_40_e8_32w_e24_v16?0"NSNotification"8lw32l8
+ ___block_descriptor_48_e29_"AMSPromise"16?0"NSError"8l
+ ___block_descriptor_48_e8_32s40r_e28_v24?0"NSData"8"NSError"16ls32l8r40l8
+ ___block_descriptor_48_e8_32s40r_e32_v24?0"AMSBoolean"8"NSError"16ls32l8r40l8
+ ___block_descriptor_48_e8_32s40s_e20_"AMSPromise"16?08ls32l8s40l8
+ ___block_descriptor_48_e8_32s_e40_v24?0"PKIdentityDocument"8"NSError"16ls32l8
+ ___block_descriptor_56_e8_32s40s_e32_v24?0"AMSBoolean"8"NSError"16ls32l8s40l8u48l8
+ ___block_descriptor_72_e8_32s40s48s56s_e8_v12?0B8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_73_e8_32s40s48s56s64s_e29_"AMSPromise"16?0"NSArray"8ls32l8s40l8s48l8s56l8s64l8
+ ___getPKIdentityAnyOfDescriptorClass_block_invoke
+ ___getPKIdentityAuthorizationControllerClass_block_invoke
+ ___getPKIdentityDriversLicenseDescriptorClass_block_invoke
+ ___getPKIdentityElementClass_block_invoke
+ ___getPKIdentityIntentToStoreClass_block_invoke
+ ___getPKIdentityNationalIDCardDescriptorClass_block_invoke
+ ___getPKIdentityPhotoIDDescriptorClass_block_invoke
+ ___getPKIdentityRequestClass_block_invoke
+ ___getSTManagementStateClass_block_invoke
+ ___maskrune
+ ___swift_closure_destructor.125Tm
+ ___swift_closure_destructor.162Tm
+ ___swift_closure_destructor.167Tm
+ ___swift_closure_destructor.171Tm
+ ___swift_closure_destructor.173Tm
+ ___swift_closure_destructor.182Tm
+ ___swift_closure_destructor.24Tm
+ ___swift_closure_destructor.274Tm
+ ___swift_closure_destructor.29Tm
+ ___swift_closure_destructor.39Tm
+ ___swift_closure_destructor.75Tm
+ ___swift_closure_destructor.80Tm
+ ___swift_closure_destructor.90Tm
+ ___swift_memcpy251_8
+ _associated conformance 18AppleMediaServices18SelfieAgeEstimatorC6ResultV10CodingKeys33_2BC3853D28E32BF2A0E39959D4E29788LLOSHAASQ
+ _associated conformance 18AppleMediaServices18SelfieAgeEstimatorC6ResultV10CodingKeys33_2BC3853D28E32BF2A0E39959D4E29788LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 18AppleMediaServices18SelfieAgeEstimatorC6ResultV10CodingKeys33_2BC3853D28E32BF2A0E39959D4E29788LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _audit_stringScreenTimeCore
+ _getPKIdentityAuthorizationControllerClass.softClass
+ _getPKIdentityRequestClass.softClass
+ _os_signpost_id_generate
+ _symbolic SdIeghHy_
+ _symbolic _____ 18AppleMediaServices18SelfieAgeEstimatorC6ResultV10CodingKeys33_2BC3853D28E32BF2A0E39959D4E29788LLO
+ _symbolic _____ 18AppleMediaServices34ServerSentEventsContinuationResultO
+ _symbolic _____XDXMT 18AppleMediaServices22ServerSentEventsClientC
+ _symbolic _____y_____G s22KeyedDecodingContainerV 18AppleMediaServices18SelfieAgeEstimatorC6ResultV10CodingKeys33_2BC3853D28E32BF2A0E39959D4E29788LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 18AppleMediaServices18SelfieAgeEstimatorC6ResultV10CodingKeys33_2BC3853D28E32BF2A0E39959D4E29788LLO
- +[AMSPromiseResult fallbackError]
- +[NSDate(AppleMediaServicesProject) ams_dateFromIMFFixDateString:]
- +[NSDate(AppleMediaServicesProject) ams_dateFromISO8601String:]
- +[NSDate(AppleMediaServicesProject) ams_dateFromLocalTimeZoneString:]
- -[AMSDaemonConnection attemptResumeIfRequired]
- -[AMSDaemonConnection setSharedConnection:]
- -[AMSMarketingItemTaskURLBuilder _countryCodeFromBag:]
- -[AMSMarketingItemTaskURLBuilder _formattedURLPathWithBag:]
- -[AMSMarketingItemTaskURLBuilder _languageTagFromBag:fallback:]
- -[AMSMarketingItemTaskURLBuilder _realmOverridesFromBag:]
- -[AMSMarketingItemTaskURLBuilder _stringForKey:fromBag:]
- -[AMSMarketingItemTaskURLBuilder _urlPathFromBag:]
- -[AMSPromiseResult getResult:error:]
- -[AMSPromiseResult immutableResult]
- -[NSDate(AppleMediaServicesProject) ams_formattedRepresentationWithTimeFunction:bufferSize:format:useColonInTZOffset:useFractionalSeconds:]
- -[NSDate(AppleMediaServicesProject) ams_imfFixDateRepresentation]
- -[NSDate(AppleMediaServicesProject) ams_iso8601LocalRepresentationWithTimeZoneFormatPreference:useFractionalSeconds:useZForUTC:]
- -[NSDate(AppleMediaServicesProject) ams_iso8601LocalRepresentation]
- -[NSDate(AppleMediaServicesProject) ams_iso8601UTCRepresentationWithTimeZoneFormatPreference:]
- -[NSDate(AppleMediaServicesProject) ams_iso8601UTCRepresentation]
- -[NSDate(AppleMediaServicesProject) ams_localTimeZoneStringRepresentation]
- -[NSString(AMSFormattingUtitlities) ams_doubleNumberValue]
- -[NSString(AMSFormattingUtitlities) ams_longLongNumberValue]
- GCC_except_table26
- GCC_except_table38
- GCC_except_table94
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSDate_$_AppleMediaServicesProject
- __OBJC_$_CATEGORY_NSDate_$_AppleMediaServicesProject
- __OBJC_$_CATEGORY_NSHTTPCookie_$_AppleMediaServices
- __OBJC_$_CLASS_METHODS_AMSPromiseResult
- __OBJC_$_CLASS_METHODS_NSDate(AppleMediaServicesProject|AppleMediaServices)
- __OBJC_$_CLASS_METHODS_NSHTTPCookie(AppleMediaServices|AMSCookieProperties|NSSecureCoding_Temporary)
- __OBJC_$_CLASS_METHODS_NSString(AppleMediaServices|AMSFormattingUtitlities|AppleMediaServices)
- __OBJC_$_CLASS_PROP_LIST_AMSPromiseResult
- __OBJC_$_INSTANCE_METHODS_AMSPromiseResult
- __OBJC_$_INSTANCE_METHODS_AMSURLAction
- __OBJC_$_INSTANCE_METHODS_AMSURLTaskInfo
- __OBJC_$_INSTANCE_METHODS_NSHTTPCookie(AppleMediaServices|AMSCookieProperties|NSSecureCoding_Temporary)
- __OBJC_$_INSTANCE_METHODS_NSString(AppleMediaServices|AMSFormattingUtitlities|AppleMediaServices)
- __OBJC_$_PROP_LIST_NSHTTPCookie_$_AppleMediaServices
- __OBJC_CLASS_PROTOCOLS_$_NSHTTPCookie(AppleMediaServices|AMSCookieProperties|NSSecureCoding_Temporary)
- ___46-[AMSDaemonConnection attemptResumeIfRequired]_block_invoke
- ___block_descriptor_40_e8_32s_e24_v16?0"NSNotification"8ls32l8
- ___block_descriptor_56_e8_32s40s_e30_v24?0"NSNumber"8"NSError"16ls32l8s40l8u48l8
- ___swift_closure_destructor.118Tm
- ___swift_closure_destructor.155Tm
- ___swift_closure_destructor.164Tm
- ___swift_closure_destructor.166Tm
- ___swift_closure_destructor.168Tm
- ___swift_closure_destructor.172Tm
- ___swift_closure_destructor.271Tm
- ___swift_closure_destructor.30Tm
- ___swift_closure_destructor.52Tm
- ___swift_closure_destructor.6Tm
- ___swift_closure_destructor.73Tm
- ___swift_closure_destructor.78Tm
- ___swift_closure_destructor.88Tm
- ___swift_memcpy250_8
- _get_type_metadata 15Synchronization5MutexVy18AppleMediaServices8OnceGateVyAD18PromiseFinishModelO6ActionVGG noncopyable
- _get_type_metadata 15Synchronization5MutexVy20ServicesAnalyticsKit7MetricsVSg7metrics_Sb11initializedtG noncopyable
- _get_type_metadata 15Synchronization5MutexVy29AppleMediaServicesKitInternal3Bag_pSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDy18AppleMediaServices22EngagementMessageCacheC20PlacementServiceType33_741E42E5AB747ED95DB42175BCCEDAA3LLVSo013AMSEngagementiH6PolicyVGG noncopyable
- _get_type_metadata 15Synchronization6AtomicVySbG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "%{public}@3DS interruption result status=%{public}@ sessionId=%{public}@ reason=%{public}@"
+ "%{public}@: Ignoring default value for buy param %{public}@ — it is not declared in %{public}@"
+ "%{public}@: [%{public}@] Account flags repair failed. error = %{public}@"
+ "%{public}@: [%{public}@] Applying Set-Storefront response header. url = %{public}@ | mediaType = %{public}@ | oldStorefront = %{public}@ | newStorefront = %{public}@"
+ "%{public}@: [%{public}@] Copying storefront from sponsor to new simple profile. storefront = %{public}@"
+ "%{public}@: [%{public}@] Failed to deserialize resumption headers. %{public}@"
+ "%{public}@: [%{public}@] Found %ld resumption headers. %ld"
+ "%{public}@: [%{public}@] ID Card UI was cancelled by user: %{public}@"
+ "%{public}@: [%{public}@] ITFE update notification received. Invalidating bag."
+ "%{public}@: [%{public}@] Opening sensitive URL: %{public}@"
+ "%{public}@: [%{public}@] Posting a CookiesChanged notification. added = %lu, removed = %lu, expiredInAdd = %lu"
+ "%{public}@: [%{public}@] Request document from wallet failed: %{public}@"
+ "%{public}@: [%{public}@] Sensitive URL failed to open."
+ "%{public}@: [%{public}@] Sensitive URL opened successfully."
+ "%{public}@: [%{public}@] Storefront changed. mediaType = %{public}@ | oldStorefront = %{public}@ | newStorefront = %{public}@ | account = %{public}@"
+ "%{public}@Account cookies added to cache. count=%lu countLimit=%lu"
+ "%{public}@Error checking for bag-based enablement: %{public}@"
+ "%{public}@Error occurred serializing resumption headers. error = %{public}@"
+ "%{public}@Failed to serialize resumption headers"
+ "%{public}@Failed to set communication safety state. error: %@"
+ "%{public}@Failed to set web content filter state. error: %@"
+ "%{public}@Failed to stash resumption headers. error: %{public}@"
+ "%{public}@In-memory cache is evicting an object. countLimit=%lu"
+ "%{public}@In-memory cache size after %{public}@: count=%lu countLimit=%lu"
+ "%{public}@Moving has eligible document task to daemon"
+ "%{public}@Moving task to daemon"
+ "%{public}@Removing X-Apple-BOP-* headers (no BOP-eligible path on this device/account)"
+ "%{public}@Setting account storefront from purchase. purchaseStorefront = %{public}@"
+ "%{public}@Starting task in daemon"
+ "%{public}@Starting task in process"
+ "%{public}@Starting task to set communication safety state: %@ and web content filter: %@"
+ "%{public}@Stashing resumption headers"
+ "%{public}@Storefront suffix changed. oldSuffix = %{public}@ | newSuffix = %{public}@"
+ "%{public}@Successfully set communication safety state"
+ "%{public}@Successfully set web content filter state"
+ "%{public}@Task failed with error: %@"
+ "%{public}@Task finished successfully with ID card data"
+ "%{public}@Task finished successfully. Has ID: %d"
+ "%{public}@failed to decode resultData payload, error = %{public}@"
+ ",shouldPerformPreflightAuthentication="
+ ",shouldUpdateDeviceState="
+ "@\"AMSBinaryPromise\"24@?0@\"AMSEngagementResult\"8@\"NSError\"16"
+ "AMSDevice+Offers: [%{public}@] Dropping Apple Music follow-up: a localized string failed to resolve (informativeText: %{public}@, title: %{public}@, continueLabel: %{public}@)"
+ "AMSDevice+Offers: [%{public}@] Dropping iCloud follow-up: a localized string failed to resolve (informativeText: %{public}@, title: %{public}@, continueLabel: %{public}@)"
+ "AMSDevice+Offers: [%{public}@] Dropping unified follow-up: a localized string failed to resolve (informativeText: %{public}@, title: %{public}@, appleMusicLabel: %{public}@, iCloudLabel: %{public}@)"
+ "AMSDevice+Offers: [%{public}@] Exception formatting follow-up description (exception: %{public}@, format: %{public}@)"
+ "AMSDevice+Offers: [%{public}@] Not posting follow up with identifier %{public}@: item could not be built"
+ "AMSManualCaptureOverride"
+ "Cannot repair account flags without an account identifier."
+ "Failed to insert resumption headers into keychain"
+ "JP"
+ "Local account fallback fetch failed. mediaType ="
+ "Local account fallback had no storefront. mediaType ="
+ "No account provided. Falling back to local account. mediaType ="
+ "PKIdentityAnyOfDescriptor"
+ "PKIdentityAuthorizationController"
+ "PKIdentityDriversLicenseDescriptor"
+ "PKIdentityElement"
+ "PKIdentityIntentToStore"
+ "PKIdentityNationalIDCardDescriptor"
+ "PKIdentityPhotoIDDescriptor"
+ "PKIdentityRequest"
+ "Payment sheet dismissed by an unrecognized authorization event"
+ "Performing XPC to daemon for account flags repair"
+ "Provided account had no storefront. Falling back to local account. mediaType ="
+ "Provided ephemeral account had no storefront. mediaType ="
+ "Provided local account had no storefront. mediaType ="
+ "Request document from wallet failed"
+ "SSE endpoint returned HTTP "
+ "STManagementState"
+ "SigningHeaders"
+ "The payment sheet was dismissed by an unrecognized event"
+ "Use -initWithResult:error:"
+ "User cancelled out of wallet UI"
+ "bundleVersion"
+ "buyParamsForLoadURLEventDefaultValues"
+ "cancelled"
+ "checkCanRequestDocument says there is nothing suitable in the wallet"
+ "com.apple.ams-identity-verification"
+ "entitlementData"
+ "extensionData"
+ "internalError"
+ "mediaType=%{public}@"
+ "push-notifications/should-register-for-managed-accounts"
+ "reasonMessage"
+ "rejected"
+ "repairAccountFlagsForAccountID called with nil accountID"
+ "resolved"
+ "shouldPerformPreflightAuthentication"
+ "shouldUpdateDeviceState"
+ "softlink:r:path:/System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeCore"
+ "v24@?0@\"PKIdentityDocument\"8@\"NSError\"16"
- "%{public}@: [%{public}@] Failed to deserialize TID continue headers. %{public}@"
- "%{public}@: [%{public}@] Failed to file auto bug capture for stale key. error = %{public}@"
- "%{public}@: [%{public}@] Found %ld TID headers. %ld"
- "%{public}@: [%{public}@] Posting a CookiesChanged notification."
- "%{public}@: [%{public}@] Reconnecting XPC connection"
- "%{public}@Account cookies added to cache."
- "%{public}@Error occurred serializing TID continue headers. error = %{public}@"
- "%{public}@Failed to serialize TID continue headers"
- "%{public}@Failed to stash TID continue headers. error: %{public}@"
- "%{public}@In-memory cache is evicting an object."
- "%{public}@Stashing TID headers"
- "AccountPropertyDecryption"
- "Failed to insert TID headers into keychain"
- "Not implemented"
- "StaleKeyDetected"
```
