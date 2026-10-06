## SiriMessagesFlowTools

> `/System/Library/PrivateFrameworks/SiriMessagesFlowTools.framework/SiriMessagesFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x104e18` | `0x1091f0` | **`+0x43d8`** |
| `__TEXT.__eh_frame` | `0x82f0` | `0x8690` | **`+0x3a0`** |
| `__TEXT.__oslogstring` | `0x7a01` | `0x7bc1` | **`+0x1c0`** |
| `__TEXT.__const` | `0xa784` | `0xa854` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x3720` | `0x37e8` | **`+0xc8`** |
| `__TEXT.__cstring` | `0x1cb4` | `0x1d74` | **`+0xc0`** |
| `__AUTH_CONST.__auth_got` | `0x1fb0` | `0x2048` | **`+0x98`** |
| `__DATA.__bss` | `0xb4b0` | `0xb530` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x1dc8` | `0x1e28` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x34da` | `0x351c` | **`+0x42`** |
| `__AUTH_CONST.__objc_const` | `0x14c0` | `0x1500` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xf98` | `0xfd8` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x20b0` | `0x20f0` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x640` | `0x66c` | **`+0x2c`** |
| `__AUTH_CONST.__const` | `0x46d0` | `0x46f0` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x1a3c` | `0x1a58` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0xcf0` | `0xd08` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x3d8` | `0x3ec` | **`+0x14`** |
| `__DATA_DIRTY.__data` | `0x19c0` | `0x19d0` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x330` | `0x33c` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x6d8` | `0x6e0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x780` | `0x784` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x244` | `0x248` | **`+0x4`** |

### Other Changes

```diff

-3600.47.9.0.0
+3600.47.13.0.0

-  Functions: 5285
-  Symbols:   1965
-  CStrings:  596
+  Functions: 5353
+  Symbols:   1971
+  CStrings:  606
Symbols:
+ _symbolic _____ 21SiriMessagesFlowTools24NetworkStatusProviderKeyO
+ _symbolic _____Sg 13FlowToolTypes0aB17InvocationContextV11InputOriginO
+ _symbolic _____Sg_ABt 13FlowToolTypes0aB17InvocationContextV11InputOriginO
+ _symbolic ______p 22SiriMessagesFlowCommon22NetworkStatusProvidingP
+ _symbolic _____m 21SiriMessagesFlowTools24NetworkStatusProviderKeyO
+ _symbolic _____y_____G 13FlowToolTypes0aB22ExecutorCallbackResultV AA0ab12IntermediateF8ResponseO
+ _symbolic _____y_____GSg 13FlowToolTypes0aB22ExecutorCallbackResultV AA0ab12IntermediateF8ResponseO
+ _symbolic _____y______pG 13FlowToolTypes0aB16EnvironmentValueC 012SiriMessagesA6Common22NetworkStatusProvidingP
- _symbolic Say_____G 21SiriMessagesFlowTools020ReadableConversationC10ToolEntityV
- _symbolic _____Sg_ABt 16SiriDialogEngine15SpeakableStringV
CStrings:
+ "#AskForAudioMessagePrompt resolve failed: %@. Falling back to default prompt."
+ "#CreateDraftMessageTool airplane mode is on, aborting"
+ "#CreateDraftMessageTool device is offline, aborting"
+ "#EditAskForPayloadPrompt resolve yielded no dialog from EditMessage#AskForPayload."
+ "#PrepareToReadMessagesTool Read introduction"
+ "#ReadingIntroductionDialog CAT generation failed: %@"
+ "#SendDraftMessageTool airplane mode is on, aborting"
+ "#SendDraftMessageTool device is offline, aborting"
+ "Audio messages can’t be sent on Mac."
+ "I can help with that if you turn off Airplane Mode."
+ "I can’t send messages while this device is offline."
+ "I couldn’t complete the action."
+ "I couldn’t find any messages."
+ "I couldn’t find that message."
+ "I couldn’t find the reaction."
+ "I couldn’t load the localized text."
+ "MESSAGESFLOWTOOL_AIRPLANE_MODE_IS_ON"
+ "MESSAGESFLOWTOOL_DEVICE_IS_OFFLINE"
+ "askUserForContentFollowUp(sentMessageContext:context:callback:)"
- "#PrepareToReadConversationTool Returning %ld conversations and %ld total messages."
- "Audio messages can't be sent on Mac."
- "I couldn't complete the action."
- "I couldn't find any messages."
- "I couldn't find that message."
- "I couldn't find the reaction."
- "I couldn't load the localized text."
- "What do you want to say instead?"
- "askUserForContentFollowUp(sentMessageContext:callback:)"
```
