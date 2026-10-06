## CoreUARP

> `/System/Library/PrivateFrameworks/CoreUARP.framework/CoreUARP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8a184` | `0x8a1c8` | **`+0x44`** |
| `__TEXT.__cstring` | `0x7d5d` | `0x7d62` | **`+0x5`** |

### Other Changes

```diff

-1587.2.3.0.0
+1587.40.26.502.1

-  Functions: 3999
-  Symbols:   6620
+  Functions: 4000
+  Symbols:   6621
Symbols:
+ _UARPLayer2RemoteNotResponding
Functions:
+ _UARPLayer2RemoteNotResponding
~ _uarpTransmitQueueService : 760 -> 784
~ _uarpPlatformNoFirmwareUpdateAvailable : 100 -> 120
CStrings:
+ "RaveBSeed"
- "Rave"
```
