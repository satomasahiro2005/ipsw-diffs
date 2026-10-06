## PosterBoard

> `/System/Library/PrivateFrameworks/PosterBoard.framework/PosterBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26b120` | `0x26e8fc` | **`+0x37dc`** |
| `__TEXT.__oslogstring` | `0x1ca9a` | `0x1ceca` | **`+0x430`** |
| `__TEXT.__swift5_typeref` | `0x8676` | `0x8948` | **`+0x2d2`** |
| `__AUTH_CONST.__objc_const` | `0x3d058` | `0x3d318` | **`+0x2c0`** |
| `__TEXT.__const` | `0x71b4` | `0x73c4` | **`+0x210`** |
| `__AUTH_CONST.__cfstring` | `0xbd40` | `0xbf40` | **`+0x200`** |
| `__TEXT.__cstring` | `0x13f65` | `0x14125` | **`+0x1c0`** |
| `__AUTH.__objc_data` | `0x3b08` | `0x3cc0` | **`+0x1b8`** |
| `__TEXT.__objc_methlist` | `0xeb24` | `0xec84` | **`+0x160`** |
| `__AUTH_CONST.__const` | `0x8f68` | `0x90a8` | **`+0x140`** |
| `__DATA.__bss` | `0x2fb8` | `0x30c8` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x6a28` | `0x6b28` | **`+0x100`** |
| `__DATA.__data` | `0x61e0` | `0x62b0` | **`+0xd0`** |
| `__TEXT.__constg_swiftt` | `0x60f4` | `0x61bc` | **`+0xc8`** |
| `__DATA_CONST.__const` | `0x5170` | `0x5210` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x9a78` | `0x9ae8` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x2504` | `0x2574` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x2ff8` | `0x3054` | **`+0x5c`** |
| `__TEXT.__ustring` | `0xe` | `0x62` | **`+0x54`** |
| `__DATA_CONST.__got` | `0x1d48` | `0x1d88` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x4abe` | `0x4afe` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `0x5a0` | `0x5d8` | **`+0x38`** |
| `__AUTH.__data` | `0x1070` | `0x10a0` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x4660` | `0x463c` | **`-0x24`** |
| `__AUTH_CONST.__auth_got` | `0x2420` | `0x2438` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x728` | `0x740` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1028` | `0x103c` | **`+0x14`** |
| `__DATA_CONST.__objc_superrefs` | `0x3c8` | `0x3d8` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x23c` | `0x244` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x238` | `0x240` | **`+0x8`** |

### Other Changes

```diff

-341.0.3.0.0
+344.0.101.0.0

-  Functions: 10674
-  Symbols:   10911
-  CStrings:  3860
+  Functions: 10758
+  Symbols:   10981
+  CStrings:  3896
Symbols:
+ +[PBFPosterExtensionDataStore dataStoreUserDefaults]
+ -[PBFExtensionOffloadCoordinator .cxx_destruct]
+ -[PBFExtensionOffloadCoordinator _acquireRuntimeAssertionWithExplanation:]
+ -[PBFExtensionOffloadCoordinator _uninstallBundleIDsSerially:atIndex:succeeded:failed:completion:]
+ -[PBFExtensionOffloadCoordinator initWithAppInstaller:bundleIDsProvider:gate:]
+ -[PBFExtensionOffloadCoordinator runStartupOffloadIfNeeded]
+ -[PBFExtensionOffloadCoordinator uninstallBundleIDs:completion:]
+ -[PBFExtensionOffloadGate .cxx_destruct]
+ -[PBFExtensionOffloadGate debugDescription]
+ -[PBFExtensionOffloadGate descriptionBuilderWithMultilinePrefix:]
+ -[PBFExtensionOffloadGate descriptionWithMultilinePrefix:]
+ -[PBFExtensionOffloadGate description]
+ -[PBFExtensionOffloadGate initWithStore:]
+ -[PBFExtensionOffloadGate init]
+ -[PBFExtensionOffloadGate recordOffloadCompletedSuccessfully]
+ -[PBFExtensionOffloadGate shouldAttemptOffload]
+ -[PBFExtensionOffloadGate succinctDescriptionBuilder]
+ -[PBFExtensionOffloadGate succinctDescription]
+ -[PBFPosterExtensionDataStore enterPosterSwitcherForRole:]
+ -[PBFPosterExtensionDataStore offloadCoordinator]
+ -[PBFPosterExtensionDataStoreXPCServiceGlue server:enterPosterSwitcherForRole:]
+ GCC_except_table125
+ GCC_except_table127
+ GCC_except_table136
+ GCC_except_table147
+ GCC_except_table159
+ GCC_except_table179
+ GCC_except_table224
+ GCC_except_table252
+ GCC_except_table260
+ GCC_except_table338
+ GCC_except_table345
+ GCC_except_table347
+ GCC_except_table372
+ GCC_except_table385
+ GCC_except_table410
+ GCC_except_table426
+ GCC_except_table440
+ GCC_except_table457
+ GCC_except_table57
+ GCC_except_table66
+ GCC_except_table74
+ GCC_except_table75
+ GCC_except_table92
+ _OBJC_CLASS_$_PBFExtensionOffloadCoordinator
+ _OBJC_CLASS_$_PBFExtensionOffloadGate
+ _OBJC_IVAR_$_PBFExtensionOffloadCoordinator._appInstaller
+ _OBJC_IVAR_$_PBFExtensionOffloadCoordinator._bundleIDsProvider
+ _OBJC_IVAR_$_PBFExtensionOffloadCoordinator._gate
+ _OBJC_IVAR_$_PBFExtensionOffloadGate._store
+ _OBJC_IVAR_$_PBFPosterExtensionDataStore._offloadCoordinator
+ _OBJC_METACLASS_$_PBFExtensionOffloadCoordinator
+ _OBJC_METACLASS_$_PBFExtensionOffloadGate
+ _OBJC_METACLASS_$__TtCV11PosterBoardP33_3C38DB3534858BC29F617ECFF78E67CB23CoverAppearanceObserver22ObserverViewController
+ _PBFGalleryLayoutIsEmpty
+ _PBFGalleryLayoutTotalItemCount
+ __DATA__TtCV11PosterBoardP33_3C38DB3534858BC29F617ECFF78E67CB23CoverAppearanceObserver22ObserverViewController
+ __INSTANCE_METHODS__TtCV11PosterBoardP33_3C38DB3534858BC29F617ECFF78E67CB23CoverAppearanceObserver22ObserverViewController
+ __IVARS__TtCV11PosterBoardP33_3C38DB3534858BC29F617ECFF78E67CB23CoverAppearanceObserver22ObserverViewController
+ __METACLASS_DATA__TtCV11PosterBoardP33_3C38DB3534858BC29F617ECFF78E67CB23CoverAppearanceObserver22ObserverViewController
+ __OBJC_$_INSTANCE_METHODS_PBFExtensionOffloadCoordinator
+ __OBJC_$_INSTANCE_METHODS_PBFExtensionOffloadGate
+ __OBJC_$_INSTANCE_VARIABLES_PBFExtensionOffloadCoordinator
+ __OBJC_$_INSTANCE_VARIABLES_PBFExtensionOffloadGate
+ __OBJC_$_PROP_LIST_PBFExtensionOffloadGate
+ __OBJC_CLASS_RO_$_PBFExtensionOffloadCoordinator
+ __OBJC_CLASS_RO_$_PBFExtensionOffloadGate
+ __OBJC_METACLASS_RO_$_PBFExtensionOffloadCoordinator
+ __OBJC_METACLASS_RO_$_PBFExtensionOffloadGate
+ ___58-[PBFPosterExtensionDataStore enterPosterSwitcherForRole:]_block_invoke
+ ___59-[PBFExtensionOffloadCoordinator runStartupOffloadIfNeeded]_block_invoke
+ ___64-[PBFExtensionOffloadCoordinator uninstallBundleIDs:completion:]_block_invoke
+ ___98-[PBFExtensionOffloadCoordinator _uninstallBundleIDsSerially:atIndex:succeeded:failed:completion:]_block_invoke
+ ___block_descriptor_56_e8_32s40s48bs_e29_v24?0"NSArray"8"NSArray"16ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40bs_e32_v28?0"NSArray"8"NSArray"16B24ls40l8s32l8
+ ___block_descriptor_72_e8_32s40s48s_e32_v28?0"NSArray"8"NSArray"16B24ls32l8s40l8s48l8
+ ___block_descriptor_88_e8_32s40s48s56s64bs_e17_v16?0"NSError"8ls32l8s64l8s40l8s48l8s56l8
+ ___block_descriptor_96_e8_32s40s48s56s64bs72w_e17_v16?0"NSError"8ls32l8s40l8s48l8w72l8s64l8s56l8
+ ___swift_closure_destructor.154Tm
+ ___swift_closure_destructor.161Tm
+ ___swift_closure_destructor.26Tm
+ ___swift_closure_destructor.393Tm
+ ___swift_closure_destructor.681Tm
+ ___swift_closure_destructor.91Tm
+ ___swift_closure_destructor.94Tm
+ _associated conformance 11PosterBoard23CoverAppearanceObserver33_3C38DB3534858BC29F617ECFF78E67CBLLV7SwiftUI29UIViewControllerRepresentableAaE4View
+ _associated conformance 11PosterBoard23CoverAppearanceObserver33_3C38DB3534858BC29F617ECFF78E67CBLLV7SwiftUI4ViewAA4BodyAeFP_AeF
+ _get_witness_table 11PosterBoard0A15GalleryModelingRzAA0aC14AssetProvidingR_AA0aC19InstallCoordinatingR0_AA0C14ViewSpecifyingR1_r2_l7SwiftUI15ModifiedContentVyAHyAHyAHyAF0I0PAFE15fullScreenCover4item15drawsBackground7contentQrAF7BindingVyqd__SgG_Sbqd_0_qd__cts12IdentifiableRd__AfIRd_0_r0_lFQOyAjFE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQOyAHyAF6ZStackVyAF05TupleN0VyAF012_ConditionalN0VyAHyAHyAHyAHyAHyAF08ProgressI0VyAF05EmptyI0VA7_GAF30_EnvironmentKeyWritingModifierVyAF11ControlSizeOGGA10_yAF5ColorVSgGGAF16_FlexFrameLayoutVGAF21_TraitWritingModifierVyAF18TransitionTraitKeyVGGAF31AccessibilityAttachmentModifierVGAHyAHyAjFE19onScrollPhaseChangeyQryAF11ScrollPhaseO_A34_tcFQOyAjFE22onScrollGeometryChange3for2of6actionQrqd__m_qd__AF14ScrollGeometryVcyqd___qd__tctSQRd__lFQOyAHyAjFE14scrollPosition2id6anchorQrAR_AF9UnitPointVSgtSHRd__lFQOyAHyAF06ScrollI0VyAF10LazyVStackVyAF7ForEachVySaySi6offset_AA0aC7SectionV7elementtGSSA1_yAHyAHyAHyAF7DividerVAF30_SafeAreaRegionsIgnoringLayoutVGAF14_PaddingLayoutVGA64_GSg_AHyAHyA3_yA3_yA3_yAA0aC16SectionContainerVyq1_AHyAF6VStackVyAjFE14scrollDisabledyQrSbFQOyA48_yAHyAF10LazyHStackVyA52_ySayAA0aC4ItemVGSSAA0aC4CellVyxq_q1_GGGA64_GG_Qo_GA64_GGAA0aC21ScrollableTallSectionVyxq_q1_GGA3_yA3_yAA0aC17ExpandableSectionVyxq0_q_q1_GA69_yq1_A71_yA1_yAA0aC13SectionHeaderVyq1_G_AjFE20scrollTargetBehavioryQrqd__AF20ScrollTargetBehaviorRd__lFQOyA48_yAHyAjFE18scrollTargetLayout9isEnabledQrSb_tFQOyA82__Qo_A64_GG_AF0I27AlignedScrollTargetBehaviorVQo_QPGGGGA111_GGA3_yA71_yA1_yA98__AHyA71_yA52_yA77_SSAHyAF6HStackVyA1_yAHyA80_AF12_FrameLayoutVG_AHyAHyAjFE15dynamicTypeSizeyQrqd__SXRd__AF15DynamicTypeSizeO5BoundRtd__lFQOyAF4TextV_s19PartialRangeThroughVyA122_GQo_A10_ySiSgGGA21_GSgQPGGA118_GGGA64_GQPGGA111_GGA64_GA64_GQPGGGGAF18_AnimationModifierVySayA55_GGG_SSQo_AF25_AllowsHitTestingModifierVG_12CoreGraphics7CGFloatVQo__Qo_A27_GA30_GG_A1_yAA21FadingGradientOverlay33_3C38DB3534858BC29F617ECFF78E67CBLLV_AHyAHyAHyAA012CancelButtonI0A170_LLVA64_GA64_GA61_GQPGSgQPGGAF25_AppearanceActionModifierVG_Qo__AA0aC13EditorContextVAHyA3_yAjFE20navigationTransitionyQrqd__AF20NavigationTransitionRd__lFQOyAjFE26interactiveDismissDisabledyQrSbFQOyAHyA_yA1_yAHyAF14GeometryReaderVyAHyAHyAHyAHyAA06PortalI0VA118_GAF12_ScaleEffectVGA21_GA61_GGA61_GSg_AHyAHyAA0ac6EditorI0VA153_ySbGGA61_GSgQPGGA61_G_Qo__AF24ZoomNavigationTransitionVQo_A212_GAF01_T8ModifierVyAHyAHyAA0Q18AppearanceObserverA170_LLVA118_GA30_GGGQo_AF23_GeometryActionModifierVySo6CGSizeVA229_SQA161_yHCg_GGA10_yA229_GGA10_yAF11ColorSchemeOGGAF01_T13StyleModifierVyA16_GGAfIHPA237_AfIHPA233_AfIHPA231_AfIHPqd0__AfIHD4_A225_HO_A230_AF0I8ModifierHPyHCHC_A232_AFA242_HPyHCHC_A236_AFA242_HPyHCHC_A240_AFA242_HPyHCHC
+ _swift_retain_x9
+ _symbolic _____ 11PosterBoard23CoverAppearanceObserver33_3C38DB3534858BC29F617ECFF78E67CBLLV
+ _symbolic _____ 11PosterBoard23CoverAppearanceObserver33_3C38DB3534858BC29F617ECFF78E67CBLLV0E14ViewControllerC
+ _symbolic _____ 7SwiftUI11ControlSizeO
+ _symbolic _____yAAyAAyAAyAAy_____y_____ACG_____y_____GGAEy_____SgGG_____G_____y_____GG_____G 7SwiftUI15ModifiedContentV AA12ProgressViewV AA05EmptyF0V AA30_EnvironmentKeyWritingModifierV AA11ControlSizeO AA5ColorV AA16_FlexFrameLayoutV AA06_TraitjK0V AA010TransitionrI0V AA023AccessibilityAttachmentK0V
+ _symbolic _____yAAyAAyAAy_____y_____ACG_____y_____GGAEy_____SgGG_____G_____y_____GG 7SwiftUI15ModifiedContentV AA12ProgressViewV AA05EmptyF0V AA30_EnvironmentKeyWritingModifierV AA11ControlSizeO AA5ColorV AA16_FlexFrameLayoutV AA06_TraitjK0V AA010TransitionrI0V
+ _symbolic _____yAAyAAyAAy_____y_____yAAy_____y_____y_____yAAyAAyAAyAAyAAy_____y_____AFG_____y_____GGAHy_____SgGG_____G_____y_____GG_____GAAyAAy_____y_____yAAy_____yAAy_____y_____y_____ySaySi6offset______7elementtGSSACyAAyAAyAAy__________G_____GA6_GSg_AAyAAyADyADyADy_____yq1_AAy_____y_____yAXyAAy_____yAZySay_____GSS_____yxq_q1_GGGA6_GG_Qo_GA6_GG_____yxq_q1_GGADyADy_____yxq0_q_q1_GA10_yq1_A11_yACy_____yq1_G______yAXyAAy_____yA18__Qo_A6_GG______Qo_QPGGGGA39_GGADyA11_yACyA31__AAyA11_yAZyA14_SSAAy_____yACyAAyA16______G_AAyAAy_____y___________y_____GQo_AHySiSgGGAPGSgQPGGA44_GGGA6_GQPGGA39_GGA6_GA6_GQPGGGG_____ySayA0_GGG_SSQo______G______Qo__Qo_ATGAVGG_ACy______AAyAAyAAy_____A6_GA6_GA4_GQPGSgQPGG_____G_Qo_______AAyADy_____y_____yAAyAByACyAAy_____yAAyAAyAAyAAy_____A44_G_____GAPGA4_GGA4_GSg_AAyAAy_____A72_ySbGGA4_GSgQPGGA4_G_Qo_______Qo_A116_G_____yAAyAAy_____A44_GAVGGGQo______y_____A128_SQ12CoreGraphicsyHCg_GGAHyA128_GGAHy_____GG_____yALGG 7SwiftUI15ModifiedContentV AA4ViewPAAE15fullScreenCover4item15drawsBackground7contentQrAA7BindingVyqd__SgG_Sbqd_0_qd__cts12IdentifiableRd__AaDRd_0_r0_lFQO AeAE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQO AA6ZStackV AA05TupleD0V AA012_ConditionalD0V AA08ProgressE0V AA05EmptyE0V AA30_EnvironmentKeyWritingModifierV AA11ControlSizeO AA5ColorV AA16_FlexFrameLayoutV AA21_TraitWritingModifierV AA015TransitionTraitZ0V AA31AccessibilityAttachmentModifierV AeAE19onScrollPhaseChangeyQryAA11ScrollPhaseO_A19_tcFQO AeAE22onScrollGeometryChange3for2of6actionQrqd__m_qd__AA14ScrollGeometryVcyqd___qd__tctSQRd__lFQO AeAE14scrollPosition2id6anchorQrAM_AA9UnitPointVSgtSHRd__lFQO AA06ScrollE0V AA10LazyVStackV AA7ForEachV 11PosterBoard20PosterGallerySectionV AA7DividerV AA30_SafeAreaRegionsIgnoringLayoutV AA14_PaddingLayoutV A38_29PosterGallerySectionContainerV AA6VStackV AeAE14scrollDisabledyQrSbFQO AA10LazyHStackV A38_17PosterGalleryItemV A38_17PosterGalleryCellV A38_34PosterGalleryScrollableTallSectionV A38_30PosterGalleryExpandableSectionV A38_26PosterGallerySectionHeaderV AeAE20scrollTargetBehavioryQrqd__AA20ScrollTargetBehaviorRd__lFQO AeAE18scrollTargetLayout9isEnabledQrSb_tFQO AA0E27AlignedScrollTargetBehaviorV AA6HStackV AA12_FrameLayoutV AeAE15dynamicTypeSizeyQrqd__SXRd__AA15DynamicTypeSizeO5BoundRtd__lFQO AA4TextV s19PartialRangeThroughV A76_ AA18_AnimationModifierV AA25_AllowsHitTestingModifierV 12CoreGraphics7CGFloatV A38_21FadingGradientOverlay33_3C38DB3534858BC29F617ECFF78E67CBLLV A38_012CancelButtonE0A91_LLV AA25_AppearanceActionModifierV A38_26PosterGalleryEditorContextV AeAE20navigationTransitionyQrqd__AA20NavigationTransitionRd__lFQO AeAE26interactiveDismissDisabledyQrSbFQO AA14GeometryReaderV A38_06PortalE0V AA12_ScaleEffectV A38_019PosterGalleryEditorE0V AA24ZoomNavigationTransitionV AA01_K8ModifierV A38_0H18AppearanceObserverA91_LLV AA23_GeometryActionModifierV So6CGSizeV AA11ColorSchemeO AA01_K13StyleModifierV
+ _symbolic _____yAAyAAy_____y_____ACG_____y_____GGAEy_____SgGG_____G 7SwiftUI15ModifiedContentV AA12ProgressViewV AA05EmptyF0V AA30_EnvironmentKeyWritingModifierV AA11ControlSizeO AA5ColorV AA16_FlexFrameLayoutV
+ _symbolic _____yAAy_____y_____ACG_____y_____GGAEy_____SgGG 7SwiftUI15ModifiedContentV AA12ProgressViewV AA05EmptyF0V AA30_EnvironmentKeyWritingModifierV AA11ControlSizeO AA5ColorV
+ _symbolic _____ySay_____GG s23_ContiguousArrayStorageC 11PosterBoard0D11GalleryItemV
+ _symbolic _____y_____G 7SwiftUI30_EnvironmentKeyWritingModifierV AA11ControlSizeO
+ _symbolic _____y__________G 7SwiftUI15ModifiedContentV 11PosterBoard23CoverAppearanceObserver33_3C38DB3534858BC29F617ECFF78E67CBLLV AA12_FrameLayoutV
+ _symbolic _____y_____yABy__________G_____GG 7SwiftUI19_BackgroundModifierV AA15ModifiedContentV 11PosterBoard23CoverAppearanceObserver33_3C38DB3534858BC29F617ECFF78E67CBLLV AA12_FrameLayoutV AA023AccessibilityAttachmentD0V
+ _symbolic _____y_____y_____ACG_____y_____GG 7SwiftUI15ModifiedContentV AA12ProgressViewV AA05EmptyF0V AA30_EnvironmentKeyWritingModifierV AA11ControlSizeO
+ _symbolic _____y_____y_____y_____yAAy_____y_____yAAy_____yAAyAAyAAyAAy__________G_____G_____G_____GGAMGSg_AAyAAy__________ySbGGAMGSgQPGGAMG_Qo_______Qo_A_G_____yAAyAAy_____AGG_____GGG 7SwiftUI15ModifiedContentV AA012_ConditionalD0V AA4ViewPAAE20navigationTransitionyQrqd__AA010NavigationH0Rd__lFQO AgAE26interactiveDismissDisabledyQrSbFQO AA6ZStackV AA05TupleD0V AA14GeometryReaderV 11PosterBoard06PortalF0V AA12_FrameLayoutV AA12_ScaleEffectV AA05_FlextU0V AA024_SafeAreaRegionsIgnoringU0V AQ0q13GalleryEditorF0V AA18_AnimationModifierV AA04ZoomiH0V AA19_BackgroundModifierV AQ23CoverAppearanceObserver33_3C38DB3534858BC29F617ECFF78E67CBLLV AA31AccessibilityAttachmentModifierV
+ _type_layout_string 11PosterBoard23CoverAppearanceObserver33_3C38DB3534858BC29F617ECFF78E67CBLLV
- GCC_except_table122
- GCC_except_table128
- GCC_except_table133
- GCC_except_table141
- GCC_except_table156
- GCC_except_table173
- GCC_except_table221
- GCC_except_table249
- GCC_except_table25
- GCC_except_table257
- GCC_except_table335
- GCC_except_table342
- GCC_except_table344
- GCC_except_table369
- GCC_except_table382
- GCC_except_table407
- GCC_except_table424
- GCC_except_table438
- GCC_except_table455
- GCC_except_table72
- GCC_except_table89
- _OUTLINED_FUNCTION_47
- _OUTLINED_FUNCTION_48
- ___55-[PBFPosterExtensionDataStore _offloadUnusedExtensions]_block_invoke
- ___block_descriptor_80_e8_32s40s48s56bs_e17_v16?0"NSError"8ls32l8s56l8s40l8s48l8
- ___swift_closure_destructor.148Tm
- ___swift_closure_destructor.155Tm
- ___swift_closure_destructor.25Tm
- ___swift_closure_destructor.387Tm
- ___swift_closure_destructor.675Tm
- ___swift_closure_destructor.70Tm
- ___swift_closure_destructor.73Tm
- _get_witness_table 11PosterBoard0A15GalleryModelingRzAA0aC14AssetProvidingR_AA0aC19InstallCoordinatingR0_AA0C14ViewSpecifyingR1_r2_l7SwiftUI15ModifiedContentVyAHyAHyAHyAF0I0PAFE15fullScreenCover4item15drawsBackground7contentQrAF7BindingVyqd__SgG_Sbqd_0_qd__cts12IdentifiableRd__AfIRd_0_r0_lFQOyAjFE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQOyAHyAF6ZStackVyAF05TupleN0VyAHyAjFE19onScrollPhaseChangeyQryAF11ScrollPhaseO_A4_tcFQOyAjFE22onScrollGeometryChange3for2of6actionQrqd__m_qd__AF14ScrollGeometryVcyqd___qd__tctSQRd__lFQOyAHyAjFE14scrollPosition2id6anchorQrAR_AF9UnitPointVSgtSHRd__lFQOyAHyAF06ScrollI0VyAF10LazyVStackVyAF7ForEachVySaySi6offset_AA0aC7SectionV7elementtGSSA1_yAHyAHyAHyAF7DividerVAF30_SafeAreaRegionsIgnoringLayoutVGAF14_PaddingLayoutVGA34_GSg_AHyAHyAF012_ConditionalN0VyA39_yA39_yAA0aC16SectionContainerVyq1_AHyAF6VStackVyAjFE14scrollDisabledyQrSbFQOyA18_yAHyAF10LazyHStackVyA22_ySayAA0aC4ItemVGSSAA0aC4CellVyxq_q1_GGGA34_GG_Qo_GA34_GGAA0aC21ScrollableTallSectionVyxq_q1_GGA39_yA39_yAA0aC17ExpandableSectionVyxq0_q_q1_GA41_yq1_A43_yA1_yAA0aC13SectionHeaderVyq1_G_AjFE20scrollTargetBehavioryQrqd__AF20ScrollTargetBehaviorRd__lFQOyA18_yAHyAjFE18scrollTargetLayout9isEnabledQrSb_tFQOyA54__Qo_A34_GG_AF0I27AlignedScrollTargetBehaviorVQo_QPGGGGA83_GGA39_yA43_yA1_yA70__AHyA43_yA22_yA49_SSAHyAF6HStackVyA1_yAHyA52_AF12_FrameLayoutVG_AHyAHyAjFE15dynamicTypeSizeyQrqd__SXRd__AF15DynamicTypeSizeO5BoundRtd__lFQOyAF4TextV_s19PartialRangeThroughVyA94_GQo_AF30_EnvironmentKeyWritingModifierVySiSgGGAF16_FlexFrameLayoutVGSgQPGGA90_GGGA34_GQPGGA83_GGA34_GA34_GQPGGGGAF18_AnimationModifierVySayA25_GGG_SSQo_AF25_AllowsHitTestingModifierVG_12CoreGraphics7CGFloatVQo__Qo_AF31AccessibilityAttachmentModifierVG_A1_yAA21FadingGradientOverlay33_3C38DB3534858BC29F617ECFF78E67CBLLV_AHyAHyAHyAA012CancelButtonI0A146_LLVA34_GA34_GA31_GQPGSgQPGGAF25_AppearanceActionModifierVG_Qo__AA0aC13EditorContextVA39_yAjFE20navigationTransitionyQrqd__AF20NavigationTransitionRd__lFQOyAjFE26interactiveDismissDisabledyQrSbFQOyAHyA_yA1_yAHyAF14GeometryReaderVyAHyAHyAHyAHyAA06PortalI0VA90_GAF12_ScaleEffectVGA109_GA31_GGA31_GSg_AHyAHyAA0ac6EditorI0VA129_ySbGGA31_GSgQPGGA31_G_Qo__AF24ZoomNavigationTransitionVQo_A188_GQo_AF23_GeometryActionModifierVySo6CGSizeVA197_SQA137_yHCg_GGA104_yA197_GGA104_yAF11ColorSchemeOGGAF01_T13StyleModifierVyAF5ColorVGGAfIHPA205_AfIHPA201_AfIHPA199_AfIHPqd0__AfIHD4_A193_HO_A198_AF0I8ModifierHPyHCHC_A200_AFA212_HPyHCHC_A204_AFA212_HPyHCHC_A210_AFA212_HPyHCHC
- _symbolic _____yAAyAAyAAy_____y_____yAAy_____y_____yAAy_____y_____yAAy_____yAAy_____y_____y_____ySaySi6offset______7elementtGSSACyAAyAAyAAy__________G_____GANGSg_AAyAAy_____yARyARy_____yq1_AAy_____y_____yADyAAy_____yAFySay_____GSS_____yxq_q1_GGGANGG_Qo_GANGG_____yxq_q1_GGARyARy_____yxq0_q_q1_GASyq1_ATyACy_____yq1_G______yADyAAy_____yA__Qo_ANGG______Qo_QPGGGGA20_GGARyATyACyA12__AAyATyAFyAWSSAAy_____yACyAAyAY_____G_AAyAAy_____y___________y_____GQo______ySiSgGG_____GSgQPGGA25_GGGANGQPGGA20_GGANGANGQPGGGG_____ySayAHGGG_SSQo______G______Qo__Qo______G_ACy______AAyAAyAAy_____ANGANGALGQPGSgQPGG_____G_Qo_______ARy_____y_____yAAyAByACyAAy_____yAAyAAyAAyAAy_____A25_G_____GA36_GALGGALGSg_AAyAAy_____A55_ySbGGALGSgQPGGALG_Qo_______Qo_A98_GQo______y_____A104_SQ12CoreGraphicsyHCg_GGA32_yA104_GGA32_y_____GG_____y_____GG 7SwiftUI15ModifiedContentV AA4ViewPAAE15fullScreenCover4item15drawsBackground7contentQrAA7BindingVyqd__SgG_Sbqd_0_qd__cts12IdentifiableRd__AaDRd_0_r0_lFQO AeAE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQO AA6ZStackV AA05TupleD0V AeAE19onScrollPhaseChangeyQryAA0wX0O_A_tcFQO AeAE0vw8GeometryY03for2of6actionQrqd__m_qd__AA0wZ0Vcyqd___qd__tctSQRd__lFQO AeAE14scrollPosition2id6anchorQrAM_AA9UnitPointVSgtSHRd__lFQO AA0wE0V AA10LazyVStackV AA7ForEachV 11PosterBoard20PosterGallerySectionV AA7DividerV AA30_SafeAreaRegionsIgnoringLayoutV AA14_PaddingLayoutV AA012_ConditionalD0V A18_29PosterGallerySectionContainerV AA6VStackV AeAE14scrollDisabledyQrSbFQO AA10LazyHStackV A18_17PosterGalleryItemV A18_17PosterGalleryCellV A18_34PosterGalleryScrollableTallSectionV A18_30PosterGalleryExpandableSectionV A18_26PosterGallerySectionHeaderV AeAE20scrollTargetBehavioryQrqd__AA0W14TargetBehaviorRd__lFQO AeAE18scrollTargetLayout9isEnabledQrSb_tFQO AA0e7AlignedW14TargetBehaviorV AA6HStackV AA12_FrameLayoutV AeAE15dynamicTypeSizeyQrqd__SXRd__AA15DynamicTypeSizeO5BoundRtd__lFQO AA4TextV s19PartialRangeThroughV A58_ AA30_EnvironmentKeyWritingModifierV AA16_FlexFrameLayoutV AA18_AnimationModifierV AA25_AllowsHitTestingModifierV 12CoreGraphics7CGFloatV AA31AccessibilityAttachmentModifierV A18_21FadingGradientOverlay33_3C38DB3534858BC29F617ECFF78E67CBLLV A18_012CancelButtonE0A79_LLV AA25_AppearanceActionModifierV A18_26PosterGalleryEditorContextV AeAE20navigationTransitionyQrqd__AA20NavigationTransitionRd__lFQO AeAE26interactiveDismissDisabledyQrSbFQO AA0Z6ReaderV A18_06PortalE0V AA12_ScaleEffectV A18_019PosterGalleryEditorE0V AA24ZoomNavigationTransitionV AA01_Z14ActionModifierV So6CGSizeV AA11ColorSchemeO AA01_K13StyleModifierV AA5ColorV
CStrings:
+ "%@|%@"
+ "-init: unavailable"
+ "EMPTY → kicking prewarm"
+ "Extensions to persist for role %{public}@ (count=%lu): %{public}@"
+ "Not stamping offload gate — %lu auto-removable apps still present after chain"
+ "Offload runtime assertion could not be acquired: %{public}@"
+ "Offload succeeded for %{public}@"
+ "Offloading container app with bundleIdentifier: %{public}@"
+ "Offloading failed for %{public}@ | %{public}@"
+ "PBF poster-app uninstall (XPC)"
+ "PBF unused-extension offload (startup)"
+ "PBFExtensionOffloadCoordinator.m"
+ "PBFExtensionOffloadGate.m"
+ "PBFExtensionOffloadLastSuccessfulBuildVersion"
+ "PBFOffloadBundle"
+ "PBFOffloadChain"
+ "PosterBoard.ObserverViewController"
+ "Skipping unused-extension offload — already succeeded against the current OS build version"
+ "Startup offload finished in %.3fs — %lu succeeded, %lu failed (ranToCompletion=%d)"
+ "XPC offload finished in %.3fs — %lu succeeded, %lu failed (ranToCompletion=%d)"
+ "[%@]-[%@]-[%@]"
+ "[%{public}@] _stateLock_loadPersistedGalleryConfigurationWithLastUpdateDate discarding empty persisted gallery (%lu sections, 0 items) from %{public}@"
+ "[%{public}@][%{public}@] _pushFaceGalleryConfigurationUpdate: dropping empty gallery (%lu sections, 0 items); keeping previous useful gallery"
+ "appInstaller"
+ "bundleID=%{public}@"
+ "bundleID=%{public}@ outcome=%{public}s"
+ "bundleIDsProvider"
+ "currentBuildVersion"
+ "enterPosterSwitcherForRole:'%{public}@' — gallery has %lu items across %lu sections; %{public}@"
+ "enterPosterSwitcherForRole:'%{public}@' — prewarm finished with error: %{public}@"
+ "gate"
+ "kickoff: Provider %{public}@ at capacity (%lu active, cap %lu, visible=%d) — skipping %{public}@"
+ "kind=startup count=%lu"
+ "kind=xpc count=%lu"
+ "populated → no-op"
+ "posterboard-gallery-loading"
+ "server:enterPosterSwitcherForRole: failed to acquire data store: %{public}@"
+ "stashedBuildVersion"
+ "store"
+ "succeeded"
+ "succeeded=%lu failed=%lu ranToCompletion=%d"
+ "v24@?0@\"NSArray\"8@\"NSArray\"16"
+ "v28@?0@\"NSArray\"8@\"NSArray\"16B24"
+ "wouldAttemptOffload"
- "Checking for extensions to persist for role %@"
- "Failed to uninstall %{public}@: %{public}@"
- "Offload succeeded for %@"
- "Offloading container app with bundleIdentifier: %@"
- "Offloading failed for %@ | %@"
- "[%@]-[%@]-[%@]-[%@].png"
- "kickoff: Provider %{public}@ at capacity (%lu active), skipping non-visible poster"
- "kickoff: Visible poster %{public}@ bypassing per-provider capacity limit"
```
