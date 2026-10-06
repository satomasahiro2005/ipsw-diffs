## Sentry

> `/System/Library/PrivateFrameworks/Sentry.framework/Sentry`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10430` | `0xffa8` | **`-0x488`** |
| `__TEXT.__oslogstring` | `0x1f8c` | `0x1d9e` | **`-0x1ee`** |
| `__TEXT.__gcc_except_tab` | `0x344` | `0x394` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x1220` | `0x1240` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xa58` | `0xa70` | **`+0x18`** |
| `__TEXT.__const` | `0x104` | `0xec` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x490` | `0x478` | **`-0x18`** |
| `__TEXT.__cstring` | `0x14c9` | `0x14cc` | **`+0x3`** |

### Other Changes

```diff

-9.0.0.0.0
+10.0.0.0.0

-  Functions: 462
-  Symbols:   894
-  CStrings:  306
+  Functions: 456
+  Symbols:   893
+  CStrings:  302
Symbols:
+ -[STYSpecialAppLaunchSignpostMonitorHelper isForegroundLaunchInterval:]
- -[STYSpecialAppLaunchSignpostMonitorHelper handleIntervalBegin:]
- _OUTLINED_FUNCTION_18
CStrings:
+ "Failed to post PerfHUD launch notification for %@: %@"
+ "Posted PerfHUD launch notification for %@ (duration: %lldms)"
+ "ms"
- "Created PerfHUD stream line %llu for app launch"
- "Ended PerfHUD stream line %llu for app launch: %@ (duration: %.2fms)"
- "Ending PerfHUD stream line for ApplicationFirstFramePresentation signpostName=%@ process=%@ subsystem=%@ category=%@ signpostID=%llu duration=%.2fms"
- "Failed to create PerfHUD stream line for app launch: %@"
- "Failed to end PerfHUD stream line %llu: %@"
- "No PerfHUD content found for line %llu - line may have timed out or was never created (process=%@, signpostID=%llu)"
- "Received app launch begin for signpostName=%@ process=%@ subsystem=%@ category=%@ signpostID=%llu timestamp=%llu isSynthetic=%d"
```
