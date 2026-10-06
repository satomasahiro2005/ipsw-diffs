## UARPAssetManagerServiceMobileAsset

> `/System/Library/PrivateFrameworks/UARPAssetManager.framework/XPCServices/UARPAssetManagerServiceMobileAsset.xpc/UARPAssetManagerServiceMobileAsset`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf338` | `0x103ac` | **`+0x1074`** |
| `__DATA_CONST.__cfstring` | `0xf00` | `0x1160` | **`+0x260`** |
| `__TEXT.__objc_methname` | `0x2106` | `0x2305` | **`+0x1ff`** |
| `__DATA.__objc_const` | `0x19e0` | `0x1b70` | **`+0x190`** |
| `__TEXT.__cstring` | `0x1134` | `0x12b5` | **`+0x181`** |
| `__TEXT.__objc_stubs` | `0x21e0` | `0x22c0` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0xc44` | `0xd14` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x1406` | `0x14cf` | **`+0xc9`** |
| `__DATA_CONST.__const` | `0x360` | `0x3e0` | **`+0x80`** |
| `__DATA.__objc_data` | `0x410` | `0x460` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x9c0` | `0xa08` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x390` | `0x3c0` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x5cc` | `0x5f1` | **`+0x25`** |
| `__TEXT.__objc_classname` | `0x24d` | `0x269` | **`+0x1c`** |
| `__DATA.__objc_ivar` | `0xbc` | `0xd0` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0x490` | `0x4a0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x258` | `0x260` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x140` | `0x148` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x68` | `0x70` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x50` | `0x58` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1587.0.3.0.3
+1587.0.21.0.0

-  Functions: 318
-  Symbols:   225
-  CStrings:  713
+  Functions: 342
+  Symbols:   238
+  CStrings:  756
Symbols:
+ _CFPreferencesCopyAppValue
+ _OBJC_CLASS_$_UARPAssetSubscriptioniCloud
+ _OBJC_CLASS_$_UARPEndpointPersonalityiCloud
+ _OBJC_METACLASS_$_UARPAssetSubscriptioniCloud
+ _containerIDForAssetContainerType
+ _createPersonalityForiCloudSubscription
+ _createiCloudSubscriptionForPersonality
+ _getContainerIDFromCFPrefs
+ _kUARPAssetManagerServiceCacheRegistryFileExtension
+ _kUARPAssetManagerServiceCacheVerificationCertsFileName
+ _kUARPAssetManagerServiceReleaseNotesFileName
+ _kUARPAssetManagerServiceiCloudCertificateFileName
+ _kUARPAssetManagerServiceiCloudTokenFileName
CStrings:
+ "%@-%@"
+ "%s: ContainerID override found for %@: %@"
+ "-[UARPAssetManagerServiceAssetCache pruneExpiredRegistryEntries:]_block_invoke"
+ "<%@: pgpn=%@-%@, containerID=%@ releaseNotes=%@ domain=%@>"
+ "@56@0:8@16@24@32B40B44@48"
+ "B20@0:8B16"
+ "NO"
+ "Only iCloud accessory personalities are currently supported"
+ "Only iCloud accessory subscriptions are currently supported"
+ "T@\"NSString\",R,V_containerID"
+ "T@\"NSString\",R,V_productGroup"
+ "T@\"NSString\",R,V_productNumber"
+ "TB,R,V_downloadOnCellularAllowed"
+ "TB,R,V_releaseNotesAsset"
+ "UARPAssetSubscriptioniCloud"
+ "UARPVerificationCertificates.plist"
+ "UARPiCloudTokens.plist"
+ "Unsupported container type %{public}ld"
+ "YES"
+ "_containerID"
+ "_downloadOnCellularAllowed"
+ "_productGroup"
+ "_productNumber"
+ "_releaseNotesAsset"
+ "cellularDownload"
+ "clearCacheRecordForSubscription:"
+ "com.apple.uarp.beta"
+ "com.apple.uarp.staging"
+ "com.apple.uarp.staging.beta"
+ "com.apple.uarp.staging.uat"
+ "com.apple.uarp.uat"
+ "containerID"
+ "downloadOnCellularAllowed"
+ "getContainerIDFromCFPrefs"
+ "initWithProductGroup:productNumber:containerID:releaseNotesAsset:downloadOnCellularAllowed:domain:"
+ "initWithProductGroup:productNumber:domain:"
+ "plist"
+ "productGroup"
+ "productNumber"
+ "pruneExpiredRegistryEntries:"
+ "releaseNotes"
+ "releaseNotesAsset"
+ "releasenotes"
+ "setContainerID:"
+ "vid0x%04lXpid0x%04lX"
- "-[UARPAssetManagerServiceAssetCache pruneExpiredRegistryEntries]_block_invoke"
- "pruneExpiredRegistryEntries"
```
