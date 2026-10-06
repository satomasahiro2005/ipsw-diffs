## CarPlayUIServices

> `/System/Library/PrivateFrameworks/CarPlayUIServices.framework/CarPlayUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e840` | `0x2f598` | **`+0xd58`** |
| `__AUTH_CONST.__objc_const` | `0x11790` | `0x11950` | **`+0x1c0`** |
| `__TEXT.__objc_methlist` | `0x3814` | `0x38f4` | **`+0xe0`** |
| `__AUTH.__objc_data` | `0x20e0` | `0x2180` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x13e4` | `0x1474` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ad0` | `0x1b30` | **`+0x60`** |
| `__TEXT.__const` | `0x8a4` | `0x904` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xae0` | `0xb30` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x460` | `0x4a4` | **`+0x44`** |
| `__TEXT.__unwind_info` | `0xee8` | `0xf18` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x760` | `0x780` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x5a0` | `0x5b0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x310` | `0x320` | **`+0x10`** |
| `__DATA.__data` | `0x14d8` | `0x14e0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x380` | `0x388` | **`+0x8`** |
| `__TEXT.__swift5_reflstr` | `0x1b9` | `0x1be` | **`+0x5`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-571.3.0.0.0
+574.2.0.0.0

-  Functions: 1462
-  Symbols:   2759
-  CStrings:  382
+  Functions: 1480
+  Symbols:   2797
+  CStrings:  385
Symbols:
+ +[UIColor(CarPlayUIServices_Gradient) crsui_iconGradientColorsWithTintColor:]
+ +[UIImage(CarPlayUIServices) _crsui_renderImage:withSize:scaleFactor:gradientColors:traitCollection:]
+ +[UIImage(CarPlayUIServices) crsui_glassSymbolImageNamed:compatibleWithTraitCollection:]
+ -[CRSUIClusterThemeManager _connectionNotAvailableError]
+ -[CRSUIClusterThemeManager _getDisplayNameForDriveMode:completionHandler:]
+ -[CRSUIClusterThemeManager getDisplayNameForDriveMode:completionHandler:]
+ -[CRSUIClusterThemeService getDisplayNameForDriveMode:completionHandler:]
+ -[CRSUIMutableWallpaperSceneClientSettings copyWithZone:]
+ -[CRSUIMutableWallpaperSceneClientSettings isReady]
+ -[CRSUIMutableWallpaperSceneClientSettings setIsReady:]
+ -[CRSUIWallpaperPreferences _invalidateCurrentWallpaperCache]
+ -[CRSUIWallpaperSceneClientSettings isReady]
+ -[CRSUIWallpaperSceneClientSettings mutableCopyWithZone:]
+ -[CRSUIWallpaperSceneSpecification clientSettingsClass]
+ GCC_except_table23
+ GCC_except_table31
+ _CGColorSpaceCreateDeviceRGB
+ _CGColorSpaceRelease
+ _CGContextDrawLinearGradient
+ _CGGradientCreateWithColors
+ _CGGradientRelease
+ _OBJC_CLASS_$_CRSUIMutableWallpaperSceneClientSettings
+ _OBJC_CLASS_$_CRSUIWallpaperSceneClientSettings
+ _OBJC_IVAR_$_CRSUIWallpaperPreferences._currentWallpaper
+ _OBJC_IVAR_$_CRSUIWallpaperPreferences._currentWallpaperValid
+ _OBJC_METACLASS_$_CRSUIMutableWallpaperSceneClientSettings
+ _OBJC_METACLASS_$_CRSUIWallpaperSceneClientSettings
+ __OBJC_$_CLASS_METHODS_UIColor(CarPlayUIServices|CarPlayUIServices_Gradient)
+ __OBJC_$_INSTANCE_METHODS_CRSUIMutableWallpaperSceneClientSettings
+ __OBJC_$_INSTANCE_METHODS_CRSUIWallpaperSceneClientSettings
+ __OBJC_$_PROP_LIST_CRSUIMutableWallpaperSceneClientSettings
+ __OBJC_$_PROP_LIST_CRSUIWallpaperSceneClientSettings
+ __OBJC_CLASS_RO_$_CRSUIMutableWallpaperSceneClientSettings
+ __OBJC_CLASS_RO_$_CRSUIWallpaperSceneClientSettings
+ __OBJC_METACLASS_RO_$_CRSUIMutableWallpaperSceneClientSettings
+ __OBJC_METACLASS_RO_$_CRSUIWallpaperSceneClientSettings
+ ___101+[UIImage(CarPlayUIServices) _crsui_renderImage:withSize:scaleFactor:gradientColors:traitCollection:]_block_invoke
+ ___73-[CRSUIClusterThemeManager getDisplayNameForDriveMode:completionHandler:]_block_invoke
+ ___73-[CRSUIClusterThemeService getDisplayNameForDriveMode:completionHandler:]_block_invoke
+ ___77+[UIColor(CarPlayUIServices_Gradient) crsui_iconGradientColorsWithTintColor:]_block_invoke
+ ___77+[UIColor(CarPlayUIServices_Gradient) crsui_iconGradientColorsWithTintColor:]_block_invoke_2
+ ___block_descriptor_40_e8_32s_e36_"UIColor"16?0"UITraitCollection"8ls32l8
+ ___block_descriptor_64_e8_32s40s48r56r_e42_v24?0"<CRSUIClusterThemeObserving>"8^B16ls32l8s40l8r48l8r56l8
+ ___block_descriptor_72_e8_32s40s48s_e40_v16?0"UIGraphicsImageRendererContext"8ls32l8s40l8s48l8
- +[UIImage(CarPlayUIServices) _crsui_renderImage:withSize:scaleFactor:backgroundColor:]
- GCC_except_table28
- _UIRectFill
- __OBJC_$_CATEGORY_CLASS_METHODS_UIColor_$_CarPlayUIServices
- ___86+[UIImage(CarPlayUIServices) _crsui_renderImage:withSize:scaleFactor:backgroundColor:]_block_invoke
- ___block_descriptor_64_e8_32s40s_e40_v16?0"UIGraphicsImageRendererContext"8ls32l8s40l8
CStrings:
+ "Display name for drive mode %@: %@"
+ "Error getting display name for drive mode %@: %@"
+ "Received request for display name for drive mode (connection: %@): %@"
```
