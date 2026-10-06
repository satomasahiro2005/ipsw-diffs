## ContinuitySing

> `/System/Library/PrivateFrameworks/ContinuitySing.framework/ContinuitySing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5dc58` | `0x5de10` | **`+0x1b8`** |
| `__TEXT.__oslogstring` | `0x3329` | `0x3389` | **`+0x60`** |
| `__TEXT.__cstring` | `0x6169` | `0x61b9` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x2ee0` | `0x2f00` | **`+0x20`** |
| `__TEXT.__const` | `0xfa4` | `0xfb4` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xb94` | `0xb98` | **`+0x4`** |

### Other Changes

```diff

-761.0.0.0.3
+764.22.5.122.2

-  CStrings:  943
+  CStrings:  946
Functions:
~ -[CSRemoteRequestClient dealloc] : 256 -> 296
~ -[CSRemoteRequestClient _registerForReactions] : 236 -> 332
~ ___74-[CSShieldManager _attemptMicrophoneConnectionOnRoute:isRetry:completion:]_block_invoke : 692 -> 716
~ ___49-[CSShieldViewController _activateEnableMicTimer]_block_invoke : 108 -> 160
~ -[CSPairingDevice preferredDeviceIdentifier] : 172 -> 400
CStrings:
+ "%s: preferredDeviceIdentifier %@ (sessionPairing:%@ peerVerified:%@ ids:%@ mediaRoute:%@)"
+ "%s: requested mic with result %@, error: %@, retry: %@"
+ "-[CSPairingDevice preferredDeviceIdentifier]"
+ "Enable microphone request timed out"
- "%s: requested mic with result %@, error: %@%@"
```
