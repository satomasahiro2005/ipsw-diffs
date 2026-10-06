## SmartNameSuggestions

> `/System/Library/PrivateFrameworks/SmartNameSuggestions.framework/SmartNameSuggestions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27a08` | `0x2a7a0` | **`+0x2d98`** |
| `__AUTH_CONST.__objc_const` | `0x900` | `0xa28` | **`+0x128`** |
| `__TEXT.__cstring` | `0x802` | `0x912` | **`+0x110`** |
| `__AUTH_CONST.__auth_got` | `0xa50` | `0xb20` | **`+0xd0`** |
| `__AUTH.__data` | `0x398` | `0x440` | **`+0xa8`** |
| `__TEXT.__eh_frame` | `0x8b0` | `0x950` | **`+0xa0`** |
| `__TEXT.__const` | `0x1120` | `0x11b8` | **`+0x98`** |
| `__DATA.__data` | `0x628` | `0x6b0` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0x748` | `0x7c8` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x658` | `0x69c` | **`+0x44`** |
| `__TEXT.__objc_methlist` | `0x320` | `0x360` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x993` | `0x9d3` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x369` | `0x3a1` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x5c4` | `0x5f7` | **`+0x33`** |
| `__AUTH.__objc_data` | `0x890` | `0x8b8` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x39c` | `0x3c4` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x128` | `0x148` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x260` | `0x280` | **`+0x20`** |
| `__DATA.__common` | `0xb8` | `0xc8` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x14c` | `0x158` | **`+0xc`** |
| `__AUTH_CONST.__const` | `0xd38` | `0xd30` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x44` | `0x48` | **`+0x4`** |

### Other Changes

```diff

-18.0.0.0.0
+19.0.0.0.0

-  Functions: 660
-  Symbols:   449
-  CStrings:  95
+  Functions: 695
+  Symbols:   460
+  CStrings:  105
Symbols:
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_NSDictionary
+ _OBJC_CLASS_$_NSNumber
+ __DATA__TtC20SmartNameSuggestions18SuggestionSignpost
+ __IVARS__TtC20SmartNameSuggestions18SuggestionSignpost
+ __METACLASS_DATA__TtC20SmartNameSuggestions18SuggestionSignpost
+ __OBJC_$_CLASS_METHODS_SNNameSuggestionRequest(SNNameSuggestionRequest)
+ ___swift_closure_destructor.50Tm
+ __os_signpost_emit_with_name_impl
+ _keypath_get.3Tm
+ _keypath_get.7Tm
+ _swift_retain_x22
+ _swift_retain_x25
+ _swift_retain_x27
+ _swift_retain_x28
+ _symbolic SDySSSo8NSObjectCG
+ _symbolic _____ 20SmartNameSuggestions18SuggestionSignpostC
+ _symbolic _____Sg 2os23OSSignpostIntervalStateC
+ _symbolic _____ySSSo8NSObjectCG s18_DictionaryStorageC
+ _symbolic _____y_____SgG 15Synchronization5MutexVAARi_zrlE 2os23OSSignpostIntervalStateC
+ _symbolic _____yyXlXpG s23_ContiguousArrayStorageC
- __CLASS_METHODS_SNNameSuggestionRequest
- ___swift_closure_destructor.56Tm
- ___swift_project_boxed_opaque_existential_1
- _get_type_metadata 15Synchronization5MutexVySbG noncopyable
- _keypath_get.5Tm
- _swift_retain_x23
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic So13UITextCheckerC
- _symbolic _____Sg 20SmartNameSuggestions0B18SuggestionResponseC
- _type_layout_string 20SmartNameSuggestions20PlatformSpellCheckerV
CStrings:
+ "%s"
+ "Spell checking: %{private}s in language: %{public}s"
+ "Suggest names for url: %{private}s"
+ "SuggestionRequest"
+ "[Error] Interval already ended"
+ "com.apple.iwork.keynote.sffkey"
+ "com.apple.iwork.numbers.sffnumbers"
+ "com.apple.iwork.pages.sffpages"
+ "error: abandoned"
+ "promptDictionary"
+ "suggestNamesFor(completion) called for %{private}s"
+ "telemetryContentType"
- "Suggest names for url: %{public}s"
- "suggestNamesFor(completion) called for %{public}s"
```
