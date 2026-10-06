## DVTInstrumentsFoundation

> `/System/Library/PrivateFrameworks/DVTInstrumentsFoundation.framework/DVTInstrumentsFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe4450` | `0xe3084` | **`-0x13cc`** |
| `__TEXT.__cstring` | `0xf31a` | `0xef4c` | **`-0x3ce`** |
| `__AUTH_CONST.__cfstring` | `0xa1e0` | `0x9e80` | **`-0x360`** |
| `__AUTH_CONST.__objc_const` | `0x123e8` | `0x12330` | **`-0xb8`** |
| `__TEXT.__objc_methlist` | `0x8514` | `0x8484` | **`-0x90`** |
| `__AUTH.__objc_data` | `0x4848` | `0x47f8` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0x62d4` | `0x6284` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x3e58` | `0x3e20` | **`-0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x4250` | `0x4220` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x3520` | `0x34f8` | **`-0x28`** |
| `__TEXT.__const` | `0x3dd0` | `0x3dc2` | **`-0xe`** |
| `__AUTH.__data` | `0x12d0` | `0x12c8` | **`-0x8`** |
| `__AUTH_CONST.__auth_got` | `0x2028` | `0x2020` | **`-0x8`** |
| `__DATA.__data` | `0x2f68` | `0x2f60` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xd50` | `0xd58` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x688` | `0x680` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x3d0` | `0x3c8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xbe4` | `0xbe0` | **`-0x4`** |

### Other Changes

```diff

-64578.141.1.0.0
+64578.145.1.0.0

-  Functions: 4991
-  Symbols:   1881
-  CStrings:  2624
+  Functions: 4964
+  Symbols:   1875
+  CStrings:  2597
Symbols:
- _DTUVRenderingServiceErrorWithDescription
- _DTXSpawn_StderrPathKey
- _DTXSpawn_StdoutPathKey
- _OBJC_CLASS_$_DTUVRenderingService
- _OBJC_METACLASS_$_DTUVRenderingService
- _swift_willThrowTypedImpl
CStrings:
- "\"startCLI\" \"launchPath\" does not exist: %@"
- "\"startCLI\" has already been called and a connection established (%@): %@"
- "\"startCLI\" message payload is not a dictionary: %@"
- "DTUVRenderingService.m"
- "Failed to launch CLI: %@"
- "No \"injectionPath\" or \"launchedPath\" provided for \"connectToPreviewHost\": %@"
- "No \"launchPath\" provided for \"startCLI\": %@"
- "No \"pid\" provided for \"connectToPreviewHost\": %@"
- "No \"serviceCommand\" specified for message: %@"
- "No connection has been established to the CLI yet for \"forwardMessage\". Make sure to pass a \"startCLI\" command first. Message was: %@"
- "Rendering service could not respond"
- "Rendering service produced unknown error"
- "Rendering service was interrupted"
- "Unknown command \"%@\": %@"
- "__SERVICEHUB_ATTACH_POINT__"
- "com.apple.instruments.server.services.ultraviolet.renderer"
- "connectToPreviewHost"
- "connectToPreviewHost: Failed to connect to %d: %@"
- "environment"
- "forwardMessage"
- "inheritEnvironment"
- "injectionPath"
- "launchPath"
- "launchedPath"
- "startCLI"
- "stderrPath"
- "stdoutPath"
```
