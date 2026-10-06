## uarpassetmanagerd

> `/usr/libexec/uarpassetmanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e098` | `0x2ef84` | **`+0xeec`** |
| `__TEXT.__objc_methname` | `0x2f37` | `0x3094` | **`+0x15d`** |
| `__TEXT.__cstring` | `0x2f99` | `0x30da` | **`+0x141`** |
| `__TEXT.__objc_stubs` | `0x2840` | `0x2960` | **`+0x120`** |
| `__DATA_CONST.__cfstring` | `0x2f00` | `0x2fc0` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x2bb0` | `0x2c30` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0xc18` | `0xc68` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x1494` | `0x14dc` | **`+0x48`** |
| `__DATA.__objc_const` | `0x3090` | `0x30c0` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x1989` | `0x19b8` | **`+0x2f`** |
| `__TEXT.__auth_stubs` | `0x4d0` | `0x4e0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3e0` | `0x3f0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x278` | `0x280` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1a8` | `0x1b0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x19c` | `0x1a0` | **`+0x4`** |
| `__TEXT.__objc_methtype` | `0x894` | `0x897` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1587.0.27.0.0
+1587.2.2.0.0

-  Functions: 501
-  Symbols:   1710
-  CStrings:  1233
+  Functions: 507
+  Symbols:   1735
+  CStrings:  1253
Symbols:
+ +[UARPAssetSubscriptioniCloud cacheSubdirectoryForContainerID:developmentEnvironment:]
+ +[UARPAssetSubscriptioniCloud developmentEnvironmentForContainerID:]
+ +[UARPAssetSubscriptioniCloud resolvedContainerIDForContainerID:]
+ -[UARPAssetManagerServiceInstanceMobileAsset createSubscriptionForPrimeCache:]
+ -[UARPAssetSubscriptioniCloud developmentEnvironment]
+ -[UARPAssetSubscriptioniCloud initWithProductGroup:productNumber:containerID:releaseNotesAsset:downloadOnCellularAllowed:developmentEnvironment:domain:]
+ -[UARPAssetSubscriptioniCloud isEqualForAnyDomain:]
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-7a1466489ea83b82120cbc16e6cc4a86.o
+ OBJC_IVAR_$_UARPAssetSubscriptioniCloud._developmentEnvironment
+ _CFPreferencesGetAppBooleanValue
+ _MA_PALLAS_AUDIENCE_RELEASE_ALIGNED_SEED_STAGING_EXT_PRERELEASE
+ _kUARPAssetSubscriptioniCloudEncoderKeyDevelopmentEnvironment
+ _kUARPiCloudCHIPContainerPrefix
+ _kUARPiCloudDefaultPublicContainer
+ _kUARPiCloudDevelopmentEnvironmentDirectory
+ _kUARPiCloudDevelopmentEnvironmentPrefKey
+ _kUARPiCloudManagedPreferencesPath
+ _kUARPiCloudPreferencesDomain
+ _objc_msgSend$containsString:
+ _objc_msgSend$developmentEnvironment
+ _objc_msgSend$developmentEnvironmentForContainerID:
+ _objc_msgSend$initWithContentsOfURL:error:
+ _objc_msgSend$initWithProductGroup:productNumber:containerID:releaseNotesAsset:downloadOnCellularAllowed:developmentEnvironment:domain:
+ _objc_msgSend$pathWithComponents:
+ _objc_msgSend$resolvedContainerIDForContainerID:
+ _objc_msgSend$stringByAppendingString:
+ _objc_msgSend$substringFromIndex:
+ _objc_msgSend$usePallas
- -[UARPAssetSubscriptioniCloud initWithProductGroup:productNumber:containerID:releaseNotesAsset:downloadOnCellularAllowed:domain:]
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/AppleAccessoryManager/install/TempContent/Objects/AppleAccessoryManager.build/uarpassetmanagerd.build/Objects-normal/arm64e/UARPAssetManagerServiceInstance-b3842435c2c82172377d4b0b45f2a480.o
- _objc_msgSend$initWithProductGroup:productNumber:containerID:releaseNotesAsset:downloadOnCellularAllowed:domain:
CStrings:
+ "%s: Failed to read managedPrefs at %@ error %@"
+ "+[UARPAssetSubscriptioniCloud developmentEnvironmentForContainerID:]"
+ "+[UARPAssetSubscriptioniCloud resolvedContainerIDForContainerID:]"
+ "/Library/Managed Preferences/mobile/com.apple.UARPiCloud.plist"
+ "165413ff-a1b0-4e64-b0a0-25ca4fa99e4a"
+ "<%@: pgpn=%@-%@, containerID=%@ releaseNotes=%@ development=%@ domain=%@>"
+ "@60@0:8@16@24@32B40B44B48@52"
+ "TB,R,V_developmentEnvironment"
+ "_developmentEnvironment"
+ "cacheSubdirectoryForContainerID:developmentEnvironment:"
+ "com.apple.UARPiCloud"
+ "com.apple.chip"
+ "containsString:"
+ "development"
+ "developmentEnvironment"
+ "developmentEnvironmentForContainerID:"
+ "initWithContentsOfURL:error:"
+ "initWithProductGroup:productNumber:containerID:releaseNotesAsset:downloadOnCellularAllowed:developmentEnvironment:domain:"
+ "pathWithComponents:"
+ "resolvedContainerIDForContainerID:"
+ "stringByAppendingString:"
+ "substringFromIndex:"
+ "usePallas"
- "<%@: pgpn=%@-%@, containerID=%@ releaseNotes=%@ domain=%@>"
- "@56@0:8@16@24@32B40B44@48"
- "initWithProductGroup:productNumber:containerID:releaseNotesAsset:downloadOnCellularAllowed:domain:"
```
