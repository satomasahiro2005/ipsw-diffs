## replayd

> `/usr/libexec/replayd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb717c` | `0xb790c` | **`+0x790`** |
| `__TEXT.__oslogstring` | `0x15c93` | `0x15e09` | **`+0x176`** |
| `__TEXT.__objc_methname` | `0x15b0d` | `0x15be0` | **`+0xd3`** |
| `__DATA_CONST.__got` | `0xbe0` | `0xc80` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x177bd` | `0x17846` | **`+0x89`** |
| `__TEXT.__objc_stubs` | `0xef20` | `0xefa0` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0x5c20` | `0x5c80` | **`+0x60`** |
| `__DATA.__objc_const` | `0x111f0` | `0x11248` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x7308` | `0x7350` | **`+0x48`** |
| `__TEXT.__objc_methtype` | `0x4357` | `0x439b` | **`+0x44`** |
| `__DATA.__objc_selrefs` | `0x4630` | `0x4658` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x2280` | `0x2298` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xf18` | `0xf24` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0xd60` | `0xd68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
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

-740.48.1.0.0
+740.53.1.0.0

-  Functions: 3606
-  Symbols:   798
-  CStrings:  7282
+  Functions: 3613
+  Symbols:   799
+  CStrings:  7299
Symbols:
+ _NSUnderlyingErrorKey
CStrings:
+ " [ERROR] %{public}s:%d Unexpected FVD start failure status %d, falling back to generic FailedToStart"
+ " [ERROR] %{public}s:%d getSystemBroadcastExtensionInfo rejected: caller lacks system recording entitlement"
+ " [ERROR] %{public}s:%d getSystemBroadcastPickerInfo rejected: caller lacks system recording entitlement"
+ " [ERROR] %{public}s:%d status: %d, error: %@"
+ " [INFO] %{public}s:%d Ignoring display change for HQLR recording"
+ " [INFO] %{public}s:%d sessionInfo=%@"
+ "-[RPClient stopHQLRWithSessionInfo:handler:]"
+ "-[RPClient stopHQLRWithSessionInfo:handler:]_block_invoke"
+ "-[RPClient stopSystemBroadcastWithSessionInfo:handler:]"
+ "-[RPClient stopSystemBroadcastWithSessionInfo:handler:]_block_invoke"
+ "-[RPClient stopSystemRecordingWithSessionInfo:handler:]"
+ "-[RPClient stopSystemRecordingWithSessionInfo:handler:]_block_invoke"
+ "-[RPConnectionManager getSystemBroadcastExtensionInfo:]"
+ "-[RPConnectionManager stopHQLRWithSessionInfo:handler:]"
+ "-[RPConnectionManager stopSystemRecordingWithSessionInfo:handler:]"
+ "-[RPScreenCaptureManagerIOS _handleFVDStartFailureWithErrorStatus:error:]"
+ "-[RPScreenCaptureManagerIOS screenCaptureController:didFailWithStatus:error:]"
+ "CTYP"
+ "RECORDING_ERROR_TIME_LIMIT_REACHED"
+ "RPConnectionManager: stopHQLRWithSessionInfo completed"
+ "RPConnectionManager: stopSystemBroadcastWithSessionInfo"
+ "RPConnectionManager: stopSystemBroadcastWithSessionInfo completed"
+ "RPConnectionManager: stopSystemRecordingWithSessionInfo completed"
+ "STPS"
+ "Tq,N,V_stopSource"
+ "_castingSessionIDs"
+ "_handleFVDStartFailureWithErrorStatus:error:"
+ "_stopSource"
+ "notifyScreenCaptureStateChanged:"
+ "screenCaptureController:didFailWithStatus:error:"
+ "serviceNameSupportsStopSource"
+ "setStopSource:"
+ "stopHQLRWithSessionInfo:handler:"
+ "stopSource"
+ "stopSourceForEndReason:"
+ "stopSystemBroadcastWithSessionInfo:handler:"
+ "stopSystemRecordingWithSessionInfo:handler:"
+ "v28@0:8i16@20"
+ "v36@0:8@\"FigScreenCaptureController\"16i24@\"NSError\"28"
- " [ERROR] %{public}s:%d status: %d"
- " [INFO] %{public}s:%d Stopped HQLR recording due to display change"
- "-[RPClient stopHQLRSessionWithHandler:]"
- "-[RPClient stopHQLRSessionWithHandler:]_block_invoke"
- "-[RPClient stopSystemBroadcastSessionWithHandler:]"
- "-[RPClient stopSystemBroadcastSessionWithHandler:]_block_invoke"
- "-[RPClient stopSystemRecordingSessionWithHandler:]"
- "-[RPClient stopSystemRecordingSessionWithHandler:]_block_invoke"
- "-[RPConnectionManager stopHQLRWithHandler:]"
- "-[RPConnectionManager stopSystemRecordingWithHandler:]"
- "-[RPScreenCaptureManagerIOS _handleFVDStartFailureWithErrorStatus:]"
- "-[RPScreenCaptureManagerIOS screenCaptureController:didFailWithStatus:]"
- "RECORDING_ERROR_FAILED_TO_START_LIGHTING"
- "RPConnectionManager: stopHQLRWithHandler completed"
- "RPConnectionManager: stopSystemBroadcastWithHandler"
- "RPConnectionManager: stopSystemBroadcastWithHandler completed"
- "RPConnectionManager: stopSystemRecordingWithHandler completed"
- "_handleFVDStartFailureWithErrorStatus:"
- "stopHQLRSessionWithHandler:"
- "stopHQLRWithHandler:"
- "stopSystemBroadcastSessionWithHandler:"
- "stopSystemRecordingSessionWithHandler:"
```
