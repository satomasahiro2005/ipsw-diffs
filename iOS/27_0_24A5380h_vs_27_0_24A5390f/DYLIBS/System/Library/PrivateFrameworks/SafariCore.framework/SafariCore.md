## SafariCore

> `/System/Library/PrivateFrameworks/SafariCore.framework/SafariCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e93b0` | `0x1eb4f8` | **`+0x2148`** |
| `__TEXT.__cstring` | `0x16bc7` | `0x16d47` | **`+0x180`** |
| `__AUTH_CONST.__cfstring` | `0x1ac40` | `0x1ad60` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0xe161` | `0xe261` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0x16200` | `0x162c0` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0xd03c` | `0xd0fc` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x58a0` | `0x5910` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x7570` | `0x75d8` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x9a88` | `0x9ae0` | **`+0x58`** |
| `__DATA.__data` | `0x34f0` | `0x3540` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0xa3c0` | `0xa3f8` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x772c` | `0x7758` | **`+0x2c`** |
| `__AUTH_CONST.__const` | `0xaff8` | `0xb018` | **`+0x20`** |
| `__DATA.__bss` | `0xa410` | `0xa420` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xd1c` | `0xd2c` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x25b4` | `0x25c2` | **`+0xe`** |
| `__AUTH_CONST.__auth_got` | `0x21a8` | `0x21b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x13a0` | `0x13a8` | **`+0x8`** |

### Other Changes

```diff

-625.1.22.10.3
+625.1.24.10.1

-  Functions: 11180
-  Symbols:   11973
-  CStrings:  5226
+  Functions: 11211
+  Symbols:   12010
+  CStrings:  5241
Symbols:
+ +[WBSFeatureAvailability shouldSkipAutomaticPasswordChangeAllowedDomainCheck]
+ +[WBSGeneratedPassword keychainDictionaryRepresentationWithPassword:displayName:serviceIdentifierType:serviceIdentifier:]
+ +[WBSSQLiteDatabase setUpSQLiteTemporaryDirectory]
+ +[WBSSavedAccountAppURL protectionSpaceForAppID:]
+ +[WBSSavedAccountStore splitAdditionalSites:forSavedAccount:additionalSitesToWriteToSidecar:additionalSitesToSaveToNewKeychainItems:]
+ -[WBSGeneratedPassword _initWithPassword:protectionSpace:displayName:serviceIdentifierType:generationDate:wasGeneratedInPrivateBrowsingSession:keychainPersistentReference:originalDictionary:]
+ -[WBSGeneratedPassword displayName]
+ -[WBSGeneratedPassword initWithPassword:protectionSpace:displayName:serviceIdentifierType:generationDate:wasGeneratedInPrivateBrowsingSession:]
+ -[WBSGeneratedPassword serviceIdentifierType]
+ -[WBSGeneratedPasswordStore addGeneratedPassword:forProtectionSpace:displayName:serviceIdentifierType:inPrivateBrowsingSession:completionHandler:]
+ -[WBSManagedExtensionsConfigurationStore cachedConfiguration]
+ -[WBSManagedExtensionsConfigurationStore init]
+ -[WBSManagedExtensionsConfigurationStore setCachedConfiguration:]
+ -[WBSSavedAccount _firstSidecarForAnySiteOfType:allowPasskeySidecars:]
+ -[WBSSavedAccount automaticPasswordChangeAccountLevelEligibility]
+ -[WBSSavedAccountKeychainCoordinator addGeneratedPassword:forProtectionSpace:displayName:serviceIdentifierType:wasGeneratedInPrivateBrowsingSession:]
+ GCC_except_table206
+ GCC_except_table240
+ GCC_except_table304
+ GCC_except_table311
+ GCC_except_table413
+ GCC_except_table418
+ GCC_except_table424
+ GCC_except_table443
+ _OBJC_IVAR_$_WBSGeneratedPassword._displayName
+ _OBJC_IVAR_$_WBSGeneratedPassword._serviceIdentifierType
+ _OBJC_IVAR_$_WBSManagedExtensionsConfigurationStore._cachedConfiguration
+ _OBJC_IVAR_$_WBSManagedExtensionsConfigurationStore._hasBegunObserving
+ _OBJC_IVAR_$_WBSManagedExtensionsConfigurationStore._internalQueue
+ _WBSAutomaticPasswordChangeDebugSiteShouldEnableObstacleKey
+ _WBSAutomaticPasswordChangeDisableIsOnAllowedDomainCheckKey
+ _WBSOSLogMagicExtensionsSync
+ _WBSOSLogMagicExtensionsSync.log
+ _WBSOSLogMagicExtensionsSync.onceToken
+ _WBSWebExtensionPointIdentifier
+ __ZZ50+[WBSSQLiteDatabase setUpSQLiteTemporaryDirectory]E9onceToken
+ ___146-[WBSGeneratedPasswordStore addGeneratedPassword:forProtectionSpace:displayName:serviceIdentifierType:inPrivateBrowsingSession:completionHandler:]_block_invoke
+ ___50+[WBSSQLiteDatabase setUpSQLiteTemporaryDirectory]_block_invoke
+ ___63-[WBSManagedExtensionsConfigurationStore beginObservingStorage]_block_invoke
+ ___76-[WBSManagedExtensionsConfigurationStore _underlyingConfigurationDidChange:]_block_invoke_2
+ ___95-[WBSSavedAccountStore _changeSavedAccountWithRequestOnInternalQueue:performPostUpdateActions:]_block_invoke_3
+ ___WBSOSLogMagicExtensionsSync_block_invoke
+ ___block_descriptor_40_e8_32s_e49_"NSString"16?0"WBSSavedAccountAdditionalSite"8ls32l8
+ ___block_descriptor_40_e8_32s_e49_"WBSSavedAccountAdditionalSite"16?0"NSString"8ls32l8
+ ___block_descriptor_45_e8_32s_e45_v24?0q8"<WBSSavedAccountSidecarInternal>"16ls32l8
+ ___block_descriptor_49_e8_32s40bs_e45_v24?0q8"<WBSSavedAccountSidecarInternal>"16ls40l8s32l8
+ ___block_descriptor_81_e8_32s40s48s56bs64w_e5_v8?0lw64l8s56l8s32l8s40l8s48l8
+ _sqlite3_mprintf
+ _sqlite3_temp_directory
+ _symbolic _____y_____G s11_SetStorageC 16GenerativeModels0cD12AvailabilityV0E0O14RestrictedInfoV0F6ReasonO
- -[WBSGeneratedPassword _initWithPassword:protectionSpace:generationDate:wasGeneratedInPrivateBrowsingSession:keychainPersistentReference:originalDictionary:]
- GCC_except_table114
- GCC_except_table204
- GCC_except_table302
- GCC_except_table309
- GCC_except_table341
- GCC_except_table409
- GCC_except_table416
- _OBJC_IVAR_$_WBSManagedExtensionsConfigurationStore._managedExtensionsConfiguration
- ___112-[WBSGeneratedPasswordStore addGeneratedPassword:forProtectionSpace:inPrivateBrowsingSession:completionHandler:]_block_invoke
- ___block_descriptor_32_e49_"NSString"16?0"WBSSavedAccountAdditionalSite"8l
- ___block_descriptor_46_e8_32s_e45_v24?0q8"<WBSSavedAccountSidecarInternal>"16ls32l8
- ___block_descriptor_65_e8_32s40s48bs56w_e5_v8?0lw56l8s48l8s32l8s40l8
CStrings:
+ "<nil>"
+ "<none>"
+ "@\"WBSSavedAccountAdditionalSite\"16@?0@\"NSString\"8"
+ "Could not create a private SQLite temporary directory; SQLite will fall back to its default. error: %{public}@"
+ "PMAutomaticPasswordChangeDebugSiteShouldEnableObstacle"
+ "Skipping isAllowedDomain check (running for %{public}@; attempted URL %{sensitive}@)"
+ "Skipping migration of accounts with invalid authentication types"
+ "TabOverviewDragAndDrop"
+ "UsageRetentionDonation"
+ "WBSAutomaticPasswordChangeDisableIsOnAllowedDomainCheck"
+ "app!"
+ "com.apple.Safari.web-extension"
+ "com.apple.SafariCore.WBSManagedExtensionsConfigurationStore"
+ "serviceIdentifier"
+ "serviceIdentifierType"
```
