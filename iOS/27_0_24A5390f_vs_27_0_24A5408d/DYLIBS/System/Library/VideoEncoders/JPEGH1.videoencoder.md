## JPEGH1.videoencoder

> `/System/Library/VideoEncoders/JPEGH1.videoencoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3728` | `0x220c` | **`-0x151c`** |
| `__TEXT.__oslogstring` | `0x5a8` | `—` | **`-0x5a8`** |
| `__TEXT.__cstring` | `0x4df` | `0x10c` | **`-0x3d3`** |
| `__AUTH_CONST.__cfstring` | `0x100` | `0xc0` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x300` | `0x2d0` | **`-0x30`** |
| `__TEXT.__const` | `0x40` | `0x10` | **`-0x30`** |
| `__DATA.__common` | `0x20` | `—` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0xd8` | `0xc8` | **`-0x10`** |

### Other Changes

```diff

-3350.71.2.11.1
+3350.75.2.0.0

-  Functions: 42
-  Symbols:   176
-  CStrings:  64
+  Functions: 28
+  Symbols:   163
+  CStrings:  12
Symbols:
+ _FigSignalErrorAtGM
+ _H1JPEGEncoder_StartSession.sRateControllerMBitCap
+ _H1JPEGEncoder_StartSession.sRateControllerWindowSizeFrames
+ _fig_log_get_emitter
- _FigGetUpTime
- _FigHostTimeToNanoseconds
- _FigSignalErrorAt3
- _OUTLINED_FUNCTION_0
- _OUTLINED_FUNCTION_1
- _OUTLINED_FUNCTION_2
- _OUTLINED_FUNCTION_3
- _OUTLINED_FUNCTION_4
- _OUTLINED_FUNCTION_5
- __MergedGlobals
- __os_log_send_and_compose_impl
- _fig_log_call_emit_and_clean_up_after_send_and_compose
- _fig_log_emitter_get_os_log_and_send_and_compose_flags_and_os_log_type
- _fig_note_initialize_category_with_default_work_cf
- _gFigJPEGEncoderRateController
- _gFigJPEGVTEncoderTrace
- _os_log_type_enabled
CStrings:
+ "%s signalled err=%d at <>:%d"
- "%s%s%s signalled err=%d (%s) (%s) at %s:%d"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMedia_VideoToolbox/Sources/JPEGH1Codec/JPEGH1Encoder.c"
- "<-<<< JPEGEncoderRateController >>>-> %s: Init Index %d, bitrate %d"
- "<-<<< JPEGEncoderRateController >>>-> %s: frame_bits %d framerate %d"
- "<-<<< JPEGEncoderRateController >>>-> %s: frame_bits_prev %d < wanted_bits %d deltaIndex (+%d +%d) Index (%d %d)"
- "<-<<< JPEGEncoderRateController >>>-> %s: frame_bits_prev %d > wanted_bits %d deltaIndex (-%d -%d) Index (%d %d)"
- "<-<<< JPEGEncoderRateController >>>-> %s: presentationTimeStamp_curr.value %lld presentationTimeStamp_curr.timescale %d"
- "<-<<< JPEGEncoderRateController >>>-> %s: presentationTimeStamp_prev.value %lld presentationTimeStamp_prev.timescale %d"
- "<-<<< JPEGVTEncoder >>>-> %s: Could not open connection to jpeg driver"
- "<-<<< JPEGVTEncoder >>>-> %s: Emit Frame %d Start"
- "<-<<< JPEGVTEncoder >>>-> %s: Emit Frame %d Stop"
- "<-<<< JPEGVTEncoder >>>-> %s: Encode Result: %d, time: %.1f ms, surface size: %d, quality: %d (%d)"
- "<-<<< JPEGVTEncoder >>>-> %s: Frame %d"
- "<-<<< JPEGVTEncoder >>>-> %s: Frame %d Finish Encode"
- "<-<<< JPEGVTEncoder >>>-> %s: Frame %d Finish Preproc"
- "<-<<< JPEGVTEncoder >>>-> %s: Frame %d Start Encode"
- "<-<<< JPEGVTEncoder >>>-> %s: Frame %d Start Preproc"
- "<-<<< JPEGVTEncoder >>>-> %s: Input pixelBuffer is not IOSurface backed"
- "<-<<< JPEGVTEncoder >>>-> %s: Waiting for previous frame to finish encoding to ensure in-order emits..."
- "<-<<< JPEGVTEncoder >>>-> %s: rate controller DISABLED"
- "<-<<< JPEGVTEncoder >>>-> %s: rate controller enabled, max Mbps: %d, window size (frames): %d"
- "<-<<< JPEGVTEncoder >>>-> Fig"
- "CFDictionaryCreate failed"
- "CFDictionaryCreate failed (once)"
- "FigDerivedObjectCreate failed"
- "H1JPEGEncoder_CheckExistence"
- "H1JPEGEncoder_CopyProperty"
- "H1JPEGEncoder_CopySupportedPropertyDictionary"
- "H1JPEGEncoder_CreateInstance"
- "H1JPEGEncoder_EncodeFrame"
- "H1JPEGEncoder_SetProperty"
- "H1JPEGEncoder_StartSession"
- "JPEGH1Encoder.c"
- "bad quality"
- "bad quality value"
- "err"
- "failed to obtain encodedBuffer struct"
- "hardware jpeg encode failed"
- "ioErr"
- "jpegEncoder_createSupportedPropertyDictionary"
- "jpeg_emitEncodedFrame"
- "jpeg_encodeFrameAsyncInternal"
- "jpeg_encodeFrameSync"
- "jpeg_encoder_rc_trace"
- "jpeg_vtencoder_trace"
- "kVTAllocationFailedErr"
- "kVTParameterErr"
- "kVTPropertyNotSupportedErr"
- "openJPEGDriverUserClientConnection"
- "stevenote_accumulate"
- "stevenote_rc_init"
- "stevenote_rc_update_index"
- "unrecognised property key"
```
