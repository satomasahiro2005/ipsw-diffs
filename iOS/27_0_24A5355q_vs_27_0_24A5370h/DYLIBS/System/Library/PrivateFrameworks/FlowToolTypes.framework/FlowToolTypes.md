## FlowToolTypes

> `/System/Library/PrivateFrameworks/FlowToolTypes.framework/FlowToolTypes`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd4dd8` | `0xda358` | **`+0x5580`** |
| `__DATA.__bss` | `0x1df88` | `0x1f8c8` | **`+0x1940`** |
| `__TEXT.__const` | `0x131b8` | `0x13d88` | **`+0xbd0`** |
| `__AUTH_CONST.__const` | `0x81d0` | `0x8610` | **`+0x440`** |
| `__TEXT.__eh_frame` | `0x8700` | `0x89b8` | **`+0x2b8`** |
| `__TEXT.__unwind_info` | `0x4ae0` | `0x4d78` | **`+0x298`** |
| `__TEXT.__swift5_typeref` | `0x3f14` | `0x411e` | **`+0x20a`** |
| `__TEXT.__swift5_fieldmd` | `0x3588` | `0x375c` | **`+0x1d4`** |
| `__TEXT.__constg_swiftt` | `0x32c4` | `0x3474` | **`+0x1b0`** |
| `__DATA.__data` | `0x1c38` | `0x1d60` | **`+0x128`** |
| `__AUTH.__data` | `0xcb8` | `0xdc8` | **`+0x110`** |
| `__TEXT.__swift5_reflstr` | `0x2295` | `0x23a5` | **`+0x110`** |
| `__TEXT.__cstring` | `0x3616` | `0x3706` | **`+0xf0`** |
| `__TEXT.__swift5_proto` | `0x11a4` | `0x1264` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x143d` | `0x13ad` | **`-0x90`** |
| `__TEXT.__swift5_types` | `0x438` | `0x468` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xed8` | `0xef0` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x1960` | `0x1968` | **`+0x8`** |

### Other Changes

```diff

-3600.59.31.1.2
+3600.65.8.0.0

-  Functions: 7518
-  Symbols:   332
-  CStrings:  470
+  Functions: 7774
+  Symbols:   331
+  CStrings:  476
Symbols:
- _swift_retain_x28
CStrings:
+ " ... with filter %s"
+ "#ToolStoring %s default implementation: This method is deprecated. Please use tools(implementing:from:filter:) instead."
+ "%s: Returning %ld tools: %s"
+ ",\n    remoteExecutionContext: "
+ "devicePreference"
+ "prefersCompanion"
+ "remoteExecutionContext"
+ "suggestedIntermediateResult"
+ "tools(implementing:from:filter:)"
+ "waitUntilRendered"
- "#ToolStoring %s default implementation: This method is deprecated. Please use tools(implementing:from:) instead."
- "%s: Companion tool execution not allowed. Returning empty set."
- "%s: Did not find any tool definitions for client device. Returning %ld local tools."
- "%s: Returning %ld client tools: %s"
```
