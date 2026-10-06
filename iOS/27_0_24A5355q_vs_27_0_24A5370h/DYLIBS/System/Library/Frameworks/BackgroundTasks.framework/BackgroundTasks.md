## BackgroundTasks

> `/System/Library/Frameworks/BackgroundTasks.framework/BackgroundTasks`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb13c` | `0xb104` | **`-0x38`** |

### Other Changes

```diff

-2463.0.0.502.1
+2467.0.9.0.0
Functions:
~ -[_BGTaskIdentifierRegistry initWithContentsFromPlist] : 692 -> 688
~ -[_BGTaskIdentifierRegistry isIdentifierValidContinuedProcessingComposedNotation:] : 380 -> 376
~ -[_BGTaskIdentifierRegistry permittedContinuedProcessingBaseNotationIdentifiers] : 428 -> 424
~ ___63-[BGTaskScheduler getPendingTaskRequestsWithCompletionHandler:]_block_invoke : 564 -> 560
~ -[BGTaskScheduler _runningTasks] : 404 -> 400
~ -[BGTaskScheduler _isRunningTaskOfClass:] : 372 -> 368
~ -[BGTaskScheduler _callRegisteredHandlersForActivities:] : 828 -> 824
~ -[BGTaskScheduler _unsafe_taskForActivity:] : 440 -> 436
~ -[BGTaskScheduler _unsafe_createExpirationRequestsForActivities:] : 404 -> 400
~ -[BGTaskScheduler scheduler:handleLifecycleEvents:] : 572 -> 568
~ -[BGTaskScheduler _expirationRequestsFrom:] : 416 -> 412
~ -[BGTaskScheduler _invokeExpirationHandlersForExpirationRequests:] : 484 -> 480
~ -[BGTaskScheduler _callExpirationHandlersFor:shouldQueue:] : 688 -> 684
~ ___56-[BGTaskScheduler _simulateLaunchForTaskWithIdentifier:]_block_invoke : 688 -> 684
```
