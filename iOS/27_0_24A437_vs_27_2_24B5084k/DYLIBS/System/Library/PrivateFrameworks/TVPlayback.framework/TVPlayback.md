## TVPlayback

> `/System/Library/PrivateFrameworks/TVPlayback.framework/TVPlayback`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68e2c` | `0x6a888` | **`+0x1a5c`** |
| `__TEXT.__oslogstring` | `0x7016` | `0x7253` | **`+0x23d`** |
| `__AUTH_CONST.__objc_const` | `0x9aa8` | `0x9c80` | **`+0x1d8`** |
| `__TEXT.__objc_methlist` | `0x5fb0` | `0x6118` | **`+0x168`** |
| `__AUTH_CONST.__cfstring` | `0x6c80` | `0x6da0` | **`+0x120`** |
| `__DATA_CONST.__objc_selrefs` | `0x3e08` | `0x3eb8` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x6b1f` | `0x6ba3` | **`+0x84`** |
| `__AUTH.__objc_data` | `0x870` | `0x8c0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x16d8` | `0x1720` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x680` | `0x6a0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x8d8` | `0x8f8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x430` | `0x448` | **`+0x18`** |
| `__DATA.__bss` | `0xa8` | `0xb8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x7cc` | `0x7d8` | **`+0xc`** |
| `__DATA_CONST.__objc_catlist` | `0x80` | `0x88` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1f8` | `0x200` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x170` | `0x178` | **`+0x8`** |

### Other Changes

```diff

-635.0.7.0.0
+635.10.11.0.0

-  Functions: 2276
-  Symbols:   4204
-  CStrings:  1449
+  Functions: 2313
+  Symbols:   4260
+  CStrings:  1468
Symbols:
+ +[AVMediaSelectionGroup(TVPSignLanguageAdditions) tvp_signLanguageOptionMatchingLanguage:inOptions:]
+ +[TVPPlayer _updateVideoSelectionCriteriaForAVQueuePlayer:isInterstitialPlayer:]
+ -[AVMediaSelectionGroup(TVPSignLanguageAdditions) tvp_signLanguageDownloadOption]
+ -[AVQueuePlayer(TVPAdditions) setTvp_cachedVideoSelectionCriteria:]
+ -[AVQueuePlayer(TVPAdditions) tvp_cachedVideoSelectionCriteria]
+ -[TVPPlayer _nextChapterInDirection:]
+ -[TVPPlayer _updateVideoSelectionCriteria]
+ -[TVPPlayer cachedSelectedVideoOption]
+ -[TVPPlayer canSkipToNextChapterInDirection:]
+ -[TVPPlayer selectedVideoOption]
+ -[TVPPlayer setCachedSelectedVideoOption:]
+ -[TVPPlayer setSelectedVideoOption:]
+ -[TVPPlayer videoOptions]
+ -[TVPVideoOption .cxx_destruct]
+ -[TVPVideoOption avMediaSelectionOption]
+ -[TVPVideoOption description]
+ -[TVPVideoOption extendedLanguageCode]
+ -[TVPVideoOption hasMediaCharacteristic:]
+ -[TVPVideoOption hasSignLanguage]
+ -[TVPVideoOption hash]
+ -[TVPVideoOption initWithOption:isDefault:]
+ -[TVPVideoOption isDefault]
+ -[TVPVideoOption isEqual:]
+ -[TVPVideoOption localizedDisplayString]
+ -[TVPVideoOption mediaCharacteristics]
+ -[TVPVideoOption setAvMediaSelectionOption:]
+ -[TVPVideoOption setIsDefault:]
+ GCC_except_table136
+ GCC_except_table239
+ GCC_except_table245
+ GCC_except_table249
+ GCC_except_table252
+ GCC_except_table301
+ GCC_except_table331
+ GCC_except_table343
+ GCC_except_table365
+ GCC_except_table369
+ GCC_except_table378
+ GCC_except_table389
+ GCC_except_table415
+ GCC_except_table418
+ GCC_except_table421
+ GCC_except_table422
+ GCC_except_table424
+ GCC_except_table427
+ GCC_except_table433
+ GCC_except_table440
+ GCC_except_table444
+ GCC_except_table449
+ GCC_except_table454
+ GCC_except_table456
+ GCC_except_table458
+ GCC_except_table483
+ GCC_except_table485
+ GCC_except_table487
+ GCC_except_table490
+ GCC_except_table496
+ GCC_except_table503
+ GCC_except_table505
+ GCC_except_table507
+ GCC_except_table512
+ GCC_except_table516
+ GCC_except_table530
+ GCC_except_table533
+ GCC_except_table545
+ GCC_except_table547
+ GCC_except_table550
+ GCC_except_table554
+ _AVMediaCharacteristicSignLanguageInterpretationForAccessibility
+ _AVMediaCharacteristicVisual
+ _CFPreferencesAppSynchronize
+ _CFPreferencesCopyAppValue
+ _CFPreferencesSetAppValue
+ _NSLocaleCountryCode
+ _OBJC_CLASS_$_TVPVideoOption
+ _OBJC_IVAR_$_TVPPlayer._cachedSelectedVideoOption
+ _OBJC_IVAR_$_TVPVideoOption._avMediaSelectionOption
+ _OBJC_IVAR_$_TVPVideoOption._isDefault
+ _OBJC_METACLASS_$_TVPVideoOption
+ _TVPSignLanguageCopyPreference
+ _TVPSignLanguageDefaultLanguageCode
+ _TVPSignLanguageDefaultLanguageCode.onceToken
+ _TVPSignLanguageDefaultLanguageCode.sDefaultLanguageCode
+ _TVPSignLanguagePreferredLanguage
+ _TVPSignLanguageSetPreferredLanguage
+ _TVPSignLanguageSetSettingEnabled
+ _TVPSignLanguageSettingEnabled
+ __OBJC_$_CATEGORY_AVMediaSelectionGroup_$_TVPSignLanguageAdditions
+ __OBJC_$_CATEGORY_CLASS_METHODS_AVMediaSelectionGroup_$_TVPSignLanguageAdditions
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_AVMediaSelectionGroup_$_TVPSignLanguageAdditions
+ __OBJC_$_INSTANCE_METHODS_TVPVideoOption
+ __OBJC_$_INSTANCE_VARIABLES_TVPVideoOption
+ __OBJC_$_PROP_LIST_AVMediaSelectionGroup_$_TVPSignLanguageAdditions
+ __OBJC_$_PROP_LIST_TVPVideoOption
+ __OBJC_CLASS_RO_$_TVPVideoOption
+ __OBJC_METACLASS_RO_$_TVPVideoOption
+ ___TVPSignLanguageDefaultLanguageCode_block_invoke
- GCC_except_table134
- GCC_except_table234
- GCC_except_table240
- GCC_except_table244
- GCC_except_table247
- GCC_except_table295
- GCC_except_table325
- GCC_except_table335
- GCC_except_table357
- GCC_except_table361
- GCC_except_table370
- GCC_except_table381
- GCC_except_table400
- GCC_except_table407
- GCC_except_table410
- GCC_except_table411
- GCC_except_table413
- GCC_except_table414
- GCC_except_table417
- GCC_except_table420
- GCC_except_table432
- GCC_except_table441
- GCC_except_table446
- GCC_except_table448
- GCC_except_table450
- GCC_except_table475
- GCC_except_table477
- GCC_except_table479
- GCC_except_table482
- GCC_except_table488
- GCC_except_table495
- GCC_except_table497
- GCC_except_table499
- GCC_except_table504
- GCC_except_table508
- GCC_except_table514
- GCC_except_table525
- GCC_except_table537
- GCC_except_table539
- GCC_except_table542
- GCC_except_table546
CStrings:
+ "%@ isDefault: %@"
+ "GB"
+ "Performing automatic re-selection of video for player item %@ in player %@"
+ "PreferredSignLanguage"
+ "Replacing default media selection with sign-language selection for %@"
+ "Selected video option: %@"
+ "Selecting video media option: %@"
+ "Setting cached video option from active player item %@ to %@."
+ "Setting prefs for video language code to %@"
+ "Setting visual media selection criteria on %@ (is interstitial player: %@) to %@"
+ "SignLanguageEnabled"
+ "Unable to load visual media selection group due to error %@"
+ "Video selection option is nil, not selecting"
+ "Will perform automatic re-selection of video for player item %@ in player %@"
+ "ase"
+ "bfi"
+ "com.apple.videos-preferences"
+ "selectedVideoOption"
+ "videoOptions"
```
