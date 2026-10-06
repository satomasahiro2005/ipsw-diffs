## CoreImage

> `/System/Library/Frameworks/CoreImage.framework/CoreImage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3497a0` | `0x349f6c` | **`+0x7cc`** |
| `__TEXT.__cstring` | `0x1049a8` | `0x104a1a` | **`+0x72`** |
| `__DATA_CONST.__const` | `0x64d8` | `0x6528` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x1858` | `0x1898` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xaf8` | `0xb20` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x2b4c0` | `0x2b4e0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x159b0` | `0x159d0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x8e50` | `0x8e68` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xa8a8` | `0xa8c0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xa868` | `0xa87c` | **`+0x14`** |
| `__TEXT.__oslogstring` | `0xb283` | `0xb275` | **`-0xe`** |

### Same-size Content Changes

- `__TEXT.__dlopen_cstrs`

### Other Changes

```diff

-1667.22.1.0.0
+1667.40.3.0.0

-  Functions: 15164
-  Symbols:   26333
-  CStrings:  8881
+  Functions: 15174
+  Symbols:   26357
+  CStrings:  8883
Symbols:
+ +[CIContextCache currentEntryCount]
+ +[CIContextCache peakEntryCount]
+ +[CIRAWFilter downloadAllResourcesWithTimeout:completionHandler:]
+ GCC_except_table280
+ GCC_except_table285
+ _CGColorSpaceContainsISO5Metadata
+ _CGColorSpaceCopyColorSyncProfile
+ _CGColorSpaceGetISO5Headroom
+ _ColorSyncProfileCopyData
+ _ColorSyncProfileCreate
+ _ColorSyncProfileCreateCopyWithISO5Metadata
+ _ColorSyncProfileGetCICPInfo
+ _ColorSyncProfileGetISO5AverageLightLevel
+ _GetSurfaceCacheEntryCount
+ _GetSurfaceCachePeakEntryCount
+ __ZL19CreateNewMTLTexturePU19objcproto9MTLDevice11objc_objectP11__IOSurfacej
+ __ZL21CCPortraitLibraryCorePPc
+ __ZN2CI44ColorSpaceCreateCopyWithISO5HeadroomMetadataEP12CGColorSpaceff
+ __ZN2CIL27pqOrExtendedRangeLightlevelEP12CGColorSpace
+ __ZNK2CI18TagColorSpaceImage10lightlevelEv
+ ___65+[CIRAWFilter downloadAllResourcesWithTimeout:completionHandler:]_block_invoke
+ ___GetSurfaceCacheEntryCount_block_invoke
+ ___GetSurfaceCachePeakEntryCount_block_invoke
+ _kColorSyncAverageLightLevel
+ _kColorSyncCLLInfo
+ _kColorSyncMaxLightLevel
+ _kColorSyncPrimaries
+ _kColorSyncReferenceWhite
- GCC_except_table144
- GCC_except_table279
- __ZNSt3__15dequeIPN2CI17SurfaceCacheEntryENS_9allocatorIS3_EEE26__maybe_remove_front_spareB9fqn220106Eb
- __ZNSt3__15dequeIPN2CI17SurfaceCacheEntryENS_9allocatorIS3_EEE9pop_frontEv
CStrings:
+ "1667.40.3"
+ "CGImage base address (%p) is not aligned to its pixel size (%lu bytes)!\n"
+ "Cannot get the provider from a CGImage.\n"
+ "Failed to load CoreImage.metallib from %{public}@: %{public}@\n"
+ "Failed to serialize CoreImage.metallib from %{public}@ to %{public}@: %{public}@\n"
+ "softlink:o:path:/System/Library/VideoProcessors/CCPortrait.bundle/CCPortrait"
- "%{public}s a CIImageProcessorInput with a empty region cannot be accessed via its base address."
- "1667.22.1"
- "Failed loading CoreImage.metallib from %{public}@: %{public}@\n"
- "softlink:r:path:/System/Library/VideoProcessors/CCPortrait.bundle/CCPortrait"
```
