## NanoMailKitServer

> `/System/Library/PrivateFrameworks/NanoMailKitServer.framework/NanoMailKitServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x787c4` | `0x7874c` | **`-0x78`** |
| `__TEXT.__oslogstring` | `0x826f` | `0x8223` | **`-0x4c`** |
| `__AUTH_CONST.__objc_const` | `0xe4d8` | `0xe4d0` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d10` | `0x3d08` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1818` | `0x1810` | **`-0x8`** |

### Other Changes

```diff

-861.1.0.0.0
+864.0.0.0.0

-  Functions: 3296
-  Symbols:   5206
+  Functions: 3295
+  Symbols:   5205
Symbols:
+ -[NNMKSyncStateManager registry:didDeactivate:]
- -[NNMKSyncProvider syncStateManagerDidUnpair:]
- ___46-[NNMKSyncProvider syncStateManagerDidUnpair:]_block_invoke
Functions:
~ -[NNMKSyncStateManager pairingStorePath] : 84 -> 76
+ -[NNMKSyncStateManager registry:didActivate:]
- ___46-[NNMKSyncProvider syncStateManagerDidUnpair:]_block_invoke
- ___58-[NNMKSyncProvider syncStateManagerDidChangePairedDevice:]_block_invoke
CStrings:
+ "Received Activate notification from PDRRegistry. Informing NNMKSyncProvider..."
+ "Received Deactivate notification from PDRRegistry. Informing NNMKSyncProvider..."
- "#PAIRING_STATE Unpairing detected. Triggering verification to insure we don't stop sync'ing if we still have another device we're talking to..."
- "Received Paired Device Changed notification from PDRRegistry. Informing NNMKSyncProvider..."
```
