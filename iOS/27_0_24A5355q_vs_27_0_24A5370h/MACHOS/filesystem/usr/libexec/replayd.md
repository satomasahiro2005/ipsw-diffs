## replayd

> `/usr/libexec/replayd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb6908` | `0xb717c` | **`+0x874`** |
| `__TEXT.__oslogstring` | `0x15a69` | `0x15c93` | **`+0x22a`** |
| `__TEXT.__objc_methname` | `0x15928` | `0x15b0d` | **`+0x1e5`** |
| `__TEXT.__cstring` | `0x1763a` | `0x177bd` | **`+0x183`** |
| `__DATA.__objc_const` | `0x110a8` | `0x111f0` | **`+0x148`** |
| `__TEXT.__objc_stubs` | `0xee00` | `0xef20` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x724c` | `0x7308` | **`+0xbc`** |
| `__DATA.__objc_selrefs` | `0x45d8` | `0x4630` | **`+0x58`** |
| `__DATA.__objc_data` | `0x1860` | `0x18b0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x2998` | `0x29e0` | **`+0x48`** |
| `__DATA_CONST.__cfstring` | `0x5be0` | `0x5c20` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x2248` | `0x2280` | **`+0x38`** |
| `__DATA_CONST.__objc_intobj` | `0x588` | `0x5b8` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x4328` | `0x4357` | **`+0x2f`** |
| `__TEXT.__objc_classname` | `0xa2d` | `0xa44` | **`+0x17`** |
| `__TEXT.__gcc_except_tab` | `0xf04` | `0xf18` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0xd54` | `0xd60` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xbd8` | `0xbe0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x270` | `0x278` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1d8` | `0x1e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`

### Other Changes

```diff

-740.44.1.0.0
+740.48.1.0.0

-  Functions: 3594
-  Symbols:   797
-  CStrings:  7249
+  Functions: 3606
+  Symbols:   798
+  CStrings:  7282
Symbols:
+ _OBJC_CLASS_$_NSNull
CStrings:
+ " [ERROR] %{public}s:%d Empty extensionToken attempted to be consumed"
+ " [ERROR] %{public}s:%d FVD start failure (status=%d) but no _didStartScreenCaptureHandler set"
+ " [ERROR] %{public}s:%d clientApplicationDidEnterForegroundWithPID: stopping session, capture requirements check failed error=%@"
+ " [INFO] %{public}s:%d 3P casting, will not stop for display configuration change"
+ " [INFO] %{public}s:%d Already invalidated, bailing on duplicate stop. session=%p streamID=%@"
+ " [INFO] %{public}s:%d Casting extension entitlement check: %s"
+ " [INFO] %{public}s:%d Created display monitor for session %@ (displayID: %u)"
+ " [INFO] %{public}s:%d Device lock or proximity sensor engaged during active call, ignoring device locked warning"
+ " [INFO] %{public}s:%d HQR videoSettings=%@"
+ " [INFO] %{public}s:%d display configuration changed: %u -> %u"
+ " [INFO] %{public}s:%d will stop for display configuration change"
+ "-[RPConnectionManager consumeSandboxExtensionToken:]"
+ "-[RPScreenCaptureManagerIOS _handleFVDStartFailureWithErrorStatus:]"
+ "-[SCCaptureSession clientApplicationDidEnterForegroundWithPID:]_block_invoke"
+ "-[SCCaptureSession handleSystemDisplayConfigurationDidChange]"
+ "-[SCDisplayChangeMonitor handleDisplayIDChanged:]_block_invoke"
+ "-[SCSystemServicesManager createDisplayMonitorsForDisplayID:]"
+ "@\"<SCDisplayChangeMonitorDelegate>\""
+ "@20@0:8I16"
+ "RECORDING_ERROR_FAILED_TO_START_HIGH_QUALITY_RECORDING"
+ "SCDisplayChangeMonitor"
+ "T@\"<SCDisplayChangeMonitorDelegate>\",W,N,V_delegate"
+ "_currentDisplayID"
+ "_displayID"
+ "_displayMonitorsForSession"
+ "_handleFVDStartFailureWithErrorStatus:"
+ "_monitorQueue"
+ "_notifyObserversForMonitor:withBlock:"
+ "com.apple.replaykit.ScreenRecordingAttribution"
+ "com.apple.screencapturekit.displaychangemonitor"
+ "createDisplayMonitorsForDisplayID:"
+ "displayChangeMonitorDidDetectDisplayConfigurationChange:"
+ "handleDisplayIDChanged:"
+ "handleSystemDisplayConfigurationDidChange"
+ "initWithDisplayID:"
+ "notifyDisplayMonitorsOfDisplayChange:"
+ "null"
+ "removeDisplayMonitorForSession:"
+ "videoSettingsForVisionHQRecording"
- " [DEBUG] %{public}s:%d Casting extension entitlement check: %s"
- " [DEBUG] %{public}s:%d System recording stopped, no AVAudioSession attribution to clear"
- " [ERROR] %{public}s:%d session=%p Cannot stop session - delegate is nil"
- " [ERROR] %{public}s:%d session=%p streamID=%@ Screen dimension changed: %zux%zu -> %zux%zu. Stopping session."
- "-[SCSystemServicesManager backlight:didCompleteUpdateToState:forEvent:]_block_invoke"
- "-[SCSystemServicesManager setUpCaptureDisplayBacklightMonitor]"
```
