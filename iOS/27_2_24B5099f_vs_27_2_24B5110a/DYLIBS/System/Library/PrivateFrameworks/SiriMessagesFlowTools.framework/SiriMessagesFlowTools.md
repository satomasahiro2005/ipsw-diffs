## SiriMessagesFlowTools

> `/System/Library/PrivateFrameworks/SiriMessagesFlowTools.framework/SiriMessagesFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x125bf4` | `0x12ad30` | **`+0x513c`** |
| `__AUTH_CONST.__const` | `0x49c8` | `0x4f68` | **`+0x5a0`** |
| `__TEXT.__oslogstring` | `0x85e1` | `0x8901` | **`+0x320`** |
| `__TEXT.__swift5_capture` | `0x738` | `0x978` | **`+0x240`** |
| `__TEXT.__eh_frame` | `0x9730` | `0x9940` | **`+0x210`** |
| `__TEXT.__unwind_info` | `0x3da8` | `0x3e80` | **`+0xd8`** |
| `__TEXT.__const` | `0xaf74` | `0xaf94` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x72c` | `0x740` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x2200` | `0x21f0` | **`-0x10`** |
| `__DATA.__data` | `0x1af8` | `0x1b00` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x3754` | `0x375c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x474` | `0x47c` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x37c` | `0x380` | **`+0x4`** |

### Other Changes

```diff

-3605.20.1.0.0
+3605.21.1.11.2

-  Functions: 5761
-  Symbols:   2025
-  CStrings:  646
+  Functions: 5868
+  Symbols:   2027
+  CStrings:  655
Symbols:
+ ___swift_closure_destructor.36Tm
+ _symbolic _____Sg 7ToolKit12TypeInstanceO
CStrings:
+ "#AutoSendUtilities homeAccessory with no speech packages on companion, allowing auto-send"
+ "#AutoSendUtilities skipping CAM analysis on homeAccessory"
+ "#SendDraftMessageIntentExecutor homeAccessory auto-confirm: skipping confirmation snippet"
+ "#SendDraftMessageIntentExecutor skipping sent tone: CarPlay Send button plays it"
+ "#SendDraftMessageTool homeAccessory: no conversation on the sent message, returning it unchanged"
+ "#SendDraftMessageTool homeAccessory: returning the conversation so the response opens the thread"
+ "#SendMessageReactionTool failed to convert the reaction for %{public}s: %@"
+ "#SendMessageReactionTool failed to find the parameter types of %{public}s"
+ "#TextMessageComponentEntity checking for high quality assets on current device : %{bool}d"
+ "#UnsendLastMessageSentWithSiriTool skipping confirmation on %s"
- "#SendMessageReactionTool failed to get reference to the input parameter TypedValues"
```
