## com.apple.photos.VideoConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/XPCServices/com.apple.photos.VideoConversionService.xpc/com.apple.photos.VideoConversionService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22678` | `0x22a2c` | **`+0x3b4`** |
| `__TEXT.__cstring` | `0x3627` | `0x3899` | **`+0x272`** |
| `__TEXT.__objc_stubs` | `0x62e0` | `0x6480` | **`+0x1a0`** |
| `__TEXT.__objc_methname` | `0x827c` | `0x83dd` | **`+0x161`** |
| `__DATA_CONST.__cfstring` | `0x27c0` | `0x28a0` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x3008` | `0x30db` | **`+0xd3`** |
| `__DATA.__objc_selrefs` | `0x1d80` | `0x1de0` | **`+0x60`** |
| `__DATA.__objc_const` | `0x2dd8` | `0x2e18` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1eac` | `0x1edc` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0xb00` | `0xb20` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x7c8` | `0x7e0` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x590` | `0x5a0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7c0` | `0x7c8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x254` | `0x258` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-916.45.110.0.0
+916.51.202.0.0

-  Functions: 695
-  Symbols:   431
-  CStrings:  1928
+  Functions: 699
+  Symbols:   436
+  CStrings:  1952
Symbols:
+ _OBJC_CLASS_$_NSThread
+ _OBJC_CLASS_$_PFRadarComponent
+ _OBJC_CLASS_$_PFTapToRadarDraft
+ _PFOSVariantHasInternalDiagnostics
+ _PFTapToRadarCreateDraft
CStrings:
+ "A video conversion stopped reporting progress, so VideoConversionService force-crashed itself. The crash report records only that deliberate crash. What the conversion and the rest of the system were stuck on is in the spindump inside the attached sysdiagnose.\n\nSource resources: %@\nSource sizes: %@\nDestination: %@\nConversion task: %@ %@\nHang detector: %@\nQueue entry: %@\nRequest reason: %@\n"
+ "Photos Backend Media Conversion Services"
+ "Photos Video Conversion"
+ "T@\"NSString\",R,V_hangDetectionSummary"
+ "Tap-to-Radar is gathering diagnostics for the stalled conversion, staying alive %.0f s so its spindump can sample us"
+ "Unable to create output image destination of type %{public}@"
+ "Unable to open a Tap-to-Radar draft for the stalled conversion: %{public}@"
+ "VideoConversionService: video conversion made no progress for an hour"
+ "_captureVideoConversionHangDiagnosticsForQueueEntry:conversionTask:"
+ "_hangDetectionSummary"
+ "all"
+ "currentStateSummary"
+ "hangDetectionSummary"
+ "initWithIdentifier:name:version:"
+ "progress %.4f unchanged for %.0f s, threshold %.0f s"
+ "setCapturesPerformanceTrace:"
+ "setClassification:"
+ "setComponent:"
+ "setDisplayReason:"
+ "setProblemDescription:"
+ "setProcessName:"
+ "setTitle:"
+ "sleepForTimeInterval:"
+ "video conversion stopped making progress"
+ "\xf0!"
- "Unable to create output image destination"
```
