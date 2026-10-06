## RawCamera

> `/System/Library/CoreServices/RawCamera.bundle/RawCamera`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23302c` | `0x2362e8` | **`+0x32bc`** |
| `__AUTH.__objc_data` | `0x1310` | `0x50` | **`-0x12c0`** |
| `__DATA_DIRTY.__objc_data` | `0xf0` | `0x13b0` | **`+0x12c0`** |
| `__DATA_DIRTY.__data` | `0x8` | `0xf78` | **`+0xf70`** |
| `__DATA.__data` | `0x20e68` | `0x206a0` | **`-0x7c8`** |
| `__AUTH.__data` | `0x7a8` | `—` | **`-0x7a8`** |
| `__TEXT.__gcc_except_tab` | `0x324b4` | `0x32a3c` | **`+0x588`** |
| `__AUTH_CONST.__const` | `0x3c648` | `0x3c8a8` | **`+0x260`** |
| `__TEXT.__oslogstring` | `0x2d42` | `0x2f9d` | **`+0x25b`** |
| `__TEXT.__cstring` | `0x128f1` | `0x12b11` | **`+0x220`** |
| `__TEXT.__const` | `0x18644` | `0x187e4` | **`+0x1a0`** |
| `__TEXT.__unwind_info` | `0xc918` | `0xca40` | **`+0x128`** |
| `__DATA_CONST.__const` | `0x2e38` | `0x2f08` | **`+0xd0`** |
| `__AUTH_CONST.__cfstring` | `0x1b0c0` | `0x1b140` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x13b8` | `0x13e8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x25ac` | `0x25dc` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x1830` | `0x1858` | **`+0x28`** |
| `__DATA.__bss` | `0x7310` | `0x7320` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x12a8` | `0x12b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xae8` | `0xaf0` | **`+0x8`** |

### Other Changes

```diff

-1821.40.4.0.0
+1821.40.6.0.0

-  Functions: 7854
-  Symbols:   987
-  CStrings:  4294
+  Functions: 7891
+  Symbols:   988
+  CStrings:  4314
Symbols:
+ _dispatch_after
CStrings:
+ "%{public}s All V9 model assets: %s."
+ "%{public}s Downloading ALL V9 model assets (%lu CFA families x %lu decoder versions)."
+ "%{public}s Exception in tile processing for tile %u: %s"
+ "%{public}s Model MobileAsset catalog fetch never reported back — no longer waiting on it."
+ "%{public}s RCMAAssetStartDownload: Download completed with result %d (%s), raw %ld (%s)"
+ "%{public}s Unknown exception in tile processing for tile %u"
+ "%{public}s V9 model for %@: a download has been in flight for %llds without installing — giving up on it. It may be a stalled task from an earlier run; `asutil --malist-tasks` / `--maclean-tasks` clears those."
+ "%{public}s V9 model for %@: a download is already in flight; watching it instead of starting a second one."
+ "%{public}s V9 model for %@: the in-flight download ended without installing (state=%d)."
+ "-[CRawModelAssetManager startAssetDownloadForClass:version:inCatalog:]_block_invoke"
+ "-[CRawModelAssetManager startDownloadForAllModelsWithCompletion:]"
+ "-[CRawModelAssetManager startDownloadForAllModelsWithCompletion:]_block_invoke"
+ "-[CRawModelAssetManager watchInFlightDownloadForClass:version:asset:deadline:]_block_invoke"
+ "@\"CIImage\"64@?0@\"CIImage\"8d16d24d32d40Q48Q56"
+ "DNGLosslessJpegUnpacker: AppleJPEG failed to decode tile"
+ "MADownloadAssetAlreadyInstalled"
+ "MADownloadSuccessful"
+ "RAWRecoverHighlightsV3"
+ "_DownloadSize"
+ "com.apple.MobileAsset.RawCamera.MLModel"
+ "com.apple.MobileAsset.RawCamera.MLModel.ma.cached-metadata-updated"
+ "every model is present"
+ "one or more did NOT download"
+ "srSCCDBoxH"
+ "srSCCDBoxV"
+ "srSCCDCombine"
+ "srSCCDDefringe"
+ "srSCCDDiff"
+ "srSCCDGreen"
+ "v12@?0B8"
+ "v16@?0@\"NSArray\"8"
- "%{public}s Exception in tile coordinate calculation for tile %u: %s"
- "%{public}s Exception in tile processing: %s"
- "%{public}s Exception in unpackSensorData: %s"
- "%{public}s RCMAAssetStartDownload: Download completed with result %d (%s)"
- "%{public}s Unknown exception in tile processing"
- "RAWRecoverHighlightsV2"
- "com.apple.MobileAsset.RawCamera.MLModels"
- "com.apple.MobileAsset.RawCamera.MLModels.ma.cached-metadata-updated"
- "deSuperCCDSR_v8"
- "deXtrans_draft"
- "deXtrans_v7_8bit"
```
