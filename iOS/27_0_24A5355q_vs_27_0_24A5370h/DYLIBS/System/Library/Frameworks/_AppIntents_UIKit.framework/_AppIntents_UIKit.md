## _AppIntents_UIKit

> `/System/Library/Frameworks/_AppIntents_UIKit.framework/_AppIntents_UIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a7b0` | `0x2bd4c` | **`+0x159c`** |
| `__TEXT.__oslogstring` | `0x7ed` | `0x8f7` | **`+0x10a`** |
| `__TEXT.__cstring` | `0x371` | `0x3f1` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x14e0` | `0x1530` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0xda0` | `0xde0` | **`+0x40`** |
| `__DATA.__data` | `0x818` | `0x848` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x1528` | `0x1558` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x738` | `0x758` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xba6` | `0xbc6` | **`+0x20`** |
| `__TEXT.__const` | `0x1540` | `0x1550` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xd30` | `0xd38` | **`+0x8`** |

### Other Changes

```diff

-301.0.41.16.106
+301.0.42.7.0

-  Functions: 1250
-  Symbols:   659
-  CStrings:  59
+  Functions: 1270
+  Symbols:   667
+  CStrings:  66
Symbols:
+ _OUTLINED_FUNCTION_93
+ ___swift_closure_destructor.38Tm
+ __swift_stdlib_bridgeErrorToNSError
+ _objc_retain_x25
+ _objc_retain_x28
+ _swift_isEscapingClosureAtFileLocation
+ _swift_task_getMainExecutor
+ _swift_task_isCurrentExecutor
+ _symbolic ______p 10AppIntents28TargetContentProvidingIntentP
+ _symbolic yt______pIgrzo_ s5ErrorP
- ___swift_closure_destructor.37Tm
- _swift_retain_x10
CStrings:
+ "Incorrect actor executor assumption; Expected same executor as "
+ "[Scene:%{public}s] Could not access scene"
+ "[Scene:%{public}s] capturing scene %{public}@ in didFailHandling"
+ "[Scene:%{public}s] capturing scene %{public}@ in didFinishHandling"
+ "[Scene:%{public}s] delegate not invoked, but no scene captured"
+ "[Scene:%{public}s] didFinishHandling for %@"
+ "[Scene:%{public}s] unable to obtain state"
+ "_AppIntents_UIKit/AppIntentSceneDelegate.swift"
+ "didFailHandling %@: %@"
+ "invokeSceneDelegate %@"
- "[Scene:%{public}s] could not find context"
- "[Scene:%{public}s] didFinishHandling for %s"
- "[Scene:%{public}s] resuming due to BSActionResponse error: %s"
```
