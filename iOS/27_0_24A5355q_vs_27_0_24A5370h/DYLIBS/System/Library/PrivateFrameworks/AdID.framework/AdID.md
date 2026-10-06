## AdID

> `/System/Library/PrivateFrameworks/AdID.framework/AdID`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18c80` | `0x18c58` | **`-0x28`** |

### Other Changes

```diff

-638.0.7.0.0
+638.1.0.0.0
Functions:
~ -[ADClientDPIDManager operationQueueLog] : 360 -> 356
~ ___50-[ADClientDPIDManager teardowniCloudSubscription:]_block_invoke_4 : 608 -> 604
~ -[ADClientDPIDManager handleCloudKitError:] : 976 -> 972
~ -[ADJingleRequest send] : 1464 -> 1460
~ -[ADIDManagerService delayForNewForceReconcileRequest] : 528 -> 524
~ -[ADIDManager(Private) save] : 1480 -> 1476
~ -[ADIDManager(Private) finishedReconciling:withError:] : 1316 -> 1312
~ -[ADAdTrackingSchedulingManager isNewsOrStocksEnabledLocality] : 956 -> 952
~ ___56-[ADSegmentDataManager noiseAppliedBirthYearFromActual:]_block_invoke : 1820 -> 1812
```
