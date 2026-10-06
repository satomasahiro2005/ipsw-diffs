## ActivitySharingUI

> `/System/Library/PrivateFrameworks/ActivitySharingUI.framework/ActivitySharingUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22bac` | `0x22b38` | **`-0x74`** |

### Other Changes

```diff

-2027.0.11.0.0
+2027.0.12.0.0
Functions:
~ -[ASFriendListSectionManager _sectionForDataVisibilityConditionalUsingBlock:comparator:] : 528 -> 524
~ -[ASCompetitionGraphView _maxDailyScore] : 264 -> 260
~ -[ASCompetitionGraphView _minDailyScore] : 300 -> 296
~ -[ASFriendListSection containsFriendListRow:] : 280 -> 276
~ -[ASFriendListSectionManager _friendWithUUID:fromFriends:] : 340 -> 336
~ -[ASFriendListSectionManager allActiveFriendsAsRecipients] : 452 -> 448
~ -[ASFriendListSectionManager allDestinationsForActiveOrPendingFriends] : 488 -> 484
~ -[ASFriendListSectionManager _queue_handleActivitySummaryUpdate:] : 688 -> 684
~ -[ASFriendListSectionManager _queue_handleMyWorkoutsUpdate] : 756 -> 752
~ -[ASFriendListSectionManager _enumerateVisibleDaysForFriends:usingBlock:] : 1020 -> 1012
~ -[ASFriendListSectionManager _createSectionsForFriends:withDisplayContext:] : 1096 -> 1092
~ ___75-[ASFriendListSectionManager _createSectionsForFriends:withDisplayContext:]_block_invoke_3 : 552 -> 548
~ ___69-[ASFriendListSectionManager _sortFriends:forDisplayMode:cacheIndex:]_block_invoke : 1568 -> 1560
~ -[ASFriendListSectionManager _queue_me] : 292 -> 288
~ -[ASCompetitionGizmoDetailView layoutForWidth:] : 1200 -> 1196
~ _ASActivitySharingBaseKeysForReplyContextType : 560 -> 556
~ _ASActivitySharingRandomizedReplyKeysForReplyContextType : 680 -> 676
~ _ASActivitySharingRandomizedLocalizedReplyForReplyContextType : 420 -> 416
~ _ASWorkoutCaloriesString : 824 -> 820
~ sub_24a0139ac -> sub_24b11d958 : 536 -> 512
~ sub_24a013c18 -> sub_24b11dbac : 276 -> 256
~ sub_24a014388 -> sub_24b11e308 : 4596 -> 4588
~ sub_24a01dc6c -> sub_24b127be4 : 244 -> 252
~ sub_24a01dd60 -> sub_24b127ce0 : 244 -> 252
~ sub_24a01de54 -> sub_24b127ddc : 236 -> 244
~ sub_24a01e3a4 -> sub_24b128334 : 116 -> 112
```
