## SafariCore

> `/System/Library/PrivateFrameworks/SafariCore.framework/SafariCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ed8b0` | `0x1f46a0` | **`+0x6df0`** |
| `__DATA.__bss` | `0xa420` | `0xa730` | **`+0x310`** |
| `__AUTH_CONST.__const` | `0xb048` | `0xb328` | **`+0x2e0`** |
| `__TEXT.__oslogstring` | `0xe371` | `0xe651` | **`+0x2e0`** |
| `__AUTH_CONST.__objc_const` | `0x16308` | `0x165e0` | **`+0x2d8`** |
| `__TEXT.__const` | `0x7aa4` | `0x7d24` | **`+0x280`** |
| `__TEXT.__objc_methlist` | `0xd124` | `0xd2ec` | **`+0x1c8`** |
| `__AUTH.__objc_data` | `0x2220` | `0x23a8` | **`+0x188`** |
| `__TEXT.__unwind_info` | `0x9b78` | `0x9cf0` | **`+0x178`** |
| `__TEXT.__constg_swiftt` | `0x21f4` | `0x2340` | **`+0x14c`** |
| `__DATA.__data` | `0x3560` | `0x36a0` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x59b8` | `0x5ad8` | **`+0x120`** |
| `__TEXT.__gcc_except_tab` | `0x77c8` | `0x78c0` | **`+0xf8`** |
| `__TEXT.__swift5_typeref` | `0x25c2` | `0x26ba` | **`+0xf8`** |
| `__DATA_CONST.__objc_selrefs` | `0x7608` | `0x76d0` | **`+0xc8`** |
| `__TEXT.__swift5_capture` | `0x1490` | `0x1538` | **`+0xa8`** |
| `__TEXT.__cstring` | `0x17047` | `0x170e7` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x1990` | `0x1a30` | **`+0xa0`** |
| `__AUTH.__data` | `0x1010` | `0x1080` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x14fb` | `0x156b` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0xa430` | `0xa460` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x608` | `0x638` | **`+0x30`** |
| `__DATA.__common` | `0x88` | `0xa8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x13b0` | `0x13c8` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x4c8` | `0x4e0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x140` | `0x154` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x6f8` | `0x708` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x210` | `0x21c` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0xd30` | `0xd34` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x2c` | `0x30` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x32c` | `0x328` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x37c` | `0x378` | **`-0x4`** |

### Other Changes

```diff

-625.1.29.10.29
+625.2.4.1.0

-  Functions: 11246
-  Symbols:   12025
-  CStrings:  5271
+  Functions: 11385
+  Symbols:   12090
+  CStrings:  5283
Symbols:
+ +[NSURLSessionConfiguration(SafariCoreExtras) safari_persistentStateSessionConfiguration]
+ +[WBSFeatureAvailability automaticPasswordChangeShouldAlwaysRecommend]
+ +[WBSFeatureAvailability isAutomaticPasswordChangeTestFestModeEnabled]
+ +[WBSFeatureAvailability setAutomaticPasswordChangeTestFestModeEnabled:]
+ +[WBSSavedAccount isDebugAccountForAutomaticPasswordChangeForDomain:]
+ +[WBSSavedAccount isUUIDHighLevelDomain:]
+ -[NSURLProtectionSpace(SafariCoreExtras) safari_getAllowsCredentialSavingWithCompletionHandler:]
+ -[WBSPasswordWarningTopFraudTargets emailProviderFraudTargets]
+ -[WBSPasswordWarningTopFraudTargets initWithHighPriorityTargets:targets:financialTargets:emailProviderFraudTargets:]
+ -[WBSSavedAccount _adoptSidecarDataFromSavedAccount:]
+ -[WBSSavedAccountStore _logSavedAccountsWithTOTPGeneratorsOnlyInPasskeySidecars:]
+ -[WBSSavedAccountStore _savedAccountConflictingWithSavedAccountOnInternalQueue:afterUpdatingUsername:password:]
+ -[WBSSavedAccountStore canSaveUser:password:forProtectionSpace:highLevelDomain:notes:customTitle:groupID:completionHandler:]
+ -[WBSSavedAccountStore canSaveUser:password:forUserTypedSite:notes:customTitle:groupID:completionHandler:]
+ GCC_except_table127
+ GCC_except_table140
+ GCC_except_table142
+ GCC_except_table182
+ GCC_except_table232
+ GCC_except_table235
+ GCC_except_table239
+ GCC_except_table313
+ GCC_except_table352
+ GCC_except_table420
+ GCC_except_table422
+ _OBJC_CLASS_$_WBSGuidedBrowsingNavigationEvent
+ _OBJC_CLASS_$_WBSRunLoopCoalescedUpdate
+ _OBJC_IVAR_$_WBSPasswordWarningTopFraudTargets._emailProviderFraudTargets
+ _OBJC_METACLASS_$_WBSGuidedBrowsingNavigationEvent
+ _OBJC_METACLASS_$_WBSRunLoopCoalescedUpdate
+ _WBSAutomaticPasswordChangeDebugLogAutoFilledDataKey
+ _WBSOSLogSearchFeatureAvailability
+ _WBSOSLogSearchFeatureAvailability.log
+ _WBSOSLogSearchFeatureAvailability.onceToken
+ __CLASS_METHODS_WBSGuidedBrowsingNavigationEvent
+ __CLASS_PROPERTIES_WBSGuidedBrowsingNavigationEvent
+ __DATA_WBSGuidedBrowsingNavigationEvent
+ __DATA_WBSRunLoopCoalescedUpdate
+ __INSTANCE_METHODS_WBSGuidedBrowsingNavigationEvent
+ __INSTANCE_METHODS_WBSRunLoopCoalescedUpdate
+ __IVARS_WBSGuidedBrowsingNavigationEvent
+ __IVARS_WBSRunLoopCoalescedUpdate
+ __IVARS__TtCE10SafariCoreV15Synchronization5MutexP33_5EB6CF0E21105A7FACDF3B64E2151CBD10SendingBox
+ __METACLASS_DATA_WBSGuidedBrowsingNavigationEvent
+ __METACLASS_DATA_WBSRunLoopCoalescedUpdate
+ __OBJC_$_INSTANCE_METHODS_WBSSavedAccountChangeRequest(SafariCore)
+ __PROPERTIES_WBSGuidedBrowsingNavigationEvent
+ __PROPERTIES_WBSRunLoopCoalescedUpdate
+ __PROTOCOLS_WBSGuidedBrowsingNavigationEvent
+ __ZL30configureCommonSessionSettingsP25NSURLSessionConfiguration
+ ___111-[WBSSavedAccountStore _savedAccountConflictingWithSavedAccountOnInternalQueue:afterUpdatingUsername:password:]_block_invoke
+ ___124-[WBSSavedAccountStore canSaveUser:password:forProtectionSpace:highLevelDomain:notes:customTitle:groupID:completionHandler:]_block_invoke
+ ___49-[WBSSavedAccount lastUsedDateForSite:inContext:]_block_invoke
+ ___81-[WBSSavedAccountStore _logSavedAccountsWithTOTPGeneratorsOnlyInPasskeySidecars:]_block_invoke
+ ___81-[WBSSavedAccountStore _logSavedAccountsWithTOTPGeneratorsOnlyInPasskeySidecars:]_block_invoke_2
+ ___94-[WBSSavedAccountStore canSaveUser:password:forUserTypedSite:notes:customTitle:groupID:error:]_block_invoke
+ ___96-[NSURLProtectionSpace(SafariCoreExtras) safari_getAllowsCredentialSavingWithCompletionHandler:]_block_invoke
+ ___96-[NSURLProtectionSpace(SafariCoreExtras) safari_getAllowsCredentialSavingWithCompletionHandler:]_block_invoke_2
+ ___WBSOSLogSearchFeatureAvailability_block_invoke
+ ___block_descriptor_32_e30_B16?0"WBSSavedAccountMatch"8l
+ ___block_descriptor_40_e8_32bs_e36_v16?0"WBSSavedAccountMatchResult"8ls32l8
+ ___block_descriptor_40_e8_32r_e49_v32?0q8"<WBSSavedAccountSidecarInternal>"16^B24lr32l8
+ ___block_descriptor_41_e8_32s_e46_v32?0"NSString"8"NSMutableDictionary"16^B24ls32l8
+ ___block_descriptor_48_e8_32s40r_e8_v12?0B8lr40l8s32l8
+ ___block_descriptor_56_e8_32s40r48r_e20_v20?0B8"NSError"12lr40l8r48l8s32l8
+ ___block_descriptor_56_e8_32s40s48r_e46_v32?0"NSString"8"NSMutableDictionary"16^B24lr48l8s32l8s40l8
+ ___block_descriptor_73_e8_32s40s48s56s64r_e42_v32?0"NSString"8"WBSSavedAccount"16^B24ls32l8s40l8s48l8s56l8r64l8
+ ___block_descriptor_96_e8_32s40s48s56s64s72s80s88bs_e5_v8?0ls32l8s40l8s48l8s88l8s56l8s64l8s72l8s80l8
+ ___swift_closure_destructor.125Tm
+ ___swift_closure_destructor.242Tm
+ ___swift_closure_destructor.252Tm
+ ___swift_closure_destructor.433Tm
+ ___swift_closure_destructor.491Tm
+ ___swift_closure_destructor.54Tm
+ ___swift_closure_destructor.58Tm
+ ___swift_closure_destructor.611Tm
+ ___unnamed_2
+ _associated conformance So13NSRunLoopModeaSHSCSQ
+ _associated conformance So13NSRunLoopModeas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So13NSRunLoopModeas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _automaticPasswordChangeTestFestModeEnabled
+ _symbolic $s10SafariCore45WBSAutomaticPasswordChangeCompletionReportingP
+ _symbolic Shy_____G 10Foundation4UUIDV
+ _symbolic So25WBSRunLoopCoalescedUpdateCSgXw
+ _symbolic _____ 10SafariCore32WBSGuidedBrowsingNavigationEventC
+ _symbolic _____ 15Synchronization5MutexV10SafariCoreE10SendingBox33_5EB6CF0E21105A7FACDF3B64E2151CBDLLC
+ _symbolic _____ So13NSRunLoopModea
+ _symbolic _____SgXwz_Xx 10SafariCore27WBSGuidedBrowsingControllerC
+ _symbolic ______pIeghg_ 10SafariCore39WBSGuidedBrowsingUIRegistrationProtocolP
+ _symbolic _____m 10SafariCore32WBSGuidedBrowsingNavigationEventC
+ _symbolic _____ySbG 15Synchronization6AtomicV
+ _symbolic _____yShy_____GG 15Synchronization5MutexVAARi_zrlE 10Foundation4UUIDV
+ _symbolic _____ySo15NSXPCConnectionCSgG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation4UUIDV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So13NSRunLoopModea
+ _symbolic _____yxG 15Synchronization5MutexVAARi_zrlE
- +[WBSFeatureAvailability isAllowFavoritesInFrequentlyVisitedEnabled]
- +[WBSFeatureAvailability isAllowLogOnURLsInFrequentlyVisitedEnabled]
- +[WBSFeatureAvailability isDropOutliersInFrequentlyVisitedEnabled]
- -[WBSPasswordWarningTopFraudTargets initWithHighPriorityTargets:targets:financialTargets:]
- -[WBSWellKnownChangePasswordURLFallbackController didFinishLoad]
- GCC_except_table124
- GCC_except_table134
- GCC_except_table176
- GCC_except_table206
- GCC_except_table240
- GCC_except_table304
- GCC_except_table311
- GCC_except_table343
- GCC_except_table413
- GCC_except_table418
- _WBSEnableDropOutliersInFrequentlyVisitedKey
- _WBSFrequentlyVisitedSitesAllowLogonURLsPreferenceKey
- _WBSFrequentlyVisitedSitesAllowSitesFromFavoritesPreferenceKey
- __OBJC_$_CLASS_PROP_LIST_NSURLSessionConfiguration_$_SafariCoreExtras
- __OBJC_$_INSTANCE_METHODS_WBSSavedAccountChangeRequest
- ___block_descriptor_104_e8_32s40s48s56s64s72s80s88r96r_e5_v8?0ls32l8s40l8r88l8r96l8s48l8s56l8s64l8s72l8s80l8
- ___block_descriptor_48_e8_32s40s_e46_v32?0"NSString"8"NSMutableDictionary"16^B24ls32l8s40l8
- ___swift_closure_destructor.236Tm
- ___swift_closure_destructor.246Tm
- ___swift_closure_destructor.427Tm
- ___swift_closure_destructor.485Tm
- ___swift_closure_destructor.53Tm
- ___swift_closure_destructor.57Tm
- ___swift_closure_destructor.605Tm
- _symbolic So15NSXPCConnectionC
- _symbolic _____y_____G s23_ContiguousArrayStorageC 10SafariCore26WBSLocalizedPluralVariableV
CStrings:
+ "-[WBSSavedAccountStore canSaveUser:password:forUserTypedSite:notes:customTitle:groupID:error:]"
+ "Connected to broker"
+ "Error reporting navigation state to broker: %{public}s"
+ "Exceeded %.2f sec timeout while checking wheather credential saving is allowed for %{sensitive}@"
+ "Expired %.2f timeout waiting for canSaveUser:password: call to resolve"
+ "Expired %.2f timeout waiting for canSaveUser:password:forProtectionSpace: to complete"
+ "Expired timeout waiting for canSaveUser:password:forProtectionSpace: to complete"
+ "Found %lu saved account(s) with a TOTP generator in a passkey sidecar but not in a password sidecar"
+ "Found saved account for '%{sensitive}@' on %{sensitive}@ that will conflict with saved account for '%{sensitive}@' after updating username"
+ "Guided browser connection dropped during teardown; not reconnecting"
+ "PMAutomaticPasswordChangeDebugLogAutoFilledData"
+ "SafariCore.WBSGuidedBrowsingNavigationEvent"
+ "SafariCore.WBSRunLoopCoalescedUpdate"
+ "SearchFeatureAvailability"
+ "Unable to decode target URL for navigation event"
+ "WBSGuidedBrowsingNavigationEvent { targetURL (hash) = "
+ "currentURLChanged"
+ "emailProviderFraudTargets"
+ "reportNavigationEvent"
- "EnableDropOutliersInFrequentlyVisited"
- "FrequentlyVisitedSitesAllowLogonURLs"
- "FrequentlyVisitedSitesAllowSitesFromFavorites"
- "New strong password has been saved for %ld"
- "New strong passwords have been saved for %ld"
- "New strong passwords have been saved for %ld out of %ld accounts."
- "strongPasswordsMessage"
```
