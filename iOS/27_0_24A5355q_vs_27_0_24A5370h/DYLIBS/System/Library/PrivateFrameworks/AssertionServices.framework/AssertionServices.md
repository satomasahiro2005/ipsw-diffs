## AssertionServices

> `/System/Library/PrivateFrameworks/AssertionServices.framework/AssertionServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7250` | `0x7224` | **`-0x2c`** |
| `__TEXT.__const` | `0x124` | `0x11c` | **`-0x8`** |

### Other Changes

```diff

-1066.0.0.0.1
+1071.0.0.0.0
Functions:
~ -[BKSApplicationStateMonitor _legacyInfoForProcess:state:] : 1188 -> 1184
~ -[BKSApplicationStateMonitor _clientSubscribedToThisReasonChange:] : 360 -> 356
~ -[BKSApplicationStateMonitor lock_updateConfiguration] : 524 -> 520
~ +[BKSProcess busyExtensionInstances:] : 428 -> 424
~ -[BKSProcess _bootstrapWithError:] : 1580 -> 1576
~ -[BKSTerminationAssertionObserverManager hasTerminationAssertionForBundleID:] : 456 -> 452
~ ___56-[BKSTerminationAssertionObserverManager _createMonitor]_block_invoke_2 : 1496 -> 1484
~ ___56-[BKSTerminationAssertionObserverManager _createMonitor]_block_invoke_3 : 252 -> 248
~ ___56-[BKSTerminationAssertionObserverManager _createMonitor]_block_invoke_4 : 252 -> 248
```
