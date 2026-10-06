## CoreBrightness

> `/System/Library/PrivateFrameworks/CoreBrightness.framework/CoreBrightness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17b78c` | `0x17d0dc` | **`+0x1950`** |
| `__AUTH_CONST.__objc_const` | `0x38c38` | `0x392c0` | **`+0x688`** |
| `__TEXT.__objc_methlist` | `0xdc6c` | `0xde50` | **`+0x1e4`** |
| `__DATA_CONST.__objc_selrefs` | `0x5c80` | `0x5d70` | **`+0xf0`** |
| `__AUTH.__objc_data` | `0x2c90` | `0x2d30` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0xed00` | `0xed80` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x58f0` | `0x5960` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x31b8` | `0x3220` | **`+0x68`** |
| `__DATA.__data` | `0x35160` | `0x351c0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x1ad8d` | `0x1aded` | **`+0x60`** |
| `__TEXT.__cstring` | `0xd2f5` | `0xd335` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x1860` | `0x1888` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x3fa0` | `0x3fc0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x28d4` | `0x28e8` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x790` | `0x7a0` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x398` | `0x3a0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x638` | `0x640` | **`+0x8`** |
| `__TEXT.__const` | `0x1b6b8` | `0x1b6c0` | **`+0x8`** |

### Other Changes

```diff

-2300.2.9.0.0
+2300.40.37.0.0

-  Functions: 9043
-  Symbols:   10659
-  CStrings:  4865
+  Functions: 9094
+  Symbols:   10737
+  CStrings:  4871
Symbols:
+ +[CBDisplayBrightnessClient copyNSNumberForKey:client:handle:andError:]
+ +[CBRampProfileSpring defaultSpringProfile]
+ -[CBCEModule copyCachedInferenceForEvent:]
+ -[CBCEModule invalidateInferenceCache]
+ -[CBCEModule shouldRunInferenceAtTime:]
+ -[CBColorModuleShared CEModulePropertyHandler:key:]
+ -[CBColorPolicyFilter colorAdaptationActive]
+ -[CBColorPolicyFilter setColorAdaptationActive:]
+ -[CBDisplayBrightnessClient currentSDRNitsWithError:]
+ -[CBDisplayBrightnessClient maxSDRDisplayNitsWithError:]
+ -[CBRampManager insertNewRampOrigin:target:length:frequency:identifier:profile:]
+ -[CBRampManager insertNewRampOrigin:target:length:frequency:startRamp:identifier:profile:]
+ -[CBRampProfileLinear normalizedOutputForProgress:]
+ -[CBRampProfileSpring _cacheNormalizer]
+ -[CBRampProfileSpring _springValAtT:]
+ -[CBRampProfileSpring damping]
+ -[CBRampProfileSpring init]
+ -[CBRampProfileSpring initialVelocity]
+ -[CBRampProfileSpring mass]
+ -[CBRampProfileSpring normalizedOutputForProgress:]
+ -[CBRampProfileSpring setDamping:]
+ -[CBRampProfileSpring setInitialVelocity:]
+ -[CBRampProfileSpring setMass:]
+ -[CBRampProfileSpring setStiffness:]
+ -[CBRampProfileSpring stiffness]
+ -[CBRingLight resetUserAdjustmentState]
+ -[CBRingLight statusInfo]
+ -[NightModeControl stop]
+ -[VMBLControl addDisplayModuleForBrightnessControlProxy:]
+ -[VMBLControl findDisplays]
+ -[VMBLControl handleCAWindowServerDisplay:]
+ -[VMBLControl sendBrightnessTransactionRequestForDisplayUUID:builtIn:]
+ -[VMBLControl sendBrightnessTransactionRequestOnQueueForDisplayUUID:builtIn:]
+ -[VMBLControl sendHeadroomRequestOnQueue:forDisplayUUID:builtIn:]
+ -[VMDisplayModule setPropertyOnQueue:forKey:]
+ GCC_except_table41
+ GCC_except_table48
+ _OBJC_CLASS_$_CBRampProfileLinear
+ _OBJC_CLASS_$_CBRampProfileSpring
+ _OBJC_IVAR_$_CBCEModule._cachedResult
+ _OBJC_IVAR_$_CBCEModule._cadenceSeconds
+ _OBJC_IVAR_$_CBCEModule._lastInferenceTime
+ _OBJC_IVAR_$_CBColorPolicyFilter._ceModelID
+ _OBJC_IVAR_$_CBColorPolicyFilter._colorAdaptationActive
+ _OBJC_IVAR_$_CBRampProfileSpring._damping
+ _OBJC_IVAR_$_CBRampProfileSpring._initialVelocity
+ _OBJC_IVAR_$_CBRampProfileSpring._mass
+ _OBJC_IVAR_$_CBRampProfileSpring._normalizer
+ _OBJC_IVAR_$_CBRampProfileSpring._stiffness
+ _OBJC_IVAR_$_CBRingLight._overriddenByUser
+ _OBJC_METACLASS_$_CBRampProfileLinear
+ _OBJC_METACLASS_$_CBRampProfileSpring
+ __OBJC_$_CLASS_METHODS_CBRampProfileSpring
+ __OBJC_$_INSTANCE_METHODS_CBRampProfileLinear
+ __OBJC_$_INSTANCE_METHODS_CBRampProfileSpring
+ __OBJC_$_INSTANCE_VARIABLES_CBRampProfileSpring
+ __OBJC_$_PROP_LIST_CBRampProfileLinear
+ __OBJC_$_PROP_LIST_CBRampProfileSpring
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CBRampProfile
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CBRampProfile
+ __OBJC_$_PROTOCOL_REFS_CBRampProfile
+ __OBJC_CLASS_PROTOCOLS_$_CBRampProfileLinear
+ __OBJC_CLASS_PROTOCOLS_$_CBRampProfileSpring
+ __OBJC_CLASS_RO_$_CBRampProfileLinear
+ __OBJC_CLASS_RO_$_CBRampProfileSpring
+ __OBJC_LABEL_PROTOCOL_$_CBRampProfile
+ __OBJC_METACLASS_RO_$_CBRampProfileLinear
+ __OBJC_METACLASS_RO_$_CBRampProfileSpring
+ __OBJC_PROTOCOL_$_CBRampProfile
+ ___29-[VMDisplayModule invalidate]_block_invoke
+ ___45-[VMDisplayModule setPropertyOnQueue:forKey:]_block_invoke
+ ___58-[VMBLControl sendHeadroomRequest:forDisplayUUID:builtIn:]_block_invoke
+ ___70-[VMBLControl sendBrightnessTransactionRequestForDisplayUUID:builtIn:]_block_invoke
+ ___90-[CBRampManager insertNewRampOrigin:target:length:frequency:startRamp:identifier:profile:]_block_invoke
+ _____DisplayReportCommit_block_invoke_2
+ ___block_descriptor_49_e8_32o40o_e5_v8?0ls32l8s40l8
+ ___block_descriptor_57_e8_32o40o48o_e5_v8?0ls32l8s40l8s48l8
+ _interpolate_value_in_table
+ _kCBSPIBrightnessCommitUpdate
+ _kCBSPIBrightnessCommitUpdateNitsFinal
+ _kCBSPIBrightnessCommitUpdateNitsInitial
+ _load_mapping_table_from_defaults
+ _mapping_table_is_valid
+ _save_mapping_table_to_defaults
- -[CBColorModuleShared CEOverridePropertyHandler:key:]
- -[CBRingLight getStatusInfo]
- -[VMBLControl requestBrightnessTransactionForDisplayUUID:builtIn:]
- _OBJC_IVAR_$_CBRingLight._overridenByUser
- ___18-[BLControl start]_block_invoke_7
- ___83-[VMDisplayModule initWithBrightnessControl:displayUUID:builtIn:delegate:andQueue:]_block_invoke_2
CStrings:
+ "Adding module for display with ID = %d uuid:%@ builtIn:%d"
+ "Angle=%f"
+ "BrightnessCommitUpdate"
+ "CECadence"
+ "HarmonyStrength"
+ "Ignoring negative CE cadence %f"
+ "OverriddenByUser"
+ "Setting CE inference cadence to %f s"
+ "WSDisplays: %{public}@"
+ "[%@]cached strength: %.2f, confidence: %f"
+ "[BRT update: %s]: Begin slider drag"
+ "[Color Mitigation] lux=%.1f nits=%.1f mitigated=%d ceEnabled=%d ttActive=%d ceAttempted=%d source=%s confidence=%.3f threshold=%.3f crossedThreshold=%d strength=%.3f"
+ "[Display Transition] ALS suppression OFF"
+ "[Display Transition] ALS suppression OFF - handling skipped"
+ "[Display Transition] ALS suppression ON"
+ "_S=%f"
+ "headroomRequestDelegate is nil, cannot request brightness transaction"
+ "initialNits"
- "ALS transition suppression: %s"
- "OverridenByUser"
- "Received angle %f"
- "Setting PLT angle to %f"
- "Transitioning to Flipbook, forcing NaN IB to CA!"
- "[%x]: _S=%f"
- "[CPMS] Current SDR brightness updated: %f -> %f"
- "[Color Mitigation] lux=%.1f nits=%.1f mitigated=%d ceEnabled=%d ceAttempted=%d source=%s confidence=%.3f threshold=%.3f crossedThreshold=%d strength=%.3f"
- "error: unknown notification type (%@)"
- "key=%@ (type=%tu) value=%@  block=%p queue=%p"
- "key=%@ property=%@ queue=%p clientBlock=%p"
- "no callback or queue available - ignoring notification"
```
