## CoreSuggestions

> `/System/Library/PrivateFrameworks/CoreSuggestions.framework/CoreSuggestions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8e574` | `0x8e434` | **`-0x140`** |

### Other Changes

```diff

-1331.0.1.0.0
+1334.0.1.0.0
Functions:
~ +[SGDSuggestManagerInterface _whitelistXPCInterface:forProtocol:alreadyWhitelisted:] : 344 -> 340
~ +[SGDSuggestManagerInterface _addSGXPCResponseToReplyWhitelistForMethods:count:interface:] : 772 -> 796
~ _sgMapAndFilter : 376 -> 372
~ _SGDelimitedStringsSerialize : 1252 -> 1240
~ _SGDelimitedStringsDeserializeWithBlock : 1100 -> 1076
~ +[SGOrigin originForMailSearchableItem:] : 588 -> 584
~ _sgFilter : 368 -> 364
~ _SGDelimitedStringsSerializeArray : 344 -> 340
~ +[SGObjCRuntime _arityForBlockAtIndex:inSelector:instanceMethod:ofProtocol:seenProtocols:foundSelector:] : 472 -> 468
~ +[SGFuture waitForFuturesToComplete:withCallback:] : 568 -> 564
~ +[SGEventGeocode isGeocodeCandidate:] : 292 -> 288
~ +[SGEventGeocode pirResultFromData:withDistance:fromCoordinates:] : 872 -> 868
~ ___31+[SGEventGeocode geocodeEvent:]_block_invoke_2 : 2016 -> 2012
~ +[SGEventGeocode poiCategoriesFromString:] : 628 -> 624
~ _collapseWhitespaceAndStrip : 984 -> 956
~ -[SGKeyValueCacheFile setValueIfNotPresentWithDict:fromRecordId:] : 952 -> 944
~ -[SGKeyValueCacheFile deleteValueByRecordIdSet:] : 708 -> 704
~ +[SGSimpleNamedEmailAddress namedEmailAddressesWithFieldValues:] : 352 -> 348
~ +[SGSimpleNamedEmailAddress emailToNameDictionaryWithNamedEmailAddresses:] : 416 -> 412
~ +[SGSimpleNamedEmailAddress serializeAll:] : 340 -> 336
~ -[SGMatchedDetails initWithContact:matchinfoData:tokens:] : 388 -> 384
~ ___61-[SGMatchedDetails _initilizeDictionariesFromTokenDetailMap:]_block_invoke : 364 -> 360
~ +[SGEventMetadata eventMetadataFromEKEvent:] : 1224 -> 1220
~ -[SGEventMetadata jsonObject] : 532 -> 528
~ _SGSetSiriPrefsHidden : 2244 -> 2232
~ _SGSetSiriPrefsLocked : 1040 -> 1032
~ _SGParseNamedEmailAddress : 6276 -> 6272
~ +[SGIPMessage messageWithIPMessage:] : 944 -> 936
~ +[SGMailIntelligenceStringHasher truncatedSHA256:salts:] : 464 -> 460
~ -[SGTimeZoneDetector _getCountryCodeForCountryName] : 1288 -> 1280
~ -[SGTimeZoneDetector _getTimeZoneForCountryCode] : 608 -> 612
~ -[SGTimeZoneDetector _countryCodeByRegionAbbreviationFromNormalizedAddress:] : 688 -> 684
~ -[SGTimeZoneDetector _countryCodeByRegularExpressionFromNormalizedAddress:] : 460 -> 456
~ -[SGTimeZoneDetector _countryCodeByCountryNameFromNormalizedAddressWords:] : 692 -> 688
~ +[SGPersistentSaltProvider hexStringForData:] : 172 -> 180
~ _sgMap : 372 -> 368
~ _sgMapSelector : 364 -> 360
~ -[SGCircularBufferArray countByEnumeratingWithState:objects:count:] : 200 -> 196
~ -[SGRealtimeContact setExtractionInfo] : 1756 -> 1740
~ -[_SGNSStringEncodingEnumerator nextObject] : 448 -> 444
~ -[SGContactMatch matchingField] : 544 -> 540
~ +[SGNLEventSuggestionsMetrics recordInteractionForEventWithInterface:actionType:harvestedSGEvent:curatedEKEvent:] : 1896 -> 1892
~ +[SGNLEventSuggestionsMetrics getAddedAttendeesCountFromEKEvent:] : 348 -> 344
~ +[SGSuggestedActionMetrics recordBannerShownWithContacts:events:inApp:] : 1412 -> 1400
~ _tagsToEventCategory : 364 -> 360
~ +[SGPreferenceStorage removeDeprecatedDefaults] : 276 -> 272
~ -[SGMessagesSuggestionsService setupContextIfNeededForConversation:] : 396 -> 392
~ -[SGMessagesSuggestionsService sendContextForMessage:] : 464 -> 460
~ -[SGContact enumerateDetailsWithBlock:] : 584 -> 580
~ -[SGGeoListSnippet dictionaryRepresentation] : 404 -> 400
~ -[SGGeoListSnippet writeTo:] : 276 -> 272
~ -[SGGeoListSnippet copyWithZone:] : 316 -> 312
~ -[SGGeoListSnippet mergeFrom:] : 260 -> 256
~ -[SGStructuredAddress writeTo:] : 572 -> 568
~ -[SGStructuredAddress copyWithZone:] : 684 -> 680
~ -[SGStructuredAddress mergeFrom:] : 532 -> 528
~ -[SGDaemonConnection _callAbortBlocks] : 288 -> 284
~ -[SGEvent initWithRecordId:origin:uniqueKey:opaqueKey:title:notes:start:startTimeZone:end:endTimeZone:isAllDay:creationDate:lastModifiedDate:locations:tags:URL:] : 944 -> 940
~ -[SGEvent ekEventAvailabilityState] : 520 -> 516
~ -[SGEvent shouldAllowNotificationsInCalendarForBundleId:appIsInForeground:allowListOverride:] : 1216 -> 1208
~ -[SGEvent _mergeTagsIntoEKEvent:withStore:] : 412 -> 408
~ -[SGEvent mergeIntoEKEvent:withStore:preservingValuesDifferentFrom:] : 4768 -> 4760
~ -[SGEvent firstLocationForType:] : 312 -> 308
~ -[SGEvent geocodingMode] : 440 -> 436
~ -[SGEvent poiFilters] : 332 -> 328
~ -[SGEvent _naturalLanguageEventTagsInTags:] : 428 -> 424
```
