## ScreenTimeCore

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe6444` | `0xf2d20` | **`+0xc8dc`** |
| `__DATA_DIRTY.__objc_data` | `0x10e0` | `0x1f18` | **`+0xe38`** |
| `__AUTH.__objc_data` | `0x3c58` | `0x31a0` | **`-0xab8`** |
| `__AUTH_CONST.__const` | `0x2978` | `0x32d8` | **`+0x960`** |
| `__TEXT.__eh_frame` | `0x31e8` | `0x3b40` | **`+0x958`** |
| `__AUTH_CONST.__objc_const` | `0x12958` | `0x13190` | **`+0x838`** |
| `__TEXT.__oslogstring` | `0xb43a` | `0xba7a` | **`+0x640`** |
| `__TEXT.__objc_methlist` | `0x9bf0` | `0xa0f0` | **`+0x500`** |
| `__TEXT.__unwind_info` | `0x3990` | `0x3d78` | **`+0x3e8`** |
| `__TEXT.__const` | `0x2ee8` | `0x3288` | **`+0x3a0`** |
| `__TEXT.__swift5_typeref` | `0x10d8` | `0x144e` | **`+0x376`** |
| `__TEXT.__swift5_capture` | `0x714` | `0xa58` | **`+0x344`** |
| `__DATA.__bss` | `0x3c80` | `0x3f80` | **`+0x300`** |
| `__TEXT.__cstring` | `0xa15c` | `0xa45c` | **`+0x300`** |
| `__DATA.__data` | `0x1f40` | `0x2190` | **`+0x250`** |
| `__DATA_CONST.__objc_selrefs` | `0x51d8` | `0x53a8` | **`+0x1d0`** |
| `__AUTH_CONST.__cfstring` | `0x9620` | `0x97c0` | **`+0x1a0`** |
| `__DATA_DIRTY.__data` | `0x120` | `0x278` | **`+0x158`** |
| `__TEXT.__constg_swiftt` | `0xbc4` | `0xd0c` | **`+0x148`** |
| `__AUTH_CONST.__auth_got` | `0x1088` | `0x1180` | **`+0xf8`** |
| `__DATA_CONST.__got` | `0xdb8` | `0xe98` | **`+0xe0`** |
| `__TEXT.__swift5_fieldmd` | `0x8e0` | `0x9a8` | **`+0xc8`** |
| `__TEXT.__swift5_reflstr` | `0x6fe` | `0x79e` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x1bcc` | `0x1b30` | **`-0x9c`** |
| `__AUTH.__data` | `0x568` | `0x4f8` | **`-0x70`** |
| `__TEXT.__swift_as_cont` | `0x1a8` | `0x210` | **`+0x68`** |
| `__TEXT.__swift5_builtin` | `0xb4` | `0xf0` | **`+0x3c`** |
| `__DATA.__objc_ivar` | `0x784` | `0x7bc` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x1c40` | `0x1c78` | **`+0x38`** |
| `__DATA_CONST.__objc_classlist` | `0x6b0` | `0x6e0` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x108` | `0x138` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x11c` | `0x148` | **`+0x2c`** |
| `__TEXT.__swift_as_ret` | `0x13c` | `0x168` | **`+0x2c`** |
| `__DATA_CONST.__objc_protolist` | `0x220` | `0x240` | **`+0x20`** |
| `__DATA.__common` | `0xb8` | `0xd0` | **`+0x18`** |
| `__DATA_DIRTY.__common` | `0x18` | `0x30` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x1f8` | `0x210` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0xd0` | `0xe8` | **`+0x18`** |
| `__DATA_CONST.__objc_protorefs` | `0x128` | `0x138` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x4b8` | `0x4c0` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x10` | `0x18` | **`+0x8`** |

### Other Changes

```diff

-640.0.100.0.0
+645.1.100.0.0

+  - /usr/lib/swift/libswiftObservation.dylib

-  Functions: 5481
-  Symbols:   6565
-  CStrings:  2196
+  Functions: 5821
+  Symbols:   6728
+  CStrings:  2231
Symbols:
+ +[STCoreUser(UnmodeledInternal) keyPathsForValuesAffectingContentPrivacySensitiveTopicsRestriction]
+ +[STCoreUser(UnmodeledInternal) keyPathsForValuesAffectingContentPrivacySiriAIRestriction]
+ +[STCoreUser(UnmodeledInternal) keyPathsForValuesAffectingContentPrivacySiriRealisticImageGenerationRestriction]
+ -[STAppInfo ratingRank]
+ -[STAppInfo setRatingRank:]
+ -[STCoreOrganizationSettings contentPrivacySensitiveTopicsRestriction]
+ -[STCoreOrganizationSettings contentPrivacySiriAIRestriction]
+ -[STCoreOrganizationSettings contentPrivacySiriRealisticImageGenerationRestriction]
+ -[STCoreOrganizationSettings setContentPrivacySensitiveTopicsRestriction:]
+ -[STCoreOrganizationSettings setContentPrivacySiriAIRestriction:]
+ -[STCoreOrganizationSettings setContentPrivacySiriRealisticImageGenerationRestriction:]
+ -[STCoreUser(UnmodeledInternal) contentPrivacySensitiveTopicsRestriction]
+ -[STCoreUser(UnmodeledInternal) contentPrivacySiriAIRestriction]
+ -[STCoreUser(UnmodeledInternal) contentPrivacySiriRealisticImageGenerationRestriction]
+ -[STCoreUser(UnmodeledInternal) setContentPrivacySensitiveTopicsRestriction:]
+ -[STCoreUser(UnmodeledInternal) setContentPrivacySiriAIRestriction:]
+ -[STCoreUser(UnmodeledInternal) setContentPrivacySiriRealisticImageGenerationRestriction:]
+ -[STManagementState shouldAllowOneMoreMinuteForBundleIdentifier:completionHandler:]
+ -[STManagementState shouldAllowOneMoreMinuteForCategoryIdentifier:completionHandler:]
+ -[STManagementState shouldAllowOneMoreMinuteForWebDomain:completionHandler:]
+ -[STRegulatoryIntelligenceSiriPolicy extensionsEditable]
+ -[STRegulatoryIntelligenceSiriPolicy extensionsFooter]
+ -[STRegulatoryIntelligenceSiriPolicy extensionsForcedToBlocked]
+ -[STRegulatoryIntelligenceSiriPolicy init]
+ -[STRegulatoryIntelligenceSiriPolicy realisticImagesEditable]
+ -[STRegulatoryIntelligenceSiriPolicy realisticImagesFooter]
+ -[STRegulatoryIntelligenceSiriPolicy realisticImagesForcedToOff]
+ -[STRegulatoryIntelligenceSiriPolicy sensitiveTopicsEditable]
+ -[STRegulatoryIntelligenceSiriPolicy sensitiveTopicsForcedToReduce]
+ -[STRegulatoryIntelligenceSiriPolicy setExtensionsEditable:]
+ -[STRegulatoryIntelligenceSiriPolicy setExtensionsFooter:]
+ -[STRegulatoryIntelligenceSiriPolicy setExtensionsForcedToBlocked:]
+ -[STRegulatoryIntelligenceSiriPolicy setRealisticImagesEditable:]
+ -[STRegulatoryIntelligenceSiriPolicy setRealisticImagesFooter:]
+ -[STRegulatoryIntelligenceSiriPolicy setRealisticImagesForcedToOff:]
+ -[STRegulatoryIntelligenceSiriPolicy setSensitiveTopicsEditable:]
+ -[STRegulatoryIntelligenceSiriPolicy setSensitiveTopicsForcedToReduce:]
+ -[STRegulatoryIntelligenceSiriPolicy setSiriAIEditable:]
+ -[STRegulatoryIntelligenceSiriPolicy setSiriAIFooter:]
+ -[STRegulatoryIntelligenceSiriPolicy setSiriAIForcedToOff:]
+ -[STRegulatoryIntelligenceSiriPolicy siriAIEditable]
+ -[STRegulatoryIntelligenceSiriPolicy siriAIFooter]
+ -[STRegulatoryIntelligenceSiriPolicy siriAIForcedToOff]
+ -[STRegulatoryPolicy intelligenceSiri]
+ -[STRegulatoryPolicy setIntelligenceSiri:]
+ -[STRegulatoryWebContentFilterPolicy setShieldVariant:]
+ -[STRegulatoryWebContentFilterPolicy shieldVariant]
+ GCC_except_table189
+ GCC_except_table192
+ GCC_except_table201
+ GCC_except_table210
+ GCC_except_table54
+ _OBJC_CLASS_$_NSLock
+ _OBJC_CLASS_$_STRegulatoryIntelligenceSiriPolicy
+ _OBJC_CLASS_$_STScreenTimeWebBrowserHistory
+ _OBJC_CLASS_$_STScreenTimeWebBrowserSettings
+ _OBJC_CLASS_$_STScreenTimeWebBrowserSettingsObserver
+ _OBJC_IVAR_$_STAppInfo._ratingRank
+ _OBJC_IVAR_$_STRegulatoryIntelligenceSiriPolicy._extensionsEditable
+ _OBJC_IVAR_$_STRegulatoryIntelligenceSiriPolicy._extensionsFooter
+ _OBJC_IVAR_$_STRegulatoryIntelligenceSiriPolicy._extensionsForcedToBlocked
+ _OBJC_IVAR_$_STRegulatoryIntelligenceSiriPolicy._realisticImagesEditable
+ _OBJC_IVAR_$_STRegulatoryIntelligenceSiriPolicy._realisticImagesFooter
+ _OBJC_IVAR_$_STRegulatoryIntelligenceSiriPolicy._realisticImagesForcedToOff
+ _OBJC_IVAR_$_STRegulatoryIntelligenceSiriPolicy._sensitiveTopicsEditable
+ _OBJC_IVAR_$_STRegulatoryIntelligenceSiriPolicy._sensitiveTopicsForcedToReduce
+ _OBJC_IVAR_$_STRegulatoryIntelligenceSiriPolicy._siriAIEditable
+ _OBJC_IVAR_$_STRegulatoryIntelligenceSiriPolicy._siriAIFooter
+ _OBJC_IVAR_$_STRegulatoryIntelligenceSiriPolicy._siriAIForcedToOff
+ _OBJC_IVAR_$_STRegulatoryPolicy._intelligenceSiri
+ _OBJC_IVAR_$_STRegulatoryWebContentFilterPolicy._shieldVariant
+ _OBJC_METACLASS_$_STRegulatoryIntelligenceSiriPolicy
+ _OBJC_METACLASS_$_STScreenTimeWebBrowserHistory
+ _OBJC_METACLASS_$_STScreenTimeWebBrowserSettings
+ _OBJC_METACLASS_$_STScreenTimeWebBrowserSettingsObserver
+ _OBJC_METACLASS_$__TtCE14ScreenTimeCoreCSo29STScreenTimeWebBrowserHistoryP33_C1361D6D4F858D96C532ECBA2F242AAC5Store
+ _OBJC_METACLASS_$__TtCE14ScreenTimeCoreCSo38STScreenTimeWebBrowserSettingsObserverP33_C1D88EBD6D178F2084F8C827022CEF0E8Settings
+ _STUserDefaultsKeyUpgradeEligibilityCheckIntervalSeconds
+ __DATA_STScreenTimeWebBrowserHistory
+ __DATA_STScreenTimeWebBrowserSettings
+ __DATA_STScreenTimeWebBrowserSettingsObserver
+ __DATA__TtCE14ScreenTimeCoreCSo29STScreenTimeWebBrowserHistoryP33_C1361D6D4F858D96C532ECBA2F242AAC5Store
+ __DATA__TtCE14ScreenTimeCoreCSo38STScreenTimeWebBrowserSettingsObserverP33_C1D88EBD6D178F2084F8C827022CEF0E8Settings
+ __INSTANCE_METHODS_STScreenTimeWebBrowserHistory
+ __INSTANCE_METHODS_STScreenTimeWebBrowserSettings
+ __INSTANCE_METHODS_STScreenTimeWebBrowserSettingsObserver
+ __INSTANCE_METHODS__TtCE14ScreenTimeCoreCSo29STScreenTimeWebBrowserHistoryP33_C1361D6D4F858D96C532ECBA2F242AAC5Store
+ __INSTANCE_METHODS__TtCE14ScreenTimeCoreCSo38STScreenTimeWebBrowserSettingsObserverP33_C1D88EBD6D178F2084F8C827022CEF0E8Settings
+ __IVARS_STScreenTimeWebBrowserHistory
+ __IVARS_STScreenTimeWebBrowserSettings
+ __IVARS_STScreenTimeWebBrowserSettingsObserver
+ __IVARS__TtCE14ScreenTimeCoreCSo29STScreenTimeWebBrowserHistoryP33_C1361D6D4F858D96C532ECBA2F242AAC5Store
+ __IVARS__TtCE14ScreenTimeCoreCSo38STScreenTimeWebBrowserSettingsObserverP33_C1D88EBD6D178F2084F8C827022CEF0E8Settings
+ __METACLASS_DATA_STScreenTimeWebBrowserHistory
+ __METACLASS_DATA_STScreenTimeWebBrowserSettings
+ __METACLASS_DATA_STScreenTimeWebBrowserSettingsObserver
+ __METACLASS_DATA__TtCE14ScreenTimeCoreCSo29STScreenTimeWebBrowserHistoryP33_C1361D6D4F858D96C532ECBA2F242AAC5Store
+ __METACLASS_DATA__TtCE14ScreenTimeCoreCSo38STScreenTimeWebBrowserSettingsObserverP33_C1D88EBD6D178F2084F8C827022CEF0E8Settings
+ __OBJC_$_INSTANCE_METHODS_STRegulatoryIntelligenceSiriPolicy
+ __OBJC_$_INSTANCE_VARIABLES_STRegulatoryIntelligenceSiriPolicy
+ __OBJC_$_PROP_LIST_STRegulatoryIntelligenceSiriPolicy
+ __OBJC_$_PROP_LIST_STScreenTimeSettingsWebBrowserHistoryStoring
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_STScreenTimeObservableWebBrowserSettings
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_STScreenTimeSettingsWebBrowserHistoryStoring
+ __OBJC_$_PROTOCOL_METHOD_TYPES_STScreenTimeObservableWebBrowserSettings
+ __OBJC_$_PROTOCOL_METHOD_TYPES_STScreenTimeSettingsWebBrowserHistoryStoring
+ __OBJC_$_PROTOCOL_REFS_STScreenTimeObservableWebBrowserSettings
+ __OBJC_$_PROTOCOL_REFS_STScreenTimeSettingsWebBrowserHistoryStoring
+ __OBJC_CLASS_RO_$_STRegulatoryIntelligenceSiriPolicy
+ __OBJC_LABEL_PROTOCOL_$_STScreenTimeObservableWebBrowserSettings
+ __OBJC_LABEL_PROTOCOL_$_STScreenTimeSettingsWebBrowserHistoryStoring
+ __OBJC_METACLASS_RO_$_STRegulatoryIntelligenceSiriPolicy
+ __OBJC_PROTOCOL_$_STScreenTimeObservableWebBrowserSettings
+ __OBJC_PROTOCOL_$_STScreenTimeSettingsWebBrowserHistoryStoring
+ __PROPERTIES_STScreenTimeWebBrowserHistory
+ __PROPERTIES_STScreenTimeWebBrowserSettings
+ __PROPERTIES_STScreenTimeWebBrowserSettingsObserver
+ __PROPERTIES__TtCE14ScreenTimeCoreCSo29STScreenTimeWebBrowserHistoryP33_C1361D6D4F858D96C532ECBA2F242AAC5Store
+ __PROTOCOLS__TtCE14ScreenTimeCoreCSo29STScreenTimeWebBrowserHistoryP33_C1361D6D4F858D96C532ECBA2F242AAC5Store
+ __PROTOCOLS__TtCE14ScreenTimeCoreCSo38STScreenTimeWebBrowserSettingsObserverP33_C1D88EBD6D178F2084F8C827022CEF0E8Settings
+ ___76-[STManagementState shouldAllowOneMoreMinuteForWebDomain:completionHandler:]_block_invoke
+ ___76-[STManagementState shouldAllowOneMoreMinuteForWebDomain:completionHandler:]_block_invoke_2
+ ___76-[STManagementState shouldAllowOneMoreMinuteForWebDomain:completionHandler:]_block_invoke_3
+ ___76-[STManagementState shouldAllowOneMoreMinuteForWebDomain:completionHandler:]_block_invoke_4
+ ___83-[STManagementState shouldAllowOneMoreMinuteForBundleIdentifier:completionHandler:]_block_invoke
+ ___83-[STManagementState shouldAllowOneMoreMinuteForBundleIdentifier:completionHandler:]_block_invoke_2
+ ___83-[STManagementState shouldAllowOneMoreMinuteForBundleIdentifier:completionHandler:]_block_invoke_3
+ ___83-[STManagementState shouldAllowOneMoreMinuteForBundleIdentifier:completionHandler:]_block_invoke_4
+ ___85-[STManagementState shouldAllowOneMoreMinuteForCategoryIdentifier:completionHandler:]_block_invoke
+ ___85-[STManagementState shouldAllowOneMoreMinuteForCategoryIdentifier:completionHandler:]_block_invoke_2
+ ___85-[STManagementState shouldAllowOneMoreMinuteForCategoryIdentifier:completionHandler:]_block_invoke_3
+ ___85-[STManagementState shouldAllowOneMoreMinuteForCategoryIdentifier:completionHandler:]_block_invoke_4
+ ___swift_closure_destructor.20Tm
+ ___swift_closure_destructor.26Tm
+ ___swift_closure_destructor.30Tm
+ ___swift_memcpy25_8
+ _associated conformance So18STFamilyMemberTypeaSHSCSQ
+ _associated conformance So18STFamilyMemberTypeas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So18STFamilyMemberTypeas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _get_enum_tag_for_layout_string 14ScreenTimeCore22RestrictionQueryResult33_85746A119BB273F4CF13C31ED127C550LLO
+ _keypath_get_selector_hasMigrated
+ _keypath_get_selector_hasPasscode
+ _keypath_get_selector_webBrowserSettings
+ _swift_release_x10
+ _swift_release_x9
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
+ _symbolic S2bIegyy_
+ _symbolic Say_____G 8Dispatch0A13WorkItemFlagsV
+ _symbolic ScTyyt_____GSg s5NeverO
+ _symbolic Shy_____GSg______pSgIeggg_ 10Foundation3URLV s5ErrorP
+ _symbolic So26NSSecurityScopedURLWrapperCSg
+ _symbolic So29STScreenTimeWebBrowserHistoryC
+ _symbolic So34STRegulatoryIntelligenceSiriPolicyCIeyBa_
+ _symbolic So34STRegulatoryIntelligenceSiriPolicyCyc
+ _symbolic So38STScreenTimeWebBrowserSettingsObserverC
+ _symbolic So38STScreenTimeWebBrowserSettingsObserverCSgXw
+ _symbolic So38STScreenTimeWebBrowserSettingsObserverCSgXwz_Xx
+ _symbolic So5NSSetCSgSo7NSErrorCSgIeyByy_
+ _symbolic So6NSLockC
+ _symbolic So8NSNumberCSgSo7NSErrorCSgIeyByy_Sg
+ _symbolic So8NSStringC_____IeyByd_ So14AKUserAgeRangeV
+ _symbolic _____ 10Foundation12DateIntervalV
+ _symbolic _____ 10Foundation3URLV
+ _symbolic _____ 14ScreenTimeCore17OneMoreMinuteGateO
+ _symbolic _____ 14ScreenTimeCore22RestrictionQueryResult33_85746A119BB273F4CF13C31ED127C550LLO
+ _symbolic _____ 26ScreenTimeSettingsServices0ab10WebBrowserC0C
+ _symbolic _____ So14AKUserAgeRangeV
+ _symbolic _____ So18STFamilyMemberTypea
+ _symbolic _____ So29STScreenTimeWebBrowserHistoryC06ScreenB4CoreE5Store33_C1361D6D4F858D96C532ECBA2F242AACLLC
+ _symbolic _____ So38STScreenTimeWebBrowserSettingsObserverC06ScreenB4CoreE0E033_C1D88EBD6D178F2084F8C827022CEF0ELLC
+ _symbolic _____14passcodePolicy______14migrationStatet 26ScreenTimeSettingsServices0abC0C13FeaturePolicyO AC9MigrationV5StateO
+ _symbolic _____14passcodePolicy______14migrationStatetSg 26ScreenTimeSettingsServices0abC0C13FeaturePolicyO AC9MigrationV5StateO
+ _symbolic _____AAIeyByy_ 10ObjectiveC8ObjCBoolV
+ _symbolic _____SSc So14AKUserAgeRangeV
+ _symbolic _____Sg 26ScreenTimeSettingsServices0ab10WebBrowserC0C
+ _symbolic _____Sg 26ScreenTimeSettingsServices0abC0C19ContentRestrictionsV020RatingsForRestrictedE0V
+ _symbolic _____Sg 26ScreenTimeSettingsServices0abC0C9MigrationV5StateO
+ _symbolic _____Sg16familyMemberType_SSSg7altDSIDt So18STFamilyMemberTypea
+ _symbolic _____SgXw 26ScreenTimeSettingsServices0abC0C
+ _symbolic _____Sg_ABt 26ScreenTimeSettingsServices0abC0C9MigrationV5StateO
+ _symbolic _____SgycSg 26ScreenTimeSettingsServices0abC0C19ContentRestrictionsV020RatingsForRestrictedE0V
+ _symbolic _____y_____14passcodePolicy______14migrationStatet_____G 11Observation12ObservationsV 26ScreenTimeSettingsServices0cdE0C13FeaturePolicyO AF9MigrationV5StateO s5NeverO
+ _symbolic _____y_____14passcodePolicy______14migrationStatet______G 11Observation12ObservationsV8IteratorV 26ScreenTimeSettingsServices0deF0C13FeaturePolicyO AH9MigrationV5StateO s5NeverO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 26ScreenTimeSettingsServices0deF0C19ContentRestrictionsV21RatingRestrictionNameV
+ _type_layout_string 14ScreenTimeCore22RestrictionQueryResult33_85746A119BB273F4CF13C31ED127C550LLO
- +[STRestrictionsFetcher fetchRestrictionsForUserDSID:persistenceController:completionHandler:]
- -[STManagementState shouldAllowOneMoreMinuteForBundleIdentifier:error:]
- -[STManagementState shouldAllowOneMoreMinuteForCategoryIdentifier:error:]
- -[STManagementState shouldAllowOneMoreMinuteForWebDomain:error:]
- GCC_except_table148
- GCC_except_table151
- GCC_except_table154
- GCC_except_table183
- GCC_except_table186
- GCC_except_table195
- GCC_except_table198
- GCC_except_table37
- GCC_except_table52
- GCC_except_table62
- GCC_except_table65
- ___64-[STManagementState shouldAllowOneMoreMinuteForWebDomain:error:]_block_invoke
- ___64-[STManagementState shouldAllowOneMoreMinuteForWebDomain:error:]_block_invoke_2
- ___71-[STManagementState shouldAllowOneMoreMinuteForBundleIdentifier:error:]_block_invoke
- ___71-[STManagementState shouldAllowOneMoreMinuteForBundleIdentifier:error:]_block_invoke_2
- ___73-[STManagementState shouldAllowOneMoreMinuteForCategoryIdentifier:error:]_block_invoke
- ___73-[STManagementState shouldAllowOneMoreMinuteForCategoryIdentifier:error:]_block_invoke_2
- ___swift_closure_destructor.21Tm
- _swift_unknownObjectRetain_n
- _symbolic _____y______G 26ScreenTimeSettingsServices0abC0C0C10CollectionV AC0B10AllowancesV5GroupV5EntryV
CStrings:
+ "%s: could not form URL for web domain, failing open"
+ "Deleting all web history for %{private}s with ScreenTimeWebBrowserSettings"
+ "Deleting web history during %{private}s for %{private}s with ScreenTimeWebBrowserSettings"
+ "Deleting web history for %{private}s for %{private}s with ScreenTimeWebBrowserSettings"
+ "Fetching all web history for %{private}s with ScreenTimeWebBrowserSettings"
+ "Fetching web history during %{private}s for %{private}s with ScreenTimeWebBrowserSettings"
+ "Realistic Image Generation: STOrganizationSettingsRestrictionUtility returning isAllowed = %{bool,public}d"
+ "Realistic Image Generation: STOrganizationSettingsRestrictionUtility saved isAllowed = %{bool,public}d"
+ "Realistic Image Generation: derived default from age range = %{public}lu"
+ "Realistic Image Generation: regulatory override — forced to off"
+ "ScreenTimeCore_Private.STScreenTimeWebBrowserSettings"
+ "ScreenTimeCore_Private.STScreenTimeWebBrowserSettingsObserver"
+ "ScreenTimeWebBrowserSettings initialization failed: %{public}@"
+ "Sensitive Topics: STOrganizationSettingsRestrictionUtility returning isAllowed = %{bool,public}d"
+ "Sensitive Topics: STOrganizationSettingsRestrictionUtility saved isAllowed = %{bool,public}d"
+ "Sensitive Topics: derived default from age range = %{public}lu"
+ "Sensitive Topics: regulatory override — forced to Reduce"
+ "Siri AI: STOrganizationSettingsRestrictionUtility returning isAllowed = %{bool,public}d"
+ "Siri AI: STOrganizationSettingsRestrictionUtility saved isAllowed = %{bool,public}d"
+ "Siri AI: derived default from age range = %{public}lu"
+ "Siri AI: regulatory override — forced to off"
+ "UpgradeEligibilityCheckIntervalSeconds"
+ "cloudSettings.contentPrivacySensitiveTopicsRestriction"
+ "cloudSettings.contentPrivacySiriAIRestriction"
+ "cloudSettings.contentPrivacySiriRealisticImageGenerationRestriction"
+ "contentPrivacySensitiveTopicsRestriction"
+ "contentPrivacySiriAIRestriction"
+ "contentPrivacySiriRealisticImageGenerationRestriction"
+ "familySettings.contentPrivacySensitiveTopicsRestriction"
+ "familySettings.contentPrivacySiriAIRestriction"
+ "familySettings.contentPrivacySiriRealisticImageGenerationRestriction"
+ "localSettings.contentPrivacySensitiveTopicsRestriction"
+ "localSettings.contentPrivacySiriAIRestriction"
+ "localSettings.contentPrivacySiriRealisticImageGenerationRestriction"
+ "shouldAllowOneMoreMinute(for:)"
+ "webBrowserHistory"
+ "webBrowserSettings"
- "shouldAllowOneMoreMinute(forBundleIdentifier:)"
- "shouldAllowOneMoreMinute(forCategoryIdentifier:)"
```
