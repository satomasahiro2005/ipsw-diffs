## ReplayKit

> `/System/Library/Frameworks/ReplayKit.framework/ReplayKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x8c0` | `—` | **`-0x8c0`** |
| `__DATA_DIRTY.__objc_data` | `0x230` | `0xaf0` | **`+0x8c0`** |
| `__TEXT.__text` | `0x361a8` | `0x36460` | **`+0x2b8`** |
| `__TEXT.__cstring` | `0x800a` | `0x80eb` | **`+0xe1`** |
| `__TEXT.__oslogstring` | `0x569a` | `0x5720` | **`+0x86`** |
| `__AUTH_CONST.__cfstring` | `0x1e60` | `0x1ec0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x3600` | `0x3630` | **`+0x30`** |
| `__AUTH_CONST.__objc_dictobj` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xbb0` | `0xbd0` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x48` | `0x60` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2118` | `0x2130` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x10` | **`+0x10`** |

### Other Changes

```diff

-740.48.1.0.0
+740.53.1.0.0

-  Functions: 1404
-  Symbols:   2221
-  CStrings:  1085
+  Functions: 1409
+  Symbols:   2226
+  CStrings:  1091
Symbols:
+ -[RPBroadcastController finishSystemBroadcastWithSessionInfo:handler:]
+ -[RPControlCenterClient stopHQLRRecordingWithStopSource:handler:]
+ -[RPControlCenterClient stopSystemRecordingWithStopSource:handler:]
+ -[RPDaemonProxy stopHQLRWithSessionInfo:handler:]
+ -[RPDaemonProxy stopSystemBroadcastWithSessionInfo:handler:]
+ -[RPDaemonProxy stopSystemRecordingWithSessionInfo:handler:]
+ -[RPScreenRecorder stopHQLRWithSessionInfo:handler:]
+ -[RPScreenRecorder stopSystemBroadcastWithSessionInfo:handler:]
+ -[RPScreenRecorder stopSystemRecordingWithSessionInfo:handler:]
+ _OBJC_CLASS_$_NSConstantDictionary
+ ___49-[RPDaemonProxy stopHQLRWithSessionInfo:handler:]_block_invoke
+ ___52-[RPScreenRecorder stopHQLRWithSessionInfo:handler:]_block_invoke
+ ___60-[RPDaemonProxy stopSystemBroadcastWithSessionInfo:handler:]_block_invoke
+ ___60-[RPDaemonProxy stopSystemRecordingWithSessionInfo:handler:]_block_invoke
+ ___63-[RPScreenRecorder stopSystemBroadcastWithSessionInfo:handler:]_block_invoke
+ ___63-[RPScreenRecorder stopSystemRecordingWithSessionInfo:handler:]_block_invoke
+ ___65-[RPControlCenterClient stopHQLRRecordingWithStopSource:handler:]_block_invoke
+ ___65-[RPControlCenterClient stopHQLRRecordingWithStopSource:handler:]_block_invoke_2
+ ___67-[RPControlCenterClient stopSystemRecordingWithStopSource:handler:]_block_invoke
+ ___67-[RPControlCenterClient stopSystemRecordingWithStopSource:handler:]_block_invoke_2
+ ___70-[RPBroadcastController finishSystemBroadcastWithSessionInfo:handler:]_block_invoke
- -[RPControlCenterClient stopHQLRRecordingWithHandler:]
- -[RPControlCenterClient stopSystemRecordingWithHandler:]
- -[RPDaemonProxy stopHQLRWithHandler:]
- -[RPDaemonProxy stopSystemBroadcastWithHandler:]
- -[RPDaemonProxy stopSystemRecordingWithHandler:]
- ___29-[RPScreenRecorder stopHQLR:]_block_invoke
- ___37-[RPDaemonProxy stopHQLRWithHandler:]_block_invoke
- ___40-[RPScreenRecorder stopSystemRecording:]_block_invoke
- ___48-[RPDaemonProxy stopSystemBroadcastWithHandler:]_block_invoke
- ___48-[RPDaemonProxy stopSystemRecordingWithHandler:]_block_invoke
- ___51-[RPScreenRecorder stopSystemBroadcastWithHandler:]_block_invoke
- ___54-[RPControlCenterClient stopHQLRRecordingWithHandler:]_block_invoke
- ___54-[RPControlCenterClient stopHQLRRecordingWithHandler:]_block_invoke_2
- ___56-[RPControlCenterClient stopSystemRecordingWithHandler:]_block_invoke
- ___56-[RPControlCenterClient stopSystemRecordingWithHandler:]_block_invoke_2
- ___58-[RPBroadcastController finishSystemBroadcastWithHandler:]_block_invoke
CStrings:
+ " [INFO] %{public}s:%d %p stopSource=%ld"
+ "-[RPControlCenterClient stopHQLRRecordingWithStopSource:handler:]"
+ "-[RPControlCenterClient stopHQLRRecordingWithStopSource:handler:]_block_invoke"
+ "-[RPControlCenterClient stopHQLRRecordingWithStopSource:handler:]_block_invoke_2"
+ "-[RPControlCenterClient stopSystemRecordingWithStopSource:handler:]"
+ "-[RPControlCenterClient stopSystemRecordingWithStopSource:handler:]_block_invoke"
+ "-[RPControlCenterClient stopSystemRecordingWithStopSource:handler:]_block_invoke_2"
+ "-[RPScreenRecorder stopHQLRWithSessionInfo:handler:]"
+ "-[RPScreenRecorder stopSystemBroadcastWithSessionInfo:handler:]"
+ "-[RPScreenRecorder stopSystemRecordingWithSessionInfo:handler:]"
+ "RECORDING_ERROR_FAILED_TO_START_HIGH_QUALITY_RECORDING"
+ "RECORDING_ERROR_TIME_LIMIT_REACHED"
+ "RPDaemonProxy: stopHQLRWithSessionInfo: proxy error: %d"
+ "RPDaemonProxy: stopHQLRWithSessionInfo:%@"
+ "RPDaemonProxy: stopSystemBroadcastWithSessionInfo: proxy error: %d"
+ "RPDaemonProxy: stopSystemBroadcastWithSessionInfo:%@"
+ "RPDaemonProxy: stopSystemRecordingWithSessionInfo: proxy error: %d"
+ "RPDaemonProxy: stopSystemRecordingWithSessionInfo:%@"
+ "stopSource"
- "-[RPControlCenterClient stopHQLRRecordingWithHandler:]"
- "-[RPControlCenterClient stopHQLRRecordingWithHandler:]_block_invoke"
- "-[RPControlCenterClient stopHQLRRecordingWithHandler:]_block_invoke_2"
- "-[RPControlCenterClient stopSystemRecordingWithHandler:]"
- "-[RPControlCenterClient stopSystemRecordingWithHandler:]_block_invoke"
- "-[RPControlCenterClient stopSystemRecordingWithHandler:]_block_invoke_2"
- "-[RPScreenRecorder stopHQLR:]"
- "-[RPScreenRecorder stopSystemBroadcastWithHandler:]"
- "-[RPScreenRecorder stopSystemRecording:]"
- "RPDaemonProxy: stopSystemBroadcastWithHandler: proxy error: %d"
- "RPDaemonProxy: stopSystemBroadcastWithHandler:withHandler:"
- "RPDaemonProxy: stopSystemRecordingWithHandler: proxy error: %d"
- "RPDaemonProxy: stopSystemRecordingWithHandler:withHandler:"
```
