## HealthToolbox

> `/System/Library/PrivateFrameworks/HealthToolbox.framework/HealthToolbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x61500` | `0x62878` | **`+0x1378`** |
| `__DATA_CONST.__objc_selrefs` | `0x4750` | `0x47f0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x77e1` | `0x7871` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x6e50` | `0x6ee0` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0xafa0` | `0xb020` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0xbb4` | `0xc28` | **`+0x74`** |
| `__DATA_CONST.__const` | `0x1828` | `0x1898` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x53e0` | `0x5440` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x320` | `0x360` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1978` | `0x19b8` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xc30` | `0xc48` | **`+0x18`** |
| `__TEXT.__const` | `0x196` | `0x1a6` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x680` | `0x688` | **`+0x8`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  Functions: 2323
-  Symbols:   4474
-  CStrings:  1063
+  Functions: 2343
+  Symbols:   4503
+  CStrings:  1068
Symbols:
+ -[WDAtrialFibrillationEventMetadataViewController lastLaidOutWidth]
+ -[WDAtrialFibrillationEventMetadataViewController setLastLaidOutWidth:]
+ -[WDAuthorizationRecord availabilityStartDate]
+ -[WDAuthorizationRecord mode]
+ -[WDBuddyFlowUserInfoViewController _updateContinueButtonState]
+ -[WDDisplayTypeDataSourcesTableViewController _accessLevelStringForAuthorizationRecord:]
+ -[WDDisplayTypeDataSourcesTableViewController _refreshAuthorizationRecordsAndReloadTable]
+ -[WDElectrocardiogramDataMetadataViewController metadataLeadingConstraint]
+ -[WDElectrocardiogramDataMetadataViewController metadataTrailingConstraint]
+ -[WDElectrocardiogramDataMetadataViewController setMetadataLeadingConstraint:]
+ -[WDElectrocardiogramDataMetadataViewController setMetadataTrailingConstraint:]
+ -[WDElectrocardiogramDataMetadataViewController tableView:viewForHeaderInSection:]
+ -[WDElectrocardiogramDataMetadataViewController viewDidLayoutSubviews]
+ -[WDElectrocardiogramDataMetadataViewController viewWillLayoutSubviews]
+ GCC_except_table39
+ GCC_except_table52
+ GCC_except_table65
+ GCC_except_table79
+ GCC_except_table80
+ GCC_except_table90
+ _NSDirectionalEdgeInsetsZero
+ _OBJC_CLASS_$_HKBackgroundAppRefreshStatusFetcher
+ _OBJC_CLASS_$_HKSettingsAuthorizationFactory
+ _OBJC_IVAR_$_WDAtrialFibrillationEventMetadataViewController._lastLaidOutWidth
+ _OBJC_IVAR_$_WDElectrocardiogramDataMetadataViewController._metadataLeadingConstraint
+ _OBJC_IVAR_$_WDElectrocardiogramDataMetadataViewController._metadataTrailingConstraint
+ ___81-[WDDisplayTypeDataSourcesTableViewController tableView:didSelectRowAtIndexPath:]_block_invoke_2
+ ___89-[WDDisplayTypeDataSourcesTableViewController _refreshAuthorizationRecordsAndReloadTable]_block_invoke
+ ___89-[WDDisplayTypeDataSourcesTableViewController _refreshAuthorizationRecordsAndReloadTable]_block_invoke_2
+ ___93+[WDSourcesListTableViewSection createDetailViewControllerForSourceModel:profile:completion:]_block_invoke_2
+ ___93+[WDSourcesListTableViewSection createDetailViewControllerForSourceModel:profile:completion:]_block_invoke_3
+ ___99-[WDDisplayTypeDataSourcesTableViewController _readerSourceCellForTableView:sourceArray:row:group:]_block_invoke_4
+ ___99-[WDDisplayTypeDataSourcesTableViewController _readerSourceCellForTableView:sourceArray:row:group:]_block_invoke_5
+ ___99-[WDDisplayTypeDataSourcesTableViewController _readerSourceCellForTableView:sourceArray:row:group:]_block_invoke_6
+ ___block_descriptor_32_e28_v24?0"NSString"8?<v?B>16l
+ ___block_descriptor_40_e8_32w_e29_v16?0"NSMutableDictionary"8lw32l8
+ ___block_descriptor_48_e8_32s40s_e23_"UIViewController"8?0ls32l8s40l8
- -[WDAtrialFibrillationEventMetadataViewController firstViewDidLayoutSubviews]
- -[WDAtrialFibrillationEventMetadataViewController setFirstViewDidLayoutSubviews:]
- GCC_except_table32
- GCC_except_table49
- GCC_except_table72
- GCC_except_table73
- GCC_except_table82
- _OBJC_IVAR_$_WDAtrialFibrillationEventMetadataViewController._firstViewDidLayoutSubviews
CStrings:
+ "@\"UIViewController\"8@?0"
+ "TIME_BOUNDED_SETTINGS_FULL_ACCESS"
+ "TIME_BOUNDED_SETTINGS_LIMITED_ACCESS"
+ "TIME_BOUNDED_SETTINGS_NONE"
+ "readerAppCell"
+ "v24@?0@\"NSString\"8@?<v@?B>16"
- "Localizable-Yodel"
```
