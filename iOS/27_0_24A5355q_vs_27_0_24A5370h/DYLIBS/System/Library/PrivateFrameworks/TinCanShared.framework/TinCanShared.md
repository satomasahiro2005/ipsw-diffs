## TinCanShared

> `/System/Library/PrivateFrameworks/TinCanShared.framework/TinCanShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12558` | `0x124c8` | **`-0x90`** |

### Other Changes

```text
Functions:
~ -[TCSSuggestions batchQueryController:updatedDestinationsStatus:onService:error:] : 956 -> 948
~ -[TCSSuggestions _generateNewSuggestions] : 904 -> 900
~ -[TCSSuggestions _destinationsFromFavorites] : 900 -> 892
~ -[TCSSuggestions _destinationsFromCallHistory] : 1216 -> 1208
~ -[TCSSuggestions _destinationsFromCoreRecents] : 1384 -> 1376
~ ___46-[TCSSuggestions _destinationsFromCoreRecents]_block_invoke : 288 -> 284
~ -[TCSSuggestions _performIDQueryForSuggestions:] : 640 -> 636
~ -[TCSSuggestions _notifyObserversSuggestionsChanged] : 292 -> 288
~ -[TCSContactsDataSource removeContact:inSection:] : 524 -> 532
~ -[TCSContactsDataSource logSortedContacts] : 1320 -> 1308
~ -[TCSContactsDataSource _contactMapFromArray:] : 344 -> 340
~ -[TCSContactsDataSource _updateSortedContactsAndNotifyIfChanged:] : 1064 -> 1052
~ -[TCSContactsDataSource _unsortedContactsArray] : 516 -> 512
~ -[TCSCall initWithURL:] : 1376 -> 1372
~ -[TCSSuggestionsDataSource suggestedContacts] : 1468 -> 1460
~ -[TCSIDSIDStatusController initWithItem:delegate:timeout:] : 440 -> 436
~ -[TCSIDSIDStatusController status] : 444 -> 440
~ -[TCSIDSIDStatusController batchQueryController:updatedDestinationsStatus:onService:error:] : 828 -> 824
~ ___38-[TCSTinCanUserDefaults clearUserData]_block_invoke : 552 -> 548
~ ___57+[TCSContacts dismissInvitationNotificationsFromContact:]_block_invoke : 932 -> 928
~ -[TCSContacts removeDestinations:] : 524 -> 520
~ -[TCSContacts setContact:supportsTinCan:] : 764 -> 760
~ -[TCSContacts contactSupportsTinCan:] : 396 -> 392
~ -[TCSContacts isContactAccepted:] : 284 -> 280
~ -[TCSContacts isContactAnInviter:] : 284 -> 280
~ -[TCSContacts setContactAsAccepted:] : 292 -> 288
~ -[TCSContacts didInitiateCallToContact:date:] : 304 -> 300
~ -[TCSContacts didReceiveCallFromContact:date:] : 304 -> 300
~ -[TCSContacts mostRecentCallDateForContact:] : 360 -> 356
~ +[TCSContacts validatedAllowlistFromDictionary:] : 368 -> 364
~ -[TCSContacts _addDestinations:asType:] : 964 -> 988
~ -[TCSContacts _removeDestinationFromAllowlist:] : 484 -> 480
~ -[TCSContacts _notifyObserversDestinationsChanged] : 292 -> 288
~ -[TCSContacts _notifyObserversRecencyChanged] : 292 -> 288
~ -[TCSContacts _notifyObserversContactBecameAccepted:] : 304 -> 300
~ +[TCSContacts canonicalDestinationsForContact:] : 688 -> 680
```
