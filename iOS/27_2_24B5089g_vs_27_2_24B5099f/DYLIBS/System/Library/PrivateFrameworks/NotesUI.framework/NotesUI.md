## NotesUI

> `/System/Library/PrivateFrameworks/NotesUI.framework/NotesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c5108` | `0x2c1094` | **`-0x4074`** |
| `__TEXT.__oslogstring` | `0xa325` | `0xa505` | **`+0x1e0`** |
| `__TEXT.__eh_frame` | `0x4930` | `0x4ac8` | **`+0x198`** |
| `__TEXT.__unwind_info` | `0x9e00` | `0x9e98` | **`+0x98`** |
| `__AUTH_CONST.__objc_const` | `0x24648` | `0x246c8` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x6648` | `0x66b8` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x17248` | `0x172b0` | **`+0x68`** |
| `__DATA.__data` | `0x585c` | `0x57fc` | **`-0x60`** |
| `__TEXT.__cstring` | `0x140e9` | `0x14099` | **`-0x50`** |
| `__DATA_CONST.__got` | `0x2f40` | `0x2ef8` | **`-0x48`** |
| `__TEXT.__swift5_typeref` | `0xcba8` | `0xcb64` | **`-0x44`** |
| `__AUTH_CONST.__cfstring` | `0xc320` | `0xc360` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x20dc` | `0x210c` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x3360` | `0x3348` | **`-0x18`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x1e0` | `0x1f8` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x4b08` | `0x4b1c` | **`+0x14`** |
| `__DATA.__bss` | `0x4470` | `0x4460` | **`-0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x328` | `0x338` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x1f8` | `0x204` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x100f8` | `0x10100` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xfc` | `0x104` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x114` | `0x11c` | **`+0x8`** |

### Other Changes

```diff

-3001.40.9.100.1
+3001.40.11.102.1

-  Functions: 15078
-  Symbols:   15994
-  CStrings:  3275
+  Functions: 15104
+  Symbols:   16007
+  CStrings:  3283
Symbols:
+ +[ICHandwritingDebugWindow preferredFrameForWindowScene:]
+ +[UIImage(IC) ic_hierarchicalConfigurationForColors:]
+ +[UIScreen(IC) ic_allScreens]
+ +[UIScreen(IC) ic_anyScreen]
+ -[AVAsset(IC_UI) ic_generatePreviewImageWithCompletion:]
+ -[AVAsset(IC_UI) ic_previewImageWithCompletion:]
+ -[ICAuthenticationPrompt(StringsPrivate) cloudAccountName]
+ -[ICAuthenticationPrompt(StringsPrivate) customAccountName]
+ -[ICAuthenticationPrompt(StringsPrivate) deviceAccountName]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForAddLock]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForChangeModeFrom]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForChangeModeTo]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForChangeMode]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForChangePassword]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForDeleteMixedNotes]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForDeleteMultipleNotes]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForDeleteNotes]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForDeleteSingleNote]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForRemoveLock]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForResetPassword]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForToggleBiometrics]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForViewAttachment]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForViewNote]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStrings]
+ -[ICHandwritingDebugWindow initWithDelegate:windowScene:]
+ -[ICTextController isListOrFixedWidthTextView:forRanges:]
+ -[ICTextController isListTextView:forRanges:]
+ -[ICTextController textView:hasListInRanges:orFixedWidth:]
+ -[UIDevice(IC) ic_isLargeiPad]
+ -[UIScreen(IC) ic_isLargeiPad]
+ GCC_except_table106
+ GCC_except_table121
+ GCC_except_table129
+ GCC_except_table147
+ GCC_except_table154
+ GCC_except_table160
+ GCC_except_table51
+ GCC_except_table59
+ GCC_except_table64
+ GCC_except_table74
+ GCC_except_table80
+ GCC_except_table89
+ GCC_except_table94
+ _AXShowBordersEnabled
+ _AXShowBordersEnabledStatusDidChangeNotification
+ _UISceneDidDisconnectNotification
+ _UISceneWillConnectNotification
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_UIDevice_$_IC
+ __OBJC_$_INSTANCE_METHODS_ICAuthenticationPrompt(StringsPrivate)
+ __OBJC_$_PROP_LIST_UIDevice_$_IC
+ ___41-[ICAttachmentImageLoadingOperation main]_block_invoke_6
+ ___46-[ICAppearanceInfo(UI) defaultTraitCollection]_block_invoke
+ ___48-[AVAsset(IC_UI) ic_previewImageWithCompletion:]_block_invoke
+ ___56-[AVAsset(IC_UI) ic_generatePreviewImageWithCompletion:]_block_invoke
+ ___70-[NoteHTMLEditorView contextMenuConfigurationForElement:presentation:]_block_invoke_5
+ ___85-[ICTextController applyDividerLine:paragraphStyle:pStart:pEnd:pContentEnd:range:tv:]_block_invoke_3
+ ___block_descriptor_40_e27_v16?0"<UIMutableTraits>"8l
+ ___block_descriptor_40_e8_32bs_e40_v48?0^{CGImage=}8{?=qiIq}16"NSError"40ls32l8
+ ___block_descriptor_40_e8_32s_e45_"NSProgress"16?0?<v?"NSData""NSError">8ls32l8
+ ___block_descriptor_48_e8_32s40r_e36_v40?0"UIColor"8{_NSRange=QQ}16^B32lr40l8s32l8
+ _get_witness_table qd0__7SwiftUI4ViewHD3_AaBPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAA24ButtonStyleConfigurationV5LabelV_SbQo_HO
+ _symbolic _____y______SbQo_ 7SwiftUI4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA24ButtonStyleConfigurationV5LabelV
- +[ICHandwritingDebugWindow preferredFrame]
- +[UIDevice(IC) ic_isLargeiPad]
- -[AVAsset(IC_UI) ic_previewImage]
- -[ICAuthenticationPrompt(Strings) cloudAccountName]
- -[ICAuthenticationPrompt(Strings) customAccountName]
- -[ICAuthenticationPrompt(Strings) deviceAccountName]
- -[ICAuthenticationPrompt(Strings) updateStringsForAddLock]
- -[ICAuthenticationPrompt(Strings) updateStringsForChangeModeFrom]
- -[ICAuthenticationPrompt(Strings) updateStringsForChangeModeTo]
- -[ICAuthenticationPrompt(Strings) updateStringsForChangeMode]
- -[ICAuthenticationPrompt(Strings) updateStringsForChangePassword]
- -[ICAuthenticationPrompt(Strings) updateStringsForDeleteMixedNotes]
- -[ICAuthenticationPrompt(Strings) updateStringsForDeleteMultipleNotes]
- -[ICAuthenticationPrompt(Strings) updateStringsForDeleteNotes]
- -[ICAuthenticationPrompt(Strings) updateStringsForDeleteSingleNote]
- -[ICAuthenticationPrompt(Strings) updateStringsForRemoveLock]
- -[ICAuthenticationPrompt(Strings) updateStringsForResetPassword]
- -[ICAuthenticationPrompt(Strings) updateStringsForToggleBiometrics]
- -[ICAuthenticationPrompt(Strings) updateStringsForViewAttachment]
- -[ICAuthenticationPrompt(Strings) updateStringsForViewNote]
- -[ICAuthenticationPrompt(Strings) updateStrings]
- -[ICHandwritingDebugWindow initWithDelegate:]
- -[ICTodoButton(PlatformSpecificResponsibility) imageRectForContentRect:]
- -[UITraitCollection(IC) ic_traitCollectionByAppendingNonNilTraitCollection:]
- GCC_except_table117
- GCC_except_table125
- GCC_except_table143
- GCC_except_table150
- GCC_except_table156
- GCC_except_table56
- GCC_except_table61
- GCC_except_table77
- GCC_except_table86
- GCC_except_table91
- _UIAccessibilityButtonShapesEnabled
- _UIAccessibilityButtonShapesEnabledStatusDidChangeNotification
- _UIScreenDidConnectNotification
- _UIScreenDidDisconnectNotification
- __OBJC_$_INSTANCE_METHODS_ICAuthenticationPrompt(Strings)
- ___block_descriptor_40_e8_32bs_e63_v32?0?<v?"<NSSecureCoding>""NSError">8#16"NSDictionary"24ls32l8
- _currMarkdownStyleLocation
- _didMarkdownStyle
- _get_witness_table 7SwiftUI15ModifiedContentVyAA24ButtonStyleConfigurationV5LabelVAA20_ValueActionModifierVySbGGAA4ViewHPAgaLHPyHC_AjA0lK0HPyHCHC
- _symbolic So6ICNoteCSgXw
- _symbolic So6ICNoteCSgXwz_Xx
- _symbolic _____Sg 11NotesShared24ActivityEventParticipantV5NamesO
- _symbolic _____ySbG 7SwiftUI20_ValueActionModifierV
- _symbolic _____y__________ySbGG 7SwiftUI15ModifiedContentV AA24ButtonStyleConfigurationV5LabelV AA20_ValueActionModifierV
- _symbolic _____z_Xx 8PaperKit19GraphableExpressionV
CStrings:
+ "Failed to generate preview image for asset: %@"
+ "Unknown activity — falling back to activityItemIdParts"
+ "Unknown activity — falling back to empty title"
+ "Unknown activity — falling back to nil destination"
+ "Unknown activity — falling back to nil subtitle"
+ "Unknown activity — treating as not cacheable"
+ "Unknown activity — treating as not visible"
+ "commonMetadata"
+ "duration"
+ "parent attachment was deallocated before saveEverything could run"
+ "v48@?0^{CGImage=}8{?=qiIq}16@\"NSError\"40"
- "Paper widget thumbnail type not supported"
- "PaperChromeOverlay"
- "v32@?0@?<v@?@\"<NSSecureCoding>\"@\"NSError\">8#16@\"NSDictionary\"24"
```
