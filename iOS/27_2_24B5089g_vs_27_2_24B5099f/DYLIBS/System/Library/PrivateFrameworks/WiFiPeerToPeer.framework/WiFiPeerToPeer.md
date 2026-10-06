## WiFiPeerToPeer

> `/System/Library/PrivateFrameworks/WiFiPeerToPeer.framework/WiFiPeerToPeer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x401e4` | `0x402bc` | **`+0xd8`** |
| `__AUTH_CONST.__objc_const` | `0x9f18` | `0x9f50` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x567c` | `0x56ac` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x22d8` | `0x22f0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x744` | `0x748` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-887.7.0.0.0
+887.9.0.0.0

-  Functions: 1757
-  Symbols:   3468
+  Functions: 1760
+  Symbols:   3472
Symbols:
+ -[WiFiAwareStateMonitor dpSetupInProgressHandler]
+ -[WiFiAwareStateMonitor setDpSetupInProgressHandler:]
+ -[WiFiAwareStateMonitor updatedNANDPInProgress:]
+ _OBJC_IVAR_$_WiFiAwareStateMonitor._dpSetupInProgressHandler
```
