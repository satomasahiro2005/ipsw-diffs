## HealthToolbox

> `/System/Library/PrivateFrameworks/HealthToolbox.framework/HealthToolbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62d64` | `0x62ed4` | **`+0x170`** |
| `__TEXT.__gcc_except_tab` | `0xc40` | `0xc00` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x6f10` | `0x6f18` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x19d0` | `0x19d8` | **`+0x8`** |

### Other Changes

```diff

-7027.0.67.2.1
+7027.0.72.2.5

-  Functions: 2349
-  Symbols:   4516
+  Functions: 2350
+  Symbols:   4517
Symbols:
+ -[WDDisplayTypeDataSourcesTableViewController _pushTimeBoundedDetailForSourceArray:indexPath:tableView:]
+ GCC_except_table95
+ ___104-[WDDisplayTypeDataSourcesTableViewController _pushTimeBoundedDetailForSourceArray:indexPath:tableView:]_block_invoke
- GCC_except_table94
- ___81-[WDDisplayTypeDataSourcesTableViewController tableView:didSelectRowAtIndexPath:]_block_invoke_2
Functions:
~ -[WDDisplayTypeDataSourcesTableViewController _readerSourceCellForTableView:sourceArray:row:group:] : 1784 -> 1788
~ -[WDDisplayTypeDataSourcesTableViewController tableView:willSelectRowAtIndexPath:] : 244 -> 364
~ -[WDDisplayTypeDataSourcesTableViewController tableView:didSelectRowAtIndexPath:] : 1508 -> 1032
+ -[WDDisplayTypeDataSourcesTableViewController _pushTimeBoundedDetailForSourceArray:indexPath:tableView:]
~ -[WDProfileHeaderView layoutSubviews] : 384 -> 456
```
