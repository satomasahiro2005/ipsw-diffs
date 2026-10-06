## NotesUI

> `/System/Library/PrivateFrameworks/NotesUI.framework/NotesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2bb898` | `0x2bfd78` | **`+0x44e0`** |
| `__TEXT.__cstring` | `0x13ffd` | `0x141cd` | **`+0x1d0`** |
| `__AUTH_CONST.__cfstring` | `0xc1a0` | `0xc340` | **`+0x1a0`** |
| `__TEXT.__objc_methlist` | `0x16ff8` | `0x17168` | **`+0x170`** |
| `__AUTH_CONST.__objc_const` | `0x242b0` | `0x24400` | **`+0x150`** |
| `__DATA_CONST.__objc_selrefs` | `0xff68` | `0x10088` | **`+0x120`** |
| `__TEXT.__gcc_except_tab` | `0x4924` | `0x4a1c` | **`+0xf8`** |
| `__DATA.__data` | `0x56e4` | `0x57d4` | **`+0xf0`** |
| `__DATA_CONST.__const` | `0x6508` | `0x65f8` | **`+0xf0`** |
| `__AUTH_CONST.__const` | `0xa2e0` | `0xa3a8` | **`+0xc8`** |
| `__TEXT.__oslogstring` | `0xa155` | `0xa215` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x9bf8` | `0x9cb8` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0xc8c4` | `0xc942` | **`+0x7e`** |
| `__AUTH_CONST.__auth_got` | `0x3320` | `0x3360` | **`+0x40`** |
| `__TEXT.__const` | `0x9ff4` | `0xa034` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x46e8` | `0x4718` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x2ee8` | `0x2f08` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x25e0` | `0x25c0` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x202c` | `0x2040` | **`+0x14`** |
| `__AUTH.__data` | `0x1c48` | `0x1c50` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x3c0` | `0x3c8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x11d0` | `0x11d4` | **`+0x4`** |

### Other Changes

```diff

-2998.0.0.0.0
+3001.2.1.0.0

-  Functions: 14892
-  Symbols:   15883
-  CStrings:  3246
+  Functions: 14940
+  Symbols:   15942
+  CStrings:  3268
Symbols:
+ +[ICDeviceSupport(UI) isEnhancedSiriAvailable]
+ +[UIAction(IC) ic_actionWithAttributedTitle:image:handler:]
+ -[ICCreateHTMLNoteAction performWithAttributedTitle:contents:pinned:stylesTitle:error:]
+ -[ICCreateModernNoteAction performWithAttributedTitle:contents:pinned:stylesTitle:error:]
+ -[ICCreateNoteAction performWithAttributedTitle:contents:pinned:container:error:]
+ -[ICDividerLineTextAttachmentView contextMenuInteraction:configurationForMenuAtLocation:]
+ -[ICDividerLineTextAttachmentView dividerContextMenuInteraction]
+ -[ICDividerLineTextAttachmentView dividerLineEditMenu]
+ -[ICDividerLineTextAttachmentView dividerLineRangeInTextView:]
+ -[ICDividerLineTextAttachmentView enclosingTextView]
+ -[ICDividerLineTextAttachmentView handleDoubleTap:]
+ -[ICDividerLineTextAttachmentView performDividerLineEdit:]
+ -[ICDividerLineTextAttachmentView selectDividerLine]
+ -[ICDividerLineTextAttachmentView setDividerContextMenuInteraction:]
+ -[ICDividerLineTextAttachmentView setupDividerInteractions]
+ -[ICNote(UI) exportDataForUTI:]
+ -[UITextView(IC) ic_availableWidthForFullWidthAttachmentInTextContainer:]
+ -[UITraitCollection(IC) ic_sceneActivationAllowed]
+ GCC_except_table124
+ GCC_except_table126
+ GCC_except_table128
+ GCC_except_table135
+ GCC_except_table137
+ GCC_except_table141
+ GCC_except_table157
+ GCC_except_table159
+ GCC_except_table69
+ GCC_except_table76
+ GCC_except_table78
+ GCC_except_table81
+ _ICStringFromSplitViewControllerDisplayMode
+ _OBJC_CLASS_$_UIContextMenuInteraction
+ _OBJC_CLASS_$_WTAvailability
+ _OBJC_IVAR_$_ICDividerLineTextAttachmentView._dividerContextMenuInteraction
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UIContextMenuInteractionDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_UIContextMenuInteractionDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_UIContextMenuInteractionDelegate
+ __OBJC_$_PROTOCOL_REFS_UIContextMenuInteractionDelegate
+ __OBJC_CLASS_PROTOCOLS_$_ICDividerLineTextAttachmentView
+ __OBJC_LABEL_PROTOCOL_$_UIContextMenuInteractionDelegate
+ __OBJC_PROTOCOL_$_UIContextMenuInteractionDelegate
+ ___54-[ICDividerLineTextAttachmentView dividerLineEditMenu]_block_invoke
+ ___54-[ICDividerLineTextAttachmentView dividerLineEditMenu]_block_invoke_2
+ ___54-[ICDividerLineTextAttachmentView dividerLineEditMenu]_block_invoke_3
+ ___54-[ICDividerLineTextAttachmentView dividerLineEditMenu]_block_invoke_4
+ ___54-[ICDividerLineTextAttachmentView dividerLineEditMenu]_block_invoke_5
+ ___54-[ICDividerLineTextAttachmentView dividerLineEditMenu]_block_invoke_6
+ ___54-[ICDividerLineTextAttachmentView dividerLineEditMenu]_block_invoke_7
+ ___54-[ICDividerLineTextAttachmentView dividerLineEditMenu]_block_invoke_8
+ ___60-[ICMarkdownRepresentation createRenderableAttributedString]_block_invoke_11
+ ___62-[ICDividerLineTextAttachmentView dividerLineRangeInTextView:]_block_invoke
+ ___81-[ICCreateNoteAction performWithAttributedTitle:contents:pinned:container:error:]_block_invoke
+ ___81-[ICCreateNoteAction performWithAttributedTitle:contents:pinned:container:error:]_block_invoke_2
+ ___83+[ICNote(AirDropDocumentUI) createNoteForAirDropDocument:legacyContext:completion:]_block_invoke_2
+ ___87-[ICCreateHTMLNoteAction performWithAttributedTitle:contents:pinned:stylesTitle:error:]_block_invoke
+ ___89-[ICCreateModernNoteAction performWithAttributedTitle:contents:pinned:stylesTitle:error:]_block_invoke
+ ___89-[ICDividerLineTextAttachmentView contextMenuInteraction:configurationForMenuAtLocation:]_block_invoke
+ ___93+[ICTextController attributedStringToPasteWithAdaptedParagraphStyles:pasteRange:textStorage:]_block_invoke
+ ___93+[ICTextController attributedStringToPasteWithAdaptedParagraphStyles:pasteRange:textStorage:]_block_invoke_2
+ ___block_descriptor_32_e20_v16?0"UITextView"8l
+ ___block_descriptor_32_e39_"NSArray"16?0"NSPresentationIntent"8l
+ ___block_descriptor_40_e8_32r_e47_v40?0"ICTTParagraphStyle"8{_NSRange=QQ}16^B32lr32l8
+ ___block_descriptor_40_e8_32w_e18_v16?0"UIAction"8lw32l8
+ ___block_descriptor_40_e8_32w_e25_"UIMenu"16?0"NSArray"8lw32l8
+ ___block_descriptor_88_e8_32s40s48s56bs64bs72r80r_e27_v40?08{_NSRange=QQ}16^B32ls56l8s32l8r72l8s40l8s48l8r80l8s64l8
+ _symbolic SDy__________G 10Foundation4UUIDV So29ICCalculateDocumentControllerC7NotesUIE5IndexC
+ _symbolic _____Sg 8PaperKit19SharedCanvasElementO
+ _symbolic ___________t 10Foundation4UUIDV So29ICCalculateDocumentControllerC7NotesUIE5IndexC
+ _symbolic _____y_____G 9Coherence12CROrderedSetV 8PaperKit19SharedCanvasElementO
+ _symbolic _____y_____GSg_ADt 9Coherence3RefV 8PaperKit12GraphElementV
+ _symbolic _____y______G 9Coherence12CROrderedSetV8IteratorV 8PaperKit19SharedCanvasElementO
+ _symbolic _____y__________G s18_DictionaryStorageC 10Foundation4UUIDV So29ICCalculateDocumentControllerC7NotesUIE5IndexC
+ _symbolic _____y_____yAAySSGGG s18ReversedCollectionV s5SliceV
- GCC_except_table101
- GCC_except_table123
- GCC_except_table127
- GCC_except_table134
- GCC_except_table136
- GCC_except_table140
- GCC_except_table145
- GCC_except_table156
- GCC_except_table80
- ___71-[ICCreateNoteAction performWithTitle:contents:pinned:container:error:]_block_invoke
- ___71-[ICCreateNoteAction performWithTitle:contents:pinned:container:error:]_block_invoke_2
- ___77-[ICCreateHTMLNoteAction performWithTitle:contents:pinned:stylesTitle:error:]_block_invoke
- ___79-[ICCreateModernNoteAction performWithTitle:contents:pinned:stylesTitle:error:]_block_invoke
- ___block_descriptor_80_e8_32s40s48s56bs64r72r_e27_v40?08{_NSRange=QQ}16^B32ls56l8s32l8r64l8s40l8s48l8r72l8
CStrings:
+ "-[ICCreateNoteAction performWithAttributedTitle:contents:pinned:container:error:]"
+ "@\"NSArray\"16@?0@\"NSPresentationIntent\"8"
+ "Automatic"
+ "Cut"
+ "Dropping non-NSTextAttachment attachment value before serialization: %@"
+ "In the middle of drawing a stroke, deferring paperDidChange for %@"
+ "Insert Graph (undo)"
+ "NotesUI/CalculateDocumentController.swift"
+ "OneBesideSecondary"
+ "OneOverSecondary"
+ "Paste"
+ "Retaining save block until merges unblock…"
+ "SecondaryOnly"
+ "Suggestion"
+ "TwoBesideSecondary"
+ "TwoDisplaceSecondary"
+ "TwoOverSecondary"
+ "Unknown(%ld)"
+ "cachedIndex(of:) must be called on the main thread"
+ "doc.on.clipboard"
+ "rebuildExpressionIndexCache() must be called on the main thread"
+ "scissors"
+ "v16@?0@\"UITextView\"8"
- "-[ICCreateNoteAction performWithTitle:contents:pinned:container:error:]"
```
