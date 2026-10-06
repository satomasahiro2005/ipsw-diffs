## JPEGH1.videodecoder

> `/System/Library/VideoDecoders/JPEGH1.videodecoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43b0` | `0x2ea0` | **`-0x1510`** |
| `__TEXT.__oslogstring` | `0x630` | `—` | **`-0x630`** |
| `__TEXT.__cstring` | `0x67c` | `0xe7` | **`-0x595`** |
| `__AUTH_CONST.__cfstring` | `0xa0` | `0x60` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x390` | `0x368` | **`-0x28`** |
| `__TEXT.__const` | `0x54` | `0x34` | **`-0x20`** |
| `__DATA_DIRTY.__common` | `0x10` | `—` | **`-0x10`** |

### Other Changes

```diff

-3385.8.1.11.1
+3385.12.1.0.0

-  Functions: 58
-  Symbols:   225
-  CStrings:  77
+  Functions: 41
+  Symbols:   203
+  CStrings:  11
Symbols:
+ _FigSignalErrorAtGM
+ _fig_log_get_emitter
- _FigHostTimeToNanoseconds
- _FigSignalErrorAt3
- _OUTLINED_FUNCTION_10
- _OUTLINED_FUNCTION_11
- _OUTLINED_FUNCTION_12
- _OUTLINED_FUNCTION_13
- _OUTLINED_FUNCTION_14
- _OUTLINED_FUNCTION_15
- _OUTLINED_FUNCTION_16
- _OUTLINED_FUNCTION_17
- _OUTLINED_FUNCTION_18
- _OUTLINED_FUNCTION_19
- _OUTLINED_FUNCTION_20
- _OUTLINED_FUNCTION_5
- _OUTLINED_FUNCTION_6
- _OUTLINED_FUNCTION_7
- _OUTLINED_FUNCTION_8
- _OUTLINED_FUNCTION_9
- __os_log_send_and_compose_impl
- _fig_log_call_emit_and_clean_up_after_send_and_compose
- _fig_log_emitter_get_os_log_and_send_and_compose_flags_and_os_log_type
- _fig_note_initialize_category_with_default_work_cf
- _gFigJPEGVTDecoderTrace
- _os_log_type_enabled
CStrings:
+ "%s signalled err=%d at <>:%d"
- "%s%s%s signalled err=%d (%s) (%s) at %s:%d"
- "<-<<< JPEGVTDecoder >>>-> %s: Could not create H1JPEG software fallback session"
- "<-<<< JPEGVTDecoder >>>-> %s: Decode complete for frame %d, total decode time: %.3f ms"
- "<-<<< JPEGVTDecoder >>>-> %s: Frame %d"
- "<-<<< JPEGVTDecoder >>>-> %s: Hardware decoder failed"
- "<-<<< JPEGVTDecoder >>>-> %s: Postprocessing complete for frame %d (took %.3f ms)"
- "<-<<< JPEGVTDecoder >>>-> %s: Received decoded frame from SW!"
- "<-<<< JPEGVTDecoder >>>-> %s: Requested frame delivery rate of %f"
- "<-<<< JPEGVTDecoder >>>-> %s: Software decode looks good, giving up on hardware decode"
- "<-<<< JPEGVTDecoder >>>-> %s: Software decoder failed, status = %d"
- "<-<<< JPEGVTDecoder >>>-> %s: VTSessionSetProperty(%@) returned err = %d"
- "<-<<< JPEGVTDecoder >>>-> %s: Waiting on pending frames to complete"
- "<-<<< JPEGVTDecoder >>>-> %s: We gave up on the hardware decoder; going straight to software"
- "<-<<< JPEGVTDecoder >>>-> %s: called async for frame %d"
- "<-<<< JPEGVTDecoder >>>-> %s: creating cached input surface %d of size %d bytes"
- "<-<<< JPEGVTDecoder >>>-> %s: performing hardware decode"
- "<-<<< JPEGVTDecoder >>>-> %s: performing software decode"
- "<-<<< JPEGVTDecoder >>>-> %s: waiting for temp422Int surface to become available"
- "<<<< H2JPEGDeviceInterface >>>> %s: WARNING: Got error code %d (0x%08X) when opening JPEG HW codec service. May fall back to using SW codec."
- "<<<< H2JPEGDeviceInterface >>>> %s: WARNING: Got error code kIOReturnNotPermitted when opening JPEG HW codec service. You may need to add AppleJPEGDriverUserClient to your entitlements. See 60229261 for more information. May fall back to using SW codec."
- "CFArrayCreate failed"
- "CFDictionaryCreate failed"
- "CFDictionaryCreate failed (once)"
- "CFNumberCreate failed"
- "Couldn't open driver connection"
- "Failed allocating attributes dictionary"
- "FigDerivedObjectCreate failed"
- "H1JPEG decode failed"
- "H1JPEGVideoDecoder_CopyProperty"
- "H1JPEGVideoDecoder_CopySupportedPropertyDictionary"
- "H1JPEGVideoDecoder_CreateInstance"
- "H1JPEGVideoDecoder_DecodeFrame"
- "H1JPEGVideoDecoder_Invalidate"
- "H1JPEGVideoDecoder_SetProperty"
- "H1JPEGVideoDecoder_StartSession"
- "JPEGH1Decoder.c"
- "ReducedFrameDelivery out of range 0.0...1.0"
- "Stevenote mode not supported on this platform (must not require strict MCU)"
- "VTDecoderSessionCreatePixelBuffer failed"
- "_openDriverConnection"
- "bad property value - should be CFNumber"
- "createJPEGInputSurface"
- "createPixelBufferAttributesDictionary"
- "decode failed"
- "err"
- "height must be >16"
- "jpeg_DecodeFrameAsynchronously"
- "jpeg_DecodeFrameSynchronously"
- "jpeg_DecodeFrameSynchronously_block_invoke"
- "jpeg_asyncDecodeComplete"
- "jpeg_createQualityOfServiceTier"
- "jpeg_createSuggestedQualityOfServiceTiers"
- "jpeg_createSupportedPropertyDictionary"
- "jpeg_initializeStevenote444fMode"
- "jpeg_vtdecoder_trace"
- "kVTAllocationFailedErr"
- "kVTParameterErr"
- "kVTPropertyNotSupportedErr"
- "kVTPropertyReadOnlyErr"
- "kVTVideoDecoderNotAvailableNowErr"
- "kVTVideoDecoderUnsupportedDataFormatErr"
- "property is read-only"
- "result"
- "special444fMode requires async decompression!"
- "temp422IntSurface creation failed"
- "unrecognised property key"
- "width must be >32"
```
