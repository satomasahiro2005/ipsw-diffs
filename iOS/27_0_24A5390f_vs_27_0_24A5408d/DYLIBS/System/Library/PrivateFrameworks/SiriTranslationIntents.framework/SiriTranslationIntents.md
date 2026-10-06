## SiriTranslationIntents

> `/System/Library/PrivateFrameworks/SiriTranslationIntents.framework/SiriTranslationIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b4bc` | `0x5d914` | **`+0x2458`** |
| `__DATA.__bss` | `0x4c80` | `0x4f80` | **`+0x300`** |
| `__AUTH_CONST.__const` | `0x3438` | `0x3728` | **`+0x2f0`** |
| `__TEXT.__const` | `0x3b54` | `0x3d24` | **`+0x1d0`** |
| `__TEXT.__eh_frame` | `0x3390` | `0x34e8` | **`+0x158`** |
| `__TEXT.__cstring` | `0xf53` | `0x1033` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x1a58` | `0x1b38` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x2a58` | `0x29a8` | **`-0xb0`** |
| `__TEXT.__swift5_typeref` | `0x1004` | `0x10b0` | **`+0xac`** |
| `__AUTH_CONST.__auth_got` | `0x1288` | `0x1300` | **`+0x78`** |
| `__DATA.__data` | `0x1290` | `0x12f0` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0xdf3` | `0xe53` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x1234` | `0x1290` | **`+0x5c`** |
| `__TEXT.__constg_swiftt` | `0x1868` | `0x18bc` | **`+0x54`** |
| `__TEXT.__swift5_assocty` | `0x290` | `0x2c0` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x2ec0` | `0x2ee0` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x284` | `0x29c` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x450` | `0x460` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xb6c` | `0xb7c` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x130` | `0x134` | **`+0x4`** |

### Other Changes

```diff

-3600.10.2.0.0
+3600.10.5.0.0

+  - /System/Library/Frameworks/NaturalLanguage.framework/NaturalLanguage

+  - /usr/lib/swift/libswiftRegexBuilder.dylib

-  Functions: 2607
-  Symbols:   947
-  CStrings:  374
+  Functions: 2681
+  Symbols:   963
+  CStrings:  400
Symbols:
+ _OBJC_CLASS_$_NLLanguageRecognizer
+ _associated conformance So10NLLanguageaSHSCSQ
+ _associated conformance So10NLLanguageas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So10NLLanguageas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _swift_getForeignTypeMetadata
+ _symbolic $ss21_ObjectiveCBridgeableP
+ _symbolic SbIegd_
+ _symbolic So8NSStringC
+ _symbolic _____ 22SiriTranslationIntents11NLConverterC14ResolvedSourceV
+ _symbolic _____ So10NLLanguagea
+ _symbolic _____3key_Sd5valuet So10NLLanguagea
+ _symbolic _____Iegd_ s5Int32V
+ _symbolic _____Iegr_ s5Int32V
+ _symbolic _____y_____3key_Sd5valuetG s23_ContiguousArrayStorageC So10NLLanguagea
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So10NLLanguagea
+ _type_layout_string So10NLLanguagea
CStrings:
+ "Capitalized intentPhrase: "
+ "DI src=%s toSrc=%{bool}d"
+ "IntentSourceLanguage: "
+ "IntentTargetLanguage: "
+ "Offering Translate App; source differs from Siri locale: %s"
+ "Setting translateToSourceLanguage TRUE, intentPhrase is %s."
+ "Source unsupported in Siri and Translate app: %s"
+ "ar"
+ "de"
+ "en"
+ "es"
+ "fr"
+ "hi"
+ "id"
+ "intentSourceLanguage: "
+ "intentTargetLanguage: "
+ "it"
+ "ja"
+ "ko"
+ "nl"
+ "pl"
+ "pt"
+ "ru"
+ "th"
+ "tr"
+ "translateToSourceLanguage=TRUE (localized uso entity), intentPhrase=%s."
+ "tw"
+ "uk"
+ "vi"
+ "yue"
+ "zh"
- "Capitalized intentPhrase: %s intentSourceLanguage: %s"
- "IntentPhrase: %s IntentTargetLanguage: %s IntentSourceLanguage: %s Reference: %s"
- "Will offer user to use Translate App because source language is not the same as the current Siri locale: %s"
- "Will respond with unsupported translation because source language isn't supported in both Siri and Translate App: %s"
- "intentTargetLanguage: %s intentPhrase: %s intentSourceLanguage: %s"
```
