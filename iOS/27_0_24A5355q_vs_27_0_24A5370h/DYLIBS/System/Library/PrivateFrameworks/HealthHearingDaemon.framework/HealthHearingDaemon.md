## HealthHearingDaemon

> `/System/Library/PrivateFrameworks/HealthHearingDaemon.framework/HealthHearingDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20bf4` | `0x20b20` | **`-0xd4`** |
| `__DATA_CONST.__objc_selrefs` | `0x17d0` | `0x17b8` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x4e0` | `0x4e8` | **`+0x8`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  Symbols:   1330
+  Symbols:   1331
Symbols:
+ _OBJC_CLASS_$_HDMetadataManager
Functions:
~ -[HDAudioAnalyticsSettingsPreferences _hasPairedWatchWithNoiseApp] : 348 -> 344
~ +[HDAudioAnalyticsUtilities boundedIntegerForValue:orderedBuckets:sentinel:transformer:] : 368 -> 364
~ +[HDHeadphoneAudioExposureStatisticsEntity insertBuckets:transaction:error:] : 332 -> 328
~ -[HDHeadphoneAudioExposureStatisticsBucket _lock_fetchIncludesPrunableDataWithError:] : 716 -> 704
~ -[HDHeadphoneDoseMetadataStore _updatePreviousSevenDayLocalNotificationFireDateWithSamplesInserted:now:error:] : 988 -> 980
~ -[HDHeadphoneExposureNotificationSyncManager _extractLatestFireDateFromResetDosageEvents:] : 496 -> 492
~ -[HDHeadphoneAudioExposureBucketCollection copyWithEarliestStartDate:resetDoseToZero:error:] : 420 -> 416
~ -[HDHeadphoneAudioExposureBucketCollection _bucketsWithEarliestStartDate:resetDoseToZero:error:] : 404 -> 400
~ -[HDHeadphoneAudioExposureBucketCollection _lock_updateWithSampleBatch:error:] : 432 -> 428
~ -[HDHeadphoneAudioExposureStatisticsCalculator _setupWithAssertion:error:] : 2360 -> 2348
~ ___118-[HDHeadphoneAudioExposureStatisticsCalculator _rebuildWithAssertion:allowInitialQueriesToFail:resetDoseToZero:error:]_block_invoke : 288 -> 284
~ -[HDHeadphoneDoseManager _reportSyncedHeadphoneNotificationSamples:journaled:nowDate:] : 552 -> 548
~ -[HDHearingProfileExtension initWithProfile:] : 744 -> 664
~ -[HDHearingProfileExtension featureAvailabilityExtensionForFeatureIdentifier:] : 240 -> 236
~ +[HDHeadphoneExposureStatisticUpdateResult _resultWithIncludedSeries:samples:] : 316 -> 312
~ sub_2635c3e3c -> sub_264a14da0 : 384 -> 352
~ sub_2635c43cc -> sub_264a15310 : 1260 -> 1268
~ sub_2635c5850 -> sub_264a1679c : 3304 -> 3320
~ sub_2635c6538 -> sub_264a17494 : 2524 -> 2504
~ sub_2635c80c8 -> sub_264a19010 : 280 -> 276
~ sub_2635c8dd4 -> sub_264a19d18 : 400 -> 376
```
