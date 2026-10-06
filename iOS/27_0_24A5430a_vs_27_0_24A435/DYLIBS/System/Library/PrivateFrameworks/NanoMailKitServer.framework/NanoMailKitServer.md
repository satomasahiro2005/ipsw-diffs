## NanoMailKitServer

> `/System/Library/PrivateFrameworks/NanoMailKitServer.framework/NanoMailKitServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7874c` | `0x78748` | **`-0x4`** |

### Other Changes

```text
Functions:
~ -[NNMKSyncPersistenceHandler addMessagesToResend:mailbox:] : 1284 -> 1288
~ -[NNMKResendScheduler registerIDSIdentifier:objectIds:type:resendInterval:].cold.1 : 88 -> 92
~ -[NNMKResendScheduler handleIDSMessageSentSuccessfullyWithId:].cold.1 : 72 -> 64
~ -[NNMKResendScheduler forceRetryingAllPendingIDSMessages].cold.1 : 64 -> 68
~ -[NNMKResendScheduler _resendObjectIds:type:resendInterval:idsIdentifier:].cold.1 : 72 -> 64
```
