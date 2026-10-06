## SiriRequestDispatcher

> `/System/Library/PrivateFrameworks/SiriRequestDispatcher.framework/SiriRequestDispatcher`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d18c` | `0x2f308` | **`+0x217c`** |
| `__AUTH_CONST.__const` | `0x20d0` | `0x23c8` | **`+0x2f8`** |
| `__TEXT.__swift5_capture` | `0x580` | `0x6b4` | **`+0x134`** |
| `__AUTH_CONST.__objc_const` | `0x4150` | `0x4220` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x24e7` | `0x25b7` | **`+0xd0`** |
| `__AUTH.__data` | `0x28` | `0xe0` | **`+0xb8`** |
| `__TEXT.__cstring` | `0x7c5` | `0x839` | **`+0x74`** |
| `__TEXT.__unwind_info` | `0xc30` | `0xc98` | **`+0x68`** |
| `__TEXT.__constg_swiftt` | `0x10c4` | `0x111c` | **`+0x58`** |
| `__AUTH.__objc_data` | `0xb0` | `0x100` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x908` | `0x958` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x82c` | `0x878` | **`+0x4c`** |
| `__AUTH_CONST.__auth_got` | `0xb40` | `0xb78` | **`+0x38`** |
| `__TEXT.__const` | `0x1c30` | `0x1c60` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0xb28` | `0xb48` | **`+0x20`** |
| `__DATA.__data` | `0x6b0` | `0x6c8` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0xca3` | `0xcb9` | **`+0x16`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x48` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xb0` | `0xb4` | **`+0x4`** |

### Other Changes

```diff

-3605.18.1.0.0
+3605.19.1.0.0

-  Functions: 1492
-  Symbols:   708
-  CStrings:  184
+  Functions: 1556
+  Symbols:   717
+  CStrings:  189
Symbols:
+ __DATA__TtC21SiriRequestDispatcher27RequestProcessorHandoffGate
+ __IVARS__TtC21SiriRequestDispatcher27RequestProcessorHandoffGate
+ __METACLASS_DATA__TtC21SiriRequestDispatcher27RequestProcessorHandoffGate
+ _dispatch_resume
+ _dispatch_suspend
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
+ _symbolic Say_____G 21SiriRequestDispatcher0B13ProcessorBaseC
+ _symbolic _____ 21SiriRequestDispatcher0B20ProcessorHandoffGateC
+ _symbolic _____ 8Dispatch0A8WorkItemC
CStrings:
+ "Holding request %{public}s while outgoing request %{public}s finishes"
+ "Message %{public}s is not registered by any handler"
+ "No RequestProcessor claimed message: %{public}s with requestId: %{public}s. Offered to %{public}ld. Dropping it."
+ "Not holding request %{public}s: it is already the outgoing processor, so there is nothing to wait for"
+ "Previous processor for requestId: %{public}s is still active; holding request %{public}s until it finishes"
+ "Request %{public}s did not finish processing pending messages in time, starting request %{public}s anyway"
+ "Resuming %{public}s: %{public}s"
+ "outgoing request drained"
+ "outgoing request timed out"
+ "siriDeviceRoutingMessageCenterTransport"
- "Previous processor for requestId: %s didn't finish processing all pending messages, creating a new processor"
- "Previous processor for requestId: %s finished processing all pending messages"
- "Timed out waiting for ActiveRequestProcessor with requestId: %s to finish processing."
- "We still have previous processor checking waiting for it to finish"
- "Will wait up to %s for the current active request to finish"
```
