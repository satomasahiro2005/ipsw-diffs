## RawCamera

> `/System/Library/CoreServices/RawCamera.bundle/RawCamera`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22c298` | `0x23302c` | **`+0x6d94`** |
| `__TEXT.__gcc_except_tab` | `0x31a18` | `0x324b4` | **`+0xa9c`** |
| `__TEXT.__oslogstring` | `0x2880` | `0x2d42` | **`+0x4c2`** |
| `__TEXT.__cstring` | `0x12431` | `0x128f1` | **`+0x4c0`** |
| `__AUTH_CONST.__objc_const` | `0x6de8` | `0x7058` | **`+0x270`** |
| `__TEXT.__unwind_info` | `0xc6b0` | `0xc918` | **`+0x268`** |
| `__AUTH_CONST.__cfstring` | `0x1ae60` | `0x1b0c0` | **`+0x260`** |
| `__DATA_CONST.__const` | `0x2c30` | `0x2e38` | **`+0x208`** |
| `__TEXT.__objc_methlist` | `0x2424` | `0x25ac` | **`+0x188`** |
| `__DATA_CONST.__objc_selrefs` | `0x16e8` | `0x1830` | **`+0x148`** |
| `__AUTH_CONST.__const` | `0x3c5a8` | `0x3c648` | **`+0xa0`** |
| `__AUTH.__objc_data` | `0x12c0` | `0x1310` | **`+0x50`** |
| `__DATA.__bss` | `0x72e0` | `0x7310` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x5e8` | `0x614` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0xad8` | `0xae8` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x3b50` | `0x3b60` | **`+0x10`** |
| `__TEXT.__const` | `0x18634` | `0x18644` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x12a0` | `0x12a8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x240` | `0x248` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x130` | `0x138` | **`+0x8`** |

### Other Changes

```diff

-1821.22.1.0.0
+1821.40.4.0.0

-  Functions: 7753
-  Symbols:   984
-  CStrings:  4228
+  Functions: 7854
+  Symbols:   987
+  CStrings:  4294
Symbols:
+ _OBJC_CLASS_$_NSProgress
+ _RCModelDownloadStart
+ _objc_retain_x6
CStrings:
+ " (no model directory was resolved)"
+ "%@_v%d"
+ "%ld_v%d"
+ "%{public}s   raw MADownloadResult = %ld (%s)"
+ "%{public}s Failed to download V9 model asset for CFA class %ld (Err: %d)"
+ "%{public}s Failed to download model MobileAsset catalog (Err: %d)"
+ "%{public}s Failed to load the V9 ML demosaic model%s after waiting up to %.0fs for the Mobile Asset download; requesting decoder version 9 without it available."
+ "%{public}s Model MobileAsset catalog download successful"
+ "%{public}s Model MobileAsset catalog loaded after download."
+ "%{public}s Model MobileAsset catalog was updated."
+ "%{public}s Model MobileAsset query unsuccessful"
+ "%{public}s Prefetching V9 model asset for CFA class %ld"
+ "%{public}s RCMAAssetAttachProgress: MobileAsset not available or nil asset"
+ "%{public}s RCMAAssetQueryMetaDataSync: Result = %d (%s), raw MAQueryResult = %ld (%s)"
+ "%{public}s V9 model asset download successful for CFA class %ld"
+ "%{public}s V9 model for %@ not present on disk — %s, waiting up to %.0fs."
+ "%{public}s V9 model for %@: asset download failed — using fallback."
+ "%{public}s V9 model for %@: download complete — model now available."
+ "%{public}s V9 model for %@: download did not complete within %.0fs — using fallback."
+ "%{public}s V9 model for %@: using BUILT-IN bundled model"
+ "%{public}s V9 model for %@: using MOBILE ASSET model (%@)"
+ "%{public}s prefetchModelForClass for CFA class %ld"
+ "+[RAWDemosaicProcessorV9 getModelForCFAPattern:useQuarterRes:useAltModel:useMPSGraph:modelDirectory:]"
+ "-[CRawModelAssetManager ensureModelDownloadedForClass:timeout:]"
+ "-[CRawModelAssetManager installedModelDirectoryForClass:]"
+ "-[CRawModelAssetManager prefetchModelForClass:]"
+ "-[CRawModelAssetManager prefetchModelForClass:]_block_invoke"
+ "/%@.mil"
+ "/%@_model.mil"
+ "Bayer"
+ "GetModelAssetCatalog_block_invoke"
+ "GetModelAssetCatalog_block_invoke_2"
+ "MADownloadTimedOutBecameStalled"
+ "MADownloadTimedOutFrequentStalls"
+ "MADownloadTimedOutNoContent"
+ "MADownloadTimedOutSlowDownload"
+ "MAQueryBeforeFirstUnlock"
+ "MAQueryCannotCreateMessage"
+ "MAQueryCatalogNotDownloaded"
+ "MAQueryDaemonExit"
+ "MAQueryFailed"
+ "MAQueryNilAssetType"
+ "MAQueryNotEntitled"
+ "MAQueryParamsEncodeFailure"
+ "MAQuerySuccessful"
+ "MAQueryXpcError"
+ "ModelDirectory"
+ "ModelGroup"
+ "Quadra"
+ "RCMAAssetAttachProgress"
+ "RawCamera_ModelAsset_Prefetch_Queue"
+ "RawCamera_ModelCatalog_Access_Queue"
+ "XTrans"
+ "_ContentVersion"
+ "_model"
+ "_quarter_res_model"
+ "already downloading"
+ "bayer"
+ "com.apple.MobileAsset.RawCamera.MLModels"
+ "com.apple.MobileAsset.RawCamera.MLModels.ma.cached-metadata-updated"
+ "downloading now"
+ "inputModelDirectory"
+ "inputModelDownloadTimeout"
+ "quadra"
+ "see MADownloadResult in MAClientComms.h"
+ "unknown"
+ "v16@?0@\"MAProgressNotification\"8"
+ "v36@?0q8q16B24d28"
+ "xtrans"
- "%{public}s Failed to load the model."
- "%{public}s RCMAAssetQueryMetaDataSync: Result = %d (%s)"
- "+[RAWDemosaicProcessorV9 getModelForCFAPattern:useQuarterRes:useAltModel:useMPSGraph:]"
```
