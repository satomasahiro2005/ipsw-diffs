## FeedbackCore

> `/System/Library/PrivateFrameworks/FeedbackCore.framework/FeedbackCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14213c` | `0x145d6c` | **`+0x3c30`** |
| `__TEXT.__oslogstring` | `0xaba6` | `0xafe6` | **`+0x440`** |
| `__AUTH_CONST.__const` | `0x4900` | `0x4b38` | **`+0x238`** |
| `__DATA.__bss` | `0x31a8` | `0x33a8` | **`+0x200`** |
| `__AUTH_CONST.__objc_const` | `0x1d330` | `0x1d4a8` | **`+0x178`** |
| `__AUTH.__objc_data` | `0x4e78` | `0x4fe0` | **`+0x168`** |
| `__TEXT.__const` | `0x37e4` | `0x3934` | **`+0x150`** |
| `__TEXT.__objc_methlist` | `0xb6b4` | `0xb7ec` | **`+0x138`** |
| `__TEXT.__unwind_info` | `0x4bc0` | `0x4ce0` | **`+0x120`** |
| `__DATA_CONST.__objc_selrefs` | `0x7710` | `0x77b8` | **`+0xa8`** |
| `__TEXT.__constg_swiftt` | `0x1df0` | `0x1e90` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x3dbe` | `0x3e56` | **`+0x98`** |
| `__DATA.__data` | `0x2d40` | `0x2dc0` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x41e0` | `0x4258` | **`+0x78`** |
| `__TEXT.__cstring` | `0xa298` | `0xa2f8` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0xbd0` | `0xc30` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0xd3c` | `0xd98` | **`+0x5c`** |
| `__TEXT.__eh_frame` | `0x12c0` | `0x1308` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x9140` | `0x9180` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0xdd8` | `0xe0c` | **`+0x34`** |
| `__TEXT.__swift5_assocty` | `0x288` | `0x2b8` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x15c8` | `0x15f0` | **`+0x28`** |
| `__AUTH.__data` | `0xe90` | `0xeb0` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0xc8` | `0xdc` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x530` | `0x540` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x164` | `0x174` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x714` | `0x71c` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x11e8` | `0x11f0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x144` | `0x14c` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__ustring`

### Other Changes

```diff

-227.0.0.0.0
+229.0.0.0.0

-  Functions: 7558
-  Symbols:   7364
-  CStrings:  2603
+  Functions: 7645
+  Symbols:   7404
+  CStrings:  2621
Symbols:
+ +[FBKResolverAppVersion name]
+ -[FBKAnnotatedFileBrowserTableViewController _refreshAfterDeletion]
+ -[FBKAnnotatedFileBrowserTableViewController _urlFileDeletionEnabled]
+ -[FBKAnnotatedFileBrowserTableViewController tableView:canEditRowAtIndexPath:]
+ -[FBKAnnotatedFileBrowserTableViewController tableView:trailingSwipeActionsConfigurationForRowAtIndexPath:]
+ -[FBKAttachment updateBackingFileURL:updateDisplayName:]
+ -[FBKAttachmentManager fileDeletionWatcherStopped]
+ -[FBKAttachmentManager setFileDeletionWatcherStopped:]
+ -[FBKBugFormTableViewController checkAnnotatedContentConsent:andContinue:]
+ -[FBKBugFormTableViewController checkPresubmissionLegalText:andContinue:]
+ -[FBKBugFormTableViewController handlePresubmissionChecks:sender:]
+ -[FBKBugFormTableViewController showMissingAnswersWithSender:andContinue:]
+ -[FBKQuestionAnswerCell errorArrowLeadingConstraint]
+ -[FBKQuestionAnswerCell setErrorArrowLeadingConstraint:]
+ -[FBKResolverAppVersion expectedArguments]
+ -[FBKResolverAppVersion run]
+ GCC_except_table10
+ GCC_except_table104
+ GCC_except_table105
+ GCC_except_table11
+ GCC_except_table123
+ GCC_except_table139
+ GCC_except_table15
+ GCC_except_table189
+ _OBJC_CLASS_$_FBKResolverAppVersion
+ _OBJC_CLASS_$_LSApplicationRecord
+ _OBJC_CLASS_$__TtC12FeedbackCore31FBKPresubmissionCheckController
+ _OBJC_IVAR_$_FBKAttachmentManager._fileDeletionWatcherStopped
+ _OBJC_IVAR_$_FBKQuestionAnswerCell._errorArrowLeadingConstraint
+ _OBJC_METACLASS_$_FBKResolverAppVersion
+ _OBJC_METACLASS_$__TtC12FeedbackCore31FBKPresubmissionCheckController
+ __DATA__TtC12FeedbackCore31FBKPresubmissionCheckController
+ __INSTANCE_METHODS__TtC12FeedbackCore31FBKPresubmissionCheckController
+ __IVARS__TtC12FeedbackCore31FBKPresubmissionCheckController
+ __METACLASS_DATA__TtC12FeedbackCore31FBKPresubmissionCheckController
+ __OBJC_$_CLASS_METHODS_FBKResolverAppVersion
+ __OBJC_$_INSTANCE_METHODS_FBKResolverAppVersion(FeedbackCore)
+ __OBJC_CLASS_RO_$_FBKResolverAppVersion
+ __OBJC_METACLASS_RO_$_FBKResolverAppVersion
+ ___107-[FBKAnnotatedFileBrowserTableViewController tableView:trailingSwipeActionsConfigurationForRowAtIndexPath:]_block_invoke
+ ___66-[FBKBugFormTableViewController handlePresubmissionChecks:sender:]_block_invoke
+ ___66-[FBKBugFormTableViewController handlePresubmissionChecks:sender:]_block_invoke_2
+ ___73-[FBKBugFormTableViewController checkPresubmissionLegalText:andContinue:]_block_invoke
+ ___73-[FBKBugFormTableViewController checkPresubmissionLegalText:andContinue:]_block_invoke_2
+ ___73-[FBKBugFormTableViewController checkPresubmissionLegalText:andContinue:]_block_invoke_3
+ ___74-[FBKBugFormTableViewController checkAnnotatedContentConsent:andContinue:]_block_invoke
+ ___74-[FBKBugFormTableViewController checkAnnotatedContentConsent:andContinue:]_block_invoke_2
+ ___80-[FBKAnnotatedFileBrowserTableViewController tableView:didSelectRowAtIndexPath:]_block_invoke
+ ___80-[FBKAnnotatedFileBrowserTableViewController tableView:didSelectRowAtIndexPath:]_block_invoke_2
+ ___80-[FBKAnnotatedFileBrowserTableViewController tableView:didSelectRowAtIndexPath:]_block_invoke_3
+ ___block_descriptor_48_e8_32s40w_e57_v16?0"_TtC12FeedbackCore27FBKEmbeddedAttachmentViewer"8ls32l8w40l8
+ ___block_descriptor_48_e8_32s40w_e8_v12?0B8ls32l8w40l8
+ ___block_descriptor_49_e8_32s40w_e5_v8?0ls32l8w40l8
+ ___block_descriptor_64_e8_32s40s48w_e8_v12?0B8ls32l8w48l8s40l8
+ _associated conformance 12FeedbackCore25FBKPresubmissionCheckStepOSHAASQ
+ _associated conformance 12FeedbackCore25FBKPresubmissionCheckStepOs12CaseIterableAA8AllCasessADP_Sl
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA6HStackVyAA05TupleD0VyACyACyACyAA5ImageVAA25_ForegroundStyleModifier2VyAA5ColorVAMGGAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGAA14_PaddingLayoutVG_AA6VStackVyAGyAA4TextVSg_A2_QPGGQPGGAA010_FlexFrameR0VGAA4ViewHPA6_AAA10_HPyHC_A8_AA0wO0HPyHCHC
+ _symbolic $ss12CaseIterableP
+ _symbolic Say_____G 12FeedbackCore25FBKPresubmissionCheckStepO
+ _symbolic SbIegy_Sg
+ _symbolic Shy_____G 12FeedbackCore25FBKPresubmissionCheckStepO
+ _symbolic So18UIContextualActionCSo6UIViewC_____IeyBy_IeyByyy_ 10ObjectiveC8ObjCBoolV
+ _symbolic _____ 12FeedbackCore25FBKPresubmissionCheckStepO
+ _symbolic _____ 12FeedbackCore31FBKPresubmissionCheckControllerC
+ _symbolic _____y_____G s11_SetStorageC 12FeedbackCore25FBKPresubmissionCheckStepO
+ _symbolic _____y_____y_____yAAyAAyAAy__________y_____AFGG_____y_____SgGG_____G______yACy_____Sg_ARQPGGQPGG_____G 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA25_ForegroundStyleModifier2V AA5ColorV AA30_EnvironmentKeyWritingModifierV AA4FontV AA14_PaddingLayoutV AA6VStackV AA4TextV AA010_FlexFrameR0V
+ _symbolic _____y_____y_____yACyACy__________y_____AFGG_____y_____SgGG_____G______yABy_____Sg_ARQPGGQPGG 7SwiftUI6HStackV AA12TupleContentV AA08ModifiedE0V AA5ImageV AA25_ForegroundStyleModifier2V AA5ColorV AA30_EnvironmentKeyWritingModifierV AA4FontV AA14_PaddingLayoutV AA6VStackV AA4TextV
- -[FBKBugFormTableViewController checkAnnotatedContentConsent:hasShownPresubmissionConsent:andContinue:]
- -[FBKBugFormTableViewController checkPresubmissionLegalText:presentedDEConsent:andContinue:]
- -[FBKBugFormTableViewController showMissingAnswersWithResult:sender:andContinue:]
- GCC_except_table100
- GCC_except_table101
- GCC_except_table108
- GCC_except_table109
- GCC_except_table126
- GCC_except_table142
- GCC_except_table192
- GCC_except_table97
- GCC_except_table99
- ___103-[FBKBugFormTableViewController checkAnnotatedContentConsent:hasShownPresubmissionConsent:andContinue:]_block_invoke
- ___103-[FBKBugFormTableViewController checkAnnotatedContentConsent:hasShownPresubmissionConsent:andContinue:]_block_invoke_2
- ___49-[FBKBugFormTableViewController beginSubmission:]_block_invoke
- ___49-[FBKBugFormTableViewController beginSubmission:]_block_invoke_2
- ___49-[FBKBugFormTableViewController beginSubmission:]_block_invoke_3
- ___49-[FBKBugFormTableViewController beginSubmission:]_block_invoke_4
- ___49-[FBKBugFormTableViewController beginSubmission:]_block_invoke_5
- ___49-[FBKBugFormTableViewController beginSubmission:]_block_invoke_6
- ___92-[FBKBugFormTableViewController checkPresubmissionLegalText:presentedDEConsent:andContinue:]_block_invoke
- ___92-[FBKBugFormTableViewController checkPresubmissionLegalText:presentedDEConsent:andContinue:]_block_invoke_2
- ___92-[FBKBugFormTableViewController checkPresubmissionLegalText:presentedDEConsent:andContinue:]_block_invoke_3
- ___block_descriptor_48_e8_32s40w_e8_v12?0B8lw40l8s32l8
- _get_witness_table 7SwiftUI15ModifiedContentVyAA6VStackVyAA05TupleD0VyACyACyACyAA5ImageVAA25_ForegroundStyleModifier2VyAA5ColorVAMGGAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGAA14_PaddingLayoutVG_AEyAGyAA4TextVSg_A0_QPGGQPGGAA010_FlexFrameR0VGAA4ViewHPA4_AAA8_HPyHC_A6_AA0vO0HPyHCHC
- _symbolic _____y_____y_____yAAyAAyAAy__________y_____AFGG_____y_____SgGG_____G_AByACy_____Sg_AQQPGGQPGG_____G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA5ImageV AA25_ForegroundStyleModifier2V AA5ColorV AA30_EnvironmentKeyWritingModifierV AA4FontV AA14_PaddingLayoutV AA4TextV AA010_FlexFrameR0V
- _symbolic _____y_____y_____yACyACy__________y_____AFGG_____y_____SgGG_____G_AAyABy_____Sg_AQQPGGQPGG 7SwiftUI6VStackV AA12TupleContentV AA08ModifiedE0V AA5ImageV AA25_ForegroundStyleModifier2V AA5ColorV AA30_EnvironmentKeyWritingModifierV AA4FontV AA14_PaddingLayoutV AA4TextV
CStrings:
+ "-[FBKBugFormTableViewController checkAnnotatedContentConsent:andContinue:]"
+ "-[FBKBugFormTableViewController checkPresubmissionLegalText:andContinue:]"
+ "-[FBKBugFormTableViewController showMissingAnswersWithSender:andContinue:]"
+ "Advancing to step [%{public}s]"
+ "FBKContentItem [%ld] -currentUserIsStakeholder: user.ID is not an NSNumber (class=%{public}@); returning NO."
+ "FBKContentItem [%ld] -needsActionFromMe: ID has unexpected non-NSNumber type (assignee.ID class=%{public}@, user.ID class=%{public}@); falling back to NO."
+ "Failed to remove file at %{public}@: %{public}@"
+ "Ignoring Close for FR [%i] because a submission is in progress"
+ "Ignoring out-of-order completion for step [%{public}s], current step is [%{public}s]"
+ "LSApplicationRecord has nil bundle version for bundleId: %{public}s. Returning nil."
+ "Marking step [%{public}s] complete, didShowAlert: [%{bool,public}d]"
+ "Out of bounds step, returning final submission step"
+ "Passed in bundle identifier is an empty string, returning nil"
+ "Passed in bundle identifier is nil, returning nil"
+ "Querying for an app record threw an exception while fetching record for bundleId: %{public}s. This is likely because the app is not installed. Error: %{public}@"
+ "Received version %{public}s for: %{public}s"
+ "Skipping inapplicable step [%{public}s]"
+ "Swiped to remove url attachment [%{public}@]"
+ "app-version-resolver"
+ "app_version"
+ "enableUrlItemDeletion"
+ "presubmission-check"
- "-[FBKBugFormTableViewController checkAnnotatedContentConsent:hasShownPresubmissionConsent:andContinue:]"
- "-[FBKBugFormTableViewController checkPresubmissionLegalText:presentedDEConsent:andContinue:]"
- "-[FBKBugFormTableViewController showMissingAnswersWithResult:sender:andContinue:]"
- "inlineFormWarning check called before attachments exist"
```
