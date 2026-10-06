## SmartNameSuggestions

> `/System/Library/PrivateFrameworks/SmartNameSuggestions.framework/SmartNameSuggestions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d1c8` | `0x27a08` | **`+0xa840`** |
| `__AUTH_CONST.__const` | `0x5d8` | `0xd38` | **`+0x760`** |
| `__DATA.__bss` | `0x900` | `0x1000` | **`+0x700`** |
| `__TEXT.__const` | `0xaf8` | `0x1120` | **`+0x628`** |
| `__AUTH_CONST.__auth_got` | `0x840` | `0xa50` | **`+0x210`** |
| `__TEXT.__cstring` | `0x622` | `0x802` | **`+0x1e0`** |
| `__DATA.__data` | `0x468` | `0x628` | **`+0x1c0`** |
| `__TEXT.__swift5_fieldmd` | `0x214` | `0x39c` | **`+0x188`** |
| `__TEXT.__swift5_typeref` | `0x468` | `0x5c4` | **`+0x15c`** |
| `__AUTH.__data` | `0x240` | `0x398` | **`+0x158`** |
| `__TEXT.__constg_swiftt` | `0x510` | `0x658` | **`+0x148`** |
| `__AUTH_CONST.__objc_const` | `0x7e8` | `0x900` | **`+0x118`** |
| `__TEXT.__unwind_info` | `0x630` | `0x748` | **`+0x118`** |
| `__TEXT.__oslogstring` | `0x883` | `0x993` | **`+0x110`** |
| `__TEXT.__eh_frame` | `0x7b0` | `0x8b0` | **`+0x100`** |
| `__TEXT.__swift5_reflstr` | `0x2b1` | `0x369` | **`+0xb8`** |
| `__TEXT.__swift5_assocty` | `0x78` | `0xd8` | **`+0x60`** |
| `__TEXT.__swift5_proto` | `0x48` | `0x84` | **`+0x3c`** |
| `__DATA_CONST.__objc_selrefs` | `0x228` | `0x260` | **`+0x38`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x50` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x28` | `0x44` | **`+0x1c`** |
| `__DATA_CONST.__const` | `0x110` | `0x128` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x338` | `0x320` | **`-0x18`** |
| `__AUTH.__objc_data` | `0x8a0` | `0x890` | **`-0x10`** |
| `__DATA.__common` | `0xc0` | `0xb8` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `—` | `0x4` | **`+0x4`** |

### Other Changes

```diff

-16.0.100.0.0
+18.0.0.0.0

+  - /System/Library/Frameworks/NaturalLanguage.framework/NaturalLanguage
+  - /System/Library/Frameworks/UIKit.framework/UIKit

+  - /usr/lib/swift/libswiftCoreImage.dylib
+  - /usr/lib/swift/libswiftCoreLocation.dylib

+  - /usr/lib/swift/libswiftNaturalLanguage.dylib

+  - /usr/lib/swift/libswiftSpatial.dylib

-  Functions: 530
-  Symbols:   368
-  CStrings:  78
+  Functions: 660
+  Symbols:   449
+  CStrings:  95
Symbols:
+ _NLTagAdjective
+ _NLTagAdverb
+ _NLTagNoun
+ _NLTagPronoun
+ _NLTagSchemeLexicalClass
+ _NLTagVerb
+ _NSURLFileSizeKey
+ _OBJC_CLASS_$_NLLanguageRecognizer
+ _OBJC_CLASS_$_NLTagger
+ _OBJC_CLASS_$_NSRegularExpression
+ _OBJC_CLASS_$_UITextChecker
+ __DATA__TtC20SmartNameSuggestions21FilenameQualityScorer
+ __IVARS__TtC20SmartNameSuggestions21FilenameQualityScorer
+ __METACLASS_DATA__TtC20SmartNameSuggestions21FilenameQualityScorer
+ ___swift_instantiateGenericMetadata
+ ___swift_mutable_project_boxed_opaque_existential_1
+ ___swift_project_boxed_opaque_existential_1
+ __objc_autoreleasePoolPop
+ __objc_autoreleasePoolPush
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftCoreImage_$_SmartNameSuggestions
+ __swift_FORCE_LOAD_$_swiftCoreLocation
+ __swift_FORCE_LOAD_$_swiftCoreLocation_$_SmartNameSuggestions
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage_$_SmartNameSuggestions
+ __swift_FORCE_LOAD_$_swiftSpatial
+ __swift_FORCE_LOAD_$_swiftSpatial_$_SmartNameSuggestions
+ __swift_FORCE_LOAD_$_swiftUIKit
+ __swift_FORCE_LOAD_$_swiftUIKit_$_SmartNameSuggestions
+ _associated conformance 20SmartNameSuggestions14ScriptCategoryOSHAASQ
+ _associated conformance So11NLTagSchemeaSHSCSQ
+ _associated conformance So11NLTagSchemeas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So11NLTagSchemeas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _associated conformance So5NLTagaSHSCSQ
+ _associated conformance So5NLTagas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So5NLTagas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _log2
+ _stat
+ _swift_arrayDestroy
+ _swift_cvw_allocateGenericValueMetadataWithLayoutString
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithCopy
+ _swift_cvw_initWithTake
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_dynamicCastClass
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getFunctionTypeMetadata0
+ _swift_getGenericMetadata
+ _swift_makeBoxUnique
+ _swift_release_x1
+ _swift_release_x26
+ _swift_retain_x19
+ _swift_retain_x24
+ _swift_storeEnumTagSinglePayloadGeneric
+ _swift_unexpectedError
+ _symbolic $s20SmartNameSuggestions13SpellCheckingP
+ _symbolic SDySSSbG
+ _symbolic SDySSSi12coveredChars_SaySSG5wordstG
+ _symbolic SaySJG
+ _symbolic SayxG
+ _symbolic Sd
+ _symbolic Si_SaySSGt
+ _symbolic So13UITextCheckerC
+ _symbolic So20NLLanguageRecognizerC
+ _symbolic _____ 10Foundation4DateV
+ _symbolic _____ 20SmartNameSuggestions0B17SuggestionRequestC16visibleItemNames2in011forChildrenE00J9Directory04dropB0SaySSG10Foundation3URLV_S2bSSSgtKFZ06ScoredG0L_V
+ _symbolic _____ 20SmartNameSuggestions13BoundedRecentV
+ _symbolic _____ 20SmartNameSuggestions14ScriptCategoryO
+ _symbolic _____ 20SmartNameSuggestions20PlatformSpellCheckerV
+ _symbolic _____ 20SmartNameSuggestions21FilenameQualityScorerC
+ _symbolic _____ So11NLTagSchemea
+ _symbolic _____ So5NLTaga
+ _symbolic ______p 20SmartNameSuggestions13SpellCheckingP
+ _symbolic _____xc 10Foundation4DateV
+ _symbolic _____ySJG s10ArraySliceV
+ _symbolic _____ySJG s11_SetStorageC
+ _symbolic _____ySJG s23_ContiguousArrayStorageC
+ _symbolic _____ySJSiG s18_DictionaryStorageC
+ _symbolic _____ySSSbG s18_DictionaryStorageC
+ _symbolic _____ySSSi12coveredChars_SaySSG5wordstG s18_DictionaryStorageC
+ _symbolic _____ySiG s11_SetStorageC
+ _symbolic _____ySi_SaySSGtG s23_ContiguousArrayStorageC
+ _symbolic _____ySsG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G 20SmartNameSuggestions13BoundedRecentV AA0B17SuggestionRequestC16visibleItemNames2in011forChildrenG00L9Directory04dropB0SaySSG10Foundation3URLV_S2bSSSgtKFZ06ScoredI0L_V
+ _symbolic _____y_____G s11_SetStorageC So5NLTaga
+ _symbolic _____y_____G s16PartialRangeFromV SS5IndexV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 20SmartNameSuggestions0E17SuggestionRequestC16visibleItemNames2in011forChildrenH00M9Directory04dropE0SaySSG10Foundation3URLV_S2bSSSgtKFZ06ScoredJ0L_V
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So11NLTagSchemea
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So5NLTaga
+ _type_layout_string 20SmartNameSuggestions20PlatformSpellCheckerV
- _OBJC_CLASS_$_NSError
- _swift_retain_x22
- _swift_retain_x25
- _swift_retain_x27
- _swift_retain_x28
- _symbolic SS4name_Sb8isFolder_____Sg3modt 10Foundation4DateV
- _symbolic SS4name_Sb8isFolder_____Sg3modtSg 10Foundation4DateV
- _symbolic SS_ypt
- _symbolic _____Sg_ABt 10Foundation4DateV
- _symbolic _____ySS4name_Sb8isFolder_____Sg3modtG s23_ContiguousArrayStorageC 10Foundation4DateV
- _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
- _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation3URLV
CStrings:
+ "%{public}s is set to 0 — this will effectively disable the parameter."
+ "File content has 0 words, minimum is "
+ "File is empty (0 bytes): %{private}s"
+ "Item is dataless: %{private}s"
+ "Permission Denied(Feature Flag)"
+ "SmartNameSuggestions/FilenameQualityScorer.swift"
+ "The item is dataless"
+ "Unable to read file content"
+ "Using non-default value for %{public}s: %ld"
+ "Value for %{public}s is out of range (%ld...%ld): %ld, clamping"
+ "[0-9a-fA-F]{8}-[0-9a-fA-F]{4}-[0-9a-fA-F]{4}-[0-9a-fA-F]{4}-[0-9a-fA-F]{12}"
+ "\\d{4}[-_]?\\d{2}[-_]?\\d{2}[-_T ]\\d{2}[-_:]?\\d{2}[-_:]?\\d{2}"
+ "\\d{4}[-_]\\d{2}[-_]\\d{2}"
+ "^[A-Z][a-z]+[A-Z][a-z]+"
+ "^[a-z]+[A-Z][a-z]+"
+ "^\\d[\\d\\s\\-_.]*\\d$|^\\d$"
+ "スクリーンショット"
```
