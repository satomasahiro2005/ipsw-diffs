## AppleVideoEncoder

> `/System/Library/Video/Plug-Ins/AppleVideoEncoder.bundle/AppleVideoEncoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e181c` | `0x1e7f84` | **`+0x6768`** |
| `__TEXT.__cstring` | `0x58a3e` | `0x59d7c` | **`+0x133e`** |
| `__TEXT.__const` | `0x24ff8` | `0x25528` | **`+0x530`** |
| `__DATA_CONST.__const` | `0xd820` | `0xda90` | **`+0x270`** |
| `__DATA_CONST.__cfstring` | `0x3460` | `0x3520` | **`+0xc0`** |
| `__DATA.__bss` | `0x1058` | `0x1060` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x9e8` | `0x9f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-912.89.1.0.0
+913.8.0.0.0

-  Functions: 1938
+  Functions: 1958

-  CStrings:  7355
+  CStrings:  7437
CStrings:
+ "%5d, %4.6f, %4.6f, %4.6f, %f, %f, %f, %f, %f, %d, %d, %d, %d, %d, %d, %f\n"
+ "%lld %d AVE %s: %s Enter %d %d %d %d %p %d %d %d %p %p"
+ "%lld %d AVE %s: %s Enter %d %d %d %d %p %d %d %d %p %p\n"
+ "%lld %d AVE %s: %s Exit %d %d %d %d %p %d %d %d %p %p %d"
+ "%lld %d AVE %s: %s Exit %d %d %d %d %p %d %d %d %p %p %d\n"
+ "%lld %d AVE %s: %s MCTF %f %f %f %f %f %d %d %d 0x%08x %d 0x%08x %d %f"
+ "%lld %d AVE %s: %s MCTF %f %f %f %f %f %d %d %d 0x%08x %d 0x%08x %d %f\n"
+ "%lld %d AVE %s: %s:%d %p %lld eGatingType %d ePreFiltAdjType %d iEnableGating %d iEnableFeedback %d"
+ "%lld %d AVE %s: %s:%d %p %lld eGatingType %d ePreFiltAdjType %d iEnableGating %d iEnableFeedback %d\n"
+ "%lld %d AVE %s: %s:%d %p sID 0x%x G(%d,%d) F(%d,%d) gating %d feedback %d"
+ "%lld %d AVE %s: %s:%d %p sID 0x%x G(%d,%d) F(%d,%d) gating %d feedback %d\n"
+ "%lld %d AVE %s: %s:%d %p sID 0x%x prefilt adj type %d"
+ "%lld %d AVE %s: %s:%d %p sID 0x%x prefilt adj type %d\n"
+ "%lld %d AVE %s: %s:%d %s | AVE_MCTF_DecideEnableFlags failed %d"
+ "%lld %d AVE %s: %s:%d %s | AVE_MCTF_DecideEnableFlags failed %d\n"
+ "%lld %d AVE %s: %s:%d %s | AVE_MCTF_GetPreFiltAdjType failed %d"
+ "%lld %d AVE %s: %s:%d %s | AVE_MCTF_GetPreFiltAdjType failed %d\n"
+ "%lld %d AVE %s: %s:%d %s | DMV2 AVE_VerifyImageBuffer failed %p %dx%d %d"
+ "%lld %d AVE %s: %s:%d %s | DMV2 AVE_VerifyImageBuffer failed %p %dx%d %d\n"
+ "%lld %d AVE %s: %s:%d %s | DMV2 HiRes resolution not supported %dx%d"
+ "%lld %d AVE %s: %s:%d %s | DMV2 HiRes resolution not supported %dx%d\n"
+ "%lld %d AVE %s: %s:%d %s | DMV2 HiRes verify failed %d"
+ "%lld %d AVE %s: %s:%d %s | DMV2 HiRes verify failed %d\n"
+ "%lld %d AVE %s: %s:%d %s | DMV2 LoRes resolution not supported %dx%d"
+ "%lld %d AVE %s: %s:%d %s | DMV2 LoRes resolution not supported %dx%d\n"
+ "%lld %d AVE %s: %s:%d %s | DMV2 LoRes verify failed %d"
+ "%lld %d AVE %s: %s:%d %s | DMV2 LoRes verify failed %d\n"
+ "%lld %d AVE %s: %s:%d %s | DMV2 buffer size (%zux%zu) does not match expected (%dx%d)"
+ "%lld %d AVE %s: %s:%d %s | DMV2 buffer size (%zux%zu) does not match expected (%dx%d)\n"
+ "%lld %d AVE %s: %s:%d %s | DMV2 requires both LoRes and HiRes pixel buffers: %p %p"
+ "%lld %d AVE %s: %s:%d %s | DMV2 requires both LoRes and HiRes pixel buffers: %p %p\n"
+ "%lld %d AVE %s: %s:%d %s | DMV: CFDictionaryCreateMutable failed %lld"
+ "%lld %d AVE %s: %s:%d %s | DMV: CFDictionaryCreateMutable failed %lld\n"
+ "%lld %d AVE %s: %s:%d %s | out of range %p %lld %p %p %p 0x%x"
+ "%lld %d AVE %s: %s:%d %s | out of range %p %lld %p %p %p 0x%x\n"
+ "%lld %d AVE %s: %s:%d %s | tile resolution out of range %p %lld %dx%d (max width %d, max area %d)"
+ "%lld %d AVE %s: %s:%d %s | tile resolution out of range %p %lld %dx%d (max width %d, max area %d)\n"
+ "%lld %d AVE %s: %s:%d %s | wrong params, %p %d %d %d %p"
+ "%lld %d AVE %s: %s:%d %s | wrong params, %p %d %d %d %p\n"
+ "%lld %d AVE %s: %s:%d %s | wrong params, %p %d %d %d %p %p"
+ "%lld %d AVE %s: %s:%d %s | wrong params, %p %d %d %d %p %p\n"
+ "%lld %d AVE %s: %s:%d aperture = %d, param set type = %d"
+ "%lld %d AVE %s: %s:%d aperture = %d, param set type = %d\n"
+ "%lld %d AVE %s: %s::%s Enter %p %llu %lld %f %f %f %f %f %d %d %d 0x%08x %d 0x%08x %d %f"
+ "%lld %d AVE %s: %s::%s Enter %p %llu %lld %f %f %f %f %f %d %d %d 0x%08x %d 0x%08x %d %f\n"
+ "%lld %d AVE %s: %s::%s Exit %p %llu %lld %f %f %f %f %f %d %d %d 0x%08x %d 0x%08x %d %f %d"
+ "%lld %d AVE %s: %s::%s Exit %p %llu %lld %f %f %f %f %f %d %d %d 0x%08x %d 0x%08x %d %f %d\n"
+ "%lld %d AVE %s: Chained mode requires P-only GOP; zeroing B-frame count (was %d)"
+ "%lld %d AVE %s: Chained mode requires P-only GOP; zeroing B-frame count (was %d)\n"
+ "%lld %d AVE %s: received AVE_DMV_UseDMV (iMode) = %d"
+ "%lld %d AVE %s: received AVE_DMV_UseDMV (iMode) = %d\n"
+ "%s MCTF %f %f %f %f %f %d %d %d 0x%08x %d 0x%08x %d %f"
+ "%s MCTF %f %f %f %f %f %d %d %d 0x%08x %d 0x%08x %d %f\n"
+ "(int32_t)CVPixelBufferGetWidth(pImgBuf) == iExpectedWidth && (int32_t)CVPixelBufferGetHeight(pImgBuf) == iExpectedHeight"
+ "19:42:59"
+ "19:43:02"
+ "19:43:03"
+ "913.8.0"
+ "AVE_DMV_GetPerFrameData"
+ "AVE_DMV_HiResPixelBuffer"
+ "AVE_DMV_LoResPixelBuffer"
+ "AVE_MCTFEnableFeedback"
+ "AVE_MCTFEnableGating"
+ "AVE_MCTF_DecideEnableFlags"
+ "AVE_MCTF_GetPreFiltAdjType"
+ "AVE_PROPERTY_KEY_MCTF_ENABLE_FEEDBACK"
+ "AVE_PROPERTY_KEY_MCTF_ENABLE_GATING"
+ "AVE_PROPERTY_KEY_QPMOD_BLOCK_GRANULARITY"
+ "AVE_PreparePixelFormat"
+ "AVE_Prop_AV1_GetMCTFEnableFeedback"
+ "AVE_Prop_AV1_GetMCTFEnableGating"
+ "AVE_Prop_AV1_GetQPModBlockGranularity"
+ "AVE_Prop_AV1_SetMCTFEnableFeedback"
+ "AVE_Prop_AV1_SetMCTFEnableGating"
+ "AVE_Prop_AV1_SetQPModBlockGranularity"
+ "AVE_Prop_AVC_GetMCTFEnableFeedback"
+ "AVE_Prop_AVC_GetMCTFEnableGating"
+ "AVE_Prop_AVC_GetQPModBlockGranularity"
+ "AVE_Prop_AVC_SetMCTFEnableFeedback"
+ "AVE_Prop_AVC_SetMCTFEnableGating"
+ "AVE_Prop_AVC_SetQPModBlockGranularity"
+ "AVE_Prop_HEVC_GetMCTFEnableFeedback"
+ "AVE_Prop_HEVC_GetMCTFEnableGating"
+ "AVE_Prop_HEVC_GetQPModBlockGranularity"
+ "AVE_Prop_HEVC_SetMCTFEnableFeedback"
+ "AVE_Prop_HEVC_SetMCTFEnableGating"
+ "AVE_Prop_HEVC_SetQPModBlockGranularity"
+ "AVE_QPModBlockGranularity"
+ "CompressorPixelBufferAttributes != __null"
+ "DMVHiResInput"
+ "DMVLoResInput"
+ "Fnumber"
+ "Frame Number, SNR, NormalizedSNR, ExposureTime, AGC, ISPDGain, SensorDGain, RangeExpFactor, ScalingFactor, SensorID, LuxLevel, CamPortID, Band0Strength, QuadraBinningFactor, BayerBinningFactor, FNumber\n"
+ "Jun 18 2026"
+ "MCTFEnableFeedback"
+ "MCTFEnableFeedback = %d\n"
+ "MCTFEnableGating"
+ "MCTFEnableGating = %d\n"
+ "QPModBlockGranularity"
+ "TemporalNoiseReductionParamAdjust"
+ "iEnableFeedback >= -1 && iEnableFeedback <= 1"
+ "iEnableGating >= -1 && iEnableGating <= 1"
+ "iGranularity != 0 && (iGranularity & ~0xFU) == 0"
+ "pDim->iWidth > 0 && pDim->iHeight > 0 && pDim->iWidth <= 4096 && (int64_t)pDim->iWidth * pDim->iHeight <= (4096 * 2304)"
+ "pLoResBuf != __null && pHiResBuf != __null"
+ "psData != __null && eDevType > AVE_DevType_None && eDevType < AVE_DevType_Max && eWorkMode > AVE_MCTF_WorkMode_None && eWorkMode < AVE_MCTF_WorkMode_Max && eLatencyMode > AVE_MCTF_Mode_Invalid && eLatencyMode < AVE_MCTF_Mode_Max && pbEnableGating != __null && pbEnableFeedback != __null"
+ "psData != __null && eDevType > AVE_DevType_None && eDevType < AVE_DevType_Max && eWorkMode > AVE_MCTF_WorkMode_None && eWorkMode < AVE_MCTF_WorkMode_Max && eLatencyMode > AVE_MCTF_Mode_Invalid && eLatencyMode < AVE_MCTF_Mode_Max && pePreFiltAdjType != __null"
- "%5d, %4.6f, %4.6f, %4.6f, %f, %f, %f, %f, %f, %d, %d, %d, %d\n"
- "%lld %d AVE %s: %s MCTF %f %f %f %f %f %d %d %d 0x%08x %d"
- "%lld %d AVE %s: %s MCTF %f %f %f %f %f %d %d %d 0x%08x %d\n"
- "%lld %d AVE %s: %s:%d %p %lld eGatingType %d"
- "%lld %d AVE %s: %s:%d %p %lld eGatingType %d\n"
- "%lld %d AVE %s: %s:%d %s | DMV: fail to create dict %lld %d"
- "%lld %d AVE %s: %s:%d %s | DMV: fail to create dict %lld %d\n"
- "%lld %d AVE %s: %s::%s Enter %p %llu %lld %f %f %f %f %f %d %d %d 0x08%x %d"
- "%lld %d AVE %s: %s::%s Enter %p %llu %lld %f %f %f %f %f %d %d %d 0x08%x %d\n"
- "%lld %d AVE %s: %s::%s Exit %p %llu %lld %f %f %f %f %f %d %d %d 0x08%x %d %d"
- "%lld %d AVE %s: %s::%s Exit %p %llu %lld %f %f %f %f %f %d %d %d 0x08%x %d %d\n"
- "%lld %d AVE %s: Register AV1 video encoder of AVE %d"
- "%lld %d AVE %s: Register AV1 video encoder of AVE %d\n"
- "%s MCTF %f %f %f %f %f %d %d %d 0x%08x %d"
- "%s MCTF %f %f %f %f %f %d %d %d 0x%08x %d\n"
- "21:29:37"
- "21:29:39"
- "21:29:40"
- "21:29:41"
- "912.89.1"
- "AVE_Plugin_AV1_Register"
- "Frame Number, SNR, NormalizedSNR, ExposureTime, AGC, ISPDGain, SensorDGain, RangeExpFactor, ScalingFactor, SensorID, LuxLevel, CamPortID, Band0Strength\n"
- "IOSurfaceProperties"
- "Jun  1 2026"
- "com.apple.videotoolbox.videoencoder.av1"
```
