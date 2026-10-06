## MediaGroups

> `/System/Library/PrivateFrameworks/MediaGroups.framework/MediaGroups`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9bd8` | `0x9b8c` | **`-0x4c`** |

### Other Changes

```text
Functions:
~ ___MGLogForCategory_block_invoke : 108 -> 112
~ +[MGGroup groupWithName:members:completion:] : 408 -> 404
~ +[MGGroup validateGroupSpecificationWithType:identifier:name:properties:members:] : 676 -> 672
~ -[MGGroup predicateForMembers] : 380 -> 376
~ -[MGGroup _conformingProtocols] : 252 -> 248
~ -[MGClientService reconnect] : 624 -> 620
~ _MGGroupIdentifierCopyApplyingHashing : 688 -> 684
~ __MGRelevantComponentsForGroupIdentifierComponents : 572 -> 568
~ _MGAccessoryFromHomeManagerForGroupIdentifier : 788 -> 768
~ _MGMemberIdentifiersForMediaSystem : 652 -> 648
~ _MGMediaSystemFromHomeManagerForGroupIdentifier : 652 -> 644
~ _MGRoomFromHomeManagerForGroupIdentifier : 652 -> 644
~ _MGZoneFromHomeManagerForGroupIdentifier : 652 -> 644
~ _MGHomeFromHomeManagerForGroupIdentifier : 420 -> 416
```
