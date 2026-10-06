## Translation

> `/System/Library/Frameworks/Translation.framework/Translation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c160` | `0x5cb08` | **`+0x9a8`** |
| `__AUTH_CONST.__objc_const` | `0xbde0` | `0xc0f8` | **`+0x318`** |
| `__TEXT.__oslogstring` | `0x5176` | `0x5306` | **`+0x190`** |
| `__TEXT.__objc_methlist` | `0x5cb0` | `0x5e10` | **`+0x160`** |
| `__AUTH_CONST.__cfstring` | `0x3c80` | `0x3d60` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x33b4` | `0x3414` | **`+0x60`** |
| `__AUTH.__objc_data` | `0xe8` | `0x138` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x2850` | `0x2898` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x1010` | `0x1050` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x8b0` | `0x8e0` | **`+0x30`** |
| `__DATA_CONST.__objc_arraydata` | `0x178` | `0x1a0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1c50` | `0x1c78` | **`+0x28`** |
| `__DATA.__bss` | `0x1070` | `0x1090` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0xd8` | `0xf0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x598` | `0x5a0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x328` | `0x330` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x2a8` | `0x2b0` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xb3c` | `0xb44` | **`+0x8`** |

### Other Changes

```diff

-385.0.0.0.0
+388.0.0.0.0

-  Functions: 2861
-  Symbols:   4346
-  CStrings:  931
+  Functions: 2896
+  Symbols:   4408
+  CStrings:  944
Symbols:
+ +[_LTLanguageVariantFilter _hiRequestedLanguageIdentifiers]
+ -[_LTCombinedTranslationResult engineInfo]
+ -[_LTLanguageVariantFilter deviceRegionForFilter:]
+ -[_LTTextResult engineInfo]
+ -[_LTTextResult initWithLocalePair:sourceAttributedText:targetAttributedText:clientIdentifier:engineInfo:]
+ -[_LTTextResult initWithLocalePair:sourceText:targetText:clientIdentifier:engineInfo:]
+ -[_LTTextSession _initWithConfiguration:]
+ -[_LTTextSession configuration]
+ -[_LTTextSession initWithConfiguration:]
+ -[_LTTextSession originatingProcessIdentifier]
+ -[_LTTextSessionConfiguration .cxx_destruct]
+ -[_LTTextSessionConfiguration copyWithZone:]
+ -[_LTTextSessionConfiguration init]
+ -[_LTTextSessionConfiguration isHeadless]
+ -[_LTTextSessionConfiguration originatingProcessIdentifier]
+ -[_LTTextSessionConfiguration preferredStrategy]
+ -[_LTTextSessionConfiguration setIsHeadless:]
+ -[_LTTextSessionConfiguration setOriginatingProcessIdentifier:]
+ -[_LTTextSessionConfiguration setPreferredStrategy:]
+ -[_LTTextSessionConfiguration setSourceLocale:]
+ -[_LTTextSessionConfiguration setTargetLocale:]
+ -[_LTTextSessionConfiguration sourceLocale]
+ -[_LTTextSessionConfiguration targetLocale]
+ -[_LTTranslationContext originatingProcessIdentifier]
+ -[_LTTranslationContext setOriginatingProcessIdentifier:]
+ -[_LTTranslationRequest originatingProcessIdentifier]
+ -[_LTTranslationRequest setOriginatingProcessIdentifier:]
+ -[_LTTranslationResult engineInfo]
+ -[_LTTranslationResult setEngineInfo:]
+ GCC_except_table131
+ GCC_except_table36
+ GCC_except_table37
+ GCC_except_table47
+ GCC_except_table55
+ GCC_except_table56
+ GCC_except_table65
+ GCC_except_table68
+ GCC_except_table72
+ GCC_except_table75
+ _OBJC_CLASS_$__LTTextSessionConfiguration
+ _OBJC_IVAR_$__LTCombinedTranslationResult._engineInfo
+ _OBJC_IVAR_$__LTTextResult._engineInfo
+ _OBJC_IVAR_$__LTTextSession._configuration
+ _OBJC_IVAR_$__LTTextSession._originatingProcessIdentifier
+ _OBJC_IVAR_$__LTTextSessionConfiguration._isHeadless
+ _OBJC_IVAR_$__LTTextSessionConfiguration._originatingProcessIdentifier
+ _OBJC_IVAR_$__LTTextSessionConfiguration._preferredStrategy
+ _OBJC_IVAR_$__LTTextSessionConfiguration._sourceLocale
+ _OBJC_IVAR_$__LTTextSessionConfiguration._targetLocale
+ _OBJC_IVAR_$__LTTranslationContext._originatingProcessIdentifier
+ _OBJC_IVAR_$__LTTranslationRequest._originatingProcessIdentifier
+ _OBJC_IVAR_$__LTTranslationResult._engineInfo
+ _OBJC_METACLASS_$__LTTextSessionConfiguration
+ __LTOSLogVariantFiltering
+ __LTOSLogVariantFiltering.log
+ __LTOSLogVariantFiltering.onceToken
+ __LTSupportedLocaleDefaultLIDLanguageMapping
+ __LTSupportedLocaleDefaultLIDLanguageMapping.mapping
+ __LTSupportedLocaleDefaultLIDLanguageMapping.onceToken
+ __OBJC_$_CLASS_METHODS__LTLanguageVariantFilter
+ __OBJC_$_CLASS_PROP_LIST__LTLanguageVariantFilter
+ __OBJC_$_INSTANCE_METHODS__LTTextSessionConfiguration
+ __OBJC_$_INSTANCE_VARIABLES__LTTextSessionConfiguration
+ __OBJC_$_PROP_LIST__LTTextSessionConfiguration
+ __OBJC_CLASS_PROTOCOLS_$__LTTextSessionConfiguration
+ __OBJC_CLASS_RO_$__LTTextSessionConfiguration
+ __OBJC_METACLASS_RO_$__LTTextSessionConfiguration
+ ____LTOSLogVariantFiltering_block_invoke
+ ____LTSupportedLocaleDefaultLIDLanguageMapping_block_invoke
- -[_LTTextResult initWithLocalePair:sourceAttributedText:targetAttributedText:clientIdentifier:]
- -[_LTTextResult initWithLocalePair:sourceText:targetText:clientIdentifier:]
- GCC_except_table129
- GCC_except_table63
- GCC_except_table66
- GCC_except_table70
- GCC_except_table73
CStrings:
+ "Debug setting to prevent language variant filtering enabled. Will show all supported variants in UI"
+ "Filtered %zu supported languages into %zu to display"
+ "NSLocale.currentLocale.regionCode: %{public}@"
+ "NSLocale.preferredLanguages: %{public}@"
+ "Not creating _LTCombinedTranslationResult instance because a translation result has engineInfo %zd, which is mismatched from other results with engineInfo %zd"
+ "VariantFiltering"
+ "ar"
+ "ar_AE"
+ "de_AT"
+ "engineInfo"
+ "nl"
+ "nl_NL"
+ "originatingProcessIdentifier"
+ "\xc2"
- "\xa2"
```
