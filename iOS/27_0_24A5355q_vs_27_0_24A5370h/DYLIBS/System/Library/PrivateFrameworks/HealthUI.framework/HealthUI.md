## HealthUI

> `/System/Library/PrivateFrameworks/HealthUI.framework/HealthUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41bb98` | `0x43c3f0` | **`+0x20858`** |
| `__AUTH_CONST.__const` | `0x7778` | `0x84b8` | **`+0xd40`** |
| `__AUTH_CONST.__objc_const` | `0x65490` | `0x66040` | **`+0xbb0`** |
| `__TEXT.__cstring` | `0x2280f` | `0x2312f` | **`+0x920`** |
| `__AUTH.__objc_data` | `0x17c10` | `0x18368` | **`+0x758`** |
| `__TEXT.__eh_frame` | `0x2a30` | `0x3058` | **`+0x628`** |
| `__TEXT.__const` | `0x8744` | `0x8d44` | **`+0x600`** |
| `__TEXT.__unwind_info` | `0xeb18` | `0xf110` | **`+0x5f8`** |
| `__DATA.__bss` | `0x6af0` | `0x70c0` | **`+0x5d0`** |
| `__TEXT.__objc_methlist` | `0x3ad04` | `0x3b27c` | **`+0x578`** |
| `__TEXT.__swift5_reflstr` | `0x2cb6` | `0x3066` | **`+0x3b0`** |
| `__TEXT.__swift5_fieldmd` | `0x2cec` | `0x3078` | **`+0x38c`** |
| `__TEXT.__swift5_typeref` | `0x311e` | `0x3488` | **`+0x36a`** |
| `__TEXT.__swift5_capture` | `0xe64` | `0x1150` | **`+0x2ec`** |
| `__TEXT.__constg_swiftt` | `0x4c68` | `0x4e84` | **`+0x21c`** |
| `__DATA_CONST.__objc_selrefs` | `0x18818` | `0x18a10` | **`+0x1f8`** |
| `__TEXT.__oslogstring` | `0x7195` | `0x7385` | **`+0x1f0`** |
| `__DATA.__data` | `0x8078` | `0x8220` | **`+0x1a8`** |
| `__AUTH.__data` | `0x2538` | `0x2628` | **`+0xf0`** |
| `__AUTH_CONST.__auth_got` | `0x3008` | `0x3078` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x79e8` | `0x7978` | **`-0x70`** |
| `__TEXT.__swift5_builtin` | `0x294` | `0x2f8` | **`+0x64`** |
| `__TEXT.__swift5_assocty` | `0x788` | `0x7e8` | **`+0x60`** |
| `__DATA_CONST.__objc_classlist` | `0x2158` | `0x21a8` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x1e980` | `0x1e9c0` | **`+0x40`** |
| `__TEXT.__swift5_types` | `0x3b0` | `0x3f0` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0xe4` | `0x11c` | **`+0x38`** |
| `__TEXT.__swift5_proto` | `0x368` | `0x39c` | **`+0x34`** |
| `__TEXT.__gcc_except_tab` | `0x2378` | `0x23a4` | **`+0x2c`** |
| `__DATA.__common` | `0x238` | `0x250` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x68` | `0x7c` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x58` | `0x6c` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x3758` | `0x3768` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x6b8` | `0x6c8` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x178` | `0x188` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x1860` | `0x1870` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0x28` | `0x38` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x4058` | `0x4054` | **`-0x4`** |
| `__TEXT.__swift5_protos` | `0x68` | `0x6c` | **`+0x4`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  Functions: 25612
-  Symbols:   35470
-  CStrings:  5247
+  Functions: 26132
+  Symbols:   35603
+  CStrings:  5300
Symbols:
+ +[HKSettingsAuthorizationFactory authorizationTypeDetailViewControllerWithTypeName:type:sourceAuthorizationController:healthStore:onDidSave:]
+ +[HKSettingsAuthorizationFactory authorizationViewControllerWithSource:sourceAuthorizationController:healthStore:shareDescription:updateDescription:storedDataViewControllerProvider:backgroundAppRefreshStatusProvider:]
+ -[HKCalendarScrollViewController _resizeWeekViewsToWidth:]
+ -[HKCalendarScrollViewController viewWillTransitionToSize:withTransitionCoordinator:]
+ -[HKCodableSummaryBalanceMetricsValue hasOutlierContext]
+ -[HKCodableSummaryBalanceMetricsValue outlierContext]
+ -[HKCodableSummaryBalanceMetricsValue setHasOutlierContext:]
+ -[HKCodableSummaryBalanceMetricsValue setOutlierContext:]
+ -[HKDataMetadataSimpleTableViewCell _updateLabelHiddenState]
+ -[HKDataMetadataSimpleTableViewCell labelStackView]
+ -[HKDataMetadataSimpleTableViewCell layoutSubviews]
+ -[HKDataMetadataSimpleTableViewCell prepareForReuse]
+ -[HKDataMetadataSimpleTableViewCell setLabelStackView:]
+ -[HKDataMetadataSimpleTableViewCell systemLayoutSizeFittingSize:withHorizontalFittingPriority:verticalFittingPriority:]
+ -[HKDisplayType(DerivedProperties) sampleTypesForDateRange]
+ -[HKElectrocardiogramMetadataView footerLabel]
+ -[HKElectrocardiogramMetadataView setFooterLabel:]
+ -[HKElectrocardiogramMetadataView setFooterPreferredMaxLayoutWidth:]
+ -[HKInteractiveChartDisplayType sampleTypesForDateRange]
+ -[HKLevelCategoryTimePeriodSeries categoryLabelBackgroundColor]
+ -[HKMonthWeekView _layoutAccessoryViewContainers]
+ -[HKNavigationController lastKnownWindowSize]
+ -[HKNavigationController setLastKnownWindowSize:]
+ -[HKOrganDonationAlreadyDonorViewController learnMoreButtonTapped:]
+ -[HKOrganDonationAlreadyDonorViewController viewDidLoad]
+ -[HKOrganDonationBaseViewController _addCustomImageIconViewIfNeeded]
+ -[HKOrganDonationBaseViewController _addDoneButtonWithAction:]
+ -[HKOrganDonationBaseViewController _removeOBContentViewHeightConstraints]
+ -[HKOrganDonationBaseViewController bodyString]
+ -[HKOrganDonationBaseViewController titleImage]
+ -[HKOrganDonationBaseViewController titleString]
+ -[HKOrganDonationBaseViewController viewDidLoad]
+ -[HKOrganDonationConfirmDeleteViewController viewDidLoad]
+ -[HKOrganDonationConfirmUpdateViewController viewDidLoad]
+ -[HKOrganDonationConfirmationViewController _privacyButtonTapped:]
+ -[HKOrganDonationConfirmationViewController _registerMeButtonTapped:]
+ -[HKOrganDonationDeleteSuccessViewController _doneButtonTapped:]
+ -[HKOrganDonationMoreAboutPrivacyViewController _closeButtonTapped:]
+ -[HKOrganDonationMoreAboutPrivacyViewController init]
+ -[HKOrganDonationRegisterViewController _addCustomImageIconViewIfNeeded]
+ -[HKOrganDonationRegisterViewController _updateContinueButtonForCurrentMode]
+ -[HKOrganDonationRegisterViewController _updateHeaderForCurrentMode]
+ -[HKOrganDonationThankYouViewController .cxx_destruct]
+ -[HKOrganDonationUnderageViewController _doneButtonTapped:]
+ -[HKOrganDonationUnderageViewController viewDidLoad]
+ -[HKOrganDonationUpdateSuccessViewController _doneButtonTapped:]
+ -[HKOverlayRoomViewController viewDidLayoutSubviews]
+ -[HKSourceAuthorizationController commitAuthorizationStatusForType:]
+ -[UIViewController(HKAdditions) hk_isInFormSheetModal]
+ -[_HKDateContentLayout _dateToContentSpacing]
+ GCC_except_table128
+ GCC_except_table143
+ GCC_except_table148
+ GCC_except_table154
+ GCC_except_table47
+ GCC_except_table88
+ OBJC_IVAR_$_HKCodableSummaryBalanceMetricsValue._outlierContext
+ _NSSelectorFromString
+ _OBJC_CLASS_$_HKAuthorizationSettingsModernizedViewController
+ _OBJC_CLASS_$_HKGlyphTightTextLayout
+ _OBJC_CLASS_$_HKSettingsAuthorizationFactory
+ _OBJC_CLASS_$__TtC8HealthUI25HKAuthorizationToggleCell
+ _OBJC_CLASS_$__TtC8HealthUI32HKAuthorizationAppIconHeaderView
+ _OBJC_CLASS_$__TtC8HealthUI37HKSettingsAuthorizationViewController
+ _OBJC_CLASS_$__TtC8HealthUI39HKAuthorizationCategoryToggleHeaderView
+ _OBJC_CLASS_$__TtC8HealthUI40HKAuthorizationTimeBoundedViewController
+ _OBJC_CLASS_$__TtC8HealthUI47HKSettingsAuthorizationTypeDetailViewController
+ _OBJC_CLASS_$__TtCO8HealthUI17WorkoutZonesCells18UnitValueEntryCell
+ _OBJC_IVAR_$_HKCalendarScrollViewController._lastLayoutWidth
+ _OBJC_IVAR_$_HKCalendarScrollViewController._pendingAnchorDate
+ _OBJC_IVAR_$_HKDataMetadataSimpleTableViewCell._labelStackView
+ _OBJC_IVAR_$_HKElectrocardiogramMetadataView._footerLabel
+ _OBJC_IVAR_$_HKLevelCategoryTimePeriodSeries._categoryLabelBackgroundColor
+ _OBJC_IVAR_$_HKNavigationController._lastKnownWindowSize
+ _OBJC_IVAR_$_HKOrganDonationThankYouViewController._shareButton
+ _OBJC_METACLASS_$_HKAuthorizationSettingsModernizedViewController
+ _OBJC_METACLASS_$_HKGlyphTightTextLayout
+ _OBJC_METACLASS_$_HKSettingsAuthorizationFactory
+ _OBJC_METACLASS_$__TtC8HealthUI25HKAuthorizationToggleCell
+ _OBJC_METACLASS_$__TtC8HealthUI32HKAuthorizationAppIconHeaderView
+ _OBJC_METACLASS_$__TtC8HealthUI37HKSettingsAuthorizationViewController
+ _OBJC_METACLASS_$__TtC8HealthUI39HKAuthorizationCategoryToggleHeaderView
+ _OBJC_METACLASS_$__TtC8HealthUI40HKAuthorizationTimeBoundedViewController
+ _OBJC_METACLASS_$__TtC8HealthUI47HKSettingsAuthorizationTypeDetailViewController
+ _OBJC_METACLASS_$__TtC8HealthUIP33_6437C8397BE458390DCCD81C27D63EDE18PreambleHeaderView
+ _OBJC_METACLASS_$__TtCO8HealthUI17WorkoutZonesCells18UnitValueEntryCell
+ _UIAccessibilityTraitButton
+ _UIAccessibilityTraitSelected
+ __CLASS_METHODS_HKGlyphTightTextLayout
+ __CLASS_METHODS__TtC8HealthUI47HKSettingsAuthorizationTypeDetailViewController
+ __DATA_HKAuthorizationSettingsModernizedViewController
+ __DATA_HKGlyphTightTextLayout
+ __DATA__TtC8HealthUI25HKAuthorizationToggleCell
+ __DATA__TtC8HealthUI32HKAuthorizationAppIconHeaderView
+ __DATA__TtC8HealthUI37HKSettingsAuthorizationViewController
+ __DATA__TtC8HealthUI39HKAuthorizationCategoryToggleHeaderView
+ __DATA__TtC8HealthUI40HKAuthorizationTimeBoundedViewController
+ __DATA__TtC8HealthUI47HKSettingsAuthorizationTypeDetailViewController
+ __DATA__TtC8HealthUIP33_6437C8397BE458390DCCD81C27D63EDE18PreambleHeaderView
+ __DATA__TtCO8HealthUI17WorkoutZonesCells18UnitValueEntryCell
+ __HKStatisticsOptionPresence
+ __INSTANCE_METHODS_HKGlyphTightTextLayout
+ __INSTANCE_METHODS__TtC8HealthUI25HKAuthorizationToggleCell
+ __INSTANCE_METHODS__TtC8HealthUI32HKAuthorizationAppIconHeaderView
+ __INSTANCE_METHODS__TtC8HealthUI39HKAuthorizationCategoryToggleHeaderView
+ __INSTANCE_METHODS__TtC8HealthUI40HKAuthorizationTimeBoundedViewController
+ __INSTANCE_METHODS__TtC8HealthUI47HKSettingsAuthorizationTypeDetailViewController
+ __INSTANCE_METHODS__TtC8HealthUIP33_6437C8397BE458390DCCD81C27D63EDE18PreambleHeaderView
+ __INSTANCE_METHODS__TtCO8HealthUI17WorkoutZonesCells18UnitValueEntryCell
+ __IVARS_HKAuthorizationSettingsModernizedViewController
+ __IVARS__TtC8HealthUI25HKAuthorizationToggleCell
+ __IVARS__TtC8HealthUI32HKAuthorizationAppIconHeaderView
+ __IVARS__TtC8HealthUI37HKSettingsAuthorizationViewController
+ __IVARS__TtC8HealthUI39HKAuthorizationCategoryToggleHeaderView
+ __IVARS__TtC8HealthUI40HKAuthorizationTimeBoundedViewController
+ __IVARS__TtC8HealthUI47HKSettingsAuthorizationTypeDetailViewController
+ __IVARS__TtC8HealthUIP33_6437C8397BE458390DCCD81C27D63EDE18PreambleHeaderView
+ __IVARS__TtCO8HealthUI17WorkoutZonesCells18UnitValueEntryCell
+ __METACLASS_DATA_HKAuthorizationSettingsModernizedViewController
+ __METACLASS_DATA_HKGlyphTightTextLayout
+ __METACLASS_DATA__TtC8HealthUI25HKAuthorizationToggleCell
+ __METACLASS_DATA__TtC8HealthUI32HKAuthorizationAppIconHeaderView
+ __METACLASS_DATA__TtC8HealthUI37HKSettingsAuthorizationViewController
+ __METACLASS_DATA__TtC8HealthUI39HKAuthorizationCategoryToggleHeaderView
+ __METACLASS_DATA__TtC8HealthUI40HKAuthorizationTimeBoundedViewController
+ __METACLASS_DATA__TtC8HealthUI47HKSettingsAuthorizationTypeDetailViewController
+ __METACLASS_DATA__TtC8HealthUIP33_6437C8397BE458390DCCD81C27D63EDE18PreambleHeaderView
+ __METACLASS_DATA__TtCO8HealthUI17WorkoutZonesCells18UnitValueEntryCell
+ __OBJC_$_CLASS_METHODS_HKSettingsAuthorizationFactory
+ __OBJC_$_INSTANCE_METHODS_HKAuthorizationSettingsModernizedViewController(HealthUI|HealthUI1|HealthUI2|HealthUI3|HealthUI4)
+ __OBJC_$_INSTANCE_METHODS_UIView(HKAdditions|HKOBKAdditions|HealthUI)
+ __OBJC_$_INSTANCE_METHODS__TtC8HealthUI37HKSettingsAuthorizationViewController(HealthUI|HealthUI1)
+ __OBJC_$_INSTANCE_VARIABLES_HKOrganDonationThankYouViewController
+ __OBJC_$_PROP_LIST_UIViewController_$_HKAdditions
+ __OBJC_CLASS_PROTOCOLS_$_HKAuthorizationSettingsModernizedViewController(HealthUI|HealthUI1|HealthUI2|HealthUI3|HealthUI4)
+ __OBJC_CLASS_PROTOCOLS_$__TtC8HealthUI37HKSettingsAuthorizationViewController(HealthUI|HealthUI1)
+ __OBJC_CLASS_RO_$_HKSettingsAuthorizationFactory
+ __OBJC_METACLASS_RO_$_HKSettingsAuthorizationFactory
+ __PROPERTIES_HKAuthorizationSettingsModernizedViewController
+ __PROPERTIES__TtC8HealthUI37HKSettingsAuthorizationViewController
+ __PROTOCOLS__TtC8HealthUI40HKAuthorizationTimeBoundedViewController
+ ___39-[HKLevelCategoryTimePeriodSeries init]_block_invoke
+ ___49-[HKMonthWeekView _layoutAccessoryViewContainers]_block_invoke
+ ___56-[HKOrganDonationConfirmationViewController viewDidLoad]_block_invoke
+ ___61-[HKSourceAuthorizationController _setAuthorizationStatuses:]_block_invoke
+ ___block_descriptor_40_e8_32s_e23_v32?0"UIView"8Q16^B24ls32l8
+ ___block_descriptor_48_e8_32s40s_e55_v32?0"_HKAuthorizationModeInfo"8"NSDictionary"16^B24ls32l8s40l8
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e47_v24?0"HKFeatureOnboardingRecord"8"NSError"16ls32l8s40l8s48l8s56l8s64l8
+ ___swift_memcpy25_8
+ ___swift_memcpy4_1
+ __swift_implicitisolationactor_to_executor_cast
+ _associated conformance 8HealthUI32HKAuthorizationAppIconHeaderViewC14ArrowDirectionOSHAASQ
+ _associated conformance 8HealthUI40HKAuthorizationTimeBoundedViewControllerC3Row33_9BE20E9F5759C0A877E43F07F0B85A10LLOSHAASQ
+ _associated conformance 8HealthUI40HKAuthorizationTimeBoundedViewControllerC3Row33_9BE20E9F5759C0A877E43F07F0B85A10LLOs12CaseIterableAA8AllCasessAGP_Sl
+ _associated conformance 8HealthUI47HKSettingsAuthorizationTypeDetailViewControllerC3Row028_F3C021AC8A66450D0B9C3955705J3CEALLOSHAASQ
+ _associated conformance 8HealthUI47HKSettingsAuthorizationTypeDetailViewControllerC3Row028_F3C021AC8A66450D0B9C3955705J3CEALLOs12CaseIterableAA8AllCasessAGP_Sl
+ _associated conformance 8HealthUI47VitalsInteractiveChartsSelectableClassificationOSHAASQ
+ _associated conformance 8HealthUI47VitalsInteractiveChartsSelectableClassificationOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 9HealthKit13HKWorkoutZoneV0A2UIE5BoundOSHADSQ
+ _associated conformance So27HKDisplayCategoryIdentifierVSHSCSQ
+ _get_enum_tag_for_layout_string 8HealthUI24AuthorizationSectionItem33_6437C8397BE458390DCCD81C27D63EDELLO
+ _get_enum_tag_for_layout_string 8HealthUI37HKSettingsAuthorizationViewControllerC7Section33_4A8F31D9C5BB5ADAAA51560B96AFC58ELLO
+ _keypath_get_selector_delegate
+ _objc_retain_x12
+ _symbolic $s8HealthUI33HKAuthorizationToggleCellDelegateP
+ _symbolic IeyB_
+ _symbolic SSSbIegy_Ieggg_
+ _symbolic SSSbytIegnr_ytIegnnr_
+ _symbolic Say_____G 8HealthUI37HKSettingsAuthorizationViewControllerC7Section33_4A8F31D9C5BB5ADAAA51560B96AFC58ELLO
+ _symbolic Say_____G 8HealthUI40HKAuthorizationTimeBoundedViewControllerC3Row33_9BE20E9F5759C0A877E43F07F0B85A10LLO
+ _symbolic Say_____G 8HealthUI47HKSettingsAuthorizationTypeDetailViewControllerC3Row028_F3C021AC8A66450D0B9C3955705J3CEALLO
+ _symbolic Say_____G 8HealthUI47VitalsInteractiveChartsSelectableClassificationO
+ _symbolic SbIegy_
+ _symbolic SbytIegnr_
+ _symbolic ScCySay_____G_____G 10Foundation4DateV s5NeverO
+ _symbolic ScCySb_____G s5NeverO
+ _symbolic ScCy_____Sg_____G 10Foundation4DateV s5NeverO
+ _symbolic ShySo12HKObjectTypeCG
+ _symbolic So023UITableViewHeaderFooterB0C
+ _symbolic So11UITextFieldC
+ _symbolic So12HKObjectTypeC
+ _symbolic So13HKHealthStoreCSo16UIViewControllerCIeggg_
+ _symbolic So13HKHealthStoreCSo16UIViewControllerCIeghgg_
+ _symbolic So13HKHealthStoreCSo16UIViewControllerCIeyByy_
+ _symbolic So13HKHealthStoreCSo16UIViewControllerCytIeghnnr_
+ _symbolic So16OBBoldTrayButtonCSgXw
+ _symbolic So16UIViewControllerCIego_
+ _symbolic So16UIViewControllerCIegr_
+ _symbolic So16UIViewControllerCIeyBa_
+ _symbolic So16UIViewControllerCycSg
+ _symbolic So17HKDisplayCategoryC8category_SaySo12HKObjectTypeCG5typest
+ _symbolic So23HKDisplayTypeControllerCSg
+ _symbolic So27HKStatisticsCollectionQueryC
+ _symbolic So31HKSourceAuthorizationControllerC
+ _symbolic So47HKAuthorizationSettingsModernizedViewControllerCSgXw
+ _symbolic So47HKAuthorizationSettingsModernizedViewControllerCSgXwz_Xx
+ _symbolic So8HKSourceC
+ _symbolic So8NSStringC_____IeyBy_IeyByy_ 10ObjectiveC8ObjCBoolV
+ _symbolic So8UIButtonC
+ _symbolic So8UISwitchC
+ _symbolic _____ 8HealthUI17WorkoutZonesCellsO18UnitValueEntryCellC
+ _symbolic _____ 8HealthUI18PreambleHeaderView33_6437C8397BE458390DCCD81C27D63EDELLC
+ _symbolic _____ 8HealthUI20GlyphTightTextLayoutC
+ _symbolic _____ 8HealthUI20GlyphTightTextLayoutC0E7MetricsV
+ _symbolic _____ 8HealthUI24AuthorizationSectionItem33_6437C8397BE458390DCCD81C27D63EDELLO
+ _symbolic _____ 8HealthUI24HKTimeBoundedAccessLevelO
+ _symbolic _____ 8HealthUI25HKAuthorizationToggleCellC
+ _symbolic _____ 8HealthUI32HKAuthorizationAppIconHeaderViewC
+ _symbolic _____ 8HealthUI32HKAuthorizationAppIconHeaderViewC14ArrowDirectionO
+ _symbolic _____ 8HealthUI37HKSettingsAuthorizationViewControllerC
+ _symbolic _____ 8HealthUI37HKSettingsAuthorizationViewControllerC7Section33_4A8F31D9C5BB5ADAAA51560B96AFC58ELLO
+ _symbolic _____ 8HealthUI39HKAuthorizationCategoryToggleHeaderViewC
+ _symbolic _____ 8HealthUI40HKAuthorizationTimeBoundedViewControllerC
+ _symbolic _____ 8HealthUI40HKAuthorizationTimeBoundedViewControllerC3Row33_9BE20E9F5759C0A877E43F07F0B85A10LLO
+ _symbolic _____ 8HealthUI47HKSettingsAuthorizationTypeDetailViewControllerC
+ _symbolic _____ 8HealthUI47HKSettingsAuthorizationTypeDetailViewControllerC3Row028_F3C021AC8A66450D0B9C3955705J3CEALLO
+ _symbolic _____ 8HealthUI47VitalsInteractiveChartsSelectableClassificationO
+ _symbolic _____ 9HealthKit13HKWorkoutZoneV
+ _symbolic _____ 9HealthKit13HKWorkoutZoneV0A2UIE5BoundO
+ _symbolic _____ So22HKAuthorizationSectionV
+ _symbolic _____ So24OBTableWelcomeControllerC8HealthUIE21OnboardingImageHeightV
+ _symbolic _____ So27HKDisplayCategoryIdentifierV
+ _symbolic _____ So29HKOverlayRoomPreferredOverlayV
+ _symbolic _____5since_t 10Foundation4DateV
+ _symbolic _____7section_So17HKDisplayCategoryC8categorySaySo12HKObjectTypeCG5typest So22HKAuthorizationSectionV
+ _symbolic _____IeyBy_ 10ObjectiveC8ObjCBoolV
+ _symbolic _____Sg 8HealthUI40HKAuthorizationTimeBoundedViewControllerC3Row33_9BE20E9F5759C0A877E43F07F0B85A10LLO
+ _symbolic _____Sg 8HealthUI47VitalsInteractiveChartsSelectableClassificationO
+ _symbolic _____SgXw 8HealthUI37HKSettingsAuthorizationViewControllerC
+ _symbolic _____SgXw 8HealthUI47HKSettingsAuthorizationTypeDetailViewControllerC
+ _symbolic _____SgXwz_Xx 8HealthUI37HKSettingsAuthorizationViewControllerC
+ _symbolic _____SgXwz_Xx 8HealthUI47HKSettingsAuthorizationTypeDetailViewControllerC
+ _symbolic ______pSgXw 8HealthUI33HKAuthorizationToggleCellDelegateP
+ _symbolic ______pSgXw So46HKHealthPrivacyServicePromptControllerDelegateP
+ _symbolic ySS_ySbctcSg
+ _symbolic y_____c 8HealthUI24HKTimeBoundedAccessLevelO
+ _type_layout_string 8HealthUI20GlyphTightTextLayoutC0E7MetricsV
+ _type_layout_string 8HealthUI24AuthorizationSectionItem33_6437C8397BE458390DCCD81C27D63EDELLO
+ _type_layout_string 8HealthUI37HKSettingsAuthorizationViewControllerC7Section33_4A8F31D9C5BB5ADAAA51560B96AFC58ELLO
- -[HKOrganDonationAlreadyDonorViewController bottomAnchoredButtons]
- -[HKOrganDonationAlreadyDonorViewController buttonAtIndexTapped:]
- -[HKOrganDonationAlreadyDonorViewController linkButtonTapped:]
- -[HKOrganDonationAlreadyDonorViewController linkButtonTitle]
- -[HKOrganDonationConfirmDeleteViewController bottomAnchoredButtons]
- -[HKOrganDonationConfirmDeleteViewController buttonAtIndexTapped:]
- -[HKOrganDonationConfirmUpdateViewController bottomAnchoredButtons]
- -[HKOrganDonationConfirmUpdateViewController buttonAtIndexTapped:]
- -[HKOrganDonationConfirmationViewController _createTableFooterView]
- -[HKOrganDonationConfirmationViewController _createTableHeaderView]
- -[HKOrganDonationConfirmationViewController loadingIndicatorBarButtonItem]
- -[HKOrganDonationConfirmationViewController loadingIndicator]
- -[HKOrganDonationConfirmationViewController setLoadingIndicator:]
- -[HKOrganDonationConfirmationViewController setLoadingIndicatorBarButtonItem:]
- -[HKOrganDonationConfirmationViewController setTableView:]
- -[HKOrganDonationConfirmationViewController tableView]
- -[HKOrganDonationConfirmationViewController titledBuddyHeaderViewDidTapLinkButton:]
- -[HKOrganDonationConfirmationViewController viewDidLayoutSubviews]
- -[HKOrganDonationDeleteSuccessViewController bottomAnchoredButtons]
- -[HKOrganDonationDeleteSuccessViewController buttonAtIndexTapped:]
- -[HKOrganDonationIntroductionViewController bottomAnchoredButtons]
- -[HKOrganDonationIntroductionViewController buttonAtIndexTapped:]
- -[HKOrganDonationIntroductionViewController linkButtonTapped:]
- -[HKOrganDonationIntroductionViewController linkButtonTitle]
- -[HKOrganDonationMoreAboutPrivacyViewController .cxx_destruct]
- -[HKOrganDonationMoreAboutPrivacyViewController _updateForCurrentSizeCategory]
- -[HKOrganDonationMoreAboutPrivacyViewController doneButtonTapped:]
- -[HKOrganDonationMoreAboutPrivacyViewController setTextView:]
- -[HKOrganDonationMoreAboutPrivacyViewController textView]
- -[HKOrganDonationMoreAboutPrivacyViewController traitCollectionDidChange:]
- -[HKOrganDonationMoreAboutPrivacyViewController viewDidLoad]
- -[HKOrganDonationMoreAboutPrivacyViewController viewWillAppear:]
- -[HKOrganDonationRegisterViewController _createTableFooterView]
- -[HKOrganDonationRegisterViewController _createTableHeaderView]
- -[HKOrganDonationRegisterViewController _headerTapped:]
- -[HKOrganDonationRegisterViewController nextButton]
- -[HKOrganDonationRegisterViewController setNextButton:]
- -[HKOrganDonationRegisterViewController tableView:heightForFooterInSection:]
- -[HKOrganDonationRegisterViewController tableView:heightForHeaderInSection:]
- -[HKOrganDonationRegisterViewController tableView:viewForFooterInSection:]
- -[HKOrganDonationRegisterViewController tableView:viewForHeaderInSection:]
- -[HKOrganDonationRegisterViewController viewWillAppear:]
- -[HKOrganDonationThankYouViewController bottomAnchoredButtons]
- -[HKOrganDonationThankYouViewController buttonAtIndexTapped:]
- -[HKOrganDonationUnderageViewController bottomAnchoredButtons]
- -[HKOrganDonationUnderageViewController buttonAtIndexTapped:]
- -[HKOrganDonationUpdateSuccessViewController bottomAnchoredButtons]
- -[HKOrganDonationUpdateSuccessViewController buttonAtIndexTapped:]
- -[HKSampleTypeDateRangeController _dateRangeSampleTypesForSampleType:]
- GCC_except_table127
- GCC_except_table142
- GCC_except_table147
- GCC_except_table153
- GCC_except_table52
- GCC_except_table87
- _OBJC_CLASS_$__TtC8HealthUI32LevelDateRangeDataSourceDelegate
- _OBJC_IVAR_$_HKOrganDonationConfirmationViewController._footerView
- _OBJC_IVAR_$_HKOrganDonationConfirmationViewController._headerView
- _OBJC_IVAR_$_HKOrganDonationConfirmationViewController._loadingIndicator
- _OBJC_IVAR_$_HKOrganDonationConfirmationViewController._loadingIndicatorBarButtonItem
- _OBJC_IVAR_$_HKOrganDonationConfirmationViewController._tableView
- _OBJC_IVAR_$_HKOrganDonationMoreAboutPrivacyViewController._textView
- _OBJC_IVAR_$_HKOrganDonationRegisterViewController._footerView
- _OBJC_IVAR_$_HKOrganDonationRegisterViewController._headerView
- _OBJC_IVAR_$_HKOrganDonationRegisterViewController._nextButton
- _OBJC_METACLASS_$__TtC8HealthUI32LevelDateRangeDataSourceDelegate
- __DATA__TtC8HealthUI32LevelDateRangeDataSourceDelegate
- __INSTANCE_METHODS__TtC8HealthUI32LevelDateRangeDataSourceDelegate
- __IVARS__TtC8HealthUI32LevelDateRangeDataSourceDelegate
- __METACLASS_DATA__TtC8HealthUI32LevelDateRangeDataSourceDelegate
- __OBJC_$_INSTANCE_METHODS_UIView(HKAdditions|HKOBKAdditions)
- __OBJC_$_INSTANCE_VARIABLES_HKOrganDonationMoreAboutPrivacyViewController
- __OBJC_$_PROP_LIST_HKOrganDonationMoreAboutPrivacyViewController
- __PROTOCOLS__TtC8HealthUI32LevelDateRangeDataSourceDelegate
- ___block_descriptor_72_e8_32s40s48s56s64bs_e30_v24?0"NSNumber"8"NSError"16ls32l8s40l8s48l8s56l8s64l8
- ___swift_memcpy3_1
- ___unnamed_5
- _associated conformance 8HealthUI25AccessoryCircularTimeViewV05SwiftB00F0AA4BodyAdEP_AdE
- _associated conformance 8HealthUI29AccessoryRectangularChartViewVyxG05SwiftB00F0AA4BodyAeFP_AeF
- _associated conformance 8HealthUI29AccessoryRectangularTitleView33_31F93BFA53726DE479048DEAB4A6115ALLV05SwiftB00F0AA4BodyAeFP_AeF
- _associated conformance 8HealthUI29AccessoryRectangularTitleView33_31F93BFA53726DE479048DEAB4A6115ALLV0E6DetailV10CodingKeysOSHAASQ
- _associated conformance 8HealthUI29AccessoryRectangularTitleView33_31F93BFA53726DE479048DEAB4A6115ALLV0E6DetailV10CodingKeysOs0M3KeyAAs23CustomStringConvertible
- _associated conformance 8HealthUI29AccessoryRectangularTitleView33_31F93BFA53726DE479048DEAB4A6115ALLV0E6DetailV10CodingKeysOs0M3KeyAAs28CustomDebugStringConvertible
- _associated conformance 8HealthUI29AccessoryRectangularTitleView33_31F93BFA53726DE479048DEAB4A6115ALLV0E6DetailVSHAASQ
- _associated conformance 8HealthUI29AccessoryRectangularTitleView33_31F93BFA53726DE479048DEAB4A6115ALLV0E6DetailVs12IdentifiableAA2IDsAGP_SH
- _get_witness_table 7SwiftUI12ViewThatFitsVyAA7ForEachVySay06HealthB0025AccessoryRectangularTitleC033_31F93BFA53726DE479048DEAB4A6115ALLV0K6DetailVGAkA0C0PAAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQOyAA15ModifiedContentVyATyAA6HStackVyAA05TupleY0VyATyAA4TextVAA0U18AttachmentModifierVG_ATyATyAN9WidgetKitE16widgetAccentableyQrSbFQOyAZ_Qo_AA14_PaddingLayoutVGA0_GAA6SpacerVQPGGAA30_EnvironmentKeyWritingModifierVySiSgGGA14_ySbGG_Qo_GGAaMHPyHC
- _get_witness_table 7SwiftUI15ModifiedContentVyAA6ZStackVyAA05TupleD0Vy9WidgetKit09AccessoryG10BackgroundVSg_AA012_ConditionalD0VyAA6VStackVyAGyAA6SpacerV_ACyAA4ViewPAHE16widgetAccentableyQrSbFQOyACyACyAA5ImageVAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGAXyAA5ColorVSgGG_Qo_AA023AccessibilityAttachmentU0VGACyAA4TextVA9_GAQQPGGAOyAGyAQ_AMyAGyACyAsHEATyQrSbFQOyA12__Qo_A9_G_A13_A10_QPGAGyA10__A13_A17_QPGGAQQPGGGQPGGAA12_FrameLayoutVGAaRHPA25_AaRHPyHC_A27_AA0nU0HPyHCHC
- _get_witness_table 7SwiftUI4ViewRzlAA15ModifiedContentVyAA6VStackVyAA05TupleE0Vy06HealthB0025AccessoryRectangularTitleC033_31F93BFA53726DE479048DEAB4A6115ALLV_xAA6SpacerVQPGGAA16_FlexFrameLayoutVGAaBHPApaBHPyHC_ArA0C8ModifierHPyHCHC
- _objc_release_x10
- _symbolic SaySSG
- _symbolic SdSg
- _symbolic _____ 10Foundation6LocaleV
- _symbolic _____ 13HealthBalance26VitalsMetricClassificationO
- _symbolic _____ 8HealthUI25AccessoryCircularTimeViewV
- _symbolic _____ 8HealthUI29AccessoryRectangularChartViewV
- _symbolic _____ 8HealthUI29AccessoryRectangularTitleView33_31F93BFA53726DE479048DEAB4A6115ALLV
- _symbolic _____ 8HealthUI29AccessoryRectangularTitleView33_31F93BFA53726DE479048DEAB4A6115ALLV0E6DetailV
- _symbolic _____ 8HealthUI29AccessoryRectangularTitleView33_31F93BFA53726DE479048DEAB4A6115ALLV0E6DetailV10CodingKeysO
- _symbolic _____ 8HealthUI32LevelDateRangeDataSourceDelegateC
- _symbolic _____ 9HealthKit26HKWorkoutZoneConfigurationV6SourceO
- _symbolic _____Sg 13HealthBalance26VitalsMetricClassificationO
- _symbolic _____y_____ySay_____GAC_____y_____yAEy_____y_____yAEy__________G_AEyAEy_____yAH_Qo______GAIG_____QPGG_____ySiSgGGARySbGG_Qo_GG 7SwiftUI12ViewThatFitsV AA7ForEachV 06HealthB0025AccessoryRectangularTitleC033_31F93BFA53726DE479048DEAB4A6115ALLV0K6DetailV AA0C0PAAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQO AA15ModifiedContentV AA6HStackV AA05TupleY0V AA4TextV AA0U18AttachmentModifierV AM9WidgetKitE16widgetAccentableyQrSbFQO AA14_PaddingLayoutV AA6SpacerV AA30_EnvironmentKeyWritingModifierV
- _symbolic _____y_____y_____y_____Sg______y_____yACy______AAy_____yAAyAAy__________y_____SgGGAJy_____SgGG_Qo______GAAy_____ATGAHQPGGAGyACyAH_AFyACyAAy_____yAV_Qo_ATG_AwUQPGACyAU_AWA_QPGGAHQPGGGQPGG_____G 7SwiftUI15ModifiedContentV AA6ZStackV AA05TupleD0V 9WidgetKit09AccessoryG10BackgroundV AA012_ConditionalD0V AA6VStackV AA6SpacerV AA4ViewPAHE16widgetAccentableyQrSbFQO AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA5ColorV AA023AccessibilityAttachmentU0V AA4TextV ArHEASyQrSbFQO AA12_FrameLayoutV
- _symbolic _____y_____y_____y______x_____QPGG_____G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V 06HealthB029AccessoryRectangularTitleView33_31F93BFA53726DE479048DEAB4A6115ALLV AA6SpacerV AA16_FlexFrameLayoutV
- _type_layout_string 7SwiftUI4ViewRzl06HealthB0025AccessoryRectangularChartC0VyxG
- _type_layout_string 8HealthUI29AccessoryRectangularTitleView33_31F93BFA53726DE479048DEAB4A6115ALLV0E6DetailV
CStrings:
+ "%s %s HKDisplayTypeController unavailable — reading types will not appear"
+ "%s %s Unable to load app icons"
+ "%s %s categorized %@ under '%s'"
+ "%s %s no display category for type %@, it will not appear"
+ "%s: unable to access the header view's custom icon container view. This view is lazy loaded, so please call on viewDidLoad, and make sure you aren't setting a symbol or image on the HeaderView that will also cause it to be nil"
+ "AuthorizationSettingsSwiftUIController"
+ "AuthorizationSettingsSwiftUIController.missingType"
+ "FBSOpenApplicationService"
+ "Failed to launch \"%{public}s\": %{public}s"
+ "HKAuthorizationCategoryToggleHeaderViewIdentifier"
+ "HKAuthorizationToggleCellIdentifier"
+ "HealthUI.HKAuthorizationAppIconHeaderView"
+ "HealthUI.HKAuthorizationSettingsModernizedViewController"
+ "HealthUI.HKAuthorizationTimeBoundedViewController"
+ "HealthUI.HKSettingsAuthorizationTypeDetailViewController"
+ "HealthUI.HKSettingsAuthorizationViewController"
+ "HealthUI.UnitValueEntryCell"
+ "HealthUI/HKAuthorizationAppIconHeaderView.swift"
+ "HealthUI/HKAuthorizationCategoryToggleHeaderView.swift"
+ "HealthUI/HKAuthorizationSettingsModernizedViewController.swift"
+ "HealthUI/HKAuthorizationTimeBoundedViewController.swift"
+ "HealthUI/HKAuthorizationToggleCell.swift"
+ "HealthUI/HKSettingsAuthorizationTypeDetailViewController.swift"
+ "HealthUI/HKSettingsAuthorizationViewController.swift"
+ "HealthUI/UIView.swift"
+ "OD_DONATION_PREFERENCES_LINK"
+ "PreambleHeaderViewIdentifier"
+ "SELECT_HOW_LONG_%@_SHOULD_HAVE_ACCESS"
+ "SETTINGS_CHANGE_ACCESS"
+ "SETTINGS_CHANGE_ACCESS_DONE_BUTTON"
+ "TIME_BOUNDED_AUTH_CONTINUE"
+ "TIME_BOUNDED_AUTH_LIMITED_SUBTITLE"
+ "TIME_BOUNDED_AUTH_LIMITED_TITLE"
+ "TIME_BOUNDED_AUTH_ONGOING_SUBTITLE"
+ "TIME_BOUNDED_AUTH_ONGOING_TITLE"
+ "TIME_BOUNDED_AUTH_TOPICS_SELECTED_%ld"
+ "TIME_BOUNDED_SETTINGS_FROM_%@_%ld_DAYS"
+ "TIME_BOUNDED_SETTINGS_FULL_ACCESS"
+ "TIME_BOUNDED_SETTINGS_HEALTH_DATA_ACCESS"
+ "TIME_BOUNDED_SETTINGS_LIMITED_ACCESS"
+ "TIME_BOUNDED_SETTINGS_NONE"
+ "TIME_BOUNDED_SETTINGS_ZERO_DAYS"
+ "The user denied authorization."
+ "Unavailable enum case found."
+ "VIEW_ALL_DATA_FROM_%@"
+ "WORKOUT_CYCLING_POWER_CONFIGURATION_AUTOMATIC_FTP_NOT_AVAILABLE_FOOTER"
+ "WORKOUT_CYCLING_POWER_CONFIGURATION_AUTOMATIC_FTP_NOT_AVAILABLE_NAME"
+ "_createCheckedContinuation(_:)"
+ "arrow.left.arrow.right"
+ "bluetooth.applewatch"
+ "category types "
+ "groupTypesByCategory(_:)"
+ "groupTypesByCategory(_:authSection:)"
+ "init(style:reuseIdentifier:)"
+ "openApplication:withOptions:completion:"
+ "outlierContext"
+ "queryAllDayDates(for:since:)"
+ "queryEarliestSampleDate(for:)"
+ "serviceWithDefaultShellEndpoint"
+ "setUpHeaderView()"
+ "type != nil"
+ "v24@?0@\"HKFeatureOnboardingRecord\"8@\"NSError\"16"
+ "v32@?0@\"_HKAuthorizationModeInfo\"8@\"NSDictionary\"16^B24"
+ "viewWillAppear(_:)"
- "\r"
- ".AccessoryCircularTimeView.DesignatorText"
- ".AccessoryCircularTimeView.Symbol"
- ".AccessoryCircularTimeView.TimeText"
- ".AccessoryRectangularChartView.DetailText"
- ".AccessoryRectangularChartView.TitleText"
- "HealthUI-Localizable-Yodel"
- "HealthUI.LevelDateRangeDataSourceDelegate"
- "HealthUI/AccessoryCircularTimeView.swift"
- "HealthUI/AccessoryRectangularChartView.swift"
- "Localizable-Yodel"
```
