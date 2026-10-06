## DataRelay_Private

> `/System/Library/PrivateFrameworks/DataRelay_Private.framework/DataRelay_Private`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf6cc` | `0xf6a8` | **`-0x24`** |

### Other Changes

```diff

-40.28.1.1.2
+40.31.1.0.0
Functions:
~ -[DataRelayDaemon handleXPCDisconnected:] -> ___41-[DataRelayDaemon handleXPCDisconnected:]_block_invoke : 120 -> 20
~ ___41-[DataRelayDaemon handleXPCDisconnected:]_block_invoke -> -[DataRelayDaemon handleXPCDisconnected:] : 20 -> 120
~ -[DRServerManager handleXPCDisconnected:] : 460 -> 456
~ ___26-[DRServer eventsHandler:]_block_invoke : 744 -> 740
~ -[DRHIDClientDM6 serviceAdded:] : 716 -> 712
~ -[DRHIDClient activate] : 1460 -> 1456
~ -[DRHIDClient invalidate] : 340 -> 336
~ -[DRHIDClient getSensorTime:] : 396 -> 392
~ -[DRHIDClient routedWxDeviceChanged:] : 528 -> 524
~ -[DRHIDClientHRM getHeartRateFlags:] : 456 -> 452
~ -[DRHIDClientHRM serviceAdded:] : 764 -> 760
```
