## PriMLETL

> `/System/Library/PrivateFrameworks/PriMLETL.framework/PriMLETL`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb96bc` | `0xb85d4` | **`-0x10e8`** |
| `__TEXT.__oslogstring` | `0x1e57` | `0x1d37` | **`-0x120`** |
| `__TEXT.__eh_frame` | `0x61d8` | `0x60d0` | **`-0x108`** |
| `__DATA.__bss` | `0xbc30` | `0xbd30` | **`+0x100`** |
| `__TEXT.__const` | `0x8f28` | `0x8f58` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x27d8` | `0x27c0` | **`-0x18`** |
| `__TEXT.__constg_swiftt` | `0x14b8` | `0x14cc` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x14e8` | `0x14d8` | **`-0x10`** |
| `__AUTH_CONST.__const` | `0x4cd8` | `0x4ce8` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x408` | `0x3f8` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x634` | `0x63c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x200` | `0x1f8` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x19c` | `0x198` | **`-0x4`** |

### Other Changes

```diff

-26.0.0.0.0
+31.0.0.0.0

+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

+  - /System/Library/Frameworks/OSLog.framework/OSLog

+  - /System/Library/Frameworks/SwiftUI.framework/SwiftUI

+  - /System/Library/Frameworks/UniformTypeIdentifiers.framework/UniformTypeIdentifiers

+  - /System/Library/PrivateFrameworks/InternalSwiftProtobuf.framework/InternalSwiftProtobuf
+  - /System/Library/PrivateFrameworks/LighthouseBackground.framework/LighthouseBackground

-  Functions: 2978
+  Functions: 2975

-  CStrings:  316
+  CStrings:  309
CStrings:
+ "failed to parse llm response: %@"
- "Calling LLM with prompt: %s"
- "Completion for item %ld: %s"
- "Generating image(s) for item %ld with prompt: %s"
- "Initialized with parsed prompt template: %s"
- "Multimodal completion for item %ld: %s"
- "chat response with tags %s"
- "failed to parse llm response: %s, error: %@"
- "parsed auto tagger response: %s"
```
