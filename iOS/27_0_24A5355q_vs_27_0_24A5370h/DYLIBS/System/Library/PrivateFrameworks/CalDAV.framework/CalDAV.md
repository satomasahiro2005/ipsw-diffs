## CalDAV

> `/System/Library/PrivateFrameworks/CalDAV.framework/CalDAV`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37784` | `0x37658` | **`-0x12c`** |

### Other Changes

```text
Functions:
~ -[CalDAVMkcalendarWithFallbackTaskGroup _mkcalendarAfterFailureCount:] : 740 -> 736
~ -[CalDAVCalendarInfoTaskGroup _copyContainerParserMappings] : 572 -> 568
~ -[CalDAVCalendarInfoTaskGroup containerForURL:] : 700 -> 728
~ -[CalDAVPostCalendarItemRecurrenceSplitTask _updateBothResponseItems] : 440 -> 436
~ -[CalDAVCompItem parserFoundAttributes:] : 332 -> 328
~ -[CalDAVSupportedCalendarComponentSet compNames] : 360 -> 356
~ -[CalDAVGetAccountPropertiesTaskGroup _setPropertiesFromParsedResponses:] : 1928 -> 1924
~ -[CalDAVGetAccountPropertiesTaskGroup userAddresses] : 332 -> 328
~ -[CalDAVMkcalendarTask requestBody] : 616 -> 612
~ +[CalDAVCalendarUserAddressItemTranslator userAddressesForAddressSetItem:] : 352 -> 348
~ +[CalDAVCalendarUserAddressItemTranslator _preferredAttributeForItem:] : 372 -> 368
~ +[CalDAVFreeBusyLookupTask _freeBusyDocumentWithOrganizer:attendees:start:end:maskedUID:extendedFreeBusy:prodID:] : 912 -> 908
~ -[CalDAVReportJunkTaskGroup startTaskGroup] : 920 -> 916
~ -[CalDAVUpdateFreeBusySetTaskGroup _startPropPatchWithURLs:] : 596 -> 592
~ -[CalDAVCalendarInfoSyncTaskGroup copyContainerParserMappings] : 572 -> 568
~ -[CalDAVAccountPropertyRefreshOperation propFindTask:parsedResponses:error:] : 796 -> 792
~ -[NSDictionary(CALExtensions) mutableCopyWithElementsCopy] : 352 -> 348
~ -[NSArray(CALExtensions) allObjectsWithClass:] : 316 -> 312
~ -[NSSet(CALExtensions) allObjectsWithClass:] : 316 -> 312
~ -[NSMutableArray(CALExtensions) removeAllObjectsWithClass:] : 308 -> 304
~ -[NSURL(CALExtensions) queryParameters] : 472 -> 468
~ -[CalDAVCalendarServerNotificationTypeItem notificationNameIn:] : 272 -> 268
~ -[CalDAVResourceTypeItem write:] : 1012 -> 1008
~ -[CalDAVCalendarServerChangedPropertyItem parserFoundAttributes:] : 412 -> 408
~ -[CalDAVCalendarServerChangedParameterItem parserFoundAttributes:] : 332 -> 328
~ -[CalDAVRecurrenceSplitTaskGroup startTaskGroup] : 1068 -> 1064
~ -[CalDAVModifySharedCalendarShareeListTaskGroup generateModificationMessageBody] : 1172 -> 1164
~ -[CalDAVModifySharedCalendarShareeListTaskGroup task:didFinishWithError:] : 1336 -> 1328
~ -[CalDAVAddDropBoxAttachmentsTaskGroup etags] : 388 -> 384
~ -[CalDAVAddDropBoxAttachmentsTaskGroup _sendAttachments] : 696 -> 692
~ +[CalDAVAddDropBoxAttachmentsTaskGroup dropboxACEItemsForPrincipalURLs:baseURL:writable:] : 784 -> 780
~ -[CalDAVOperation _tearDownAllTaskGroupsWithBlock:] : 340 -> 336
~ -[CalDAVCalendarPropertyRefreshOperation _sendDeletesForCalendars] : 960 -> 956
~ -[CalDAVCalendarPropertyRefreshOperation _sendAddsForCalendars] : 700 -> 696
~ -[CalDAVCalendarPropertyRefreshOperation _handleCalendarPublish] : 1304 -> 1300
~ -[CalDAVCalendarPropertyRefreshOperation _sendShareActionTasks] : 2032 -> 2028
~ -[CalDAVCalendarPropertyRefreshOperation _initializePrincipalCalendarCache] : 636 -> 632
~ -[CalDAVCalendarPropertyRefreshOperation _handleUpdateForCalendar:] : 11092 -> 11088
~ -[CalDAVCalendarPropertyRefreshOperation _updateDefaultSchedulingCalendarIfNeededForInboxCalendar:withContainer:] : 716 -> 712
~ -[CalDAVCalendarPropertyRefreshOperation _continueHandleContainerInfoTask:completedWithContainers:error:] : 2180 -> 2164
~ -[CalDAVCalendarPropertyRefreshOperation containerInfoSyncTask:retrievedAddedOrModifiedContainers:removedContainerURLs:] : 1152 -> 1144
~ -[CalDAVPrincipalSearchPropertySet initWithSearchProperties:] : 540 -> 536
~ ___48-[CalDAVPrincipalPropertySearchTask searchItems]_block_invoke : 436 -> 432
~ +[CalDAVPrincipalEmailDetailsResult resultFromResponseItem:] : 952 -> 944
~ -[CalDAVPrincipalEmailDetailsResult addresses] : 332 -> 328
~ +[CalDAVCalendarUserAddress _minPreferredAddress:] : 376 -> 372
~ +[CalDAVCalendarUserAddress _preferredAddressNoPreferred:] : 852 -> 848
~ -[CalDAVGetDelegatesTaskGroup task:didFinishWithError:] : 1488 -> 1480
~ -[CalDAVGetDelegatesBaseTaskGroup _processDetailsFromMultiStatus:allowWrite:] : 396 -> 392
~ -[CalDAVGetGrantedDelegatesTaskGroup task:didFinishWithError:] : 1160 -> 1156
~ -[CalDAVUpdateGrantedDelegatesTaskGroup _updateDelegatesWithAllowWrite:] : 788 -> 784
~ -[CalDAVUpdateGrantedDelegatesTaskGroup taskGroup:didFinishWithError:] : 652 -> 644
~ +[CalDAVServerVersion _prototypeMatchingServerHeaders:] : 560 -> 556
~ +[CalDAVServerVersion versionWithHTTPHeaders:] : 428 -> 424
~ -[CalDAVServerVersion copyWithZone:] : 428 -> 424
~ -[CalDAVServerVersion isEqual:] : 512 -> 508
~ -[CalDAVServerVersion description] : 432 -> 428
~ +[CalDAVServerVersion versionWithPropertyValue:] : 1104 -> 1100
~ -[CalDAVSupportedCalendarComponentSets componentsAsString] : 420 -> 416
~ +[CalDAVSupportedCalendarComponentSets allowedCalendars:contains:] : 404 -> 400
~ -[CalDAVCalendarQueryTask requestBody] : 616 -> 612
~ -[CalDAVMergeUploadTaskGroup _performRegularUpload] : 852 -> 848
~ -[CalDAVAddManagedAttachmentsTaskGroup _sendAttachments] : 1052 -> 1048
~ +[CalDAVOccurrenceChange changeWithItem:] : 756 -> 752
~ +[CalDAVScheduleChangesProperty propertyWithItem:] : 720 -> 716
~ -[CalDAVContainerChecksumSyncTaskGroup _handleResponseToChecksumPropfind:] : 524 -> 520
~ -[CalDAVContainerChecksumSyncTaskGroup deleteResourceURLs:] : 432 -> 428
~ -[CalDAVCalendarColorItem parserFoundAttributes:] : 360 -> 356
~ +[CalDAVCalendarUserSearchTask tokensAreLegal:] : 312 -> 308
~ -[CalDAVCalendarUserSearchTask searchItems] : 376 -> 372
~ -[CalDAVCalendarUserSearchTask requestBody] : 848 -> 840
~ -[CalDAVCalendarSearchTask requestBody] : 884 -> 880
~ -[CalDAVCalendarSearchTask finishCoreDAVTaskWithError:] : 492 -> 488
```
