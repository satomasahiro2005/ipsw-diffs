## PassKitCore

> `/System/Library/PrivateFrameworks/PassKitCore.framework/PassKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x915b9c` | `0x91ef24` | **`+0x9388`** |
| `__AUTH_CONST.__const` | `0x269e8` | `0x27248` | **`+0x860`** |
| `__TEXT.__cstring` | `0x73c5e` | `0x741ce` | **`+0x570`** |
| `__AUTH_CONST.__cfstring` | `0x7a140` | `0x7a620` | **`+0x4e0`** |
| `__TEXT.__oslogstring` | `0x3c80d` | `0x3cc09` | **`+0x3fc`** |
| `__TEXT.__swift5_capture` | `0x512c` | `0x543c` | **`+0x310`** |
| `__AUTH_CONST.__objc_const` | `0xd0590` | `0xd07b0` | **`+0x220`** |
| `__AUTH.__data` | `0x5828` | `0x59a8` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x23760` | `0x238c8` | **`+0x168`** |
| `__TEXT.__swift5_typeref` | `0x8c68` | `0x8da0` | **`+0x138`** |
| `__TEXT.__objc_methlist` | `0x72968` | `0x72a98` | **`+0x130`** |
| `__DATA.__bss` | `0x26758` | `0x26858` | **`+0x100`** |
| `__DATA_CONST.__objc_selrefs` | `0x25328` | `0x25420` | **`+0xf8`** |
| `__TEXT.__unwind_info` | `0x1fe20` | `0x1fee8` | **`+0xc8`** |
| `__TEXT.__const` | `0x2d6b0` | `0x2d770` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x7da0` | `0x7de0` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x2fd8` | `0x3010` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x7554` | `0x7588` | **`+0x34`** |
| `__DATA_DIRTY.__bss` | `0x1328` | `0x1358` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x661d` | `0x664d` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x7328` | `0x734c` | **`+0x24`** |
| `__DATA.__data` | `0xa2a0` | `0xa2b0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x53b0` | `0x53a0` | **`-0x10`** |
| `__TEXT.__eh_frame` | `0x8988` | `0x8978` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x3b8` | `0x3ac` | **`-0xc`** |
| `__TEXT.__swift5_proto` | `0x13e8` | `0x13f0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x1a0` | `0x198` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x1c4` | `0x1bc` | **`-0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0x1f4c` | `0x1f50` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x7f4` | `0x7f8` | **`+0x4`** |

### Other Changes

```diff

-1696.2.5.0.0
+1696.2.8.1.0

-  Functions: 55789
-  Symbols:   79126
-  CStrings:  21767
+  Functions: 55942
+  Symbols:   79224
+  CStrings:  21824
Symbols:
+ +[PKAnalyticsReporter(Attribution) isNewToWalletUser]
+ +[PKAnalyticsReporter(Attribution) reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:newToWalletUser:newToProductUser:]
+ +[PKCoreSpotlightUtilities _addNormalizedPhoneNumberForPhoneNumber:toAttributeSet:]
+ +[PKCoreSpotlightUtilities _normalizedPhoneNumberDigitsFromPhoneNumber:]
+ -[PKExistingCardAuthorizationRequestMessage contentType]
+ -[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:contentType:analyticsArchivedParentToken:]
+ -[PKPassCredentialShare isLocal]
+ -[PKPassShare isSameUnderlyingShareAs:ignoringRecipientHandle:]
+ -[PKPaymentButtonAnalytics _lock_payloadForEvent:error:]
+ -[PKPaymentButtonAnalytics _reportPayload:]
+ -[PKPaymentButtonAnalytics didRenderContent]
+ -[PKPaymentButtonAnalytics reportContentRendered]
+ -[PKPaymentPassAction isTopUpAction]
+ -[PKPaymentRemoteCredential supportsExistingCardAuthorization]
+ -[PKPaymentSetupFieldPickerItem localizedDescriptionStyle]
+ -[PKPaymentSetupFieldPickerItem localizedDescription]
+ -[PKPaymentSetupFieldPickerItem submissionConfirmationActionStyle]
+ -[PKPaymentSetupFieldPickerItem submissionConfirmationActionTitle]
+ -[PKPeerPaymentRequiredFieldsPage headerImageStyle]
+ -[PKPeerPaymentRequiredFieldsPage setHeaderImageStyle:]
+ -[PKProvisioningAnalyticsSession reportNCCCheck]
+ -[PKProvisioningAnalyticsSessionCampaignAttributionSubjectHandle reportNCCCheckWithState:]
+ -[PKProvisioningAnalyticsState campaignAttributionNewToProductUser]
+ -[PKProvisioningAnalyticsState campaignAttributionNewToWalletUser]
+ -[PKProvisioningAnalyticsState campaignAttributionReferralSource]
+ -[PKProvisioningAnalyticsState setCampaignAttributionNewToProductUser:]
+ -[PKProvisioningAnalyticsState setCampaignAttributionNewToWalletUser:]
+ -[PKSharedPassSharesController _activeUserShare]
+ -[PKSharedPassSharesController sharesCreatedByCurrentUser]
+ -[PKTransitBalanceModel displayableCommutePlanMatchingPlan:]
+ GCC_except_table104
+ _OBJC_IVAR_$_PKPaymentButtonAnalytics._didRenderContent
+ _OBJC_IVAR_$_PKPaymentButtonAnalytics._lock
+ _OBJC_IVAR_$_PKPaymentSetupFieldPickerItem._localizedDescription
+ _OBJC_IVAR_$_PKPaymentSetupFieldPickerItem._localizedDescriptionStyle
+ _OBJC_IVAR_$_PKPaymentSetupFieldPickerItem._submissionConfirmationActionStyle
+ _OBJC_IVAR_$_PKPaymentSetupFieldPickerItem._submissionConfirmationActionTitle
+ _OBJC_IVAR_$_PKPeerPaymentRequiredFieldsPage._headerImageStyle
+ _OBJC_IVAR_$_PKProvisioningAnalyticsSession._didReportNCCCheck
+ _OBJC_IVAR_$_PKProvisioningAnalyticsState._campaignAttributionNewToProductUser
+ _OBJC_IVAR_$_PKProvisioningAnalyticsState._campaignAttributionNewToWalletUser
+ _PKAggDKeyApplePayButtonErrorTypeCardArtNotDisplayed
+ _PKAggDKeyApplePayButtonErrorTypeNoEligibleCard
+ _PKAggDKeyApplePayButtonErrorTypePassImageConversionFailed
+ _PKAggDKeyApplePayButtonErrorTypePassLibraryUnavailable
+ _PKAggDKeyApplePayButtonErrorTypePaymentPassLookupFailed
+ _PKAggDKeyApplePayButtonEventTypeContentRendered
+ _PKAnalyticsReportErrorTypeHandoffPaymentFailure
+ _PKAnalyticsReportErrorTypeHandoffUserDismissed
+ _PKAnalyticsReportNewToCreditUserKey
+ _PKAnalyticsReportNewToDebitUserKey
+ _PKAnalyticsReportNewToTransitUserKey
+ _PKAnalyticsReportNewToWalletUserKey
+ _PKAnalyticsReportPeerPaymentKeyboardTapBillSplitButtonTag
+ _PKAnalyticsReportPeerPaymentKeyboardTapButtonTag
+ _PKAnalyticsReportPeerPaymentKeyboardTapOpenButtonTag
+ _PKCoreSpotlightCustomKeyNormalizedPhoneNumbers
+ _PKCurrentSecureElementPasses
+ _PKExistingCardAuthorizationContentTypeKey
+ _PKHomeAppSharingHost
+ _PKHomeAppURLScheme
+ _PKHomeAppUserLockSettingsHost
+ _PKISO23220_1_PhotoID_ResidentAddressLatinCharacter
+ _PKISO23220_1_PhotoID_ResidentState
+ _PKISO23220_1_PhotoID_ResidentStateLatinCharacter
+ _PKISO23220_1_PhotoID_ResidentStateUnicode
+ _PKISO23220_1_PhotoID_ResidentStreet
+ _PKISO23220_1_PhotoID_ResidentStreetLatinCharacter
+ _PKISO23220_1_PhotoID_ResidentStreetUnicode
+ _PKPassCredentialShareTargetDeviceIsLocal
+ _PKPaymentFieldPickerItemLocalizedDescriptionStyleKey
+ _PKPaymentFieldPickerItemSubmissionConfirmationActionStyleKey
+ _PKPaymentFieldPickerItemSubmissionConfirmationActionTitleKey
+ _PKPaymentSetupHeaderImageStyleFromString
+ _PKPeerPaymentReceiptMockingEnabled
+ _PKPendingCampaignAttributionCampaignIdentifierKey
+ _PKPendingCampaignAttributionForPassUniqueIdentifier
+ _PKPendingCampaignAttributionNewToProductUserKey
+ _PKPendingCampaignAttributionNewToWalletUserKey
+ _PKPendingCampaignAttributionProductTypeKey
+ _PKPendingCampaignAttributionReferralSourceKey
+ _PKRemovePendingCampaignAttributionForPassUniqueIdentifier
+ _PKSetLocalSecureElementPassesProvider
+ _PKSetPendingCampaignAttributionForPassUniqueIdentifier
+ _PKSharingInvitationFlowIsDeviceTransfer
+ _PKSharingSanitizedRelayURL
+ _PKUserGeneratedPassSupported
+ __DoNotUse_PassDesignerOnly_PKPassSecurePreviewContextCreateMessagesPreviewForUnsignedPass
+ ___188-[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:contentType:analyticsArchivedParentToken:]_block_invoke
+ ___48-[PKSharedPassSharesController _activeUserShare]_block_invoke
+ ___58-[PKSharedPassSharesController sharesCreatedByCurrentUser]_block_invoke
+ ___58-[PKSharedPassSharesController sharesCreatedByCurrentUser]_block_invoke_2
+ ___60-[PKTransitBalanceModel displayableCommutePlanMatchingPlan:]_block_invoke
+ ___60-[PKTransitBalanceModel displayableCommutePlanMatchingPlan:]_block_invoke_2
+ ____PKPaymentButtonAnalyticsDeviceClass_block_invoke
+ ____PKPaymentButtonAnalyticsOSVersion_block_invoke
+ ___block_descriptor_32_e21_B16?0"PKPassShare"8l
+ ___block_descriptor_40_e8_32s_e30_B16?0"PKTransitCommutePlan"8ls32l8
+ ___block_descriptor_40_e8_32s_e37_B32?0"PKTransitCommutePlan"8Q16^B24ls32l8
+ ___swift__destructor.219Tm
+ ___swift_closure_destructor.150Tm
+ ___swift_closure_destructor.159Tm
+ ___swift_closure_destructor.173Tm
+ ___swift_closure_destructor.252Tm
+ ___swift_closure_destructor.34Tm
+ ___swift_closure_destructor.41Tm
+ ___swift_closure_destructor.54Tm
+ ___swift_closure_destructor.68Tm
+ ___swift_closure_destructor.9Tm
+ _associated conformance 11PassKitCore37ProvisioningDeviceTransferContentTypeOSHAASQ
+ _generic environment 11PassKitCore25ProvisioningOperationStepRzl
+ _symbolic SDySSSo19PKPaymentCredentialCGz_Xx
+ _symbolic SS_So19PKPaymentCredentialCt
+ _symbolic Say______pG 11PassKitCore27ProvisioningOperationRunnerP
+ _symbolic SiIegd_
+ _symbolic _____ 11PassKitCore37ProvisioningDeviceTransferContentTypeO
+ _symbolic _____ySDySSSo19PKPaymentCredentialCG_____G s6ResultOsRi_zRi0_zrlE 11PassKitCore27ProvisioningContinuityErrorO
+ _symbolic _____ySDySSSo19PKPaymentCredentialCG_____GIegn_ s6ResultOsRi_zRi0_zrlE 11PassKitCore27ProvisioningContinuityErrorO
+ _symbolic _____ySS_So19PKPaymentCredentialCtG s23_ContiguousArrayStorageC
+ _symbolic _____ySbG 2os21OSAllocatedUnfairLockV
+ _symbolic _____ySb_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic x4step_______p6runnert 11PassKitCore27ProvisioningOperationRunnerP
+ _symbolic y_____ySDySSSo19PKPaymentCredentialCG_____GcSg s6ResultOsRi_zRi0_zrlE 11PassKitCore27ProvisioningContinuityErrorO
- +[PKAnalyticsReporter(Attribution) reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:]
- -[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:analyticsArchivedParentToken:]
- -[PKPaymentButtonAnalytics _recordEvent:]
- -[PKPaymentButtonAnalytics _recordEvent:withError:]
- -[PKStatefulTransferCredential serialNumber]
- -[PKStatefulTransferCredential setSerialNumber:]
- GCC_except_table64
- GCC_except_table71
- _OBJC_IVAR_$_PKStatefulTransferCredential._serialNumber
- _PKAnalyticsReportViewedLineItemKey
- _PKPassSecurePreviewContextCreateMessagesPreviewForUnsignedPass
- ___176-[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:analyticsArchivedParentToken:]_block_invoke
- ___swift__destructor.176Tm
- ___swift_closure_destructor.113Tm
- ___swift_closure_destructor.156Tm
- ___swift_closure_destructor.176Tm
- ___swift_closure_destructor.19Tm
- ___swift_closure_destructor.209Tm
- ___swift_closure_destructor.23Tm
- ___swift_closure_destructor.29Tm
- _symbolic ScTy___________pG 11PassKitCore24UnifiedCardReaderAdapterC13PrepareResultV s5ErrorP
- _symbolic Scgy___________pG 11PassKitCore24UnifiedCardReaderAdapterC13PrepareResultV s5ErrorP
- _symbolic _____Sg 11PassKitCore24UnifiedCardReaderAdapterC13PrepareResultV
- _symbolic _____ySaySo19PKPaymentCredentialCG_____G s6ResultOsRi_zRi0_zrlE 11PassKitCore27ProvisioningContinuityErrorO
- _symbolic y_____ySaySo19PKPaymentCredentialCG_____GcSg s6ResultOsRi_zRi0_zrlE 11PassKitCore27ProvisioningContinuityErrorO
CStrings:
+ "ADT source UI provider: self deallocated in _generateCryptograms"
+ "B16@?0@\"PKTransitCommutePlan\"8"
+ "B32@?0@\"PKTransitCommutePlan\"8Q16^B24"
+ "COULD_NOT_ADD_KEY_TITLE"
+ "PKPendingCampaignAttributionKey"
+ "PROVISIONING_DEVICE_TRANSFER_GENERIC_ERROR_MESSAGE"
+ "Passbook_normalizedPhoneNumbers"
+ "SHAREABLE_CREDENTIAL_ERROR_MISMATCHED_ROLE_MESSAGE"
+ "SHAREABLE_CREDENTIAL_ERROR_MISMATCHED_ROLE_TITLE"
+ "Sharing Capabilities: %{public}@ cannot share, activation state %ld and application state %ld."
+ "[%@] PKPaymentProvisioningController: skipping NCCE for FPAN credential, missing a field required by this card's issuer (expiration required: %d missing: %d, name required: %d missing: %d)"
+ "[%s] Car key destination provider: Missing pass identifiers on credential"
+ "[%s] Dropping credential %s: failed to create PKExistingCardAuthorizationCredential"
+ "[%s] Dropping credential %s: no redemption token in response"
+ "[%s] Dropping credential with no remote credential"
+ "[%s] Failed to deprovision removed pass, result %lu: %@"
+ "[%s] Failed to deprovision rolled back pass, result %lu: %@"
+ "[%s] Failed to deprovision tracked pass during teardown, result %lu: %@"
+ "[%s] ProvisioningOperationComposer: Timed out tearing down %ld step(s); continuing"
+ "[%s] Timed out deprovisioning removed passes"
+ "[%s] Timed out deprovisioning rolled back passes."
+ "appleAccount"
+ "campaignAttributionNewToProductUser"
+ "campaignAttributionNewToWalletUser"
+ "cardReadyToUse"
+ "com.apple.Home-private"
+ "com.apple.wallet.ecom.smartButtons.errorType.CardArtNotDisplayed"
+ "com.apple.wallet.ecom.smartButtons.errorType.NoEligibleCard"
+ "com.apple.wallet.ecom.smartButtons.errorType.PassImageConversionFailed"
+ "com.apple.wallet.ecom.smartButtons.errorType.PassLibraryUnavailable"
+ "com.apple.wallet.ecom.smartButtons.errorType.PaymentPassLookupFailed"
+ "com.apple.wallet.ecom.smartButtons.eventType.applePayButtonContentRendered"
+ "contentType"
+ "contentType: '%ld'; "
+ "destructive"
+ "didRenderContent"
+ "didRenderContent: '%@'; "
+ "headerImageStyle"
+ "highlighted"
+ "keyboardTap"
+ "keyboardTapBillSplit"
+ "keyboardTapOpen"
+ "localizedDescriptionStyle"
+ "nccCheck"
+ "newToCreditUser"
+ "newToDebitUser"
+ "newToProductUser"
+ "newToTransitUser"
+ "newToWalletUser"
+ "paymentFailure"
+ "resident_address_latin1"
+ "resident_state_latin1"
+ "resident_state_unicode"
+ "resident_street_latin1"
+ "resident_street_unicode"
+ "submissionConfirmationActionStyle"
+ "submissionConfirmationActionTitle"
+ "userDismissed"
+ "userLockSettings"
- "ADT source UI provider: self deallocated in _generateCrytogram"
- "viewedLineItem"
```
