## SiriMessagesFlowTools

> `/System/Library/PrivateFrameworks/SiriMessagesFlowTools.framework/SiriMessagesFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0xd6b0` | `0xb4b0` | **`-0x2200`** |
| `__DATA_DIRTY.__bss` | `0x880` | `0x2a00` | **`+0x2180`** |
| `__DATA_DIRTY.__data` | `0x390` | `0x19c0` | **`+0x1630`** |
| `__AUTH.__data` | `0x19d8` | `0xec8` | **`-0xb10`** |
| `__DATA.__data` | `0x2478` | `0x19b8` | **`-0xac0`** |
| `__TEXT.__text` | `0x1054d0` | `0x104e18` | **`-0x6b8`** |
| `__TEXT.__eh_frame` | `0x8598` | `0x82f0` | **`-0x2a8`** |
| `__AUTH_CONST.__const` | `0x47d8` | `0x46d0` | **`-0x108`** |
| `__TEXT.__const` | `0xa874` | `0xa784` | **`-0xf0`** |
| `__DATA.__common` | `0x288` | `0x1c8` | **`-0xc0`** |
| `__DATA_DIRTY.__common` | `—` | `0xc0` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x7941` | `0x7a01` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x150` | `0x98` | **`-0xb8`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0xb8` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0x37c8` | `0x3720` | **`-0xa8`** |
| `__DATA_CONST.__got` | `0x1020` | `0xf98` | **`-0x88`** |
| `__TEXT.__cstring` | `0x1c64` | `0x1cb4` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x72c` | `0x6ec` | **`-0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x20d8` | `0x20b0` | **`-0x28`** |
| `__TEXT.__swift_as_cont` | `0x668` | `0x640` | **`-0x28`** |
| `__TEXT.__constg_swiftt` | `0x1a58` | `0x1a3c` | **`-0x1c`** |
| `__TEXT.__swift_as_ret` | `0x3f4` | `0x3d8` | **`-0x1c`** |
| `__TEXT.__swift5_typeref` | `0x34e6` | `0x34da` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1fa8` | `0x1fb0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x784` | `0x780` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x248` | `0x244` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-3600.47.5.0.0
+3600.47.9.0.0

-  Functions: 5336
-  Symbols:   1971
-  CStrings:  591
+  Functions: 5285
+  Symbols:   1965
+  CStrings:  596
Symbols:
- ___swift_memcpy8_8
- _get_enum_tag_for_layout_string 21SiriMessagesFlowTools27MessageEntityHydrationErrorO
- _get_type_metadata 15Synchronization5MutexVy21SiriMessagesFlowTools23TimedSentMessageContextVSgG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic _____ 21SiriMessagesFlowTools27MessageEntityHydrationErrorO
- _type_layout_string 21SiriMessagesFlowTools27MessageEntityHydrationErrorO
CStrings:
+ "#EditLastMessageSentWithSiriTool routing decision: %{public}s"
+ "#EditLastMessageSentWithSiriTool: hydration failed for non-attributed entity; falling back to cached identifier: %{public}s"
+ "#SendDraftMessageTool using recipients from draft for snippet"
+ "#TimedSentMessageContext bundleIdentifier: empty entityIdentifierValues"
+ "#TimedSentMessageContext typeName: empty entityIdentifierValues"
+ "#TimedSentMessageContext typeName: unhandled TypeIdentifier case=%{public}s"
+ "#UnsendLastMessageSentWithSiriTool execute: cache miss — no sent message context available"
+ "#UnsendLastMessageSentWithSiriTool routing decision: %{public}s"
+ "#UnsendLastMessageSentWithSiriTool searching for tools by schema for app=%{public}s"
+ "#UnsendLastMessageSentWithSiriTool unsupported service: %s"
+ "#UnsendLastMessageSentWithSiriTool: hydration failed for non-attributed entity; proceeding with cached entity reference only: %{public}s"
+ ".attributed(containerId="
+ ".custom(bundleIdentifier="
+ "MESSAGESFLOWTOOL_UNSEND_UNSUPPORTED_ON_SERVICE"
+ "You can’t unsend messages sent using SMS or RCS."
+ "invokeAppIntentForEntity(entity:toolDefinition:callback:skipConfirmation:)"
- "#EditLastMessageSentWithSiriTool %s: Failed to hydrate conversation entity: %s"
- "#MessageEntity hydration failed: Could not find conversation type"
- "#MessageEntity hydration failed: Could not find message type"
- "#SendDraftMessageTool skipping hydration of conversation entity -- using recipients from draft due to latency"
- "#TTSUtil isAvailable for '%s': matchedBaseLanguage=%{bool}d, hasAnyKeyboardForLanguage=%{bool}d"
- "#TimedSentMessageContext: Could not extract type from entityIdentifierValues: %{private}s"
- "#UnsendLastMessageSentWithSiriTool searching for tools by schema for app %s"
- "#UnsendLastMessageSentWithSiriTool: Failed to hydrate entity for snippet: %s"
- "MessageEntity: Failed to hydrate conversation entity - %@"
- "hydrateMessageEntity(sentMessageContext:callback:)"
- "invokeAppIntentForEntity(entity:toolDefinition:bundleIdentifier:typeName:callback:skipConfirmation:)"
```
