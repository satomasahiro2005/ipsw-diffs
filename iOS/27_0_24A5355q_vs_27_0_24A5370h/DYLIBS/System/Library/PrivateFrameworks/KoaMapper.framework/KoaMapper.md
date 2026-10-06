## KoaMapper

> `/System/Library/PrivateFrameworks/KoaMapper.framework/KoaMapper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d550` | `0x1d524` | **`-0x2c`** |

### Other Changes

```diff

-3600.11.1.0.0
+3600.13.1.0.0
Functions:
~ -[KMMapper_SASyncSiriKitAppVocabulary itemsFromExternalObject:additionalFields:error:] : 1092 -> 1088
~ -[KMRadioStationBridge enumerateItemsWithError:usingBlock:] : 588 -> 584
~ -[KMFindMySyncDevicesBridge enumerateItemsWithError:usingBlock:] : 668 -> 664
~ ___60-[KMCalendarEventBridge enumerateItemsWithError:usingBlock:]_block_invoke : 428 -> 424
~ -[KMMapper_RTLocationOfInterest itemsFromExternalObject:additionalFields:error:] : 856 -> 852
~ -[KMLaunchServicesBridge enumerateItemsWithError:usingBlock:] : 956 -> 952
~ +[KMLaunchServicesBridge allInstalledAppBundleIdentifiers] : 584 -> 580
~ -[KMMapper_SAPerson _addLabeledFieldsForPhones:error:] : 348 -> 344
~ -[KMMapper_SAPerson _addLabeledFieldsForEmails:error:] : 348 -> 344
~ -[KMMapper_SAPerson _addLabeledFieldsForPostalAddresses:error:] : 348 -> 344
~ -[KMMapper_SAPerson _addLabeledFieldsForRelatedNames:error:] : 376 -> 372
~ -[KMMapper_CNContact _addLabeledFieldsOfType:labeledValues:labelOnly:excludeDefault:error:] : 732 -> 728
~ -[KMMapper_SAAppInfo itemsFromExternalObject:additionalFields:error:] : 864 -> 860
~ -[KMHomeManagerBridge enumerateItemsWithError:usingBlock:] : 1204 -> 1200
~ -[KMAppGlobalVocabularyMultiDatasetBridge enumerateAllDatasets:usingBlock:] : 880 -> 872
~ -[KMAppGlobalVocabularyMultiDatasetBridge _sortAppIntentVocabularyByCascadeItemType:] : 400 -> 396
~ -[KMAppGlobalVocabularyBridge enumerateItemsWithError:usingBlock:] : 328 -> 324
~ -[KMContactStoreBridge enumerateDeltaItemsWithError:addOrUpdateBlock:removeBlock:] : 1780 -> 1792
~ -[KMMapper_AppGlobalVocabulary itemsFromExternalObject:additionalFields:error:] : 2040 -> 2028
~ -[KMMapper_AppGlobalVocabulary _addItemWithItemId:fieldType:values:error:] : 528 -> 524
~ -[NSDictionary(KMMapper_AppGlobalVocabulary) _collectionValueForKey:collectonType:expectedObjectsType:keyRequired:error:] : 876 -> 872
~ -[KMMapper_MPMediaEntity _addItemWithItemId:itemIdType:fields:error:] : 724 -> 720
~ -[KMCoreRoutineBridge enumerateItemsWithError:usingBlock:] : 892 -> 888
~ -[KMMapper_HMHome itemsFromExternalObject:additionalFields:error:] : 2452 -> 2432
~ -[KMIntentVocabularyMultiDatasetBridge enumerateAllDatasets:usingBlock:] : 856 -> 852
~ -[KMIntentVocabularyDatasetBridge enumerateItemsWithError:usingBlock:] : 688 -> 684
~ _$s9KoaMapper13RadioListenerC11serialQueueACSo17OS_dispatch_queueC_tcfc : 296 -> 300
~ _$s9KoaMapper13RadioListenerCfETo : 140 -> 144
~ _$s9KoaMapper13RadioListenerC20clearDonatedStationsyyF : 532 -> 536
~ _$s9KoaMapper13RadioListenerC13radioStationsSaySo6KVItemCGyF : 2176 -> 2172
~ _$s9KoaMapper13RadioListenerC32generateItemsFromFrequencyRanges33_09F2E86DD1D686ED44BB7E40182A5028LLySaySo6KVItemCGSay10CAFCombine24CAFMediaSourceObservableCGSgF : 800 -> 804
~ _$s9KoaMapper13RadioListenerC19observeMediaSources33_09F2E86DD1D686ED44BB7E40182A5028LL4fromySo8CAFMediaC_tF : 2664 -> 2688
~ _$sSTsSQ7ElementRpzrlE8containsySbABFSaySo26CAFMediaSourceSemanticTypeVG_Tg5 : 48 -> 56
~ _$s9KoaMapper13RadioListenerC12itemListFrom33_09F2E86DD1D686ED44BB7E40182A5028LL12semanticType10mediaItemsSo022CAFMediaSourceSemanticQ0V_SaySo6KVItemCGtAI_SaySo0T4ItemCGtF : 312 -> 308
~ _$s9KoaMapper13RadioListenerC8itemFrom33_09F2E86DD1D686ED44BB7E40182A5028LL12semanticType9mediaItemSo6KVItemCSgSo022CAFMediaSourceSemanticP0V_So0tR0CtF : 1088 -> 1084
~ _$sShyShyxGqd__nc7ElementQyd__RszSTRd__lufCSo6KVItemC_SayAEGTt0g5 : 296 -> 304
~ _$s9KoaMapper13RadioListenerC23donationUpdateTriggeredyyF : 1156 -> 1148
~ _$s9KoaMapper13RadioListenerC18accessoryDidUpdate_17receivedAllValuesySo12CAFAccessoryC_SbtF : 500 -> 504
~ _$ss11_StringGutsV16_deconstructUTF87scratchyXlSg5owner_xSi6lengthSb11usesScratchSb15allocatedMemorytSwSg_ts8_PointerRzlFSV_Tgq5 : 268 -> 264
~ _OUTLINED_FUNCTION_17 : 24 -> 28
~ _OUTLINED_FUNCTION_18 : 32 -> 24
~ _OUTLINED_FUNCTION_20 -> _OUTLINED_FUNCTION_19 : 12 -> 32
~ _OUTLINED_FUNCTION_23 -> _OUTLINED_FUNCTION_22 : 28 -> 12
~ _OUTLINED_FUNCTION_24 : 16 -> 28
~ _OUTLINED_FUNCTION_28 -> _OUTLINED_FUNCTION_26 : 24 -> 16
~ _OUTLINED_FUNCTION_29 : 12 -> 24
~ _OUTLINED_FUNCTION_31 : 24 -> 12
~ _OUTLINED_FUNCTION_33 : 12 -> 24
~ _OUTLINED_FUNCTION_37 : 20 -> 12
~ _OUTLINED_FUNCTION_38 : 12 -> 20
~ _$s9KoaMapper19FrequencyRangeUtilsO27createStationGeneratorsFrom12mediaSourcesShyAA05RadiocD13ItemGeneratorVGSaySo14CAFMediaSourceCG_tFZ : 380 -> 388
~ _$sSp6assign9repeating5countyx_SitFs13_UnsafeBitsetV4WordV_Tgq5 : 28 -> 36
~ _$s9KoaMapper32RadioFrequencyRangeItemGeneratorV07stationD22StringsFromMediaSourceySaySSGSo08CAFMediaL0CF : 1080 -> 1076
~ _$s9KoaMapper32RadioFrequencyRangeItemGeneratorV09speakableD6String_12semanticTypeSSSi_So022CAFMediaSourceSemanticK0VtF : 200 -> 208
~ _$s9KoaMapper32RadioFrequencyRangeItemGeneratorV10itemIDFrom12semanticType9frequencySSSo022CAFMediaSourceSemanticK0V_SStF : 144 -> 152
~ _OUTLINED_FUNCTION_1 : 20 -> 12
```
