## uarpassetmanagerd

> `/usr/libexec/uarpassetmanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a6e4` | `0x2e098` | **`+0x39b4`** |
| `__DATA_CONST.__const` | `0x27d0` | `0x2c40` | **`+0x470`** |
| `__DATA_CONST.__cfstring` | `0x2bc0` | `0x2f40` | **`+0x380`** |
| `__TEXT.__cstring` | `0x2c7e` | `0x2fe3` | **`+0x365`** |
| `__DATA.__objc_const` | `0x2d48` | `0x3090` | **`+0x348`** |
| `__TEXT.__objc_methname` | `0x2c59` | `0x2f37` | **`+0x2de`** |
| `__TEXT.__objc_methlist` | `0x12bc` | `0x1494` | **`+0x1d8`** |
| `__TEXT.__oslogstring` | `0x1826` | `0x1989` | **`+0x163`** |
| `__TEXT.__objc_stubs` | `0x26e0` | `0x2840` | **`+0x160`** |
| `__DATA.__objc_data` | `0x500` | `0x5f0` | **`+0xf0`** |
| `__DATA.__objc_selrefs` | `0xbb0` | `0xc18` | **`+0x68`** |
| `__TEXT.__objc_classname` | `0x2e4` | `0x341` | **`+0x5d`** |
| `__TEXT.__objc_methtype` | `0x837` | `0x894` | **`+0x5d`** |
| `__TEXT.__unwind_info` | `0x3a0` | `0x3e0` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x17c` | `0x19c` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x4b0` | `0x4d0` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x80` | `0x98` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x78` | `0x90` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x268` | `0x278` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x198` | `0x1a8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-1587.0.3.0.3
+1587.0.21.0.0

-  Functions: 458
-  Symbols:   1600
-  CStrings:  1169
+  Functions: 501
+  Symbols:   1712
+  CStrings:  1235
Symbols:
+ +[UARPAssetCacheRecordiCloud supportsSecureCoding]
+ +[UARPAssetSubscriptioniCloud supportsSecureCoding]
+ -[UARPAssetCacheRecordiCloud .cxx_destruct]
+ -[UARPAssetCacheRecordiCloud assetHash]
+ -[UARPAssetCacheRecordiCloud containerID]
+ -[UARPAssetCacheRecordiCloud copyWithZone:]
+ -[UARPAssetCacheRecordiCloud description]
+ -[UARPAssetCacheRecordiCloud encodeWithCoder:]
+ -[UARPAssetCacheRecordiCloud hash]
+ -[UARPAssetCacheRecordiCloud initWithAssetVersion:containerID:assetURL:assetHash:deploymentRules:]
+ -[UARPAssetCacheRecordiCloud initWithCoder:]
+ -[UARPAssetCacheRecordiCloud isEqual:]
+ -[UARPAssetManagerController getAssetURLForPersonality:releaseNotes:]
+ -[UARPAssetManagerListener getAssetURLForPersonality:releaseNotes:reply:]
+ -[UARPAssetManagerServiceInstance checkCacheForPersonality:releaseNotes:]
+ -[UARPAssetManagerServiceInstance createSubscriptionForPrimeCache:]
+ -[UARPAssetManagerServiceInstanceMobileAsset checkCacheForPersonality:releaseNotes:]
+ -[UARPAssetManagerServiceInstanceiCloud .cxx_destruct]
+ -[UARPAssetManagerServiceInstanceiCloud assetAvailabilityUpdateForPersonality:assetVersion:creationDate:status:]
+ -[UARPAssetManagerServiceInstanceiCloud assetAvailabilityUpdateForSubscription:cacheRecord:asyncUpdate:]
+ -[UARPAssetManagerServiceInstanceiCloud assetType]
+ -[UARPAssetManagerServiceInstanceiCloud checkCacheForPersonality:releaseNotes:]
+ -[UARPAssetManagerServiceInstanceiCloud createPersonality:]
+ -[UARPAssetManagerServiceInstanceiCloud createSubscriptionForPrimeCache:]
+ -[UARPAssetManagerServiceInstanceiCloud encodedClasses]
+ -[UARPAssetManagerServiceInstanceiCloud initWithServiceName:delegate:]
+ -[UARPAssetManagerServiceInstanceiCloud isSubscriptionSupported:]
+ -[UARPAssetManagerServiceInstanceiCloud subscribeForPersonality:]
+ -[UARPAssetManagerServiceManager checkCacheForPersonality:releaseNotes:]
+ -[UARPAssetSubscriptioniCloud .cxx_destruct]
+ -[UARPAssetSubscriptioniCloud containerID]
+ -[UARPAssetSubscriptioniCloud copyWithZone:]
+ -[UARPAssetSubscriptioniCloud description]
+ -[UARPAssetSubscriptioniCloud downloadOnCellularAllowed]
+ -[UARPAssetSubscriptioniCloud encodeWithCoder:]
+ -[UARPAssetSubscriptioniCloud hash]
+ -[UARPAssetSubscriptioniCloud initWithCoder:]
+ -[UARPAssetSubscriptioniCloud initWithProductGroup:productNumber:containerID:releaseNotesAsset:downloadOnCellularAllowed:domain:]
+ -[UARPAssetSubscriptioniCloud isEqual:]
+ -[UARPAssetSubscriptioniCloud productGroup]
+ -[UARPAssetSubscriptioniCloud productNumber]
+ -[UARPAssetSubscriptioniCloud releaseNotesAsset]
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetCacheRecordiCloud.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-4b0ed6e1656d20a748062c3f582e7535.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstanceiCloud.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetSubscriptioniCloud.o
+ GCC_except_table14
+ OBJC_IVAR_$_UARPAssetCacheRecordiCloud._assetHash
+ OBJC_IVAR_$_UARPAssetCacheRecordiCloud._containerID
+ OBJC_IVAR_$_UARPAssetManagerServiceInstanceiCloud._log
+ OBJC_IVAR_$_UARPAssetSubscriptioniCloud._containerID
+ OBJC_IVAR_$_UARPAssetSubscriptioniCloud._downloadOnCellularAllowed
+ OBJC_IVAR_$_UARPAssetSubscriptioniCloud._productGroup
+ OBJC_IVAR_$_UARPAssetSubscriptioniCloud._productNumber
+ OBJC_IVAR_$_UARPAssetSubscriptioniCloud._releaseNotesAsset
+ UARPAssetCacheRecordiCloud.m
+ UARPAssetManagerServiceInstanceiCloud.m
+ UARPAssetSubscriptioniCloud.m
+ _CFPreferencesCopyAppValue
+ _OBJC_CLASS_$_UARPAssetCacheRecordiCloud
+ _OBJC_CLASS_$_UARPAssetManagerServiceInstanceiCloud
+ _OBJC_CLASS_$_UARPAssetSubscriptioniCloud
+ _OBJC_CLASS_$_UARPEndpointPersonalityiCloud
+ _OBJC_METACLASS_$_UARPAssetCacheRecordiCloud
+ _OBJC_METACLASS_$_UARPAssetManagerServiceInstanceiCloud
+ _OBJC_METACLASS_$_UARPAssetSubscriptioniCloud
+ _UARPiCloudPublicContainerBetaKey
+ _UARPiCloudPublicContainerKey
+ _UARPiCloudPublicContainerUATKey
+ _UARPiCloudStagingContainerBetaKey
+ _UARPiCloudStagingContainerKey
+ _UARPiCloudStagingContainerUATKey
+ __61-[UARPAssetManagerServiceInstance unregisterForSubscription:]_block_invoke
+ __OBJC_$_CLASS_METHODS_UARPAssetCacheRecordiCloud
+ __OBJC_$_CLASS_METHODS_UARPAssetSubscriptioniCloud
+ __OBJC_$_INSTANCE_METHODS_UARPAssetCacheRecordiCloud
+ __OBJC_$_INSTANCE_METHODS_UARPAssetManagerServiceInstanceiCloud
+ __OBJC_$_INSTANCE_METHODS_UARPAssetSubscriptioniCloud
+ __OBJC_$_INSTANCE_VARIABLES_UARPAssetCacheRecordiCloud
+ __OBJC_$_INSTANCE_VARIABLES_UARPAssetManagerServiceInstanceiCloud
+ __OBJC_$_INSTANCE_VARIABLES_UARPAssetSubscriptioniCloud
+ __OBJC_$_PROP_LIST_UARPAssetCacheRecordiCloud
+ __OBJC_$_PROP_LIST_UARPAssetSubscriptioniCloud
+ __OBJC_CLASS_RO_$_UARPAssetCacheRecordiCloud
+ __OBJC_CLASS_RO_$_UARPAssetManagerServiceInstanceiCloud
+ __OBJC_CLASS_RO_$_UARPAssetSubscriptioniCloud
+ __OBJC_METACLASS_RO_$_UARPAssetCacheRecordiCloud
+ __OBJC_METACLASS_RO_$_UARPAssetManagerServiceInstanceiCloud
+ __OBJC_METACLASS_RO_$_UARPAssetSubscriptioniCloud
+ ___55-[UARPAssetManagerServiceInstance releaseXPCConnection]_block_invoke
+ ___block_descriptor_40_e8_32s_e5_v8?0ls32l8
+ ___os_log_helper_16_0_1_8_2
+ ___os_log_helper_16_2_4_8_32_8_64_8_64_4_0
+ _containerIDForAssetContainerType
+ _createPersonalityForiCloudSubscription
+ _createiCloudEndpointPersonality
+ _createiCloudSubscriptionForPersonality
+ _getContainerIDFromCFPrefs
+ _kUARPAssetCacheRecordEncoderKeyAssetHash
+ _kUARPAssetCacheRecordEncoderKeyContainerID
+ _kUARPAssetManagerServiceCacheRegistryFileExtension
+ _kUARPAssetManagerServiceCacheVerificationCertsFileName
+ _kUARPAssetManagerServiceReleaseNotesFileName
+ _kUARPAssetManagerServiceiCloudCertificateFileName
+ _kUARPAssetManagerServiceiCloudTokenFileName
+ _kUARPAssetSubscriptionMobileAssetEncoderKeyCellDownload
+ _kUARPAssetSubscriptionMobileAssetEncoderKeyReleaseNotes
+ _kUARPAssetSubscriptionUARPiCloudEncoderKeyContainerID
+ _kUARPAssetSubscriptionUARPiCloudEncoderKeyProductGroup
+ _kUARPAssetSubscriptionUARPiCloudEncoderKeyProductNumber
+ _objc_msgSend$assetAvailabilityUpdateForPersonality:assetVersion:creationDate:status:
+ _objc_msgSend$assetHash
+ _objc_msgSend$checkCacheForPersonality:releaseNotes:
+ _objc_msgSend$containerID
+ _objc_msgSend$createSubscriptionForPrimeCache:
+ _objc_msgSend$getAssetURLForPersonality:releaseNotes:
+ _objc_msgSend$initWithAssetVersion:containerID:assetURL:assetHash:deploymentRules:
+ _objc_msgSend$initWithProductGroup:productNumber:containerID:releaseNotesAsset:downloadOnCellularAllowed:domain:
+ _objc_msgSend$initWithProductGroup:productNumber:domain:
+ _objc_msgSend$model
+ _objc_msgSend$productGroup
+ _objc_msgSend$productNumber
+ _objc_msgSend$releaseNotesAsset
+ _objc_msgSend$setContainerID:
+ _objc_msgSend$useiCloud
- -[UARPAssetManagerController getAssetURLForPersonality:]
- -[UARPAssetManagerListener getAssetURLForPersonality:reply:]
- -[UARPAssetManagerServiceInstance assetManagerService]
- -[UARPAssetManagerServiceInstance checkCacheForPersonality:]
- -[UARPAssetManagerServiceInstanceMobileAsset assetManagerService]
- -[UARPAssetManagerServiceInstanceMobileAsset checkCacheForPersonality:]
- -[UARPAssetManagerServiceManager checkCacheForPersonality:]
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-66c0fcf2e523785dc7e763a7403edba6.o
- GCC_except_table13
- _objc_msgSend$assetManagerService
- _objc_msgSend$checkCacheForPersonality:
- _objc_msgSend$getAssetURLForPersonality:
- _objc_msgSend$usePallas
CStrings:
+ "%@-%@"
+ "%s Could not create valid iCloud subscription for %{public}@"
+ "%s: ContainerID override found for %@: %@"
+ "-"
+ "-[UARPAssetManagerListener getAssetURLForPersonality:releaseNotes:reply:]"
+ "-[UARPAssetManagerServiceInstance checkCacheForPersonality:releaseNotes:]"
+ "-[UARPAssetManagerServiceInstance createSubscriptionForPrimeCache:]"
+ "-[UARPAssetManagerServiceInstanceMobileAsset checkCacheForPersonality:releaseNotes:]"
+ "-[UARPAssetManagerServiceInstanceiCloud assetAvailabilityUpdateForSubscription:cacheRecord:asyncUpdate:]"
+ "-[UARPAssetManagerServiceInstanceiCloud checkCacheForPersonality:releaseNotes:]"
+ "<%@: assetVersion=%@, assetURL=%@ containerID=%@ assetHash=%@>"
+ "<%@: pgpn=%@-%@, containerID=%@ releaseNotes=%@ domain=%@>"
+ "@\"NSURL\"28@0:8@\"UARPEndpointPersonality\"16B24"
+ "@56@0:8@16@24@32@40@48"
+ "@56@0:8@16@24@32B40B44@48"
+ "Could not create valid iCloud subscription for %{public}@"
+ "NO"
+ "Only iCloud accessory personalities are currently supported"
+ "Only iCloud accessory subscriptions are currently supported"
+ "RECEIVED %s: %@, returning %@ / %d"
+ "T@\"NSString\",R,V_assetHash"
+ "T@\"NSString\",R,V_containerID"
+ "T@\"NSString\",R,V_productGroup"
+ "T@\"NSString\",R,V_productNumber"
+ "TB,R,V_downloadOnCellularAllowed"
+ "TB,R,V_releaseNotesAsset"
+ "UARPAssetCacheRecordiCloud"
+ "UARPAssetManagerServiceInstanceiCloud"
+ "UARPAssetSubscriptioniCloud"
+ "UARPVerificationCertificates.plist"
+ "UARPiCloudPublicContainer"
+ "UARPiCloudPublicContainerBeta"
+ "UARPiCloudPublicContainerUAT"
+ "UARPiCloudStagingContainer"
+ "UARPiCloudStagingContainerBeta"
+ "UARPiCloudStagingContainerUAT"
+ "UARPiCloudTokens.plist"
+ "Unsupported container type %{public}ld"
+ "YES"
+ "_assetHash"
+ "_containerID"
+ "_downloadOnCellularAllowed"
+ "_productGroup"
+ "_productNumber"
+ "_releaseNotesAsset"
+ "assetAvailabilityUpdateForPersonality:assetVersion:creationDate:status:"
+ "assetHash"
+ "assetType"
+ "cellularDownload"
+ "checkCacheForPersonality:releaseNotes:"
+ "com.apple.uarp.beta"
+ "com.apple.uarp.staging"
+ "com.apple.uarp.staging.beta"
+ "com.apple.uarp.staging.uat"
+ "com.apple.uarp.uat"
+ "containerID"
+ "createSubscriptionForPrimeCache:"
+ "downloadOnCellularAllowed"
+ "getAssetURLForPersonality:releaseNotes:"
+ "getAssetURLForPersonality:releaseNotes:reply:"
+ "getContainerIDFromCFPrefs"
+ "initWithAssetVersion:containerID:assetURL:assetHash:deploymentRules:"
+ "initWithProductGroup:productNumber:containerID:releaseNotesAsset:downloadOnCellularAllowed:domain:"
+ "initWithProductGroup:productNumber:domain:"
+ "model"
+ "plist"
+ "productGroup"
+ "productNumber"
+ "releaseNotes"
+ "releaseNotesAsset"
+ "releasenotes"
+ "setContainerID:"
+ "useiCloud"
+ "v36@0:8@\"UARPEndpointPersonality\"16B24@?<v@?@\"NSURL\">28"
+ "v36@0:8@16B24@?28"
+ "v48@0:8@16@24@32q40"
+ "vid0x%04lXpid0x%04lX"
- "-[UARPAssetManagerListener getAssetURLForPersonality:reply:]"
- "-[UARPAssetManagerServiceInstance assetManagerService]"
- "-[UARPAssetManagerServiceInstance checkCacheForPersonality:]"
- "-[UARPAssetManagerServiceInstanceMobileAsset checkCacheForPersonality:]"
- "@\"NSURL\"24@0:8@\"UARPEndpointPersonality\"16"
- "assetManagerService"
- "checkCacheForPersonality:"
- "getAssetURLForPersonality:"
- "getAssetURLForPersonality:reply:"
- "usePallas"
- "v32@0:8@\"UARPEndpointPersonality\"16@?<v@?@\"NSURL\">24"
```
