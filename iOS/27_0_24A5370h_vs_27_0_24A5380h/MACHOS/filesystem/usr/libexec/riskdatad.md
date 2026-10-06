## riskdatad

> `/usr/libexec/riskdatad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3bd94` | `0x4385c` | **`+0x7ac8`** |
| `__DATA_CONST.__const` | `0xe40` | `0x12d8` | **`+0x498`** |
| `__TEXT.__eh_frame` | `0x3188` | `0x3578` | **`+0x3f0`** |
| `__TEXT.__swift5_capture` | `0x2fc` | `0x648` | **`+0x34c`** |
| `__TEXT.__const` | `0x2378` | `0x2598` | **`+0x220`** |
| `__TEXT.__auth_stubs` | `0x1ce0` | `0x1df0` | **`+0x110`** |
| `__TEXT.__cstring` | `0x890` | `0x990` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0xfd8` | `0x10a0` | **`+0xc8`** |
| `__DATA_CONST.__auth_got` | `0xe78` | `0xf00` | **`+0x88`** |
| `__TEXT.__swift5_typeref` | `0xaac` | `0xb04` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x4b8` | `0x504` | **`+0x4c`** |
| `__TEXT.__swift5_reflstr` | `0x45b` | `0x49b` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x618` | `0x648` | **`+0x30`** |
| `__DATA.__objc_const` | `0xa18` | `0xa38` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x680` | `0x660` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x6a4` | `0x6c0` | **`+0x1c`** |
| `__DATA.__data` | `0x1298` | `0x12b0` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x4c8` | `0x4e0` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x791` | `0x7a1` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x1a8` | `0x1b0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x58` | `0x5c` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x37c` | `0x380` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x180` | `0x184` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-27.0.44.0.0
+27.0.49.0.0

-  Functions: 954
-  Symbols:   796
-  CStrings:  228
+  Functions: 1019
+  Symbols:   823
+  CStrings:  234
Symbols:
+ _$s10Foundation4DataVMn
+ _$s17CoreODIEssentials0A9ODILoggerV7warning_8categoryySS_2os6LoggerVAAE11LogCategoryOtF
+ _$s17CoreODIEssentials20FetchInsightsRequestV0dE18SpecWithAssessmentV016getProfileIdFromH0SSSgyF
+ _$s17CoreODIEssentials20FetchInsightsRequestV0dE18SpecWithAssessmentV017getWorkflowIdFromH0SSyF
+ _$s17CoreODIEssentials20TelemetryDataRequestV4SpanV0F4TypeO7end2EndyA2GmFWC
+ _$s17CoreODIEssentials20TelemetryDataRequestV4SpanV0F4TypeOMa
+ _$s17CoreODIEssentials20TelemetryDataRequestV4SpanV0F6StatusO5erroryA2GmFWC
+ _$s17CoreODIEssentials20TelemetryDataRequestV4SpanV0F6StatusO7successyA2GmFWC
+ _$s17CoreODIEssentials20TelemetryDataRequestV4SpanV0F6StatusOMa
+ _$s17CoreODIEssentials20TelemetryDataRequestV4SpanV4type6status14startTimestamp8duration11errorString10profileIds08workflowO0A2E0F4TypeO_AE0F6StatusOS2iSSSgSayAQGSgSaySSGSgtcfC
+ _$s17CoreODIEssentials20TelemetryDataRequestV4SpanVMa
+ _$s17CoreODIEssentials20TelemetryDataRequestV4SpanVMn
+ _$s17CoreODIEssentials24RealTimeTelemetryManagerC04sendE05spans9isSandboxySayAA0E11DataRequestV4SpanVG_SbtYaFTjTu
+ _$s17CoreODIEssentials24RealTimeTelemetryManagerCACSgyYacfC
+ _$s17CoreODIEssentials24RealTimeTelemetryManagerCACSgyYacfCTu
+ _$s17CoreODIEssentials24RealTimeTelemetryManagerCMa
+ _$s2os6LoggerV17CoreODIEssentialsE9sensitiveyySSyXKF
+ _$s7CoreODI18EvaluationErrorDTOO015payloadSecurityD0yA2CmFWC
+ _$s7CoreODI18EvaluationErrorDTOO16debugDescriptionSSvg
+ _$s7CoreODI18EvaluationErrorDTOOMn
+ _$s7CoreODI18InsightResponseDTOV14assessmentData016signedAssessmentG09isSandbox6teamId012conversationM0AC10Foundation0G0V_AKSbS2StcfC
+ _$s7CoreODI18OnDeviceAPIServiceP17submitConsumption14conversationId17operationCategory8statuses8insightsySS_SSSayAA07InsightG3DTOVGSayAA0n6ResultO0VGtYaFTq
+ _$s7CoreODI18OnDeviceAPIServiceP17submitConsumption14conversationId17operationCategory8statuses8insightsySS_SSSayAA07InsightG3DTOVGSayAA0n6ResultO0VGtYaKFTqTE
+ _$s7CoreODI28InsightEvaluationIdentifiersV9requestId05eventG006deviceG0ACSSSg_SSAGtcfC
+ _$ss15ContinuousClockV3nowAB7InstantVvgZ
+ _$ss15ContinuousClockV7InstantV8duration2tos8DurationVAD_tF
+ _$ss15ContinuousClockV7InstantVMa
+ _$ss15ContinuousClockV7InstantVMn
+ _$ss8DurationV1doiySdAB_ABtFZ
+ _objc_release_x28
+ _swift_release_x28
- _$s7CoreODI18InsightResponseDTOV14assessmentData016signedAssessmentG09isSandbox6teamIdAC10Foundation0G0V_AJSbSStcfC
- _$s7CoreODI18OnDeviceAPIServiceP17submitConsumption14conversationId8statuses8insightsySS_SayAA07InsightG3DTOVGSayAA0l6ResultM0VGtYaFTq
- _$s7CoreODI18OnDeviceAPIServiceP17submitConsumption14conversationId8statuses8insightsySS_SayAA07InsightG3DTOVGSayAA0l6ResultM0VGtYaKFTqTE
- _$s7CoreODI28InsightEvaluationIdentifiersV9requestId012conversationG005eventG006deviceG0ACSSSg_S2SAHtcfC
CStrings:
+ " is unsupported."
+ "No sandbox status, skipping real-time telemetry"
+ "No versions requested."
+ "ODIAdviceSession"
+ "Raw insights received: "
+ "Too many versions requested."
+ "Unable to initiate CallerInfo: "
+ "com.apple.coreodi.real-time-telemetry"
+ "conversationId"
- "No versions requested"
- "Raw insights received: %s"
- "Too many versions requested"
```
