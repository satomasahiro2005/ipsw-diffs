## SpotlightUIInternal

> `/System/Library/PrivateFrameworks/SpotlightUIInternal.framework/SpotlightUIInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x46e00` | `0x4a2a0` | **`+0x34a0`** |
| `__DATA_DIRTY.__objc_data` | `0x5f0` | `0xa48` | **`+0x458`** |
| `__AUTH.__objc_data` | `0xe38` | `0xa80` | **`-0x3b8`** |
| `__DATA_DIRTY.__bss` | `0x38` | `0x260` | **`+0x228`** |
| `__DATA.__bss` | `0xb58` | `0x950` | **`-0x208`** |
| `__DATA_DIRTY.__data` | `—` | `0x1c8` | **`+0x1c8`** |
| `__TEXT.__eh_frame` | `0x9f4` | `0xbb4` | **`+0x1c0`** |
| `__AUTH_CONST.__objc_const` | `0x8da0` | `0x8f48` | **`+0x1a8`** |
| `__TEXT.__oslogstring` | `0xd85` | `0xe95` | **`+0x110`** |
| `__DATA_CONST.__objc_selrefs` | `0x40b0` | `0x41a0` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x5a58` | `0x5b38` | **`+0xe0`** |
| `__AUTH.__data` | `0x4b8` | `0x408` | **`-0xb0`** |
| `__TEXT.__unwind_info` | `0x1430` | `0x14d8` | **`+0xa8`** |
| `__TEXT.__const` | `0x1008` | `0x10a8` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0xccc` | `0xd6a` | **`+0x9e`** |
| `__AUTH_CONST.__cfstring` | `0x1580` | `0x15e0` | **`+0x60`** |
| `__DATA_CONST.__got` | `0xa00` | `0xa58` | **`+0x58`** |
| `__AUTH_CONST.__const` | `0xa48` | `0xa78` | **`+0x30`** |
| `__DATA.__data` | `0x1728` | `0x16f8` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x2cb` | `0x2fb` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x330` | `0x358` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0xd40` | `0xd58` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x400` | `0x410` | **`+0x10`** |
| `__TEXT.__cstring` | `0x12ff` | `0x130f` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x670` | `0x67c` | **`+0xc`** |
| `__DATA.__common` | `0x8` | `—` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1c0` | `0x1c8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x1c8` | `0x1d0` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x74` | `0x7c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x50` | `0x54` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x38` | `0x3c` | **`+0x4`** |

### Other Changes

```diff

-235.3.100.0.0
+236.0.4.100.0

+  - /System/Library/PrivateFrameworks/DeviceManagement.framework/DeviceManagement

+  - /System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices

+  - /System/Library/PrivateFrameworks/GenerativePartnerServiceUI.framework/GenerativePartnerServiceUI

-  Functions: 1889
-  Symbols:   3157
-  CStrings:  327
+  Functions: 1938
+  Symbols:   3205
+  CStrings:  332
Symbols:
+ -[SPUINavigationController footerViewCache]
+ -[SPUINavigationController setFooterViewCache:]
+ -[SPUIResultsViewController displayState]
+ -[SPUIResultsViewController setDisplayState:]
+ -[SPUISearchHeader(SUICompletionViewControllerDelegate) setSearchFieldVisible:]
+ -[SPUISearchViewController displayPolicyDidTransitionToState:]
+ -[SPUISearchViewController displayPolicy]
+ -[SPUISearchViewController hasPushedViewController]
+ -[SPUISearchViewController searchFieldContentsDidChange]
+ -[SPUISearchViewController setDisplayPolicy:]
+ -[SPUITextView providerCursorTintColor]
+ -[SPUITextView setProviderCursorTintColor:]
+ GCC_except_table44
+ _OBJC_CLASS_$_DMFPolicyMonitor
+ _OBJC_CLASS_$_FBSDisplayLayoutElement
+ _OBJC_CLASS_$_FBSDisplayLayoutMonitor
+ _OBJC_CLASS_$_FBSDisplayLayoutMonitorConfiguration
+ _OBJC_CLASS_$_NSLock
+ _OBJC_CLASS_$_SPUIForegroundAppMonitor
+ _OBJC_CLASS_$_SPUISAskSiriResultBuilder
+ _OBJC_CLASS_$_SSMixedRankingUtilities
+ _OBJC_CLASS_$_SUISDisplaySignals
+ _OBJC_CLASS_$_SUISWindowDisplayPolicy
+ _OBJC_IVAR_$_SPUINavigationController._footerViewCache
+ _OBJC_IVAR_$_SPUIResultsViewController._displayState
+ _OBJC_IVAR_$_SPUISearchViewController._displayPolicy
+ _OBJC_IVAR_$_SPUITextView._providerCursorTintColor
+ _OBJC_METACLASS_$_SPUIForegroundAppMonitor
+ __CLASS_METHODS_SPUIForegroundAppMonitor
+ __CLASS_PROPERTIES_SPUIForegroundAppMonitor
+ __DATA_SPUIForegroundAppMonitor
+ __INSTANCE_METHODS_SPUIForegroundAppMonitor
+ __IVARS_SPUIForegroundAppMonitor
+ __METACLASS_DATA_SPUIForegroundAppMonitor
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SUISWindowDisplayPolicyDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SUISWindowDisplayPolicyDelegate
+ __OBJC_$_PROTOCOL_REFS_SUISWindowDisplayPolicyDelegate
+ __OBJC_LABEL_PROTOCOL_$_SUISWindowDisplayPolicyDelegate
+ __OBJC_PROTOCOL_$_SUISWindowDisplayPolicyDelegate
+ __PROPERTIES_SPUIForegroundAppMonitor
+ ___swift_allocate_value_buffer
+ ___swift_project_value_buffer
+ __swiftEmptyDictionarySingleton
+ _swift_allocError
+ _swift_continuation_throwingResume
+ _swift_continuation_throwingResumeWithError
+ _swift_willThrow
+ _symbolic SSSg
+ _symbolic SaySo23FBSDisplayLayoutElementCG
+ _symbolic SccySDySSSo8NSNumberCG______pG s5ErrorP
+ _symbolic So23FBSDisplayLayoutMonitorCSg
+ _symbolic So6NSLockC
+ _symbolic _____ 19SpotlightUIInternal20ForegroundAppMonitorC
+ _symbolic _____SgXw 19SpotlightUIInternal20ForegroundAppMonitorC
+ _symbolic ______p s5ErrorP
+ _symbolic _____ySSSo8NSNumberCG s18_DictionaryStorageC
+ _symbolic _____ySnySiGG s23_ContiguousArrayStorageC
- -[SPUISearchHeader(SUICompletionViewControllerDelegate) setCursorVisible:]
- -[SPUISearchViewController searchTextDidChange]
- GCC_except_table45
- ___65-[SPUINavigationController generateFooterViewForProactive:cache:]_block_invoke
- _generateFooterViewForProactive:cache:.footerViewCache
- _generateFooterViewForProactive:cache:.onceToken
- _swift_release_x28
- _symbolic _____Sg 17SpotlightUIShared9DebouncerC
- _symbolic _____SgXw 19SpotlightUIInternal21AccessoryStateManagerC
CStrings:
+ "  section: bundle=%{public}@ title=%{public}@ resultCount=%lu"
+ "(nil)"
+ "DisplayPolicy signals: query=%{public}@ qid=%lu len=%ld elevatable=%d isSiriWorthy=%d firstBundle=%{public}@ firstResultBundle=%{public}@ firstResultCount=%lu hasTopHits=%d hasTopHitResult=%d complete=%d sectionCount=%lu"
+ "T"
+ "com.apple."
+ "displayPolicyDidTransitionToState: transitioning to AskSiri, setting Ask Siri completion"
+ "frontmost = %{public}s"
+ "nil"
+ "non-nil"
+ "searchAgentUpdatedResults: sectionCount=%lu complete=%d priorityComplete=%d"
+ "updateSelectedItem: setting Ask Siri completion"
+ "updateSelectedItem: setting non-Ask Siri completion (selectedItem=%{public}@)"
- "S"
- "com.apple.spotlight.tophits"
- "debouncedUpdateAccessoryState triggered (delay: %f, queryLength: %ld)"
- "debouncedUpdateAccessoryState triggered (delay: instant, queryLength: %ld)"
- "didReceiveResponse"
- "didReceiveResponse empty results: short circuiting"
- "didReceiveResponse forced state or non results: short circuiting"
```
