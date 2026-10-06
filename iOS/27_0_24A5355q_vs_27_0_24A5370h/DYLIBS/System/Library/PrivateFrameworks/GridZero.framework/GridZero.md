## GridZero

> `/System/Library/PrivateFrameworks/GridZero.framework/GridZero`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8e6f8` | `0x8ea30` | **`+0x338`** |
| `__AUTH_CONST.__objc_const` | `0x184a0` | `0x186e0` | **`+0x240`** |
| `__TEXT.__objc_methlist` | `0xcc58` | `0xcda0` | **`+0x148`** |
| `__DATA_CONST.__objc_selrefs` | `0x73b8` | `0x7418` | **`+0x60`** |
| `__DATA.__objc_ivar` | `0x1470` | `0x1498` | **`+0x28`** |
| `__TEXT.__cstring` | `0x5305` | `0x5329` | **`+0x24`** |
| `__AUTH_CONST.__cfstring` | `0x2680` | `0x26a0` | **`+0x20`** |
| `__TEXT.__const` | `0x2ae8` | `0x2af8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1130` | `0x1128` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x2388` | `0x2390` | **`+0x8`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Functions: 5073
-  Symbols:   7482
+  Functions: 5094
+  Symbols:   7512
Symbols:
+ +[PXPhotosGridHitTestUtilities _handleBadgeHitTestResult:badgeProvider:view:atLocation:executeActionIfNecessary:]
+ +[PXPhotosGridHitTestUtilities canHandleBadgeHitTestResult:badgeProvider:view:atLocation:]
+ -[PXAssetsSectionLayout excludesSelectionIndicator]
+ -[PXAssetsSectionLayout setExcludesSelectionIndicator:]
+ -[PXPhotosGridAssetDecorationSource disablesSelectionIndicator]
+ -[PXPhotosGridAssetDecorationSource setDisablesSelectionIndicator:]
+ -[PXPhotosGridAssetDecorationSource setWantsCommentBadges:]
+ -[PXPhotosGridAssetDecorationSource wantsCommentBadgeDecorationsInLayout:]
+ -[PXPhotosGridAssetDecorationSource wantsCommentBadges]
+ -[PXPhotosLayoutSpec initWithExtendedTraitCollection:options:gridStyle:backgroundStyle:shouldMakeSpaceForLeadingChrome:hasPhysicalHomeButton:overrideDefaultNumberOfColumns:]
+ -[PXPhotosViewConfiguration activityButtonAction]
+ -[PXPhotosViewConfiguration allowsCommentBadges]
+ -[PXPhotosViewConfiguration excludesSelectionIndicator]
+ -[PXPhotosViewConfiguration setActivityButtonAction:]
+ -[PXPhotosViewConfiguration setAllowsCommentBadges:]
+ -[PXPhotosViewConfiguration setExcludesSelectionIndicator:]
+ -[PXPhotosViewModel activityButtonAction]
+ -[PXPhotosViewModel allowsCommentBadges]
+ -[PXPhotosViewModel excludesSelectionIndicator]
+ -[PXPhotosViewModel placeholderStyleOverride]
+ -[PXPhotosViewModel setActivityButtonAction:]
+ -[PXPhotosViewModel setAllowsCommentBadges:]
+ -[PXPhotosViewModel wantsCommentBadge]
+ -[PXZoomablePhotosViewModel allowsCommentBadges]
+ -[PXZoomablePhotosViewModel excludesSelectionIndicator]
+ -[PXZoomablePhotosViewModel setAllowsCommentBadges:]
+ -[PXZoomablePhotosViewModel setExcludesSelectionIndicator:]
+ -[_PXPhotosLayoutWithSectionHeadersSpec initWithExtendedTraitCollection:options:gridStyle:backgroundStyle:shouldMakeSpaceForLeadingChrome:hasPhysicalHomeButton:overrideDefaultNumberOfColumns:]
+ GCC_except_table1083
+ GCC_except_table1115
+ GCC_except_table1135
+ GCC_except_table1231
+ GCC_except_table1285
+ GCC_except_table1326
+ GCC_except_table1375
+ GCC_except_table142
+ GCC_except_table1487
+ GCC_except_table1507
+ GCC_except_table1600
+ GCC_except_table1641
+ GCC_except_table1726
+ GCC_except_table1759
+ GCC_except_table1938
+ GCC_except_table2230
+ GCC_except_table2426
+ GCC_except_table2444
+ GCC_except_table2449
+ GCC_except_table2490
+ GCC_except_table2496
+ GCC_except_table2498
+ GCC_except_table2507
+ GCC_except_table2621
+ GCC_except_table2640
+ GCC_except_table2652
+ GCC_except_table2658
+ GCC_except_table2660
+ GCC_except_table2764
+ GCC_except_table2982
+ GCC_except_table3052
+ GCC_except_table3129
+ GCC_except_table3175
+ GCC_except_table593
+ GCC_except_table625
+ GCC_except_table80
+ _OBJC_IVAR_$_PXAssetsSectionLayout._excludesSelectionIndicator
+ _OBJC_IVAR_$_PXPhotosGridAssetDecorationSource._disablesSelectionIndicator
+ _OBJC_IVAR_$_PXPhotosGridAssetDecorationSource._wantsCommentBadges
+ _OBJC_IVAR_$_PXPhotosViewConfiguration._activityButtonAction
+ _OBJC_IVAR_$_PXPhotosViewConfiguration._allowsCommentBadges
+ _OBJC_IVAR_$_PXPhotosViewConfiguration._excludesSelectionIndicator
+ _OBJC_IVAR_$_PXPhotosViewModel._activityButtonAction
+ _OBJC_IVAR_$_PXPhotosViewModel._allowsCommentBadges
+ _OBJC_IVAR_$_PXPhotosViewModel._excludesSelectionIndicator
+ _OBJC_IVAR_$_PXPhotosViewModel._placeholderStyleOverride
+ _OBJC_IVAR_$_PXPhotosViewModel._wantsCommentBadge
+ _OBJC_IVAR_$_PXZoomablePhotosViewModel._allowsCommentBadges
+ _OBJC_IVAR_$_PXZoomablePhotosViewModel._excludesSelectionIndicator
+ _PXPhotosGridActionToggleCommentBadges
- -[PXPhotosLayoutSpec initWithExtendedTraitCollection:options:gridStyle:backgroundStyle:wantsToggleSidebarButton:shouldMakeSpaceForLeadingChrome:hasPhysicalHomeButton:overrideDefaultNumberOfColumns:]
- -[PXPhotosLayoutSpec wantsToggleSidebarButton]
- -[PXPhotosLayoutSpecManager setWantsToggleSidebarButton:]
- -[PXPhotosLayoutSpecManager wantsToggleSidebarButton]
- -[PXPhotosViewModel headerTitleTopInset]
- -[PXPhotosViewModel setHeaderTitleTopInset:]
- -[_PXPhotosLayoutWithSectionHeadersSpec initWithExtendedTraitCollection:options:gridStyle:backgroundStyle:wantsToggleSidebarButton:shouldMakeSpaceForLeadingChrome:hasPhysicalHomeButton:overrideDefaultNumberOfColumns:]
- GCC_except_table1076
- GCC_except_table1108
- GCC_except_table1128
- GCC_except_table1224
- GCC_except_table1278
- GCC_except_table1319
- GCC_except_table1368
- GCC_except_table141
- GCC_except_table1480
- GCC_except_table1500
- GCC_except_table1593
- GCC_except_table1634
- GCC_except_table1719
- GCC_except_table1752
- GCC_except_table1930
- GCC_except_table2222
- GCC_except_table2413
- GCC_except_table2431
- GCC_except_table2436
- GCC_except_table2475
- GCC_except_table2477
- GCC_except_table2481
- GCC_except_table2483
- GCC_except_table2606
- GCC_except_table2625
- GCC_except_table2637
- GCC_except_table2643
- GCC_except_table2645
- GCC_except_table2749
- GCC_except_table2954
- GCC_except_table3038
- GCC_except_table3115
- GCC_except_table3161
- GCC_except_table591
- GCC_except_table623
- GCC_except_table79
- _OBJC_IVAR_$_PXPhotosLayoutSpec._wantsToggleSidebarButton
- _OBJC_IVAR_$_PXPhotosLayoutSpecManager._wantsToggleSidebarButton
- _OBJC_IVAR_$_PXPhotosViewModel._headerTitleTopInset
- _PXSolariumMetricsEnabled
- ___43-[PXPhotosLayout _updateHeaderMeasurements]_block_invoke
CStrings:
+ "PXPhotosGridActionToggleCommentBadges"
+ "\xf0\xf0\xf0\x92\xf0\xf0\xf0\xf1Q"
- "\xb1"
- "\xf0\xf0\xf0\xa2\xf0\xf0\xf0\xe1Q"
```
