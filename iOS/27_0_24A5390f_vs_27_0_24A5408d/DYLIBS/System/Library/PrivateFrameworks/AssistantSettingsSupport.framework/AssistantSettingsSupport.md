## AssistantSettingsSupport

> `/System/Library/PrivateFrameworks/AssistantSettingsSupport.framework/AssistantSettingsSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x3f60` | `0x3fc0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x6e38` | `0x6e78` | **`+0x40`** |
| `__TEXT.__text` | `0x8471c` | `0x84754` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0xaef` | `0xabf` | **`-0x30`** |
| `__DATA_CONST.__got` | `0xce8` | `0xcf8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x2e28` | `0x2e38` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x944` | `0x938` | **`-0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x2478` | `0x2480` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1e98` | `0x1ea0` | **`+0x8`** |

### Other Changes

```diff

-3600.55.30.0.0
+3600.55.37.11.2

-  Functions: 2630
-  Symbols:   2763
-  CStrings:  984
+  Functions: 2629
+  Symbols:   2766
+  CStrings:  986
Symbols:
+ -[AssistantDetailController setShowCallSuggestions:specifier:]
+ -[AssistantDetailController showCallSuggestionsEnabled:]
+ GCC_except_table21
+ GCC_except_table29
+ _kCFBooleanFalse
+ _kCFBooleanTrue
- +[SRUIFSiriFeatureFlag(SWEFeatureFlags) isAssistedLinwoodVoiceResponseFromCompanionEnabled]
- GCC_except_table19
- GCC_except_table27
CStrings:
+ "SIRIANDSEARCH_PERAPP_SUGGESTIONS_SHOWCALLSUGGESTIONS_TOGGLE_FACETIMEAPP"
+ "ShouldShowCallSuggestions"
+ "com.apple.facetime"
- "assisted_linwood_voice_response_from_companion"
```
