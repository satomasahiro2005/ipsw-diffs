## SiriMessagesFlowTools

> `/System/Library/PrivateFrameworks/SiriMessagesFlowTools.framework/SiriMessagesFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x121e40` | `0x122d94` | **`+0xf54`** |
| `__DATA.__bss` | `0xba50` | `0xb650` | **`-0x400`** |
| `__DATA_DIRTY.__bss` | `0x2a00` | `0x2e00` | **`+0x400`** |
| `__TEXT.__cstring` | `0x2034` | `0x20b4` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x8351` | `0x83a1` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x9610` | `0x9658` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x4928` | `0x4950` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x3d38` | `0x3d58` | **`+0x20`** |
| `__DATA.__data` | `0x1b08` | `0x1af8` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x1038` | `0x1028` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x19c0` | `0x19d0` | **`+0x10`** |
| `__TEXT.__const` | `0xaf54` | `0xaf64` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x6f8` | `0x708` | **`+0x10`** |

### Other Changes

```diff

-3605.15.1.0.0
+3605.17.1.1.1

-  Functions: 5719
+  Functions: 5728

-  CStrings:  639
+  CStrings:  640
CStrings:
+ "#UnsendLastMessageSentWithSiriTool %s: received a result other than .confirmed from callback.showActionConfirmation. Flow tool should never reach this point."
+ "invokeAppIntent(entities:hydratedTypedValue:toolDefinition:bundleIdentifier:typeName:callback:skipConfirmation:)"
- "#UnsendLastMessageSentWithSiriTool user cancelled unsend confirmation"
```
