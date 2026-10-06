## BusinessChatService

> `/System/Library/PrivateFrameworks/BusinessChatService.framework/BusinessChatService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6d428` | `0x6d21c` | **`-0x20c`** |

### Other Changes

```diff

-30122.30.5.19.1
+30123.30.6.2.1
Functions:
~ -[BCSOpenHours isOpenAtDate:] : 684 -> 680
~ -[BCSOpenHours dateWhenOpenNextAfterDate:] : 868 -> 864
~ -[BCSOpenHours debugDescription] : 680 -> 676
~ -[BCSHoursPeriodMessage dictionaryRepresentation] : 404 -> 400
~ -[BCSHoursPeriodMessage writeTo:] : 276 -> 272
~ -[BCSHoursPeriodMessage copyWithZone:] : 316 -> 312
~ -[BCSHoursPeriodMessage mergeFrom:] : 260 -> 256
~ ___74-[BCSBloomFilterExtractor extractShardsURLsFromBloomFilterURL:completion:]_block_invoke.12 : 1044 -> 1040
~ -[BCSDomainBundleIdPatterns dictionaryRepresentation] : 440 -> 436
~ -[BCSDomainBundleIdPatterns writeTo:] : 308 -> 304
~ -[BCSDomainBundleIdPatterns copyWithZone:] : 356 -> 352
~ -[BCSDomainBundleIdPatterns mergeFrom:] : 308 -> 304
~ -[BCSFilterShardItem containsItemMatching:] : 520 -> 516
~ -[BCSBusinessCallerItem(ProtoConversion) initWithParquetMessage:] : 976 -> 968
~ -[BCSBusinessQueryController warmCacheIfNecessaryForPhoneNumbers:forClientBundleID:] : 384 -> 380
~ -[BCSBusinessQueryController _itemResolverForType:] : 84 -> 88
~ -[BCSBusinessQueryController fetchConfigForQuery:completion:] : 868 -> 872
~ -[BCSBusinessQueryController _shardResolverForType:] : 88 -> 92
~ ___62-[BCSBusinessQueryController fetchShardsWithQuery:completion:]_block_invoke.60 : 804 -> 800
~ ___79-[BCSBusinessQueryController fetchAreBusinessesRegisteredWithQuery:completion:]_block_invoke : 924 -> 920
~ ___79-[BCSBusinessQueryController fetchAreBusinessesRegisteredWithQuery:completion:]_block_invoke.139 : 928 -> 924
~ -[BCSBusinessQueryController fetchItemsWithQuery:perItemCompletion:completion:] : 1196 -> 1192
~ ___79-[BCSBusinessQueryController fetchItemsWithQuery:perItemCompletion:completion:]_block_invoke : 2428 -> 2420
~ -[BCSBusinessQueryController fetchBusinessMetadataForEmails:forClientBundleID:requestId:completion:] : 2552 -> 2544
~ -[BCSWebPresentmentParquetMessage dictionaryRepresentation] : 672 -> 668
~ -[BCSWebPresentmentParquetMessage writeTo:] : 492 -> 488
~ -[BCSWebPresentmentParquetMessage copyWithZone:] : 568 -> 564
~ -[BCSWebPresentmentParquetMessage mergeFrom:] : 476 -> 472
~ -[BCSBusinessEmailItemIdentifier pirKey] : 236 -> 232
~ -[BCSOpenHours(BCSProtoConversion) initWithHoursMessages:timeZone:] : 828 -> 820
~ -[BCSBusinessItem(BCSProtoConversion) initWithChatSuggestMessage:bucketID:] : 1164 -> 1156
~ +[BCSBusinessItem(BCSProtoConversion) businessItemsFromChatSuggestJSONObj:] : 776 -> 768
~ +[BCSBusinessItem(BCSProtoConversion) businessItemsFromChatSuggestMessageDictionary:] : 632 -> 628
~ +[BCSBusinessItem(BCSProtoConversion) businessItemsFromRecords:] : 560 -> 556
~ -[BCSLinkItemModel(BCSProtoConversion) initWithLinkMessage:bucketID:] : 1088 -> 1080
~ +[BCSLinkItemModel(BCSProtoConversion) linkItemModelsFromLinkJSONObj:] : 796 -> 780
~ +[BCSLinkItemModel(BCSProtoConversion) linkItemModelsFromRecords:] : 564 -> 560
~ +[BCSLinkItem(BCSProtoConversion) linkItemsFromLinkItemModels:] : 384 -> 380
~ -[BCSEmailMetadataParquetMessage dictionaryRepresentation] : 920 -> 912
~ -[BCSEmailMetadataParquetMessage writeTo:] : 628 -> 620
~ -[BCSEmailMetadataParquetMessage copyWithZone:] : 724 -> 716
~ -[BCSEmailMetadataParquetMessage mergeFrom:] : 624 -> 616
~ -[BCSBusinessEmailResolver itemsMatching:metric:perItemBlock:completion:] : 1716 -> 1712
~ -[BCSHoursMessage dictionaryRepresentation] : 592 -> 584
~ -[BCSHoursMessage writeTo:] : 340 -> 332
~ -[BCSHoursMessage copyWithZone:] : 336 -> 332
~ -[BCSHoursMessage mergeFrom:] : 332 -> 328
~ -[BCSIdentityService businessChatAccount] : 504 -> 500
~ ___57-[BCSIdentityService refreshIDStatusForBizID:completion:]_block_invoke : 464 -> 460
~ +[BCSHashService SHA256HashForInputString:] : 196 -> 204
~ -[BCSChatSuggestMessage dictionaryRepresentation] : 1640 -> 1624
~ -[BCSChatSuggestMessage writeTo:] : 1148 -> 1132
~ -[BCSChatSuggestMessage copyWithZone:] : 1308 -> 1292
~ -[BCSChatSuggestMessage mergeFrom:] : 1112 -> 1096
~ -[BCSBundleIdPatterns dictionaryRepresentation] : 440 -> 436
~ -[BCSBundleIdPatterns writeTo:] : 308 -> 304
~ -[BCSBundleIdPatterns copyWithZone:] : 356 -> 352
~ -[BCSBundleIdPatterns mergeFrom:] : 308 -> 304
~ -[BCSQueryChopper queryChopperDelegate:isBusinessRegisteredForURL:isBloomFilterCached:forClientBundleID:metric:completion:] : 1616 -> 1612
~ -[BCSWebPresentmentItem initWithBrandID:localizedNames:] : 452 -> 448
~ -[BCSWebPresentmentItem initWithBrandID:localizedNames:businessId:companyId:] : 508 -> 504
~ -[BCSBusinessEmailItem initWithEmail:localizedNames:] : 448 -> 444
~ -[BCSBusinessEmailItem initWithEmail:localizedNames:localizedDisplayNames:businessId:companyId:] : 672 -> 664
~ -[BCSItemCache itemMatching:] : 216 -> 212
~ -[BCSItemCache updateItem:withItemIdentifier:] : 228 -> 224
~ -[BCSItemCache deleteItemMatching:] : 208 -> 204
~ -[BCSLinkItem businessLinkContentItem] : 1044 -> 1036
~ -[BCSCallerIdParquetMessage dictionaryRepresentation] : 920 -> 912
~ -[BCSCallerIdParquetMessage writeTo:] : 628 -> 620
~ -[BCSCallerIdParquetMessage copyWithZone:] : 724 -> 716
~ -[BCSCallerIdParquetMessage mergeFrom:] : 624 -> 616
~ -[BCSBusinessLinkMessage dictionaryRepresentation] : 1068 -> 1060
~ -[BCSBusinessLinkMessage writeTo:] : 724 -> 716
~ -[BCSBusinessLinkMessage copyWithZone:] : 828 -> 820
~ -[BCSBusinessLinkMessage mergeFrom:] : 708 -> 700
~ -[BCSShardResolver shardItemsMatching:metric:completion:] : 1368 -> 1364
~ ___57-[BCSShardResolver shardItemsMatching:metric:completion:]_block_invoke : 532 -> 528
~ -[BCSURLPatternController matchPatternForURL:forClientBundleID:completion:] : 1848 -> 1844
~ -[BCSURLPatternController mostExplicitMatchingResultFromResults:] : 396 -> 392
~ -[NSArray(BCSProtoLocalizedStringsHelper) localizedStringsToDictionary] : 352 -> 348
~ -[NSArray(BCSProtoLocalizedStringsHelper) defaultLocalizedStringsValue] : 328 -> 324
~ -[BCSBusinessItem debugDescription] : 1020 -> 1016
~ -[BCSBusinessItem callToAction] : 432 -> 428
~ -[BCSBusinessItem _selectedVisibilityItemForLanguage:country:] : 892 -> 884
~ -[BCSOpenHours(Conversion) initWithOpenHours:timeZone:] : 992 -> 988
~ -[BCSURLPatternMatcher matchPattern:withURL:forBundleID:expirationDate:error:] : 2012 -> 2008
~ -[BCSURLPatternMatcher dictionaryFromQueryString:orderedKeys:] : 616 -> 608
~ -[BCSURLPatternMatcher orderedKeysForPatternQuery:originalURLQuery:orderedOriginalURLQueryKeys:] : 588 -> 580
~ ___87-[BCSRemoteFetchCloudKit fetchConfigItemWithType:clientBundleID:systemTask:completion:]_block_invoke : 504 -> 500
~ ___71-[BCSRemoteFetchCloudKit fetchShardMatching:clientBundleID:completion:]_block_invoke : 504 -> 500
~ ___90-[BCSRemoteFetchCloudKit fetchMegashardItemWithType:clientBundleID:systemTask:completion:]_block_invoke : 536 -> 532
~ ___100-[BCSRemoteFetchCloudKit fetchItemsWithBucketStartIndex:endIndex:type:forClientBundleID:completion:]_block_invoke : 504 -> 500
~ -[BCSBusinessCallerItem initWithPhoneNumber:phoneHash:localizedNames:localizedDepartments:logoURL:logo:logoFormat:verified:] : 756 -> 748
~ ___86-[BCSIconRemoteFetch fetchSquareIconDataForBusinessItem:forClientBundleID:completion:]_block_invoke : 500 -> 496
~ -[BCSBlastDoorPersistentStore deleteExpiredImages] : 788 -> 784
~ -[BCSRemoteFetchPIR fetchDataMatchingBatch:timeout:perItemBlock:completion:] : 1504 -> 1500
~ ___76-[BCSRemoteFetchPIR fetchDataMatchingBatch:timeout:perItemBlock:completion:]_block_invoke_2 : 948 -> 944
~ -[BCSPIRBatchRequest initWithQuery:] : 556 -> 552
```
