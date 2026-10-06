## ScreenTimeSettingsUI

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsUI.framework/ScreenTimeSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x124f50` | `0x12730c` | **`+0x23bc`** |
| `__AUTH_CONST.__cfstring` | `0xb1c0` | `0xb5c0` | **`+0x400`** |
| `__TEXT.__cstring` | `0xd355` | `0xd6e5` | **`+0x390`** |
| `__TEXT.__oslogstring` | `0x5f53` | `0x60e3` | **`+0x190`** |
| `__DATA_CONST.__objc_selrefs` | `0x6de8` | `0x6f68` | **`+0x180`** |
| `__TEXT.__objc_methlist` | `0xc4dc` | `0xc61c` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x25e48` | `0x25f50` | **`+0x108`** |
| `__DATA_CONST.__got` | `0x1438` | `0x1498` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x26f8` | `0x2748` | **`+0x50`** |
| `__AUTH_CONST.__objc_arrayobj` | `0xf0` | `0x138` | **`+0x48`** |
| `__AUTH_CONST.__objc_intobj` | `0x8d0` | `0x918` | **`+0x48`** |
| `__DATA_CONST.__objc_arraydata` | `0x2e0` | `0x318` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x3ce8` | `0x3d20` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0xd00` | `0xd14` | **`+0x14`** |

### Other Changes

```diff

-640.0.100.0.0
+645.1.100.0.0

-  Functions: 6231
-  Symbols:   8414
-  CStrings:  2138
+  Functions: 6272
+  Symbols:   8450
+  CStrings:  2177
Symbols:
+ -[STContentPrivacyMediaRestrictionsDetailController setWebContentSpecifier:]
+ -[STContentPrivacyMediaRestrictionsDetailController webContentSpecifier]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _capabilityIconWithSymbolName:backgroundColor:]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _getRealisticImageGenerationLinkListSpecifierValue:]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _getSensitiveTopicsLinkListSpecifierValue:]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _getSiriPickerSpecifierValue:]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _realisticImageGenerationSpecifier]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _sensitiveTopicsSpecifier]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _setRealisticImageGenerationLinkListSpecifierValue:specifier:]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _setSensitiveTopicsLinkListSpecifierValue:specifier:]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _setSiriPickerSpecifierValue:specifier:]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _siriPickerSpecifier]
+ -[STContentPrivacyViewModel isRealisticImageGenerationAllowed]
+ -[STContentPrivacyViewModel isSensitiveTopicsAllowed]
+ -[STContentPrivacyViewModel isSiriAIAllowed]
+ -[STContentPrivacyViewModel regulatoryIntelligenceSiriPolicy]
+ -[STContentPrivacyViewModel setIsRealisticImageGenerationAllowed:]
+ -[STContentPrivacyViewModel setIsSensitiveTopicsAllowed:]
+ -[STContentPrivacyViewModel setIsSiriAIAllowed:]
+ -[STContentPrivacyViewModel setRegulatoryIntelligenceSiriPolicy:]
+ -[STContentPrivacyViewModelCoordinator saveRealisticImageGenerationIsAllowed:error:]
+ -[STContentPrivacyViewModelCoordinator saveSensitiveTopicsIsAllowed:error:]
+ -[STContentPrivacyViewModelCoordinator saveSiriAIIsAllowed:error:]
+ GCC_except_table119
+ GCC_except_table18
+ GCC_except_table204
+ GCC_except_table213
+ _OBJC_CLASS_$_UIGraphicsImageRendererFormat
+ _OBJC_IVAR_$_STContentPrivacyMediaRestrictionsDetailController._webContentSpecifier
+ _OBJC_IVAR_$_STContentPrivacyViewModel._isRealisticImageGenerationAllowed
+ _OBJC_IVAR_$_STContentPrivacyViewModel._isSensitiveTopicsAllowed
+ _OBJC_IVAR_$_STContentPrivacyViewModel._isSiriAIAllowed
+ _OBJC_IVAR_$_STContentPrivacyViewModel._regulatoryIntelligenceSiriPolicy
+ ___106-[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _setSiriPickerSpecifierValue:specifier:]_block_invoke
+ ___113-[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _capabilityIconWithSymbolName:backgroundColor:]_block_invoke
+ ___159-[STContentPrivacyViewModelCoordinator initWithPersistenceController:userDSID:userName:currentAccountIsProto:regulatoryUIPolicyProvider:loadCompletionHandler:]_block_invoke
+ ___67-[STContentPrivacyMediaRestrictionsDetailController viewDidAppear:]_block_invoke_2
+ ___69-[STRootViewModelCoordinator loadRegionRatingsWithCompletionHandler:]_block_invoke_2
+ ___block_descriptor_133_e8_32s40s48s56s64s72s80s88s96s104s112bs_e20_v20?0B8"NSError"12ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8
+ ___block_descriptor_145_e8_32s40s48s56s64s72s80s88s96s104s112s120bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s120l8s112l8
+ ___block_descriptor_40_e8_32s_e41_"STRegulatoryIntelligenceSiriPolicy"8?0ls32l8
+ ___block_descriptor_48_e8_32s40s_e40_v16?0"UIGraphicsImageRendererContext"8ls32l8s40l8
- GCC_except_table110
- GCC_except_table203
- GCC_except_table212
- ___block_descriptor_125_e8_32s40s48s56s64s72s80s88s96s104bs_e20_v20?0B8"NSError"12ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8
- ___block_descriptor_134_e8_32s40s48s56s64s72s80s88s96s104s112bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s112l8s104l8
- _objc_retain_x7
CStrings:
+ "@\"STRegulatoryIntelligenceSiriPolicy\"8@?0"
+ "AllowedSiriVersionFooterText"
+ "AllowedSiriVersionFooterText_ChildRestricted"
+ "AllowedSiriVersionLabel"
+ "CONTENT_RESTRICTIONS/WEB_CONTENT"
+ "CapabilitiesLabel"
+ "DictationSpecifierName"
+ "ExplicitLanguageFooterText"
+ "Failed to fetch Realistic Image Generation restriction: %{public}@. Assuming Don't Allow."
+ "Failed to fetch Sensitive Topics restriction: %{public}@. Assuming Reduce."
+ "Failed to fetch Siri AI restriction: %{public}@. Assuming Don't Allow."
+ "Failed to save Realistic Image Generation restriction: %{public}@"
+ "Failed to save Sensitive Topics restriction: %{public}@"
+ "Failed to save Siri AI restriction: %{public}@"
+ "ImageCreationFooterText"
+ "ImageCreationFooterTextWithRealisticImages"
+ "ImageCreationFooterTextWithRealisticImages_ChildRestricted"
+ "IntelligenceExtensionsFooterText_ChildRestricted"
+ "MathAssistanceFooterText"
+ "MathAssistanceSpecifierName"
+ "RealisticImageGenerationSpecifierName"
+ "ReduceLabel"
+ "SensitiveTopicsFooterText"
+ "SensitiveTopicsSpecifierName"
+ "SiriAIOptionLabel"
+ "SiriClassicOptionLabel"
+ "SiriSpecifierName"
+ "WEB_CONTENT"
+ "WebContentAndKnowledgeFooterText"
+ "WebContentAndKnowledgeSpecifierName"
+ "WritingAssistanceFooterText"
+ "WritingAssistanceSpecifierName"
+ "com.apple.graphic-icon.microphone"
+ "exclamationmark.bubble.fill"
+ "exclamationmark.shield.fill"
+ "globe"
+ "math.operators"
+ "person.crop.artframe"
+ "photo.artframe"
+ "puzzlepiece.extension"
+ "summary.writing.tools.page"
- "AppleIntelligenceLabel"
- "IntelligenceExtensionsDetailFooterText"
```
