## Catalyst

> `/System/Library/PrivateFrameworks/Catalyst.framework/Catalyst`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5f8d0` | `0x5f934` | **`+0x64`** |
| `__AUTH_CONST.__objc_const` | `0xb598` | `0xb5b8` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x798` | `0x79c` | **`+0x4`** |

### Other Changes

```diff

-23.0.0.0.0
+24.0.0.0.0

-  Symbols:   4081
+  Symbols:   4082
Symbols:
+ _OBJC_IVAR_$_CATSharingServiceTransport.mIsInvalidating
Functions:
~ -[CATSharingBroadcastConnection messageReceived:] : 264 -> 268
~ -[CATSharingDeviceSessionConnection didReceiveMessage:] : 264 -> 268
~ -[CATSharingServiceTransport invalidateConnection] : 108 -> 148
~ -[CATSharingServiceTransport connectionClosed:] : 172 -> 224
```
