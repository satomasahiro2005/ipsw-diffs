## SearchUI

> `/System/Library/PrivateFrameworks/SearchUI.framework/SearchUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf3c28` | `0xf58a0` | **`+0x1c78`** |
| `__DATA_DIRTY.__objc_data` | `0x1c40` | `0x3258` | **`+0x1618`** |
| `__AUTH.__objc_data` | `0x5ca8` | `0x4750` | **`-0x1558`** |
| `__DATA_DIRTY.__bss` | `0xc0` | `0xce8` | **`+0xc28`** |
| `__DATA.__bss` | `0x27e0` | `0x1c60` | **`-0xb80`** |
| `__TEXT.__swift5_typeref` | `0x3378` | `0x3992` | **`+0x61a`** |
| `__DATA_DIRTY.__data` | `0x180` | `0x4b0` | **`+0x330`** |
| `__AUTH_CONST.__objc_const` | `0x1dd98` | `0x1e028` | **`+0x290`** |
| `__TEXT.__const` | `0x38a4` | `0x3a74` | **`+0x1d0`** |
| `__TEXT.__objc_methlist` | `0x12258` | `0x123d8` | **`+0x180`** |
| `__AUTH.__data` | `0x908` | `0x7c8` | **`-0x140`** |
| `__TEXT.__cstring` | `0x3998` | `0x3aa9` | **`+0x111`** |
| `__DATA.__data` | `0x3440` | `0x3384` | **`-0xbc`** |
| `__AUTH_CONST.__auth_got` | `0x1878` | `0x1900` | **`+0x88`** |
| `__AUTH_CONST.__const` | `0x2a28` | `0x2ab0` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0xa1f0` | `0xa268` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x4800` | `0x4870` | **`+0x70`** |
| `__TEXT.__lazy_helpers` | `—` | `0x54` | **`+0x54`** |
| `__TEXT.__oslogstring` | `0x28c5` | `0x2915` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x1418` | `0x145c` | **`+0x44`** |
| `__DATA_CONST.__got` | `0x2538` | `0x2578` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x8c0` | `0x8f4` | **`+0x34`** |
| `__DATA_CONST.__const` | `0x2878` | `0x28a0` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x230c` | `0x2334` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x6d5` | `0x6fa` | **`+0x25`** |
| `__AUTH_CONST.__cfstring` | `0x33a0` | `0x33c0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0xcdc` | `0xcf4` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x9e8` | `0xa00` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x2f8` | `0x310` | **`+0x18`** |
| `__DATA.__common` | `0xd8` | `0xe8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xad0` | `0xae0` | **`+0x10`** |
| `__AUTH_CONST.__lazy_load_got` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x358` | `0x360` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x6f0` | `0x6f8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x130` | `0x138` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x114` | `0x11c` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x148` | `0x14c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0xdc` | `0xe0` | **`+0x4`** |

### Other Changes

```diff

-673.0.1.0.0
+673.0.6.0.0

-  - /System/Library/PrivateFrameworks/PhotosUIPrivate.framework/PhotosUIPrivate

+  - /System/Library/PrivateFrameworks/SpringBoardUIServices.framework/SpringBoardUIServices

-  Functions: 6943
-  Symbols:   11415
-  CStrings:  819
+  Functions: 6996
+  Symbols:   11493
+  CStrings:  826
Symbols:
+ +[SearchUICardViewController _loadAndEnrichCardSectionsFromCard:cardLoader:withCompletionHandler:]
+ +[SearchUIUtilities appClipIdentifierFromBundleIdentifier:]
+ -[SearchFTEView .cxx_destruct]
+ -[SearchFTEView continueButtonPressed]
+ -[SearchFTEView continueButtonTitle]
+ -[SearchFTEView delegate]
+ -[SearchFTEView explanationText]
+ -[SearchFTEView initWithDomains:explanationText:learnMoreText:continueButtonTitle:]
+ -[SearchFTEView learnMoreText]
+ -[SearchFTEView makeViews]
+ -[SearchFTEView setContinueButtonTitle:]
+ -[SearchFTEView setDelegate:]
+ -[SearchFTEView setExplanationText:]
+ -[SearchFTEView setLearnMoreText:]
+ -[SearchFTEView setSupportedDomains:]
+ -[SearchFTEView supportedDomains]
+ -[SearchFTEView textView:shouldInteractWithURL:inRange:interaction:]
+ -[SearchUIAppIconImage useDarkStyleForTraitCollection:]
+ -[SearchUIButtonBackgroundView setUsesThinMaterialBackground:]
+ -[SearchUIButtonBackgroundView usesThinMaterialBackground]
+ -[SearchUIFirstTimeExperienceViewController fteContinueButtonPressed]
+ -[SearchUIFirstTimeExperienceViewController fteLearnMoreTapped]
+ -[SearchUIFirstTimeExperienceViewController initWithDomains:explanationText:learnMoreText:continueButtonTitle:useSiriFTE:]
+ -[SearchUIFirstTimeExperienceViewController setUseSiriFTE:]
+ -[SearchUIFirstTimeExperienceViewController useSiriFTE]
+ -[SearchUIImage useDarkStyleForTraitCollection:]
+ -[SearchUITLKImage useDarkStyleForTraitCollection:]
+ GCC_except_table32
+ _OBJC_CLASS_$_SBSUITraitHomeScreenIconStyle
+ _OBJC_CLASS_$_SearchFTEView
+ _OBJC_CLASS_$_SiriFTEHostingView
+ _OBJC_IVAR_$_SearchFTEView._continueButtonTitle
+ _OBJC_IVAR_$_SearchFTEView._delegate
+ _OBJC_IVAR_$_SearchFTEView._explanationText
+ _OBJC_IVAR_$_SearchFTEView._learnMoreText
+ _OBJC_IVAR_$_SearchFTEView._supportedDomains
+ _OBJC_IVAR_$_SearchUIButtonBackgroundView._usesThinMaterialBackground
+ _OBJC_IVAR_$_SearchUIFirstTimeExperienceViewController._useSiriFTE
+ _OBJC_METACLASS_$_SearchFTEView
+ _OBJC_METACLASS_$_SiriFTEHostingView
+ _PUItemProviderForAsset$lazyAuthGOT_IA_ad_0
+ _PUItemProviderForAsset$lazyLoadStub
+ _SearchUIResultPlatterMaxCornerRadius
+ __CLASS_METHODS_SiriFTEHostingView
+ __DATA_SiriFTEHostingView
+ __INSTANCE_METHODS_SiriFTEHostingView
+ __METACLASS_DATA_SiriFTEHostingView
+ __OBJC_$_INSTANCE_METHODS_SearchFTEView
+ __OBJC_$_INSTANCE_VARIABLES_SearchFTEView
+ __OBJC_$_PROP_LIST_SearchFTEView
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SearchFTEViewDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SearchFTEViewDelegate
+ __OBJC_$_PROTOCOL_REFS_SearchFTEViewDelegate
+ __OBJC_CLASS_PROTOCOLS_$_SearchFTEView
+ __OBJC_CLASS_RO_$_SearchFTEView
+ __OBJC_LABEL_PROTOCOL_$_SearchFTEViewDelegate
+ __OBJC_METACLASS_RO_$_SearchFTEView
+ __OBJC_PROTOCOL_$_SearchFTEViewDelegate
+ ___98+[SearchUICardViewController _loadAndEnrichCardSectionsFromCard:cardLoader:withCompletionHandler:]_block_invoke
+ ___98+[SearchUICardViewController _loadAndEnrichCardSectionsFromCard:cardLoader:withCompletionHandler:]_block_invoke_2
+ ___98+[SearchUICardViewController _loadAndEnrichCardSectionsFromCard:cardLoader:withCompletionHandler:]_block_invoke_3
+ ___98+[SearchUICardViewController _loadAndEnrichCardSectionsFromCard:cardLoader:withCompletionHandler:]_block_invoke_4
+ ___block_descriptor_48_e8_32s40bs_e28_v24?0"SFCard"8"NSError"16ls40l8s32l8
+ __dyld_lazy_load
+ _associated conformance 8SearchUI11SiriFTEViewV05SwiftB04ViewAA4BodyAdEP_AdE
+ _get_witness_table 7SwiftUI6HStackVyAA12TupleContentVyAA6SpacerV_AA08ModifiedE0VyAIyAIyAIyAIyAA6VStackVyAEyAIyAIyAIyAIyAA5ImageVAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGAA12_FrameLayoutVGAOyAM5ScaleOGGAA016_ForegroundStyleM0VyAA017HierarchicalShapeS0VGG_AIyAIyAA4TextVAA08_PaddingP0VGA9_GA7_QPGGA9_GA9_GAA05_FlexoP0VGAOyAA0V9AlignmentOGGAA010_FixedSizeP0VGAGQPGGAA4ViewHPyHC
+ _lazyLoadFlag$PhotosUIPrivate
+ _symbolic _____ 7SwiftUI13TextAlignmentO
+ _symbolic _____ 8SearchUI11SiriFTEViewV
+ _symbolic _____Sg 7SwiftUI4FontV6DesignO
+ _symbolic ___________yAByAByAByABy_____y_____yAByAByAByABy__________y_____SgGG_____GAFy_____GG_____y_____GG_AByABy__________GAUGATQPGGAUGAUG_____GAFy_____GG_____GAAt 7SwiftUI6SpacerV AA15ModifiedContentV AA6VStackV AA05TupleE0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA12_FrameLayoutV AK5ScaleO AA016_ForegroundStyleL0V AA017HierarchicalShapeR0V AA4TextV AA08_PaddingO0V AA05_FlexnO0V AA0U9AlignmentO AA010_FixedSizeO0V
+ _symbolic _____yAAyAAyAAyAAy_____y_____yAAyAAyAAyAAy__________y_____SgGG_____GAEy_____GG_____y_____GG_AAyAAy__________GATGASQPGGATGATG_____GAEy_____GG_____G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA12_FrameLayoutV AI5ScaleO AA016_ForegroundStyleK0V AA017HierarchicalShapeQ0V AA4TextV AA08_PaddingN0V AA05_FlexmN0V AA0T9AlignmentO AA010_FixedSizeN0V
+ _symbolic _____yAAyAAyAAy__________y_____SgGG_____GACy_____GG_____y_____GG 7SwiftUI15ModifiedContentV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA12_FrameLayoutV AE5ScaleO AA016_ForegroundStyleI0V AA017HierarchicalShapeO0V
+ _symbolic _____yAAyAAyAAy__________y_____SgGG_____GACy_____GG_____y_____GG_AAyAAy__________GARGAQt 7SwiftUI15ModifiedContentV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA12_FrameLayoutV AE5ScaleO AA016_ForegroundStyleI0V AA017HierarchicalShapeO0V AA4TextV AA08_PaddingL0V
+ _symbolic _____yAAyAAyAAy_____y_____yAAyAAyAAyAAy__________y_____SgGG_____GAEy_____GG_____y_____GG_AAyAAy__________GATGASQPGGATGATG_____GAEy_____GG 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA12_FrameLayoutV AI5ScaleO AA016_ForegroundStyleK0V AA017HierarchicalShapeQ0V AA4TextV AA08_PaddingN0V AA05_FlexmN0V AA0T9AlignmentO
+ _symbolic _____yAAyAAy__________y_____SgGG_____GACy_____GG 7SwiftUI15ModifiedContentV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA12_FrameLayoutV AE5ScaleO
+ _symbolic _____yAAyAAy_____y_____yAAyAAyAAyAAy__________y_____SgGG_____GAEy_____GG_____y_____GG_AAyAAy__________GATGASQPGGATGATG_____G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA12_FrameLayoutV AI5ScaleO AA016_ForegroundStyleK0V AA017HierarchicalShapeQ0V AA4TextV AA08_PaddingN0V AA05_FlexmN0V
+ _symbolic _____yAAy__________GACG 7SwiftUI15ModifiedContentV AA4TextV AA14_PaddingLayoutV
+ _symbolic _____yAAy__________y_____SgGG_____G 7SwiftUI15ModifiedContentV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA12_FrameLayoutV
+ _symbolic _____yAAy_____y_____yAAyAAyAAyAAy__________y_____SgGG_____GAEy_____GG_____y_____GG_AAyAAy__________GATGASQPGGATGATG 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA12_FrameLayoutV AI5ScaleO AA016_ForegroundStyleK0V AA017HierarchicalShapeQ0V AA4TextV AA08_PaddingN0V
+ _symbolic _____y_____G 7SwiftUI14_UIHostingViewC 06SearchB011SiriFTEViewV
+ _symbolic _____y___________y___________yAEyAEyAEyAEy_____yACyAEyAEyAEyAEy__________y_____SgGG_____GAHy_____GG_____y_____GG_AEyAEy__________GAWGAVQPGGAWGAWG_____GAHy_____GG_____GADQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA6SpacerV AA08ModifiedI0V AA6VStackV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA06_FrameG0V AQ5ScaleO AA016_ForegroundStyleQ0V AA017HierarchicalShapeV0V AA4TextV AA08_PaddingG0V AA05_FlexsG0V AA0Y9AlignmentO AA010_FixedSizeG0V
+ _symbolic _____y___________y_____yADyADyADy__________y_____SgGG_____GAFy_____GG_____y_____GG_ADyADy__________GAUGATQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA08ModifiedI0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA06_FrameG0V AM5ScaleO AA016_ForegroundStyleO0V AA017HierarchicalShapeT0V AA4TextV AA08_PaddingG0V
+ _symbolic _____y_____y___________yADyADyADyADy_____yAByADyADyADyADy__________y_____SgGG_____GAGy_____GG_____y_____GG_ADyADy__________GAVGAUQPGGAVGAVG_____GAGy_____GG_____GACQPGG 7SwiftUI6HStackV AA12TupleContentV AA6SpacerV AA08ModifiedE0V AA6VStackV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA12_FrameLayoutV AM5ScaleO AA016_ForegroundStyleM0V AA017HierarchicalShapeS0V AA4TextV AA08_PaddingP0V AA05_FlexoP0V AA0V9AlignmentO AA010_FixedSizeP0V
+ _symbolic _____y_____y_____yAAyAAyAAyAAy__________y_____SgGG_____GAEy_____GG_____y_____GG_AAyAAy__________GATGASQPGGATG 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA12_FrameLayoutV AI5ScaleO AA016_ForegroundStyleK0V AA017HierarchicalShapeQ0V AA4TextV AA08_PaddingN0V
+ _type_layout_string 8SearchUI11SiriFTEViewV
- -[SearchUIButtonItemView shouldAvoidBackgroundView]
- -[SearchUIFirstTimeExperienceViewController continueButtonPressed]
- -[SearchUIFirstTimeExperienceViewController textView:shouldInteractWithURL:inRange:interaction:]
- GCC_except_table17
- GCC_except_table30
- _OBJC_IVAR_$_SearchUIButtonItemView._shouldAvoidBackgroundView
- ___87+[SearchUICardViewController _loadAndEnrichCardSectionsFromCard:withCompletionHandler:]_block_invoke
- ___87+[SearchUICardViewController _loadAndEnrichCardSectionsFromCard:withCompletionHandler:]_block_invoke_2
CStrings:
+ "+[SearchUIUtilities openURL:withCompletion:] called with nil URL; ignoring"
+ "Contradictory frame constraints specified."
+ "Description for first time experience shown to users about Siri AI."
+ "Search for anything or start a conversation with Siri."
+ "SettingToggleSwitch"
+ "Title for Siri AI FTE."
+ "v24@?0@\"SFCard\"8@\"NSError\"16"
```
