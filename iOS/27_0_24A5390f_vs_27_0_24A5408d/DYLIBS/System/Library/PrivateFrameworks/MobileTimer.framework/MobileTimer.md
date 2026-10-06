## MobileTimer

> `/System/Library/PrivateFrameworks/MobileTimer.framework/MobileTimer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1360e0` | `0x137d28` | **`+0x1c48`** |
| `__TEXT.__oslogstring` | `0x12d93` | `0x13213` | **`+0x480`** |
| `__TEXT.__objc_methlist` | `0xea84` | `0xeb44` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x6830` | `0x68b8` | **`+0x88`** |
| `__DATA_CONST.__const` | `0x4988` | `0x4a00` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x59a8` | `0x5a10` | **`+0x68`** |
| `__AUTH_CONST.__const` | `0x5c68` | `0x5cc8` | **`+0x60`** |
| `__TEXT.__cstring` | `0x99d2` | `0x99f2` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1228` | `0x1248` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x4ad` | `0x4cd` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x5cc` | `0x5d8` | **`+0xc`** |
| `__AUTH_CONST.__objc_const` | `0x2c510` | `0x2c518` | **`+0x8`** |

### Other Changes

```diff

-2330.0.0.0.0
+2333.0.0.0.0

-  Functions: 7894
-  Symbols:   9960
-  CStrings:  2853
+  Functions: 7930
+  Symbols:   9997
+  CStrings:  2872
Symbols:
+ -[MTAgent holidayAwareAlarmsEnabled]
+ -[MTAlarmStorage upcomingDateForHolidayAwareAlarm:]
+ -[MTAppEntityDonor donateHolidayAlarmsToIndex:]
+ -[MTAppEntityDonor partitionAlarms:completion:]
+ -[MTCalendarDataStorage upcomingDateForHolidayAlarm:]
+ -[MTTimerManager(Testing) test_currentTimer]
+ -[MTTimerManager(Testing) test_nextTimer]
+ -[MTTimerManager(Testing) test_pauseCurrentTimer]
+ -[MTTimerManager(Testing) test_resumeCurrentTimer]
+ -[MTTimerManager(Testing) test_startCurrentTimerWithDuration:]
+ -[MTTimerManager(Testing) test_stopCurrentTimer]
+ -[MTTimerManager(Testing) test_timerSyncWithIdentifier:]
+ -[MTTimerManager(Testing) test_timerWithIdentifier:]
+ -[MTTimerManager(Testing) test_timers]
+ -[MTTimerManager(Testing) test_updateCurrentTimerWithState:]
+ -[MTTimerServer test_getTimersWithCompletion:]
+ -[MTTimerStorage coreDataReady]
+ -[MTTimerStorage test_getTimersWithCompletion:]
+ GCC_except_table39
+ GCC_except_table75
+ __OBJC_$_INSTANCE_METHODS_MTTimerManager(IntentsSupport|Testing|MTTimerManagerProviding)
+ __OBJC_CLASS_PROTOCOLS_$_MTTimerManager(IntentsSupport|Testing|MTTimerManagerProviding)
+ ___38-[MTTimerManager(Testing) test_timers]_block_invoke
+ ___38-[MTTimerManager(Testing) test_timers]_block_invoke_2
+ ___38-[MTTimerManager(Testing) test_timers]_block_invoke_3
+ ___40-[MTAppEntityDonor source:didAddAlarms:]_block_invoke
+ ___41-[MTTimerManager(Testing) test_nextTimer]_block_invoke
+ ___41-[MTTimerManager(Testing) test_nextTimer]_block_invoke_2
+ ___41-[MTTimerManager(Testing) test_nextTimer]_block_invoke_3
+ ___43-[MTAppEntityDonor source:didUpdateAlarms:]_block_invoke
+ ___44-[MTTimerManager(Testing) test_currentTimer]_block_invoke
+ ___47-[MTAppEntityDonor partitionAlarms:completion:]_block_invoke
+ ___47-[MTTimerStorage test_getTimersWithCompletion:]_block_invoke
+ ___47-[MTTimerStorage test_getTimersWithCompletion:]_block_invoke_2
+ ___47-[MTTimerStorage test_getTimersWithCompletion:]_block_invoke_3
+ ___52-[MTTimerManager(Testing) test_timerWithIdentifier:]_block_invoke
+ ___52-[MTTimerManager(Testing) test_timerWithIdentifier:]_block_invoke_2
+ ___54-[MTAlarmIntentDonor source:didFireAlarm:triggerType:]_block_invoke
+ ___56-[MTTimerManager(Testing) test_timerSyncWithIdentifier:]_block_invoke
+ ___56-[MTTimerManager(Testing) test_timerSyncWithIdentifier:]_block_invoke_2
+ ___60-[MTTimerManager(Testing) test_updateCurrentTimerWithState:]_block_invoke
+ ___62-[MTTimerManager(Testing) test_startCurrentTimerWithDuration:]_block_invoke
+ ___block_descriptor_40_e8_32s_e25_v16?0"<MTTimerServer>"8ls32l8
+ ___block_descriptor_40_e8_32s_e29_v24?0"NSArray"8"NSArray"16ls32l8
+ ___block_descriptor_56_e8_32s40s48r_e29_v24?0"NSArray"8"NSError"16lr48l8s32l8s40l8
- -[MTTimerStorage _createDefaultTimerIfNeededWithCompletion:]
- -[MTTimerStorage shouldUseCoreData]
- GCC_except_table42
- __OBJC_$_INSTANCE_METHODS_MTTimerManager(IntentsSupport|MTTimerManagerProviding)
- __OBJC_CLASS_PROTOCOLS_$_MTTimerManager(IntentsSupport|MTTimerManagerProviding)
- ___42-[MTTimerStorage getTimersWithCompletion:]_block_invoke_2
- ___60-[MTTimerStorage _createDefaultTimerIfNeededWithCompletion:]_block_invoke
- ___60-[MTTimerStorage _createDefaultTimerIfNeededWithCompletion:]_block_invoke_2
CStrings:
+ "%{public}@ Holiday alarm fired - re-donating intent: %{public}@"
+ "%{public}@ associatesEntities=NO, dropping didAddAlarms"
+ "%{public}@ associatesEntities=NO, dropping didAddTimers"
+ "%{public}@ associatesEntities=NO, dropping didDismissAlarm"
+ "%{public}@ associatesEntities=NO, dropping didDismissTimer"
+ "%{public}@ associatesEntities=NO, dropping didFireAlarm"
+ "%{public}@ associatesEntities=NO, dropping didFireTimer"
+ "%{public}@ associatesEntities=NO, dropping didRemoveAlarms"
+ "%{public}@ associatesEntities=NO, dropping didRemoveTimers"
+ "%{public}@ associatesEntities=NO, dropping didUpdateAlarms"
+ "%{public}@ associatesEntities=NO, dropping didUpdateTimers"
+ "%{public}@ associatesEntities=NO, dropping handleSystemReady"
+ "%{public}@ associatesEntities=NO, dropping reindexAllItems"
+ "%{public}@ associatesEntities=NO, dropping updateStopwatch"
+ "%{public}@ core data not ready, returning error to client: %{public}@"
+ "Earliest trigger date %{public}@ is past the last makeup day %{public}@, using current date instead"
+ "Error re-donating holiday alarm on fire: %{public}@"
+ "not initializing calendar data storage; holiday-aware alarms unsupported or disabled on this platform"
+ "repeatSchedule == %lld OR repeatSchedule == %lld"
+ "v24@?0@\"NSArray\"8@\"NSArray\"16"
- "enabled == YES AND (repeatSchedule == %lld OR repeatSchedule == %lld)"
```
