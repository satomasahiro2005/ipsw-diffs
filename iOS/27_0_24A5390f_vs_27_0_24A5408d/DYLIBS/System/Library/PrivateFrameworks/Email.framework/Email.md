## Email

> `/System/Library/PrivateFrameworks/Email.framework/Email`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd72c4` | `0xda6d0` | **`+0x340c`** |
| `__TEXT.__gcc_except_tab` | `0x1aef4` | `0x1b088` | **`+0x194`** |
| `__TEXT.__oslogstring` | `0x67a3` | `0x6913` | **`+0x170`** |
| `__TEXT.__cstring` | `0xc21f` | `0xc37f` | **`+0x160`** |
| `__AUTH_CONST.__objc_const` | `0x16e10` | `0x16f60` | **`+0x150`** |
| `__AUTH_CONST.__cfstring` | `0xa480` | `0xa560` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x8160` | `0x81d0` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0xd044` | `0xd0ac` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x45b8` | `0x4610` | **`+0x58`** |
| `__TEXT.__dlopen_cstrs` | `0x10a` | `0x160` | **`+0x56`** |
| `__AUTH.__objc_data` | `0x1b0` | `0x200` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0xb88` | `0xbc8` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x1e60` | `0x1ea0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x6280` | `0x62b8` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x486` | `0x4aa` | **`+0x24`** |
| `__TEXT.__const` | `0x18bc` | `0x18dc` | **`+0x20`** |
| `__DATA.__data` | `0x2a28` | `0x2a40` | **`+0x18`** |
| `__DATA.__bss` | `0x23d0` | `0x23e0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xc44` | `0xc4c` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x588` | `0x590` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x478` | `0x480` | **`+0x8`** |

### Other Changes

```diff

-3897.100.8.2.5
+3901.100.1.2.7

-  Functions: 5140
-  Symbols:   8943
-  CStrings:  2150
+  Functions: 5173
+  Symbols:   8986
+  CStrings:  2166
Symbols:
+ +[EMServerConfiguration configurationURL]
+ -[CSSearchableItem(SFMailRankingSignals) em_isSemanticMatch]
+ -[CSSearchableItem(SFMailRankingSignals) em_isSyntacticMatch]
+ -[EMMessageRepository loadOlderItemsForObservationIdentifier:mailboxesToLoad:]
+ -[EMSearchResultMetadata .cxx_destruct]
+ -[EMSearchResultMetadata initWithRankingSignals:rankPosition:]
+ -[EMSearchResultMetadata rankPosition]
+ -[EMSearchResultMetadata rankingSignals]
+ -[EMUbiquitouslyPersistedDictionary _applyFullCloudMerge:]
+ -[EMUbiquitouslyPersistedDictionary _scheduleFullCloudMerge]
+ _CloudSharingLibraryCore.frameworkLibrary
+ _EMGenerativeModelsAvailabilityIsPolicyLimitedOnlyChangeKey
+ _EMGenerativeModelsAvailabilityNewStateKey
+ _EMGenerativeModelsAvailabilityOldStateKey
+ _EMIsChinaRegion
+ _EMIsShareOwnerManagedAppleAccount
+ _EMUserDefaultAllResultsSearchProximityThreshold
+ _EMUserDefaultPersonalizedSmartReplies
+ _EMUserDefaultShownPersonalizeSmartRepliesAlert
+ _OBJC_CLASS_$_EMSearchResultMetadata
+ _OBJC_IVAR_$_EMSearchResultMetadata._rankPosition
+ _OBJC_IVAR_$_EMSearchResultMetadata._rankingSignals
+ _OBJC_METACLASS_$_EMSearchResultMetadata
+ __OBJC_$_CLASS_PROP_LIST_EMServerConfiguration
+ __OBJC_$_INSTANCE_METHODS_EMSearchResultMetadata
+ __OBJC_$_INSTANCE_VARIABLES_EMSearchResultMetadata
+ __OBJC_$_PROP_LIST_CSSearchableItem_$_SFMailRankingSignals
+ __OBJC_$_PROP_LIST_EMSearchResultMetadata
+ __OBJC_CLASS_RO_$_EMSearchResultMetadata
+ __OBJC_METACLASS_RO_$_EMSearchResultMetadata
+ ___58-[EMUbiquitouslyPersistedDictionary _applyFullCloudMerge:]_block_invoke
+ ___60-[EMUbiquitouslyPersistedDictionary _scheduleFullCloudMerge]_block_invoke
+ ___60-[EMUbiquitouslyPersistedDictionary _scheduleFullCloudMerge]_block_invoke_2
+ ___71-[EMUbiquitouslyPersistedDictionary _waitForPendingMutationsForTesting]_block_invoke_2
+ ___71-[EMUbiquitouslyPersistedDictionary _waitForPendingMutationsForTesting]_block_invoke_3
+ ___CloudSharingLibraryCore_block_invoke
+ ___EMRegisteredIDSRecipients_block_invoke_3
+ ___EMResolveUnknownIDStatuses_block_invoke
+ ___block_descriptor_48_ea8_32s40r_e22_v16?0"NSDictionary"8lr40l8s32l8
+ ___getCloudSharingClass_block_invoke
+ _audit_stringCloudSharing
+ _getCloudSharingClass.softClass
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_deallocClassInstance
+ _swift_release_x12
+ _symbolic _____Sg 16GenerativeModels0aB12AvailabilityV0C0O14RestrictedInfoV0D6ReasonO
+ _symbolic _____y_____G s11_SetStorageC 16GenerativeModels0cD12AvailabilityV0E0O14RestrictedInfoV0F6ReasonO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 16GenerativeModels0dE12AvailabilityV0F0O14RestrictedInfoV0G6ReasonO
- +[EMServerConfiguration _configurationLocation]
- -[EMMessageRepository loadOlderItemsForObservationIdentifier:]
- -[EMUbiquitouslyPersistedDictionary _performFullCloudMerge]
- _EMIsCurrentUserManagedAppleAccountForShare
- ___59-[EMUbiquitouslyPersistedDictionary _performFullCloudMerge]_block_invoke
- ___85-[EMUbiquitouslyPersistedDictionary initWithPlistPath:identifier:encrypted:delegate:]_block_invoke
CStrings:
+ "AllResultsSearchProximityThreshold"
+ "Class getCloudSharingClass(void)_block_invoke"
+ "CloudSharing"
+ "EMCKShareUtilities.m"
+ "EMGenerativeModelsAvailabilityIsPolicyLimitedOnlyChange"
+ "EMGenerativeModelsAvailabilityNewState"
+ "EMGenerativeModelsAvailabilityOldState"
+ "IDS status: %lu of %lu recipient(s) IDS-registered"
+ "IDS status: force-refresh timed out after %llds; treating remaining unknowns as non-IDS"
+ "IDS status: force-refreshing %lu unknown recipient(s), round %lu"
+ "IDS status: incomplete cached result (%lu of %lu); treating all recipients as non-IDS"
+ "IDS status: round %lu resolved nothing new; treating remaining unknowns as non-IDS"
+ "PersonalizedSmartReplies"
+ "ShownPersonalizeSmartRepliesAlert"
+ "softlink:r:path:/System/Library/PrivateFrameworks/CloudSharing.framework/CloudSharing"
+ "void *CloudSharingLibrary(void)"
```
