## TextInputUI

> `/System/Library/PrivateFrameworks/TextInputUI.framework/TextInputUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x135a98` | `0x1400fc` | **`+0xa664`** |
| `__AUTH_CONST.__objc_const` | `0x197f0` | `0x1a1c0` | **`+0x9d0`** |
| `__TEXT.__objc_methlist` | `0xfeac` | `0x10604` | **`+0x758`** |
| `__TEXT.__const` | `0x368e` | `0x3c7e` | **`+0x5f0`** |
| `__DATA.__bss` | `0x2e18` | `0x33b8` | **`+0x5a0`** |
| `__DATA_CONST.__objc_selrefs` | `0xa358` | `0xa830` | **`+0x4d8`** |
| `__TEXT.__swift5_typeref` | `0x198c` | `0x1dee` | **`+0x462`** |
| `__AUTH_CONST.__const` | `0x2c30` | `0x2fe8` | **`+0x3b8`** |
| `__DATA.__data` | `0x28f8` | `0x2ca8` | **`+0x3b0`** |
| `__TEXT.__oslogstring` | `0x618c` | `0x6533` | **`+0x3a7`** |
| `__TEXT.__eh_frame` | `0x1884` | `0x1c14` | **`+0x390`** |
| `__AUTH.__objc_data` | `0x39d0` | `0x3c38` | **`+0x268`** |
| `__TEXT.__unwind_info` | `0x4230` | `0x4480` | **`+0x250`** |
| `__TEXT.__constg_swiftt` | `0x17c8` | `0x19c0` | **`+0x1f8`** |
| `__AUTH.__data` | `0x990` | `0xb80` | **`+0x1f0`** |
| `__AUTH_CONST.__auth_got` | `0x1bd0` | `0x1da8` | **`+0x1d8`** |
| `__TEXT.__swift5_fieldmd` | `0xcd4` | `0xe38` | **`+0x164`** |
| `__TEXT.__swift5_capture` | `0x4f8` | `0x624` | **`+0x12c`** |
| `__DATA_CONST.__got` | `0x14d0` | `0x15e8` | **`+0x118`** |
| `__TEXT.__cstring` | `0xd835` | `0xd935` | **`+0x100`** |
| `__TEXT.__swift5_reflstr` | `0xca5` | `0xd95` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0xeb00` | `0xebe0` | **`+0xe0`** |
| `__TEXT.__swift5_assocty` | `0x2f0` | `0x370` | **`+0x80`** |
| `__DATA_CONST.__objc_protolist` | `0x278` | `0x2b8` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0x150` | `0x17c` | **`+0x2c`** |
| `__DATA_CONST.__objc_protorefs` | `0x80` | `0xa8` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x7a98` | `0x7ab8` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x134` | `0x154` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x128` | `0x144` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0x708` | `0x720` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x154` | `0x168` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x60` | `0x74` | **`+0x14`** |
| `__DATA_DIRTY.__data` | `0x2d8` | `0x2e8` | **`+0x10`** |
| `__DATA.__common` | `0x280` | `0x288` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1218` | `0x1220` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `0x50` | `0x58` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x470` | `0x468` | **`-0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x20c8` | `0x20d0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x70` | `0x78` | **`+0x8`** |

### Other Changes

```diff

-9127.0.84.1.113
+9127.1.6.0.0

+  - /System/Library/Frameworks/ImagePlayground.framework/ImagePlayground

+  - /usr/lib/swift/libswiftGLKit.dylib

+  - /usr/lib/swift/libswiftMetalKit.dylib
+  - /usr/lib/swift/libswiftModelIO.dylib

+  - /usr/lib/swift/libswiftSceneKit.dylib

-  Functions: 6872
-  Symbols:   10793
-  CStrings:  2732
+  Functions: 7070
+  Symbols:   10927
+  CStrings:  2750
Symbols:
+ +[TUICandidateGrid isFullWidthSuggestionCandidate:]
+ -[TUICandidateGrid resetContentOffsetIfContentFits]
+ -[TUICandidateGrid showSiriButtonOnLeft]
+ -[TUICandidateGrid showsFullWidthSuggestionCandidate]
+ -[TUICandidateView candidateGroupArrayByRepositioningCompositionCandidates:]
+ -[TUICandidateView candidatesByRepositioningFirstCompositionCandidate:]
+ -[TUIKeyPopupView isNarrowLayout]
+ -[TUIKeyPopupView setIsNarrowLayout:]
+ -[TUIKeyplaneView setSizeClassTraitChangeRegistration:]
+ -[TUIKeyplaneView sizeClassTraitChangeRegistration]
+ -[_TUIKeyboardCandidateContainer _arrayCountOrNilDebugDescription:]
+ _CATransform3DMakeScale
+ _OBJC_CLASS_$_CAAnimation
+ _OBJC_CLASS_$_CAPackage
+ _OBJC_CLASS_$_TUIImagePlaygroundPresenter
+ _OBJC_CLASS_$_UIScene
+ _OBJC_CLASS_$_UITraitHorizontalSizeClass
+ _OBJC_CLASS_$_UITraitVerticalSizeClass
+ _OBJC_CLASS_$_UIWindowScene
+ _OBJC_IVAR_$_TUIKeyPopupView._isNarrowLayout
+ _OBJC_IVAR_$_TUIKeyplaneView._sizeClassTraitChangeRegistration
+ _OBJC_METACLASS_$_TUIImagePlaygroundPresenter
+ _OBJC_METACLASS_$__TtC11TextInputUIP33_4E3CCC217D4507E7AD2D9EBD007764CA19GenmojiMicaHostView
+ _OBJC_METACLASS_$__TtC11TextInputUIP33_63F729F5376141D9E861BEE38CFE809112_Coordinator
+ _UIAccessibilityIsReduceMotionEnabled
+ __CATEGORY_INSTANCE_METHODS_UIResponder_$_TextInputUI
+ __CATEGORY_UIResponder_$_TextInputUI
+ __CLASS_METHODS_TUIImagePlaygroundPresenter
+ __CLASS_PROPERTIES_TUIImagePlaygroundPresenter
+ __DATA_TUIImagePlaygroundPresenter
+ __DATA__TtC11TextInputUIP33_4E3CCC217D4507E7AD2D9EBD007764CA19GenmojiMicaHostView
+ __DATA__TtC11TextInputUIP33_63F729F5376141D9E861BEE38CFE809112_Coordinator
+ __INSTANCE_METHODS_TUIImagePlaygroundPresenter
+ __INSTANCE_METHODS__TtC11TextInputUIP33_4E3CCC217D4507E7AD2D9EBD007764CA19GenmojiMicaHostView
+ __INSTANCE_METHODS__TtC11TextInputUIP33_63F729F5376141D9E861BEE38CFE809112_Coordinator
+ __IVARS_TUIImagePlaygroundPresenter
+ __IVARS__TtC11TextInputUIP33_4E3CCC217D4507E7AD2D9EBD007764CA19GenmojiMicaHostView
+ __IVARS__TtC11TextInputUIP33_63F729F5376141D9E861BEE38CFE809112_Coordinator
+ __METACLASS_DATA_TUIImagePlaygroundPresenter
+ __METACLASS_DATA__TtC11TextInputUIP33_4E3CCC217D4507E7AD2D9EBD007764CA19GenmojiMicaHostView
+ __METACLASS_DATA__TtC11TextInputUIP33_63F729F5376141D9E861BEE38CFE809112_Coordinator
+ __OBJC_$_PROP_LIST_UIKeyInput
+ __OBJC_$_PROP_LIST_UITextInput
+ __OBJC_$_PROP_LIST_UITextInputTraits
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UITextInput
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UITextInputTraits
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_UIKeyInput
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_UITextInput
+ __OBJC_$_PROTOCOL_METHOD_TYPES_UIKeyInput
+ __OBJC_$_PROTOCOL_METHOD_TYPES_UITextInput
+ __OBJC_$_PROTOCOL_METHOD_TYPES_UITextInputTraits
+ __OBJC_$_PROTOCOL_REFS_UIKeyInput
+ __OBJC_$_PROTOCOL_REFS_UITextInput
+ __OBJC_$_PROTOCOL_REFS_UITextInputTraits
+ __OBJC_LABEL_PROTOCOL_$_UIKeyInput
+ __OBJC_LABEL_PROTOCOL_$_UITextInput
+ __OBJC_LABEL_PROTOCOL_$_UITextInputTraits
+ __OBJC_PROTOCOL_$_UIKeyInput
+ __OBJC_PROTOCOL_$_UITextInput
+ __OBJC_PROTOCOL_$_UITextInputTraits
+ __PROTOCOLS__TtC11TextInputUIP33_63F729F5376141D9E861BEE38CFE809112_Coordinator
+ __PROTOCOL_INSTANCE_METHODS_ImageGenerationViewControllerDelegate
+ __PROTOCOL_INSTANCE_METHODS_OPT_ImageGenerationViewControllerDelegate
+ __PROTOCOL_INSTANCE_METHODS__TtP11TextInputUIP33_63F729F5376141D9E861BEE38CFE809118_UIKeyboardImplSPI_
+ __PROTOCOL_ImageGenerationViewControllerDelegate
+ __PROTOCOL_METHOD_TYPES_ImageGenerationViewControllerDelegate
+ __PROTOCOL_METHOD_TYPES__TtP11TextInputUIP33_63F729F5376141D9E861BEE38CFE809118_UIKeyboardImplSPI_
+ __PROTOCOL_PROTOCOLS_ImageGenerationViewControllerDelegate
+ __PROTOCOL_PROTOCOLS__TtP11TextInputUIP33_63F729F5376141D9E861BEE38CFE809118_UIKeyboardImplSPI_
+ __PROTOCOL__TtP11TextInputUIP33_63F729F5376141D9E861BEE38CFE809118_UIKeyboardImplSPI_
+ ___45-[TUIKeyplaneView createContentViewsIfNeeded]_block_invoke_2
+ ___swift_closure_destructor.14Tm
+ __swift_FORCE_LOAD_$_swiftGLKit
+ __swift_FORCE_LOAD_$_swiftGLKit_$_TextInputUI
+ __swift_FORCE_LOAD_$_swiftMetalKit
+ __swift_FORCE_LOAD_$_swiftMetalKit_$_TextInputUI
+ __swift_FORCE_LOAD_$_swiftModelIO
+ __swift_FORCE_LOAD_$_swiftModelIO_$_TextInputUI
+ __swift_FORCE_LOAD_$_swiftSceneKit
+ __swift_FORCE_LOAD_$_swiftSceneKit_$_TextInputUI
+ _associated conformance 11TextInputUI20GenmojiAnimatedGlyph33_4E3CCC217D4507E7AD2D9EBD007764CALLV05SwiftC04ViewAA4BodyAeFP_AeF
+ _associated conformance 11TextInputUI22GenmojiButtonAnimationOSHAASQ
+ _associated conformance 11TextInputUI26GenmojiButtonAnimationViewV05SwiftC00G0AA4BodyAdEP_AdE
+ _associated conformance 11TextInputUI26GenmojiButtonAnimationViewV05SwiftC019UIViewRepresentableAaD0G0
+ _associated conformance So21NSAttributedStringKeyaSHSCSQ
+ _associated conformance So21NSAttributedStringKeyas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So21NSAttributedStringKeyas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _get_witness_table 7SwiftUI15ModifiedContentVyACyAA4ViewPAAE10fontWeightyQrAA4FontV0G0VSgFQOyAA5ImageV_Qo_AA14_OpacityEffectVGAA16_OverlayModifierVyACy09TextInputB0022GenmojiButtonAnimationE0VAA023AccessibilityAttachmentM0VGGGAaDHPAqaDHPqd__AaDHD2_ANHO_ApA0eM0HPyHCHC_AzAA0_HPyHCHC
+ _get_witness_table 7SwiftUI15ModifiedContentVyACyACyAA6HStackVyAA05TupleD0VyAA012_ConditionalD0VyACyAA6IDViewVy09TextInputB020GenmojiAnimatedGlyph33_4E3CCC217D4507E7AD2D9EBD007764CALLVSiGAA13_OffsetEffectVGACyAA4ViewPAAE10fontWeightyQrAA4FontV0Z0VSgFQOyAA5ImageV_Qo_ARGG_AuAEAVyQrA_FQOyACyAA0I0VAA30_EnvironmentKeyWritingModifierVySiSgGG_Qo_SgQPGGAA14_PaddingLayoutVGA17_GA8_yAA15DynamicTypeSizeOGGAaTHPA19_AaTHPA18_AaTHPA15_AaTHPyHC_A17_AA0X8ModifierHPyHCHC_A17_AAA24_HPyHCHC_A22_AAA24_HPyHCHC
+ _kCAPackageTypeCAMLBundle
+ _swift_dynamicCastObjCProtocolConditional
+ _swift_stdlib_random
+ _symbolic $s11TextInputUI18_UIKeyboardImplSPI33_63F729F5376141D9E861BEE38CFE8091LLP
+ _symbolic $s7SwiftUI19UIViewRepresentableP
+ _symbolic Sdz_Xx
+ _symbolic So10_UIStickerC
+ _symbolic So11UIResponderC
+ _symbolic So11UIResponderCSg
+ _symbolic So11UIResponderCSgXw
+ _symbolic So20NSAdaptiveImageGlyphC
+ _symbolic So7CALayerCSg
+ _symbolic So7UIImageCSg
+ _symbolic _____ 11TextInputUI12_Coordinator33_63F729F5376141D9E861BEE38CFE8091LLC
+ _symbolic _____ 11TextInputUI19GenmojiMicaHostView33_4E3CCC217D4507E7AD2D9EBD007764CALLC
+ _symbolic _____ 11TextInputUI20GenmojiAnimatedGlyph33_4E3CCC217D4507E7AD2D9EBD007764CALLV
+ _symbolic _____ 11TextInputUI22GenmojiButtonAnimationO
+ _symbolic _____ 11TextInputUI26GenmojiButtonAnimationViewV
+ _symbolic _____ 11TextInputUI27TUIImagePlaygroundPresenterC
+ _symbolic _____ 7SwiftUI11ColorSchemeO
+ _symbolic _____ So21NSAttributedStringKeya
+ _symbolic _____11colorScheme_Sb4boldt 7SwiftUI11ColorSchemeO
+ _symbolic _____11colorScheme_Sb4boldtSg 7SwiftUI11ColorSchemeO
+ _symbolic _____Sg 10Foundation3URLV
+ _symbolic _____Sg 11TextInputUI22GenmojiButtonAnimationO
+ _symbolic _____Sg 14SuggestedImage7UseCaseO
+ _symbolic _____Sg 7SwiftUI11ColorSchemeO
+ _symbolic _____Sg 7SwiftUI16LegibilityWeightO
+ _symbolic _____Sg_ABt 7SwiftUI11ColorSchemeO
+ _symbolic _____Sg_ABt 7SwiftUI16LegibilityWeightO
+ _symbolic _____XMT 11TextInputUI19GenmojiMicaHostView33_4E3CCC217D4507E7AD2D9EBD007764CALLC
+ _symbolic _____XMT 11TextInputUI27TUIImagePlaygroundPresenterC
+ _symbolic _____yAAyAAy_____y_____y_____yAAy_____y_____SiG_____GAAy_____y______Qo_AHGG______yAAy__________ySiSgGG_Qo_SgQPGG_____GAWGAOy_____GG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA012_ConditionalD0V AA6IDViewV 09TextInputB020GenmojiAnimatedGlyph33_4E3CCC217D4507E7AD2D9EBD007764CALLV AA13_OffsetEffectV AA4ViewPAAE10fontWeightyQrAA4FontV0Z0VSgFQO AA5ImageV AsAEATyQrAYFQO AA0I0V AA30_EnvironmentKeyWritingModifierV AA14_PaddingLayoutV AA15DynamicTypeSizeO
+ _symbolic _____yAAy_____y______Qo______G_____yAAy__________GGG 7SwiftUI15ModifiedContentV AA4ViewPAAE10fontWeightyQrAA4FontV0G0VSgFQO AA5ImageV AA14_OpacityEffectV AA16_OverlayModifierV 09TextInputB0022GenmojiButtonAnimationE0V AA023AccessibilityAttachmentM0V
+ _symbolic _____yAAy_____y_____y_____yAAy_____y_____SiG_____GAAy_____y______Qo_AHGG______yAAy__________ySiSgGG_Qo_SgQPGG_____GAWG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA012_ConditionalD0V AA6IDViewV 09TextInputB020GenmojiAnimatedGlyph33_4E3CCC217D4507E7AD2D9EBD007764CALLV AA13_OffsetEffectV AA4ViewPAAE10fontWeightyQrAA4FontV0Z0VSgFQO AA5ImageV AsAEATyQrAYFQO AA0I0V AA30_EnvironmentKeyWritingModifierV AA14_PaddingLayoutV
+ _symbolic _____ySbG 7SwiftUI7BindingV
+ _symbolic _____ySbG 7SwiftUI9LazyStateV
+ _symbolic _____y_____G 7SwiftUI11EnvironmentV AA11ColorSchemeO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 15ImagePlayground0dE5StyleV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 15ImagePlayground0dE7ConceptV
+ _symbolic _____y_____SgG 7SwiftUI11EnvironmentV AA16LegibilityWeightO
+ _symbolic _____y_____Sg_G 7SwiftUI11EnvironmentV7ContentO AA16LegibilityWeightO
+ _symbolic _____y_____SiG 7SwiftUI6IDViewV 09TextInputB020GenmojiAnimatedGlyph33_4E3CCC217D4507E7AD2D9EBD007764CALLV
+ _symbolic _____y______G 7SwiftUI11EnvironmentV7ContentO AA11ColorSchemeO
+ _symbolic _____y___________y_____y_____y_____y_____SiG_____GAEy_____y______Qo_AIGG______yAEy__________ySiSgGG_Qo_SgQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA012_ConditionalI0V AA08ModifiedI0V AA6IDViewV 09TextInputB020GenmojiAnimatedGlyph33_4E3CCC217D4507E7AD2D9EBD007764CALLV AA13_OffsetEffectV AA0D0PAAE10fontWeightyQrAA4FontV6WeightVSgFQO AA5ImageV AwAEAXyQrA1_FQO AA0M0V AA30_EnvironmentKeyWritingModifierV
+ _symbolic _____y_____y_____SiG_____G 7SwiftUI15ModifiedContentV AA6IDViewV 09TextInputB020GenmojiAnimatedGlyph33_4E3CCC217D4507E7AD2D9EBD007764CALLV AA13_OffsetEffectV
+ _symbolic _____y_____y______Qo______G 7SwiftUI15ModifiedContentV AA4ViewPAAE10fontWeightyQrAA4FontV0G0VSgFQO AA5ImageV AA13_OffsetEffectV
+ _symbolic _____y_____y______Qo______G 7SwiftUI15ModifiedContentV AA4ViewPAAE10fontWeightyQrAA4FontV0G0VSgFQO AA5ImageV AA14_OpacityEffectV
+ _symbolic _____y_____y__________GG 7SwiftUI16_OverlayModifierV AA15ModifiedContentV 09TextInputB026GenmojiButtonAnimationViewV AA023AccessibilityAttachmentD0V
+ _symbolic _____y_____y_____y_____SiG_____GABy_____y______Qo_AFGG 7SwiftUI19_ConditionalContentV AA08ModifiedD0V AA6IDViewV 09TextInputB020GenmojiAnimatedGlyph33_4E3CCC217D4507E7AD2D9EBD007764CALLV AA13_OffsetEffectV AA4ViewPAAE10fontWeightyQrAA4FontV0X0VSgFQO AA5ImageV
+ _symbolic _____y_____y_____y_____SiG_____GABy_____y______Qo_AFGG______yABy__________ySiSgGG_Qo_Sgt 7SwiftUI19_ConditionalContentV AA08ModifiedD0V AA6IDViewV 09TextInputB020GenmojiAnimatedGlyph33_4E3CCC217D4507E7AD2D9EBD007764CALLV AA13_OffsetEffectV AA4ViewPAAE10fontWeightyQrAA4FontV0X0VSgFQO AA5ImageV AoAEAPyQrAUFQO AA0G0V AA30_EnvironmentKeyWritingModifierV
+ _symbolic _____y_____y_____y_____SiG_____GABy_____y______Qo_AFG_G 7SwiftUI19_ConditionalContentV7StorageO AA08ModifiedD0V AA6IDViewV 09TextInputB020GenmojiAnimatedGlyph33_4E3CCC217D4507E7AD2D9EBD007764CALLV AA13_OffsetEffectV AA4ViewPAAE10fontWeightyQrAA4FontV0Y0VSgFQO AA5ImageV
+ _symbolic _____y_____y_____y_____yAAy_____y_____SiG_____GAAy_____y______Qo_AHGG______yAAy__________ySiSgGG_Qo_SgQPGG_____G 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA012_ConditionalD0V AA6IDViewV 09TextInputB020GenmojiAnimatedGlyph33_4E3CCC217D4507E7AD2D9EBD007764CALLV AA13_OffsetEffectV AA4ViewPAAE10fontWeightyQrAA4FontV0Z0VSgFQO AA5ImageV AsAEATyQrAYFQO AA0I0V AA30_EnvironmentKeyWritingModifierV AA14_PaddingLayoutV
+ _symbolic _____y_____y_____y_____y_____y_____SiG_____GADy_____y______Qo_AHGG______yADy__________ySiSgGG_Qo_SgQPGG 7SwiftUI6HStackV AA12TupleContentV AA012_ConditionalE0V AA08ModifiedE0V AA6IDViewV 09TextInputB020GenmojiAnimatedGlyph33_4E3CCC217D4507E7AD2D9EBD007764CALLV AA13_OffsetEffectV AA4ViewPAAE10fontWeightyQrAA4FontV0Z0VSgFQO AA5ImageV AsAEATyQrAYFQO AA0I0V AA30_EnvironmentKeyWritingModifierV
+ _type_layout_string So6CGSizeV
- -[TUIFlickVariantCell defaultFontSize]
- -[TUIFlickVariantCell initWithFrame:string:annotation:traits:]
- _get_witness_table 7SwiftUI15ModifiedContentVyACyACyAA6HStackVyAA05TupleD0VyACyAA5ImageVAA13_OffsetEffectVG_AA4ViewPAAE10fontWeightyQrAA4FontV0L0VSgFQOyACyAA4TextVAA30_EnvironmentKeyWritingModifierVySiSgGG_Qo_SgQPGGAA14_PaddingLayoutVGA5_GAXyAA15DynamicTypeSizeOGGAaMHPA7_AaMHPA6_AaMHPA3_AaMHPyHC_A5_AA0jR0HPyHCHC_A5_AAA12_HPyHCHC_A10_AAA12_HPyHCHC
- _symbolic _____yAAyAAy_____y_____yAAy__________G______yAAy__________ySiSgGG_Qo_SgQPGG_____GAPGAHy_____GG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA13_OffsetEffectV AA4ViewPAAE10fontWeightyQrAA4FontV0L0VSgFQO AA4TextV AA30_EnvironmentKeyWritingModifierV AA14_PaddingLayoutV AA15DynamicTypeSizeO
- _symbolic _____yAAy_____y_____yAAy__________G______yAAy__________ySiSgGG_Qo_SgQPGG_____GAPG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA13_OffsetEffectV AA4ViewPAAE10fontWeightyQrAA4FontV0L0VSgFQO AA4TextV AA30_EnvironmentKeyWritingModifierV AA14_PaddingLayoutV
- _symbolic _____y__________G______yAAy__________ySiSgGG_Qo_Sgt 7SwiftUI15ModifiedContentV AA5ImageV AA13_OffsetEffectV AA4ViewPAAE10fontWeightyQrAA4FontV0J0VSgFQO AA4TextV AA30_EnvironmentKeyWritingModifierV
- _symbolic _____y___________y_____y__________G______yADy__________ySiSgGG_Qo_SgQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA08ModifiedI0V AA5ImageV AA13_OffsetEffectV AA0D0PAAE10fontWeightyQrAA4FontV0O0VSgFQO AA4TextV AA30_EnvironmentKeyWritingModifierV
- _symbolic _____y_____y_____yAAy__________G______yAAy__________ySiSgGG_Qo_SgQPGG_____G 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA13_OffsetEffectV AA4ViewPAAE10fontWeightyQrAA4FontV0L0VSgFQO AA4TextV AA30_EnvironmentKeyWritingModifierV AA14_PaddingLayoutV
- _symbolic _____y_____y_____y__________G______yACy__________ySiSgGG_Qo_SgQPGG 7SwiftUI6HStackV AA12TupleContentV AA08ModifiedE0V AA5ImageV AA13_OffsetEffectV AA4ViewPAAE10fontWeightyQrAA4FontV0L0VSgFQO AA4TextV AA30_EnvironmentKeyWritingModifierV
- _type_layout_string So7CGPointV
CStrings:
+ "%@ {autocorrectionList: %@}"
+ "%@ {candidate resultset: %@}"
+ "%@, predictions: %@, emojis: %@, containsProactiveTriggers: %s, containsAutofillCandidates: %s"
+ "%tu"
+ "(nil)"
+ "Allowing smart reply generation without network access for on-device Mail replies"
+ "ImagePlaygroundAdoption"
+ "KBD returned nil autocorrectionList for request token: %@"
+ "KBD returned nil candidate result set for request token: %@"
+ "Optional<LegibilityWeight>"
+ "Remix tapped but _pregeneratedStickerWrapper is nil — the sticker did not survive decoding into this process"
+ "[FedStats] Resolved staged use case '%{public}s'"
+ "[FedStats] Staged use case '%{public}s' is absent from SuggestedImage on this build; falling back to commonPhrases, which imageplaygroundd rejects. Cases offered: %{public}s"
+ "_present: topmostAppViewController() returned nil — cannot present"
+ "autocorrection: %tu, alternate correction: %tu"
+ "candidates: %@, hasOnlyProactiveCandidates: %s"
+ "could not load %{public}s.ca"
+ "didCreate: no viable insertion path for %s"
+ "didCreateSticker: failed to convert to _UISticker"
+ "present(forInput:sourceImage:) called with a nil image — falling back to the create flow. The pregenerated sticker did not survive to this process."
- "canInsertGenmoji"
- "supportsGenmojiCreation"
```
