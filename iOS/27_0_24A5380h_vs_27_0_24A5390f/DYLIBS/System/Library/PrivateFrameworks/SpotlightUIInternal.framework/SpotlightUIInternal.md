## SpotlightUIInternal

> `/System/Library/PrivateFrameworks/SpotlightUIInternal.framework/SpotlightUIInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a2a0` | `0x4ea80` | **`+0x47e0`** |
| `__TEXT.__oslogstring` | `0xe95` | `0x12da` | **`+0x445`** |
| `__TEXT.__const` | `0x10a8` | `0x1398` | **`+0x2f0`** |
| `__AUTH_CONST.__objc_const` | `0x8f48` | `0x91f0` | **`+0x2a8`** |
| `__DATA.__bss` | `0x950` | `0xbf8` | **`+0x2a8`** |
| `__AUTH_CONST.__const` | `0xa78` | `0xca8` | **`+0x230`** |
| `__TEXT.__objc_methlist` | `0x5b38` | `0x5d00` | **`+0x1c8`** |
| `__DATA_CONST.__objc_selrefs` | `0x41a0` | `0x42d8` | **`+0x138`** |
| `__AUTH.__objc_data` | `0xa80` | `0xb98` | **`+0x118`** |
| `__TEXT.__cstring` | `0x130f` | `0x1218` | **`-0xf7`** |
| `__TEXT.__unwind_info` | `0x14d8` | `0x15b8` | **`+0xe0`** |
| `__TEXT.__swift5_typeref` | `0xd6a` | `0xe00` | **`+0x96`** |
| `__DATA_DIRTY.__objc_data` | `0xa48` | `0xac8` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x1ec` | `0x26c` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0xd58` | `0xda0` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x358` | `0x3a0` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x15e0` | `0x15a0` | **`-0x40`** |
| `__DATA.__data` | `0x16f8` | `0x1738` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0xbb4` | `0xbf0` | **`+0x3c`** |
| `__AUTH.__data` | `0x408` | `0x3d0` | **`-0x38`** |
| `__TEXT.__swift5_assocty` | `0xf0` | `0x128` | **`+0x38`** |
| `__DATA_CONST.__got` | `0xa58` | `0xa88` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x2fb` | `0x326` | **`+0x2b`** |
| `__TEXT.__gcc_except_tab` | `0x29c` | `0x27c` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x4c` | `0x60` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0x410` | `0x420` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1c8` | `0x1d8` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x1d0` | `0x1e0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x54` | `0x60` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x28` | `0x34` | **`+0xc`** |
| `__DATA_CONST.__const` | `0xb78` | `0xb70` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x67c` | `0x684` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x7c` | `0x84` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x3c` | `0x44` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x4` | `—` | **`-0x4`** |

### Other Changes

```diff

-236.0.4.100.0
+236.0.11.100.0

-  - /System/Library/PrivateFrameworks/IconServices.framework/IconServices

-  Functions: 1938
-  Symbols:   3205
-  CStrings:  332
+  Functions: 2038
+  Symbols:   3251
+  CStrings:  337
Symbols:
+ -[SPUIResultsViewController flushPendingSectionsUpdate]
+ -[SPUISearchStateRestorationContext displayState]
+ -[SPUISearchStateRestorationContext setDisplayState:]
+ -[SPUISearchViewController _expectedState]
+ -[SPUISearchViewController askSiriEnterTimer]
+ -[SPUISearchViewController cardLoader]
+ -[SPUISearchViewController checkAndExecutePendingEnter]
+ -[SPUISearchViewController fireAskSiriEnter]
+ -[SPUISearchViewController firePendingEnter]
+ -[SPUISearchViewController invalidateAskSiriEnterTimer]
+ -[SPUISearchViewController isAccessoryStateShowMore]
+ -[SPUISearchViewController pendingEnterIsReady]
+ -[SPUISearchViewController pendingEnterQueryId]
+ -[SPUISearchViewController scheduleAskSiriEnter]
+ -[SPUISearchViewController selectFirstResultAndEnter]
+ -[SPUISearchViewController sendFeedbackForShowMoreButtonPress]
+ -[SPUISearchViewController setAskSiriEnterTimer:]
+ -[SPUISearchViewController setPendingEnterQueryId:]
+ -[SPUISearchViewController setShouldRestore:]
+ -[SPUISearchViewController shouldRestore]
+ -[SPUITextView spui_applyDynamicTypeFont]
+ -[SPUIViewController isAccessoryStateShowMore]
+ GCC_except_table89
+ _OBJC_CLASS_$_NSMutableOrderedSet
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _OBJC_CLASS_$_SFAppIconImage
+ _OBJC_CLASS_$_SFButtonItem
+ _OBJC_CLASS_$_SFCommand
+ _OBJC_CLASS_$_SFDefaultPunchoutAppIconImage
+ _OBJC_CLASS_$_SFImage
+ _OBJC_CLASS_$_SFVisibleResultsFeedback
+ _OBJC_CLASS_$_SPUIFeedbackUtilities
+ _OBJC_CLASS_$_SPUISDefaultsManager
+ _OBJC_CLASS_$_SPUISearchResultUtilities
+ _OBJC_CLASS_$_SPUISearchStateRestorationStore
+ _OBJC_CLASS_$_SUISCardLoader
+ _OBJC_CLASS_$_UIFontMetrics
+ _OBJC_IVAR_$_SPUISearchStateRestorationContext._displayState
+ _OBJC_IVAR_$_SPUISearchViewController._askSiriEnterTimer
+ _OBJC_IVAR_$_SPUISearchViewController._pendingEnterQueryId
+ _OBJC_IVAR_$_SPUISearchViewController._shouldRestore
+ _OBJC_METACLASS_$_SPUIFeedbackUtilities
+ _OBJC_METACLASS_$_SPUISearchResultUtilities
+ _OBJC_METACLASS_$_SPUISearchStateRestorationStore
+ _OUTLINED_FUNCTION_2
+ __CLASS_METHODS_SPUISearchStateRestorationStore
+ __DATA_SPUIFeedbackUtilities
+ __DATA_SPUISearchResultUtilities
+ __DATA_SPUISearchStateRestorationStore
+ __INSTANCE_METHODS_SPUIFeedbackUtilities
+ __INSTANCE_METHODS_SPUISearchResultUtilities
+ __INSTANCE_METHODS_SPUISearchStateRestorationStore
+ __METACLASS_DATA_SPUIFeedbackUtilities
+ __METACLASS_DATA_SPUISearchResultUtilities
+ __METACLASS_DATA_SPUISearchStateRestorationStore
+ __OBJC_$_CLASS_METHODS_SPUIFeedbackUtilities(SpotlightUIInternal)
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SUISAccessoryFeedbackDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SUISAccessoryFeedbackDelegate
+ __OBJC_LABEL_PROTOCOL_$_SUISAccessoryFeedbackDelegate
+ __OBJC_PROTOCOL_$_SUISAccessoryFeedbackDelegate
+ __PROTOCOL_INSTANCE_METHODS_SUISAccessoryFeedbackDelegate
+ __PROTOCOL_METHOD_TYPES_SUISAccessoryFeedbackDelegate
+ __PROTOCOL_SUISAccessoryFeedbackDelegate
+ ___44-[SPUISearchViewController firePendingEnter]_block_invoke
+ ___55-[SPUISearchViewController checkAndExecutePendingEnter]_block_invoke
+ ___70-[SPUISearchViewController searchViewWillPresentFromSource:isOverApp:]_block_invoke_3
+ ___swift_memcpy0_1
+ ___swift_memcpy8_8
+ __swift_stdlib_bridgeErrorToNSError
+ _associated conformance 19SpotlightUIInternal16RestorationError33_B018F2EC028DD32252FF451CA8A49BDBLLOSHAASQ
+ _associated conformance 19SpotlightUIInternal23SearchUIImageViewBridge33_2102EC304E763A420A65D2540E713AF9LLV7SwiftUI0E0AA4BodyAeFP_AeF
+ _associated conformance 19SpotlightUIInternal23SearchUIImageViewBridge33_2102EC304E763A420A65D2540E713AF9LLV7SwiftUI19UIViewRepresentableAaE0E0
+ _flat unique So29SUISAccessoryFeedbackDelegate_p
+ _get_witness_table 7SwiftUI15ModifiedContentVy19SpotlightUIInternal23SearchUIImageViewBridge33_2102EC304E763A420A65D2540E713AF9LLVAA12_FrameLayoutVGAA0I0HPAgaKHPyHC_AiA0I8ModifierHPyHCHC
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA6ZStackVyAA7ForEachVys18ReversedCollectionVySaySi6offset_So7SFImageC7elementtGGSiACyACy19SpotlightUIInternal12AppIconImage33_2102EC304E763A420A65D2540E713AF9LLVAA14_PaddingLayoutVGAA21_TraitWritingModifierVyAA14ZIndexTraitKeyVGGGGAA06_FrameZ0VGAA4ViewHPA2_AAA6_HPyHC_A4_AA12ViewModifierHPyHCHC
+ _objc_retain_x28
+ _swift_errorRetain
+ _swift_isEscapingClosureAtFileLocation
+ _swift_release_x25
+ _symbolic $s19SpotlightUIInternal25AccessoryFeedbackDelegateP
+ _symbolic $s7SwiftUI19UIViewRepresentableP
+ _symbolic Ig_
+ _symbolic SaySi6offset_So7SFImageC7elementtG
+ _symbolic SaySo15SFResultSectionCG
+ _symbolic SaySo15SFResultSectionCGSg
+ _symbolic SaySo7SFImageCG
+ _symbolic SaySo7SFImageCG6images_SaySSG17bundleIdentifierst
+ _symbolic SaySo7SFImageCG6images_SaySSG17bundleIdentifierstIeAgHr_
+ _symbolic SaySo7SFImageCGSg
+ _symbolic Say_____G 8Dispatch0A13WorkItemFlagsV
+ _symbolic Say_____G So17OS_dispatch_queueC8DispatchE10AttributesV
+ _symbolic Si6offset_So7SFImageC7elementt
+ _symbolic SiSo7SFImageC_____yACy__________G_____y_____GGIegygr_ 7SwiftUI15ModifiedContentV 19SpotlightUIInternal12AppIconImage33_2102EC304E763A420A65D2540E713AF9LLV AA14_PaddingLayoutV AA21_TraitWritingModifierV AA06ZIndexS3KeyV
+ _symbolic So17SearchUIImageViewC
+ _symbolic So31SPUISearchStateRestorationStoreCXMT
+ _symbolic So7SFImageC
+ _symbolic _____ 10Foundation3URLV
+ _symbolic _____ 10Foundation4DataV
+ _symbolic _____ 19SpotlightUIInternal16RestorationError33_B018F2EC028DD32252FF451CA8A49BDBLLO
+ _symbolic _____ 19SpotlightUIInternal17FeedbackUtilitiesC
+ _symbolic _____ 19SpotlightUIInternal21SearchResultUtilitiesC
+ _symbolic _____ 19SpotlightUIInternal23SearchUIImageViewBridge33_2102EC304E763A420A65D2540E713AF9LLV
+ _symbolic _____ s5NeverO
+ _symbolic _____Sg 10Foundation4DataV
+ _symbolic _____Sg 17SpotlightUIShared12DisplayStateO
+ _symbolic _____SgXw 19SpotlightUIInternal21AccessoryStateManagerC
+ _symbolic _____SgXwz_Xx 19SpotlightUIInternal21AccessoryStateManagerC
+ _symbolic _____XMT 19SpotlightUIInternal21SearchResultUtilitiesC
+ _symbolic ______pSgXw 19SpotlightUIInternal25AccessoryFeedbackDelegateP
+ _symbolic _____ySSG s11_SetStorageC
+ _symbolic _____ySaySi6offset_So7SFImageC7elementtGG s18ReversedCollectionV
+ _symbolic _____ySi6offset_So7SFImageC7elementtG s23_ContiguousArrayStorageC
+ _symbolic _____y__________G 7SwiftUI15ModifiedContentV 19SpotlightUIInternal23SearchUIImageViewBridge33_2102EC304E763A420A65D2540E713AF9LLV AA12_FrameLayoutV
+ _symbolic _____y___________y_____ySaySi6offset_So7SFImageC7elementtGGSi_____yAKy__________G_____y_____GGGG 7SwiftUI13_VariadicViewO4TreeV AA13_ZStackLayoutV AA7ForEachV s18ReversedCollectionV AA15ModifiedContentV 19SpotlightUIInternal12AppIconImage33_2102EC304E763A420A65D2540E713AF9LLV AA08_PaddingG0V AA21_TraitWritingModifierV AA14ZIndexTraitKeyV
+ _symbolic _____y_____y_____ySaySi6offset_So7SFImageC7elementtGGSi_____yAJy__________G_____y_____GGGG 7SwiftUI6ZStackV AA7ForEachV s18ReversedCollectionV AA15ModifiedContentV 19SpotlightUIInternal12AppIconImage33_2102EC304E763A420A65D2540E713AF9LLV AA14_PaddingLayoutV AA21_TraitWritingModifierV AA06ZIndexX3KeyV
+ _symbolic _____y_____y_____y_____ySaySi6offset_So7SFImageC7elementtGGSiAAyAAy__________G_____y_____GGGG_____G 7SwiftUI15ModifiedContentV AA6ZStackV AA7ForEachV s18ReversedCollectionV 19SpotlightUIInternal12AppIconImage33_2102EC304E763A420A65D2540E713AF9LLV AA14_PaddingLayoutV AA21_TraitWritingModifierV AA06ZIndexX3KeyV AA06_FrameW0V
+ _symbolic _____z_Xx 19SpotlightUIInternal14AccessoryStateO
+ _symbolic yt
+ _type_layout_string 19SpotlightUIInternal12AppIconImage33_2102EC304E763A420A65D2540E713AF9LLV
+ _type_layout_string 19SpotlightUIInternal15StackedAppIcons33_2102EC304E763A420A65D2540E713AF9LLV
- +[SPUISearchViewWindowSceneDelegate restorationDataQueue]
- +[SPUISearchViewWindowSceneDelegate restorationData]
- +[SPUISearchViewWindowSceneDelegate restorationUrl]
- +[SPUISearchViewWindowSceneDelegate saveRestorationData:]
- GCC_except_table4
- GCC_except_table83
- _OBJC_CLASS_$_ISIcon
- _OBJC_CLASS_$_ISImageDescriptor
- _OBJC_CLASS_$_NSURL
- _OBJC_CLASS_$_SPUIExternalProviderFeedback
- _OBJC_METACLASS_$_SPUIExternalProviderFeedback
- __CLASS_METHODS_SPUIExternalProviderFeedback
- __DATA_SPUIExternalProviderFeedback
- __INSTANCE_METHODS_SPUIExternalProviderFeedback
- __METACLASS_DATA_SPUIExternalProviderFeedback
- __MergedGlobals
- ___44-[SPUISearchViewController returnKeyPressed]_block_invoke
- ___52+[SPUISearchViewWindowSceneDelegate restorationData]_block_invoke
- ___57+[SPUISearchViewWindowSceneDelegate restorationDataQueue]_block_invoke
- ___57+[SPUISearchViewWindowSceneDelegate saveRestorationData:]_block_invoke
- ___block_descriptor_48_e8_32r_e5_v8?0lr32l8
- ___isPlatformVersionAtLeast
- __availability_version_check
- __initializeAvailabilityCheck
- _compatibilityInitializeAvailabilityCheck
- _dispatch_once_f
- _fclose
- _fopen
- _fread
- _fseek
- _ftell
- _get_underlying_type_ref 7SwiftUI4ViewPAAEAcAE4task2id4name8priority4file4line_Qrqd___SSSgScPSSSiyyYaYAcntSQRd__lFQOQr
- _get_underlying_witness 7SwiftUI4ViewPAAEAcAE4task2id4name8priority4file4line_Qrqd___SSSgScPSSSiyyYaYAcntSQRd__lFQOqd0__AaBHC
- _get_witness_table 7SwiftUI15ModifiedContentVyAA6ZStackVyAA7ForEachVySaySi6offset_SS7elementtGSSACyACy19SpotlightUIInternal12AppIconImage33_2102EC304E763A420A65D2540E713AF9LLVAA14_PaddingLayoutVGAA21_TraitWritingModifierVyAA06ZIndexX3KeyVGGGGAA06_FrameW0VGAA4ViewHPAyAA1_HPyHC_A_AA04ViewZ0HPyHCHC
- _get_witness_table qd0__7SwiftUI4ViewHD3_AaBPAAE4task2id4name8priority4file4line_Qrqd___SSSgScPSSSiyyYaYAcntSQRd__lFQOyAA15ModifiedContentVyAA5GroupVyAA012_ConditionalK0VyALyAA5ImageVAA21_TraitWritingModifierVyAA010TransitionO3KeyVGGAA5ColorVGGAA12_FrameLayoutVG_SSQo_HO
- _initializeAvailabilityCheck
- _malloc
- _restorationDataQueue.onceToken
- _restorationDataQueue.queue
- _rewind
- _sscanf
- _swift_continuation_resume
- _swift_getAtKeyPath
- _swift_release_x26
- _swift_retain_x28
- _symbolic $s19SpotlightUIInternal36ShowMoreButtonViewControllerDelegateP
- _symbolic SaySi6offset_SS7elementtG
- _symbolic SccySo7IFImageCSg_____G s5NeverO
- _symbolic Si6offset_SS7elementt
- _symbolic SiSS_____yAAy__________G_____y_____GGIegygr_ 7SwiftUI15ModifiedContentV 19SpotlightUIInternal12AppIconImage33_2102EC304E763A420A65D2540E713AF9LLV AA14_PaddingLayoutV AA21_TraitWritingModifierV AA06ZIndexS3KeyV
- _symbolic _____ 12CoreGraphics7CGFloatV
- _symbolic _____ 19SpotlightUIInternal30ExternalProviderFeedbackBridgeC
- _symbolic _____Sg 7SwiftUI5ImageV
- _symbolic _____SgXw 19SpotlightUIInternal28ShowMoreButtonViewControllerC
- _symbolic ______pSgXw 19SpotlightUIInternal36ShowMoreButtonViewControllerDelegateP
- _symbolic _____yAAy_____y_____yAAy__________y_____GG_____GG_____G_____ySSGG 7SwiftUI15ModifiedContentV AA5GroupV AA012_ConditionalD0V AA5ImageV AA21_TraitWritingModifierV AA010TransitionH3KeyV AA5ColorV AA12_FrameLayoutV AA19_TaskValueModifier2V
- _symbolic _____ySSG 7SwiftUI19_TaskValueModifier2V
- _symbolic _____ySi6offset_SS7elementtG s23_ContiguousArrayStorageC
- _symbolic _____y_____G 7SwiftUI11EnvironmentV 12CoreGraphics7CGFloatV
- _symbolic _____y_____G 7SwiftUI21_TraitWritingModifierV AA010TransitionC3KeyV
- _symbolic _____y_____SgG 7SwiftUI9LazyStateV AA5ImageV
- _symbolic _____y_____Sg_G 7SwiftUI9LazyStateV7StorageO AA5ImageV
- _symbolic _____y_____Sg_G_yXlSgt 7SwiftUI9LazyStateV7StorageO AA5ImageV
- _symbolic _____y__________G 7SwiftUI15ModifiedContentV 19SpotlightUIInternal12AppIconImage33_2102EC304E763A420A65D2540E713AF9LLV AA14_PaddingLayoutV
- _symbolic _____y___________ySaySi6offset_SS7elementtGSS_____yAGy__________G_____y_____GGGG 7SwiftUI13_VariadicViewO4TreeV AA13_ZStackLayoutV AA7ForEachV AA15ModifiedContentV 19SpotlightUIInternal12AppIconImage33_2102EC304E763A420A65D2540E713AF9LLV AA08_PaddingG0V AA21_TraitWritingModifierV AA06ZIndexY3KeyV
- _symbolic _____y__________y_____GG 7SwiftUI15ModifiedContentV AA5ImageV AA21_TraitWritingModifierV AA010TransitionF3KeyV
- _symbolic _____y_____ySaySi6offset_SS7elementtGSS_____yAFy__________G_____y_____GGGG 7SwiftUI6ZStackV AA7ForEachV AA15ModifiedContentV 19SpotlightUIInternal12AppIconImage33_2102EC304E763A420A65D2540E713AF9LLV AA14_PaddingLayoutV AA21_TraitWritingModifierV AA06ZIndexV3KeyV
- _symbolic _____y_____y__________y_____GG_____G 7SwiftUI19_ConditionalContentV AA08ModifiedD0V AA5ImageV AA21_TraitWritingModifierV AA010TransitionG3KeyV AA5ColorV
- _symbolic _____y_____y_____yAAy__________y_____GG_____GG_____G 7SwiftUI15ModifiedContentV AA5GroupV AA012_ConditionalD0V AA5ImageV AA21_TraitWritingModifierV AA010TransitionH3KeyV AA5ColorV AA12_FrameLayoutV
- _symbolic _____y_____y_____ySaySi6offset_SS7elementtGSSAAyAAy__________G_____y_____GGGG_____G 7SwiftUI15ModifiedContentV AA6ZStackV AA7ForEachV 19SpotlightUIInternal12AppIconImage33_2102EC304E763A420A65D2540E713AF9LLV AA14_PaddingLayoutV AA21_TraitWritingModifierV AA06ZIndexV3KeyV AA06_FrameU0V
- _symbolic _____y_____y_____y__________y_____GG_____GG 7SwiftUI5GroupV AA19_ConditionalContentV AA08ModifiedE0V AA5ImageV AA21_TraitWritingModifierV AA010TransitionH3KeyV AA5ColorV
- _symbolic _____y_____y_____y_____yAAy__________y_____GG_____GG_____G_SSQo_ 7SwiftUI4ViewPAAE4task2id4name8priority4file4line_Qrqd___SSSgScPSSSiyyYaYAcntSQRd__lFQO AA15ModifiedContentV AA5GroupV AA012_ConditionalK0V AA5ImageV AA21_TraitWritingModifierV AA010TransitionO3KeyV AA5ColorV AA12_FrameLayoutV
- _symbolic qd0__
- _symbolic qd__
CStrings:
+ "%s newstate: %s resultImagesChange: %{bool}d imageCount: %ld bundleIdentifiers: %s"
+ "/Saved Application State/"
+ "DisplayPolicy signals: query=%{sensitive}@ qid=%lu len=%ld elevatable=%d isSiriWorthy=%d firstBundle=%{sensitive}@ firstResultBundle=%{sensitive}@ firstResultCount=%lu hasTopHits=%d hasTopHitResult=%d complete=%d sectionCount=%lu"
+ "StateRestoration"
+ "[FTE] ZKW footer path (legacy): incrementing view count"
+ "[FTE] activateFirstTimeExperienceViewIfNecessary: needsDisplay=YES useZKWFTE=%d hasContentInSearchField=%d"
+ "[FTE] allowInternet=%d"
+ "[FTE] dismissForever (campo): setting newFTECount = 1"
+ "[FTE] dismissForever (legacy): setting viewCount = %lu"
+ "[FTE] incrementViewCount (campo): newFTECount %ld -> %ld"
+ "[FTE] incrementViewCount (legacy): viewCount %ld -> %ld"
+ "[FTE] needsDisplay=%d (campoEnabled=%d viewCount=%ld newFTECount=%ld maxCount=%lu)"
+ "[FTE] presented-VC path (campo or iPad): presenting FTE view controller"
+ "[enter] askSiri debounce fired -> perform"
+ "[enter] askSiri tier -> schedule debounce (%.0fms)"
+ "[enter] checkPending qid=%lu pendingId=%lu tier=%ld topHitIsIn=%d ready=%d"
+ "[enter] perform -> askSiri (tier=%ld)"
+ "[enter] perform -> firstResult (tier=%ld)"
+ "[enter] perform -> selectedItem"
+ "com.apple.collapsedShowMore"
+ "com.apple.spotlight.ui"
+ "displayPolicyDidTransitionToState: transitioning to AskSiri, suppressing Ask Siri completion (device locked, assistant disabled while locked)"
+ "displayState"
+ "failed to read restoration data with error %@"
+ "failed to save restoration data with error %@"
+ "restoration: post-present navMode=%ld navContentHeight=%f vcContentHeight=%f displayState=%ld"
+ "sendResultsExpandedFeedback: resultCount=%ld queryId=%llu"
+ "sendSiriClassificationFeedbackIfNeeded: state=%s queryId=%llu"
+ "show_more"
- "%@/%@/%@.%@"
- "%d.%d.%d"
- "%s newstate: %s bundleIdentifiersChange: %{bool}d newBundleIdentifiers: %{sensitive}s"
- "/System/Library/CoreServices/SystemVersion.plist"
- "Accessing Environment<%s>'s value outside of being installed on a View. This will always read the default value and will not update."
- "CFDataCreateWithBytesNoCopy"
- "CFDictionaryGetValue"
- "CFGetTypeID"
- "CFPropertyListCreateFromXMLData"
- "CFPropertyListCreateWithData"
- "CFRelease"
- "CFStringCreateWithCStringNoCopy"
- "CFStringGetCString"
- "CFStringGetTypeID"
- "DisplayPolicy signals: query=%{public}@ qid=%lu len=%ld elevatable=%d isSiriWorthy=%d firstBundle=%{public}@ firstResultBundle=%{public}@ firstResultCount=%lu hasTopHits=%d hasTopHitResult=%d complete=%d sectionCount=%lu"
- "ProductVersion"
- "Saved Application State"
- "View.task @ SpotlightUIInternal/ShowMoreButtonView.swift:"
- "com.apple.Spotlight"
- "failed to decompress data with error %@"
- "failed to get restoration data with error %@"
- "kCFAllocatorNull"
- "r"
- "savedState"
```
