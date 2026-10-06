## PushKit

> `/System/Library/Frameworks/PushKit.framework/PushKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4998` | `0x4988` | **`-0x10`** |

### Other Changes

```text
Functions:
~ ___38-[PKPushRegistry setDesiredPushTypes:]_block_invoke : 476 -> 468
~ -[PKUserNotificationsRemoteNotificationServiceConnection _queue_remoteUserNotificationsRegistrationSucceededWithDeviceToken:] : 268 -> 264
~ -[PKUserNotificationsRemoteNotificationServiceConnection _queue_remoteUserNotificationPayloadReceived:completionHandler:] : 552 -> 548
```
