## replayd

> `/usr/libexec/replayd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb929c` | `0xbac1c` | **`+0x1980`** |
| `__TEXT.__oslogstring` | `0x1634a` | `0x166f4` | **`+0x3aa`** |
| `__TEXT.__objc_methname` | `0x15d0c` | `0x15f58` | **`+0x24c`** |
| `__TEXT.__objc_stubs` | `0xf0e0` | `0xf320` | **`+0x240`** |
| `__TEXT.__cstring` | `0x17b48` | `0x17c86` | **`+0x13e`** |
| `__TEXT.__objc_methlist` | `0x73c8` | `0x74a0` | **`+0xd8`** |
| `__DATA.__objc_selrefs` | `0x4690` | `0x4720` | **`+0x90`** |
| `__DATA.__objc_const` | `0x11310` | `0x11388` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x2310` | `0x2370` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x2ab8` | `0x2b00` | **`+0x48`** |
| `__DATA_CONST.__cfstring` | `0x5ce0` | `0x5d20` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x4403` | `0x43f5` | **`-0xe`** |
| `__DATA.__objc_ivar` | `0xd7c` | `0xd84` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-740.63.1.2.0
+765.9.1.0.0

-  Functions: 3639
+  Functions: 3680

-  CStrings:  7343
+  CStrings:  7382
Symbols:
+ __exit
- _notify_register_check
CStrings:
+ " [ERROR] %{public}s:%d RPConnectionManager: SIGTERM cleanup window elapsed, exiting cleanly"
+ " [ERROR] %{public}s:%d Unable to re-latch capture display on session reuse: no current FBS layout identity"
+ " [ERROR] %{public}s:%d failed to create SCPreviewSession for previewID=%@"
+ " [ERROR] %{public}s:%d failed to stop own session"
+ " [ERROR] %{public}s:%d maximum preview count (%lu) reached for previewContent=%d"
+ " [ERROR] %{public}s:%d missing or malformed previewID in previewConfig (got %@)"
+ " [ERROR] %{public}s:%d no client found for %{public}@, nothing to stop"
+ " [ERROR] %{public}s:%d no preview found for previewID=%@ content=%d"
+ " [ERROR] %{public}s:%d previewID=%@ already exists for previewContent=%d"
+ " [ERROR] %{public}s:%d stopAllActiveClients: caller pid %d lacks system recording entitlement, scoping stop to its own sessions"
+ " [ERROR] %{public}s:%d unsupported previewContent=%d"
+ " [INFO] %{public}s:%d Stopped recording due to display change, outputURL: %@ error: %@"
+ " [INFO] %{public}s:%d stop own session success"
+ "-[RPConnectionManager handleSIGTERMWithExitAfter:exitBlock:]"
+ "-[RPConnectionManager handleSIGTERMWithExitAfter:exitBlock:]_block_invoke"
+ "-[RPConnectionManager stopAllActiveClients]"
+ "-[RPRecordingManager stopActiveSessionForClientWithBundleID:]"
+ "-[RPRecordingManager stopActiveSessionForClientWithBundleID:]_block_invoke"
+ "-[RPSession handleCaptureDisplayIDUpdate:]"
+ "@\"NSUUID\""
+ "RPConnectionManager: stopAllActiveClients completed for the calling client only"
+ "RPConnectionManager: stopAllActiveClientsInternal"
+ "RPConnectionManager: stopAllActiveClientsInternal completed"
+ "T@\"NSUUID\",R,N,V_previewID"
+ "T@\"SCClipSession\",&,V_clipSession"
+ "VB40@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32"
+ "VB40@0:8@16@24@32"
+ "_cameraPreviewSessions"
+ "_displayFrameOnCameraPreviewSessions:"
+ "_displayFrameOnScreenPreviewSessions:"
+ "_screenPreviewSessions"
+ "_screenStreamsLock"
+ "_stopAndRemoveAllPreviewSessions"
+ "clipSession"
+ "com.screenCaptureKit.previewUpdateQueue.%@"
+ "currentLayout"
+ "elapsedClipBufferingSeconds"
+ "getStreamWithStreamID:"
+ "getStreamsSnapshot"
+ "handleCaptureDisplayIDUpdate:"
+ "handleSIGTERM"
+ "handleSIGTERMWithExitAfter:exitBlock:"
+ "initSystemTapWithFormat:excludePIDs:"
+ "initWithUUIDString:"
+ "previewID"
+ "profileConnectionDidReceiveAllowCloudSyncChangedNotification:userInfo:"
+ "removeStreamWithStreamID:"
+ "setClipSession:"
+ "setStream:withStreamID:"
+ "showRemoteAlertOfType:application:bundleID:"
+ "stopActiveSessionForClientWithBundleID:"
+ "stopAllActiveClientsInternal"
+ "unknown"
+ "v24@?0@\"NSError\"8Q16"
+ "v32@0:8d16@?24"
- " [ERROR] %{public}s:%d failed to start previewContent=%d alreadyStarted=%d"
- " [ERROR] %{public}s:%d failed to stop previewContent=%d alreadyStopped=%d"
- " [INFO] %{public}s:%d Stopped recording due to display change"
- "-[RPSession setUpFrontBoardServices]_block_invoke"
- "@\"SCPreviewSession\""
- "RPConnectionManager: stopAllActiveClients completed"
- "RPDaemonRun_block_invoke"
- "VB32@0:8@\"NSString\"16@\"NSString\"24"
- "VB32@0:8@16@24"
- "Vv32@0:8@\"NSString\"16@\"NSString\"24"
- "_cameraPreviewSession"
- "_screenPreviewSession"
- "com.screenCaptureKit.previewUpdateQueue"
- "dismissReactionsTipForApplication:bundleID:"
- "showReactionsTipForApplication:bundleID:"
- "valueForKey:"
```
