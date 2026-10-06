## MailUI

> `/System/Library/PrivateFrameworks/MailUI.framework/MailUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d0fc8` | `0x2dd0ac` | **`+0xc0e4`** |
| `__TEXT.__swift5_typeref` | `0xd84a` | `0xe07a` | **`+0x830`** |
| `__TEXT.__const` | `0xe854` | `0xefa4` | **`+0x750`** |
| `__DATA.__bss` | `0x7458` | `0x7af8` | **`+0x6a0`** |
| `__AUTH_CONST.__const` | `0x102a0` | `0x10638` | **`+0x398`** |
| `__TEXT.__cstring` | `0xdd09` | `0xe089` | **`+0x380`** |
| `__TEXT.__eh_frame` | `0x2a5c` | `0x2c74` | **`+0x218`** |
| `__TEXT.__unwind_info` | `0x60a8` | `0x62b0` | **`+0x208`** |
| `__DATA.__data` | `0x5da8` | `0x5f98` | **`+0x1f0`** |
| `__TEXT.__constg_swiftt` | `0x3d8c` | `0x3ed4` | **`+0x148`** |
| `__AUTH_CONST.__objc_const` | `0x14198` | `0x142a8` | **`+0x110`** |
| `__TEXT.__swift5_fieldmd` | `0x3148` | `0x3238` | **`+0xf0`** |
| `__TEXT.__swift5_reflstr` | `0x381b` | `0x390b` | **`+0xf0`** |
| `__AUTH_CONST.__auth_got` | `0x2be8` | `0x2cb0` | **`+0xc8`** |
| `__TEXT.__swift5_capture` | `0x4a60` | `0x4b28` | **`+0xc8`** |
| `__AUTH.__data` | `0xfe0` | `0x10a0` | **`+0xc0`** |
| `__TEXT.__swift5_assocty` | `0x1078` | `0x1108` | **`+0x90`** |
| `__AUTH.__objc_data` | `0x1da0` | `0x1df0` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x1d28` | `0x1d68` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0x63c` | `0x670` | **`+0x34`** |
| `__TEXT.__objc_methlist` | `0x9e04` | `0x9e34` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x6598` | `0x65c0` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x480` | `0x4a0` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x500` | `0x514` | **`+0x14`** |
| `__DATA_DIRTY.__data` | `0x3510` | `0x3500` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x238` | `0x244` | **`+0xc`** |
| `__DATA.__common` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x588` | `0x590` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x9a8` | `0x9ac` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x17c` | `0x180` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x144` | `0x148` | **`+0x4`** |

### Other Changes

```diff

-3891.100.17.2.4
+3893.100.7.0.0

-  Functions: 13895
-  Symbols:   8226
-  CStrings:  1981
+  Functions: 14102
+  Symbols:   8287
+  CStrings:  1999
Symbols:
+ -[MUISearchSuggestionPhraseManager filterQueryMessageIDs]
+ -[MUISearchSuggestionPhraseManager setFilterQueryMessageIDs:]
+ -[MessageListCellLayoutValuesHelper messageResultSeparatorLeadingInset]
+ -[MessageListDataSource messageListContainingItemID:]
+ GCC_except_table110
+ GCC_except_table32
+ GCC_except_table68
+ GCC_except_table93
+ _OBJC_CLASS_$_OS_os_log
+ _OBJC_IVAR_$_MUISearchSuggestionPhraseManager._filterQueryMessageIDs
+ __DATA__TtC6MailUI17PPTTestsViewModel
+ __IVARS__TtC6MailUI17PPTTestsViewModel
+ __METACLASS_DATA__TtC6MailUI17PPTTestsViewModel
+ _associated conformance 6MailUI0A22MessageQueryScopeErrorOSHAASQ
+ _associated conformance 6MailUI12PPTTestsViewV05SwiftB00D0AA4BodyAdEP_AdE
+ _associated conformance 6MailUI17PPTTestDefinitionVs12IdentifiableAA2IDsADP_SH
+ _associated conformance 6MailUI22PPTTestsViewModelErrorO10Foundation09LocalizedF0AAs0F0
+ _associated conformance So31NSPropertyListMutabilityOptionsVs10SetAlgebraSCSQ
+ _associated conformance So31NSPropertyListMutabilityOptionsVs10SetAlgebraSCs25ExpressibleByArrayLiteral
+ _associated conformance So31NSPropertyListMutabilityOptionsVs9OptionSetSCSY
+ _associated conformance So31NSPropertyListMutabilityOptionsVs9OptionSetSCs0F7Algebra
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA6VStackVyAA05TupleD0VyAA6HStackVyAGyAEyAGyAA4TextV_AKQPGG_AA6SpacerVAA6ButtonVyAKGQPGG_AA7ForEachVySaySSGSSACyAA4ViewPAAE14textFieldStyleyQrqd__AA0hoP0Rd__lFQOyAA0hO0VyAKG_AA013RoundedBorderhoP0VQo_AA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGGQPGGAA14_PaddingLayoutVGAaXHPA15_AaXHPyHC_A17_AA0mV0HPyHCHC
+ _get_witness_table 7SwiftUI4FormVyAA12TupleContentVyAA7SectionVyAA9EmptyViewVAEyAA4TextV_A2KSgQPGAIG_AA7ForEachVyAA7BindingVySay04MailB017PPTTestDefinitionVGGSSAA08ModifiedE0VyAA6VStackVyAEyAA6HStackVyAEyA_yAEyAK_AKQPGG_AA6SpacerVAA6ButtonVyAKGQPGG_APySaySSGSSAYyAA0H0PAAE14textFieldStyleyQrqd__AA0ivW0Rd__lFQOyAA0iV0VyAKG_AA013RoundedBorderivW0VQo_AA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGGQPGGAA14_PaddingLayoutVGGQPGGAAA12_HPyHC
+ _symbolic SDyS2SG
+ _symbolic SDySSypG
+ _symbolic SaySDySSypGG
+ _symbolic Say_____G 6MailUI17PPTTestDefinitionV
+ _symbolic So17EMMessageObjectIDCSg
+ _symbolic _____ 6MailUI0A22MessageQueryScopeErrorO
+ _symbolic _____ 6MailUI12PPTTestsViewV
+ _symbolic _____ 6MailUI17PPTTestDefinitionV
+ _symbolic _____ 6MailUI17PPTTestsViewModelC
+ _symbolic _____ 6MailUI22PPTTestsViewModelErrorO
+ _symbolic _____ So31NSPropertyListMutabilityOptionsV
+ _symbolic ______A2ASgt 7SwiftUI4TextV
+ _symbolic _____yS2S_G SD4KeysV
+ _symbolic _____ySSyp_G SD4KeysV
+ _symbolic _____ySSyp_G SD8IteratorV
+ _symbolic _____ySaySSGSS_____y_____y_____y_____G______Qo______y_____SgGGG 7SwiftUI7ForEachV AA15ModifiedContentV AA4ViewPAAE14textFieldStyleyQrqd__AA04TextiJ0Rd__lFQO AA0kI0V AA0K0V AA013RoundedBorderkiJ0V AA30_EnvironmentKeyWritingModifierV AA4FontV
+ _symbolic _____ySay_____GG 7SwiftUI7BindingV 04MailB017PPTTestDefinitionV
+ _symbolic _____ySo7NSArrayCG 15EmailFoundation8EFFutureC
+ _symbolic _____ySo9EMMessageCG 15EmailFoundation8EFFutureC
+ _symbolic _____y_____G 7SwiftUI5StateV 04MailB017PPTTestsViewModelC
+ _symbolic _____y_____G 7SwiftUI7BindingV 04MailB017PPTTestDefinitionV
+ _symbolic _____y_____G 7SwiftUI7BindingV 04MailB017PPTTestsViewModelC
+ _symbolic _____y______A2BSgQPG 7SwiftUI12TupleContentV AA4TextV
+ _symbolic _____y___________y_____yACy______AEQPGG___________yAEGQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA6VStackV AA4TextV AA6SpacerV AA6ButtonV
+ _symbolic _____y___________y_____yACy_____yACy______AFQPGG___________yAFGQPGG______ySaySSGSS_____y_____y_____yAFG______Qo______y_____SgGGGQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA6HStackV AA0F0V AA4TextV AA6SpacerV AA6ButtonV AA7ForEachV AA08ModifiedI0V AA0D0PAAE14textFieldStyleyQrqd__AA0krS0Rd__lFQO AA0kR0V AA013RoundedBorderkrS0V AA30_EnvironmentKeyWritingModifierV AA4FontV
+ _symbolic _____y__________y______A2DSgQPGABG 7SwiftUI7SectionV AA9EmptyViewV AA12TupleContentV AA4TextV
+ _symbolic _____y__________y______A2DSgQPGABG______y_____ySay_____GGSS_____y_____yACy_____yACyANyACyAD_ADQPGG___________yADGQPGG_AHySaySSGSSAMy_____y_____yADG______Qo______y_____SgGGGQPGG_____GGt 7SwiftUI7SectionV AA9EmptyViewV AA12TupleContentV AA4TextV AA7ForEachV AA7BindingV 04MailB017PPTTestDefinitionV AA08ModifiedG0V AA6VStackV AA6HStackV AA6SpacerV AA6ButtonV AA0E0PAAE14textFieldStyleyQrqd__AA0huV0Rd__lFQO AA0hU0V AA013RoundedBorderhuV0V AA30_EnvironmentKeyWritingModifierV AA4FontV AA14_PaddingLayoutV
+ _symbolic _____y_____yAAy______ACQPGG___________yACGQPG 7SwiftUI12TupleContentV AA6VStackV AA4TextV AA6SpacerV AA6ButtonV
+ _symbolic _____y_____yAAy_____yAAy______ADQPGG___________yADGQPGG______ySaySSGSS_____y_____y_____yADG______Qo______y_____SgGGGQPG 7SwiftUI12TupleContentV AA6HStackV AA6VStackV AA4TextV AA6SpacerV AA6ButtonV AA7ForEachV AA08ModifiedD0V AA4ViewPAAE14textFieldStyleyQrqd__AA0goP0Rd__lFQO AA0gO0V AA013RoundedBordergoP0V AA30_EnvironmentKeyWritingModifierV AA4FontV
+ _symbolic _____y_____ySay_____GGSS_____y_____y_____y_____yAHyAGyAHy______AJQPGG___________yAJGQPGG_AAySaySSGSSAFy_____y_____yAJG______Qo______y_____SgGGGQPGG_____GG 7SwiftUI7ForEachV AA7BindingV 04MailB017PPTTestDefinitionV AA15ModifiedContentV AA6VStackV AA05TupleJ0V AA6HStackV AA4TextV AA6SpacerV AA6ButtonV AA4ViewPAAE14textFieldStyleyQrqd__AA0nsT0Rd__lFQO AA0nS0V AA013RoundedBordernsT0V AA30_EnvironmentKeyWritingModifierV AA4FontV AA14_PaddingLayoutV
+ _symbolic _____y_____y_____AAy______A2DSgQPGACG______y_____ySay_____GGSS_____y_____yAAy_____yAAyANyAAyAD_ADQPGG___________yADGQPGG_AHySaySSGSSAMy_____y_____yADG______Qo______y_____SgGGGQPGG_____GGQPG 7SwiftUI12TupleContentV AA7SectionV AA9EmptyViewV AA4TextV AA7ForEachV AA7BindingV 04MailB017PPTTestDefinitionV AA08ModifiedD0V AA6VStackV AA6HStackV AA6SpacerV AA6ButtonV AA0G0PAAE14textFieldStyleyQrqd__AA0huV0Rd__lFQO AA0hU0V AA013RoundedBorderhuV0V AA30_EnvironmentKeyWritingModifierV AA4FontV AA14_PaddingLayoutV
+ _symbolic _____y_____y_____G______Qo_ 7SwiftUI4ViewPAAE14textFieldStyleyQrqd__AA04TexteF0Rd__lFQO AA0gE0V AA0G0V AA013RoundedBordergeF0V
+ _symbolic _____y_____y______ACQPGG___________yACGt 7SwiftUI6VStackV AA12TupleContentV AA4TextV AA6SpacerV AA6ButtonV
+ _symbolic _____y_____y_____yAByAAyABy______ADQPGG___________yADGQPGG______ySaySSGSS_____y_____y_____yADG______Qo______y_____SgGGGQPGG 7SwiftUI6VStackV AA12TupleContentV AA6HStackV AA4TextV AA6SpacerV AA6ButtonV AA7ForEachV AA08ModifiedE0V AA4ViewPAAE14textFieldStyleyQrqd__AA0goP0Rd__lFQO AA0gO0V AA013RoundedBordergoP0V AA30_EnvironmentKeyWritingModifierV AA4FontV
+ _symbolic _____y_____y_____yABy______ADQPGG___________yADGQPGG 7SwiftUI6HStackV AA12TupleContentV AA6VStackV AA4TextV AA6SpacerV AA6ButtonV
+ _symbolic _____y_____y_____yABy______ADQPGG___________yADGQPGG______ySaySSGSS_____y_____y_____yADG______Qo______y_____SgGGGt 7SwiftUI6HStackV AA12TupleContentV AA6VStackV AA4TextV AA6SpacerV AA6ButtonV AA7ForEachV AA08ModifiedE0V AA4ViewPAAE14textFieldStyleyQrqd__AA0goP0Rd__lFQO AA0gO0V AA013RoundedBordergoP0V AA30_EnvironmentKeyWritingModifierV AA4FontV
+ _symbolic _____y_____y_____y_____ABy______A2ESgQPGADG______y_____ySay_____GGSS_____y_____yABy_____yAByAOyAByAE_AEQPGG___________yAEGQPGG_AIySaySSGSSANy_____y_____yAEG______Qo______y_____SgGGGQPGG_____GGQPGG 7SwiftUI4FormV AA12TupleContentV AA7SectionV AA9EmptyViewV AA4TextV AA7ForEachV AA7BindingV 04MailB017PPTTestDefinitionV AA08ModifiedE0V AA6VStackV AA6HStackV AA6SpacerV AA6ButtonV AA0H0PAAE14textFieldStyleyQrqd__AA0ivW0Rd__lFQO AA0iV0V AA013RoundedBorderivW0V AA30_EnvironmentKeyWritingModifierV AA4FontV AA14_PaddingLayoutV
+ _symbolic _____y_____y_____y_____G______Qo______y_____SgGG 7SwiftUI15ModifiedContentV AA4ViewPAAE14textFieldStyleyQrqd__AA04TextgH0Rd__lFQO AA0iG0V AA0I0V AA013RoundedBorderigH0V AA30_EnvironmentKeyWritingModifierV AA4FontV
+ _symbolic _____y_____y_____y_____yACyAByACy______AEQPGG___________yAEGQPGG______ySaySSGSSAAy_____y_____yAEG______Qo______y_____SgGGGQPGG_____G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA6HStackV AA4TextV AA6SpacerV AA6ButtonV AA7ForEachV AA4ViewPAAE14textFieldStyleyQrqd__AA0hoP0Rd__lFQO AA0hO0V AA013RoundedBorderhoP0V AA30_EnvironmentKeyWritingModifierV AA4FontV AA14_PaddingLayoutV
+ _symbolic xq_xq_Iegnnrr_
+ _symbolic ySS_SDySSypGtScMYcc
+ _symbolic ypSg
+ _type_layout_string 6MailUI12PPTTestsViewV
+ _type_layout_string 6MailUI17PPTTestDefinitionV
+ _type_layout_string 6MailUI22PPTTestsViewModelErrorO
- -[_TopHitsMessageListCellLayoutValues linesOfSummaryForCompactHeight:]
- GCC_except_table67
- GCC_except_table79
- _EMPersistenceStatisticsKeyMessagesInLargestRemoteAccount
- _symbolic Say______pSgG So17EMMessageListItemP
- _symbolic _____y_____GSg 16GenerativeSearch15ComposableQueryV AA11MailContentV
- _symbolic _____y______pG 15EmailFoundation8EFFutureC So17EMMessageListItemP
CStrings:
+ " is locked, charging, and connected to WLAN. This may take more than a few days."
+ " is locked, charging, and connected to Wi-Fi. This may take more than a few days."
+ ": "
+ "Could not find resource: "
+ "Dialog to show and say when the user has asked to do something with an email draft, but we did not find any matching results."
+ "Draft_Not_Found_Dialog"
+ "Failed to load PPT test definitions: %@"
+ "List of top result messages"
+ "PList contains unexpected data"
+ "Power & Performance Tests"
+ "Run"
+ "Running tests from here is only useful for development — **no performance metrics are gathered and certain tests may not work out-of-the-box**. This list and the editable parameters are populated from `testDefinitions.plist`; the tests are implemented in `MailAppControllerTesting` (defined on each platform)."
+ "Sorry, I couldn't find any matching email drafts."
+ "Swift/Sequence.swift"
+ "Top Results"
+ "aggregate"
+ "plist"
+ "testDefinitions"
+ "testDefinitions.plist"
+ "testName"
+ "timeoutInSeconds"
- " is locked, charging, and connected to WLAN. This may take up to a week."
- " is locked, charging, and connected to Wi-Fi. This may take up to a week."
- "List of top hit messages"
```
