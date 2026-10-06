## ChatKit

> `/System/Library/PrivateFrameworks/ChatKit.framework/ChatKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x2b050` | `0x2c298` | **`+0x1248`** |
| `__DATA_DIRTY.__objc_data` | `0x7780` | `0x6558` | **`-0x1228`** |
| `__TEXT.__text` | `0xbfd4bc` | `0xbfe194` | **`+0xcd8`** |
| `__TEXT.__oslogstring` | `0x545c7` | `0x54847` | **`+0x280`** |
| `__TEXT.__objc_methlist` | `0x7244c` | `0x7268c` | **`+0x240`** |
| `__DATA_CONST.__got` | `0x79d8` | `0x7c08` | **`+0x230`** |
| `__AUTH_CONST.__objc_const` | `0x9c8a0` | `0x9ca78` | **`+0x1d8`** |
| `__TEXT.__eh_frame` | `0x12a08` | `0x12868` | **`-0x1a0`** |
| `__AUTH_CONST.__const` | `0x3e1e8` | `0x3e378` | **`+0x190`** |
| `__DATA_CONST.__objc_selrefs` | `0x36df0` | `0x36f58` | **`+0x168`** |
| `__DATA.__data` | `0x21d70` | `0x21ecc` | **`+0x15c`** |
| `__TEXT.__const` | `0x41d64` | `0x41c74` | **`-0xf0`** |
| `__DATA.__bss` | `0x43f70` | `0x43ff0` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x8e8c` | `0x8ec4` | **`+0x38`** |
| `__AUTH.__data` | `0x157b0` | `0x157d8` | **`+0x28`** |
| `__DATA_CONST.__const` | `0xf2b0` | `0xf288` | **`-0x28`** |
| `__TEXT.__swift_as_entry` | `0x648` | `0x624` | **`-0x24`** |
| `__TEXT.__swift_as_ret` | `0x5d4` | `0x5b0` | **`-0x24`** |
| `__AUTH_CONST.__cfstring` | `0x24380` | `0x243a0` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x540` | `0x520` | **`-0x20`** |
| `__TEXT.__cstring` | `0x3ee4f` | `0x3ee2f` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x127e3` | `0x12803` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x31520` | `0x31540` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x20918` | `0x20900` | **`-0x18`** |
| `__TEXT.__swift_as_cont` | `0xe04` | `0xe1c` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x498c` | `0x499c` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x5f8` | `0x608` | **`+0x10`** |
| `__TEXT.__ustring` | `0x218` | `0x20a` | **`-0xe`** |
| `__TEXT.__swift5_fieldmd` | `0x1095c` | `0x10968` | **`+0xc`** |

### Other Changes

```diff

-1483.100.10.2.4
+1486.100.5.2.1

-  - /System/Library/Frameworks/EnhancedLinkSecurity.framework/EnhancedLinkSecurity

+  - /System/Library/Frameworks/LinkSecurity.framework/LinkSecurity

-  - /System/Library/PrivateFrameworks/Sage.framework/Sage

-  Functions: 74089
-  Symbols:   73194
-  CStrings:  13166
+  Functions: 74142
+  Symbols:   73254
+  CStrings:  13168
Symbols:
+ +[CKAttachmentBalloonView linkMetadataFromMediaObject:withThumbnailPreview:forSnapshot:]
+ +[CKAttachmentBalloonView linkViewThumbnailFromMediaObject:withPreviewImage:forSnapshot:]
+ +[CKSpotlightQueryUtilities normalizedPhoneNumberForSearchString:]
+ +[CKSwipeToReplyRules _balloonCellAtLocation:inTranscriptCollectionView:]
+ +[CKSwipeToReplyRules isPointEligibleForSwipeToReply:inTranscriptCollectionView:]
+ -[CKAnimatedImageMediaObject cacheAndPersistPreview:orientation:]
+ -[CKAttachmentBalloonView setMediaObject:forSnapshot:]
+ -[CKAttachmentBalloonView(CKMediaObject) configureForMediaObject:previewWidth:orientation:forSnapshot:]
+ -[CKAttachmentMessagePartChatItem _scaledGradientSizeForWidth:]
+ -[CKBalloonView isTextSelectionActive]
+ -[CKBrowserDragViewController grabOffsetWithinSticker]
+ -[CKBrowserDragViewController setGrabOffsetWithinSticker:]
+ -[CKChatController _canProcessDismissKeyboardSnapshotRequest]
+ -[CKChatController _canProcessShowKeyboardSnapshotRequest]
+ -[CKChatController isValidatingPayloadForSending]
+ -[CKChatController setIsValidatingPayloadForSending:]
+ -[CKChatControllerCoordinator canProcessDismissKeyboardSnapshotRequestForProposal:]
+ -[CKChatControllerCoordinator canProcessShowKeyboardSnapshotRequestForProposal:]
+ -[CKChatInputController _resetStagedPhotosStateForReplacement]
+ -[CKConversationQueryController _queryStringWithText:]
+ -[CKInvisibleInkGestureRecognizer _finishTrackingTouches]
+ -[CKMessageEntryContentView _updatedPluginPayloadFromResizeNotification:]
+ -[CKMessagesController _isAppCardPresentedOverNewCompose]
+ -[CKMessagesController conversationListControllerContentAvailabilityDidChange:]
+ -[CKMessagesSplitViewCoordinator _contentSizeCategoryDidChange:]
+ -[CKMessagesSplitViewCoordinator _evaluatePrimaryColumnCollapseState]
+ -[CKMessagesSplitViewCoordinator _isAccessibilityContentSizeCategory]
+ -[CKMessagesSplitViewCoordinator _minimumAllowedPrimaryColumnWidth]
+ -[CKMessagesSplitViewCoordinator isPrimaryColumnContentAvailable]
+ -[CKMessagesSplitViewCoordinator setIsPrimaryColumnContentAvailable:]
+ -[CKNavigationController .cxx_destruct]
+ -[CKNavigationController _touchHitsSwipeEligibleTranscriptArea:]
+ -[CKNavigationController forwardingTargetForSelector:]
+ -[CKNavigationController gestureRecognizer:shouldReceiveTouch:]
+ -[CKNavigationController originalContentPopGestureDelegate]
+ -[CKNavigationController respondsToSelector:]
+ -[CKNavigationController setOriginalContentPopGestureDelegate:]
+ -[CKPendingConversation _updateSupportsRepliesForService:withServiceForSendingResult:]
+ -[CKPendingConversation setSupportsReplies:]
+ -[CKPendingConversation supportsReplies]
+ -[CKSendMenuPresentationStyleProvider needsKeyboardDismissalForAppCardPresentationForProposal:]
+ -[CKSendProgressIndicatorChatItem transcriptOrientation]
+ -[CKSendProgressIndicatorChatItem wantsDrawerLayout]
+ -[CKSplitViewControllerHooks didShowNewCompose]
+ -[CKSyndicationContentViewController _setRichContentHidden:]
+ -[CKSyndicationContentViewController _shouldHideRichContent]
+ -[CKTextBalloonView isTextSelectionActive]
+ -[CKTranscriptCollectionView _ck_isInteractiveContentPopGesture:]
+ -[CKTranscriptCollectionView gestureRecognizer:shouldRequireFailureOfGestureRecognizer:]
+ -[CKTranscriptCollectionViewController _shouldBlockUnknownSenderRichLinks]
+ -[CKUIBehavior ckShouldUpdatereplyCountBottomTranscriptSpace]
+ -[CKUIBehavior replyCountBottomTranscriptSpace]
+ GCC_except_table1000
+ GCC_except_table1002
+ GCC_except_table1008
+ GCC_except_table1010
+ GCC_except_table1013
+ GCC_except_table1019
+ GCC_except_table1026
+ GCC_except_table1031
+ GCC_except_table1042
+ GCC_except_table1046
+ GCC_except_table1069
+ GCC_except_table1072
+ GCC_except_table1078
+ GCC_except_table1085
+ GCC_except_table1116
+ GCC_except_table1118
+ GCC_except_table1141
+ GCC_except_table1146
+ GCC_except_table1148
+ GCC_except_table1193
+ GCC_except_table1195
+ GCC_except_table1197
+ GCC_except_table1199
+ GCC_except_table1203
+ GCC_except_table1207
+ GCC_except_table1210
+ GCC_except_table1212
+ GCC_except_table1214
+ GCC_except_table1222
+ GCC_except_table1240
+ GCC_except_table125
+ GCC_except_table1251
+ GCC_except_table1407
+ GCC_except_table194
+ GCC_except_table197
+ GCC_except_table209
+ GCC_except_table235
+ GCC_except_table242
+ GCC_except_table251
+ GCC_except_table257
+ GCC_except_table260
+ GCC_except_table264
+ GCC_except_table290
+ GCC_except_table293
+ GCC_except_table302
+ GCC_except_table305
+ GCC_except_table311
+ GCC_except_table321
+ GCC_except_table322
+ GCC_except_table337
+ GCC_except_table347
+ GCC_except_table369
+ GCC_except_table387
+ GCC_except_table400
+ GCC_except_table404
+ GCC_except_table415
+ GCC_except_table425
+ GCC_except_table437
+ GCC_except_table442
+ GCC_except_table450
+ GCC_except_table455
+ GCC_except_table459
+ GCC_except_table468
+ GCC_except_table471
+ GCC_except_table475
+ GCC_except_table477
+ GCC_except_table479
+ GCC_except_table490
+ GCC_except_table494
+ GCC_except_table505
+ GCC_except_table507
+ GCC_except_table513
+ GCC_except_table521
+ GCC_except_table523
+ GCC_except_table530
+ GCC_except_table532
+ GCC_except_table534
+ GCC_except_table544
+ GCC_except_table550
+ GCC_except_table567
+ GCC_except_table570
+ GCC_except_table571
+ GCC_except_table589
+ GCC_except_table595
+ GCC_except_table596
+ GCC_except_table599
+ GCC_except_table649
+ GCC_except_table661
+ GCC_except_table667
+ GCC_except_table673
+ GCC_except_table678
+ GCC_except_table682
+ GCC_except_table686
+ GCC_except_table687
+ GCC_except_table691
+ GCC_except_table695
+ GCC_except_table715
+ GCC_except_table720
+ GCC_except_table721
+ GCC_except_table741
+ GCC_except_table754
+ GCC_except_table758
+ GCC_except_table770
+ GCC_except_table777
+ GCC_except_table778
+ GCC_except_table783
+ GCC_except_table823
+ GCC_except_table824
+ GCC_except_table828
+ GCC_except_table854
+ GCC_except_table863
+ GCC_except_table870
+ GCC_except_table879
+ GCC_except_table890
+ GCC_except_table893
+ GCC_except_table895
+ GCC_except_table918
+ GCC_except_table921
+ GCC_except_table938
+ GCC_except_table942
+ GCC_except_table945
+ GCC_except_table954
+ GCC_except_table958
+ GCC_except_table966
+ GCC_except_table968
+ GCC_except_table972
+ GCC_except_table975
+ GCC_except_table980
+ GCC_except_table982
+ GCC_except_table986
+ GCC_except_table992
+ GCC_except_table994
+ GCC_except_table998
+ _CKBalloonViewUtilitiesLog.log
+ _CKBalloonViewUtilitiesLog.onceToken
+ _CKMessageSpamFilteringEnabledUnderFirstUnlock.sLastLoggedSpamFilteringValue
+ _OBJC_CLASS_$_LSLinkSecurityManager
+ _OBJC_IVAR_$_CKBrowserDragViewController._grabOffsetWithinSticker
+ _OBJC_IVAR_$_CKChatController._isValidatingPayloadForSending
+ _OBJC_IVAR_$_CKMessagesSplitViewCoordinator._isPrimaryColumnContentAvailable
+ _OBJC_IVAR_$_CKNavigationController._originalContentPopGestureDelegate
+ _OBJC_IVAR_$_CKPendingConversation._supportsReplies
+ _UTITypes._types
+ __OBJC_$_INSTANCE_METHODS_CKTapbackPickerCollectionViewLayout(ChatKit)
+ __OBJC_$_INSTANCE_VARIABLES_CKNavigationController
+ __OBJC_$_PROP_LIST_CKNavigationController
+ __OBJC_CLASS_PROTOCOLS_$_CKNavigationController
+ __UIClamp
+ ___30+[CKImageMediaObject UTITypes]_block_invoke_2
+ ___66+[CKSpotlightQueryUtilities normalizedPhoneNumberForSearchString:]_block_invoke
+ ___66-[CKFullScreenBalloonViewControllerPhone performInitialAnimations]_block_invoke_2
+ ___89+[CKAttachmentBalloonView linkViewThumbnailFromMediaObject:withPreviewImage:forSnapshot:]_block_invoke
+ ___89+[CKAttachmentBalloonView linkViewThumbnailFromMediaObject:withPreviewImage:forSnapshot:]_block_invoke_2
+ ___CKBalloonViewUtilitiesLog_block_invoke
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e20_v24?0q8"NSError"16ls32l8s64l8s40l8s48l8s56l8
+ ___swift_closure_destructor.200Tm
+ ___swift_closure_destructor.36Tm
+ ___swift_closure_destructor.42Tm
+ ___swift_closure_destructor.80Tm
+ ___swift_closure_destructor.89Tm
+ _normalizedPhoneNumberForSearchString:.nonDigitCharacterSet
+ _normalizedPhoneNumberForSearchString:.onceToken
+ _normalizedPhoneNumberForSearchString:.phoneFormattingCharacterSet
+ _replyCountBottomTranscriptSpace.sBehavior
+ _replyCountBottomTranscriptSpace.sContentSizeCategory_replyCountBottomTranscriptSpace
+ _replyCountBottomTranscriptSpace.sCustomTextFontName_replyCountBottomTranscriptSpace
+ _replyCountBottomTranscriptSpace.sCustomTextFontSize_replyCountBottomTranscriptSpace
+ _replyCountBottomTranscriptSpace.sIsBoldTextEnabled_replyCountBottomTranscriptSpace
+ _replyCountBottomTranscriptSpace.sTextFontSize_replyCountBottomTranscriptSpace
+ _swift_task_localValuePop
+ _swift_task_localValuePush
+ _symbolic SbIegy_Sg
- +[CKCommSafetyAnalytics recordContextMenuButtonTappedWithContentType:subContentType:direction:options:isBlurred:identifier:]
- +[CKCommSafetyAnalytics recordObscuredViewRemovedWithIdentifier:]
- -[CKAttachmentMessagePartChatItem _scaledGradientSizeForHeight:]
- -[CKMessageEntryContentView _updatedPluginPayloadFromNotification:]
- -[CKMessageEntryView _shouldUseDarkAppearanceFromTraitCollection:]
- -[CKTranscriptCollectionViewController cachedEmojiResponses]
- -[CKTranscriptCollectionViewController setCachedEmojiResponses:]
- GCC_except_table1001
- GCC_except_table1006
- GCC_except_table1009
- GCC_except_table1012
- GCC_except_table1018
- GCC_except_table1024
- GCC_except_table1028
- GCC_except_table1035
- GCC_except_table1041
- GCC_except_table1045
- GCC_except_table1068
- GCC_except_table1071
- GCC_except_table1077
- GCC_except_table1084
- GCC_except_table1115
- GCC_except_table1117
- GCC_except_table1140
- GCC_except_table1145
- GCC_except_table1147
- GCC_except_table1192
- GCC_except_table1194
- GCC_except_table1196
- GCC_except_table1198
- GCC_except_table1201
- GCC_except_table1206
- GCC_except_table1208
- GCC_except_table1211
- GCC_except_table1213
- GCC_except_table1221
- GCC_except_table1239
- GCC_except_table1250
- GCC_except_table1405
- GCC_except_table144
- GCC_except_table210
- GCC_except_table240
- GCC_except_table243
- GCC_except_table249
- GCC_except_table258
- GCC_except_table267
- GCC_except_table270
- GCC_except_table273
- GCC_except_table292
- GCC_except_table298
- GCC_except_table304
- GCC_except_table309
- GCC_except_table315
- GCC_except_table319
- GCC_except_table326
- GCC_except_table336
- GCC_except_table345
- GCC_except_table354
- GCC_except_table367
- GCC_except_table370
- GCC_except_table385
- GCC_except_table403
- GCC_except_table405
- GCC_except_table407
- GCC_except_table416
- GCC_except_table438
- GCC_except_table443
- GCC_except_table452
- GCC_except_table456
- GCC_except_table470
- GCC_except_table476
- GCC_except_table478
- GCC_except_table481
- GCC_except_table492
- GCC_except_table506
- GCC_except_table511
- GCC_except_table512
- GCC_except_table515
- GCC_except_table525
- GCC_except_table529
- GCC_except_table537
- GCC_except_table539
- GCC_except_table543
- GCC_except_table545
- GCC_except_table551
- GCC_except_table565
- GCC_except_table568
- GCC_except_table569
- GCC_except_table587
- GCC_except_table593
- GCC_except_table594
- GCC_except_table597
- GCC_except_table611
- GCC_except_table614
- GCC_except_table620
- GCC_except_table630
- GCC_except_table631
- GCC_except_table647
- GCC_except_table650
- GCC_except_table655
- GCC_except_table658
- GCC_except_table659
- GCC_except_table676
- GCC_except_table680
- GCC_except_table684
- GCC_except_table685
- GCC_except_table689
- GCC_except_table693
- GCC_except_table705
- GCC_except_table710
- GCC_except_table711
- GCC_except_table718
- GCC_except_table732
- GCC_except_table733
- GCC_except_table750
- GCC_except_table756
- GCC_except_table768
- GCC_except_table775
- GCC_except_table779
- GCC_except_table819
- GCC_except_table822
- GCC_except_table826
- GCC_except_table852
- GCC_except_table862
- GCC_except_table868
- GCC_except_table878
- GCC_except_table889
- GCC_except_table892
- GCC_except_table894
- GCC_except_table917
- GCC_except_table920
- GCC_except_table937
- GCC_except_table940
- GCC_except_table944
- GCC_except_table952
- GCC_except_table956
- GCC_except_table965
- GCC_except_table967
- GCC_except_table971
- GCC_except_table974
- GCC_except_table979
- GCC_except_table981
- GCC_except_table984
- GCC_except_table989
- GCC_except_table993
- GCC_except_table996
- GCC_except_table999
- _OBJC_CLASS_$_IMEnhancedLinkSecurityManager
- _OBJC_IVAR_$_CKTranscriptCollectionViewController._cachedEmojiResponses
- __INSTANCE_METHODS_CKTapbackPickerCollectionViewLayout
- ___114-[CKTranscriptCollectionViewController _addChatItemsToInputContextHistory:signalingResponseContextChangeIfNeeded:]_block_invoke
- ___44-[CKImageMediaObject pasteboardItemProvider]_block_invoke_3
- ___51-[CKChatController _editingToolbarSelectedForward:]_block_invoke
- ___77+[CKAttachmentBalloonView linkViewThumbnailFromMediaObject:withPreviewImage:]_block_invoke
- ___77+[CKAttachmentBalloonView linkViewThumbnailFromMediaObject:withPreviewImage:]_block_invoke_2
- ___block_descriptor_40_e8_32s_e34_v16?0"UIActivityViewController"8ls32l8
- ___block_descriptor_64_e8_32s40s48s56bs_e20_v24?0q8"NSError"16ls56l8s32l8s40l8s48l8
- ___swift_closure_destructor.196Tm
- ___swift_closure_destructor.38Tm
- ___swift_closure_destructor.76Tm
- ___swift_closure_destructor.84Tm
- ___swift_closure_destructor.85Tm
- _symbolic _____ 4Sage21TextCompositionClientC
- _symbolic _____ySSSaySSGG s18_DictionaryStorageC
CStrings:
+ "()-.+ /"
+ "Already validating a payload for sending. Dropping duplicate send."
+ "Balloon view %p double tap suppressed due to active text selection"
+ "Balloon view %p long press suppressed due to active text selection"
+ "CKBalloonViewReuse: skipping push, app is backgrounded (class=%@)"
+ "Could not build live photo bundle for transfer with GUID %@"
+ "Determined spatial state = %{BOOL}d for %p"
+ "ExtensionIdentifiers"
+ "Failed to delete file at URL %@ with error %@"
+ "Failed to move preview from temporary URL %@ to target URL %@ with error: %@"
+ "GUID is nil, unable to return EntityIdentifier for CKTranscriptCollectionViewController item of type %s at indexPath: %s"
+ "Generating gradient for thumbnail with expectedFilename %@"
+ "IMChatItem is nil, unable to return EntityIdentifier for CKTranscriptCollectionViewController item of type %s at indexPath: %s"
+ "Kicking preview reload, we have a preflight preview in-memory and a HQ preview on disk that has not been loaded yet"
+ "Non-animated transcript update via full reloadData — chatItems: %@, regenerateOrReloadOnly: %{BOOL}d, chatGUID: %@"
+ "Refusing to cache invalid size (height: %f, fittingWidth: %f) for chatItem <%@ %@>."
+ "Returning EntityIdentifier for CKTranscriptCollectionViewController item of type %s and %s at indexPath: %s"
+ "com.apple.DEC.AppPredictionInternal.DiagnosticExtension"
+ "configureForTranscriptPlugin guid=%@ bundle=%@ mayReparentPluginViews=%{BOOL}d: plugin view %p is parented in another balloon %p; setPluginView will move it here"
+ "public.font"
+ "savePreview no-op: preview is nil for transferGUID=%@ URL=%@"
+ "willTransitionToTraitCollection: dismissing app card presented over new compose before collapse (rdar://178594118)"
+ "\u2009"
- "%@\u00a0%@\u2009%@"
- "A plugin was updated without a staging identifier! Programming error."
- "Beginning emoji smart replies request for guids of count: %ld"
- "CommunicationDetails"
- "Consolidating smart Tapback suggestions for chatItem guid: %s"
- "Could not determine messageGUID. Returning no results for smart emoji responses."
- "Determined spatial state = %@ for %p"
- "Failed creating item provider for live photo on transfer with GUID %@"
- "Found error requesting smartEmojiResponses: %@"
- "Merged emoji smart replies request for guids of count: %ld"
- "PLASThumbnails"
- "ProcessIdentifier"
- "Refusing to cache invalid height (%f) for chatItem <%@ %@>."
- "Returning EntityIdentifier for CKTranscriptCollectionViewController item at indexPath: %s"
- "Suggesting %ld from smart replies"
- "Swipe to reply is active on view: %@, updating with reply layout offset: %f"
- "Using chat display name."
- "Withholding chat display name because shouldDisplayGroupIdentity == false."
- "[Tapbacks] showTapbackPicker: during double-tap"
- "com.apple.CommunicationDetails"
- "v16@?0@\"UIActivityViewController\"8"
```
