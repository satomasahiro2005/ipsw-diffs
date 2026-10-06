## TextInputUI

> `/System/Library/PrivateFrameworks/TextInputUI.framework/TextInputUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x130278` | `0x134df0` | **`+0x4b78`** |
| `__AUTH_CONST.__objc_const` | `0x19260` | `0x197f8` | **`+0x598`** |
| `__TEXT.__cstring` | `0xdc7c` | `0xd80d` | **`-0x46f`** |
| `__TEXT.__oslogstring` | `0x5cb4` | `0x6081` | **`+0x3cd`** |
| `__AUTH_CONST.__cfstring` | `0xe700` | `0xeac0` | **`+0x3c0`** |
| `__TEXT.__objc_methlist` | `0xfb6c` | `0xfebc` | **`+0x350`** |
| `__DATA_CONST.__objc_selrefs` | `0xa0d0` | `0xa330` | **`+0x260`** |
| `__DATA_CONST.__objc_arraydata` | `0xa08` | `0xad0` | **`+0xc8`** |
| `__TEXT.__unwind_info` | `0x4160` | `0x4228` | **`+0xc8`** |
| `__AUTH.__objc_data` | `0x3930` | `0x39e0` | **`+0xb0`** |
| `__DATA.__data` | `0x2848` | `0x28f8` | **`+0xb0`** |
| `__AUTH_CONST.__const` | `0x2b68` | `0x2be0` | **`+0x78`** |
| `__TEXT.__const` | `0x3630` | `0x368e` | **`+0x5e`** |
| `__DATA.__bss` | `0x2dc0` | `0x2e18` | **`+0x58`** |
| `__DATA.__objc_ivar` | `0x11c8` | `0x1218` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x7a18` | `0x7a58` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1bb0` | `0x1bd0` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x258` | `0x270` | **`+0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0x3f0` | `0x3d8` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x14b8` | `0x14d0` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x17c0` | `0x17d8` | **`+0x18`** |
| `__TEXT.__dlopen_cstrs` | `0x406` | `0x3f1` | **`-0x15`** |
| `__TEXT.__swift5_capture` | `0x4f8` | `0x4e4` | **`-0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x6f8` | `0x708` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x4f0` | `0x4e0` | **`-0x10`** |
| `__DATA.__common` | `0x288` | `0x280` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x270` | `0x278` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x468` | `0x470` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x20c0` | `0x20c8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x1964` | `0x196a` | **`+0x6`** |

### Other Changes

```diff

-9127.0.79.0.0
+9127.0.84.1.901

-  Functions: 6781
-  Symbols:   10661
-  CStrings:  2704
+  Functions: 6865
+  Symbols:   10785
+  CStrings:  2727
Symbols:
+ +[TUIEmojiRemoteKeyViewProvider isDynamicEmojiLayoutEnabled]
+ +[TUIEmojiRemoteKeyViewProvider sharedProvider]
+ +[TUIGenmojiCandidateCell reuseIdentifier]
+ +[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]
+ +[TUIKeyplane dynamicEmojiReservedAssistantBarHeightForLayoutClass:]
+ +[TUIKeyplane isRegularWidthLayoutClass:]
+ +[TUIKeyplane layoutHasNumberRow:]
+ +[TUIKeyplaneView constrainedGridSkipsKeyplaneInsetCorrectionForLayoutClass:hostIsEmojiPoster:]
+ +[TUIKeyplaneView emojiGridBaseOffsetsForSurface:layoutClass:minorEdgeWidth:nextToKeyplane:constrainedToHost:]
+ +[TUIKeyplaneView hostProcessIsEmojiPoster]
+ -[TUICandidateGeneratorInstallContext setStickerStoreWrapper:]
+ -[TUICandidateGeneratorInstallContext setTextComposerWrapper:]
+ -[TUICandidateGeneratorInstallContext stickerStoreWrapper]
+ -[TUICandidateGeneratorInstallContext textComposerWrapper]
+ -[TUICandidateThrottler _queueOnly_updateWithAutocorrectionList:]
+ -[TUIEmojiRemoteKeyViewProvider _remoteViewClassForDisplayType:]
+ -[TUIEmojiRemoteKeyViewProvider remoteViewForKey:inKeyplane:screenTraits:]
+ -[TUIGenmojiCandidateCell .cxx_destruct]
+ -[TUIGenmojiCandidateCell bottomPaddingConstraint]
+ -[TUIGenmojiCandidateCell commonInit]
+ -[TUIGenmojiCandidateCell genmojiContentView]
+ -[TUIGenmojiCandidateCell initWithCoder:]
+ -[TUIGenmojiCandidateCell initWithFrame:]
+ -[TUIGenmojiCandidateCell layoutSubviews]
+ -[TUIGenmojiCandidateCell leftPaddingConstraint]
+ -[TUIGenmojiCandidateCell rightPaddingConstraint]
+ -[TUIGenmojiCandidateCell setBottomPaddingConstraint:]
+ -[TUIGenmojiCandidateCell setCandidate:]
+ -[TUIGenmojiCandidateCell setGenmojiContentView:]
+ -[TUIGenmojiCandidateCell setLeftPaddingConstraint:]
+ -[TUIGenmojiCandidateCell setRightPaddingConstraint:]
+ -[TUIGenmojiCandidateCell setStyle:]
+ -[TUIGenmojiCandidateCell setTopPaddingConstraint:]
+ -[TUIGenmojiCandidateCell topPaddingConstraint]
+ -[TUIGenmojiCandidateCell updateLayout]
+ -[TUIInputSession forwardInvocation:]
+ -[TUIInputSession methodSignatureForSelector:]
+ -[TUIInputSession respondsToSelector:]
+ -[TUIInputSessionManager inputSessionForHostAuditToken:]
+ -[TUIKBKeyView installedRemoteContentView]
+ -[TUIKBKeyView setInstalledRemoteContentView:]
+ -[TUIKBKeyView(RemoteContent) installRemoteContentView:inContainerView:leadingExtent:trailingExtent:verticalExtent:bottomOffset:topOffset:]
+ -[TUIKey isLastKeyBeforeSplit]
+ -[TUIKey pairedSplitKey]
+ -[TUIKey setLastKeyBeforeSplit:]
+ -[TUIKey setPairedSplitKey:]
+ -[TUIKey setSplitRowMultiplier:]
+ -[TUIKey shouldSplitAfter]
+ -[TUIKey splitCopyOfKey]
+ -[TUIKey splitRowMultiplier]
+ -[TUIKeyplane checkForCachedSplitKeys]
+ -[TUIKeyplane duplicateKeyForSplitMode:]
+ -[TUIKeyplane duplicateKeyList]
+ -[TUIKeyplane handleSplitDuplicationForKey:inRow:keyRow:multiplier:layoutType:layoutShape:outSubtreesCopy:]
+ -[TUIKeyplane isCoreKey:]
+ -[TUIKeyplane isEmojiLayout]
+ -[TUIKeyplane moveControlKey:toRowAtIndex:inRowSet:]
+ -[TUIKeyplane numberOfCachedKeys]
+ -[TUIKeyplane setDuplicateKeyList:]
+ -[TUIKeyplane setNumberOfCachedKeys:]
+ -[TUIKeyplane setStackedControlColumnSwitchKey:spanningFromRow:toRow:inRowSet:]
+ -[TUIKeyplane stackedControlColumnSwitchKeyInRowSet:]
+ -[TUIKeyplane unduplicateDoubleHeightKey:fromRow:]
+ -[TUIKeyplane updateStackedControlColumnForRowSet:]
+ -[TUIKeyplane usesStackedControlColumn]
+ -[TUIKeyplaneRow reservesDockCornerPadding]
+ -[TUIKeyplaneRow setReservesDockCornerPadding:]
+ -[TUIKeyplaneRowInfo hasMiddlePadding]
+ -[TUIKeyplaneRowInfo setHasMiddlePadding:]
+ -[TUIKeyplaneTransitionRow description]
+ -[TUIKeyplaneTransitionRow stringForKeyArray:]
+ -[TUIKeyplaneView _installRemoteViewForKeyIfAvailable:]
+ -[TUIKeyplaneView _updateHandwritingLayoutWithOffset:isFinished:]
+ -[TUIKeyplaneView _walkKeyplaneAndInstallRemoteViewsIfNeeded]
+ -[TUIKeyplaneView _walkSubtreeForRemoteViews:]
+ -[TUIKeyplaneView currentEmojiGridSurface]
+ -[TUIKeyplaneView emojiGridContainmentView]
+ -[TUIKeyplaneView emojiGridOffsetsConstrainedToHost:]
+ -[TUIKeyplaneView installedRemoteViews]
+ -[TUIKeyplaneView remoteContentViewForKey:]
+ -[TUIKeyplaneView remoteKeyViewProvider]
+ -[TUIKeyplaneView setEmojiGridContainmentView:]
+ -[TUIKeyplaneView setInstalledRemoteViews:]
+ -[TUIKeyplaneView setOverrideScreenTraits:currentKeyboardMode:]
+ -[TUIKeyplaneView setRemoteKeyViewProvider:]
+ -[TUIKeyplaneView setShouldForceResetLayoutForNextKeyplane:]
+ -[TUIKeyplaneView setTraitChangeRegistration:]
+ -[TUIKeyplaneView setTransitionBottomRowSizingConstraint:]
+ -[TUIKeyplaneView shouldForceResetLayoutForNextKeyplane]
+ -[TUIKeyplaneView traitChangeRegistration]
+ -[TUIKeyplaneView transitionBottomRowSizingConstraint]
+ -[TUIKeyplaneView updateBottomRowSpacingForSplitProgress:]
+ -[TUIPredictionViewCell minimumNonClippingWidth]
+ -[TUIPredictionViewStackView _spacingBetweenCells]
+ -[TUIPredictionViewStackView _updateHiddenCellsToFitWidth:]
+ -[TUIPredictionViewStackView fitsCellsToMinimumWidth]
+ -[TUIPredictionViewStackView setFitsCellsToMinimumWidth:]
+ -[TUIRecentPasteGenerator pasteboardHasRemoteClipboard:]
+ _OBJC_CLASS_$_TUIEmojiRemoteKeyViewProvider
+ _OBJC_CLASS_$_TUIGenmojiCandidateCell
+ _OBJC_IVAR_$_TUICandidateGeneratorInstallContext._stickerStoreWrapper
+ _OBJC_IVAR_$_TUICandidateGeneratorInstallContext._textComposerWrapper
+ _OBJC_IVAR_$_TUICandidateThrottler._timerGeneration
+ _OBJC_IVAR_$_TUIGenmojiCandidateCell._bottomPaddingConstraint
+ _OBJC_IVAR_$_TUIGenmojiCandidateCell._genmojiContentView
+ _OBJC_IVAR_$_TUIGenmojiCandidateCell._leftPaddingConstraint
+ _OBJC_IVAR_$_TUIGenmojiCandidateCell._rightPaddingConstraint
+ _OBJC_IVAR_$_TUIGenmojiCandidateCell._topPaddingConstraint
+ _OBJC_IVAR_$_TUIKBKeyView._installedRemoteContentView
+ _OBJC_IVAR_$_TUIKey._lastKeyBeforeSplit
+ _OBJC_IVAR_$_TUIKey._pairedSplitKey
+ _OBJC_IVAR_$_TUIKey._splitRowMultiplier
+ _OBJC_IVAR_$_TUIKeyplane._duplicateKeyList
+ _OBJC_IVAR_$_TUIKeyplane._numberOfCachedKeys
+ _OBJC_IVAR_$_TUIKeyplaneRow._reservesDockCornerPadding
+ _OBJC_IVAR_$_TUIKeyplaneRowInfo._hasMiddlePadding
+ _OBJC_IVAR_$_TUIKeyplaneView._emojiGridContainmentView
+ _OBJC_IVAR_$_TUIKeyplaneView._installedRemoteViews
+ _OBJC_IVAR_$_TUIKeyplaneView._remoteKeyViewProvider
+ _OBJC_IVAR_$_TUIKeyplaneView._shouldForceResetLayoutForNextKeyplane
+ _OBJC_IVAR_$_TUIKeyplaneView._traitChangeRegistration
+ _OBJC_IVAR_$_TUIKeyplaneView._transitionBottomRowSizingConstraint
+ _OBJC_IVAR_$_TUIPredictionViewStackView._fitsCellsToMinimumWidth
+ _OBJC_METACLASS_$_TUIEmojiRemoteKeyViewProvider
+ _OBJC_METACLASS_$_TUIGenmojiCandidateCell
+ _UTTypePlainText
+ __OBJC_$_CLASS_METHODS_TUIEmojiRemoteKeyViewProvider
+ __OBJC_$_CLASS_METHODS_TUIGenmojiCandidateCell
+ __OBJC_$_CLASS_METHODS_TUIInputSession
+ __OBJC_$_INSTANCE_METHODS_TUIEmojiRemoteKeyViewProvider
+ __OBJC_$_INSTANCE_METHODS_TUIGenmojiCandidateCell
+ __OBJC_$_INSTANCE_METHODS_TUIKBKeyView(RemoteContent)
+ __OBJC_$_INSTANCE_VARIABLES_TUIGenmojiCandidateCell
+ __OBJC_$_PROP_LIST_TUIEmojiRemoteKeyViewProvider
+ __OBJC_$_PROP_LIST_TUIGenmojiCandidateCell
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_TUIRemoteKeyViewProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_TUIRemoteKeyViewProviding
+ __OBJC_$_PROTOCOL_REFS_TUIRemoteKeyViewProviding
+ __OBJC_CLASS_PROTOCOLS_$_TUIEmojiRemoteKeyViewProvider
+ __OBJC_CLASS_RO_$_TUIEmojiRemoteKeyViewProvider
+ __OBJC_CLASS_RO_$_TUIGenmojiCandidateCell
+ __OBJC_LABEL_PROTOCOL_$_TUIRemoteKeyViewProviding
+ __OBJC_METACLASS_RO_$_TUIEmojiRemoteKeyViewProvider
+ __OBJC_METACLASS_RO_$_TUIGenmojiCandidateCell
+ __OBJC_PROTOCOL_$_TUIRemoteKeyViewProviding
+ __TUIEmojiRemoteKeyViewProviderLogger.log
+ __TUIEmojiRemoteKeyViewProviderLogger.onceToken
+ ___107-[TUIKeyplane handleSplitDuplicationForKey:inRow:keyRow:multiplier:layoutType:layoutShape:outSubtreesCopy:]_block_invoke
+ ___32-[TUIKeyplane buildSplitRowInfo]_block_invoke
+ ___34+[TUIKeyplane layoutHasNumberRow:]_block_invoke
+ ___43+[TUIKeyplaneView hostProcessIsEmojiPoster]_block_invoke
+ ___47+[TUIEmojiRemoteKeyViewProvider sharedProvider]_block_invoke
+ ___59-[TUIPredictionViewStackView _updateHiddenCellsToFitWidth:]_block_invoke
+ ___65-[TUICandidateThrottler _queueOnly_updateWithAutocorrectionList:]_block_invoke
+ ___92+[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]_block_invoke
+ ___92+[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]_block_invoke_2
+ ____TUIEmojiRemoteKeyViewProviderLogger_block_invoke
+ ___block_descriptor_32_e23_B32?0"TUIKey"8Q16^B24l
+ ___block_descriptor_40_8_32w_e52_v24?0"<UITraitEnvironment>"8"UITraitCollection"16lw32l8
+ ___block_descriptor_40_e23_v32?0"UIView"8Q16^B24l
+ ___block_descriptor_48_8_32s40s_e15_B32?08Q16^B24ls32l8s40l8
+ ___block_descriptor_48_8_32w_e5_v8?0lw32l8
+ ___getUIRemoteCategoryKeyViewClass_block_invoke
+ ___getUIRemoteEmojiAndStickerInputViewClass_block_invoke
+ _getUIRemoteCategoryKeyViewClass.softClass
+ _getUIRemoteEmojiAndStickerInputViewClass.softClass
+ _hostProcessIsEmojiPoster.isEmojiPoster
+ _hostProcessIsEmojiPoster.onceToken
+ _layoutHasNumberRow:.__layouts
+ _layoutHasNumberRow:.onceToken
+ _sharedProvider.onceToken
+ _sharedProvider.sharedInstance
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _symbolic _____Sg 16GenerativeModels0aB12AvailabilityV
+ _symbolic _____Sg______t 16GenerativeModels0aB12AvailabilityV s6UInt64V
+ _symbolic _____ySS_____G s18_DictionaryStorageC 16GenerativeModels0cD12AvailabilityV
- -[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]
- -[TUIInputSession acceptingCandidateWithTrigger:]
- -[TUIInputSession addSupplementalLexicon:completionHandler:]
- -[TUIInputSession adjustPhraseBoundaryInForwardDirection:granularity:keyboardState:completionHandler:]
- -[TUIInputSession adjustPhraseBoundaryInForwardDirection:keyboardState:completionHandler:]
- -[TUIInputSession candidateRejected:]
- -[TUIInputSession changingContextWithTrigger:]
- -[TUIInputSession generateInlineCompletions:withPrefix:]
- -[TUIInputSession generateRefinementsForCandidate:keyboardState:completionHandler:]
- -[TUIInputSession generateReplacementsForString:keyLayout:continuation:]
- -[TUIInputSession handleAcceptedCandidate:keyboardState:completionHandler:]
- -[TUIInputSession handleKeyboardInput:keyboardState:completionHandler:]
- -[TUIInputSession lastAcceptedCandidateCorrected]
- -[TUIInputSession logDiscoverabilityEvent:userInfo:]
- -[TUIInputSession performHitTestForTouchEvent:keyboardState:continuation:]
- -[TUIInputSession performHitTestForTouchEvents:keyboardState:continuation:]
- -[TUIInputSession predominantLanguageInContextWithCompletionHandler:]
- -[TUIInputSession registerLearning:fullCandidate:keyboardState:mode:]
- -[TUIInputSession registerLearningForCompletion:fullCompletion:context:prefix:mode:]
- -[TUIInputSession removeSupplementalLexiconWithIdentifier:]
- -[TUIInputSession setOriginalInput:]
- -[TUIInputSession skipHitTestForTouchEvent:keyboardState:]
- -[TUIInputSession skipHitTestForTouchEvents:keyboardState:]
- -[TUIInputSession smartSelectionForTextInDocument:inRange:language:tokenizedRanges:options:completion:]
- -[TUIInputSession stickerWithIdentifier:stickerRoles:completionHandler:]
- -[TUIInputSession textAccepted:]
- -[TUIInputSession textAccepted:completionHandler:]
- -[TUIInputSession writeTypologyLogWithCompletionHandler:]
- -[TUIKey isDuplicatedSplitKey]
- -[TUIKey setIsDuplicatedSplitKey:]
- -[TUIKeyboardCandidateMultiplexer internalSharedClientWrapper]
- -[TUIKeyboardCandidateMultiplexer internalSharedStickerStoreWrapper]
- -[TUIKeyboardCandidateMultiplexer setInternalSharedClientWrapper:]
- -[TUIKeyboardCandidateMultiplexer setInternalSharedStickerStoreWrapper:]
- -[TUIKeyplane unduplicateDoubleHeightKey:]
- -[TUIKeyplaneView _updateHandwritingLayoutWithOffset:]
- -[TUISmartReplyGenerator createLocalTextComposerClientIfNeeded]
- _MobileKeyBagLibraryCore.frameworkLibrary
- _OBJC_IVAR_$_TUIKey._isDuplicatedSplitKey
- _OBJC_IVAR_$_TUIKeyboardCandidateMultiplexer._internalSharedClientWrapper
- _OBJC_IVAR_$_TUIKeyboardCandidateMultiplexer._internalSharedStickerStoreWrapper
- _UIKeyboardIsEmojiInputModeActive
- __OBJC_$_INSTANCE_METHODS_TUIKBKeyView
- ___92-[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]_block_invoke
- ___92-[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]_block_invoke_2
- ___MobileKeyBagLibraryCore_block_invoke
- ___block_descriptor_40_8_32s_e52_v24?0"<UITraitEnvironment>"8"UITraitCollection"16ls32l8
- ___block_descriptor_52_8_32s40s_e5_v8?0ls32l8s40l8
- ___block_descriptor_52_8_32s40w_e5_v8?0lw40l8s32l8
- ___getMKBGetDeviceLockStateSymbolLoc_block_invoke
- _audit_stringMobileKeyBag
- _getMKBGetDeviceLockStateSymbolLoc.ptr
- _symbolic So28TIKeyboardCandidateResultSetC
CStrings:
+ "#e"
+ "%@|"
+ "6"
+ "<%@: %p; left full = %@; left small = %@; core keys = %@; right small = %@; right full = %@>"
+ "<%@: %p; name = %@; preferredSize = %@; currentKeyplane = %@; frame = %@"
+ "Armenian"
+ "Assamese"
+ "B32@?0@\"TUIKey\"8Q16^B24"
+ "B32@?0@8Q16^B24"
+ "Cached key mismatch but no split support; expected %li vs %li"
+ "Cancelled paste candidate generation due to paste from remote clipboard"
+ "Cancelled smart reply generation due to text composer client being nil."
+ "Devanagari-Hindi"
+ "Devanagari-Marathi"
+ "EmojiRemoteKeyViewProvider"
+ "Fula-Adlam-QWERTY"
+ "GenerativeModelsAvailability changed; cleared cached eligibility"
+ "Genmoji creation not available: emoji input mode not available"
+ "Gujarati"
+ "Kannada"
+ "Kazakh-Cyrillic"
+ "Keyplane transition core keys: %@"
+ "Keyplane transition full row\nLeft: %@\nRight: %@"
+ "Keyplane transition small row\nLeft: %@\nRight: %@"
+ "Khmer"
+ "Korean10Key-Small-Wide"
+ "Kurdish-Sorani-QWERTY"
+ "Malayalam"
+ "Mongolian-Cyrillic"
+ "No view controller is set to receive autocorrections"
+ "Now resetting layout for updated keyplane."
+ "Oriya"
+ "Provider returned nil for key %{public}@ displayType=%d"
+ "Punjabi"
+ "Punjabi-Phonetic"
+ "QWERTY-Kurdish-Kurmanji"
+ "QWERTY-Numbers"
+ "QWERTY-VIQR"
+ "R"
+ "Remote view class %{public}@ does not respond to expected init"
+ "Santali-OlChiki-QWERTY"
+ "Screen traits changed split support. Force a reset on the next keyplane change."
+ "Sinhala"
+ "Stale timer handler fired (gen %lu, current %lu) - ignoring"
+ "Suppressing GLP search candidate: cannot evaluate authentication"
+ "TUIGenmojiCandidateCell"
+ "Tajik-Cyrillic"
+ "Tamil"
+ "Telugu"
+ "UIRemoteCategoryKeyView"
+ "UIRemoteEmojiAndStickerInputView"
+ "Uzbek-Cyrillic"
+ "W!!"
+ "Will perform deeper paste eligiblity check..."
+ "[%@:%@] forwarding invocation: [%@], target: %@, identifier: [%@]"
+ "[install-HOIST] key=%{public}@ hoisting grid into containment=%p so its variant selector draws above the search bar"
+ "[install-HOST-MISS] key=%{public}@ — no host TUIKBKeyView in storedKeyViews; falling back to sibling install"
+ "[install-HOST] key=%{public}@ host=%p hostFrame=%@"
+ "[install-WINDOW-MISS] key=%{public}@ host has no window yet — API fell back to host bounds; will retry on next walk"
+ "com.apple.EmojiPoster"
+ "com.apple.is-remote-clipboard"
+ "dynamic_emoji_layout"
+ "|"
+ "\x8b"
- "#T"
- "-[TUIInputSession acceptingCandidateWithTrigger:]"
- "-[TUIInputSession addSupplementalLexicon:completionHandler:]"
- "-[TUIInputSession adjustPhraseBoundaryInForwardDirection:granularity:keyboardState:completionHandler:]"
- "-[TUIInputSession adjustPhraseBoundaryInForwardDirection:keyboardState:completionHandler:]"
- "-[TUIInputSession candidateRejected:]"
- "-[TUIInputSession changingContextWithTrigger:]"
- "-[TUIInputSession generateInlineCompletions:withPrefix:]"
- "-[TUIInputSession generateRefinementsForCandidate:keyboardState:completionHandler:]"
- "-[TUIInputSession generateReplacementsForString:keyLayout:continuation:]"
- "-[TUIInputSession handleAcceptedCandidate:keyboardState:completionHandler:]"
- "-[TUIInputSession handleKeyboardInput:keyboardState:completionHandler:]"
- "-[TUIInputSession lastAcceptedCandidateCorrected]"
- "-[TUIInputSession logDiscoverabilityEvent:userInfo:]"
- "-[TUIInputSession performHitTestForTouchEvent:keyboardState:continuation:]"
- "-[TUIInputSession performHitTestForTouchEvents:keyboardState:continuation:]"
- "-[TUIInputSession predominantLanguageInContextWithCompletionHandler:]"
- "-[TUIInputSession registerLearning:fullCandidate:keyboardState:mode:]"
- "-[TUIInputSession registerLearningForCompletion:fullCompletion:context:prefix:mode:]"
- "-[TUIInputSession removeSupplementalLexiconWithIdentifier:]"
- "-[TUIInputSession setOriginalInput:]"
- "-[TUIInputSession skipHitTestForTouchEvent:keyboardState:]"
- "-[TUIInputSession skipHitTestForTouchEvents:keyboardState:]"
- "-[TUIInputSession smartSelectionForTextInDocument:inRange:language:tokenizedRanges:options:completion:]"
- "-[TUIInputSession stickerWithIdentifier:stickerRoles:completionHandler:]"
- "-[TUIInputSession textAccepted:]"
- "-[TUIInputSession textAccepted:completionHandler:]"
- "-[TUIInputSession writeTypologyLogWithCompletionHandler:]"
- "8"
- "<%@: %p> name = %@; preferredSize = %@; currentKeyplane = %@"
- "Autocorrection list contains candidates to be redacted.  Unsupported selector `redactedList`.  Sending empty autocorrection list instead."
- "Candidate result set contains candidates to be redacted.  Unsupported selector `redactedSet`.  Sending empty result set instead."
- "Floating transition core keys: %@"
- "Floating transition floating row\nLeft: %@\nRight: %@"
- "Floating transition full row\nLeft: %@\nRight: %@"
- "Genmoji creation not available: emoji input mode not active"
- "MKBGetDeviceLockState"
- "One Key"
- "W!"
- "softlink:r:path:/System/Library/PrivateFrameworks/MobileKeyBag.framework/MobileKeyBag"
- "{"
```
