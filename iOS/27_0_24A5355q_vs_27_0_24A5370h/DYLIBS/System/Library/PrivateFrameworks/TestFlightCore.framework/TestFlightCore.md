## TestFlightCore

> `/System/Library/PrivateFrameworks/TestFlightCore.framework/TestFlightCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x50c28` | `0x50bdc` | **`-0x4c`** |
| `__TEXT.__unwind_info` | `0x12b8` | `0x12b0` | **`-0x8`** |

### Other Changes

```text
Functions:
~ -[TFLinkableHeaderFooterView _updateTextViewWithLinkMap:] : 644 -> 640
~ ___62-[TFDataAggregator _prepareDestinationDataContainer:forTasks:]_block_invoke : 416 -> 412
~ ___81-[TFDataAggregator _finishUpdatingDataContainer:byMergingDataContainer:forTasks:]_block_invoke : 428 -> 424
~ -[TFDataAggregator _loadAndExtractDataForTasks:intoDataContainer:] : 556 -> 552
~ ___55-[TFFeedbackDataContainer prepareInitialValuesForForm:]_block_invoke : 316 -> 312
~ -[TFFeedbackDataContainer overwriteWithContentsOfDataContainer:] : 736 -> 724
~ -[TFFeedbackFormPresenter prepareViewForForm] : 848 -> 840
~ _TFAMPCFStringGetCharacterAtIndex : 460 -> 444
~ -[TFImageFetcher _urlStringForIconArtwork:ofSize:fileFormat:] : 600 -> 596
~ +[TFLocale preferredLocaleKeyFromAvailableKeys:primaryLocaleKey:] : 616 -> 612
~ ___49+[TFDataAggregationTask(WatchInfo) watchInfoTask]_block_invoke : 464 -> 460
~ -[TFFeedbackFormImageCollectionCell layoutSubviews] : 624 -> 620
~ +[TFFeedbackFormImageCollectionCell _sizeForImages:fittingSize:inTraitEnvironment:] : 408 -> 404
~ -[TFFeedbackSession _associatePrefilledEmailIfNeeded] : 488 -> 484
~ ___100-[TFFeedbackSession feedbackWillSendFeedbackSubmissionWithFeedbackText:emailAddress:screenshotURLs:]_block_invoke : 444 -> 440
~ sub_2a6ddce74 -> sub_2a8841e20 : 320 -> 324
~ sub_2a6ddd608 -> sub_2a88425b8 : 72 -> 76
~ sub_2a6ddd75c -> sub_2a8842710 : 124 -> 128
~ sub_2a6ddd93c -> sub_2a88428f4 : 376 -> 380
~ sub_2a6de41b0 -> sub_2a884916c : 408 -> 404
~ sub_2a6de4348 -> sub_2a8849300 : 560 -> 564
~ sub_2a6de46c4 -> sub_2a8849680 : 416 -> 412
~ sub_2a6de486c -> sub_2a8849824 : 380 -> 360
~ sub_2a6de4ab4 -> sub_2a8849a58 : 280 -> 276
~ sub_2a6de984c -> sub_2a884e7ec : 324 -> 328
~ sub_2a6dea974 -> sub_2a884f918 : 232 -> 236
~ sub_2a6deaf50 -> sub_2a884fef8 : 5264 -> 5268
~ sub_2a6deda40 -> sub_2a88529ec : 2856 -> 2800
~ sub_2a6dee5bc -> sub_2a8853530 : 3368 -> 3416
~ sub_2a6df0854 -> sub_2a88557f8 : 500 -> 504
~ sub_2a6df0a48 -> sub_2a88559f0 : 480 -> 484
~ sub_2a6df10c0 -> sub_2a885606c : 888 -> 884
~ sub_2a6df23e8 -> sub_2a8857390 : 360 -> 356
~ sub_2a6df2610 -> sub_2a88575b4 : 348 -> 344
~ sub_2a6df9608 -> sub_2a885e5a8 : 652 -> 640
~ sub_2a6dfa488 -> sub_2a885f41c : 116 -> 120
~ sub_2a6dfa63c -> sub_2a885f5d4 : 100 -> 104
~ sub_2a6e01080 -> sub_2a886601c : 136 -> 144
~ sub_2a6e064f0 -> sub_2a886b494 : 232 -> 240
~ sub_2a6e06858 -> sub_2a886b804 : 232 -> 240
```
