## DACalDAV

> `/System/Library/PrivateFrameworks/DataAccess.framework/Frameworks/DACalDAV.framework/DACalDAV`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36948` | `0x3677c` | **`-0x1cc`** |

### Other Changes

```diff

-2703.0.0.0.0
+2704.0.0.0.0
Functions:
~ -[MobileCalDAVDAAccount upgradeAccount] : 2160 -> 2168
~ -[MobileCalDAVAccount ingestBackingAccountInfoProperties] : 1376 -> 1372
~ -[MobileCalDAVAccount removeCalendarWithURL:] : 484 -> 480
~ +[MobileCalDAVAccount _defaultAlarmOffsetFromICSString:] : 708 -> 704
~ -[MobileCalDAVAccount _saveModifiedSubscribedCalendarsOnBackingAccount] : 1300 -> 1292
~ -[MobileCalDAVAccount _saveModifiedPrincipalsOnBackingAccount] : 1024 -> 1016
~ -[MobileCalDAVAccount refreshActor:didCompleteWithError:] : 3328 -> 3324
~ -[MobileCalDAVAccount _collectActionsFromMoveDictionary:forDataclass:outShouldSave:] : 1684 -> 1680
~ -[MobileCalDAVAccount updateDelegatesWithUserInfo:] : 2032 -> 2024
~ -[MobileCalDAVAccount task:didFinishWithError:] : 968 -> 964
~ -[MobileCalDAVAccount _reallyCancelSearchQuery:] : 480 -> 476
~ -[MobileCalDAVAccount _reallyCancelAllSearchQueries] : 384 -> 380
~ -[MobileCalDAVPrincipal initWithConfiguration:principalUID:account:] : 3032 -> 3028
~ -[MobileCalDAVPrincipal calendarUserAddresses] : 316 -> 312
~ -[MobileCalDAVPrincipal prepareCalendarsForSyncWithCompletionBlock:] : 1048 -> 1040
~ -[MobileCalDAVPrincipal updateAddedOrModifiedSubscribedCalendars:] : 276 -> 272
~ -[MobileCalDAVPrincipal setCalendarsAreDirty:] : 252 -> 248
~ -[MobileCalDAVPrincipal calendarsAreDirty] : 272 -> 268
~ -[MobileCalDAVPrincipal preferredCalendarEmailAddress] : 436 -> 432
~ -[MobileCalDAVPrincipal preferredCalendarPhoneNumber] : 436 -> 432
~ -[MobileCalDAVPrincipal hasCalendarUserAddress:] : 404 -> 400
~ -[MobileCalDAVPrincipal calendarUserAddressIsEquivalentToURL:] : 344 -> 340
~ -[MobileCalDAVCalendar ownerEmailAddress] : 432 -> 428
~ -[MobileCalDAVCalendar ownerPhoneNumber] : 432 -> 428
~ -[MobileCalDAVCalendar calendarUserAddresses] : 316 -> 312
~ -[MobileCalDAVCalendar setPreferredCalendarUserAddresses:] : 436 -> 432
~ -[MobileCalDAVCalendar hasCalendarUserAddressEquivalentToURL:] : 344 -> 340
~ -[MobileCalDAVCalendar setSharees:] : 1288 -> 1280
~ -[MobileCalDAVCalendar etagsForItemURLs:] : 800 -> 796
~ -[MobileCalDAVCalendar setURL:forResourceWithUUID:] : 744 -> 740
~ -[MobileCalDAVCalendar removeInvitationsForItemWithUniqueIdentifier:] : 732 -> 720
~ -[MobileCalDAVCalendar updateResourcesFromServer:] : 2588 -> 2576
~ -[MobileCalDAVCalendar correctLocationPredictionStateForRecurrenceSets:calDB:] : 576 -> 568
~ -[MobileCalDAVCalendar deleteResourcesAtURLs:] : 352 -> 348
~ +[MobileCalDAVCalendar gatherCalendarChangesInPrincipal:calendars:adds:modifies:deletes:changeTracker:] : 2120 -> 2116
~ -[MobileCalDAVCalendar _addCalendarItemWithRowID:toArrayIfNeeded:withChangeRowid:changeType:] : 1836 -> 1832
~ -[MobileCalDAVCalendar _clearChangesAtIndices:forType:] : 644 -> 640
~ -[MobileCalDAVCalendar _saveChangesAtIndices:forType:] : 448 -> 444
~ -[MobileCalDAVCalendar _actionsForJunkItemsInModifiedItems:alreadySentItems:] : 756 -> 752
~ -[MobileCalDAVCalendar _recurrenceSplitActionsForItems:alreadySentItems:] : 936 -> 932
~ -[MobileCalDAVCalendar _createActionsForItems:withAction:alreadySentItems:createServerIDs:shouldSave:] : 1212 -> 1224
~ -[MobileCalDAVCalendar _collectShareeActions] : 2420 -> 2412
~ -[MobileCalDAVCalendar createSyncActions] : 3004 -> 2992
~ -[MobileCalDAVCalendar generateICSForActions] : 276 -> 272
~ -[MobileCalDAVCalendar prepareMergeSyncActionsWithCompletionBlock:] : 1996 -> 1984
~ -[MobileCalDAVCalendar syncDidFinishWithError:] : 684 -> 680
~ -[MobileCalDAVAccountRefreshActor _teardownAllOutstandingOperations] : 496 -> 488
~ ___74-[MobileCalDAVAccountRefreshActor _propFindForNewEtagFollowingMoveOfItem:]_block_invoke : 996 -> 992
~ -[MobileCalDAVAccountRefreshActor calendarRefreshForPrincipal:completedWithNewCTags:newSyncTokens:calendarHomeSyncToken:updatedCalendars:error:] : 1972 -> 1968
~ -[MobileCalDAVAccountRefreshActor _cleanUpDuplicateCalendars] : 728 -> 724
~ -[MobileCalDAVAccountRefreshActor _checkForNewOrMovedItemsDeletedSinceSyncStartedInCalendars:database:moves:] : 984 -> 976
~ -[MobileCalDAVAccountRefreshActor _refreshSpecialCalendars] : 540 -> 536
~ -[MobileCalDAVAccountRefreshActor _refreshRegularCalendars] : 412 -> 408
~ -[MobileCalDAVAccountRefreshActor _prepareAttachmentsForUpload] : 2476 -> 2464
~ -[MobileCalDAVAccountRefreshActor _uploadAttachments:] : 356 -> 352
~ -[MobileCalDAVAccountRefreshActor _uploadAttachments:forOwnerURL:syncKey:scheduleTag:] : 1896 -> 1892
~ -[MobileCalDAVAccountRefreshActor _handleAttachmentUploadsComplete:attachments:] : 1312 -> 1308
~ -[MobileCalDAVAccountRefreshActor _cleanUpOrphanedPreferredUserAddressesPerCalendar] : 500 -> 496
~ -[MobileCalDAVAccountRefreshActor _guidsOfExistingCalendars] : 572 -> 568
~ -[MobileCalDAVAccountRefreshActor _updateDefaultCalendarIfNeededWithDatabase:] : 636 -> 632
~ -[DACalDAViCalItem _removeDetachedEventsWithUniqueIdentifiers:fromEvent:withContainer:inMobileCalendar:] : 536 -> 532
~ -[DACalDAViCalItem _addOrModifyEvent:inICSCalendar:withContainer:shouldMergeProperties:outMergeDidChooseLocalProperties:inMobileCalendar:] : 2348 -> 2344
~ +[DACalDAViCalItem _checkOccurrencesForEvent:fromDate:toDate:] : 1148 -> 1144
~ -[DACalDAViCalItem saveToContainer:shouldMergeProperties:outMergeDidChooseLocalProperties:account:mobileCalendar:outRecurrenceSets:] : 3336 -> 3260
~ -[DACalDAViCalItem recurrenceSetsForICSCalendar:] : 632 -> 628
~ -[DACalDAViCalItem _fixUpCalendarForServer:] : 856 -> 848
~ -[MobileCalDAVInboxCalendar etagsForItemURLs:] : 568 -> 564
~ -[MobileCalDAVInboxCalendar updateResourcesFromServer:] : 1712 -> 1696
~ -[MobileCalDAVInboxCalendar deleteResourcesAtURLs:] : 344 -> 340
~ -[CalDAVPrincipalResult initWithResponse:] : 1364 -> 1356
~ -[CalDAVPrincipalResult preferredCUAddress] : 472 -> 468
~ -[CalDAVPrincipalResult emailAddress] : 396 -> 392
~ -[MobileCalDAVNotificationCalendar etagsForItemURLs:] : 728 -> 724
~ -[MobileCalDAVNotificationCalendar updateResourcesFromServer:] : 1392 -> 1376
~ -[MobileCalDAVNotificationCalendar prepareSyncActionsWithCompletionBlock:] : 1192 -> 1188
~ -[CalDAVAccountDelegatesRefreshOperation taskGroup:didFinishWithError:] : 868 -> 860
```
