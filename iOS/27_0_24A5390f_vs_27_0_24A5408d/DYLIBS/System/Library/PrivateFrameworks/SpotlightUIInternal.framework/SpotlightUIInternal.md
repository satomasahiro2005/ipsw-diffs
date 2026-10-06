## SpotlightUIInternal

> `/System/Library/PrivateFrameworks/SpotlightUIInternal.framework/SpotlightUIInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ea80` | `0x4f1d4` | **`+0x754`** |
| `__AUTH_CONST.__cfstring` | `0x15a0` | `0x1900` | **`+0x360`** |
| `__TEXT.__cstring` | `0x1218` | `0x13c2` | **`+0x1aa`** |
| `__DATA_CONST.__const` | `0xb70` | `0xc60` | **`+0xf0`** |
| `__AUTH_CONST.__objc_const` | `0x91f0` | `0x92a0` | **`+0xb0`** |
| `__AUTH.__data` | `0x3d0` | `0x470` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0xbf0` | `0xc70` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x12da` | `0x132a` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x42d8` | `0x4320` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x15b8` | `0x1600` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x684` | `0x6c8` | **`+0x44`** |
| `__DATA.__bss` | `0xbf8` | `0xc28` | **`+0x30`** |
| `__TEXT.__const` | `0x1398` | `0x13c0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x5d00` | `0x5d28` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0xca8` | `0xcc8` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x3a0` | `0x3bc` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0xe00` | `0xe1a` | **`+0x1a`** |
| `__AUTH_CONST.__auth_got` | `0xda0` | `0xdb0` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x34` | `0x40` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x44` | `0x50` | **`+0xc`** |
| `__TEXT.__swift5_reflstr` | `0x326` | `0x330` | **`+0xa`** |
| `__DATA.__data` | `0x1738` | `0x1740` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x420` | `0x418` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xa88` | `0xa90` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1d8` | `0x1e0` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x84` | `0x8c` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x26c` | `0x270` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x60` | `0x64` | **`+0x4`** |

### Other Changes

```diff

-236.0.11.100.0
+236.0.21.100.0

-  Functions: 2038
-  Symbols:   3251
-  CStrings:  337
+  Functions: 2058
+  Symbols:   3263
+  CStrings:  367
Symbols:
+ +[SPUIFeedbackManager feedbackQueue]
+ +[SPUISearchViewController stringForInvocationSource:]
+ +[SPUISearchViewController stringForPresentationSource:]
+ -[SPUISearchHeader(SUICompletionViewControllerDelegate) completionTypedQueryAddressesExternalProvider:]
+ -[SPUISearchViewController currentlyDisplayedResultsViewController]
+ -[SPUISearchViewController shouldAllowAskSiriForModel:]
+ GCC_except_table92
+ _OBJC_CLASS_$_NSCache
+ __DATA__TtCC19SpotlightUIInternal36SPUIExternalGenerativePartnerManagerP33_A96508C3EE92D1DF1644A8F59FE141E316ProviderSnapshot
+ __IVARS__TtCC19SpotlightUIInternal36SPUIExternalGenerativePartnerManagerP33_A96508C3EE92D1DF1644A8F59FE141E316ProviderSnapshot
+ __METACLASS_DATA__TtCC19SpotlightUIInternal36SPUIExternalGenerativePartnerManagerP33_A96508C3EE92D1DF1644A8F59FE141E316ProviderSnapshot
+ __OBJC_$_CLASS_METHODS__TtC19SpotlightUIInternal36SPUIExternalGenerativePartnerManager(SpotlightUIInternal)
+ __OBJC_$_PROP_LIST_SearchUICommandDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SUICompletionViewControllerDelegate
+ ___36+[SPUIFeedbackManager feedbackQueue]_block_invoke
+ ___48+[SPUIFeedbackManager resultsDidFinishForModel:]_block_invoke
+ ___block_descriptor_65_e8_32s40s_e5_v8?0ls32l8s40l8
+ _feedbackQueue.feedbackQueue
+ _feedbackQueue.onceToken
+ _symbolic Say_____G 13CampoServices15MontaraProviderV
+ _symbolic _____ 19SpotlightUIInternal36SPUIExternalGenerativePartnerManagerC16ProviderSnapshot33_A96508C3EE92D1DF1644A8F59FE141E3LLC
+ _symbolic _____XMT 19SpotlightUIInternal36SPUIExternalGenerativePartnerManagerC
- -[SPUITextField isCursorVisible]
- -[SPUITextField setIsCursorVisible:]
- -[SPUITextView caretAssertion]
- -[SPUITextView isCursorVisible]
- -[SPUITextView setCaretAssertion:]
- -[SPUITextView setIsCursorVisible:]
- GCC_except_table89
- _OBJC_IVAR_$_SPUITextField.isCursorVisible
- _OBJC_IVAR_$_SPUITextView._caretAssertion
- __CLASS_METHODS__TtC19SpotlightUIInternal36SPUIExternalGenerativePartnerManager
CStrings:
+ "AppToolbar"
+ "AskSiri"
+ "BreadCrumb"
+ "Camera"
+ "ContextMenu"
+ "DynamicIslandPullDown"
+ "HardwareKeyboard"
+ "HomeScreenButton"
+ "KeyboardCandidateBar"
+ "NO"
+ "NotificationCenter"
+ "PartialPullDown"
+ "Photos"
+ "PullDownHomeScreen"
+ "PullDownNotificationCenter"
+ "ScreenshotUI"
+ "ScribbleUI"
+ "SiriApp"
+ "TextCursorAffordance"
+ "TextEditMenu"
+ "TextEditWritingToolsPanel"
+ "TextFormatBar"
+ "TodayView"
+ "Unknown"
+ "Unspecified"
+ "VisualIntelligence"
+ "YES"
+ "com.apple.spotlightui.feedbackQueue"
+ "invoked deviceLockState=%@ isOverApp=%@ presentationSource=%@ afInvocationSource=%@"
+ "providers"
```
