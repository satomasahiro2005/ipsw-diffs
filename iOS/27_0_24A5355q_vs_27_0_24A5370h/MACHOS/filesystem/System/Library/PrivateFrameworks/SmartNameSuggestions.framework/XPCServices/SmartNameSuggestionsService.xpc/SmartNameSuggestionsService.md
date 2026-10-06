## SmartNameSuggestionsService

> `/System/Library/PrivateFrameworks/SmartNameSuggestions.framework/XPCServices/SmartNameSuggestionsService.xpc/SmartNameSuggestionsService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x257d8` | `0x30334` | **`+0xab5c`** |
| `__DATA_CONST.__const` | `0x5e0` | `0xd98` | **`+0x7b8`** |
| `__DATA.__bss` | `0xb00` | `0x1200` | **`+0x700`** |
| `__TEXT.__const` | `0xec0` | `0x14f6` | **`+0x636`** |
| `__TEXT.__auth_stubs` | `0x15b0` | `0x1940` | **`+0x390`** |
| `__DATA.__data` | `0xe60` | `0x1198` | **`+0x338`** |
| `__TEXT.__eh_frame` | `0xce8` | `0xf18` | **`+0x230`** |
| `__DATA_CONST.__auth_got` | `0xae0` | `0xca8` | **`+0x1c8`** |
| `__TEXT.__cstring` | `0x7cf` | `0x997` | **`+0x1c8`** |
| `__TEXT.__swift5_fieldmd` | `0x4e8` | `0x670` | **`+0x188`** |
| `__TEXT.__swift5_typeref` | `0x4e8` | `0x660` | **`+0x178`** |
| `__TEXT.__constg_swiftt` | `0x83c` | `0x984` | **`+0x148`** |
| `__TEXT.__unwind_info` | `0x730` | `0x870` | **`+0x140`** |
| `__TEXT.__objc_stubs` | `0x4e0` | `0x600` | **`+0x120`** |
| `__DATA.__objc_const` | `0xf30` | `0x1048` | **`+0x118`** |
| `__TEXT.__objc_methname` | `0xb70` | `0xc31` | **`+0xc1`** |
| `__TEXT.__swift5_reflstr` | `0x4e4` | `0x5a0` | **`+0xbc`** |
| `__TEXT.__oslogstring` | `0xbb1` | `0xc3b` | **`+0x8a`** |
| `__DATA_CONST.__got` | `0x2a0` | `0x320` | **`+0x80`** |
| `__TEXT.__swift5_assocty` | `0xc0` | `0x120` | **`+0x60`** |
| `__DATA_CONST.__auth_ptr` | `0x258` | `0x298` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0x58` | `0x94` | **`+0x3c`** |
| `__DATA.__objc_selrefs` | `0x2e0` | `0x318` | **`+0x38`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x50` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x39f` | `0x3c5` | **`+0x26`** |
| `__TEXT.__swift5_capture` | `0xb0` | `0xd0` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x58` | `0x74` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x448` | `0x430` | **`-0x18`** |
| `__DATA.__objc_data` | `0x9e8` | `0x9d8` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x29f` | `0x295` | **`-0xa`** |
| `__DATA.__common` | `0xc8` | `0xc0` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x70` | `0x78` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `—` | `0x4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-16.0.100.0.0
+18.0.0.0.0

+  - /System/Library/Frameworks/NaturalLanguage.framework/NaturalLanguage

+  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Functions: 534
-  Symbols:   229
-  CStrings:  290
+  Functions: 655
+  Symbols:   249
+  CStrings:  317
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
+ __objc_autoreleasePoolPop
+ __objc_autoreleasePoolPush
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage
+ _log2
+ _swift_cvw_allocateGenericValueMetadataWithLayoutString
+ _swift_deallocUninitializedObject
+ _swift_getFunctionTypeMetadata0
+ _swift_getGenericMetadata
+ _swift_makeBoxUnique
+ _swift_release_x1
+ _swift_retain_x21
+ _swift_unexpectedError
- _swift_retain_x22
- _swift_retain_x25
- _swift_retain_x27
CStrings:
+ "File is empty (0 bytes), skipping content fetch"
+ "SmartNameSuggestionsService/FilenameQualityScorer.swift"
+ "Stripped %{public}ld iWork media/font noise items, length now %ld"
+ "Unable to read file content"
+ "[0-9a-fA-F]{8}-[0-9a-fA-F]{4}-[0-9a-fA-F]{4}-[0-9a-fA-F]{4}-[0-9a-fA-F]{12}"
+ "\\d{4}[-_]?\\d{2}[-_]?\\d{2}[-_T ]\\d{2}[-_:]?\\d{2}[-_:]?\\d{2}"
+ "\\d{4}[-_]\\d{2}[-_]\\d{2}"
+ "^[A-Z][a-z]+[A-Z][a-z]+"
+ "^[a-z]+[A-Z][a-z]+"
+ "^\\d[\\d\\s\\-_.]*\\d$|^\\d$"
+ "_TtC27SmartNameSuggestionsService21FilenameQualityScorer"
+ "com.apple.SmartNaming"
+ "com_apple_iwork_Media"
+ "currentLanguage"
+ "currentScript"
+ "dominantLanguage"
+ "dpCache"
+ "firstMatchInString:options:range:"
+ "initWithPattern:options:error:"
+ "initWithTagSchemes:"
+ "languageRecognizer"
+ "minWordLength"
+ "processString:"
+ "range"
+ "rangeOfMisspelledWordInString:range:startingAt:wrap:language:"
+ "reset"
+ "setString:"
+ "spellChecker"
+ "wordCache"
+ "スクリーンショット"
- "T@\"NSArray\",N,R"
- "reasoning"
- "suggestions"
```
