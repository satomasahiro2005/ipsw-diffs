## CoreImage

> `/System/Library/Frameworks/CoreImage.framework/CoreImage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x349f6c` | `0x34b1fc` | **`+0x1290`** |
| `__AUTH.__objc_data` | `0x9dd0` | `0x9a88` | **`-0x348`** |
| `__DATA_DIRTY.__objc_data` | `0x6e0` | `0xa28` | **`+0x348`** |
| `__TEXT.__cstring` | `0x104a1a` | `0x104bb8` | **`+0x19e`** |
| `__AUTH_CONST.__cfstring` | `0x1dba0` | `0x1dcc0` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0xb275` | `0xb37e` | **`+0x109`** |
| `__DATA_CONST.__const` | `0x6528` | `0x65b8` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0xa8c0` | `0xa920` | **`+0x60`** |
| `__TEXT.__dlopen_cstrs` | `0x3fd` | `0x445` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0xa87c` | `0xa8b4` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x159d0` | `0x159f0` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x688` | `0x6a0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x8e68` | `0x8e78` | **`+0x10`** |
| `__DATA.__bss` | `0x3ae8` | `0x3ae0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xb20` | `0xb28` | **`+0x8`** |

### Other Changes

```diff

-1667.40.3.0.0
+1667.40.5.0.0

-  Functions: 15174
-  Symbols:   26357
-  CStrings:  8883
+  Functions: 15194
+  Symbols:   26377
+  CStrings:  8900
Symbols:
+ -[CIImage isMonochrome]
+ -[CIRAWFilterImpl rawSensorPattern]
+ GCC_except_table156
+ GCC_except_table159
+ GCC_except_table164
+ GCC_except_table175
+ GCC_except_table178
+ GCC_except_table186
+ GCC_except_table331
+ GCC_except_table341
+ _CIRAWFilterDownloadNotNeeded
+ _CIRAWFilterStartDownload
+ _OBJC_CLASS_$_NSLock
+ _RawCameraLibraryCore
+ _RawCameraLibraryCore.frameworkLibrary
+ __ZN2CI6CGNode15restore_cgimageENS_10ImageIndexENS_22ImageLeafContentDigestEP7CGImageS4_PU28objcproto17OS_dispatch_queue8NSObject
+ __ZN2CI6CGNodeC1EiNS_10ImageIndexEP7CGImageS3_NS_22ImageLeafContentDigestEPU28objcproto17OS_dispatch_queue8NSObjectNS_11PixelFormatENS_8EdgeModeEbb
+ __ZN2CI6CGNodeC2EiNS_10ImageIndexEP7CGImageS3_NS_22ImageLeafContentDigestEPU28objcproto17OS_dispatch_queue8NSObjectNS_11PixelFormatENS_8EdgeModeEbb
+ __ZN2CI7CGImage18updateDecodedImageEv
+ __ZN2CIL25fillBlockFromDataProviderEP14CGDataProvidermP11__IOSurface
+ __ZZN2CI7CGImage18updateDecodedImageEvEN3$_08__invokeEPvPKvm
+ __ZZN2CI7CGImage18updateDecodedImageEvEN3$_18__invokeEPvPKvm
+ ___CIRAWFilterDownloadNotNeeded_block_invoke
+ ___CIRAWFilterStartDownload_block_invoke
+ ___CIRAWFilterStartDownload_block_invoke_2
+ ___CIRAWFilterStartDownload_block_invoke_3
+ ___RawCameraLibraryCore_block_invoke
+ ____ZN2CIL25fillBlockFromDataProviderEP14CGDataProvidermP11__IOSurface_block_invoke
+ ___block_descriptor_48_e8_32o40b_e5_v8?0ls40l8s32l8
+ ___block_descriptor_48_e8_32o40b_e8_v12?0B8ls40l8s32l8
+ ___block_descriptor_56_e8_32o40b48r_e17_v16?0"NSError"8ls32l8r48l8s40l8
+ ___block_descriptor_76_e23_v16?0r^{__IOSurface=}8l
+ ___getRCModelDownloadStartSymbolLoc_block_invoke
+ _audit_stringRawCamera
+ _getRCModelDownloadStartSymbolLoc
+ _getRCModelDownloadStartSymbolLoc.ptr
- GCC_except_table147
- GCC_except_table157
- GCC_except_table161
- GCC_except_table165
- GCC_except_table172
- GCC_except_table185
- GCC_except_table318
- GCC_except_table342
- GCC_except_table352
- __ZL27_cgImageProviderGetPropertyP15CGImageProviderPK10__CFString
- __ZN2CI6CGNode15restore_cgimageENS_10ImageIndexENS_22ImageLeafContentDigestEP7CGImagePU28objcproto17OS_dispatch_queue8NSObject
- __ZN2CI6CGNodeC1EiNS_10ImageIndexEP7CGImageNS_22ImageLeafContentDigestEPU28objcproto17OS_dispatch_queue8NSObjectNS_11PixelFormatENS_8EdgeModeEbb
- __ZN2CI6CGNodeC2EiNS_10ImageIndexEP7CGImageNS_22ImageLeafContentDigestEPU28objcproto17OS_dispatch_queue8NSObjectNS_11PixelFormatENS_8EdgeModeEbb
- ___62-[CIRAWFilter downloadResourcesWithTimeout:completionHandler:]_block_invoke
- ___65+[CIRAWFilter downloadAllResourcesWithTimeout:completionHandler:]_block_invoke
- ___block_descriptor_60_e23_v16?0r^{__IOSurface=}8l
CStrings:
+ "%{public}s Raw demosaic filter produced no image; the decoder's on-demand resources may be unavailable."
+ "%{public}s RawCamera is not available on this platform."
+ "%{public}s Unable to soft link RCModelDownloadStart from RawCamera."
+ "+[CIRAWFilter downloadAllResourcesWithTimeout:completionHandler:]"
+ "-[CIRAWFilter downloadResourcesWithTimeout:completionHandler:]"
+ "1667.40.5"
+ "CIRAWFilter.m"
+ "CIRAWFilterErrorDomain"
+ "Failed to access data provider bytes."
+ "Failed to download %@."
+ "NSProgress *CI_RCModelDownloadStart(uint32_t, int, void (^)(BOOL))"
+ "RCModelDownloadStart"
+ "Source data provider is nil."
+ "Timed out downloading %@."
+ "inputPattern"
+ "softlink:o:path:/System/Library/CoreServices/RawCamera.bundle/RawCamera"
+ "the RAW decoder resources"
+ "the resources required to decode this image"
+ "v16@?0@\"NSError\"8"
+ "void *RawCameraLibrary(void)"
- "1667.40.3"
- "Source image provider is nil."
- "_inputImage != nil"
```
