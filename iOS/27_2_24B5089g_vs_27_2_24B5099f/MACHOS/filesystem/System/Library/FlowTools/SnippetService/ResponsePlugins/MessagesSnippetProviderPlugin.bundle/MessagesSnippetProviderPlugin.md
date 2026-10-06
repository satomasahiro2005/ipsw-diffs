## MessagesSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/MessagesSnippetProviderPlugin.bundle/MessagesSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c36c` | `0x2dfe8` | **`+0x1c7c`** |
| `__TEXT.__eh_frame` | `0x1390` | `0x17d0` | **`+0x440`** |
| `__TEXT.__unwind_info` | `0x788` | `0x850` | **`+0xc8`** |
| `__TEXT.__auth_stubs` | `0x2100` | `0x21c0` | **`+0xc0`** |
| `__DATA_CONST.__auth_got` | `0x1088` | `0x10e8` | **`+0x60`** |
| `__TEXT.__const` | `0xd08` | `0xd48` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0xc8` | `0x104` | **`+0x3c`** |
| `__TEXT.__swift_as_ret` | `0xc0` | `0xdc` | **`+0x1c`** |
| `__TEXT.__cstring` | `0x281` | `0x271` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x1737` | `0x1747` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0xb4` | `0xc4` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x400` | `0x408` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x3b0` | `0x3b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-3605.17.1.1.1
+3605.20.1.0.0

-  Functions: 817
+  Functions: 868
CStrings:
+ "#MessagesReadingSnippetHandler Building chained OfferFullRead"
+ "#MessagesReadingSnippetHandler Building chained OfferReply"
+ "#MessagesReadingSnippetHandler Chained %ld AddViews for silent CarPlay announce follow-up"
+ "#MessagesReadingSnippetHandler Chained pattern produced no AddViews; falling back to read-only output"
+ "#MessagesReadingSnippetHandler Failed to build chained pattern: %@. Falling back to read-only output."
+ "#MessagesSendSnippetHandler %s Unsupported: Skip for non sendDraftMessageFlowTool"
+ "#SystemResponse %s didn't find a single sourceToolId: %s"
+ "#SystemResponse %s sourceTool doesn't match sendDraftMessage or editMessage"
+ "isFromSentMessageTool"
- "#MessagesReadingSnippetHandler Chained %ld OfferReply AddViews for silent CarPlay announce reply prompt"
- "#MessagesReadingSnippetHandler Chained OfferReply produced no AddViews; falling back to read-only output"
- "#MessagesReadingSnippetHandler Failed to build chained OfferReply: %@. Falling back to read-only output."
- "#MessagesSendSnippetHandler %s Didn't find a SendDraftMessageIntent or EditMessageFlowTool"
- "#MessagesSendSnippetHandler %s Didn't find a toolId: %s"
- "#MessagesSendSnippetHandler %s Unsupported: Skip for system response"
- "#MessagesSendSnippetHandler %s responseType: %s"
- "#MessagesSendSnippetHandler %s values: %s"
- "isSentMessageEntityResponse(systemResponse:)"
```
