## UIKitCore

> `/System/Library/PrivateFrameworks/UIKitCore.framework/UIKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bf0814` | `0x1bf24d4` | **`+0x1cc0`** |
| `__AUTH.__objc_data` | `0x56e40` | `0x558a8` | **`-0x1598`** |
| `__DATA_DIRTY.__objc_data` | `0x2e420` | `0x2f688` | **`+0x1268`** |
| `__DATA_DIRTY.__bss` | `0x15c58` | `0x16678` | **`+0xa20`** |
| `__DATA.__bss` | `0x3f5c8` | `0x3ec80` | **`-0x948`** |
| `__AUTH_CONST.__objc_const` | `0x27b4f8` | `0x27b0e0` | **`-0x418`** |
| `__TEXT.__oslogstring` | `0x559a1` | `0x55ca4` | **`+0x303`** |
| `__TEXT.__cstring` | `0x10209e` | `0x10236b` | **`+0x2cd`** |
| `__DATA_DIRTY.__data` | `0xba5a` | `0xbc6a` | **`+0x210`** |
| `__TEXT.__constg_swiftt` | `0x1dbf8` | `0x1da4c` | **`-0x1ac`** |
| `__DATA_DIRTY.__objc_ivar` | `0x87dc` | `0x895c` | **`+0x180`** |
| `__TEXT.__objc_methlist` | `0x1a0c30` | `0x1a0ab0` | **`-0x180`** |
| `__DATA.__objc_ivar` | `0x11e1c` | `0x11ca0` | **`-0x17c`** |
| `__TEXT.__gcc_except_tab` | `0x26d8c` | `0x26ee4` | **`+0x158`** |
| `__AUTH_CONST.__const` | `0x5dd20` | `0x5de40` | **`+0x120`** |
| `__AUTH.__data` | `0xacd8` | `0xabd8` | **`-0x100`** |
| `__DATA.__data` | `0x33130` | `0x33070` | **`-0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x96230` | `0x96170` | **`-0xc0`** |
| `__TEXT.__const` | `0x4da38` | `0x4dac8` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0xbaf0` | `0xbb48` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x72830` | `0x72888` | **`+0x58`** |
| `__AUTH_CONST.__cfstring` | `0xb3ae0` | `0xb3aa0` | **`-0x40`** |
| `__TEXT.__swift5_typeref` | `0x19238` | `0x1926a` | **`+0x32`** |
| `__DATA_CONST.__const` | `0x3ecc8` | `0x3ecf8` | **`+0x30`** |
| `__DATA_DIRTY.__common` | `0x650` | `0x680` | **`+0x30`** |
| `__DATA.__common` | `0x3958` | `0x3938` | **`-0x20`** |
| `__TEXT.__swift5_assocty` | `0x4f70` | `0x4f58` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x90a0` | `0x9090` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xb428` | `0xb418` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x174a0` | `0x174b0` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x17b5f` | `0x17b4f` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x8740` | `0x8748` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0xdd0` | `0xdd8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x25d0` | `0x25d4` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x1c3c` | `0x1c40` | **`+0x4`** |

### Other Changes

```diff

-9127.1.6.1.103
+9127.1.7.1.0

-  Functions: 182355
-  Symbols:   229344
-  CStrings:  33863
+  Functions: 182347
+  Symbols:   229340
+  CStrings:  33882
Symbols:
+ +[UITextInteractionAssistant(UITextInteractionAssistant_Internal) _isCampoLightweightUIAvailable]
+ -[UIDictationController restoreInputViewsAndTearDownPrivacyDataSharingSheetWindowIfNeeded]
+ -[UINavigationController _separateViewController:forSplitViewController:]
+ -[UIPageControl _overrideMinimumPressDurationForContinuousInteraction]
+ -[UIPageControl _setOverrideMinimumPressDurationForContinuousInteraction:]
+ -[UIStatusBarManager _updateStyleForWindow:animationParameters:shouldAnimate:shouldFence:]
+ -[UITextSelectionDisplayInteraction _writingToolsBehavior]
+ -[UIView _contentMarginsDidChange]
+ -[_UIPlaceholderWindowScene(RenderingEnvironment) _renderingEnvironment]
+ -[_UIPlaceholderWindowScene(SystemShellHostingEnvironment) _systemShellHostingEnvironment]
+ -[_UITabBarControllerVisualStyle additionalContentMargins]
+ GCC_except_table1052
+ GCC_except_table1055
+ GCC_except_table1062
+ GCC_except_table1210
+ GCC_except_table1288
+ GCC_except_table1344
+ GCC_except_table1346
+ GCC_except_table1495
+ GCC_except_table1502
+ GCC_except_table1504
+ GCC_except_table282
+ GCC_except_table325
+ GCC_except_table326
+ GCC_except_table363
+ GCC_except_table364
+ GCC_except_table390
+ GCC_except_table413
+ GCC_except_table443
+ GCC_except_table481
+ GCC_except_table482
+ GCC_except_table487
+ GCC_except_table514
+ GCC_except_table529
+ GCC_except_table561
+ GCC_except_table571
+ GCC_except_table602
+ GCC_except_table624
+ GCC_except_table625
+ GCC_except_table741
+ GCC_except_table806
+ GCC_except_table819
+ GCC_except_table826
+ GCC_except_table832
+ GCC_except_table921
+ GCC_except_table924
+ GCC_except_table930
+ GCC_except_table965
+ __OBJC_$_INSTANCE_METHODS__UIPlaceholderWindowScene(SystemShellHostingEnvironment|RenderingEnvironment)
+ __OBJC_PROTOCOL_REFERENCE_$_UIPopoverPresentationControllerSourceItem
+ __UIAsymmetricLayoutMarginsEnabled
+ __UIDictationEnablementLog
+ __UIDictationEnablementLog.log
+ __UIDictationEnablementLog.onceToken
+ __UIEdgeInsetsFlippedHorizontally
+ __UIRectEdgeFlippedHorizontally
+ __UIStatusBarEffectivePartStyle
+ ____UIAsymmetricLayoutMarginsEnabled_block_invoke
+ ____UIDictationEnablementLog_block_invoke
+ ___block_descriptor_72_e8_32s40s48bs56r_e24_v16?0?<"NSNumber"?>8ls32l8r56l8s40l8s48l8
+ ___swift_memcpy296_8
+ ___swift_memcpy297_8
+ ___swift_memcpy345_8
+ ___swift_memcpy409_8
+ ___swift_memcpy424_8
+ ___swift_memcpy473_8
+ ___unnamed_176
+ _symbolic So36_UITabBarControllerVisualStyle_PhoneC
+ _symbolic So36_UITabBarControllerVisualStyle_PhoneCSgXw
+ _symbolic _____ 5UIKit21_UIToolbarPaddingSpecV
+ _symbolic _____ 5UIKit27UIHostingViewInsetsProviderV
+ _symbolic _____ 5UIKit32UITraitGlassContainerMorphTargetV
+ _symbolic ______p 7SwiftUI22RootViewInsetsProviderP
+ _symbolic _____ySo6UIViewCG 5UIKit22_UIObjCIdentityWeakBoxC
+ _symbolic _____ySo6UIViewCGSg 5UIKit22_UIObjCIdentityWeakBoxC
+ _type_layout_string 5UIKit21_UIToolbarPaddingSpecV
+ _type_layout_string 5UIKit27UIHostingViewInsetsProviderV
- +[_UITraitHiddenViewsContributeToPocket _isPrivate]
- +[_UITraitHiddenViewsContributeToPocket affectsColorAppearance]
- +[_UITraitHiddenViewsContributeToPocket defaultValueRepresentsUnspecified]
- +[_UITraitHiddenViewsContributeToPocket defaultValue]
- +[_UITraitHiddenViewsContributeToPocket identifier]
- +[_UITraitHiddenViewsContributeToPocket name]
- -[UIDictationController tearDownPrivacyAndDataSharingSheetPresenterWindowAfterRemoteDictationEnablement]
- -[UIDictationController tearDownPrivacyAndDataSharingSheetPresenterWindowAfterTextResponderReloads]
- -[UIStatusBarManager _updateStyleForWindow:animationParameters:]
- GCC_except_table1051
- GCC_except_table1054
- GCC_except_table1061
- GCC_except_table1209
- GCC_except_table1287
- GCC_except_table1343
- GCC_except_table1345
- GCC_except_table1494
- GCC_except_table1501
- GCC_except_table1503
- GCC_except_table265
- GCC_except_table270
- GCC_except_table321
- GCC_except_table330
- GCC_except_table359
- GCC_except_table366
- GCC_except_table367
- GCC_except_table392
- GCC_except_table415
- GCC_except_table419
- GCC_except_table445
- GCC_except_table489
- GCC_except_table516
- GCC_except_table531
- GCC_except_table567
- GCC_except_table568
- GCC_except_table573
- GCC_except_table604
- GCC_except_table626
- GCC_except_table629
- GCC_except_table740
- GCC_except_table805
- GCC_except_table818
- GCC_except_table825
- GCC_except_table831
- GCC_except_table920
- GCC_except_table923
- GCC_except_table929
- GCC_except_table964
- _OBJC_CLASS_$__TtC5UIKit21_UIToolbarPaddingSpec
- _OBJC_CLASS_$__UITraitHiddenViewsContributeToPocket
- _OBJC_METACLASS_$__TtC5UIKit21_UIToolbarPaddingSpec
- _OBJC_METACLASS_$__UITraitHiddenViewsContributeToPocket
- __CLASS_METHODS__TtC5UIKit21_UIToolbarPaddingSpec
- __CLASS_PROPERTIES__TtC5UIKit21_UIToolbarPaddingSpec
- __DATA__TtC5UIKit21_UIToolbarPaddingSpec
- __INSTANCE_METHODS__TtC5UIKit21_UIToolbarPaddingSpec
- __IVARS__TtC5UIKit21_UIToolbarPaddingSpec
- __METACLASS_DATA__TtC5UIKit21_UIToolbarPaddingSpec
- __OBJC_$_CLASS_METHODS__UITraitHiddenViewsContributeToPocket
- __OBJC_$_CLASS_PROP_LIST__UITraitHiddenViewsContributeToPocket
- __OBJC_$_INSTANCE_METHODS__UIPlaceholderWindowScene
- __OBJC_CLASS_PROTOCOLS_$__UITraitHiddenViewsContributeToPocket
- __OBJC_CLASS_RO_$__UITraitHiddenViewsContributeToPocket
- __OBJC_METACLASS_RO_$__UITraitHiddenViewsContributeToPocket
- __PROPERTIES__TtC5UIKit21_UIToolbarPaddingSpec
- ___72-[UIDictationController _presentEnablementAndDataSharingPromptIfNeeded:]_block_invoke_2
- ___72-[UIDictationController _presentEnablementAndDataSharingPromptIfNeeded:]_block_invoke_3
- ___72-[UIDictationController _presentEnablementAndDataSharingPromptIfNeeded:]_block_invoke_4
- ___72-[UIDictationController _presentEnablementAndDataSharingPromptIfNeeded:]_block_invoke_5
- ___72-[UIDictationController _presentEnablementAndDataSharingPromptIfNeeded:]_block_invoke_6
- ___99-[UIDictationController tearDownPrivacyAndDataSharingSheetPresenterWindowAfterTextResponderReloads]_block_invoke
- ___block_descriptor_64_e8_32s40s48bs56r_e24_v16?0?<"NSNumber"?>8ls32l8r56l8s40l8s48l8
- ___swift_memcpy265_8
- ___swift_memcpy329_8
- ___swift_memcpy344_8
- ___swift_memcpy393_8
- ___unnamed_178
- _symbolic So36_UITabBarControllerVisualStyle_PhoneCXo
- _symbolic So37_UITraitHiddenViewsContributeToPocketC
- _symbolic _____ 5UIKit21_UIToolbarPaddingSpecC
- _symbolic _____ 5UIKit37_UITraitHiddenViewsContributeToPocketV
CStrings:
+ "%s Checking Siri & Dictation Data Sharing Opt In Eligibility"
+ "%s Dictation Enablement Early Return, dictationEnabled=%d, dataSharingOptInSuppressed=%d"
+ "%s Enablement Flow Complete, success=%d"
+ "%s Presenting Dictation Enablement Prompt"
+ "%s Presenting Siri & Dictation Data Sharing Opt In Sheet"
+ "%s Recieved Dictation Enablement Prompt Response, dictationEnabled=%d, firstDictation=%d"
+ "%s Recieved Siri & Dictation Data Sharing Opt In Response, dataSharingDecided=%d"
+ "%s svc = %p; viewController = %@; column = %ld; separating view controller"
+ "%s, alertType=%lu"
+ "-[UIDictationController _endEnableDictationPromptAnimated:]"
+ "-[UIDictationController _presentAlertForDictationInputModeOfType:completionHandler:]"
+ "-[UIDictationController _presentEnablementAndDataSharingPromptIfNeeded:]"
+ "-[UIDictationController _presentEnablementAndDataSharingPromptIfNeeded:]_block_invoke"
+ "-[UIDictationController presentAlertOfType:withCompletion:]"
+ "-[UIDictationController presentAlertOfType:withCompletion:]_block_invoke_3"
+ "-[UIDictationController restoreInputViewsAndTearDownPrivacyDataSharingSheetWindowIfNeeded]"
+ "-[UIDictationController startDictationAfterSuccessfulEnablementOnNextRunLoop]"
+ "-[UIDictationController startDictationAfterSuccessfulEnablement]"
+ "-[UIDictationController startDictationAfterTextResponderReloads]"
+ "-[UIDictationController tearDownPrivacyAndDataSharingSheetPresenterWindow]"
+ "Delegate reports supportsAdaptiveImageGlyph but does not implement -insertAdaptiveImageGlyph:replacementRange:; falling back. Responder: %@"
+ "DictationEnablement"
+ "GlassContainerMorphTarget"
+ "UIGlassContainerMorphTargetTrait"
+ "Unexpectedly falling back to the key window scene for the renderingEnvironment"
+ "asymmetric_layout_margins"
- "HiddenViewsContributeToPocket"
- "Horizontal Padding Overflow"
- "Phone (compact height)"
- "UIHiddenViewsContributeToPocket"
- "maxHorizontalPaddingOverflow"
- "phoneCompactHeightBottom"
- "phoneCompactHeightSides"
```
