## Weather

> `/private/var/staged_system_apps/Weather.app/Weather`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb480ac` | `0xb4a800` | **`+0x2754`** |
| `__TEXT.__swift5_typeref` | `0xaa418` | `0xac558` | **`+0x2140`** |
| `__DATA.__bss` | `0xc05f8` | `0xc24d8` | **`+0x1ee0`** |
| `__TEXT.__const` | `0x93fe4` | `0x95b04` | **`+0x1b20`** |
| `__DATA.__data` | `0x5b710` | `0x5bd20` | **`+0x610`** |
| `__TEXT.__constg_swiftt` | `0x2811c` | `0x286e8` | **`+0x5cc`** |
| `__TEXT.__swift5_assocty` | `0x5d48` | `0x6210` | **`+0x4c8`** |
| `__DATA_CONST.__const` | `0x4b170` | `0x4b588` | **`+0x418`** |
| `__TEXT.__swift5_fieldmd` | `0x27b80` | `0x27d7c` | **`+0x1fc`** |
| `__TEXT.__unwind_info` | `0x21030` | `0x211f8` | **`+0x1c8`** |
| `__TEXT.__eh_frame` | `0x1cbf4` | `0x1cd4c` | **`+0x158`** |
| `__TEXT.__swift5_proto` | `0x67d4` | `0x68cc` | **`+0xf8`** |
| `__TEXT.__auth_stubs` | `0x168c0` | `0x16990` | **`+0xd0`** |
| `__TEXT.__swift5_reflstr` | `0x23f06` | `0x23e66` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x2a693` | `0x2a603` | **`-0x90`** |
| `__TEXT.__swift5_capture` | `0xcd1c` | `0xcc8c` | **`-0x90`** |
| `__TEXT.__swift5_types` | `0x2bb0` | `0x2c2c` | **`+0x7c`** |
| `__DATA_CONST.__auth_got` | `0xb468` | `0xb4d0` | **`+0x68`** |
| `__DATA.__objc_data` | `0x4d60` | `0x4db0` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0x6936` | `0x6966` | **`+0x30`** |
| `__DATA.__objc_const` | `0x1cb08` | `0x1cb30` | **`+0x28`** |
| `__DATA_CONST.__auth_ptr` | `0x81e8` | `0x8208` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0xad05` | `0xad25` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x3ca0` | `0x3cc0` | **`+0x20`** |
| `__DATA.__common` | `0x2410` | `0x23f8` | **`-0x18`** |
| `__TEXT.__oslogstring` | `0xc5ab` | `0xc5bb` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1828` | `0x1830` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x61d0` | `0x61d8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xfb0` | `0xfb8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x510` | `0x518` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x2d0` | `0x2d8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x29c` | `0x2a0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types2`

### Other Changes

```diff

-1439.0.0.0.0
+1444.1.0.0.0

-  Functions: 59617
-  Symbols:   10133
-  CStrings:  5871
+  Functions: 59826
+  Symbols:   10150
+  CStrings:  5868
Symbols:
+ _$s10AppIntents11EntityQueryP22displayRepresentations3forSDy0C0_2IDQZAA21DisplayRepresentationVGSayAHG_tYaKFTq
+ _$s10AppIntents11EntityQueryPAAE22displayRepresentations3forSDy0C0_2IDQZAA21DisplayRepresentationVGSayAHG_tYaKF
+ _$s10AppIntents11EntityQueryPAAE22displayRepresentations3forSDy0C0_2IDQZAA21DisplayRepresentationVGSayAHG_tYaKFTu
+ _$s10Foundation4UUIDV4uuidACs5UInt8V_A15Ft_tcfC
+ _$s17WeatherAppSupport17SameDayCalculatorO02isdE0__8calendarSb10Foundation4DateV_AhF8CalendarVtFZ
+ _$s17WeatherAppSupport17SameDayCalculatorO07startOfE0_8calendar10Foundation4DateVAH_AF8CalendarVtFZ
+ _$s17WeatherAppSupport23DynamicGridArrangementsV12arrangementsACyxGSayAA0dE11ArrangementVyxGG_tcfC
+ _$s17WeatherAppSupport23DynamicGridArrangementsV2eeoiySbACyxG_AEtFZ
+ _$s17WeatherAppSupport23DynamicGridArrangementsVMa
+ _$s17WeatherAppSupport25DynamicConditionEvaluatorV21imminentRainLookahead30significantPrecipRateMMPerHour24todayMinSignificantHours06tenDayP14QualifyingDays22severeAlertOnsetWindow015highlightActiveI0ACSd_SdS2iSdSgAJtcfC
+ _$s17WeatherAppSupport25DynamicConditionEvaluatorV8evaluate14hourlyForecast6alerts21historicalComparisons19highlightStatements07currentE03now8timeZone10locationId0A4Core0E11OfRelevanceOSgSay0A3Kit04HourA0VG_SayAQ0A5AlertVGAQ010HistoricalL0VSgSayAQ0A9StatementVGAQ0aE0OSg10Foundation4DateVA5_04TimeR0VSSSgtF
+ _$s17WeatherAppSupport25DynamicConditionEvaluatorVMa
+ _$s17WeatherAppSupport30DynamicGridArrangementsBuilderV15buildExpressionyAA0deF0VyxGAGFZ
+ _$s7SwiftUI18_TaskValueModifierVMa
+ _$s7SwiftUI18_TaskValueModifierVyxGAA04ViewE0AAMc
+ _$s7SwiftUI19_TaskValueModifier2V2id4name18executorPreference8priority6actionACyxGx_SSSch_pSgScPyyYaYAcntcfC
+ _$s7SwiftUI19_TaskValueModifier2VMa
+ _$s7SwiftUI19_TaskValueModifier2VMn
+ _$s7SwiftUI19_TaskValueModifier2VyxGAA12ViewModifierAAMc
+ _$s7SwiftUI39_PlatformViewRepresentableLayoutOptionsV18propagatesSafeAreaACvgZ
+ _$s7SwiftUI39_PlatformViewRepresentableLayoutOptionsVMa
+ _$s7SwiftUI39_PlatformViewRepresentableLayoutOptionsVMn
+ _$s7SwiftUI39_PlatformViewRepresentableLayoutOptionsVs10SetAlgebraAAMc
+ _$s9WeatherUI14SafeAreaInsetsV6CornerVMa
+ _$sScTss5NeverORszABRs_rlE11isCancelledSbvgZ
+ _$sSo6CGSizeVSQ12CoreGraphicsMc
- _$s10WeatherKit0A8SeverityOSQAAMc
- _$s10WeatherKit0A9ConditionOs23CustomStringConvertibleAAMc
- _$s17WeatherAppSupport14IsSameDayCacheC012asyncPreloadG0_8calendarySay10Foundation4DateVG_AF8CalendarVtYaF
- _$s17WeatherAppSupport14IsSameDayCacheC012asyncPreloadG0_8calendarySay10Foundation4DateVG_AF8CalendarVtYaFTu
- _$s17WeatherAppSupport14IsSameDayCacheC02iseF0__8calendarSb10Foundation4DateV_AhF8CalendarVtF
- _$s17WeatherAppSupport14IsSameDayCacheC07startOfF0_8calendar10Foundation4DateVAH_AF8CalendarVtF
- _$s17WeatherAppSupport14IsSameDayCacheCMa
- _$s17WeatherAppSupport14IsSameDayCacheCMn
- _swift_release_x10
CStrings:
+ "443a538c2209bce67735f472d2aadc64"
+ "View.task @ Weather/MoonComponentView.swift:"
+ "Weather data cleared after significant location change"
+ "_TtC7Weather29_ParasolSharedLabelWidthCache"
+ "columnCountBreakpoints"
+ "intrinsicContentSize"
+ "measurements"
- "%{private,mask.hash}s: %s (%s). %s"
- ", precipHighlight: "
- ", severeAlerts: "
- ", tenDayQualifyingDays: "
- ", todaySigHours: "
- "c18e6bcfcdbd65fd193e4ba6a8294c04"
- "isSameDayCache"
- "mm), condition: "
- "sameDayCache"
- "significantPrecipitation"
```
