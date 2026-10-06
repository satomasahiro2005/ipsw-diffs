## TextInputUI

> `/System/Library/PrivateFrameworks/TextInputUI.framework/TextInputUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x126838` | `0x12a35c` | **`+0x3b24`** |
| `__AUTH_CONST.__objc_const` | `0x18750` | `0x189b8` | **`+0x268`** |
| `__AUTH_CONST.__cfstring` | `0xe2e0` | `0xe4a0` | **`+0x1c0`** |
| `__TEXT.__swift5_typeref` | `0x1ae2` | `0x1964` | **`-0x17e`** |
| `__TEXT.__objc_methlist` | `0xf414` | `0xf574` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x5702` | `0x585b` | **`+0x159`** |
| `__TEXT.__cstring` | `0xd77e` | `0xd8c3` | **`+0x145`** |
| `__DATA_CONST.__objc_selrefs` | `0x9be0` | `0x9d08` | **`+0x128`** |
| `__DATA.__bss` | `0x2e40` | `0x2d40` | **`-0x100`** |
| `__AUTH_CONST.__const` | `0x29d0` | `0x2ac8` | **`+0xf8`** |
| `__AUTH.__objc_data` | `0x3830` | `0x3880` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x3fc0` | `0x4008` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x4b4` | `0x4f8` | **`+0x44`** |
| `__TEXT.__const` | `0x3640` | `0x3600` | **`-0x40`** |
| `__TEXT.__swift5_fieldmd` | `0xca0` | `0xcd4` | **`+0x34`** |
| `__DATA_CONST.__got` | `0x1450` | `0x1480` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x1130` | `0x1158` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x7778` | `0x77a0` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1b78` | `0x1b98` | **`+0x20`** |
| `__DATA.__data` | `0x27c8` | `0x27e8` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x990` | `0x9b0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xc85` | `0xca5` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x308` | `0x2f0` | **`-0x18`** |
| `__TEXT.__constg_swiftt` | `0x17a4` | `0x17b8` | **`+0x14`** |
| `__TEXT.__swift5_builtin` | `0x140` | `0x154` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x6d0` | `0x6d8` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x187c` | `0x1884` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x158` | `0x150` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x124` | `0x128` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x130` | `0x134` | **`+0x4`** |
| `__DATA.__common` | `0x280` | `0x281` | **`+0x1`** |

### Other Changes

```diff

-9127.0.66.1.102
+9127.0.71.1.101

-  - /System/Library/PrivateFrameworks/CollectionsInternal.framework/CollectionsInternal

-  Functions: 6598
-  Symbols:   10354
-  CStrings:  2628
+  Functions: 6630
+  Symbols:   10412
+  CStrings:  2647
Symbols:
+ +[TUIPredictionViewCell defaultTextMarginWithImage]
+ +[TUIRecentPasteCandidate contentIdentifierForPasteboard:]
+ -[TUIInputSession notifyCandidateAccepted:]
+ -[TUIInputSession setSharedKeyboardContext:]
+ -[TUIInputSession sharedKeyboardContext]
+ -[TUIInputSessionManager _propagateSharedKeyboardContext]
+ -[TUIInputSessionManager notifyCandidateAccepted:forHostAuditToken:]
+ -[TUIInputSessionManager setSharedKeyboardContext:]
+ -[TUIInputSessionManager sharedKeyboardContext]
+ -[TUIKBKeyView isDuplicatedSplitKey]
+ -[TUIKey isDuplicatedSplitKey]
+ -[TUIKey isSplitDuplicate]
+ -[TUIKey setIsDuplicatedSplitKey:]
+ -[TUIKeyplane keyplaneHasCustomSplitLayout]
+ -[TUIKeyplane(TransitionSupport) customSplitKeyplaneTreeForLayoutName:screenTraits:]
+ -[TUIKeyplaneRow extraSplitKeys]
+ -[TUIKeyplaneRow setExtraSplitKeys:]
+ -[TUIPredictionView applyDefaultAssistantStyle]
+ -[TUIRecentPasteCandidate contentIdentifier]
+ -[TUIRecentPasteCellContentView _captionBaselineDistance]
+ -[TUIRecentPasteCellContentView _contentSizeCategoryDidChange]
+ -[TUIRecentPasteCellContentView _refreshLabelFonts]
+ -[TUIRecentPasteCellContentView _shadowOpacityForCurrentTraits]
+ -[TUIRecentPasteCellContentView _userInterfaceStyleDidChange]
+ -[TUIRecentPasteGenerator pasteboardContentAlreadyInsertedForContext:]
+ -[TUISharedKeyboardContext copyWithZone:]
+ -[TUISharedKeyboardContext description]
+ -[TUISharedKeyboardContext lastInsertedPasteContentIdentifier]
+ -[TUISharedKeyboardContext setLastInsertedPasteContentIdentifier:]
+ -[_TUIKeyboardCandidateGenerationContext setSharedKeyboardContext:]
+ -[_TUIKeyboardCandidateGenerationContext sharedKeyboardContext]
+ _CFStringGetLength
+ _CFStringTokenizerAdvanceToNextToken
+ _CFStringTokenizerCreate
+ _CFStringTokenizerGetCurrentTokenRange
+ _OBJC_CLASS_$_TUISharedKeyboardContext
+ _OBJC_CLASS_$_UITraitPreferredContentSizeCategory
+ _OBJC_IVAR_$_TUIInputSession._sharedKeyboardContext
+ _OBJC_IVAR_$_TUIInputSessionManager._sharedKeyboardContext
+ _OBJC_IVAR_$_TUIKey._isDuplicatedSplitKey
+ _OBJC_IVAR_$_TUIKeyplaneRow._extraSplitKeys
+ _OBJC_IVAR_$_TUIRecentPasteCandidate._contentIdentifier
+ _OBJC_IVAR_$_TUIRecentPasteCellContentView._captionBaselineConstraint
+ _OBJC_IVAR_$_TUIRecentPasteCellContentView._contentWrapper
+ _OBJC_IVAR_$_TUIRecentPasteCellContentView._imageContainer
+ _OBJC_IVAR_$_TUIRecentPasteCellContentView._labelGroup
+ _OBJC_IVAR_$_TUISharedKeyboardContext._lastInsertedPasteContentIdentifier
+ _OBJC_IVAR_$__TUIKeyboardCandidateGenerationContext._sharedKeyboardContext
+ _OBJC_METACLASS_$_TUISharedKeyboardContext
+ _UIKBAttributeNameCustomSplitLayout
+ _UIKBAttributeNameSplitIndex
+ _UIKBTreePropertySplitDuplicate
+ _UTTypeFileURL
+ __OBJC_$_CLASS_METHODS__TtC11TextInputUI28TUITextComposerClientWrapper(TextInputUI)
+ __OBJC_$_INSTANCE_METHODS_TUISharedKeyboardContext
+ __OBJC_$_INSTANCE_VARIABLES_TUISharedKeyboardContext
+ __OBJC_$_PROP_LIST_TUISharedKeyboardContext
+ __OBJC_CLASS_PROTOCOLS_$_TUISharedKeyboardContext
+ __OBJC_CLASS_RO_$_TUISharedKeyboardContext
+ __OBJC_METACLASS_RO_$_TUISharedKeyboardContext
+ ___57-[TUIInputSessionManager _propagateSharedKeyboardContext]_block_invoke
+ _associated conformance 11TextInputUI21CalistogaFeatureFlags33_C90572265959E209E1BF186B5F2EDED5LLOSHAASQ
+ _get_witness_table 7SwiftUI15ModifiedContentVyACyACyAA6HStackVyAA05TupleD0VyACyACyAA5ImageVAA12_FrameLayoutVGAA21_TraitWritingModifierVyAA0i8PriorityJ3KeyVGG_ACyAA4TextVAA012_EnvironmentnkL0VySiSgGGQPGGAA05_FlexhI0VGAA08_PaddingI0VGAVyAA15DynamicTypeSizeOGGAA4ViewHPA5_AAA10_HPA2_AAA10_HPA_AAA10_HPyHC_A1_AA0vL0HPyHCHC_A4_AAA11_HPyHCHC_A8_AAA11_HPyHCHC
+ _get_witness_table 7SwiftUI15ModifiedContentVyACyACyAA6HStackVyAA05TupleD0VyACyACyAA5ImageVAA12_FrameLayoutVGAA21_TraitWritingModifierVyAA0i8PriorityJ3KeyVGG_ACyAA6VStackVyAGyACyAA4TextVAA012_EnvironmentnkL0VySiSgGG_A_QPGGAQGQPGGAA08_PaddingI0VGAA05_FlexhI0VGAXyAA15DynamicTypeSizeOGGAA4ViewHPA10_AAA15_HPA7_AAA15_HPA4_AAA15_HPyHC_A6_AA0wL0HPyHCHC_A9_AAA16_HPyHCHC_A13_AAA16_HPyHCHC
+ _get_witness_table 7SwiftUI15ModifiedContentVyACyACyAA6HStackVyAA05TupleD0VyACyACyACyAA5ImageVAA18_AspectRatioLayoutVGAA06_FrameJ0VGAA21_TraitWritingModifierVyAA0j8PriorityL3KeyVGG_ACyAA6VStackVyAGyACyAA4TextVAA012_EnvironmentpmN0VySiSgGG_A2_QPGGATGQPGGAA08_PaddingJ0VGAA05_FlexkJ0VGA_yAA15DynamicTypeSizeOGGAA4ViewHPA13_AAA18_HPA10_AAA18_HPA7_AAA18_HPyHC_A9_AA0yN0HPyHCHC_A12_AAA19_HPyHCHC_A16_AAA19_HPyHCHC
+ _swift_dynamicCastClass
+ _symbolic Sbz_Xx
+ _symbolic So12BSAuditTokenC
+ _symbolic So15TIKeyboardStateC
+ _symbolic _____ 11TextInputUI21CalistogaFeatureFlags33_C90572265959E209E1BF186B5F2EDED5LLO
+ _symbolic _____ So8_NSRangeV
+ _symbolic _____Sg 12TextComposer14DocumentFormatV
+ _symbolic _____yAAyAAy_____y_____yAAyAAyAAy__________G_____G_____y_____GG_AAy_____yACyAAy__________ySiSgGG_ARQPGGAKGQPGG_____G_____GAOy_____GG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA18_AspectRatioLayoutV AA06_FrameJ0V AA21_TraitWritingModifierV AA0j8PriorityL3KeyV AA6VStackV AA4TextV AA012_EnvironmentpmN0V AA08_PaddingJ0V AA05_FlexkJ0V AA15DynamicTypeSizeO
+ _symbolic _____yAAyAAy_____y_____yAAyAAy__________G_____y_____GG_AAy__________ySiSgGGQPGG_____G_____GALy_____GG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA12_FrameLayoutV AA21_TraitWritingModifierV AA0i8PriorityJ3KeyV AA4TextV AA012_EnvironmentnkL0V AA05_FlexhI0V AA08_PaddingI0V AA15DynamicTypeSizeO
+ _symbolic _____yAAyAAy_____y_____yAAyAAy__________G_____y_____GG_AAy_____yACyAAy__________ySiSgGG_APQPGGAIGQPGG_____G_____GAMy_____GG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA12_FrameLayoutV AA21_TraitWritingModifierV AA0i8PriorityJ3KeyV AA6VStackV AA4TextV AA012_EnvironmentnkL0V AA08_PaddingI0V AA05_FlexhI0V AA15DynamicTypeSizeO
+ _symbolic _____yAAy_____y_____yAAyAAyAAy__________G_____G_____y_____GG_AAy_____yACyAAy__________ySiSgGG_ARQPGGAKGQPGG_____G_____G 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA18_AspectRatioLayoutV AA06_FrameJ0V AA21_TraitWritingModifierV AA0j8PriorityL3KeyV AA6VStackV AA4TextV AA012_EnvironmentpmN0V AA08_PaddingJ0V AA05_FlexkJ0V
+ _symbolic _____yAAy_____y_____yAAyAAy__________G_____y_____GG_AAy_____yACyAAy__________ySiSgGG_APQPGGAIGQPGG_____G_____G 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA12_FrameLayoutV AA21_TraitWritingModifierV AA0i8PriorityJ3KeyV AA6VStackV AA4TextV AA012_EnvironmentnkL0V AA08_PaddingI0V AA05_FlexhI0V
+ _symbolic _____y_____G s16PartialRangeFromV SS5IndexV
+ _type_layout_string So8_NSRangeV
- -[TUIKeyplaneRow extraSpaceBar]
- -[TUIKeyplaneRow setExtraSpaceBar:]
- -[TUISmartReplyGenerator conversationType:]
- _OBJC_IVAR_$_TUIKeyplaneRow._extraSpaceBar
- __CLASS_METHODS__TtC11TextInputUI28TUITextComposerClientWrapper
- _associated conformance 11TextInputUI24IconServicesFeatureFlags33_C90572265959E209E1BF186B5F2EDED5LLOSHAASQ
- _get_witness_table 7SwiftUI15ModifiedContentVyACyACyACyAA6HStackVyAA05TupleD0VyACyACyAA5ImageVAA12_FrameLayoutVGAA21_TraitWritingModifierVyAA0i8PriorityJ3KeyVGG_ACyAA6VStackVyAGyACyAA4TextVAA012_EnvironmentnkL0VySiSgGG_A_QPGGAQGQPGGAA08_PaddingI0VGA6_GA6_GAXyAA15DynamicTypeSizeOGGAA4ViewHPA9_AAA14_HPA8_AAA14_HPA7_AAA14_HPA4_AAA14_HPyHC_A6_AA0vL0HPyHCHC_A6_AAA15_HPyHCHC_A6_AAA15_HPyHCHC_A12_AAA15_HPyHCHC
- _get_witness_table 7SwiftUI15ModifiedContentVyACyACyACyAA6HStackVyAA05TupleD0VyACyACyACyAA5ImageVAA18_AspectRatioLayoutVGAA06_FrameJ0VGAA21_TraitWritingModifierVyAA0j8PriorityL3KeyVGG_ACyAA6VStackVyAGyACyAA4TextVAA012_EnvironmentpmN0VySiSgGG_A2_QPGGATGQPGGAA08_PaddingJ0VGA9_GA9_GA_yAA15DynamicTypeSizeOGGAA4ViewHPA12_AAA17_HPA11_AAA17_HPA10_AAA17_HPA7_AAA17_HPyHC_A9_AA0xN0HPyHCHC_A9_AAA18_HPyHCHC_A9_AAA18_HPyHCHC_A15_AAA18_HPyHCHC
- _get_witness_table 7SwiftUI15ModifiedContentVyACyACyACyACyAA6HStackVyAA05TupleD0VyACyACyAA5ImageVAA12_FrameLayoutVGAA21_TraitWritingModifierVyAA0i8PriorityJ3KeyVGG_ACyAA4TextVAA012_EnvironmentnkL0VySiSgGGQPGGAA05_FlexhI0VGAA08_PaddingI0VGA4_GA4_GAVyAA15DynamicTypeSizeOGGAA4ViewHPA7_AAA12_HPA6_AAA12_HPA5_AAA12_HPA2_AAA12_HPA_AAA12_HPyHC_A1_AA0vL0HPyHCHC_A4_AAA13_HPyHCHC_A4_AAA13_HPyHCHC_A4_AAA13_HPyHCHC_A10_AAA13_HPyHCHC
- _swift_isUniquelyReferenced_native
- _symbolic _____ 11TextInputUI24IconServicesFeatureFlags33_C90572265959E209E1BF186B5F2EDED5LLO
- _symbolic _____yAAyAAyAAyAAy_____y_____yAAyAAy__________G_____y_____GG_AAy__________ySiSgGGQPGG_____G_____GATGATGALy_____GG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA12_FrameLayoutV AA21_TraitWritingModifierV AA0i8PriorityJ3KeyV AA4TextV AA012_EnvironmentnkL0V AA05_FlexhI0V AA08_PaddingI0V AA15DynamicTypeSizeO
- _symbolic _____yAAyAAyAAy_____y_____yAAyAAyAAy__________G_____G_____y_____GG_AAy_____yACyAAy__________ySiSgGG_ARQPGGAKGQPGG_____GAXGAXGAOy_____GG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA18_AspectRatioLayoutV AA06_FrameJ0V AA21_TraitWritingModifierV AA0j8PriorityL3KeyV AA6VStackV AA4TextV AA012_EnvironmentpmN0V AA08_PaddingJ0V AA15DynamicTypeSizeO
- _symbolic _____yAAyAAyAAy_____y_____yAAyAAy__________G_____y_____GG_AAy__________ySiSgGGQPGG_____G_____GATGATG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA12_FrameLayoutV AA21_TraitWritingModifierV AA0i8PriorityJ3KeyV AA4TextV AA012_EnvironmentnkL0V AA05_FlexhI0V AA08_PaddingI0V
- _symbolic _____yAAyAAyAAy_____y_____yAAyAAy__________G_____y_____GG_AAy_____yACyAAy__________ySiSgGG_APQPGGAIGQPGG_____GAVGAVGAMy_____GG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA12_FrameLayoutV AA21_TraitWritingModifierV AA0i8PriorityJ3KeyV AA6VStackV AA4TextV AA012_EnvironmentnkL0V AA08_PaddingI0V AA15DynamicTypeSizeO
- _symbolic _____yAAyAAy_____y_____yAAyAAyAAy__________G_____G_____y_____GG_AAy_____yACyAAy__________ySiSgGG_ARQPGGAKGQPGG_____GAXGAXG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA18_AspectRatioLayoutV AA06_FrameJ0V AA21_TraitWritingModifierV AA0j8PriorityL3KeyV AA6VStackV AA4TextV AA012_EnvironmentpmN0V AA08_PaddingJ0V
- _symbolic _____yAAyAAy_____y_____yAAyAAy__________G_____y_____GG_AAy__________ySiSgGGQPGG_____G_____GATG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA12_FrameLayoutV AA21_TraitWritingModifierV AA0i8PriorityJ3KeyV AA4TextV AA012_EnvironmentnkL0V AA05_FlexhI0V AA08_PaddingI0V
- _symbolic _____yAAyAAy_____y_____yAAyAAy__________G_____y_____GG_AAy_____yACyAAy__________ySiSgGG_APQPGGAIGQPGG_____GAVGAVG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA12_FrameLayoutV AA21_TraitWritingModifierV AA0i8PriorityJ3KeyV AA6VStackV AA4TextV AA012_EnvironmentnkL0V AA08_PaddingI0V
- _symbolic _____yAAy_____y_____yAAyAAyAAy__________G_____G_____y_____GG_AAy_____yACyAAy__________ySiSgGG_ARQPGGAKGQPGG_____GAXG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA18_AspectRatioLayoutV AA06_FrameJ0V AA21_TraitWritingModifierV AA0j8PriorityL3KeyV AA6VStackV AA4TextV AA012_EnvironmentpmN0V AA08_PaddingJ0V
- _symbolic _____yAAy_____y_____yAAyAAy__________G_____y_____GG_AAy_____yACyAAy__________ySiSgGG_APQPGGAIGQPGG_____GAVG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA12_FrameLayoutV AA21_TraitWritingModifierV AA0i8PriorityJ3KeyV AA6VStackV AA4TextV AA012_EnvironmentnkL0V AA08_PaddingI0V
- _symbolic _____ySSG 19CollectionsInternal10OrderedSetV
CStrings:
+ "-Split"
+ "-Wide"
+ "<%@: %p; _lastInsertedPasteContentIdentifier = %llu>"
+ "Cancelled paste candidate generation due to content already inserted"
+ "Candidate"
+ "KBSplitDuplicate"
+ "Manipuri-MeeteiMayek-QWERTY"
+ "Middle Padding"
+ "No custom split layout available for %@"
+ "No session found for versionedPID %@; cannot forward candidateAccepted"
+ "Padding"
+ "RECENT_PASTE_PHOTO_SINGULAR"
+ "Recorded last inserted paste content identifier on shared keyboard context for versionedPID %@"
+ "Small-Split"
+ "UIKBAttributeNameCustomSplitLayout"
+ "UIKBAttributeNameSplitIndex"
+ "Uyghur"
+ "[FedStats] Skipping '%s' — existing emoji covers it"
+ "custom-split-layout"
+ "recentPasteContentIdentifier"
+ "split-index"
- "%@ %@"
- "%ld %@"
```
