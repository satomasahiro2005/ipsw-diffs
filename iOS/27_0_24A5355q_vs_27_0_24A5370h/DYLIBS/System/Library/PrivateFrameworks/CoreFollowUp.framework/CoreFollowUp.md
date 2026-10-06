## CoreFollowUp

> `/System/Library/PrivateFrameworks/CoreFollowUp.framework/CoreFollowUp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20bd4` | `0x20c08` | **`+0x34`** |

### Other Changes

```text
Functions:
~ -[FLTopLevelViewModel _groupsForPrimaryAccount:secondaryAccounts:simpleAccountGrouping:] : 1932 -> 1928
~ -[FLTelemetryAnalyticsController captureCurrentState:] : 656 -> 652
~ -[FLGroupViewModelImpl _firstUserInfoValueForKey:ofClass:] : 352 -> 348
~ -[FLGroupViewModelImpl _expirationOrInformativeText] : 588 -> 584
~ -[FLTopLevelViewModel allPendingItems] : 900 -> 896
~ -[FLTopLevelViewModel _refreshItemsWithExtensionToItemMap:completion:] : 1044 -> 1040
~ ___70-[FLTopLevelViewModel _refreshItemsWithExtensionToItemMap:completion:]_block_invoke_2 : 124 -> 120
~ ___70-[FLTopLevelViewModel _refreshItemsWithExtensionToItemMap:completion:]_block_invoke_3 : 144 -> 140
~ ___88-[FLTopLevelViewModel mapItems:toGroups:unknownGroup:deviceGroup:simpleAccountGrouping:]_block_invoke : 544 -> 540
~ sub_1dd2d56a4 -> sub_1ddcbc680 : 92 -> 88
~ sub_1dd2dadc8 -> sub_1ddcc1da0 : 232 -> 236
~ sub_1dd2de9b8 -> sub_1ddcc5994 : 1296 -> 1316
~ sub_1dd2df334 -> sub_1ddcc6324 : 212 -> 208
~ sub_1dd2e0484 -> sub_1ddcc7470 : 316 -> 320
~ sub_1dd2e1138 -> sub_1ddcc8128 : 4832 -> 4900
```
