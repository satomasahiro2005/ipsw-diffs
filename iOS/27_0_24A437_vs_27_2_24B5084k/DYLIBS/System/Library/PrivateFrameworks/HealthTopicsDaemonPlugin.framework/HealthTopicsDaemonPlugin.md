## HealthTopicsDaemonPlugin

> `/System/Library/PrivateFrameworks/HealthTopicsDaemonPlugin.framework/HealthTopicsDaemonPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe91c` | `0xf880` | **`+0xf64`** |
| `__TEXT.__oslogstring` | `0x51d` | `0x5bd` | **`+0xa0`** |
| `__AUTH_CONST.__auth_got` | `0x710` | `0x730` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x30c` | `0x31e` | **`+0x12`** |
| `__TEXT.__const` | `0x410` | `0x420` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xe4` | `0xf4` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2e0` | `0x2f0` | **`+0x10`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 212
-  Symbols:   340
-  CStrings:  38
+  Functions: 213
+  Symbols:   341
+  CStrings:  40
Symbols:
+ _symbolic _____ s15ContinuousClockV7InstantV
+ _symbolic _____XDXMT 24HealthTopicsDaemonPlugin20TopicExecutionEngineC
- _objc_retain_x21
CStrings:
+ "PERFTOPIC blocking topic=%{public}s heldMs=%{public}f waitedMs=%{public}f kind=%{public}s"
+ "TopicClientProcessMonitor: ignoring suspension for %{public}s"
```
