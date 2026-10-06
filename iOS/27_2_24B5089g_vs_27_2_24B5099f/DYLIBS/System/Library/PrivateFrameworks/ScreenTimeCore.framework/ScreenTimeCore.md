## ScreenTimeCore

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xff1ec` | `0x10811c` | **`+0x8f30`** |
| `__TEXT.__oslogstring` | `0xc32a` | `0xc85a` | **`+0x530`** |
| `__TEXT.__eh_frame` | `0x4490` | `0x4960` | **`+0x4d0`** |
| `__TEXT.__unwind_info` | `0x40f8` | `0x4290` | **`+0x198`** |
| `__DATA.__data` | `0x2210` | `0x2350` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0x15d2` | `0x1704` | **`+0x132`** |
| `__AUTH_CONST.__const` | `0x37c8` | `0x38b8` | **`+0xf0`** |
| `__AUTH_CONST.__objc_const` | `0x135b0` | `0x13660` | **`+0xb0`** |
| `__TEXT.__cstring` | `0xa91c` | `0xa9cc` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0xa420` | `0xa4c0` | **`+0xa0`** |
| `__AUTH.__objc_data` | `0x3248` | `0x32b8` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x13a0` | `0x1410` | **`+0x70`** |
| `__TEXT.__const` | `0x3538` | `0x35a8` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x54f0` | `0x5548` | **`+0x58`** |
| `__TEXT.__swift5_capture` | `0xb8c` | `0xbe4` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0x1b80` | `0x1bb0` | **`+0x30`** |
| `__AUTH.__data` | `0x4e0` | `0x508` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x9a60` | `0x9a80` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x258` | `0x278` | **`+0x20`** |
| `__DATA.__common` | `0xd0` | `0xe8` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x240` | `0x250` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x2a8` | `0x2b8` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x180` | `0x18c` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x1bc` | `0x1c8` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xef0` | `0xef8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x6f0` | `0x6f8` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x138` | `0x140` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x7e0` | `0x7e4` | **`+0x4`** |

### Other Changes

```diff

-655.1.9.1.0
+655.1.12.0.0

-  Functions: 6048
-  Symbols:   6865
-  CStrings:  2294
+  Functions: 6144
+  Symbols:   6905
+  CStrings:  2309
Symbols:
+ -[STAppInfoCache isMigratedToNewScreenTime]
+ -[STConversation _allHandlesAreManagingParents:]
+ -[STConversation _isManagingParentHandle:]
+ -[STConversation allowableByContactsHandles:allowingManagingParentsWhenBlocked:]
+ -[STConversationContext allowsManagingParentsWhenBlocked]
+ -[STConversationContext setAllowsManagingParentsWhenBlocked:]
+ -[STConversationContext updateShouldBeAllowedDuringGeneralScreenTime:shouldBeAllowedByScreenTimeWhenLimited:shouldBeAllowedWhenBlocked:currentApplicationState:emergencyModeEnabled:]
+ -[STManagementState migrateAppDataFromBundleIdentifier:toBundleIdentifier:completionHandler:]
+ GCC_except_table34
+ GCC_except_table37
+ GCC_except_table40
+ GCC_except_table50
+ GCC_except_table55
+ GCC_except_table66
+ GCC_except_table68
+ _OBJC_CLASS_$_STAppDataMigrator
+ _OBJC_IVAR_$_STConversationContext._allowsManagingParentsWhenBlocked
+ _OBJC_METACLASS_$_STAppDataMigrator
+ _STDisplayableBundleIdentifiers
+ __CLASS_METHODS_STAppDataMigrator
+ __DATA_STAppDataMigrator
+ __INSTANCE_METHODS_STAppDataMigrator
+ __METACLASS_DATA_STAppDataMigrator
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_STAppDataMigratorCategoryProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_STAppDataMigratorCategoryProviding
+ __OBJC_$_PROTOCOL_REFS_STAppDataMigratorCategoryProviding
+ __OBJC_LABEL_PROTOCOL_$_STAppDataMigratorCategoryProviding
+ __OBJC_PROTOCOL_$_STAppDataMigratorCategoryProviding
+ ___93-[STManagementState migrateAppDataFromBundleIdentifier:toBundleIdentifier:completionHandler:]_block_invoke
+ ___93-[STManagementState migrateAppDataFromBundleIdentifier:toBundleIdentifier:completionHandler:]_block_invoke_2
+ __swift_implicitisolationactor_to_executor_cast
+ _flat unique So34STAppDataMigratorCategoryProviding_p
+ _swift_release_n
+ _swift_retain_x28
+ _symbolic SDySSSo10CTCategoryCG
+ _symbolic ScCySDySSSo10CTCategoryCG______pG s5ErrorP
+ _symbolic So17STAppDataMigratorCXMT
+ _symbolic ______p So34STAppDataMigratorCategoryProvidingP
+ _symbolic _____ySSSo10CTCategoryCG s18_DictionaryStorageC
+ _symbolic _____ySnySiGG s23_ContiguousArrayStorageC
+ _symbolic _____ySo11STBlueprintCG s11_SetStorageC
+ _symbolic _____ySo21STBlueprintUsageLimitCG s11_SetStorageC
+ _symbolic _____ySo24STBlueprintConfigurationCG s11_SetStorageC
+ _symbolic _____ySo8NSNumberCACG s18_DictionaryStorageC
+ _symbolic _____y______pG s23_ContiguousArrayStorageC s5ErrorP
- -[STConversationContext updateShouldBeAllowedDuringGeneralScreenTime:shouldBeAllowedByScreenTimeWhenLimited:currentApplicationState:emergencyModeEnabled:]
- GCC_except_table44
- GCC_except_table54
- GCC_except_table63
- GCC_except_table64
CStrings:
+ "Added %{public}s to %ld of %ld app limit(s) for app data migration"
+ "Failed to fetch always-allowed bundle identifiers, proceeding as if empty: %{public}s"
+ "Failed to save app limit while adding %{public}s for app data migration: %{public}s"
+ "Not adding destination to app limit matched by source bundle identifier: already covered by the limit's own category"
+ "Not making any changes for app data migration from %{public}s to %{public}s due to a missing managing organization"
+ "Not updating app limits for source category: %{public}s and %{public}s share the same category"
+ "Not updating app limits for source category: no category found for source bundle identifier %{public}s"
+ "Not updating app limits for source category: source bundle identifier's category is not covered by any app limit"
+ "Requested %{public}@ context allowing managing parents when blocked for handles:%{private}@. currentApplicationState:%lu allowedByScreenTime:%d managingParentAppleIDs:%{private}@"
+ "Skipping app data migration as source and destination resolve to the same canonical app: %{public}s"
+ "Skipping app data migration to %{public}s as it already has an existing app limits configured"
+ "Skipping app data migration to %{public}s as it is already in always allowed"
+ "appDataMigration"
+ "com.apple.SiriApp"
+ "migrateAppData(fromBundleIdentifier:toBundleIdentifier:persistenceController:categoryProvider:completionHandler:)"
```
