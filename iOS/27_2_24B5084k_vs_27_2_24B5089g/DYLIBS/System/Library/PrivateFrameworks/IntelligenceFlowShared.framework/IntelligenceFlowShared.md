## IntelligenceFlowShared

> `/System/Library/PrivateFrameworks/IntelligenceFlowShared.framework/IntelligenceFlowShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd4270` | `0xd88d4` | **`+0x4664`** |
| `__DATA_DIRTY.__bss` | `0xc900` | `0xde80` | **`+0x1580`** |
| `__DATA.__bss` | `0x1a210` | `0x19010` | **`-0x1200`** |
| `__DATA_DIRTY.__data` | `0x3820` | `0x41f8` | **`+0x9d8`** |
| `__AUTH_CONST.__const` | `0xc578` | `0xcb10` | **`+0x598`** |
| `__DATA.__data` | `0x2878` | `0x2348` | **`-0x530`** |
| `__AUTH.__data` | `0x608` | `0x218` | **`-0x3f0`** |
| `__TEXT.__const` | `0x15250` | `0x15570` | **`+0x320`** |
| `__TEXT.__oslogstring` | `0xb16` | `0xd66` | **`+0x250`** |
| `__TEXT.__unwind_info` | `0x5a98` | `0x5c20` | **`+0x188`** |
| `__TEXT.__cstring` | `0x93ea` | `0x956a` | **`+0x180`** |
| `__TEXT.__eh_frame` | `0x5374` | `0x54d4` | **`+0x160`** |
| `__TEXT.__swift5_capture` | `0x230` | `0x354` | **`+0x124`** |
| `__TEXT.__swift5_typeref` | `0x3cf6` | `0x3df2` | **`+0xfc`** |
| `__TEXT.__swift5_fieldmd` | `0x56c8` | `0x57bc` | **`+0xf4`** |
| `__TEXT.__constg_swiftt` | `0x3878` | `0x3954` | **`+0xdc`** |
| `__AUTH.__objc_data` | `0x130` | `0x90` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x288` | `0x328` | **`+0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x3e8c` | `0x3f1c` | **`+0x90`** |
| `__AUTH_CONST.__auth_got` | `0x13a8` | `0x1428` | **`+0x80`** |
| `__DATA_CONST.__got` | `0x760` | `0x7b8` | **`+0x58`** |
| `__TEXT.__swift5_proto` | `0x13e4` | `0x1400` | **`+0x1c`** |
| `__DATA.__common` | `0x20` | `0x8` | **`-0x18`** |
| `__DATA_CONST.__const` | `0x560` | `0x578` | **`+0x18`** |
| `__DATA_DIRTY.__common` | `0x30` | `0x48` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x5b8` | `0x5d0` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x80` | `0x8c` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x7c` | `0x88` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x330` | `0x338` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x9c` | `0xa0` | **`+0x4`** |

### Other Changes

```diff

-3605.14.3.501.4
+3605.16.9.501.1

+  - /System/Library/PrivateFrameworks/CMPhoto.framework/CMPhoto

+  - /usr/lib/swift/libswiftCompression.dylib

-  Functions: 9594
-  Symbols:   284
-  CStrings:  1145
+  Functions: 9764
+  Symbols:   308
+  CStrings:  1162
Symbols:
+ _CFGetTypeID
+ _CMPhotoDecompressionContainerCreateImageForIndex
+ _CMPhotoDecompressionContainerCreateOutputBufferAttributesForImageIndex
+ _CMPhotoDecompressionSessionCreate
+ _CMPhotoDecompressionSessionCreateContainer
+ _CVPixelBufferCreate
+ _CVPixelBufferGetTypeID
+ _OBJC_CLASS_$_NSDictionary
+ __swift_FORCE_LOAD_$_swiftCompression
+ _kCFAllocatorDefault
+ _kCMPhotoDecompressionOption_OutputPixelFormat
+ _kCMPhotoDecompressionOption_UseProvidedPixelBuffer
+ _kCMPhotoDecompressionSessionOption_SurfacePool
+ _kCMPhotoSurfacePoolOneShot
+ _kCVPixelBufferBytesPerRowAlignmentKey
+ _kCVPixelBufferHeightKey
+ _kCVPixelBufferIOSurfacePropertiesKey
+ _kCVPixelBufferWidthKey
+ _objc_retain_x25
+ _objc_retain_x26
+ _swift_dynamicCastObjCClass
+ _swift_dynamicCastUnknownClassUnconditional
+ _swift_retain_x21
+ _swift_retain_x28
CStrings:
+ "AutoBugCapture also targeting %{public}ld companion IDS destination(s) for %s"
+ "BytesPerRowAlignment"
+ "Done with AutoBugCapture (with companion destinations) for %s."
+ "Failed to decode screenshot for %{public}s from %{public}ld bytes"
+ "Populated screenshot for %{public}s: %{public}ldx%{public}ld"
+ "Taking an AutoBugCapture snapshot only for local device"
+ "[ScreenshotDecode] CVPixelBufferCreate failed (%{public}d) for %{public}ldx%{public}ld"
+ "[ScreenshotDecode] Could not resolve output buffer attributes (err %{public}d)"
+ "[ScreenshotDecode] Decode failed (err %{public}d)"
+ "if.planner.tool_result.entity_id"
+ "if.planner.tool_result.entity_kind"
+ "if.planner.tool_result.error_code"
+ "if.planner.tool_result.error_kind"
+ "if.planner.tool_result.provenance"
+ "if.planner.tool_result.variant"
+ "if.search.multi_device_routing_mode_raw"
+ "if.search.remote_call"
```
