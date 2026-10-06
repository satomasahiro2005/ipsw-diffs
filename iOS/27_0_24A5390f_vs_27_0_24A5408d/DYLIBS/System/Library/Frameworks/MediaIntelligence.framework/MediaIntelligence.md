## MediaIntelligence

> `/System/Library/Frameworks/MediaIntelligence.framework/MediaIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19854` | `0x19a68` | **`+0x214`** |
| `__AUTH_CONST.__const` | `0x1000` | `0x10a0` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x450` | `0x490` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0xa58` | `0xa88` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x524` | `0x4f4` | **`-0x30`** |
| `__TEXT.__swift5_capture` | `0x74` | `0x94` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x67c` | `0x694` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x5c0` | `0x5d8` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x892` | `0x8a6` | **`+0x14`** |
| `__DATA.__data` | `0x470` | `0x480` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x333` | `0x343` | **`+0x10`** |
| `__AUTH.__data` | `0x700` | `0x708` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x258` | `0x260` | **`+0x8`** |
| `__TEXT.__const` | `0x1788` | `0x1780` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x9f8` | `0x9f0` | **`-0x8`** |

### Other Changes

```diff

-435.73.2.0.0
+435.79.1.4.0

-  - /System/Library/Frameworks/CoreVideo.framework/CoreVideo

-  Functions: 546
-  Symbols:   479
-  CStrings:  50
+  Functions: 559
+  Symbols:   481
+  CStrings:  49
Symbols:
+ _CGImageDestinationAddImage
+ _CGImageDestinationCreateWithData
+ _CGImageDestinationFinalize
+ _OBJC_CLASS_$_NSMutableData
+ _OBJC_CLASS_$_VNSession
+ _kCGImageDestinationImageMaxPixelSize
+ _kCGImageDestinationLossyCompressionQuality
+ _kCGImageDestinationOptimizeColorForSharing
+ _objc_retain_x27
+ _swift_isEscapingClosureAtFileLocation
+ _swift_release_x1
+ _swift_retain_x19
+ _swift_retain_x23
+ _swift_retain_x26
+ _symbolic Igh_
+ _symbolic So9VNSessionC
- _CGBitmapContextCreate
- _CGColorSpaceCreateDeviceRGB
- _CGContextSetInterpolationQuality
- _CVPixelBufferCreate
- _CVPixelBufferGetBaseAddress
- _CVPixelBufferGetBytesPerRow
- _CVPixelBufferGetDataSize
- _CVPixelBufferLockBaseAddress
- _CVPixelBufferUnlockBaseAddress
- ___CGBitmapContextCreate
- _kCFAllocatorDefault
- _kCVPixelBufferCGBitmapContextCompatibilityKey
- _kCVPixelBufferCGImageCompatibilityKey
- _kCVPixelBufferIOSurfacePropertiesKey
CStrings:
+ "Failed to create image destination for face crop"
+ "Failed to finalize face crop encoding"
- "Failed to create CGContext for pixel buffer"
- "Failed to create CVPixelBuffer"
- "Scaling down face crop from %{public}fpx max side with factor %{public}f"
```
