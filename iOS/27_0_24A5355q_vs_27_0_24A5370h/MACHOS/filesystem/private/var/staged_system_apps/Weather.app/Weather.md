## Weather

> `/private/var/staged_system_apps/Weather.app/Weather`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2a2e4` | `0xb41e98` | **`+0x117bb4`** |
| `__DATA.__bss` | `0xdb348` | `0xc01f8` | **`-0x1b150`** |
| `__DATA.__data` | `0x50278` | `0x5b6f0` | **`+0xb478`** |
| `__TEXT.__swift5_typeref` | `0xa3a86` | `0xaa7a8` | **`+0x6d22`** |
| `__TEXT.__const` | `0x98f94` | `0x93e74` | **`-0x5120`** |
| `__DATA_CONST.__const` | `0x46c78` | `0x4ae18` | **`+0x41a0`** |
| `__TEXT.__swift5_capture` | `0x9168` | `0xcc28` | **`+0x3ac0`** |
| `__TEXT.__constg_swiftt` | `0x2b2ec` | `0x280e8` | **`-0x3204`** |
| `__TEXT.__swift5_fieldmd` | `0x2a544` | `0x27ab0` | **`-0x2a94`** |
| `__TEXT.__unwind_info` | `0x235b8` | `0x21030` | **`-0x2588`** |
| `__TEXT.__swift5_reflstr` | `0x26066` | `0x23da6` | **`-0x22c0`** |
| `__TEXT.__eh_frame` | `0x1dfd8` | `0x1cc30` | **`-0x13a8`** |
| `__TEXT.__cstring` | `0x29923` | `0x2a563` | **`+0xc40`** |
| `__TEXT.__swift5_proto` | `0x7004` | `0x67b8` | **`-0x84c`** |
| `__TEXT.__swift5_types` | `0x3324` | `0x2ba8` | **`-0x77c`** |
| `__TEXT.__swift5_assocty` | `0x6108` | `0x5d48` | **`-0x3c0`** |
| `__DATA.__objc_const` | `0x1c968` | `0x1cb98` | **`+0x230`** |
| `__DATA_CONST.__auth_ptr` | `0x80c8` | `0x81d0` | **`+0x108`** |
| `__DATA.__common` | `0x2500` | `0x2410` | **`-0xf0`** |
| `__DATA.__objc_data` | `0x4c70` | `0x4d60` | **`+0xf0`** |
| `__TEXT.__objc_classname` | `0x6886` | `0x6966` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0xc34b` | `0xc42b` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0xac35` | `0xad05` | **`+0xd0`** |
| `__TEXT.__swift_as_ret` | `0x35c` | `0x29c` | **`-0xc0`** |
| `__TEXT.__swift_as_entry` | `0x388` | `0x2d0` | **`-0xb8`** |
| `__TEXT.__auth_stubs` | `0x167c0` | `0x16850` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0x3d00` | `0x3ca0` | **`-0x60`** |
| `__TEXT.__swift_as_cont` | `0x560` | `0x510` | **`-0x50`** |
| `__DATA_CONST.__auth_got` | `0xb3e8` | `0xb430` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x6200` | `0x61b8` | **`-0x48`** |
| `__DATA.__objc_selrefs` | `0x1840` | `0x1828` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xfa0` | `0xfb8` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x438` | `0x424` | **`-0x14`** |
| `__TEXT.__objc_methtype` | `0x20a8` | `0x209a` | **`-0xe`** |
| `__TEXT.__swift5_mpenum` | `0x18c` | `0x184` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types2`

### Other Changes

```diff

-1431.1.0.0.0
+1435.0.0.0.0

-  - /System/Library/Frameworks/DeveloperToolsSupport.framework/DeveloperToolsSupport

-  - /System/Library/PrivateFrameworks/IconServices.framework/IconServices

-  Functions: 67664
-  Symbols:   10145
-  CStrings:  5797
+  Functions: 59553
+  Symbols:   10123
+  CStrings:  5865
Symbols:
+ _$s10WeatherKit0A9ConditionO0A10AppSupportE21dominantPrecipitationAD08DominantG0OSgvg
+ _$s11TeaSettings0B0C11WeatherCoreE8FeaturesV7ParasolV25dynamicConditionAsDefaultAA7SettingCyAA12FeatureStateOGvgZ
+ _$s11TeaSettings8AppGroupC12userDefaultsSo06NSUserF0Cvg
+ _$s11WeatherCore09PreferredA9ConditionO16resolvingDefault5usingAcA20OutlookConfigurationV_tF
+ _$s11WeatherCore16AppConfigurationV07outlookD0AA07OutlookD0Vvg
+ _$s11WeatherCore20OutlookConfigurationV36resolvedDynamicConditionAsDefaultKeySSvgZ
+ _$s11WeatherCore20OutlookConfigurationVMa
+ _$s17WeatherAppSupport13GridInputDataV11SeverAlertsO2eeoiySbAE_AEtFZ
+ _$s17WeatherAppSupport13GridInputDataV12severeAlertsAC05SeverH0Ovg
+ _$s17WeatherAppSupport13GridInputDataV3AQIO2eeoiySbAE_AEtFZ
+ _$s17WeatherAppSupport13GridInputDataV3aqiAC3AQIOvg
+ _$s17WeatherAppSupport13GridInputDataV6hasNHP11supportsMap3aqi15enabledFeatures4news12severeAlerts8averages20feelsLikeTemperature15notificationTip06reportaV9PlacementACSb_SbAC3AQIOAC0M0VAC4NewsOAC05SeverP0OAC8AveragesOAC05FeelssT0OAC012NotificationV0OAC06ReportavX5ValueOtcfC
+ _$s17WeatherAppSupport21DominantPrecipitationOSQAAMc
+ _$s17WeatherAppSupport25AnyDynamicGridArrangementV3row3forAA0F4UnitVSgs0D8HashableV_tF
+ _$s17WeatherAppSupport34ParasolHourlyForecastStringBuilderV8subtitle4with21dominantPrecipitationSS0A3Kit07CurrentA0V_AA08DominantL0OSgtF
+ _$s17WeatherAppSupport39DynamicGridArrangementSelectionCriteriaO19geometryLayoutValueyACs7KeyPathCyAA08GeometryJ7ContextVxG_xtSHRzlFZ
+ _$s17WeatherAppSupport39DynamicGridArrangementSelectionCriteriaO6alwaysyA2CmFWC
+ _$s4Body6TipKit0B9ViewStylePTl
+ _$s6TipKit0A22ViewStyleConfigurationV3tipAA0A0_pvg
+ _$s6TipKit0A22ViewStyleConfigurationV5title7SwiftUI4TextVSgvg
+ _$s6TipKit0A22ViewStyleConfigurationV7actionsSayAA4TipsO6ActionVGvg
+ _$s6TipKit0A22ViewStyleConfigurationV7message7SwiftUI4TextVSgvg
+ _$s6TipKit0A22ViewStyleConfigurationVMa
+ _$s6TipKit0A22ViewStyleConfigurationVMn
+ _$s6TipKit0A9ViewStyleMp
+ _$s6TipKit0A9ViewStyleP4BodyAC_7SwiftUI0C0Tn
+ _$s6TipKit0A9ViewStyleP8makeBody13configuration0F0QzAA0acD13ConfigurationV_tFTq
+ _$s6TipKit4TipsO14OptionsBuilderV15buildExpressionyQrSayxGAA0A6OptionRzlFZ
+ _$s6TipKit4TipsO14OptionsBuilderV15buildExpressionyQrSayxGAA0A6OptionRzlFZQOMQ
+ _$s7Combine10PublishersO16RemoveDuplicatesVMn
+ _$s7Combine10PublishersO4DropVMn
+ _$s7Combine10PublishersO8ThrottleVMn
+ _$s7Combine25ObservableObjectPublisherCMa
+ _$s7SwiftUI12VerticalEdgeOMn
+ _$s7SwiftUI12VerticalEdgeON
+ _$s7SwiftUI15DynamicTypeSizeOSHAAMc
+ _$s7SwiftUI17EnvironmentValuesV17WeatherAppSupportE39pagingDynamicGridIsAfterTransitionResetSbvg
+ _$s7SwiftUI17EnvironmentValuesV17WeatherAppSupportE39pagingDynamicGridIsAfterTransitionResetSbvpMV
+ _$s7SwiftUI17EnvironmentValuesV17WeatherAppSupportE39pagingDynamicGridIsAfterTransitionResetSbvs
+ _$s7SwiftUI22_AnchorWritingModifierVyxq_GAA04ViewE0AAMc
+ _$s7SwiftUI23AccessibilityFocusStateV12wrappedValuexvs
+ _$s7SwiftUI23AccessibilityFocusStateV14projectedValueAC7BindingVyx_Gvg
+ _$s7SwiftUI23AccessibilityFocusStateVACySbGycSbRszrlufC
+ _$s7SwiftUI23AccessibilityFocusStateVMa
+ _$s7SwiftUI23AccessibilityFocusStateVMn
+ _$s7SwiftUI23ToolbarMinimizeBehaviorV8disabledACvgZ
+ _$s7SwiftUI23ToolbarMinimizeBehaviorVMa
+ _$s7SwiftUI23_CompositingGroupEffectVAA12ViewModifierAAWP
+ _$s7SwiftUI25AccessibilityTechnologiesVMa
+ _$s7SwiftUI31ViewAlignedScrollTargetBehaviorV05LimitG0V6alwaysAEvgZ
+ _$s7SwiftUI31ViewAlignedScrollTargetBehaviorV05LimitG0VMa
+ _$s7SwiftUI31ViewAlignedScrollTargetBehaviorV05limitG0A2C05LimitG0V_tcfC
+ _$s7SwiftUI31ViewAlignedScrollTargetBehaviorVAA0efG0AAWP
+ _$s7SwiftUI31ViewAlignedScrollTargetBehaviorVMa
+ _$s7SwiftUI31ViewAlignedScrollTargetBehaviorVMn
+ _$s7SwiftUI4PathV12closeSubpathyyF
+ _$s7SwiftUI4PathV6addArc6center6radius10startAngle03endI09clockwise9transformySo7CGPointV_12CoreGraphics7CGFloatVAA0I0VAQSbSo17CGAffineTransformVtF
+ _$s7SwiftUI4ViewP17WeatherAppSupportE27dynamicGridDecorationZIndexyQr12CoreGraphics7CGFloatVF
+ _$s7SwiftUI4ViewP17WeatherAppSupportE27dynamicGridDecorationZIndexyQr12CoreGraphics7CGFloatVFQOMQ
+ _$s7SwiftUI4ViewP6ChartsE11chartYScale6domain4typeQrqd___AD9ScaleTypeVSgtAD0I6DomainRd__lF
+ _$s7SwiftUI4ViewP6ChartsE11chartYScale6domain4typeQrqd___AD9ScaleTypeVSgtAD0I6DomainRd__lFQOMQ
+ _$s7SwiftUI4ViewP6TipKitE03tipC5StyleyQrqd__AD0dcG0Rd__lF
+ _$s7SwiftUI4ViewP6TipKitE03tipC5StyleyQrqd__AD0dcG0Rd__lFQOMQ
+ _$s7SwiftUI4ViewPAAE20accessibilityFocusedyQrAA23AccessibilityFocusStateV7BindingVySb_GF
+ _$s7SwiftUI4ViewPAAE20accessibilityFocusedyQrAA23AccessibilityFocusStateV7BindingVySb_GFQOMQ
+ _$s7SwiftUI4ViewPAAE23toolbarMinimizeBehavior_3forQrAA07ToolbareF0V_AA0H9PlacementVdtF
+ _$s7SwiftUI4ViewPAAE23toolbarMinimizeBehavior_3forQrAA07ToolbareF0V_AA0H9PlacementVdtFQOMQ
+ _$s7SwiftUI9AnimationV07WeatherB0E010vfxOpacityC0ACvgZ
+ _$s7SwiftUI9UnitPointV14bottomTrailingACvgZ
+ _$sSdSQsWP
+ _$sSo12UIRectCornerV5TeaUIE7isEmptySbvg
+ _$sSo14NSUserDefaultsC11WeatherCoreE3get3forxSgSS_tlF
+ _objc_retain_x11
+ _swift_deletedAsyncMethodErrorTu
+ _swift_release_x10
+ _swift_task_getMainExecutor
+ _swift_task_isCurrentExecutor
- _$s10AppIntents0A17EntityVisualStateVMa
- _$s10AppIntents0A17EntityVisualStateVMn
- _$s10AppIntents0A17EntityVisualStateVs10SetAlgebraAAMc
- _$s10Foundation11MeasurementV9WeatherUISo17NSUnitTemperatureCRszrlE10fahrenheityACyAFGSdFZ
- _$s10Foundation24NSKeyValueObservedChangeV03oldC0xSgvg
- _$s10WeatherKit0A10HighlightsV17notableConditions3forAA07NotableE0O10Foundation4DateV_tF
- _$s10WeatherKit17NotableConditionsOSQAAMc
- _$s10WeatherKit9DeviationO2eeoiySbAC_ACtFZ
- _$s11TeaSettings0B0C11WeatherCoreE11HomeAndWorkV04showefG6LabelsAA7SettingCySbGvgZ
- _$s11WeatherCore17KeyValueStoreTypeP3get3forqd__SgSS_tlFTj
- _$s11WeatherMaps0A21MapZoomControllerTypeP010stopLinearD0yyFTj
- _$s11WeatherMaps0A21MapZoomControllerTypeP011startLinearD2InyyFTj
- _$s11WeatherMaps0A21MapZoomControllerTypeP011startLinearD3OutyyFTj
- _$s12CoreGraphics7CGFloatVSLAAMc
- _$s13TeaFoundation6AtomicC12wrappedValuexvM
- _$s17WeatherAppSupport13GridInputDataV6hasNHP11supportsMap3aqi3uvi15enabledFeatures4news12severeAlerts8averages20feelsLikeTemperature15notificationTip06reportaW9PlacementACSb_SbAC3AQIOAC7UVIndexOAC0N0VAC4NewsOAC05SeverQ0OAC8AveragesOAC05FeelstU0OAC012NotificationW0OAC06ReportawY5ValueOtcfC
- _$s17WeatherAppSupport13GridInputDataV7UVIndexO3lowyA2EmFWC
- _$s17WeatherAppSupport13GridInputDataV7UVIndexO8elevatedyA2EmFWC
- _$s17WeatherAppSupport13GridInputDataV7UVIndexOMa
- _$s17WeatherAppSupport21GeometryLayoutContextV4sizeSo6CGSizeVvg
- _$s17WeatherAppSupport34ParasolHourlyForecastStringBuilderV8subtitle4withSS0A3Kit07CurrentA0V_tF
- _$s7Combine10PublishersO16RemoveDuplicatesVMa
- _$s7Combine10PublishersO8ThrottleVMa
- _$s7Combine16ObservableObjectP16objectWillChange0ceF9PublisherQzvgTj
- _$s7Combine16ObservableObjectTL
- _$s7Combine9PublishedV14projectedValueAC9PublisherVyx_Gvs
- _$s7Combine9PublishedV18_enclosingInstance7wrapped7storagexqd___s24ReferenceWritableKeyPathCyqd__xGAHyqd__ACyxGGtcRld__CluiMZ
- _$s7Combine9PublishedV9PublisherVMa
- _$s7SwiftUI11StateObjectV12wrappedValueACyxGxyXA_tcfC
- _$s7SwiftUI11_MaskEffectVyxGAA12ViewModifierAAMc
- _$s7SwiftUI15PreviewProviderMp
- _$s7SwiftUI15PreviewProviderP8PreviewsAC_AA4ViewTn
- _$s7SwiftUI15PreviewProviderP8platformAA0C8PlatformOSgvgZTq
- _$s7SwiftUI15PreviewProviderP8previews8PreviewsQzvgZTq
- _$s7SwiftUI15PreviewProviderPAA01_cD0Tb
- _$s7SwiftUI15PreviewProviderPAAE8platformAA0C8PlatformOSgvgZ
- _$s7SwiftUI15PreviewProviderPAAE9_platformAA0C8PlatformOSgvgZ
- _$s7SwiftUI15PreviewProviderPAAE9_previewsypvgZ
- _$s7SwiftUI16_PreviewProviderMp
- _$s7SwiftUI16_PreviewProviderP9_platformAA0C8PlatformOSgvgZTq
- _$s7SwiftUI16_PreviewProviderP9_previewsypvgZTq
- _$s7SwiftUI18ViewInputPredicateP8evaluate6inputsSbAA12_GraphInputsV_tFZTj
- _$s7SwiftUI19ConcentricRectangleVACycfC
- _$s7SwiftUI19ConcentricRectangleVMn
- _$s7SwiftUI20_HoverRegionModifierVAA04ViewE0AAMc
- _$s7SwiftUI20_HoverRegionModifierVN
- _$s7SwiftUI23LabelStyleConfigurationV5TitleVAA4ViewAAMc
- _$s7SwiftUI23LabelStyleConfigurationV5TitleVMa
- _$s7SwiftUI29_BackgroundPreferenceModifierVMa
- _$s7SwiftUI32_EnvironmentKeyTransformModifierVMa
- _$s7SwiftUI4EdgeO3SetVSQAAMc
- _$s7SwiftUI4ViewP012_AppIntents_aB0E9appEntity_5stateQrqd___0dE00dG11VisualStateVtAG0dG0Rd__lF
- _$s7SwiftUI4ViewP012_AppIntents_aB0E9appEntity_5stateQrqd___0dE00dG11VisualStateVtAG0dG0Rd__lFQOMQ
- _$s7SwiftUI4ViewP17WeatherAppSupportE017pagingDynamicGridC16HideOffsidePagesyQrSbF
- _$s7SwiftUI4ViewP17WeatherAppSupportE017pagingDynamicGridC16HideOffsidePagesyQrSbFQOMQ
- _$s7SwiftUI4ViewPAAE10preference3key5valueQrqd__m_5ValueQyd__tAA13PreferenceKeyRd__lF
- _$s7SwiftUI4ViewPAAE12onTapGesture5count15coordinateSpace7performQrSi_AA010CoordinateI0OySo7CGPointVctF
- _$s7SwiftUI4ViewPAAE12onTapGesture5count15coordinateSpace7performQrSi_AA010CoordinateI0OySo7CGPointVctFQOMQ
- _$s7SwiftUI4ViewPAAE25backgroundPreferenceValue_9alignment_Qrqd__m_AA9AlignmentVqd_0_0F0Qyd__ctAA0E3KeyRd__AaBRd_0_r0_lF
- _$s7SwiftUI4ViewPAAE9clipShape_5styleQrqd___AA9FillStyleVtAA0E0Rd__lF
- _$s7SwiftUI9RectangleVAA4ViewAAMc
- _$s8Previews7SwiftUI15PreviewProviderPTl
- _$s9WeatherUI21SkyBackgroundGradientV8topColorAA07CodableG0Vvg
- _$s9WeatherUI35NextHourPrecipitationChartViewModelV04mockH0ACvgZ
- _$sS2ayxGycfC
- _$sSDyxq_Gs23CustomStringConvertiblesMc
- _$sSSs23CustomStringConvertiblesWP
- _$sST19underestimatedCountSivgTj
- _$sSTsE6reduceyqd__qd___qd__qd___7ElementQztKXEtKlF
- _$sSTsSQ7ElementRpzrlE8containsySbABF
- _$sSa13_adoptStorage_5countSayxG_SpyxGts016_ContiguousArrayB0CyxGn_SitFZ
- _$sSa6appendyyxnF
- _$sSayxGs14_ArrayProtocolsMc
- _$sSbs23CustomStringConvertiblesWP
- _$sShyxGSlsMc
- _$sSl30_customIndexOfEquatableElementy0B0QzSgSg0E0QzFTj
- _$sSlsEy11SubSequenceQzqd__cSXRd__5BoundQyd__5IndexRtzluig
- _$sSlsSQ7ElementRpzrlE10firstIndex2of0C0QzSgAB_tF
- _$sSo8NSBundleC17WeatherAppSupportE07weathercD0ABvgZ
- _$ss12Zip2SequenceVMa
- _$ss12Zip2SequenceVyxq_GSTsMc
- _$ss15WritableKeyPathCMn
- _$ss15WritableKeyPathCMo
- _$ss15_arrayForceCastySayq_GSayxGr0_lF
- _$ss16PartialRangeFromVMa
- _$ss16PartialRangeFromVyxGSXsMc
- _$ss21_arrayConditionalCastySayq_GSgSayxGr0_lF
- _$ss23_ContiguousArrayStorageCMa
- _$ss3maxyxx_xtSLRzlF
- _$ss3minyxx_xtSLRzlF
- _$ss3zipys12Zip2SequenceVyxq_Gx_q_tSTRzSTR_r0_lF
- _$ss5ErrorWS
- _$ss7KeyPathCMa
- _OBJC_CLASS_$_ISIcon
- _OBJC_CLASS_$_ISImageDescriptor
- _kISImageDescriptorHomeScreen
- _swift_isClassType
- _swift_isaMask
- _swift_setAtWritableKeyPath
CStrings:
+ "%s: Deferring view session start for %{private,mask.hash}s"
+ "%s: Processing change in location view visibility. Target=%{private,mask.hash}s, Reason: %s, Arg=%{private,mask.hash}s"
+ "%s: Tracking view session end for %{private,mask.hash}s"
+ "%s: Tracking view session start for %{private,mask.hash}s"
+ "+isAutoSwitchActive"
+ ", precipHighlight: "
+ ", tenDayQualifyingDays: "
+ ", todaySigHours: "
+ "Accessibility label for the close button on the parasol auto-switch tip popover."
+ "ActiveLocationInput"
+ "ActiveLocationModel"
+ "AirQualityDetailViewModel"
+ "AveragesDetailInput"
+ "AveragesDetailViewModel"
+ "AveragesLocationContentComponent is unconditional, but missing from LocationContentViewLayoutConfiguration!"
+ "ConditionDetailInput"
+ "ConditionDetailMapDisplayStyle"
+ "DailyForecastLocationContentComponent is unconditional, but missing from LocationContentViewLayoutConfiguration!"
+ "DayPickerViewModel"
+ "Dynamic as Default View"
+ "EnhancedLandscapeLocationPreviewInput"
+ "EnhancedLandscapeLocationPreviewViewModel"
+ "EnhancedLandscapeLocationViewerInput"
+ "EnhancedLandscapeLocationViewerViewModel"
+ "FeelsLikeLocationContentComponent is unconditional, but missing from LocationContentViewLayoutConfiguration!"
+ "Force Show Parasol Auto-Switch Tip"
+ "GeneralConfigurationInput"
+ "GeneralConfigurationViewModel"
+ "HomeAndWorkRefinementInput"
+ "HomeAndWorkRefinementViewModel"
+ "HorizontalABWithB1x1RatioLayout"
+ "HourlyForecastLocationContentComponent is unconditional, but missing from LocationContentViewLayoutConfiguration!"
+ "Hourly_Forecast_Input_Precipitation_Subtitle_Sleet_AX"
+ "Hourly_Forecast_Input_Precipitation_Subtitle_Snow_AX"
+ "Hourly_Forecast_Input_Precipitation_Subtitle_WintryMix_AX"
+ "HumidityLocationContentComponent is unconditional, but missing from LocationContentViewLayoutConfiguration!"
+ "Incorrect actor executor assumption; Expected same executor as "
+ "Intensity, Chance of Sleet"
+ "Intensity, Chance of Snow"
+ "Intensity, Chance of Wintry Mix"
+ "InteractiveMapInput"
+ "InteractiveMapViewModel"
+ "InteractiveSceneResizeTraits"
+ "ListMenuViewModel"
+ "LocationPreviewInput"
+ "LocationPreviewViewModel"
+ "LocationViewModel"
+ "LocationViewerInput"
+ "LocationViewerViewModel"
+ "MoonCalendarInput"
+ "MoonCalendarViewModel"
+ "MoonDetailViewModel"
+ "MoonLocationContentComponent is unconditional, but missing from LocationContentViewLayoutConfiguration!"
+ "MoonScrubberInput"
+ "MoonScrubberViewModel"
+ "NextHourPrecipitationDetailInput"
+ "NextHourPrecipitationDetailViewModel"
+ "NotificationSettingsInput"
+ "NotificationSettingsViewModel"
+ "NotificationsOptInInput"
+ "NotificationsOptInViewModel"
+ "Only Show Parasol Auto-Switch Tip"
+ "OpenL2Descriptor"
+ "Optional<AttributedString>.nil"
+ "Optional<Bool>.nil"
+ "Optional<Date>.nil"
+ "Optional<Dictionary<String, NSSecureCoding>>.nil"
+ "Optional<Int>.nil"
+ "Optional<LocationsOfInterestState>.nil"
+ "Optional<String>.nil"
+ "Optional<URL>.nil"
+ "ParasolAutoSwitchTip.isAutoSwitchActive=%{bool}d"
+ "ParasolAutoSwitchTip.isValid=%{bool}d"
+ "ParasolDailyForecastLocationContentComponent is unconditional, but missing from LocationContentViewLayoutConfiguration!"
+ "PrecipitationTotalLocationContentComponent is unconditional, but missing from LocationContentViewLayoutConfiguration!"
+ "PressureLocationContentComponent is unconditional, but missing from LocationContentViewLayoutConfiguration!"
+ "ReportWeatherViewModel"
+ "Reset Condition to Default"
+ "SizeClassTransitionTracker"
+ "SunriseSunsetDetailDataProcessor"
+ "SunriseSunsetDetailInput"
+ "SunriseSunsetDetailInteractor"
+ "SunriseSunsetDetailViewModel"
+ "SunriseSunsetLocationContentComponent is unconditional, but missing from LocationContentViewLayoutConfiguration!"
+ "Tap for More Conditions"
+ "The accessibility description used for the subtitle of the Hourly Forecast component when the 'Precipitation' notable condition is selected and current conditions are snowy"
+ "The accessibility description used for the subtitle of the Hourly Forecast component when the 'Precipitation' notable condition is selected and current conditions include sleet"
+ "The accessibility description used for the subtitle of the Hourly Forecast component when the 'Precipitation' notable condition is selected and current conditions include wintry mix"
+ "The precipitation or wind view displays automatically based on the forecast. You can change this in Settings."
+ "Title of an action in a tip that redirects the user to the Weather pane in system Settings."
+ "UVIndexLocationContentComponent is unconditional, but missing from LocationContentViewLayoutConfiguration!"
+ "UnitsConfigurationInput"
+ "UnitsConfigurationViewModel"
+ "VFXTestViewModel"
+ "VisibilityLocationContentComponent is unconditional, but missing from LocationContentViewLayoutConfiguration!"
+ "Weather/LocationViewerStoreObserver.swift"
+ "WeatherConditionBackgroundModel"
+ "WeatherConditionBackgroundModelFactoryInput"
+ "WeatherDataStoreObserver"
+ "WeatherMenuInput"
+ "WeatherMenuViewModel"
+ "WindLocationContentComponent is unconditional, but missing from LocationContentViewLayoutConfiguration!"
+ "XCTAutomationSupport bundle is loaded"
+ "XCTAutomationSupport bundle is not loaded"
+ "_TtC7Weather26SizeClassTransitionTracker"
+ "_TtC7Weather33LocationDetailDismissalFocusState"
+ "_TtC7WeatherP33_7CEEE4CFF6C247D2D17BF5A0A3D2F8E846EnhancedLandscapeLocationViewObserverViewState"
+ "_activeLocationIdentifier"
+ "_dismissalToken"
+ "_isInTransition"
+ "_isParasolAutoSwitchTipAvailable"
+ "_parasolAutoSwitchTipScrollDismissedLocationIDs"
+ "bundleWithIdentifier:"
+ "c18e6bcfcdbd65fd193e4ba6a8294c04"
+ "com.apple.dt.XCTAutomationSupport"
+ "lastParasolActiveLocationIdentifier"
+ "latestContentStatus"
+ "mm), condition: "
+ "parasolAutoSwitch"
+ "parasolAutoSwitchTip"
+ "parasolAutoSwitched"
+ "significantPrecipitation"
+ "transitionTracker"
+ "visibleLocationIdentifier"
+ "weather.tappableModulesTip.tipOverrides.forceShowParasolAutoSwitchTip"
+ "weather.tappableModulesTip.tipsFilters.forceShowParasolAutoSwitchTip"
- " is unconditional, but missing from "
- ", precipDeviation: "
- "About to present reset identifier alert"
- "Allow Weather to access your home and work addresses from ^[Contact Card](link: 'linkA'). Requires Location Services."
- "Average high: **%@**"
- "Description for the average high temperature across the span of a day, averaged over every year since around 1933. Bold formatting is denoted by asterisks. ex: 'Average high: **30°**'"
- "Description for the historic average precipitation over a 30 day period, averaged over every year since around 1933, when space is limited. Bold formatting is denoted by asterisks. ex: 'Average: **5cm**'"
- "Description for today's high temperature. Bold formatting is denoted by asterisks. ex: 'Today’s high: **30°**'"
- "EnvironmentValues"
- "Failed to find location index from location list for location:%{private,mask.hash}s"
- "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do"
- "Message of Reset Identifier confirmation dialog."
- "Performing Tap instruction: %s"
- "Performing enumerate instruction"
- "Rain for the next 45 minutes."
- "Reset Identifier"
- "Text of cancel button in Reset Identifier confirmation dialog."
- "Text of confirm button in Reset Identifier confirmation dialog."
- "The title for the home and work section in the general setting view"
- "Title of Reset Identifier confirmation dialog."
- "Title of a checkbox that can enable or disable Home and Work location feature in Mac Weather app settings"
- "Today’s high: **%@**"
- "Weather Component Button"
- "Weather Component Button AX Label"
- "Weather Component Button AX Value"
- "Weather/CopyOnWrite.swift"
- "Would you like to reset the identifier used by Apple Weather to report aggregate app usage statistics to Apple? The identifier will be reset the next time you close Weather and reopen the app."
- "averages_precipitation_average"
- "averages_temperature_average"
- "averages_temperature_current"
- "cell"
- "changeInCondition"
- "channelName"
- "com.apple.systempreferences"
- "component"
- "ed0cb1820a00e77084036761638c7575"
- "failed to obtain rootViewController for resetting identifier"
- "general_configuration_home_and_work_section_title"
- "getCGImageForImageDescriptor:completion:"
- "https://gspe21-ssl.ls.apple.com/html/attribution-221.html"
- "https://support.apple.com/en-us/HT211777"
- "imageDescriptorNamed:"
- "initWithBundleIdentifier:"
- "initWithCGImage:"
- "m/s, gust12h_max: "
- "m/s, windHighlight: "
- "min max "
- "mm), snow12h_max: "
- "mm, pastPrecip6h_avg: "
- "mm/h, wind12h_max: "
- "overlayKind"
- "reportConcern"
- "searchSelection"
- "seasonalContrast"
- "start width "
- "unusuallyHighGusts"
- "unusuallyHighWind"
- "v16@?0^{CGImage=}8"
```
