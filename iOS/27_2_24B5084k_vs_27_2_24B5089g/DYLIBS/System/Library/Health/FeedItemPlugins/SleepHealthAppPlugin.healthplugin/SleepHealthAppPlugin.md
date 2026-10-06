## SleepHealthAppPlugin

> `/System/Library/Health/FeedItemPlugins/SleepHealthAppPlugin.healthplugin/SleepHealthAppPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x181af4` | `0x195708` | **`+0x13c14`** |
| `__AUTH.__objc_data` | `0x40f0` | `0x4788` | **`+0x698`** |
| `__AUTH_CONST.__objc_const` | `0x6510` | `0x6a88` | **`+0x578`** |
| `__AUTH.__data` | `0x2e80` | `0x3330` | **`+0x4b0`** |
| `__TEXT.__cstring` | `0x75d9` | `0x7a09` | **`+0x430`** |
| `__TEXT.__constg_swiftt` | `0x5794` | `0x5b78` | **`+0x3e4`** |
| `__TEXT.__unwind_info` | `0x48c0` | `0x4bc0` | **`+0x300`** |
| `__TEXT.__const` | `0xcac4` | `0xcd64` | **`+0x2a0`** |
| `__TEXT.__objc_methlist` | `0x2000` | `0x2298` | **`+0x298`** |
| `__DATA.__data` | `0x4ba8` | `0x4e28` | **`+0x280`** |
| `__TEXT.__swift5_fieldmd` | `0x39d8` | `0x3c34` | **`+0x25c`** |
| `__TEXT.__eh_frame` | `0x3948` | `0x3b90` | **`+0x248`** |
| `__TEXT.__swift5_reflstr` | `0x35db` | `0x380b` | **`+0x230`** |
| `__TEXT.__swift5_typeref` | `0x4232` | `0x4412` | **`+0x1e0`** |
| `__AUTH_CONST.__const` | `0x7e10` | `0x7fc8` | **`+0x1b8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c28` | `0x1da0` | **`+0x178`** |
| `__TEXT.__oslogstring` | `0x4bac` | `0x4cec` | **`+0x140`** |
| `__DATA.__bss` | `0xb050` | `0xaf50` | **`-0x100`** |
| `__DATA_DIRTY.__bss` | `0x4880` | `0x4980` | **`+0x100`** |
| `__TEXT.__swift5_capture` | `0x11d4` | `0x1294` | **`+0xc0`** |
| `__AUTH_CONST.__auth_got` | `0x4228` | `0x42c0` | **`+0x98`** |
| `__DATA_DIRTY.__data` | `0x2c88` | `0x2d08` | **`+0x80`** |
| `__DATA_CONST.__got` | `0x24a8` | `0x24e0` | **`+0x38`** |
| `__DATA_CONST.__objc_classlist` | `0x2e8` | `0x318` | **`+0x30`** |
| `__DATA_DIRTY.__common` | `0x158` | `0x188` | **`+0x30`** |
| `__TEXT.__swift5_types` | `0x4f0` | `0x51c` | **`+0x2c`** |
| `__TEXT.__swift5_proto` | `0x880` | `0x89c` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `0x12c` | `0x140` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x234` | `0x248` | **`+0x14`** |
| `__DATA.__common` | `0x570` | `0x580` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x260` | `0x270` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0x8` | `0x18` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x11c` | `0x128` | **`+0xc`** |
| `__DATA_CONST.__objc_protorefs` | `0x130` | `0x138` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x58` | `0x5c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xe4` | `0xe8` | **`+0x4`** |

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

-  Functions: 6646
-  Symbols:   576
-  CStrings:  932
+  Functions: 6908
+  Symbols:   589
+  CStrings:  957
Symbols:
+ _HKLinearTransformValue
+ _HKUIMidDate
+ _HKUINoDataAvailableSentinel
+ _OBJC_CLASS_$_HKAccessibilityPointData
+ _OBJC_CLASS_$_HKCodableSleepSummaryCollection
+ _OBJC_CLASS_$_HKDisplayTypeContextItemAttributedLabelOverride
+ _OBJC_CLASS_$_HKDisplayTypeContextItemTitleAccessory
+ _OBJC_METACLASS_$_HKOverlayRoomTrendContext
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_unknownObjectRelease_n
+ _swift_unknownObjectRetain_n
CStrings:
+ "LESS_THAN_1_PERCENT"
+ "SLEEP_AVERAGE_ASLEEP"
+ "SLEEP_AVERAGE_IN_BED"
+ "SLEEP_STAGES_PERCENTAGE_SECTION_HEADER"
+ "STAGES_OVERLAY_CONTEXT_AVERAGE_AWAKE"
+ "STAGES_OVERLAY_CONTEXT_AVERAGE_CORE"
+ "STAGES_OVERLAY_CONTEXT_AVERAGE_DEEP"
+ "STAGES_OVERLAY_CONTEXT_AVERAGE_REM"
+ "SleepHealthAppPlugin.SleepChartDataSourceProvider"
+ "SleepHealthAppPlugin.SleepChartPointCarrier"
+ "SleepHealthAppPlugin.SleepDurationAverageFormatter"
+ "SleepHealthAppPlugin.SleepDurationAverageOverlayContext"
+ "SleepHealthAppPlugin.SleepTrendOverlayContext"
+ "SleepHealthAppPlugin/HKInteractiveChartDisplayType+SleepDurationAverage.swift"
+ "SleepHealthAppPlugin/HKInteractiveChartDisplayType+SleepStagesDuration.swift"
+ "SleepHealthAppPlugin/SleepDurationAverageOverlayContext.swift"
+ "SleepHealthAppPlugin/SleepTrendOverlayContext.swift"
+ "SleepStagePercentageContextItemProvider"
+ "[%{public}s] Dashboard production is off; clearing the dashboard copy instead of submitting"
+ "[%{public}s] Dashboard production is off; clearing the dashboard copy instead of submitting."
+ "[%{public}s] could not decode a sleep sharing payload"
+ "[%{public}s] no day series to take an axis interval from"
+ "[%{public}s] no graph series to average over"
+ "[%{public}s] no nights to share: %{public}s"
+ "[%{public}s] no stage title for %{public}s"
+ "init(baseDisplayType:trendModel:overlayChartController:applicationItems:overlayMode:)"
+ "sleepChart"
- "[%{public}s] day axis %{public}s for segment %ld section %ld"
- "[%{public}s] no dynamic day series to take an axis interval from"
```
