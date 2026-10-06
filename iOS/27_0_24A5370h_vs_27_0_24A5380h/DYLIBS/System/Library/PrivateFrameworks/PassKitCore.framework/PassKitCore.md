## PassKitCore

> `/System/Library/PrivateFrameworks/PassKitCore.framework/PassKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8e3394` | `0x8f7dcc` | **`+0x14a38`** |
| `__TEXT.__oslogstring` | `0x3a920` | `0x3b52f` | **`+0xc0f`** |
| `__AUTH_CONST.__const` | `0x254c8` | `0x25e18` | **`+0x950`** |
| `__AUTH_CONST.__cfstring` | `0x77ac0` | `0x781e0` | **`+0x720`** |
| `__DATA.__bss` | `0x259c8` | `0x260e8` | **`+0x720`** |
| `__DATA_DIRTY.__objc_data` | `0x57d0` | `0x5eb0` | **`+0x6e0`** |
| `__AUTH.__objc_data` | `0x228e0` | `0x222c0` | **`-0x620`** |
| `__TEXT.__const` | `0x2c950` | `0x2cf60` | **`+0x610`** |
| `__TEXT.__cstring` | `0x71b3b` | `0x720f4` | **`+0x5b9`** |
| `__TEXT.__swift5_typeref` | `0x852c` | `0x8a28` | **`+0x4fc`** |
| `__TEXT.__swift5_capture` | `0x4aec` | `0x4ddc` | **`+0x2f0`** |
| `__AUTH_CONST.__objc_const` | `0xcf2a0` | `0xcf500` | **`+0x260`** |
| `__TEXT.__unwind_info` | `0x1f710` | `0x1f960` | **`+0x250`** |
| `__DATA.__data` | `0x9e88` | `0xa0b0` | **`+0x228`** |
| `__DATA_CONST.__const` | `0x22b88` | `0x22d58` | **`+0x1d0`** |
| `__AUTH.__data` | `0x5250` | `0x5418` | **`+0x1c8`** |
| `__TEXT.__eh_frame` | `0x8718` | `0x88a8` | **`+0x190`** |
| `__TEXT.__constg_swiftt` | `0x70d8` | `0x7264` | **`+0x18c`** |
| `__TEXT.__objc_methlist` | `0x72028` | `0x72178` | **`+0x150`** |
| `__TEXT.__swift5_fieldmd` | `0x79d8` | `0x7ad0` | **`+0xf8`** |
| `__AUTH_CONST.__auth_got` | `0x2eb8` | `0x2f90` | **`+0xd8`** |
| `__TEXT.__swift5_reflstr` | `0x629d` | `0x636d` | **`+0xd0`** |
| `__DATA_CONST.__objc_selrefs` | `0x24ec0` | `0x24f58` | **`+0x98`** |
| `__DATA_CONST.__got` | `0x5310` | `0x5358` | **`+0x48`** |
| `__TEXT.__swift5_assocty` | `0xd98` | `0xde0` | **`+0x48`** |
| `__TEXT.__swift5_builtin` | `0x4b0` | `0x4ec` | **`+0x3c`** |
| `__TEXT.__swift5_proto` | `0x1378` | `0x13b0` | **`+0x38`** |
| `__TEXT.__swift5_types` | `0x7a0` | `0x7c0` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x12e8` | `0x1300` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x188` | `0x19c` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x1ac` | `0x1c0` | **`+0x14`** |
| `__DATA.__common` | `0xc39` | `0xc49` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x7294` | `0x72a4` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x3de8` | `0x3df8` | **`+0x10`** |
| `__DATA_DIRTY.__common` | `0x40` | `0x30` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x3148` | `0x3140` | **`-0x8`** |
| `__DATA_DIRTY.__data` | `0x188` | `0x180` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x3b0` | `0x3ac` | **`-0x4`** |

### Other Changes

```diff

-1682.1.0.0.0
+1686.3.0.0.0

+  - /System/Library/PrivateFrameworks/IMTransferServices.framework/IMTransferServices

-  Functions: 55024
-  Symbols:   78461
-  CStrings:  21323
+  Functions: 55281
+  Symbols:   78600
+  CStrings:  21418
Symbols:
+ +[PKAnalyticsReporter(AppleCash) reportSplitBillReceiptLoadErrorWithEventType:buttonTag:errorType:p2pContext:messagesContext:]
+ -[PKContent applySecureElementContext:]
+ -[PKEntitlementWhitelist existingPendingProvisioningAccess]
+ -[PKEntitlementWhitelist passesAdd]
+ -[PKEntitlementWhitelist siriSuggestionsAccess]
+ -[PKEventDateInfo hash]
+ -[PKEventDateInfo isEqual:]
+ -[PKExistingCardAuthorizationCredential supportsFrictionlessProvisioning]
+ -[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:]
+ -[PKExistingCardAuthorizationRequestMessage selectedCredentialCount]
+ -[PKFileDataAccessor secureElementIdentifiers]
+ -[PKFileDataAccessor setSecureElementIdentifiers:]
+ -[PKPaymentAuthorizationStateMachine _insertPendingOrderDetails]
+ -[PKPaymentPassContent applySecureElementContext:]
+ -[PKPaymentPassContent isPrecursorPass:]
+ -[PKPaymentPassContent provisioningAvailable]
+ GCC_except_table260
+ _CGImageSourceCreateThumbnailAtIndex
+ _NSURLCreationDateKey
+ _OBJC_CLASS_$_IMTransferServicesController
+ _OBJC_CLASS_$_PKPeerPaymentReceiptImageManager
+ _OBJC_IVAR_$_PKEntitlementWhitelist._existingPendingProvisioningAccess
+ _OBJC_IVAR_$_PKEntitlementWhitelist._passesAdd
+ _OBJC_IVAR_$_PKEntitlementWhitelist._siriSuggestionsAccess
+ _OBJC_IVAR_$_PKPaymentPassContent._provisioningAvailable
+ _OBJC_METACLASS_$_PKPeerPaymentReceiptImageManager
+ _PDPassesAddEntitlement
+ _PDPaymentExistingPendingProvisioningEntitlement
+ _PDPaymentSiriSuggestionsEntitlement
+ _PKAnalyticsFieldNameForUserGeneratedPassFieldKey
+ _PKAnalyticsFieldNameForUserGeneratedPassSemanticTag
+ _PKAnalyticsReportBarcodeFormatKey
+ _PKAnalyticsReportBarcodeLengthKey
+ _PKAnalyticsReportEditUserPassAddRemoveFieldsButtonTag
+ _PKAnalyticsReportEditUserPassAddRemoveFieldsPageTag
+ _PKAnalyticsReportEditUserPassBackgroundColorButtonTag
+ _PKAnalyticsReportEditUserPassCancelButtonTag
+ _PKAnalyticsReportEditUserPassChooseFromLibraryButtonTag
+ _PKAnalyticsReportEditUserPassDoneButtonTag
+ _PKAnalyticsReportEditUserPassDoneInFieldEditingModeButtonTag
+ _PKAnalyticsReportEditUserPassPageTag
+ _PKAnalyticsReportEventTypeSuccessfulFaceID
+ _PKAnalyticsReportEventTypeSuccessfulPasscode
+ _PKAnalyticsReportEventTypeSuccessfulTouchID
+ _PKAnalyticsReportEventTypeSwipeBackward
+ _PKAnalyticsReportEventTypeSwipeForward
+ _PKAnalyticsReportNumberOfAvailableCardsKey
+ _PKAnalyticsReportPassActionsAvailableKey
+ _PKAnalyticsReportPassDashboardCancelButtonTag
+ _PKAnalyticsReportPassDashboardEditPassButtonTag
+ _PKAnalyticsReportPassDashboardRemovePassButtonTag
+ _PKAnalyticsReportPassDashboardViewOriginalPhotoButtonTag
+ _PKAnalyticsReportPassLastUpdatedKey
+ _PKAnalyticsReportPassSizeClassKey
+ _PKAnalyticsReportPassTokenSubTypeKey
+ _PKAnalyticsReportPassTokenTypeKey
+ _PKAnalyticsReportPeerPaymentReceiptErrorImageProcessingNotAvailable
+ _PKAnalyticsReportPeerPaymentReceiptErrorMissingTotal
+ _PKAnalyticsReportPeerPaymentReceiptErrorOther
+ _PKAnalyticsReportPeerPaymentReceiptErrorPixelBufferConversionFailed
+ _PKAnalyticsReportPeerPaymentReceiptErrorReceiptNotFound
+ _PKAnalyticsReportPeerPaymentReceiptErrorSaliencySessionNotAvailable
+ _PKAnalyticsReportPeerPaymentReceiptErrorUnsupportedCurrency
+ _PKAnalyticsReportPeerPaymentReceiptLoadErrorPageTag
+ _PKAnalyticsReportReceiptSources
+ _PKAnalyticsReportTransactionGroupingKey
+ _PKAnalyticsReportUserPassAddedFieldNamesKey
+ _PKAnalyticsReportUserPassContentTypeEventTicket
+ _PKAnalyticsReportUserPassContentTypeGiftCard
+ _PKAnalyticsReportUserPassContentTypeMembershipCard
+ _PKAnalyticsReportUserPassContentTypeOther
+ _PKAnalyticsReportUserPassDeletedFieldNamesKey
+ _PKAnalyticsReportUserPassEditedFieldNameOthers
+ _PKAnalyticsReportUserPassEditedFieldNamesKey
+ _PKAnalyticsReportUserPassNumberOfAddedFieldsKey
+ _PKAnalyticsReportUserPassNumberOfDeletedFieldsKey
+ _PKAnalyticsReportUserPassNumberOfEditedFieldsKey
+ _PKAnalyticsSubjectForEditUserPassStyle
+ _PKCommutePlanShouldReverseLabelAndValue
+ _PKEditUserPassStyleAnalyticsDescriptor
+ _PKExistingCardAuthorizationSelectedCredentialCountKey
+ _PKHasSeenPeerPaymentBillSplitCameraGuidance
+ _PKHasSeenPeerPaymentBillSplitCameraGuidanceKey
+ _PKPaymentRequestClientAnalyticsParametersIssuerKey
+ _PKPaymentRequestClientAnalyticsParametersProductSubTypeKey
+ _PKPaymentRequestClientAnalyticsParametersTokenSubTypeKey
+ _PKPaymentRequestClientAnalyticsParametersTokenTypeKey
+ _PKPeerPaymentAccountIsParticipantGraduationRequired
+ _PKSetHasSeenPeerPaymentBillSplitCameraGuidance
+ _PKUseFakeDevicePhoneNumber
+ _PKUseFakeDevicePhoneNumberKey
+ __CLASS_METHODS_PKPeerPaymentReceiptImageManager
+ __DATA_PKPeerPaymentReceiptImageManager
+ __DATA__TtCE11PassKitCoreCSo32PKPeerPaymentReceiptImageManagerP33_408BE6E8F1385DA2E81DBA2F3F4A7F307Request
+ __INSTANCE_METHODS_PKPeerPaymentReceiptImageManager
+ __IVARS_PKPeerPaymentReceiptImageManager
+ __IVARS__TtCE11PassKitCoreCSo32PKPeerPaymentReceiptImageManagerP33_408BE6E8F1385DA2E81DBA2F3F4A7F307Request
+ __METACLASS_DATA_PKPeerPaymentReceiptImageManager
+ __METACLASS_DATA__TtCE11PassKitCoreCSo32PKPeerPaymentReceiptImageManagerP33_408BE6E8F1385DA2E81DBA2F3F4A7F307Request
+ __PROPERTIES_PKPeerPaymentReceiptImageManager
+ ___147-[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:]_block_invoke
+ ___73-[PKExistingCardAuthorizationCredential supportsFrictionlessProvisioning]_block_invoke
+ ___PKAnalyticsFieldNameForUserGeneratedPassFieldKey_block_invoke
+ ___PKAnalyticsFieldNameForUserGeneratedPassSemanticTag_block_invoke
+ ___swift_closure_destructor.121Tm
+ ___swift_closure_destructor.2Tm
+ ___swift_closure_destructor.56Tm
+ ___swift_closure_destructor.79Tm
+ ___swift_closure_destructor.98Tm
+ _associated conformance So11CFStringRefa14CoreFoundation9_CFObjectSCSH
+ _associated conformance So11CFStringRefaSHSCSQ
+ _associated conformance So16NSURLResourceKeyaSHSCSQ
+ _associated conformance So16NSURLResourceKeyas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So16NSURLResourceKeyas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _associated conformance So32PKPeerPaymentReceiptImageManagerC11PassKitCoreE04PeerbcD5ErrorO10Foundation09LocalizedJ0ACs0J0
+ _get_enum_tag_for_layout_string 11PassKitCore22MultimodalReceiptErrorO
+ _get_enum_tag_for_layout_string So32PKPeerPaymentReceiptImageManagerC11PassKitCoreE04PeerbcD5ErrorO
+ _kCGImageSourceCreateThumbnailFromImageAlways
+ _kCGImageSourceCreateThumbnailWithTransform
+ _kCGImageSourceThumbnailMaxPixelSize
+ _swift_getTupleTypeMetadata
+ _swift_getTupleTypeMetadata3
+ _symbolic SDySS_____G 11PassKitCore40ProvisioningContinuityChannelCoordinatorC14TrackedSession33_AD38C0BFE09D92233AEC7B97F0FA14EALLV
+ _symbolic Say_____G So17OS_dispatch_queueC8DispatchE10AttributesV
+ _symbolic SayySo39PKPeerPaymentMessageFileTransferDetailsCSg_AC______pSgtcG s5ErrorP
+ _symbolic Sayy_____Sg_______pSgtcG 10Foundation4DataV s5ErrorP
+ _symbolic Sayy______pSgcG s5ErrorP
+ _symbolic Sb______pSg_____SgIgygn_ s5ErrorP 10Foundation3URLV
+ _symbolic So32PKPeerPaymentReceiptImageManagerC
+ _symbolic So32PKPeerPaymentReceiptImageManagerCSgXw
+ _symbolic So32PKPeerPaymentReceiptImageManagerCSgXwz_Xx
+ _symbolic So39PKPeerPaymentMessageFileTransferDetailsCSg
+ _symbolic So39PKPeerPaymentMessageFileTransferDetailsCSgACSo7NSErrorCSgIeyByyy_
+ _symbolic So39PKPeerPaymentMessageFileTransferDetailsCSgAC______pSgIegggg_ s5ErrorP
+ _symbolic So39PKPeerPaymentMessageFileTransferDetailsCSgz_Xx
+ _symbolic So6NSDataCSgSo7NSErrorCSgIeyByy_
+ _symbolic So7NSErrorCSgIeyBy_
+ _symbolic _____ 11PassKitCore40ProvisioningContinuityChannelCoordinatorC14TrackedSession33_AD38C0BFE09D92233AEC7B97F0FA14EALLV
+ _symbolic _____ So16NSURLResourceKeya
+ _symbolic _____ So18PKRemoteDeviceTypeV
+ _symbolic _____ So32PKPeerPaymentReceiptImageManagerC11PassKitCoreE04PeerbcD5ErrorO
+ _symbolic _____ So32PKPeerPaymentReceiptImageManagerC11PassKitCoreE7Request33_408BE6E8F1385DA2E81DBA2F3F4A7F30LLC
+ _symbolic _____ So32PKPeerPaymentReceiptImageManagerC11PassKitCoreE7Request33_408BE6E8F1385DA2E81DBA2F3F4A7F30LLC6ActionO
+ _symbolic _____ So32PKPeerPaymentReceiptImageVariantV
+ _symbolic _____Sg 11PassKitCore40ProvisioningContinuityChannelCoordinatorC14TrackedSession33_AD38C0BFE09D92233AEC7B97F0FA14EALLV
+ _symbolic _____Sg So18PKRemoteDeviceTypeV
+ _symbolic _____Sg______pSgIeggg_ 10Foundation4DataV s5ErrorP
+ _symbolic ______AAt So32PKPeerPaymentReceiptImageManagerC11PassKitCoreE7Request33_408BE6E8F1385DA2E81DBA2F3F4A7F30LLC6ActionO
+ _symbolic ______SayySo39PKPeerPaymentMessageFileTransferDetailsCSg_AD______pSgtcG18completionHandlerst 10Foundation4UUIDV s5ErrorP
+ _symbolic ______So39PKPeerPaymentMessageFileTransferDetailsCSg_____Sayy_____Sg_______pSgtcG18completionHandlerst 10Foundation4UUIDV So32PKPeerPaymentReceiptImageVariantV AA4DataV s5ErrorP
+ _symbolic ___________Sayy______pSgcG18completionHandlerst 10Foundation4DataV AA4UUIDV s5ErrorP
+ _symbolic ______pSg_SSSg19additionalErrorInfot s5ErrorP
+ _symbolic ______ypt So11CFStringRefa
+ _symbolic _____ySS_____G s18_DictionaryStorageC 11PassKitCore40ProvisioningContinuityChannelCoordinatorC14TrackedSession33_AD38C0BFE09D92233AEC7B97F0FA14EALLV
+ _symbolic _____ySo39PKPeerPaymentMessageFileTransferDetailsC______pGIegg_ s6ResultOsRi_zRi0_zrlE s5ErrorP
+ _symbolic _____y_____G s11_SetStorageC So16NSURLResourceKeya
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So16NSURLResourceKeya
+ _symbolic _____y___________pG s6ResultOsRi_zRi0_zrlE 10Foundation3URLV s5ErrorP
+ _symbolic _____y___________pGIegn_ s6ResultOsRi_zRi0_zrlE 10Foundation3URLV s5ErrorP
+ _symbolic _____y______yptG s23_ContiguousArrayStorageC So11CFStringRefa
+ _symbolic _____y_____ypG s18_DictionaryStorageC So11CFStringRefa
+ _symbolic _____yySo39PKPeerPaymentMessageFileTransferDetailsCSg_AD______pSgtcG s23_ContiguousArrayStorageC s5ErrorP
+ _symbolic _____yy_____Sg_______pSgtcG s23_ContiguousArrayStorageC 10Foundation4DataV s5ErrorP
+ _symbolic _____yy______pSgcG s23_ContiguousArrayStorageC s5ErrorP
+ _type_layout_string 11PassKitCore40ProvisioningContinuityChannelCoordinatorC14TrackedSession33_AD38C0BFE09D92233AEC7B97F0FA14EALLV
+ _type_layout_string So32PKPeerPaymentReceiptImageManagerC11PassKitCoreE04PeerbcD5ErrorO
- +[PKWebServiceDocumentDeliveryFeature featureWithWebService:]
- -[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:]
- -[PKPaymentAuthorizationStateMachine _insertPendingOrderDetails:]
- -[PKPaymentAuthorizationStateMachine _insertPendingTransactionRegistration]
- -[PKPaymentRewrapRequestBase applePayMerchandisingWidgetType]
- -[PKPaymentRewrapRequestBase setApplePayMerchandisingWidgetType:]
- -[PKPaymentService(PendingProvisioning) addPendingProvisioning:]
- -[PKPaymentTransaction isUnknownNearbyPeerPayment]
- -[PKPrecursorPassCredential supportsSuperEasyProvisioning]
- -[PKWebServiceDocumentDeliveryFeature initWithDictionary:region:]
- GCC_except_table264
- GCC_except_table272
- GCC_except_table289
- _OBJC_CLASS_$_FKTrillianTransactionImporter
- _PKDocumentDeliveryEnabled
- _PKDocumentDeliveryEnabledKey
- _PKHasSeenPeerPaymentBillSplitDisclosureWarning
- _PKHasSeenPeerPaymentBillSplitDisclosureWarningKey
- _PKIsPaymentRequestTypeEligibleForDocumentDelivery
- _PKSetHasSeenPeerPaymentBillSplitDisclosureWarning
- ___123-[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:]_block_invoke
- ___64-[PKPaymentService(PendingProvisioning) addPendingProvisioning:]_block_invoke
- ___swift_closure_destructor.37Tm
- _get_type_metadata 11PassKitCore9TaskQueueC5StateV noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic SDySS_____G 11PassKitCore40ProvisioningContinuityChannelCoordinatorC7SessionO
- _symbolic _____ySS_____G s18_DictionaryStorageC 11PassKitCore40ProvisioningContinuityChannelCoordinatorC7SessionO
CStrings:
+ "   completionHandlers "
+ "  completionHandlers "
+ " completionHandlers "
+ "ELIGIBILITY_HARDWARE_NOT_SUPPORTED_ERROR_MESSAGE"
+ "ELIGIBILITY_HARDWARE_NOT_SUPPORTED_ERROR_TITLE"
+ "ELIGIBILITY_NEWER_OS_VERSION_REQUIRED_ERROR_MESSAGE"
+ "ELIGIBILITY_NEWER_OS_VERSION_REQUIRED_ERROR_TITLE"
+ "LaunchServices yielded localized app name '%@' for pid %d"
+ "Merchant session validation error: initiativeContext present but missing from signedFields"
+ "Merchant session: initiativeContext did not validate"
+ "PKHasSeenPeerPaymentBillSplitCameraGuidance"
+ "PKUseFakeDevicePhoneNumber"
+ "PeerPaymentReceiptImageManager: Cannot create CGImageSource from image data for message %s"
+ "PeerPaymentReceiptImageManager: Cannot create HEIC destination at %s"
+ "PeerPaymentReceiptImageManager: Cannot finalize HEIC destination at %s"
+ "PeerPaymentReceiptImageManager: Encountered error trying to read data from existing local file %s: %@. Proceeding to fetch from MMCS"
+ "PeerPaymentReceiptImageManager: Error: Failed to read directory contents: %@ at url: %s"
+ "PeerPaymentReceiptImageManager: Failed cleaning up thumbnail. Error: %@"
+ "PeerPaymentReceiptImageManager: Failed converting and storing regular size image for message %s. Error: %@"
+ "PeerPaymentReceiptImageManager: Failed converting and storing thumbnail for message %s. Error: %@"
+ "PeerPaymentReceiptImageManager: Failed to create thumbnail for variant %s"
+ "PeerPaymentReceiptImageManager: Failed to get cache directory for purging: %@"
+ "PeerPaymentReceiptImageManager: Failed to remove cached receipt image at url: %s with error: %@"
+ "PeerPaymentReceiptImageManager: IMTransferServicesController beginning download of file to %s"
+ "PeerPaymentReceiptImageManager: IMTransferServicesController beginning upload of file at %s"
+ "PeerPaymentReceiptImageManager: IMTransferServicesController failed to download receipt image to %s. Error: %@. Additional error info: %s"
+ "PeerPaymentReceiptImageManager: IMTransferServicesController failed to send file at %s. Error: %@. Additional error info: %s"
+ "PeerPaymentReceiptImageManager: IMTransferServicesController succeeded but one or more of the following outputs are missing: ownerID: %{bool}d, signature: %{bool}d, requestURLString: %{bool}d, encryptionKey: %{bool}d"
+ "PeerPaymentReceiptImageManager: IMTransferServicesController successfully downloaded receipt image to %s"
+ "PeerPaymentReceiptImageManager: IMTransferServicesController successfully sent file at %s"
+ "PeerPaymentReceiptImageManager: Local file not found: %s, and no fileTransferDetails provided that would allow us to fetch from MMCS."
+ "PeerPaymentReceiptImageManager: Purging %ld entries from the receipt image cache"
+ "PeerPaymentReceiptImageManager: Returning image cached locally: %s"
+ "PeerPaymentReceiptImageManager: adding pending request %s"
+ "PeerPaymentReceiptImageManager: coalescing incoming request %s with existing request %s"
+ "PeerPaymentReceiptImageManager: converting and storing image of variant %s for message %s"
+ "PeerPaymentReceiptImageManager: dequeueing next request %s"
+ "PeerPaymentReceiptImageManager: failed to initialize local storage directory. Error: %@"
+ "PeerPaymentReceiptImageManager: finished processing request %s"
+ "PeerPaymentReceiptImageManager: initialized local storage directory at %s"
+ "PeerPaymentReceiptImageManager: not dequeueing next request yet. currently processing request: %{bool}d, pendingRequests: %ld"
+ "PeerPaymentReceiptImageManager: received request %s"
+ "PeerPaymentReceiptImageManager: uploading images for message %s"
+ "PeerPaymentReceipts"
+ "Receipt total is nil"
+ "[%s] Setting brandCode from car access feature: %ld"
+ "[%s] Setting manufacturerIdentifier from terminal: %s"
+ "addRemoveFields"
+ "addedFieldName"
+ "barcodeLength"
+ "chooseFromLibrary"
+ "codeTypes"
+ "com.apple.passes.add"
+ "com.apple.payment.existing-pending-provisioning"
+ "com.apple.payment.siri-suggestions"
+ "com.apple.peerpayment.receipt-images"
+ "contactPhoneNumber"
+ "deletedFieldName"
+ "doneEditing"
+ "editPass"
+ "editedFieldName"
+ "eventAdmissionType"
+ "eventAttendeeName"
+ "eventEndDatetime"
+ "eventLocation"
+ "eventPerformerNames"
+ "eventSeats"
+ "eventStartDatetime"
+ "eventVenueName"
+ "fetch(identifier: "
+ "full_name"
+ "giftCardNumber"
+ "giftCardPin"
+ "imageProcessingNotAvailable"
+ "memberSince"
+ "membershipCard"
+ "missingTotal"
+ "monetaryAmount"
+ "numberOfAddedFields"
+ "numberOfAvailableCards"
+ "numberOfDeletedFields"
+ "numberOfEditedFields"
+ "passActionsAvailable"
+ "passLastUpdated"
+ "passSize"
+ "pixelBufferConversionFailed"
+ "provisioningAvailable"
+ "receiptLoadError"
+ "receiptNotFound"
+ "receiptSources"
+ "removePass"
+ "saliencySessionNotAvailable"
+ "selectedCredentialCount"
+ "selectedCredentialCount: '%ld'; "
+ "store(identifier: "
+ "successfulFaceID"
+ "successfulPasscode"
+ "successfulTouchID"
+ "swipeBackward"
+ "swipeForward"
+ "tokenSubType"
+ "transactionGrouping"
+ "unsupportedCurrency"
+ "upload(identifier: "
+ "viewOriginalPhoto"
- "DocumentDelivery"
- "Inserting pending transaction registration"
- "Missing webServiceURL for document delivery feature"
- "PKDocumentDeliveryEnabled"
- "PKHasSeenPeerPaymentBillSplitDisclosureWarning"
- "Springboard yielded localized app name '%@' for pid %d"
- "[%s] Setting brandCode %%ld from car access feature: %ld"
- "[%s] Setting manufacturerIdentifier %%ld from terminal: %s"
- "documentDelivery"
- "documentDeliveryLiveOn"
```
