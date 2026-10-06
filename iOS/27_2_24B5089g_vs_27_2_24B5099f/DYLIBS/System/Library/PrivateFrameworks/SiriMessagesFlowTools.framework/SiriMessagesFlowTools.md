## SiriMessagesFlowTools

> `/System/Library/PrivateFrameworks/SiriMessagesFlowTools.framework/SiriMessagesFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x122d94` | `0x125bf4` | **`+0x2e60`** |
| `__TEXT.__oslogstring` | `0x83a1` | `0x85e1` | **`+0x240`** |
| `__TEXT.__eh_frame` | `0x9658` | `0x9730` | **`+0xd8`** |
| `__AUTH_CONST.__const` | `0x4950` | `0x49c8` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x3d58` | `0x3da8` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x21c0` | `0x2200` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x708` | `0x738` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x2048` | `0x2068` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1028` | `0x1040` | **`+0x18`** |
| `__TEXT.__const` | `0xaf64` | `0xaf74` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2328` | `0x2334` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x720` | `0x72c` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x46c` | `0x474` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x374e` | `0x3754` | **`+0x6`** |
| `__TEXT.__swift_as_entry` | `0x378` | `0x37c` | **`+0x4`** |

### Other Changes

```diff

-3605.17.1.1.1
+3605.20.1.0.0

+  - /System/Library/PrivateFrameworks/IntelligenceFlowShared.framework/IntelligenceFlowShared

-  Functions: 5728
-  Symbols:   2024
-  CStrings:  640
+  Functions: 5761
+  Symbols:   2025
+  CStrings:  646
Symbols:
+ _symbolic _____ 7ToolKit10TypedValueO09PrimitiveD0O03AppD0V
CStrings:
+ "#MessagesSchemaTypes no app name resolved for %{public}s; leaving app displayRepresentation unset"
+ "#SendDraftMessageTool failed to resolve the sent dialog, falling back to the static dialog: %@"
+ "#SendDraftMessageTool no dialog resolved from EditMessage#MessageEdited, falling back to the static dialog"
+ "#SendDraftMessageTool not a mid-read reply, using the static sent dialog"
+ "#SendDraftMessageTool replied while reading is in progress, keeping control so reading can resume"
+ "#SendDraftMessageTool user declined the send confirmation"
```
