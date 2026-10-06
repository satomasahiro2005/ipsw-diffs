## SchoolTime

> `/System/Library/PrivateFrameworks/SchoolTime.framework/SchoolTime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29a54` | `0x299e8` | **`-0x6c`** |

### Other Changes

```text
Functions:
~ -[SCLSettingsSyncErrorHandler behaviorForError:history:] : 440 -> 436
~ -[SCLPBScheduleSettings dictionaryRepresentation] : 548 -> 544
~ -[SCLPBScheduleSettings writeTo:] : 360 -> 356
~ -[SCLPBScheduleSettings copyWithZone:] : 416 -> 412
~ -[SCLPBScheduleSettings mergeFrom:] : 380 -> 376
~ -[SCLScheduleFormatter stringFromSchedule:] : 916 -> 912
~ -[SCLScheduleFormatter stringForWeekdaysInItem:] : 776 -> 772
~ _SCLScheduleSettingsFromSCLPBScheduleSettings : 412 -> 408
~ _SCLPBScheduleSettingsFromSCLScheduleSettings : 404 -> 400
~ -[SCLTransportService service:account:identifier:didSendWithSuccess:error:context:] : 536 -> 532
~ -[SCLSchoolModeServer schedulingEngine:didUpdateState:fromState:nextEvaluationDate:] : 400 -> 396
~ -[SCLSchedule scheduledDays] : 264 -> 260
~ -[SCLSchedule(Convenience) timeIntervalsForDay:] : 324 -> 320
~ _SCLIDSDeviceForPDRDevice : 364 -> 360
~ -[SCLSchoolModeCoordinator _updateClientsWithSchedule:notify:] : 344 -> 340
~ -[SCLSchoolModeCoordinator _noteHistoryDidUpdate] : 288 -> 284
~ -[SCLSchoolModeCoordinator server:didUpdateState:fromState:] : 1572 -> 1568
~ -[SCLRecurrenceSchedule(SCLRecurrenceScheduleCreation) initWithTimeIntervals:repeatSchedule:] : 412 -> 408
~ ___53-[SCLUnlockHistoryPersistentStore recentHistoryItems]_block_invoke : 708 -> 704
~ -[SCLScheduleAttributes _prepareWithRecurrences:] : 1032 -> 1028
~ -[SCLSuppressSchoolModeAssertionManager performObserverBlock:] : 332 -> 328
~ -[SCLSchoolModeManager loadPairedDevices] : 340 -> 336
~ ___57-[SCLSchoolModeManager handleDeviceUnpairedNotification:]_block_invoke : 1308 -> 1300
~ -[SCLSchoolModeManager removeCoordinator:] : 680 -> 676
~ -[SCLSchoolModeManager _updateActivityRegistration] : 668 -> 664
~ ___47-[SCLSchoolModeManager _handleActivityStarted:]_block_invoke : 392 -> 388
```
