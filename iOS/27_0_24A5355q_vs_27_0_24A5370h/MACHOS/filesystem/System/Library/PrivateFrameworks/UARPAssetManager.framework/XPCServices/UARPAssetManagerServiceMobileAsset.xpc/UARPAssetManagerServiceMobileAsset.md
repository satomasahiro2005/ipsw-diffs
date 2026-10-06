## UARPAssetManagerServiceMobileAsset

> `/System/Library/PrivateFrameworks/UARPAssetManager.framework/XPCServices/UARPAssetManagerServiceMobileAsset.xpc/UARPAssetManagerServiceMobileAsset`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc9e0` | `0xf338` | **`+0x2958`** |
| `__TEXT.__objc_stubs` | `0x1bc0` | `0x21e0` | **`+0x620`** |
| `__TEXT.__objc_methname` | `0x1d1f` | `0x2106` | **`+0x3e7`** |
| `__TEXT.__oslogstring` | `0x109f` | `0x1406` | **`+0x367`** |
| `__DATA_CONST.__cfstring` | `0xce0` | `0xf00` | **`+0x220`** |
| `__TEXT.__cstring` | `0xfac` | `0x1134` | **`+0x188`** |
| `__DATA.__objc_selrefs` | `0x840` | `0x9c0` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x340` | `0x390` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x340` | `0x360` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x120` | `0x140` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x470` | `0x490` | **`+0x20`** |
| `__DATA.__bss` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x248` | `0x258` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1576.0.0.0.0
+1587.0.3.0.3

+  - /System/Library/PrivateFrameworks/AUSettings.framework/AUSettings

-  Functions: 292
-  Symbols:   205
-  CStrings:  630
+  Functions: 318
+  Symbols:   225
+  CStrings:  713
Symbols:
+ _AUDeveloperSettingsURLStringToType
+ _AUDeveloperSettingsURLTypeToString
+ _OBJC_CLASS_$_AUDeveloperSettingsDatabase
+ _OBJC_CLASS_$_NSUUID
+ _OBJC_CLASS_$_UARPEndpointPersonalityMobileAsset
+ _OBJC_CLASS_$_UARPSettingsAccessory
+ _assetLocationTypeFromBasePath
+ _correctAssetSettingsForGroup
+ _createPersonalityForSubscription
+ _createSubscriptionForPersonality
+ _currentOSTrainName
+ _generateMobileAssetBaseAddress
+ _getDefaultMesuAddress
+ _getDefaultPallasAudience
+ _getPallasSettingForAccessory
+ _groupAccessoriesForPersonality
+ _isDefaultAssetConfiguration
+ _loadProfileAssetOverrideSettings
+ _loadProfilePallasURLOverrideSetting
+ _setPallasAudienceForSubscription
CStrings:
+ ""
+ "$RC_RELEASE"
+ "$SIDEBUILD_PARENT_TRAIN"
+ "%@ (%@)"
+ "%@/%@"
+ "%@/%@/%@%@"
+ "%s"
+ "%s: Accessory with serial number %{public}@ does not exist"
+ "%s: Cannot group accessories without a serial number for %{public}@"
+ "/Library/Managed Preferences/mobile/com.apple.AUDeveloperSettings.plist"
+ "0206c249-b301-46e0-9d6a-23ce9c5d875d"
+ "0c88076f-c292-4dad-95e7-304db9d29d34"
+ "Cleaning up previous relationship between %@ and %@"
+ "Failed to read profile with error %{public}@"
+ "Invalid asset location for subscription %{public}@"
+ "Invalid pallas audience detected for asset %{public}@"
+ "Invalid profile asset URL override %{public}@"
+ "No Settings Entry found for personality %{public}@"
+ "Only mobile asset accessory personalities are currently supported"
+ "Only mobile asset accessory subscriptions are currently supported"
+ "Release"
+ "Setting %{public}@ as the new primary for %{public}@"
+ "Setting %{public}@ with final list  %{public}@"
+ "URLWithString:"
+ "UnknownPlatform"
+ "Updating Asset Location for %{public}@ to %{public}@"
+ "Updating Settings Entry with personality %{public}@"
+ "Using %{public}@ for subscription %{public}@"
+ "Using profile settings for asset %{public}@ and url %{public}@"
+ "assetLocation"
+ "assetURLOverride"
+ "b1f792b1-0797-48f1-8603-107cefcf1d45"
+ "ce9c2203-903b-4fb3-9f03-040dc2202694"
+ "copyAccessoryWithSerialNumber:directMatchOnly:"
+ "copyAssetLocationSettings:"
+ "customBuild"
+ "customTrain"
+ "dictionaryWithContentsOfURL:error:"
+ "friendlyName"
+ "groupAccessoriesForPersonality"
+ "http"
+ "https://mesu.apple.com/assets"
+ "hwRevision"
+ "initWithAppleModelNumber:serialNumber:hwFusing:domain:"
+ "initWithFormat:"
+ "initWithUUIDString:"
+ "isAssetLocationSettingsEqual:"
+ "lowercaseString"
+ "mobileAssetAppleModelNumber"
+ "models"
+ "name"
+ "otaDisabled"
+ "pallasAudience"
+ "pallasAudienceOverride"
+ "pallasInternalAssetVariant"
+ "pallasSupportEnabled"
+ "pallasURL"
+ "parentSerialNumber"
+ "partnerSerialNumbers"
+ "remoteAccessoryList"
+ "removeObjectAtIndex:"
+ "serialNumber"
+ "setActiveVersion:"
+ "setAssetLocation:"
+ "setAssetURLOverride:"
+ "setHwFusing:"
+ "setHwRevision:"
+ "setMobileAssetModelNumber:"
+ "setModelNumber:"
+ "setName:"
+ "setPallasAudience:"
+ "setPallasInternalAssetVariant:"
+ "setPallasSupportEnabled:"
+ "setParentSerialNumber:"
+ "setPartnerSerialNumbers:"
+ "setSerialNumber:"
+ "setSoftwareUpdateAsset:"
+ "setSoftwareUpdateAssetType:"
+ "setSoftwareUpdateEraseInstall:"
+ "sharedDatabase"
+ "softwareUpdateAsset"
+ "stringWithUTF8String:"
+ "updateAccessory:"
```
