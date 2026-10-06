## SpringBoardServices

> `/System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x260a8` | `0x279a8` | **`+0x1900`** |
| `__TEXT.__text` | `0x7b5fc` | `0x7caec` | **`+0x14f0`** |
| `__TEXT.__objc_methlist` | `0x8b58` | `0x8e58` | **`+0x300`** |
| `__TEXT.__oslogstring` | `0x490e` | `0x4b4a` | **`+0x23c`** |
| `__AUTH.__objc_data` | `0x3ac0` | `0x3ca0` | **`+0x1e0`** |
| `__DATA.__data` | `0x2210` | `0x2390` | **`+0x180`** |
| `__DATA_CONST.__objc_selrefs` | `0x3490` | `0x35a8` | **`+0x118`** |
| `__TEXT.__cstring` | `0xde60` | `0xdf69` | **`+0x109`** |
| `__DATA_CONST.__const` | `0x3908` | `0x3978` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x29f8` | `0x2a60` | **`+0x68`** |
| `__AUTH_CONST.__cfstring` | `0xaea0` | `0xaee0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0xcbc` | `0xcf8` | **`+0x3c`** |
| `__DATA_CONST.__objc_classlist` | `0x6d0` | `0x700` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x8c0` | `0x8e8` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x2908` | `0x2928` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x874` | `0x894` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x2c0` | `0x2e0` | **`+0x20`** |
| `__DATA_CONST.__objc_protorefs` | `0x1b8` | `0x1d0` | **`+0x18`** |
| `__DATA.__bss` | `0x900` | `0x910` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x488` | `0x498` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x268` | `0x278` | **`+0x10`** |
| `__DATA_CONST.__objc_catlist` | `0x20` | `0x28` | **`+0x8`** |

### Other Changes

```diff

-4630.1.102.0.0
+4636.102.1.0.0

-  Functions: 4302
-  Symbols:   7921
-  CStrings:  2126
+  Functions: 4359
+  Symbols:   8055
+  CStrings:  2137
Symbols:
+ +[SBSFDIDeviceControlClientSettingsExtension protocol]
+ +[SBSFDIDeviceControlSceneExtension clientComponents]
+ +[SBSFDIDeviceControlSceneExtension clientSettingsExtensions]
+ +[SBSFDIDeviceControlSceneExtension hostComponents]
+ +[SBSSecureIndicatorElevationAssertionServiceSpecification identifier]
+ +[SBSSecureIndicatorElevationAssertionServiceSpecification interface]
+ +[SBSSecureIndicatorElevationAssertionServiceSpecification serviceQuality]
+ -[FBSScene(SBSFDIDeviceControl) sbs_fdiDeviceControlComponent]
+ -[SBSFDIDeviceControlClientComponent disablesLiftToWake]
+ -[SBSFDIDeviceControlClientComponent disablesTapToWake]
+ -[SBSFDIDeviceControlClientComponent restrictsToConfigurationA]
+ -[SBSFDIDeviceControlClientComponent setDisablesLiftToWake:]
+ -[SBSFDIDeviceControlClientComponent setDisablesTapToWake:]
+ -[SBSFDIDeviceControlClientComponent setRestrictsToConfigurationA:]
+ -[SBSFDIDeviceControlHostComponent .cxx_destruct]
+ -[SBSFDIDeviceControlHostComponent _clientSettings]
+ -[SBSFDIDeviceControlHostComponent coordinator]
+ -[SBSFDIDeviceControlHostComponent disablesLiftToWake]
+ -[SBSFDIDeviceControlHostComponent disablesTapToWake]
+ -[SBSFDIDeviceControlHostComponent invalidate]
+ -[SBSFDIDeviceControlHostComponent restrictsToConfigurationA]
+ -[SBSFDIDeviceControlHostComponent scene:didUpdateClientSettings:]
+ -[SBSFDIDeviceControlHostComponent setCoordinator:]
+ -[SBSHomeScreenService canSwapApplicationIconsInProminentPositionsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:]
+ -[SBSHomeScreenService replaceApplicationIconsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:]
+ -[SBSHomeScreenService swapApplicationIconsInProminentPositionsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:]
+ -[SBSHomeScreenService tearDownAndResetRootIconLists]
+ -[SBSLockScreenContentAction abortForUsageViolation:]
+ -[SBSRelaunchAction abortForUsageViolation:]
+ -[SBSRemoteAlertActivationContext deviceCanBeTreatedAsEffectivelyLocked]
+ -[SBSRemoteAlertActivationContext setDeviceCanBeTreatedAsEffectivelyLocked:]
+ -[SBSSecureIndicatorElevationAssertion .cxx_destruct]
+ -[SBSSecureIndicatorElevationAssertion _sendCurrentStyle]
+ -[SBSSecureIndicatorElevationAssertion dealloc]
+ -[SBSSecureIndicatorElevationAssertion initWithStyle:reason:]
+ -[SBSSecureIndicatorElevationAssertion invalidate]
+ -[SBSSecureIndicatorElevationAssertion setStyle:]
+ -[SBSSecureIndicatorElevationAssertion style]
+ -[SBSSystemNotesConnectAction abortForUsageViolation:]
+ -[SBSSystemNotesCreateAction abortForUsageViolation:]
+ -[SBSSystemNotesTakeScreenshotAction abortForUsageViolation:]
+ _OBJC_CLASS_$_FBSScene
+ _OBJC_CLASS_$_FBSSceneComponent
+ _OBJC_CLASS_$_FBSSceneExtension
+ _OBJC_CLASS_$_FBSSettingsExtension
+ _OBJC_CLASS_$_SBSFDIDeviceControlClientComponent
+ _OBJC_CLASS_$_SBSFDIDeviceControlClientSettingsExtension
+ _OBJC_CLASS_$_SBSFDIDeviceControlHostComponent
+ _OBJC_CLASS_$_SBSFDIDeviceControlSceneExtension
+ _OBJC_CLASS_$_SBSSecureIndicatorElevationAssertion
+ _OBJC_CLASS_$_SBSSecureIndicatorElevationAssertionServiceSpecification
+ _OBJC_IVAR_$_SBSFDIDeviceControlHostComponent._coordinator
+ _OBJC_IVAR_$_SBSRemoteAlertActivationContext._deviceCanBeTreatedAsEffectivelyLocked
+ _OBJC_IVAR_$_SBSSecureIndicatorElevationAssertion._connection
+ _OBJC_IVAR_$_SBSSecureIndicatorElevationAssertion._connectionQueue
+ _OBJC_IVAR_$_SBSSecureIndicatorElevationAssertion._isValid
+ _OBJC_IVAR_$_SBSSecureIndicatorElevationAssertion._reason
+ _OBJC_IVAR_$_SBSSecureIndicatorElevationAssertion._style
+ _OBJC_IVAR_$_SBSSecureIndicatorElevationAssertion._styleLock
+ _OBJC_METACLASS_$_FBSSceneComponent
+ _OBJC_METACLASS_$_FBSSceneExtension
+ _OBJC_METACLASS_$_FBSSettingsExtension
+ _OBJC_METACLASS_$_SBSFDIDeviceControlClientComponent
+ _OBJC_METACLASS_$_SBSFDIDeviceControlClientSettingsExtension
+ _OBJC_METACLASS_$_SBSFDIDeviceControlHostComponent
+ _OBJC_METACLASS_$_SBSFDIDeviceControlSceneExtension
+ _OBJC_METACLASS_$_SBSSecureIndicatorElevationAssertion
+ _OBJC_METACLASS_$_SBSSecureIndicatorElevationAssertionServiceSpecification
+ _SBLogFDIDeviceControl
+ _SBLogFDIDeviceControl.__logObj
+ _SBLogFDIDeviceControl.onceToken
+ __OBJC_$_CATEGORY_FBSScene_$_SBSFDIDeviceControl
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_FBSScene_$_SBSFDIDeviceControl
+ __OBJC_$_CLASS_METHODS_SBSFDIDeviceControlClientSettingsExtension
+ __OBJC_$_CLASS_METHODS_SBSFDIDeviceControlSceneExtension
+ __OBJC_$_CLASS_METHODS_SBSSecureIndicatorElevationAssertionServiceSpecification
+ __OBJC_$_CLASS_PROP_LIST_SBSSecureIndicatorElevationAssertionServiceSpecification
+ __OBJC_$_INSTANCE_METHODS_SBSFDIDeviceControlClientComponent
+ __OBJC_$_INSTANCE_METHODS_SBSFDIDeviceControlHostComponent
+ __OBJC_$_INSTANCE_METHODS_SBSSecureIndicatorElevationAssertion
+ __OBJC_$_INSTANCE_VARIABLES_SBSFDIDeviceControlHostComponent
+ __OBJC_$_INSTANCE_VARIABLES_SBSSecureIndicatorElevationAssertion
+ __OBJC_$_PROP_LIST_FBSScene_$_SBSFDIDeviceControl
+ __OBJC_$_PROP_LIST_SBSFDIDeviceControlClientComponent
+ __OBJC_$_PROP_LIST_SBSFDIDeviceControlClientSettings
+ __OBJC_$_PROP_LIST_SBSFDIDeviceControlHostComponent
+ __OBJC_$_PROP_LIST_SBSFDIDeviceControlMutableClientSettings
+ __OBJC_$_PROP_LIST_SBSSecureIndicatorElevationAssertion
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SBSFDIDeviceControlClientSettings
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SBSFDIDeviceControlMutableClientSettings
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SBSSecureIndicatorElevationAssertionServerInterface
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SBSFDIDeviceControlClientSettings
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SBSFDIDeviceControlMutableClientSettings
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SBSSecureIndicatorElevationAssertionServerInterface
+ __OBJC_$_PROTOCOL_REFS_SBSFDIDeviceControlClientSettings
+ __OBJC_$_PROTOCOL_REFS_SBSFDIDeviceControlMutableClientSettings
+ __OBJC_$_PROTOCOL_REFS_SBSSecureIndicatorElevationAssertionClientInterface
+ __OBJC_$_PROTOCOL_REFS_SBSSecureIndicatorElevationAssertionServerInterface
+ __OBJC_CLASS_PROTOCOLS_$_SBSFDIDeviceControlClientComponent
+ __OBJC_CLASS_PROTOCOLS_$_SBSFDIDeviceControlHostComponent
+ __OBJC_CLASS_PROTOCOLS_$_SBSSecureIndicatorElevationAssertion
+ __OBJC_CLASS_RO_$_SBSFDIDeviceControlClientComponent
+ __OBJC_CLASS_RO_$_SBSFDIDeviceControlClientSettingsExtension
+ __OBJC_CLASS_RO_$_SBSFDIDeviceControlHostComponent
+ __OBJC_CLASS_RO_$_SBSFDIDeviceControlSceneExtension
+ __OBJC_CLASS_RO_$_SBSSecureIndicatorElevationAssertion
+ __OBJC_CLASS_RO_$_SBSSecureIndicatorElevationAssertionServiceSpecification
+ __OBJC_LABEL_PROTOCOL_$_SBSFDIDeviceControlClientSettings
+ __OBJC_LABEL_PROTOCOL_$_SBSFDIDeviceControlMutableClientSettings
+ __OBJC_LABEL_PROTOCOL_$_SBSSecureIndicatorElevationAssertionClientInterface
+ __OBJC_LABEL_PROTOCOL_$_SBSSecureIndicatorElevationAssertionServerInterface
+ __OBJC_METACLASS_RO_$_SBSFDIDeviceControlClientComponent
+ __OBJC_METACLASS_RO_$_SBSFDIDeviceControlClientSettingsExtension
+ __OBJC_METACLASS_RO_$_SBSFDIDeviceControlHostComponent
+ __OBJC_METACLASS_RO_$_SBSFDIDeviceControlSceneExtension
+ __OBJC_METACLASS_RO_$_SBSSecureIndicatorElevationAssertion
+ __OBJC_METACLASS_RO_$_SBSSecureIndicatorElevationAssertionServiceSpecification
+ __OBJC_PROTOCOL_$_SBSFDIDeviceControlClientSettings
+ __OBJC_PROTOCOL_$_SBSFDIDeviceControlMutableClientSettings
+ __OBJC_PROTOCOL_$_SBSSecureIndicatorElevationAssertionClientInterface
+ __OBJC_PROTOCOL_$_SBSSecureIndicatorElevationAssertionServerInterface
+ __OBJC_PROTOCOL_REFERENCE_$_SBSFDIDeviceControlMutableClientSettings
+ __OBJC_PROTOCOL_REFERENCE_$_SBSSecureIndicatorElevationAssertionClientInterface
+ __OBJC_PROTOCOL_REFERENCE_$_SBSSecureIndicatorElevationAssertionServerInterface
+ ___59-[SBSFDIDeviceControlClientComponent setDisablesTapToWake:]_block_invoke
+ ___60-[SBSFDIDeviceControlClientComponent setDisablesLiftToWake:]_block_invoke
+ ___61-[SBSSecureIndicatorElevationAssertion initWithStyle:reason:]_block_invoke
+ ___61-[SBSSecureIndicatorElevationAssertion initWithStyle:reason:]_block_invoke_2
+ ___67-[SBSFDIDeviceControlClientComponent setRestrictsToConfigurationA:]_block_invoke
+ ___69+[SBSSecureIndicatorElevationAssertionServiceSpecification interface]_block_invoke
+ ___SBLogFDIDeviceControl_block_invoke
+ ___block_descriptor_33_e69_v24?0"FBSMutableSceneClientSettings"8"FBSSceneTransitionContext"16l
+ ___block_descriptor_40_e8_32s_e57_v16?0"BSServiceConnection<BSServiceConnectionContext>"8ls32l8
+ ___block_descriptor_56_e8_32s40s48w_e42_v16?0"<BSServiceConnectionConfiguring>"8ls32l8s40l8w48l8
CStrings:
+ "FDIDeviceControl"
+ "SBSFDIDeviceControlHostComponent: client settings changed (liftToWake=%{BOOL}u tapToWake=%{BOOL}u configurationA=%{BOOL}u); updating"
+ "SBSFDIDeviceControlHostComponent: invalidating FDIDeviceControl"
+ "SBSHomeScreenService: failed replaceApplicationIconsWithBundleIdentifier request (no target)."
+ "SBSHomeScreenService: failed tearDownAndResetRootIconLists (no target)."
+ "SBSSecureIndicatorElevationAssertion(%{public}@) connection interrupted. Reactivating."
+ "SBSSecureIndicatorElevationAssertion(%{public}@) connection invalidated remotely. (Do you have the required entitlement?)"
+ "com.apple.SpringBoardServices.SBSSecureIndicatorElevationAssertion.connectionQueue"
+ "com.apple.springboard.secure-indicator-elevation-service"
+ "deviceCanBeTreatedAsEffectivelyLocked"
+ "v24@?0@\"FBSMutableSceneClientSettings\"8@\"FBSSceneTransitionContext\"16"
```
