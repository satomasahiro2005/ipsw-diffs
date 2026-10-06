## ImageGenerationServices

> `/System/Library/PrivateFrameworks/ImageGenerationServices.framework/ImageGenerationServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8ed84` | `0x91b08` | **`+0x2d84`** |
| `__DATA.__bss` | `0x5980` | `0x6810` | **`+0xe90`** |
| `__AUTH_CONST.__const` | `0x4640` | `0x4ff8` | **`+0x9b8`** |
| `__TEXT.__const` | `0x64d5` | `0x6ded` | **`+0x918`** |
| `__TEXT.__eh_frame` | `0x40c0` | `0x3a38` | **`-0x688`** |
| `__TEXT.__cstring` | `0x7a62` | `0x7f62` | **`+0x500`** |
| `__TEXT.__swift5_reflstr` | `0x1615` | `0x1ac5` | **`+0x4b0`** |
| `__TEXT.__swift5_fieldmd` | `0x15d8` | `0x1950` | **`+0x378`** |
| `__AUTH_CONST.__objc_const` | `0x990` | `0xb88` | **`+0x1f8`** |
| `__DATA.__data` | `0x990` | `0xb70` | **`+0x1e0`** |
| `__TEXT.__swift5_typeref` | `0x16e2` | `0x1894` | **`+0x1b2`** |
| `__TEXT.__constg_swiftt` | `0x1008` | `0x11a0` | **`+0x198`** |
| `__AUTH.__data` | `0x1b0` | `0x310` | **`+0x160`** |
| `__AUTH_CONST.__auth_got` | `0x1718` | `0x1810` | **`+0xf8`** |
| `__TEXT.__unwind_info` | `0x2098` | `0x2190` | **`+0xf8`** |
| `__TEXT.__swift5_assocty` | `0x240` | `0x2e8` | **`+0xa8`** |
| `__TEXT.__swift5_capture` | `0x2a8` | `0x344` | **`+0x9c`** |
| `__DATA_DIRTY.__bss` | `0x1280` | `0x1200` | **`-0x80`** |
| `__TEXT.__swift_as_cont` | `0x2e8` | `0x268` | **`-0x80`** |
| `__TEXT.__swift5_proto` | `0x37c` | `0x3ec` | **`+0x70`** |
| `__DATA_CONST.__got` | `0x870` | `0x8d0` | **`+0x60`** |
| `__DATA_DIRTY.__data` | `0x1938` | `0x18d8` | **`-0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x158` | `0x1a8` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x18d2` | `0x1892` | **`-0x40`** |
| `__TEXT.__swift_as_ret` | `0x188` | `0x150` | **`-0x38`** |
| `__TEXT.__swift5_types` | `0x190` | `0x1c0` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x110` | `0xf0` | **`-0x20`** |
| `__DATA_DIRTY.__common` | `0x50` | `0x38` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0xf0` | `0xdc` | **`-0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x50` | `0x60` | **`+0x10`** |
| `__DATA.__common` | `0x50` | `0x48` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x20` | `0x18` | **`-0x8`** |

### Other Changes

```diff

-194.1.0.0.0
+198.1.0.0.0

+  - /System/Library/PrivateFrameworks/CoreEmoji.framework/CoreEmoji
+  - /System/Library/PrivateFrameworks/EmojiFoundation.framework/EmojiFoundation

-  Functions: 2486
-  Symbols:   1458
-  CStrings:  351
+  Functions: 2655
+  Symbols:   1531
+  CStrings:  389
Symbols:
+ _CEMCreateEmojiLocaleData
+ _CEMEmojiTokenCopyGenmojiDescription
+ _CEMEmojiTokenCopyName
+ _CEMEmojiTokenGetSkinTone
+ _CEMEmojiTokenGetString
+ _CEMEnumerateEmojiTokensInStringWithBlock
+ _CEMEnumerateEmojiTokensInStringWithLocaleAndBlock
+ _LXLexiconCreate
+ _OBJC_CLASS_$_EMFEmojiLocaleData
+ _OBJC_CLASS_$_EMFEmojiToken
+ _OBJC_CLASS_$_NSMutableString
+ _OBJC_CLASS_$_NSString
+ _OBJC_CLASS_$_OS_os_log
+ __DATA__TtC23ImageGenerationServices19EmojiPromptResolver
+ __DATA__TtC23ImageGenerationServices39UnsupportedLanguageOffensiveWordChecker
+ __IVARS__TtC23ImageGenerationServices11EmojiPrompt
+ __IVARS__TtC23ImageGenerationServices19EmojiPromptResolver
+ __IVARS__TtC23ImageGenerationServices39UnsupportedLanguageOffensiveWordChecker
+ __METACLASS_DATA__TtC23ImageGenerationServices19EmojiPromptResolver
+ __METACLASS_DATA__TtC23ImageGenerationServices39UnsupportedLanguageOffensiveWordChecker
+ ___swift_allocate_boxed_opaque_existential_1Tm
+ ___swift_memcpy248_8
+ ___swift_memcpy51_8
+ _associated conformance 23ImageGenerationServices19EmojiPromptCategoryV10CodingKeysOSHAASQ
+ _associated conformance 23ImageGenerationServices19EmojiPromptCategoryV10CodingKeysOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 23ImageGenerationServices19EmojiPromptCategoryV10CodingKeysOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 23ImageGenerationServices19EmojiPromptCategoryVSHAASQ
+ _associated conformance 23ImageGenerationServices19EmojiPromptResolverC16SubstitutionModeOSHAASQ
+ _associated conformance 23ImageGenerationServices19EmojiPromptResolverC19CuratedPromptsPlist018_C840F46D4A5342D05L13B7D8C0EE12279LLV10CodingKeysOSHAASQ
+ _associated conformance 23ImageGenerationServices19EmojiPromptResolverC19CuratedPromptsPlist018_C840F46D4A5342D05L13B7D8C0EE12279LLV10CodingKeysOs0S3KeyAAs23CustomStringConvertible
+ _associated conformance 23ImageGenerationServices19EmojiPromptResolverC19CuratedPromptsPlist018_C840F46D4A5342D05L13B7D8C0EE12279LLV10CodingKeysOs0S3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 23ImageGenerationServices21EmojiPromptDescriptorV10CodingKeysOSHAASQ
+ _associated conformance 23ImageGenerationServices21EmojiPromptDescriptorV10CodingKeysOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 23ImageGenerationServices21EmojiPromptDescriptorV10CodingKeysOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 23ImageGenerationServices21EmojiPromptDescriptorV5StyleOSHAASQ
+ _associated conformance 23ImageGenerationServices21EmojiPromptDescriptorVSHAASQ
+ _objc_retain_x26
+ _swift_dynamicCastObjCClass
+ _swift_getKeyPath
+ _swift_retain_x28
+ _symbolic $s10Foundation26DecodableWithConfigurationP
+ _symbolic SDySJ_____G 23ImageGenerationServices21EmojiPromptDescriptorV
+ _symbolic SDySi_____G 23ImageGenerationServices19EmojiPromptCategoryV
+ _symbolic SJSg
+ _symbolic Say_____G 23ImageGenerationServices19EmojiPromptCategoryV
+ _symbolic Say_____G 23ImageGenerationServices19EmojiPromptResolverC13parsingEmojis2in4mode9isSubjectS2S_AC16SubstitutionModeOSbtF11ReplacementL_V
+ _symbolic Say_____G 23ImageGenerationServices21EmojiPromptDescriptorV
+ _symbolic Say_____G So12LXLexiconRefa
+ _symbolic Say_____Gz_Xx 23ImageGenerationServices19EmojiPromptResolverC13parsingEmojis2in4mode9isSubjectS2S_AC16SubstitutionModeOSbtF11ReplacementL_V
+ _symbolic Say_____Gz_Xx 23ImageGenerationServices21EmojiPromptDescriptorV
+ _symbolic Say_____SgG 23ImageGenerationServices19EmojiPromptCategoryV
+ _symbolic Say_____SgG 23ImageGenerationServices21EmojiPromptDescriptorV
+ _symbolic Si______t 23ImageGenerationServices19EmojiPromptCategoryV
+ _symbolic Siz_Xx
+ _symbolic _____ 23ImageGenerationServices19EmojiPromptCategoryV
+ _symbolic _____ 23ImageGenerationServices19EmojiPromptCategoryV10CodingKeysO
+ _symbolic _____ 23ImageGenerationServices19EmojiPromptCategoryV21DecodingConfigurationV
+ _symbolic _____ 23ImageGenerationServices19EmojiPromptResolverC
+ _symbolic _____ 23ImageGenerationServices19EmojiPromptResolverC13parsingEmojis2in4mode9isSubjectS2S_AC16SubstitutionModeOSbtF11ReplacementL_V
+ _symbolic _____ 23ImageGenerationServices19EmojiPromptResolverC16SubstitutionModeO
+ _symbolic _____ 23ImageGenerationServices19EmojiPromptResolverC19CuratedPromptsPlist018_C840F46D4A5342D05L13B7D8C0EE12279LLV
+ _symbolic _____ 23ImageGenerationServices19EmojiPromptResolverC19CuratedPromptsPlist018_C840F46D4A5342D05L13B7D8C0EE12279LLV10CodingKeysO
+ _symbolic _____ 23ImageGenerationServices19EmojiPromptResolverC19CuratedPromptsPlist018_C840F46D4A5342D05L13B7D8C0EE12279LLV21DecodingConfigurationV
+ _symbolic _____ 23ImageGenerationServices21EmojiPromptDescriptorV
+ _symbolic _____ 23ImageGenerationServices21EmojiPromptDescriptorV10CodingKeysO
+ _symbolic _____ 23ImageGenerationServices21EmojiPromptDescriptorV21DecodingConfigurationV
+ _symbolic _____ 23ImageGenerationServices21EmojiPromptDescriptorV5StyleO
+ _symbolic _____ 23ImageGenerationServices39UnsupportedLanguageOffensiveWordCheckerC
+ _symbolic _____Sg 10Foundation3URLV
+ _symbolic _____Sg 23ImageGenerationServices19EmojiPromptCategoryV
+ _symbolic _____Sg 23ImageGenerationServices21EmojiPromptDescriptorV
+ _symbolic _____Sg_SSt So11CFStringRefa
+ _symbolic _____XDXMT 23ImageGenerationServices19EmojiPromptResolverC
+ _symbolic _____ySJ_____G s18_DictionaryStorageC 23ImageGenerationServices21EmojiPromptDescriptorV
+ _symbolic _____ySi_____G s18_DictionaryStorageC 23ImageGenerationServices19EmojiPromptCategoryV
+ _symbolic _____ySi______tG s23_ContiguousArrayStorageC 23ImageGenerationServices19EmojiPromptCategoryV
+ _symbolic _____y_____G 10Foundation17KeyPathComparatorV 23ImageGenerationServices19EmojiPromptCategoryV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 23ImageGenerationServices19EmojiPromptCategoryV10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 23ImageGenerationServices19EmojiPromptResolverC19CuratedPromptsPlist018_C840F46D4A5342D05O13B7D8C0EE12279LLV10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 23ImageGenerationServices21EmojiPromptDescriptorV10CodingKeysO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 23ImageGenerationServices19EmojiPromptCategoryV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 23ImageGenerationServices19EmojiPromptResolverC13parsingEmojis2in4mode9isSubjectS2S_AE16SubstitutionModeOSbtF11ReplacementL_V
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 23ImageGenerationServices21EmojiPromptDescriptorV
+ _symbolic _____y_____SgG 2os21OSAllocatedUnfairLockV 23ImageGenerationServices39UnsupportedLanguageOffensiveWordCheckerC
+ _symbolic _____y_____SgSSG s18_DictionaryStorageC So11CFStringRefa
+ _symbolic _____y_____Sg_____G s13ManagedBufferCsRi__rlE 23ImageGenerationServices39UnsupportedLanguageOffensiveWordCheckerC So16os_unfair_lock_sV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 23ImageGenerationServices19EmojiPromptResolverC So16os_unfair_lock_sV
+ _type_layout_string 23ImageGenerationServices19EmojiPromptCategoryV
+ _type_layout_string 23ImageGenerationServices19EmojiPromptResolverC13parsingEmojis2in4mode9isSubjectS2S_AC16SubstitutionModeOSbtF11ReplacementL_V
+ _type_layout_string 23ImageGenerationServices19EmojiPromptResolverC19CuratedPromptsPlist018_C840F46D4A5342D05L13B7D8C0EE12279LLV
+ _type_layout_string 23ImageGenerationServices21EmojiPromptDescriptorV
+ _type_layout_string 23ImageGenerationServices21EmojiPromptDescriptorV21DecodingConfigurationV
- ___swift_allocate_boxed_opaque_existential_0Tm
- ___swift_memcpy33_8
- _get_enum_tag_for_layout_string 23ImageGenerationServices22OnDevicePromptAnalyzerC13AFMModelErrorO
- _swift_release_x10
- _symbolic SS8bundleID_SS08templateB0t
- _symbolic Say_____G 23ImageGenerationServices22OnDevicePromptAnalyzerC14PersonEntityV2V
- _symbolic Say_____G 23ImageGenerationServices22OnDevicePromptAnalyzerC14PersonEntityV3V
- _symbolic _____ 23ImageGenerationServices22OnDevicePromptAnalyzerC14PersonEntityV2V
- _symbolic _____ 23ImageGenerationServices22OnDevicePromptAnalyzerC14PersonEntityV3V
- _symbolic _____6entity______0A4Typet 23ImageGenerationServices22OnDevicePromptAnalyzerC12PersonEntityV AA0fG0C0I4TypeO
- _symbolic _____Sg 12ModelCatalog20AssetBackedLLMBundleV
- _symbolic ______p 12ModelCatalog14ResourceBundleP
- _symbolic ______pSg 12ModelCatalog14ResourceBundleP
- _symbolic _____ySbSgG 2os21OSAllocatedUnfairLockV
- _symbolic _____ySbSg_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
- _symbolic _____y_____6entity______0A4TypetG s23_ContiguousArrayStorageC 23ImageGenerationServices22OnDevicePromptAnalyzerC12PersonEntityV AC0iJ0C0L4TypeO
- _symbolic _____y_____G 12ModelCatalog24ResourceBundleIdentifierV AA20AssetBackedLLMBundleV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 23ImageGenerationServices14PromptAnalyzerC10EntityTypeO
- _type_layout_string 23ImageGenerationServices22OnDevicePromptAnalyzerC14PersonEntityV3V
CStrings:
+ ", "
+ ", dark skin, black hair"
+ ", medium brown skin, light brown hair"
+ ", medium dark skin, brown hair"
+ ", medium light brown skin, blond hair"
+ ", pale skin, black hair"
+ "Duplicate values for key: '"
+ "EmojiPromptResolver: failed to load curated_prompts.plist at %{public}@: %{public}@"
+ "OnDevicePromptAnalyzer instantiated with bundle %s; model display version %s"
+ "Resolved userProvidedPrompt: %s"
+ "Swift/NativeDictionary.swift"
+ "VisualGeneration.Genmoji.SheetAPI.Base.1p"
+ "VisualGeneration.Genmoji.SheetAPI.Base.3p"
+ "VisualGeneration.Genmoji.SheetAPI.Personalized.1p"
+ "VisualGeneration.Genmoji.SheetAPI.Personalized.3p"
+ "_LOCALIZABLE_"
+ "allowsMultipleSelection"
+ "categories"
+ "category not found"
+ "categoryID"
+ "com.apple.fm.language.instruct_3b.adm_prompt_analyzer?variant=generic_sparse"
+ "com.apple.fm.language.instruct_3b.adm_prompt_analyzer_v2"
+ "displayName"
+ "emoji"
+ "emojiRepresentation"
+ "extractPersonSpans model output: %s"
+ "first_person"
+ "forcesPersonalization"
+ "genmojiNonSubjectDescription"
+ "genmojiNonSubjectPersonalizationDescription"
+ "genmojiShouldAutomatchPersonalization"
+ "genmojiSubjectDescription"
+ "iconFilename"
+ "id"
+ "localizable fields not found"
+ "localizedDisplayName"
+ "needsPersonalizationUI"
+ "nonSubjectDescription"
+ "nonSubjectPersonalizationDescription"
+ "other"
+ "prompts"
+ "sAgJ3eeqHpCIk79v46FQSIOesKw."
+ "shouldUsePersonDescriptionDirective"
+ "subjectDescription"
+ "subjectPriorityIndex"
+ "unlocalizedName"
+ "version"
- "ErosN6Ih6hAvXBsFkitROGnWnZE."
- "ImageGenerationServices.OnDevicePromptAnalyzer"
- "S3NsYMVrgU7tYn5EDr62d2se9P0."
- "classifyLandscape V3 model output: %s"
- "displayVersion = %s"
- "extractPersonSpans V1 model output: %s"
- "extractPersonSpans V2 model output: %s"
- "extractPersonSpans V3 model output: %s"
- "localizedEmojiDescription is not implemented yet."
```
