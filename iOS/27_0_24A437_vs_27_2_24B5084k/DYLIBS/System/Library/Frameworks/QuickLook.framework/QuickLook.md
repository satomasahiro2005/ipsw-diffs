## QuickLook

> `/System/Library/Frameworks/QuickLook.framework/QuickLook`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdddb8` | `0xddf58` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x56d7` | `0x57d7` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0x3958` | `0x3938` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1758` | `0x175c` | **`+0x4`** |

### Other Changes

```diff

-1034.0.0.0.0
+1034.1.3.0.0

-  Symbols:   7549
-  CStrings:  904
+  Symbols:   7548
+  CStrings:  906
Symbols:
- ___75-[QLPageViewController _setCurrentPageIndex:direction:animated:completion:]_block_invoke_3
Functions:
~ -[QLPreviewController _refreshCurrentPreviewItemAnimated:] : 112 -> 296
~ -[QLItemAggregatedViewController showPreviewViewController:animatingWithCrossfade:] : 1696 -> 1672
~ -[QLPageViewController _setCurrentPageIndex:direction:animated:completion:] : 608 -> 824
~ ___75-[QLPageViewController _setCurrentPageIndex:direction:animated:completion:]_block_invoke_3 -> ___75-[QLPageViewController _setCurrentPageIndex:direction:animated:completion:]_block_invoke.18 : 4 -> 44
CStrings:
+ "Data source returned no view controller for index %lu (current page index %ld). Showing an empty placeholder. #PreviewCollection"
+ "Not refreshing the current preview item at index %ld because the preview collection still needs to be configured. #PreviewController"
```
