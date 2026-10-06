## replayd

> `/usr/libexec/replayd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb790c` | `0xb7fa0` | **`+0x694`** |
| `__TEXT.__oslogstring` | `0x15e09` | `0x15f42` | **`+0x139`** |
| `__DATA_CONST.__const` | `0x29e0` | `0x2a70` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0xf24` | `0xfa4` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x15be0` | `0x15c42` | **`+0x62`** |
| `__TEXT.__objc_stubs` | `0xefa0` | `0xf000` | **`+0x60`** |
| `__TEXT.__cstring` | `0x17846` | `0x1787a` | **`+0x34`** |
| `__DATA.__objc_const` | `0x11248` | `0x11278` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x7350` | `0x7378` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x439b` | `0x43c3` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x2298` | `0x22c0` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x5c80` | `0x5ca0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x4658` | `0x4670` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x1900` | `0x1910` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xc90` | `0xc98` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xc80` | `0xc88` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xd68` | `0xd6c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-740.53.1.0.0
+740.57.1.0.0

-  Functions: 3613
-  Symbols:   799
-  CStrings:  7299
+  Functions: 3622
+  Symbols:   801
+  CStrings:  7310
Symbols:
+ __dispatch_source_type_signal
+ _signal
CStrings:
+ " [ERROR] %{public}s:%d %p endSessionAtSourceTime: raised %@: %@"
+ " [ERROR] %{public}s:%d RPConnectionManager: SIGTERM received, stopping active clients"
+ " [ERROR] %{public}s:%d endSessionAtSourceTime: raised %@: %@"
+ " [ERROR] %{public}s:%d start called after audio recorder queue was freed"
+ " [ERROR] %{public}s:%d stop called but audio recorder queue is freed or not started"
+ "-[RPClient stopStreamForStreamID:stopSource:error:]"
+ "-[SCCaptureSession stopAndInvalidateWithStreamData:userStopped:stopSource:completionHandler:]"
+ "RPDaemonRun_block_invoke"
+ "STSS"
+ "getRecordingAlertTitle:body:forError:"
+ "reason"
+ "stopAndInvalidateWithStreamData:userStopped:stopSource:completionHandler:"
+ "stopSourceForStreamStopReason:"
+ "stopStreamForStreamID:stopSource:error:"
+ "v40@0:8^@16^@24@32"
+ "v44@0:8@16B24q28@?36"
- " [ERROR] %{public}s:%d stop called but not never start"
- "-[RPClient stopStreamForStreamID:error:]"
- "-[SCCaptureSession stopAndInvalidateWithStreamData:userStopped:completionHandler:]"
- "stopAndInvalidateWithStreamData:userStopped:completionHandler:"
- "stopStreamForStreamID:error:"
```
