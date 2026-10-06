## HeartHealthDaemon

> `/System/Library/PrivateFrameworks/HeartHealthDaemon.framework/HeartHealthDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x64174` | `0x64dd4` | **`+0xc60`** |
| `__TEXT.__cstring` | `0x55d2` | `0x57d2` | **`+0x200`** |
| `__TEXT.__oslogstring` | `0xc175` | `0xc32f` | **`+0x1ba`** |
| `__AUTH_CONST.__cfstring` | `0x4600` | `0x4760` | **`+0x160`** |
| `__DATA_CONST.__objc_selrefs` | `0x3520` | `0x35c0` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x99a0` | `0x9a00` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x4ecc` | `0x4f24` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x1678` | `0x1688` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x62c` | `0x634` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xeb8` | `0xec0` | **`+0x8`** |

### Other Changes

```diff

-7027.0.64.0.0
+7027.0.67.2.1

-  Functions: 2062
-  Symbols:   4038
-  CStrings:  1320
+  Functions: 2077
+  Symbols:   4050
+  CStrings:  1338
Symbols:
+ -[HDHRAFibBurdenNotificationModeDeterminer breadcrumbManager]
+ -[HDHRAFibBurdenNotificationModeDeterminer setBreadcrumbManager:]
+ -[HDHRAFibBurdenSevenDayAnalysisBreadcrumbManager _currentRunSnapshotWithError:]
+ -[HDHRAFibBurdenSevenDayAnalysisBreadcrumbManager _loadRunHistoryWithError:]
+ -[HDHRAFibBurdenSevenDayAnalysisBreadcrumbManager _queue_rollCurrentRunIntoHistoryAndStartNewRunWithAlarmFiredDate:]
+ -[HDHRAFibBurdenSevenDayAnalysisBreadcrumbManager _queue_saveRunHistory:]
+ -[HDHRAFibBurdenSevenDayAnalysisBreadcrumbManager dropNotificationDecisionBreadcrumb:]
+ -[HDHRAFibBurdenSevenDayAnalysisBreadcrumbManager initWithLocalKeyValueDomain:syncedKeyValueDomain:dateGenerator:queue:]
+ _OBJC_CLASS_$_NSKeyedUnarchiver
+ _OBJC_IVAR_$_HDHRAFibBurdenNotificationModeDeterminer._breadcrumbManager
+ _OBJC_IVAR_$_HDHRAFibBurdenSevenDayAnalysisBreadcrumbManager._localKeyValueDomain
+ _OBJC_IVAR_$_HDHRAFibBurdenSevenDayAnalysisBreadcrumbManager._syncedKeyValueDomain
+ __OBJC_$_PROP_LIST_HDHRAFibBurdenNotificationModeDeterminer
+ ___86-[HDHRAFibBurdenSevenDayAnalysisBreadcrumbManager dropNotificationDecisionBreadcrumb:]_block_invoke
- -[HDHRAFibBurdenSevenDayAnalysisBreadcrumbManager initWithKeyValueDomain:dateGenerator:queue:]
- _OBJC_IVAR_$_HDHRAFibBurdenSevenDayAnalysisBreadcrumbManager._keyValueDomain
CStrings:
+ "Posted: no-data notification (forwarded to watch)"
+ "Posted: no-data notification (phone only)"
+ "Posted: value notification (current and previous week)"
+ "Posted: value notification (current week)"
+ "SevenDayAnalysisBreadcrumbNotificationDecision"
+ "SevenDayAnalysisBreadcrumbRunHistory"
+ "Suppressed: after weekday cutoff"
+ "Suppressed: analysis requirements not satisfied"
+ "Suppressed: most recent sample not for previous calendar week"
+ "Suppressed: onboarded within analysis interval"
+ "Suppressed: weekly notifications disabled"
+ "[%{public}@] Error archiving run history: %{public}@"
+ "[%{public}@] Error loading run history to append, starting fresh: %{public}@"
+ "[%{public}@] Error resetting prior run breadcrumbs: %{public}@"
+ "[%{public}@] Error saving run history: %{public}@"
+ "[%{public}@] Error snapshotting run for history: %{public}@"
+ "[%{public}@] Error unarchiving run history, treating as empty: %{public}@"
+ "[%{public}@] Error when saving notification decision: %{public}@"
```
