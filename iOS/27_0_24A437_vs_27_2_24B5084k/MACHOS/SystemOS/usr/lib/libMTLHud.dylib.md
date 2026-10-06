## libMTLHud.dylib

> `/usr/lib/libMTLHud.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3181c` | `0x319d4` | **`+0x1b8`** |
| `__TEXT.__objc_methname` | `0x4a31` | `0x4a0c` | **`-0x25`** |
| `__DATA_CONST.__cfstring` | `0x3460` | `0x3480` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x3ba0` | `0x3bc0` | **`+0x20`** |
| `__DATA.__objc_const` | `0x34b0` | `0x3498` | **`-0x18`** |
| `__TEXT.__auth_stubs` | `0xcc0` | `0xcd0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1d0c` | `0x1d1c` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x213c` | `0x2148` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x678` | `0x680` | **`+0x8`** |
| `__TEXT.__cstring` | `0x79c6` | `0x79cd` | **`+0x7`** |
| `__DATA.__objc_ivar` | `0x1f8` | `0x1f4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__thread_vars`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-5.0.24.0.0
+5.0.26.0.0

-  Symbols:   2268
+  Symbols:   2269
Symbols:
+ _CFStringFind
+ __Z15_HUDUIDrawFrameP12HUDUIOverlayPU27objcproto16MTLCommandBuffer11objc_objectPKPU21objcproto10MTLTexture11objc_objectiS4_13MTLLoadActionbmbPU18objcproto8MTLEvent11objc_objectS9_yfbbU13block_pointerFvPU34objcproto23MTLRenderCommandEncoder11objc_objectEU13block_pointerFvvE
+ __Z28HUDUIOverlayGetPipelineStateP12HUDUIOverlayPU21objcproto10MTLTexture11objc_objectbbb
+ __ZL36_HUDUIFrameGetCompositeSourceTextureP10HUDUIFrame14MTLPixelFormatbb
+ ____Z15_HUDUIDrawFrameP12HUDUIOverlayPU27objcproto16MTLCommandBuffer11objc_objectPKPU21objcproto10MTLTexture11objc_objectiS4_13MTLLoadActionbmbPU18objcproto8MTLEvent11objc_objectS9_yfbbU13block_pointerFvPU34objcproto23MTLRenderCommandEncoder11objc_objectEU13block_pointerFvvE_block_invoke
+ ____ZL19_HUDUIBlitFrameMTL4P12HUDUIOverlayPU27objcproto16MTL4CommandQueue11objc_objectPU21objcproto10MTLTexture11objc_object13MTLLoadActionPU18objcproto8MTLEvent11objc_objectyU13block_pointerFvPU35objcproto24MTL4RenderCommandEncoder11objc_objectPU26objcproto15MTLResidencySet11objc_objectEU13block_pointerFvvEbb_block_invoke
+ _objc_msgSend$metalFXFrameInterpolatorDisable
- OBJC_IVAR_$_HUDMTLLayerTracking._metalFXFrameInterpolatorWaitCounter
- __Z15_HUDUIDrawFrameP12HUDUIOverlayPU27objcproto16MTLCommandBuffer11objc_objectPKPU21objcproto10MTLTexture11objc_objectiS4_13MTLLoadActionbmbPU18objcproto8MTLEvent11objc_objectS9_yfbU13block_pointerFvPU34objcproto23MTLRenderCommandEncoder11objc_objectEU13block_pointerFvvE
- __Z28HUDUIOverlayGetPipelineStateP12HUDUIOverlayPU21objcproto10MTLTexture11objc_objectbb
- __ZL36_HUDUIFrameGetCompositeSourceTextureP10HUDUIFrame14MTLPixelFormat
- ____Z15_HUDUIDrawFrameP12HUDUIOverlayPU27objcproto16MTLCommandBuffer11objc_objectPKPU21objcproto10MTLTexture11objc_objectiS4_13MTLLoadActionbmbPU18objcproto8MTLEvent11objc_objectS9_yfbU13block_pointerFvPU34objcproto23MTLRenderCommandEncoder11objc_objectEU13block_pointerFvvE_block_invoke
- ____ZL19_HUDUIBlitFrameMTL4P12HUDUIOverlayPU27objcproto16MTL4CommandQueue11objc_objectPU21objcproto10MTLTexture11objc_object13MTLLoadActionPU18objcproto8MTLEvent11objc_objectyU13block_pointerFvPU35objcproto24MTL4RenderCommandEncoder11objc_objectPU26objcproto15MTLResidencySet11objc_objectEU13block_pointerFvvEb_block_invoke
Functions:
~ -[HUDMTLLayerTracking _snapshotDrawable:] : 708 -> 828
~ -[HUDMTLLayerOverlay layerTracking:presentDrawable:mtl4Queue:] : 2736 -> 2816
~ __Z28HUDUIOverlayGetPipelineStateP12HUDUIOverlayPU21objcproto10MTLTexture11objc_objectbb -> __Z28HUDUIOverlayGetPipelineStateP12HUDUIOverlayPU21objcproto10MTLTexture11objc_objectbbb : 1464 -> 1516
~ __ZL36_HUDUIFrameGetCompositeSourceTextureP10HUDUIFrame14MTLPixelFormat -> __ZL36_HUDUIFrameGetCompositeSourceTextureP10HUDUIFrame14MTLPixelFormatbb : 128 -> 180
~ __Z15_HUDUIDrawFrameP12HUDUIOverlayPU27objcproto16MTLCommandBuffer11objc_objectPKPU21objcproto10MTLTexture11objc_objectiS4_13MTLLoadActionbmbPU18objcproto8MTLEvent11objc_objectS9_yfbU13block_pointerFvPU34objcproto23MTLRenderCommandEncoder11objc_objectEU13block_pointerFvvE -> __Z15_HUDUIDrawFrameP12HUDUIOverlayPU27objcproto16MTLCommandBuffer11objc_objectPKPU21objcproto10MTLTexture11objc_objectiS4_13MTLLoadActionbmbPU18objcproto8MTLEvent11objc_objectS9_yfbbU13block_pointerFvPU34objcproto23MTLRenderCommandEncoder11objc_objectEU13block_pointerFvvE : 1652 -> 1656
~ _HUDUIDrawFrames : 3032 -> 3096
~ ____ZL22_HUDUIBlitFramesMetal4P12HUDUIOverlayPU27objcproto16MTL4CommandQueue11objc_objectPU21objcproto10MTLTexture11objc_objectP17HUDUIFrameContextjPU18objcproto8MTLEvent11objc_objectyU13block_pointerFvvE_block_invoke : 1092 -> 1120
~ ____ZL22_HUDUIBlitFramesMetal3P12HUDUIOverlayPU21objcproto10MTLTexture11objc_objectS2_P17HUDUIFrameContextjmPU18objcproto8MTLEvent11objc_objectyU13block_pointerFvvE_block_invoke : 628 -> 680
~ -[MTLHUDService metalFXFrameInterpolatorEncodingEndNoDirectObject:] : 264 -> 252
CStrings:
+ "Linear"
- "_metalFXFrameInterpolatorWaitCounter"
```
