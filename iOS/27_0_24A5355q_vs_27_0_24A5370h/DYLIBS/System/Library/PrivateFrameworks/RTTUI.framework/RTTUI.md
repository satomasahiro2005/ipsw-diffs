## RTTUI

> `/System/Library/PrivateFrameworks/RTTUI.framework/RTTUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1db70` | `0x1db50` | **`-0x20`** |

### Other Changes

```diff

-527.0.0.0.0
+530.0.0.0.0
Functions:
~ ___91-[RTTUIConversationControllerCoordinator _sendNewUtteranceString:atIndex:forCellPath:call:]_block_invoke : 472 -> 468
~ ___63-[RTTUIConversationControllerCoordinator processUtteranceQueue]_block_invoke.115 -> ___63-[RTTUIConversationControllerCoordinator processUtteranceQueue]_block_invoke.130 : 492 -> 488
~ ___62-[RTTUIConversationControllerCoordinator hearingServerDidDie:]_block_invoke : 316 -> 312
~ ___67-[RTTUIConversationViewController tableView:cellForRowAtIndexPath:]_block_invoke.602 -> ___67-[RTTUIConversationViewController tableView:cellForRowAtIndexPath:]_block_invoke.623 : 360 -> 356
~ +[RTTUIUtilities phoneNumberStringFromString:] : 800 -> 796
~ -[RTTUIUtilities transcriptStringForConversation:] : 936 -> 932
~ -[RTTUITextView _loadTTYAbbreviations] : 860 -> 856
~ sub_293fd1c5c -> sub_2953a7c40 : 280 -> 276
```
