## WeatherFoundation

> `/System/Library/PrivateFrameworks/WeatherFoundation.framework/WeatherFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x47508` | `0x4746c` | **`-0x9c`** |

### Other Changes

```text
Functions:
~ -[WFDefaultFavoritesProvider locations] : 520 -> 516
~ -[WFWeatherDataServiceParserV1(ParseNextHour) parseNextHourPrecipitationFromData:withUnit:] : 2192 -> 2180
~ -[WFWeatherDataServiceParserV1(ParsePollen) parsePollenFromData:] : 892 -> 888
~ +[WFLocationQueryGeocode queryWithDictionaryRepresentation:resultHandler:] : 560 -> 556
~ -[WFWeatherChannelParserV2 parseForecastData:types:location:locale:date:error:rules:] : 1220 -> 1216
~ -[WFWeatherChannelParserV2 parseDailyForecasts:] : 1608 -> 1600
~ -[WFWeatherChannelParserV2 parseHourlyForecasts:] : 1256 -> 1252
~ -[WFWeatherChannelParserV2 parseAirQualityData:location:error:] : 2024 -> 2020
~ -[WFWeatherDataServiceParserV1(ParseHourlyForecast) parseHourlyForecastFromData:withUnit:] : 440 -> 436
~ -[WFWeatherChannelValidator validateDictionary:expectedStructure:] : 1056 -> 1052
~ ___31-[WeatherService removeClient:]_block_invoke : 404 -> 400
~ -[WFWeatherDataServiceParserV1(ParseSevereWeather) parseSevereWeatherEventsFromData:withUnit:] : 800 -> 796
~ -[WFNextHourPrecipitation activeMinutes] : 692 -> 688
~ -[WFNextHourPrecipitation currentDescription] : 580 -> 576
~ -[WFNextHourPrecipitation description] : 420 -> 416
~ -[WFRemoteAppSettings getSpecificConfigFromConfigs:configSpecifiers:specifierKey:] : 536 -> 532
~ -[WFRemoteAppSettings getAPIVersionFromDictionary:userID:] : 576 -> 572
~ ___44-[WFNetworkBehaviorMonitor logNetworkEvent:]_block_invoke : 252 -> 248
~ -[WFWeatherDataServiceParserV1(ParseHourlyHistory) parseHourlyHistoryFromData:withUnit:] : 440 -> 436
~ -[WFWeatherDataServiceParserV1 parseAQIScaleNamed:data:error:] : 3184 -> 3176
~ -[NSDictionary(WFAdditions) wf_objectOfKind:forKeyPath:] : 492 -> 488
~ -[WFWeatherStoreService _cleanupCallbacksAndTasksForURL:] : 704 -> 700
~ -[WFWeatherUndergroundParser parseHistoricalForecast:error:] : 2048 -> 2044
~ +[NSDate(WFPrivateAdditions) wf_weatherConditionsClosestToDate:inArray:] : 396 -> 392
~ +[NSDate(WFPrivateAdditions) wf_allWeatherConditionsOnDate:inCalendar:inArray:] : 408 -> 404
~ -[WFWeatherChannelParserV3 _parseForecastedConditions:individualForecastProcessingBlock:uniqueParsingBlock:] : 776 -> 772
~ ___60-[WFWeatherChannelParserV3 _parseDailyForecastedConditions:]_block_invoke : 556 -> 552
~ -[WFWeatherChannelParserV3 _parseDailyPollenForecastedConditions:] : 908 -> 904
~ -[WFWeatherChannelParserV3 parseForecastData:types:location:locale:date:error:rules:] : 2816 -> 2820
~ -[WFAirQualityProviderAttribution p_invokeAndClearCompletionBlocksWithImage:error:] : 384 -> 380
~ _CLPlacemarkClosestToReferenceLocation : 424 -> 420
~ -[WFLocation summaryThatIsCompact:] : 436 -> 432
~ +[WFLocation locationsByFilteringDuplicates:] : 448 -> 444
~ +[WFLocation locationsByConsolidatingDuplicates:originalOrder:] : 720 -> 716
~ +[WFLocation locationsByConsolidatingDuplicatesInBucket:] : 528 -> 524
~ -[WFWeatherDataServiceParserV1(ParseDailyHistory) parseDailyHistoryFromData:withUnit:] : 440 -> 436
~ -[WFSettingsManager notifyObserversOfAppConfigRefresh] : 332 -> 328
```
