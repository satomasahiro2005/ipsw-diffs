## com.apple.driver.AppleProResHW

> `com.apple.driver.AppleProResHW`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x4e148` | `0x502d0` | **`+0x2188`** |
| `__DATA_CONST.__const` | `0xb190` | `0xba28` | **`+0x898`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x5e0` | **`+0x5e0`** |
| `__TEXT.__os_log` | `0x9ab8` | `0x9d00` | **`+0x248`** |
| `__TEXT.__const` | `0x2378` | `0x23a8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x112a` | `0x114b` | **`+0x21`** |
| `__DATA.__data` | `0x448` | `0x458` | **`+0x10`** |

### Other Changes

```diff

-600.24.1.0.0
-  Functions: 2758
+600.38.0.0.0
+  Functions: 2818

-  CStrings:  553
+  CStrings:  563
CStrings:
+ "121111121222121211221111211111121111112111111211222211112222211112111111211111121111112111111111111111111111111111111121121121121111111111111111111111111111111111111111111111111111111111111111111112222222222222222221111111222221111111111111111212222211112"
+ "AppleProResHW (0x%x): %s(): CurrentClient->perfMode %d pDecodeFrame->perfMode %d\n"
+ "AppleProResHW (0x%x): %s(): ERROR: SPARE readback 0x%x != 0x%x, coreIdx %d\n"
+ "AppleProResHW (0x%x): %s(): TopVersion %u (0x%x) published to IORegistry\n"
+ "AppleProResHW (0x%x): %s(): TopVersion not published: HW verification failed\n"
+ "AppleProResHW (0x%x): %s(): coreIdx %d topVersion 0x%x\n"
+ "AppleProResHW (0x%x): %s(): coreIdx %u: PSD device - cannot set perf state as m_pSetPerfStateFunction is NULL"
+ "AppleProResHW (0x%x): %s(): devFeaturelist: numFramesPendingMultiplier=%d, bUseLegacyTargetSize=%d, bRAWCodec=%d, bAlphaOnlyCodec=%d, bFrameMaxSizeLimit=%d, bLossyInterchangeFormat=%d, bMBsPerSlice=%d, bRAWRateControl=%d, bHWStatsQPMap=%d, bSwapBRRaw=%d, bAlphaProcessing=%d, bDisableBitstream=%d, bRAWV2=%d, bCommandSplitterFix=%d, isDevBinned=%d, eAprDesc=%d, bUseLegacyEncoderID=%d, bWriteDMAStatsReg=%d, bisFastsim=%d "
+ "AppleProResHW (0x%x): %s(): readiness check passed, coreIdx %d\n"
+ "ProRes-fw-enable"
+ "TopVersion"
+ "s0"
+ "verifyHWReadiness"
- "12111112122212121122111121111112111111211111121122221111222221111211111121111112111111211111111111111111111111111111112112112112111111111111111111111111111111111111111111111111111111111111111111111222222222222222222111111122221111111111111111212222211112"
- "AppleProResHW (0x%x): %s(): devFeaturelist: bLossyInterchangeFormat=%d, bRAWCodec=%d, numFramesPendingMultiplier=%d, bFrameMaxSizeLimit=%d, bMBsPerSlice=%d, bAlphaOnlyCodec=%d, bRAWRateControl=%d, bHWStatsQPMap=%d, bCommandSplitterFix=%d, isDevBinned=%d, bAlphaProcessing=%d, bDisableBitstream=%d"
- "aprDeviceEnabled"
```
