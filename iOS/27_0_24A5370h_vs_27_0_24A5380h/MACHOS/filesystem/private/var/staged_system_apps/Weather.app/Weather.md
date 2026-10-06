## Weather

> `/private/var/staged_system_apps/Weather.app/Weather`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb41e98` | `0xb480ac` | **`+0x6214`** |
| `__DATA.__bss` | `0xc01f8` | `0xc05f8` | **`+0x400`** |
| `__TEXT.__swift5_typeref` | `0xaa7a8` | `0xaa418` | **`-0x390`** |
| `__DATA_CONST.__const` | `0x4ae18` | `0x4b170` | **`+0x358`** |
| `__TEXT.__oslogstring` | `0xc42b` | `0xc5ab` | **`+0x180`** |
| `__TEXT.__const` | `0x93e74` | `0x93fe4` | **`+0x170`** |
| `__TEXT.__swift5_reflstr` | `0x23da6` | `0x23f06` | **`+0x160`** |
| `__TEXT.__cstring` | `0x2a563` | `0x2a693` | **`+0x130`** |
| `__TEXT.__swift5_capture` | `0xcc28` | `0xcd1c` | **`+0xf4`** |
| `__TEXT.__swift5_fieldmd` | `0x27ab0` | `0x27b80` | **`+0xd0`** |
| `__DATA.__objc_const` | `0x1cb98` | `0x1cb08` | **`-0x90`** |
| `__TEXT.__auth_stubs` | `0x16850` | `0x168c0` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x1cc30` | `0x1cbf4` | **`-0x3c`** |
| `__DATA_CONST.__auth_got` | `0xb430` | `0xb468` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x280e8` | `0x2811c` | **`+0x34`** |
| `__TEXT.__objc_classname` | `0x6966` | `0x6936` | **`-0x30`** |
| `__DATA.__data` | `0x5b6f0` | `0x5b710` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x67b8` | `0x67d4` | **`+0x1c`** |
| `__DATA_CONST.__auth_ptr` | `0x81d0` | `0x81e8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x61b8` | `0x61d0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xfb8` | `0xfb0` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x2ba8` | `0x2bb0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x5a4` | `0x5a0` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1435.0.0.0.0
+1439.0.0.0.0

-  Functions: 59553
-  Symbols:   10123
-  CStrings:  5865
+  Functions: 59617
+  Symbols:   10133
+  CStrings:  5871
Symbols:
+ _$s10WeatherKit13PrecipitationO0A10AppSupportE08dominantC0AD08DominantC0Ovg
+ _$s11WeatherCore20OutlookConfigurationV21imminentRainLookaheadSdvg
+ _$s11WeatherCore20OutlookConfigurationV22severeAlertOnsetWindowSdSgvg
+ _$s11WeatherCore20OutlookConfigurationV23tenDayMinQualifyingDaysSivg
+ _$s11WeatherCore20OutlookConfigurationV24highlightActiveLookaheadSdSgvg
+ _$s11WeatherCore20OutlookConfigurationV24todayMinSignificantHoursSivg
+ _$s11WeatherCore20OutlookConfigurationV30significantPrecipRateMMPerHourSdvg
+ _$s13TeaFoundation12CapabilitiesC19isInternalUIEnabledSbyFZ
+ _$s17WeatherAppSupport21DominantPrecipitationO4hailyA2CmFWC
+ _$s17WeatherAppSupport26DynamicGridContentGeometryV14topRowSubviews2inSayAC7SubviewVG7SwiftUI0G5ProxyV_tF
+ _$s17WeatherAppSupport27PrecipitationCalculatorTypeP03hasD10ForDisplay2inSb0A3Kit03DayA0V_tFTj
+ _$s7SwiftUI10TransitionPAAE8combined4withQrqd___tAaBRd__lF
+ _$s7SwiftUI10TransitionPAAE8combined4withQrqd___tAaBRd__lFQOMQ
+ _$s7SwiftUI11GestureMaskV8subviewsACvgZ
+ _$s7SwiftUI14MoveTransitionV4edgeAcA4EdgeO_tcfC
+ _$s7SwiftUI14MoveTransitionVAA0D0AAMc
+ _$s7SwiftUI14MoveTransitionVMa
+ _$s7SwiftUI14MoveTransitionVMn
+ _$s7SwiftUI17OpacityTransitionVMn
+ _$s7SwiftUI22_MatchedGeometryEffectVMa
+ _$s7SwiftUI25MatchedGeometryPropertiesVN
+ _$s7SwiftUI4ViewPAAE21matchedGeometryEffect2id2in10properties6anchor8isSourceQrqd___AA9NamespaceV2IDVAA07MatchedE10PropertiesVAA9UnitPointVSbtSHRd__lF
+ _$s7SwiftUI9UnitPointVN
+ _CGRectContainsRect
- _$s17WeatherAppSupport13GridInputDataV11SeverAlertsO2eeoiySbAE_AEtFZ
- _$s17WeatherAppSupport13GridInputDataV12severeAlertsAC05SeverH0Ovg
- _$s17WeatherAppSupport13GridInputDataV3AQIO2eeoiySbAE_AEtFZ
- _$s17WeatherAppSupport13GridInputDataV3aqiAC3AQIOvg
- _$s17WeatherAppSupport26DynamicGridContentGeometryV8subviews8alongRow2inSayAC7SubviewVGAA0E4UnitV_7SwiftUI0G5ProxyVtF
- _$s17WeatherAppSupport27PrecipitationCalculatorTypeP03hasD02inSb0A3Kit03DayA0V_tFTj
- _$s7SwiftUI12VerticalEdgeOMn
- _$s7SwiftUI12VerticalEdgeON
- _$s7SwiftUI19TitleOnlyLabelStyleVAA0eF0AAMc
- _$s7SwiftUI19TitleOnlyLabelStyleVACycfC
- _$s7SwiftUI19TitleOnlyLabelStyleVMa
- _$s7SwiftUI19TitleOnlyLabelStyleVMn
- _$ss26DefaultStringInterpolationV06appendC0yyxlF
- _swift_willThrowTypedImpl
CStrings:
+ "CoordinateHandler failed to reverse geocode a name-less coordinate; falling back to preview. error=%{public}s"
+ "CoordinateHandler matched a saved location after reverse geocoding a name-less coordinate; opening location viewer; location=%{private,mask.hash}s"
+ "Hourly_Forecast_Input_Precipitation_Subtitle_Hail_AX"
+ "Intensity, Chance of Hail"
+ "NewsArticleComponentFactory - Matched severe article %s with article.alertIds=%s for alert %s"
+ "NewsArticleComponentFactory - Matched trend article %s with article.alertIds=%s for alert %s, using trend placement"
+ "NewsArticleComponentFactory - Placing matched severe article above1x1s"
+ "NewsArticleComponentFactory - Placing matched severe article belowSevereAlert"
+ "NewsArticleComponentFactory - Placing trend article at newsConfiguration.trendPlacement=%s"
+ "The accessibility description used for the subtitle of the Hourly Forecast component when the 'Precipitation' notable condition is selected and current conditions include hail"
+ "The precipitation view displays automatically based on the forecast. You can change this in Settings."
+ "aboutCommand"
+ "contentStatusBanner"
- "NewsArticleComponentFactory - Matched article %s with article.alertIds=%s for alert %s"
- "NewsArticleComponentFactory - Placing matched article above1x1s"
- "NewsArticleComponentFactory - Placing matched article belowSevereAlert"
- "NewsArticleComponentFactory - Trend article with no phenomenon found, placing at newsConfiguration.trendPlacement=%s"
- "The precipitation or wind view displays automatically based on the forecast. You can change this in Settings."
- "_TtC7Weather24EmptySidebarWidthStorage"
- "sidebarWidthStorage"
```
