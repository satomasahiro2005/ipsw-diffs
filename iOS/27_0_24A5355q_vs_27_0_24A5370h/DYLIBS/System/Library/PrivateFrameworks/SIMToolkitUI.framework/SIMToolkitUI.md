## SIMToolkitUI

> `/System/Library/PrivateFrameworks/SIMToolkitUI.framework/SIMToolkitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12cf4` | `0x12ca4` | **`-0x50`** |

### Other Changes

```text
Functions:
~ -[STKTelephonySelectionListItemsProvider selectionListItemsForContext:options:] : 536 -> 532
~ ___61-[STKUSSDAlertSessionManager remoteAlertHandleDidDeactivate:]_block_invoke : 1364 -> 1348
~ ___71-[STKUSSDAlertSessionManager remoteAlertHandle:didInvalidateWithError:]_block_invoke : 1536 -> 1520
~ ___64-[STKClass0SMSAlertSessionManager incomingCallUIStateDidChange:]_block_invoke : 416 -> 412
~ -[STKDeviceLockMonitor _updateDeviceLockState] : 436 -> 432
~ -[STKAlertSessionEventQueue _queue_dequeueEventsIfPossible] : 316 -> 312
~ -[STKCarrierSubscriptionMonitor subscriptionInfoDidChange] : 688 -> 680
~ -[STKSIMToolkitAlertSessionManager _queue_handleSIMToolkitEvent:responder:userInfo:] : 3644 -> 3640
~ -[STKSIMToolkitAlertSessionManager _listItemsFromCTItems:] : 428 -> 424
~ -[STKUSSDFilter shouldFilterString:coalescable:] : 800 -> 792
~ -[STKUSSDAlertSession listener:shouldAcceptNewConnection:] : 400 -> 396
~ -[STKIncomingCallUIStateMonitor _setIncomingCallUIState:forReason:] : 616 -> 612
```
