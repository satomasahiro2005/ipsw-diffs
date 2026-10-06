## MobileBluetooth

> `/System/Library/PrivateFrameworks/MobileBluetooth.framework/MobileBluetooth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e648` | `0x2e744` | **`+0xfc`** |
| `__AUTH.__data` | `—` | `0x68` | **`+0x68`** |
| `__DATA_DIRTY.__data` | `0x1e8` | `0x180` | **`-0x68`** |

### Other Changes

```diff

-2700.41.1.1.0
+2700.43.0.0.0
Functions:
~ __localBTAccessoryManagerAddCallbacks : 348 -> 364
~ __localBTLocalDeviceAddCallbacks : 204 -> 220
~ __localBTDeviceServiceAddCallbacks : 168 -> 180
~ __localBTLocalDeviceGetCallbacks : 140 -> 148
~ __localBTLocalDeviceGetStatsCallbacks : 136 -> 144
~ __localBTDeviceServiceGetUserData : 136 -> 148
~ __localBTLocalDeviceGetUserData : 220 -> 236
~ __localBTAccessoryManagerAddCustomCallbacks : 376 -> 400
~ __localBTAccessoryManagerGetCallbacksCBID : 156 -> 164
~ __localBTAccessoryManagerGetCustomCallbacksCBID : 152 -> 156
~ __localBTAccessoryManagerGetCustomCallbackMsgType : 136 -> 148
~ __localBTAccessoryManagerGetUserData : 212 -> 236
~ __localBTDeviceServiceGetCBID : 136 -> 144
~ __localBTDiscoveryAgentAddCallbacks : 172 -> 188
~ __localBTDiscoveryAgentGetUserData : 136 -> 148
~ __localBTLocalDeviceGetCallbacksCBID : 160 -> 168
~ __localBTLocalDeviceStatsGetCallbacksCBID : 140 -> 148
~ __localBTLocalDeviceAddStatsCallbacks : 192 -> 208
~ __localBTPairingAgentAddCallbacks : 180 -> 192
~ __localBTPairingAgentGetUserData : 120 -> 132
```
