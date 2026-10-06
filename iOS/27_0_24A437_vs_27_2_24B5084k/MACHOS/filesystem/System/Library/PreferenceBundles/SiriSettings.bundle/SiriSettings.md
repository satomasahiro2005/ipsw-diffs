## SiriSettings

> `/System/Library/PreferenceBundles/SiriSettings.bundle/SiriSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfa3c` | `0xff98` | **`+0x55c`** |
| `__DATA.__bss` | `0x8a0` | `0x730` | **`-0x170`** |
| `__DATA.__objc_const` | `0x5f0` | `0x6a0` | **`+0xb0`** |
| `__DATA_CONST.__cfstring` | `0x140` | `0x1e0` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x6e0` | `0x780` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x840` | `0x7c0` | **`-0x80`** |
| `__TEXT.__const` | `0x878` | `0x7f8` | **`-0x80`** |
| `__TEXT.__swift5_reflstr` | `0x156` | `0xe6` | **`-0x70`** |
| `__TEXT.__auth_stubs` | `0xcf0` | `0xd50` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x17c` | `0x124` | **`-0x58`** |
| `__DATA.__objc_data` | `0xa0` | `0xf0` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x745` | `0x795` | **`+0x50`** |
| `__TEXT.__dlopen_cstrs` | `0x64` | `0xae` | **`+0x4a`** |
| `__TEXT.__cstring` | `0x55f` | `0x59f` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x172` | `0x1b2` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x688` | `0x6b8` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x260` | `0x288` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x10` | `0x38` | **`+0x28`** |
| `__DATA.__data` | `0x680` | `0x6a0` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x290` | `0x2b0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x174` | `0x194` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x13c` | `0x14c` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x2a9` | `0x29b` | **`-0xe`** |
| `__TEXT.__swift5_proto` | `0x44` | `0x38` | **`-0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x3d0` | `0x3d4` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x38` | `0x34` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.62.43.11.103
+3605.24.1.1.2

-  - /usr/lib/swift/libswiftSpriteKit.dylib

-  Functions: 389
-  Symbols:   1259
-  CStrings:  171
+  Functions: 370
+  Symbols:   1262
+  CStrings:  181
Symbols:
+ +[SRSAppClipsSearchVisibility isShowInSearchEnabled]
+ +[SRSAppClipsSearchVisibility setShowInSearchEnabled:]
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/SiriSetup/install/TempContent/Objects/SiriSetup.build/SiriSettings.build/Objects-normal/arm64e/SRSAppClipsSearchVisibility.o
+ GCC_except_table1
+ GCC_except_table2
+ PSSPGetDisabledBundleSet
+ SRSAppClipsSearchVisibility.m
+ SearchLibraryCore.frameworkLibrary
+ _$s12SiriSettings0A16SetupFeatureFlagOwetTm
+ _$s12SiriSettings0A16SetupFeatureFlagOwstTm
+ _$s12SiriSettings19SuggestionsProviderC0A5Setup0C9ProvidingAadEP24isSuggestAppClipsEnabledSbyFTW
+ _$s12SiriSettings19SuggestionsProviderC0A5Setup0C9ProvidingAadEP25setSuggestAppClipsEnabledyySbFTW
+ _$s12SiriSettings19SuggestionsProviderC0A5Setup0C9ProvidingAadEP29isShowAppClipsInSearchEnabledSbyFTW
+ _$s12SiriSettings19SuggestionsProviderC0A5Setup0C9ProvidingAadEP30setShowAppClipsInSearchEnabledyySbFTW
+ _$s12SiriSettings19SuggestionsProviderC24isSuggestAppClipsEnabledSbyF
+ _$s12SiriSettings19SuggestionsProviderC24isSuggestAppClipsEnabledSbyFTq
+ _$s12SiriSettings19SuggestionsProviderC25setSuggestAppClipsEnabledyySbF
+ _$s12SiriSettings19SuggestionsProviderC25setSuggestAppClipsEnabledyySbFTq
+ _$s12SiriSettings19SuggestionsProviderC29isShowAppClipsInSearchEnabledSbyF
+ _$s12SiriSettings19SuggestionsProviderC29isShowAppClipsInSearchEnabledSbyFTq
+ _$s12SiriSettings19SuggestionsProviderC30setShowAppClipsInSearchEnabledyySbF
+ _$s12SiriSettings19SuggestionsProviderC30setShowAppClipsInSearchEnabledyySbFTq
+ _$s12SiriSettings22RestrictAccessProviderC10controller33_66C4B3A0C06B7EB3D990F0393DAFD9F8LLypSgvpWvd
+ _$s12SiriSettings22RestrictAccessProviderC10controller33_66C4B3A0C06B7EB3D990F0393DAFD9F8LLypSgvpfi
+ _$s9SiriSetup20SuggestionsProvidingP24isSuggestAppClipsEnabledSbyFTq
+ _$s9SiriSetup20SuggestionsProvidingP25setSuggestAppClipsEnabledyySbFTq
+ _$s9SiriSetup20SuggestionsProvidingP29isShowAppClipsInSearchEnabledSbyFTq
+ _$s9SiriSetup20SuggestionsProvidingP30setShowAppClipsInSearchEnabledyySbFTq
+ _$s9SiriSetup21RestrictAccessAppInfoV16appClipsBundleIDSSvgZ
+ _$s9SiriSetup21RestrictAccessAppInfoV8appClipsACvgZ
+ _CFPreferencesAppSynchronize
+ _OBJC_CLASS_$_SRSAppClipsSearchVisibility
+ _OBJC_METACLASS_$_SRSAppClipsSearchVisibility
+ _PSSPGetDisabledBundleSet
+ _SearchLibrary
+ __OBJC_$_CLASS_METHODS_SRSAppClipsSearchVisibility
+ __OBJC_CLASS_RO_$_SRSAppClipsSearchVisibility
+ __OBJC_METACLASS_RO_$_SRSAppClipsSearchVisibility
+ ___SearchLibraryCore_block_invoke
+ ___getSPGetDisabledAppSetSymbolLoc_block_invoke
+ ___getSPGetDisabledBundleSetSymbolLoc_block_invoke
+ _audit_stringSearch
+ _dlerror
+ _dlsym
+ _objc_msgSend$allObjects
+ _objc_msgSend$containsObject:
+ _objc_msgSend$isShowInSearchEnabled
+ _objc_msgSend$removeObject:
+ _objc_msgSend$setShowInSearchEnabled:
+ _swift_release_x27
+ getSPGetDisabledAppSetSymbolLoc.ptr
+ getSPGetDisabledBundleSetSymbolLoc.ptr
- _$s12SiriSettings0A11FeatureFlagO9hashValueSivgTm
- _$s12SiriSettings0A11FeatureFlagO9isEnabledSbvgTm
- _$s12SiriSettings0A11FeatureFlagOSHAASH13_rawHashValue4seedS2i_tFTWTm
- _$s12SiriSettings0A11FeatureFlagOSHAASH9hashValueSivgTWTm
- _$s12SiriSettings0A11FeatureFlagOwetTm
- _$s12SiriSettings0A11FeatureFlagOwstTm
- _$s12SiriSettings0A21TTSServiceFeatureFlagO0D5Flags0dF3KeyAAMc
- _$s12SiriSettings0A21TTSServiceFeatureFlagO0D5Flags0dF3KeyAAMcMK
- _$s12SiriSettings0A21TTSServiceFeatureFlagO0D5Flags0dF3KeyAadEP6domains12StaticStringVvgTW
- _$s12SiriSettings0A21TTSServiceFeatureFlagO0D5Flags0dF3KeyAadEP7features12StaticStringVvgTW
- _$s12SiriSettings0A21TTSServiceFeatureFlagO21__derived_enum_equalsySbAC_ACtFZ
- _$s12SiriSettings0A21TTSServiceFeatureFlagO4hash4intoys6HasherVz_tF
- _$s12SiriSettings0A21TTSServiceFeatureFlagO6domains12StaticStringVvg
- _$s12SiriSettings0A21TTSServiceFeatureFlagO6domains12StaticStringVvpMV
- _$s12SiriSettings0A21TTSServiceFeatureFlagO7features12StaticStringVvg
- _$s12SiriSettings0A21TTSServiceFeatureFlagO7features12StaticStringVvpMV
- _$s12SiriSettings0A21TTSServiceFeatureFlagO9hashValueSivg
- _$s12SiriSettings0A21TTSServiceFeatureFlagO9hashValueSivpMV
- _$s12SiriSettings0A21TTSServiceFeatureFlagO9isEnabledSbvg
- _$s12SiriSettings0A21TTSServiceFeatureFlagO9isEnabledSbvpMV
- _$s12SiriSettings0A21TTSServiceFeatureFlagOAC0D5Flags0dF3KeyAAWL
- _$s12SiriSettings0A21TTSServiceFeatureFlagOAC0D5Flags0dF3KeyAAWl
- _$s12SiriSettings0A21TTSServiceFeatureFlagOACSQAAWL
- _$s12SiriSettings0A21TTSServiceFeatureFlagOACSQAAWl
- _$s12SiriSettings0A21TTSServiceFeatureFlagOMF
- _$s12SiriSettings0A21TTSServiceFeatureFlagOMa
- _$s12SiriSettings0A21TTSServiceFeatureFlagOMf
- _$s12SiriSettings0A21TTSServiceFeatureFlagOMn
- _$s12SiriSettings0A21TTSServiceFeatureFlagON
- _$s12SiriSettings0A21TTSServiceFeatureFlagOSHAAMc
- _$s12SiriSettings0A21TTSServiceFeatureFlagOSHAAMcMK
- _$s12SiriSettings0A21TTSServiceFeatureFlagOSHAASH13_rawHashValue4seedS2i_tFTW
- _$s12SiriSettings0A21TTSServiceFeatureFlagOSHAASH4hash4intoys6HasherVz_tFTW
- _$s12SiriSettings0A21TTSServiceFeatureFlagOSHAASH9hashValueSivgTW
- _$s12SiriSettings0A21TTSServiceFeatureFlagOSHAASQWb
- _$s12SiriSettings0A21TTSServiceFeatureFlagOSQAAMc
- _$s12SiriSettings0A21TTSServiceFeatureFlagOSQAAMcMK
- _$s12SiriSettings0A21TTSServiceFeatureFlagOSQAASQ2eeoiySbx_xtFZTW
- _$s12SiriSettings0A21TTSServiceFeatureFlagOWV
- _$s12SiriSettings0A21TTSServiceFeatureFlagOwet
- _$s12SiriSettings0A21TTSServiceFeatureFlagOwst
- _$s12SiriSettings0A21TTSServiceFeatureFlagOwug
- _$s12SiriSettings0A21TTSServiceFeatureFlagOwui
- _$s12SiriSettings0A21TTSServiceFeatureFlagOwup
- ___swift_memcpy1_1
- __swift_FORCE_LOAD_$_swiftSpriteKit
- __swift_FORCE_LOAD_$_swiftSpriteKit_$_SiriSettings
- _associated conformance 12SiriSettings0A21TTSServiceFeatureFlagOSHAASQ
- _symbolic _____ 12SiriSettings0A21TTSServiceFeatureFlagO
CStrings:
+ "LFTA sync %s canLearn=false"
+ "LFTA sync %s canLearn=true"
+ "SBSearchDisabledApps"
+ "SBSearchDisabledBundles"
+ "SPGetDisabledAppSet"
+ "SPGetDisabledBundleSet"
+ "SRSAppClipsSearchVisibility"
+ "SuggestionsSuggestAppClips"
+ "allObjects"
+ "com.apple.app-clips"
+ "com.apple.spotlightui"
+ "com.apple.spotlightui.prefschanged"
+ "containsObject:"
+ "isShowInSearchEnabled"
+ "removeObject:"
+ "setShowInSearchEnabled:"
+ "softlink:r:path:/System/Library/PrivateFrameworks/Search.framework/Search"
+ "v20@0:8B16"
- "Linwood"
- "SiriTTSService"
- "audio_accessories_iOS"
- "buddy_iOS"
- "custom_voice_preset"
- "linwood_voices_seed"
- "settings_iOS"
- "settings_macOS"
```
