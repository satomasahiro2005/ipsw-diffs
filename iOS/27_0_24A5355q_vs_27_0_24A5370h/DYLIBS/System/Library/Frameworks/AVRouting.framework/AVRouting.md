## AVRouting

> `/System/Library/Frameworks/AVRouting.framework/AVRouting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x63d3c` | `0x63d50` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x10c8` | `0x10d8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1890` | `0x1898` | **`+0x8`** |
| `__TEXT.__cstring` | `0xecf7` | `0xecfe` | **`+0x7`** |

### Other Changes

```diff

-360.58.1.0.0
+360.63.1.11.2

-  Functions: 2571
-  Symbols:   4645
+  Functions: 2572
+  Symbols:   4647
Symbols:
+ -[AVFigEndpointUIAgentOutputDeviceAuthorizationSessionImpl _finishedWithPromptReason:]
+ _kFigEndpointUIAgentNotificationPayloadKey_FinishedWithPromptInfo
+ _kFigEndpointUIAgentPromptInfo_ReasonErrorMDEAuthorizationFailed
- -[AVFigEndpointUIAgentOutputDeviceAuthorizationSessionImpl _finishedWithPrompt]
CStrings:
+ "-[AVFigEndpointUIAgentOutputDeviceAuthorizationSessionImpl _finishedWithPromptReason:]"
- "-[AVFigEndpointUIAgentOutputDeviceAuthorizationSessionImpl _finishedWithPrompt]"
```
