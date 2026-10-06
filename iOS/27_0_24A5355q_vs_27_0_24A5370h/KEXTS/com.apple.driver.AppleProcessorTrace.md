## com.apple.driver.AppleProcessorTrace

> `com.apple.driver.AppleProcessorTrace`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x780` | **`+0x780`** |
| `__TEXT_EXEC.__text` | `0x33ca4` | `0x338e4` | **`-0x3c0`** |
| `__DATA_CONST.__const` | `0x9cf0` | `0x9d90` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x5403` | `0x548e` | **`+0x8b`** |
| `__TEXT.__os_log` | `0x194f` | `0x19a2` | **`+0x53`** |

### Other Changes

```diff

-125.0.0.0.0
-  Functions: 1166
+129.0.0.0.0
+  Functions: 1184

-  CStrings:  494
+  CStrings:  500
CStrings:
+ "AppleProcessorTrace::hibernationSleep\n"
+ "AppleProcessorTrace::hibernationWake\n"
+ "AppleProcessorTrace::startTracingOnClustersGated(%p)\n"
+ "AppleProcessorTrace::stopTracingOnClustersGated\n"
+ "expectState(DriverState::Hibernating)"
+ "expectState(DriverState::Tracing) || expectState(DriverState::Paused)"
+ "void AppleProcessorTrace::hibernationSleep()"
+ "void AppleProcessorTrace::hibernationWake()"
+ "void AppleProcessorTrace::startTracingOnClustersGated(DriverState)"
+ "void AppleProcessorTrace::startTracingOnTraceableCores()"
+ "void AppleProcessorTrace::stopTracingOnClustersGated()"
- "AppleProcessorTrace::startTracingOnClusterGated\n"
- "AppleProcessorTrace::stopTracingOnClusterGated\n"
- "IOReturn AppleProcessorTrace::startTracingOnClusterGated(ml_topology_cluster_t)"
- "IOReturn AppleProcessorTrace::stopTracingOnClusterGated(ml_topology_cluster_t)"
- "void AppleProcessorTrace::startTracingOnTraceableCores(ml_topology_cluster_t)"
```
