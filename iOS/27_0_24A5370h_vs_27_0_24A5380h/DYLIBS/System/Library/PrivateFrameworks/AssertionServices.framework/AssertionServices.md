## AssertionServices

> `/System/Library/PrivateFrameworks/AssertionServices.framework/AssertionServices`

### Other Changes

```diff

-1071.0.0.0.0
+1072.0.0.0.0
Functions:
~ -[BKSAssertion _acquireAsynchronously] -> -[BKSProcessAssertion initWithBundleIdentifier:flags:reason:name:] : 120 -> 12
~ -[BKSAssertion _setAttributes:] -> -[BKSAssertion _lock_setAttributes:] : 84 -> 156
~ -[BKSAssertion _lock_setAttributes:] -> -[BKSAssertion _acquireAsynchronously] : 156 -> 120
~ -[BKSApplicationStateMonitor applicationInfoForPID:] -> -[BKSAssertion _setAttributes:] : 184 -> 84
~ _BKSProcessAssertionBackgroundTimeRemaining -> -[BKSApplicationStateMonitor applicationInfoForPID:] : 112 -> 184
~ -[BKSApplicationStateMonitor interestedStates] -> _BKSProcessAssertionBackgroundTimeRemaining : 56 -> 112
~ -[BKSAssertion setInvalidationHandler:] -> -[BKSApplicationStateMonitor interestedStates] : 104 -> 56
~ -[BKSProcessAssertion initWithBundleIdentifier:flags:reason:name:] -> -[BKSAssertion setInvalidationHandler:] : 12 -> 104
```
