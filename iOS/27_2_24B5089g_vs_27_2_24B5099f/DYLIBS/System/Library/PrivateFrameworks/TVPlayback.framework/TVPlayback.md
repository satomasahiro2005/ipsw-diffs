## TVPlayback

> `/System/Library/PrivateFrameworks/TVPlayback.framework/TVPlayback`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6a888` | `0x6adf0` | **`+0x568`** |
| `__AUTH_CONST.__objc_const` | `0x9c80` | `0x9d40` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x6118` | `0x61b0` | **`+0x98`** |
| `__DATA_CONST.__objc_selrefs` | `0x3eb8` | `0x3f10` | **`+0x58`** |
| `__TEXT.__cstring` | `0x6ba3` | `0x6bed` | **`+0x4a`** |
| `__TEXT.__unwind_info` | `0x1720` | `0x1738` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x7d8` | `0x7e8` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x7253` | `0x725f` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x448` | `0x450` | **`+0x8`** |

### Other Changes

```diff

-635.10.11.0.0
+635.10.14.0.0

-  Functions: 2313
-  Symbols:   4260
-  CStrings:  1468
+  Functions: 2326
+  Symbols:   4278
+  CStrings:  1469
Symbols:
+ +[TVPPlayer _downloadedOptionsInGroup:ofAsset:]
+ +[TVPPlayer _updateVideoSelectionCriteriaForAVQueuePlayer:isInterstitialPlayer:preferredSignLanguage:]
+ +[TVPPlayer savedPreferredSignLanguage]
+ -[TVPPlayer _downloadedSignLanguageOptions]
+ -[TVPPlayer _effectiveSignLanguage]
+ -[TVPPlayer _signLanguageForSelectionCriteria]
+ -[TVPPlayer allowsSignLanguageSelection]
+ -[TVPPlayer preferredSignLanguage]
+ -[TVPPlayer setAllowsSignLanguageSelection:]
+ -[TVPPlayer setPreferredSignLanguage:]
+ -[TVPPlayer setSignLanguageChosenByViewer:]
+ -[TVPPlayer signLanguageChosenByViewer]
+ -[TVPVideoOption initWithOption:isDefault:isDownloaded:]
+ -[TVPVideoOption isDownloaded]
+ -[TVPVideoOption setIsDownloaded:]
+ GCC_except_table241
+ GCC_except_table247
+ GCC_except_table251
+ GCC_except_table254
+ GCC_except_table303
+ GCC_except_table333
+ GCC_except_table349
+ GCC_except_table371
+ GCC_except_table375
+ GCC_except_table384
+ GCC_except_table395
+ GCC_except_table414
+ GCC_except_table430
+ GCC_except_table431
+ GCC_except_table434
+ GCC_except_table439
+ GCC_except_table442
+ GCC_except_table446
+ GCC_except_table450
+ GCC_except_table455
+ GCC_except_table460
+ GCC_except_table462
+ GCC_except_table464
+ GCC_except_table489
+ GCC_except_table491
+ GCC_except_table493
+ GCC_except_table502
+ GCC_except_table509
+ GCC_except_table511
+ GCC_except_table513
+ GCC_except_table518
+ GCC_except_table528
+ GCC_except_table536
+ GCC_except_table539
+ GCC_except_table551
+ GCC_except_table553
+ GCC_except_table556
+ GCC_except_table560
+ _OBJC_IVAR_$_TVPPlayer._allowsSignLanguageSelection
+ _OBJC_IVAR_$_TVPPlayer._preferredSignLanguage
+ _OBJC_IVAR_$_TVPPlayer._signLanguageChosenByViewer
+ _OBJC_IVAR_$_TVPVideoOption._isDownloaded
+ _TVPSignLanguageDownloadLanguage
+ _notify_post
- +[TVPPlayer _updateVideoSelectionCriteriaForAVQueuePlayer:isInterstitialPlayer:]
- -[TVPVideoOption initWithOption:isDefault:]
- GCC_except_table239
- GCC_except_table245
- GCC_except_table249
- GCC_except_table252
- GCC_except_table301
- GCC_except_table331
- GCC_except_table343
- GCC_except_table365
- GCC_except_table369
- GCC_except_table378
- GCC_except_table389
- GCC_except_table408
- GCC_except_table415
- GCC_except_table416
- GCC_except_table418
- GCC_except_table419
- GCC_except_table436
- GCC_except_table440
- GCC_except_table444
- GCC_except_table449
- GCC_except_table454
- GCC_except_table456
- GCC_except_table458
- GCC_except_table483
- GCC_except_table485
- GCC_except_table487
- GCC_except_table490
- GCC_except_table503
- GCC_except_table505
- GCC_except_table507
- GCC_except_table512
- GCC_except_table516
- GCC_except_table530
- GCC_except_table533
- GCC_except_table545
- GCC_except_table547
- GCC_except_table550
- GCC_except_table554
- _TVPSignLanguageSetSettingEnabled
CStrings:
+ "%@ isDefault: %@ isDownloaded: %@"
+ "Not the same show; clearing the preferred sign language"
+ "PreferredSignLanguageDownload"
+ "com.apple.AppleTV.signLanguageSettingDidChange"
- "%@ isDefault: %@"
- "Setting prefs for video language code to %@"
- "SignLanguageEnabled"
```
