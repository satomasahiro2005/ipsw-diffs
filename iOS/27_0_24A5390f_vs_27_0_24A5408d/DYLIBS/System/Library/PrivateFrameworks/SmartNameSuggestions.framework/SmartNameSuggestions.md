## SmartNameSuggestions

> `/System/Library/PrivateFrameworks/SmartNameSuggestions.framework/SmartNameSuggestions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3040c` | `0x334a0` | **`+0x3094`** |
| `__TEXT.__eh_frame` | `0xa60` | `0xcb0` | **`+0x250`** |
| `__AUTH.__data` | `0x578` | `0x698` | **`+0x120`** |
| `__AUTH_CONST.__auth_got` | `0xc90` | `0xd80` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x880` | `0x960` | **`+0xe0`** |
| `__TEXT.__cstring` | `0xc22` | `0xcf5` | **`+0xd3`** |
| `__TEXT.__swift5_typeref` | `0x74a` | `0x80e` | **`+0xc4`** |
| `__TEXT.__const` | `0x1544` | `0x15f4` | **`+0xb0`** |
| `__AUTH_CONST.__objc_const` | `0xbd8` | `0xc70` | **`+0x98`** |
| `__DATA.__data` | `0x758` | `0x7f0` | **`+0x98`** |
| `__AUTH.__objc_data` | `0x978` | `0xa00` | **`+0x88`** |
| `__TEXT.__constg_swiftt` | `0x7d8` | `0x860` | **`+0x88`** |
| `__TEXT.__swift5_fieldmd` | `0x4a8` | `0x504` | **`+0x5c`** |
| `__TEXT.__oslogstring` | `0xa93` | `0xad3` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x10` | `0x40` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x441` | `0x461` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x190` | `0x1a4` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e8` | `0x2f8` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x24` | `0x34` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x28` | `0x38` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x3a0` | `0x3ac` | **`+0xc`** |
| `__DATA.__common` | `0xe8` | `0xf0` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1a0` | `0x1a8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x5c` | `0x64` | **`+0x8`** |

### Other Changes

```diff

-21.0.0.0.0
+24.0.0.0.0

-  Functions: 804
-  Symbols:   522
-  CStrings:  129
+  Functions: 860
+  Symbols:   547
+  CStrings:  136
Symbols:
+ _OBJC_CLASS_$_NSUUID
+ __DATA__TtC20SmartNameSuggestionsP33_B7362F010E40E0E3A812011B410B3BFE18_ContinuationState
+ __IVARS__TtC20SmartNameSuggestionsP33_B7362F010E40E0E3A812011B410B3BFE18_ContinuationState
+ __METACLASS_DATA__TtC20SmartNameSuggestionsP33_B7362F010E40E0E3A812011B410B3BFE18_ContinuationState
+ ___swift_closure_destructor.102Tm
+ ___swift_closure_destructor.23Tm
+ ___swift_closure_destructor.45Tm
+ ___swift_closure_destructor.55Tm
+ _getuid
+ _swift_allocError
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
+ _swift_release_x10
+ _swift_retain_x26
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
+ _symbolic ScCy___________pGSg 20SmartNameSuggestions0B18SuggestionResponseC s5ErrorP
+ _symbolic Scgy___________pG 20SmartNameSuggestions0B18SuggestionResponseC s5ErrorP
+ _symbolic _____ 10Foundation4UUIDV
+ _symbolic _____ 20SmartNameSuggestions18_ContinuationState33_B7362F010E40E0E3A812011B410B3BFELLC
+ _symbolic _____ 20SmartNameSuggestions18_ContinuationState33_B7362F010E40E0E3A812011B410B3BFELLC01_E0O
+ _symbolic _____ s8DurationV
+ _symbolic _____Sg 10Foundation4UUIDV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 20SmartNameSuggestions18_ContinuationState33_B7362F010E40E0E3A812011B410B3BFELLC01_G0O
+ _symbolic _____y_____G 15Synchronization5_CellVAARi_zrlE 20SmartNameSuggestions18_ContinuationState33_B7362F010E40E0E3A812011B410B3BFELLC01_G0O
+ _symbolic _____y_____yAAyAByAAyABySaySSGGSSSgGGSSGGSSG s15LazyMapSequenceV s0a6FilterC0V
+ _symbolic _____y_____ySaySSGGSSSgG s15LazyMapSequenceV s0a6FilterC0V
+ _symbolic _____y_____ySaySSGGSSSg_G s15LazyMapSequenceV8IteratorV s0a6FilterC0V
- ___swift_closure_destructor.18Tm
- ___swift_closure_destructor.40Tm
- ___swift_closure_destructor.50Tm
- ___swift_closure_destructor.74Tm
CStrings:
+ "Fatal error"
+ "No response from request group"
+ "Request timed out after "
+ "SmartNameSuggestions/SmartNameSuggestions.swift"
+ "Task cancelled while awaiting XPC response — sending cancel to service"
+ "The request timed out."
+ "Unable to access model, running as root"
+ "_ContinuationState.setContinuation called twice"
+ "_sendRequest(_:)"
- "Spell checking: %{private}s in language: %{public}s"
- "suggestNamesFor(request:)"
```
