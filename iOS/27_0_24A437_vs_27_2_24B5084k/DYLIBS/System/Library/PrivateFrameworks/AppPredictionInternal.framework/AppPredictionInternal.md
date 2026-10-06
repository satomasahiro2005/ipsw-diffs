## AppPredictionInternal

> `/System/Library/PrivateFrameworks/AppPredictionInternal.framework/AppPredictionInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48ecb8` | `0x48f7c8` | **`+0xb10`** |
| `__TEXT.__oslogstring` | `0x3bb49` | `0x3bcc9` | **`+0x180`** |
| `__AUTH_CONST.__cfstring` | `0x3b240` | `0x3b2c0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x38eac` | `0x38f2c` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x1bf80` | `0x1bfe0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x596b2` | `0x59712` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x83ba0` | `0x83be8` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0xe640` | `0xe668` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x8d58` | `0x8d38` | **`-0x20`** |
| `__DATA.__bss` | `0x2918` | `0x2928` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x21d8` | `0x21e0` | **`+0x8`** |

### Other Changes

```diff

-671.0.2.0.1
+674.0.1.0.0

-  Functions: 25705
-  Symbols:   36750
-  CStrings:  12400
+  Functions: 25714
+  Symbols:   36763
+  CStrings:  12407
Symbols:
+ +[ATXHeroDataServerHelper anyHeroPredictionsAreEligibleGivenIsMoving:isNearKnownTypeLOI:isNearKnownTypeLOIExcludingGym:isNearFrequentLOI:]
+ +[ATXHeroDataServerHelper canPredictClipsGivenRecentMotionWithContext:]
+ +[ATXHeroDataServerHelper heroAppAndClipPredictionsAreEligibleGivenIsMoving:isNearKnownTypeLOI:isNearFrequentLOI:]
+ +[ATXHeroDataServerHelper heroPoiPredictionsAreEligibleGivenIsMoving:isNearKnownTypeLOIExcludingGym:]
+ +[ATXHeroDataServerHelper isNearKnownTypeLocationOfInterest:]
+ +[ATXHeroDataServerHelper isNearKnownTypeLocationOfInterestExcludingGym:]
+ +[_ATXDataStore histogramTypeForString:found:]
+ -[ATXCDNDownloaderTriggerManager _anyHeroPredictionsAreEligible]
+ -[ATXStackStateTracker internalStateFromDisk]
+ -[_ATXInspectionClient launchCountForBundleId:inHistogramNamed:reply:]
+ -[_ATXInspectionServer launchCountForBundleId:inHistogramNamed:reply:]
+ _ATXLanguageChangeIsAwaitingRestart
+ __ATXLanguageChangeObservedTime
+ ___70-[_ATXInspectionClient launchCountForBundleId:inHistogramNamed:reply:]_block_invoke
+ ___block_descriptor_40_e49_v24?0"ATXFaceGalleryConfiguration"8"NSError"16l
+ _clock_gettime_nsec_np
- -[ATXHeroDataServer heroAppAndClipPredictionsAreEligibleGivenIsMoving:isNearKnownTypeLOI:isNearFrequentLOI:]
- -[ATXHeroDataServer heroPoiPredictionsAreEligibleGivenIsMoving:isNearKnownTypeLOIExcludingGym:isNearFrequentLOI:]
- ___block_descriptor_32_e49_v24?0"ATXFaceGalleryConfiguration"8"NSError"16l
CStrings:
+ "%@ is deprecated and no longer records launches."
+ "%@ is not a known _ATXHistogramType. Use `atxtool histograms show-all-by-size` to see the valid names."
+ "%s: [role=%lu] deferring generation: awaiting restart after language change"
+ "%s: [role=%lu] localization mismatch: section titles resolve in '%{public}@' but the configuration is stamped '%{public}@'; gallery strings are stale"
+ "%s: [role=%lu] using locale: %{public}@ (bundle localization: %{public}@, preferred language: %{public}@)"
+ "%{public}s: Could not unarchive internal state (unarchiveErr %@, internalState %@)"
+ "%{public}s: No internal state read from disk (dataFromDisk is nil)"
+ "-[ATXStackStateTracker internalStateFromDisk]"
+ "Could not instantiate a histogram of type %@."
+ "Defaults for OverrideHeroAppPredictionEligibility set to True: treating hero predictions as eligible."
+ "FaceSuggestionAssetParametersAmbient_iOS"
+ "Skipping CDN download since no hero prediction type is eligible here. Clearing predictions."
+ "error regenerating gallery for role %ld after process restart due to language change: %@"
+ "launchCountForBundleId"
+ "successfully regenerated gallery for role %ld after process restart due to language change"
- "%s: no section order provided in ambient asset parameters, or asset parameters missing!"
- "%s: using locale: %@"
- "%{public}s: Using empty internal state because loadInternalState failed (dataFromDisk is nil)"
- "%{public}s: Using empty internal state because loadInternalState failed (unarchiveErr %@, internalState %@)"
- "-[ATXFaceGalleryLayoutGenerator _ambientFaceGallerySectionsWithWidgetDescriptorsAdditionalData:aggregatedAppLaunchData:bundleIdToCompanionBundleId:ambientParameters:]"
- "FaceSuggestionAssetParametersAmbient"
- "error regenerating gallery after process restart due to language change: %@"
- "successfully regenerated gallery after process restart due to language change"
```
