## CascadeEngine

> `/System/Library/PrivateFrameworks/CascadeEngine.framework/CascadeEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65860` | `0x658b0` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a68` | `0x1a70` | **`+0x8`** |

### Other Changes

```diff

-255.0.2.0.0
+256.0.1.0.0

-  Functions: 2314
+  Functions: 2315
Symbols:
+ _CCRapportSyncArmTimeout
- GCC_except_table34
Functions:
~ ___122-[CCDonationServiceConnection remoteUpdateFromDeviceUUID:options:mergeableDeltas:peerDeviceSite:relayedDeviceSites:reply:]_block_invoke : 360 -> 364
~ -[CCDonationServiceConnection _resolveSetAccessForResourceSpecifier:accessMode:error:] : 916 -> 920
~ -[CCRapportSyncInteraction setTimeoutForRapportRequest:] : 256 -> 236
+ _CCRapportSyncArmTimeout
~ -[CCRapportSyncSession _setNextInteractionTimeout:] : 400 -> 380
```
