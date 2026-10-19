## SpringBoard

> `/System/Library/PrivateFrameworks/SpringBoard.framework/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb1619c` | `0xb18b84` | **`+0x29e8`** |
| `__AUTH_CONST.__objc_const` | `0x28a9f0` | `0x28b228` | **`+0x838`** |
| `__TEXT.__oslogstring` | `0x65afe` | `0x660a4` | **`+0x5a6`** |
| `__TEXT.__objc_methlist` | `0xbe4f0` | `0xbe6c0` | **`+0x1d0`** |
| `__DATA_CONST.__objc_selrefs` | `0x4ed30` | `0x4ee30` | **`+0x100`** |
| `__DATA.__data` | `0x210a0` | `0x21160` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0xd9d0` | `0xda70` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x74f80` | `0x75020` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x27970` | `0x27a10` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x2e7c0` | `0x2e830` | **`+0x70`** |
| `__TEXT.__cstring` | `0x85af0` | `0x85b58` | **`+0x68`** |
| `__DATA_CONST.__got` | `0xa9c0` | `0xaa00` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x1dae0` | `0x1dac0` | **`-0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x5520` | `0x5540` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0xfd40` | `0xfd5c` | **`+0x1c`** |
| `__DATA_CONST.__objc_catlist` | `0x338` | `0x350` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2c00` | `0x2c10` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x2af8` | `0x2b08` | **`+0x10`** |
| `__TEXT.__const` | `0x11370` | `0x11380` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x40c0` | `0x40c8` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 73747
-  Symbols:   119682
-  CStrings:  23612
+  Functions: 73776
+  Symbols:   119766
+  CStrings:  23633
Symbols:
+ +[SBDeviceEmulationController applicationInitializationContext]
+ +[SBDeviceEmulationController deviceContext]
+ +[SBDeviceEmulationController displayContext]
+ +[SBFDIDeviceControlCoordinator _scene:hasEntitlement:]
+ +[SBFDIDeviceControlCoordinator addSceneExtensionIfNeeded:]
+ +[SBScreenEdgeCompensationDisplayTransformer isScreenEdgeCompensationEnabled]
+ +[SBScreenEdgeCompensationDisplayTransformer sceneTransformForWindowScene:]
+ +[SBScreenEdgeCompensationDisplayTransformer transformedConfigurationForConfiguration:]
+ -[SBFDIDeviceControlBacklightInformer isRestricting]
+ -[SBFDIDeviceControlBacklightInformer setRestricting:]
+ -[SBFDIDeviceControlBacklightInformer shouldTurnOnScreenForBacklightSource:]
+ -[SBFDIDeviceControlCoordinator .cxx_destruct]
+ -[SBFDIDeviceControlCoordinator _updateBacklightRestrictionForWindowScene:wantsRestriction:]
+ -[SBFDIDeviceControlCoordinator _updateLiftToWakeForWindowScenes:wantsSuppression:]
+ -[SBFDIDeviceControlCoordinator _updateShieldButtonsRestrictionForWindowScenes:wantsRestriction:]
+ -[SBFDIDeviceControlCoordinator _updateTapToWakeForWindowScenes:wantsSuppression:]
+ -[SBFDIDeviceControlCoordinator applyFDIDeviceControlClientSettings:]
+ -[SBFDIDeviceControlCoordinator init]
+ -[SBFDIDeviceControlCoordinator invalidate]
+ -[SBSAPlatformMetricsContext _setSensorVariant:]
+ -[SBSAPlatformMetricsContext copyBySettingSensorVariant:]
+ -[SBSAPlatformMetricsContext sensorVariant]
+ -[SBSAPlatformMetricsContextMutator sensorVariant]
+ -[SBSAPlatformMetricsContextMutator setSensorVariant:]
+ -[UISMutableApplicationInitializationContext(DeviceEmulation) sb_configureForDeviceEmulation]
+ -[UISMutableDeviceContext(DeviceEmulation) sb_configureForDeviceEmulation]
+ -[UISMutableDisplayContext(DeviceEmulation) sb_configureForDeviceEmulation]
+ _OBJC_CLASS_$_FBSDeviceEmulationConfiguration
+ _OBJC_CLASS_$_SBDeviceEmulationController
+ _OBJC_CLASS_$_SBFDIDeviceControlBacklightInformer
+ _OBJC_CLASS_$_SBFDIDeviceControlCoordinator
+ _OBJC_CLASS_$_SBSFDIDeviceControlHostComponent
+ _OBJC_CLASS_$_SBSFDIDeviceControlSceneExtension
+ _OBJC_CLASS_$_SBScreenEdgeCompensationDisplayTransformer
+ _OBJC_CLASS_$_SSKHostingConfiguration
+ _OBJC_CLASS_$_SSKLayerConfiguration
+ _OBJC_IVAR_$_SBApplicationInfo._disableD2026ClassicMode
+ _OBJC_IVAR_$_SBFDIDeviceControlBacklightInformer._restricting
+ _OBJC_IVAR_$_SBFDIDeviceControlCoordinator._backlightInformer
+ _OBJC_IVAR_$_SBFDIDeviceControlCoordinator._disableLiftToWakeAssertions
+ _OBJC_IVAR_$_SBFDIDeviceControlCoordinator._disableShieldButtonsAssertions
+ _OBJC_IVAR_$_SBFDIDeviceControlCoordinator._disableTapToWakeAssertions
+ _OBJC_IVAR_$_SBFDIDeviceControlCoordinator._restrictedBacklightControllers
+ _OBJC_METACLASS_$_SBDeviceEmulationController
+ _OBJC_METACLASS_$_SBFDIDeviceControlBacklightInformer
+ _OBJC_METACLASS_$_SBFDIDeviceControlCoordinator
+ _OBJC_METACLASS_$_SBScreenEdgeCompensationDisplayTransformer
+ _SBLogDisplayTransforming
+ _SBLogFDIDeviceControl
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_UISMutableApplicationInitializationContext_$_DeviceEmulation
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_UISMutableDeviceContext_$_DeviceEmulation
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_UISMutableDisplayContext_$_DeviceEmulation
+ __OBJC_$_CATEGORY_UISMutableApplicationInitializationContext_$_DeviceEmulation
+ __OBJC_$_CATEGORY_UISMutableDeviceContext_$_DeviceEmulation
+ __OBJC_$_CATEGORY_UISMutableDisplayContext_$_DeviceEmulation
+ __OBJC_$_CLASS_METHODS_SBDeviceEmulationController
+ __OBJC_$_CLASS_METHODS_SBFDIDeviceControlCoordinator
+ __OBJC_$_CLASS_METHODS_SBScreenEdgeCompensationDisplayTransformer
+ __OBJC_$_CLASS_PROP_LIST_SBDeviceEmulationController
+ __OBJC_$_INSTANCE_METHODS_SBFDIDeviceControlBacklightInformer
+ __OBJC_$_INSTANCE_METHODS_SBFDIDeviceControlCoordinator
+ __OBJC_$_INSTANCE_VARIABLES_SBFDIDeviceControlBacklightInformer
+ __OBJC_$_INSTANCE_VARIABLES_SBFDIDeviceControlCoordinator
+ __OBJC_$_PROP_LIST_SBFDIDeviceControlBacklightInformer
+ __OBJC_$_PROP_LIST_SBFDIDeviceControlCoordinator
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SBBacklightInforming
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SBSFDIDeviceControlCoordinating
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SBBacklightInforming
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SBSFDIDeviceControlCoordinating
+ __OBJC_$_PROTOCOL_REFS_SBBacklightInforming
+ __OBJC_$_PROTOCOL_REFS_SBSFDIDeviceControlCoordinating
+ __OBJC_CLASS_PROTOCOLS_$_SBFDIDeviceControlBacklightInformer
+ __OBJC_CLASS_PROTOCOLS_$_SBFDIDeviceControlCoordinator
+ __OBJC_CLASS_RO_$_SBDeviceEmulationController
+ __OBJC_CLASS_RO_$_SBFDIDeviceControlBacklightInformer
+ __OBJC_CLASS_RO_$_SBFDIDeviceControlCoordinator
+ __OBJC_CLASS_RO_$_SBScreenEdgeCompensationDisplayTransformer
+ __OBJC_LABEL_PROTOCOL_$_SBBacklightInforming
+ __OBJC_LABEL_PROTOCOL_$_SBSFDIDeviceControlCoordinating
+ __OBJC_METACLASS_RO_$_SBDeviceEmulationController
+ __OBJC_METACLASS_RO_$_SBFDIDeviceControlBacklightInformer
+ __OBJC_METACLASS_RO_$_SBFDIDeviceControlCoordinator
+ __OBJC_METACLASS_RO_$_SBScreenEdgeCompensationDisplayTransformer
+ __OBJC_PROTOCOL_$_SBBacklightInforming
+ __OBJC_PROTOCOL_$_SBSFDIDeviceControlCoordinating
+ ___57-[SBSAPlatformMetricsContext copyBySettingSensorVariant:]_block_invoke
- -[SBLockScreenBiometricAuthenticationCoordinator _shouldShowAlertForSeed]
- ___block_descriptor_33_e31_v16?0"SSKDisplayPreferences"8l
CStrings:
+ "%{public}@: screen edge compensation transform built: %{BOOL}u"
+ "Applying screen edge compensation: D76 main display size matched; rewriting bounds from %{public}@ to %{public}@"
+ "EdgeSwipeBandExpansionEnabled"
+ "FDIDeviceControl"
+ "SBDisableD2026ClassicMode"
+ "SBFDIDeviceControlCoordinator: acquired lift-to-wake disable across %lu window scenes"
+ "SBFDIDeviceControlCoordinator: acquired shield-buttons disable across %lu non-main-root window scenes"
+ "SBFDIDeviceControlCoordinator: acquired tap-to-wake disable across %lu window scenes"
+ "SBFDIDeviceControlCoordinator: attached FDI device control extension to entitled scene %{public}@"
+ "SBFDIDeviceControlCoordinator: invalidate"
+ "SBFDIDeviceControlCoordinator: powered off + registered wake veto on non-main-root display for scene %{public}@"
+ "SBFDIDeviceControlCoordinator: released lift-to-wake disable across %lu window scenes"
+ "SBFDIDeviceControlCoordinator: released shield-buttons disable across %lu window scenes"
+ "SBFDIDeviceControlCoordinator: released tap-to-wake disable across %lu window scenes"
+ "SBFDIDeviceControlCoordinator: removed wake veto from non-main-root display for scene %{public}@"
+ "SBFDIDeviceControlCoordinator: updating FDI device control (liftToWake=%{BOOL}u tapToWake=%{BOOL}u configurationA=%{BOOL}u) across %lu window scenes"
+ "Skipping screen edge compensation: isMainD76Display=%{BOOL}u"
+ "Unable to build screen edge compensated display configuration: %{public}@ from configuration: %{public}@"
+ "Unable to create redacted display configuration: %@ from configuration:%@"
+ "com.apple.Energy"
+ "sensorVariant"
```
