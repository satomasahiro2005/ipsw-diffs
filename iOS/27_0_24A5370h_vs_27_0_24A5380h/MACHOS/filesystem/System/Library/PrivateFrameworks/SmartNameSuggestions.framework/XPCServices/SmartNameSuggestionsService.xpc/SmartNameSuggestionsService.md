## SmartNameSuggestionsService

> `/System/Library/PrivateFrameworks/SmartNameSuggestions.framework/XPCServices/SmartNameSuggestionsService.xpc/SmartNameSuggestionsService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30334` | `0x17230` | **`-0x19104`** |
| `__DATA_CONST.__const` | `0xd98` | `0x510` | **`-0x888`** |
| `__DATA.__objc_const` | `0x1048` | `0x860` | **`-0x7e8`** |
| `__TEXT.__const` | `0x14f6` | `0xd18` | **`-0x7de`** |
| `__DATA.__objc_data` | `0x9d8` | `0x258` | **`-0x780`** |
| `__TEXT.__objc_methname` | `0xc31` | `0x4db` | **`-0x756`** |
| `__DATA.__data` | `0x1198` | `0xa48` | **`-0x750`** |
| `__DATA.__bss` | `0x1200` | `0xc80` | **`-0x580`** |
| `__TEXT.__constg_swiftt` | `0x984` | `0x48c` | **`-0x4f8`** |
| `__TEXT.__cstring` | `0x997` | `0x4bf` | **`-0x4d8`** |
| `__TEXT.__auth_stubs` | `0x1940` | `0x14a0` | **`-0x4a0`** |
| `__TEXT.__eh_frame` | `0xf18` | `0xab8` | **`-0x460`** |
| `__TEXT.__swift5_reflstr` | `0x5a0` | `0x1d3` | **`-0x3cd`** |
| `__TEXT.__swift5_fieldmd` | `0x670` | `0x2b4` | **`-0x3bc`** |
| `__TEXT.__unwind_info` | `0x870` | `0x4d8` | **`-0x398`** |
| `__TEXT.__oslogstring` | `0xc3b` | `0x8ab` | **`-0x390`** |
| `__TEXT.__objc_methlist` | `0x430` | `0x198` | **`-0x298`** |
| `__TEXT.__objc_stubs` | `0x600` | `0x3a0` | **`-0x260`** |
| `__DATA_CONST.__auth_got` | `0xca8` | `0xa58` | **`-0x250`** |
| `__TEXT.__swift5_typeref` | `0x660` | `0x468` | **`-0x1f8`** |
| `__DATA.__objc_selrefs` | `0x318` | `0x1b0` | **`-0x168`** |
| `__TEXT.__objc_classname` | `0x3c5` | `0x29f` | **`-0x126`** |
| `__DATA_CONST.__got` | `0x320` | `0x208` | **`-0x118`** |
| `__TEXT.__objc_methtype` | `0x295` | `0x1db` | **`-0xba`** |
| `__DATA.__common` | `0xc0` | `0x58` | **`-0x68`** |
| `__TEXT.__swift5_assocty` | `0x120` | `0xd8` | **`-0x48`** |
| `__DATA_CONST.__objc_classlist` | `0x78` | `0x48` | **`-0x30`** |
| `__TEXT.__swift5_proto` | `0x94` | `0x64` | **`-0x30`** |
| `__TEXT.__swift5_types` | `0x74` | `0x44` | **`-0x30`** |
| `__DATA_CONST.__objc_protolist` | `0x48` | `0x28` | **`-0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x298` | `0x2b0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x50` | `0x3c` | **`-0x14`** |
| `__DATA_CONST.__objc_protorefs` | `0x28` | `0x18` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0xd0` | `0xc0` | **`-0x10`** |
| `__TEXT.__swift5_protos` | `0x4` | `—` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-18.0.0.0.0
+19.0.0.0.0

-  - /System/Library/Frameworks/FileProvider.framework/FileProvider

-  - /System/Library/Frameworks/NaturalLanguage.framework/NaturalLanguage

+  - /System/Library/PrivateFrameworks/SmartNameSuggestions.framework/SmartNameSuggestions

-  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  - /usr/lib/swift/libswiftSynchronization.dylib

-  - /usr/lib/swift/libswift_DarwinFoundation1.dylib

-  Functions: 655
-  Symbols:   249
-  CStrings:  317
+  Functions: 335
+  Symbols:   197
+  CStrings:  185
Symbols:
+ _SNSmartNameSuggestionsErrorDomain
+ _objc_release_x9
- _NLTagAdjective
- _NLTagAdverb
- _NLTagNoun
- _NLTagPronoun
- _NLTagSchemeLexicalClass
- _NLTagVerb
- _NSURLAttributeModificationDateKey
- _NSURLContentTypeKey
- _NSURLIsDirectoryKey
- _NSURLIsHiddenKey
- _NSURLIsPackageKey
- _OBJC_CLASS_$_FPSandboxingURLWrapper
- _OBJC_CLASS_$_NLLanguageRecognizer
- _OBJC_CLASS_$_NLTagger
- _OBJC_CLASS_$_NSDate
- _OBJC_CLASS_$_NSFileManager
- _OBJC_CLASS_$_NSRegularExpression
- _OBJC_CLASS_$_NSString
- _OBJC_CLASS_$_NSURL
- _OBJC_CLASS_$_SNDirectorySuggestionRequest
- _OBJC_CLASS_$_SNFileSuggestionRequest
- _OBJC_CLASS_$_SNNameSuggestionRequest
- _OBJC_CLASS_$_SNNameSuggestionResponse
- _OBJC_CLASS_$_UITextChecker
- _OBJC_METACLASS_$_SNDirectorySuggestionRequest
- _OBJC_METACLASS_$_SNFileSuggestionRequest
- _OBJC_METACLASS_$_SNNameSuggestionRequest
- _OBJC_METACLASS_$_SNNameSuggestionResponse
- __objc_autoreleasePoolPop
- __objc_autoreleasePoolPush
- __swift_FORCE_LOAD_$_swiftNaturalLanguage
- _free
- _log2
- _objc_autorelease
- _objc_autoreleaseReturnValue
- _objc_retain_x9
- _os_unfair_lock_lock
- _os_unfair_lock_unlock
- _realpath$DARWIN_EXTSN
- _swift_arrayInitWithTakeBackToFront
- _swift_arrayInitWithTakeFrontToBack
- _swift_cvw_allocateGenericValueMetadataWithLayoutString
- _swift_endAccess
- _swift_getFunctionTypeMetadata0
- _swift_getGenericMetadata
- _swift_getObjCClassFromMetadata
- _swift_isaMask
- _swift_makeBoxUnique
- _swift_release_x1
- _swift_release_x22
- _swift_retain_x23
- _swift_retain_x28
- _swift_runtimeSupportsNoncopyableTypes
- _swift_unexpectedError
CStrings:
- "$__lazy_storage_$_allExtensions"
- "$__lazy_storage_$_originalBaseName"
- "$__lazy_storage_$_originalExtension"
- "$__lazy_storage_$_originalType"
- "$__lazy_storage_$_siblingNameSet"
- "?"
- "@20@0:8B16"
- "@24@0:8@\"NSCoder\"16"
- "@24@0:8@16"
- "@44@0:8@16@24B32@36"
- "@44@0:8@16@24B32^@36"
- "@48@0:8@16B24B28@32^@40"
- "An unknown error occurred."
- "B"
- "Children names have been provided skipping lookup"
- "Enumerating to get children of %{private}s"
- "Enumerating to get siblings of %{private}s"
- "Failed to get children %{public}@"
- "Failed to get enumerator for url %{private}s"
- "Failed to resolve url with realpath error=%d url=%{private}s"
- "Found children count=%{public}ld"
- "Found siblings count=%{public}ld"
- "Found type for url %{public}s"
- "Looking up type from url"
- "NSCoding"
- "NSSecureCoding"
- "No content was available to analyze."
- "No derived content could be produced from the input."
- "No suggestions could be produced for the given input."
- "Received invalid URL in the request: %s"
- "Request created with url %{private}s"
- "Request with initial url %{private}s"
- "SNDirectorySuggestionRequest"
- "SNFileSuggestionRequest"
- "SNNameSuggestionRequest"
- "SNNameSuggestionResponse"
- "Sibling names have been provided skipping lookup"
- "SmartNameSuggestionsService.NameSuggestionRequest"
- "SmartNameSuggestionsService.NameSuggestionResponse"
- "SmartNameSuggestionsService/FilenameQualityScorer.swift"
- "Suggestion Refiner Removed %{public}ld suggestions"
- "T@\"NSArray\",N,C"
- "T@\"NSDate\",N,C"
- "T@\"NSString\",N,C"
- "T@\"NSString\",N,R"
- "T@\"NSURL\",N,R"
- "TB,N,R"
- "TB,N,R,VisDirectory"
- "TB,R"
- "The caller does not have permission to use this service."
- "The content type is not supported."
- "The language model encountered an error."
- "The request did not contain enough content to produce meaningful suggestions."
- "The request was malformed or missing required parameters."
- "The request was rejected due to content safety policy."
- "The suggestion service is unavailable."
- "URL is not a file URL: "
- "Unable to caption image"
- "Unable to find type from URL %{public}@"
- "Unable to read siblings %{public}@"
- "Using non-default value for %{public}s: %{bool}d"
- "[0-9a-fA-F]{8}-[0-9a-fA-F]{4}-[0-9a-fA-F]{4}-[0-9a-fA-F]{4}-[0-9a-fA-F]{12}"
- "\\d{4}[-_]?\\d{2}[-_]?\\d{2}[-_T ]\\d{2}[-_:]?\\d{2}[-_:]?\\d{2}"
- "\\d{4}[-_]\\d{2}[-_]\\d{2}"
- "^[A-Z][a-z]+[A-Z][a-z]+"
- "^[a-z]+[A-Z][a-z]+"
- "^\\d[\\d\\s\\-_.]*\\d$|^\\d$"
- "_TtC27SmartNameSuggestionsService17SuggestionRefiner"
- "_TtC27SmartNameSuggestionsService21FilenameQualityScorer"
- "_isSpeculative"
- "_url"
- "bestExtension"
- "boolForKey:"
- "childrenNames"
- "creationDate"
- "currentLanguage"
- "currentScript"
- "decodeBoolForKey:"
- "defaultManager"
- "dominantLanguage"
- "dpCache"
- "encodeBool:forKey:"
- "encodeObject:forKey:"
- "encodeWithCoder:"
- "fetchMissingAttributes"
- "firstMatchInString:options:range:"
- "initWithCoder:"
- "initWithPattern:options:error:"
- "initWithSuggestions:url:directory:pathExtension:"
- "initWithSuggestions:url:directory:reasoning:"
- "initWithTagSchemes:"
- "initWithURL:typeIdentifier:speculative:error:"
- "initialSuggestions"
- "isDirectory"
- "languageRecognizer"
- "localeIdentifier"
- "locationString"
- "minWordLength"
- "originalFilename"
- "pathExtension"
- "processString:"
- "range"
- "rangeOfMisspelledWordInString:range:startingAt:wrap:language:"
- "requestURL"
- "reset"
- "setChildrenNames:"
- "setCreationDate:"
- "setLocaleIdentifier:"
- "setLocationString:"
- "setSiblingNames:"
- "setString:"
- "setTextContent:"
- "setTextSummary:"
- "siblingNames"
- "spellChecker"
- "startedAccessing"
- "stringByAppendingPathExtension:"
- "stringByDeletingPathExtension"
- "suggestedBaseNames"
- "suggestionsWithExtension:"
- "supportsSecureCoding"
- "textContent"
- "textSummary"
- "typeIdentifier"
- "url"
- "urlWrapper"
- "v24@0:8@\"NSCoder\"16"
- "v24@0:8@16"
- "visibleItemNamesIn:forChildrenRequest:forDirectory:dropName:error:"
- "wordCache"
- "wrapperWithURL:readonly:error:"
- "スクリーンショット"
```
