## HomeKitEventRouter

> `/System/Library/PrivateFrameworks/HomeKitEventRouter.framework/HomeKitEventRouter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16f10` | `0x16f08` | **`-0x8`** |

### Other Changes

```diff

-1493.1.5.1.1
+1514.0.0.0.1
Functions:
~ ___50-[HMEMessageDatagramClient _performConnectRequest]_block_invoke : 572 -> 564
~ -[HMEMessageDatagramClient _removeRetryTimer] -> ___50-[HMEMessageDatagramClient _performConnectRequest]_block_invoke.10 : 108 -> 764
~ ___50-[HMEMessageDatagramClient _performConnectRequest]_block_invoke.10 -> -[HMEMessageDatagramClient _didDisconnect] : 764 -> 160
~ -[HMEMessageDatagramClient _didDisconnect] -> -[HMEMessageDatagramClient _enableRetryTimer] : 160 -> 564
~ -[HMEMessageDatagramClient _enableRetryTimer] -> -[HMEMessageDatagramClient _performRequestWithBlock:] : 564 -> 188
~ -[HMEMessageDatagramClient _performRequestWithBlock:] -> ___62-[HMEMessageDatagramClient _performChangeRegistrationsRequest]_block_invoke : 188 -> 756
~ ___62-[HMEMessageDatagramClient _performChangeRegistrationsRequest]_block_invoke -> -[HMEMessageDatagramClient _removeRetryTimer] : 756 -> 108
```
