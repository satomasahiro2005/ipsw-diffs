## CallIntelligence

> `/System/Library/PrivateFrameworks/CallIntelligence.framework/CallIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdfa8c` | `0xe2944` | **`+0x2eb8`** |
| `__DATA_DIRTY.__data` | `0x1350` | `0x34e0` | **`+0x2190`** |
| `__AUTH.__data` | `0x2328` | `0x6b0` | **`-0x1c78`** |
| `__AUTH.__objc_data` | `0x5c0` | `0x90` | **`-0x530`** |
| `__DATA_DIRTY.__objc_data` | `0x50` | `0x580` | **`+0x530`** |
| `__DATA.__data` | `0x26c8` | `0x22b0` | **`-0x418`** |
| `__AUTH_CONST.__const` | `0x7d08` | `0x7eb0` | **`+0x1a8`** |
| `__TEXT.__oslogstring` | `0x3753` | `0x38f3` | **`+0x1a0`** |
| `__TEXT.__const` | `0xe590` | `0xe6d0` | **`+0x140`** |
| `__TEXT.__cstring` | `0x2571` | `0x2691` | **`+0x120`** |
| `__TEXT.__eh_frame` | `0x7fb0` | `0x80d0` | **`+0x120`** |
| `__DATA.__bss` | `0x13650` | `0x13550` | **`-0x100`** |
| `__DATA_DIRTY.__bss` | `0x2f00` | `0x3000` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0x8218` | `0x82f0` | **`+0xd8`** |
| `__DATA.__common` | `0x138` | `0x68` | **`-0xd0`** |
| `__DATA_DIRTY.__common` | `0xb8` | `0x188` | **`+0xd0`** |
| `__TEXT.__swift5_capture` | `0xafc` | `0xb94` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x3950` | `0x39e0` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x2f34` | `0x2f8c` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x3580` | `0x35d0` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x2bc8` | `0x2c18` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xe70` | `0xeb0` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1388` | `0x13b8` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x3ab5` | `0x3ae3` | **`+0x2e`** |
| `__DATA_CONST.__got` | `0xa48` | `0xa60` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x4ac` | `0x4c4` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xee4` | `0xef0` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x120` | `0x128` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x3fc` | `0x404` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x280` | `0x288` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xb78` | `0xb7c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x2a4` | `0x2a8` | **`+0x4`** |

### Other Changes

```diff

-143.100.11.2.1
+145.100.7.2.1

-  Functions: 4453
-  Symbols:   2005
-  CStrings:  471
+  Functions: 4502
+  Symbols:   2015
+  CStrings:  483
Symbols:
+ _MDItemBundleID
+ _MDItemDateAdded
+ _MDItemExternalID
+ _TUCanShowContextCards
+ __DATA__TtC16CallIntelligence33CallContextCardsSettingsAnalytics
+ __METACLASS_DATA__TtC16CallIntelligence33CallContextCardsSettingsAnalytics
+ ___swift_closure_destructor.7Tm
+ ___swift_closure_destructor.82Tm
+ ___swift_closure_destructor.91Tm
+ ___swift_memcpy18_8
+ _symbolic SS_So8NSObjectCt
+ _symbolic ShySSG
+ _symbolic _____ 16CallIntelligence0A25ContextCardsSettingsEventV
+ _symbolic _____ 16CallIntelligence0A29ContextCardsSettingsAnalyticsC
+ _symbolic _____Sg 10Foundation6LocaleV
+ _symbolic _____ySS_So8NSObjectCtG s23_ContiguousArrayStorageC
+ _type_layout_string 16CallIntelligence0A25ContextCardsSettingsEventV
- ___swift_closure_destructor.114Tm
- ___swift_closure_destructor.65Tm
- _get_type_metadata 15Synchronization5MutexVy16CallIntelligence14CircularBufferVy10Foundation6LocaleV12LanguageCodeV_SdtGG noncopyable
- _get_type_metadata 15Synchronization5MutexVyScTyyts5Error_pGSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVySo16AVCMediaAnalyzerCSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVyys5Error_pYbcSgG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "\"cd && kMDItemEventSourceBundleIdentifier == \""
+ "(kMDItemRelatedUniqueIdentifier == \""
+ "Associated CoreSuggestions query returned %ld items"
+ "Associated CoreSuggestions search failed: %@"
+ "Building associated lookup with %ld clause(s)"
+ "Dropping spotlight item that does not match any searched business name (%{private}s)"
+ "Received context cards testing overrides: %s"
+ "Related items query string: %{private}s"
+ "Sending context cards settings periodic report: currently_enabled=%{bool}d, ever_enabled=%{bool}d"
+ "WaitTimePredictor"
+ "callContextCardsSettingsEverEnabled"
+ "com.apple.settings.smartActionEnablement"
+ "currently_enabled"
+ "runQuery(queryString:atTime:disableMinimumFieldRequirements:queryContainsName:searchedBusinessNames:)"
- "Received context cars testing overrides: %s"
- "runQuery(queryString:atTime:disableMinimumFieldRequirements:queryContainsName:)"
```
