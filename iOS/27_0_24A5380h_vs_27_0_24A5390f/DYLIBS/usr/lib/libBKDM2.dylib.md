## libBKDM2.dylib

> `/usr/lib/libBKDM2.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7c434` | `0x7cabc` | **`+0x688`** |
| `__AUTH_CONST.__objc_const` | `0x9948` | `0x9a28` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x465c` | `0x4720` | **`+0xc4`** |
| `__TEXT.__objc_methlist` | `0x5d2c` | `0x5d84` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0x177c` | `0x17c0` | **`+0x44`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d28` | `0x3d58` | **`+0x30`** |
| `__AUTH_CONST.__objc_intobj` | `0x3f0` | `0x3d8` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0xab0` | `0xac8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xe10` | `0xe20` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x728` | `0x730` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x448` | `0x450` | **`+0x8`** |
| `__TEXT.__cstring` | `0x703d` | `0x7041` | **`+0x4`** |

### Other Changes

```diff

-980.0.0.0.10
+980.0.18.0.0

-  Functions: 2895
-  Symbols:   4330
-  CStrings:  1607
+  Functions: 2904
+  Symbols:   4344
+  CStrings:  1608
Symbols:
+ -[BLFrameDebugExtra processFrameDebugData:withHeader:dict:]
+ -[BLFrameDebugExtraEisp processFrameDebugData:withHeader:dict:]
+ -[PearlCoreAnalytics analyzeSecureFaceDetectCoachingStatus:]
+ -[PearlCoreAnalytics analyzeSecureFaceDetectFrameMeta:fromCameraID:faceDetected:]
+ -[PearlCoreAnalytics analyzeSecureFrameMeta:fromCameraID:faceDetected:]
+ -[PearlCoreAnalytics deviceThermalState]
+ -[PearlCoreAnalyticsEnrollEvent deviceThermalState]
+ -[PearlCoreAnalyticsEnrollEvent setDeviceThermalState:]
+ -[PearlCoreAnalyticsMatchEvent deviceThermalState]
+ -[PearlCoreAnalyticsMatchEvent setDeviceThermalState:]
+ GCC_except_table16
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_IVAR_$_PearlCoreAnalytics._secureEnrollEvent
+ _OBJC_IVAR_$_PearlCoreAnalytics._secureEnrollEventValid
+ _OBJC_IVAR_$_PearlCoreAnalytics._secureMatchEvent
+ _OBJC_IVAR_$_PearlCoreAnalytics._secureMatchEventValid
+ _OBJC_IVAR_$_PearlCoreAnalyticsEnrollEvent._deviceThermalState
+ _OBJC_IVAR_$_PearlCoreAnalyticsMatchEvent._deviceThermalState
+ ___63-[BLFrameDebugExtraEisp processFrameDebugData:withHeader:dict:]_block_invoke
+ _dispatch_suspend
- -[BLFrameDebugExtra processFrameDebugData:forSeqType:withDict:]
- -[BLFrameDebugExtraEisp processFrameDebugData:forSeqType:withDict:]
- -[PearlCoreAnalytics analyzeSecureFrameMeta:faceDetected:]
- GCC_except_table12
- _OUTLINED_FUNCTION_59
- ___67-[BLFrameDebugExtraEisp processFrameDebugData:forSeqType:withDict:]_block_invoke
CStrings:
+ "NOTICE: analyzeSecureFaceDetectFrameMeta: Face detected on RGB camera first! Awaiting IR frame...\n"
+ "PearlCoreAnalytics analyzeSecureFaceDetectFrameMeta\n"
+ "PearlCoreAnalytics analyzeSecureFrameMeta: Unexpected secureFaceDetectRequestType: %u\n"
+ "enroll_group_count"
+ "processed_groups"
- "\t"
- "PearlCoreAnalytics analyzeSecureFrameMeta\n"
- "enroll_frames_num"
- "processed_doubles"
```
