## WritingToolsUI

> `/System/Library/PrivateFrameworks/WritingToolsUI.framework/WritingToolsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x66720` | `0x698fc` | **`+0x31dc`** |
| `__TEXT.__cstring` | `0x2ef7` | `0x34f7` | **`+0x600`** |
| `__AUTH_CONST.__cfstring` | `0xc40` | `0xe60` | **`+0x220`** |
| `__TEXT.__objc_methlist` | `0x48f4` | `0x4acc` | **`+0x1d8`** |
| `__TEXT.__gcc_except_tab` | `0xba0` | `0xd60` | **`+0x1c0`** |
| `__DATA_CONST.__objc_selrefs` | `0x2df8` | `0x2f68` | **`+0x170`** |
| `__TEXT.__unwind_info` | `0x1ac0` | `0x1c18` | **`+0x158`** |
| `__AUTH_CONST.__objc_const` | `0x6720` | `0x67d0` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0xcc8` | `0xd70` | **`+0xa8`** |
| `__DATA.__bss` | `0x3510` | `0x3590` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x1e5d` | `0x1ead` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0xd3c` | `0xd7c` | **`+0x40`** |
| `__TEXT.__const` | `0x30a4` | `0x30d4` | **`+0x30`** |
| `__DATA.__data` | `0x1ea8` | `0x1ed0` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x2030` | `0x2010` | **`-0x20`** |
| `__DATA.__common` | `0x108` | `0xf0` | **`-0x18`** |
| `__TEXT.__swift5_fieldmd` | `0xc30` | `0xc48` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xf58` | `0xf68` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x370` | `0x37c` | **`+0xc`** |
| `__AUTH.__data` | `0x8f8` | `0x900` | **`+0x8`** |
| `__AUTH.__objc_data` | `0x1408` | `0x1410` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xa20` | `0xa28` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xfb8` | `0xfc0` | **`+0x8`** |

### Other Changes

```diff

-129.1.103.0.0
+134.0.0.0.0

-  Functions: 2835
-  Symbols:   3049
-  CStrings:  492
+  Functions: 2918
+  Symbols:   3165
+  CStrings:  531
Symbols:
+ +[WTInputAnalytics _aopPayloadForSuggestion:bundleIdentifier:]
+ +[WTInputAnalytics _sendAOPSignal:forSuggestion:bundleIdentifier:]
+ +[WTInputAnalytics asyncSendSignal:toChannel:withPayload:]
+ +[WTInputAnalytics asyncSendWritingToolsSignal:payload:]
+ +[WTInputAnalytics getIAPayloadKeyAlwaysOnBundleID]
+ +[WTInputAnalytics getIAPayloadKeyAlwaysOnGrammarUUID]
+ +[WTInputAnalytics getIAPayloadKeyAlwaysOnModelInfo]
+ +[WTInputAnalytics getIAPayloadKeyAlwaysOnSuggestionCategory]
+ +[WTInputAnalytics getIAPayloadKeyAlwaysOnSuggestionCount]
+ +[WTInputAnalytics getIAPayloadKeyWritingToolsInputLanguage]
+ +[WTInputAnalytics getIASignalAlwaysOnProofreadingAcceptAllSuggestionsEngaged]
+ +[WTInputAnalytics getIASignalAlwaysOnProofreadingIgnoreAllSuggestionsEngaged]
+ +[WTInputAnalytics getIASignalAlwaysOnProofreadingPanelDismissed]
+ +[WTInputAnalytics getIASignalAlwaysOnProofreadingPanelIndexChanged]
+ +[WTInputAnalytics getIASignalAlwaysOnProofreadingPanelShown]
+ +[WTInputAnalytics getIASignalAlwaysOnProofreadingSuggestionAcceptedInPanel]
+ +[WTInputAnalytics getIASignalAlwaysOnProofreadingSuggestionAccepted]
+ +[WTInputAnalytics getIASignalAlwaysOnProofreadingSuggestionBubbleShown]
+ +[WTInputAnalytics getIASignalAlwaysOnProofreadingSuggestionIgnored]
+ +[WTInputAnalytics getIASignalAlwaysOnProofreadingSuggestionShown]
+ +[WTInputAnalytics getIASignalAlwaysOnProofreadingTemporarilyPauseSuggestionsEngaged]
+ +[WTInputAnalytics sendAOPAcceptAllSuggestionsWithCount:bundleIdentifier:]
+ +[WTInputAnalytics sendAOPIgnoreAllSuggestionsWithCount:bundleIdentifier:]
+ +[WTInputAnalytics sendAOPPanelDismissedForSuggestion:bundleIdentifier:]
+ +[WTInputAnalytics sendAOPPanelIndexChangedForSuggestion:bundleIdentifier:]
+ +[WTInputAnalytics sendAOPPanelShownForSuggestion:bundleIdentifier:]
+ +[WTInputAnalytics sendAOPSuggestionAcceptedInPanelForSuggestion:bundleIdentifier:]
+ +[WTInputAnalytics sendAOPSuggestionIgnoredForSuggestion:bundleIdentifier:]
+ +[WTInputAnalytics sendAOPTemporarilyPauseSuggestionsWithBundleIdentifier:]
+ -[WTWritingToolsController presentingError]
+ -[WTWritingToolsController setPresentingError:]
+ -[_WTReplaceTextEffect _ownLineHeight]
+ -[_WTReplaceTextEffect _sharedSweepFrame]
+ -[_WTReplaceTextEffect _sharedSweepHeight]
+ -[_WTTextEffectView replaceLineHeight]
+ -[_WTTextEffectView replaceSweepFrameHeight]
+ -[_WTTextEffectView setReplaceLineHeight:]
+ -[_WTTextEffectView setReplaceSweepFrameHeight:]
+ GCC_except_table104
+ GCC_except_table110
+ GCC_except_table147
+ GCC_except_table162
+ GCC_except_table165
+ GCC_except_table205
+ GCC_except_table212
+ GCC_except_table214
+ GCC_except_table216
+ GCC_except_table3
+ GCC_except_table47
+ GCC_except_table53
+ GCC_except_table55
+ GCC_except_table57
+ GCC_except_table59
+ GCC_except_table61
+ GCC_except_table63
+ GCC_except_table65
+ GCC_except_table67
+ GCC_except_table69
+ GCC_except_table71
+ GCC_except_table73
+ GCC_except_table75
+ GCC_except_table77
+ GCC_except_table79
+ _MGGetBoolAnswer
+ _OBJC_IVAR_$_WTWritingToolsController._presentingError
+ _OBJC_IVAR_$__WTTextEffectView._replaceLineHeight
+ _OBJC_IVAR_$__WTTextEffectView._replaceSweepFrameHeight
+ _WTWritingToolsPreservedAttributeName
+ ___58+[WTInputAnalytics asyncSendSignal:toChannel:withPayload:]_block_invoke
+ ___83-[WTFullScreenContainerViewController _sendKeyboardTrackingNotificationsForReason:]_block_invoke
+ ___99-[WTUIAttributedStringController reconstitutedAttributedStringForContext:digestedAttributedString:]_block_invoke
+ ___99-[WTUIAttributedStringController reconstitutedAttributedStringForContext:digestedAttributedString:]_block_invoke_2
+ ___block_descriptor_40_e8_32r_e27_v40?08{_NSRange=QQ}16^B32lr32l8
+ ___block_descriptor_40_e8_32s_e27_v40?08{_NSRange=QQ}16^B32ls32l8
+ ___block_descriptor_48_e8_32s40s_e27_v40?08{_NSRange=QQ}16^B32ls32l8s40l8
+ ___block_descriptor_48_e8_32s40w_e5_B8?0lw40l8s32l8
+ ___block_descriptor_64_e8_32s40s48s_e5_v8?0lu56l8s32l8s40l8s48l8
+ ___getIAPayloadKeyWritingToolsAlwaysOnBundleIDSymbolLoc_block_invoke
+ ___getIAPayloadKeyWritingToolsAlwaysOnGrammarUUIDSymbolLoc_block_invoke
+ ___getIAPayloadKeyWritingToolsAlwaysOnModelInfoSymbolLoc_block_invoke
+ ___getIAPayloadKeyWritingToolsAlwaysOnSuggestionCategorySymbolLoc_block_invoke
+ ___getIAPayloadKeyWritingToolsAlwaysOnSuggestionCountSymbolLoc_block_invoke
+ ___getIAPayloadKeyWritingToolsInputLanguageSymbolLoc_block_invoke
+ ___getIASignalWritingToolsAlwaysOnProofreadingAcceptAllSuggestionsEngagedSymbolLoc_block_invoke
+ ___getIASignalWritingToolsAlwaysOnProofreadingIgnoreAllSuggestionsEngagedSymbolLoc_block_invoke
+ ___getIASignalWritingToolsAlwaysOnProofreadingPanelDismissedSymbolLoc_block_invoke
+ ___getIASignalWritingToolsAlwaysOnProofreadingPanelIndexChangedSymbolLoc_block_invoke
+ ___getIASignalWritingToolsAlwaysOnProofreadingPanelShownSymbolLoc_block_invoke
+ ___getIASignalWritingToolsAlwaysOnProofreadingSuggestionAcceptedInPanelSymbolLoc_block_invoke
+ ___getIASignalWritingToolsAlwaysOnProofreadingSuggestionAcceptedSymbolLoc_block_invoke
+ ___getIASignalWritingToolsAlwaysOnProofreadingSuggestionBubbleShownSymbolLoc_block_invoke
+ ___getIASignalWritingToolsAlwaysOnProofreadingSuggestionIgnoredSymbolLoc_block_invoke
+ ___getIASignalWritingToolsAlwaysOnProofreadingSuggestionShownSymbolLoc_block_invoke
+ ___getIASignalWritingToolsAlwaysOnProofreadingTemporarilyPauseSuggestionsEngagedSymbolLoc_block_invoke
+ ___swift_closure_destructor.126Tm
+ _dispatch_get_global_queue
+ _getIAPayloadKeyWritingToolsAlwaysOnBundleIDSymbolLoc
+ _getIAPayloadKeyWritingToolsAlwaysOnBundleIDSymbolLoc.ptr
+ _getIAPayloadKeyWritingToolsAlwaysOnGrammarUUIDSymbolLoc
+ _getIAPayloadKeyWritingToolsAlwaysOnGrammarUUIDSymbolLoc.ptr
+ _getIAPayloadKeyWritingToolsAlwaysOnModelInfoSymbolLoc
+ _getIAPayloadKeyWritingToolsAlwaysOnModelInfoSymbolLoc.ptr
+ _getIAPayloadKeyWritingToolsAlwaysOnSuggestionCategorySymbolLoc
+ _getIAPayloadKeyWritingToolsAlwaysOnSuggestionCategorySymbolLoc.ptr
+ _getIAPayloadKeyWritingToolsAlwaysOnSuggestionCountSymbolLoc
+ _getIAPayloadKeyWritingToolsAlwaysOnSuggestionCountSymbolLoc.ptr
+ _getIAPayloadKeyWritingToolsInputLanguageSymbolLoc
+ _getIAPayloadKeyWritingToolsInputLanguageSymbolLoc.ptr
+ _getIASignalWritingToolsAlwaysOnProofreadingAcceptAllSuggestionsEngagedSymbolLoc
+ _getIASignalWritingToolsAlwaysOnProofreadingAcceptAllSuggestionsEngagedSymbolLoc.ptr
+ _getIASignalWritingToolsAlwaysOnProofreadingIgnoreAllSuggestionsEngagedSymbolLoc
+ _getIASignalWritingToolsAlwaysOnProofreadingIgnoreAllSuggestionsEngagedSymbolLoc.ptr
+ _getIASignalWritingToolsAlwaysOnProofreadingPanelDismissedSymbolLoc
+ _getIASignalWritingToolsAlwaysOnProofreadingPanelDismissedSymbolLoc.ptr
+ _getIASignalWritingToolsAlwaysOnProofreadingPanelIndexChangedSymbolLoc
+ _getIASignalWritingToolsAlwaysOnProofreadingPanelIndexChangedSymbolLoc.ptr
+ _getIASignalWritingToolsAlwaysOnProofreadingPanelShownSymbolLoc
+ _getIASignalWritingToolsAlwaysOnProofreadingPanelShownSymbolLoc.ptr
+ _getIASignalWritingToolsAlwaysOnProofreadingSuggestionAcceptedInPanelSymbolLoc
+ _getIASignalWritingToolsAlwaysOnProofreadingSuggestionAcceptedInPanelSymbolLoc.ptr
+ _getIASignalWritingToolsAlwaysOnProofreadingSuggestionAcceptedSymbolLoc
+ _getIASignalWritingToolsAlwaysOnProofreadingSuggestionAcceptedSymbolLoc.ptr
+ _getIASignalWritingToolsAlwaysOnProofreadingSuggestionBubbleShownSymbolLoc
+ _getIASignalWritingToolsAlwaysOnProofreadingSuggestionBubbleShownSymbolLoc.ptr
+ _getIASignalWritingToolsAlwaysOnProofreadingSuggestionIgnoredSymbolLoc
+ _getIASignalWritingToolsAlwaysOnProofreadingSuggestionIgnoredSymbolLoc.ptr
+ _getIASignalWritingToolsAlwaysOnProofreadingSuggestionShownSymbolLoc
+ _getIASignalWritingToolsAlwaysOnProofreadingSuggestionShownSymbolLoc.ptr
+ _getIASignalWritingToolsAlwaysOnProofreadingTemporarilyPauseSuggestionsEngagedSymbolLoc
+ _getIASignalWritingToolsAlwaysOnProofreadingTemporarilyPauseSuggestionsEngagedSymbolLoc.ptr
- GCC_except_table103
- GCC_except_table109
- GCC_except_table146
- GCC_except_table161
- GCC_except_table164
- GCC_except_table204
- GCC_except_table211
- GCC_except_table213
- GCC_except_table215
- GCC_except_table5
- GCC_except_table6
- GCC_except_table68
- ___block_descriptor_32_e23_v16?0"UIAlertAction"8l
- ___swift_closure_destructor.122Tm
CStrings:
+ "2`"
+ "AlwaysOnProofreadingAcceptAllSuggestionsEngaged"
+ "AlwaysOnProofreadingIgnoreAllSuggestionsEngaged"
+ "AlwaysOnProofreadingPanelDismissed"
+ "AlwaysOnProofreadingPanelIndexChanged"
+ "AlwaysOnProofreadingPanelShown"
+ "AlwaysOnProofreadingSuggestionAccepted"
+ "AlwaysOnProofreadingSuggestionAcceptedInPanel"
+ "AlwaysOnProofreadingSuggestionBubbleShown"
+ "AlwaysOnProofreadingSuggestionIgnored"
+ "AlwaysOnProofreadingSuggestionShown"
+ "AlwaysOnProofreadingTemporarilyPauseSuggestionsEngaged"
+ "B8@?0"
+ "BundleID"
+ "DisableInvisibleTextWorkaround"
+ "GrammarUUID"
+ "IAPayloadKeyWritingToolsAlwaysOnBundleID"
+ "IAPayloadKeyWritingToolsAlwaysOnGrammarUUID"
+ "IAPayloadKeyWritingToolsAlwaysOnModelInfo"
+ "IAPayloadKeyWritingToolsAlwaysOnSuggestionCategory"
+ "IAPayloadKeyWritingToolsAlwaysOnSuggestionCount"
+ "IAPayloadKeyWritingToolsInputLanguage"
+ "IASignalWritingToolsAlwaysOnProofreadingAcceptAllSuggestionsEngaged"
+ "IASignalWritingToolsAlwaysOnProofreadingIgnoreAllSuggestionsEngaged"
+ "IASignalWritingToolsAlwaysOnProofreadingPanelDismissed"
+ "IASignalWritingToolsAlwaysOnProofreadingPanelIndexChanged"
+ "IASignalWritingToolsAlwaysOnProofreadingPanelShown"
+ "IASignalWritingToolsAlwaysOnProofreadingSuggestionAccepted"
+ "IASignalWritingToolsAlwaysOnProofreadingSuggestionAcceptedInPanel"
+ "IASignalWritingToolsAlwaysOnProofreadingSuggestionBubbleShown"
+ "IASignalWritingToolsAlwaysOnProofreadingSuggestionIgnored"
+ "IASignalWritingToolsAlwaysOnProofreadingSuggestionShown"
+ "IASignalWritingToolsAlwaysOnProofreadingTemporarilyPauseSuggestionsEngaged"
+ "InputLanguage"
+ "ModelInfo"
+ "SuggestionCategory"
+ "SuggestionCount"
+ "setSession: external result — skipping KB suppression and updateSourceView"
+ "v40@?0@8{_NSRange=QQ}16^B32"
```
