## MobileSafariSettings

> `/System/Library/PreferenceBundles/MobileSafariSettings.bundle/MobileSafariSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f2b8` | `0x6f118` | **`-0x1a0`** |
| `__DATA_CONST.__cfstring` | `0x4e00` | `0x4de0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x5dcb` | `0x5dab` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x1db0` | `0x1dc0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xef0` | `0xef8` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x2888` | `0x2880` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x10d8` | `0x10e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7625.1.18.10.4
+7625.1.20.10.3

-  Symbols:   5566
-  CStrings:  3729
+  Symbols:   5567
+  CStrings:  3728
Symbols:
+ _objc_retain_x9
Functions:
~ -[SafariExtensionPermissionsExplanation specifiers] : 1300 -> 1296
~ -[SafariContentBlockerPermissionsSettingsController _specifiersForEnablingExtension] : 2584 -> 2580
~ -[SafariSavedCreditCardsController _specifiersForVirtualCardSection] : 1220 -> 1216
~ -[SafariSavedCreditCardsController specifiers] : 1008 -> 1004
~ -[SafariSavedCreditCardsController deleteItemsForSpecifiers:] : 364 -> 360
~ -[SafariSavedCreditCardsController setEditing:animated:] : 608 -> 604
~ -[SafariSavedCreditCardsController _deleteSelectedItems] : 400 -> 396
~ -[SafariSavedCreditCardsController _autoFillItemCount] : 292 -> 288
~ -[SafariSettingsBrowsingDataExportController _extensionsToBeExported] : 964 -> 960
~ -[SafariSettingsBrowsingDataExportController _numberOfDescendantsInBookmarkFolder:collection:] : 400 -> 396
~ ___72-[SafariSettingsBrowsingDataExportController exportExtensionsWithBlock:]_block_invoke : 556 -> 552
~ -[SafariFavoritesFolderPickerContoller specifiers] : 1340 -> 1336
~ -[SafariVisualPickerSettingsTableCell buttonTapped:] : 756 -> 752
~ -[SafariDownloadsSettingsController _updateSpecifiersWithProviderDomains:] : 636 -> 632
~ -[SafariDownloadsSettingsController _locationContainingItem:] : 364 -> 360
~ -[FrequentlyVisitedSitesController _canonicalizedFavoritesURLStringSet] : 432 -> 428
~ ___82-[FrequentlyVisitedSitesController _saveFrequentlyVisitedSites:completionHandler:]_block_invoke : 1100 -> 1092
~ -[SafariProfileFavoritesFolderPickerController specifiers] : 716 -> 712
~ -[SafariPerSitePreferenceSettingsController reloadSpecifiers] : 436 -> 432
~ -[SafariPerSitePreferenceSettingsController _specifiersForDomains:] : 360 -> 356
~ -[SafariPerSitePreferenceSettingsController _editableSpecifiersForDomains:] : 352 -> 348
~ -[SafariPerSitePreferenceSettingsController _preferenceSpecifierNamed:set:get:] : 712 -> 708
~ ___76-[SafariPerSitePreferenceSettingsController _didRetrieveValue:forSpecifier:]_block_invoke : 532 -> 528
~ -[SafariPerSitePreferenceSettingsController _clearSelectedDomains:] : 364 -> 360
~ -[SafariPerSitePreferenceSettingsController _setUpConstantSpecifiers] : 980 -> 976
~ -[SafariWebExtensionDataSource _deleteDataForWebExtensionWithComposedIdentifier:] : 524 -> 520
~ -[SafariWebExtensionDataSource _calculateTotalExtensionStorageWithCompletionHandler:] : 976 -> 972
~ ___70-[SafariWebExtensionDataSource createSpecifiersWithCompletionHandler:]_block_invoke : 612 -> 608
~ -[SafariQuickWebsiteSearchSettingsController specifiers] : 1140 -> 1136
~ -[SafariQuickWebsiteSearchSettingsController _deleteSelectedItems:] : 532 -> 524
~ ___68-[SafariImportViewController _searchForExportWithCompletionHandler:]_block_invoke_2 : 1040 -> 1036
~ ___68-[SafariImportViewController _searchForExportWithCompletionHandler:]_block_invoke_4 : 548 -> 540
~ -[ImportDetailsStackView setNumberOfItemsToBeImportedPerDataType:] : 396 -> 392
~ -[SafariExtensionsProfileSettingsController specifiers] : 1824 -> 1840
~ +[SafariSettingsController _createTabGroupManagerForClearingHistory] : 364 -> 360
~ -[SafariSettingsController _setSearchEngineLocalizedTitlesForSearchEngineSpecifier:] : 436 -> 432
~ -[SafariSettingsController specifiers] : 4964 -> 4956
~ ___87+[SafariSettingsController _alertToDeleteBrowsingDataFiles:importedDataClassification:]_block_invoke_2 : 452 -> 448
~ ___47-[SafariSettingsController _exportButtonTapped]_block_invoke : 236 -> 232
~ -[SafariSettingsController _safariClearHistoryAndDataAddedAfterDate:beforeDate:profileIdentifier:clearAllProfiles:closeTabs:] : 2904 -> 2896
~ -[SafariSettingsController _areContentBlockersEnabled] : 720 -> 712
~ -[SafariSettingsController _mobileSafariChangedExtensionSettings] : 352 -> 348
~ __69+[SafariWebsiteDataDataSource deleteAllDataForProfileWithIdentifier:]_block_invoke.27 : 636 -> 632
~ ___76-[SafariWebsiteDataDataSource _addWebSecurityDomainsToArray:withCompletion:]_block_invoke : 260 -> 256
~ -[SafariProfileIconPickerCell refreshCellContentsWithSpecifier:] : 812 -> 808
~ _processIDForProcessNamed : 368 -> 388
~ -[SafariStorageSettingsController _totalUsageString] : 308 -> 304
~ ___52-[SafariStorageSettingsController _createSpecifiers]_block_invoke : 572 -> 568
~ -[SafariStorageSettingsController _deleteAllElements] : 736 -> 728
~ -[SafariStorageSettingsController _specifierRepresentingAllProfilesDataForDomain:] : 412 -> 408
~ ___54-[CreateEditProfileViewController deleteButtonTapped:]_block_invoke_2 : 1004 -> 1000
~ -[CreateEditProfileViewController _deleteDefunctCustomFavoritesFolderWithServerID:] : 764 -> 760
~ ___132-[SafariSettingsBrowsingDataImportController _generateLockupViewsForAvailableAppsWithWebBookmarksSettingsGateway:completionHandler:]_block_invoke_2 : 560 -> 556
~ -[SafariSettingsBrowsingDataImportController contentBlockerManagerExtensionListDidChange:] : 388 -> 384
~ -[SafariSettingsBrowsingDataImportController extensionsControllerExtensionListDidChange:] : 348 -> 344
~ -[SafariExtensionSettingsTableCell refreshCellContentsWithSpecifier:] : 556 -> 552
~ -[SafariWebExtensionsPermissionsSettingsController _specifiersForEnablingExtension] : 2048 -> 2044
~ -[SafariWebExtensionsPermissionsSettingsController _specifiersForExtensionErrors] : 1376 -> 1372
~ -[SafariWebExtensionsPermissionsSettingsController _deleteExtensionStorage:] : 1044 -> 1040
~ -[SafariWebExtensionsPermissionsSettingsController _isExtensionEnabledInMoreThanOneProfile] : 432 -> 428
~ -[SafariWebExtensionsPermissionsSettingsController _calculateExtensionStorageSizeAndCreateClearStorageButton] : 908 -> 904
~ ___109-[SafariWebExtensionsPermissionsSettingsController _calculateExtensionStorageSizeAndCreateClearStorageButton]_block_invoke : 1072 -> 1068
~ -[SafariWebExtensionsPermissionsSettingsController specifiers] : 2904 -> 2900
~ -[SafariWebExtensionsPermissionsSettingsController _setDomainPermission:forSpecifier:] : 620 -> 616
~ -[SafariWebExtensionsPermissionsSettingsController tableView:editingStyleForRowAtIndexPath:] : 608 -> 604
~ -[SafariSettingsListController updateRestrictionsForSpecifiers:] : 340 -> 336
~ -[SafariNewTabOverrideSettingsController specifiers] : 1080 -> 1076
~ -[SafariWebKitExperimentalFeaturesSettingsController specifiers] : 1012 -> 1008
~ -[SafariWebKitExperimentalFeaturesSettingsController resetAllExperimentalFeatures:] : 364 -> 360
~ -[SafariProfileColorPickerCell refreshCellContentsWithSpecifier:] : 800 -> 796
~ -[AvailableAppTableCell refreshCellContentsWithSpecifier:] : 732 -> 728
~ -[SafariExtensionsSettingsController specifiers] : 1292 -> 1284
~ -[SafariExtensionsSettingsController _contentBlockerAndWebExtensionSpecifiers] : 1596 -> 1580
~ -[SafariExtensionsSettingsController _adamIDsForInstalledAndCloudExtensions] : 404 -> 400
~ -[SafariExtensionsSettingsController _adamIDsForInstalledExtensions] : 544 -> 536
~ ___81-[SafariExtensionsSettingsController _extension:wasAddedToProfileWithIdentifier:]_block_invoke_4 : 832 -> 820
~ ___78-[SafariExtensionsSettingsController _selectOrHighlightExtensionsIfNecessary:]_block_invoke : 360 -> 356
~ -[SafariExportDataTypeToggleContainer initWithFrame:] : 968 -> 960
~ -[SafariExportDataTypeToggleContainer updateCountOfBrowsingDataExportType:count:] : 444 -> 440
~ sub_54bd8 -> sub_54a8c : 504 -> 512
~ sub_59aa4 -> sub_59960 : 804 -> 812
~ sub_5ac70 -> sub_5ab34 : 232 -> 236
~ sub_60f7c -> sub_60e44 : 764 -> 772
~ sub_6ab88 -> sub_6aa58 : 5024 -> 4908
~ sub_6cbe8 -> sub_6ca44 : 256 -> 264
~ sub_6cd90 -> sub_6cbf4 : 260 -> 272
~ sub_6d1a4 -> sub_6d014 : 1028 -> 1024
~ sub_6ddd0 -> sub_6dc3c : 380 -> 372
~ sub_6f080 -> sub_6eee4 : 1688 -> 1680
~ sub_6fb38 -> sub_6f994 : 1268 -> 1272
CStrings:
- "ShowRecentSearches"
```
