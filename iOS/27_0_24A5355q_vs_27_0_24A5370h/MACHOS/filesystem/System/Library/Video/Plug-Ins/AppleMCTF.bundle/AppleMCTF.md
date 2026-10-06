## AppleMCTF

> `/System/Library/Video/Plug-Ins/AppleMCTF.bundle/AppleMCTF`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83afc` | `0x85ea4` | **`+0x23a8`** |
| `__TEXT.__cstring` | `0x27544` | `0x2809a` | **`+0xb56`** |
| `__TEXT.__const` | `0x22588` | `0x22ab8` | **`+0x530`** |
| `__DATA_CONST.__cfstring` | `0x880` | `0x940` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x5300` | `0x53b0` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x658` | `0x668` | **`+0x10`** |
| `__DATA.__bss` | `0x8c8` | `0x8d0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-912.89.1.0.0
+913.8.0.0.0

-  Functions: 662
+  Functions: 668

-  CStrings:  3364
+  CStrings:  3412
CStrings:
+ "%5d, %4.6f, %4.6f, %4.6f, %f, %f, %f, %f, %f, %d, %d, %d, %d, %d, %d, %f\n"
+ "%lld %d AVE %s: %s Enter %d %d %d %d %p %d %d %d %p %p"
+ "%lld %d AVE %s: %s Enter %d %d %d %d %p %d %d %d %p %p\n"
+ "%lld %d AVE %s: %s Exit %d %d %d %d %p %d %d %d %p %p %d"
+ "%lld %d AVE %s: %s Exit %d %d %d %d %p %d %d %d %p %p %d\n"
+ "%lld %d AVE %s: %s MCTF %f %f %f %f %f %d %d %d 0x%08x %d 0x%08x %d %f"
+ "%lld %d AVE %s: %s MCTF %f %f %f %f %f %d %d %d 0x%08x %d 0x%08x %d %f\n"
+ "%lld %d AVE %s: %s:%d  [%d] pMCTF = %p %lld, output CVPixelFormatType = %d %lu x %lu, Strength = %d, AlgoAdj = 0x%08x, NumRefs = %d, ParamAdj = 0x%08x"
+ "%lld %d AVE %s: %s:%d  [%d] pMCTF = %p %lld, output CVPixelFormatType = %d %lu x %lu, Strength = %d, AlgoAdj = 0x%08x, NumRefs = %d, ParamAdj = 0x%08x\n"
+ "%lld %d AVE %s: %s:%d %p %lld eGatingType %d ePreFiltAdjType %d iEnableGating %d iEnableFeedback %d"
+ "%lld %d AVE %s: %s:%d %p %lld eGatingType %d ePreFiltAdjType %d iEnableGating %d iEnableFeedback %d\n"
+ "%lld %d AVE %s: %s:%d %p sID 0x%x G(%d,%d) F(%d,%d) gating %d feedback %d"
+ "%lld %d AVE %s: %s:%d %p sID 0x%x G(%d,%d) F(%d,%d) gating %d feedback %d\n"
+ "%lld %d AVE %s: %s:%d %p sID 0x%x prefilt adj type %d"
+ "%lld %d AVE %s: %s:%d %p sID 0x%x prefilt adj type %d\n"
+ "%lld %d AVE %s: %s:%d %s | AVE_MCTF_DecideEnableFlags failed %p %p %lld %d"
+ "%lld %d AVE %s: %s:%d %s | AVE_MCTF_DecideEnableFlags failed %p %p %lld %d\n"
+ "%lld %d AVE %s: %s:%d %s | AVE_MCTF_GetPreFiltAdjType failed %p %p %lld %d"
+ "%lld %d AVE %s: %s:%d %s | AVE_MCTF_GetPreFiltAdjType failed %p %p %lld %d\n"
+ "%lld %d AVE %s: %s:%d %s | fail to create CFNumber for %p iParamSetType %u"
+ "%lld %d AVE %s: %s:%d %s | fail to create CFNumber for %p iParamSetType %u\n"
+ "%lld %d AVE %s: %s:%d %s | fail to create pMctfParamAdj for %p"
+ "%lld %d AVE %s: %s:%d %s | fail to create pMctfParamAdj for %p\n"
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
+ "%s MCTF %f %f %f %f %f %d %d %d 0x%08x %d 0x%08x %d %f"
+ "%s MCTF %f %f %f %f %f %d %d %d 0x%08x %d 0x%08x %d %f\n"
+ "19:43:30"
+ "913.8.0"
+ "AVE_MCTFEnableFeedback"
+ "AVE_MCTFEnableGating"
+ "AVE_MCTF_DecideEnableFlags"
+ "AVE_MCTF_GetPreFiltAdjType"
+ "AVE_PROPERTY_KEY_MCTF_ENABLE_FEEDBACK"
+ "AVE_PROPERTY_KEY_MCTF_ENABLE_GATING"
+ "AVE_Prop_MCTF_GetMCTFEnableFeedback"
+ "AVE_Prop_MCTF_GetMCTFEnableGating"
+ "AVE_Prop_MCTF_SetMCTFEnableFeedback"
+ "AVE_Prop_MCTF_SetMCTFEnableGating"
+ "AVE_QPModBlockGranularity"
+ "DMVHiResInput"
+ "DMVLoResInput"
+ "Fnumber"
+ "Frame Number, SNR, NormalizedSNR, ExposureTime, AGC, ISPDGain, SensorDGain, RangeExpFactor, ScalingFactor, SensorID, LuxLevel, CamPortID, Band0Strength, QuadraBinningFactor, BayerBinningFactor, FNumber\n"
+ "GatingVersion"
+ "Jun 18 2026"
+ "MCTFEnableFeedback"
+ "MCTFEnableFeedback = %d\n"
+ "MCTFEnableGating"
+ "MCTFEnableGating = %d\n"
+ "ParamAdjustment"
+ "ParamSetType"
+ "TemporalNoiseReductionParamAdjust"
+ "iEnableFeedback >= -1 && iEnableFeedback <= 1"
+ "iEnableGating >= -1 && iEnableGating <= 1"
+ "pMctfParamAdj != __null"
+ "psData != __null && eDevType > AVE_DevType_None && eDevType < AVE_DevType_Max && eWorkMode > AVE_MCTF_WorkMode_None && eWorkMode < AVE_MCTF_WorkMode_Max && eLatencyMode > AVE_MCTF_Mode_Invalid && eLatencyMode < AVE_MCTF_Mode_Max && pbEnableGating != __null && pbEnableFeedback != __null"
+ "psData != __null && eDevType > AVE_DevType_None && eDevType < AVE_DevType_Max && eWorkMode > AVE_MCTF_WorkMode_None && eWorkMode < AVE_MCTF_WorkMode_Max && eLatencyMode > AVE_MCTF_Mode_Invalid && eLatencyMode < AVE_MCTF_Mode_Max && pePreFiltAdjType != __null"
- "%5d, %4.6f, %4.6f, %4.6f, %f, %f, %f, %f, %f, %d, %d, %d, %d\n"
- "%lld %d AVE %s: %s MCTF %f %f %f %f %f %d %d %d 0x%08x %d"
- "%lld %d AVE %s: %s MCTF %f %f %f %f %f %d %d %d 0x%08x %d\n"
- "%lld %d AVE %s: %s:%d  [%d] pMCTF = %p %lld, output CVPixelFormatType = %d %lu x %lu, Strength = %d, AlgoAdj = 0x%08x, NumRefs = %d"
- "%lld %d AVE %s: %s:%d  [%d] pMCTF = %p %lld, output CVPixelFormatType = %d %lu x %lu, Strength = %d, AlgoAdj = 0x%08x, NumRefs = %d\n"
- "%lld %d AVE %s: %s:%d %p %lld eGatingType %d"
- "%lld %d AVE %s: %s:%d %p %lld eGatingType %d\n"
- "%lld %d AVE %s: %s::%s Enter %p %llu %lld %f %f %f %f %f %d %d %d 0x08%x %d"
- "%lld %d AVE %s: %s::%s Enter %p %llu %lld %f %f %f %f %f %d %d %d 0x08%x %d\n"
- "%lld %d AVE %s: %s::%s Exit %p %llu %lld %f %f %f %f %f %d %d %d 0x08%x %d %d"
- "%lld %d AVE %s: %s::%s Exit %p %llu %lld %f %f %f %f %f %d %d %d 0x08%x %d %d\n"
- "%s MCTF %f %f %f %f %f %d %d %d 0x%08x %d"
- "%s MCTF %f %f %f %f %f %d %d %d 0x%08x %d\n"
- "21:29:58"
- "912.89.1"
- "Frame Number, SNR, NormalizedSNR, ExposureTime, AGC, ISPDGain, SensorDGain, RangeExpFactor, ScalingFactor, SensorID, LuxLevel, CamPortID, Band0Strength\n"
- "Jun  1 2026"
- "iGatingVersion"
```
