## NotesUI

> `/System/Library/PrivateFrameworks/NotesUI.framework/NotesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b5914` | `0x2bb898` | **`+0x5f84`** |
| `__AUTH_CONST.__objc_const` | `0x24898` | `0x242b0` | **`-0x5e8`** |
| `__AUTH_CONST.__const` | `0x9d68` | `0xa2e0` | **`+0x578`** |
| `__TEXT.__objc_methlist` | `0x17428` | `0x16ff8` | **`-0x430`** |
| `__TEXT.__const` | `0x9d54` | `0x9ff4` | **`+0x2a0`** |
| `__TEXT.__swift5_reflstr` | `0x2047` | `0x2284` | **`+0x23d`** |
| `__AUTH_CONST.__cfstring` | `0xc3c0` | `0xc1a0` | **`-0x220`** |
| `__TEXT.__swift5_fieldmd` | `0x2344` | `0x2560` | **`+0x21c`** |
| `__DATA.__bss` | `0x3f50` | `0x4160` | **`+0x210`** |
| `__DATA_CONST.__objc_selrefs` | `0x10168` | `0xff68` | **`-0x200`** |
| `__TEXT.__ustring` | `0x13a84` | `0x13896` | **`-0x1ee`** |
| `__TEXT.__swift5_typeref` | `0xc6ec` | `0xc8c4` | **`+0x1d8`** |
| `__TEXT.__constg_swiftt` | `0x3a00` | `0x3b78` | **`+0x178`** |
| `__AUTH_CONST.__auth_got` | `0x31d0` | `0x3320` | **`+0x150`** |
| `__TEXT.__swift5_capture` | `0x1edc` | `0x202c` | **`+0x150`** |
| `__DATA.__data` | `0x561c` | `0x56e4` | **`+0xc8`** |
| `__TEXT.__cstring` | `0x13f37` | `0x13ffd` | **`+0xc6`** |
| `__AUTH.__objc_data` | `0x4008` | `0x40c8` | **`+0xc0`** |
| `__AUTH.__data` | `0x1bb0` | `0x1c48` | **`+0x98`** |
| `__DATA.__objc_ivar` | `0x124c` | `0x11d0` | **`-0x7c`** |
| `__DATA_CONST.__got` | `0x2ea0` | `0x2ee8` | **`+0x48`** |
| `__AUTH_CONST.__objc_intobj` | `0x630` | `0x660` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x64d8` | `0x6508` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0x258` | `0x280` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x9bd0` | `0x9bf8` | **`+0x28`** |
| `__DATA_DIRTY.__data` | `0x2600` | `0x25e0` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x4944` | `0x4924` | **`-0x20`** |
| `__TEXT.__swift5_types` | `0x2ec` | `0x30c` | **`+0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0x6b8` | `0x6a0` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xad8` | `0xac8` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x3f4` | `0x404` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x170` | `0x178` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x46f0` | `0x46e8` | **`-0x8`** |
| `__TEXT.__oslogstring` | `0xa152` | `0xa155` | **`+0x3`** |

### Other Changes

```diff

-2996.0.0.0.0
+2998.0.0.0.0

-  Functions: 14844
-  Symbols:   15995
-  CStrings:  3252
+  Functions: 14892
+  Symbols:   15883
+  CStrings:  3246
Symbols:
+ +[ICPasswordChangePresenter viewControllerForAddingPasswordWithAccount:completion:]
+ +[ICPasswordChangePresenter viewControllerForChangingPasswordWithAccount:didAuthenticateWithBiometrics:completion:]
+ -[ICAttachment(UI) imageActivityItemProvider]
+ -[ICAuthorHighlightsController flashNavigationHighlightForRange:color:duration:inTextStorage:]
+ -[ICCreateHTMLNoteAction performWithTitle:contents:pinned:stylesTitle:error:]
+ -[ICCreateModernNoteAction performWithTitle:contents:pinned:stylesTitle:error:]
+ -[ICCreateNoteAction setStylesTitle:]
+ -[ICCreateNoteAction stylesTitle]
+ _ICAuthorHighlightAnimationDefaultNavigationFlashDuration
+ _ICNoteExporterAIGCDocumentCommentSentinel
+ _NSCommentDocumentAttribute
+ _OBJC_CLASS_$_ICPasswordChangePresenter
+ _OBJC_CLASS_$_NSCollectionLayoutSection
+ _OBJC_CLASS_$_UICollectionViewCompositionalLayout
+ _OBJC_CLASS_$__TtC7NotesUI17PasswordFieldCell
+ _OBJC_IVAR_$_ICCreateNoteAction._stylesTitle
+ _OBJC_METACLASS_$_ICPasswordChangePresenter
+ _OBJC_METACLASS_$__TtC7NotesUI17PasswordFieldCell
+ _UICollectionElementKindSectionFooter
+ __DATA_ICPasswordChangeViewController
+ __DATA__TtC7NotesUI17PasswordFieldCell
+ __INSTANCE_METHODS_ICPasswordChangeViewController
+ __IVARS_ICPasswordChangeViewController
+ __IVARS__TtC7NotesUI17PasswordFieldCell
+ __METACLASS_DATA_ICPasswordChangeViewController
+ __METACLASS_DATA__TtC7NotesUI17PasswordFieldCell
+ __OBJC_$_CLASS_METHODS_ICPasswordChangePresenter
+ __OBJC_$_INSTANCE_METHODS__TtC7NotesUI17PasswordFieldCell(NotesUI)
+ __OBJC_CLASS_PROTOCOLS_$__TtC7NotesUI17PasswordFieldCell(NotesUI)
+ __OBJC_CLASS_RO_$_ICPasswordChangePresenter
+ __OBJC_METACLASS_RO_$_ICPasswordChangePresenter
+ ___45-[ICAttachment(UI) imageActivityItemProvider]_block_invoke
+ ___45-[ICAttachment(UI) imageActivityItemProvider]_block_invoke_10
+ ___45-[ICAttachment(UI) imageActivityItemProvider]_block_invoke_11
+ ___45-[ICAttachment(UI) imageActivityItemProvider]_block_invoke_12
+ ___45-[ICAttachment(UI) imageActivityItemProvider]_block_invoke_2
+ ___45-[ICAttachment(UI) imageActivityItemProvider]_block_invoke_3
+ ___45-[ICAttachment(UI) imageActivityItemProvider]_block_invoke_4
+ ___45-[ICAttachment(UI) imageActivityItemProvider]_block_invoke_5
+ ___45-[ICAttachment(UI) imageActivityItemProvider]_block_invoke_6
+ ___45-[ICAttachment(UI) imageActivityItemProvider]_block_invoke_7
+ ___45-[ICAttachment(UI) imageActivityItemProvider]_block_invoke_8
+ ___45-[ICAttachment(UI) imageActivityItemProvider]_block_invoke_9
+ ___77-[ICCreateHTMLNoteAction performWithTitle:contents:pinned:stylesTitle:error:]_block_invoke
+ ___79-[ICCreateModernNoteAction performWithTitle:contents:pinned:stylesTitle:error:]_block_invoke
+ ___94-[ICAuthorHighlightsController flashNavigationHighlightForRange:color:duration:inTextStorage:]_block_invoke
+ ___block_descriptor_64_e8_32s40s48s56s_e20_v24?0{_NSRange=QQ}8ls32l8s40l8s48l8s56l8
+ ___block_descriptor_66_e8_32s40s48r56r_e5_v8?0ls32l8r48l8s40l8r56l8
+ ___swift_memcpy144_8
+ _associated conformance 7NotesUI28PasswordChangeViewControllerC3Row33_063C9B0EE5701E98F450560DEF660F10LLOSHAASQ
+ _associated conformance 7NotesUI28PasswordChangeViewControllerC7Section33_063C9B0EE5701E98F450560DEF660F10LLOSHAASQ
+ _keypath_get.134Tm
+ _symbolic Sb29didAuthenticateWithBiometrics_t
+ _symbolic So11UIStackViewC
+ _symbolic So11UITextFieldC
+ _symbolic So16UICollectionViewCSg
+ _symbolic So18NSLayoutConstraintCSg
+ _symbolic So24UICollectionViewListCellC
+ _symbolic So26ICAccountPassphraseManagerC
+ _symbolic _____ 7NotesUI17PasswordFieldCellC
+ _symbolic _____ 7NotesUI26PasswordFieldConfigurationV
+ _symbolic _____ 7NotesUI28PasswordChangeViewControllerC
+ _symbolic _____ 7NotesUI28PasswordChangeViewControllerC3Row33_063C9B0EE5701E98F450560DEF660F10LLO
+ _symbolic _____ 7NotesUI28PasswordChangeViewControllerC4Mode33_063C9B0EE5701E98F450560DEF660F10LLO
+ _symbolic _____ 7NotesUI28PasswordChangeViewControllerC7Section33_063C9B0EE5701E98F450560DEF660F10LLO
+ _symbolic _____ So15UIReturnKeyTypeV
+ _symbolic _____ So22ICAuthenticationResultV
+ _symbolic _____Iegy_Sg So22ICAuthenticationResultV
+ _symbolic _____IeyBy_ So22ICAuthenticationResultV
+ _symbolic _____Sg 10Foundation9IndexPathV
+ _symbolic _____Sg 7NotesUI28PasswordChangeViewControllerC3Row33_063C9B0EE5701E98F450560DEF660F10LLO
+ _symbolic _____SgXw 7NotesUI28PasswordChangeViewControllerC
+ _symbolic _____SgXwz_Xx 7NotesUI28PasswordChangeViewControllerC
+ _symbolic _____y_So24UICollectionViewListCellCG So16UICollectionViewC5UIKitE25SupplementaryRegistrationV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12CoreGraphics7CGFloatV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 7NotesUI28PasswordChangeViewControllerC3Row33_063C9B0EE5701E98F450560DEF660F10LLO
+ _symbolic _____y__________G 5UIKit28NSDiffableDataSourceSnapshotV 7NotesUI28PasswordChangeViewControllerC7Section33_063C9B0EE5701E98F450560DEF660F10LLO AF3RowAHLLO
+ _symbolic _____y__________G 5UIKit34UICollectionViewDiffableDataSourceC 7NotesUI014PasswordChangeC10ControllerC7Section33_063C9B0EE5701E98F450560DEF660F10LLO AF3RowAHLLO
+ _symbolic _____y__________GSg 5UIKit34UICollectionViewDiffableDataSourceC 7NotesUI014PasswordChangeC10ControllerC7Section33_063C9B0EE5701E98F450560DEF660F10LLO AF3RowAHLLO
+ _symbolic _____y___________G So16UICollectionViewC5UIKitE16CellRegistrationV 7NotesUI013PasswordFieldD0C AF0h6ChangeB10ControllerC3Row33_063C9B0EE5701E98F450560DEF660F10LLO
+ _symbolic ySSc
+ _symbolic y_____cSg So22ICAuthenticationResultV
+ _type_layout_string 7NotesUI26PasswordFieldConfigurationV
- -[ICCreateHTMLNoteAction performWithTitle:contents:pinned:error:]
- -[ICCreateModernNoteAction performWithTitle:contents:pinned:error:]
- -[ICPasswordChangeView .cxx_destruct]
- -[ICPasswordChangeView layoutSubviews]
- -[ICPasswordChangeView parentViewController]
- -[ICPasswordChangeView setParentViewController:]
- -[ICPasswordChangeView updateConstraints]
- -[ICPasswordChangeViewController .cxx_destruct]
- -[ICPasswordChangeViewController alternateConstraintsForAXLargerTextSizes]
- -[ICPasswordChangeViewController cancelButtonPressed:]
- -[ICPasswordChangeViewController cancelButton]
- -[ICPasswordChangeViewController completionHandler]
- -[ICPasswordChangeViewController consumedBottomAreaForResizer:]
- -[ICPasswordChangeViewController contentSizeCategoryDidChange]
- -[ICPasswordChangeViewController dealloc]
- -[ICPasswordChangeViewController defaultConstraints]
- -[ICPasswordChangeViewController didAttemptToSubmitWithoutHint]
- -[ICPasswordChangeViewController didAuthenticateWithBiometrics]
- -[ICPasswordChangeViewController disclaimerAttributedString]
- -[ICPasswordChangeViewController dismissKeyboardIfNeeded]
- -[ICPasswordChangeViewController dismissWithResult:]
- -[ICPasswordChangeViewController doneButtonPressed:]
- -[ICPasswordChangeViewController doneButton]
- -[ICPasswordChangeViewController firstResponderTextField]
- -[ICPasswordChangeViewController headerBackground]
- -[ICPasswordChangeViewController headerLabel]
- -[ICPasswordChangeViewController hintLabel]
- -[ICPasswordChangeViewController hintTextField]
- -[ICPasswordChangeViewController incorrectPasswordAttempts]
- -[ICPasswordChangeViewController initWithCompletionHandler:]
- -[ICPasswordChangeViewController isInSettings]
- -[ICPasswordChangeViewController isSettingInitialPassword]
- -[ICPasswordChangeViewController isSetupForChangePassword]
- -[ICPasswordChangeViewController keyboardResizerScrollView]
- -[ICPasswordChangeViewController oldPasswordHeightConstraint]
- -[ICPasswordChangeViewController oldPasswordLabel]
- -[ICPasswordChangeViewController oldPasswordTextField]
- -[ICPasswordChangeViewController orderedTextFields]
- -[ICPasswordChangeViewController passphraseManager]
- -[ICPasswordChangeViewController passwordAndVerifyTextFieldsMatch]
- -[ICPasswordChangeViewController passwordLabel]
- -[ICPasswordChangeViewController passwordTextField]
- -[ICPasswordChangeViewController passwordUtilities]
- -[ICPasswordChangeViewController registerForTraitChanges]
- -[ICPasswordChangeViewController resetTextFields]
- -[ICPasswordChangeViewController scrollViewResizer]
- -[ICPasswordChangeViewController scrollView]
- -[ICPasswordChangeViewController setAlternateConstraintsForAXLargerTextSizes:]
- -[ICPasswordChangeViewController setCancelButton:]
- -[ICPasswordChangeViewController setCompletionHandler:]
- -[ICPasswordChangeViewController setDefaultConstraints:]
- -[ICPasswordChangeViewController setDidAttemptToSubmitWithoutHint:]
- -[ICPasswordChangeViewController setDidAuthenticateWithBiometrics:]
- -[ICPasswordChangeViewController setDoneButton:]
- -[ICPasswordChangeViewController setHeaderBackground:]
- -[ICPasswordChangeViewController setHeaderLabel:]
- -[ICPasswordChangeViewController setHintLabel:]
- -[ICPasswordChangeViewController setHintTextField:]
- -[ICPasswordChangeViewController setIncorrectPasswordAttempts:]
- -[ICPasswordChangeViewController setIsInSettings:]
- -[ICPasswordChangeViewController setIsSettingInitialPassword:]
- -[ICPasswordChangeViewController setIsSetupForChangePassword:]
- -[ICPasswordChangeViewController setOldPasswordHeightConstraint:]
- -[ICPasswordChangeViewController setOldPasswordLabel:]
- -[ICPasswordChangeViewController setOldPasswordTextField:]
- -[ICPasswordChangeViewController setOrderedTextFields:]
- -[ICPasswordChangeViewController setPassphraseManager:]
- -[ICPasswordChangeViewController setPasswordLabel:]
- -[ICPasswordChangeViewController setPasswordTextField:]
- -[ICPasswordChangeViewController setPasswordUtilities:]
- -[ICPasswordChangeViewController setScrollView:]
- -[ICPasswordChangeViewController setScrollViewResizer:]
- -[ICPasswordChangeViewController setTextBackgroundViews:]
- -[ICPasswordChangeViewController setUpForAddingPasswordWithAccount:]
- -[ICPasswordChangeViewController setUpForChangePasswordWithAccount:didAuthenticateWithBiometrics:]
- -[ICPasswordChangeViewController setUpNavigationBar]
- -[ICPasswordChangeViewController setUsingLargerAXSizes:]
- -[ICPasswordChangeViewController setVerifyLabel:]
- -[ICPasswordChangeViewController setVerifyTextField:]
- -[ICPasswordChangeViewController setWarningLabel:]
- -[ICPasswordChangeViewController setupAccessibility]
- -[ICPasswordChangeViewController textBackgroundViews]
- -[ICPasswordChangeViewController textFieldShouldReturn:]
- -[ICPasswordChangeViewController updateFonts]
- -[ICPasswordChangeViewController usingLargerAXSizes]
- -[ICPasswordChangeViewController validateInput]
- -[ICPasswordChangeViewController verifyLabel]
- -[ICPasswordChangeViewController verifyTextField]
- -[ICPasswordChangeViewController viewDidAppear:]
- -[ICPasswordChangeViewController viewDidLoad]
- -[ICPasswordChangeViewController viewWillAppear:]
- -[ICPasswordChangeViewController viewWillDisappear:]
- -[ICPasswordChangeViewController viewWillTransitionToSize:withTransitionCoordinator:]
- -[ICPasswordChangeViewController warningLabel]
- -[ICSinglePixelHorizontalLineView sizeLayoutAttribute]
- -[ICSinglePixelLineView addSizeConstraint]
- -[ICSinglePixelLineView findSizeLayoutConstraintIfExists]
- -[ICSinglePixelLineView hasSetUpSizeConstraint]
- -[ICSinglePixelLineView ic_displayScale]
- -[ICSinglePixelLineView setHasSetUpSizeConstraint:]
- -[ICSinglePixelLineView setUpSizeConstraintIfNecessary]
- -[ICSinglePixelLineView updateConstraints]
- -[ICSinglePixelVerticalLineView sizeLayoutAttribute]
- _OBJC_CLASS_$_ICPasswordChangeView
- _OBJC_CLASS_$_ICSinglePixelHorizontalLineView
- _OBJC_CLASS_$_ICSinglePixelLineView
- _OBJC_CLASS_$_ICSinglePixelVerticalLineView
- _OBJC_IVAR_$_ICPasswordChangeView._parentViewController
- _OBJC_IVAR_$_ICPasswordChangeViewController._alternateConstraintsForAXLargerTextSizes
- _OBJC_IVAR_$_ICPasswordChangeViewController._cancelButton
- _OBJC_IVAR_$_ICPasswordChangeViewController._completionHandler
- _OBJC_IVAR_$_ICPasswordChangeViewController._defaultConstraints
- _OBJC_IVAR_$_ICPasswordChangeViewController._didAttemptToSubmitWithoutHint
- _OBJC_IVAR_$_ICPasswordChangeViewController._didAuthenticateWithBiometrics
- _OBJC_IVAR_$_ICPasswordChangeViewController._doneButton
- _OBJC_IVAR_$_ICPasswordChangeViewController._headerBackground
- _OBJC_IVAR_$_ICPasswordChangeViewController._headerLabel
- _OBJC_IVAR_$_ICPasswordChangeViewController._hintLabel
- _OBJC_IVAR_$_ICPasswordChangeViewController._hintTextField
- _OBJC_IVAR_$_ICPasswordChangeViewController._incorrectPasswordAttempts
- _OBJC_IVAR_$_ICPasswordChangeViewController._isInSettings
- _OBJC_IVAR_$_ICPasswordChangeViewController._isSettingInitialPassword
- _OBJC_IVAR_$_ICPasswordChangeViewController._isSetupForChangePassword
- _OBJC_IVAR_$_ICPasswordChangeViewController._oldPasswordHeightConstraint
- _OBJC_IVAR_$_ICPasswordChangeViewController._oldPasswordLabel
- _OBJC_IVAR_$_ICPasswordChangeViewController._oldPasswordTextField
- _OBJC_IVAR_$_ICPasswordChangeViewController._orderedTextFields
- _OBJC_IVAR_$_ICPasswordChangeViewController._passphraseManager
- _OBJC_IVAR_$_ICPasswordChangeViewController._passwordLabel
- _OBJC_IVAR_$_ICPasswordChangeViewController._passwordTextField
- _OBJC_IVAR_$_ICPasswordChangeViewController._passwordUtilities
- _OBJC_IVAR_$_ICPasswordChangeViewController._scrollView
- _OBJC_IVAR_$_ICPasswordChangeViewController._scrollViewResizer
- _OBJC_IVAR_$_ICPasswordChangeViewController._textBackgroundViews
- _OBJC_IVAR_$_ICPasswordChangeViewController._usingLargerAXSizes
- _OBJC_IVAR_$_ICPasswordChangeViewController._verifyLabel
- _OBJC_IVAR_$_ICPasswordChangeViewController._verifyTextField
- _OBJC_IVAR_$_ICPasswordChangeViewController._warningLabel
- _OBJC_IVAR_$_ICSinglePixelLineView._hasSetUpSizeConstraint
- _OBJC_METACLASS_$_ICPasswordChangeView
- _OBJC_METACLASS_$_ICSinglePixelHorizontalLineView
- _OBJC_METACLASS_$_ICSinglePixelLineView
- _OBJC_METACLASS_$_ICSinglePixelVerticalLineView
- _UIAccessibilityTraitHeader
- __OBJC_$_INSTANCE_METHODS_ICPasswordChangeView
- __OBJC_$_INSTANCE_METHODS_ICPasswordChangeViewController
- __OBJC_$_INSTANCE_METHODS_ICSinglePixelHorizontalLineView
- __OBJC_$_INSTANCE_METHODS_ICSinglePixelLineView
- __OBJC_$_INSTANCE_METHODS_ICSinglePixelVerticalLineView
- __OBJC_$_INSTANCE_VARIABLES_ICPasswordChangeView
- __OBJC_$_INSTANCE_VARIABLES_ICPasswordChangeViewController
- __OBJC_$_INSTANCE_VARIABLES_ICSinglePixelLineView
- __OBJC_$_PROP_LIST_ICPasswordChangeView
- __OBJC_$_PROP_LIST_ICPasswordChangeViewController
- __OBJC_$_PROP_LIST_ICSinglePixelLineView
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_ICScrollViewKeyboardResizerDelegate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_ICScrollViewKeyboardResizerDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_ICScrollViewKeyboardResizerDelegate
- __OBJC_$_PROTOCOL_REFS_ICScrollViewKeyboardResizerDelegate
- __OBJC_CLASS_PROTOCOLS_$_ICPasswordChangeViewController
- __OBJC_CLASS_RO_$_ICPasswordChangeView
- __OBJC_CLASS_RO_$_ICPasswordChangeViewController
- __OBJC_CLASS_RO_$_ICSinglePixelHorizontalLineView
- __OBJC_CLASS_RO_$_ICSinglePixelLineView
- __OBJC_CLASS_RO_$_ICSinglePixelVerticalLineView
- __OBJC_LABEL_PROTOCOL_$_ICScrollViewKeyboardResizerDelegate
- __OBJC_METACLASS_RO_$_ICPasswordChangeView
- __OBJC_METACLASS_RO_$_ICPasswordChangeViewController
- __OBJC_METACLASS_RO_$_ICSinglePixelHorizontalLineView
- __OBJC_METACLASS_RO_$_ICSinglePixelLineView
- __OBJC_METACLASS_RO_$_ICSinglePixelVerticalLineView
- __OBJC_PROTOCOL_$_ICScrollViewKeyboardResizerDelegate
- ___52-[ICPasswordChangeViewController dismissWithResult:]_block_invoke
- ___52-[ICPasswordChangeViewController doneButtonPressed:]_block_invoke
- ___57-[ICPasswordChangeViewController firstResponderTextField]_block_invoke
- ___57-[ICPasswordChangeViewController registerForTraitChanges]_block_invoke
- ___59-[ICAttachmentImageActivityItemSource _resolveItemProvider]_block_invoke
- ___59-[ICAttachmentImageActivityItemSource _resolveItemProvider]_block_invoke_10
- ___59-[ICAttachmentImageActivityItemSource _resolveItemProvider]_block_invoke_11
- ___59-[ICAttachmentImageActivityItemSource _resolveItemProvider]_block_invoke_12
- ___59-[ICAttachmentImageActivityItemSource _resolveItemProvider]_block_invoke_2
- ___59-[ICAttachmentImageActivityItemSource _resolveItemProvider]_block_invoke_3
- ___59-[ICAttachmentImageActivityItemSource _resolveItemProvider]_block_invoke_4
- ___59-[ICAttachmentImageActivityItemSource _resolveItemProvider]_block_invoke_5
- ___59-[ICAttachmentImageActivityItemSource _resolveItemProvider]_block_invoke_6
- ___59-[ICAttachmentImageActivityItemSource _resolveItemProvider]_block_invoke_7
- ___59-[ICAttachmentImageActivityItemSource _resolveItemProvider]_block_invoke_8
- ___59-[ICAttachmentImageActivityItemSource _resolveItemProvider]_block_invoke_9
- ___65-[ICCreateHTMLNoteAction performWithTitle:contents:pinned:error:]_block_invoke
- ___67-[ICCreateModernNoteAction performWithTitle:contents:pinned:error:]_block_invoke
- ___85-[ICPasswordChangeViewController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke
- ___85-[ICPasswordChangeViewController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke_2
- ___block_descriptor_32_e28_B32?0"UITextField"8Q16^B24l
- ___block_descriptor_65_e8_32s40s48r56r_e5_v8?0ls32l8r48l8s40l8r56l8
- _keypath_get.124Tm
CStrings:
+ "AIGC=1;src=writingTools"
+ "Change this account’s locked notes password."
+ "NotesUI.PasswordChangeViewController"
+ "NotesUI/PasswordChangeViewController.swift"
+ "NotesUI/PasswordFieldCell.swift"
- "B32@?0@\"UITextField\"8Q16^B24"
- "Change Password"
- "Done"
- "Hint"
- "IMPORTANT: If you forget this password, you won’t be able to view the locked notes that use it."
- "IMPORTANT: If you forget this password, you won’t be able to view your locked notes."
- "New Password"
- "Old Password"
- "Password Hint"
- "Set Password"
- "Verify"
```
