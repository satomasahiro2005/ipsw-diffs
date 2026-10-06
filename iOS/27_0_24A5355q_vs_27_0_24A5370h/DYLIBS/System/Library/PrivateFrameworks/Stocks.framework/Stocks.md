## Stocks

> `/System/Library/PrivateFrameworks/Stocks.framework/Stocks`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x499a0` | `0x497b8` | **`-0x1e8`** |
| `__TEXT.__unwind_info` | `0x11c8` | `0x11d0` | **`+0x8`** |

### Other Changes

```text
Functions:
~ -[SPChartView _prepareXAxisLabelsForLabelInfoArray:] : 808 -> 796
~ -[SPChartView _setDayLabelsWithInterval:realTimePositions:] : 2008 -> 2012
~ -[SPChartView _setHourLabels] : 1308 -> 1304
~ -[SPChartView widestYLabelWidthForMode:] : 288 -> 284
~ -[SCKZoneModificationSilo initWithZoneSchema:contents:] : 504 -> 500
~ -[SCKZoneModificationSilo deleteRecordWithName:] : 524 -> 520
~ -[Stock updateMetadataWithDictionary:forTime:] : 1168 -> 1164
~ -[Stock .cxx_destruct] : 304 -> 312
~ +[SCWatchlistDefaults defaultsFromCarrierBundle] : 1292 -> 1288
~ +[SCWatchlistDefaults defaultsHistoryForCurrentCountry] : 448 -> 444
~ -[ExchangeManager _loadExchangesFromDefaults] : 556 -> 552
~ -[YQLRequest(YQLDoppelganger) _yahooDoppelganger_taskForRequest:delegate:] : 536 -> 532
~ +[YahooDoppelganger prepDoppelgangerForQuotesResponseWithSymbols:includeMetdata:] : 1200 -> 1192
~ +[YahooDoppelganger prepDoppelgangerForChartResponseWithSymbol:numberOfDataPoints:] : 680 -> 676
~ +[YahooDoppelganger _spewDoppelgangerArray:named:] : 608 -> 604
~ -[SCKZoneSchema allRecordFieldNames] : 320 -> 316
~ -[SCKZoneSchema schemaForRecordType:] : 340 -> 336
~ -[SCKZoneSchema isValidRecord:] : 452 -> 448
~ -[StockUpdateManager hadError] : 256 -> 252
~ -[StockUpdateManager updateStockComprehensive:forced:withCompletion:] : 908 -> 904
~ -[StockUpdater _updateStocks:comprehensive:forceUpdate:] : 1576 -> 1572
~ -[StockUpdater _parseQuoteDictionaries:withDataSourceDictionaries:] : 620 -> 616
~ -[StockUpdater _parseExchangeDictionaries:] : 764 -> 760
~ -[SymbolValidator parseData:] : 1060 -> 1052
~ -[ChartUpdater parseDataSeriesDictionary:] : 3020 -> 3012
~ -[ChartUpdater didParseData] : 1492 -> 1516
~ _ParameterString : 456 -> 452
~ ____ConsumerSecret_block_invoke : 148 -> 156
~ -[SCKDatabaseSchema zoneIDs] : 320 -> 316
~ -[SCKDatabaseSchema schemaForZoneName:] : 340 -> 336
~ -[ChartLabelInfoManager monthLabelInfoArrayForLabelLength:] : 756 -> 752
~ ___46-[SCWatchlist database:didChangeZone:from:to:]_block_invoke : 740 -> 732
~ -[SCWatchlist _sortedStocks:withSymbolOrder:] : 564 -> 556
~ ___38-[SCWatchlist _enqueueStartupSequence]_block_invoke_3 : 696 -> 692
~ -[LabelSequenceView requiredSize] : 340 -> 336
~ -[LabelSequenceView drawRect:] : 628 -> 624
~ -[ChartTitleLabel prepareStringsWithStock:width:] : 2156 -> 2196
~ -[StockNewsItemCollection initWithArchiveArray:] : 416 -> 412
~ -[StockNewsItemCollection archiveArray] : 332 -> 328
~ -[NewsUpdater parseData:] : 2928 -> 2912
~ -[NewsUpdater resetLocale] : 304 -> 300
~ -[StocksTapDragGestureRecognizer touchesBegan:withEvent:] : 1168 -> 1160
~ -[SCKDatabaseJSONStore initWithSchema:fileURL:allowedCommands:] : 924 -> 920
~ -[SCKDatabaseJSONStore _saveToFileURL:] : 1824 -> 1812
~ -[SCKDatabaseJSONStore _loadFromFileURL:] : 2144 -> 2132
~ ___51-[SCKDatabaseJSONStore _listenForChangesToFileURL:]_block_invoke : 556 -> 552
~ -[StockPlatterViewController viewDidLoad] : 2656 -> 2648
~ -[ChartHUDView initWithFrame:] : 1236 -> 1232
~ -[ChartHUDView setOverlayHidden:] : 264 -> 260
~ -[ChartHUDView layoutSubviews] : 3512 -> 3500
~ -[ChartHUDView tapDragGestureChanged:] : 1416 -> 1396
~ -[SCKZoneSnapshot isEqualToSnapshot:] : 804 -> 800
~ ___37-[SCKZoneSnapshot isEqualToSnapshot:]_block_invoke_6 : 508 -> 504
~ -[SCKZoneSnapshot descriptionOfContents] : 904 -> 900
~ -[ChartIntervalButtonRow sizeToBoldLabels] : 280 -> 276
~ -[ChartIntervalButtonRow layoutSubviews] : 724 -> 716
~ -[StockChartView enumerateGraphsAndDisplayModesUsingBlock:] : 368 -> 364
~ -[StockChartView layoutPreviousClose] : 1208 -> 1204
~ -[StockChartView hideOtherGraphViews] : 312 -> 308
~ -[StockChartView _setMonthAndYearLabels] : 2816 -> 2820
~ -[StockChartView _setDayLabelsWithInterval:realTimePositions:] : 1996 -> 2000
~ -[StockChartView _setHourLabels] : 1296 -> 1292
~ -[StockChartView _layoutAxesAndXLabels] : 2236 -> 2224
~ -[StockChartView widestYLabelWidthForMode:] : 288 -> 284
~ -[StockChartView hideLabelsAxesAndGraphs] : 644 -> 632
~ -[StockChartView setLabelsAndAxesAlpha:] : 592 -> 580
~ +[StocksOpenURLHelper componentDictionaryFromURL:] : 380 -> 376
~ -[SCKRecordSchema fieldNames] : 320 -> 316
~ -[SCKRecordSchema schemaForFieldName:] : 340 -> 336
~ -[SCKRecordSchema isValidRecord:] : 348 -> 344
~ -[StockGraphView setDottedLinePositionsWithLabelInfo:] : 404 -> 400
~ -[StockGraphView _priceAtTime:dataPosition:] : 368 -> 384
~ -[StockGraphView _timeAtPosition:] : 244 -> 248
~ -[StockGraphView _finishCurrentLine] : 340 -> 336
~ -[StockGraphView _processGraphDataForWidth:] : 2896 -> 2904
~ -[StockGraphView plottedPointNearestToPoint:] : 460 -> 468
~ -[StockGraphView volumeBarRectNearestToPoint:] : 376 -> 380
~ -[SCWatchlistDiff initWithOldStocks:newStocks:] : 1128 -> 1120
~ -[GraphRenderOperation renderGraphLineInContext:withColor:offset:] : 508 -> 504
~ -[GraphRenderOperation renderLineGraph] : 2504 -> 2496
~ -[GraphRenderOperation renderVolumeGraph] : 324 -> 316
~ -[StockManager init] : 1832 -> 1820
~ -[StockManager _defaultStockDictionaries] : 432 -> 428
~ -[StockManager reloadStocksFromDefaults] : 604 -> 600
~ -[StockManager handleSyncedDataChanged:] : 1304 -> 1300
~ -[StockManager makeSyncableStockListFromList:] : 892 -> 884
~ -[StockManager setLocalStockListFromSyncableStockList:] : 1000 -> 1016
~ -[StockManager stockWithSymbol:] : 336 -> 332
~ -[StockManager anyMarketOpen] : 256 -> 252
~ -[StockManager saveListChanges] : 836 -> 828
~ -[StockManager saveDataChanges] : 332 -> 328
~ -[StockManager purgeTransientData] : 444 -> 436
~ -[StockManager _checkForAddedStocks] : 640 -> 636
~ -[StockManager _checkForDeletedStocks] : 976 -> 964
~ -[StockManager _checkForMovedStocks] : 668 -> 664
~ -[NSArray(SCKAdditions) sck_dictionaryWithKeyBlock:] : 356 -> 352
~ -[NSArray(SCKAdditions) sck_containsObjectPassingTest:] : 288 -> 284
~ -[SCKZone clientDiff] : 404 -> 400
~ -[SCKZoneDiff applyToRecords:] : 692 -> 680
~ -[SCKZoneDiff hasSameBaseAsDiff:] : 1000 -> 988
~ +[YahooResponseParser parseStockQuoteDictionaries:withDataSources:parsedStockResult:] : 1036 -> 1032
~ -[SCKDatabase initWithSchema:store:features:mergeHandlers:containerProxy:] : 888 -> 876
~ ___26-[SCKDatabase synchronize]_block_invoke : 344 -> 340
~ ___51-[SCKDatabase _enqueueStartupSequenceWithFeatures:]_block_invoke_2.54 : 732 -> 724
~ ___51-[SCKDatabase _enqueueStartupSequenceWithFeatures:]_block_invoke_2.56 : 336 -> 332
~ ___51-[SCKDatabase _fetchDatabaseChangesWithCompletion:]_block_invoke.76 : 444 -> 440
~ ___52-[SCKDatabase _fetchZoneChangesForZones:completion:]_block_invoke_2 : 492 -> 488
~ -[SCKDatabase _squashZoneForMerge:zoneStore:] : 984 -> 980
~ ___56-[SCKDatabase _deleteAndRecreateAllZonesWithCompletion:]_block_invoke : 700 -> 696
~ -[SCKDatabase _emptyZonesNeedingFirstSync] : 460 -> 456
~ -[SCKDatabase _zonesNeedingFetch] : 460 -> 456
~ -[SCKDatabase _zonesNeedingSave] : 456 -> 452
~ ___47-[SCKDatabase _reloadSnapshotOfZone:fromStore:]_block_invoke : 296 -> 292
~ ___54-[SCKDatabase _recoverFromIdentityLossWithCompletion:]_block_invoke : 336 -> 332
~ -[SCKStubContainer setContentsOfZone:toRecords:] : 412 -> 408
~ -[SCKStubContainer addDatabaseOperation:] : 4876 -> 4852
~ ___41-[SCKStubContainer addDatabaseOperation:]_block_invoke : 692 -> 688
~ ___41-[SCKStubContainer addDatabaseOperation:]_block_invoke_2 : 492 -> 488
~ ___41-[SCKStubContainer addDatabaseOperation:]_block_invoke_3 : 360 -> 356
~ -[SCKStubContainer _errorForErrorMode:itemIDs:] : 552 -> 548
~ -[NSDictionary(SCKAdditions) sck_objectsForKeys:] : 352 -> 348
```
