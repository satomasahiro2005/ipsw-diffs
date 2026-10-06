## PrintKit

> `/System/Library/PrivateFrameworks/PrintKit.framework/PrintKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x47938` | `0x47aa4` | **`+0x16c`** |
| `__TEXT.__cstring` | `0x7ce4` | `0x7d9a` | **`+0xb6`** |
| `__AUTH_CONST.__objc_intobj` | `0x1350` | `0x13f8` | **`+0xa8`** |
| `__AUTH_CONST.__cfstring` | `0xd960` | `0xda00` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x8dec` | `0x8e40` | **`+0x54`** |
| `__TEXT.__objc_methlist` | `0x312c` | `0x30f0` | **`-0x3c`** |
| `__AUTH_CONST.__objc_const` | `0x5478` | `0x5450` | **`-0x28`** |
| `__DATA_CONST.__const` | `0xdf68` | `0xdf90` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d00` | `0x1cf0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2cd8` | `0x2ce0` | **`+0x8`** |

### Other Changes

```diff

-324.0.0.0.0
+326.0.0.0.0

-  Symbols:   3070
-  CStrings:  2059
+  Symbols:   3075
+  CStrings:  2064
Symbols:
+ -[PKPrinterTool_Client logiCloudPrintersWithCompletionHandler:]
+ _PKiCloudCommandKey
+ _PKiCloudPrinterInfoKey
+ _PKiCloudPrinterNewInfo
+ _PKiCloudPrinterNewInfoKey
+ _PKiCloudPrintersKey
+ ___63-[PKPrinterTool_Client logiCloudPrintersWithCompletionHandler:]_block_invoke
- -[PKPrinterTool_Client logiCloudPrintersCompletionHandler:]
- ___59-[PKPrinterTool_Client logiCloudPrintersCompletionHandler:]_block_invoke
Functions:
~ -[PKPrinterTool_Client getiCloudPrintersWithCompletionHandler:] : 296 -> 360
~ -[PKPrinterTool_Client addPrinterToiCloud:] : 204 -> 288
~ -[PKPrinterTool_Client removePrinterFromiCloud:] : 204 -> 288
~ -[PKPrinterTool_Client updateiCloudPrinter:withInfo:forInfoKey:] : 260 -> 368
~ -[PKPrinterTool_Client setiCloudPrinters:] : 168 -> 252
~ -[PKPrinterTool_Client resetPKCloudData] : 128 -> 188
~ -[PKPrinterTool_Client logiCloudPrintersCompletionHandler:] -> -[PKPrinterTool_Client logiCloudPrintersWithCompletionHandler:] : 296 -> 360
~ __ZL17ippReadWithReaderR11IPPIOReaderR11ipp_state_eR9ipp_tag_ebP8PK_ipp_t : 5008 -> 5012
~ __ZL12urf_compressP14_urf_context_s : 1560 -> 1576
~ -[PK_ipp_value_t loggingValue:] : 2104 -> 2100
~ -[PK_ipp_attribute_t copyWithZone:] : 352 -> 348
~ -[PK_ipp_t _initWithAttrs:] : 372 -> 368
~ ___50-[PK_ipp_t _addStrings:valueTag:name:lang:values:]_block_invoke : 584 -> 580
~ __Z28liteFigureOutDriverSetupInfoP16XDriverSetupInfoP13lite_driver_sP12NSDictionaryIP8NSStringS5_E : 1868 -> 1856
~ __Z15pwgMediaForSizeiiP10pwg_info_t : 452 -> 464
~ __ZN10MediaArray9findMediaEPKcU13block_pointerFS1_PK11pwg_media_sE : 136 -> 144
~ __ZL17pwgFormatSizeNamePcmPKcS1_iiS1_ : 768 -> 760
~ _liteInitURF : 3212 -> 3244
~ __ZL16urf_parse_valuesPKcPii : 140 -> 144
~ ___48+[PKDefaults lastUsedPrintersCompletionHandler:]_block_invoke : 808 -> 804
~ +[PKDefaults lastUsedPrintersForPhoto:completionHandler:] : 1176 -> 1164
~ +[PKDefaults iCloudPrintersSync] : 672 -> 668
~ ___53+[PKDefaults getUpdatediCloudPrintersFromPrinterTool]_block_invoke : 592 -> 588
~ +[PKDefaults(PrintKitPrivate) uriMatchesMCProfileAdded:] : 460 -> 456
~ ___21+[PKJob jobForJobID:]_block_invoke_2 : 356 -> 352
~ ___37+[PKJob currentJobCompletionHandler:]_block_invoke : 532 -> 528
~ -[PKJob localizedJobOptions] : 1564 -> 1560
~ -[PKiCloudPrinter userCodableDictionary] : 1580 -> 1576
~ -[PKMediaName parseMediaName:] : 612 -> 624
~ ___27-[PKPaper visitProperties:]_block_invoke : 476 -> 472
~ -[PKPrinterDescription makeTXTRecordWithURL:] : 1176 -> 1172
~ -[PKPrinterDescription(PrintertoolSideConstruction) _calcFinishingTemplates:] : 1340 -> 1336
~ -[PKPrinterDescription(PrintertoolSideConstruction) _calcIdentifyActions:] : 436 -> 432
~ -[PKPrinterDescription(PrintertoolSideConstruction) _calcSpecialFeedOrientation:] : 692 -> 688
~ -[PKPrinterDescription(PrintertoolSideConstruction) _calculateFormats:] : 852 -> 848
~ -[PKPrinterDescription(PrintertoolSideConstruction) _calcInputSlots:] : 600 -> 596
~ -[PKPrinterDescription(PrintertoolSideConstruction) _calcMediaTypes:] : 848 -> 844
~ -[PKPrinterDescription(PrintertoolSideConstruction) _calcJobPresets:] : 836 -> 832
~ __Z18_cupsGet1284ValuesP8NSString : 648 -> 620
~ -[PKPrinterDescription(PrintertoolSideConstruction) _makePrinterDeviceIDFromTxt] : 1440 -> 1436
~ -[PKMediaCol getMargins:] : 376 -> 368
~ -[PKMutableMediaCol setMarginsTop:left:bottom:right:] : 328 -> 324
~ -[PKPaperList(PrintertoolSideConstruction) initWithParams:translations:] : 944 -> 940
~ -[PKPaperList adjustMargins:forDuplex:] : 452 -> 448
~ -[PKPaperList categorizePapers:] : 1084 -> 1048
~ -[PKPaperList tersePaperFrom:withRequest:] : 728 -> 724
~ -[PKPaperList tersePaperFrom:withMediaInfo:] : 580 -> 576
~ -[PKPaperList rollReadyPaperListForDocumentWithContentSize:scaleUp:] : 564 -> 560
~ -[PKPaperList rollReadyPaperListForPhotoWithContentSize:] : 636 -> 632
~ -[PKPaperList availableRollPapersPreferBorderless:] : 624 -> 620
~ -[PKPaperList jobTypesSupported:] : 548 -> 544
~ ____ZN30XUserCodedSerializationVisitor27makeTypedArrayFromUserCodedIU8__strongP7NSValueEEU13block_pointerFP8NSObjectPU28objcproto17PKUserCodableTypeS4_Ev_block_invoke : 440 -> 436
~ ____ZN30XUserCodedSerializationVisitor27makeTypedArrayFromUserCodedIU8__strongP8NSNumberEEU13block_pointerFP8NSObjectPU28objcproto17PKUserCodableTypeS4_Ev_block_invoke : 440 -> 436
~ ____ZN30XUserCodedSerializationVisitor27makeTypedArrayFromUserCodedIU8__strongP8NSStringEEU13block_pointerFP8NSObjectPU28objcproto17PKUserCodableTypeS4_Ev_block_invoke : 440 -> 436
~ ____ZN30XUserCodedSerializationVisitor27makeTypedArrayFromUserCodedIU8__strongP12NSDictionaryEEU13block_pointerFP8NSObjectPU28objcproto17PKUserCodableTypeS4_Ev_block_invoke : 440 -> 436
~ ____ZN30XUserCodedSerializationVisitor27makeTypedArrayFromUserCodedIU8__strongP7PKPaperEEU13block_pointerFP8NSObjectPU28objcproto17PKUserCodableTypeS4_Ev_block_invoke : 440 -> 436
~ ____ZN30XUserCodedSerializationVisitor27makeTypedArrayFromUserCodedIU8__strongP6PKTrayEEU13block_pointerFP8NSObjectPU28objcproto17PKUserCodableTypeS4_Ev_block_invoke : 440 -> 436
~ -[PKPrintSettings pageRanges] : 456 -> 452
~ -[PKPrintSettings setPageRanges:] : 444 -> 440
~ ____Z14_visitHexLinesP6NSDatabU13block_pointerFvP8NSStringE_block_invoke : 616 -> 596
~ -[PKPrinter jobTypesSupported] : 516 -> 512
~ ___57-[PKPrinter pollForPrinterStatusQueue:completionHandler:]_block_invoke : 1460 -> 1456
~ -[PKPrinterBrowser btleRssiUpdated:rssi:] : 904 -> 900
~ -[PKPrinterBrowser printerAdded:more:] : 1420 -> 1412
~ -[PKPrinterBrowser btlePrinterFound:] : 1252 -> 1244
~ +[PKSupply isValidColorString:] : 144 -> 156
~ __ZL15_is_valid_colorPKc : 152 -> 176
~ -[PKSupply initWithName:markerType:colors:level:lowLevel:highLevel:] : 748 -> 776
~ -[PKTXTRecord initWithDictionary:] : 468 -> 464
~ +[PKTray filter:withBlock:] : 408 -> 404
~ -[PKTray initWithString:andMediaSource:] : 804 -> 800
~ __ZL28dictionaryWithLowercasedKeysP12NSDictionary : 604 -> 600
~ _PKParsePrinterStateReasons : 988 -> 984
~ _PKCopyLocalizedPrinterStateReasons : 1460 -> 1452
CStrings:
+ "com.apple.printkit.icloud-command"
+ "com.apple.printkit.icloud-printer-info"
+ "com.apple.printkit.icloud-printers"
+ "com.apple.printkit.new-icloud-info"
+ "com.apple.printkit.new-icloud-info-key"
```
