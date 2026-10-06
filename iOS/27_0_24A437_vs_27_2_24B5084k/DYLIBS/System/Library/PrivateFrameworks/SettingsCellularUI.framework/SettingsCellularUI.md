## SettingsCellularUI

> `/System/Library/PrivateFrameworks/SettingsCellularUI.framework/SettingsCellularUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x94480` | `0x944d8` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x56a8` | `0x56a0` | **`-0x8`** |

### Other Changes

```diff

-752.0.0.0.0
+756.0.0.0.0
Symbols:
+ -[PSUIDataUsageCategorySpecifier initWithAppType:usageType:subSpecifiers:statisticsCache:]
- -[PSUIDataUsageCategorySpecifier initWithAppType:usageType:subSpecifiers:]
Functions:
~ -[PSUIAppsAndCategoriesDataUsageSubgroup specifiersWithSortComparator:] : 388 -> 392
~ -[PSUIAppsAndCategoriesDataUsageSubgroup addDataUsageCategorySpecifierToSpecifiers:appType:] : 264 -> 272
~ ___40-[PSUITopAppUsageGroup createSpecifiers]_block_invoke : 2816 -> 2820
~ -[PSUIDataUsageCategoryListController shouldShowSpinner] : 172 -> 228
~ -[PSUIDataUsageCategorySpecifier initWithAppType:usageType:subSpecifiers:] -> -[PSUIDataUsageCategorySpecifier initWithAppType:usageType:subSpecifiers:statisticsCache:] : 668 -> 664
~ -[PSUICellularPlanAddOnPlanTableCell _setupView:] : 1632 -> 1652
```
