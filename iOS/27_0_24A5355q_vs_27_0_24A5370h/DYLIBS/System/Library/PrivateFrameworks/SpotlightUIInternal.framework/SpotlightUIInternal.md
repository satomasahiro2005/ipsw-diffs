## SpotlightUIInternal

> `/System/Library/PrivateFrameworks/SpotlightUIInternal.framework/SpotlightUIInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x45f8c` | `0x46e00` | **`+0xe74`** |
| `__AUTH_CONST.__objc_const` | `0x8b28` | `0x8da0` | **`+0x278`** |
| `__TEXT.__objc_methlist` | `0x58b0` | `0x5a58` | **`+0x1a8`** |
| `__AUTH.__data` | `0x348` | `0x4b8` | **`+0x170`** |
| `__DATA_CONST.__objc_selrefs` | `0x3ff8` | `0x40b0` | **`+0xb8`** |
| `__AUTH.__objc_data` | `0xd88` | `0xe38` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0x5cc` | `0x670` | **`+0xa4`** |
| `__TEXT.__const` | `0xfb0` | `0x1008` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x2dc` | `0x330` | **`+0x54`** |
| `__TEXT.__oslogstring` | `0xd35` | `0xd85` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x13e0` | `0x1430` | **`+0x50`** |
| `__DATA.__data` | `0x16e0` | `0x1728` | **`+0x48`** |
| `__TEXT.__cstring` | `0x12bf` | `0x12ff` | **`+0x40`** |
| `__DATA_CONST.__const` | `0xb58` | `0xb78` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x1a8` | `0x1c0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xd30` | `0xd40` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x2bb` | `0x2cb` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x44` | `0x50` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x408` | `0x400` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x9f8` | `0xa00` | **`+0x8`** |
| `__DATA_CONST.__objc_nlclslist` | `0x8` | `—` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x1c0` | `0x1c8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xcc9` | `0xccc` | **`+0x3`** |

### Other Changes

```diff

-228.102.0.0.0
+235.3.100.0.0

-  Functions: 1863
-  Symbols:   3128
-  CStrings:  323
+  Functions: 1889
+  Symbols:   3157
+  CStrings:  327
Symbols:
+ +[SPUIFeedbackManager didAppearFromSource:withQueryId:queryString:deviceIsAuthenticated:isPresentedOverApp:isInImageContextMode:]
+ -[SPUIResultsViewController selectFirstResult]
+ -[SPUISearchHeader hasSelectedItem]
+ -[SPUISearchHeader selectFirstResultIfNecessary]
+ -[SPUISearchViewController didChangeSelectedItem:]
+ -[SPUISearchViewController didUpdateFromResultsInViewController:]
+ -[SPUISearchViewController executeSelectedItem]
+ -[SPUISearchViewController hasExplicitlyInvokedZKW]
+ -[SPUISearchViewController searchTextDidChange]
+ -[SPUISearchViewController selectFirstResultIfNecessary]
+ -[SPUISearchViewController setHasExplicitlyInvokedZKW:]
+ -[SPUITextView becomeFirstResponder]
+ -[SPUITextView canBecomeFocused]
+ -[SPUITextView canResignFirstResponder]
+ -[SPUITextView escapeKeyCommand]
+ -[SPUITextView focusGroupIdentifier]
+ -[SPUITextView preferredFocusEnvironments]
+ -[SPUITextView presses:containKeyCode:]
+ -[SPUITextView pressesBegan:withEvent:]
+ -[SPUIViewController didChangeSelectedItem:]
+ -[SPUIViewController didUpdateFromResultsInViewController:]
+ -[SPUIViewController selectionController]
+ -[SPUIViewController setSelectionController:]
+ GCC_except_table33
+ GCC_except_table83
+ _OBJC_CLASS_$_SFCardSection
+ _OBJC_CLASS_$_SFCommandEngagementFeedback
+ _OBJC_CLASS_$_SPUIExternalProviderFeedback
+ _OBJC_IVAR_$_SPUISearchViewController._hasExplicitlyInvokedZKW
+ _OBJC_IVAR_$_SPUIViewController.selectionController
+ _OBJC_METACLASS_$_SPUIExternalProviderFeedback
+ __CLASS_METHODS_SPUIExternalProviderFeedback
+ __DATA_SPUIExternalProviderFeedback
+ __DATA__TtC19SpotlightUIInternal14AnimationTrace
+ __DATA__TtC19SpotlightUIInternal21SpotlightBootstrapper
+ __INSTANCE_METHODS_SPUIExternalProviderFeedback
+ __IVARS__TtC19SpotlightUIInternal14AnimationTrace
+ __METACLASS_DATA_SPUIExternalProviderFeedback
+ __METACLASS_DATA__TtC19SpotlightUIInternal14AnimationTrace
+ __METACLASS_DATA__TtC19SpotlightUIInternal21SpotlightBootstrapper
+ __OBJC_$_PROP_LIST_SPUIResultsViewDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SearchUIFeedbackDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SearchUIFeedbackDelegate
+ __OBJC_$_PROTOCOL_REFS_SearchUIFeedbackDelegate
+ __OBJC_LABEL_PROTOCOL_$_SearchUIFeedbackDelegate
+ __OBJC_PROTOCOL_$_SearchUIFeedbackDelegate
+ ___129+[SPUIFeedbackManager didAppearFromSource:withQueryId:queryString:deviceIsAuthenticated:isPresentedOverApp:isInImageContextMode:]_block_invoke
+ ___129+[SPUIFeedbackManager didAppearFromSource:withQueryId:queryString:deviceIsAuthenticated:isPresentedOverApp:isInImageContextMode:]_block_invoke_2
+ ___39-[SPUITextView presses:containKeyCode:]_block_invoke
+ ___block_descriptor_40_e21_B24?0"UIPress"8^B16l
+ ___block_descriptor_67_e8_32s_e5_v8?0ls32l8
+ _didAppearFromSource:withQueryId:queryString:deviceIsAuthenticated:isPresentedOverApp:isInImageContextMode:.onceToken
+ _didAppearFromSource:withQueryId:queryString:deviceIsAuthenticated:isPresentedOverApp:isInImageContextMode:.queue
+ _symbolic _____ 19SpotlightUIInternal0A12BootstrapperC
+ _symbolic _____ 19SpotlightUIInternal14AnimationTraceC
+ _symbolic _____ 19SpotlightUIInternal30ExternalProviderFeedbackBridgeC
- +[SPUIFeedbackManager didAppearFromSource:withQueryId:queryString:deviceIsAuthenticated:isPresentedOverApp:]
- +[SUIAppIntentsPresentationProxy load]
- -[SPUIResultsViewController allowHighlightingWhenInactive]
- -[SPUIResultsViewController didChangeSelectedItem:]
- -[SPUIResultsViewController elevatedViewControllerActive]
- -[SPUIResultsViewController goTakeoverResult]
- -[SPUIResultsViewController performReturnKeyPressAction]
- -[SPUIResultsViewController selectionController]
- -[SPUIResultsViewController setAllowHighlightingWhenInactive:]
- -[SPUIResultsViewController setElevatedViewControllerActive:]
- -[SPUIResultsViewController setGoTakeoverResult:]
- -[SPUIResultsViewController setSelectionController:]
- -[SPUISearchViewController activeSelectionController]
- -[SPUISearchViewController resultsViewController:didChangeSelectedItem:]
- -[SPUIViewController resultsViewController:didChangeSelectedItem:]
- GCC_except_table32
- GCC_except_table79
- _OBJC_IVAR_$_SPUIResultsViewController._allowHighlightingWhenInactive
- _OBJC_IVAR_$_SPUIResultsViewController._elevatedViewControllerActive
- _OBJC_IVAR_$_SPUIResultsViewController._goTakeoverResult
- _OBJC_IVAR_$_SPUIResultsViewController._selectionController
- ___108+[SPUIFeedbackManager didAppearFromSource:withQueryId:queryString:deviceIsAuthenticated:isPresentedOverApp:]_block_invoke
- ___108+[SPUIFeedbackManager didAppearFromSource:withQueryId:queryString:deviceIsAuthenticated:isPresentedOverApp:]_block_invoke_2
- ___block_descriptor_66_e8_32s_e5_v8?0ls32l8
- _didAppearFromSource:withQueryId:queryString:deviceIsAuthenticated:isPresentedOverApp:.onceToken
- _didAppearFromSource:withQueryId:queryString:deviceIsAuthenticated:isPresentedOverApp:.queue
- _symbolic _____y______pG s23_ContiguousArrayStorageC s7CVarArgP
CStrings:
+ "!"
+ "B24@?0@\"UIPress\"8^B16"
+ "com.apple.askSiri"
+ "com.apple.otherProvider"
+ "debouncedUpdateAccessoryState triggered (delay: instant, queryLength: %ld)"
- "a"
```
