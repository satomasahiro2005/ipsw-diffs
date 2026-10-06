## HeartHealth

> `/System/Library/PrivateFrameworks/HeartHealth.framework/HeartHealth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x266f4` | `0x26f08` | **`+0x814`** |
| `__TEXT.__cstring` | `0x34ee` | `0x361a` | **`+0x12c`** |
| `__AUTH_CONST.__cfstring` | `0x2bc0` | `0x2ce0` | **`+0x120`** |
| `__DATA.__bss` | `0x1c0` | `0x2c0` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0x5da8` | `0x5e68` | **`+0xc0`** |
| `__TEXT.__const` | `0x272` | `0x2f8` | **`+0x86`** |
| `__TEXT.__objc_methlist` | `0x2f7c` | `0x2fec` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ba8` | `0x1be8` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x64` | `0x90` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0x5c8` | `0x5f0` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x370` | `0x390` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0x304` | `0x314` | **`+0x10`** |
| `__DATA.__data` | `0x920` | `0x928` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xc` | `0x14` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xbd8` | `0xbe0` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x23` | `0x29` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x8` | `0xc` | **`+0x4`** |

### Other Changes

```diff

-7027.0.64.0.0
+7027.0.67.2.1

-  Functions: 1211
-  Symbols:   2369
-  CStrings:  496
+  Functions: 1227
+  Symbols:   2386
+  CStrings:  506
Symbols:
+ -[HKHRAFibBurdenSevenDayAnalysisBreadcrumbs initWithAlarmFiredDate:xpcActivityFiredDate:protectedDataOperationRunDate:analysisStartedDate:tachogramsClassifiedDate:analysisEndedDate:analysisRetryLaterRequestedDate:lastAnalysisResultDate:lastAnalysisResultContext:lastNotificationDecision:lastNotificationSentDate:lastAnalysisCompletedDate:runHistory:]
+ -[HKHRAFibBurdenSevenDayAnalysisBreadcrumbs lastAnalysisCompletedDate]
+ -[HKHRAFibBurdenSevenDayAnalysisBreadcrumbs lastNotificationDecision]
+ -[HKHRAFibBurdenSevenDayAnalysisBreadcrumbs lastNotificationSentDate]
+ -[HKHRAFibBurdenSevenDayAnalysisBreadcrumbs runHistory]
+ -[HKHRAFibBurdenSevenDayAnalysisBreadcrumbs setLastAnalysisCompletedDate:]
+ -[HKHRAFibBurdenSevenDayAnalysisBreadcrumbs setLastNotificationDecision:]
+ -[HKHRAFibBurdenSevenDayAnalysisBreadcrumbs setLastNotificationSentDate:]
+ -[HKHRAFibBurdenSevenDayAnalysisBreadcrumbs setRunHistory:]
+ _OBJC_IVAR_$_HKHRAFibBurdenSevenDayAnalysisBreadcrumbs._lastAnalysisCompletedDate
+ _OBJC_IVAR_$_HKHRAFibBurdenSevenDayAnalysisBreadcrumbs._lastNotificationDecision
+ _OBJC_IVAR_$_HKHRAFibBurdenSevenDayAnalysisBreadcrumbs._lastNotificationSentDate
+ _OBJC_IVAR_$_HKHRAFibBurdenSevenDayAnalysisBreadcrumbs._runHistory
+ __appendBreadcrumbTables
+ __dateStringOrNull
+ _swift_getForeignTypeMetadata
+ _symbolic _____ So24HKHeartbeatSeriesFeatureV
CStrings:
+ "\n-------- Run %lu --------\n"
+ "\n======== Previous Runs (oldest first, %lu) ========\n"
+ "\r"
+ "HKHeartbeatSeriesFeature."
+ "Last Analysis Completed Date"
+ "Last Notification Decision"
+ "Last Notification Sent Date"
+ "LastAnalysisCompletedDateKey"
+ "LastNotificationDecisionKey"
+ "LastNotificationSentDateKey"
+ "RunHistoryKey"
- "\t"
```
