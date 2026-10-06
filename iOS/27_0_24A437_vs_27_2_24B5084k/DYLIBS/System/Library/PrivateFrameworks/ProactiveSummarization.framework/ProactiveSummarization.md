## ProactiveSummarization

> `/System/Library/PrivateFrameworks/ProactiveSummarization.framework/ProactiveSummarization`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x162480` | `0x1634cc` | **`+0x104c`** |
| `__DATA.__bss` | `0x16460` | `0x16160` | **`-0x300`** |
| `__TEXT.__const` | `0x10628` | `0x10458` | **`-0x1d0`** |
| `__TEXT.__oslogstring` | `0x682b` | `0x695b` | **`+0x130`** |
| `__TEXT.__eh_frame` | `0xe850` | `0xe938` | **`+0xe8`** |
| `__TEXT.__cstring` | `0xa0c2` | `0xa152` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x3ee8` | `0x3e62` | **`-0x86`** |
| `__DATA.__data` | `0x1570` | `0x1540` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x10c0` | `0x1090` | **`-0x30`** |
| `__TEXT.__swift5_assocty` | `0x318` | `0x2e8` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0x3084` | `0x3058` | **`-0x2c`** |
| `__AUTH_CONST.__const` | `0xd518` | `0xd4f0` | **`-0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1d98` | `0x1db8` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x3a0` | `0x3c0` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x1400` | `0x1420` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x28e0` | `0x28c0` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x376d` | `0x374d` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x5b10` | `0x5b30` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x393c` | `0x3920` | **`-0x1c`** |
| `__TEXT.__swift5_proto` | `0xb98` | `0xb80` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x12c` | `0x118` | **`-0x14`** |
| `__TEXT.__swift_as_cont` | `0xaa4` | `0xab8` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0xe20` | `0xe30` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x70c` | `0x718` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x4b8` | `0x4b4` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x4dc` | `0x4e0` | **`+0x4`** |

### Other Changes

```diff

-1346.0.1.0.0
+1351.0.0.0.0

-  Functions: 9487
-  Symbols:   3000
-  CStrings:  1246
+  Functions: 9497
+  Symbols:   2986
+  CStrings:  1254
Symbols:
+ _OBJC_CLASS_$_NSKeyedArchiver
+ ___swift_closure_destructor.49Tm
+ _symbolic _____ 12TextComposer0aB6ClientC
- _OBJC_CLASS_$_TCSmartAction
- _TCTextCompositionAssistantDocumentTypeTextMessage
- _TCTextCompositionAssistantResponseAll
- _TCTextCompositionAssistantResponseSmartReply
- ___swift_closure_destructor.48Tm
- _associated conformance So38TCTextCompositionAssistantResponseTypeaSHSCSQ
- _associated conformance So38TCTextCompositionAssistantResponseTypeas20_SwiftNewtypeWrapperSCSY
- _associated conformance So38TCTextCompositionAssistantResponseTypeas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
- _swift_asyncLet_begin
- _swift_asyncLet_finish
- _symbolic So21TCSmartActionFollowUpC_SDySSypGt
- _symbolic So22TCSmartRepliesResponseC_SDySSypGt
- _symbolic _____ 4Sage21TextCompositionClientC
- _symbolic _____ So38TCTextCompositionAssistantResponseTypea
- _symbolic _____y_____G s11_SetStorageC So38TCTextCompositionAssistantResponseTypea
- _symbolic _____y_____G s23_ContiguousArrayStorageC So38TCTextCompositionAssistantResponseTypea
- _type_layout_string So38TCTextCompositionAssistantResponseTypea
CStrings:
+ "Could not create custom attribute keys for Smart Actions response"
+ "Could not write Smart Actions response with error: %@"
+ "Failed to generate message Smart Response: %@; id: %{public}s"
+ "Generated Smart Response for messages; id: %{public}s"
+ "Invoking TextComposer for mail smart responses"
+ "Invoking TextComposer for messages smart responses"
+ "Mail.SmartResponseGeneration"
+ "Message not eligible for Smart Responses (already processed); id: %{public}s"
+ "Wrote Smart Actions response to Spotlight"
+ "com_apple_textcomposer_smartActionsResponse"
+ "com_apple_textcomposer_smartActionsVersion"
+ "maxMessageAgeForSmartResponsesContextRetrieval"
- "Failed to generate message Smart Replies: %@; id: %{public}s"
- "Generated Smart Replies for messages; id: %{public}s"
- "Mail.SmartReplyGeneration"
- "Message not eligible for Smart Replies (already processed); id: %{public}s"
```
