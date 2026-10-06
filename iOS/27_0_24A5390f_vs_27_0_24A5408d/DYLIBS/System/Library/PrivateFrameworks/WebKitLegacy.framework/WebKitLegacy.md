## WebKitLegacy

> `/System/Library/PrivateFrameworks/WebKitLegacy.framework/WebKitLegacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16533c` | `0x1651c8` | **`-0x174`** |
| `__TEXT.__cstring` | `0x1ca1e` | `0x1c8d9` | **`-0x145`** |
| `__AUTH_CONST.__cfstring` | `0xf700` | `0xf600` | **`-0x100`** |
| `__AUTH_CONST.__const` | `0x5348` | `0x5370` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x1320c` | `0x13200` | **`-0xc`** |

### Other Changes

```diff

-625.1.24.10.1
+625.1.29.10.3

-  Functions: 7318
-  Symbols:   13077
-  CStrings:  2315
+  Functions: 7319
+  Symbols:   13080
+  CStrings:  2307
Symbols:
+ GCC_except_table212
+ GCC_except_table227
+ GCC_except_table229
+ GCC_except_table232
+ GCC_except_table238
+ GCC_except_table241
+ GCC_except_table258
+ GCC_except_table269
+ GCC_except_table276
+ GCC_except_table283
+ GCC_except_table296
+ GCC_except_table299
+ GCC_except_table311
+ GCC_except_table314
+ GCC_except_table326
+ GCC_except_table329
+ GCC_except_table349
+ GCC_except_table362
+ GCC_except_table376
+ GCC_except_table384
+ GCC_except_table391
+ GCC_except_table395
+ GCC_except_table401
+ GCC_except_table409
+ GCC_except_table416
+ GCC_except_table418
+ GCC_except_table429
+ GCC_except_table439
+ GCC_except_table442
+ GCC_except_table453
+ GCC_except_table456
+ GCC_except_table468
+ GCC_except_table475
+ GCC_except_table485
+ GCC_except_table547
+ GCC_except_table549
+ GCC_except_table604
+ GCC_except_table606
+ GCC_except_table617
+ GCC_except_table629
+ __ZN20WebFrameLoaderClient34dispatchGoToBackForwardItemAtIndexEiN7WebCore13FrameLoadTypeE
+ __ZN7WebCore12ChromeClient20transcodeChosenFilesEON3WTF6VectorINS1_6StringELm0ENS1_15CrashOnOverflowELm16ENS1_10FastMallocEEEOS3_S8_ONS1_17CompletionHandlerIFvS7_EEE
+ __ZN7WebCore12ChromeClient26showWritingToolsAffordanceEv
+ __ZNK7WebCore12ChromeClient21writingToolsAvailableEv
- GCC_except_table225
- GCC_except_table230
- GCC_except_table236
- GCC_except_table239
- GCC_except_table264
- GCC_except_table270
- GCC_except_table274
- GCC_except_table284
- GCC_except_table292
- GCC_except_table298
- GCC_except_table300
- GCC_except_table310
- GCC_except_table327
- GCC_except_table342
- GCC_except_table364
- GCC_except_table383
- GCC_except_table385
- GCC_except_table388
- GCC_except_table394
- GCC_except_table397
- GCC_except_table413
- GCC_except_table415
- GCC_except_table417
- GCC_except_table430
- GCC_except_table440
- GCC_except_table444
- GCC_except_table447
- GCC_except_table455
- GCC_except_table465
- GCC_except_table469
- GCC_except_table477
- GCC_except_table482
- GCC_except_table486
- GCC_except_table548
- GCC_except_table551
- GCC_except_table605
- GCC_except_table607
- GCC_except_table618
- GCC_except_table630
- __ZN20WebFrameLoaderClient34dispatchGoToBackForwardItemAtIndexEi
- __ZN20WebFrameLoaderClient36dispatchEnqueueHistoryTraversalDeltaEi
Functions:
- __ZN20WebFrameLoaderClient36dispatchEnqueueHistoryTraversalDeltaEi
~ -[WebView(WebPrivate) setSelectTrailingWhitespaceEnabled:] : 76 -> 68
~ __ZN7WebCore20CacheStorageProvider28createCacheStorageConnectionEv : 84 -> 88
+ __ZNK7WebCore12ChromeClient21writingToolsAvailableEv
+ __ZN7WebCore12ChromeClient33hasActiveNowPlayingSessionChangedEb
~ +[WebPreferences initialize] : 13076 -> 13052
~ +[WebPreferences(WebPrivateExperimentalFeatures) _experimentalFeatures] : 25264 -> 25016
~ -[WebView(WebViewInternalPreferencesChangedGenerated) _preferencesChangedGenerated:] : 24060 -> 23956
CStrings:
- "Enable Global Privacy Control (GPC) Feature"
- "Expose the status of Global Privacy Control (GPC) API (navigtor.gloabalPrivacyControl)"
- "Global Privacy Control API"
- "Global Privacy Control Feature"
- "GlobalPrivacyControlFeatureEnabled"
- "GlobalPrivacyControlStatus"
- "WebKitGlobalPrivacyControlFeatureEnabled"
- "WebKitGlobalPrivacyControlStatus"
```
