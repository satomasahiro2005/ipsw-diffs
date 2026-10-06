## AppSupport

> `/System/Library/PrivateFrameworks/AppSupport.framework/AppSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2dd80` | `0x2df24` | **`+0x1a4`** |
| `__TEXT.__unwind_info` | `0xc48` | `0xc50` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 1192
-  Symbols:   2469
+  Functions: 1191
+  Symbols:   2468
Symbols:
- _OUTLINED_FUNCTION_11
Functions:
~ _CPDateFormatStringForFormatType : 2404 -> 2400
~ _migHelperRecievePortCallout : 500 -> 504
~ _ExplainQueryPlanCallback : 364 -> 376
~ _CPSqliteConnectionFlushStatementCache : 196 -> 200
~ _CPSqliteStatementBindValuesForColumns : 96 -> 112
~ _CPSqliteConnectionAddRecordWithRowid : 984 -> 996
~ __sqliteStatementApplyValuesFromRecordWithNullValue : 852 -> 876
~ _CPSqlitePhoneNumberContainsAlphaCharacters : 216 -> 236
~ _CPRecordCreateWithRecordID : 184 -> 180
~ _CPRecordCreateCopy : 160 -> 164
~ _CPRecordDestroy : 260 -> 244
~ _CPRecordShow : 580 -> 576
~ _CPRecordIndexOfPropertyNamed : 104 -> 108
~ _CPRecordStoreCopyDeletedRecords : 316 -> 320
~ _CPRecordStoreCreateTablesForClass : 1264 -> 1256
~ _CPRecordStoreCreateReadColumns : 664 -> 680
~ __CPRecordStoreCreateColumnListFromRecordDescriptor : 572 -> 564
~ __CPRecordStoreGetChangesAndChangeIndicesAndSequenceNumbersForClassWithPropertiesV : 396 -> 388
~ _CPRecordStoreGetChangesAndChangeIndicesAndSequenceNumbersForClassWithBindBlockAndPropertiesA : 268 -> 272
~ __CPRecordStoreGetChangesAndChangeIndicesAndSequenceNumbersForClassWithPropertiesA : 1256 -> 1292
~ __updateModificationDateProperties : 180 -> 176
~ _CPRecordStoreWriteColumnsForRecord : 616 -> 612
~ __logRecordEvent : 1220 -> 1240
~ _OUTLINED_FUNCTION_1 : 16 -> 20
~ _OUTLINED_FUNCTION_2 : 36 -> 16
~ _OUTLINED_FUNCTION_6 : 44 -> 28
~ _OUTLINED_FUNCTION_7 : 24 -> 44
- _OUTLINED_FUNCTION_11
~ _CPPhoneNumberGetLastFour : 544 -> 548
~ _CPSecureDeleteFile : 500 -> 504
~ ___CPPowerAssertionGetTimeouts : 144 -> 140
~ -[CPDistributedNotificationCenter postNotificationName:userInfo:toBundleIdentifier:] : 896 -> 908
~ _dictionaryWithoutLargestNSData : 432 -> 428
~ -[CPNetworkObserver removeObserver:] : 300 -> 296
~ -[CPNetworkObserver _networkReachableCallBack:] : 400 -> 396
~ -[CPSearchMatcher matchesASCIIString:matchType:] : 1004 -> 1028
~ -[CPSearchMatcher matchesUTF8String:matchType:matchOptions:] : 648 -> 644
~ -[CPSearchMatcher initWithSearchString:andLocale:andOptions:] : 440 -> 436
~ _matche : 5592 -> 5744
~ _utf8_prev_char_start : 144 -> 140
~ _utf8_to_code_point : 108 -> 112
~ _unicode_combinable : 88 -> 96
~ _unicode_decomposeable : 88 -> 96
~ _utf8_encodestr : 792 -> 784
~ _utf8_decodestr : 1148 -> 1220
~ _check_and_decompose_string : 584 -> 596
~ _map_case : 200 -> 192
~ __ICUSQLiteMatch : 1208 -> 1216
~ -[PEPServiceConfiguration _updateDefaults:] : 828 -> 824
~ -[PEPServiceConfiguration registerNetworkDefaultsForAppIDs:forceUpdate:] : 568 -> 564
~ -[ALCityManager localizeCities:] : 1984 -> 1980
~ +[ALCityManager newCitiesByIdentifierMap:] : 348 -> 344
~ -[ALCityManager citiesWithIdentifiers:] : 744 -> 740
~ -[ALCityManager bestCityForLegacyCity:] : 464 -> 460
~ -[ALCityManager defaultCitiesForLocaleCode:options:] : 868 -> 864
~ -[ALCityManager _defaultCityForTimeZone:localeCode:] : 868 -> 864
~ -[CPBitmapStore openAndMmap:withInfo:] : 432 -> 428
~ ___85-[CPBitmapStore storeImageDataForKey:inGroup:withSize:format:formatColor:scale:data:]_block_invoke : 272 -> 280
~ ___49-[CPBitmapStore removeImagesInGroups:completion:]_block_invoke : 760 -> 756
~ __obfuscatedRepresentation : 708 -> 712
~ __createUTF8StringFromString : 380 -> 384
~ -[CPMemoryPool nextSlotWithBytes:length:] : 376 -> 372
~ _CPRecordStoreSaveRecord : 1396 -> 1424
~ _CPRecordStoreUpdateRecord : 848 -> 900
~ _CPRecordStoreProcessAddedRecordsWithPolicyAndTransactionTypeMatchingPredicate : 468 -> 476
```
