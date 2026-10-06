## DocumentManagerExecutables

> `/System/Library/AccessibilityBundles/DocumentManagerExecutables.axbundle/DocumentManagerExecutables`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c44` | `0x5d34` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x2b0` | `0x2c0` | **`+0x10`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Symbols:   587
+  Symbols:   586
Symbols:
- _UIAXStringForAllChildren
Functions:
~ -[DOCItemCollectionCellAccessibility _axCustomActionsFromUIMenu:] : 932 -> 928
~ -[DOCChainedTagsViewAccessibility accessibilityLabel] : 356 -> 352
~ ___61-[DOCSidebarItemCellAccessibility accessibilityCustomActions]_block_invoke : 424 -> 420
~ +[DOCItemCollectionOutlineCellAccessibility _accessibilityPerformValidations:] : 4 -> 64
~ -[DOCItemCollectionOutlineCellAccessibility accessibilityLabel] : 4 -> 196
```
