## ScreenTimeSettingsUI

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsUI.framework/ScreenTimeSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1270a8` | `0x12a0c8` | **`+0x3020`** |
| `__TEXT.__cstring` | `0xd6e5` | `0xe475` | **`+0xd90`** |
| `__AUTH_CONST.__cfstring` | `0xb5c0` | `0xbd40` | **`+0x780`** |
| `__TEXT.__objc_methlist` | `0xc63c` | `0xc7b4` | **`+0x178`** |
| `__AUTH_CONST.__objc_const` | `0x25f50` | `0x26078` | **`+0x128`** |
| `__AUTH.__objc_data` | `0x5170` | `0x5270` | **`+0x100`** |
| `__DATA_CONST.__objc_selrefs` | `0x6f90` | `0x7060` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x60e3` | `0x6173` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x3d30` | `0x3dc0` | **`+0x90`** |
| `__AUTH_CONST.__auth_got` | `0x1858` | `0x18d8` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x2748` | `0x27c0` | **`+0x78`** |
| `__TEXT.__const` | `0x3d44` | `0x3da4` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x1228` | `0x127c` | **`+0x54`** |
| `__AUTH_CONST.__const` | `0x2f88` | `0x2fd8` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x14a0` | `0x14d8` | **`+0x38`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x150` | `0x180` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x1544` | `0x1570` | **`+0x2c`** |
| `__AUTH.__data` | `0xa38` | `0xa58` | **`+0x20`** |
| `__DATA.__data` | `0x2838` | `0x2858` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x328` | `0x348` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x43ce` | `0x43e4` | **`+0x16`** |
| `__DATA_CONST.__objc_classlist` | `0x7a0` | `0x7b0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xb28` | `0xb38` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xc3c` | `0xc4c` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x608` | `0x610` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x2030` | `0x2038` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xd14` | `0xd18` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x104` | `0x108` | **`+0x4`** |

### Other Changes

```diff

-649.0.0.0.0
+655.0.101.0.0

+  - /System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels

-  Functions: 6277
-  Symbols:   8453
-  CStrings:  2177
+  Functions: 6330
+  Symbols:   8505
+  CStrings:  2240
Symbols:
+ -[STContentPrivacyAccessibilityRestrictionsDetailController _confirmationAlertMessageKey]
+ -[STContentPrivacyAccessibilityRestrictionsDetailController _isExplicitLanguageBlocked]
+ -[STContentPrivacyAccessibilityRestrictionsDetailController _isMathResultsBlocked]
+ -[STContentPrivacyAccessibilityRestrictionsDetailController _isSiriAIAvailable]
+ -[STContentPrivacyAccessibilityRestrictionsDetailController _isSiriAIBlocked]
+ -[STContentPrivacyAccessibilityRestrictionsDetailController _isTargetChild]
+ -[STContentPrivacyAccessibilityRestrictionsDetailController _isWritingToolsBlocked]
+ -[STContentPrivacyAccessibilityRestrictionsDetailController _shouldShowConfirmationAlert]
+ -[STContentPrivacyAccessibilityRestrictionsDetailController _showConfirmationAlertWithCompletion:]
+ -[STContentPrivacyAccessibilityRestrictionsDetailController dealloc]
+ -[STContentPrivacyAccessibilityRestrictionsDetailController initWithRootViewModelCoordinator:]
+ -[STContentPrivacyAccessibilityRestrictionsDetailController observeValueForKeyPath:ofObject:change:context:]
+ -[STContentPrivacyAccessibilityRestrictionsDetailController setCoordinator:]
+ -[STContentPrivacyAccessibilityRestrictionsDetailController specifiers]
+ -[STContentPrivacyAccessibilityRestrictionsDetailController tableView:didSelectRowAtIndexPath:]
+ -[STContentPrivacyListController _topLevelSpecifierWithAction:name:viewableWhenRestrictionsDisabled:]
+ -[STContentPrivacyListController showAccessibilityRestrictions:]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _currentSiriPickerOption]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _openLearnMore]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _radioGroupSpecifierWithName:footerText:showsLearnMoreLink:item:]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _siriTwoOptionPickerSpecifier]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _webContentSpecifierForSiriAI:]
+ -[STContentPrivacyViewModel isAccessibilityAskAllowed]
+ -[STContentPrivacyViewModel setIsAccessibilityAskAllowed:]
+ -[STContentPrivacyViewModelCoordinator saveAccessibilityAskIsAllowed:error:]
+ GCC_except_table121
+ GCC_except_table18
+ _OBJC_CLASS_$_NSLock
+ _OBJC_CLASS_$_STContentPrivacyAccessibilityRestrictionsDetailController
+ _OBJC_CLASS_$_STUICoreDevice
+ _OBJC_CLASS_$__TtC20ScreenTimeSettingsUI30STAccessibilityAskAvailability
+ _OBJC_IVAR_$_STContentPrivacyViewModel._isAccessibilityAskAllowed
+ _OBJC_METACLASS_$_STContentPrivacyAccessibilityRestrictionsDetailController
+ _OBJC_METACLASS_$__TtC20ScreenTimeSettingsUI30STAccessibilityAskAvailability
+ _STIsDeviceChinaSKU
+ __CLASS_METHODS__TtC20ScreenTimeSettingsUI30STAccessibilityAskAvailability
+ __CLASS_PROPERTIES__TtC20ScreenTimeSettingsUI30STAccessibilityAskAvailability
+ __DATA__TtC20ScreenTimeSettingsUI30STAccessibilityAskAvailability
+ __INSTANCE_METHODS__TtC20ScreenTimeSettingsUI30STAccessibilityAskAvailability
+ __METACLASS_DATA__TtC20ScreenTimeSettingsUI30STAccessibilityAskAvailability
+ __OBJC_$_INSTANCE_METHODS_STContentPrivacyAccessibilityRestrictionsDetailController
+ __OBJC_CLASS_RO_$_STContentPrivacyAccessibilityRestrictionsDetailController
+ __OBJC_METACLASS_RO_$_STContentPrivacyAccessibilityRestrictionsDetailController
+ ___95-[STContentPrivacyAccessibilityRestrictionsDetailController tableView:didSelectRowAtIndexPath:]_block_invoke
+ ___95-[STContentPrivacyAccessibilityRestrictionsDetailController tableView:didSelectRowAtIndexPath:]_block_invoke_2
+ ___95-[STContentPrivacyAccessibilityRestrictionsDetailController tableView:didSelectRowAtIndexPath:]_block_invoke_3
+ ___95-[STContentPrivacyAccessibilityRestrictionsDetailController tableView:didSelectRowAtIndexPath:]_block_invoke_4
+ ___98-[STContentPrivacyAccessibilityRestrictionsDetailController _showConfirmationAlertWithCompletion:]_block_invoke
+ ___98-[STContentPrivacyAccessibilityRestrictionsDetailController _showConfirmationAlertWithCompletion:]_block_invoke_2
+ ___block_descriptor_146_e8_32s40s48s56s64s72s80s88s96s104s112s120bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s120l8s112l8
+ ___block_descriptor_40_e8_32bs_e23_v16?0"UIAlertAction"8ls32l8
+ ___block_descriptor_41_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_49_e8_32bs40w_e5_v8?0lw40l8s32l8
+ _symbolic _____ 20ScreenTimeSettingsUI30STAccessibilityAskAvailabilityC
+ _symbolic _____Sg 10Foundation6LocaleV12LanguageCodeV
+ _symbolic _____XMT 20ScreenTimeSettingsUI30STAccessibilityAskAvailabilityC
- -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _radioGroupSpecifierWithName:footerText:item:]
- GCC_except_table119
- GCC_except_table20
- ___block_descriptor_145_e8_32s40s48s56s64s72s80s88s96s104s112s120bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s120l8s112l8
CStrings:
+ "AADC_AccessibilityRestrictionsSpecifierName"
+ "ACCESSIBILITY_RESTRICTIONS"
+ "AccessibilityAskConfirmationAlertAllow"
+ "AccessibilityAskConfirmationAlertCancel"
+ "AccessibilityAskConfirmationAlertTitle"
+ "AccessibilityAskConfirmationMessage_Fallback"
+ "AccessibilityAskConfirmationMessage_NoSiri_ExplicitLanguage"
+ "AccessibilityAskConfirmationMessage_NoSiri_ExplicitLanguage_Named"
+ "AccessibilityAskConfirmationMessage_NoSiri_MathResults"
+ "AccessibilityAskConfirmationMessage_NoSiri_MathResults_ExplicitLanguage"
+ "AccessibilityAskConfirmationMessage_NoSiri_MathResults_ExplicitLanguage_Named"
+ "AccessibilityAskConfirmationMessage_NoSiri_MathResults_Named"
+ "AccessibilityAskConfirmationMessage_NoSiri_WritingTools"
+ "AccessibilityAskConfirmationMessage_NoSiri_WritingTools_ExplicitLanguage"
+ "AccessibilityAskConfirmationMessage_NoSiri_WritingTools_ExplicitLanguage_Named"
+ "AccessibilityAskConfirmationMessage_NoSiri_WritingTools_MathResults"
+ "AccessibilityAskConfirmationMessage_NoSiri_WritingTools_MathResults_ExplicitLanguage"
+ "AccessibilityAskConfirmationMessage_NoSiri_WritingTools_MathResults_ExplicitLanguage_Named"
+ "AccessibilityAskConfirmationMessage_NoSiri_WritingTools_MathResults_Named"
+ "AccessibilityAskConfirmationMessage_NoSiri_WritingTools_Named"
+ "AccessibilityAskConfirmationMessage_TeenSiriAI"
+ "AccessibilityAskConfirmationMessage_TeenSiriAI_ExplicitLanguage"
+ "AccessibilityAskConfirmationMessage_TeenSiriAI_ExplicitLanguage_Named"
+ "AccessibilityAskConfirmationMessage_TeenSiriAI_MathResults"
+ "AccessibilityAskConfirmationMessage_TeenSiriAI_MathResults_ExplicitLanguage"
+ "AccessibilityAskConfirmationMessage_TeenSiriAI_MathResults_ExplicitLanguage_Named"
+ "AccessibilityAskConfirmationMessage_TeenSiriAI_MathResults_Named"
+ "AccessibilityAskConfirmationMessage_TeenSiriAI_Named"
+ "AccessibilityAskConfirmationMessage_TeenSiriAI_WritingTools"
+ "AccessibilityAskConfirmationMessage_TeenSiriAI_WritingTools_ExplicitLanguage"
+ "AccessibilityAskConfirmationMessage_TeenSiriAI_WritingTools_ExplicitLanguage_Named"
+ "AccessibilityAskConfirmationMessage_TeenSiriAI_WritingTools_MathResults"
+ "AccessibilityAskConfirmationMessage_TeenSiriAI_WritingTools_MathResults_ExplicitLanguage"
+ "AccessibilityAskConfirmationMessage_TeenSiriAI_WritingTools_MathResults_ExplicitLanguage_Named"
+ "AccessibilityAskConfirmationMessage_TeenSiriAI_WritingTools_MathResults_Named"
+ "AccessibilityAskConfirmationMessage_TeenSiriAI_WritingTools_Named"
+ "AccessibilityAskConfirmationMessage_U13_SiriAI"
+ "AccessibilityAskConfirmationMessage_U13_SiriAI_ExplicitLanguage"
+ "AccessibilityAskConfirmationMessage_U13_SiriAI_MathResults"
+ "AccessibilityAskConfirmationMessage_U13_SiriAI_MathResults_ExplicitLanguage"
+ "AccessibilityAskConfirmationMessage_U13_SiriAI_WritingTools"
+ "AccessibilityAskConfirmationMessage_U13_SiriAI_WritingTools_ExplicitLanguage"
+ "AccessibilityAskConfirmationMessage_U13_SiriAI_WritingTools_MathResults"
+ "AccessibilityAskConfirmationMessage_U13_SiriAI_WritingTools_MathResults_ExplicitLanguage"
+ "AccessibilityAskFooterText"
+ "AccessibilityAskSpecifierName"
+ "AccessibilityRestrictionsViewModelLoadedContext"
+ "AllowedLabel"
+ "AllowedSiriVersionFooterText_Child"
+ "AllowedSiriVersionFooterText_ChildNamed"
+ "AllowedSiriVersionFooterText_ChildNamedRestricted"
+ "AllowedSiriVersionFooterText_Restricted"
+ "BlockedLabel"
+ "BroadWorldKnowledgeFooterText"
+ "BroadWorldKnowledgeSpecifierName"
+ "Failed to fetch Accessibility Ask restriction: %{public}@. Assuming Allow."
+ "Failed to save Accessibility Ask restriction: %{public}@"
+ "ReducedLabel"
+ "SiriAllowOptionLabel"
+ "SiriBlockedOptionLabel"
+ "SiriDontAllowOptionLabel"
+ "SiriRestrictionsLearnMoreFooterLink"
+ "WebContentSearchFooterText"
+ "WebContentSearchSpecifierName"
+ "accessibility.magnifier"
+ "helpkit://open?book=child-safety&topic=k4n88xwnliel#e6123c9b-5509-437f-8012-327953bcb9f4"
+ "system.siri.allowAccessibilityAsk"
- "ImageCreationFooterText"
- "ReduceLabel"
- "WebContentAndKnowledgeFooterText"
- "WebContentAndKnowledgeSpecifierName"
```
