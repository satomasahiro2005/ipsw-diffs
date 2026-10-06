## CalendarNotification

> `/System/Library/PrivateFrameworks/CalendarNotification.framework/CalendarNotification`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53268` | `0x53140` | **`-0x128`** |
| `__DATA.__data` | `0x1930` | `0x1938` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x40` | `0x38` | **`-0x8`** |

### Other Changes

```diff

-1545.0.0.0.0
+1547.0.0.0.0
Symbols:
+ _symbolic _____yS2SG 10AppIntents24SyncableEntityIdentifierV
- _symbolic _____yS2SG 10AppIntents25_SyncableEntityIdentifierV
Functions:
~ -[CALNSchedulingSnoozeUpdateTimer _dequeueEventsDueBy:] : 516 -> 508
~ -[CALNSchedulingSnoozeUpdateTimer _scheduleTimer] : 916 -> 912
~ +[CALNNotificationRecordsDiffer diffOldRecords:withNewRecords:filteredBySourceClientIDs:] : 1064 -> 1056
~ +[CALNNotificationRecordsDiffApplier applyDiff:toNotificationManager:] : 916 -> 904
~ -[CALNSharedCalendarInvitationResponseNotificationSource refreshNotifications:] : 744 -> 740
~ -[CALNEventInvitationNotificationSource refreshNotifications:] : 744 -> 740
~ -[CALNTriggeredEventNotificationEKDataSource _alertsFired:] : 632 -> 628
~ -[CALNTriggeredEventNotificationEKDataSource _filterAlerts:] : 832 -> 824
~ +[CALNTriggeredEventNotificationEKDataSource _alarmForEvent:withAlarmID:] : 368 -> 364
~ -[CALNSharedCalendarInvitationNotificationSource refreshNotifications:] : 744 -> 740
~ -[CALNNotificationSourceRefresher _refreshNotifications:] : 652 -> 648
~ -[CALNNotificationSourceRefresher _withdrawExpiredNotificationsForSource:] : 528 -> 524
~ -[CALNNotificationServer _notificationSourceMapWithNotificationSources:] : 344 -> 340
~ -[CALNEventCanceledNotificationEKDataSource fetchEventCanceledNotifications] : 504 -> 500
~ -[CALNEventCanceledNotificationEKDataSource fetchEventCanceledNotificationSourceClientIdentifiers:] : 596 -> 592
~ -[CALNPersistentNotificationStorage _loadNotificationsWithError:] : 476 -> 472
~ -[CALNEventCanceledNotificationSource refreshNotifications:] : 744 -> 740
~ ___58-[CALNInMemoryNotificationStorage addNotificationRecords:]_block_invoke : 248 -> 244
~ -[CALNInMemoryNotificationStorage _removeNotificationRecordsPassingTest:] : 572 -> 568
~ -[CALNNotificationIconUpdater _updateAllIconIdentifiersInStorage:] : 696 -> 692
~ -[CALNInboxNotificationMonitor eventNotificationCount] : 692 -> 688
~ -[CALNSuggestedEventNotificationSource contentForNotificationWithSourceClientIdentifier:] : 1680 -> 1676
~ -[CALNSuggestedEventNotificationSource refreshNotifications:] : 888 -> 884
~ -[CALNSuggestedEventNotificationSource _sourceClientIdentifiersForObjectIDs:] : 396 -> 392
~ +[EKTravelEngine travelEligibleEvents:fromStartDate:untilEndDate:] : 548 -> 544
~ -[EKTravelEngine _unregisterAllAgendaEntries] : 324 -> 320
~ -[CALNSuggestedEventNotificationEKDataSource fetchSuggestedEventNotifications] : 468 -> 464
~ -[CALNSuggestedEventNotificationEKDataSource fetchSuggestedEventNotificationObjectIDs] : 588 -> 584
~ -[CALNSuggestedEventNotificationEKDataSource fetchSuggestedEventNotificationsWithSourceClientIdentifier:] : 812 -> 804
~ -[CALNSuggestedEventNotificationEKDataSource clearSuggestedEventNotificationWithSourceClientIdentifier:] : 360 -> 356
~ ___50-[CALNTriggeredEventNotificationSource categories]_block_invoke_2 : 528 -> 524
~ -[CALNTriggeredEventNotificationSource _clearTravelAdvisoryHypotheses] : 536 -> 532
~ -[CALNTriggeredEventNotificationSource _updateSnoozeOptionsForEvents:] : 376 -> 372
~ ___81-[CALNTriggeredEventNotificationSource updateSnoozeOptionsForPostedNotifications]_block_invoke : 1456 -> 1444
~ -[CALNTriggeredEventNotificationSource _refreshNotificationRecordsWithObjectIDs:] : 424 -> 420
~ ___57-[CALNTriggeredEventNotificationSource migrateToStorage:]_block_invoke : 696 -> 692
~ ___60-[_EKAlarmEngine _storeAlarms:nextScheduleLimit:eventStore:]_block_invoke : 1060 -> 1056
~ -[_EKAlarmEngine _populateAlarmTable:] : 1568 -> 1564
~ -[CALNEventInvitationNotificationEKDataSource fetchEventInvitationNotifications] : 504 -> 500
~ -[CALNEventInvitationNotificationEKDataSource fetchEventInvitationNotificationSourceClientIdentifiers:] : 616 -> 612
~ +[CALNEventInvitationNotificationDataSourceUtils expirationDateForEventInvitation:] : 464 -> 460
~ -[CALNNotificationServerModule activate] : 268 -> 264
~ -[CALNNotificationServerModule deactivate] : 240 -> 236
~ -[CALNNotificationServerModule receivedNotificationNamed:] : 496 -> 492
~ -[CALNNotificationServerModule didRegisterForAlarms] : 240 -> 236
~ -[CALNNotificationServerModule receivedAlarmNamed:] : 292 -> 288
~ -[CALNNotificationServerModule protectedDataDidBecomeAvailable] : 320 -> 316
~ -[CALNNotificationServerModule _reloadNotificationRecords:forNotificationServer:] : 804 -> 788
~ ___HandleDarwinNotification_block_invoke : 276 -> 272
~ -[CALNCalendarResourceChangedNotificationSource refreshNotifications:] : 744 -> 740
~ +[CALNSnoozeCategory snoozeCategoryForEventWithStartDate:endDate:now:isAllDay:] : 472 -> 468
~ -[EKSideTableContext deleteAllAlarms] : 252 -> 248
~ -[CALNEventInvitationResponseNotificationEKDataSource fetchEventInvitationResponseNotifications] : 504 -> 500
~ -[CALNEventInvitationResponseNotificationEKDataSource fetchEventInvitationResponseNotificationSourceClientIdentifiers:] : 600 -> 596
~ -[CALNEventInvitationResponseNotificationEKDataSource acceptEventInvitationResponseWithSourceClientIdentifier:] : 820 -> 816
~ -[CALNEventInvitationResponseNotificationEKDataSource declineEventInvitationResponseWithSourceClientIdentifier:] : 800 -> 796
~ -[CALNSharedCalendarInvitationNotificationEKDataSource fetchSharedCalendarInvitationNotifications] : 504 -> 500
~ -[CALNSharedCalendarInvitationNotificationEKDataSource fetchSharedCalendarInvitationNotificationSourceClientIdentifiers:] : 584 -> 580
~ -[CALNSharedCalendarInvitationResponseNotificationEKDataSource fetchSharedCalendarInvitationResponseNotifications] : 504 -> 500
~ -[CALNSharedCalendarInvitationResponseNotificationEKDataSource fetchSharedCalendarInvitationResponseNotificationSourceClientIdentifiers:] : 652 -> 648
~ -[CALNCalendarResourceChangedNotificationEKDataSource fetchCalendarResourceChangedNotifications] : 504 -> 500
~ -[CALNCalendarResourceChangedNotificationEKDataSource fetchCalendarResourceChangedNotificationSourceClientIdentifiers:] : 652 -> 648
~ -[CALNEventInvitationResponseNotificationSource refreshNotifications:] : 744 -> 740
```
