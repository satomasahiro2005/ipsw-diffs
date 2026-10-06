## HomeUIService

> `/Applications/HomeUIService.app/HomeUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7b424` | `0x7d16c` | **`+0x1d48`** |
| `__TEXT.__objc_methname` | `0x15dba` | `0x163f6` | **`+0x63c`** |
| `__TEXT.__objc_stubs` | `0xf180` | `0xf6a0` | **`+0x520`** |
| `__DATA.__objc_const` | `0xd6d8` | `0xd8b8` | **`+0x1e0`** |
| `__DATA_CONST.__cfstring` | `0x46c0` | `0x48a0` | **`+0x1e0`** |
| `__TEXT.__objc_methlist` | `0x7b34` | `0x7ccc` | **`+0x198`** |
| `__DATA.__objc_selrefs` | `0x50a8` | `0x5218` | **`+0x170`** |
| `__TEXT.__cstring` | `0x94d1` | `0x9601` | **`+0x130`** |
| `__TEXT.__gcc_except_tab` | `0xb00` | `0xc00` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x8912` | `0x8842` | **`-0xd0`** |
| `__DATA_CONST.__const` | `0x31b8` | `0x3250` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x1dc8` | `0x1e60` | **`+0x98`** |
| `__DATA_CONST.__got` | `0xc10` | `0xc60` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0x69c` | `0x6c4` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x13b0` | `0x13d0` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x3dce` | `0x3de9` | **`+0x1b`** |
| `__DATA_CONST.__auth_got` | `0x9e8` | `0x9f8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1227.0.0.0.1
+1232.3.0.0.0

-  Functions: 2851
-  Symbols:   843
-  CStrings:  5222
+  Functions: 2891
+  Symbols:   848
+  CStrings:  5294
Symbols:
+ _$s4Home24HFHapticFeedbackProviderC7prewarmyyF
+ _OBJC_CLASS_$_HUProximityAssetImage
+ _OBJC_CLASS_$_NSData
+ _OBJC_CLASS_$_NSNull
+ _OBJC_CLASS_$_NSProcessInfo
+ _dispatch_get_global_queue
- _NSLocalizedDescriptionKey
CStrings:
+ "%s fetchPrimaryImage failed; keeping fallback icon: %@"
+ "-[HSProximityCardHostViewController _fetchAndCrossFadePrimaryImageWithVendorID:productID:]_block_invoke"
+ "@\"HMAccessorySetupManager\""
+ "HMASM.pa.category"
+ "HMASM.pa.darkBias"
+ "HMASM.pa.darkMatrix"
+ "HMASM.pa.friendlyName"
+ "HMASM.pa.lightBias"
+ "HMASM.pa.lightMatrix"
+ "HMASM.pa.primaryImage2x"
+ "HMASM.pa.primaryImage3x"
+ "HMASM.pa.videoURL"
+ "Pairing completed - Home App hand-off - skipping advance to the next step"
+ "ProximityGuide: allAssets resolved without video; keeping fallback icon"
+ "ProximityGuide: no allAssetsFetchFuture; keeping fallback icon"
+ "T@\"HMAccessorySetupManager\",&,N,V_accessorySetupManager"
+ "T@\"HUIconView\",&,N,V_placeholderIconView"
+ "T@\"HUProximityAssetRecord\",&,N,V_pendingAssetRecord"
+ "T@\"HUProximityAssetRecord\",&,N,V_pendingVideoRecord"
+ "T@\"UIImageView\",&,N,V_placeholderIconView"
+ "T@\"UIView\",&,N,V_assetContainer"
+ "TB,N,V_assetApplied"
+ "TB,N,V_didAppear"
+ "TB,N,V_videoApplied"
+ "_accessorySetupManager"
+ "_assetApplied"
+ "_assetContainer"
+ "_brandedAssetFieldsFromHomedInfo:"
+ "_brandedAssetRecordFromHomedInfo:"
+ "_didAppear"
+ "_fetchAndCrossFadePrimaryImageWithVendorID:productID:"
+ "_installVideoWhenSettled:"
+ "_pendingAssetRecord"
+ "_pendingVideoRecord"
+ "_placeholderIconView"
+ "_presentProxCardFirstWithUserInfo:"
+ "_resolveBrandedAssetWithVendorID:productID:buildAndPresent:"
+ "_selfFetchBrandedAssetsWithVendorID:productID:guidePromise:"
+ "_videoApplied"
+ "_warmOnboardingUtilitiesCache"
+ "_willContinueSetupInHomeApp"
+ "_willContinueSetupInHomeApp returning false"
+ "_willContinueSetupInHomeApp returning true since HUIS was launched by 1st party"
+ "_willSkipDetectedCardForRecentNFC"
+ "accessoryCategory"
+ "accessorySetupManager"
+ "animateWithDuration:delay:options:animations:completion:"
+ "applyProductKitAsset:"
+ "assetApplied"
+ "assetContainer"
+ "darkBias"
+ "darkMatrix"
+ "didAppear"
+ "fetchCachedProximityAssetWithCompletionHandler:"
+ "friendlyName"
+ "hasInstructionalVideo"
+ "hasVideo"
+ "hit"
+ "homed prox-asset pull responded in %.1f ms (%{public}s)"
+ "initWithAccessoryCategory:accessoryFriendlyName:primaryImage:instructionalVideoURL:lightBias:lightMatrix:darkBias:darkMatrix:"
+ "initWithData2x:data3x:"
+ "installAssetImageFromRecord:animated:"
+ "installVideoFromRecord:animated:"
+ "lightBias"
+ "lightMatrix"
+ "miss"
+ "null"
+ "numberWithDouble:"
+ "numberWithUnsignedChar:"
+ "pendingAssetRecord"
+ "pendingVideoRecord"
+ "placeholderIconView"
+ "prewarm"
+ "processInfo"
+ "recordSkippedDetectedForRecentNFC"
+ "setAccessorySetupManager:"
+ "setAlpha:"
+ "setAssetApplied:"
+ "setAssetContainer:"
+ "setDidAppear:"
+ "setPendingAssetRecord:"
+ "setPendingVideoRecord:"
+ "setPlaceholderIconView:"
+ "setVideoApplied:"
+ "subscribeForInstructionalVideo"
+ "systemUptime"
+ "unsignedCharValue"
+ "v24@?0@\"NSDictionary\"8@\"NSError\"16"
+ "videoApplied"
+ "videoURL"
+ "viewIfLoaded"
- "%s Starting fetchPrimaryImage for vendorID: %@ productID: %@"
- "@\"NAFuture\"16@?0@\"HUProximityAssetRecord\"8"
- "Pairing completed - finishing setup in Home App. Cancelling advance to the next step"
- "Primary image fetch failed or timed out, using fallback icons: %@"
- "Primary image fetch timed out"
- "ProximityGuide: allAssets already resolved, updating assetRecord with video URL"
- "ProximityGuide: allAssets not yet resolved, using current assetRecord (fallback)"
- "ProximityGuide: allAssets resolved but failed, keeping current assetRecord"
- "TB,N,V_isContinuingSetupInHomeApp"
- "_isContinuingSetupInHomeApp"
- "_primaryImageFetchTimeoutForLaunchReason:"
- "com.apple.Home.ProximityPairing"
- "errorWithDomain:code:userInfo:"
- "fetchAllAssets failed, falling back to primary image: %@"
- "fetchPrimaryImage completed successfully for: %@"
- "fetchPrimaryImage completed with error: %@"
- "fetchPrimaryImage timed out after %.1fs"
- "isContinuingSetupInHomeApp"
- "setIsContinuingSetupInHomeApp:"
```
