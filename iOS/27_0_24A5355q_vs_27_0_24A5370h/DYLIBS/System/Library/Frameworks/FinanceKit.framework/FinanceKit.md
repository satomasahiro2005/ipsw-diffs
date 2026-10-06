## FinanceKit

> `/System/Library/Frameworks/FinanceKit.framework/FinanceKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7abcac` | `0x7c3af4` | **`+0x17e48`** |
| `__DATA.__bss` | `0xd3b40` | `0xd6cd0` | **`+0x3190`** |
| `__TEXT.__const` | `0x85938` | `0x87338` | **`+0x1a00`** |
| `__AUTH_CONST.__const` | `0x444f0` | `0x45600` | **`+0x1110`** |
| `__TEXT.__swift5_fieldmd` | `0x1da08` | `0x1e2c8` | **`+0x8c0`** |
| `__TEXT.__eh_frame` | `0x37f34` | `0x38690` | **`+0x75c`** |
| `__TEXT.__swift5_reflstr` | `0x12187` | `0x128c7` | **`+0x740`** |
| `__AUTH_CONST.__objc_const` | `0x172a0` | `0x17900` | **`+0x660`** |
| `__TEXT.__unwind_info` | `0x22f90` | `0x235f0` | **`+0x660`** |
| `__TEXT.__cstring` | `0x1602e` | `0x1658e` | **`+0x560`** |
| `__DATA.__data` | `0x13fc0` | `0x143a0` | **`+0x3e0`** |
| `__TEXT.__swift5_typeref` | `0x1a7fe` | `0x1abde` | **`+0x3e0`** |
| `__DATA_CONST.__const` | `0x5f48` | `0x6248` | **`+0x300`** |
| `__TEXT.__constg_swiftt` | `0x17f80` | `0x1826c` | **`+0x2ec`** |
| `__DATA_CONST.__objc_selrefs` | `0x50e8` | `0x5308` | **`+0x220`** |
| `__TEXT.__swift5_assocty` | `0x3210` | `0x33f0` | **`+0x1e0`** |
| `__TEXT.__swift5_proto` | `0x74f8` | `0x7684` | **`+0x18c`** |
| `__TEXT.__oslogstring` | `0x9679` | `0x97f9` | **`+0x180`** |
| `__TEXT.__objc_methlist` | `0x4b04` | `0x4c44` | **`+0x140`** |
| `__TEXT.__swift_as_cont` | `0x1ebc` | `0x1f30` | **`+0x74`** |
| `__TEXT.__swift5_capture` | `0x2960` | `0x29c8` | **`+0x68`** |
| `__DATA.__objc_ivar` | `0x4b4` | `0x510` | **`+0x5c`** |
| `__TEXT.__swift5_types` | `0x245c` | `0x24b8` | **`+0x5c`** |
| `__DATA.__common` | `0x228` | `0x260` | **`+0x38`** |
| `__DATA_DIRTY.__data` | `0x9a60` | `0x9a90` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0xc54` | `0xc80` | **`+0x2c`** |
| `__TEXT.__swift_as_entry` | `0xbd0` | `0xbf4` | **`+0x24`** |
| `__AUTH.__data` | `0xc448` | `0xc468` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x5c8` | `0x5dc` | **`+0x14`** |
| `__AUTH.__objc_data` | `0x6718` | `0x6728` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2cc0` | `0x2cd0` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0x22c` | `0x234` | **`+0x8`** |

### Other Changes

```diff

-357.2.1.0.0
+362.0.0.0.0

-  - /usr/lib/swift/libswiftRegexBuilder.dylib

-  Functions: 49421
-  Symbols:   14822
-  CStrings:  2984
+  Functions: 50110
+  Symbols:   15009
+  CStrings:  3031
Symbols:
+ -[FKApplePayTransactionInsight amountAddedToAuthCurrencyCode]
+ -[FKApplePayTransactionInsight amountAddedToAuth]
+ -[FKApplePayTransactionInsight cardNumberSuffix]
+ -[FKApplePayTransactionInsight feesJSON]
+ -[FKApplePayTransactionInsight initWithPaymentHash:transactionDate:transactionSource:cardType:adjustmentSubtype:adjustmentSubtypeReason:merchantName:merchantRawName:industryCategory:industryCode:merchantType:merchantCountryCode:terminalIdentifier:merchantAdditionalData:paymentNetwork:isMerchantTokenTransaction:isCoarseLocation:location:merchantIdentifier:merchantRawCANL:merchantRawCity:merchantRawState:merchantRawCountry:merchantCity:merchantZip:merchantState:merchantCleanConfidenceLevel:rewardsAmount:rewardsCurrency:rewardsEligibilityReason:adamIdentifier:webURL:webMerchantIdentifier:webMerchantName:isIssuerInstallmentTransaction:issuerInstallmentManagementURL:feesJSON:subtotalAmount:subtotalCurrencyCode:amountAddedToAuth:amountAddedToAuthCurrencyCode:rewardsDetailJSON:rewardsInProgressJSON:cardNumberSuffix:transactionDeclinedReason:technologyType:topUpType:interestReassessment:isRecurring:primaryFundingSourceAmount:primaryFundingSourceCurrencyCode:secondaryFundingSourceAmount:secondaryFundingSourceCurrencyCode:secondaryFundingSourceDPANSuffix:secondaryFundingSourceType:]
+ -[FKApplePayTransactionInsight interestReassessment]
+ -[FKApplePayTransactionInsight isRecurring]
+ -[FKApplePayTransactionInsight primaryFundingSourceAmount]
+ -[FKApplePayTransactionInsight primaryFundingSourceCurrencyCode]
+ -[FKApplePayTransactionInsight rewardsDetailJSON]
+ -[FKApplePayTransactionInsight rewardsInProgressJSON]
+ -[FKApplePayTransactionInsight secondaryFundingSourceAmount]
+ -[FKApplePayTransactionInsight secondaryFundingSourceCurrencyCode]
+ -[FKApplePayTransactionInsight secondaryFundingSourceDPANSuffix]
+ -[FKApplePayTransactionInsight secondaryFundingSourceType]
+ -[FKApplePayTransactionInsight subtotalAmount]
+ -[FKApplePayTransactionInsight subtotalCurrencyCode]
+ -[FKApplePayTransactionInsight technologyType]
+ -[FKApplePayTransactionInsight topUpType]
+ -[FKApplePayTransactionInsight transactionDeclinedReason]
+ -[FKContactTransactionInsight initWithPeerPaymentCounterpartHandle:peerPaymentType:peerPaymentMemo:peerPaymentMessageReceivedDate:]
+ -[FKContactTransactionInsight peerPaymentMemo]
+ -[FKContactTransactionInsight peerPaymentMessageReceivedDate]
+ -[FKContactTransactionInsight peerPaymentType]
+ -[FKInstitution financeKitDiscoveryEnabled]
+ -[FKInstitution initWithInstitutionIdentifier:name:reconsentType:supportedAuthTypes:firstTransactionsRequestWindow:maxAgeTransactionsFirstRequest:maxAgeTransactionsRefreshRequest:maxAgeTransactionsBackgroundRefreshRequest:extensionsBundleIdentifiers:maximumNumberOfBackgroundRefreshes:numberOfRemainingBackgroundRefreshes:backgroundRefreshRetryAfterDate:lastBackgroundRefreshDate:backgroundRefreshConfirmationWindow:backgroundRefreshConfirmationExpiryWindow:multipleConsentsEnabled:termsAndConditions:problemReportingEnabled:financialLabEnabled:consentSyncingEnabled:balanceWidgetEnabled:transactionSyncingEnabled:personalizedInsightsEnabled:supportsTransactions:inAppLinkingEnabled:financeKitDiscoveryEnabled:scheduledPaymentsEnabled:acceptsNewConsents:unlinkedPassReminderInterval:consentSyncingOutdatedTokenWaitTimeout:timestampSuitableForUserDisplay:piiRedactionConfigurationCountryCodes:privacyLabels:accountMatchType:accountsLimitedToCurrency:]
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._amountAddedToAuth
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._amountAddedToAuthCurrencyCode
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._cardNumberSuffix
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._feesJSON
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._interestReassessment
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._isRecurring
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._primaryFundingSourceAmount
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._primaryFundingSourceCurrencyCode
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._rewardsDetailJSON
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._rewardsInProgressJSON
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._secondaryFundingSourceAmount
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._secondaryFundingSourceCurrencyCode
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._secondaryFundingSourceDPANSuffix
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._secondaryFundingSourceType
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._subtotalAmount
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._subtotalCurrencyCode
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._technologyType
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._topUpType
+ _OBJC_IVAR_$_FKApplePayTransactionInsight._transactionDeclinedReason
+ _OBJC_IVAR_$_FKContactTransactionInsight._peerPaymentMemo
+ _OBJC_IVAR_$_FKContactTransactionInsight._peerPaymentMessageReceivedDate
+ _OBJC_IVAR_$_FKContactTransactionInsight._peerPaymentType
+ _OBJC_IVAR_$_FKInstitution._financeKitDiscoveryEnabled
+ _TCCAccessSetForBundleIdWithOptions
+ ___swift_closure_destructor.50Tm
+ ___swift_memcpy137_8
+ _associated conformance 10FinanceKit0A5StoreC7MessageO29WalletDidForegroundCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 10FinanceKit0A5StoreC7MessageO29WalletDidForegroundCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 10FinanceKit0A5StoreC7MessageO30AuthorizeApplicationCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLOSHAASQ
+ _associated conformance 10FinanceKit0A5StoreC7MessageO30AuthorizeApplicationCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 10FinanceKit0A5StoreC7MessageO30AuthorizeApplicationCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 10FinanceKit0A5StoreC7MessageO40ForceReadOrderEmailBiomeStreamCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLOs0K3KeyAAs23CustomStringConvertible
+ _associated conformance 10FinanceKit0A5StoreC7MessageO40ForceReadOrderEmailBiomeStreamCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLOs0K3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 10FinanceKit0A5StoreC7MessageO46PrioritizeAllExtractedOrderWorkItemsCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLOs0K3KeyAAs23CustomStringConvertible
+ _associated conformance 10FinanceKit0A5StoreC7MessageO46PrioritizeAllExtractedOrderWorkItemsCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLOs0K3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 10FinanceKit18BankConnectServiceC7MessageO50InstitutionsForPrimaryAccountIdentifiersCodingKeys33_C75ACFA73ABE193C5ECAF2509A19A51ELLOSHAASQ
+ _associated conformance 10FinanceKit18BankConnectServiceC7MessageO50InstitutionsForPrimaryAccountIdentifiersCodingKeys33_C75ACFA73ABE193C5ECAF2509A19A51ELLOs0L3KeyAAs23CustomStringConvertible
+ _associated conformance 10FinanceKit18BankConnectServiceC7MessageO50InstitutionsForPrimaryAccountIdentifiersCodingKeys33_C75ACFA73ABE193C5ECAF2509A19A51ELLOs0L3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 10FinanceKit18RawBankConnectDataO11InstitutionV19ClientConfigurationV0aB18DiscoveryBehaviourV10CodingKeys33_D8221EEEC044A807CCA353F1B9385F4DLLOSHAASQ
+ _associated conformance 10FinanceKit18RawBankConnectDataO11InstitutionV19ClientConfigurationV0aB18DiscoveryBehaviourV10CodingKeys33_D8221EEEC044A807CCA353F1B9385F4DLLOs0L3KeyAAs23CustomStringConvertible
+ _associated conformance 10FinanceKit18RawBankConnectDataO11InstitutionV19ClientConfigurationV0aB18DiscoveryBehaviourV10CodingKeys33_D8221EEEC044A807CCA353F1B9385F4DLLOs0L3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 10FinanceKit25ContactTransactionInsightO15PeerPaymentTypeOSHAASQ
+ _associated conformance 10FinanceKit25ContactTransactionInsightO15PeerPaymentTypeOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV0E14DeclinedReasonOSHAASQ
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV0E14DeclinedReasonOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV11FeeItemTypeOSHAASQ
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV11FeeItemTypeOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV11RewardsItemV10CodingKeysOSHAASQ
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV11RewardsItemV10CodingKeysOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV11RewardsItemV10CodingKeysOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV14TechnologyTypeOSHAASQ
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV14TechnologyTypeOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV15RewardsItemTypeOSHAASQ
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV15RewardsItemTypeOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV16RewardsItemStateOSHAASQ
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV16RewardsItemStateOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV20RewardsItemValueUnitOSHAASQ
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV20RewardsItemValueUnitOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV26SecondaryFundingSourceTypeOSHAASQ
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV26SecondaryFundingSourceTypeOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV7FeeItemV10CodingKeysOSHAASQ
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV7FeeItemV10CodingKeysOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV7FeeItemV10CodingKeysOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV9TopUpTypeOSHAASQ
+ _associated conformance 10FinanceKit26ApplePayTransactionInsightV9TopUpTypeOs12CaseIterableAA8AllCasessAFP_Sl
+ _get_enum_tag_for_layout_string 10FinanceKit27BankConnectAccountsProviderC11StoresState33_DFAAF0A220CBE86CB324400498351B20LLO
+ _get_type_metadata 15Synchronization5MutexVy10FinanceKit27BankConnectAccountsProviderC11StoresState33_DFAAF0A220CBE86CB324400498351B20LLOG noncopyable
+ _keypath_get_selector_amountAddedToAuth
+ _keypath_get_selector_amountAddedToAuthCurrencyCode
+ _keypath_get_selector_cardNumberSuffix
+ _keypath_get_selector_feesJSON
+ _keypath_get_selector_financeKitDiscoveryEnabled
+ _keypath_get_selector_foundInMailItemObject
+ _keypath_get_selector_interestReassessment
+ _keypath_get_selector_isEligibleForAggregation
+ _keypath_get_selector_isPendingEntityResolution
+ _keypath_get_selector_isPendingFusion
+ _keypath_get_selector_isPendingNormalization
+ _keypath_get_selector_isPendingReceiptEmailLinking
+ _keypath_get_selector_isPendingReevaluation
+ _keypath_get_selector_isRecurringAppleCash
+ _keypath_get_selector_lastNotifiedOrderUpdateDate
+ _keypath_get_selector_lineItemImageObjects
+ _keypath_get_selector_peerPaymentMemo
+ _keypath_get_selector_peerPaymentMessageReceivedDate
+ _keypath_get_selector_peerPaymentTypeValue
+ _keypath_get_selector_primaryFundingSourceAmount
+ _keypath_get_selector_primaryFundingSourceCurrencyCode
+ _keypath_get_selector_rewardsDetailJSON
+ _keypath_get_selector_rewardsInProgressJSON
+ _keypath_get_selector_secondaryFundingSourceAmount
+ _keypath_get_selector_secondaryFundingSourceCurrencyCode
+ _keypath_get_selector_secondaryFundingSourceDPANSuffix
+ _keypath_get_selector_secondaryFundingSourceTypeValue
+ _keypath_get_selector_subtotalAmount
+ _keypath_get_selector_subtotalCurrencyCode
+ _keypath_get_selector_technologyTypeValue
+ _keypath_get_selector_topUpTypeValue
+ _keypath_get_selector_transactionDeclinedReasonValue
+ _symbolic SS4name_SSSg12merchantLogot
+ _symbolic Say_____G 10FinanceKit25ContactTransactionInsightO15PeerPaymentTypeO
+ _symbolic Say_____G 10FinanceKit26ApplePayTransactionInsightV0E14DeclinedReasonO
+ _symbolic Say_____G 10FinanceKit26ApplePayTransactionInsightV11FeeItemTypeO
+ _symbolic Say_____G 10FinanceKit26ApplePayTransactionInsightV11RewardsItemV
+ _symbolic Say_____G 10FinanceKit26ApplePayTransactionInsightV14TechnologyTypeO
+ _symbolic Say_____G 10FinanceKit26ApplePayTransactionInsightV15RewardsItemTypeO
+ _symbolic Say_____G 10FinanceKit26ApplePayTransactionInsightV16RewardsItemStateO
+ _symbolic Say_____G 10FinanceKit26ApplePayTransactionInsightV20RewardsItemValueUnitO
+ _symbolic Say_____G 10FinanceKit26ApplePayTransactionInsightV26SecondaryFundingSourceTypeO
+ _symbolic Say_____G 10FinanceKit26ApplePayTransactionInsightV7FeeItemV
+ _symbolic Say_____G 10FinanceKit26ApplePayTransactionInsightV9TopUpTypeO
+ _symbolic Say_____GSg 10FinanceKit26ApplePayTransactionInsightV11RewardsItemV
+ _symbolic Say_____GSg 10FinanceKit26ApplePayTransactionInsightV7FeeItemV
+ _symbolic SccySay_____G______pG 10FinanceKit19InstitutionWithPassV s5ErrorP
+ _symbolic ShySSG10messageIDs_t
+ _symbolic _____ 10FinanceKit0A5StoreC7MessageO29WalletDidForegroundCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLO
+ _symbolic _____ 10FinanceKit0A5StoreC7MessageO30AuthorizeApplicationCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLO
+ _symbolic _____ 10FinanceKit0A5StoreC7MessageO40ForceReadOrderEmailBiomeStreamCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLO
+ _symbolic _____ 10FinanceKit0A5StoreC7MessageO46PrioritizeAllExtractedOrderWorkItemsCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLO
+ _symbolic _____ 10FinanceKit18BankConnectServiceC7MessageO50InstitutionsForPrimaryAccountIdentifiersCodingKeys33_C75ACFA73ABE193C5ECAF2509A19A51ELLO
+ _symbolic _____ 10FinanceKit18RawBankConnectDataO11InstitutionV19ClientConfigurationV0aB18DiscoveryBehaviourV
+ _symbolic _____ 10FinanceKit18RawBankConnectDataO11InstitutionV19ClientConfigurationV0aB18DiscoveryBehaviourV10CodingKeys33_D8221EEEC044A807CCA353F1B9385F4DLLO
+ _symbolic _____ 10FinanceKit25ContactTransactionInsightO
+ _symbolic _____ 10FinanceKit25ContactTransactionInsightO15PeerPaymentTypeO
+ _symbolic _____ 10FinanceKit26ApplePayTransactionInsightV0E14DeclinedReasonO
+ _symbolic _____ 10FinanceKit26ApplePayTransactionInsightV11FeeItemTypeO
+ _symbolic _____ 10FinanceKit26ApplePayTransactionInsightV11RewardsItemV
+ _symbolic _____ 10FinanceKit26ApplePayTransactionInsightV11RewardsItemV10CodingKeysO
+ _symbolic _____ 10FinanceKit26ApplePayTransactionInsightV14TechnologyTypeO
+ _symbolic _____ 10FinanceKit26ApplePayTransactionInsightV15RewardsItemTypeO
+ _symbolic _____ 10FinanceKit26ApplePayTransactionInsightV16RewardsItemStateO
+ _symbolic _____ 10FinanceKit26ApplePayTransactionInsightV20RewardsItemValueUnitO
+ _symbolic _____ 10FinanceKit26ApplePayTransactionInsightV26SecondaryFundingSourceTypeO
+ _symbolic _____ 10FinanceKit26ApplePayTransactionInsightV7FeeItemV
+ _symbolic _____ 10FinanceKit26ApplePayTransactionInsightV7FeeItemV10CodingKeysO
+ _symbolic _____ 10FinanceKit26ApplePayTransactionInsightV9TopUpTypeO
+ _symbolic _____ 10FinanceKit27BankConnectAccountsProviderC11StoresState33_DFAAF0A220CBE86CB324400498351B20LLO
+ _symbolic _____ 10FinanceKit27BankConnectAccountsProviderC14ResolvedStores33_DFAAF0A220CBE86CB324400498351B20LLV
+ _symbolic _____8bundleID_SDy__________G25accountIDsWithSharingDatet 10FinanceKit16BundleIdentifierV 10Foundation4UUIDV AA16AccountStartDateV
+ _symbolic _____Sg 10FinanceKit18RawBankConnectDataO11InstitutionV19ClientConfigurationV0aB18DiscoveryBehaviourV
+ _symbolic ___________pIegor_ 10FinanceKit13CoreDataStoreC AA25BankConnectConsentStoringP
+ _symbolic _____ySSG 10FinanceKit0aB11UserDefaultV
+ _symbolic _____ySay_____GSay_____GG s15LazyMapSequenceV 10FinanceKit23ManagedOrderFulfillmentO AC0fG8LineItemC
+ _symbolic _____y_Say_____GG 10FinanceKit0A5StoreC5ReplyO AA19InstitutionWithPassV
+ _symbolic _____y_____G 12ModelCatalog24ResourceBundleIdentifierV AA20AssetBackedLLMBundleV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 10FinanceKit27BankConnectAccountsProviderC11StoresState33_DFAAF0A220CBE86CB324400498351B20LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 10FinanceKit0D5StoreC7MessageO29WalletDidForegroundCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 10FinanceKit0D5StoreC7MessageO30AuthorizeApplicationCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 10FinanceKit0D5StoreC7MessageO40ForceReadOrderEmailBiomeStreamCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 10FinanceKit0D5StoreC7MessageO46PrioritizeAllExtractedOrderWorkItemsCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 10FinanceKit18BankConnectServiceC7MessageO50InstitutionsForPrimaryAccountIdentifiersCodingKeys33_C75ACFA73ABE193C5ECAF2509A19A51ELLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 10FinanceKit18RawBankConnectDataO11InstitutionV19ClientConfigurationV0dE18DiscoveryBehaviourV10CodingKeys33_D8221EEEC044A807CCA353F1B9385F4DLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 10FinanceKit26ApplePayTransactionInsightV11RewardsItemV10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 10FinanceKit26ApplePayTransactionInsightV7FeeItemV10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 10FinanceKit0D5StoreC7MessageO29WalletDidForegroundCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 10FinanceKit0D5StoreC7MessageO30AuthorizeApplicationCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 10FinanceKit0D5StoreC7MessageO40ForceReadOrderEmailBiomeStreamCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 10FinanceKit0D5StoreC7MessageO46PrioritizeAllExtractedOrderWorkItemsCodingKeys33_5013BE85E9F3658B9690D21D4C96B924LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 10FinanceKit18BankConnectServiceC7MessageO50InstitutionsForPrimaryAccountIdentifiersCodingKeys33_C75ACFA73ABE193C5ECAF2509A19A51ELLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 10FinanceKit18RawBankConnectDataO11InstitutionV19ClientConfigurationV0dE18DiscoveryBehaviourV10CodingKeys33_D8221EEEC044A807CCA353F1B9385F4DLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 10FinanceKit26ApplePayTransactionInsightV11RewardsItemV10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 10FinanceKit26ApplePayTransactionInsightV7FeeItemV10CodingKeysO
+ _symbolic _____yc 10FinanceKit27BankConnectAccountsProviderC14ResolvedStores33_DFAAF0A220CBE86CB324400498351B20LLV
+ _type_layout_string 10FinanceKit27BankConnectAccountsProviderC11StoresState33_DFAAF0A220CBE86CB324400498351B20LLO
+ _type_layout_string 10FinanceKit27BankConnectAccountsProviderC14ResolvedStores33_DFAAF0A220CBE86CB324400498351B20LLV
- -[FKInstitution initWithInstitutionIdentifier:name:reconsentType:supportedAuthTypes:firstTransactionsRequestWindow:maxAgeTransactionsFirstRequest:maxAgeTransactionsRefreshRequest:maxAgeTransactionsBackgroundRefreshRequest:extensionsBundleIdentifiers:maximumNumberOfBackgroundRefreshes:numberOfRemainingBackgroundRefreshes:backgroundRefreshRetryAfterDate:lastBackgroundRefreshDate:backgroundRefreshConfirmationWindow:backgroundRefreshConfirmationExpiryWindow:multipleConsentsEnabled:termsAndConditions:problemReportingEnabled:financialLabEnabled:consentSyncingEnabled:balanceWidgetEnabled:transactionSyncingEnabled:personalizedInsightsEnabled:supportsTransactions:inAppLinkingEnabled:scheduledPaymentsEnabled:acceptsNewConsents:unlinkedPassReminderInterval:consentSyncingOutdatedTokenWaitTimeout:timestampSuitableForUserDisplay:piiRedactionConfigurationCountryCodes:privacyLabels:accountMatchType:accountsLimitedToCurrency:]
- _OBJC_CLASS_$_NSOrderedSet
- _symbolic SaySSG5names_SSSg12merchantLogot
- _symbolic ShySSGSg10messageIDs_t
CStrings:
+ "' is not a valid decimal amount"
+ "' is not a valid decimal value"
+ "AccountEligibleForUpcomingTransactionsByExternalID"
+ "Bank Connect endpoint overridden with URL: %{public}s."
+ "Bank Connect endpoint override is an invalid URL: %{public}s, falling back to the default URL."
+ "FINANCE_RECEIPT_LINKING"
+ "Failed to decode %s: %@"
+ "Failed to encode %s: %@"
+ "Failed to set initial query generation: %@"
+ "Fetching account eligible for upcoming transactions by external account ID."
+ "Silently %s access for %s"
+ "Trial value for supportedOrderExtractionLanguages parsed to an empty list, falling back to defaults. Raw value: %{public}s"
+ "Trial value for supportedReceiptLinkingLanguages parsed to an empty list, falling back to defaults. Raw value: %{public}s"
+ "accountSubtype indicates a BUY_NOW_PAY_LATER companion but no associatedAccountIds entry is present"
+ "amountAddedToAuth"
+ "authorizeApplication"
+ "biomeOrderEmailObjects"
+ "bundleID accountIDsWithSharingDate "
+ "cardNumberSuffix"
+ "category"
+ "currencyCode"
+ "eligibleValue"
+ "eligibleValueUnit"
+ "eligible_activity"
+ "financeKitDiscoveryBehaviour"
+ "financeKitDiscoveryEnabled"
+ "forceReadOrderEmailBiomeStream"
+ "foreignTransaction"
+ "hasEnhancedMerchantProgramIdentifier"
+ "instantWithdrawal"
+ "institutionsForPrimaryAccountIdentifiers"
+ "interestReassessment"
+ "isEligibleForAggregation"
+ "isEligibleForAggregation == true"
+ "isPendingEntityResolution"
+ "isPendingNormalization"
+ "isPendingReceiptEmailLinking"
+ "isPendingReevaluation"
+ "isRecurringAppleCash"
+ "localizedDisplayName"
+ "primaryFundingSource"
+ "prioritizeAllExtractedOrderWorkItems"
+ "programId"
+ "promotionIdentifier"
+ "promotionName"
+ "rewardsDetailJSON"
+ "rewardsInProgress"
+ "rewardsInProgressJSON"
+ "secondaryFundingSource"
+ "secondaryFundingSourceDPANSuffix"
+ "secondaryFundingSourceType"
+ "state"
+ "supportedOrderExtractionLanguages"
+ "supportedReceiptLinkingLanguages"
+ "transactionDeclinedReason"
+ "type"
+ "walletDidForeground"
- "Bank Connect endpoint overridden with URL: %s."
- "Bank Connect endpoint overridden with an invalid URL: %s, falling back to the default URL."
- "CloudBankCredential"
- "FINANCE_PHOENIX"
- "Unable to add transaction for unconnected pass because the expected consent object does not exist."
- "com.apple.fm.language.instruct_3b.wallet_receipt_linking"
- "connectivityChangeNumber"
- "currentBalance must be provided"
- "lastProcessedSequenceNumber"
- "lastVerifiedConnectivityChangeNumber"
```
