## PrintKitUI

> `/System/Library/PrivateFrameworks/PrintKitUI.framework/PrintKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x653f0` | `0x655d8` | **`+0x1e8`** |
| `__DATA_CONST.__objc_selrefs` | `0x4950` | `0x4968` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1c8c` | `0x1c9c` | **`+0x10`** |

### Other Changes

```diff

-91.1.0.0.0
+93.0.0.0.0

-  Functions: 2298
-  Symbols:   4279
+  Functions: 2299
+  Symbols:   4280
Symbols:
+ GCC_except_table47
+ GCC_except_table49
+ GCC_except_table92
+ GCC_except_table99
+ ___53-[UIPrintPreviewViewController updatePreviewViewSize]_block_invoke
- GCC_except_table44
- GCC_except_table84
- GCC_except_table91
- GCC_except_table98
Functions:
~ -[UIPrinterAccessoryView sizeThatFits:] : 408 -> 404
~ -[UIPrinterBrowserViewController initWithOwnerViewController:printInfo:printPanelViewController:] : 596 -> 624
~ -[UIPrinterBrowserViewController viewIsAppearing:] : 204 -> 272
~ ___85-[UIPrinterBrowserViewController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke : 156 -> 224
~ ___56-[UIPrinterBrowserViewController addPrinter:moreComing:]_block_invoke : 1212 -> 1292
~ ___58-[UIPrinterBrowserViewController removePrinter:moreGoing:]_block_invoke : 680 -> 752
~ -[UIPrintInteractionController updatePrintingItems:] : 2440 -> 2428
~ -[UIPrintInteractionController _presentAnimated:hostingScene:completionHandler:] : 788 -> 784
~ -[UIPrintInteractionController _canShowDuplex] : 356 -> 352
~ -[UIPrintInteractionController _canShowLayout] : 360 -> 356
~ -[UIPrintInteractionController _canShowOrientation] : 372 -> 368
~ -[UIPrintInteractionController _canShowScaling] : 372 -> 368
~ -[UIPrintInteractionController setPageRanges:] : 348 -> 344
~ -[UIPrintInteractionController setPrinter:] : 824 -> 820
~ -[UIPrintInteractionController paper] : 1740 -> 1724
~ -[UIPrintInteractionController rendererToUse] : 676 -> 672
~ -[UIPrintInteractionController _updatePageCount] : 1420 -> 1412
~ -[UIPrintInteractionController getPrintingItemForPageNum:pdfItemPageNum:] : 448 -> 444
~ -[UIPrintInteractionController _cancelAllPreviewGeneration] : 260 -> 256
~ -[UIPrintInteractionController _updateCutterBehavior] : 932 -> 928
~ -[UIPrintInteractionController _paperForPDFItem:withDuplexMode:] : 364 -> 420
~ -[UIPrintInteractionController _paperForContentType:] : 408 -> 404
~ -[UIPrintInteractionController _updatePrintPaper] : 2352 -> 2492
~ -[UIPrintInteractionController _canShowPreview] : 876 -> 872
~ -[UIPrintInteractionController _canPreviewContent] : 772 -> 768
~ -[UIPrintInteractionController _completePrintPageWithError:] : 840 -> 836
~ -[UIPrintingProgressViewController shouldAutorotateToInterfaceOrientation:] : 420 -> 416
~ -[UIPrintingProgressViewController supportedInterfaceOrientations] : 320 -> 316
~ -[UIPrintOptionListViewController tableView:cellForRowAtIndexPath:] : 900 -> 896
~ -[UIPrintOptionListCell printOptionCellTapped] : 432 -> 476
~ -[UIPrintOptionListCell previewDidChangeSize:] : 184 -> 236
~ -[UIPrintOptionPopupCell setPopupActions:] : 492 -> 488
~ -[UIPrintPresetsOption updateFromPrintInfo] : 572 -> 568
~ -[UIPrintPresetsOption appliedPresetsSummary] : 460 -> 456
~ -[UIPrintPresetsOption presetNames] : 552 -> 548
~ -[UIPrintPresetsOption selectedItems] : 528 -> 524
~ -[UIPrintPresetsOption printerContainsQuality:] : 304 -> 300
~ -[UIPrintPresetsOption getPrinterPresets] : 608 -> 604
~ -[UIPrintInfo applyPreset:] : 1884 -> 1880
~ -[UIPrintInfo clearPreset:origPrintInfo:] : 2112 -> 2108
~ -[UIPrintPreviewViewController updateLayoutControl] : 2092 -> 2088
~ -[UIPrintPreviewViewController resetAllPages:] : 652 -> 676
~ -[UIPrintPreviewViewController updatePrintPreviewPages:] : 404 -> 428
~ -[UIPrintPreviewViewController updatePreviewViewSize] : 344 -> 384
+ ___53-[UIPrintPreviewViewController updatePreviewViewSize]_block_invoke
~ ___48-[UIPrintPreviewViewController updatePageRange:]_block_invoke : 372 -> 368
~ -[UIPrintPreviewViewController collectionView:prefetchItemsAtIndexPaths:] : 460 -> 456
~ -[UIPrintPreviewViewController pageIndexIsInRange:] : 300 -> 296
~ -[UIPrintPreviewViewController canRemovePage:forPageIndex:] : 340 -> 336
~ -[UIFinishingOptionsSection didSelectPrintOptionSection] : 440 -> 484
~ -[UIFinishingsOption printerFinishingOptions] : 11384 -> 11380
~ -[UIFinishingsOption summaryString] : 692 -> 688
~ -[UIPrintFinishingTemplatesOption finishingTempletesTableViewCell] : 808 -> 804
~ -[UIPrintFinishingTemplatesOption selectedTemplate] : 380 -> 376
~ -[UIPrintFinishingTemplatesOption updateFromPrintInfo] : 512 -> 508
~ -[UIPrinterFinishingOption updateFromPrintInfo] : 564 -> 560
~ -[UIPrinterFinishingOption selectedFinishingChoice] : 988 -> 976
~ -[UIPrinterFinishingOption printerFinishingOptionTableViewCell] : 1348 -> 1344
~ -[UIPrintLayoutSection didSelectPrintOptionSection] : 472 -> 516
~ +[UIPrintPaper bestPaperForPageSize:andContentType:withPapersFromArray:] : 2184 -> 2164
~ +[UIPrintPaper _readyPaperListForPrinter:withDuplexMode:forContentType:contentSize:] : 436 -> 432
~ +[UIPrintPaper _readyDocumentPaperListForPrinter:withDuplexMode:contentSize:scaleUpForRoll:] : 416 -> 412
~ +[UIPrintPaper _genericPaperListForOutputType:] : 816 -> 812
~ +[UIPrintPaper _defaultPaperListForOutputType:] : 456 -> 452
~ -[UIPrintPreviewPageCell prepareForReuse] : 284 -> 336
~ -[UIPrintPreviewPageCell setThumbnailImage:] : 208 -> 260
~ -[UIPrintPreviewPageCell showThumbnailProgressSpinner] : 228 -> 272
~ -[UIPrintMediaQualitySection didSelectPrintOptionSection] : 456 -> 500
~ -[UIPrintFeedFromOption updateFromPrintInfo] : 920 -> 912
~ -[UIPrintFeedFromOption createPrintOptionTableViewCell] : 708 -> 704
~ -[UIPrintFeedFromOption trayNames] : 692 -> 688
~ -[UIPrintMediaTypeOption updateFromPrintInfo] : 864 -> 856
~ -[UIPrintMediaTypeOption mediaTypeNames] : 712 -> 708
~ -[UIPrintMediaTypeOption createPrintOptionTableViewCell] : 712 -> 708
~ _redrawPDFWithNUp : 3528 -> 3576
~ _getPDFPageProperties : 292 -> 288
~ -[UIPrintPanelViewController dealloc] : 344 -> 380
~ -[UIPrintPanelViewController observeValueForKeyPath:ofObject:change:context:] : 792 -> 524
~ -[UIPrintPanelViewController showCompactPreview] : 336 -> 332
~ -[UIPrintPanelViewController showSidebarPreview] : 352 -> 348
~ -[UIPrintPageRenderer dealloc] : 276 -> 272
~ -[UIPrintPageRenderer setPrintFormatters:] : 524 -> 516
~ -[UIPrintPageRenderer printFormattersForPageAtIndex:] : 372 -> 368
~ -[UIPrintPageRenderer _maxFormatterPage] : 312 -> 308
~ -[UIPrintPageRenderer setHeaderHeight:] : 352 -> 348
~ -[UIPrintPageRenderer setFooterHeight:] : 352 -> 348
~ -[UIPrintPageRenderer setPaperRect:] : 396 -> 392
~ -[UIPrintPageRenderer setPrintableRect:] : 396 -> 392
~ -[UIPrintPageRenderer drawPageAtIndex:inRect:] : 624 -> 620
~ -[UIPrintCopiesOption textField:editMenuForCharactersInRange:suggestedActions:] : 336 -> 332
~ _SummaryForRange : 1212 -> 1208
~ -[UIPrintPaperSizeOption getPaperNames:] : 476 -> 472
~ -[UIPrintPaperSizeOption defaultPaperIndex] : 504 -> 500
~ ___45-[UIPrintPaperSizeOption updateSelectedPaper]_block_invoke : 820 -> 812
~ -[UIPrintScalingOption textField:editMenuForCharactersInRange:suggestedActions:] : 432 -> 428
~ -[UIPrintOptionSection summaryString] : 448 -> 444
~ -[UIPrintOptionSection canDismiss] : 260 -> 256
~ -[UIPrinterPickerViewController shouldAutorotateToInterfaceOrientation:] : 412 -> 408
~ -[UIPrinterPickerViewController supportedInterfaceOrientations] : 384 -> 380
~ -[UIPrinterUtilityTableViewController initWithPrinter:printPanelViewController:] : 1044 -> 1072
~ -[UIPrinterUtilityTableViewController viewDidAppear:] : 172 -> 208
~ ___90-[UIPrinterUtilityTableViewController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke : 152 -> 188
~ -[UIPrintSupplyLevelView drawRect:] : 756 -> 752
~ _NupManagerDrawASheet : 760 -> 740
~ _WindowSceneForPrintPanel : 512 -> 508
~ -[UIPrintSheetController numberOfPagesInSelection] : 288 -> 284
~ -[UIPrintOptionsTableViewController initWithTableView:printInfo:printPanelViewController:] : 1144 -> 1140
~ -[UIPrintOptionsTableViewController canDismissPrintOptions] : 336 -> 332
```
