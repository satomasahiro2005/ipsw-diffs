## MobileStoreDemoKit

> `/System/Library/PrivateFrameworks/MobileStoreDemoKit.framework/MobileStoreDemoKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d554` | `0x2d4f4` | **`-0x60`** |
| `__AUTH_CONST.__cfstring` | `0x50c0` | `0x50e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x783a` | `0x7858` | **`+0x1e`** |
| `__TEXT.__const` | `0xe0` | `0xe8` | **`+0x8`** |

### Other Changes

```diff

-1865.0.0.0.0
+1871.0.14.0.0

-  CStrings:  1236
+  CStrings:  1237
Functions:
~ -[NSArray(xpcarrayConv) xpcSafeArrayFromArray] : 872 -> 868
~ -[MSDPlatform isValidProductList:] : 560 -> 556
~ -[WhitelistChecker checkManifest:] : 700 -> 720
~ -[WhitelistChecker checkFile_iOS:withMetaData:] : 1340 -> 1372
~ -[WhitelistChecker checkFile_WatchAndTV:withMetaData:] : 288 -> 300
~ -[WhitelistChecker createFullPathList:rootPath:isAllowList:] : 528 -> 524
~ -[WhitelistChecker file:whitelisted:] : 308 -> 304
~ -[WhitelistChecker file:blacklisted:] : 420 -> 416
~ -[WhitelistChecker handleSystemContainerFiles:withMetadata:] : 852 -> 844
~ -[MSDKSignedManifest _parseFactoryBackupList] : 512 -> 508
~ -[MSDKSignedManifest _parseLocale] : 620 -> 616
~ -[MSDKSignedManifest _parseAllFiles] : 776 -> 772
~ -[MSDKSignedManifest _buildAppDepedencies] : 804 -> 800
~ -[MSDKSignedManifest _toComponentDictionary:] : 324 -> 320
~ -[MSDKSignedManifest _addDependenciesForComponent:withLookupDict:] : 812 -> 808
~ -[MSDDemoManifestCheck verifyManifestSignature:forDataSectionKeys:withOptions:] : 3476 -> 3404
~ -[MSDDemoManifestCheck runFileSecurityChecksForSection:dataType:options:] : 2160 -> 2152
~ -[MSDDemoManifestCheck getAllowedISTSignedComponentsFromManifest:] : 944 -> 940
~ -[MSDDemoManifestCheck removeBlocklistedItemFromSection:withName:] : 1032 -> 1024
~ -[MSDKPeerDemoDeviceManager registerPeerEventsObserver:] : 560 -> 556
~ -[MSDKPeerDemoDeviceManager _cleanUpUponXPCDisconnection] : 404 -> 400
~ ___49+[MSDLocalization getLocalizedOwnershipWarnings:]_block_invoke : 1144 -> 1156
~ +[MSDLocalization fillInMissingLocales:withOwnershipWarningMsg:] : 352 -> 348
~ -[MSDKPeerDemoDevice refreshDevicePropertiesUsingProperties:] : 512 -> 508
~ -[NSDictionary(xpcdictConv) createXPCDictionary] : 1092 -> 1088
~ -[MSDKManagedDevice _getCurrentNetworkInfoForKeys:outError:] : 908 -> 904
~ -[MSDKManifestComponent _parseFileItems:] : 516 -> 512
~ __MobileAssetHashAssetData : 108 -> 104
~ __hashCFArray : 396 -> 392
~ __hashCFDictionary : 412 -> 408
~ -[NSData(hexString) hexStringRepresentation] : 156 -> 172
~ -[MSDKSignedManifest _componentListForSection:fromPayload:] : 888 -> 884
CStrings:
+ "/var/mobile/Home/DemoContent/"
```
