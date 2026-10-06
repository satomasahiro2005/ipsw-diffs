## SiriSettings

> `/System/Library/PreferenceBundles/SiriSettings.bundle/SiriSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf2d4` | `0xfa38` | **`+0x764`** |
| `__DATA.__data` | `0x650` | `0x680` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x810` | `0x840` | **`+0x30`** |
| `__TEXT.__cstring` | `0x52f` | `0x55f` | **`+0x30`** |
| `__TEXT.__const` | `0x858` | `0x878` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x278` | `0x290` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x3b8` | `0x3d0` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0x166` | `0x156` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x188` | `0x17c` | **`-0xc`** |
| `__TEXT.__unwind_info` | `0x488` | `0x490` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.62.36.1.1
+3600.62.43.1.7

-  Functions: 381
-  Symbols:   1242
-  CStrings:  170
+  Functions: 389
+  Symbols:   1259
+  CStrings:  171
Symbols:
+ _$s12SiriSettings09AppAccessB8ProviderC0A5Setup0cdB9ProvidingAadEP22callSuggestionsEnabledSbyFTW
+ _$s12SiriSettings09AppAccessB8ProviderC0A5Setup0cdB9ProvidingAadEP23isCallSuggestionsClientySbSSFTW
+ _$s12SiriSettings09AppAccessB8ProviderC0A5Setup0cdB9ProvidingAadEP25setCallSuggestionsEnabled7enabledySb_tFTW
+ _$s12SiriSettings09AppAccessB8ProviderC17excludedBundleIDs33_6F79FAEF4EB59C99E422FE75093A968ALLShySSGvpZ
+ _$s12SiriSettings09AppAccessB8ProviderC17excludedBundleIDs33_6F79FAEF4EB59C99E422FE75093A968ALL_WZ
+ _$s12SiriSettings09AppAccessB8ProviderC17excludedBundleIDs33_6F79FAEF4EB59C99E422FE75093A968ALL_WZTv_r
+ _$s12SiriSettings09AppAccessB8ProviderC17excludedBundleIDs33_6F79FAEF4EB59C99E422FE75093A968ALL_Wz
+ _$s12SiriSettings09AppAccessB8ProviderC22callSuggestionsEnabledSbyF
+ _$s12SiriSettings09AppAccessB8ProviderC22callSuggestionsEnabledSbyFTq
+ _$s12SiriSettings09AppAccessB8ProviderC23isCallSuggestionsClientySbSSF
+ _$s12SiriSettings09AppAccessB8ProviderC23isCallSuggestionsClientySbSSFTq
+ _$s12SiriSettings09AppAccessB8ProviderC25setCallSuggestionsEnabled7enabledySb_tF
+ _$s12SiriSettings09AppAccessB8ProviderC25setCallSuggestionsEnabled7enabledySb_tFTq
+ _$s9SiriSetup26AppAccessSettingsProvidingP22callSuggestionsEnabledSbyFTq
+ _$s9SiriSetup26AppAccessSettingsProvidingP23isCallSuggestionsClientySbSSFTq
+ _$s9SiriSetup26AppAccessSettingsProvidingP25setCallSuggestionsEnabled7enabledySb_tFTq
+ _$s9SiriSetup30MainAssistantSettingsViewModelC09appAccessE9Providing011suggestionsJ013afPreferencesAcA03AppieJ0_p_AA011SuggestionsJ0_pSo13AFPreferencesCSgtcfc
+ _$sSMsSKRzrlE14_insertionSort6within9sortedEnd2byySny5IndexSlQzG_AFSb7ElementSTQz_AItKXEtKFSry9SiriSetup09AppAccessK4InfoVG_Tg504$s12i10Settings09kl40B8ProviderC11visibleAppsSay0A5Setup0cdC4M18VGyFSbAG_AGtXEfU2_Tf1nncn_n
+ _$sSMsSkRzrlE4sort2byySb7ElementSTQz_ADtKXE_tKFs15ContiguousArrayVy9SiriSetup09AppAccessH4InfoVG_Tg504$s12f10Settings09hi40B8ProviderC11visibleAppsSay0A5Setup0cdC4J18VGyFSbAG_AGtXEfU2_Tf1cn_n
+ _$sSSWOh
+ _$sSr13_mergeTopRuns_6buffer2bySbSaySnySiGGz_SpyxGSbx_xtKXEtKF9SiriSetup09AppAccessH4InfoV_Tg504$s12f10Settings09hi40B8ProviderC11visibleAppsSay0A5Setup0cdC4J18VGyFSbAG_AGtXEfU2_Tf1nncn_n
+ _$sSr15_stableSortImpl2byySbx_xtKXE_tKF9SiriSetup09AppAccessG4InfoV_Tg504$s12e10Settings09gh40B8ProviderC11visibleAppsSay0A5Setup0cdC4I18VGyFSbAG_AGtXEfU2_Tf1cn_n
+ _$sSr15_stableSortImpl2byySbx_xtKXE_tKFySryxGz_SiztKXEfU_9SiriSetup09AppAccessG4InfoV_Tg504$s12e10Settings09gh40B8ProviderC11visibleAppsSay0A5Setup0cdC4I18VGyFSbAG_AGtXEfU2_Tf1nnncn_n
+ _$ss6_merge3low3mid4high6buffer2bySbSpyxG_A3GSbx_xtKXEtKlF9SiriSetup09AppAccessI4InfoV_Tg504$s12g10Settings09ij40B8ProviderC11visibleAppsSay0A5Setup0cdC4K18VGyFSbAG_AGtXEfU2_Tf1nnnnc_n
- _$s9SiriSetup30MainAssistantSettingsViewModelC09appAccessE9Providing13afPreferencesAcA03AppieJ0_p_So13AFPreferencesCSgtcfc
- _$sSMsSKRzrlE14_insertionSort6within9sortedEnd2byySny5IndexSlQzG_AFSb7ElementSTQz_AItKXEtKFSry9SiriSetup09AppAccessK4InfoVG_Tg504$s12i10Settings09kl40B8ProviderC11visibleAppsSay0A5Setup0cdC4M18VGyFSbAG_AGtXEfU1_Tf1nncn_n
- _$sSMsSkRzrlE4sort2byySb7ElementSTQz_ADtKXE_tKFs15ContiguousArrayVy9SiriSetup09AppAccessH4InfoVG_Tg504$s12f10Settings09hi40B8ProviderC11visibleAppsSay0A5Setup0cdC4J18VGyFSbAG_AGtXEfU1_Tf1cn_n
- _$sSr13_mergeTopRuns_6buffer2bySbSaySnySiGGz_SpyxGSbx_xtKXEtKF9SiriSetup09AppAccessH4InfoV_Tg504$s12f10Settings09hi40B8ProviderC11visibleAppsSay0A5Setup0cdC4J18VGyFSbAG_AGtXEfU1_Tf1nncn_n
- _$sSr15_stableSortImpl2byySbx_xtKXE_tKF9SiriSetup09AppAccessG4InfoV_Tg504$s12e10Settings09gh40B8ProviderC11visibleAppsSay0A5Setup0cdC4I18VGyFSbAG_AGtXEfU1_Tf1cn_n
- _$sSr15_stableSortImpl2byySbx_xtKXE_tKFySryxGz_SiztKXEfU_9SiriSetup09AppAccessG4InfoV_Tg504$s12e10Settings09gh40B8ProviderC11visibleAppsSay0A5Setup0cdC4I18VGyFSbAG_AGtXEfU1_Tf1nnncn_n
- _$ss6_merge3low3mid4high6buffer2bySbSpyxG_A3GSbx_xtKXEtKlF9SiriSetup09AppAccessI4InfoV_Tg504$s12g10Settings09ij40B8ProviderC11visibleAppsSay0A5Setup0cdC4K18VGyFSbAG_AGtXEfU1_Tf1nnnnc_n
CStrings:
+ "ShouldShowCallSuggestions"
+ "com.apple.facetime"
- "linwood_voices"
```
