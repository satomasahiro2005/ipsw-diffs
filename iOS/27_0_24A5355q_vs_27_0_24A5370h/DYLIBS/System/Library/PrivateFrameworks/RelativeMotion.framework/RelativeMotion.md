## RelativeMotion

> `/System/Library/PrivateFrameworks/RelativeMotion.framework/RelativeMotion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9c3c` | `0x9c28` | **`-0x14`** |
| `__TEXT.__cstring` | `0xe20` | `0xe21` | **`+0x1`** |

### Other Changes

```diff

-375.0.0.0.0
+374.0.6.0.0
Functions:
~ _CreateXpcMessage : 312 -> 304
~ -[RMConnectionClient replayCache] : 636 -> 632
~ -[RMConnectionClient sendMessage:withData:reply:] : 456 -> 452
~ -[RMConnectionClient stopStreaming] : 304 -> 300
CStrings:
+ "kRMConnectionRequestStreamingKey"
- "kRMConnectionRequestSteamingKey"
```
