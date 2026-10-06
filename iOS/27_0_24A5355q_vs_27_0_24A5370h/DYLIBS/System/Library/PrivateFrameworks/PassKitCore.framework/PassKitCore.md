## PassKitCore

> `/System/Library/PrivateFrameworks/PassKitCore.framework/PassKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8e06dc` | `0x8e3394` | **`+0x2cb8`** |
| `__TEXT.__oslogstring` | `0x39d55` | `0x3a920` | **`+0xbcb`** |
| `__TEXT.__eh_frame` | `0x7cb8` | `0x8718` | **`+0xa60`** |
| `__TEXT.__cstring` | `0x7246d` | `0x71b3b` | **`-0x932`** |
| `__AUTH.__data` | `0x4c40` | `0x5250` | **`+0x610`** |
| `__AUTH_CONST.__objc_const` | `0xcece0` | `0xcf2a0` | **`+0x5c0`** |
| `__TEXT.__swift5_reflstr` | `0x5f0d` | `0x629d` | **`+0x390`** |
| `__TEXT.__swift5_fieldmd` | `0x7680` | `0x79d8` | **`+0x358`** |
| `__TEXT.__unwind_info` | `0x1f418` | `0x1f710` | **`+0x2f8`** |
| `__TEXT.__constg_swiftt` | `0x6e3c` | `0x70d8` | **`+0x29c`** |
| `__AUTH_CONST.__const` | `0x25278` | `0x254c8` | **`+0x250`** |
| `__TEXT.__const` | `0x2c730` | `0x2c950` | **`+0x220`** |
| `__TEXT.__swift5_typeref` | `0x86ec` | `0x852c` | **`-0x1c0`** |
| `__TEXT.__swift5_capture` | `0x49dc` | `0x4aec` | **`+0x110`** |
| `__AUTH_CONST.__cfstring` | `0x779c0` | `0x77ac0` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x22ab8` | `0x22b88` | **`+0xd0`** |
| `__TEXT.__swift_as_cont` | `0x32c` | `0x3b0` | **`+0x84`** |
| `__DATA.__bss` | `0x25958` | `0x259c8` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x24f18` | `0x24ec0` | **`-0x58`** |
| `__AUTH.__objc_data` | `0x22890` | `0x228e0` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x5820` | `0x57d0` | **`-0x50`** |
| `__DATA_CONST.__got` | `0x5350` | `0x5310` | **`-0x40`** |
| `__TEXT.__swift5_types` | `0x76c` | `0x7a0` | **`+0x34`** |
| `__TEXT.__swift_as_ret` | `0x17c` | `0x1ac` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x15c` | `0x188` | **`+0x2c`** |
| `__DATA.__data` | `0x9ea8` | `0x9e88` | **`-0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x3dc8` | `0x3de8` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x6a18` | `0x6a00` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x72040` | `0x72028` | **`-0x18`** |
| `__TEXT.__swift5_assocty` | `0xd80` | `0xd98` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x7280` | `0x7294` | **`+0x14`** |
| `__DATA_DIRTY.__objc_ivar` | `0x1f0c` | `0x1f20` | **`+0x14`** |
| `__TEXT.__swift5_builtin` | `0x49c` | `0x4b0` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x2ec8` | `0x2eb8` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x1374` | `0x1378` | **`+0x4`** |

### Other Changes

```diff

-1677.4.0.0.0
+1682.1.0.0.0

-  Functions: 54855
-  Symbols:   78385
-  CStrings:  21325
+  Functions: 55024
+  Symbols:   78461
+  CStrings:  21323
Symbols:
+ +[PKAccountServiceUnavailablePeriod supportsSecureCoding]
+ +[PKAnalyticsReporter(AppleCash) reportSplitBillLineItemEventWithPageTag:eventType:buttonTag:p2pContext:messagesContext:billSplitContext:]
+ +[PKAnalyticsReporter(IdentityShared) reportIdentityPassUpdateBundleEventType:additionalDetails:bundleSessionID:]
+ -[PKAccount serviceUnavailablePeriod]
+ -[PKAccount setServiceUnavailablePeriod:]
+ -[PKAccountServiceUnavailablePeriod .cxx_destruct]
+ -[PKAccountServiceUnavailablePeriod copyWithZone:]
+ -[PKAccountServiceUnavailablePeriod description]
+ -[PKAccountServiceUnavailablePeriod encodeWithCoder:]
+ -[PKAccountServiceUnavailablePeriod hash]
+ -[PKAccountServiceUnavailablePeriod initWithCoder:]
+ -[PKAccountServiceUnavailablePeriod initWithDictionary:]
+ -[PKAccountServiceUnavailablePeriod isEqual:]
+ -[PKAccountServiceUnavailablePeriod isEqualToAccountServiceUnavailablePeriod:]
+ -[PKAccountServiceUnavailablePeriod reason]
+ -[PKAccountServiceUnavailablePeriod setReason:]
+ -[PKAccountServiceUnavailablePeriod setStartDate:]
+ -[PKAccountServiceUnavailablePeriod startDate]
+ -[PKAccountSupportTopicExplanationLink termsIdentifier]
+ -[PKAnonymizedAnalyticsSecret setSyncedToKeychain:]
+ -[PKAnonymizedAnalyticsSecret syncedToKeychain]
+ -[PKAppletSubcredentialSharingSession getPretrackRequestForInvitationWithIdentifier:withCompletion:]
+ -[PKAppletSubcredentialSharingSession getProductPlanIdentifierRequestForInvitationWithIdentifier:completion:]
+ -[PKAppletSubcredentialSharingSession handleInitiatorMessage:forInvitationIdentifier:completion:]
+ -[PKAppletSubcredentialSharingSession routingInformationForInvitationWithIdentifier:completionHandler:]
+ -[PKAppletSubcredentialSharingSession startShareAcceptanceFlowWithInvitation:completion:]
+ -[PKApplyWebServiceAugmentedProductRequest productIdentifier]
+ -[PKApplyWebServiceAugmentedProductRequest setProductIdentifier:]
+ -[PKApplyWebServiceCreateRequest productIdentifier]
+ -[PKApplyWebServiceCreateRequest setProductIdentifier:]
+ -[PKApplyWebServiceFeatureTermsDataRequest productIdentifier]
+ -[PKApplyWebServiceFeatureTermsDataRequest setProductIdentifier:]
+ -[PKDAManager getPretrackRequestForInvitationWithIdentifier:withCompletion:]
+ -[PKDAManager getProductPlanIdentifierRequestForInvitationWithIdentifier:completion:]
+ -[PKDAManager handleInitiatorMessage:forInvitationIdentifier:completion:]
+ -[PKDAManager routingInformationForInvitationWithIdentifier:completionHandler:]
+ -[PKDAManager startShareAcceptanceFlowWithInvitation:completion:]
+ -[PKExistingCardAuthorizationRequestMessage destinationDeviceName]
+ -[PKExistingCardAuthorizationRequestMessage destinationDeviceType]
+ -[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:]
+ -[PKFileDataAccessor _passLocalizedStringForKey:preferredLanguages:]
+ -[PKMobileAssetManager cachedStringsBundleWithIdentifier:completion:]
+ -[PKPassAuxiliaryPassInformationItem _recomputeEffectiveSubtitles]
+ -[PKPassAuxiliaryPassInformationItem detailBackgroundImageResourceWithScale:]
+ -[PKPassAuxiliaryPassInformationItem detailIconImageResourceWithScale:]
+ -[PKPaymentAuthorizationDataModel _defaultSelectedPaymentApplicationForPaymentApplications:issuerCountryCode:]
+ -[PKPaymentRequest remoteNetworkRequestHostApplicationIdentifier]
+ -[PKPaymentRequest remoteNetworkRequestHostApplicationName]
+ -[PKPaymentRequest remoteNetworkRequestHostBundleIdentifier]
+ -[PKPaymentRequest setRemoteNetworkRequestHostApplicationIdentifier:]
+ -[PKPaymentRequest setRemoteNetworkRequestHostApplicationName:]
+ -[PKPaymentRequest setRemoteNetworkRequestHostBundleIdentifier:]
+ -[PKPaymentService augmentedProductForInstallmentConfiguration:experimentDetails:feature:productIdentifier:withCompletion:]
+ -[PKPaymentTransaction peerPaymentFlowType]
+ -[PKPaymentTransaction setPeerPaymentFlowType:]
+ -[PKPaymentWebServiceTargetDevice carKeyGetPretrackRequestForInvitationWithIdentifier:completion:]
+ -[PKPeerPaymentPendingRequest isExpired]
+ -[PKPendingCarKeyProvisioning applyResumeSessionConfigurationForManualResume:userInitiated:]
+ -[PKProvisioningAssetManager preloadProvisioningStringsBundleWithCompletion:]
+ -[PKTransitBalanceModel updateWithPass:]
+ GCC_except_table107
+ GCC_except_table132
+ GCC_except_table221
+ GCC_except_table285
+ GCC_except_table288
+ GCC_except_table295
+ GCC_except_table312
+ GCC_except_table318
+ GCC_except_table324
+ GCC_except_table326
+ GCC_except_table336
+ GCC_except_table341
+ GCC_except_table365
+ GCC_except_table378
+ GCC_except_table396
+ GCC_except_table412
+ GCC_except_table471
+ GCC_except_table481
+ GCC_except_table483
+ GCC_except_table492
+ GCC_except_table538
+ GCC_except_table540
+ GCC_except_table544
+ GCC_except_table546
+ GCC_except_table548
+ GCC_except_table554
+ GCC_except_table556
+ GCC_except_table563
+ GCC_except_table571
+ GCC_except_table598
+ GCC_except_table688
+ GCC_except_table732
+ GCC_except_table740
+ GCC_except_table773
+ GCC_except_table81
+ GCC_except_table85
+ GCC_except_table891
+ _OBJC_CLASS_$_PKAccountServiceUnavailablePeriod
+ _OBJC_IVAR_$_PKAccount._serviceUnavailablePeriod
+ _OBJC_IVAR_$_PKAccountServiceUnavailablePeriod._reason
+ _OBJC_IVAR_$_PKAccountServiceUnavailablePeriod._startDate
+ _OBJC_IVAR_$_PKAccountSupportTopicExplanationLink._termsIdentifier
+ _OBJC_IVAR_$_PKAnonymizedAnalyticsSecret._syncedToKeychain
+ _OBJC_IVAR_$_PKPassAuxiliaryPassInformationItem._detailBackgroundImageResource
+ _OBJC_IVAR_$_PKPassAuxiliaryPassInformationItem._detailBackgroundImageScale
+ _OBJC_IVAR_$_PKPassAuxiliaryPassInformationItem._detailIconImageResource
+ _OBJC_IVAR_$_PKPassAuxiliaryPassInformationItem._detailIconImageScale
+ _OBJC_IVAR_$_PKPassAuxiliaryPassInformationItem._effectiveSubtitle
+ _OBJC_IVAR_$_PKPassAuxiliaryPassInformationItem._effectiveSubtitle2
+ _OBJC_IVAR_$_PKPaymentRequest._remoteNetworkRequestHostApplicationIdentifier
+ _OBJC_IVAR_$_PKPaymentRequest._remoteNetworkRequestHostApplicationName
+ _OBJC_IVAR_$_PKPaymentRequest._remoteNetworkRequestHostBundleIdentifier
+ _OBJC_IVAR_$_PKPaymentTransaction._peerPaymentFlowType
+ _OBJC_METACLASS_$_PKAccountServiceUnavailablePeriod
+ _PKAccountServiceUnavailablePeriodReasonToString
+ _PKAnalyticsReportAddMoneyPresentedTag
+ _PKAnalyticsReportBundleSessionIDKey
+ _PKAnalyticsReportEventTypeBalanceRefreshed
+ _PKAnalyticsReportEventTypePIITokenDeleteCalled
+ _PKAnalyticsReportEventTypePIITokenRetrievalCalled
+ _PKAnalyticsReportEventTypePassKeyGenerationFailed
+ _PKAnalyticsReportEventTypePassPayloadDigestionFailed
+ _PKAnalyticsReportEventTypePassPayloadDownloadFailed
+ _PKAnalyticsReportEventTypePassRegisterFailed
+ _PKAnalyticsReportEventTypePassUpdateNotificationReceived
+ _PKAnalyticsReportEventTypeTopUpFailure
+ _PKAnalyticsReportEventTypeTopUpSuccess
+ _PKAnalyticsReportPeerPaymentAddTipAlertPageTag
+ _PKAnalyticsReportPeerPaymentAddTipButtonTag
+ _PKAnalyticsReportPeerPaymentCancelButtonTag
+ _PKAnalyticsReportPeerPaymentContinueButtonTag
+ _PKAnalyticsReportPeerPaymentCustomTaxButtonTag
+ _PKAnalyticsReportPeerPaymentCustomTipButtonTag
+ _PKAnalyticsReportPeerPaymentDoneButtonTag
+ _PKAnalyticsReportPeerPaymentEditButtonTag
+ _PKAnalyticsReportPeerPaymentItemSelectButtonTag
+ _PKAnalyticsReportPeerPaymentItemUpdateButtonTag
+ _PKAnalyticsReportPeerPaymentLoadingScreenPageTag
+ _PKAnalyticsReportPeerPaymentNoTaxButtonTag
+ _PKAnalyticsReportPeerPaymentNoTipButtonTag
+ _PKAnalyticsReportPeerPaymentOkButtonTag
+ _PKAnalyticsReportPeerPaymentPresetTaxButtonTag
+ _PKAnalyticsReportPeerPaymentPresetTipButtonTag
+ _PKAnalyticsReportPeerPaymentRetakeButtonTag
+ _PKAnalyticsReportPeerPaymentSplitRequestPageTag
+ _PKAnalyticsReportPeerPaymentSplitSendPageTag
+ _PKAnalyticsReportPeerPaymentTaxButtonTag
+ _PKAnalyticsReportSyncedToKeychainKey
+ _PKAnalyticsReportTopUpInitiatedPageTag
+ _PKAppleCardMultiIssuerModeEnabled
+ _PKCameraInputFileData
+ _PKExistingCardAuthorizationDestinationDeviceNameKey
+ _PKExistingCardAuthorizationDestinationDeviceTypeKey
+ _PKHasSeenPeerPaymentBillSplitEducation
+ _PKHasSeenPeerPaymentBillSplitEducationKey
+ _PKPassbookUIServiceProvisioningContinuityRemoteDeviceType
+ _PKPaymentRequestRemoteNetworkRequestHostApplicationIdentifierKey
+ _PKPaymentRequestRemoteNetworkRequestHostApplicationNameKey
+ _PKPaymentRequestRemoteNetworkRequestHostBundleIdentifierKey
+ _PKPeerPaymentAccountCanGraduate
+ _PKPeerPaymentDismissedGraduationEducation
+ _PKPeerPaymentFlowTypeFromString
+ _PKPeerPaymentHasDismissedGraduationEducation
+ _PKPeerPaymentReceiptSimulatedError
+ _PKPeerPaymentReceiptSimulatedErrorKey
+ _PKPeerPaymentSetHasDismissedGraduationEducation
+ _PKProvisioningErrorSeverityForSPStatusCode
+ _PKRemoteDeviceTypeFromString
+ _PKRemoteDeviceTypeToString
+ _PKServiceProviderOrderCardTypeKey
+ _PKServiceProviderOrderDisplayNameKey
+ _PKServiceProviderOrderPaymentNetworkKey
+ _PKSetCameraInputFileData
+ _PKSetHasSeenPeerPaymentBillSplitEducation
+ _PKSetPeerPaymentReceiptSimulatedError
+ _PKSyncedToKeychain
+ _PKTransitCommutePlanGenericTimedPlanKey
+ _PKURLActionPhysicalCardOrderReason
+ _PKURLSubactionRouteCreditPaymentPassLockUnlock
+ __DATA__TtCC11PassKitCore28StartRemotePaymentDispatcher15PaymentExecutor
+ __DATA__TtCC11PassKitCore28StartRemotePaymentDispatcher15PrewarmExecutor
+ __DATA__TtCC11PassKitCore28StartRemotePaymentDispatcher18CompanionDiscovery
+ __DATA__TtCC11PassKitCore28StartRemotePaymentDispatcher18PrewarmCoordinator
+ __DATA__TtCC11PassKitCore28StartRemotePaymentDispatcher19ActiveDispatchStore
+ __IVARS__TtCC11PassKitCore28StartRemotePaymentDispatcher15PaymentExecutor
+ __IVARS__TtCC11PassKitCore28StartRemotePaymentDispatcher15PrewarmExecutor
+ __IVARS__TtCC11PassKitCore28StartRemotePaymentDispatcher18CompanionDiscovery
+ __IVARS__TtCC11PassKitCore28StartRemotePaymentDispatcher18PrewarmCoordinator
+ __IVARS__TtCC11PassKitCore28StartRemotePaymentDispatcher19ActiveDispatchStore
+ __METACLASS_DATA__TtCC11PassKitCore28StartRemotePaymentDispatcher15PaymentExecutor
+ __METACLASS_DATA__TtCC11PassKitCore28StartRemotePaymentDispatcher15PrewarmExecutor
+ __METACLASS_DATA__TtCC11PassKitCore28StartRemotePaymentDispatcher18CompanionDiscovery
+ __METACLASS_DATA__TtCC11PassKitCore28StartRemotePaymentDispatcher18PrewarmCoordinator
+ __METACLASS_DATA__TtCC11PassKitCore28StartRemotePaymentDispatcher19ActiveDispatchStore
+ __OBJC_$_CLASS_METHODS_PKAccountServiceUnavailablePeriod
+ __OBJC_$_CLASS_PROP_LIST_PKAccountServiceUnavailablePeriod
+ __OBJC_$_INSTANCE_METHODS_PKAccountServiceUnavailablePeriod
+ __OBJC_$_INSTANCE_VARIABLES_PKAccountServiceUnavailablePeriod
+ __OBJC_$_PROP_LIST_PKAccountServiceUnavailablePeriod
+ __OBJC_CLASS_PROTOCOLS_$_PKAccountServiceUnavailablePeriod
+ __OBJC_CLASS_RO_$_PKAccountServiceUnavailablePeriod
+ __OBJC_METACLASS_RO_$_PKAccountServiceUnavailablePeriod
+ __ResolveDetailImage
+ ___100-[PKAppletSubcredentialSharingSession getPretrackRequestForInvitationWithIdentifier:withCompletion:]_block_invoke
+ ___109-[PKAppletSubcredentialSharingSession getProductPlanIdentifierRequestForInvitationWithIdentifier:completion:]_block_invoke
+ ___123-[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:]_block_invoke
+ ___123-[PKPaymentService augmentedProductForInstallmentConfiguration:experimentDetails:feature:productIdentifier:withCompletion:]_block_invoke
+ ___65-[PKDAManager startShareAcceptanceFlowWithInvitation:completion:]_block_invoke
+ ___69-[PKMobileAssetManager cachedStringsBundleWithIdentifier:completion:]_block_invoke
+ ___73-[PKDAManager handleInitiatorMessage:forInvitationIdentifier:completion:]_block_invoke
+ ___73-[PKMobileAssetManager updateUGPassBackgroundsIfNecessaryWithCompletion:]_block_invoke_2
+ ___76-[PKDAManager getPretrackRequestForInvitationWithIdentifier:withCompletion:]_block_invoke
+ ___76-[PKDAManager getPretrackRequestForInvitationWithIdentifier:withCompletion:]_block_invoke_2
+ ___77-[PKProvisioningAssetManager preloadProvisioningStringsBundleWithCompletion:]_block_invoke
+ ___79-[PKDAManager routingInformationForInvitationWithIdentifier:completionHandler:]_block_invoke
+ ___79-[PKDAManager routingInformationForInvitationWithIdentifier:completionHandler:]_block_invoke_2
+ ___83-[PKContactlessInterfaceSession stsSession:didReceive18013Requests:readerAuthInfo:]_block_invoke_2
+ ___85-[PKDAManager getProductPlanIdentifierRequestForInvitationWithIdentifier:completion:]_block_invoke
+ ___85-[PKDAManager getProductPlanIdentifierRequestForInvitationWithIdentifier:completion:]_block_invoke_2
+ ___98-[PKPaymentWebServiceTargetDevice carKeyGetPretrackRequestForInvitationWithIdentifier:completion:]_block_invoke
+ ___block_descriptor_48_e8_32bs40bs_e32_v16?0"DAShareInitiatorResult"8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e18_v16?0"NSBundle"8ls32l8s40l8s48l8
+ ___block_descriptor_56_e8_32s40s48bs_e8_v16?0q8ls48l8s32l8s40l8
+ ___block_descriptor_57_e8_32s40bs_e8_v12?0B8ls40l8s32l8
+ ___block_descriptor_65_e8_32s40s48s56bs_e8_v16?0q8ls32l8s56l8s40l8s48l8
+ ___swift_memcpy416_8
+ _kSecAttrIsInvisible
+ _kSecAttrSyncViewHint
+ _kSecAttrViewHintLimitedPeersAllowed
+ _swift_release_x10
+ _symbolic 6Output_____Qz 18AppIntentsServices0A20IntentRepresentationP
+ _symbolic SDy__________y___________ySbGGG 10Foundation4UUIDV 18AppIntentsServices0dE0O12ProgressTaskV AF08DispatchF0O AD0C19IntentSuccessResultV
+ _symbolic Say_____G 11PassKitCore19RemoteDeviceContextV
+ _symbolic Say_____G 11PassKitCore28StartRemotePaymentDispatcherC18PrewarmCoordinatorC7Pending33_37FFC685440A20DF275B82D2DDD563C6LLV
+ _symbolic ScCyyt______pG s5ErrorP
+ _symbolic ScCyyt______pGSg s5ErrorP
+ _symbolic ScTyyt_____GSg s5NeverO
+ _symbolic _____ 11PassKitCore07FinanceB22EligibleAccountsLoaderO
+ _symbolic _____ 11PassKitCore19RemoteDeviceContextV
+ _symbolic _____ 11PassKitCore27BundledIntentRepresentation33_76A9337E6F832EE58D4B71BAF92E309ELLV
+ _symbolic _____ 11PassKitCore28StartRemotePaymentDispatcherC0F8ExecutorC
+ _symbolic _____ 11PassKitCore28StartRemotePaymentDispatcherC0G5State33_FBBDA1DCB3D9D036BB198D211E1E2946LLV
+ _symbolic _____ 11PassKitCore28StartRemotePaymentDispatcherC0G5State33_FBBDA1DCB3D9D036BB198D211E1E2946LLV7PrewarmV
+ _symbolic _____ 11PassKitCore28StartRemotePaymentDispatcherC14PrewarmContext33_FBBDA1DCB3D9D036BB198D211E1E2946LLV
+ _symbolic _____ 11PassKitCore28StartRemotePaymentDispatcherC15PrewarmExecutorC
+ _symbolic _____ 11PassKitCore28StartRemotePaymentDispatcherC18CompanionDiscoveryC
+ _symbolic _____ 11PassKitCore28StartRemotePaymentDispatcherC18PrewarmCoordinatorC
+ _symbolic _____ 11PassKitCore28StartRemotePaymentDispatcherC18PrewarmCoordinatorC5State33_37FFC685440A20DF275B82D2DDD563C6LLV
+ _symbolic _____ 11PassKitCore28StartRemotePaymentDispatcherC18PrewarmCoordinatorC7Pending33_37FFC685440A20DF275B82D2DDD563C6LLV
+ _symbolic _____ 11PassKitCore28StartRemotePaymentDispatcherC19ActiveDispatchStoreC
+ _symbolic _____ 11PassKitCore28StartRemotePaymentDispatcherC19ActiveDispatchStoreC0hI0V
+ _symbolic _____ 11PassKitCore28StartRemotePaymentDispatcherC19ActiveDispatchStoreC5State33_3E7DDA97A71E34A45313BC15A7DE7099LLV
+ _symbolic _____ 18AppIntentsServices0bC0O15DevicePredicateO
+ _symbolic _____ 18AppIntentsServices0bC0O6DeviceV
+ _symbolic _____ So34PKContinueRemoteNetworkPaymentTypeV
+ _symbolic _____IeghHn_ 18AppIntentsServices0bC0O6DeviceV
+ _symbolic _____Sg 11PassKitCore28StartRemotePaymentDispatcherC0F8ExecutorC
+ _symbolic _____Sg 11PassKitCore28StartRemotePaymentDispatcherC14PrewarmContext33_FBBDA1DCB3D9D036BB198D211E1E2946LLV
+ _symbolic _____Sg 11PassKitCore28StartRemotePaymentDispatcherC15PrewarmExecutorC
+ _symbolic _____Sg 11PassKitCore28StartRemotePaymentDispatcherC19ActiveDispatchStoreC0hI0V
+ _symbolic _____Sg 18AppIntentsServices13SchemaVersionV
+ _symbolic _____SgXw 11PassKitCore28StartRemotePaymentDispatcherC0F8ExecutorC
+ _symbolic _____SgXw 11PassKitCore28StartRemotePaymentDispatcherC18CompanionDiscoveryC
+ _symbolic _____SgXw 11PassKitCore28StartRemotePaymentDispatcherC18PrewarmCoordinatorC
+ _symbolic _____SgXwz_Xx 11PassKitCore28StartRemotePaymentDispatcherC0F8ExecutorC
+ _symbolic _____SgXwz_Xx 11PassKitCore28StartRemotePaymentDispatcherC18CompanionDiscoveryC
+ _symbolic _____SgXwz_Xx 11PassKitCore28StartRemotePaymentDispatcherC18PrewarmCoordinatorC
+ _symbolic _____Sg_ABt 10Foundation4UUIDV
+ _symbolic ___________y___________ySbGGt 10Foundation4UUIDV 18AppIntentsServices0dE0O12ProgressTaskV AF08DispatchF0O AD0C19IntentSuccessResultV
+ _symbolic ______pIeghg_ 18AppIntentsServices06RemoteA17IntentDispatchingP
+ _symbolic _____yScCyyt______pGG s23_ContiguousArrayStorageC s5ErrorP
+ _symbolic _____yScTyyt_____GSgG 2os21OSAllocatedUnfairLockV s5NeverO
+ _symbolic _____yScTyyt_____GSg_____G s13ManagedBufferCsRi__rlE s5NeverO So16os_unfair_lock_sV
+ _symbolic _____y_____G 11PassKitCore27BundledIntentRepresentation33_76A9337E6F832EE58D4B71BAF92E309ELLV AA025StartRemoteNetworkPaymenteF0V
+ _symbolic _____y_____G 11PassKitCore27BundledIntentRepresentation33_76A9337E6F832EE58D4B71BAF92E309ELLV AA030EndRemoteNetworkPaymentPairingeF0V
+ _symbolic _____y_____G 11PassKitCore27BundledIntentRepresentation33_76A9337E6F832EE58D4B71BAF92E309ELLV AA032CheckPaymentRequestCompatibilityeF0V
+ _symbolic _____y_____G 11PassKitCore27BundledIntentRepresentation33_76A9337E6F832EE58D4B71BAF92E309ELLV AA039PrewarmStartRemoteNetworkPaymentPairingeF0V
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 11PassKitCore28StartRemotePaymentDispatcherC0K5State33_FBBDA1DCB3D9D036BB198D211E1E2946LLV
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 11PassKitCore28StartRemotePaymentDispatcherC18PrewarmCoordinatorC5State33_37FFC685440A20DF275B82D2DDD563C6LLV
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 11PassKitCore28StartRemotePaymentDispatcherC19ActiveDispatchStoreC5State33_3E7DDA97A71E34A45313BC15A7DE7099LLV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10FinanceKit15InternalAccountV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 11PassKitCore19RemoteDeviceContextV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 11PassKitCore28StartRemotePaymentDispatcherC18PrewarmCoordinatorC7Pending33_37FFC685440A20DF275B82D2DDD563C6LLV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 11PassKitCore28StartRemotePaymentDispatcherC0I5State33_FBBDA1DCB3D9D036BB198D211E1E2946LLV So16os_unfair_lock_sV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 11PassKitCore28StartRemotePaymentDispatcherC18PrewarmCoordinatorC5State33_37FFC685440A20DF275B82D2DDD563C6LLV So16os_unfair_lock_sV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 11PassKitCore28StartRemotePaymentDispatcherC19ActiveDispatchStoreC5State33_3E7DDA97A71E34A45313BC15A7DE7099LLV So16os_unfair_lock_sV
+ _symbolic _____y___________ySbGGSg 18AppIntentsServices0bC0O12ProgressTaskV AC08DispatchD0O AA0A19IntentSuccessResultV
+ _symbolic _____y___________y_____GG 18AppIntentsServices0bC0O12ProgressTaskV AC08DispatchD0O AA0A19IntentSuccessResultV 11PassKitCore017PaymentCapabilityI14RepresentationO
+ _symbolic _____y__________y___________ySbGGG s18_DictionaryStorageC 10Foundation4UUIDV 18AppIntentsServices0fG0O12ProgressTaskV AH08DispatchH0O AF0E19IntentSuccessResultV
+ _symbolic ySSYbc
+ _symbolic y_____YaYbc 11PassKitCore28StartRemotePaymentDispatcherC15ConnectedDeviceO
+ _symbolic yyYaYbc
+ _type_layout_string 11PassKitCore19RemoteDeviceContextV
+ _type_layout_string 11PassKitCore28StartRemotePaymentDispatcherC18PrewarmCoordinatorC5State33_37FFC685440A20DF275B82D2DDD563C6LLV
- +[PKAnonymizedAnalyticsSecretFetcher _wrapperWithType:forIdentifier:]
- +[PKPassFeaturedActionTileBuilder _createTileFromFeaturedAction:]
- +[PKPassFeaturedActionTileBuilder createTilesFromFeaturedActions:]
- +[PKPassSharePendingActivation supportsSecureCoding]
- -[PKAppletSubcredentialManagementSession signData:auth:bundleIdentifier:nonce:credential:completion:]
- -[PKAppletSubcredentialManagementSession trackSubcredential:encryptedContainer:withReceipt:]
- -[PKAppletSubcredentialPairingSession trackSubcredential:encryptedContainer:withReceipt:]
- -[PKAppletSubcredentialSharingInvitation invitationRequestRepresentation]
- -[PKAppletSubcredentialSharingInvitation sharingConfigurationRepresentation]
- -[PKAppletSubcredentialSharingSession acceptCrossPlatformInvitationWithIdentifier:transportChannelIdentifier:activationCode:encryptedProductPlanIdentifierContainer:completion:]
- -[PKAppletSubcredentialSharingSession getProductPlanIdentifierRequestForInvitationWithIdentifier:fromMailboxIdentifier:completion:]
- -[PKAppletSubcredentialSharingSession retryActivationCodeForCredentialIdentifier:activationCode:completion:]
- -[PKAppletSubcredentialSharingSession routingInformationForInvitationWithIdentifier:fromMailboxIdentifier:completionHandler:]
- -[PKAppletSubcredentialSharingSession setTransportChannelIdentifier:forCredential:forCredentialShare:completion:]
- -[PKAppletSubcredentialSharingSession startShareAcceptanceFlowWithInvitation:fromMailboxIdentifier:completion:]
- -[PKDAManager acceptCrossPlatformInvitationWithIdentifier:transportChannelIdentifier:activationCode:encryptedProductPlanIdentifierContainer:completion:]
- -[PKDAManager handleOutstandingMessage:subcredentialIdentifier:credentialShareIdentifier:transportIdentifier:completion:]
- -[PKDAManager retryActivationCodeForCredentialIdentifier:activationCode:completion:]
- -[PKDAManager setTransportChannelIdentifier:forCredential:forCredentialShare:completion:]
- -[PKDAManager signData:auth:bundleIdentifier:nonce:credential:completion:]
- -[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:]
- -[PKPassAuxiliaryPassInformationItem detailBackgroundImageName]
- -[PKPassAuxiliaryPassInformationItem detailIconImageName]
- -[PKPassAuxiliaryPassInformationItem setDetailBackgroundImageName:]
- -[PKPassAuxiliaryPassInformationItem setDetailIconImageName:]
- -[PKPassLibrary hasProvisioningExtensionsWithSupportedNetworks:merchantCapabilities:issuerCountryCodes:]
- -[PKPassSharePendingActivation .cxx_destruct]
- -[PKPassSharePendingActivation description]
- -[PKPassSharePendingActivation encodeWithCoder:]
- -[PKPassSharePendingActivation hash]
- -[PKPassSharePendingActivation initWithCoder:]
- -[PKPassSharePendingActivation isEqual:]
- -[PKPassSharePendingActivation isEqualToPassSharePendingActivation:]
- -[PKPassSharePendingActivation isWaitingOnUserAction]
- -[PKPassSharePendingActivation originalInvitation]
- -[PKPassSharePendingActivation setIsWaitingOnUserAction:]
- -[PKPassSharePendingActivation setOriginalInvitation:]
- -[PKPassSharePendingActivation setShareIdentifier:]
- -[PKPassSharePendingActivation shareIdentifier]
- -[PKPaymentAuthorizationDataModel _defaultSelectedPaymentApplicationForPaymentApplications:]
- -[PKPaymentService allPaymentApplicationUsageSummaries]
- -[PKPaymentService augmentedProductForInstallmentConfiguration:experimentDetails:feature:withCompletion:]
- -[PKPaymentService recordPaymentApplicationUsageForPassUniqueIdentifier:paymentApplicationIdentifier:]
- -[PKPaymentService(Sharing) pendingShareActivationForShareIdentifier:completion:]
- -[PKPaymentWebServiceLocalProxyTargetDevice allPaymentApplicationUsageSummaries]
- -[PKPaymentWebServiceRemoteProxyTargetDevice allPaymentApplicationUsageSummariesWithCompletion:]
- -[PKPaymentWebServiceTargetDevice allPaymentApplicationUsageSummaries]
- -[PKPaymentWebServiceTargetDevice carKeyGetPretrackRequestForKeyWithInvitationIdentifier:completion:]
- -[PKRemoteNetworkPaymentHandoffConfiguration setShowDeviceGlyph:]
- -[PKRemoteNetworkPaymentHandoffConfiguration showDeviceGlyph]
- -[PKRemoteNetworkPaymentHandoffStageConfiguration customGlyphName]
- -[PKRemoteNetworkPaymentHandoffStageConfiguration glyphPointSize]
- -[PKRemoteNetworkPaymentHandoffStageConfiguration glyphWeight]
- -[PKRemoteNetworkPaymentHandoffStageConfiguration setCustomGlyphName:]
- -[PKRemoteNetworkPaymentHandoffStageConfiguration setGlyphPointSize:]
- -[PKRemoteNetworkPaymentHandoffStageConfiguration setGlyphWeight:]
- GCC_except_table213
- GCC_except_table225
- GCC_except_table228
- GCC_except_table253
- GCC_except_table279
- GCC_except_table287
- GCC_except_table290
- GCC_except_table301
- GCC_except_table315
- GCC_except_table322
- GCC_except_table327
- GCC_except_table332
- GCC_except_table339
- GCC_except_table344
- GCC_except_table368
- GCC_except_table377
- GCC_except_table381
- GCC_except_table399
- GCC_except_table415
- GCC_except_table476
- GCC_except_table484
- GCC_except_table489
- GCC_except_table497
- GCC_except_table543
- GCC_except_table545
- GCC_except_table549
- GCC_except_table553
- GCC_except_table557
- GCC_except_table559
- GCC_except_table568
- GCC_except_table583
- GCC_except_table601
- GCC_except_table690
- GCC_except_table734
- GCC_except_table742
- GCC_except_table778
- GCC_except_table896
- _CFStringConvertEncodingToIANACharSetName
- _OBJC_CLASS_$_DAKeyInvitationRequestConfig
- _OBJC_CLASS_$_PKPassFeaturedActionTileBuilder
- _OBJC_CLASS_$_PKPassSharePendingActivation
- _OBJC_IVAR_$_PKExistingCardAuthorizationRequestMessage._groupsBySessionIdentifier
- _OBJC_IVAR_$_PKPassAuxiliaryPassInformationItem._detailBackgroundImageName
- _OBJC_IVAR_$_PKPassAuxiliaryPassInformationItem._detailIconImageName
- _OBJC_IVAR_$_PKPassSharePendingActivation._isWaitingOnUserAction
- _OBJC_IVAR_$_PKPassSharePendingActivation._originalInvitation
- _OBJC_IVAR_$_PKPassSharePendingActivation._shareIdentifier
- _OBJC_IVAR_$_PKRemoteNetworkPaymentHandoffConfiguration._showDeviceGlyph
- _OBJC_IVAR_$_PKRemoteNetworkPaymentHandoffStageConfiguration._customGlyphName
- _OBJC_IVAR_$_PKRemoteNetworkPaymentHandoffStageConfiguration._glyphPointSize
- _OBJC_IVAR_$_PKRemoteNetworkPaymentHandoffStageConfiguration._glyphWeight
- _OBJC_METACLASS_$_PKPassFeaturedActionTileBuilder
- _OBJC_METACLASS_$_PKPassSharePendingActivation
- _PKCameraInputFile
- _PKCashGroupsEnabled
- _PKMobileAssetPrefetchUGPassBackgroundsAssetsActivityIdentifier
- _PKPeerPaymentFDICSignageEnabled
- _PKProvisioningExtensionCheckInCMPWACEnabled
- _PKSetCameraInputFile
- _PKURLActionShareActivateShare
- __OBJC_$_CLASS_METHODS_PKPassFeaturedActionTileBuilder
- __OBJC_$_CLASS_METHODS_PKPassSharePendingActivation
- __OBJC_$_CLASS_PROP_LIST_PKPassSharePendingActivation
- __OBJC_$_INSTANCE_METHODS_PKPassSharePendingActivation
- __OBJC_$_INSTANCE_VARIABLES_PKPassSharePendingActivation
- __OBJC_$_PROP_LIST_PKPassSharePendingActivation
- __OBJC_CLASS_PROTOCOLS_$_PKPassSharePendingActivation
- __OBJC_CLASS_RO_$_PKPassFeaturedActionTileBuilder
- __OBJC_CLASS_RO_$_PKPassSharePendingActivation
- __OBJC_METACLASS_RO_$_PKPassFeaturedActionTileBuilder
- __OBJC_METACLASS_RO_$_PKPassSharePendingActivation
- ___101-[PKAppletSubcredentialManagementSession signData:auth:bundleIdentifier:nonce:credential:completion:]_block_invoke
- ___101-[PKDAManager routingInformationForInvitationWithIdentifier:fromMailboxIdentifier:completionHandler:]_block_invoke
- ___101-[PKDAManager routingInformationForInvitationWithIdentifier:fromMailboxIdentifier:completionHandler:]_block_invoke_2
- ___101-[PKPaymentWebServiceTargetDevice carKeyGetPretrackRequestForKeyWithInvitationIdentifier:completion:]_block_invoke
- ___102-[PKPaymentService recordPaymentApplicationUsageForPassUniqueIdentifier:paymentApplicationIdentifier:]_block_invoke
- ___104-[PKPassLibrary hasProvisioningExtensionsWithSupportedNetworks:merchantCapabilities:issuerCountryCodes:]_block_invoke
- ___105-[PKPaymentService augmentedProductForInstallmentConfiguration:experimentDetails:feature:withCompletion:]_block_invoke
- ___107-[PKDAManager getProductPlanIdentifierRequestForInvitationWithIdentifier:fromMailboxIdentifier:completion:]_block_invoke
- ___107-[PKDAManager getProductPlanIdentifierRequestForInvitationWithIdentifier:fromMailboxIdentifier:completion:]_block_invoke_2
- ___108-[PKAppletSubcredentialSharingSession retryActivationCodeForCredentialIdentifier:activationCode:completion:]_block_invoke
- ___121-[PKDAManager handleOutstandingMessage:subcredentialIdentifier:credentialShareIdentifier:transportIdentifier:completion:]_block_invoke
- ___131-[PKAppletSubcredentialSharingSession getProductPlanIdentifierRequestForInvitationWithIdentifier:fromMailboxIdentifier:completion:]_block_invoke
- ___152-[PKDAManager acceptCrossPlatformInvitationWithIdentifier:transportChannelIdentifier:activationCode:encryptedProductPlanIdentifierContainer:completion:]_block_invoke
- ___152-[PKDAManager acceptCrossPlatformInvitationWithIdentifier:transportChannelIdentifier:activationCode:encryptedProductPlanIdentifierContainer:completion:]_block_invoke_2
- ___152-[PKDAManager acceptCrossPlatformInvitationWithIdentifier:transportChannelIdentifier:activationCode:encryptedProductPlanIdentifierContainer:completion:]_block_invoke_3
- ___176-[PKAppletSubcredentialSharingSession acceptCrossPlatformInvitationWithIdentifier:transportChannelIdentifier:activationCode:encryptedProductPlanIdentifierContainer:completion:]_block_invoke
- ___55-[PKPaymentService allPaymentApplicationUsageSummaries]_block_invoke
- ___59-[PKPassLibrary signData:withSecureElementPass:completion:]_block_invoke
- ___74-[PKDAManager signData:auth:bundleIdentifier:nonce:credential:completion:]_block_invoke
- ___74-[PKDAManager signData:auth:bundleIdentifier:nonce:credential:completion:]_block_invoke_2
- ___79-[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:]_block_invoke
- ___80-[PKPaymentWebServiceLocalProxyTargetDevice allPaymentApplicationUsageSummaries]_block_invoke
- ___81-[PKPaymentService(Sharing) pendingShareActivationForShareIdentifier:completion:]_block_invoke
- ___84-[PKDAManager retryActivationCodeForCredentialIdentifier:activationCode:completion:]_block_invoke
- ___84-[PKDAManager retryActivationCodeForCredentialIdentifier:activationCode:completion:]_block_invoke_2
- ___87-[PKDAManager startShareAcceptanceFlowWithInvitation:fromMailboxIdentifier:completion:]_block_invoke
- ___89-[PKDAManager setTransportChannelIdentifier:forCredential:forCredentialShare:completion:]_block_invoke
- ___89-[PKDAManager setTransportChannelIdentifier:forCredential:forCredentialShare:completion:]_block_invoke_2
- ___block_descriptor_40_e8_32bs_e39_v32?0"NSData"8"NSData"16"NSError"24ls32l8
- ___block_descriptor_48_e8_32bs40bs_e39_v32?0"NSData"8"NSData"16"NSError"24ls32l8s40l8
- ___block_descriptor_48_e8_32s40bs_e38_v16?0"PKPassSharePendingActivation"8ls40l8s32l8
- ___block_descriptor_56_e8_32s40bs48bs_e70_v32?0"DACarKeySharingMessage"8"PKAppletSubcredential"16"NSError"24ls40l8s48l8s32l8
- ___block_descriptor_56_e8_32s40s48bs_e31_v16?0"PKAppletSubcredential"8ls48l8s32l8s40l8
- ___block_descriptor_56_e8_32s40s48bs_e8_v16?0q8ls32l8s48l8s40l8
- ___block_descriptor_57_e8_32s40bs_e8_v12?0B8ls32l8s40l8
- ___block_descriptor_64_e8_32s40s48s56bs_e54_v24?0"PKAppletSubcredentialSharingSession"8?<v?>16ls56l8s32l8s40l8s48l8
- ___block_descriptor_65_e8_32s40s48s56bs_e8_v16?0q8ls32l8s40l8s48l8s56l8
- ___block_descriptor_80_e8_32s40s48s56s64s72bs_e57_v24?0"PKAppletSubcredentialManagementSession"8?<v?>16ls32l8s40l8s48l8s56l8s64l8s72l8
- ___swift_closure_destructor.85Tm
- ___swift_memcpy400_8
- _symbolic SDy_____ypGSg s11AnyHashableV
- _symbolic SSSg8deviceId______Sg6resultt 11PassKitCore37PaymentCapabilityResultRepresentationO
- _symbolic SSSg8deviceId______Sg6resulttIeAgHr_ 11PassKitCore37PaymentCapabilityResultRepresentationO
- _symbolic SaySDyS2SGG
- _symbolic SaySDySSypGG
- _symbolic SaySDy_____ypGSgG s11AnyHashableV
- _symbolic SaySSSg8deviceId______Sg6resulttG 11PassKitCore37PaymentCapabilityResultRepresentationO
- _symbolic SaySo11PKPassFieldCG
- _symbolic SaySo9PKBarcodeCG
- _symbolic Say_____G 18AppIntentsServices0bC0O6DeviceV
- _symbolic Say_____GIeAgHr_ 18AppIntentsServices0bC0O6DeviceV
- _symbolic Say______pG 18AppIntentsServices06RemoteA17IntentDispatchingP
- _symbolic Say_____y___________ySbGGG 18AppIntentsServices0bC0O12ProgressTaskV AC08DispatchD0O AA0A19IntentSuccessResultV
- _symbolic Sb______Sg_____y___________ySbGGSgt 11PassKitCore28StartRemotePaymentDispatcherC15ConnectedDeviceO 18AppIntentsServices0kL0O12ProgressTaskV AH08DispatchM0O AF0J19IntentSuccessResultV
- _symbolic Sb______Sg_____y___________ySbGGSgtIeAgHr_ 11PassKitCore28StartRemotePaymentDispatcherC15ConnectedDeviceO 18AppIntentsServices0kL0O12ProgressTaskV AH08DispatchM0O AF0J19IntentSuccessResultV
- _symbolic Sb______Sg_____y___________ySbGGSgtSg 11PassKitCore28StartRemotePaymentDispatcherC15ConnectedDeviceO 18AppIntentsServices0kL0O12ProgressTaskV AH08DispatchM0O AF0J19IntentSuccessResultV
- _symbolic ScTySay_____G_____G 18AppIntentsServices0bC0O6DeviceV s5NeverO
- _symbolic So11PKPassFieldCSg
- _symbolic _____ 10FinanceKit16ScheduledPaymentV
- _symbolic _____ 11PassKitCore09ExtractedA9GeneratorV
- _symbolic _____ 11PassKitCore09ExtractedA9GeneratorV10ParsedDate33_0BAD796060CE332F313D69D22CDC93EELLO
- _symbolic _____Sg 10FinanceKit16ScheduledPaymentV6StatusO
- _symbolic _____Sg 10Foundation6LocaleV
- _symbolic _____Sg 11PassKitCore09ExtractedA6FieldsV
- _symbolic _____Sg 11PassKitCore09ExtractedA9GeneratorV10ParsedDate33_0BAD796060CE332F313D69D22CDC93EELLO
- _symbolic _____Sg_ABt 10FinanceKit16ScheduledPaymentV6StatusO
- _symbolic _____Sg_ABt 11PassKitCore09ExtractedA6FieldsV
- _symbolic ______pSgSbIeggy_ s5ErrorP
- _symbolic _____ySDyS2SGG s23_ContiguousArrayStorageC
- _symbolic _____ySDySSypGG s23_ContiguousArrayStorageC
- _symbolic _____ySDy_____ypGSgG s23_ContiguousArrayStorageC s11AnyHashableV
- _symbolic _____ySSSg8deviceId______Sg6resulttG s23_ContiguousArrayStorageC 11PassKitCore37PaymentCapabilityResultRepresentationO
- _symbolic _____ySSSg8deviceId______Sg6resultt_G ScG8IteratorV 11PassKitCore37PaymentCapabilityResultRepresentationO
- _symbolic _____ySb______Sg_____y___________ySbGGSgt_G ScG8IteratorV 11PassKitCore28StartRemotePaymentDispatcherC15ConnectedDeviceO 18AppIntentsServices0lM0O12ProgressTaskV AJ08DispatchN0O AH0K19IntentSuccessResultV
- _symbolic _____ySo11PKPassFieldCSgG s23_ContiguousArrayStorageC
- _symbolic _____y_____G s23_ContiguousArrayStorageC 11PassKitCore09ExtractedD6FieldsV7BarcodeV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 18AppIntentsServices0eF0O6DeviceV
- _symbolic _____y_____GSg 18AppIntentsServices0A19IntentSuccessResultV s5NeverO
- _symbolic _____y______G 10Foundation20PredicateExpressionsO10NilLiteralV 10FinanceKit16ScheduledPaymentV6StatusO
- _symbolic _____y______G 10Foundation20PredicateExpressionsO8VariableV 10FinanceKit16ScheduledPaymentV
- _symbolic _____y______QPG 10Foundation9PredicateV 10FinanceKit16ScheduledPaymentV
- _symbolic _____y______QPGSg 10Foundation9PredicateV 10FinanceKit16ScheduledPaymentV
- _symbolic _____y______SgG 10Foundation20PredicateExpressionsO5ValueV 10FinanceKit16ScheduledPaymentV6StatusO
- _symbolic _____y______pG s23_ContiguousArrayStorageC 18AppIntentsServices06RemoteD17IntentDispatchingP
- _symbolic _____y______y_Shy_____GG_____y______y______GACGG 10Foundation20PredicateExpressionsO16SequenceContainsV AC5ValueV AA4UUIDV AC7KeyPathV AC8VariableV 10FinanceKit16ScheduledPaymentV
- _symbolic _____y______y______G_____G 10Foundation20PredicateExpressionsO7KeyPathV AC8VariableV 10FinanceKit16ScheduledPaymentV AA4UUIDV
- _symbolic _____y______y______G_____SgG 10Foundation20PredicateExpressionsO7KeyPathV AC8VariableV 10FinanceKit16ScheduledPaymentV AJ6StatusO
- _symbolic _____y______y______y_Shy_____GG_____y______y______GADGG_____y______y_AGy_AJ_____SgG_____y_AOGGANy_AqCy_APGGGG 10Foundation20PredicateExpressionsO11ConjunctionV AC16SequenceContainsV AC5ValueV AA4UUIDV AC7KeyPathV AC8VariableV 10FinanceKit16ScheduledPaymentV AC11DisjunctionV AC5EqualV AR6StatusO AC10NilLiteralV
- _symbolic _____y______y______y______G_____SgG_____y_AFGG 10Foundation20PredicateExpressionsO5EqualV AC7KeyPathV AC8VariableV 10FinanceKit16ScheduledPaymentV AL6StatusO AC10NilLiteralV
- _symbolic _____y______y______y______G_____SgG_____y_AGGG 10Foundation20PredicateExpressionsO5EqualV AC7KeyPathV AC8VariableV 10FinanceKit16ScheduledPaymentV AL6StatusO AC5ValueV
- _symbolic _____y______y______y______y______G_____SgG_____y_AGGGABy_AI_____y_AHGGG 10Foundation20PredicateExpressionsO11DisjunctionV AC5EqualV AC7KeyPathV AC8VariableV 10FinanceKit16ScheduledPaymentV AN6StatusO AC10NilLiteralV AC5ValueV
CStrings:
+ "%@://%@"
+ "%@://cards/%@"
+ "******** ERROR: Using DevSE with non QA Environment - refusing to validate preconditions **********"
+ "AppleCardMultiIssuerMode"
+ "Bank Connect account %s has no externalAccountId; dropping"
+ "Bank Connect account %s is linked to a pass that no longer exists in Wallet; dropping"
+ "Continuing fetch with expired catalog"
+ "Encrypted data shorter than ECC tag length, refusing to decrypt"
+ "Encrypted data shorter than GCM tag length, refusing to decrypt"
+ "Error archiving secret: %@"
+ "Error fetching secret from Keychain: %d"
+ "Error writing secret to keychain: %d"
+ "Failed to query assets result %lu for pass backgrounds"
+ "Found %lu assets in Mobile Assets for pass backgrounds"
+ "PKAssertionTypeIdentityNotificationSuppression"
+ "PKHasSeenPeerPaymentBillSplitEducation"
+ "PKPassLibrary returned no secure-element pass list; dropping Bank Connect accounts"
+ "PKPeerPaymentDismissedGraduationEducation"
+ "PKPeerPaymentReceiptSimulatedError"
+ "Unable to fetch pass background asset %@: %lu"
+ "[%s] Fetching pretrack request for invitation identifier: %s"
+ "[%s] activeDispatch: %s already dispatched (or no active dispatch), skipping"
+ "[%s] activeDispatch: %s returned accepted=%{bool}d"
+ "[%s] activeDispatch: %s shouldNotify=%{bool}d"
+ "[%s] activeDispatch: dispatching to %s"
+ "[%s] activeDispatch: failed to dispatch payment to device: %@"
+ "[%s] activeDispatch: registerInFlight rejected (dispatch swapped), cancelling progress task"
+ "[%s] activeDispatch: skipping dispatcher with no idsIdentifier"
+ "[%s] commitPrewarm: dispatcher list emptied during prewarm, throwing noDispatcher"
+ "[%s] commitPrewarm: slot was taken over by another caller, throwing CancellationError"
+ "[%s] coordinator: timeout fired, resolving %ld waiter(s) with %s"
+ "[%s] createInitialDispatcher: cancelled mid-create"
+ "[%s] createInitialDispatcher: dispatcher has no idsIdentifier, throwing noDispatcher"
+ "[%s] createInitialDispatcher: factory returned nil, throwing noDispatcher"
+ "[%s] createInitialDispatcher: factory threw: %@"
+ "[%s] createInitialDispatcher: registered %s bundle=%s"
+ "[%s] deinit: tearing down"
+ "[%s] discovery: %s already known, skipping"
+ "[%s] discovery: %s arrived but session has ended, skipping"
+ "[%s] discovery: %s is capable, dispatching active payment if any"
+ "[%s] discovery: %s was added by a concurrent path, skipping"
+ "[%s] discovery: continuous discovery failed: %@"
+ "[%s] discovery: factory returned nil for %s"
+ "[%s] discovery: failed to create dispatcher for %s: %@"
+ "[%s] discovery: registered %s bundle=%s, prewarming"
+ "[%s] discovery: session rolled while prewarming %s, discarding result"
+ "[%s] discovery: skipping endpoint with no IDS identifier"
+ "[%s] discovery: start called while already running, no-op"
+ "[%s] discovery: starting continuous discovery"
+ "[%s] discovery: stopping continuous discovery"
+ "[%s] dispatcherInvalidated: %s"
+ "[%s] dispatcherInvalidated: %s was the last dispatcher, prewarm state cleared"
+ "[%s] endRemotePaymentPairing: end-pairing %ld dispatcher(s)"
+ "[%s] endRemotePaymentPairing: end-pairing sent to %s"
+ "[%s] endRemotePaymentPairing: end-pairing to %s failed: %@"
+ "[%s] endRemotePaymentPairing: invoked"
+ "[%s] endRemotePaymentPairing: no dispatchers to end-pair"
+ "[%s] endRemotePaymentPairing: nothing to clean up, returning"
+ "[%s] prewarm: device %s capability check encountered an unknown failure"
+ "[%s] prewarm: device %s capability check failed: %s"
+ "[%s] prewarm: device %s capability check returned nil result"
+ "[%s] prewarm: device %s capability supported"
+ "[%s] prewarm: device %s does not have CheckPaymentRequestCompatibilityIntent (older OS), assuming supported"
+ "[%s] prewarm: device %s does not have the remote network payment feature enabled"
+ "[%s] prewarm: device %s does not support the required payment request version"
+ "[%s] prewarm: device %s has biometrics locked out and cannot authenticate"
+ "[%s] prewarm: device %s has no compatible payment cards"
+ "[%s] prewarm: pruning incapable dispatcher %s"
+ "[%s] remoteDeviceContext: unsupported companion device type: %s, defaulting to com.apple.Passbook"
+ "[%s] startPrewarming: complete anyResponded=%{bool}d anyCanPay=%{bool}d remainingDispatchers=%ld"
+ "[%s] startPrewarming: invoked supportTransientErrors=%{bool}d deviceFilter=%s"
+ "[%s] startPrewarming: multi-device prewarm failed: %@"
+ "[%s] startPrewarming: notifying delegate of completion"
+ "[%s] startPrewarming: single-device prewarm failed: %@"
+ "[%s] startPrewarming: slot already claimed, returning"
+ "[%s] startPrewarming: throwing %s"
+ "[%s] startPrewarming: throwing prewarmFailed (no device responded)"
+ "[%s] startRemotePayment: invoked paymentType=%s"
+ "[%s] startRemotePayment: not prewarmed, returning"
+ "[%s] startRemotePayment: swapped active dispatch, fanning out to %ld dispatcher(s)"
+ "[%s] startRemotePayment: throwing noDispatcher (dispatcher list empty)"
+ "[INTERNAL] Dev-keyed Secure Element on non-QA environment (\"%@\"). Switch to a QA env or use a production-keyed device."
+ "addMoneyPresented"
+ "addTip"
+ "addTipAlert"
+ "balanceRefreshed"
+ "biometricsLockedOut"
+ "bundleSessionID"
+ "customTax"
+ "customTip"
+ "destinationDeviceName"
+ "destinationDeviceName: '%@'; "
+ "destinationDeviceType"
+ "destinationDeviceType: '%@'; "
+ "detailBackgroundImageResource"
+ "detailBackgroundImageScale"
+ "detailIconImageResource"
+ "detailIconImageScale"
+ "endRemotePaymentPairing"
+ "featureNotSupported"
+ "hostApplicationName"
+ "hostBundleIdentifier"
+ "issuerMigration"
+ "itemSelect"
+ "itemUpdate"
+ "loadingScreen"
+ "lockUnlock"
+ "missing invitation identifier on subcredential for pretrack request"
+ "noTax"
+ "noTip"
+ "openTerms"
+ "passKeyGenerationFailed"
+ "passPayloadDigestionFailed"
+ "passPayloadDownloadFailed"
+ "passRegisterFailed"
+ "passUpdateNotificationReceived"
+ "peerPaymentFlowType"
+ "piiTokenDeleteCalled"
+ "piiTokenRetrievalCalled"
+ "presetTax"
+ "presetTip"
+ "provisioningTerms"
+ "remoteDeviceType"
+ "remoteNetworkRequestHostApplicationIdentifier"
+ "remoteNetworkRequestHostApplicationName"
+ "remoteNetworkRequestHostBundleIdentifier"
+ "retake"
+ "serviceUnavailablePeriod"
+ "serviceUnavailablePeriod: '%@'; "
+ "shouldShowWalletInSettingsWithApplePaySupportInformation - settings should show returned: %{public}@ (daemonIsAvailable: %{public}@ or hasPaymentPasses: %{public}@) isDeletedByUser: %{public}@ supported in current region (%{public}@) returned: %{public}@ (hasPaymentPasses: %{public}@ or canAddPaymentPasses: %{public}@) error: %@"
+ "splitRequest"
+ "splitSend"
+ "startPrewarming"
+ "startRemotePayment"
+ "syncedToKeychain"
+ "topUpFailure"
+ "topUpInitiated"
+ "topUpSuccess"
+ "v16@?0@\"DAShareInitiatorResult\"8"
+ "waitForFirstCapable(timeoutSeconds:)"
- "%s got provisioning extensions: %d"
- "%s returned on capability check: InstantFundsOut"
- "CashFDICSignage"
- "CashGroups"
- "Contactless Interface Could Not Stop Transaction with Error %@"
- "Device discovery failed during payment intent dispatch: %@"
- "Discovery devices count: %ld"
- "Error writing secret information to keychain: %@"
- "Failed to dispatch payment to device: %@"
- "Failed to get session to sign with"
- "FestivalTemplateBackground"
- "Finished prefetch of UG Pass background assets with success %ld"
- "Generate Pass Failure: failed to find pass template"
- "Generate Pass Failure: failed to init PKPlaceholderPassGenerator"
- "Generate Pass Failure: failure to handle temporary directory with error %@"
- "Generate Pass Failure: generator failed to generate pass"
- "GiftCardTemplateBackground"
- "KML returned 'friend not ready for passcode' error. Ignoring error so that call and KML both think they are waiting on the sender."
- "MembershipTemplateBackground"
- "Missing daEncryptedProductPlanIdentifierContainer"
- "Missing originator IDS handle while creating invitation request"
- "Missing session handle while creating invitation request"
- "PASS_ACTION_ADD_TO_BALANCE_TITLE"
- "PASS_ACTION_BOOK_AN_APPOINTMENT_TITLE"
- "PASS_ACTION_BOOK_A_CAR_TITLE"
- "PASS_ACTION_BOOK_A_FLIGHT_TITLE"
- "PASS_ACTION_BOOK_A_STAY_TITLE"
- "PASS_ACTION_CALL_TITLE"
- "PASS_ACTION_FOOTER_OPEN_LINK"
- "PASS_ACTION_FOOTER_OPEN_MAPS"
- "PASS_ACTION_GO_TO_LOCATION_TITLE"
- "PASS_ACTION_LISTEN_TO_MUSIC_TITLE"
- "PASS_ACTION_ORDER_DELIVERY_OR_PICKUP_TITLE"
- "PASS_ACTION_SHOP_TITLE"
- "PASS_ACTION_VIEW_MEMBERSHIP_BENEFITS_TITLE"
- "PASS_ACTION_VIEW_OFFERS_AND_REWARDS_TITLE"
- "PASS_ACTION_VIEW_SCHEDULE_TITLE"
- "PASS_ACTION_WATCH_TRAILER_TITLE"
- "PASS_FIELD_LABEL_EVENT_ADMISSION_TYPE"
- "PASS_FIELD_LABEL_EVENT_ATTENDEE_NAME"
- "PASS_FIELD_LABEL_EVENT_END_DATE"
- "PASS_FIELD_LABEL_EVENT_LOCATION"
- "PASS_FIELD_LABEL_EVENT_NAME"
- "PASS_FIELD_LABEL_EVENT_PERFORMERS"
- "PASS_FIELD_LABEL_EVENT_SEAT"
- "PASS_FIELD_LABEL_EVENT_SEATS"
- "PASS_FIELD_LABEL_EVENT_START_DATE"
- "PASS_FIELD_LABEL_EVENT_VENUE"
- "PASS_FIELD_LABEL_GENERIC_EMAIL"
- "PASS_FIELD_LABEL_GENERIC_PHONE"
- "PASS_FIELD_LABEL_GENERIC_WEBSITE"
- "PASS_FIELD_LABEL_MEMBERSHIP_CARD_NUMBER"
- "PASS_FIELD_LABEL_MEMBERSHIP_EXPIRATION_DATE"
- "PASS_FIELD_LABEL_MEMBERSHIP_LOCATION"
- "PASS_FIELD_LABEL_MEMBERSHIP_ORIGINAL_AMOUNT"
- "PASS_FIELD_LABEL_MEMBERSHIP_PIN"
- "PASS_FIELD_LABEL_MEMBERSHIP_PROGRAM_NAME"
- "PASS_FIELD_LABEL_MEMBERSHIP_START_DATE"
- "PASS_FIELD_LABEL_MEMBERSHIP_STATUS"
- "PASS_FIELD_LABEL_MEMBER_NAME"
- "PASS_FIELD_LABEL_MEMBER_NUMBER"
- "PASS_FIELD_LABEL_MERCHANT_NAME"
- "PASS_FIELD_VALUE_EVENT_SEAT_NUMBER"
- "PASS_FIELD_VALUE_EVENT_SEAT_ROW"
- "PASS_FIELD_VALUE_EVENT_SEAT_SECTION"
- "PKAutoFillCardManager: Not returning active cards because Wallet has been deleted."
- "PKEventTypeGeneric"
- "PrefetchUGPassBackgroundsAssets"
- "Prewarm complete: anyResponded=%{bool}d anyCanPay=%{bool}d remainingDispatchers=%ld"
- "Prewarm: device %s capability check encountered an unknown failure"
- "Prewarm: device %s capability check failed: %s"
- "Prewarm: device %s capability check returned nil result"
- "Prewarm: device %s does not have CheckPaymentRequestCompatibilityIntent (older OS), assuming supported"
- "Prewarm: device %s does not support the required payment request version"
- "Prewarm: device %s has no compatible payment cards"
- "ProvisioningExtensionCheckInCMPWAC"
- "Requesting data signing for key identifier: %@"
- "Session is in invalid state for signing operation"
- "Signing response with error: %@"
- "StandardTemplateBackground"
- "USER_GENERATED_PASS_CUSTOM_DATE_FIELD_LABEL_PLACEHOLDER"
- "USER_GENERATED_PASS_CUSTOM_EVENT_ADMISSION_PLACEHOLDER"
- "USER_GENERATED_PASS_CUSTOM_METRIC_FIELD_LABEL_PLACEHOLDER"
- "USER_GENERATED_PASS_CUSTOM_METRIC_FIELD_VALUE_PLACEHOLDER"
- "USER_GENERATED_PASS_CUSTOM_ORGANIZATION_NAME_PLACEHOLDER"
- "USER_GENERATED_PASS_CUSTOM_SEAT_VALUE_PLACEHOLDER"
- "USER_GENERATED_PASS_CUSTOM_VALUE_FIELD_LABEL_PLACEHOLDER"
- "USER_GENERATED_PASS_CUSTOM_VALUE_FIELD_VALUE_PLACEHOLDER"
- "USER_GENERATED_PASS_CUSTOM_VALUE_FIELD_VALUE_PLACEHOLDER_TAP_TO_ADD_TEXT"
- "USER_GENERATED_PASS_MEMBER_NAME_VALUE_PLACEHOLDER"
- "USER_GENERATED_PASS_MEMBER_STATUS_VALUE_PLACEHOLDER"
- "USER_GENERATED_PASS_TEMPLATE_EVENT_LOCATION"
- "USER_GENERATED_PASS_TEMPLATE_MEMBERSHIP_PROGRAM"
- "USER_GENERATED_PASS_TEMPLATE_NAME_EVENT"
- "USER_GENERATED_PASS_TEMPLATE_NAME_MEMBERSHIP"
- "Unsupported companion device type: %s"
- "Wallet has been deleted, disabling showWalletSettings"
- "[%s] Fetching pretrack request for key identifier: %s"
- "_PKHasProvisioningExtensionProducts"
- "airplane.circle.fill"
- "bed.double.circle.fill"
- "building.columns.circle.fill"
- "calendar.circle.fill"
- "car.circle.fill"
- "cart.circle.fill"
- "creditcard.circle.fill"
- "customGlyphName"
- "detailBackgroundImageName"
- "detailIconImageName"
- "featuredActionTileGroup"
- "film.circle.fill"
- "generatePassFromExtractedPassFields"
- "gift.circle.fill"
- "glyphPointSize"
- "glyphWeight"
- "https://maps.apple.com/place?place-id=%@"
- "isWaitingOnUserAction"
- "isWaitingOnUserAction: '%@'; "
- "location.circle.fill"
- "music.microphone.circle.fill"
- "originalInvitation"
- "originalInvitation: '%@'; "
- "pencil.circle.fill"
- "phone.circle.fill"
- "provisioningTermsCondition"
- "rgb(12, 165, 199)"
- "rgb(220, 58, 92)"
- "rgb(224, 138, 61)"
- "rgb(255, 255, 255)"
- "shareIdentifier: '%@'; "
- "shoebox://"
- "shoebox://%@"
- "shoebox://cards/%@"
- "shouldShowWalletInSettingsWithApplePaySupportInformation - settings should show returned: %{public}@ (daemonIsAvailable: %{public}@ or hasPaymentPasses: %{public}@) supported in current region (%{public}@) returned: %{public}@ (hasPaymentPasses: %{public}@ or canAddPaymentPasses: %{public}@) error: %@"
- "showDeviceGlyph"
- "star.circle.fill"
- "userGeneratedPassTemplate"
- "v16@?0@\"PKPassSharePendingActivation\"8"
- "v32@?0@\"DACarKeySharingMessage\"8@\"PKAppletSubcredential\"16@\"NSError\"24"
- "waveform.circle.fill"
- "yyyy-MM-dd HH:mm:ss"
- "yyyy-MM-dd'T'HH:mm:ss"
```
