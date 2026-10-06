## ContextKitExtraction

> `/System/Library/PrivateFrameworks/ContextKitExtraction.framework/ContextKitExtraction`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__unwind_info` | `0x3e8` | `0x3e0` | **`-0x8`** |

### Other Changes

```text
Functions:
~ -[CKContextContentProviderUIScene _setScene:] -> +[CKContextContentProviderManager isSpringBoard] : 20 -> 12
~ -[CKContextContentProviderManager userActivityWasCreated:] -> -[CKContextContentProviderUIScene _setScene:] : 180 -> 20
~ +[CKContextContentProviderManager isSpringBoard] -> -[CKContextContentProviderManager userActivityWasCreated:] : 12 -> 180
~ -[CKContextContentProviderManager scheduleUserActivityRecordingWithUserActivity:] -> -[CKContextContentProviderManager _hasForegroundActiveContentWithReply:] : 480 -> 204
~ -[CKContextContentProviderManager _isActivityReportingAllowedForCurrentBundleIdentifier:] -> -[CKContextContentProviderUIScene _scene] : 264 -> 52
~ -[CKContextContentProviderManager _loadContextKitIfNecessaryWithExecutor:] -> -[CKContextContentProviderManager scheduleUserActivityRecordingWithUserActivity:] : 192 -> 480
~ -[CKContextContentProviderManager _queueActivityForReporting:] -> -[CKContextContentProviderManager _isActivityReportingAllowedForCurrentBundleIdentifier:] : 148 -> 264
~ -[CKContextContentProviderUIScene _scene] -> -[CKContextContentProviderManager _loadContextKitIfNecessaryWithExecutor:] : 52 -> 192
~ -[CKContextContentProviderManager _prepareDonationWithNonce:options:isRecentsCapture:requiringMainQueue:andReply:] -> -[CKContextContentProviderManager _queueActivityForReporting:] : 264 -> 148
~ -[CKContextContentProviderManager _hasForegroundActiveContentWithReply:] -> -[CKContextContentProviderManager _prepareDonationWithNonce:options:isRecentsCapture:requiringMainQueue:andReply:] : 204 -> 264
```
