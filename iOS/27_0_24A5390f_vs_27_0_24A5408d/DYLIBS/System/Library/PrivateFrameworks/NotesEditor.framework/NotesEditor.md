## NotesEditor

> `/System/Library/PrivateFrameworks/NotesEditor.framework/NotesEditor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x308fbc` | `0x30c150` | **`+0x3194`** |
| `__TEXT.__swift5_typeref` | `0x361d0` | `0x3632a` | **`+0x15a`** |
| `__AUTH_CONST.__objc_const` | `0x20778` | `0x208a8` | **`+0x130`** |
| `__TEXT.__objc_methlist` | `0x16bdc` | `0x16d04` | **`+0x128`** |
| `__DATA_CONST.__objc_selrefs` | `0xfa08` | `0xfb08` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0x61e0` | `0x62a0` | **`+0xc0`** |
| `__TEXT.__const` | `0xbd14` | `0xbdb4` | **`+0xa0`** |
| `__AUTH_CONST.__auth_got` | `0x3988` | `0x3a10` | **`+0x88`** |
| `__DATA_CONST.__got` | `0x3108` | `0x3170` | **`+0x68`** |
| `__DATA.__data` | `0x87cc` | `0x881c` | **`+0x50`** |
| `__TEXT.__cstring` | `0xb88b` | `0xb8db` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xa010` | `0xa050` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x3d90` | `0x3dbc` | **`+0x2c`** |
| `__AUTH_CONST.__const` | `0xb8f0` | `0xb918` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x4748` | `0x4770` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x1110` | `0x1128` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x34e4` | `0x34f4` | **`+0x10`** |

### Other Changes

```diff

-2998.0.0.0.0
+3001.2.1.0.0

-  Functions: 15717
-  Symbols:   14299
-  CStrings:  1901
+  Functions: 15752
+  Symbols:   14341
+  CStrings:  1907
Symbols:
+ -[ICEditingTextView pasteAsMarkdown:]
+ -[ICEditingTextView selectionContainsOnlyDividerLine]
+ -[ICNoteEditorNavigationItemConfiguration calculatorModeBarButtonItemGroupWithItem:]
+ -[ICNoteEditorNavigationItemConfiguration calculatorModeBarButtonItemGroup]
+ -[ICNoteEditorNavigationItemConfiguration collaborationBarButtonItemGroupWithItem:]
+ -[ICNoteEditorNavigationItemConfiguration collaborationBarButtonItemGroup]
+ -[ICNoteEditorNavigationItemConfiguration itemsHostedInContextualFormatBar:]
+ -[ICNoteEditorNavigationItemConfiguration lockBarButtonItemGroupWithItem:]
+ -[ICNoteEditorNavigationItemConfiguration lockBarButtonItemGroup]
+ -[ICNoteEditorNavigationItemConfiguration quickNoteSaveBarButtonItemGroup]
+ -[ICNoteEditorNavigationItemConfiguration setCalculatorModeBarButtonItemGroup:]
+ -[ICNoteEditorNavigationItemConfiguration setCollaborationBarButtonItemGroup:]
+ -[ICNoteEditorNavigationItemConfiguration setLockBarButtonItemGroup:]
+ -[ICNoteEditorNavigationItemConfiguration setQuickNoteSaveBarButtonItemGroup:]
+ -[ICNoteEditorNavigationItemConfiguration setShareBarButtonItemGroup:]
+ -[ICNoteEditorNavigationItemConfiguration setWritingToolsFormatBarButtonItem:]
+ -[ICNoteEditorNavigationItemConfiguration shareBarButtonItemGroupWithItem:]
+ -[ICNoteEditorNavigationItemConfiguration shareBarButtonItemGroup]
+ -[ICNoteEditorNavigationItemConfiguration writingToolsBarButtonItemImage]
+ -[ICNoteEditorNavigationItemConfiguration writingToolsFormatBarButtonItem]
+ -[ICNoteEditorViewController refreshInlineAttachmentTextStyling]
+ -[ICTextView _systemContentInset]
+ GCC_except_table105
+ GCC_except_table130
+ GCC_except_table145
+ GCC_except_table148
+ GCC_except_table167
+ GCC_except_table170
+ GCC_except_table183
+ GCC_except_table219
+ GCC_except_table269
+ GCC_except_table317
+ GCC_except_table323
+ GCC_except_table352
+ GCC_except_table354
+ GCC_except_table357
+ GCC_except_table36
+ GCC_except_table405
+ GCC_except_table548
+ GCC_except_table579
+ GCC_except_table584
+ GCC_except_table610
+ GCC_except_table63
+ GCC_except_table649
+ GCC_except_table682
+ GCC_except_table694
+ GCC_except_table71
+ GCC_except_table725
+ GCC_except_table742
+ GCC_except_table75
+ GCC_except_table83
+ GCC_except_table92
+ _NSProtocolFromString
+ _OBJC_CLASS_$_UIKeyboardSceneDelegate
+ _OBJC_IVAR_$_ICNoteEditorNavigationItemConfiguration._calculatorModeBarButtonItemGroup
+ _OBJC_IVAR_$_ICNoteEditorNavigationItemConfiguration._collaborationBarButtonItemGroup
+ _OBJC_IVAR_$_ICNoteEditorNavigationItemConfiguration._lockBarButtonItemGroup
+ _OBJC_IVAR_$_ICNoteEditorNavigationItemConfiguration._quickNoteSaveBarButtonItemGroup
+ _OBJC_IVAR_$_ICNoteEditorNavigationItemConfiguration._shareBarButtonItemGroup
+ _OBJC_IVAR_$_ICNoteEditorNavigationItemConfiguration._writingToolsFormatBarButtonItem
+ _UIMenuAutoFill
+ _UIMenuLookup
+ ___37-[ICEditingTextView pasteAsMarkdown:]_block_invoke
+ ___53-[ICEditingTextView selectionContainsOnlyDividerLine]_block_invoke
+ ___64-[ICNoteEditorViewController refreshInlineAttachmentTextStyling]_block_invoke
+ ___block_descriptor_56_e8_32s40r48r_e27_v40?08{_NSRange=QQ}16^B32lr40l8s32l8r48l8
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA6ZStackVyAA4ViewPAAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQOyAA6VStackVyAA05TupleD0VyACyACyACyAA5ImageVAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGAA016_ForegroundStyleS0VyAA017HierarchicalShapeV0VGGAA0j10AttachmentS0VG_ACyAA012_ConditionalD0VyACyAA4TextVASyAA13OpenURLActionVGGA9_GA1_GQPGG_Qo_G11NotesEditor016ErrorPlaceHolderfS0VGAaFHPA19_AaFHPyHC_A22_AA0fS0HPyHCHC
+ _symbolic _____ 7SwiftUI13OpenURLActionV
+ _symbolic _____yAAyAAy__________y_____SgGG_____y_____GG_____G_AAy_____yAAy_____ACy_____GGAOGAJGt 7SwiftUI15ModifiedContentV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleI0V AA017HierarchicalShapeL0V AA023AccessibilityAttachmentI0V AA012_ConditionalD0V AA4TextV AA13OpenURLActionV
+ _symbolic _____ySny_____GG s23_ContiguousArrayStorageC 10Foundation16AttributedStringV5IndexV
+ _symbolic _____y_____G 7SwiftUI30_EnvironmentKeyWritingModifierV AA13OpenURLActionV
+ _symbolic _____y_____G s16IndexingIteratorV 10Foundation16AttributedStringV4RunsV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation16AttributedStringV4RunsV3RunV
+ _symbolic _____y___________y_____yADyADy__________y_____SgGG_____y_____GG_____G_ADy_____yADy_____AFy_____GGARGAMGQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA08ModifiedI0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleO0V AA017HierarchicalShapeR0V AA023AccessibilityAttachmentO0V AA012_ConditionalI0V AA4TextV AA13OpenURLActionV
+ _symbolic _____y___________y_____y_____y_____yAEyAEy__________y_____SgGG_____y_____GG_____G_AEy_____yAEy_____AGy_____GGASGANGQPGG_Qo_G 7SwiftUI13_VariadicViewO4TreeV AA13_ZStackLayoutV AA0D0PAAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQO AA6VStackV AA12TupleContentV AA08ModifiedP0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleV0V AA017HierarchicalShapeY0V AA0k10AttachmentV0V AA012_ConditionalP0V AA4TextV AA13OpenURLActionV
+ _symbolic _____y__________y_____GG 7SwiftUI15ModifiedContentV AA4TextV AA30_EnvironmentKeyWritingModifierV AA13OpenURLActionV
+ _symbolic _____y_____yAAy__________y_____GGACG_____y_____GG 7SwiftUI15ModifiedContentV AA012_ConditionalD0V AA4TextV AA30_EnvironmentKeyWritingModifierV AA13OpenURLActionV AA016_ForegroundStyleJ0V AA017HierarchicalShapeN0V
+ _symbolic _____y_____y__________y_____GGAC_G 7SwiftUI19_ConditionalContentV7StorageO AA08ModifiedD0V AA4TextV AA30_EnvironmentKeyWritingModifierV AA13OpenURLActionV
+ _symbolic _____y_____y_____yACyACy__________y_____SgGG_____y_____GG_____G_ACy_____yACy_____AEy_____GGAQGALGQPGG 7SwiftUI6VStackV AA12TupleContentV AA08ModifiedE0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleK0V AA017HierarchicalShapeN0V AA023AccessibilityAttachmentK0V AA012_ConditionalE0V AA4TextV AA13OpenURLActionV
+ _symbolic _____y_____y_____y_____y_____yAAyAAyAAy__________y_____SgGG_____y_____GG_____G_AAy_____yAAy_____AFy_____GGARGAMGQPGG_Qo_G_____G 7SwiftUI15ModifiedContentV AA6ZStackV AA4ViewPAAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQO AA6VStackV AA05TupleD0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleS0V AA017HierarchicalShapeV0V AA0j10AttachmentS0V AA012_ConditionalD0V AA4TextV AA13OpenURLActionV 11NotesEditor016ErrorPlaceHolderfS0V
+ _symbolic _____y_____y_____y_____y_____yADyADy__________y_____SgGG_____y_____GG_____G_ADy_____yADy_____AFy_____GGARGAMGQPGG_Qo_G 7SwiftUI6ZStackV AA4ViewPAAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQO AA6VStackV AA12TupleContentV AA08ModifiedM0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleS0V AA017HierarchicalShapeV0V AA0h10AttachmentS0V AA012_ConditionalM0V AA4TextV AA13OpenURLActionV
- GCC_except_table110
- GCC_except_table116
- GCC_except_table129
- GCC_except_table144
- GCC_except_table147
- GCC_except_table166
- GCC_except_table169
- GCC_except_table178
- GCC_except_table182
- GCC_except_table218
- GCC_except_table268
- GCC_except_table316
- GCC_except_table322
- GCC_except_table351
- GCC_except_table353
- GCC_except_table356
- GCC_except_table404
- GCC_except_table547
- GCC_except_table578
- GCC_except_table583
- GCC_except_table60
- GCC_except_table609
- GCC_except_table648
- GCC_except_table681
- GCC_except_table693
- GCC_except_table723
- GCC_except_table73
- GCC_except_table741
- GCC_except_table86
- GCC_except_table93
- GCC_except_table97
- ___101-[ICNoteEditorViewController managedObjectContextChangeController:performUpdatesForManagedObjectIDs:]_block_invoke
- _get_witness_table 7SwiftUI15ModifiedContentVyAA6ZStackVyAA4ViewPAAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQOyAA6VStackVyAA05TupleD0VyACyACyACyAA5ImageVAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGAA016_ForegroundStyleS0VyAA017HierarchicalShapeV0VGGAA0j10AttachmentS0VG_AA4TextVQPGG_Qo_G11NotesEditor016ErrorPlaceHolderfS0VGAaFHPA11_AaFHPyHC_A14_AA0fS0HPyHCHC
- _symbolic _____yAAyAAy__________y_____SgGG_____y_____GG_____G______t 7SwiftUI15ModifiedContentV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleI0V AA017HierarchicalShapeL0V AA023AccessibilityAttachmentI0V AA4TextV
- _symbolic _____y___________y_____yADyADy__________y_____SgGG_____y_____GG_____G______QPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA08ModifiedI0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleO0V AA017HierarchicalShapeR0V AA023AccessibilityAttachmentO0V AA4TextV
- _symbolic _____y___________y_____y_____y_____yAEyAEy__________y_____SgGG_____y_____GG_____G______QPGG_Qo_G 7SwiftUI13_VariadicViewO4TreeV AA13_ZStackLayoutV AA0D0PAAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQO AA6VStackV AA12TupleContentV AA08ModifiedP0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleV0V AA017HierarchicalShapeY0V AA0k10AttachmentV0V AA4TextV
- _symbolic _____y_____y_____yACyACy__________y_____SgGG_____y_____GG_____G______QPGG 7SwiftUI6VStackV AA12TupleContentV AA08ModifiedE0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleK0V AA017HierarchicalShapeN0V AA023AccessibilityAttachmentK0V AA4TextV
- _symbolic _____y_____y_____y_____y_____yAAyAAyAAy__________y_____SgGG_____y_____GG_____G______QPGG_Qo_G_____G 7SwiftUI15ModifiedContentV AA6ZStackV AA4ViewPAAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQO AA6VStackV AA05TupleD0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleS0V AA017HierarchicalShapeV0V AA0j10AttachmentS0V AA4TextV 11NotesEditor016ErrorPlaceHolderfS0V
- _symbolic _____y_____y_____y_____y_____yADyADy__________y_____SgGG_____y_____GG_____G______QPGG_Qo_G 7SwiftUI6ZStackV AA4ViewPAAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQO AA6VStackV AA12TupleContentV AA08ModifiedM0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleS0V AA017HierarchicalShapeV0V AA0h10AttachmentS0V AA4TextV
CStrings:
+ "Add Row (undo)"
+ "Add Table (undo)"
+ "ICAllowNotificationsWarmingSheet"
+ "Paste (undo)"
+ "Pasted markdown"
+ "Writing Tools"
+ "siri"
- "ICAllowNotificationsViewController"
```
