## DACalDAV

> `/System/Library/PrivateFrameworks/CDDataAccess.framework/Frameworks/DACalDAV.framework/DACalDAV`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ab74` | `0x2aa3c` | **`-0x138`** |

### Other Changes

```diff

-4034.15.0.0.0
+4037.1.0.0.0
Functions:
~ -[MobileCalDAVAccount ingestBackingAccountInfoProperties] : 1264 -> 1260
~ -[MobileCalDAVAccount removeCalendarWithURL:] : 484 -> 480
~ -[MobileCalDAVAccount calendars] : 1304 -> 1300
~ -[MobileCalDAVAccount _updateCalendarStoreNoDBOpen:] : 440 -> 432
~ -[MobileCalDAVAccount _saveModifiedPrincipalsOnBackingAccount] : 1020 -> 1012
~ -[MobileCalDAVAccount refreshActor:didCompleteWithError:] : 2832 -> 2828
~ -[MobileCalDAVAccount updateDelegates] : 1448 -> 1432
~ -[MobileCalDAVAccount task:didFinishWithError:] : 936 -> 932
~ -[MobileCalDAVAccount _reallyCancelSearchQuery:] : 480 -> 476
~ -[MobileCalDAVAccount _reallyCancelAllSearchQueries] : 384 -> 380
~ -[MobileCalDAVPrincipal initWithConfiguration:principalUID:account:] : 2940 -> 2936
~ -[MobileCalDAVPrincipal calendarUserAddresses] : 316 -> 312
~ -[MobileCalDAVPrincipal prepareCalendarsForSyncWithCompletionBlock:] : 2432 -> 2416
~ -[MobileCalDAVPrincipal setCalendarsAreDirty:] : 252 -> 248
~ -[MobileCalDAVPrincipal calendarsAreDirty] : 272 -> 268
~ -[MobileCalDAVPrincipal preferredCalendarEmailAddress] : 436 -> 432
~ -[MobileCalDAVPrincipal preferredCalendarPhoneNumber] : 436 -> 432
~ -[MobileCalDAVPrincipal hasCalendarUserAddress:] : 404 -> 400
~ -[MobileCalDAVPrincipal calendarUserAddressIsEquivalentToURL:] : 344 -> 340
~ -[MobileCalDAVCalendar ownerEmailAddress] : 432 -> 428
~ -[MobileCalDAVCalendar ownerPhoneNumber] : 432 -> 428
~ -[MobileCalDAVCalendar calendarUserAddresses] : 316 -> 312
~ -[MobileCalDAVCalendar hasCalendarUserAddressEquivalentToURL:] : 344 -> 340
~ -[MobileCalDAVCalendar setSharees:] : 1988 -> 1976
~ -[MobileCalDAVCalendar sharees] : 416 -> 412
~ -[MobileCalDAVCalendar allItemURLs] : 928 -> 924
~ -[MobileCalDAVCalendar etagsForItemURLs:] : 1144 -> 1140
~ -[MobileCalDAVCalendar deleteResourcesAtURLs:] : 248 -> 244
~ +[MobileCalDAVCalendar rem_addedCalendarsWithChangeTrackingHelper:inPrincipal:] : 968 -> 956
~ +[MobileCalDAVCalendar rem_modifiedCalendarsWithChangeTrackingHelper:inPrincipal:] : 968 -> 956
~ -[MobileCalDAVCalendar copyAllItemsWithBatchHandler:] : 944 -> 940
~ -[MobileCalDAVCalendar copyAddedItemsWithBatchHandler:] : 664 -> 652
~ -[MobileCalDAVCalendar copyModifiedItemsWithBatchHandler:] : 664 -> 652
~ -[MobileCalDAVCalendar copyDeletedItems] : 632 -> 628
~ -[MobileCalDAVCalendar _addChangedReminder:toArrayIfNeeded:] : 968 -> 964
~ -[MobileCalDAVCalendar _createActionsForItems:withAction:backingReminders:alreadySentItems:createServerIDs:shouldSave:] : 2816 -> 2812
~ -[MobileCalDAVCalendar _collectShareeActions] : 2912 -> 2896
~ -[MobileCalDAVCalendar prepareSyncActionsWithCompletionBlock:] : 1540 -> 1536
~ ___109-[MobileCalDAVCalendar _prepareForcedRefreshSyncActionsForTruncatedHistoryWithTrackingState:completionBlock:]_block_invoke : 1544 -> 1548
~ ___67-[MobileCalDAVCalendar prepareMergeSyncActionsWithCompletionBlock:]_block_invoke : 2040 -> 2028
~ -[MobileCalDAVAccountRefreshActor _teardownAllOutstandingOperations] : 496 -> 488
~ -[MobileCalDAVAccountRefreshActor calendarRefreshForPrincipal:completedWithNewCTags:newSyncTokens:calendarHomeSyncToken:updatedCalendars:error:] : 2148 -> 2144
~ -[MobileCalDAVAccountRefreshActor _refreshSpecialCalendars] : 540 -> 536
~ -[MobileCalDAVAccountRefreshActor _refreshRegularCalendars] : 412 -> 408
~ -[MobileCalDAVNotificationCalendar etagsForItemURLs:] : 880 -> 876
~ -[MobileCalDAVNotificationCalendar prepareSyncActionsWithCompletionBlock:] : 1080 -> 1072
~ -[MobileCalDAVNotificationCalendar _changedAttributesFromCalendarChanges:] : 1000 -> 996
~ -[MobileCalDAVNotificationCalendar _handleResourceChanged:withResource:uid:] : 1728 -> 1708
~ _rem_reminderFromICSTodoWithOptions : 3820 -> 3844
~ -[DACalDAViCalItem saveWithLocalObject:toContainer:shouldMergeProperties:outMergeDidChooseLocalProperties:account:calendar:batchSaveRequest:] : 1708 -> 1704
~ -[DACalDAViCalItem _fixUpCalendarForServer:] : 856 -> 848
~ -[CalDAVPrincipalResult initWithResponse:] : 1364 -> 1356
~ -[CalDAVPrincipalResult preferredCUAddress] : 472 -> 468
~ -[CalDAVPrincipalResult emailAddress] : 396 -> 392
~ -[CalDAVAccountDelegatesRefreshOperation taskGroup:didFinishWithError:] : 912 -> 904
```
