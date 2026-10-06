## FMCore

> `/System/Library/PrivateFrameworks/FMCore.framework/FMCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14d24` | `0x14ce0` | **`-0x44`** |

### Other Changes

```text
Functions:
~ -[FMCommandBase sendRequest] : 1756 -> 1752
~ -[FMDaemon verifyLaunchEventsConfiguration:withExclusions:] : 1648 -> 1640
~ -[FMLocationShifter isLocationShiftRequiredForItems:] : 272 -> 268
~ -[FMLocationShifter shiftLocations:withCompletionHandler:callbackQueue:] : 816 -> 812
~ ___42-[FMAPSHandler registerDelegate:forTopic:]_block_invoke : 812 -> 804
~ ___35-[FMAPSHandler deregisterDelegate:]_block_invoke : 708 -> 700
~ ___41-[FMAPSHandler _registrationsWereResumed]_block_invoke : 768 -> 760
~ ___39-[FMAPSHandler _handleMessage:onTopic:]_block_invoke : 704 -> 700
~ ___49-[FMAPSHandler connection:didReceivePublicToken:]_block_invoke.36 : 276 -> 272
~ -[NSString(FMCoreAdditions) fm_decodeHexString] : 340 -> 348
~ ___64+[FMXPCNotificationsUtil handleDarwinNotificationsWithHandlers:]_block_invoke : 416 -> 412
~ ___69+[FMXPCNotificationsUtil handleDistributedNotificationsWithHandlers:]_block_invoke : 416 -> 412
~ -[CKVOBlockHelper dealloc] : 356 -> 352
~ +[FMStopwatch dumpBuffer:] : 688 -> 684
~ -[FMKeychainManager allServices] : 392 -> 388
~ -[FMKeychainManager allAccountsForService:] : 424 -> 420
```
