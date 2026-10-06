## FriendKit

> `/System/Library/PrivateFrameworks/FriendKit.framework/FriendKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd378` | `0xd2e8` | **`-0x90`** |

### Other Changes

```text
Functions:
~ -[NSSet(FriendKit) fkSanitizedDestinationSet] : 372 -> 368
~ ___38-[FKFriendsManager _curatedFriendList]_block_invoke : 1128 -> 1116
~ -[FKFriendsManager canAddFriend] : 276 -> 272
~ -[FKFriendsManager friendGroup:didMoveFriends:] : 372 -> 368
~ -[FKFriendsManager addFriend:] : 312 -> 308
~ -[FKFriendsManager _save] : 928 -> 924
~ -[FKFriendsManager _addPersonToIdentifiersToPersonMap:] : 364 -> 360
~ -[FKFriendsManager _removePersonFromIdentifiersToPersonMap:] : 356 -> 352
~ -[FKFriendsManager _createAddressToPersonDictionary] : 384 -> 380
~ -[FKFriendsManager _destinations] : 416 -> 412
~ -[FKFriendsManager idStatusUpdatedForDestinations:] : 1552 -> 1508
~ -[FKFriendsManager statusForPerson:requery:] : 580 -> 576
~ -[FKFriendsManager _queryDestinations:] : 552 -> 548
~ ___35-[FKFriendsManager _updateFriends:]_block_invoke : 924 -> 920
~ ___35-[FKFriendsManager _updateFriends:]_block_invoke_2 : 1320 -> 1312
~ +[FKFriendsManager collapseChangeLogsIntoChangeLog:] : 404 -> 400
~ -[FKFriendsManager saveFriendGroupTitles] : 424 -> 420
~ -[FKPerson isEqualToDictionaryRepresentation:] : 416 -> 412
~ +[FKPerson allValuesForPerson:] : 500 -> 496
~ +[FKPerson _allPhoneValuesInSet:] : 328 -> 324
~ +[FKPerson _allEmailValuesInSet:] : 328 -> 324
~ -[FKFriendGroup displayNameForGroupWithSeparator:] : 776 -> 768
```
