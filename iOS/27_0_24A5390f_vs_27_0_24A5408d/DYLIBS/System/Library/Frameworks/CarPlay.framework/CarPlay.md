## CarPlay

> `/System/Library/Frameworks/CarPlay.framework/CarPlay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f68c` | `0x704bc` | **`+0xe30`** |
| `__TEXT.__oslogstring` | `0x34d6` | `0x36d6` | **`+0x200`** |
| `__AUTH_CONST.__auth_got` | `0x6c8` | `0x7d0` | **`+0x108`** |
| `__AUTH_CONST.__cfstring` | `0x5680` | `0x5720` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x21510` | `0x215a0` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x4368` | `0x43b8` | **`+0x50`** |
| `__TEXT.__cstring` | `0x5a26` | `0x5a76` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x9a78` | `0x9ac8` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1f70` | `0x1f98` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x860` | `0x880` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0xa38` | `0xa44` | **`+0xc`** |

### Other Changes

```diff

-540.1.0.0.0
+542.7.0.0.0

+  - /System/Library/Frameworks/CoreVideo.framework/CoreVideo

+  - /System/Library/Frameworks/IOSurface.framework/IOSurface

-  Functions: 3382
-  Symbols:   6332
-  CStrings:  1094
+  Functions: 3402
+  Symbols:   6382
+  CStrings:  1108
Symbols:
+ -[CPImageSet _iosurfaceFromImage:]
+ -[CPImageSet darkIOSurface]
+ -[CPImageSet darkPixelHash]
+ -[CPImageSet lightIOSurface]
+ -[CPImageSet lightPixelHash]
+ -[CPImageSet setDarkIOSurface:]
+ -[CPImageSet setDarkPixelHash:]
+ -[CPImageSet setLightIOSurface:]
+ -[CPImageSet setLightPixelHash:]
+ _CC_SHA1_Final
+ _CC_SHA1_Init
+ _CC_SHA1_Update
+ _CFDataGetBytePtr
+ _CFRelease
+ _CFRetain
+ _CGBitmapContextCreate
+ _CGColorSpaceCreateDeviceRGB
+ _CGColorSpaceRelease
+ _CGContextDrawImage
+ _CGContextRelease
+ _CGDataProviderCopyData
+ _CGImageGetBitsPerPixel
+ _CGImageGetBytesPerRow
+ _CGImageGetDataProvider
+ _CGImageGetHeight
+ _CGImageGetWidth
+ _CGImageRelease
+ _CPImageFromIOSurface
+ _CPPixelHashForIOSurface
+ _CPPixelHashForImage
+ _CVPixelBufferCreate
+ _CVPixelBufferGetBaseAddress
+ _CVPixelBufferGetBytesPerRow
+ _CVPixelBufferGetIOSurface
+ _CVPixelBufferLockBaseAddress
+ _CVPixelBufferRelease
+ _CVPixelBufferUnlockBaseAddress
+ _IOSurfaceGetBaseAddress
+ _IOSurfaceGetBytesPerElement
+ _IOSurfaceGetBytesPerRow
+ _IOSurfaceGetHeight
+ _IOSurfaceGetWidth
+ _IOSurfaceLock
+ _IOSurfaceUnlock
+ _OBJC_IVAR_$_CPImageSet._darkIOSurface
+ _OBJC_IVAR_$_CPImageSet._darkPixelHash
+ _OBJC_IVAR_$_CPImageSet._lightIOSurface
+ _OBJC_IVAR_$_CPImageSet._lightPixelHash
+ _UICreateCGImageFromIOSurface
+ _kCFAllocatorDefault
+ _kCVPixelBufferCGBitmapContextCompatibilityKey
+ _kCVPixelBufferCGImageCompatibilityKey
+ _kCVPixelBufferIOSurfacePropertiesKey
- -[CPImageSet computedHashAtInitialization]
- -[CPImageSet setComputedHashAtInitialization:]
- _OBJC_IVAR_$_CPImageSet._computedHashAtInitialization
CStrings:
+ "\t"
+ "CPImageSet: Failed to create CGContext for pixel buffer"
+ "CPImageSet: Failed to create CVPixelBuffer: %d"
+ "CPImageSet: Failed to get IOSurface from CVPixelBuffer"
+ "CPImageSet: both IOSurface and PNG data absent or unreadable; images will be nil"
+ "CPImageSet: encoding via PNG fallback (light surface=%@, dark surface=%@)"
+ "CPImageSet: image has no CGImage"
+ "CPImageSet: only one IOSurface decoded (light=%@, dark=%@); using available surface for both"
+ "CPImageSet: only one PNG decoded (light=%@, dark=%@); using available image for both"
+ "IOSurface"
+ "kCPDarkContentIOSurfaceKey"
+ "kCPLightContentIOSurfaceKey"
+ "nil"
+ "ok"
```
