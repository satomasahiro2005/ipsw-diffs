## FrontBoardServices

> `/System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x996d8` | `0x98c98` | **`-0xa40`** |
| `__AUTH_CONST.__objc_const` | `0x10458` | `0x100f8` | **`-0x360`** |
| `__TEXT.__cstring` | `0xc425` | `0xc104` | **`-0x321`** |
| `__AUTH_CONST.__cfstring` | `0xa540` | `0xa320` | **`-0x220`** |
| `__TEXT.__objc_methlist` | `0x87a8` | `0x8688` | **`-0x120`** |
| `__DATA_CONST.__objc_selrefs` | `0x3e70` | `0x3d68` | **`-0x108`** |
| `__DATA_DIRTY.__objc_data` | `0x2080` | `0x1fe0` | **`-0xa0`** |
| `__AUTH_CONST.__objc_intobj` | `0x90` | `0x48` | **`-0x48`** |
| `__AUTH_CONST.__const` | `0x880` | `0x840` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x2b18` | `0x2ae0` | **`-0x38`** |
| `__DATA_DIRTY.__bss` | `0x1f8` | `0x1c8` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0x888` | `0x878` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x4a0` | `0x490` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x3128` | `0x3130` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x740` | `0x738` | **`-0x8`** |

### Other Changes

```diff

-1153.0.1.0.0
+1153.2.1.0.0

-  Functions: 4407
-  Symbols:   6543
-  CStrings:  1974
+  Functions: 4379
+  Symbols:   6496
+  CStrings:  1940
Symbols:
+ _FBSDebugOptionKeyDeveloperToolsOptions
- +[FBSDeviceEmulationConfiguration _forceIsD22ChecksToPass]
- +[FBSDeviceEmulationConfiguration _isEmulatedDeviceViaDefaults]
- +[FBSDeviceEmulationConfiguration _isEmulatedDeviceViaGestalt]
- +[FBSDeviceEmulationConfiguration _sharedDefaults]
- +[FBSDeviceEmulationConfiguration customScaleFactorX]
- +[FBSDeviceEmulationConfiguration customScaleFactorY]
- +[FBSDeviceEmulationConfiguration customTranslationOffsetX]
- +[FBSDeviceEmulationConfiguration customTranslationOffsetY]
- +[FBSDeviceEmulationConfiguration deviceEmulationVersion]
- +[FBSDeviceEmulationConfiguration emulatedArtworkSubtype]
- +[FBSDeviceEmulationConfiguration emulatedDeviceBezelImageName]
- +[FBSDeviceEmulationConfiguration emulatedDeviceBounds]
- +[FBSDeviceEmulationConfiguration emulatedDeviceClass]
- +[FBSDeviceEmulationConfiguration emulatedDeviceImageContainingBundle]
- +[FBSDeviceEmulationConfiguration emulatedDeviceMaskImageName]
- +[FBSDeviceEmulationConfiguration emulatedDisplayCornerRadius]
- +[FBSDeviceEmulationConfiguration emulatedHomeButtonType]
- +[FBSDeviceEmulationConfiguration hasEmulatedDeviceBounds]
- +[FBSDeviceEmulationConfiguration isEmulatedDevice]
- +[FBSDeviceEmulationConfiguration rootLayerBackgroundColorString]
- +[FBSDeviceEmulationConfiguration scalingStyle]
- -[FBSDeviceEmulationDefaults _bindAndRegisterDefaults]
- _MGGetBoolAnswer
- _OBJC_CLASS_$_BSAbstractDefaultDomain
- _OBJC_CLASS_$_FBSDeviceEmulationConfiguration
- _OBJC_CLASS_$_FBSDeviceEmulationDefaults
- _OBJC_METACLASS_$_BSAbstractDefaultDomain
- _OBJC_METACLASS_$_FBSDeviceEmulationConfiguration
- _OBJC_METACLASS_$_FBSDeviceEmulationDefaults
- __OBJC_$_CLASS_METHODS_FBSDeviceEmulationConfiguration
- __OBJC_$_CLASS_PROP_LIST_FBSDeviceEmulationConfiguration
- __OBJC_$_INSTANCE_METHODS_FBSDeviceEmulationDefaults
- __OBJC_$_PROP_LIST_FBSDeviceEmulationDefaults
- __OBJC_CLASS_RO_$_FBSDeviceEmulationConfiguration
- __OBJC_CLASS_RO_$_FBSDeviceEmulationDefaults
- __OBJC_METACLASS_RO_$_FBSDeviceEmulationConfiguration
- __OBJC_METACLASS_RO_$_FBSDeviceEmulationDefaults
- ___50+[FBSDeviceEmulationConfiguration _sharedDefaults]_block_invoke
- ___62+[FBSDeviceEmulationConfiguration _isEmulatedDeviceViaGestalt]_block_invoke
- ___63+[FBSDeviceEmulationConfiguration _isEmulatedDeviceViaDefaults]_block_invoke
- ___kCFBooleanFalse
- __isEmulatedDeviceViaDefaults.isEmulatedViaDefaults
- __isEmulatedDeviceViaDefaults.onceToken
- __isEmulatedDeviceViaGestalt.onceToken
- __isEmulatedDeviceViaGestalt.sIsEmulatedDevice
- __sharedDefaults.onceToken
- __sharedDefaults.sEmulationDefaults
- _os_variant_has_internal_diagnostics
CStrings:
+ "OSLaunchdDeveloperToolsOptions"
+ "There should be no more update completions (%lu remaining for diff: %@)."
+ "__DeveloperToolsOptions"
- "FBSBezelImageName"
- "FBSCustomXScaleFactor"
- "FBSCustomXTranslationOffset"
- "FBSCustomYScaleFactor"
- "FBSCustomYTranslationOffset"
- "FBSDeviceEmulationBackgroundColorString"
- "FBSDeviceEmulationScalingStyle"
- "FBSEmulatedArtworkSubtype"
- "FBSEmulatedDeviceClass"
- "FBSEmulatedDisplayCornerRadius"
- "FBSEmulatedDisplayHeight"
- "FBSEmulatedDisplayWidth"
- "FBSEmulatedHomeButtonType"
- "FBSEnableDeviceEmulation"
- "FBSForceIsD22ChecksToPass"
- "FBSImageContainingBundleIdentifier"
- "FBSMaskImageName"
- "There should be no more update completions."
- "bezelImageName"
- "com.apple.frontboardservices.device_emulation"
- "customScaleFactorX"
- "customScaleFactorY"
- "customTranslationOffsetX"
- "customTranslationOffsetY"
- "emulatedArtworkSubtype"
- "emulatedDeviceClass"
- "emulatedDisplayCornerRadius"
- "emulatedDisplayHeight"
- "emulatedDisplayWidth"
- "emulatedHomeButtonType"
- "enableEmulation"
- "forceIsD22ChecksToPass"
- "imageContainingBundleIdentifier"
- "maskImageName"
- "rootLayerBackgroundColorString"
- "scalingStyle"
- "z5G/N9jcMdgPm8UegLwbKg"
```
