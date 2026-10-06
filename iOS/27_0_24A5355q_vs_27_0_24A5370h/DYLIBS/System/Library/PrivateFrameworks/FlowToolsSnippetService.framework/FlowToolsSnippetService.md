## FlowToolsSnippetService

> `/System/Library/PrivateFrameworks/FlowToolsSnippetService.framework/FlowToolsSnippetService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd1f80` | `0xd74b8` | **`+0x5538`** |
| `__AUTH_CONST.__const` | `0x7dd8` | `0x8160` | **`+0x388`** |
| `__TEXT.__cstring` | `0x37bf` | `0x397e` | **`+0x1bf`** |
| `__TEXT.__swift5_capture` | `0xac0` | `0xc0c` | **`+0x14c`** |
| `__TEXT.__const` | `0xd0d6` | `0xd1a6` | **`+0xd0`** |
| `__TEXT.__swift5_typeref` | `0x3200` | `0x32b3` | **`+0xb3`** |
| `__TEXT.__unwind_info` | `0x3a08` | `0x3ab0` | **`+0xa8`** |
| `__TEXT.__oslogstring` | `0x305c` | `0x30fc` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x6cdc` | `0x6d5c` | **`+0x80`** |
| `__DATA.__data` | `0x1180` | `0x11f0` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x2648` | `0x2694` | **`+0x4c`** |
| `__AUTH_CONST.__auth_got` | `0x1aa8` | `0x1a60` | **`-0x48`** |
| `__AUTH_CONST.__objc_const` | `0x15e0` | `0x1620` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x338` | `0x378` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x13c7` | `0x1406` | **`+0x3f`** |
| `__TEXT.__swift_as_entry` | `0x31c` | `0x348` | **`+0x2c`** |
| `__DATA_DIRTY.__data` | `0x1b58` | `0x1b80` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x2194` | `0x21b8` | **`+0x24`** |
| `__TEXT.__swift_as_cont` | `0x3a4` | `0x3b8` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x770` | `0x768` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0xb28` | `0xb24` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x34c` | `0x350` | **`+0x4`** |

### Other Changes

```diff

-3600.59.31.1.2
+3600.65.8.0.0

-  - /System/Library/PrivateFrameworks/LinkServices.framework/LinkServices

-  Functions: 6142
-  Symbols:   328
-  CStrings:  501
+  Functions: 6266
+  Symbols:   329
+  CStrings:  510
Symbols:
+ _OBJC_CLASS_$_SAUIAssistantUtteranceView
+ _objc_release_x9
- _OBJC_CLASS_$_LNEnvironment
CStrings:
+ " Found response handler in provider="
+ " Skipping snippet output for voice-only response: "
+ " entity-renderer AddViews into stream chunk commands for CarPlay (top-level dispatch would invalidate the active stream)"
+ "%s Encoded TypedValue metadata sidecar for entity tag: %s (%ld entries)"
+ "%s Surfacing %ld entity-renderer AddViews (utterance views stripped) for CarPlay in-chunk dispatch (entity tag: %s)"
+ "UnrecoverableError#ContextLimitExceeded"
+ "UnrecoverableError#UserDistressEnd"
+ "_typedvalue_metadata"
+ "context(totalItemCount:)"
+ "displayRepresentations"
+ "performPreload()"
+ "responseCommandsFor(systemResponse:inlineEntityRendering:totalItemCount:)"
+ "responseCommandsFor(systemResponse:inlineEntityRendering:totalItemCount:) Adding attribution to commands"
+ "responseFor(systemResponse:inlineEntityRendering:totalItemCount:)"
+ "tryHandler(_:systemResponse:totalItemCount:logName:) Using "
- "Could not set up remote dispatcher: %@"
- "responseCommandsFor(systemResponse:inlineEntityRendering:)"
- "responseCommandsFor(systemResponse:inlineEntityRendering:) Adding attribution to commands"
- "responseFor(systemResponse:inlineEntityRendering:)"
- "supportsAsync(systemResponse:) Found response handler for tools: "
- "tryHandler(_:systemResponse:logName:) Using "
```
