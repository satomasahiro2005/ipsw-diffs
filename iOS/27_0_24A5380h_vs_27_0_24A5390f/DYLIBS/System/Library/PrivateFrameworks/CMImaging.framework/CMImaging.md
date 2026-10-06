## CMImaging

> `/System/Library/PrivateFrameworks/CMImaging.framework/CMImaging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1da208` | `0x1da510` | **`+0x308`** |
| `__TEXT.__cstring` | `0x28b23` | `0x28bdb` | **`+0xb8`** |
| `__AUTH_CONST.__cfstring` | `0x6be0` | `0x6c20` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x1f118` | `0x1f158` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xc48` | `0xc58` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x17d4` | `0x17dc` | **`+0x8`** |

### Other Changes

```diff

-758.0.0.122.2
+761.0.0.0.3

-  Symbols:   8769
-  CStrings:  5293
+  Symbols:   8773
+  CStrings:  5295
Symbols:
+ _OBJC_IVAR_$_CMIStyleEngineApplyStyle._skinMaskPurpose
+ _OBJC_IVAR_$_CMIStyleEngineProcessor._skinMaskPurpose
+ _kFigCaptureSampleBufferMetadata_IntermediateZoomDstRect
+ _kFigCaptureSampleBufferMetadata_IntermediateZoomSrcRect
CStrings:
+ "%@ColorPrimaries:%@, YCbCrMatrix:%@, TransferFunction:%@"
+ "( inputTexture.pixelFormat == outputTexture.pixelFormat ) || ( [CMIGuidedFilter isSingleChannelTexture:inputTexture] && [CMIGuidedFilter isSingleChannelTexture:outputTexture] )"
+ "N/A"
+ "err = FigSignalErrorAt3(\"%s%s%s signalled err=%d (%s) (%s) at %s:%d\", gStyleEngineProcessorTrace.note.emitter, (CMIStyleEngineStatusResourcesNotReleased), \"CMIStyleEngineStatusResourcesNotReleased\", (\"FigMetalAllocator resources not correctly released\"), \"<<<< StyleEngineProcessor >>>>\", __FUNCTION__, \"CMIStyleEngineProcessor.m\", 3625, __builtin_return_address(0), 0) == 0 "
- "err = FigSignalErrorAt3(\"%s%s%s signalled err=%d (%s) (%s) at %s:%d\", gStyleEngineProcessorTrace.note.emitter, (CMIStyleEngineStatusResourcesNotReleased), \"CMIStyleEngineStatusResourcesNotReleased\", (\"FigMetalAllocator resources not correctly released\"), \"<<<< StyleEngineProcessor >>>>\", __FUNCTION__, \"CMIStyleEngineProcessor.m\", 3586, __builtin_return_address(0), 0) == 0 "
- "inputTexture.pixelFormat == outputTexture.pixelFormat"
```
