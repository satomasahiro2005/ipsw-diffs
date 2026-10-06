## DeviceAccess

> `/System/Library/PrivateFrameworks/DeviceAccess.framework/DeviceAccess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1088` | `0x98` | **`-0xff0`** |
| `__DATA_DIRTY.__objc_data` | `0x2a8` | `0x1298` | **`+0xff0`** |
| `__TEXT.__text` | `0x54708` | `0x549e4` | **`+0x2dc`** |
| `__DATA_DIRTY.__data` | `0x70` | `0x270` | **`+0x200`** |
| `__AUTH.__data` | `0x258` | `0x90` | **`-0x1c8`** |
| `__AUTH_CONST.__objc_const` | `0x7fa0` | `0x8060` | **`+0xc0`** |
| `__TEXT.__cstring` | `0xa0e3` | `0xa143` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x467c` | `0x46c4` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x3580` | `0x35c0` | **`+0x40`** |
| `__DATA.__data` | `0xc40` | `0xc08` | **`-0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f70` | `0x1f98` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x70c` | `0x71c` | **`+0x10`** |

### Other Changes

```diff

-2700.27.0.0.0
+2700.30.0.0.0

-  Functions: 2294
-  Symbols:   3339
-  CStrings:  1508
+  Functions: 2300
+  Symbols:   3349
+  CStrings:  1511
Symbols:
+ -[DAAppAsset distributorBundleID]
+ -[DAAppAsset initWithBundleID:adamID:appName:developerName:iconData:distributorBundleID:]
+ -[DADevice preUpgradeDiscoveryConfiguration]
+ -[DADevice setPreUpgradeDiscoveryConfiguration:]
+ -[DADeviceRegistry initWithManufacturerID:modelID:friendlyName:image2xData:image3xData:videoURL:companionAppBundleID:companionAppIsOptional:supportedFeatures:manufacturerURL:supportedModes:]
+ -[DADeviceRegistry manufacturerURL]
+ -[DADeviceRegistryInfo manufacturerURL]
+ -[DADeviceRegistryInfo setManufacturerURL:]
+ _OBJC_IVAR_$_DAAppAsset._distributorBundleID
+ _OBJC_IVAR_$_DADevice._preUpgradeDiscoveryConfiguration
+ _OBJC_IVAR_$_DADeviceRegistry._manufacturerURL
+ _OBJC_IVAR_$_DADeviceRegistryInfo._manufacturerURL
- -[DAAppAsset initWithBundleID:adamID:appName:developerName:iconData:]
- -[DADeviceRegistry initWithManufacturerID:modelID:friendlyName:image2xData:image3xData:videoURL:companionAppBundleID:companionAppIsOptional:supportedFeatures:supportedModes:]
CStrings:
+ "<%@: %p; friendlyName=%@; image2x=%@; image3x=%@; videoURL=%@; companionAppBundleID=%@; companionAppIsOptional=%@; manufacturerURL=%@; supportedFeatures=%@ supportedMode=%@>"
+ "<%@: %p; manufacturerID=%@; modelID=%@; friendlyName=%@; image2x=%@; image3x=%@; videoURL=%@; companionAppBundleID=%@; companionAppIsOptional=%@; manufacturerURL=%@; supportedFeatures=%@; supportedMode=%@>"
+ "<DAAppAsset bundleID=%@ adamID=%@ appName=%@ developerName=%@ distributor=%@ iconSize=%lu cached=%@>"
+ "distributorBundleID"
+ "drMU"
+ "dsBd"
- "<%@: %p; friendlyName=%@; image2x=%@; image3x=%@; videoURL=%@; companionAppBundleID=%@; companionAppIsOptional=%@; supportedFeatures=%@ supportedMode=%@>"
- "<%@: %p; manufacturerID=%@; modelID=%@; friendlyName=%@; image2x=%@; image3x=%@; videoURL=%@; companionAppBundleID=%@; companionAppIsOptional=%@; supportedFeatures=%@; supportedMode=%@>"
- "<DAAppAsset bundleID=%@ adamID=%@ appName=%@ developerName=%@  iconSize=%lu cached=%@>"
```
