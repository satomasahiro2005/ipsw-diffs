## FlowToolsSnippetService

> `/System/Library/PrivateFrameworks/FlowToolsSnippetService.framework/FlowToolsSnippetService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11b520` | `0x11e240` | **`+0x2d20`** |
| `__TEXT.__oslogstring` | `0x7356` | `0x74b6` | **`+0x160`** |
| `__TEXT.__cstring` | `0x23dd` | `0x248d` | **`+0xb0`** |
| `__AUTH_CONST.__auth_got` | `0x1d40` | `0x1db8` | **`+0x78`** |
| `__AUTH_CONST.__const` | `0xb778` | `0xb7f0` | **`+0x78`** |
| `__TEXT.__const` | `0xe4e6` | `0xe546` | **`+0x60`** |
| `__DATA.__data` | `0xf60` | `0xfa0` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x3852` | `0x3888` | **`+0x36`** |
| `__DATA.__bss` | `0x10220` | `0x10250` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x1c6c` | `0x1c9c` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x17b6` | `0x17d6` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x2ca8` | `0x2cc0` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x7ce0` | `0x7cd0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x4638` | `0x4648` | **`+0x10`** |

### Other Changes

```diff

-3605.25.1.1.1
+3605.30.2.0.0

+  - /usr/lib/swift/libswift_StringProcessing.dylib

-  Functions: 7663
-  Symbols:   358
-  CStrings:  563
+  Functions: 7712
+  Symbols:   359
+  CStrings:  570
Symbols:
+ _OBJC_CLASS_$__SFPBCardSection
CStrings:
+ "<key_entity\\b[^>]*?\\bid=\"([^\"]*)\"[^>]*?/?>"
+ "CommonErrors#CheckNetworkConnection"
+ "OmniSearch.SearchResultFileEntity"
+ "StreamingHandler: enrichUpdate dropping key_entity members with no sidecar data droppedCount=%{public}ld memberCount=%{public}ld dropped=%{sensitive}s"
+ "StreamingHandler: enrichUpdate split composite key_entity tag into %{public}ld tags"
+ "StreamingHandler: enrichUpdate wrapped directly encoded SFCard for entity tag=%{sensitive}s"
+ "handoffInstanceIdentifier"
```
