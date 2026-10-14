## AssistantUI

> `/System/Library/PrivateFrameworks/AssistantUI.framework/AssistantUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x66004` | `0x66170` | **`+0x16c`** |
| `__DATA.__data` | `0x1830` | `0x1848` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xdf0` | `0xe00` | **`+0x10`** |
| `__TEXT.__const` | `0x1094` | `0x10a4` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x5400` | `0x5408` | **`+0x8`** |

### Other Changes

```diff

-3605.30.1.0.0
+3605.31.1.11.2

-  Functions: 2809
+  Functions: 2812
Functions:
~ -[AFUISiriViewController tvRemoteSentButtonDownWhileListening] : 112 -> 124
~ -[AFUISiriViewController _canIgnoreHoldToTalkThreshold] : 168 -> 200
~ -[AFUISiriViewController _enterHoldToTalkMode] : 188 -> 224
~ -[AFUISiriViewController startRequestWithActivationTrigger:completion:] : 480 -> 512
+ sub_203f5d204
+ sub_203f5d42c
+ sub_203f5db70
```
