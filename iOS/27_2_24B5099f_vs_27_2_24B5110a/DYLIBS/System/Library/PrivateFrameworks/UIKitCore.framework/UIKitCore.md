## UIKitCore

> `/System/Library/PrivateFrameworks/UIKitCore.framework/UIKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bdb010` | `0x1bdc124` | **`+0x1114`** |
| `__DATA.__bss` | `0x3eae0` | `0x3ebe8` | **`+0x108`** |
| `__DATA_CONST.__got` | `0x90b0` | `0x9140` | **`+0x90`** |
| `__DATA.__data` | `0x330d0` | `0x33150` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0xb3c80` | `0xb3ce0` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x5cb78` | `0x5cbc0` | **`+0x48`** |
| `__TEXT.__cstring` | `0x102736` | `0x1026f3` | **`-0x43`** |
| `__AUTH_CONST.__objc_const` | `0x27b390` | `0x27b350` | **`-0x40`** |
| `__TEXT.__eh_frame` | `0xb9ac` | `0xb974` | **`-0x38`** |
| `__TEXT.__unwind_info` | `0x72640` | `0x72678` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x26f4c` | `0x26f80` | **`+0x34`** |
| `__TEXT.__oslogstring` | `0x5676c` | `0x56795` | **`+0x29`** |
| `__DATA_DIRTY.__data` | `0xbc0a` | `0xbbea` | **`-0x20`** |
| `__TEXT.__const` | `0x4d878` | `0x4d898` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x17a7f` | `0x17a9f` | **`+0x20`** |
| `__AUTH.__data` | `0xaac8` | `0xaad8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x962f0` | `0x962e0` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x1a0da8` | `0x1a0db8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x17290` | `0x1729c` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x8678` | `0x8680` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x11d00` | `0x11cf8` | **`-0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x2f630` | `0x2f638` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0xa410` | `0xa408` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x192f4` | `0x192fa` | **`+0x6`** |
| `__DATA_DIRTY.__objc_ivar` | `0x8978` | `0x8974` | **`-0x4`** |

### Other Changes

```diff

-9127.1.12.1.101
+9127.1.13.1.106

-  Functions: 182086
-  Symbols:   229446
-  CStrings:  33935
+  Functions: 182113
+  Symbols:   229440
+  CStrings:  33937
Symbols:
+ +[UIViewController _wideHorizontalContentMarginForTraitCollection:]
+ -[UICollectionViewListCell _edgesAbuttingAccessories]
+ -[UIColor(Adaptive) _adaptive]
+ -[UIColor(Adaptive) _isAdaptive]
+ -[UIDynamicModifiedColor initWithBaseColor:alphaComponent:contrast:adaptive:]
+ -[UIDynamicModifiedColor initWithBaseColor:alphaComponent:contrast:prominence:adaptive:]
+ -[UIDynamicModifiedColor(Adaptive) _adaptive]
+ -[UIDynamicModifiedColor(Adaptive) _isAdaptive]
+ -[UIPopoverPresentationController _occludedFrameOfPresentedViewInContainerView]
+ -[UITextInputController _selectedRangeBoundedToTextStorage:]
+ -[UIView(UIDragging) _beginDragWithTouches:orInitialCentroid:accessibilityEndpoint:contextMenuConfiguration:]
+ GCC_except_table1151
+ GCC_except_table1156
+ GCC_except_table1223
+ GCC_except_table1404
+ GCC_except_table1438
+ GCC_except_table150
+ GCC_except_table191
+ GCC_except_table271
+ GCC_except_table276
+ GCC_except_table361
+ GCC_except_table401
+ GCC_except_table435
+ GCC_except_table473
+ GCC_except_table589
+ GCC_except_table661
+ GCC_except_table745
+ GCC_except_table770
+ GCC_except_table823
+ GCC_except_table830
+ GCC_except_table841
+ GCC_except_table861
+ GCC_except_table955
+ GCC_except_table960
+ _OBJC_IVAR_$_UIDynamicModifiedColor._isAdaptive
+ __OBJC_$_CLASS_METHODS_UIColor(_UIViewMaterial|Swift|UIAccessibility|UIAccessibilityPrivate|CandidateView|SwiftSupport|_UIDynamicColor|DynamicColors|_UIInterfaceAPI|_InProgressSPI|ProminenceSupport|Adaptive|UIKeyboardCandidateUIAdditions|UINSItemProvider|UIItemProviderReadingWriting|ForPencilKitOnly)
+ __OBJC_$_INSTANCE_METHODS_UIColor(_UIViewMaterial|Swift|UIAccessibility|UIAccessibilityPrivate|CandidateView|SwiftSupport|_UIDynamicColor|DynamicColors|_UIInterfaceAPI|_InProgressSPI|ProminenceSupport|Adaptive|UIKeyboardCandidateUIAdditions|UINSItemProvider|UIItemProviderReadingWriting|ForPencilKitOnly)
+ __OBJC_$_INSTANCE_METHODS_UIDynamicModifiedColor(ProminenceSupport|Adaptive)
+ __OBJC_CLASS_PROTOCOLS_$_UIColor(_UIViewMaterial|Swift|UIAccessibility|UIAccessibilityPrivate|CandidateView|SwiftSupport|_UIDynamicColor|DynamicColors|_UIInterfaceAPI|_InProgressSPI|ProminenceSupport|Adaptive|UIKeyboardCandidateUIAdditions|UINSItemProvider|UIItemProviderReadingWriting|ForPencilKitOnly)
+ ___113-[UIResponder(WritingToolsSupport) pushAutocorrectionListForNonMeaningFullText:pushTimeStamp:autocorrectionList:]_block_invoke_2
+ ___113-[UIResponder(WritingToolsSupport) pushAutocorrectionListForNonMeaningFullText:pushTimeStamp:autocorrectionList:]_block_invoke_3
+ ___113-[UIResponder(WritingToolsSupport) pushAutocorrectionListForNonMeaningFullText:pushTimeStamp:autocorrectionList:]_block_invoke_4
+ ___30-[UIColor(Adaptive) _adaptive]_block_invoke
+ ___65-[_UISplitViewControllerAdaptiveImpl _prepareTransitionToLayout:]_block_invoke_9
+ ___79-[UINavigationController _performCoordinatedUpdateTopFramesTransitionAnimation]_block_invoke_2
+ ____UIViewInferredContentMarginPropagationEnabled_block_invoke
+ ___block_descriptor_72_e8_32s40s48bs56r_e17_v16?0"NSArray"8ls32l8s48l8s40l8r56l8
+ ___swift_closure_destructor.367Tm
+ _pushAutocorrectionListForNonMeaningFullText:pushTimeStamp:autocorrectionList:.nonMeaningfulCharacters
+ _pushAutocorrectionListForNonMeaningFullText:pushTimeStamp:autocorrectionList:.onceToken
+ _symbolic So8UIScreenC3key______5valuet 21UIIntelligenceSupport19IntelligenceElementV
+ _symbolic _____Sg 21UIIntelligenceSupport19IntelligenceElementV23ContextMenuPresentationV
- -[UIDynamicModifiedColor initWithBaseColor:alphaComponent:contrast:]
- -[UIDynamicModifiedColor initWithBaseColor:alphaComponent:contrast:prominence:]
- -[UIResponder(WritingToolsSupport) _hasMeaningfulTextForWritingToolsWithCompletionHandler:]
- -[UIResponder(WritingToolsSupport) _shouldDisplayWriteWithSiriCandidateOptionsWithCompletionHandler:]
- -[UITextNonEditableInteraction toggleSelectionCommandsAtLocation:inCoordinateSpace:]
- -[UIViewController _childViewControllerForDirectTouchSystemGesturesDisabled]
- -[UIViewController _prefersDirectTouchSystemGesturesDisabled]
- -[_UICampoLightweightController originalUserInteractionEnabledForSourceView]
- -[_UICampoLightweightController setOriginalUserInteractionEnabledForSourceView:]
- -[_UITextInteractionEditMenuAssistant showSelectionCommandsAtLocation:inCoordinateSpace:]
- GCC_except_table1145
- GCC_except_table1152
- GCC_except_table1157
- GCC_except_table1224
- GCC_except_table1351
- GCC_except_table1405
- GCC_except_table1439
- GCC_except_table187
- GCC_except_table233
- GCC_except_table270
- GCC_except_table284
- GCC_except_table362
- GCC_except_table370
- GCC_except_table408
- GCC_except_table434
- GCC_except_table513
- GCC_except_table588
- GCC_except_table660
- GCC_except_table744
- GCC_except_table769
- GCC_except_table822
- GCC_except_table829
- GCC_except_table835
- GCC_except_table840
- GCC_except_table954
- GCC_except_table959
- _OBJC_IVAR_$_UIViewController.__prefersDirectTouchSystemGesturesDisabled
- _OBJC_IVAR_$__UICampoLightweightController._originalUserInteractionEnabledForSourceView
- _OBJC_IVAR_$__UITextInteractionEditMenuAssistant._contextMenuLocation
- _TIGetDontShowFullSizeWriteWithSiriButtonValue
- __OBJC_$_CLASS_METHODS_UIColor(_UIViewMaterial|Swift|UIAccessibility|UIAccessibilityPrivate|CandidateView|SwiftSupport|_UIDynamicColor|DynamicColors|_UIInterfaceAPI|_InProgressSPI|ProminenceSupport|UIKeyboardCandidateUIAdditions|UINSItemProvider|UIItemProviderReadingWriting|ForPencilKitOnly)
- __OBJC_$_INSTANCE_METHODS_UIColor(_UIViewMaterial|Swift|UIAccessibility|UIAccessibilityPrivate|CandidateView|SwiftSupport|_UIDynamicColor|DynamicColors|_UIInterfaceAPI|_InProgressSPI|ProminenceSupport|UIKeyboardCandidateUIAdditions|UINSItemProvider|UIItemProviderReadingWriting|ForPencilKitOnly)
- __OBJC_$_INSTANCE_METHODS_UIDynamicModifiedColor(ProminenceSupport)
- __OBJC_CLASS_PROTOCOLS_$_UIColor(_UIViewMaterial|Swift|UIAccessibility|UIAccessibilityPrivate|CandidateView|SwiftSupport|_UIDynamicColor|DynamicColors|_UIInterfaceAPI|_InProgressSPI|ProminenceSupport|UIKeyboardCandidateUIAdditions|UINSItemProvider|UIItemProviderReadingWriting|ForPencilKitOnly)
- ___101-[UIResponder(WritingToolsSupport) _shouldDisplayWriteWithSiriCandidateOptionsWithCompletionHandler:]_block_invoke
- ___54-[UINavigationController setViewControllers:animated:]_block_invoke_4
- ___57-[_UIKeyboardStateManager generateCandidatesWithOptions:]_block_invoke_3
- ___91-[UIResponder(WritingToolsSupport) _hasMeaningfulTextForWritingToolsWithCompletionHandler:]_block_invoke
- ___91-[UIResponder(WritingToolsSupport) _hasMeaningfulTextForWritingToolsWithCompletionHandler:]_block_invoke_2
- ___91-[UIResponder(WritingToolsSupport) _hasMeaningfulTextForWritingToolsWithCompletionHandler:]_block_invoke_3
- ___91-[UIResponder(WritingToolsSupport) _hasMeaningfulTextForWritingToolsWithCompletionHandler:]_block_invoke_4
- ___block_descriptor_72_e8_32s40s48bs56r_e8_v12?0B8ls32l8s48l8s40l8r56l8
- ___swift_closure_destructor.357Tm
- __hasMeaningfulTextForWritingToolsWithCompletionHandler:.nonMeaningfulCharacters
- __hasMeaningfulTextForWritingToolsWithCompletionHandler:.onceToken
- _setViewControllers:animated:.__s_category
- _symbolic _____XMT 12AnimationKit09InProcessA7ManagerC
- _symbolic _____z_Xx So16_UIUpdateRequestV
CStrings:
+ "%@ called on <%@ %p> while an existing transition or presentation is occurring; deferring the update until it completes."
+ "UIDynamicModifiedAdaptive"
+ "com.kylin.readnew"
+ "com.phoenix.video"
- "Touch-location heuristic matched element with customTypeNames=%s"
- "UISplitViewController internal inconsistency: unexpected attempt to complete transition which has already completed"
```
