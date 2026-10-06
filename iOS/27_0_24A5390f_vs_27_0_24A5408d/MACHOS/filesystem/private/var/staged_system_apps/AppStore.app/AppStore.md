## AppStore

> `/private/var/staged_system_apps/AppStore.app/AppStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77a594` | `0x782cc4` | **`+0x8730`** |
| `__TEXT.__objc_methname` | `0x1f8b5` | `0x1fc45` | **`+0x390`** |
| `__DATA.__objc_data` | `0x2a920` | `0x2ac40` | **`+0x320`** |
| `__DATA.__objc_const` | `0x6d3c0` | `0x6d6c0` | **`+0x300`** |
| `__DATA.__data` | `0x2a440` | `0x2a6e0` | **`+0x2a0`** |
| `__DATA.__bss` | `0x37558` | `0x377d8` | **`+0x280`** |
| `__TEXT.__swift5_reflstr` | `0x17b58` | `0x17d78` | **`+0x220`** |
| `__TEXT.__objc_stubs` | `0xbc80` | `0xbe60` | **`+0x1e0`** |
| `__TEXT.__const` | `0x35b84` | `0x35d44` | **`+0x1c0`** |
| `__TEXT.__swift5_fieldmd` | `0x1278c` | `0x12938` | **`+0x1ac`** |
| `__DATA.__common` | `0x6f70` | `0x7110` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x131e5` | `0x13385` | **`+0x1a0`** |
| `__TEXT.__eh_frame` | `0x3090` | `0x2f18` | **`-0x178`** |
| `__TEXT.__constg_swiftt` | `0x19e4c` | `0x19fa8` | **`+0x15c`** |
| `__TEXT.__unwind_info` | `0x12438` | `0x12550` | **`+0x118`** |
| `__TEXT.__swift5_typeref` | `0xfadc` | `0xfbc8` | **`+0xec`** |
| `__DATA_CONST.__const` | `0x26b58` | `0x26a80` | **`-0xd8`** |
| `__TEXT.__swift5_capture` | `0x8b34` | `0x8c04` | **`+0xd0`** |
| `__TEXT.__auth_stubs` | `0x16f00` | `0x16fc0` | **`+0xc0`** |
| `__DATA.__objc_selrefs` | `0x4d80` | `0x4e20` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0xe3ac` | `0xe424` | **`+0x78`** |
| `__DATA_CONST.__auth_got` | `0xb790` | `0xb7f0` | **`+0x60`** |
| `__TEXT.__objc_classname` | `0x9bd7` | `0x9c17` | **`+0x40`** |
| `__DATA_CONST.__auth_ptr` | `0x6c68` | `0x6c98` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x4e88` | `0x4eb8` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x20f8` | `0x2128` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x198` | `0x17c` | **`-0x1c`** |
| `__TEXT.__swift5_builtin` | `0x3d4` | `0x3e8` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x1fd0` | `0x1fe4` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x1420` | `0x1428` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1174` | `0x117c` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x14c` | `0x148` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-27.0.65.0.0
+27.0.75.0.0

-  Functions: 27808
-  Symbols:   9787
-  CStrings:  7262
+  Functions: 27962
+  Symbols:   9805
+  CStrings:  7319
Symbols:
+ _$s11AppStoreKit14PageLayoutModeOSHAAMc
+ _$s11AppStoreKit14TodayCardMediaC4KindO11descriptionSSvg
+ _$s11AppStoreKit15MediaPageHeaderC14eyebrowArtworkAA0H0CSgvg
+ _$s11AppStoreKit17PrivacyTypeLayoutV7MetricsV19horizontalAlignment12iconTopSpace0J4Size0J8Baseline05titlekL006detailkL012maxTextWidth023minimumCategoriesColumnS0010categorieskL00W17HorizontalPadding0w6BottomL00H6Margin07compactZ6Margin07regularZ6Margin22maximumCategoryColumnsA2E0xI0O_5JetUI12AnyDimension_pSo6CGSizeV12CoreGraphics7CGFloatVAwX_pAwX_pAwX_pSgAwX_pAwX_pAwX_pAwX_pAwX_pAwX_pAwX_pSitcfC
+ _$s11AppStoreKit18OfferButtonMetricsV02inA17PurchaseTextSpace5JetUI12AnyDimension_pvs
+ _$s11AppStoreKit18OfferButtonMetricsV10fontSource012subtitleFontH002inA17PurchaseTextSpace13contentInsets15redownloadImage05pauseR006pausedR19SymbolConfiguration06symbolV00qruV011minimumSize16progressDiameter9lineWidth18textShapeLineWidth12expandsToFit12cornerRadius17includeTopPadding06resumeR16NavigationHeight06resumeR24NavigationBaselineOffset0I8MaxWidth32multilineSubtitleTopPaddingScaleAC5JetUI0jH0O_AzX12AnyDimension_pSo06UIEdgeP0VSo7UIImageCyXAA3_yXASo07UIImageuV0CSgA5_A6_So6CGSizeV12CoreGraphics7CGFloatVA11_A11_SgSbA12_SbA12_A12_A12_A11_tcfC
+ _$s11AppStoreKit18OfferButtonMetricsV13contentInsetsSo06UIEdgeH0Vvs
+ _$s11AppStoreKit18OfferButtonMetricsV16progressDiameter12CoreGraphics7CGFloatVvs
+ _$s11AppStoreKit18OfferButtonMetricsV16subtitleMaxWidth12CoreGraphics7CGFloatVSgvs
+ _$s11AppStoreKit18OfferButtonMetricsV18subtitleFontSource5JetUI0hI0Ovs
+ _$s11AppStoreKit18OfferButtonMetricsV32multilineSubtitleTopPaddingScale12CoreGraphics7CGFloatVvs
+ _$s11AppStoreKit21DiffablePagePresenterC16reconfigureItemsyySayAA0dE17ContentIdentifierVGFTj
+ _$s11AppStoreKit21GuidedSearchPresenterC13currentTokensAA0dE15TokenCollectionVvg
+ _$s11AppStoreKit22SheetEngagementManagerC07requesta6LaunchD03bag10onFinishedyAA14ASKBagContractCSg_yycSgtF
+ _$s11AppStoreKit25MediumSummaryLockupLayoutV7MetricsV18titleNumberOfLinesSivg
+ _$s11AppStoreKit26TodayDiffablePagePresenterC012debugCurrentD5CardsSayAA0D4CardCGvg
+ _$s11AppStoreKit26TodaySectionDisplayOptionsV05GroupF5StyleOMn
+ _$s11AppStoreKit26TodaySectionDisplayOptionsV05GroupF5StyleOSQAAMc
+ _$s11AppStoreKit26TodaySectionDisplayOptionsV29canExtendStandardOverflowItemSbvg
+ _$s11AppStoreKit34SearchResultsDiffablePagePresenterC06notifyG11DidReappearyyFTj
+ _$s11AppStoreKit42NestedCollectionViewImpressionsCoordinatorC10deregister3forySo012UICollectionF4CellC_tFTj
+ _$s11AppStoreKit7ArtworkC11URLTemplateV15systemImageNameSSSgvg
+ _$s20ServicesIntelligence0aB8ProviderC13clearAppUsageyyYaKF
+ _$s20ServicesIntelligence0aB8ProviderC13clearAppUsageyyYaKFTu
+ _$s5UIKit15UIMutableTraitsPAAE12displayScale12CoreGraphics7CGFloatVvs
+ _$s5UIKit15UIMutableTraitsPAAE15layoutDirectionSo024UITraitEnvironmentLayoutE0Vvs
+ _$s5UIKit15UIMutableTraitsPAAE17verticalSizeClassSo015UIUserInterfaceeF0Vvs
+ _$s5UIKit15UIMutableTraitsPAAE18userInterfaceIdiomSo06UIUsereF0Vvs
+ _$s5UIKit15UIMutableTraitsPAAE19horizontalSizeClassSo015UIUserInterfaceeF0Vvs
+ _$s9JetEngine17ImpressionMetricsV2IDVSQAAMc
+ _$sSfs7CVarArgsWP
+ _$sSo17UITraitCollectionC5UIKitE9mutationsAByAC15UIMutableTraits_pzXE_tcfC
+ _CGImageGetHeight
+ _CGImageGetWidth
+ _OBJC_CLASS_$_AMSFeatureFlagITFE
+ _OBJC_CLASS_$_UIGlassContainerEffect
+ _OBJC_CLASS_$_UISlider
+ _UIBarButtonItemVisibilityPriorityHigh
- _$s11AppStoreKit10RateActionC6adamIdAA04AdamG0Vvg
- _$s11AppStoreKit14ASKBagContractC20isRatingsLoadEnabledSbvg
- _$s11AppStoreKit15MediaPageHeaderC13eyebrowSymbolSSSgvg
- _$s11AppStoreKit15UserRatingCacheC04loadE06adamIdySS_tFTj
- _$s11AppStoreKit15UserRatingCacheC10invalidate6adamIdySS_tFTj
- _$s11AppStoreKit15UserRatingCacheC11objectGraphAC9JetEngine010BaseObjectH0C_tcfC
- _$s11AppStoreKit15UserRatingCacheC5stars14fromNormalizedSuSd_tFZ
- _$s11AppStoreKit15UserRatingCacheC6update6adamId6ratingySS_SuSgtFTj
- _$s11AppStoreKit15UserRatingCacheC7ratings3forScSySuSgGSS_tFTj
- _$s11AppStoreKit15UserRatingCacheCMa
- _$s11AppStoreKit15UserRatingCacheCMn
- _$s11AppStoreKit15UserRatingCacheCScAAAMc
- _$s11AppStoreKit17PrivacyTypeLayoutV7MetricsV19horizontalAlignment12iconTopSpace0J4Size0J8Baseline05titlekL006detailkL012maxTextWidth023minimumCategoriesColumnS0010categorieskL00W17HorizontalPadding0w6BottomL00H6Margin07compactZ6Margin07regularZ6MarginA2E0xI0O_5JetUI12AnyDimension_pSo6CGSizeV12CoreGraphics7CGFloatVAvW_pAvW_pAvW_pSgAvW_pAvW_pAvW_pAvW_pAvW_pAvW_pAvW_ptcfC
- _$s11AppStoreKit18OfferButtonMetricsV10fontSource012subtitleFontH002inA17PurchaseTextSpace13contentInsets15redownloadImage05pauseR006pausedR19SymbolConfiguration06symbolV00qruV011minimumSize16progressDiameter9lineWidth18textShapeLineWidth12expandsToFit12cornerRadius17includeTopPadding06resumeR16NavigationHeight06resumeR24NavigationBaselineOffsetAC5JetUI0jH0O_AxV12AnyDimension_pSo06UIEdgeP0VSo7UIImageCyXAA1_yXASo07UIImageuV0CSgA3_A4_So6CGSizeV12CoreGraphics7CGFloatVA9_A9_SgSbA10_SbA10_A10_tcfC
- _$s11AppStoreKit22SheetEngagementManagerC07requesta6LaunchD03bagyAA14ASKBagContractCSg_tF
- _$s11AppStoreKit9TapToRateC6ratingSfSgvg
- _$s20AppleMediaServicesUI10ReviewDataC6ratingSdSgvg
- _$s20AppleMediaServicesUI12ReviewResultO7successyAcA0E4DataC_tcACmFWC
- _$s5UIKit15UIMutableTraitsP11AppStoreKitE14pageLayoutModeAD04PagehI0Ovg
- __UIBarElementVisibilityPriorityHigh
CStrings:
+ "AppStore.TodayCardTransitionHarnessViewController"
+ "AppStore/TodayCardTransitionHarnessViewController.swift"
+ "Card Transition Lab"
+ "Compact height (landscape)"
+ "Enable the on screen button that opens the Today card VisualStyle transition harness"
+ "Failed to clear app usage: "
+ "No cards in feed"
+ "TodaySettings.transitionHarness"
+ "_TtC8AppStore40TodayCardTransitionHarnessViewController"
+ "_gridFootprint"
+ "addClip"
+ "alignedRegionArtworkAspectRatio"
+ "bezierPathWithOvalInRect:"
+ "canvas"
+ "cardPickerButton"
+ "cards"
+ "compactHeightSwitch"
+ "compactHeightToggled"
+ "currentCard"
+ "currentWidth"
+ "dismissHarness"
+ "durationLabel"
+ "durationSlider"
+ "durationSliderChanged"
+ "fontForStyle"
+ "fontStyle"
+ "glassContainer"
+ "gridFootprint"
+ "hostedCell"
+ "inAppPurchaseCompact"
+ "initWithInteger:"
+ "initWithItems:"
+ "initWithPath:retinaScale:"
+ "isMini"
+ "isOriginallyMini"
+ "lastConfiguredContentWidth"
+ "minWidth"
+ "originalGridFootprint"
+ "originalIsMini"
+ "paletteImpressionCalculator"
+ "pathForResource:ofType:"
+ "rectangle.expand.vertical"
+ "refreshGuidedSearchImpressionsOnNextAppear"
+ "removeArrangedSubview:"
+ "setContentsRect:"
+ "setIncludeAppLinksForCallingApplication:"
+ "setMaximumValue:"
+ "setMinimumValue:"
+ "setMutableFeatureName:toValue:"
+ "setSearchBarStyle:"
+ "setValue:"
+ "setVisibilityPriority:"
+ "stopCount"
+ "stopsBuiltForMaxWidth"
+ "stopsRow"
+ "stopsSegmentChanged"
+ "stopsSegmentedControl"
+ "systemPurpleColor"
+ "transitionHarnessButton"
+ "usesCompactMetrics"
+ "value"
+ "visualStyle"
+ "widthLabel"
+ "widthSlider"
+ "widthSliderChanged"
- "Compact Extra Wide"
- "_setVisibilityPriority:"
- "_sizeCategory"
- "fontForSizeCategory"
- "initWithFileName:retinaScale:"
- "originalSizeCategory"
- "ratingSubscription"
- "sizeCategory"
```
