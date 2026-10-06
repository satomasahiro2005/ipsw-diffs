## riskdatad

> `/usr/libexec/riskdatad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x50e90` | `0x522fc` | **`+0x146c`** |
| `__TEXT.__eh_frame` | `0x3e70` | `0x3ff0` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x16f0` | `0x1790` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x838` | `0x8c0` | **`+0x88`** |
| `__TEXT.__auth_stubs` | `0x1fa0` | `0x2000` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1358` | `0x13b0` | **`+0x58`** |
| `__DATA.__data` | `0x1610` | `0x1660` | **`+0x50`** |
| `__TEXT.__const` | `0x28a0` | `0x28f0` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0xfd8` | `0x1008` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0xc50` | `0xc68` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x3f8` | `0x40c` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x4f8` | `0x500` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x680` | `0x688` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x1f8` | `0x200` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-27.0.61.0.0
+27.2.2.0.0

-  Functions: 1165
-  Symbols:   855
+  Functions: 1181
+  Symbols:   862
Symbols:
+ _$s17CoreODIEssentials18ODISessionInternalC13getAssessmentSS_AA20TelemetryDataRequestV4SpanVtyYaFTjTu
+ _$s17CoreODIEssentials18ODISessionInternalC19getAssessmentResultAA013ODIAssessmentG0O_AA20TelemetryDataRequestV4SpanVtyYaFTjTu
+ _$s17CoreODIEssentials19ScreenCaptureStatusC15startMonitoringyyFZ
+ _$s17CoreODIEssentials19ScreenCaptureStatusCMa
+ _$s17CoreODIEssentials22TelemetrySpanCollectorC5spansSayAA0C11DataRequestV0D0VGvg
+ _$s17CoreODIEssentials22TelemetrySpanCollectorC6recordyyAA0C11DataRequestV0D0VF
+ _$s17CoreODIEssentials22TelemetrySpanCollectorCACycfc
+ _$s17CoreODIEssentials22TelemetrySpanCollectorCMa
+ _$s17CoreODIEssentials22TelemetrySpanCollectorCMn
+ _$s17CoreODIEssentials24RealTimeTelemetryManagerC04sendE05spans9isSandbox8bundleId04teamL010appVersionySayAA0E11DataRequestV4SpanVG_SbSSSgA2OtYaFTjTu
+ _$s17CoreODIEssentials24RealTimeTelemetryManagerC6sharedACvgZ
+ _$s17CoreODIEssentials24RealTimeTelemetryManagerC6sharedACvgZTu
- _$s17CoreODIEssentials18ODISessionInternalC13getAssessmentSSyYaFTjTu
- _$s17CoreODIEssentials18ODISessionInternalC19getAssessmentResultAA013ODIAssessmentG0OyYaFTjTu
- _$s17CoreODIEssentials24RealTimeTelemetryManagerC04sendE05spans9isSandbox8bundleId04teamL010appVersionySayAA0E11DataRequestV4SpanVG_SbS3StYaFTjTu
- _$s17CoreODIEssentials24RealTimeTelemetryManagerCACSgyYacfC
- _$s17CoreODIEssentials24RealTimeTelemetryManagerCACSgyYacfCTu
```
