## ChatKit

> `/System/Library/PrivateFrameworks/ChatKit.framework/ChatKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbe6bdc` | `0xbfd4bc` | **`+0x168e0`** |
| `__TEXT.__swift5_typeref` | `0x459f0` | `0x47f94` | **`+0x25a4`** |
| `__TEXT.__oslogstring` | `0x53395` | `0x545c7` | **`+0x1232`** |
| `__TEXT.__unwind_info` | `0x30768` | `0x31520` | **`+0xdb8`** |
| `__TEXT.__const` | `0x411d4` | `0x41d64` | **`+0xb90`** |
| `__DATA.__bss` | `0x434c0` | `0x43f70` | **`+0xab0`** |
| `__AUTH_CONST.__const` | `0x3d800` | `0x3e1e8` | **`+0x9e8`** |
| `__TEXT.__cstring` | `0x3e5de` | `0x3ee4f` | **`+0x871`** |
| `__TEXT.__eh_frame` | `0x12540` | `0x12a08` | **`+0x4c8`** |
| `__AUTH_CONST.__cfstring` | `0x23ec0` | `0x24380` | **`+0x4c0`** |
| `__AUTH_CONST.__objc_const` | `0x9cd50` | `0x9c8a0` | **`-0x4b0`** |
| `__DATA.__data` | `0x218c8` | `0x21d70` | **`+0x4a8`** |
| `__DATA_DIRTY.__objc_data` | `0x7af8` | `0x7780` | **`-0x378`** |
| `__AUTH.__objc_data` | `0x2b2b8` | `0x2b050` | **`-0x268`** |
| `__TEXT.__swift5_capture` | `0x8c58` | `0x8e8c` | **`+0x234`** |
| `__TEXT.__gcc_except_tab` | `0x206ec` | `0x20918` | **`+0x22c`** |
| `__TEXT.__objc_methlist` | `0x72644` | `0x7244c` | **`-0x1f8`** |
| `__TEXT.__swift5_reflstr` | `0x12964` | `0x127e3` | **`-0x181`** |
| `__TEXT.__swift5_assocty` | `0x4860` | `0x49c8` | **`+0x168`** |
| `__AUTH_CONST.__auth_got` | `0x69c8` | `0x6b10` | **`+0x148`** |
| `__DATA_CONST.__objc_selrefs` | `0x36d08` | `0x36df0` | **`+0xe8`** |
| `__DATA_CONST.__got` | `0x7908` | `0x79d8` | **`+0xd0`** |
| `__TEXT.__constg_swiftt` | `0x1d998` | `0x1d8dc` | **`-0xbc`** |
| `__AUTH.__data` | `0x15700` | `0x157b0` | **`+0xb0`** |
| `__TEXT.__swift5_fieldmd` | `0x108ac` | `0x1095c` | **`+0xb0`** |
| `__DATA_DIRTY.__data` | `0x678` | `0x5f8` | **`-0x80`** |
| `__TEXT.__swift5_proto` | `0x1c44` | `0x1c94` | **`+0x50`** |
| `__DATA.__common` | `0x1548` | `0x1590` | **`+0x48`** |
| `__AUTH_CONST.__objc_arrayobj` | `0xe10` | `0xde0` | **`-0x30`** |
| `__DATA_CONST.__objc_arraydata` | `0xf00` | `0xed0` | **`-0x30`** |
| `__TEXT.__swift_as_cont` | `0xdd4` | `0xe04` | **`+0x30`** |
| `__DATA_CONST.__objc_classlist` | `0x2ff0` | `0x2fd0` | **`-0x20`** |
| `__DATA_CONST.__const` | `0xf298` | `0xf2b0` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x13c0` | `0x13a8` | **`-0x18`** |
| `__TEXT.__swift5_types` | `0x1420` | `0x1434` | **`+0x14`** |
| `__DATA_CONST.__objc_protorefs` | `0x560` | `0x550` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x63c` | `0x648` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x5c8` | `0x5d4` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x4984` | `0x498c` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `0x560` | `0x568` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x19d0` | `0x19d8` | **`+0x8`** |

### Other Changes

```diff

-1481.100.29.2.9
+1483.100.10.2.4

+  - /System/Library/PrivateFrameworks/AppProtection.framework/AppProtection

+  - /System/Library/PrivateFrameworks/OSEligibility.framework/OSEligibility

+  - /usr/lib/swift/libswiftRegexBuilder.dylib

-  Functions: 73970
-  Symbols:   72977
-  CStrings:  13050
+  Functions: 74089
+  Symbols:   73194
+  CStrings:  13166
Symbols:
+ +[CABasicAnimation(SendAnimation) ck_positionXAnimationWithBeginTime:initialPositionX:finalPositionX:delegate:]
+ +[CABasicAnimation(SendAnimation) ck_positionYAnimationWithBeginTime:initialPositionY:finalPositionY:delegate:]
+ +[CKBalloonChatItem(MaxWidthComputation) resultingMaxWidthWithBalloonMaxWidth:fullMaxWidth:transcriptTraitCollection:]
+ +[CKChatItem resultingMaxWidthWithBalloonMaxWidth:fullMaxWidth:transcriptTraitCollection:]
+ +[CKChatItem(CKChatItems) chatItemWithIMChatItem:balloonMaxWidth:fullMaxWidth:transcriptTraitCollection:overlayLayout:]
+ +[CKTranscriptPluginChatItem(MaxWidthComputation) resultingMaxWidthWithBalloonMaxWidth:fullMaxWidth:transcriptTraitCollection:]
+ +[_CKStickerEntry entriesFromChatItem:]
+ -[CKAttachmentMessagePartChatItem _scaledGradientSizeForHeight:]
+ -[CKBackgroundGalleryFetchRequest initWithPreferredSuggestionCount:shouldBypassPosterGalleryCache:extensionIdentifiers:fallbackExtensionIdentifiers:]
+ -[CKBackgroundGalleryFetchRequest setShouldBypassPosterGalleryCache:]
+ -[CKBackgroundGalleryFetchRequest shouldBypassPosterGalleryCache]
+ -[CKBrowserItemPayload isScreenshot]
+ -[CKBrowserItemPayload preflightMediaType]
+ -[CKBrowserViewController presentationReadyHandler]
+ -[CKBrowserViewController setPresentationReadyHandler:]
+ -[CKChatController _updateNavBarMinimizeBehavior]
+ -[CKChatController didPresentDetailsInPortrait]
+ -[CKChatController entryViewWasFirstResponderBeforeDetailsPresentation]
+ -[CKChatController setDidPresentDetailsInPortrait:]
+ -[CKChatController setEntryViewWasFirstResponderBeforeDetailsPresentation:]
+ -[CKChatController(CKChatController_Stickers) saveStickerFromChatItem:]
+ -[CKChatController(CKChatController_Stickers) saveStickers:]
+ -[CKChatController(ClickyOrbConformance) _saveStickersActionForChatItem:]
+ -[CKChatController(ClickyOrbConformance) _stickerInfoActionForChatItem:]
+ -[CKChatController(SendAnimation) _makeThrowBalloonsForSendAnimationInContainerView:forSendingMessages:shouldUseQuickReplySourceRect:quickReplySourceRect:quickReplySnapshotView:audioMessageSourceRect:audioRecordingPillViewSnapshot:]
+ -[CKChatController(SendAnimation) _shouldHideNavigationBarForSendAnimationContext:manager:]
+ -[CKChatController(SendAnimation) _throwBalloonAttributesForSendAnimationWithShouldUseQuickReplySourceRect:quickReplySourceRect:isRunningPhotosPlugin:chatItem:isPhotosExtensionMediaPayload:pluginChatItemCounterInOut:containerView:isChatItemFromShelf:isLastChatItem:currentBalloonOriginInOut:quickReplySnapshotView:]
+ -[CKChatController(SendAnimation) throwAnimationContainerInsertBelowView:]
+ -[CKChatControllerDummyAnimator __beginThrowAnimationWithThrowBalloonViewAttributesCollection:framesOfAddedChatItems:entryViewSize:]
+ -[CKChatInputController generatePreflightThumbnailFillToSize:assetPxSize:scale:thumbnail:isScreenshot:mediaType:]
+ -[CKChatItem updateWithBalloonMaxWidth:fullMaxWidth:transcriptTraitCollection:wantsOverlayLayout:metricsProvider:getDidUpdate:]
+ -[CKChatSceneDelegate sendMenuPresentationShouldIgnoreKeyboardNotifications:]
+ -[CKComposeChatController _contentInsetForSendAnimation]
+ -[CKComposeChatController shouldSetFirstResponderWhenPresented]
+ -[CKComposeChatController throwAnimationManagerTopHeaderHeight:]
+ -[CKConversationListCollectionViewController(RecentlyDeleted) removeRecentlyDeletedNotifitcationObservers]
+ -[CKCoreChatController transcriptCollectionViewController:viewedCommSafetyAssociatedItemsWithIndexPath:updatedSensitivityAnalysesByTransferGUID:]
+ -[CKCoreChatController transcriptCollectionViewController:viewedCommSafetyItemWithIndexPath:updatedSensitivityAnalysesByTransferGUID:]
+ -[CKCoreChatController(UserSafety) presentCommSafetyInterventionIfNecessaryForSticker:willPresentHandler:sendHandler:]
+ -[CKDefaultPluginEntryViewController _pluginContentViewController]
+ -[CKFullScreenCardAppViewController presentationReadyHandler]
+ -[CKFullScreenCardAppViewController setPresentationReadyHandler:]
+ -[CKImpactEffectManager placesContainerViewInWindow]
+ -[CKImpactEffectManager setPlacesContainerViewInWindow:]
+ -[CKLocationMediaObject shouldShowViewer]
+ -[CKMediaObject preflightAssetSize]
+ -[CKMediaObject(Display) _isNonPreflightPreview]
+ -[CKMediaObject(Display) _previewCachesFileURLWithOrientation:extension:generateIntermediaries:preflightPreviewPath:transferGUID:]
+ -[CKMessageEntryRichTextView ck_disallowBecomeFirstResponder]
+ -[CKMessageEntryRichTextView setCk_disallowBecomeFirstResponder:]
+ -[CKMessagesController forcedSupportedInterfaceOrientations]
+ -[CKMessagesController sendMenuPresentationShouldIgnoreKeyboardNotifications:]
+ -[CKObscurableBalloonView didBlockContacts:]
+ -[CKObscurableBalloonView didLeaveConversation:]
+ -[CKOrganicImageBalloonView isShowingThumbnailPreview]
+ -[CKQLPreviewController pendingShareBarButtonItem]
+ -[CKQLPreviewController setPendingShareBarButtonItem:]
+ -[CKReaderViewController setShowsScrollIndicators:]
+ -[CKReaderViewController showsScrollIndicators]
+ -[CKRefinedNotificationChatController _entryViewTopInsetPadding]
+ -[CKReplyContextTranscriptPluginChatItem replyPreviewAttributedText]
+ -[CKThrowAnimationManager placesContainerViewInWindow]
+ -[CKThrowAnimationManager setPlacesContainerViewInWindow:]
+ -[CKTranscriptCollectionViewController _prewarmChatBotAssetsWithChatItems:]
+ -[CKTranscriptCollectionViewController _recoverFromTranscriptUpdateException:imChatItems:inserted:removed:reload:regenerate:animated:completion:]
+ -[CKTranscriptCollectionViewController conversationForBalloonView:]
+ -[CKTranscriptCollectionViewController didTapBlockContactsInBalloonView:]
+ -[CKTranscriptCollectionViewController didTapLeaveConversationInBalloonView:]
+ -[CKTranscriptCollectionViewController invalidateChatItemLayoutWithNewBalloonMaxWidth:marginInsets:traitCollection:]
+ -[CKTranscriptCollectionViewController newChatItemWithIMChatItem:traitCollection:]
+ -[CKTranscriptCollectionViewController(UserSafety) _updateCommSafetySensitivityForContentAtIndexPath:shouldTargetAssociatedMessages:updatedSensitivityAnalyses:]
+ -[CKTranscriptModel chatItemWithIMChatItem:traitCollection:]
+ -[CKTranscriptPluginReplyPreviewBalloonView .cxx_destruct]
+ -[CKTranscriptPluginReplyPreviewBalloonView balloonTypePillContentInsets]
+ -[CKTranscriptPluginReplyPreviewBalloonView initWithFrame:]
+ -[CKTranscriptPluginReplyPreviewBalloonView prepareForDisplay]
+ -[CKTranscriptPluginReplyPreviewBalloonView prepareForReuse]
+ -[CKTranscriptPluginReplyPreviewBalloonView sizeThatFits:textAlignmentInsets:tailInsets:]
+ -[CKTranscriptPluginReplyPreviewBalloonView titleLabel]
+ -[CKTranscriptPluginReplyPreviewBalloonView(CKReplyContextTranscriptPluginChatItem) configureForTranscriptPlugin:]
+ -[CKTranscriptPreviewController transcriptCollectionViewController:viewedCommSafetyAssociatedItemsWithIndexPath:updatedSensitivityAnalysesByTransferGUID:]
+ -[CKTranscriptPreviewController transcriptCollectionViewController:viewedCommSafetyItemWithIndexPath:updatedSensitivityAnalysesByTransferGUID:]
+ -[CKUIBehavior ckShouldUpdatepluginReplyPreviewBalloonAlignmentRectInsets]
+ -[CKUIBehavior notificationHeaderToEntryViewPadding]
+ -[CKUIBehavior pluginReplyPreviewBalloonAlignmentRectInsets]
+ -[CKUIBehaviorMac pluginReplyPreviewBalloonAlignmentRectInsets]
+ -[CKUIBehaviorMac snapToMinConversationListWidth]
+ -[NSAttributedString(CompositionSanitizing) ck_attributedStringByStrippingEditComparisonArtifacts]
+ -[UIWindowScene(Helper) __ck_isFullscreen]
+ -[_CKStickerEntry .cxx_destruct]
+ -[_CKStickerEntry isInline]
+ -[_CKStickerEntry setIsInline:]
+ -[_CKStickerEntry setSticker:]
+ -[_CKStickerEntry setType:]
+ -[_CKStickerEntry sticker]
+ -[_CKStickerEntry type]
+ GCC_except_table1001
+ GCC_except_table1007
+ GCC_except_table1012
+ GCC_except_table1018
+ GCC_except_table1024
+ GCC_except_table1028
+ GCC_except_table1029
+ GCC_except_table1030
+ GCC_except_table1035
+ GCC_except_table1036
+ GCC_except_table1041
+ GCC_except_table1045
+ GCC_except_table1071
+ GCC_except_table1077
+ GCC_except_table1084
+ GCC_except_table1115
+ GCC_except_table1117
+ GCC_except_table1140
+ GCC_except_table1145
+ GCC_except_table1147
+ GCC_except_table1192
+ GCC_except_table1194
+ GCC_except_table1196
+ GCC_except_table1201
+ GCC_except_table1202
+ GCC_except_table1209
+ GCC_except_table1211
+ GCC_except_table1213
+ GCC_except_table1221
+ GCC_except_table1239
+ GCC_except_table1250
+ GCC_except_table161
+ GCC_except_table222
+ GCC_except_table249
+ GCC_except_table270
+ GCC_except_table291
+ GCC_except_table292
+ GCC_except_table300
+ GCC_except_table308
+ GCC_except_table309
+ GCC_except_table314
+ GCC_except_table319
+ GCC_except_table326
+ GCC_except_table339
+ GCC_except_table345
+ GCC_except_table356
+ GCC_except_table367
+ GCC_except_table374
+ GCC_except_table385
+ GCC_except_table388
+ GCC_except_table409
+ GCC_except_table413
+ GCC_except_table418
+ GCC_except_table421
+ GCC_except_table438
+ GCC_except_table443
+ GCC_except_table453
+ GCC_except_table461
+ GCC_except_table462
+ GCC_except_table469
+ GCC_except_table478
+ GCC_except_table480
+ GCC_except_table481
+ GCC_except_table489
+ GCC_except_table498
+ GCC_except_table501
+ GCC_except_table503
+ GCC_except_table508
+ GCC_except_table509
+ GCC_except_table512
+ GCC_except_table517
+ GCC_except_table519
+ GCC_except_table522
+ GCC_except_table524
+ GCC_except_table525
+ GCC_except_table540
+ GCC_except_table542
+ GCC_except_table543
+ GCC_except_table545
+ GCC_except_table551
+ GCC_except_table565
+ GCC_except_table568
+ GCC_except_table569
+ GCC_except_table587
+ GCC_except_table588
+ GCC_except_table593
+ GCC_except_table594
+ GCC_except_table600
+ GCC_except_table601
+ GCC_except_table602
+ GCC_except_table613
+ GCC_except_table614
+ GCC_except_table615
+ GCC_except_table616
+ GCC_except_table620
+ GCC_except_table621
+ GCC_except_table623
+ GCC_except_table626
+ GCC_except_table632
+ GCC_except_table633
+ GCC_except_table634
+ GCC_except_table635
+ GCC_except_table641
+ GCC_except_table647
+ GCC_except_table652
+ GCC_except_table654
+ GCC_except_table655
+ GCC_except_table658
+ GCC_except_table659
+ GCC_except_table660
+ GCC_except_table666
+ GCC_except_table668
+ GCC_except_table671
+ GCC_except_table676
+ GCC_except_table680
+ GCC_except_table684
+ GCC_except_table685
+ GCC_except_table689
+ GCC_except_table701
+ GCC_except_table704
+ GCC_except_table706
+ GCC_except_table707
+ GCC_except_table710
+ GCC_except_table712
+ GCC_except_table718
+ GCC_except_table723
+ GCC_except_table736
+ GCC_except_table738
+ GCC_except_table739
+ GCC_except_table749
+ GCC_except_table752
+ GCC_except_table755
+ GCC_except_table756
+ GCC_except_table761
+ GCC_except_table762
+ GCC_except_table764
+ GCC_except_table768
+ GCC_except_table775
+ GCC_except_table776
+ GCC_except_table781
+ GCC_except_table786
+ GCC_except_table787
+ GCC_except_table789
+ GCC_except_table792
+ GCC_except_table821
+ GCC_except_table822
+ GCC_except_table826
+ GCC_except_table852
+ GCC_except_table853
+ GCC_except_table862
+ GCC_except_table868
+ GCC_except_table869
+ GCC_except_table878
+ GCC_except_table892
+ GCC_except_table894
+ GCC_except_table920
+ GCC_except_table940
+ GCC_except_table944
+ GCC_except_table952
+ GCC_except_table956
+ GCC_except_table957
+ GCC_except_table965
+ GCC_except_table967
+ GCC_except_table974
+ GCC_except_table979
+ GCC_except_table984
+ GCC_except_table985
+ GCC_except_table989
+ GCC_except_table991
+ GCC_except_table997
+ GCC_except_table999
+ _CKDefaultsKeyDisableNewComposeAutomaticKeyboardPresentation
+ _CKDefaultsKeyForceUnknownSenderForTesting
+ _CKDescriptionForUIViewController
+ _CKIsMiCAccountNeedsRepair
+ _CKIsMiCAccountNeedsRepair.onceToken
+ _CKStringFromSplitViewControllerColumn
+ _CKStringFromSplitViewControllerDisplayMode
+ _CKTranscriptIgnoreContentOffsetUpdatesReasonInteractiveResize
+ _IMAttachmentPreflightPreviewFileURL
+ _IMBalloonPluginIdentifierCanRenderReplyPreview
+ _IMBalloonPluginIdentifierReplyPreviewFallbackText
+ _IMBalloonPluginIdentifierReplyPreviewSymbolName
+ _IMFileTransferPreflightAssetIdentifierKey
+ _IMGetUserAccountActionIntent
+ _IMGetUserIgnoreFailureMiCAccountNeedsRepairIntent
+ _IMSCSensitivityAnalysisPrepareContentPolicy
+ _IMSetUserIgnoreFailureMiCAccountNeedsRepairIntent
+ _IMUTTypeIsGIF
+ _IMUserAccountActionIntentChanged
+ _OBJC_CLASS_$_APApplication
+ _OBJC_CLASS_$_CKAppCardPresentationDecision
+ _OBJC_CLASS_$_CKTranscriptPluginReplyPreviewBalloonView
+ _OBJC_CLASS_$_IMChatForkingDiff
+ _OBJC_CLASS_$_IMChatForkingInfo
+ _OBJC_CLASS_$_IMChatForkingReport
+ _OBJC_CLASS_$_IMChatForkingRequest
+ _OBJC_CLASS_$_UIWindowSceneGeometryPreferencesIOS
+ _OBJC_CLASS_$__CKStickerEntry
+ _OBJC_CLASS_$__TtC7ChatKit21CKGlassSendMenuButton
+ _OBJC_IVAR_$_CKBackgroundGalleryFetchRequest._shouldBypassPosterGalleryCache
+ _OBJC_IVAR_$_CKBrowserViewController._presentationReadyHandler
+ _OBJC_IVAR_$_CKChatController._didPresentDetailsInPortrait
+ _OBJC_IVAR_$_CKChatController._entryViewWasFirstResponderBeforeDetailsPresentation
+ _OBJC_IVAR_$_CKFullScreenCardAppViewController._presentationReadyHandler
+ _OBJC_IVAR_$_CKImpactEffectManager.placesContainerViewInWindow
+ _OBJC_IVAR_$_CKMessageEntryRichTextView._ck_disallowBecomeFirstResponder
+ _OBJC_IVAR_$_CKQLPreviewController._pendingShareBarButtonItem
+ _OBJC_IVAR_$_CKReaderViewController._showsScrollIndicators
+ _OBJC_IVAR_$_CKThrowAnimationManager._placesContainerViewInWindow
+ _OBJC_IVAR_$_CKTranscriptPluginReplyPreviewBalloonView._titleLabel
+ _OBJC_IVAR_$__CKStickerEntry._isInline
+ _OBJC_IVAR_$__CKStickerEntry._sticker
+ _OBJC_IVAR_$__CKStickerEntry._type
+ _OBJC_METACLASS_$_CKAppCardPresentationDecision
+ _OBJC_METACLASS_$_CKTranscriptPluginReplyPreviewBalloonView
+ _OBJC_METACLASS_$__CKStickerEntry
+ _OBJC_METACLASS_$__TtC7ChatKit21CKGlassSendMenuButton
+ __CKCalculateIsMiCAccountNeedsRepairValue
+ __CLASS_METHODS_CKStickerStore
+ __CLASS_METHODS__TtC7ChatKit21CKGlassSendMenuButton
+ __CLASS_METHODS__TtC7ChatKit34CKCommunicationSafetyFlowPresenter
+ __DATA_CKAppCardPresentationDecision
+ __DATA__TtC7ChatKit21CKGlassSendMenuButton
+ __INSTANCE_METHODS_CKAppCardPresentationDecision
+ __INSTANCE_METHODS__TtC7ChatKit34CKCommunicationSafetyFlowPresenter
+ __IVARS_CKAppCardPresentationDecision
+ __IVARS__TtC7ChatKit21CKGlassSendMenuButton
+ __METACLASS_DATA_CKAppCardPresentationDecision
+ __METACLASS_DATA__TtC7ChatKit21CKGlassSendMenuButton
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_UIWindowScene_$_Helper
+ __OBJC_$_CATEGORY_UIWindowScene_$_Helper
+ __OBJC_$_CLASS_METHODS__CKStickerEntry
+ __OBJC_$_INSTANCE_METHODS_CKChatController(MacToolbar|ClickyOrbConformance|CKChatController_Stickers|CKStickerDetailViewControllerDelegate|ChatItemSelection|Debug|ImpactEffectPicker|MenuBar|MessageHistoryViewController|MessageHistoryViewControllerDelegate|SendAnimation|QuickLook|CKNavBarUnifiedCallButton|Collaboration|GroupCollaboration|TipKit|SafetyMonitor|MediaInput|GlassThrowSendAnimation|PhotosSupport|Contacts|Wallet|Location|BackgroundContextMenu|NavigationBar|TapbackPicker|TapbackPicker_QuickLook|TapbackPicker_Orb|ChatKit|ChatKit1|TapbackPicker_ContextMenu|ChatKit2|ChatKit3|ChatKit4|BalloonFocus|ChatKit5|ChatKit6|MenuBarKeyCommands|ChatKit7|ChatKit8|Translation|ChatKit9|ChatKit10|ChatKit11|ChatKit12)
+ __OBJC_$_INSTANCE_METHODS_CKTranscriptPluginReplyPreviewBalloonView(CKReplyContextTranscriptPluginChatItem)
+ __OBJC_$_INSTANCE_METHODS__CKStickerEntry
+ __OBJC_$_INSTANCE_METHODS__TtC7ChatKit21CKGlassSendMenuButton(ChatKit)
+ __OBJC_$_INSTANCE_VARIABLES_CKTranscriptPluginReplyPreviewBalloonView
+ __OBJC_$_INSTANCE_VARIABLES__CKStickerEntry
+ __OBJC_$_PROP_LIST_CKTranscriptPluginReplyPreviewBalloonView
+ __OBJC_$_PROP_LIST_UIWindowScene_$_Helper
+ __OBJC_$_PROP_LIST__CKStickerEntry
+ __OBJC_CLASS_PROTOCOLS_$_CKChatController(MacToolbar|ClickyOrbConformance|CKChatController_Stickers|CKStickerDetailViewControllerDelegate|ChatItemSelection|Debug|ImpactEffectPicker|MenuBar|MessageHistoryViewController|MessageHistoryViewControllerDelegate|SendAnimation|QuickLook|CKNavBarUnifiedCallButton|Collaboration|GroupCollaboration|TipKit|SafetyMonitor|MediaInput|GlassThrowSendAnimation|PhotosSupport|Contacts|Wallet|Location|BackgroundContextMenu|NavigationBar|TapbackPicker|TapbackPicker_QuickLook|TapbackPicker_Orb|ChatKit|ChatKit1|TapbackPicker_ContextMenu|ChatKit2|ChatKit3|ChatKit4|BalloonFocus|ChatKit5|ChatKit6|MenuBarKeyCommands|ChatKit7|ChatKit8|Translation|ChatKit9|ChatKit10|ChatKit11|ChatKit12)
+ __OBJC_CLASS_PROTOCOLS_$__TtC7ChatKit21CKGlassSendMenuButton(ChatKit)
+ __OBJC_CLASS_RO_$_CKTranscriptPluginReplyPreviewBalloonView
+ __OBJC_CLASS_RO_$__CKStickerEntry
+ __OBJC_METACLASS_RO_$_CKTranscriptPluginReplyPreviewBalloonView
+ __OBJC_METACLASS_RO_$__CKStickerEntry
+ __PROPERTIES_CKAppCardPresentationDecision
+ __PROPERTIES__TtC7ChatKit21CKGlassSendMenuButton
+ ___113-[CKChatInputController generatePreflightThumbnailFillToSize:assetPxSize:scale:thumbnail:isScreenshot:mediaType:]_block_invoke
+ ___118-[CKChatController _presentShareSheetForMessagePartChatItems:sourceItem:sourceView:sourceRect:presentationCompletion:]_block_invoke_2
+ ___118-[CKCoreChatController(UserSafety) presentCommSafetyInterventionIfNecessaryForSticker:willPresentHandler:sendHandler:]_block_invoke
+ ___118-[CKCoreChatController(UserSafety) presentCommSafetyInterventionIfNecessaryForSticker:willPresentHandler:sendHandler:]_block_invoke_2
+ ___132-[CKChatControllerDummyAnimator __beginThrowAnimationWithThrowBalloonViewAttributesCollection:framesOfAddedChatItems:entryViewSize:]_block_invoke
+ ___134-[CKCoreChatController transcriptCollectionViewController:viewedCommSafetyItemWithIndexPath:updatedSensitivityAnalysesByTransferGUID:]_block_invoke
+ ___145-[CKCoreChatController transcriptCollectionViewController:viewedCommSafetyAssociatedItemsWithIndexPath:updatedSensitivityAnalysesByTransferGUID:]_block_invoke
+ ___145-[CKTranscriptCollectionViewController _recoverFromTranscriptUpdateException:imChatItems:inserted:removed:reload:regenerate:animated:completion:]_block_invoke
+ ___232-[CKChatController(SendAnimation) _makeThrowBalloonsForSendAnimationInContainerView:forSendingMessages:shouldUseQuickReplySourceRect:quickReplySourceRect:quickReplySnapshotView:audioMessageSourceRect:audioRecordingPillViewSnapshot:]_block_invoke
+ ___41-[CKChatController viewDidLayoutSubviews]_block_invoke
+ ___49-[CKUIBehaviorMac snapToMinConversationListWidth]_block_invoke
+ ___51-[CKObscurableBalloonView _makeSCAUIObscuringView:]_block_invoke_6
+ ___52-[CKUIBehavior notificationHeaderToEntryViewPadding]_block_invoke
+ ___53-[CKQLPreviewController showShareSheetFromBarButton:]_block_invoke_2
+ ___56-[CKQLPreviewController _flushQueuedSaveAttemptIfNeeded]_block_invoke
+ ___60-[CKMessagesController updateInterfaceOrientationsAnimated:]_block_invoke_2
+ ___63-[CKComposeChatController shouldSetFirstResponderWhenPresented]_block_invoke
+ ___63-[CKUIBehaviorMac pluginReplyPreviewBalloonAlignmentRectInsets]_block_invoke
+ ___72-[CKChatController(ClickyOrbConformance) _stickerInfoActionForChatItem:]_block_invoke
+ ___73-[CKChatController(ClickyOrbConformance) _saveStickersActionForChatItem:]_block_invoke
+ ___73-[CKTranscriptCollectionViewController didTapBlockContactsInBalloonView:]_block_invoke
+ ___75-[CKChatController(CKChatController_Stickers) saveStickerFromEmojiDetails:]_block_invoke
+ ___77-[CKTranscriptCollectionViewController didTapLeaveConversationInBalloonView:]_block_invoke
+ ___CKIsMiCAccountNeedsRepair
+ ___CKIsMiCAccountNeedsRepair_block_invoke
+ ___block_descriptor_113_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_131_e8_32s40s48s56s64s72r80r88r_e27_v32?0"CKChatItem"8Q16^B24ls32l8s40l8s48l8r72l8s56l8r80l8s64l8r88l8
+ ___block_descriptor_40_e8_32s_e33_v24?0"NSString"8"NSIndexSet"16ls32l8
+ ___block_descriptor_40_e8_32s_e34_v16?0"UIActivityViewController"8ls32l8
+ ___block_descriptor_41_e8_32w_e18_v16?0"UIAction"8lw32l8
+ ___block_descriptor_56_e8_32s40s48w_e22_v16?0"NSDictionary"8lw48l8s32l8s40l8
+ ___block_descriptor_57_e8_32s40s48s_e22_v16?0"NSDictionary"8ls32l8s40l8s48l8
+ ___block_descriptor_57_e8_32s40s48s_e31_v16?0"SCSensitivityAnalysis"8ls32l8s40l8s48l8
+ ___block_descriptor_57_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48bs56w_e5_v8?0lw56l8s32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56s_e45_v32?0"CKThrowBalloonViewAttributes"8Q16^B24ls32l8s40l8s48l8s56l8
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e31_v16?0"SCSensitivityAnalysis"8ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_72_e8_32s40s48s56s64r_e27_v32?0"IMChatItem"8Q16^B24ls32l8s40l8s48l8s56l8r64l8
+ ___block_descriptor_72_e8_32s40s48s56s64w_e22_v16?0"NSDictionary"8lw64l8s32l8s40l8s48l8s56l8
+ ___block_descriptor_72_e8_32s40s48s_e45_v32?0"CKThrowBalloonViewAttributes"8Q16^B24ls32l8s40l8s48l8
+ ___block_descriptor_80_e8_32s40s48s56r64r72r_e27_v32?0"IMChatItem"8Q16^B24ls32l8s40l8s48l8r56l8r64l8r72l8
+ ___swift_closure_destructor.196Tm
+ ___swift_closure_destructor.35Tm
+ ___swift_closure_destructor.55Tm
+ ___swift_closure_destructor.68Tm
+ ___swift_closure_destructor.76Tm
+ ___swift_closure_destructor.85Tm
+ __ck_stickerTypeForIMSticker
+ _associated conformance 7ChatKit0A18PropertyEditorViewV7SwiftUI0E0AA4BodyAdEP_AdE
+ _associated conformance 7ChatKit13MessageEntityV10AppIntents08SyncableD0AaD0eD0
+ _associated conformance 7ChatKit14ForkReportViewV014ExpectedActualE0V7SwiftUI0E0AA4BodyAfGP_AfG
+ _associated conformance 7ChatKit14ForkReportViewV11ItemListRowV7SwiftUI0E0AA4BodyAfGP_AfG
+ _associated conformance 7ChatKit14ForkReportViewV13ScalarDiffRowV7SwiftUI0E0AA4BodyAfGP_AfG
+ _associated conformance 7ChatKit14ForkReportViewV15LabeledValueRowV7SwiftUI0E0AA4BodyAfGP_AfG
+ _associated conformance 7ChatKit14ForkReportViewV16NoDifferencesRowV7SwiftUI0E0AA4BodyAfGP_AfG
+ _associated conformance 7ChatKit14ForkReportViewV17CollectionDiffRowV7SwiftUI0E0AA4BodyAfGP_AfG
+ _associated conformance 7ChatKit14ForkReportViewV17SequentialDiffRowV7SwiftUI0E0AA4BodyAfGP_AfG
+ _associated conformance 7ChatKit14ForkReportViewV7SwiftUI0E0AA4BodyAdEP_AdE
+ _associated conformance 7ChatKit24MiCAccountNeedsRepairTipV0gB00G0AAs12Identifiable
+ _associated conformance 7ChatKit24MiCAccountNeedsRepairTipV0gB00G7ContentAA9ImageViewAdEP_7SwiftUI0J0
+ _associated conformance 7ChatKit24MiCAccountNeedsRepairTipVs12IdentifiableAA2IDsADP_SH
+ _associated conformance 7ChatKit25KeyboardDismissalBehaviorOSHAASQ
+ _associated conformance 7ChatKit26ConversationsInspectorViewV3Tab33_5837B76DFB3CAF2693E77824077F5A11LLOSHAASQ
+ _associated conformance 7ChatKit34CKCommunicationSafetyFlowPresenterC13SensitiveItemCs12IdentifiableAA2IDsAFP_SH
+ _associated conformance 7ChatKit34CKCommunicationSafetyFlowPresenterC18SensitiveMediaKind33_841501E1B0CE74F15963B24750700A4ALLOSHAASQ
+ _associated conformance So23SCUIMoreHelpMenuOptionsVs10SetAlgebraSCSQ
+ _associated conformance So23SCUIMoreHelpMenuOptionsVs10SetAlgebraSCs25ExpressibleByArrayLiteral
+ _associated conformance So23SCUIMoreHelpMenuOptionsVs9OptionSetSCSY
+ _associated conformance So23SCUIMoreHelpMenuOptionsVs9OptionSetSCs0F7Algebra
+ _get_witness_table 7ChatKit27DebugInspectorContainerViewVy7SwiftUI03TabF0VyAA013ConversationsdF0V0I033_5837B76DFB3CAF2693E77824077F5A11LLOAD12TupleContentVyAD0F0PADE3tag_15includeOptionalQrqd___SbtSHRd__lFQOyAoDE7tabItemyQrqd__yXEAdNRd__lFQOyAD4ListVys5NeverOAD7ForEachVySaySi6offset_So14CKConversationC7elementtGSiAD7SectionVyAD4TextVAXy19CollectionsInternal17OrderedDictionaryV8ElementsVyS2SSg_GSSAA0cd4CellF0VSgGAD05EmptyF0VGGG_AD5LabelVyA5_AD5ImageVGQo__AKQo__AoDEAP_AQQrqd___SbtSHRd__lFQOyAoDEARyQrqd__yXEAdNRd__lFQOyATyAvXyA1_SiA3_yA5_AA0a14PropertyEditorF0VA18_GGG_A26_Qo__AKQo_AoDEAP_AQQrqd___SbtSHRd__lFQOyAoDEARyQrqd__yXEAdNRd__lFQOyAA010ForkReportF0V_A26_Qo__AKQo_QPGGGAdNHPyHC
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA6HStackVyAA05TupleD0VyACyAA5ImageVAA24_ForegroundStyleModifierVyAA5ColorVGG_AA4TextVQPGGAA14_PaddingLayoutVGAA4ViewHPAsaWHPyHC_AuA0oJ0HPyHCHC
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA6VStackVyAA05TupleD0VyAA4TextV_7ChatKit14ForkReportViewV014ExpectedActualL0VQPGGAA14_PaddingLayoutVGAA0L0HPApaTHPyHC_ArA0L8ModifierHPyHCHC
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA6VStackVyAA05TupleD0VyAA4TextV_AA012_ConditionalD0VyAiA7ForEachVySaySi6offset_SS7elementtGSiAA4ViewPAAE13textSelectionyQrqd__AA0G13SelectabilityRd__lFQOyAI_AA07EnabledgP0VQo_GGQPGGAA14_PaddingLayoutVGAaQHPA_AaQHPyHC_A1_AA0M8ModifierHPyHCHC
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA6VStackVyAA05TupleD0VyAA4TextV_AA4ViewPAAE13textSelectionyQrqd__AA0G13SelectabilityRd__lFQOyAI_AA07EnabledgK0VQo_ACyAA6HStackVyAGyAI_AIQPGGAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGG7ChatKit010ForkReportH0V014ExpectedActualH0VQPGGAA14_PaddingLayoutVGAaJHPA6_AaJHPyHC_A8_AA0hQ0HPyHCHC
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA6VStackVyAA05TupleD0VyAA4TextV_AA4ViewPAAE13textSelectionyQrqd__AA0G13SelectabilityRd__lFQOyAI_AA07EnabledgK0VQo_QPGGAA14_PaddingLayoutVGAaJHPAraJHPyHC_AtA0H8ModifierHPyHCHC
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA6VStackVyAA05TupleD0VyAA4TextV_AEyAGyAI_AA7ForEachVySaySi6offset_SS7elementtGSiAA6HStackVyAGyACyACyAA5ImageVAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGAA016_ForegroundStyleQ0VyAA5ColorVGG_AA4ViewPAAE13textSelectionyQrqd__AA0G13SelectabilityRd__lFQOyAI_AA07EnabledgY0VQo_QPGGGQPGGSgA16_QPGGAA14_PaddingLayoutVGAAA4_HPA18_AAA4_HPyHC_A20_AA0vQ0HPyHCHC
+ _get_witness_table 7SwiftUI19_ConditionalContentVyAA4ViewPAAE11contextMenu9menuItems7preview0J6ActionQrqd__yXE_qd_0_yXEyyctAaDRd__AaDRd_0_r0_lFQOyAA01_e9Modifier_D0Vy7ChatKit07Detailse13CommonContextG0VG_AA5GroupVyAA05TupleD0VyAA7SectionVyAA05EmptyE0VAN0G4Item33_F28409D6AF308FDD12CA19D65AD16453LLVy_AA19TitleOnlyLabelStyleVGSgAWG_AUyAwZy_AA22TitleAndIconLabelStyleVGSgAWGA3_SgA3_QPGGAN34CKQLPreviewControllerRepresentableAYLLVQo_AeAEAfGQrqd__yXE_tAaDRd__lFQOyAO_A11_Qo_GAaDHPqd0__AaDHD4_A14_HO_qd0__AaDHD3_A15_HOHC
+ _get_witness_table 7SwiftUI4ListVys5NeverOAA12TupleContentVyAA7SectionVyAA9EmptyViewVAA08ModifiedF0VyAA6ButtonVyAA6HStackVyAGyAA4TextV_AGyAA6SpacerV_AA08ProgressI0VyA2KGQPGSgQPGGGAA32_EnvironmentKeyTransformModifierVySbGGASGSg_AA7ForEachVySaySi6offset_So19IMChatForkingReportC7elementtGSiAGyAIyAsGy7ChatKit04ForkyI0V15LabeledValueRowV_A19_A17_04ItemC3RowVA19_A19_A19_A19_A19_A21_QPGAKG_A9_ySaySiA10__So0wX4DiffCA13_tGSiAIyAsGyA19__AA012_ConditionalF0VyAGyA17_13ScalarDiffRowVSg_A17_17CollectionDiffRowVSgA17_17SequentialDiffRowVSgA31_A31_A31_A31_A34_QPGA17_16NoDifferencesRowVGQPGAKGGA44_A28_yAIyAkMyAMyAA6VStackVyAGyAMyAMyAA5ImageVAA01_pq7WritingS0VyAA4FontVSgGGAA016_ForegroundStyleS0VyAA5ColorVGG_ASQPGGAA16_FlexFrameLayoutVGAA14_PaddingLayoutVGAKGAIyAkMyAOyASGA4_GAKGGQPGGSgQPGGAA0I0HPyHC
+ _get_witness_table 7SwiftUI6VStackVyAA12TupleContentVyACyAEyAA4TextV_AA4ViewPAAE13textSelectionyQrqd__AA0F13SelectabilityRd__lFQOyAG_AA07EnabledfJ0VQo_QPGG_APQPGGAaHHPyHC
+ _notificationHeaderToEntryViewPadding.once
+ _notificationHeaderToEntryViewPadding.sBehavior
+ _pluginReplyPreviewBalloonAlignmentRectInsets.once
+ _pluginReplyPreviewBalloonAlignmentRectInsets.sBehavior
+ _pluginReplyPreviewBalloonAlignmentRectInsets.sContentSizeCategory_pluginReplyPreviewBalloonAlignmentRectInsets
+ _pluginReplyPreviewBalloonAlignmentRectInsets.sCustomTextFontName_pluginReplyPreviewBalloonAlignmentRectInsets
+ _pluginReplyPreviewBalloonAlignmentRectInsets.sCustomTextFontSize_pluginReplyPreviewBalloonAlignmentRectInsets
+ _pluginReplyPreviewBalloonAlignmentRectInsets.sIsBoldTextEnabled_pluginReplyPreviewBalloonAlignmentRectInsets
+ _pluginReplyPreviewBalloonAlignmentRectInsets.sTextFontSize_pluginReplyPreviewBalloonAlignmentRectInsets
+ _shouldSetFirstResponderWhenPresented.onceToken
+ _shouldSetFirstResponderWhenPresented.res
+ _symbolic SDySSSaySSGG
+ _symbolic SDySSSo21SCSensitivityAnalysisCG
+ _symbolic SDySSSo21SCSensitivityAnalysisCGIegg_
+ _symbolic SS3key_SDySSSaySSGG5valuet
+ _symbolic SS3key_SaySSG5valuet
+ _symbolic SaySi6offset_SS7elementtG
+ _symbolic SaySi6offset_So17IMChatForkingDiffC7elementtG
+ _symbolic SaySi6offset_So19IMChatForkingReportC7elementtG
+ _symbolic SaySo19IMChatForkingReportCG
+ _symbolic SaySo19IMChatForkingReportCGSg
+ _symbolic Si6offset_SS7elementt
+ _symbolic Si6offset_So17IMChatForkingDiffC7elementt
+ _symbolic Si6offset_So19IMChatForkingReportC7elementt
+ _symbolic SiSS_____y_____y_____yACy__________y_____SgGG_____y_____GG______y___________Qo_QPGGIegygr_ 7SwiftUI6HStackV AA12TupleContentV AA08ModifiedE0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleK0V AA5ColorV AA4ViewPAAE13textSelectionyQrqd__AA17TextSelectabilityRd__lFQO AA0S0V AA07EnabledsT0V
+ _symbolic SiSo14CKConversationC_____y_______________GIegygr_ 7SwiftUI7SectionV AA4TextV 7ChatKit0E18PropertyEditorViewV AA05EmptyI0V
+ _symbolic SiSo17IMChatForkingDiffC_____y__________y___________yAEy_____Sg______Sg_____SgA4iKQPG_____GQPG_____GIegygr_ 7SwiftUI7SectionV AA4TextV AA12TupleContentV 7ChatKit14ForkReportViewV15LabeledValueRowV AA012_ConditionalF0V AJ010ScalarDiffN0V AJ010CollectionqN0V AJ010SequentialqN0V AJ013NoDifferencesN0V AA05EmptyK0V
+ _symbolic SiSo19IMChatForkingReportC_____y_____y_____ACy______AF_____A5fGQPG_____G______ySaySi6offset_So0aB4DiffC7elementtGSiADyAeCyAF______yACy_____Sg______Sg_____SgA4sUQPG_____GQPGAIGGA1_AQyADyAI_____yA2_y_____yACyA2_yA2_y__________y_____SgGG_____y_____GG_AEQPGG_____G_____GAIGADyAIA2_y_____yAEG_____ySbGGAIGGQPGIegygr_ 7SwiftUI12TupleContentV AA7SectionV AA4TextV 7ChatKit14ForkReportViewV15LabeledValueRowV AJ08ItemListN0V AA05EmptyK0V AA7ForEachV AA012_ConditionalD0V AJ010ScalarDiffN0V AJ010CollectionvN0V AJ010SequentialvN0V AJ013NoDifferencesN0V AA08ModifiedD0V AA6VStackV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA24_ForegroundStyleModifierV AA5ColorV AA16_FlexFrameLayoutV AA14_PaddingLayoutV AA6ButtonV AA32_EnvironmentKeyTransformModifierV
+ _symbolic So12NSDictionaryCIeyBy_
+ _symbolic So13CKBalloonViewCSgXw
+ _symbolic So13CKBalloonViewCSgXwz_Xx
+ _symbolic So23IMChatForkingScalarDiffC
+ _symbolic So27IMChatForkingCollectionDiffC
+ _symbolic So27IMChatForkingSequentialDiffC
+ _symbolic So33CKCloudKitAccountRepairControllerCSg
+ _symbolic _____ 12TextComposer0aB6ClientC
+ _symbolic _____ 7ChatKit0A18PropertyEditorViewV
+ _symbolic _____ 7ChatKit14ForkReportViewV
+ _symbolic _____ 7ChatKit14ForkReportViewV014ExpectedActualE0V
+ _symbolic _____ 7ChatKit14ForkReportViewV11ItemListRowV
+ _symbolic _____ 7ChatKit14ForkReportViewV13ScalarDiffRowV
+ _symbolic _____ 7ChatKit14ForkReportViewV15LabeledValueRowV
+ _symbolic _____ 7ChatKit14ForkReportViewV16NoDifferencesRowV
+ _symbolic _____ 7ChatKit14ForkReportViewV17CollectionDiffRowV
+ _symbolic _____ 7ChatKit14ForkReportViewV17SequentialDiffRowV
+ _symbolic _____ 7ChatKit21CKGlassSendMenuButtonC
+ _symbolic _____ 7ChatKit24MiCAccountNeedsRepairTipV
+ _symbolic _____ 7ChatKit25KeyboardDismissalBehaviorO
+ _symbolic _____ 7ChatKit26ConversationsInspectorViewV3Tab33_5837B76DFB3CAF2693E77824077F5A11LLO
+ _symbolic _____ 7ChatKit29CKAppCardPresentationDecisionC
+ _symbolic _____ 7ChatKit34CKCommunicationSafetyFlowPresenterC18SensitiveMediaKind33_841501E1B0CE74F15963B24750700A4ALLO
+ _symbolic _____ So23SCUIMoreHelpMenuOptionsV
+ _symbolic _____4kind______7optionsSDySSypG17contextDictionaryt 26SensitiveContentAnalysisUI20SCUIInterventionKindV So23SCUIMoreHelpMenuOptionsV
+ _symbolic _____4kind______7optionsSDySSypG17contextDictionarytSg 26SensitiveContentAnalysisUI20SCUIInterventionKindV So23SCUIMoreHelpMenuOptionsV
+ _symbolic _____4kind______7optionst 26SensitiveContentAnalysisUI20SCUIInterventionKindV So23SCUIMoreHelpMenuOptionsV
+ _symbolic _____4kind______7optionstSg 26SensitiveContentAnalysisUI20SCUIInterventionKindV So23SCUIMoreHelpMenuOptionsV
+ _symbolic _____Sg 24SensitiveContentAnalysis0aB0V0B6SourceO
+ _symbolic _____Sg 26SensitiveContentAnalysisUI20SCUIInterventionKindV
+ _symbolic _____Sg 7ChatKit14ForkReportViewV13ScalarDiffRowV
+ _symbolic _____Sg 7ChatKit14ForkReportViewV17CollectionDiffRowV
+ _symbolic _____Sg 7ChatKit14ForkReportViewV17SequentialDiffRowV
+ _symbolic _____Sg 7ChatKit24MiCAccountNeedsRepairTipV
+ _symbolic _____Sg 7SwiftUI4TextV9LineStyleV
+ _symbolic ______SSSg12sandboxTokent 10Foundation3URLV
+ _symbolic ___________SDySSypGt 26SensitiveContentAnalysisUI20SCUIInterventionKindV So23SCUIMoreHelpMenuOptionsV
+ _symbolic ___________t 26SensitiveContentAnalysisUI20SCUIInterventionKindV So23SCUIMoreHelpMenuOptionsV
+ _symbolic ___________yAA______Qo______y_____y_____yAA_AAQPGG_____y_____SgGG_____t 7SwiftUI4TextV AA4ViewPAAE13textSelectionyQrqd__AA0C13SelectabilityRd__lFQO AA07EnabledcG0V AA15ModifiedContentV AA6HStackV AA05TupleJ0V AA30_EnvironmentKeyWritingModifierV AA4FontV 7ChatKit010ForkReportD0V014ExpectedActualD0V
+ _symbolic ___________yAA______Qo_t 7SwiftUI4TextV AA4ViewPAAE13textSelectionyQrqd__AA0C13SelectabilityRd__lFQO AA07EnabledcG0V
+ _symbolic ___________yAA_____ySaySi6offset_SS7elementtGSi_____yAA______Qo_GGt 7SwiftUI4TextV AA19_ConditionalContentV AA7ForEachV AA4ViewPAAE13textSelectionyQrqd__AA0C13SelectabilityRd__lFQO AA07EnabledcK0V
+ _symbolic ___________ySaySi6offset_SS7elementtGSi_____y_____y_____yAHy__________y_____SgGG_____y_____GG______yAA______Qo_QPGGGt 7SwiftUI4TextV AA7ForEachV AA6HStackV AA12TupleContentV AA08ModifiedH0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleN0V AA5ColorV AA4ViewPAAE13textSelectionyQrqd__AA0C13SelectabilityRd__lFQO AA07EnabledcV0V
+ _symbolic ___________y_____ACGt 7SwiftUI6SpacerV AA12ProgressViewV AA05EmptyE0V
+ _symbolic ___________y___________y_____AEGQPGSgt 7SwiftUI4TextV AA12TupleContentV AA6SpacerV AA12ProgressViewV AA05EmptyH0V
+ _symbolic ___________y_____yAA______ySaySi6offset_SS7elementtGSi_____yACy_____yAIy__________y_____SgGG_____y_____GG______yAA______Qo_QPGGGQPGGSgA_t 7SwiftUI4TextV AA6VStackV AA12TupleContentV AA7ForEachV AA6HStackV AA08ModifiedF0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleO0V AA5ColorV AA4ViewPAAE13textSelectionyQrqd__AA0C13SelectabilityRd__lFQO AA07EnabledcW0V
+ _symbolic _____yAAy__________y_____SgGG_____y_____GG______y___________Qo_t 7SwiftUI15ModifiedContentV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleI0V AA5ColorV AA4ViewPAAE13textSelectionyQrqd__AA17TextSelectabilityRd__lFQO AA0Q0V AA07EnabledqR0V
+ _symbolic _____yAAy_____y_____yAAyAAy__________y_____SgGG_____y_____GG______QPGG_____G_____G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleK0V AA5ColorV AA4TextV AA16_FlexFrameLayoutV AA08_PaddingS0V
+ _symbolic _____ySS3key_SDySSSaySSGG5valuetG s23_ContiguousArrayStorageC
+ _symbolic _____ySS3key_SaySSG5valuetG s23_ContiguousArrayStorageC
+ _symbolic _____ySSSo21SCSensitivityAnalysisCG s18_DictionaryStorageC
+ _symbolic _____ySaySi6offset_SS7elementtGSi_____y_____y_____yAGy__________y_____SgGG_____y_____GG______y___________Qo_QPGGG 7SwiftUI7ForEachV AA6HStackV AA12TupleContentV AA08ModifiedG0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleM0V AA5ColorV AA4ViewPAAE13textSelectionyQrqd__AA17TextSelectabilityRd__lFQO AA0U0V AA07EnableduV0V
+ _symbolic _____ySaySi6offset_So14CKConversationC7elementtGSi_____y_______________GG 7SwiftUI7ForEachV AA7SectionV AA4TextV 7ChatKit0G18PropertyEditorViewV AA05EmptyK0V
+ _symbolic _____ySaySi6offset_So17IMChatForkingDiffC7elementtGSi_____y__________y___________yAIy_____Sg______Sg_____SgA4mOQPG_____GQPG_____GG 7SwiftUI7ForEachV AA7SectionV AA4TextV AA12TupleContentV 7ChatKit14ForkReportViewV15LabeledValueRowV AA012_ConditionalH0V AL010ScalarDiffP0V AL010CollectionsP0V AL010SequentialsP0V AL013NoDifferencesP0V AA05EmptyM0V
+ _symbolic _____ySaySi6offset_So19IMChatForkingReportC7elementtGSi_____y_____y_____AGy______AJ_____A5jKQPG_____G_AAySaySiAB_So0bC4DiffCAEtGSiAHyAiGyAJ______yAGy_____Sg______Sg_____SgA4tVQPG_____GQPGAMGGA2_ARyAHyAM_____yA3_y_____yAGyA3_yA3_y__________y_____SgGG_____y_____GG_AIQPGG_____G_____GAMGAHyAMA3_y_____yAIG_____ySbGGAMGGQPGG 7SwiftUI7ForEachV AA12TupleContentV AA7SectionV AA4TextV 7ChatKit14ForkReportViewV15LabeledValueRowV AL08ItemListP0V AA05EmptyM0V AA012_ConditionalF0V AL010ScalarDiffP0V AL010CollectionvP0V AL010SequentialvP0V AL013NoDifferencesP0V AA08ModifiedF0V AA6VStackV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA24_ForegroundStyleModifierV AA5ColorV AA16_FlexFrameLayoutV AA14_PaddingLayoutV AA6ButtonV AA32_EnvironmentKeyTransformModifierV
+ _symbolic _____ySaySi6offset_So19IMChatForkingReportC7elementtGSi_____y_____y_____AGy______AJ_____A5jKQPG_____G_AAySaySiAB_So0bC4DiffCAEtGSiAHyAiGyAJ______yAGy_____Sg______Sg_____SgA4tVQPG_____GQPGAMGGA2_ARyAHyAM_____yA3_y_____yAGyA3_yA3_y__________y_____SgGG_____y_____GG_AIQPGG_____G_____GAMGAHyAMA3_y_____yAIG_____ySbGGAMGGQPGGSg 7SwiftUI7ForEachV AA12TupleContentV AA7SectionV AA4TextV 7ChatKit14ForkReportViewV15LabeledValueRowV AL08ItemListP0V AA05EmptyM0V AA012_ConditionalF0V AL010ScalarDiffP0V AL010CollectionvP0V AL010SequentialvP0V AL013NoDifferencesP0V AA08ModifiedF0V AA6VStackV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA24_ForegroundStyleModifierV AA5ColorV AA16_FlexFrameLayoutV AA14_PaddingLayoutV AA6ButtonV AA32_EnvironmentKeyTransformModifierV
+ _symbolic _____ySaySo19IMChatForkingReportCGSgG 7SwiftUI9LazyStateV
+ _symbolic _____ySaySo19IMChatForkingReportCGSg_G 7SwiftUI9LazyStateV7StorageO
+ _symbolic _____ySaySo19IMChatForkingReportCGSg_G_yXlSgt 7SwiftUI9LazyStateV7StorageO
+ _symbolic _____ySi6offset_SS7elementtG s23_ContiguousArrayStorageC
+ _symbolic _____ySi6offset_So17IMChatForkingDiffC7elementtG s23_ContiguousArrayStorageC
+ _symbolic _____ySi6offset_So19IMChatForkingReportC7elementtG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G 7SwiftUI9LazyStateV 7ChatKit26ConversationsInspectorViewV3Tab33_5837B76DFB3CAF2693E77824077F5A11LLO
+ _symbolic _____y_____Sg______Sg_____SgA4cEQPG 7SwiftUI12TupleContentV 7ChatKit14ForkReportViewV13ScalarDiffRowV AF010CollectionkL0V AF010SequentialkL0V
+ _symbolic _____y______AB_____A5bCQPG 7SwiftUI12TupleContentV 7ChatKit14ForkReportViewV15LabeledValueRowV AF08ItemListL0V
+ _symbolic _____y______G 7ChatKit28DetailsViewCommonContextMenuV0G4Item33_F28409D6AF308FDD12CA19D65AD16453LLV 7SwiftUI19TitleOnlyLabelStyleV
+ _symbolic _____y______G 7SwiftUI9LazyStateV7StorageO 7ChatKit26ConversationsInspectorViewV3Tab33_5837B76DFB3CAF2693E77824077F5A11LLO
+ _symbolic _____y______GSg 7ChatKit28DetailsViewCommonContextMenuV0G4Item33_F28409D6AF308FDD12CA19D65AD16453LLV 7SwiftUI19TitleOnlyLabelStyleV
+ _symbolic _____y___________Qo_ 7SwiftUI4ViewPAAE13textSelectionyQrqd__AA17TextSelectabilityRd__lFQO AA0F0V AA07EnabledfG0V
+ _symbolic _____y_______________G 7SwiftUI7SectionV AA4TextV 7ChatKit0E18PropertyEditorViewV AA05EmptyI0V
+ _symbolic _____y___________yAAy_____Sg______Sg_____SgA4eGQPG_____GQPG 7SwiftUI12TupleContentV 7ChatKit14ForkReportViewV15LabeledValueRowV AA012_ConditionalD0V AF010ScalarDiffL0V AF010CollectionoL0V AF010SequentialoL0V AF013NoDifferencesL0V
+ _symbolic _____y___________y_____ADGQPG 7SwiftUI12TupleContentV AA6SpacerV AA12ProgressViewV AA05EmptyG0V
+ _symbolic _____y___________y_____ADGQPGSg 7SwiftUI12TupleContentV AA6SpacerV AA12ProgressViewV AA05EmptyG0V
+ _symbolic _____y___________y______ACy___________y_____AGGQPGSgQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA4TextV AA6SpacerV AA08ProgressD0V AA05EmptyD0V
+ _symbolic _____y___________y__________GQo_ 7SwiftUI4ViewPAAE7tabItemyQrqd__yXEAaBRd__lFQO 7ChatKit010ForkReportC0V AA5LabelV AA4TextV AA5ImageV
+ _symbolic _____y___________y___________yACyAD______ySaySi6offset_SS7elementtGSi_____yACy_____yAKy__________y_____SgGG_____y_____GG______yAD______Qo_QPGGGQPGGSgA1_QPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA4TextV AA0F0V AA7ForEachV AA6HStackV AA08ModifiedI0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleS0V AA5ColorV AA0D0PAAE13textSelectionyQrqd__AA0J13SelectabilityRd__lFQO AA07EnabledjZ0V
+ _symbolic _____y___________y___________yAD______Qo_QPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA4TextV AA0D0PAAE13textSelectionyQrqd__AA0J13SelectabilityRd__lFQO AA07EnabledjM0V
+ _symbolic _____y___________y___________yAD______Qo______y_____yACyAD_ADQPGG_____y_____SgGG_____QPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA4TextV AA0D0PAAE13textSelectionyQrqd__AA0J13SelectabilityRd__lFQO AA07EnabledjM0V AA08ModifiedI0V AA6HStackV AA30_EnvironmentKeyWritingModifierV AA4FontV 7ChatKit010ForkReportD0V014ExpectedActualD0V
+ _symbolic _____y___________y___________yAD_____ySaySi6offset_SS7elementtGSi_____yAD______Qo_GGQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA4TextV AA012_ConditionalI0V AA7ForEachV AA0D0PAAE13textSelectionyQrqd__AA0J13SelectabilityRd__lFQO AA07EnabledjP0V
+ _symbolic _____y___________y___________ySaySi6offset_SS7elementtGSi_____yACy_____yAJy__________y_____SgGG_____y_____GG______yAD______Qo_QPGGGQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA4TextV AA7ForEachV AA6HStackV AA08ModifiedI0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleS0V AA5ColorV AA0D0PAAE13textSelectionyQrqd__AA0J13SelectabilityRd__lFQO AA07EnabledjZ0V
+ _symbolic _____y___________y_____yACy___________yAE______Qo_QPGG_AIQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA0F0V AA4TextV AA0D0PAAE13textSelectionyQrqd__AA0J13SelectabilityRd__lFQO AA07EnabledjM0V
+ _symbolic _____y___________y_____yADy__________y_____SgGG_____y_____GG______y___________Qo_QPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA08ModifiedI0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleO0V AA5ColorV AA0D0PAAE13textSelectionyQrqd__AA17TextSelectabilityRd__lFQO AA0V0V AA07EnabledvW0V
+ _symbolic _____y__________yACy_____y_____yACyACy__________y_____SgGG_____y_____GG______QPGG_____G_____GABG 7SwiftUI7SectionV AA9EmptyViewV AA15ModifiedContentV AA6VStackV AA05TupleG0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleN0V AA5ColorV AA4TextV AA16_FlexFrameLayoutV AA08_PaddingV0V
+ _symbolic _____y__________ySaySi6offset_SS7elementtGSi_____yAB______Qo_GG 7SwiftUI19_ConditionalContentV AA4TextV AA7ForEachV AA4ViewPAAE13textSelectionyQrqd__AA0E13SelectabilityRd__lFQO AA07EnabledeK0V
+ _symbolic _____y__________ySaySi6offset_SS7elementtGSi_____yAB______Qo_G_G 7SwiftUI19_ConditionalContentV7StorageO AA4TextV AA7ForEachV AA4ViewPAAE13textSelectionyQrqd__AA0F13SelectabilityRd__lFQO AA07EnabledfL0V
+ _symbolic _____y__________ySaySi6offset_So14CKConversationC7elementtGSi_____y_______________GGG 7SwiftUI4ListV s5NeverO AA7ForEachV AA7SectionV AA4TextV 7ChatKit0I18PropertyEditorViewV AA05EmptyM0V
+ _symbolic _____y__________y______AD_____A5dEQPG_____G 7SwiftUI7SectionV AA4TextV AA12TupleContentV 7ChatKit14ForkReportViewV15LabeledValueRowV AJ08ItemListN0V AA05EmptyK0V
+ _symbolic _____y__________y______AD_____A5dEQPG_____G______ySaySi6offset_So17IMChatForkingDiffC7elementtGSiAAyAbCyAD______yACy_____Sg______Sg_____SgA4qSQPG_____GQPGAGGGA_AOyAAyAG_____yA0_y_____yACyA0_yA0_y__________y_____SgGG_____y_____GG_ABQPGG_____G_____GAGGAAyAGA0_y_____yABG_____ySbGGAGGGt 7SwiftUI7SectionV AA4TextV AA12TupleContentV 7ChatKit14ForkReportViewV15LabeledValueRowV AJ08ItemListN0V AA05EmptyK0V AA7ForEachV AA012_ConditionalF0V AJ010ScalarDiffN0V AJ010CollectionvN0V AJ010SequentialvN0V AJ013NoDifferencesN0V AA08ModifiedF0V AA6VStackV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA24_ForegroundStyleModifierV AA5ColorV AA16_FlexFrameLayoutV AA14_PaddingLayoutV AA6ButtonV AA32_EnvironmentKeyTransformModifierV
+ _symbolic _____y__________y______GSgABG 7SwiftUI7SectionV AA9EmptyViewV 7ChatKit07DetailsE17CommonContextMenuV0K4Item33_F28409D6AF308FDD12CA19D65AD16453LLV AA19TitleOnlyLabelStyleV
+ _symbolic _____y__________y______GSgABGSg 7SwiftUI7SectionV AA9EmptyViewV 7ChatKit07DetailsE17CommonContextMenuV0K4Item33_F28409D6AF308FDD12CA19D65AD16453LLV AA19TitleOnlyLabelStyleV
+ _symbolic _____y__________y______GSgABG_AAyAbCy______GSgABGAGSgAGt 7SwiftUI7SectionV AA9EmptyViewV 7ChatKit07DetailsE17CommonContextMenuV0K4Item33_F28409D6AF308FDD12CA19D65AD16453LLV AA19TitleOnlyLabelStyleV AA0t7AndIconvW0V
+ _symbolic _____y__________y___________yACy_____Sg______Sg_____SgA4gIQPG_____GQPG_____G 7SwiftUI7SectionV AA4TextV AA12TupleContentV 7ChatKit14ForkReportViewV15LabeledValueRowV AA012_ConditionalF0V AJ010ScalarDiffN0V AJ010CollectionqN0V AJ010SequentialqN0V AJ013NoDifferencesN0V AA05EmptyK0V
+ _symbolic _____y__________y_____y_____G_____ySbGGABG 7SwiftUI7SectionV AA9EmptyViewV AA15ModifiedContentV AA6ButtonV AA4TextV AA32_EnvironmentKeyTransformModifierV
+ _symbolic _____y__________y_____y__________y_____y_____yACy______ACy___________yA2EGQPGSgQPGGG_____ySbGGAIGSg______ySaySi6offset_So19IMChatForkingReportC7elementtGSiACyADyAiCy______A1______A1_A1_A1_A1_A1_A2_QPGAEG_AWySaySiAX_So0bC4DiffCA_tGSiADyAiCyA1_______yACy_____Sg______Sg_____SgA10_A10_A10_A10_A12_QPG_____GQPGAEGGA20_A8_yADyAeFyAFy_____yACyAFyAFy__________y_____SgGG_____y_____GG_AIQPGG_____G_____GAEGADyAeFyAGyAIGASGAEGGQPGGSgQPGG 7SwiftUI4ListV s5NeverO AA12TupleContentV AA7SectionV AA9EmptyViewV AA08ModifiedF0V AA6ButtonV AA6HStackV AA4TextV AA6SpacerV AA08ProgressI0V AA32_EnvironmentKeyTransformModifierV AA7ForEachV 7ChatKit010ForkReportI0V15LabeledValueRowV A2_04ItemC3RowV AA012_ConditionalF0V A2_13ScalarDiffRowV A2_17CollectionDiffRowV A2_17SequentialDiffRowV A2_16NoDifferencesRowV AA6VStackV AA5ImageV AA01_pq7WritingS0V AA4FontV AA016_ForegroundStyleS0V AA5ColorV AA16_FlexFrameLayoutV AA14_PaddingLayoutV
+ _symbolic _____y__________y_____y_____y_____y______AFy___________yA2BGQPGSgQPGGG_____ySbGGAGG 7SwiftUI7SectionV AA9EmptyViewV AA15ModifiedContentV AA6ButtonV AA6HStackV AA05TupleG0V AA4TextV AA6SpacerV AA08ProgressE0V AA32_EnvironmentKeyTransformModifierV
+ _symbolic _____y__________y_____y_____y_____y______AFy___________yA2BGQPGSgQPGGG_____ySbGGAGGSg 7SwiftUI7SectionV AA9EmptyViewV AA15ModifiedContentV AA6ButtonV AA6HStackV AA05TupleG0V AA4TextV AA6SpacerV AA08ProgressE0V AA32_EnvironmentKeyTransformModifierV
+ _symbolic _____y__________y_____y_____y_____y______AFy___________yA2BGQPGSgQPGGG_____ySbGGAGGSg______ySaySi6offset_So19IMChatForkingReportC7elementtGSiAFyAAyAgFy______A______A_A_A_A_A_A0_QPGABG_AUySaySiAV_So0bC4DiffCAYtGSiAAyAgFyA_______yAFy_____Sg______Sg_____SgA8_A8_A8_A8_A10_QPG_____GQPGABGGA18_A6_yAAyAbCyACy_____yAFyACyACy__________y_____SgGG_____y_____GG_AGQPGG_____G_____GABGAAyAbCyADyAGGAQGABGGQPGGSgt 7SwiftUI7SectionV AA9EmptyViewV AA15ModifiedContentV AA6ButtonV AA6HStackV AA05TupleG0V AA4TextV AA6SpacerV AA08ProgressE0V AA32_EnvironmentKeyTransformModifierV AA7ForEachV 7ChatKit010ForkReportE0V15LabeledValueRowV AZ08ItemListZ0V AA012_ConditionalG0V AZ010ScalarDiffZ0V AZ014CollectionDiffZ0V AZ014SequentialDiffZ0V AZ013NoDifferencesZ0V AA6VStackV AA5ImageV AA01_no7WritingQ0V AA4FontV AA016_ForegroundStyleQ0V AA5ColorV AA16_FlexFrameLayoutV AA14_PaddingLayoutV
+ _symbolic _____y_____yAAyABy___________yAC______Qo_QPGG_AGQPGG 7SwiftUI6VStackV AA12TupleContentV AA4TextV AA4ViewPAAE13textSelectionyQrqd__AA0F13SelectabilityRd__lFQO AA07EnabledfJ0V
+ _symbolic _____y_____y_____AAy______AD_____A5dEQPG_____G______ySaySi6offset_So17IMChatForkingDiffC7elementtGSiAByAcAyAD______yAAy_____Sg______Sg_____SgA4qSQPG_____GQPGAGGGA_AOyAByAG_____yA0_y_____yAAyA0_yA0_y__________y_____SgGG_____y_____GG_ACQPGG_____G_____GAGGAByAGA0_y_____yACG_____ySbGGAGGGQPG 7SwiftUI12TupleContentV AA7SectionV AA4TextV 7ChatKit14ForkReportViewV15LabeledValueRowV AJ08ItemListN0V AA05EmptyK0V AA7ForEachV AA012_ConditionalD0V AJ010ScalarDiffN0V AJ010CollectionvN0V AJ010SequentialvN0V AJ013NoDifferencesN0V AA08ModifiedD0V AA6VStackV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA24_ForegroundStyleModifierV AA5ColorV AA16_FlexFrameLayoutV AA14_PaddingLayoutV AA6ButtonV AA32_EnvironmentKeyTransformModifierV
+ _symbolic _____y_____y_____Sg______Sg_____SgA4dFQPG_____G 7SwiftUI19_ConditionalContentV AA05TupleD0V 7ChatKit14ForkReportViewV13ScalarDiffRowV AH010CollectionlM0V AH010SequentiallM0V AH013NoDifferencesM0V
+ _symbolic _____y_____y______AAyAByAC______ySaySi6offset_SS7elementtGSi_____yABy_____yAIy__________y_____SgGG_____y_____GG______yAC______Qo_QPGGGQPGGSgA_QPGG 7SwiftUI6VStackV AA12TupleContentV AA4TextV AA7ForEachV AA6HStackV AA08ModifiedE0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleO0V AA5ColorV AA4ViewPAAE13textSelectionyQrqd__AA0F13SelectabilityRd__lFQO AA07EnabledfW0V
+ _symbolic _____y_____y______ABy___________y_____AFGQPGSgQPGG 7SwiftUI6HStackV AA12TupleContentV AA4TextV AA6SpacerV AA12ProgressViewV AA05EmptyI0V
+ _symbolic _____y_____y______ACQPGG 7SwiftUI6HStackV AA12TupleContentV AA4TextV
+ _symbolic _____y_____y___________QPGG 7SwiftUI6VStackV AA12TupleContentV AA4TextV 7ChatKit14ForkReportViewV014ExpectedActualK0V
+ _symbolic _____y_____y___________yAC______Qo_QPGG 7SwiftUI6VStackV AA12TupleContentV AA4TextV AA4ViewPAAE13textSelectionyQrqd__AA0F13SelectabilityRd__lFQO AA07EnabledfJ0V
+ _symbolic _____y_____y___________yAC______Qo_QPGG_AGt 7SwiftUI6VStackV AA12TupleContentV AA4TextV AA4ViewPAAE13textSelectionyQrqd__AA0F13SelectabilityRd__lFQO AA07EnabledfJ0V
+ _symbolic _____y_____y___________yAC______Qo______y_____yAByAC_ACQPGG_____y_____SgGG_____QPGG 7SwiftUI6VStackV AA12TupleContentV AA4TextV AA4ViewPAAE13textSelectionyQrqd__AA0F13SelectabilityRd__lFQO AA07EnabledfJ0V AA08ModifiedE0V AA6HStackV AA30_EnvironmentKeyWritingModifierV AA4FontV 7ChatKit010ForkReportG0V014ExpectedActualG0V
+ _symbolic _____y_____y___________yAC_____ySaySi6offset_SS7elementtGSi_____yAC______Qo_GGQPGG 7SwiftUI6VStackV AA12TupleContentV AA4TextV AA012_ConditionalE0V AA7ForEachV AA4ViewPAAE13textSelectionyQrqd__AA0F13SelectabilityRd__lFQO AA07EnabledfM0V
+ _symbolic _____y_____y___________ySaySi6offset_SS7elementtGSi_____yABy_____yAIy__________y_____SgGG_____y_____GG______yAC______Qo_QPGGGQPGG 7SwiftUI6VStackV AA12TupleContentV AA4TextV AA7ForEachV AA6HStackV AA08ModifiedE0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleO0V AA5ColorV AA4ViewPAAE13textSelectionyQrqd__AA0F13SelectabilityRd__lFQO AA07EnabledfW0V
+ _symbolic _____y_____y___________ySaySi6offset_SS7elementtGSi_____yABy_____yAIy__________y_____SgGG_____y_____GG______yAC______Qo_QPGGGQPGGSg 7SwiftUI6VStackV AA12TupleContentV AA4TextV AA7ForEachV AA6HStackV AA08ModifiedE0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleO0V AA5ColorV AA4ViewPAAE13textSelectionyQrqd__AA0F13SelectabilityRd__lFQO AA07EnabledfW0V
+ _symbolic _____y_____y___________y__________GQo_______Qo_ 7SwiftUI4ViewPAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AcAE7tabItemyQrqd__yXEAaBRd__lFQO 7ChatKit010ForkReportC0V AA5LabelV AA4TextV AA5ImageV AG022ConversationsInspectorC0V3Tab33_5837B76DFB3CAF2693E77824077F5A11LLO
+ _symbolic _____y_____y___________y__________GQo______y_____GG 7SwiftUI15ModifiedContentV AA4ViewPAAE7tabItemyQrqd__yXEAaDRd__lFQO 7ChatKit010ForkReportE0V AA5LabelV AA4TextV AA5ImageV AA24_TagTraitWritingModifierV AG022ConversationsInspectorE0V3Tab33_5837B76DFB3CAF2693E77824077F5A11LLO
+ _symbolic _____y_____y__________yADy_____y_____yADyADy__________y_____SgGG_____y_____GG______QPGG_____G_____GACGAByAcDy_____yAQG_____ySbGGACGG 7SwiftUI19_ConditionalContentV AA7SectionV AA9EmptyViewV AA08ModifiedD0V AA6VStackV AA05TupleD0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleO0V AA5ColorV AA4TextV AA16_FlexFrameLayoutV AA08_PaddingW0V AA6ButtonV AA01_lm9TransformO0V
+ _symbolic _____y_____y__________yADy_____y_____yADyADy__________y_____SgGG_____y_____GG______QPGG_____G_____GACGAByAcDy_____yAQG_____ySbGGACG_G 7SwiftUI19_ConditionalContentV7StorageO AA7SectionV AA9EmptyViewV AA08ModifiedD0V AA6VStackV AA05TupleD0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleP0V AA5ColorV AA4TextV AA16_FlexFrameLayoutV AA08_PaddingX0V AA6ButtonV AA01_mn9TransformP0V
+ _symbolic _____y_____y__________ySaySi6offset_So14CKConversationC7elementtGSi_____y_______________GGG______yAJ_____GQo_ 7SwiftUI4ViewPAAE7tabItemyQrqd__yXEAaBRd__lFQO AA4ListV s5NeverO AA7ForEachV AA7SectionV AA4TextV 7ChatKit0l14PropertyEditorC0V AA05EmptyC0V AA5LabelV AA5ImageV
+ _symbolic _____y_____y__________y______GSgACG_AByAcDy______GSgACGAHSgAHQPG 7SwiftUI12TupleContentV AA7SectionV AA9EmptyViewV 7ChatKit07DetailsG17CommonContextMenuV0M4Item33_F28409D6AF308FDD12CA19D65AD16453LLV AA19TitleOnlyLabelStyleV AA0v7AndIconxY0V
+ _symbolic _____y_____y__________y_____y_____yAAy______AAy___________yA2CGQPGSgQPGGG_____ySbGGAGGSg______ySaySi6offset_So19IMChatForkingReportC7elementtGSiAAyAByAgAy______A______A_A_A_A_A_A0_QPGACG_AUySaySiAV_So0bC4DiffCAYtGSiAByAgAyA_______yAAy_____Sg______Sg_____SgA8_A8_A8_A8_A10_QPG_____GQPGACGGA18_A6_yAByAcDyADy_____yAAyADyADy__________y_____SgGG_____y_____GG_AGQPGG_____G_____GACGAByAcDyAEyAGGAQGACGGQPGGSgQPG 7SwiftUI12TupleContentV AA7SectionV AA9EmptyViewV AA08ModifiedD0V AA6ButtonV AA6HStackV AA4TextV AA6SpacerV AA08ProgressG0V AA32_EnvironmentKeyTransformModifierV AA7ForEachV 7ChatKit010ForkReportG0V15LabeledValueRowV AZ08ItemListZ0V AA012_ConditionalD0V AZ010ScalarDiffZ0V AZ014CollectionDiffZ0V AZ014SequentialDiffZ0V AZ013NoDifferencesZ0V AA6VStackV AA5ImageV AA01_no7WritingQ0V AA4FontV AA016_ForegroundStyleQ0V AA5ColorV AA16_FlexFrameLayoutV AA14_PaddingLayoutV
+ _symbolic _____y_____y__________y_____y_____y_____y__________ySaySi6offset_So14CKConversationC7elementtGSi_____y_____AGy_____yS2SSg_GSS_____SgG_____GGG______yAN_____GQo__ACQo_______y_____yAEyAfGyALSiAMyAN_____AUGGG_A_Qo__ACQo______y_____y______A_Qo__ACQo_QPGGG 7ChatKit27DebugInspectorContainerViewV 7SwiftUI03TabF0V AA013ConversationsdF0V0I033_5837B76DFB3CAF2693E77824077F5A11LLO AD12TupleContentV AD0F0PADE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AoDE7tabItemyQrqd__yXEAdNRd__lFQO AD4ListV s5NeverO AD7ForEachV AD7SectionV AD4TextV 19CollectionsInternal17OrderedDictionaryV8ElementsV AA0cd4CellF0V AD05EmptyF0V AD5LabelV AD5ImageV AoDEAP_AQQrqd___SbtSHRd__lFQO AoDEARyQrqd__yXEAdNRd__lFQO AA0a14PropertyEditorF0V AoDEAP_AQQrqd___SbtSHRd__lFQO AoDEARyQrqd__yXEAdNRd__lFQO AA010ForkReportF0V
+ _symbolic _____y_____y_____yAAyAAy__________y_____SgGG_____y_____GG______QPGG_____G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleK0V AA5ColorV AA4TextV AA16_FlexFrameLayoutV
+ _symbolic _____y_____y_____yAAy__________y_____GG______QPGG_____G 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5ImageV AA24_ForegroundStyleModifierV AA5ColorV AA4TextV AA14_PaddingLayoutV
+ _symbolic _____y_____y_____yACy__________y_____SgGG_____y_____GG______QPGG 7SwiftUI6VStackV AA12TupleContentV AA08ModifiedE0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleK0V AA5ColorV AA4TextV
+ _symbolic _____y_____y_____yACy__________y_____SgGG_____y_____GG______y___________Qo_QPGG 7SwiftUI6HStackV AA12TupleContentV AA08ModifiedE0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleK0V AA5ColorV AA4ViewPAAE13textSelectionyQrqd__AA17TextSelectabilityRd__lFQO AA0S0V AA07EnabledsT0V
+ _symbolic _____y_____y_____y_____G______y_____y_____y__________y______GSgAHG_AGyAhIy______GSgAHGAMSgAMQPGG_____Qo______yAD_ATQo_G 7SwiftUI19_ConditionalContentV AA4ViewPAAE11contextMenu9menuItems7preview0J6ActionQrqd__yXE_qd_0_yXEyyctAaDRd__AaDRd_0_r0_lFQO AA01_e9Modifier_D0V 7ChatKit07Detailse13CommonContextG0V AA5GroupV AA05TupleD0V AA7SectionV AA05EmptyE0V AN0G4Item33_F28409D6AF308FDD12CA19D65AD16453LLV AA19TitleOnlyLabelStyleV AA22TitleAndIconLabelStyleV AN34CKQLPreviewControllerRepresentableAXLLV AeAEAfGQrqd__yXE_tAaDRd__lFQO
+ _symbolic _____y_____y_____y_____G______y_____y_____y__________y______GSgAHG_AGyAhIy______GSgAHGAMSgAMQPGG_____Qo______yAD_ATQo__G 7SwiftUI19_ConditionalContentV7StorageO AA4ViewPAAE11contextMenu9menuItems7preview0K6ActionQrqd__yXE_qd_0_yXEyyctAaFRd__AaFRd_0_r0_lFQO AA01_f9Modifier_D0V 7ChatKit07Detailsf13CommonContextH0V AA5GroupV AA05TupleD0V AA7SectionV AA05EmptyF0V AP0H4Item33_F28409D6AF308FDD12CA19D65AD16453LLV AA19TitleOnlyLabelStyleV AA22TitleAndIconLabelStyleV AP34CKQLPreviewControllerRepresentableAZLLV AgAEAhIQrqd__yXE_tAaFRd__lFQO
+ _symbolic _____y_____y_____y______AByACyAD______ySaySi6offset_SS7elementtGSi_____yACyAAyAAy__________y_____SgGG_____y_____GG______yAD______Qo_QPGGGQPGGSgA_QPGG_____G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA4TextV AA7ForEachV AA6HStackV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA016_ForegroundStyleO0V AA5ColorV AA4ViewPAAE13textSelectionyQrqd__AA0G13SelectabilityRd__lFQO AA07EnabledgW0V AA14_PaddingLayoutV
+ _symbolic _____y_____y_____y______ACy___________y_____AGGQPGSgQPGGG 7SwiftUI6ButtonV AA6HStackV AA12TupleContentV AA4TextV AA6SpacerV AA12ProgressViewV AA05EmptyJ0V
+ _symbolic _____y_____y_____y______ADQPGG_____y_____SgGG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA4TextV AA30_EnvironmentKeyWritingModifierV AA4FontV
+ _symbolic _____y_____y_____y___________QPGG_____G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA4TextV 7ChatKit14ForkReportViewV014ExpectedActualL0V AA14_PaddingLayoutV
+ _symbolic _____y_____y_____y___________yAD______Qo_AAy_____yACyAD_ADQPGG_____y_____SgGG_____QPGG_____G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA4TextV AA4ViewPAAE13textSelectionyQrqd__AA0G13SelectabilityRd__lFQO AA07EnabledgK0V AA6HStackV AA30_EnvironmentKeyWritingModifierV AA4FontV 7ChatKit010ForkReportH0V014ExpectedActualH0V AA14_PaddingLayoutV
+ _symbolic _____y_____y_____y___________yAD______Qo_QPGG_____G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA4TextV AA4ViewPAAE13textSelectionyQrqd__AA0G13SelectabilityRd__lFQO AA07EnabledgK0V AA14_PaddingLayoutV
+ _symbolic _____y_____y_____y___________yAD_____ySaySi6offset_SS7elementtGSi_____yAD______Qo_GGQPGG_____G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA4TextV AA012_ConditionalD0V AA7ForEachV AA4ViewPAAE13textSelectionyQrqd__AA0G13SelectabilityRd__lFQO AA07EnabledgN0V AA14_PaddingLayoutV
+ _symbolic _____y_____y_____y__________ySaySi6offset_So14CKConversationC7elementtGSi_____y_____ACy_____yS2SSg_GSS_____SgG_____GGG______yAJ_____GQo_______Qo_ 7SwiftUI4ViewPAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AcAE7tabItemyQrqd__yXEAaBRd__lFQO AA4ListV s5NeverO AA7ForEachV AA7SectionV AA4TextV 19CollectionsInternal17OrderedDictionaryV8ElementsV 7ChatKit018DebugInspectorCellC0V AA05EmptyC0V AA5LabelV AA5ImageV AV013ConversationswC0V3Tab33_5837B76DFB3CAF2693E77824077F5A11LLO
+ _symbolic _____y_____y_____y__________ySaySi6offset_So14CKConversationC7elementtGSi_____y_____ACy_____yS2SSg_GSS_____SgG_____GGG______yAJ_____GQo_______Qo_______y_____yAAyAbCyAHSiAIyAJ_____AQGGG_AWQo__AYQo______y_____y______AWQo__AYQo_t 7SwiftUI4ViewPAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AcAE7tabItemyQrqd__yXEAaBRd__lFQO AA4ListV s5NeverO AA7ForEachV AA7SectionV AA4TextV 19CollectionsInternal17OrderedDictionaryV8ElementsV 7ChatKit018DebugInspectorCellC0V AA05EmptyC0V AA5LabelV AA5ImageV AV013ConversationswC0V3Tab33_5837B76DFB3CAF2693E77824077F5A11LLO AcAEAD_AEQrqd___SbtSHRd__lFQO AcAEAFyQrqd__yXEAaBRd__lFQO AV0t14PropertyEditorC0V AcAEAD_AEQrqd___SbtSHRd__lFQO AcAEAFyQrqd__yXEAaBRd__lFQO AV010ForkReportC0V
+ _symbolic _____y_____y_____y__________ySaySi6offset_So14CKConversationC7elementtGSi_____y_____ADy_____yS2SSg_GSS_____SgG_____GGG______yAK_____GQo______y_____GG 7SwiftUI15ModifiedContentV AA4ViewPAAE7tabItemyQrqd__yXEAaDRd__lFQO AA4ListV s5NeverO AA7ForEachV AA7SectionV AA4TextV 19CollectionsInternal17OrderedDictionaryV8ElementsV 7ChatKit018DebugInspectorCellE0V AA05EmptyE0V AA5LabelV AA5ImageV AA24_TagTraitWritingModifierV AV013ConversationsvE0V3Tab33_5837B76DFB3CAF2693E77824077F5A11LLO
+ _symbolic _____y_____y_____y__________ySaySi6offset_So14CKConversationC7elementtGSi_____y_______________GGG______yAJ_____GQo_______Qo_ 7SwiftUI4ViewPAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AcAE7tabItemyQrqd__yXEAaBRd__lFQO AA4ListV s5NeverO AA7ForEachV AA7SectionV AA4TextV 7ChatKit0o14PropertyEditorC0V AA05EmptyC0V AA5LabelV AA5ImageV AQ022ConversationsInspectorC0V3Tab33_5837B76DFB3CAF2693E77824077F5A11LLO
+ _symbolic _____y_____y_____y__________ySaySi6offset_So14CKConversationC7elementtGSi_____y_______________GGG______yAK_____GQo______y_____GG 7SwiftUI15ModifiedContentV AA4ViewPAAE7tabItemyQrqd__yXEAaDRd__lFQO AA4ListV s5NeverO AA7ForEachV AA7SectionV AA4TextV 7ChatKit0n14PropertyEditorE0V AA05EmptyE0V AA5LabelV AA5ImageV AA24_TagTraitWritingModifierV AQ022ConversationsInspectorE0V3Tab33_5837B76DFB3CAF2693E77824077F5A11LLO
+ _symbolic _____y_____y_____y__________y_____GG______QPGG 7SwiftUI6HStackV AA12TupleContentV AA08ModifiedE0V AA5ImageV AA24_ForegroundStyleModifierV AA5ColorV AA4TextV
+ _symbolic _____y_____y_____y__________y______GSgADG_ACyAdEy______GSgADGAISgAIQPGG 7SwiftUI5GroupV AA12TupleContentV AA7SectionV AA9EmptyViewV 7ChatKit07DetailsH17CommonContextMenuV0N4Item33_F28409D6AF308FDD12CA19D65AD16453LLV AA19TitleOnlyLabelStyleV AA0w7AndIconyZ0V
+ _symbolic _____y_____y_____y_____y______ADy___________y_____AHGQPGSgQPGGG_____ySbGG 7SwiftUI15ModifiedContentV AA6ButtonV AA6HStackV AA05TupleD0V AA4TextV AA6SpacerV AA12ProgressViewV AA05EmptyK0V AA32_EnvironmentKeyTransformModifierV
+ _symbolic _____y_____y_____y_____y__________ySaySi6offset_So14CKConversationC7elementtGSi_____y_____ADy_____yS2SSg_GSS_____SgG_____GGG______yAK_____GQo_______Qo_______y_____yAByAcDyAISiAJyAK_____ARGGG_AXQo__AZQo______y_____y______AXQo__AZQo_QPG 7SwiftUI12TupleContentV AA4ViewPAAE3tag_15includeOptionalQrqd___SbtSHRd__lFQO AeAE7tabItemyQrqd__yXEAaDRd__lFQO AA4ListV s5NeverO AA7ForEachV AA7SectionV AA4TextV 19CollectionsInternal17OrderedDictionaryV8ElementsV 7ChatKit018DebugInspectorCellE0V AA05EmptyE0V AA5LabelV AA5ImageV AX013ConversationsyE0V3Tab33_5837B76DFB3CAF2693E77824077F5A11LLO AeAEAF_AGQrqd___SbtSHRd__lFQO AeAEAHyQrqd__yXEAaDRd__lFQO AX0v14PropertyEditorE0V AeAEAF_AGQrqd___SbtSHRd__lFQO AeAEAHyQrqd__yXEAaDRd__lFQO AX010ForkReportE0V
+ _type_layout_string 7ChatKit14ForkReportViewV11ItemListRowV
+ _type_layout_string 7ChatKit14ForkReportViewV13ScalarDiffRowV
+ _type_layout_string 7ChatKit14ForkReportViewV15LabeledValueRowV
+ _type_layout_string 7ChatKit14ForkReportViewV16NoDifferencesRowV
+ _type_layout_string 7ChatKit14ForkReportViewV17CollectionDiffRowV
+ _type_layout_string 7ChatKit14ForkReportViewV17SequentialDiffRowV
+ _type_layout_string 7ChatKit24MiCAccountNeedsRepairTipV
- +[CABasicAnimation(SendAnimation) ck_positionXAnimationForSendAnimationType:beginTime:initialPositionX:finalPositionX:durationScaleFactor:delegate:]
- +[CABasicAnimation(SendAnimation) ck_positionYAnimationForSendAnimationType:beginTime:initialPositionY:finalPositionY:durationScaleFactor:delegate:]
- +[CKBalloonChatItem(MaxWidthComputation) resultingMaxWidthWithBalloonMaxWidth:fullMaxWidth:transcriptTraitCollection:transcriptBackgroundLuminance:]
- +[CKChatItem resultingMaxWidthWithBalloonMaxWidth:fullMaxWidth:transcriptTraitCollection:transcriptBackgroundLuminance:]
- +[CKChatItem(CKChatItems) chatItemWithIMChatItem:balloonMaxWidth:fullMaxWidth:transcriptTraitCollection:transcriptBackgroundLuminance:overlayLayout:]
- +[CKThrowAnimationManager nonGlassThrowSendAnimationManager]
- +[CKTranscriptPluginChatItem(MaxWidthComputation) resultingMaxWidthWithBalloonMaxWidth:fullMaxWidth:transcriptTraitCollection:transcriptBackgroundLuminance:]
- -[CKAssociatedMessageTranscriptCell setTranscriptBackgroundLuminance:]
- -[CKAssociatedMessageTranscriptCell transcriptBackgroundLuminance]
- -[CKAttachmentMessagePartChatItem transcriptBackgroundLuminance]
- -[CKBackgroundGalleryFetchRequest initWithPreferredSuggestionCount:extensionIdentifiers:fallbackExtensionIdentifiers:]
- -[CKChatController(CKChatController_Stickers) saveStickerFromChatItem:pluginSourceView:animateFlyIn:]
- -[CKChatController(SendAnimation) _makeThrowBalloonsForSendAnimationWithType:inContainerView:forSendingMessages:shouldUseQuickReplySourceRect:quickReplySourceRect:quickReplySnapshotView:audioMessageSourceRect:audioRecordingPillViewSnapshot:]
- -[CKChatController(SendAnimation) _shouldHideNavigationBarForSendAnimationContext:]
- -[CKChatController(SendAnimation) _throwBalloonAttributesForSendAnimationWithType:shouldUseQuickReplySourceRect:quickReplySourceRect:isRunningPhotosPlugin:chatItem:isPhotosExtensionMediaPayload:pluginChatItemCounterInOut:containerView:isChatItemFromShelf:isLastChatItem:currentBalloonOriginInOut:quickReplySnapshotView:]
- -[CKChatControllerCoordinator preferredTranscriptNavigationBarContextFlagsForProposedFlags:]
- -[CKChatControllerDummyAnimator __beginThrowAnimationWithThrowBalloonViewAttributesCollection:framesOfAddedChatItems:sendAnimationType:entryViewSize:]
- -[CKChatControllerDummyAnimator _throwAnimationDurationScaleFactorForThrownBalloonAttributes:finalBalloonFrames:sendAnimationType:]
- -[CKChatControllerDummyAnimator balloonViewFadeAnimationForConvertedCurrentMediaTime:direction:sendAnimationType:]
- -[CKChatItem setTranscriptBackgroundLuminance:]
- -[CKChatItem transcriptBackgroundLuminance]
- -[CKChatItem updateWithBalloonMaxWidth:fullMaxWidth:transcriptTraitCollection:transcriptBackgroundLuminance:wantsOverlayLayout:metricsProvider:getDidUpdate:]
- -[CKConversationListCollectionViewController coordinator]
- -[CKConversationListCollectionViewController setCoordinator:]
- -[CKConversationListCollectionViewControllerCoordinator .cxx_destruct]
- -[CKConversationListCollectionViewControllerCoordinator initWithConversationListCollectionViewController:]
- -[CKConversationListCollectionViewControllerCoordinator preferredWantsBottomAlignedComposeButtonForProposal:]
- -[CKConversationListCollectionViewControllerCoordinator setWrappedCoordinator:]
- -[CKConversationListCollectionViewControllerCoordinator wrappedCoordinator]
- -[CKCoreChatController setShouldOpenMediaObjectAfterDownload:]
- -[CKCoreChatController shouldOpenMediaObjectAfterDownload]
- -[CKCoreChatController transcriptCollectionViewController:viewedCommSafetyAssociatedItemsWithIndexPath:updatedSensitivityAnalysis:]
- -[CKCoreChatController transcriptCollectionViewController:viewedCommSafetyItemWithIndexPath:updatedSensitivityAnalysis:]
- -[CKCoreChatController(UserSafety) presentCommSafetyInterventionIfNecessaryForMediaObject:willPresentHandler:sendHandler:]
- -[CKMediaObject gradientSize]
- -[CKMediaObject preflightThumbnailImage]
- -[CKMediaObject setPreflightThumbnailImage:]
- -[CKMediaObject(Display) invalidateNonPreflightPreviewForOrientation:]
- -[CKNotificationContentViewController viewDidLoad]
- -[CKObscurableBalloonView _presentGetHelpAlert:]
- -[CKPosterRenderingTranscriptBackground traitCollectionDidChange:]
- -[CKSendAnimationContext sendAnimationType]
- -[CKSendAnimationContext setSendAnimationType:]
- -[CKThrowAnimationManager initWithSendAnimationType:]
- -[CKThrowAnimationManager sendAnimationType]
- -[CKThrowAnimationManager sendAnimationWindow]
- -[CKThrowAnimationManager setSendAnimationType:]
- -[CKThrowAnimationManager setSendAnimationWindow:]
- -[CKTranscriptCollectionViewController invalidateChatItemLayoutWithNewBalloonMaxWidth:marginInsets:traitCollection:transcriptBackgroundLuminance:]
- -[CKTranscriptCollectionViewController isReportingEnabled]
- -[CKTranscriptCollectionViewController newChatItemWithIMChatItem:traitCollection:transcriptBackgroundLuminance:]
- -[CKTranscriptCollectionViewController setTranscriptBackgroundLuminance:]
- -[CKTranscriptCollectionViewController traitCollectionDidChange:]
- -[CKTranscriptCollectionViewController transcriptBackgroundLuminance]
- -[CKTranscriptCollectionViewController updateTranscriptBackgroundLuminanceToMatchBackgroundColor]
- -[CKTranscriptCollectionViewController(UserSafety) _moreHelpMenuOptions:]
- -[CKTranscriptCollectionViewController(UserSafety) _updateCommSafetySensitivityForContentAtIndexPath:shouldTargetAssociatedMessages:updatedSensitivityAnalysis:]
- -[CKTranscriptModel chatItemWithIMChatItem:traitCollection:transcriptBackgroundLuminance:]
- -[CKTranscriptPreviewController transcriptCollectionViewController:viewedCommSafetyAssociatedItemsWithIndexPath:updatedSensitivityAnalysis:]
- -[CKTranscriptPreviewController transcriptCollectionViewController:viewedCommSafetyItemWithIndexPath:updatedSensitivityAnalysis:]
- -[CKTypingView setTranscriptBackgroundLuminance:]
- -[CKTypingView transcriptBackgroundLuminance]
- GCC_except_table1003
- GCC_except_table1004
- GCC_except_table1015
- GCC_except_table1021
- GCC_except_table1022
- GCC_except_table1026
- GCC_except_table1027
- GCC_except_table1032
- GCC_except_table1033
- GCC_except_table1042
- GCC_except_table1065
- GCC_except_table1074
- GCC_except_table1081
- GCC_except_table1112
- GCC_except_table1114
- GCC_except_table1137
- GCC_except_table1142
- GCC_except_table1144
- GCC_except_table1189
- GCC_except_table1191
- GCC_except_table1193
- GCC_except_table1195
- GCC_except_table1199
- GCC_except_table1203
- GCC_except_table1205
- GCC_except_table1210
- GCC_except_table1218
- GCC_except_table1236
- GCC_except_table1247
- GCC_except_table164
- GCC_except_table194
- GCC_except_table238
- GCC_except_table260
- GCC_except_table263
- GCC_except_table264
- GCC_except_table286
- GCC_except_table290
- GCC_except_table296
- GCC_except_table302
- GCC_except_table306
- GCC_except_table307
- GCC_except_table313
- GCC_except_table324
- GCC_except_table331
- GCC_except_table337
- GCC_except_table344
- GCC_except_table365
- GCC_except_table368
- GCC_except_table369
- GCC_except_table383
- GCC_except_table386
- GCC_except_table399
- GCC_except_table408
- GCC_except_table411
- GCC_except_table417
- GCC_except_table420
- GCC_except_table424
- GCC_except_table432
- GCC_except_table441
- GCC_except_table450
- GCC_except_table458
- GCC_except_table466
- GCC_except_table468
- GCC_except_table477
- GCC_except_table485
- GCC_except_table486
- GCC_except_table487
- GCC_except_table493
- GCC_except_table494
- GCC_except_table505
- GCC_except_table507
- GCC_except_table513
- GCC_except_table521
- GCC_except_table527
- GCC_except_table530
- GCC_except_table532
- GCC_except_table534
- GCC_except_table547
- GCC_except_table563
- GCC_except_table566
- GCC_except_table567
- GCC_except_table577
- GCC_except_table584
- GCC_except_table591
- GCC_except_table592
- GCC_except_table595
- GCC_except_table596
- GCC_except_table598
- GCC_except_table609
- GCC_except_table612
- GCC_except_table617
- GCC_except_table618
- GCC_except_table619
- GCC_except_table628
- GCC_except_table629
- GCC_except_table637
- GCC_except_table645
- GCC_except_table648
- GCC_except_table653
- GCC_except_table656
- GCC_except_table661
- GCC_except_table662
- GCC_except_table663
- GCC_except_table664
- GCC_except_table667
- GCC_except_table674
- GCC_except_table678
- GCC_except_table682
- GCC_except_table683
- GCC_except_table687
- GCC_except_table691
- GCC_except_table695
- GCC_except_table698
- GCC_except_table700
- GCC_except_table708
- GCC_except_table715
- GCC_except_table716
- GCC_except_table730
- GCC_except_table731
- GCC_except_table745
- GCC_except_table748
- GCC_except_table751
- GCC_except_table753
- GCC_except_table754
- GCC_except_table758
- GCC_except_table760
- GCC_except_table766
- GCC_except_table769
- GCC_except_table770
- GCC_except_table772
- GCC_except_table777
- GCC_except_table782
- GCC_except_table783
- GCC_except_table784
- GCC_except_table785
- GCC_except_table817
- GCC_except_table820
- GCC_except_table824
- GCC_except_table849
- GCC_except_table850
- GCC_except_table859
- GCC_except_table865
- GCC_except_table866
- GCC_except_table875
- GCC_except_table886
- GCC_except_table891
- GCC_except_table914
- GCC_except_table934
- GCC_except_table938
- GCC_except_table949
- GCC_except_table950
- GCC_except_table954
- GCC_except_table962
- GCC_except_table964
- GCC_except_table968
- GCC_except_table976
- GCC_except_table978
- GCC_except_table982
- GCC_except_table986
- GCC_except_table987
- GCC_except_table988
- GCC_except_table994
- GCC_except_table998
- _CKCommSafetyReceiveContextDictionary
- _IMGetUserRegistrationFailureIntent
- _IMUserRegistrationFailureIntentChanged
- _OBJC_CLASS_$_CKConversationListCollectionViewControllerCoordinator
- _OBJC_CLASS_$_CKEntryViewPlusButton
- _OBJC_CLASS_$_CKGlassSendMenuButton
- _OBJC_IVAR_$_CKAssociatedMessageTranscriptCell._transcriptBackgroundLuminance
- _OBJC_IVAR_$_CKAttachmentMessagePartChatItem._transcriptBackgroundLuminance
- _OBJC_IVAR_$_CKChatItem._transcriptBackgroundLuminance
- _OBJC_IVAR_$_CKConversationListCollectionViewController._coordinator
- _OBJC_IVAR_$_CKConversationListCollectionViewControllerCoordinator._wrappedCoordinator
- _OBJC_IVAR_$_CKCoreChatController._shouldOpenMediaObjectAfterDownload
- _OBJC_IVAR_$_CKMediaObject._preflightThumbnailImage
- _OBJC_IVAR_$_CKSendAnimationContext.sendAnimationType
- _OBJC_IVAR_$_CKThrowAnimationManager._sendAnimationType
- _OBJC_IVAR_$_CKThrowAnimationManager._sendAnimationWindow
- _OBJC_IVAR_$_CKTranscriptCollectionViewController._transcriptBackgroundLuminance
- _OBJC_IVAR_$_CKTypingView._transcriptBackgroundLuminance
- _OBJC_METACLASS_$_CKConversationListCollectionViewControllerCoordinator
- _OBJC_METACLASS_$_CKEntryViewPlusButton
- _OBJC_METACLASS_$_CKGlassSendMenuButton
- _OBJC_METACLASS_$__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387320PlusButtonButtonView
- _OBJC_METACLASS_$__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387322PlusButtonClippingView
- _OBJC_METACLASS_$__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387327PlusButtonBlurContainerView
- _OBJC_METACLASS_$__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387328PlusButtonBlurBackgroundView
- _OBJC_METACLASS_$__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387331PlusButtonBlendedBackgroundView
- __CLASS_METHODS_CKGlassSendMenuButton
- __DATA_CKEntryViewPlusButton
- __DATA_CKGlassSendMenuButton
- __DATA__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387320PlusButtonButtonView
- __DATA__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387322PlusButtonClippingView
- __DATA__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387327PlusButtonBlurContainerView
- __DATA__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387328PlusButtonBlurBackgroundView
- __DATA__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387331PlusButtonBlendedBackgroundView
- __INSTANCE_METHODS__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387320PlusButtonButtonView
- __INSTANCE_METHODS__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387322PlusButtonClippingView
- __INSTANCE_METHODS__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387327PlusButtonBlurContainerView
- __INSTANCE_METHODS__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387328PlusButtonBlurBackgroundView
- __INSTANCE_METHODS__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387331PlusButtonBlendedBackgroundView
- __IVARS_CKEntryViewPlusButton
- __IVARS_CKGlassSendMenuButton
- __IVARS__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387322PlusButtonClippingView
- __IVARS__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387327PlusButtonBlurContainerView
- __MEPConversationListCollectionViewControllerCoordinatorClass
- __MEPConversationListCollectionViewControllerCoordinatorClass.onceToken
- __MEPConversationListCollectionViewControllerCoordinatorClass.result
- __METACLASS_DATA_CKEntryViewPlusButton
- __METACLASS_DATA_CKGlassSendMenuButton
- __METACLASS_DATA__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387320PlusButtonButtonView
- __METACLASS_DATA__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387322PlusButtonClippingView
- __METACLASS_DATA__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387327PlusButtonBlurContainerView
- __METACLASS_DATA__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387328PlusButtonBlurBackgroundView
- __METACLASS_DATA__TtC7ChatKitP33_3A4F9EFB16D832C5123E30AA2C9D387331PlusButtonBlendedBackgroundView
- __OBJC_$_CLASS_METHODS__TtC7ChatKit34CKCommunicationSafetyFlowPresenter(ChatKit|ChatKit1)
- __OBJC_$_INSTANCE_METHODS_CKChatController(MacToolbar|ClickyOrbConformance|CKChatController_Stickers|CKStickerDetailViewControllerDelegate|ChatItemSelection|Debug|ImpactEffectPicker|MenuBar|MessageHistoryViewController|MessageHistoryViewControllerDelegate|SendAnimation|QuickLook|CKNavBarUnifiedCallButton|Collaboration|GroupCollaboration|TipKit|SafetyMonitor|MediaInput|GlassThrowSendAnimation|PhotosSupport|Contacts|Wallet|Location|BackgroundContextMenu|NavigationBar|TapbackPicker|TapbackPicker_QuickLook|TapbackPicker_Orb|ChatKit|ChatKit1|TapbackPicker_ContextMenu|ChatKit2|ChatKit3|BalloonFocus|ChatKit4|ChatKit5|MenuBarKeyCommands|ChatKit6|ChatKit7|Translation|ChatKit8|ChatKit9|ChatKit10|ChatKit11)
- __OBJC_$_INSTANCE_METHODS_CKConversationListCollectionViewControllerCoordinator
- __OBJC_$_INSTANCE_METHODS_CKEntryViewPlusButton(ChatKit)
- __OBJC_$_INSTANCE_METHODS_CKGlassSendMenuButton(ChatKit)
- __OBJC_$_INSTANCE_METHODS__TtC7ChatKit34CKCommunicationSafetyFlowPresenter(ChatKit|ChatKit1)
- __OBJC_$_INSTANCE_VARIABLES_CKConversationListCollectionViewControllerCoordinator
- __OBJC_$_PROP_LIST_CKConversationListCollectionViewControllerCoordinator
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SCUIInterventionViewControllerDelegate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_SCUIInterventionViewControllerDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_SCUIInterventionViewControllerDelegate
- __OBJC_$_PROTOCOL_REFS_SCUIInterventionViewControllerDelegate
- __OBJC_CLASS_PROTOCOLS_$_CKChatController(MacToolbar|ClickyOrbConformance|CKChatController_Stickers|CKStickerDetailViewControllerDelegate|ChatItemSelection|Debug|ImpactEffectPicker|MenuBar|MessageHistoryViewController|MessageHistoryViewControllerDelegate|SendAnimation|QuickLook|CKNavBarUnifiedCallButton|Collaboration|GroupCollaboration|TipKit|SafetyMonitor|MediaInput|GlassThrowSendAnimation|PhotosSupport|Contacts|Wallet|Location|BackgroundContextMenu|NavigationBar|TapbackPicker|TapbackPicker_QuickLook|TapbackPicker_Orb|ChatKit|ChatKit1|TapbackPicker_ContextMenu|ChatKit2|ChatKit3|BalloonFocus|ChatKit4|ChatKit5|MenuBarKeyCommands|ChatKit6|ChatKit7|Translation|ChatKit8|ChatKit9|ChatKit10|ChatKit11)
- __OBJC_CLASS_PROTOCOLS_$_CKEntryViewPlusButton(ChatKit)
- __OBJC_CLASS_PROTOCOLS_$_CKGlassSendMenuButton(ChatKit)
- __OBJC_CLASS_PROTOCOLS_$__TtC7ChatKit34CKCommunicationSafetyFlowPresenter(ChatKit|ChatKit1)
- __OBJC_CLASS_RO_$_CKConversationListCollectionViewControllerCoordinator
- __OBJC_LABEL_PROTOCOL_$_SCUIInterventionViewControllerDelegate
- __OBJC_METACLASS_RO_$_CKConversationListCollectionViewControllerCoordinator
- __OBJC_PROTOCOL_$_SCUIInterventionViewControllerDelegate
- __PROPERTIES_CKEntryViewPlusButton
- __PROPERTIES_CKGlassSendMenuButton
- __PROTOCOL_CKSendMenuButtonProtocol
- __PROTOCOL_INSTANCE_METHODS_CKSendMenuButtonProtocol
- __PROTOCOL_METHOD_TYPES_CKSendMenuButtonProtocol
- __PROTOCOL_PROPERTIES_CKSendMenuButtonProtocol
- ___101-[CKChatController(CKChatController_Stickers) saveStickerFromChatItem:pluginSourceView:animateFlyIn:]_block_invoke
- ___120-[CKCoreChatController transcriptCollectionViewController:viewedCommSafetyItemWithIndexPath:updatedSensitivityAnalysis:]_block_invoke
- ___122-[CKCoreChatController(UserSafety) presentCommSafetyInterventionIfNecessaryForMediaObject:willPresentHandler:sendHandler:]_block_invoke
- ___122-[CKCoreChatController(UserSafety) presentCommSafetyInterventionIfNecessaryForMediaObject:willPresentHandler:sendHandler:]_block_invoke_2
- ___131-[CKChatControllerDummyAnimator _throwAnimationDurationScaleFactorForThrownBalloonAttributes:finalBalloonFrames:sendAnimationType:]_block_invoke
- ___131-[CKCoreChatController transcriptCollectionViewController:viewedCommSafetyAssociatedItemsWithIndexPath:updatedSensitivityAnalysis:]_block_invoke
- ___150-[CKChatControllerDummyAnimator __beginThrowAnimationWithThrowBalloonViewAttributesCollection:framesOfAddedChatItems:sendAnimationType:entryViewSize:]_block_invoke
- ___241-[CKChatController(SendAnimation) _makeThrowBalloonsForSendAnimationWithType:inContainerView:forSendingMessages:shouldUseQuickReplySourceRect:quickReplySourceRect:quickReplySnapshotView:audioMessageSourceRect:audioRecordingPillViewSnapshot:]_block_invoke
- ___66-[CKChatInputController _beginPreviewCreationWithFileURL:payload:]_block_invoke_5
- ___70-[CKChatController(CKChatController_Stickers) saveSticker:sourceRect:]_block_invoke
- ___82-[CKChatController(SendAnimation) sendAnimationManagerWillStartAnimation:context:]_block_invoke_10
- ___97-[CKTranscriptBackgroundChannelController _fetchPosterGalleryForChannel:fetchRequest:completion:]_block_invoke_3
- ____MEPConversationListCollectionViewControllerCoordinatorClass_block_invoke
- ___block_descriptor_139_e8_32s40s48s56s64s72r80r88r_e27_v32?0"CKChatItem"8Q16^B24ls32l8s40l8s48l8r72l8s56l8r80l8s64l8r88l8
- ___block_descriptor_49_e8_32s40s_e31_v16?0"SCSensitivityAnalysis"8ls32l8s40l8
- ___block_descriptor_56_e8_32s40s48w_e17_v16?0"NSArray"8lw48l8s32l8s40l8
- ___block_descriptor_57_e8_32s40s48s_e17_v16?0"NSArray"8ls32l8s40l8s48l8
- ___block_descriptor_64_e8_32s40s48s56w_e17_v16?0"NSArray"8lw56l8s32l8s40l8s48l8
- ___block_descriptor_72_e8_32s40s48s56s64bs_e17_v16?0"NSArray"8ls32l8s40l8s48l8s56l8s64l8
- ___block_descriptor_72_e8_32s40s48s56s_e45_v32?0"CKThrowBalloonViewAttributes"8Q16^B24ls32l8s40l8s48l8s56l8
- ___block_descriptor_80_e8_32s40s48s56s64r_e27_v32?0"IMChatItem"8Q16^B24ls32l8s40l8s48l8s56l8r64l8
- ___block_descriptor_88_e8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
- ___block_descriptor_88_e8_32s40s48s56r64r72r_e27_v32?0"IMChatItem"8Q16^B24ls32l8s40l8s48l8r56l8r64l8r72l8
- ___block_descriptor_88_e8_32s40s48s_e45_v32?0"CKThrowBalloonViewAttributes"8Q16^B24ls32l8s40l8s48l8
- ___block_descriptor_97_e8_32s40w_e5_v8?0lw40l8s32l8
- ___swift_closure_destructor.10Tm
- ___swift_closure_destructor.15Tm
- ___swift_closure_destructor.185Tm
- ___swift_closure_destructor.21Tm
- ___swift_closure_destructor.23Tm
- ___swift_closure_destructor.63Tm
- ___swift_closure_destructor.72Tm
- _associated conformance 7ChatKit26ConversationsInspectorViewV0a14PropertyEditorE0V7SwiftUI0E0AA4BodyAfGP_AfG
- _associated conformance 7ChatKit34CKCommunicationSafetyFlowPresenterC18SensitiveMediaKindOSHAASQ
- _associated conformance So17IMCommSafetyStateVSHSCSQ
- _get_witness_table 7ChatKit27DebugInspectorContainerViewVy7SwiftUI03TabF0VySiAD12TupleContentVyAD0F0PADE7tabItemyQrqd__yXEAdIRd__lFQOyAD4ListVys5NeverOAD7ForEachVySaySi6offset_So14CKConversationC7elementtGSiAD7SectionVyAD4TextVAQy19CollectionsInternal17OrderedDictionaryV8ElementsVyS2SSg_GSSAA0cd4CellF0VSgGAD05EmptyF0VGGG_AD5LabelVyAzD5ImageVGQo__AjDEAKyQrqd__yXEAdIRd__lFQOyAMyAoQyAVSiAXyAzA013ConversationsdF0V0a14PropertyEditorF0VA11_GGG_A19_Qo_QPGGGAdIHPyHC
- _get_witness_table 7SwiftUI19_ConditionalContentVyAA4ViewPAAE11contextMenu9menuItems7preview0J6ActionQrqd__yXE_qd_0_yXEyyctAaDRd__AaDRd_0_r0_lFQOyAA01_e9Modifier_D0Vy7ChatKit07Detailse13CommonContextG0VG_AA5GroupVyAA05TupleD0VyAA7SectionVyAA05EmptyE0VAN0G4Item33_F28409D6AF308FDD12CA19D65AD16453LLVy_AA17DefaultLabelStyleVGSgAWG_AUyAwZy_AA22TitleAndIconLabelStyleVGSgAWGA3_SgA3_QPGGAN34CKQLPreviewControllerRepresentableAYLLVQo_AeAEAfGQrqd__yXE_tAaDRd__lFQOyAO_A11_Qo_GAaDHPqd0__AaDHD4_A14_HO_qd0__AaDHD3_A15_HOHC
- _keypath_get.19Tm
- _objc_retain_x11
- _objc_retain_x12
- _swift_release_x11
- _symbolic $s7ChatKit22SendMenuButtonProtocolP
- _symbolic SaySo21SCSensitivityAnalysisCG
- _symbolic SaySo21SCSensitivityAnalysisCGIegg_
- _symbolic SaySo9IMStickerCG
- _symbolic SbIegy_Sg
- _symbolic SiSo14CKConversationC_____y_______________GIegygr_ 7SwiftUI7SectionV AA4TextV 7ChatKit26ConversationsInspectorViewV0e14PropertyEditorI0V AA05EmptyI0V
- _symbolic _____ 7ChatKit010PlusButtonD4View33_3A4F9EFB16D832C5123E30AA2C9D3873LLC
- _symbolic _____ 7ChatKit19EntryViewPlusButtonC
- _symbolic _____ 7ChatKit19GlassSendMenuButtonC
- _symbolic _____ 7ChatKit22PlusButtonClippingView33_3A4F9EFB16D832C5123E30AA2C9D3873LLC
- _symbolic _____ 7ChatKit26ConversationsInspectorViewV0a14PropertyEditorE0V
- _symbolic _____ 7ChatKit27PlusButtonBlurContainerView33_3A4F9EFB16D832C5123E30AA2C9D3873LLC
- _symbolic _____ 7ChatKit28PlusButtonBlurBackgroundView33_3A4F9EFB16D832C5123E30AA2C9D3873LLC
- _symbolic _____ 7ChatKit31PlusButtonBlendedBackgroundView33_3A4F9EFB16D832C5123E30AA2C9D3873LLC
- _symbolic _____ 7ChatKit34CKCommunicationSafetyFlowPresenterC18SensitiveMediaKindO
- _symbolic _____ So17IMCommSafetyStateV
- _symbolic _____ So24SCUIInterventionWorkflowV
- _symbolic _____Sg 24SensitiveContentAnalysis0B11DescriptionV
- _symbolic _____XDXMT 7ChatKit34CKCommunicationSafetyFlowPresenterC
- _symbolic _____ySaySi6offset_So14CKConversationC7elementtGSi_____y_______________GG 7SwiftUI7ForEachV AA7SectionV AA4TextV 7ChatKit26ConversationsInspectorViewV0g14PropertyEditorK0V AA05EmptyK0V
- _symbolic _____y_____G s11_SetStorageC 7ChatKit34CKCommunicationSafetyFlowPresenterC
- _symbolic _____y______G 7ChatKit28DetailsViewCommonContextMenuV0G4Item33_F28409D6AF308FDD12CA19D65AD16453LLV 7SwiftUI17DefaultLabelStyleV
- _symbolic _____y______GSg 7ChatKit28DetailsViewCommonContextMenuV0G4Item33_F28409D6AF308FDD12CA19D65AD16453LLV 7SwiftUI17DefaultLabelStyleV
- _symbolic _____y_______________G 7SwiftUI7SectionV AA4TextV 7ChatKit26ConversationsInspectorViewV0e14PropertyEditorI0V AA05EmptyI0V
- _symbolic _____y__________ySaySi6offset_So14CKConversationC7elementtGSi_____y_______________GGG 7SwiftUI4ListV s5NeverO AA7ForEachV AA7SectionV AA4TextV 7ChatKit26ConversationsInspectorViewV0i14PropertyEditorM0V AA05EmptyM0V
- _symbolic _____y__________y______GSgABG 7SwiftUI7SectionV AA9EmptyViewV 7ChatKit07DetailsE17CommonContextMenuV0K4Item33_F28409D6AF308FDD12CA19D65AD16453LLV AA17DefaultLabelStyleV
- _symbolic _____y__________y______GSgABGSg 7SwiftUI7SectionV AA9EmptyViewV 7ChatKit07DetailsE17CommonContextMenuV0K4Item33_F28409D6AF308FDD12CA19D65AD16453LLV AA17DefaultLabelStyleV
- _symbolic _____y__________y______GSgABG_AAyAbCy______GSgABGAGSgAGt 7SwiftUI7SectionV AA9EmptyViewV 7ChatKit07DetailsE17CommonContextMenuV0K4Item33_F28409D6AF308FDD12CA19D65AD16453LLV AA17DefaultLabelStyleV AA012TitleAndIconuV0V
- _symbolic _____y_____ySi_____y_____y_____y__________ySaySi6offset_So14CKConversationC7elementtGSi_____y_____AFy_____yS2SSg_GSS_____SgG_____GGG______yAM_____GQo_______yADyAeFyAKSiALyAM_____ATGGG_AZQo_QPGGG 7ChatKit27DebugInspectorContainerViewV 7SwiftUI03TabF0V AD12TupleContentV AD0F0PADE7tabItemyQrqd__yXEAdIRd__lFQO AD4ListV s5NeverO AD7ForEachV AD7SectionV AD4TextV 19CollectionsInternal17OrderedDictionaryV8ElementsV AA0cd4CellF0V AD05EmptyF0V AD5LabelV AD5ImageV AjDEAKyQrqd__yXEAdIRd__lFQO AA013ConversationsdF0V0a14PropertyEditorF0V
- _symbolic _____y_____y__________ySaySi6offset_So14CKConversationC7elementtGSi_____y_____ACy_____yS2SSg_GSS_____SgG_____GGG______yAJ_____GQo_______yAAyAbCyAHSiAIyAJ_____AQGGG_AWQo_t 7SwiftUI4ViewPAAE7tabItemyQrqd__yXEAaBRd__lFQO AA4ListV s5NeverO AA7ForEachV AA7SectionV AA4TextV 19CollectionsInternal17OrderedDictionaryV8ElementsV 7ChatKit018DebugInspectorCellC0V AA05EmptyC0V AA5LabelV AA5ImageV AcAEADyQrqd__yXEAaBRd__lFQO AT013ConversationstC0V0q14PropertyEditorC0V
- _symbolic _____y_____y__________ySaySi6offset_So14CKConversationC7elementtGSi_____y_______________GGG______yAJ_____GQo_ 7SwiftUI4ViewPAAE7tabItemyQrqd__yXEAaBRd__lFQO AA4ListV s5NeverO AA7ForEachV AA7SectionV AA4TextV 7ChatKit022ConversationsInspectorC0V0l14PropertyEditorC0V AA05EmptyC0V AA5LabelV AA5ImageV
- _symbolic _____y_____y__________y______GSgACG_AByAcDy______GSgACGAHSgAHQPG 7SwiftUI12TupleContentV AA7SectionV AA9EmptyViewV 7ChatKit07DetailsG17CommonContextMenuV0M4Item33_F28409D6AF308FDD12CA19D65AD16453LLV AA17DefaultLabelStyleV AA012TitleAndIconwX0V
- _symbolic _____y_____y_____y_____G______y_____y_____y__________y______GSgAHG_AGyAhIy______GSgAHGAMSgAMQPGG_____Qo______yAD_ATQo_G 7SwiftUI19_ConditionalContentV AA4ViewPAAE11contextMenu9menuItems7preview0J6ActionQrqd__yXE_qd_0_yXEyyctAaDRd__AaDRd_0_r0_lFQO AA01_e9Modifier_D0V 7ChatKit07Detailse13CommonContextG0V AA5GroupV AA05TupleD0V AA7SectionV AA05EmptyE0V AN0G4Item33_F28409D6AF308FDD12CA19D65AD16453LLV AA17DefaultLabelStyleV AA22TitleAndIconLabelStyleV AN34CKQLPreviewControllerRepresentableAXLLV AeAEAfGQrqd__yXE_tAaDRd__lFQO
- _symbolic _____y_____y_____y_____G______y_____y_____y__________y______GSgAHG_AGyAhIy______GSgAHGAMSgAMQPGG_____Qo______yAD_ATQo__G 7SwiftUI19_ConditionalContentV7StorageO AA4ViewPAAE11contextMenu9menuItems7preview0K6ActionQrqd__yXE_qd_0_yXEyyctAaFRd__AaFRd_0_r0_lFQO AA01_f9Modifier_D0V 7ChatKit07Detailsf13CommonContextH0V AA5GroupV AA05TupleD0V AA7SectionV AA05EmptyF0V AP0H4Item33_F28409D6AF308FDD12CA19D65AD16453LLV AA17DefaultLabelStyleV AA22TitleAndIconLabelStyleV AP34CKQLPreviewControllerRepresentableAZLLV AgAEAhIQrqd__yXE_tAaFRd__lFQO
- _symbolic _____y_____y_____y__________ySaySi6offset_So14CKConversationC7elementtGSi_____y_____ADy_____yS2SSg_GSS_____SgG_____GGG______yAK_____GQo_______yAByAcDyAISiAJyAK_____ARGGG_AXQo_QPG 7SwiftUI12TupleContentV AA4ViewPAAE7tabItemyQrqd__yXEAaDRd__lFQO AA4ListV s5NeverO AA7ForEachV AA7SectionV AA4TextV 19CollectionsInternal17OrderedDictionaryV8ElementsV 7ChatKit018DebugInspectorCellE0V AA05EmptyE0V AA5LabelV AA5ImageV AeAEAFyQrqd__yXEAaDRd__lFQO AV013ConversationsvE0V0s14PropertyEditorE0V
- _symbolic _____y_____y_____y__________y______GSgADG_ACyAdEy______GSgADGAISgAIQPGG 7SwiftUI5GroupV AA12TupleContentV AA7SectionV AA9EmptyViewV 7ChatKit07DetailsH17CommonContextMenuV0N4Item33_F28409D6AF308FDD12CA19D65AD16453LLV AA17DefaultLabelStyleV AA012TitleAndIconxY0V
- _type_layout_string 7ChatKit26ConversationsInspectorViewV
CStrings:
+ "    Matches the lead on all compared fields."
+ "    No differences."
+ "  %@[first=%@]: class=%@, itemGUID=%@"
+ "  %@[last=%@]: class=%@, itemGUID=%@"
+ "  Account Login ID: "
+ "  Chat Identifier: "
+ "  Display Name: "
+ "  Domain Identifiers: "
+ "  Exception callStackSymbols: %@"
+ "  Exception name: %@"
+ "  Exception reason: %@"
+ "  Last Addressed Handle: "
+ "  Last Addressed SIM ID: "
+ "  Participants: "
+ "  Person Centric ID: "
+ "  chat guid: %@"
+ "  chat shape: chatStyle=%@, participants=%@, service=%@, hasThreadOriginator=%@"
+ "  count-math: chatItems(%@) + inserted(%@) - removed(%@) = expected(%@), imChatItems=%@, collectionView=%@"
+ "  imChatItems drift vs expected: %@"
+ "  imChatItems param (count): %@"
+ "  imChatItems[last=%@]: class=%@, itemGUID=%@"
+ "  index-bounds: max(inserted)=%@, max(removed)=%@, max(reload)=%@, max(regenerate)=%@, imChatItems=%@, chatItems=%@"
+ "  isHoldingForCollectionViewUpdateInProgress=%@"
+ "  process: %@ (pid %d)"
+ "  self.imChatItems (count): %@"
+ "  state: isInline=%@, isInSectionProvider=%@, sizedFullTranscript=%@, isPerformingRegenerateOrReloadOnlyUpdate=%@, chat.isFiltered=%@"
+ "!B"
+ "!a"
+ "%@ viewControllers=[%@]"
+ "(null)"
+ "+micAccountNeedsRepair"
+ "<%@ %p>"
+ "=== Fork Report: "
+ "AEAssetPackageAssetIdentifier"
+ "AEAssetPackageDisplayIsScreenshot"
+ "AEAssetPackageDisplayMediaType"
+ "ASSISTANT_ACTION_SUGGESTION_GENERIC_ERROR_ALERT"
+ "ATTRIBUTION_TEXT_SENSITIVE_STICKER_SHOW_MULTIPLE"
+ "ATTRIBUTION_TEXT_SENSITIVE_STICKER_SHOW_ONE"
+ "Account Login ID"
+ "Actual (this chat)"
+ "AllowGradientOverrides"
+ "Assistant action suggestions are not available in context menus, due to os_eligibility returning an unexpected maybe response for the hassium domain."
+ "Assistant action suggestions are not available in context menus, due to os_eligibility."
+ "Assistant action suggestions are tentatively available in context menus, due to os_eligibility not possessing a definition for the hassium domain."
+ "Automatic"
+ "Building media object from URL"
+ "Building media object from bytes"
+ "Bypassed/confirmed with %ld analysis flipped to userOptedToShow"
+ "ChatBot - Prewarmed %s %s from %s to %s, success: %{bool}d with error %s "
+ "ChatBot - Prewarmed %s %s to %s, success: %{bool}d with error %s "
+ "ChatKit.CKAppCardPresentationDecision"
+ "ChatKit/CKGlassSendMenuButton.swift"
+ "Compact"
+ "Creating PXUnfinishedAssetInfo with filename=%{public}@, width: %f, height: %f, completePreview: %@"
+ "DisableNewComposeAutomaticKeyboardPresentation"
+ "Domain Identifiers"
+ "Duplicate SensitiveItem.id indicating duplicate transfer GUIDs. This should not happen."
+ "Error %@"
+ "Failed to create a media object for the audio message from embedded data."
+ "Failed to fetch os eligibility for assistant action suggestions in context menus. Error: %@"
+ "Fetch request wants a new gallery. Bypassing gallery cache to fetch new gallery for channel with id %@."
+ "ForceUnknownSenderForTesting"
+ "Generating a forking report can take between a few seconds and several minutes. It will search for possible forks of the selected chat(s) and display a diff between the selected chat(s) and the possible forks. Once generated, if there are forks, you will be provided with the option to apply the diffs to any selected forks in order to have the chats merge. If this chat is the fork, it is recommended that you open the internal conversation details of the chat with the expected display name and participants and generate the report on that chat."
+ "Generating asset package from asset URL, appended video and preview image"
+ "Generating shelf-eligible asset package from PXUnfinishedAssetInfo"
+ "Generating shelf-eligible asset package from asset URL, appended video and preview image"
+ "Handling of assistant action completed."
+ "Handling of assistant sub-action completed."
+ "Here, not on lead"
+ "ID/analysis count mismatch: %ld vs. %ld"
+ "IMESSAGE_MIC_ACCOUNT_REPAIR_NOTIFICATION_DESCRIPTION"
+ "IMESSAGE_MIC_ACCOUNT_REPAIR_NOTIFICATION_HEADER"
+ "IMESSAGE_MIC_ACCOUNT_REPAIR_NOTIFICATION_REPAIR"
+ "Image edges could not be enhanced. Error: CGImage dimensions exceed uint32_t (w=%zu h=%zu)"
+ "Image edges could not be enhanced. Error: bytesPerPixel × width × height overflows uint32_t (w=%u h=%u)"
+ "Image edges could not be enhanced. Error: calloc(%u) failed"
+ "Inspector"
+ "InteractiveResize"
+ "Kind %s"
+ "Last Addressed Handle"
+ "Last Addressed SIM ID"
+ "Matches the lead on all compared fields — this chat should likely be merged."
+ "Merge Forks (coming soon)"
+ "MiC account repair finished — didRepair=%{bool}d, error=%s"
+ "MiC account-repair tip action: no presenting controller available."
+ "New gallery fetch with primary extension identifiers had a sufficient number of descriptors or had no fallback set. Returning immediately."
+ "No fork report generated yet."
+ "On lead, missing here"
+ "OneBesideSecondary"
+ "OneOverSecondary"
+ "Person Centric ID"
+ "Precomputing short-form smart responses on conversation open"
+ "Presenting generic error alert for error: %@"
+ "Primary"
+ "Recovery from transcript update exception also threw: %@"
+ "SAVE_GENMOJI_PLURAL_CONTEXT_MENU_ACTION_TITLE"
+ "SAVE_STICKER_CONTEXT_MENU_ACTION_TITLE"
+ "SAVE_STICKER_PLURAL_CONTEXT_MENU_ACTION_TITLE"
+ "SCUIMoreHelpMenuController did not return an updated analysis with a `userOptedToShow` flag"
+ "Secondary"
+ "SecondaryOnly"
+ "Sending notification: WaitingForCloud %{BOOL}d, UpdateAppleID: %{BOOL}d, MiCAccountNeedsRepair: %{BOOL}d"
+ "Setting %@ as the inspector."
+ "Short-form smart responses precompute error: %@"
+ "Skipping draft shelfPluginPayload restore: photos extension has no staged asset identifiers"
+ "Split view did collapse. displayMode: %@"
+ "Split view did expand. displayMode: %@, chatNavigationController.viewControllers.count: %lu"
+ "Split view did hide column: %@"
+ "Split view did show column: %@"
+ "Split view will hide column: %@"
+ "Supplementary"
+ "Tapped downloadable chat item with visible preview. Opening QuickLook immediately; transfer continues to fault in full asset."
+ "Tapped downloadable chat item without visible preview. Downloading; user must tap again once thumbnail appears to open QuickLook."
+ "TranscriptBatchUpdateRecovered"
+ "Transfer %s has no cached preflight preview"
+ "TwoBesideSecondary"
+ "TwoDisplaceSecondary"
+ "TwoOverSecondary"
+ "Unknown(%ld)"
+ "Updating KT Tip Rules. ktWaitingForCloud=%{bool}d, updateAppleID=%{bool}d, micAccountNeedsRepair=%{bool}d"
+ "User canceled or an updated analysis is missing: %s"
+ "User selected context menu option for assistant action: %s"
+ "User selected context menu option for assistant sub-action: %s"
+ "User tapped close button for MiC account-repair tip."
+ "User tapped to repair MiC account."
+ "We have a preflight preview, but media object is eligible for full res preview. Kicking off a new generation request"
+ "[%p, %@, %@] Returning preflight preview from cache. fileNeedsAcquisition %{BOOL}d, transcoderPreviewGenerationFailed %{BOOL}d, preflightStage %lu"
+ "[Suggestions] Photos app is locked. No first featured photo available."
+ "added (this chat)"
+ "a\xf0\xf0\x81"
+ "chat.guid"
+ "chatItems.count"
+ "collectionView.count"
+ "didMessageSomeone"
+ "didPresent"
+ "exception.name"
+ "imChatItems.param.count"
+ "imChatItems.self.count"
+ "inserted"
+ "inserted.count"
+ "isPhotosAppLocked during fetch = %{bool}d"
+ "os_eligibility response was an unhandled value"
+ "presentModernCardForPlugin: completion (after) restored preventResignFirstResponder=%{BOOL}d"
+ "presentModernCardForPlugin: completion (alongside) restored preventResignFirstResponder=%{BOOL}d, ck_disallowBecomeFirstResponder=NO"
+ "presentModernCardForPlugin: locking ck_disallowBecomeFirstResponder=YES for alongside present"
+ "presentModernCardForPlugin: pinning first responder (preventResignFirstResponder=YES) for keyboardDismissal=%ld"
+ "rdar://172852166"
+ "rdar://172852166 transcript batch update inconsistency — recovering. process=%@ chat=%@ animated=%@ exceptionReason=%@ counts: chatItems(%@)+inserted(%@)-removed(%@)=expected(%@) imChatItems=%@ collectionView=%@"
+ "regenerate"
+ "regenerate.count"
+ "reload"
+ "reload.count"
+ "removed.count"
+ "requestGeometryUpdate failed while forcing orientation: %@"
+ "sensitivity.compactAnalysisBitMask"
+ "showConversation: dismissing details view on push because conversation does not allow showing details. conversation=%@"
+ "showConversation: restoring details view on push. inspectorWasPresented=%{BOOL}d, hasRedesignedDetailsNavController=%{BOOL}d, allowsShowingDetailsView=%{BOOL}d, conversation=%@"
+ "topColumnForCollapsingToProposedTopColumn: accepting proposed column %@"
+ "topColumnForCollapsingToProposedTopColumn: choosing Primary because selection VC is showing with no active compose."
+ "topColumnForCollapsingToProposedTopColumn: choosing Primary because user is composing a message."
+ "topColumnForCollapsingToProposedTopColumn: proposed=%@ isComposingMessage=%{BOOL}d, currentConversation=%@ - skipping rebuild — modal already presented (%p), returning Primary"
+ "topColumnForCollapsingToProposedTopColumn: proposed=%@, isComposingMessage=%{BOOL}d, currentConversation=%@"
+ "v16@?0@\"UIActivityViewController\"8"
+ "v24@?0@\"NSString\"8@\"NSIndexSet\"16"
+ "\xc1\xd1"
- "  imChatItems (count): %@"
- " transcriptBackgroundLuminance: "
- "!Q"
- "!R"
- "%s: bypassed with %ld analysis result(s)"
- "%s: didMessageSomeone"
- "%s: didPresent"
- "%s: error %@"
- "%s: kind %s"
- "%s: user canceled or an updated analysis is missing: %s"
- "4\""
- "App was not set up, setting Shared with You to %d for %@"
- "ChatBot - Prewarmed media %s from %s to %s, success: %{bool}d with error %s "
- "ChatBot - Prewarmed media %s to %s, success: %{bool}d with error %s "
- "ChatBot - Prewarmed thumbnail %s from %s to %s, success: %{bool}d with error %s "
- "ChatKit-Civic"
- "ChatKit.PlusButtonBlendedBackgroundView"
- "ChatKit.PlusButtonBlurBackgroundView"
- "ChatKit.PlusButtonClippingView"
- "ChatKit/EntryViewPlusButton.swift"
- "ChatKit/GlassSendMenuButton.swift"
- "D"
- "Different number of sensitiveMediaObjects (%lu) than updatedAnalyses (%lu). Sending media as obscured."
- "Different number of sensitiveTransfers (%lu) than updatedAnalyses (%lu)"
- "Ending confirmed actionBlock"
- "Ending rejected actionBlock"
- "MEPConversationListCollectionViewControllerCoordinator"
- "New gallery fetch with primary extension identifiers had a sufficient number of descriptors. Returning immediately."
- "No actionBlock defined on interventionContainer"
- "SAFETY_MENU_CONTENT_KIND_STICKER"
- "SAFETY_MENU_CONTENT_KIND_STICKERS"
- "SEND_MENU_APPS_BUTTON_ACCESSIBILITY_TITLE"
- "Sending notification: WaitingForCloud %d, UpdateAppleID: %d"
- "Starting confirmed actionBlock"
- "Starting rejected actionBlock"
- "Tapped downloadable chat item with visible preview. Will download and display immediately."
- "Tapped downloadable chat item without visible preview. Will download but not display immediately."
- "Transfer %s has no preflightThumbnailImage"
- "Updating KT Tip Rules. ktWaitingForCloud=%{bool}d, updateAppleID=%{bool}d"
- "We have a preflight preview but file no longer needs acquisition, purging LQ preview from disk and kicking off a new generation request"
- "[%p, %@, %@] PREFLIGHT preview found in cache! returning %@"
- "[t: %@] Invalidating non preflight preview %@"
- "[t: %@] No cached valid preview exists. Don't delete previewURL because a preview generation might be in flight."
- "a\xf0\xf0\x91"
- "didConfirm on interventionContainer"
- "didReject on interventionContainer"
- "init(effect:)"
- "presentIntervention(for:with:parentViewController:completion:)"
- "rasterizationScale"
- "\xd1\xd1"
```
