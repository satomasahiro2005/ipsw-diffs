## SiriSettings

> `/System/Library/PreferenceBundles/SiriSettings.bundle/SiriSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10758` | `0x106a0` | **`-0xb8`** |
| `__TEXT.__cstring` | `0x59f` | `0x56f` | **`-0x30`** |
| `__DATA_CONST.__cfstring` | `0x1e0` | `0x1c0` | **`-0x20`** |
| `__DATA.__data` | `0x6f8` | `0x6e8` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x2e0` | `0x2d0` | **`-0x10`** |
| `__TEXT.__const` | `0x852` | `0x842` | **`-0x10`** |
| `__TEXT.__constg_swiftt` | `0x3d4` | `0x3c4` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3605.26.3.0.0
+3605.32.1.0.0

-  Functions: 376
-  Symbols:   1314
-  CStrings:  181
+  Functions: 372
+  Symbols:   1306
+  CStrings:  180
Symbols:
+ _$sSMsSkRzrlE4sort2byySb7ElementSTQz_ADtKXE_tKFySryADGzKXEfU_s15ContiguousArrayVy9SiriSetup09AppAccessH4InfoVG_Tg504$s12f10Settings09hi40B8ProviderC11visibleAppsSay0A5Setup0cdC4J18VGyFSbAG_AGtXEfU2_Tf1nnc_n
+ _$sSMsSkRzrlE4sort2byySb7ElementSTQz_ADtKXE_tKFySryADGzKXEfU_s15ContiguousArrayVy9SiriSetup21RestrictAccessAppInfoVG_Tg504$s12f10Settings22hi80ProviderC17allVisibleIOSApps33_66C4B3A0C06B7EB3D990F0393DAFD9F8LLSay0A5Setup0cD7jK18VGyFSbAH_AHtXEfU2_Tf1nnc_n
+ _SGIsGlobalHomeScreenSuggestionsEnabledTm
+ _SGSetGlobalHomeScreenSuggestionsTm
- _$s12SiriSettings19SuggestionsProviderC0A5Setup0C9ProvidingAadEP35isSuggestAppsBeforeSearchingEnabledSbyFTW
- _$s12SiriSettings19SuggestionsProviderC0A5Setup0C9ProvidingAadEP36setSuggestAppsBeforeSearchingEnabledyySbFTW
- _$s12SiriSettings19SuggestionsProviderC35isSuggestAppsBeforeSearchingEnabledSbyF
- _$s12SiriSettings19SuggestionsProviderC35isSuggestAppsBeforeSearchingEnabledSbyFTq
- _$s12SiriSettings19SuggestionsProviderC36setSuggestAppsBeforeSearchingEnabledyySbF
- _$s12SiriSettings19SuggestionsProviderC36setSuggestAppsBeforeSearchingEnabledyySbFTq
- _$s9SiriSetup20SuggestionsProvidingP35isSuggestAppsBeforeSearchingEnabledSbyFTq
- _$s9SiriSetup20SuggestionsProvidingP36setSuggestAppsBeforeSearchingEnabledyySbFTq
- _$sSr15_stableSortImpl2byySbx_xtKXE_tKF9SiriSetup09AppAccessG4InfoV_Tg504$s12e10Settings09gh40B8ProviderC11visibleAppsSay0A5Setup0cdC4I18VGyFSbAG_AGtXEfU2_Tf1cn_n
- _$sSr15_stableSortImpl2byySbx_xtKXE_tKF9SiriSetup21RestrictAccessAppInfoV_Tg504$s12e10Settings22gh80ProviderC17allVisibleIOSApps33_66C4B3A0C06B7EB3D990F0393DAFD9F8LLSay0A5Setup0cD7iJ18VGyFSbAH_AHtXEfU2_Tf1cn_n
- _SGIsGlobalZKWSuggestionsEnabledTm
- _SGSetGlobalZKWSuggestionsTm
CStrings:
- "SuggestionsSpotlightZKWEnabled"
```
