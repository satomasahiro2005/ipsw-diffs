## SafariCore

> `/System/Library/PrivateFrameworks/SafariCore.framework/SafariCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d6f80` | `0x1e138c` | **`+0xa40c`** |
| `__TEXT.__cstring` | `0x18587` | `0x190f7` | **`+0xb70`** |
| `__TEXT.__unwind_info` | `0x9048` | `0x97e0` | **`+0x798`** |
| `__TEXT.__eh_frame` | `0x9790` | `0x9de0` | **`+0x650`** |
| `__AUTH_CONST.__objc_const` | `0x15ac8` | `0x15f00` | **`+0x438`** |
| `__AUTH_CONST.__const` | `0xa610` | `0xa8f8` | **`+0x2e8`** |
| `__DATA.__bss` | `0x8600` | `0x88b0` | **`+0x2b0`** |
| `__TEXT.__const` | `0x6c84` | `0x6ef4` | **`+0x270`** |
| `__AUTH_CONST.__cfstring` | `0x1cfc0` | `0x1d200` | **`+0x240`** |
| `__TEXT.__gcc_except_tab` | `0x72a4` | `0x74d8` | **`+0x234`** |
| `__TEXT.__oslogstring` | `0xdaa1` | `0xdc91` | **`+0x1f0`** |
| `__DATA.__data` | `0x3360` | `0x3520` | **`+0x1c0`** |
| `__TEXT.__constg_swiftt` | `0x1e78` | `0x1ff0` | **`+0x178`** |
| `__TEXT.__objc_methlist` | `0xcd24` | `0xce6c` | **`+0x148`** |
| `__TEXT.__swift5_fieldmd` | `0x160c` | `0x1714` | **`+0x108`** |
| `__DATA_CONST.__const` | `0x56a0` | `0x5788` | **`+0xe8`** |
| `__AUTH.__data` | `0x1550` | `0x1630` | **`+0xe0`** |
| `__TEXT.__swift5_typeref` | `0x237a` | `0x2454` | **`+0xda`** |
| `__TEXT.__swift5_reflstr` | `0x134b` | `0x13eb` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x73f8` | `0x7480` | **`+0x88`** |
| `__AUTH_CONST.__objc_intobj` | `0x8b8` | `0x930` | **`+0x78`** |
| `__AUTH.__objc_data` | `0x19b8` | `0x1a08` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x2100` | `0x2150` | **`+0x50`** |
| `__DATA_CONST.__objc_arraydata` | `0x2a50` | `0x2aa0` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x6c4` | `0x704` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x14c0` | `0x1490` | **`-0x30`** |
| `__TEXT.__swift_as_ret` | `0x34c` | `0x37c` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0xcd0` | `0xcf8` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0x304` | `0x32c` | **`+0x28`** |
| `__TEXT.__swift5_assocty` | `0x578` | `0x590` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x3e4` | `0x3f8` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x1cc` | `0x1e0` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x1290` | `0x12a0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x6d0` | `0x6e0` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x210` | `0x218` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x4b0` | `0x4b8` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x28` | `0x2c` | **`+0x4`** |

### Other Changes

```diff

-625.1.18.10.4
+625.1.20.10.3

-  Functions: 10715
-  Symbols:   11728
-  CStrings:  5487
+  Functions: 10892
+  Symbols:   11849
+  CStrings:  5544
Symbols:
+ +[WBSFeatureAvailability isRecentSearchesInStartPageEnabled]
+ +[WBSManagedExtensionsConfigurationStore configurationURL]
+ +[WBSPasswordBreachStore defaultBackingStoreURL]
+ +[WBSTOTPGenerator keyDataForBase32EncodedString:]
+ -[NSFileManager(SafariNSFileManagerExtras) safari_createTemporaryDirectoryWithError:]
+ -[WBSAuthenticationServicesAgentProxy credentialProviderInformationForAnyRecentAutoFillOfUsername:password:hostApplicationBundleIdentifier:completionHandler:]
+ -[WBSAutoFillQuirksManager test_waitForInternalQueueToEmpty]
+ -[WBSGeneratedPasswordStore addGeneratedPassword:forProtectionSpace:completionHandler:]
+ -[WBSManagedExtensionsConfigurationStore .cxx_destruct]
+ -[WBSManagedExtensionsConfigurationStore _refreshFromDisk]
+ -[WBSManagedExtensionsConfigurationStore _underlyingConfigurationDidChange:]
+ -[WBSManagedExtensionsConfigurationStore beginObservingStorage]
+ -[WBSManagedExtensionsConfigurationStore dealloc]
+ -[WBSManagedExtensionsConfigurationStore delegate]
+ -[WBSManagedExtensionsConfigurationStore managedExtensionsConfiguration]
+ -[WBSManagedExtensionsConfigurationStore setDelegate:]
+ -[WBSManagedExtensionsController _initWithConfigurationStore:]
+ -[WBSManagedExtensionsController managedExtensionsConfigurationStoreDidChange:]
+ -[WBSPasswordBreachStore dealloc]
+ -[WBSPasswordBreachStore initWithBackingStoreURL:accessMode:]
+ -[WBSPasswordWarningManager _breachResultRecordsForSavedAccounts:]
+ -[WBSSQLiteDatabase isDatabaseOpen]
+ -[WBSSafariBookmarksSyncAgentProxy deleteSafariContainerDataWithCompletionHandler:]
+ -[WBSSavedAccountStore _newUniqueIdentifierIfNecessaryForSavedAccount:]
+ -[WBSSavedAccountStore _saveUniqueIdentifierOnInternalQueue:savedAccount:]
+ -[WBSSavedAccountStore createUniqueIdentifiersIfNecessaryForSavedAccounts:completionHandler:]
+ GCC_except_table139
+ GCC_except_table228
+ GCC_except_table238
+ GCC_except_table302
+ GCC_except_table309
+ GCC_except_table341
+ GCC_except_table409
+ GCC_except_table411
+ GCC_except_table75
+ GCC_except_table88
+ GCC_except_table92
+ GCC_except_table95
+ _OBJC_CLASS_$_WBSManagedExtensionsConfigurationStore
+ _OBJC_IVAR_$_WBSAppIDsToDomainsAssociationManager._queue
+ _OBJC_IVAR_$_WBSChangePasswordURLManager._queue
+ _OBJC_IVAR_$_WBSManagedExtensionsConfigurationStore._delegate
+ _OBJC_IVAR_$_WBSManagedExtensionsConfigurationStore._managedExtensionsConfiguration
+ _OBJC_IVAR_$_WBSManagedExtensionsController._store
+ _OBJC_IVAR_$_WBSPasswordAuditingEligibleDomainsManager._queue
+ _OBJC_IVAR_$_WBSPasswordBreachStore._accessMode
+ _OBJC_IVAR_$_WBSPasswordGenerationManager._queue
+ _OBJC_IVAR_$_WBSPasswordWarningManager._breachResultRecordsBySavedAccount
+ _OBJC_IVAR_$_WBSPasswordWarningManager._passwordBreachQueryInProgress
+ _OBJC_IVAR_$_WBSPasswordWarningManager._topFraudTargets
+ _OBJC_METACLASS_$_WBSManagedExtensionsConfigurationStore
+ _WBSAllowAutomaticPasswordChangeInDetailViewKey
+ _WBSAutomaticPasswordChangeDebugSiteShouldEnableHardModeKey
+ _WBSAutomaticPasswordChangeDebugSiteShouldRequestOneTimeCodeKey
+ _WBSAutomaticPasswordChangeShouldAdvanceManuallyKey
+ _WBSAutomaticPasswordChangeShouldAlwaysRecommendKey
+ _WBSAutomaticPasswordChangeShouldShowWebViewKey
+ _WBSAutomaticPasswordChangeShowSessionDoneButtonKey
+ _WBSAutomaticPasswordChangeShowVerboseErrorsKey
+ _WBSDebugEnablePasswordChangeClassifierKey
+ _WBSDebugLogFullAgentToolOutputKey
+ _WBSDidApplyStartPageSectionPositionHealKey
+ _WBSOSLogSync
+ _WBSOSLogSync.log
+ _WBSOSLogSync.onceToken
+ __DATA__TtC10SafariCore20WBSAsyncSerialRunner
+ __IVARS__TtC10SafariCore10WBSRunOnce
+ __IVARS__TtC10SafariCore20WBSAsyncSerialRunner
+ __IVARS__TtC10SafariCore7WBSLazy
+ __METACLASS_DATA__TtC10SafariCore20WBSAsyncSerialRunner
+ __OBJC_$_CLASS_METHODS_WBSManagedExtensionsConfigurationStore
+ __OBJC_$_CLASS_PROP_LIST_WBSManagedExtensionsConfigurationStore
+ __OBJC_$_CLASS_PROP_LIST_WBSPasswordBreachStore
+ __OBJC_$_INSTANCE_METHODS_WBSManagedExtensionsConfigurationStore
+ __OBJC_$_INSTANCE_VARIABLES_WBSManagedExtensionsConfigurationStore
+ __OBJC_$_PROP_LIST_WBSManagedExtensionsConfigurationStore
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_WBSManagedExtensionsConfigurationStoreDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_WBSManagedExtensionsConfigurationStoreDelegate
+ __OBJC_$_PROTOCOL_REFS_WBSManagedExtensionsConfigurationStoreDelegate
+ __OBJC_CLASS_PROTOCOLS_$_WBSManagedExtensionsController
+ __OBJC_CLASS_RO_$_WBSManagedExtensionsConfigurationStore
+ __OBJC_LABEL_PROTOCOL_$_WBSManagedExtensionsConfigurationStoreDelegate
+ __OBJC_METACLASS_RO_$_WBSManagedExtensionsConfigurationStore
+ __OBJC_PROTOCOL_$_WBSManagedExtensionsConfigurationStoreDelegate
+ __ZNSt3__110__function12__value_funcIFbiN8nlohmann6detail13parse_event_tERNS2_10basic_jsonINS_3mapENS_6vectorENS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEbxydSB_NS2_14adl_serializerENS7_IhNSB_IhEEEEEEEEC2B9sqn220106EOSK_
+ __ZNSt3__110__function12__value_funcIFbiN8nlohmann6detail13parse_event_tERNS2_10basic_jsonINS_3mapENS_6vectorENS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEbxydSB_NS2_14adl_serializerENS7_IhNSB_IhEEEEEEEEC2B9sqn220106ERKSK_
+ __ZNSt3__110__function12__value_funcIFbiN8nlohmann6detail13parse_event_tERNS2_10basic_jsonINS_3mapENS_6vectorENS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEbxydSB_NS2_14adl_serializerENS7_IhNSB_IhEEEEEEEED2B9sqn220106Ev
+ __ZNSt3__110unique_ptrIN12SafariShared25SuddenTerminationDisablerENS_14default_deleteIS2_EEE5resetB9sqn220106EPS2_
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9sqn220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9sqn220106Em
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B9sqn220106ILi0EEEPKc
+ __ZNSt3__113__tree_removeB9sqn220106IPNS_16__tree_node_baseIPvEEEEvT_S5_
+ __ZNSt3__116__if_likely_elseB9sqn220106IZNS_6vectorIcNS_9allocatorIcEEE12emplace_backIJcEEERcDpOT_EUlvE_ZNS5_IJcEEES6_S9_EUlvE0_EEvbT_T0_
+ __ZNSt3__127__tree_balance_after_insertB9sqn220106IPNS_16__tree_node_baseIPvEEEEvT_S5_
+ __ZNSt3__13setIPN12SafariShared25SuddenTerminationDisablerENS_4lessIS3_EENS_9allocatorIS3_EEE6insertB9sqn220106EOS3_
+ __ZNSt3__16__treeIPN12SafariShared25SuddenTerminationDisablerENS_4lessIS3_EENS_9allocatorIS3_EEE14__tree_deleterclB9sqn220106EPNS_11__tree_nodeIS3_PvEE
+ __ZNSt3__16vectorIbNS_9allocatorIbEEE11__vallocateB9sqn220106Em
+ __ZNSt3__16vectorIbNS_9allocatorIbEEE20__throw_length_errorB9sqn220106Ev
+ __ZNSt3__16vectorIcNS_9allocatorIcEEE20__throw_length_errorB9sqn220106Ev
+ __ZNSt3__16vectorIcNS_9allocatorIcEEE9push_backB9sqn220106EOc
+ __ZNSt3__16vectorIhNS_9allocatorIhEEE11__vallocateB9sqn220106Em
+ __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9sqn220106Ev
+ __ZNSt3__16vectorIhNS_9allocatorIhEEEC2B9sqn220106Em
+ __ZNSt3__16vectorItNS_9allocatorItEEE11__vallocateB9sqn220106Em
+ __ZNSt3__16vectorItNS_9allocatorItEEE20__throw_length_errorB9sqn220106Ev
+ __ZNSt3__16vectorItNS_9allocatorItEEEC2B9sqn220106Em
+ __ZNSt3__19allocatorImE17allocate_at_leastB9sqn220106Em
+ __ZNSt3__19allocatorItE17allocate_at_leastB9sqn220106Em
+ __ZSt28__throw_bad_array_new_lengthB9sqn220106v
+ __ZZ85-[NSFileManager(SafariNSFileManagerExtras) safari_createTemporaryDirectoryWithError:]E7baseURL
+ __ZZ85-[NSFileManager(SafariNSFileManagerExtras) safari_createTemporaryDirectoryWithError:]E9onceToken
+ ___158-[WBSAuthenticationServicesAgentProxy credentialProviderInformationForAnyRecentAutoFillOfUsername:password:hostApplicationBundleIdentifier:completionHandler:]_block_invoke
+ ___50+[WBSTOTPGenerator keyDataForBase32EncodedString:]_block_invoke
+ ___51-[WBSAppIDsToDomainsAssociationManager description]_block_invoke
+ ___53-[WBSPasswordGenerationManager passwordRulesByDomain]_block_invoke
+ ___55-[WBSAppIDsToDomainsAssociationManager appIDsToDomains]_block_invoke
+ ___55-[WBSChangePasswordURLManager changePasswordURLStrings]_block_invoke
+ ___57-[WBSPasswordGenerationManager setPasswordRulesByDomain:]_block_invoke
+ ___59-[WBSAppIDsToDomainsAssociationManager setAppIDsToDomains:]_block_invoke
+ ___59-[WBSChangePasswordURLManager setChangePasswordURLStrings:]_block_invoke
+ ___60+[WBSFeatureAvailability isRecentSearchesInStartPageEnabled]_block_invoke
+ ___60-[WBSAutoFillQuirksManager test_waitForInternalQueueToEmpty]_block_invoke
+ ___60-[WBSPasswordGenerationManager passwordRequirementsByDomain]_block_invoke
+ ___61-[WBSPasswordBreachStore initWithBackingStoreURL:accessMode:]_block_invoke
+ ___61-[WBSPasswordBreachStore initWithBackingStoreURL:accessMode:]_block_invoke_2
+ ___61-[WBSPasswordGenerationManager defaultRequirementsForDomain:]_block_invoke
+ ___62-[WBSPasswordGenerationManager defaultPasswordRulesForDomain:]_block_invoke
+ ___64-[WBSPasswordGenerationManager setPasswordRequirementsByDomain:]_block_invoke
+ ___67-[WBSChangePasswordURLManager changePasswordURLForHighLevelDomain:]_block_invoke
+ ___74-[WBSSavedAccountStore _saveUniqueIdentifierOnInternalQueue:savedAccount:]_block_invoke
+ ___75-[WBSPasswordWarningManager getAllWarningsForcingUpdate:completionHandler:]_block_invoke_7
+ ___75-[WBSPasswordWarningManager getAllWarningsForcingUpdate:completionHandler:]_block_invoke_8
+ ___76-[WBSManagedExtensionsConfigurationStore _underlyingConfigurationDidChange:]_block_invoke
+ ___81-[WBSAppIDsToDomainsAssociationManager domainsWithAssociatedCredentialsForAppID:]_block_invoke
+ ___81-[WBSPasswordAuditingEligibleDomainsManager domainsIneligibleForPasswordAuditing]_block_invoke
+ ___85-[NSFileManager(SafariNSFileManagerExtras) safari_createTemporaryDirectoryWithError:]_block_invoke
+ ___85-[WBSPasswordAuditingEligibleDomainsManager setDomainsIneligibleForPasswordAuditing:]_block_invoke
+ ___93-[WBSSavedAccountStore createUniqueIdentifiersIfNecessaryForSavedAccounts:completionHandler:]_block_invoke
+ ___WBSOSLogSync_block_invoke
+ ___block_descriptor_33_e5_v8?0l
+ ___block_descriptor_40_e8_32s_e43_v16?0"WBSPasswordWarningTopFraudTargets"8ls32l8
+ ___block_descriptor_40_e8_32s_e45_"WBSPasswordWarning"16?0"WBSSavedAccount"8ls32l8
+ ___block_descriptor_48_ea8_32s40r_e5_v8?0lr40l8s32l8
+ ___block_descriptor_49_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_56_ea8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
+ ___swift_closure_destructor.106Tm
+ ___swift_closure_destructor.19Tm
+ ___swift_closure_destructor.53Tm
+ ___swift_closure_destructor.57Tm
+ _associated conformance 10SafariCore34WBSAutomaticSecurityUpgradeResultsV9PlacementOSHAASQ
+ _associated conformance 10SafariCore37WBSSavedAccountSecurityUpgradeSessionCs12IdentifiableAA2IDsADP_SH
+ _get_type_metadata l15Synchronization5MutexVyxSgG noncopyable
+ _isRecentSearchesInStartPageEnabled.isRecentSearchesInStartPageEnabled
+ _isRecentSearchesInStartPageEnabled.onceToken
+ _keyDataForBase32EncodedString:.inverseAlphabet
+ _keyDataForBase32EncodedString:.onceToken
+ _swift_getTupleTypeMetadata
+ _swift_task_addCancellationHandler
+ _swift_task_future_wait_throwing
+ _swift_task_removeCancellationHandler
+ _symbolic $s10SafariCore16WBSRetryStrategyP
+ _symbolic Say_____G So35WBSAutomaticPasswordChangeErrorCodeV
+ _symbolic ScTyx______pG s5ErrorP
+ _symbolic _____ 10SafariCore10WBSRunOnceC
+ _symbolic _____ 10SafariCore14WBSRetryRunnerV
+ _symbolic _____ 10SafariCore20WBSAsyncSerialRunnerC
+ _symbolic _____ 10SafariCore34WBSAutomaticSecurityUpgradeResultsV
+ _symbolic _____ 10SafariCore34WBSAutomaticSecurityUpgradeResultsV9PlacementO
+ _symbolic _____ 10SafariCore7WBSLazyC
+ _symbolic ______SSSg17generatedPasswordt So35WBSAutomaticPasswordChangeErrorCodeV
+ _symbolic ___________p_SitYbKc s8DurationV s5ErrorP
+ _symbolic ______p 10SafariCore16WBSRetryStrategyP
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10SafariCore26WBSLocalizedPluralVariableV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So35WBSAutomaticPasswordChangeErrorCodeV
+ _symbolic x______pIeghHrzo_ s5ErrorP
+ _symbolic xyc
+ _symbolic yxxQpc
+ _type_layout_string 10SafariCore14WBSRetryRunnerV
+ _type_layout_string 10SafariCore34WBSAutomaticSecurityUpgradeResultsV
- +[WBSManagedExtensionsController managedExtensionsConfigurationURL]
- +[WBSTOTPGenerator _keyDataForBase32EncodedString:]
- -[WBSManagedExtensionsController _managedExtensionConfigurationDidChange:]
- -[WBSManagedExtensionsController _readManagedExtensionsStateFromDisk]
- -[WBSPasswordBreachStore initWithBackingStoreURL:]
- -[WBSPasswordWarningTopFraudTargetsManager dealloc]
- GCC_except_table298
- GCC_except_table305
- GCC_except_table345
- GCC_except_table405
- GCC_except_table407
- GCC_except_table412
- _OBJC_IVAR_$_WBSManagedExtensionsController._managedExtensionsState
- __OBJC_$_CLASS_PROP_LIST_WBSManagedExtensionsController
- __ZNSt3__110__function12__value_funcIFbiN8nlohmann6detail13parse_event_tERNS2_10basic_jsonINS_3mapENS_6vectorENS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEbxydSB_NS2_14adl_serializerENS7_IhNSB_IhEEEEEEEEC2B9sqn220100EOSK_
- __ZNSt3__110__function12__value_funcIFbiN8nlohmann6detail13parse_event_tERNS2_10basic_jsonINS_3mapENS_6vectorENS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEbxydSB_NS2_14adl_serializerENS7_IhNSB_IhEEEEEEEEC2B9sqn220100ERKSK_
- __ZNSt3__110__function12__value_funcIFbiN8nlohmann6detail13parse_event_tERNS2_10basic_jsonINS_3mapENS_6vectorENS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEbxydSB_NS2_14adl_serializerENS7_IhNSB_IhEEEEEEEED2B9sqn220100Ev
- __ZNSt3__110unique_ptrIN12SafariShared25SuddenTerminationDisablerENS_14default_deleteIS2_EEE5resetB9sqn220100EPS2_
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9sqn220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9sqn220100Em
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B9sqn220100ILi0EEEPKc
- __ZNSt3__113__tree_removeB9sqn220100IPNS_16__tree_node_baseIPvEEEEvT_S5_
- __ZNSt3__116__if_likely_elseB9sqn220100IZNS_6vectorIcNS_9allocatorIcEEE12emplace_backIJcEEERcDpOT_EUlvE_ZNS5_IJcEEES6_S9_EUlvE0_EEvbT_T0_
- __ZNSt3__127__tree_balance_after_insertB9sqn220100IPNS_16__tree_node_baseIPvEEEEvT_S5_
- __ZNSt3__13setIPN12SafariShared25SuddenTerminationDisablerENS_4lessIS3_EENS_9allocatorIS3_EEE6insertB9sqn220100EOS3_
- __ZNSt3__16__treeIPN12SafariShared25SuddenTerminationDisablerENS_4lessIS3_EENS_9allocatorIS3_EEE14__tree_deleterclB9sqn220100EPNS_11__tree_nodeIS3_PvEE
- __ZNSt3__16vectorIbNS_9allocatorIbEEE11__vallocateB9sqn220100Em
- __ZNSt3__16vectorIbNS_9allocatorIbEEE20__throw_length_errorB9sqn220100Ev
- __ZNSt3__16vectorIcNS_9allocatorIcEEE20__throw_length_errorB9sqn220100Ev
- __ZNSt3__16vectorIcNS_9allocatorIcEEE9push_backB9sqn220100EOc
- __ZNSt3__16vectorIhNS_9allocatorIhEEE11__vallocateB9sqn220100Em
- __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9sqn220100Ev
- __ZNSt3__16vectorIhNS_9allocatorIhEEEC2B9sqn220100Em
- __ZNSt3__16vectorItNS_9allocatorItEEE11__vallocateB9sqn220100Em
- __ZNSt3__16vectorItNS_9allocatorItEEE20__throw_length_errorB9sqn220100Ev
- __ZNSt3__16vectorItNS_9allocatorItEEEC2B9sqn220100Em
- __ZNSt3__19allocatorImE17allocate_at_leastB9sqn220100Em
- __ZNSt3__19allocatorItE17allocate_at_leastB9sqn220100Em
- __ZSt28__throw_bad_array_new_lengthB9sqn220100v
- ___50-[WBSPasswordBreachStore initWithBackingStoreURL:]_block_invoke
- ___51+[WBSTOTPGenerator _keyDataForBase32EncodedString:]_block_invoke
- ___74-[WBSManagedExtensionsController _managedExtensionConfigurationDidChange:]_block_invoke
- ___93-[WBSSavedAccountStore uniqueIdentifierCreatingIfNecessaryForSavedAccount:completionHandler:]_block_invoke_2
- ___block_descriptor_48_e8_32s40r_e20_v16?0"NSMapTable"8lr40l8s32l8
- ___block_descriptor_48_e8_32s40r_e43_v16?0"WBSPasswordWarningTopFraudTargets"8lr40l8s32l8
- ___block_descriptor_56_e8_32s40r48r_e45_"WBSPasswordWarning"16?0"WBSSavedAccount"8lr40l8s32l8r48l8
- ___block_descriptor_56_e8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
- ___block_descriptor_73_e8_32s40s48s56r64r_e5_v8?0ls32l8s40l8r56l8r64l8s48l8
- ___swift_closure_destructor.17Tm
- ___swift_closure_destructor.50Tm
- ___swift_closure_destructor.56Tm
- ___swift_closure_destructor.82Tm
- ___swift_closure_destructor.8Tm
- __keyDataForBase32EncodedString:.inverseAlphabet
- __keyDataForBase32EncodedString:.onceToken
- _objc_setProperty_atomic_copy
- _symbolic So7NSArrayC
- _symbolic _____ 10SafariCore35WBSAutomaticPasswordChangeUtilitiesV
CStrings:
+ "%lu passwords could not be fixed because Passwords could not access verification codes."
+ "-[WBSSavedAccountStore _addNewGroupToCachedSharingGroups:]"
+ "-[WBSSavedAccountStore _canMoveSavedAccountWithPasskey:toGroup:]"
+ "-[WBSSavedAccountStore _conflictExistsForSavedAccount:inGroupWithID:]"
+ "-[WBSSavedAccountStore _diagnosticStateDictionary]"
+ "-[WBSSavedAccountStore _persistentIdentifierForUser:host:]"
+ "-[WBSSavedAccountStore _saveUser:passkeyCredential:passkeyRelyingPartyID:]"
+ "-[WBSSavedAccountStore _updateLastOneTimeShareDateforSavedAccountIfNeeded:]"
+ "-[WBSSavedAccountStore allRecentlyDeletedSavedAccounts]"
+ "-[WBSSavedAccountStore canChangeSavedAccount:toUser:password:]"
+ "-[WBSSavedAccountStore canSaveUser:password:forProtectionSpace:highLevelDomain:notes:customTitle:groupID:error:]"
+ "-[WBSSavedAccountStore changeSavedAccount:toUser:password:]"
+ "-[WBSSavedAccountStore exportPasskeyCredentialWithID:]"
+ "-[WBSSavedAccountStore getSavedAccountsMatchingCriteria:withSynchronousCompletionHandler:]"
+ "-[WBSSavedAccountStore recentlyDeletedSavedAccountsForGroupWithID:]"
+ "-[WBSSavedAccountStore recentlyDeletedSavedAccountsInPersonalKeychain]"
+ "-[WBSSavedAccountStore removeHideWarningMarkerForSavedAccount:]"
+ "-[WBSSavedAccountStore removeTOTPGeneratorForSavedAccount:]"
+ "-[WBSSavedAccountStore saveUser:password:forProtectionSpace:highLevelDomain:customTitle:groupID:]"
+ "-[WBSSavedAccountStore savedAccountHasPasskeyPRFData:]"
+ "-[WBSSavedAccountStore savedAccountUUIDToSavedAccounts]"
+ "-[WBSSavedAccountStore savedAccountsForGroupID:]"
+ "-[WBSSavedAccountStore savedAccountsInPersonalKeychain]"
+ "-[WBSSavedAccountStore savedAccountsWithNeverSaveMarker]"
+ "-[WBSSavedAccountStore savedAccountsWithPasswords]"
+ "-[WBSSavedAccountStore setSavedAccountAsDefault:forProtectionSpace:context:associatedDomainsManager:]"
+ "-[WBSSavedAccountStore sharingGroupsWithRecentlyDeletedSavedAccounts]"
+ "-[WBSSavedAccountStore sharingGroupsWithSavedAccounts]"
+ "-[WBSSavedAccountStore shouldShowServiceNamesForPasswordAndPasskeyItems]"
+ "-[WBSSavedAccountStore test_loadSavedAccountsWithPasskeysFromPasskeyData:]"
+ "-[WBSSavedAccountStore test_setSharedAccountsGroups:]"
+ "Automatic Password Fix Cancelled"
+ "Cannot import passkey: another credential already exists for the same userHandle."
+ "Could not check existing passkeys for relying party: %{public}d"
+ "Could not derive protection space to salvage generated password for task with savedAccountUUID: %s"
+ "Could not save salvaged generated password for task with savedAccountUUID: %s"
+ "EnableRecentSearchesInStartPage"
+ "Failed to save generated password to WBSGeneratedPasswordStore; leaving task status unchanged for retry"
+ "Magic Extensions Account Added"
+ "Magic Extensions Account Modified"
+ "Magic Extensions Local Push Notification"
+ "Magic Extensions PCS Identities Changed"
+ "Magic Extensions Property Migration Update"
+ "Main thread waiting in %{public}s"
+ "PMAllowAutomaticPasswordChangeInDetailView"
+ "PMAutomaticPasswordChangeDebugForceFeatureEnabled"
+ "PMAutomaticPasswordChangeDebugSiteShouldEnableHardMode"
+ "PMAutomaticPasswordChangeDebugSiteShouldRequestOneTimeCode"
+ "PMAutomaticPasswordChangeShouldAdvanceManually"
+ "PMAutomaticPasswordChangeShouldShowWebView"
+ "PMAutomaticPasswordChangeShowSessionDoneButton"
+ "PMAutomaticPasswordChangeShowVerboseErrors"
+ "PasswordBreachStore.plist"
+ "Sync"
+ "Unexpected password breach store version %{public}lu in read-only store; ignoring contents."
+ "WBSDebugEnablePasswordChangeClassifier"
+ "WBSDebugLogFullAgentToolOutput"
+ "WBSDidApplyStartPageSectionPositionHealForRdar177455102"
+ "fileVaultRecoveryKey(volumeID:serialNumber:)"
+ "fileVaultRecoveryKeys(serialNumber:)"
- "\""
- "%lu passwords could not be fixed because Passwords could not access the verification codes."
- "Failed to save generated password to WBSGeneratedPasswordStore; leaving task as .inProgress for retry"
```
