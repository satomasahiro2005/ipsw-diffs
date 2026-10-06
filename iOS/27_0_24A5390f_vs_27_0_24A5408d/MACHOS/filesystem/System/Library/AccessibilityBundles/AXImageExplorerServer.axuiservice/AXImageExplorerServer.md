## AXImageExplorerServer

> `/System/Library/AccessibilityBundles/AXImageExplorerServer.axuiservice/AXImageExplorerServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53fe8` | `0x538f8` | **`-0x6f0`** |
| `__TEXT.__swift5_typeref` | `0x72da` | `0x6c12` | **`-0x6c8`** |
| `__TEXT.__eh_frame` | `0x2654` | `0x23fc` | **`-0x258`** |
| `__TEXT.__cstring` | `0x110b` | `0x128b` | **`+0x180`** |
| `__TEXT.__const` | `0x2974` | `0x2804` | **`-0x170`** |
| `__TEXT.__oslogstring` | `0x1249` | `0x1399` | **`+0x150`** |
| `__TEXT.__auth_stubs` | `0x2950` | `0x2a40` | **`+0xf0`** |
| `__DATA_CONST.__const` | `0x12b0` | `0x11f0` | **`-0xc0`** |
| `__TEXT.__objc_methname` | `0x13c1` | `0x1481` | **`+0xc0`** |
| `__DATA.__bss` | `0x1b78` | `0x1ae8` | **`-0x90`** |
| `__DATA.__data` | `0x1ea0` | `0x1e20` | **`-0x80`** |
| `__DATA_CONST.__auth_got` | `0x14b0` | `0x1528` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x1258` | `0x11e0` | **`-0x78`** |
| `__TEXT.__swift5_reflstr` | `0x637` | `0x6a7` | **`+0x70`** |
| `__DATA.__objc_const` | `0x9c0` | `0xa20` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0xb40` | `0xba0` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x90c` | `0x8c8` | **`-0x44`** |
| `__TEXT.__swift5_capture` | `0x460` | `0x41c` | **`-0x44`** |
| `__DATA_CONST.__got` | `0x998` | `0x9c8` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x5a8` | `0x5d4` | **`+0x2c`** |
| `__TEXT.__swift_as_cont` | `0x1d4` | `0x1b0` | **`-0x24`** |
| `__DATA.__objc_data` | `0x328` | `0x340` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x4d0` | `0x4e8` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x270` | `0x258` | **`-0x18`** |
| `__TEXT.__swift_as_ret` | `0xcc` | `0xb4` | **`-0x18`** |
| `__TEXT.__swift_as_entry` | `0x94` | `0x88` | **`-0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x7d8` | `0x7e0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xd0` | `0xcc` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x7c` | `0x78` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Functions: 1342
-  Symbols:   260
-  CStrings:  451
+  Functions: 1325
+  Symbols:   259
+  CStrings:  474
Symbols:
+ _AXDateStringForFormatWithTimeZone
+ _AXImageExplorerProcessingHapticEnabled
+ _AXImageExplorerProcessingSoundEnabled
+ _swift_asyncLet_get_throwing
+ _swift_task_future_wait_throwing
- _AXDateStringForFormat
- _AXDeviceSupportsAppleIntelligence
- _AXImageExplorerGetSilentMode
- _swift_asyncLet_get
- _swift_retain_x25
- _swift_retain_x26
CStrings:
+ "$__lazy_storage_$_multimodalGuardrail"
+ "%s cancelled."
+ "%s failed. %@"
+ "%s rejected by an unrecognized safety guardrail. %@"
+ "%s timed out after %ld attempt(s)."
+ "ASK_ABOUT_SCREEN"
+ "Ask about image request"
+ "Fail to prompt Siri request. AXChatProvider is not available."
+ "Failed to ask user prompt. AXChatProvider is not available."
+ "Failed to fetch image description: %s."
+ "Failed to request description. AXChatProvider is not available."
+ "Failed to request description. Creating fallback message for user."
+ "Failed to request description. Image was nil."
+ "Failed to request description. Intelligence is not enabled and vision analysis failed."
+ "INTELLIGENT_IMAGE_DESCRIPTION"
+ "INTELLIGENT_IMAGE_SENSITIVE_CONTENT"
+ "INTELLIGENT_QUESTION_SENSITIVE_CONTENT"
+ "INTELLIGENT_SCREEN_DESCRIPTION"
+ "INTELLIGENT_SCREEN_SENSITIVE_CONTENT"
+ "Ignoring present request; a presentation is already in progress."
+ "Image Explorer description request"
+ "Image Explorer question request"
+ "Intelligent description request"
+ "PARENTAL_RESTRICTION_ALERT_MESSAGE"
+ "PARENTAL_RESTRICTION_ALERT_OK"
+ "PARENTAL_RESTRICTION_ALERT_TITLE"
+ "Rejected by output safety guardrail. %s rejectedContent=%{sensitive}s"
+ "Requested description rejected by output safety guardrail. %@"
+ "Safety rejection due to offensive words - providing content to user."
+ "Service got a message: %ld from client: %s."
+ "Service got async message: %ld from client: %s."
+ "Unknown async message: '%ld' from client: '%s'."
+ "Unknown message: '%ld' from client: '%s'."
+ "_showingRestrictionAlert"
+ "_sourceIsItem"
+ "accessibility.magnifier.reduceSensitiveTopics"
+ "activationState"
+ "displayID"
+ "displayIdentity"
+ "isPresenting"
+ "screen"
- "AFM_FAILED_RESPONSE"
- "AXChatProvider is not available."
- "Failed to ask user prompt. %@"
- "Failed to fetch image description within %ld seconds or due to error."
- "Failed to fetch image description."
- "Failed to fetch model result. %@"
- "Failed to generate image description: empty result."
- "IMAGE_EXPLORER_SENSITIVE_CONTENT"
- "IMAGE_EXPLORER_SENSITIVE_CONTENT_ASK"
- "IMAGE_EXPLORER_SENSITIVE_CONTENT_DESCRIPTION"
- "Service got a message: %ld from client: %s. Payload: %s."
- "Service got async message: %ld from client: %s. Payload: %s."
- "Unknown async message: '%ld' from client: '%s' with payload: '%s'."
- "Unknown message: '%ld' from client: '%s' with payload: '%s'."
- "Will not proceed with presenting Image Explorer. Guardrail evaluation failed: %@"
- "Will not proceed with speak description. Guardrail evaluation failed: %@"
- "multimodalGuardrail"
- "tertiarySystemFillColor"
```
