## Weather

> `/System/Library/PrivateFrameworks/Weather.framework/Weather`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x488d4` | `0x487bc` | **`-0x118`** |

### Other Changes

```text
Functions:
~ _WASymbolGlyphHexColorsFromConditionCode : 348 -> 344
~ _WAConditionsLine2StringFromHourlyForecasts : 912 -> 908
~ ___42-[WATodayModel _fireTodayModelWantsUpdate]_block_invoke : 296 -> 292
~ ___50-[WATodayModel _fireTodayModelForecastWasUpdated:]_block_invoke : 296 -> 292
~ -[NSArray(Weather) wa_allObjectsPassTest:] : 292 -> 288
~ -[WATodayHourlyForecastView initWithFrame:] : 864 -> 860
~ -[WATodayHourlyForecastView _setupConstraints] : 2024 -> 2020
~ _ChanceOfRainWithHourlyForecasts : 320 -> 316
~ ___WAUIFormattedTimeString_block_invoke : 416 -> 412
~ ___93+[WeatherImageLoader conditionImageNamed:size:cloudAligned:stroke:strokeAlpha:lighterColors:]_block_invoke : 640 -> 636
~ +[WeatherImageLoader conditionImageNameWithConditionIndex:] : 32 -> 28
~ -[WATodayHeaderView _setupSubviews] : 1820 -> 1800
~ -[WATodayHeaderView _setupConstraints] : 3544 -> 3540
~ -[WFNextHourPrecipitationDescription(WeatherAdditions) initWithDictionary:] : 564 -> 560
~ -[WFNextHourPrecipitationDescription(WeatherAdditions) dictionaryRepresentation] : 628 -> 624
~ -[City localWeatherDidBeginUpdate] : 320 -> 316
~ -[City _notifyDidStartWeatherUpdate] : 368 -> 364
~ -[City cityDidFinishUpdatingWithError:] : 676 -> 672
~ +[City cityContainingLocation:expectedName:fromCities:] : 440 -> 436
~ -[City primaryConditionForRange:] : 532 -> 520
~ -[City locationOfTime:] : 328 -> 324
~ -[City precipitationForecast] : 508 -> 504
~ -[City _generateLocalizableStrings] : 2732 -> 2704
~ -[City updateCityForSevereWeatherEvents:] : 456 -> 452
~ -[WAForecastOperation _determineSunriseAndSunset] : 800 -> 796
~ +[CityPersistenceConversions cityFromDictionary:] : 2832 -> 2828
~ +[CityPersistenceConversions populateCity:withDayForecastDictionaries:] : 660 -> 656
~ +[CityPersistenceConversions populateCity:withHourlyForecastDictionaries:] : 560 -> 556
~ +[CityPersistenceConversions dictionaryRepresentationOfCity:] : 584 -> 580
~ +[WASevereWeatherStringBuilder headlineForEvents:shouldUppercase:] : 580 -> 576
~ +[WASevereWeatherStringBuilder descriptionForEvents:includeLearnMore:useSentenceCase:] : 1616 -> 1612
~ +[WASevereWeatherStringBuilder _hasImportantEvent:] : 296 -> 292
~ -[WeatherPreferences _defaultsAreValid] : 116 -> 128
~ ___36-[WeatherPreferences _defaultCities]_block_invoke_2 : 476 -> 472
~ -[WeatherPreferences setDefaultCities:] : 564 -> 560
~ -[WeatherPreferences loadSavedCities] : 1788 -> 1784
~ -[WeatherPreferences citiesByConsolidatingDuplicates:originalOrder:] : 696 -> 692
~ -[WeatherPreferences citiesByConsolidatingDuplicatesInBucket:] : 440 -> 436
~ -[WeatherPreferences areCitiesDefault:] : 516 -> 512
~ ___68+[WeatherPreferences performUpgradeOfPersistence:fileManager:error:]_block_invoke_3 : 1404 -> 1396
~ ___68+[WeatherPreferences performUpgradeOfPersistence:fileManager:error:]_block_invoke.190 : 408 -> 404
~ -[WAWeatherPlatterViewController _updateViewContent] : 2868 -> 2860
~ -[WALegibilityLabel updateConstraints] : 704 -> 700
~ +[WeatherOpenURLHelper cityFromURL:withContainerViewController:] : 520 -> 516
~ ___33-[WAForecastModelController init]_block_invoke_2 : 456 -> 452
~ ___33-[WAForecastModelController init]_block_invoke_2.13 : 444 -> 440
~ -[WAForecastModelController fetchForecastForCities:completion:] : 632 -> 628
~ ___51-[WAForecastModelController cancelAllFetchRequests]_block_invoke : 588 -> 584
~ -[WFNextHourPrecipitation(WeatherAdditions) initWithDictionary:] : 1080 -> 1068
~ -[WFNextHourPrecipitation(WeatherAdditions) dictionaryRepresentation] : 956 -> 944
~ -[WATodayPadView initWithFrame:] : 740 -> 736
~ -[WATodayPadView updateForChangedSettings:] : 364 -> 360
~ ___120-[WeatherDeviceLookup checkAllDevicesRunningMinimumiOSVersion:macOSVersion:orInactiveForTimeInterval:completionHandler:]_block_invoke : 624 -> 620
~ ___120-[WeatherDeviceLookup checkAllDevicesRunningMinimumiOSVersion:macOSVersion:orInactiveForTimeInterval:completionHandler:]_block_invoke_2 : 392 -> 388
~ +[WAAQIScale scaleFromFoundationScale:] : 768 -> 760
```
