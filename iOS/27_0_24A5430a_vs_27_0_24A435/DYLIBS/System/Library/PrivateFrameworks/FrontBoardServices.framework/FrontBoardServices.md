## FrontBoardServices

> `/System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x98a4c` | `0x996d8` | **`+0xc8c`** |
| `__TEXT.__cstring` | `0xc0b0` | `0xc425` | **`+0x375`** |
| `__AUTH_CONST.__objc_const` | `0x100f8` | `0x10458` | **`+0x360`** |
| `__AUTH_CONST.__cfstring` | `0xa2e0` | `0xa540` | **`+0x260`** |
| `__TEXT.__objc_methlist` | `0x8688` | `0x87a8` | **`+0x120`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d68` | `0x3e70` | **`+0x108`** |
| `__DATA_DIRTY.__objc_data` | `0x1fe0` | `0x2080` | **`+0xa0`** |
| `__AUTH_CONST.__objc_intobj` | `0x48` | `0x90` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x840` | `0x880` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x2ad8` | `0x2b18` | **`+0x40`** |
| `__DATA_DIRTY.__bss` | `0x1c8` | `0x1f8` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x878` | `0x888` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x490` | `0x4a0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x738` | `0x740` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 4380
-  Symbols:   6495
-  CStrings:  1938
+  Functions: 4407
+  Symbols:   6543
+  CStrings:  1974
Symbols:
+ +[FBSDeviceEmulationConfiguration _forceIsD22ChecksToPass]
+ +[FBSDeviceEmulationConfiguration _isEmulatedDeviceViaDefaults]
+ +[FBSDeviceEmulationConfiguration _isEmulatedDeviceViaGestalt]
+ +[FBSDeviceEmulationConfiguration _sharedDefaults]
+ +[FBSDeviceEmulationConfiguration customScaleFactorX]
+ +[FBSDeviceEmulationConfiguration customScaleFactorY]
+ +[FBSDeviceEmulationConfiguration customTranslationOffsetX]
+ +[FBSDeviceEmulationConfiguration customTranslationOffsetY]
+ +[FBSDeviceEmulationConfiguration deviceEmulationVersion]
+ +[FBSDeviceEmulationConfiguration emulatedArtworkSubtype]
+ +[FBSDeviceEmulationConfiguration emulatedDeviceBezelImageName]
+ +[FBSDeviceEmulationConfiguration emulatedDeviceBounds]
+ +[FBSDeviceEmulationConfiguration emulatedDeviceClass]
+ +[FBSDeviceEmulationConfiguration emulatedDeviceImageContainingBundle]
+ +[FBSDeviceEmulationConfiguration emulatedDeviceMaskImageName]
+ +[FBSDeviceEmulationConfiguration emulatedDisplayCornerRadius]
+ +[FBSDeviceEmulationConfiguration emulatedHomeButtonType]
+ +[FBSDeviceEmulationConfiguration hasEmulatedDeviceBounds]
+ +[FBSDeviceEmulationConfiguration isEmulatedDevice]
+ +[FBSDeviceEmulationConfiguration rootLayerBackgroundColorString]
+ +[FBSDeviceEmulationConfiguration scalingStyle]
+ -[FBSDeviceEmulationDefaults _bindAndRegisterDefaults]
+ _MGGetBoolAnswer
+ _OBJC_CLASS_$_BSAbstractDefaultDomain
+ _OBJC_CLASS_$_FBSDeviceEmulationConfiguration
+ _OBJC_CLASS_$_FBSDeviceEmulationDefaults
+ _OBJC_METACLASS_$_BSAbstractDefaultDomain
+ _OBJC_METACLASS_$_FBSDeviceEmulationConfiguration
+ _OBJC_METACLASS_$_FBSDeviceEmulationDefaults
+ __OBJC_$_CLASS_METHODS_FBSDeviceEmulationConfiguration
+ __OBJC_$_CLASS_PROP_LIST_FBSDeviceEmulationConfiguration
+ __OBJC_$_INSTANCE_METHODS_FBSDeviceEmulationDefaults
+ __OBJC_$_PROP_LIST_FBSDeviceEmulationDefaults
+ __OBJC_CLASS_RO_$_FBSDeviceEmulationConfiguration
+ __OBJC_CLASS_RO_$_FBSDeviceEmulationDefaults
+ __OBJC_METACLASS_RO_$_FBSDeviceEmulationConfiguration
+ __OBJC_METACLASS_RO_$_FBSDeviceEmulationDefaults
+ ___50+[FBSDeviceEmulationConfiguration _sharedDefaults]_block_invoke
+ ___62+[FBSDeviceEmulationConfiguration _isEmulatedDeviceViaGestalt]_block_invoke
+ ___63+[FBSDeviceEmulationConfiguration _isEmulatedDeviceViaDefaults]_block_invoke
+ ___kCFBooleanFalse
+ __isEmulatedDeviceViaDefaults.isEmulatedViaDefaults
+ __isEmulatedDeviceViaDefaults.onceToken
+ __isEmulatedDeviceViaGestalt.onceToken
+ __isEmulatedDeviceViaGestalt.sIsEmulatedDevice
+ __sharedDefaults.onceToken
+ __sharedDefaults.sEmulationDefaults
+ _os_variant_has_internal_diagnostics
CStrings:
+ "FBSBezelImageName"
+ "FBSCustomXScaleFactor"
+ "FBSCustomXTranslationOffset"
+ "FBSCustomYScaleFactor"
+ "FBSCustomYTranslationOffset"
+ "FBSDeviceEmulationBackgroundColorString"
+ "FBSDeviceEmulationScalingStyle"
+ "FBSEmulatedArtworkSubtype"
+ "FBSEmulatedDeviceClass"
+ "FBSEmulatedDisplayCornerRadius"
+ "FBSEmulatedDisplayHeight"
+ "FBSEmulatedDisplayWidth"
+ "FBSEmulatedHomeButtonType"
+ "FBSEnableDeviceEmulation"
+ "FBSForceIsD22ChecksToPass"
+ "FBSImageContainingBundleIdentifier"
+ "FBSMaskImageName"
+ "bezelImageName"
+ "com.apple.frontboardservices.device_emulation"
+ "customScaleFactorX"
+ "customScaleFactorY"
+ "customTranslationOffsetX"
+ "customTranslationOffsetY"
+ "emulatedArtworkSubtype"
+ "emulatedDeviceClass"
+ "emulatedDisplayCornerRadius"
+ "emulatedDisplayHeight"
+ "emulatedDisplayWidth"
+ "emulatedHomeButtonType"
+ "enableEmulation"
+ "forceIsD22ChecksToPass"
+ "imageContainingBundleIdentifier"
+ "maskImageName"
+ "rootLayerBackgroundColorString"
+ "scalingStyle"
+ "z5G/N9jcMdgPm8UegLwbKg"
```
