## RespiratoryHealthDaemon

> `/System/Library/PrivateFrameworks/RespiratoryHealthDaemon.framework/RespiratoryHealthDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80ec` | `0x810c` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x23c` | `0x220` | **`-0x1c`** |
| `__DATA_CONST.__got` | `0x2b8` | `0x2c0` | **`+0x8`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  Symbols:   566
+  Symbols:   568
Symbols:
+ _OBJC_CLASS_$_HDMetadataManager
+ _objc_opt_respondsToSelector
Functions:
~ -[HDRPOxygenSaturationAnalyzer initWithProfile:oxygenSaturationFeatureStatusProvider:oxygenSaturationCompanionAnalysisFeatureStatusProvider:analyticsEventSubmissionManager:unitTestDelegate:] : 392 -> 432
~ -[HDRPOxygenSaturationAnalyzer _analyzeUnprocessedSamples] : 1188 -> 1148
~ -[HDRPOxygenSaturationAnalyzer _sendAnalyticEventsForAnalysisSummaryIfNeeded:] : 772 -> 764
~ ___58-[HDRPOxygenSaturationAnalyzer _analyzeUnprocessedSamples]_block_invoke : 904 -> 868
~ -[HDRPOxygenSaturationAnalyzer _analyzeSample:transaction:error:] : 648 -> 736
~ -[HDRPDailyAnalyticsReport _numberOfWeeksSinceOnboardedAndReturnError:] : 228 -> 256
~ -[HDRPDailyAnalyticsReport _hasCompatiblePairedAppleWatch] : 344 -> 340
~ -[HDRPDailyAnalyticsReport _queryForBackgroundOxygenSaturationSamplesInPreviousDays:error:] : 476 -> 448
~ -[HDRPDailyAnalyticsReport _numberOfSamplesByTruncatedOxygenSaturationValueFromSamples:keyPrefix:] : 496 -> 492
~ -[HDRespiratoryProfileExtension featureAvailabilityExtensionForFeatureIdentifier:] : 144 -> 140
```
