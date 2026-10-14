## SiriMessagesFlow

> `/System/Library/PrivateFrameworks/SiriMessagesFlow.framework/SiriMessagesFlow`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39af5c` | `0x39bc54` | **`+0xcf8`** |
| `__AUTH_CONST.__const` | `0x15351` | `0x14ba9` | **`-0x7a8`** |
| `__TEXT.__eh_frame` | `0x25328` | `0x258d0` | **`+0x5a8`** |
| `__TEXT.__unwind_info` | `0xc6f8` | `0xcc28` | **`+0x530`** |
| `__TEXT.__oslogstring` | `0x2646f` | `0x2678f` | **`+0x320`** |
| `__TEXT.__swift5_capture` | `0x4918` | `0x4608` | **`-0x310`** |
| `__AUTH_CONST.__auth_got` | `0x4848` | `0x48c0` | **`+0x78`** |
| `__TEXT.__const` | `0x14804` | `0x14874` | **`+0x70`** |
| `__TEXT.__swift_as_cont` | `0x1e98` | `0x1edc` | **`+0x44`** |
| `__TEXT.__swift_as_ret` | `0x1620` | `0x1648` | **`+0x28`** |
| `__DATA.__data` | `0x4b70` | `0x4b80` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x15f0` | `0x15f8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x6ba1` | `0x6ba9` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x10cc` | `0x10d0` | **`+0x4`** |

### Other Changes

```diff

-3605.20.1.0.0
+3605.21.1.11.2

+  - /System/Library/Frameworks/AppIntents.framework/AppIntents

-  Functions: 18385
-  Symbols:   3868
-  CStrings:  3097
+  Functions: 18414
+  Symbols:   3874
+  CStrings:  3107
Symbols:
+ _OBJC_CLASS_$_SAUIHideSiriOverlay
+ _OUTLINED_FUNCTION_657
+ _OUTLINED_FUNCTION_658
+ _OUTLINED_FUNCTION_659
+ _OUTLINED_FUNCTION_660
+ ___swift_closure_destructor.41Tm
+ _symbolic _____Sg 10AppIntents12IntentPersonV
+ _symbolic _____Sg 18AppIntentsServices0A20IntentPerformOptionsV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10AppIntents12IntentPersonV
- ___swift_closure_destructor.39Tm
- ___swift_closure_destructor.64Tm
- _symbolic SaySo8INPersonCGIegr_
CStrings:
+ "#SearchForMessagesFlow executeAppIntent on conversation: %s"
+ "#SearchForMessagesFlow failed %@"
+ "#SendMessageBaseFlowStrategy: appended SAUIHideSiriOverlay to manifest"
+ "#SendMessageBaseFlowStrategy: set additionalCommands to SAUIHideSiriOverlay"
+ "#SendMessageConfirmIntentFlowStrategy completed app intent"
+ "#SendMessageConfirmIntentFlowStrategy performing open conversation app intent"
+ "#SendMessageConfirmIntentFlowStrategy returning output for home with identifier for persons : %s"
+ "#SendMessageConfirmIntentFlowStrategy: Error while awaiting final value from execution: %@"
+ "#SendMessageConfirmIntentFlowStrategy: awaiting final value from execution"
+ "SendSupportCheck# Unsupported request because screenshots are not allowed on this device"
```
