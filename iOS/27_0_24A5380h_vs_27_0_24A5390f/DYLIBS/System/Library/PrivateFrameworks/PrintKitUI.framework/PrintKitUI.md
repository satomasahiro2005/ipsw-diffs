## PrintKitUI

> `/System/Library/PrivateFrameworks/PrintKitUI.framework/PrintKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x655d8` | `0x6560c` | **`+0x34`** |
| `__DATA_CONST.__objc_selrefs` | `0x4968` | `0x4970` | **`+0x8`** |

### Other Changes

```diff

-93.0.0.0.0
+94.0.0.0.0
Symbols:
+ -[UIPrintPreviewViewController printPanelDidDismiss]
- -[UIPrintPreviewViewController dealloc]
Functions:
~ -[UIPrintInteractionController _printPageWithDelay:] : 216 -> 204
~ -[UIPrintPagesController baseImageForPageNum:] : 808 -> 800
~ -[UIPrintPreviewViewController dealloc] -> -[UIPrintPreviewViewController printPanelDidDismiss] : 964 -> 952
~ -[UIPrintPanelViewController printNavigationConrollerDidDismiss] : 316 -> 380
~ -[UIPrintPanelViewController dismissPrintPanelWithAction:animated:completionHandler:] : 500 -> 548
~ -[UIPrintPageRenderer _drawPageAtIndex:withScale:drawingToPDF:] : 264 -> 236
```
