## com.apple.driver.AppleProcessorTrace

> `com.apple.driver.AppleProcessorTrace`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x3c314` | `0x3c5a0` | **`+0x28c`** |
| `__DATA_CONST.__const` | `0xb188` | `0xb1c8` | **`+0x40`** |
| `__TEXT.__cstring` | `0x5981` | `0x59a7` | **`+0x26`** |
| `__TEXT.__os_log` | `0x19a2` | `0x1993` | **`-0xf`** |
| `__DATA_CONST.__got` | `0xb0` | `0xb8` | **`+0x8`** |

### Other Changes

```diff

-130.0.0.0.0
-  Functions: 1314
+130.40.6.0.0
+  Functions: 1317

-  CStrings:  519
+  CStrings:  522
CStrings:
+ "%s: resume tracing"
+ "%s: state=%d"
+ "AppleProcessorTrace::enterSleep\n"
+ "AppleProcessorTrace::enterWake\n"
+ "expectState(DriverState::Sleeping)"
+ "setState"
+ "startTracingOnClustersGated"
+ "void AppleProcessorTrace::enterSleep()"
+ "void AppleProcessorTrace::enterWake()"
+ "void AppleProcessorTrace::stopTracingOnClustersGated(ChunkQueueTarget)"
- "AppleProcessorTrace::hibernationSleep\n"
- "AppleProcessorTrace::hibernationWake\n"
- "AppleProcessorTrace::setState(%d)\n"
- "expectState(DriverState::Hibernating)"
- "void AppleProcessorTrace::hibernationSleep()"
- "void AppleProcessorTrace::hibernationWake()"
- "void AppleProcessorTrace::stopTracingOnClustersGated()"
```
