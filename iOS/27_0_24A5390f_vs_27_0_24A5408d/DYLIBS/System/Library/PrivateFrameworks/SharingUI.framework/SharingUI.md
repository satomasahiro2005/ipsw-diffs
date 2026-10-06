## SharingUI

> `/System/Library/PrivateFrameworks/SharingUI.framework/SharingUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaadd8` | `0xab498` | **`+0x6c0`** |
| `__AUTH_CONST.__objc_const` | `0xa2e8` | `0xa528` | **`+0x240`** |
| `__AUTH.__objc_data` | `0x1470` | `0x15b0` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x42e4` | `0x441c` | **`+0x138`** |
| `__DATA_CONST.__objc_selrefs` | `0x3848` | `0x38e8` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x1c60` | `0x1ce0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x4028` | `0x4098` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x1bb8` | `0x1be0` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x268` | `0x288` | **`+0x20`** |

### Other Changes

```diff

-2126.10.4.0.0
+2131.10.1.2.7

-  Functions: 3227
-  Symbols:   3541
-  CStrings:  750
+  Functions: 3250
+  Symbols:   3584
+  CStrings:  754
Symbols:
+ +[SFUIActivityViewControllerConfigurator _platformConfiguratorClass]
+ +[SFUIActivityViewControllerConfigurator adaptivePresentationStyleForTraitCollection:]
+ +[SFUIActivityViewControllerConfigurator popoverWidth]
+ +[SFUIAirDropLayoutMetrics _platformMetricsClass]
+ +[SFUIAirDropLayoutMetrics adjustedPaddingAboveAirDropText:]
+ +[SFUIDevicePickerViewUtilities _platformUtilitiesClass]
+ +[SFUIDevicePickerViewUtilities contextDescriptionForScreen:]
+ +[SFUIDevicePickerViewUtilities heightForAssetNamed:]
+ +[SFUIDevicePickerViewUtilities needsCommunicationsUICoreBundleForAssetNamed:]
+ +[SFUIDevicePickerViewUtilities needsHorizontalFlipForAssetNamed:]
+ +[SFUIDevicePickerViewUtilities needsTopAnchorPointForAssetNamed:]
+ +[SFUIDevicePickerViewUtilities needsVerticalOffsetForAssetNamed:]
+ +[SFUIDevicePickerViewUtilities paddingForAssetNamed:]
+ +[SFUIDevicePickerViewUtilities spacerWidthForAssetNamed:]
+ +[SFUIDevicePickerViewUtilities widthForAssetNamed:]
+ +[SFUINearbySharingInteractionViewMetrics nameDropViewButtonBottomPaddingForHorizontalSizeClass:originalPadding:]
+ +[SFUINearbySharingInteractionViewMetrics nameDropViewButtonSpacingForHorizontalSizeClass:originalSpacing:]
+ +[SFUINearbySharingInteractionViewMetrics nameDropViewButtonTopPaddingForHorizontalSizeClass:originalPadding:]
+ +[SFUINearbySharingInteractionViewMetrics nameDropViewCornerRadiusForRectAlignment:horizontalSizeClass:screenCornerRadius:]
+ +[SFUINearbySharingInteractionViewMetrics nameDropViewStandardHorizontalMarginForHorizontalSizeClass:originalMargin:]
+ +[SFUIProxCardConfigurator _platformConfiguratorClass]
+ +[SFUIProxCardConfigurator shouldFreezeSafeAreas]
+ +[SFUIProxCardConfigurator supportedInterfaceOrientationsForTraitCollection:permitLandscapePhone:]
+ _OBJC_CLASS_$_SFUIActivityViewControllerConfigurator
+ _OBJC_CLASS_$_SFUIAirDropLayoutMetrics
+ _OBJC_CLASS_$_SFUIDevicePickerViewUtilities
+ _OBJC_CLASS_$_SFUIProxCardConfigurator
+ _OBJC_METACLASS_$_SFUIActivityViewControllerConfigurator
+ _OBJC_METACLASS_$_SFUIAirDropLayoutMetrics
+ _OBJC_METACLASS_$_SFUIDevicePickerViewUtilities
+ _OBJC_METACLASS_$_SFUIProxCardConfigurator
+ __OBJC_$_CLASS_METHODS_SFUIActivityViewControllerConfigurator
+ __OBJC_$_CLASS_METHODS_SFUIAirDropLayoutMetrics
+ __OBJC_$_CLASS_METHODS_SFUIDevicePickerViewUtilities
+ __OBJC_$_CLASS_METHODS_SFUIProxCardConfigurator
+ __OBJC_CLASS_RO_$_SFUIActivityViewControllerConfigurator
+ __OBJC_CLASS_RO_$_SFUIAirDropLayoutMetrics
+ __OBJC_CLASS_RO_$_SFUIDevicePickerViewUtilities
+ __OBJC_CLASS_RO_$_SFUIProxCardConfigurator
+ __OBJC_METACLASS_RO_$_SFUIActivityViewControllerConfigurator
+ __OBJC_METACLASS_RO_$_SFUIAirDropLayoutMetrics
+ __OBJC_METACLASS_RO_$_SFUIDevicePickerViewUtilities
+ __OBJC_METACLASS_RO_$_SFUIProxCardConfigurator
CStrings:
+ "SFPActivityViewControllerConfigurator"
+ "SFPAirDropLayoutMetrics"
+ "SFPDevicePickerViewUtilities"
+ "SFPProxCardConfigurator"
```
