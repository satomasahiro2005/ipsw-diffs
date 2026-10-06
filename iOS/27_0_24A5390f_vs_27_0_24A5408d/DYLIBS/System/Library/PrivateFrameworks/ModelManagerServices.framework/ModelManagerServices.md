## ModelManagerServices

> `/System/Library/PrivateFrameworks/ModelManagerServices.framework/ModelManagerServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x158b30` | `0x15a418` | **`+0x18e8`** |
| `__TEXT.__unwind_info` | `0x7f88` | `0x8170` | **`+0x1e8`** |
| `__AUTH_CONST.__const` | `0xcfa8` | `0xd0e8` | **`+0x140`** |
| `__TEXT.__eh_frame` | `0x11ba0` | `0x11c68` | **`+0xc8`** |
| `__TEXT.__oslogstring` | `0x1c5b` | `0x1d0b` | **`+0xb0`** |
| `__TEXT.__swift5_capture` | `0xfdc` | `0x1064` | **`+0x88`** |
| `__TEXT.__const` | `0x1b468` | `0x1b478` | **`+0x10`** |

### Other Changes

```diff

-703.0.21.502.1
+703.0.33.0.0

-  Functions: 11600
-  Symbols:   3175
+  Functions: 11610
+  Symbols:   3171
Symbols:
+ ___swift_closure_destructor.154Tm
- _OUTLINED_FUNCTION_378
- _OUTLINED_FUNCTION_379
- _OUTLINED_FUNCTION_380
- _OUTLINED_FUNCTION_381
- _OUTLINED_FUNCTION_382
CStrings:
+ "Consuming buffered results for stream %s, subrequest %u"
+ "Created input stream request %s, subrequest %u with configuration %s"
+ "Error occurred when invalidating RunningBoard assertion for request %s subrequest %u: %@"
+ "First request for an input sequence did not return an iterator: %s subrequest %u"
+ "Invalidating direct InferenceProvider connection for request %s subrequest %u."
+ "No endpoint returned for a successful stream request: %s subrequest %u"
+ "Received endOfStream request for %s, subrequest %u"
+ "Requesting first result in stream %s, subrequest %u"
+ "Task for executeInputStreamRequest %s subrequest %u cancelled before sending"
- "Consuming buffered results for stream %s"
- "Created input stream request %s with configuration %s"
- "Error occurred when invalidating RunningBoard assertion: %@"
- "First request for an input sequence did not return an iterator"
- "Invalidating direct InferenceProvider connection."
- "No endpoint returned for a successful stream request"
- "Received endOfStream request for %s"
- "Requesting first result in stream %s"
- "Task for executeInputStreamRequest %s cancelled before sending"
```
