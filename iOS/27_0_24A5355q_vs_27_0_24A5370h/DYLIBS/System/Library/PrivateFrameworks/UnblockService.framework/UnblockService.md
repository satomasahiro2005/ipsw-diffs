## UnblockService

> `/System/Library/PrivateFrameworks/UnblockService.framework/UnblockService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd9f4` | `0xd9a0` | **`-0x54`** |

### Other Changes

```text
Functions:
~ -[UBDeadlockInfo debugDescription] : 500 -> 496
~ ___52-[UBUnblockReactiveRecovery(Deadlock) findDeadlocks]_block_invoke : 1208 -> 1200
~ -[UBUnblockReactiveRecovery(Deadlock) selectNodeInDeadlocksBlockingTask:preferredMinimumDuration:serviceContext:processLevelDependencies:] : 1200 -> 1196
~ -[UBUnblockReactiveRecovery(Deadlock) selectNodeInDeadlocks:longerThan:serviceContext:] : 1612 -> 1608
~ -[UBUnblockReactiveRecovery(ThreadExhaustion) selectThreadExhaustionInAllThreadExhaustionsWithServiceContext:] : 744 -> 736
~ -[UBUnblockReactiveRecovery(ThreadExhaustion) selectThreadExhaustionInThreadExhaustions:allowSuspended:serviceContext:] : 744 -> 736
~ -[UBUnblockReactiveRecovery(ThreadExhaustion) selectThreadExhaustionBlockingTask:serviceContext:processLevelDependencies:] : 696 -> 692
~ ___106-[UBUnblockReactiveRecovery(ThreadExhaustion) threadExhaustionsAboveLimit:threadIDToThreadExhaustionDict:]_block_invoke.153 : 836 -> 832
~ -[UBUnblockReactiveRecovery(Termination) doTerminations:options:] : 1276 -> 1284
~ -[UBUnblockReactiveRecovery fillInRecoveryInfo:deadlockNodeSelected:exhaustedTaskSelected:suspendedTaskSelected:threadExhaustions:processLevelDependencies:options:] : 4068 -> 4032
~ -[UBUnblockReactiveRecovery taskIs3PApp:options:] : 1404 -> 1400
~ -[UBUnblockReactiveRecovery selectTaskBlockingTask:serviceContext:] : 4208 -> 4204
~ -[UBUnblockReactiveRecovery selectTaskInTasks:serviceContext:] : 2364 -> 2340
~ -[UBUnblockReactiveRecovery _recover:error:] : 5380 -> 5404
~ -[UBUnblockService(XPCHandling) handleReactiveRecoveryRequest:] : 1276 -> 1272
```
