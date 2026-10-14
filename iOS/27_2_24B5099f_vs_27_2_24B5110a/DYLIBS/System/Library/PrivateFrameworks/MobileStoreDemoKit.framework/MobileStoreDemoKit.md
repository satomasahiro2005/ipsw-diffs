## MobileStoreDemoKit

> `/System/Library/PrivateFrameworks/MobileStoreDemoKit.framework/MobileStoreDemoKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2db94` | `0x2e124` | **`+0x590`** |
| `__TEXT.__oslogstring` | `0x399c` | `0x3ac6` | **`+0x12a`** |
| `__AUTH_CONST.__objc_const` | `0x3908` | `0x3a08` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0x5320` | `0x53e0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x7d1e` | `0x7dc4` | **`+0xa6`** |
| `__AUTH.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x2594` | `0x25e4` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x1988` | `0x19c0` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0x248` | `0x250` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2f0` | `0x2f8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xe0` | `0xe8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xc0` | `0xc8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xbe0` | `0xbe8` | **`+0x8`** |

### Other Changes

```diff

-1871.40.61.0.0
+1871.40.62.0.0

-  Functions: 1219
-  Symbols:   1719
-  CStrings:  1260
+  Functions: 1228
+  Symbols:   1734
+  CStrings:  1272
Symbols:
+ +[MSDKDemoOverlayAsset demoOverlayAssetForApplicationWithBundleIdentifier:]
+ -[MSDKDemoOverlayAsset .cxx_destruct]
+ -[MSDKDemoOverlayAsset assetPath]
+ -[MSDKDemoOverlayAsset assetType]
+ -[MSDKDemoOverlayAsset initWithAssetType:andAssetPath:]
+ _OBJC_CLASS_$_MSDKDemoOverlayAsset
+ _OBJC_IVAR_$_MSDKDemoOverlayAsset._assetPath
+ _OBJC_IVAR_$_MSDKDemoOverlayAsset._assetType
+ _OBJC_METACLASS_$_MSDKDemoOverlayAsset
+ __OBJC_$_CLASS_METHODS_MSDKDemoOverlayAsset
+ __OBJC_$_INSTANCE_METHODS_MSDKDemoOverlayAsset
+ __OBJC_$_INSTANCE_VARIABLES_MSDKDemoOverlayAsset
+ __OBJC_$_PROP_LIST_MSDKDemoOverlayAsset
+ __OBJC_CLASS_RO_$_MSDKDemoOverlayAsset
+ __OBJC_METACLASS_RO_$_MSDKDemoOverlayAsset
CStrings:
+ "%s - Failed to open asset preferences file %{public}@ - %{public}@"
+ "%s - No overlay assets found at path %{public}@ for app  %{public}@"
+ "%s - Unrecognized preferred overlay asset type: %{public}@ - Default to Image."
+ "%s - assetPath:  %{public}@ - Asset type:  %ld"
+ "%s - preferredAssetType:  %{public}@"
+ "+[MSDKDemoOverlayAsset demoOverlayAssetForApplicationWithBundleIdentifier:]"
+ ".mov"
+ ".png"
+ "/var/mobile/Library/RetailDemo/OverlayAssets"
+ "AssetPreferences.plist"
+ "Image"
+ "Video"
```
