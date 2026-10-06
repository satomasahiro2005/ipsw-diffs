## HealthMedications

> `/System/Library/PrivateFrameworks/HealthMedications.framework/HealthMedications`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1eeac` | `0x1ee7c` | **`-0x30`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2
Functions:
~ +[HKMedicationLoggingAnalytics _extractCommonScheduleTypeForMedicationSchedules:] : 280 -> 276
~ -[HKConcept(Medications) _meds_isA:] : 340 -> 336
~ +[HKMedicationScheduleBaseIncompatibilityResolver computeIncompatibleSchedulesFromSchedules:devices:] : 572 -> 568
~ +[HKMedicationSchedule _validateDailyScheduleTimeIntervals:] : 332 -> 328
~ +[HKMedicationSchedule _validateEveryXDaysScheduleTimeIntervals:] : 1052 -> 1048
~ +[HKMedicationSchedule _validateDaysOfWeekScheduleTimeIntervals:scheduleType:] : 712 -> 708
~ +[HKMedicationSchedule _validateActiveXWeeksPauseYWeeksTimeIntervals:scheduleType:] : 1532 -> 1528
~ +[HKMedicationSchedule _validateActiveXPauseYScheduleTimeIntervals:scheduleType:] : 828 -> 824
~ -[HKMedicationSearchResult(Traversal) _visit:ofRoot:withMaxDepth:handler:] : 592 -> 588
~ -[HKMedicationUserDomainConcept _computedPropertyLock_generateListOfLocalizedNamesWithPropertyType:] : 516 -> 512
~ -[HKMedicationSchedule _timeIntervalsString] : 396 -> 392
~ -[HKMedicationScheduleItem _dosesDescription] : 400 -> 396
```
