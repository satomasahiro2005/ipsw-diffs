## ChatKit

> `/System/Library/PrivateFrameworks/ChatKit.framework/ChatKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc3699c` | `0xc3b17c` | **`+0x47e0`** |
| `__DATA.__bss` | `0x44f40` | `0x45300` | **`+0x3c0`** |
| `__DATA_DIRTY.__objc_data` | `0x65a8` | `0x68a8` | **`+0x300`** |
| `__TEXT.__const` | `0x41854` | `0x41af4` | **`+0x2a0`** |
| `__TEXT.__cstring` | `0x3f9e7` | `0x3fbf7` | **`+0x210`** |
| `__TEXT.__oslogstring` | `0x55d67` | `0x55f57` | **`+0x1f0`** |
| `__AUTH_CONST.__const` | `0x3f948` | `0x3faf8` | **`+0x1b0`** |
| `__AUTH.__objc_data` | `0x2cb78` | `0x2c9f8` | **`-0x180`** |
| `__AUTH_CONST.__objc_const` | `0x9e0e0` | `0x9e248` | **`+0x168`** |
| `__TEXT.__swift5_fieldmd` | `0x10fc8` | `0x11104` | **`+0x13c`** |
| `__TEXT.__unwind_info` | `0x31ed0` | `0x31ff8` | **`+0x128`** |
| `__TEXT.__eh_frame` | `0x12e98` | `0x12f98` | **`+0x100`** |
| `__TEXT.__swift5_typeref` | `0x4945a` | `0x49556` | **`+0xfc`** |
| `__TEXT.__objc_methlist` | `0x73664` | `0x73754` | **`+0xf0`** |
| `__DATA.__data` | `0x226d0` | `0x22790` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x1e040` | `0x1e0e8` | **`+0xa8`** |
| `__DATA_DIRTY.__data` | `0x608` | `0x6a8` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x37820` | `0x378a0` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x12fd3` | `0x13053` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x6bd8` | `0x6c28` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x208f4` | `0x20934` | **`+0x40`** |
| `__AUTH.__data` | `0x15ca0` | `0x15c70` | **`-0x30`** |
| `__DATA.__common` | `0x1630` | `0x1600` | **`-0x30`** |
| `__AUTH_CONST.__cfstring` | `0x244c0` | `0x244e0` | **`+0x20`** |
| `__DATA_DIRTY.__common` | `0x48` | `0x68` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x1d14` | `0x1d30` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0x3028` | `0x3038` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x14a4` | `0x14b4` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x4a18` | `0x4a20` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x7d48` | `0x7d50` | **`+0x8`** |

### Other Changes

```diff

-1491.200.63.2.1
+1491.200.73.0.0

+  - /System/Library/PrivateFrameworks/SearchIntrospectionKit.framework/SearchIntrospectionKit

-  Functions: 75143
-  Symbols:   73854
-  CStrings:  13285
+  Functions: 75250
+  Symbols:   73903
+  CStrings:  13304
Symbols:
+ +[CKAttachmentSearchResultCell renderedTitleForSearchText:attributeSet:]
+ +[CKConversationAvatarSearchResultCell renderedNameForConversation:searchText:]
+ +[CKConversationSearchResultCell renderedSummaryForResult:searchText:]
+ +[CKLocationSearchResultCell renderedPlaceForResult:searchText:]
+ +[CKMessageSearchResultCell renderedBodyForResult:searchText:]
+ -[CKConversationListCollectionViewController _preloadDraftsWithReason:]
+ -[CKConversationListCollectionViewController hasRequestedDraftsPreload]
+ -[CKConversationListCollectionViewController setHasRequestedDraftsPreload:]
+ -[CKPinnedConversationView _muteIndicatorColor]
+ -[CKPinnedConversationView _showsMuteIndicator]
+ -[CKSearchViewController _reportSearchIntrospection]
+ -[CKUIBehavior ckShouldUpdatepinnedConversationMutedIndicatorImage]
+ -[CKUIBehavior pinnedConversationMutedIndicatorImage]
+ -[CKUIBehaviorMac ckShouldUpdatepinnedConversationMutedIndicatorImage]
+ -[CKUIBehaviorMac pinnedConversationMutedIndicatorImage]
+ -[_CKStickerEntry isFromMe]
+ -[_CKStickerEntry setIsFromMe:]
+ GCC_except_table1412
+ GCC_except_table463
+ _OBJC_CLASS_$_CKSearchIntrospectionReporting
+ _OBJC_CLASS_$_CKSearchIntrospectionSection
+ _OBJC_IVAR_$_CKConversationListCollectionViewController._hasRequestedDraftsPreload
+ _OBJC_IVAR_$__CKStickerEntry._isFromMe
+ _OBJC_METACLASS_$_CKSearchIntrospectionReporting
+ _OBJC_METACLASS_$_CKSearchIntrospectionSection
+ __CLASS_METHODS_CKSearchIntrospectionReporting
+ __DATA_CKSearchIntrospectionReporting
+ __DATA_CKSearchIntrospectionSection
+ __INSTANCE_METHODS_CKSearchIntrospectionReporting
+ __INSTANCE_METHODS_CKSearchIntrospectionSection
+ __IVARS_CKSearchIntrospectionSection
+ __METACLASS_DATA_CKSearchIntrospectionReporting
+ __METACLASS_DATA_CKSearchIntrospectionSection
+ ___71-[CKConversationListCollectionViewController _preloadDraftsWithReason:]_block_invoke
+ _associated conformance 7ChatKit26MessagesSearchResultDetailV10CodingKeys33_744BCB8B029E6247F9DEB3642334AA47LLOSHAASQ
+ _associated conformance 7ChatKit26MessagesSearchResultDetailV10CodingKeys33_744BCB8B029E6247F9DEB3642334AA47LLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 7ChatKit26MessagesSearchResultDetailV10CodingKeys33_744BCB8B029E6247F9DEB3642334AA47LLOs0G3KeyAAs28CustomDebugStringConvertible
+ _pinnedConversationMutedIndicatorImage.sBehavior
+ _pinnedConversationMutedIndicatorImage.sContentSizeCategory_pinnedConversationMutedIndicatorImage
+ _pinnedConversationMutedIndicatorImage.sCustomTextFontName_pinnedConversationMutedIndicatorImage
+ _pinnedConversationMutedIndicatorImage.sCustomTextFontSize_pinnedConversationMutedIndicatorImage
+ _pinnedConversationMutedIndicatorImage.sIsBoldTextEnabled_pinnedConversationMutedIndicatorImage
+ _pinnedConversationMutedIndicatorImage.sIsIncreaseContrastEnabled_pinnedConversationMutedIndicatorImage
+ _pinnedConversationMutedIndicatorImage.sTextFontSize_pinnedConversationMutedIndicatorImage
+ _symbolic _____ 7ChatKit26MessagesSearchResultDetailV
+ _symbolic _____ 7ChatKit26MessagesSearchResultDetailV10CodingKeys33_744BCB8B029E6247F9DEB3642334AA47LLO
+ _symbolic _____ 7ChatKit28CKSearchIntrospectionSectionC
+ _symbolic _____ 7ChatKit30CKSearchIntrospectionReportingC
+ _symbolic _____Sg s15ContinuousClockV7InstantV
+ _symbolic _____ySo18NSAttributedStringCG 22SearchIntrospectionKit11SecureCodedV
+ _symbolic _____ySo18NSAttributedStringCGSg 22SearchIntrospectionKit11SecureCodedV
+ _symbolic _____y_____G 22SearchIntrospectionKit14ReportedResultV 04ChatC008MessagesaE6DetailV
+ _symbolic _____y_____G 22SearchIntrospectionKit15ReportedSectionV 04ChatC008MessagesA12ResultDetailV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7ChatKit26MessagesSearchResultDetailV10CodingKeys33_744BCB8B029E6247F9DEB3642334AA47LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7ChatKit26MessagesSearchResultDetailV10CodingKeys33_744BCB8B029E6247F9DEB3642334AA47LLO
+ _symbolic _____y_____y_____GG s23_ContiguousArrayStorageC 22SearchIntrospectionKit14ReportedResultV 04ChatF008MessagesdH6DetailV
+ _symbolic _____y_____y_____GG s23_ContiguousArrayStorageC 22SearchIntrospectionKit15ReportedSectionV 04ChatF008MessagesD12ResultDetailV
+ _type_layout_string 7ChatKit26MessagesSearchResultDetailV
- +[CKConversationLargeTextSearchCell annotatedResultStringWithSearchText:resultText:primaryTextColor:primaryFont:annotatedTextColor:annotatedFont:]
- +[CKConversationSearchResultEmbeddedCell annotatedResultStringWithSearchText:resultText:primaryTextColor:primaryFont:annotatedTextColor:annotatedFont:]
- -[CKMessageSearchResultCell _annotatedResultStringForResult:searchText:]
- GCC_except_table1410
- GCC_except_table461
- __OBJC_$_CLASS_METHODS_CKConversationLargeTextSearchCell
- __OBJC_$_CLASS_METHODS_CKConversationSearchResultEmbeddedCell
- ___72-[CKConversationListCollectionViewController viewDidAppearDeferredSetup]_block_invoke_5
- ___72-[CKConversationListCollectionViewController viewDidAppearDeferredSetup]_block_invoke_6
CStrings:
+ "ChatKit.CKSearchIntrospectionSection"
+ "Clearing group photo. [%s]"
+ "Not reporting zero-keyword results against a {%lu} char query"
+ "Updating group photo. [%s]"
+ "User reported an extended transcript push that took "
+ "[Auto Capture] Slow Messages transcript push: ("
+ "com.apple.HangTracer.HangLogsDiagnosticExtension"
+ "com.apple.MobileSMS.ExtendedTranscriptPushSlow"
+ "conversationName"
+ "drafts reloaded on resume"
+ "handleGroupIdentityChange: committing display name '%s' to chat [%s]"
+ "handleGroupIdentityChange: display name unchanged, not committing [%s]"
+ "handleGroupIdentityChange: group photo unchanged, not updating [%s]"
+ "handleGroupIdentityChange: incoming name '%s', current name '%s' [%s]"
+ "handleGroupIdentityChange: not a group conversation, ignoring [%s]"
+ "s maximum threshold. This radar was filed automatically."
+ "s) transcript push hang detected!"
+ "s, exceeding the "
+ "searchableItemIdentifier"
+ "sectionIdentifier"
- "Updating group photo."
```
