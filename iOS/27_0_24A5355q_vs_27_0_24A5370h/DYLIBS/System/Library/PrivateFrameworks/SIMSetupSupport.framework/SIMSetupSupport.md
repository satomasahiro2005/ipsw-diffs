## SIMSetupSupport

> `/System/Library/PrivateFrameworks/SIMSetupSupport.framework/SIMSetupSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdb198` | `0xdf23c` | **`+0x40a4`** |
| `__TEXT.__cstring` | `0x15704` | `0x16c4a` | **`+0x1546`** |
| `__AUTH_CONST.__cfstring` | `0x9de0` | `0xa640` | **`+0x860`** |
| `__AUTH_CONST.__objc_const` | `0x4dab8` | `0x4d368` | **`-0x750`** |
| `__TEXT.__objc_methlist` | `0xbef4` | `0xc1f4` | **`+0x300`** |
| `__TEXT.__oslogstring` | `0x860f` | `0x87f4` | **`+0x1e5`** |
| `__DATA_CONST.__objc_selrefs` | `0x5b88` | `0x5d40` | **`+0x1b8`** |
| `__TEXT.__gcc_except_tab` | `0x1f88` | `0x2068` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x2e58` | `0x2ed8` | **`+0x80`** |
| `__DATA.__objc_ivar` | `0x1268` | `0x12c4` | **`+0x5c`** |
| `__AUTH.__objc_data` | `0x3570` | `0x35c0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x2090` | `0x20d8` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0xb40` | `0xb60` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x208` | `0x228` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0xf0` | `0x108` | **`+0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0x7c8` | `0x7e0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xbd8` | `0xbe0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x560` | `0x568` | **`+0x8`** |

### Other Changes

```diff

-953.0.0.0.0
+960.1.0.0.0

-  Functions: 4740
-  Symbols:   7641
-  CStrings:  2958
+  Functions: 4818
+  Symbols:   7754
+  CStrings:  3044
Symbols:
+ +[SSQuickSwitchEACSSignOutViewController _contentForFlowType:data:isDeleteESIM:needsConfirmation:]
+ +[TSFlowHelper filterForCarrierSetupItems:transferPlans:quickSwitchPlans:quickSwitchToTransferPlanMap:]
+ +[TSUtilities filterToQSOnlyAccounts:magnoliaOnlyPlans:quickSwitchToTransferPlanMap:]
+ +[TSUtilities isQuickSwitchActiveAsSecondaryForAccount:]
+ +[TSUtilities isQuickSwitchActiveForAccount:]
+ -[NSArray(CTDisplayPlan) filteredPlansForUnsupportedQSBucket]
+ -[NSMutableArray(CTQuickSwitchAccountInfo) filteredQSAccountsWithoutSODATether:transferPlanMap:]
+ -[NSString(SimSetup) stringWithFirstCharacterUppercase]
+ -[SSCardManualEntryViewController _validateEnteredInputAndDeferInstall]
+ -[SSCardManualEntryViewController enteredAddress]
+ -[SSCardManualEntryViewController enteredConfirmationCode]
+ -[SSCardManualEntryViewController enteredMatchingId]
+ -[SSCardManualEntryViewController setEnteredAddress:]
+ -[SSCardManualEntryViewController setEnteredConfirmationCode:]
+ -[SSCardManualEntryViewController setEnteredMatchingId:]
+ -[SSCellularPlanScanViewController _presentParseErrorAlertForError:]
+ -[SSCellularPlanScanViewController _validateCardDataAndDeferInstall:]
+ -[SSInstallPlanInformation setSourceErrorMessage:]
+ -[SSInstallPlanInformation sourceErrorMessage]
+ -[SSPRXQuickSwitchPrimaryCompleteViewController account]
+ -[SSPRXQuickSwitchPrimaryCompleteViewController companion]
+ -[SSPRXQuickSwitchPrimaryCompleteViewController getTitleAndSubtitleForTransferViaMagnoliaFlow]
+ -[SSPRXQuickSwitchPrimaryCompleteViewController initWithPhoneNumber:result:quickSwitchFlowType:account:secondary:companion:]
+ -[SSPRXQuickSwitchPrimaryCompleteViewController quickSwitchFlowType]
+ -[SSPRXQuickSwitchPrimaryCompleteViewController secondary]
+ -[SSPRXQuickSwitchPrimaryCompleteViewController setAccount:]
+ -[SSPRXQuickSwitchPrimaryCompleteViewController setCompanion:]
+ -[SSPRXQuickSwitchPrimaryCompleteViewController setQuickSwitchFlowType:]
+ -[SSPRXQuickSwitchPrimaryCompleteViewController setSecondary:]
+ -[SSPRXQuickSwitchPrimarySettingUpViewController initWithQuickSwitchFlowType:]
+ -[SSPRXQuickSwitchPrimarySettingUpViewController quickSwitchFlowType]
+ -[SSPRXQuickSwitchPrimarySettingUpViewController setQuickSwitchFlowType:]
+ -[SSQuickSwitchDevicePickerViewController _getDetailsForAccounts:quickSwitchToTransferPlanMap:]
+ -[SSQuickSwitchDevicePickerViewController _sortAccountsByPrimaryRoleFirst:]
+ -[SSQuickSwitchEACSContent .cxx_destruct]
+ -[SSQuickSwitchEACSContent _adviceSentenceForGroup:]
+ -[SSQuickSwitchEACSContent _confirmMessage]
+ -[SSQuickSwitchEACSContent _impactSentenceForGroup:]
+ -[SSQuickSwitchEACSContent buildConfirmAlertWithConfirmHandler:cancelHandler:]
+ -[SSQuickSwitchEACSContent detailText]
+ -[SSQuickSwitchEACSContent initWithData:isDeleteESIM:needsConfirmation:]
+ -[SSQuickSwitchEACSContent shouldShowConfirmAlert]
+ -[SSQuickSwitchEACSSignOutViewController detailTextForTesting]
+ -[SSQuickSwitchFindMyWipeContent .cxx_destruct]
+ -[SSQuickSwitchFindMyWipeContent _confirmMessage]
+ -[SSQuickSwitchFindMyWipeContent _impactSentenceForGroup:]
+ -[SSQuickSwitchFindMyWipeContent buildConfirmAlertWithConfirmHandler:cancelHandler:]
+ -[SSQuickSwitchFindMyWipeContent detailText]
+ -[SSQuickSwitchFindMyWipeContent initWithData:needsConfirmation:]
+ -[SSQuickSwitchFindMyWipeContent shouldShowConfirmAlert]
+ -[SSQuickSwitchLifeCycleData .cxx_destruct]
+ -[SSQuickSwitchLifeCycleData _knownPhoneNumbersInInfos:]
+ -[SSQuickSwitchLifeCycleData _resolveDerivedState]
+ -[SSQuickSwitchLifeCycleData groupsByRoleAndDevice]
+ -[SSQuickSwitchLifeCycleData hasMultiplePrimaryDevices]
+ -[SSQuickSwitchLifeCycleData infos]
+ -[SSQuickSwitchLifeCycleData initWithInfos:selfSerialNumber:]
+ -[SSQuickSwitchLifeCycleData knownCompanionDeviceNameForInfo:]
+ -[SSQuickSwitchLifeCycleData knownJoinedPhonesForInfos:]
+ -[SSQuickSwitchLifeCycleData knownOrJoinedPhonesForInfos:]
+ -[SSQuickSwitchLifeCycleData knownPrimaryDeviceName]
+ -[SSQuickSwitchLifeCycleData primaryInfos]
+ -[SSQuickSwitchLifeCycleData secondaryInfos]
+ -[SSQuickSwitchListViewController _getDeviceNamesForGroup:]
+ -[SSQuickSwitchListViewController _getPhoneNumberForGroup:]
+ -[SSQuickSwitchListViewController _getSubtextForGroup:]
+ -[SSQuickSwitchListViewController _getTextForGroup:]
+ -[SSQuickSwitchListViewController _isUnSelectableGroup:]
+ -[SSQuickSwitchLocalSignOutContent .cxx_destruct]
+ -[SSQuickSwitchLocalSignOutContent _confirmTitle]
+ -[SSQuickSwitchLocalSignOutContent _impactSentenceForGroup:]
+ -[SSQuickSwitchLocalSignOutContent buildConfirmAlertWithConfirmHandler:cancelHandler:]
+ -[SSQuickSwitchLocalSignOutContent detailText]
+ -[SSQuickSwitchLocalSignOutContent initWithData:needsConfirmation:]
+ -[SSQuickSwitchLocalSignOutContent shouldShowConfirmAlert]
+ -[SSQuickSwitchNoWiFiViewController initWithDelegate:otherDeviceName:]
+ -[SSQuickSwitchPrimaryEnrollmentFlow companion]
+ -[SSQuickSwitchPrimaryEnrollmentFlow setCompanion:]
+ -[SSQuickSwitchSecondaryEnrollmentFlow areAllSecondaryTwinnedNoTransferWithoutCompanion:]
+ -[SSQuickSwitchSecondaryEnrollmentFlow quickSwitchPlans]
+ -[SSQuickSwitchSecondaryEnrollmentFlow setQuickSwitchPlans:]
+ -[SSQuickSwitchSecondarySharingViewController _prepareCellInformationWithAccounts:transferPlans:]
+ -[SSQuickSwitchSecondarySharingViewController initWithAccounts:transferPlans:blockerViewNeeded:showConfirmationAlert:messageSession:quickSwitchToTransferPlanMap:delegate:]
+ -[SSQuickSwitchSecondarySharingViewController qsOptionSubtitle]
+ -[SSQuickSwitchSecondarySharingViewController qsOptionTitle]
+ -[SSQuickSwitchSecondarySharingViewController setQsOptionSubtitle:]
+ -[SSQuickSwitchSecondarySharingViewController setQsOptionTitle:]
+ -[SSQuickSwitchSecondarySharingViewController setTransferOptionSubtitle:]
+ -[SSQuickSwitchSecondarySharingViewController setTransferOptionTitle:]
+ -[SSQuickSwitchSecondarySharingViewController transferOptionSubtitle]
+ -[SSQuickSwitchSecondarySharingViewController transferOptionTitle]
+ -[TSCarrierSetupItemsFilterResult .cxx_destruct]
+ -[TSCarrierSetupItemsFilterResult carrierSetupItems]
+ -[TSCarrierSetupItemsFilterResult quickSwitchPlans]
+ -[TSCarrierSetupItemsFilterResult setCarrierSetupItems:]
+ -[TSCarrierSetupItemsFilterResult setQuickSwitchPlans:]
+ -[TSCarrierSetupItemsFilterResult setTransferPlans:]
+ -[TSCarrierSetupItemsFilterResult transferPlans]
+ -[TSCellularSetupActivatingViewController initWithPlans:skip:quickSwitchFlowType:]
+ -[TSCellularSetupActivatingViewController initWithQuickSwitchPlan:quickSwitchFlowType:]
+ -[TSCellularSetupActivatingViewController quickSwitchFlowType]
+ -[TSCellularSetupActivatingViewController setQuickSwitchFlowType:]
+ -[TSMidOperationFailureViewController initWithPlanItemError:updatePlanItem:withBackButton:forCarrier:withCarrierErrorCode:isEmbeddedInResultView:sourceErrorMessage:]
+ -[TSMultiPlanIntermediateViewController _prepareCellInformationWithPendingInstallPlans:transferPlans:carrierSetupPlans:isHiddenPlanSelectable:quickSwitchPlans:]
+ -[TSMultiPlanIntermediateViewController qsBucketSubtitle]
+ -[TSMultiPlanIntermediateViewController qsBucketTitle]
+ -[TSMultiPlanIntermediateViewController setQsBucketSubtitle:]
+ -[TSMultiPlanIntermediateViewController setQsBucketTitle:]
+ -[TSQRCodeScanFlow deferredAddress]
+ -[TSQRCodeScanFlow deferredCardData]
+ -[TSQRCodeScanFlow deferredConfirmationCode]
+ -[TSQRCodeScanFlow deferredInstallTriggered]
+ -[TSQRCodeScanFlow deferredMatchingId]
+ -[TSQRCodeScanFlow setDeferredAddress:]
+ -[TSQRCodeScanFlow setDeferredCardData:]
+ -[TSQRCodeScanFlow setDeferredConfirmationCode:]
+ -[TSQRCodeScanFlow setDeferredInstallTriggered:]
+ -[TSQRCodeScanFlow setDeferredMatchingId:]
+ -[TSQRCodeScanFlow viewControllerDidComplete:]
+ GCC_except_table129
+ GCC_except_table135
+ GCC_except_table140
+ GCC_except_table148
+ GCC_except_table149
+ GCC_except_table156
+ GCC_except_table164
+ GCC_except_table198
+ GCC_except_table201
+ GCC_except_table209
+ GCC_except_table24
+ GCC_except_table53
+ _OBJC_CLASS_$_SSQuickSwitchEACSContent
+ _OBJC_CLASS_$_SSQuickSwitchFindMyWipeContent
+ _OBJC_CLASS_$_SSQuickSwitchLifeCycleData
+ _OBJC_CLASS_$_SSQuickSwitchLocalSignOutContent
+ _OBJC_CLASS_$_TSCarrierSetupItemsFilterResult
+ _OBJC_IVAR_$_SSCardManualEntryViewController._coreTelephonyClient
+ _OBJC_IVAR_$_SSCardManualEntryViewController._enteredAddress
+ _OBJC_IVAR_$_SSCardManualEntryViewController._enteredConfirmationCode
+ _OBJC_IVAR_$_SSCardManualEntryViewController._enteredMatchingId
+ _OBJC_IVAR_$_SSInstallPlanInformation._sourceErrorMessage
+ _OBJC_IVAR_$_SSPRXQuickSwitchPrimaryCompleteViewController._account
+ _OBJC_IVAR_$_SSPRXQuickSwitchPrimaryCompleteViewController._companion
+ _OBJC_IVAR_$_SSPRXQuickSwitchPrimaryCompleteViewController._quickSwitchFlowType
+ _OBJC_IVAR_$_SSPRXQuickSwitchPrimaryCompleteViewController._secondary
+ _OBJC_IVAR_$_SSPRXQuickSwitchPrimarySettingUpViewController._quickSwitchFlowType
+ _OBJC_IVAR_$_SSQuickSwitchEACSContent._data
+ _OBJC_IVAR_$_SSQuickSwitchEACSContent._isDeleteESIM
+ _OBJC_IVAR_$_SSQuickSwitchEACSContent._needsConfirmation
+ _OBJC_IVAR_$_SSQuickSwitchEACSSignOutViewController._content
+ _OBJC_IVAR_$_SSQuickSwitchFindMyWipeContent._data
+ _OBJC_IVAR_$_SSQuickSwitchFindMyWipeContent._needsConfirmation
+ _OBJC_IVAR_$_SSQuickSwitchLifeCycleData._groupsByRoleAndDevice
+ _OBJC_IVAR_$_SSQuickSwitchLifeCycleData._hasMultiplePrimaryDevices
+ _OBJC_IVAR_$_SSQuickSwitchLifeCycleData._infos
+ _OBJC_IVAR_$_SSQuickSwitchLifeCycleData._knownPrimaryDeviceName
+ _OBJC_IVAR_$_SSQuickSwitchLifeCycleData._primaryInfos
+ _OBJC_IVAR_$_SSQuickSwitchLifeCycleData._secondaryInfos
+ _OBJC_IVAR_$_SSQuickSwitchLifeCycleData._selfSerialNumber
+ _OBJC_IVAR_$_SSQuickSwitchLocalSignOutContent._data
+ _OBJC_IVAR_$_SSQuickSwitchLocalSignOutContent._needsConfirmation
+ _OBJC_IVAR_$_SSQuickSwitchPrimaryEnrollmentFlow._companion
+ _OBJC_IVAR_$_SSQuickSwitchSecondaryEnrollmentFlow._quickSwitchPlans
+ _OBJC_IVAR_$_SSQuickSwitchSecondarySharingViewController._qsOptionSubtitle
+ _OBJC_IVAR_$_SSQuickSwitchSecondarySharingViewController._qsOptionTitle
+ _OBJC_IVAR_$_SSQuickSwitchSecondarySharingViewController._transferOptionSubtitle
+ _OBJC_IVAR_$_SSQuickSwitchSecondarySharingViewController._transferOptionTitle
+ _OBJC_IVAR_$_SSQuickSwitchSecondarySharingViewController._transferPlans
+ _OBJC_IVAR_$_TSCarrierSetupItemsFilterResult._carrierSetupItems
+ _OBJC_IVAR_$_TSCarrierSetupItemsFilterResult._quickSwitchPlans
+ _OBJC_IVAR_$_TSCarrierSetupItemsFilterResult._transferPlans
+ _OBJC_IVAR_$_TSCellularSetupActivatingViewController._quickSwitchFlowType
+ _OBJC_IVAR_$_TSMultiPlanIntermediateViewController._qsBucketSubtitle
+ _OBJC_IVAR_$_TSMultiPlanIntermediateViewController._qsBucketTitle
+ _OBJC_IVAR_$_TSQRCodeScanFlow._deferredAddress
+ _OBJC_IVAR_$_TSQRCodeScanFlow._deferredCardData
+ _OBJC_IVAR_$_TSQRCodeScanFlow._deferredConfirmationCode
+ _OBJC_IVAR_$_TSQRCodeScanFlow._deferredInstallTriggered
+ _OBJC_IVAR_$_TSQRCodeScanFlow._deferredMatchingId
+ _OBJC_METACLASS_$_SSQuickSwitchEACSContent
+ _OBJC_METACLASS_$_SSQuickSwitchFindMyWipeContent
+ _OBJC_METACLASS_$_SSQuickSwitchLifeCycleData
+ _OBJC_METACLASS_$_SSQuickSwitchLocalSignOutContent
+ _OBJC_METACLASS_$_TSCarrierSetupItemsFilterResult
+ __OBJC_$_CATEGORY_NSString_$_SimSetup
+ __OBJC_$_CLASS_METHODS_SSQuickSwitchEACSSignOutViewController
+ __OBJC_$_INSTANCE_METHODS_NSMutableArray(CTDisplayPlan|CTQuickSwitchAccountInfo)
+ __OBJC_$_INSTANCE_METHODS_NSString(SimSetup|SHA256|QRCode|PhoneNumber)
+ __OBJC_$_INSTANCE_METHODS_SSQuickSwitchEACSContent
+ __OBJC_$_INSTANCE_METHODS_SSQuickSwitchFindMyWipeContent
+ __OBJC_$_INSTANCE_METHODS_SSQuickSwitchLifeCycleData
+ __OBJC_$_INSTANCE_METHODS_SSQuickSwitchLocalSignOutContent
+ __OBJC_$_INSTANCE_METHODS_TSCarrierSetupItemsFilterResult
+ __OBJC_$_INSTANCE_METHODS_TSCellularPlanActivatingFlow(Override|TSCellularPlanManagerCacheDelegate|CoreTelephonyClientCellularPlanManagementDelegate|CoreTelephonyClientQuickSwitchEnrollmentDelegate|TSSIMSetupDelegate|TSSIMSetupFlowDelegate|Single|Consolidated|UpdatePlanInfo|InteractiveUI|SecureIntent)
+ __OBJC_$_INSTANCE_VARIABLES_SSQuickSwitchEACSContent
+ __OBJC_$_INSTANCE_VARIABLES_SSQuickSwitchFindMyWipeContent
+ __OBJC_$_INSTANCE_VARIABLES_SSQuickSwitchLifeCycleData
+ __OBJC_$_INSTANCE_VARIABLES_SSQuickSwitchLocalSignOutContent
+ __OBJC_$_INSTANCE_VARIABLES_TSCarrierSetupItemsFilterResult
+ __OBJC_$_PROP_LIST_SSQuickSwitchEACSContent
+ __OBJC_$_PROP_LIST_SSQuickSwitchFindMyWipeContent
+ __OBJC_$_PROP_LIST_SSQuickSwitchLifeCycleContent
+ __OBJC_$_PROP_LIST_SSQuickSwitchLifeCycleData
+ __OBJC_$_PROP_LIST_SSQuickSwitchLocalSignOutContent
+ __OBJC_$_PROP_LIST_TSCarrierSetupItemsFilterResult
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SSQuickSwitchLifeCycleContent
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SSQuickSwitchLifeCycleContent
+ __OBJC_$_PROTOCOL_REFS_SSQuickSwitchLifeCycleContent
+ __OBJC_CLASS_PROTOCOLS_$_SSQuickSwitchEACSContent
+ __OBJC_CLASS_PROTOCOLS_$_SSQuickSwitchFindMyWipeContent
+ __OBJC_CLASS_PROTOCOLS_$_SSQuickSwitchLocalSignOutContent
+ __OBJC_CLASS_PROTOCOLS_$_TSCellularPlanActivatingFlow(Override|TSCellularPlanManagerCacheDelegate|CoreTelephonyClientCellularPlanManagementDelegate|CoreTelephonyClientQuickSwitchEnrollmentDelegate|TSSIMSetupDelegate|TSSIMSetupFlowDelegate|Single|Consolidated|UpdatePlanInfo|InteractiveUI|SecureIntent)
+ __OBJC_CLASS_RO_$_SSQuickSwitchEACSContent
+ __OBJC_CLASS_RO_$_SSQuickSwitchFindMyWipeContent
+ __OBJC_CLASS_RO_$_SSQuickSwitchLifeCycleData
+ __OBJC_CLASS_RO_$_SSQuickSwitchLocalSignOutContent
+ __OBJC_CLASS_RO_$_TSCarrierSetupItemsFilterResult
+ __OBJC_LABEL_PROTOCOL_$_SSQuickSwitchLifeCycleContent
+ __OBJC_METACLASS_RO_$_SSQuickSwitchEACSContent
+ __OBJC_METACLASS_RO_$_SSQuickSwitchFindMyWipeContent
+ __OBJC_METACLASS_RO_$_SSQuickSwitchLifeCycleData
+ __OBJC_METACLASS_RO_$_SSQuickSwitchLocalSignOutContent
+ __OBJC_METACLASS_RO_$_TSCarrierSetupItemsFilterResult
+ __OBJC_PROTOCOL_$_SSQuickSwitchLifeCycleContent
+ ___103+[TSFlowHelper filterForCarrierSetupItems:transferPlans:quickSwitchPlans:quickSwitchToTransferPlanMap:]_block_invoke
+ ___205-[SSQuickSwitchSecondaryEnrollmentFlow initWithMessageSession:accounts:primarySerialNumber:carrierSetupItems:sourceOSVersion:sourceDeviceClass:isFirstView:quickSwitchToTransferPlanMap:quickSwitchFlowType:]_block_invoke
+ ___58-[SSQuickSwitchPrimaryEnrollmentFlow firstViewController:]_block_invoke
+ ___68-[SSCellularPlanScanViewController _presentParseErrorAlertForError:]_block_invoke
+ ___69-[SSCellularPlanScanViewController _validateCardDataAndDeferInstall:]_block_invoke
+ ___69-[SSCellularPlanScanViewController _validateCardDataAndDeferInstall:]_block_invoke_2
+ ___71-[SSCardManualEntryViewController _validateEnteredInputAndDeferInstall]_block_invoke
+ ___71-[SSCardManualEntryViewController _validateEnteredInputAndDeferInstall]_block_invoke_2
+ ___75-[SSQuickSwitchDevicePickerViewController _sortAccountsByPrimaryRoleFirst:]_block_invoke
+ ___78-[SSQuickSwitchEACSContent buildConfirmAlertWithConfirmHandler:cancelHandler:]_block_invoke
+ ___78-[SSQuickSwitchEACSContent buildConfirmAlertWithConfirmHandler:cancelHandler:]_block_invoke_2
+ ___84-[SSQuickSwitchFindMyWipeContent buildConfirmAlertWithConfirmHandler:cancelHandler:]_block_invoke
+ ___84-[SSQuickSwitchFindMyWipeContent buildConfirmAlertWithConfirmHandler:cancelHandler:]_block_invoke_2
+ ___86-[SSQuickSwitchLocalSignOutContent buildConfirmAlertWithConfirmHandler:cancelHandler:]_block_invoke
+ ___86-[SSQuickSwitchLocalSignOutContent buildConfirmAlertWithConfirmHandler:cancelHandler:]_block_invoke_2
+ ___96-[NSMutableArray(CTQuickSwitchAccountInfo) filteredQSAccountsWithoutSODATether:transferPlanMap:]_block_invoke
+ ___block_descriptor_32_e63_q24?0"CTQuickSwitchAccountInfo"8"CTQuickSwitchAccountInfo"16l
+ ___block_descriptor_40_e8_32s_e40_B24?0"CTDisplayPlan"8"NSDictionary"16ls32l8
+ ___block_descriptor_40_e8_32w_e48_v24?0"CTCellularPlanQRCodeAction"8"NSError"16lw32l8
+ ___block_descriptor_48_e8_32s40s_e25_B24?08"NSDictionary"16ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e51_B24?0"CTQuickSwitchAccountInfo"8"NSDictionary"16ls32l8s40l8
+ ___block_descriptor_48_e8_32s40w_e48_v24?0"CTCellularPlanQRCodeAction"8"NSError"16lw40l8s32l8
+ _kQuickSwitchIconKey
- +[TSSIMSetupFlow _maybeCreateSIMConfigFlowAsPreFlow:options:]
- +[TSUtilities getStringWithFirstCharacterUppercase:]
- +[TSUtilities groupHasOrphanPrimary:]
- -[SSPRXQuickSwitchPrimaryCompleteViewController initWithPhoneNumber:result:]
- -[SSPRXQuickSwitchPrimaryWebsheetIncompleteViewController .cxx_destruct]
- -[SSPRXQuickSwitchPrimaryWebsheetIncompleteViewController delegate]
- -[SSPRXQuickSwitchPrimaryWebsheetIncompleteViewController setDelegate:]
- -[SSPRXQuickSwitchPrimaryWebsheetIncompleteViewController viewDidLayoutSubviews]
- -[SSPRXQuickSwitchPrimaryWebsheetIncompleteViewController viewDidLoad]
- -[SSPRXQuickSwitchPrimaryWebsheetIncompleteViewController viewWillAppear:]
- -[SSQuickSwitchDevicePickerViewController _primaryDeviceNameExcluding:]
- -[SSQuickSwitchDevicePickerViewController selectedNewLine]
- -[SSQuickSwitchEACSSignOutViewController _buildDetailTextWithInfos:flowType:isDeleteESIM:selfSerialNumber:]
- -[SSQuickSwitchEACSSignOutViewController _carrierNameForInfos:]
- -[SSQuickSwitchEACSSignOutViewController _deviceNameForInfo:selfSerialNumber:]
- -[SSQuickSwitchEACSSignOutViewController _groupInfosByRoleAndDevice:selfSerialNumber:]
- -[SSQuickSwitchEACSSignOutViewController _isCarrierNameFallback:]
- -[SSQuickSwitchEACSSignOutViewController _isDeviceNameFallback:selfSerialNumber:]
- -[SSQuickSwitchEACSSignOutViewController _joinPhonesWithOr:]
- -[SSQuickSwitchEACSSignOutViewController _numberKeyForPrimary:flowType:isDeleteESIM:plural:deviceIsFallback:]
- -[SSQuickSwitchEACSSignOutViewController _phoneNumberForInfo:]
- -[SSQuickSwitchEACSSignOutViewController _preambleForFlowType:]
- -[SSQuickSwitchEACSSignOutViewController _scanInfos:hasPrimary:hasSecondary:primaryDeviceName:primaryDeviceIsFallback:primaryPhoneNumber:secondaryPhoneNumbers:secondaryDeviceName:secondaryDeviceIsFallback:]
- -[SSQuickSwitchEACSSignOutViewController _shouldShowConfirmAlertWithInfos:flowType:needsConfirmation:isDeleteESIM:]
- -[SSQuickSwitchEACSSignOutViewController prepare:]
- -[SSQuickSwitchEnrollmentFollowUpFlow .cxx_destruct]
- -[SSQuickSwitchEnrollmentFollowUpFlow firstViewController:]
- -[SSQuickSwitchEnrollmentFollowUpFlow firstViewController]
- -[SSQuickSwitchEnrollmentFollowUpFlow initWithPhoneNumber:]
- -[SSQuickSwitchEnrollmentFollowUpFlow isBootstrapAssertionRequired]
- -[SSQuickSwitchFollowUpOnOtherPhoneViewController .cxx_destruct]
- -[SSQuickSwitchFollowUpOnOtherPhoneViewController _doneButtonTapped]
- -[SSQuickSwitchFollowUpOnOtherPhoneViewController delegate]
- -[SSQuickSwitchFollowUpOnOtherPhoneViewController initWithPhoneNumber:]
- -[SSQuickSwitchFollowUpOnOtherPhoneViewController setDelegate:]
- -[SSQuickSwitchFollowUpOnOtherPhoneViewController viewDidLoad]
- -[SSQuickSwitchIncompleteWebsheetDecisionViewController .cxx_destruct]
- -[SSQuickSwitchIncompleteWebsheetDecisionViewController _continueButtonTapped]
- -[SSQuickSwitchIncompleteWebsheetDecisionViewController _setUpLaterButtonTapped]
- -[SSQuickSwitchIncompleteWebsheetDecisionViewController decisionDelegate]
- -[SSQuickSwitchIncompleteWebsheetDecisionViewController delegate]
- -[SSQuickSwitchIncompleteWebsheetDecisionViewController initWithPlans:skip:]
- -[SSQuickSwitchIncompleteWebsheetDecisionViewController isShown]
- -[SSQuickSwitchIncompleteWebsheetDecisionViewController prepare:]
- -[SSQuickSwitchIncompleteWebsheetDecisionViewController setDecisionDelegate:]
- -[SSQuickSwitchIncompleteWebsheetDecisionViewController setDelegate:]
- -[SSQuickSwitchIncompleteWebsheetDecisionViewController viewDidLoad]
- -[SSQuickSwitchNoWiFiViewController initWithDelegate:]
- -[SSQuickSwitchPrimaryEnrollmentFlow isSlidingWebsheetIncomplete]
- -[SSQuickSwitchPrimaryEnrollmentFlow setIsSlidingWebsheetIncomplete:]
- -[SSQuickSwitchSecondaryEnrollmentFlow accounts]
- -[SSQuickSwitchSecondaryEnrollmentFlow setAccounts:]
- -[SSQuickSwitchSecondarySharingViewController _shareOptionSubtext]
- -[SSQuickSwitchSecondarySharingViewController initWithAccounts:hasTransferPlans:blockerViewNeeded:showConfirmationAlert:messageSession:quickSwitchToTransferPlanMap:delegate:]
- -[TSActivationFlowWithSimSetupFlow _filterCarrierSetupItems:]
- -[TSCellularPlanActivatingFlow(SSQuickSwitchIncompleteWebsheetDecision) resolveIncompleteWebsheetWithFollowup:]
- -[TSCellularSetupActivatingViewController initWithPlans:skip:]
- -[TSCellularSetupActivatingViewController initWithQuickSwitchPlan:]
- -[TSMultiPlanIntermediateViewController _prepareCellInformationWithPendingInstallPlans:transferPlans:carrierSetupPlans:isHiddenPlanSelectable:]
- GCC_except_table133
- GCC_except_table137
- GCC_except_table142
- GCC_except_table150
- GCC_except_table151
- GCC_except_table158
- GCC_except_table166
- GCC_except_table200
- GCC_except_table203
- GCC_except_table215
- GCC_except_table29
- GCC_except_table56
- _OBJC_CLASS_$_SSPRXQuickSwitchPrimaryWebsheetIncompleteViewController
- _OBJC_CLASS_$_SSQuickSwitchEnrollmentFollowUpFlow
- _OBJC_CLASS_$_SSQuickSwitchFollowUpOnOtherPhoneViewController
- _OBJC_CLASS_$_SSQuickSwitchIncompleteWebsheetDecisionViewController
- _OBJC_IVAR_$_SSPRXQuickSwitchPrimaryWebsheetIncompleteViewController._delegate
- _OBJC_IVAR_$_SSQuickSwitchDevicePickerViewController._hasOrphanPrimary
- _OBJC_IVAR_$_SSQuickSwitchDevicePickerViewController._selectedNewLine
- _OBJC_IVAR_$_SSQuickSwitchEACSSignOutViewController._flowType
- _OBJC_IVAR_$_SSQuickSwitchEACSSignOutViewController._infos
- _OBJC_IVAR_$_SSQuickSwitchEACSSignOutViewController._isDeleteESIM
- _OBJC_IVAR_$_SSQuickSwitchEACSSignOutViewController._needsConfirmation
- _OBJC_IVAR_$_SSQuickSwitchEACSSignOutViewController._selfSerialNumber
- _OBJC_IVAR_$_SSQuickSwitchEACSSignOutViewController._showsConfirmAlert
- _OBJC_IVAR_$_SSQuickSwitchEnrollmentFollowUpFlow._phoneNumber
- _OBJC_IVAR_$_SSQuickSwitchFollowUpOnOtherPhoneViewController._delegate
- _OBJC_IVAR_$_SSQuickSwitchIncompleteWebsheetDecisionViewController._decisionDelegate
- _OBJC_IVAR_$_SSQuickSwitchIncompleteWebsheetDecisionViewController._delegate
- _OBJC_IVAR_$_SSQuickSwitchIncompleteWebsheetDecisionViewController._installPlans
- _OBJC_IVAR_$_SSQuickSwitchIncompleteWebsheetDecisionViewController._isShown
- _OBJC_IVAR_$_SSQuickSwitchIncompleteWebsheetDecisionViewController._skip
- _OBJC_IVAR_$_SSQuickSwitchPrimaryEnrollmentFlow._isSlidingWebsheetIncomplete
- _OBJC_IVAR_$_SSQuickSwitchSecondaryEnrollmentFlow._accounts
- _OBJC_IVAR_$_SSQuickSwitchSecondarySharingViewController._hasTransferPlans
- _OBJC_IVAR_$_TSCellularPlanActivatingFlow._isWebsheetIncomplete
- _OBJC_METACLASS_$_SSPRXQuickSwitchPrimaryWebsheetIncompleteViewController
- _OBJC_METACLASS_$_SSQuickSwitchEnrollmentFollowUpFlow
- _OBJC_METACLASS_$_SSQuickSwitchFollowUpOnOtherPhoneViewController
- _OBJC_METACLASS_$_SSQuickSwitchIncompleteWebsheetDecisionViewController
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSMutableArray_$_CTDisplayPlan
- __OBJC_$_CATEGORY_NSString_$_SHA256
- __OBJC_$_INSTANCE_METHODS_NSString(SHA256|QRCode|PhoneNumber)
- __OBJC_$_INSTANCE_METHODS_SSPRXQuickSwitchPrimaryWebsheetIncompleteViewController
- __OBJC_$_INSTANCE_METHODS_SSQuickSwitchEnrollmentFollowUpFlow
- __OBJC_$_INSTANCE_METHODS_SSQuickSwitchFollowUpOnOtherPhoneViewController
- __OBJC_$_INSTANCE_METHODS_SSQuickSwitchIncompleteWebsheetDecisionViewController
- __OBJC_$_INSTANCE_METHODS_TSCellularPlanActivatingFlow(Override|SSQuickSwitchIncompleteWebsheetDecision|TSCellularPlanManagerCacheDelegate|CoreTelephonyClientCellularPlanManagementDelegate|CoreTelephonyClientQuickSwitchEnrollmentDelegate|TSSIMSetupDelegate|TSSIMSetupFlowDelegate|Single|Consolidated|UpdatePlanInfo|InteractiveUI|SecureIntent)
- __OBJC_$_INSTANCE_VARIABLES_SSPRXQuickSwitchPrimaryWebsheetIncompleteViewController
- __OBJC_$_INSTANCE_VARIABLES_SSQuickSwitchEnrollmentFollowUpFlow
- __OBJC_$_INSTANCE_VARIABLES_SSQuickSwitchFollowUpOnOtherPhoneViewController
- __OBJC_$_INSTANCE_VARIABLES_SSQuickSwitchIncompleteWebsheetDecisionViewController
- __OBJC_$_PROP_LIST_SSPRXQuickSwitchPrimaryWebsheetIncompleteViewController
- __OBJC_$_PROP_LIST_SSQuickSwitchFollowUpOnOtherPhoneViewController
- __OBJC_$_PROP_LIST_SSQuickSwitchIncompleteWebsheetDecisionViewController
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_SSQuickSwitchIncompleteWebsheetDecisionDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_SSQuickSwitchIncompleteWebsheetDecisionDelegate
- __OBJC_$_PROTOCOL_REFS_SSQuickSwitchIncompleteWebsheetDecisionDelegate
- __OBJC_CLASS_PROTOCOLS_$_SSPRXQuickSwitchPrimaryWebsheetIncompleteViewController
- __OBJC_CLASS_PROTOCOLS_$_SSQuickSwitchFollowUpOnOtherPhoneViewController
- __OBJC_CLASS_PROTOCOLS_$_SSQuickSwitchIncompleteWebsheetDecisionViewController
- __OBJC_CLASS_PROTOCOLS_$_TSCellularPlanActivatingFlow(Override|SSQuickSwitchIncompleteWebsheetDecision|TSCellularPlanManagerCacheDelegate|CoreTelephonyClientCellularPlanManagementDelegate|CoreTelephonyClientQuickSwitchEnrollmentDelegate|TSSIMSetupDelegate|TSSIMSetupFlowDelegate|Single|Consolidated|UpdatePlanInfo|InteractiveUI|SecureIntent)
- __OBJC_CLASS_RO_$_SSPRXQuickSwitchPrimaryWebsheetIncompleteViewController
- __OBJC_CLASS_RO_$_SSQuickSwitchEnrollmentFollowUpFlow
- __OBJC_CLASS_RO_$_SSQuickSwitchFollowUpOnOtherPhoneViewController
- __OBJC_CLASS_RO_$_SSQuickSwitchIncompleteWebsheetDecisionViewController
- __OBJC_LABEL_PROTOCOL_$_SSQuickSwitchIncompleteWebsheetDecisionDelegate
- __OBJC_METACLASS_RO_$_SSPRXQuickSwitchPrimaryWebsheetIncompleteViewController
- __OBJC_METACLASS_RO_$_SSQuickSwitchEnrollmentFollowUpFlow
- __OBJC_METACLASS_RO_$_SSQuickSwitchFollowUpOnOtherPhoneViewController
- __OBJC_METACLASS_RO_$_SSQuickSwitchIncompleteWebsheetDecisionViewController
- __OBJC_PROTOCOL_$_SSQuickSwitchIncompleteWebsheetDecisionDelegate
- ___111-[TSCellularPlanActivatingFlow(SSQuickSwitchIncompleteWebsheetDecision) resolveIncompleteWebsheetWithFollowup:]_block_invoke
- ___block_descriptor_33_e17_v16?0"NSError"8l
- ___block_descriptor_56_e8_32s40s48s_e23_v16?0"UIAlertAction"8ls32l8s40l8s48l8
CStrings:
+ "%ld|%@"
+ "+[TSFlowHelper filterForCarrierSetupItems:transferPlans:quickSwitchPlans:quickSwitchToTransferPlanMap:]"
+ "+[TSUtilities filterToQSOnlyAccounts:magnoliaOnlyPlans:quickSwitchToTransferPlanMap:]"
+ "-[NSMutableArray(CTQuickSwitchAccountInfo) filteredQSAccountsWithoutSODATether:transferPlanMap:]_block_invoke"
+ "-[SSCardManualEntryViewController _validateEnteredInputAndDeferInstall]_block_invoke"
+ "-[SSCardManualEntryViewController _validateEnteredInputAndDeferInstall]_block_invoke_2"
+ "-[SSCellularPlanScanViewController _validateCardDataAndDeferInstall:]_block_invoke"
+ "-[SSCellularPlanScanViewController _validateCardDataAndDeferInstall:]_block_invoke_2"
+ "-[SSQuickSwitchPrimaryEnrollmentFlow firstViewController:]_block_invoke"
+ "-[SSQuickSwitchSecondaryEnrollmentFlow initWithMessageSession:accounts:primarySerialNumber:carrierSetupItems:sourceOSVersion:sourceDeviceClass:isFirstView:quickSwitchToTransferPlanMap:quickSwitchFlowType:]_block_invoke"
+ "<FALLBACK>"
+ "After SODA tether filtering - transferPlans: %@ quickSwitchPlans: %@ @%s"
+ "CUMessageSession invalidated; clearing _messageSession @%s"
+ "DOUBLE_CLICK_SIDE_BUTTON_QS_TRANSFER_%@"
+ "DOUBLE_CLICK_SIDE_BUTTON_QS_TRANSFER_NO_NUMBER"
+ "Enrollment result %ld (failure) received while on ConsentVC, progressing to CompleteVC @%s"
+ "Enrollment result %ld received while on ConsentVC, waiting for user action @%s"
+ "Home ICCID is a travel SIM, skipping travel buddy flow. @%s"
+ "LPA:1$%@$%@$"
+ "MULTI_PLAN_INTERMEDIATE_DETAIL"
+ "MULTI_PLAN_INTERMEDIATE_DETAIL_POST_BUDDY"
+ "Magnolia plans after removing QS enrolled: %@ @%s"
+ "QS account member plan (%@) with a SODA tether @%s"
+ "QS plans after removing standalone: %@ @%s"
+ "QS secondary account (%@) with a SODA tether @%s"
+ "QS websheet-inbuddy plan (%@) with a SODA tether @%s"
+ "QS_ACTIVE_ON_%@"
+ "QS_ACTIVE_ON_PLURAL_%@_%@"
+ "QS_APPLE_ACCOUNTS_MISMATCH_DETAIL"
+ "QS_APPLE_ACCOUNTS_MISMATCH_TITLE"
+ "QS_BLOCKER_AA_MISMATCH_DETAIL_OTHER_BUDDY_GENERIC"
+ "QS_BLOCKER_AA_MISMATCH_DETAIL_OTHER_BUDDY_GENERIC_PLURAL"
+ "QS_BLOCKER_AA_MISMATCH_DETAIL_OTHER_POSTBUDDY_GENERIC"
+ "QS_BLOCKER_AA_MISMATCH_DETAIL_OTHER_POSTBUDDY_GENERIC_PLURAL"
+ "QS_BLOCKER_SECONDARY_TWINNED_NO_TRANSFER_%@_%@"
+ "QS_BLOCKER_SECONDARY_TWINNED_NO_TRANSFER_NO_NUMBER_%@"
+ "QS_COMPANION_ESIM_TRANSFER_ALERT_BODY_%@_%@"
+ "QS_COMPANION_ESIM_TRANSFER_ALERT_BODY_NO_PHONENUMBER_%@"
+ "QS_COMPANION_ESIM_TRANSFER_ALERT_TITLE"
+ "QS_DEVICE_PICKER_MAIN_TEXT_%@"
+ "QS_DEVICE_PICKER_PRIMARY_NEARBY_%@"
+ "QS_DEVICE_PICKER_SUB_TEXT_COMPANION_ESIM_%@"
+ "QS_DEVICE_PICKER_SUB_TEXT_MAIN_ESIM_%@"
+ "QS_FLOW_TYPE_CHOICE_OPTION_ENROLL_ONLY_SUBTITLE_NO_NAME"
+ "QS_ICLOUD_MISMATCH_DETAIL"
+ "QS_ICLOUD_MISMATCH_TITLE"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_CONFIRM_BUTTON"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_CONFIRM_TITLE"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_PRIMARY_IMPACT_%@_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_PRIMARY_IMPACT_FALLBACK_DEVICE_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_PRIMARY_IMPACT_FALLBACK_PHONE_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_PRIMARY_IMPACT_FALLBACK_PHONE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_PRIMARY_IMPACT_PLURAL_%@_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_PRIMARY_IMPACT_PLURAL_FALLBACK_DEVICES_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_PRIMARY_IMPACT_PLURAL_FALLBACK_DEVICE_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_PRIMARY_IMPACT_PLURAL_FALLBACK_PHONE_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_PRIMARY_IMPACT_PLURAL_FALLBACK_PHONE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_PRIMARY_IMPACT_PLURAL_FALLBACK_PHONE_FALLBACK_DEVICES"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_SECONDARY_IMPACT_%@_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_SECONDARY_IMPACT_FALLBACK_DEVICE_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_SECONDARY_IMPACT_FALLBACK_PHONE_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_SECONDARY_IMPACT_FALLBACK_PHONE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_SECONDARY_IMPACT_PLURAL_%@_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_SECONDARY_IMPACT_PLURAL_FALLBACK_DEVICE_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_SECONDARY_IMPACT_PLURAL_FALLBACK_PHONE_%@"
+ "QS_LIFECYCLE_EACS_DELETE_ESIM_SECONDARY_IMPACT_PLURAL_FALLBACK_PHONE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_PRIMARY_ADVICE_%@"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_PRIMARY_ADVICE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_PRIMARY_IMPACT_%@_%@"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_PRIMARY_IMPACT_FALLBACK_DEVICE_%@"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_PRIMARY_IMPACT_FALLBACK_PHONE_%@"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_PRIMARY_IMPACT_FALLBACK_PHONE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_PRIMARY_IMPACT_PLURAL_%@_%@"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_PRIMARY_IMPACT_PLURAL_FALLBACK_DEVICE_%@"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_PRIMARY_IMPACT_PLURAL_FALLBACK_PHONE_%@"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_PRIMARY_IMPACT_PLURAL_FALLBACK_PHONE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_SECONDARY_ADVICE"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_SECONDARY_ADVICE_PLURAL_%@"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_SECONDARY_ADVICE_PLURAL_FALLBACK_PHONE"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_SECONDARY_IMPACT_%@_%@"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_SECONDARY_IMPACT_FALLBACK_DEVICE_%@"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_SECONDARY_IMPACT_FALLBACK_PHONE_%@"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_SECONDARY_IMPACT_FALLBACK_PHONE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_SECONDARY_IMPACT_PLURAL_%@_%@"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_SECONDARY_IMPACT_PLURAL_FALLBACK_DEVICE_%@"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_SECONDARY_IMPACT_PLURAL_FALLBACK_PHONE_%@"
+ "QS_LIFECYCLE_EACS_KEEP_ESIM_SECONDARY_IMPACT_PLURAL_FALLBACK_PHONE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_FINDMY_WIPE_CONFIRM_BUTTON"
+ "QS_LIFECYCLE_FINDMY_WIPE_CONFIRM_MESSAGE_%@"
+ "QS_LIFECYCLE_FINDMY_WIPE_CONFIRM_MESSAGE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_FINDMY_WIPE_CONFIRM_MESSAGE_PLURAL_%@"
+ "QS_LIFECYCLE_FINDMY_WIPE_CONFIRM_MESSAGE_PLURAL_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_FINDMY_WIPE_CONFIRM_TITLE"
+ "QS_LIFECYCLE_FINDMY_WIPE_IMPACT_%@_%@"
+ "QS_LIFECYCLE_FINDMY_WIPE_IMPACT_FALLBACK_DEVICE_%@"
+ "QS_LIFECYCLE_FINDMY_WIPE_IMPACT_FALLBACK_PHONE_%@"
+ "QS_LIFECYCLE_FINDMY_WIPE_IMPACT_FALLBACK_PHONE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_FINDMY_WIPE_IMPACT_PLURAL_%@_%@"
+ "QS_LIFECYCLE_FINDMY_WIPE_IMPACT_PLURAL_FALLBACK_DEVICE_%@"
+ "QS_LIFECYCLE_FINDMY_WIPE_IMPACT_PLURAL_FALLBACK_PHONE_%@"
+ "QS_LIFECYCLE_FINDMY_WIPE_IMPACT_PLURAL_FALLBACK_PHONE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_CANCEL_BUTTON"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_CONFIRM_BUTTON"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_MESSAGE_WIFI"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_MESSAGE_WLAN"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_TITLE_%@"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_TITLE_FALLBACK_PHONE"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_TITLE_PLURAL_%@"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_CONFIRM_TITLE_PLURAL_FALLBACK_PHONE"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_PRIMARY_IMPACT_%@_%@"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_PRIMARY_IMPACT_FALLBACK_DEVICE_%@"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_PRIMARY_IMPACT_FALLBACK_PHONE_%@"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_PRIMARY_IMPACT_FALLBACK_PHONE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_PRIMARY_IMPACT_PLURAL_%@_%@"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_PRIMARY_IMPACT_PLURAL_FALLBACK_DEVICE_%@"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_PRIMARY_IMPACT_PLURAL_FALLBACK_PHONE_%@"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_PRIMARY_IMPACT_PLURAL_FALLBACK_PHONE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_SECONDARY_IMPACT_%@_%@"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_SECONDARY_IMPACT_FALLBACK_DEVICE_%@"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_SECONDARY_IMPACT_FALLBACK_PHONE_%@"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_SECONDARY_IMPACT_FALLBACK_PHONE_FALLBACK_DEVICE"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_SECONDARY_IMPACT_PLURAL_%@_%@"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_SECONDARY_IMPACT_PLURAL_FALLBACK_DEVICE_%@"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_SECONDARY_IMPACT_PLURAL_FALLBACK_PHONE_%@"
+ "QS_LIFECYCLE_LOCAL_SIGNOUT_SECONDARY_IMPACT_PLURAL_FALLBACK_PHONE_FALLBACK_DEVICE"
+ "QS_MAIN_DEVICE_NEEDED_%@"
+ "QS_MAIN_DEVICE_NEEDED_NO_NAME"
+ "QS_MAIN_DSIDS_MISMATCHED_SUBTEXT"
+ "QS_MAIN_ESIM_TRANSFER_ALERT_BODY_%@_%@"
+ "QS_MAIN_ESIM_TRANSFER_ALERT_BODY_NO_PHONENUMBER_%@"
+ "QS_MAIN_ESIM_TRANSFER_ALERT_TITLE"
+ "QS_NO_WIFI_DETAILS_BUDDY_%@"
+ "QS_NO_WIFI_DETAILS_BUDDY_NO_NAME"
+ "QS_NO_WIFI_DETAILS_POSTBUDDY_%@"
+ "QS_NO_WIFI_DETAILS_POSTBUDDY_NO_NAME"
+ "QS_NO_WIFI_TITLE_BUDDY"
+ "QS_NO_WIFI_TITLE_POSTBUDDY"
+ "QS_NO_WLAN_DETAILS_POSTBUDDY_%@"
+ "QS_NO_WLAN_DETAILS_POSTBUDDY_NO_NAME"
+ "QS_PLAN_DISABLED_IN_CURRENT_SIM_CONFIG_DETAIL"
+ "QS_PLAN_DISABLED_IN_CURRENT_SIM_CONFIG_TITLE"
+ "QS_PRX_TRANSFERRING_DETAILS"
+ "QS_PRX_TRANSFERRING_TITLE"
+ "QS_PRX_TRANSFER_FAILURE_%@"
+ "QS_PRX_TRANSFER_SUCCESS_COMPANION_SUBTITLE_%@_%@_%@"
+ "QS_PRX_TRANSFER_SUCCESS_COMPANION_SUBTITLE_NO_MAIN_%@_%@"
+ "QS_PRX_TRANSFER_SUCCESS_COMPANION_SUBTITLE_NO_MAIN_NO_NUMBER_%@"
+ "QS_PRX_TRANSFER_SUCCESS_COMPANION_SUBTITLE_NO_NUMBER_%@_%@"
+ "QS_PRX_TRANSFER_SUCCESS_MAIN_SUBTITLE_%@_%@_%@"
+ "QS_PRX_TRANSFER_SUCCESS_MAIN_SUBTITLE_NO_COMPANION_%@_%@"
+ "QS_PRX_TRANSFER_SUCCESS_MAIN_SUBTITLE_NO_COMPANION_NO_NUMBER_%@"
+ "QS_PRX_TRANSFER_SUCCESS_MAIN_SUBTITLE_NO_NUMBER_%@_%@"
+ "QS_SHARE_ESIM_DETAILS_QS_ALREADY_ENROLLED_%@"
+ "QS_SHARE_ESIM_DETAILS_QS_ALREADY_ENROLLED_NO_NUMBER"
+ "QS_SHARE_ESIM_DETAILS_SINGLE_%@"
+ "QS_SHARE_PHONE_NUMBER_SINGLE_PRIMARY_DETAIL_%@_%@_%@"
+ "QS_SHARE_PHONE_NUMBER_SINGLE_SECONDARY_DETAIL_%@_%@_%@"
+ "QS_TRANSFERRING_DETAILS"
+ "QS_TRANSFERRING_TITLE"
+ "QS_TRANSFER_COMPANION_COMPLETE_DETAIL_%@"
+ "QS_TRANSFER_COMPANION_COMPLETE_DETAIL_NO_NUMBER"
+ "QS_TRANSFER_ESIM_DETAILS_%@"
+ "QS_TRANSFER_ESIM_DETAILS_NO_NUMBER"
+ "QS_TRANSFER_IN_PROGRESS"
+ "QS_TRANSFER_MAIN_COMPLETE_DETAIL_%@"
+ "QS_TRANSFER_MAIN_COMPLETE_DETAIL_NO_NUMBER"
+ "QUICK_SWITCH_PREPARING_FOR_TRANSFER"
+ "QUICK_SWITCH_PRIMARY_TRANSFER_SUCCESS_TITLE"
+ "QUICK_SWITCH_TRANSFER_SUBTITLE_%@"
+ "QUICK_SWITCH_TRANSFER_SUBTITLE_NO_NUMBER"
+ "QUICK_SWITCH_WEBSHEET_INCOMPLETE_NEW_PHONE_DETAIL"
+ "QUICK_SWITCH_WEBSHEET_INCOMPLETE_NEW_PHONE_TITLE"
+ "Resetting carrierSetupItems @%s"
+ "SourceErrorMessage"
+ "User confirmed device selection: %@ (role: %d) @%s"
+ "User consented to Quick Switch enrollment: flowType=%lu @%s"
+ "[E]invalid SSQuickSwitchPrimaryEnrollmentFlow @%s"
+ "[E]local validate failed: %@ @%s"
+ "[E]manual-entry local validate failed: %@ @%s"
+ "[E]query accounts supporting qs failed @%s"
+ "[I] websheet incomplete (kUserDeclined). Current VC: %@ @%s"
+ "https://support.apple.com/118669?cid=mc-ols-esim-article_ht212780-ios_ui-07192022"
+ "https://support.apple.com/127274"
+ "iphone.on.iphone.and.arrow.backward.and.arrow.forward"
+ "local validate succeeded for cardData @%s"
+ "manual-entry local validate succeeded @%s"
+ "q24@?0@\"CTQuickSwitchAccountInfo\"8@\"CTQuickSwitchAccountInfo\"16"
+ "subtitle"
+ "v24@?0@\"CTCellularPlanQRCodeAction\"8@\"NSError\"16"
+ "\xf1"
- "%ld_%@"
- ", "
- "-[TSCellularPlanActivatingFlow(SSQuickSwitchIncompleteWebsheetDecision) resolveIncompleteWebsheetWithFollowup:]"
- "-[TSCellularPlanActivatingFlow(SSQuickSwitchIncompleteWebsheetDecision) resolveIncompleteWebsheetWithFollowup:]_block_invoke"
- "27.0"
- "Default voice iccid is not set. @%s"
- "Enrollment result %ld received on WebsheetIncompleteVC, completing flow @%s"
- "FALLBACK_CARRIER_NAME"
- "FALLBACK_DEVICE_NAME"
- "FALLBACK_PHONE_NUMBER"
- "MULTI_ALS_DETAIL"
- "MULTI_ESIM_TRANSFER_DETAIL"
- "MULTI_ESIM_TRANSFER_QR_CODE_DETAIL"
- "ON_%@"
- "QS_BLOCKER_SECONDARY_TWINNED_NO_TRANSFER_%@"
- "QS_COMPANION_DEVICE_NEEDED_%@"
- "QS_CONFIRM_TRANSFER_ALERT_%@_%@"
- "QS_DEVICE_PICKER_KEEP_NEARBY_%@"
- "QS_DEVICE_PICKER_REPLACE_%@"
- "QS_DEVICE_PICKER_SET_UP_NEW_LINE"
- "QS_EACS_CARRIER_NOTICE"
- "QS_EACS_CARRIER_NOTICE_%@"
- "QS_EACS_CONFIRM_BUTTON_DELETE_ESIM"
- "QS_EACS_CONFIRM_BUTTON_ERASE"
- "QS_EACS_CONFIRM_BUTTON_SIGNOUT"
- "QS_EACS_CONFIRM_TITLE_DELETE_ESIM"
- "QS_EACS_CONFIRM_TITLE_ERASE"
- "QS_EACS_CONFIRM_TITLE_SIGNOUT"
- "QS_EACS_PRIMARY_DELETE_ESIM_CONFIRM_%@"
- "QS_EACS_PRIMARY_DELETE_ESIM_CONFIRM_%@_%@"
- "QS_EACS_PRIMARY_DELETE_ESIM_CONFIRM_FALLBACK_DEVICE"
- "QS_EACS_PRIMARY_DELETE_ESIM_CONFIRM_FALLBACK_DEVICE_%@"
- "QS_EACS_PRIMARY_DELETE_ESIM_NUMBERS_%@_%@"
- "QS_EACS_PRIMARY_DELETE_ESIM_NUMBERS_FALLBACK_DEVICE_%@"
- "QS_EACS_PRIMARY_DELETE_ESIM_NUMBER_%@_%@"
- "QS_EACS_PRIMARY_DELETE_ESIM_NUMBER_FALLBACK_DEVICE_%@"
- "QS_EACS_PRIMARY_KEEP_ESIM_ADVICE_%@_%@"
- "QS_EACS_PRIMARY_KEEP_ESIM_ADVICE_FALLBACK_DEVICE"
- "QS_EACS_PRIMARY_KEEP_ESIM_CONFIRM_%@"
- "QS_EACS_PRIMARY_KEEP_ESIM_CONFIRM_FALLBACK_DEVICE"
- "QS_EACS_PRIMARY_KEEP_ESIM_NUMBERS_%@_%@"
- "QS_EACS_PRIMARY_KEEP_ESIM_NUMBERS_FALLBACK_DEVICE_%@"
- "QS_EACS_PRIMARY_KEEP_ESIM_NUMBER_%@_%@"
- "QS_EACS_PRIMARY_KEEP_ESIM_NUMBER_FALLBACK_DEVICE_%@"
- "QS_EACS_PRIMARY_SIGNOUT_CONFIRM_%@_%@"
- "QS_EACS_PRIMARY_SIGNOUT_CONFIRM_FALLBACK_DEVICE_%@"
- "QS_EACS_PRIMARY_SIGNOUT_NUMBERS_%@_%@"
- "QS_EACS_PRIMARY_SIGNOUT_NUMBERS_FALLBACK_DEVICE_%@"
- "QS_EACS_PRIMARY_SIGNOUT_NUMBER_%@_%@"
- "QS_EACS_PRIMARY_SIGNOUT_NUMBER_FALLBACK_DEVICE_%@"
- "QS_EACS_SECONDARY_DELETE_ESIM_NUMBERS_%@_%@"
- "QS_EACS_SECONDARY_DELETE_ESIM_NUMBERS_FALLBACK_DEVICE_%@"
- "QS_EACS_SECONDARY_DELETE_ESIM_NUMBER_%@_%@"
- "QS_EACS_SECONDARY_DELETE_ESIM_NUMBER_FALLBACK_DEVICE_%@"
- "QS_EACS_SECONDARY_KEEP_ESIM_ADVICE"
- "QS_EACS_SECONDARY_KEEP_ESIM_ADVICE_NUMBERS_%@"
- "QS_EACS_SECONDARY_KEEP_ESIM_NUMBERS_%@_%@"
- "QS_EACS_SECONDARY_KEEP_ESIM_NUMBERS_FALLBACK_DEVICE_%@"
- "QS_EACS_SECONDARY_KEEP_ESIM_NUMBER_%@_%@"
- "QS_EACS_SECONDARY_KEEP_ESIM_NUMBER_FALLBACK_DEVICE_%@"
- "QS_EACS_SECONDARY_SIGNOUT_CONFIRM"
- "QS_EACS_SECONDARY_SIGNOUT_NUMBERS_%@_%@"
- "QS_EACS_SECONDARY_SIGNOUT_NUMBERS_FALLBACK_DEVICE_%@"
- "QS_EACS_SECONDARY_SIGNOUT_NUMBER_%@_%@"
- "QS_EACS_SECONDARY_SIGNOUT_NUMBER_FALLBACK_DEVICE_%@"
- "QS_FINDMY_WIPE_CONFIRM_BUTTON"
- "QS_FINDMY_WIPE_CONFIRM_NUMBERS_%@"
- "QS_FINDMY_WIPE_CONFIRM_NUMBER_%@"
- "QS_FINDMY_WIPE_NUMBERS_%@_%@"
- "QS_FINDMY_WIPE_NUMBER_%@_%@"
- "QS_FINDMY_WIPE_PREAMBLE"
- "QS_FOLLOWUP_OTHER_PHONE_DETAIL"
- "QS_FOLLOWUP_OTHER_PHONE_DETAIL_%@"
- "QS_FOLLOWUP_OTHER_PHONE_TITLE"
- "QS_LOCAL_SIGNOUT_CONFIRM_BUTTON_CANCEL"
- "QS_LOCAL_SIGNOUT_CONFIRM_BUTTON_CONTINUE"
- "QS_LOCAL_SIGNOUT_CONFIRM_MESSAGE"
- "QS_LOCAL_SIGNOUT_CONFIRM_TITLE_%@"
- "QS_NOT_AVAILABLE"
- "QS_NO_WIFI_DETAILS"
- "QS_NO_WIFI_TITLE"
- "QS_SHARE_ESIM_SET_UP_CARRIER_%@"
- "QS_SHARE_ESIM_SET_UP_DEVICE_NAMES_%@"
- "QS_SHARE_ESIM_SET_UP_PHONE_%@"
- "QS_SHARE_PHONE_NUMBER_DETAILS"
- "QS_TRANSFER_ESIM_DETAILS"
- "QUICK_SWITCH_PRIMARY_SLIDING_START_TITLE"
- "QUICK_SWITCH_PRIMARY_START_TITLE"
- "QUICK_SWITCH_PRIMARY_TRANSFER_START_SUBTITLE"
- "QUICK_SWITCH_WEBSHEET_INCOMPLETE_DECISION_DETAIL"
- "QUICK_SWITCH_WEBSHEET_INCOMPLETE_DECISION_TITLE"
- "QUICK_SWITCH_WEBSHEET_INCOMPLETE_SET_UP_LATER"
- "Source OS version %@ is below %@ - skipping Quick Switch @%s"
- "THIS_IPHONE"
- "User confirmed device selection: %@ (role: %d, newLine: %d) @%s"
- "User consented to Quick Switch enrollment @%s"
- "User selected: Set up new line on this iPhone @%s"
- "[E]no plan info to resolve websheet incomplete @%s"
- "[E]websheet incomplete with invalid top VC. expect WaitOnWebsheet VC. @%s"
- "https://support.apple.com/en-us/118669?cid=mc-ols-esim-article_ht212780-ios_ui-07192022"
- "incomplete"
- "resolved websheet incomplete with followup:%{bool}d, error:%@ @%s"
- "websheet incomplete on primary device! current VC: %@ @%s"
- "\xe1"
```
