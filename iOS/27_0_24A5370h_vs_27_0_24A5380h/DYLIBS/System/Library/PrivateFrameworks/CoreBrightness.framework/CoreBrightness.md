## CoreBrightness

> `/System/Library/PrivateFrameworks/CoreBrightness.framework/CoreBrightness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1681ec` | `0x16a888` | **`+0x269c`** |
| `__AUTH.__objc_data` | `0x1630` | `0x2630` | **`+0x1000`** |
| `__DATA_DIRTY.__objc_data` | `0x3238` | `0x2238` | **`-0x1000`** |
| `__TEXT.__oslogstring` | `0x18fed` | `0x1963d` | **`+0x650`** |
| `__AUTH_CONST.__objc_const` | `0x331f0` | `0x334e0` | **`+0x2f0`** |
| `__TEXT.__cstring` | `0xcdf5` | `0xcb1a` | **`-0x2db`** |
| `__DATA_DIRTY.__data` | `0x318` | `0x4e8` | **`+0x1d0`** |
| `__AUTH.__data` | `0x7f0` | `0x640` | **`-0x1b0`** |
| `__TEXT.__objc_methlist` | `0xcf0c` | `0xd08c` | **`+0x180`** |
| `__AUTH_CONST.__cfstring` | `0xe260` | `0xe380` | **`+0x120`** |
| `__DATA_CONST.__objc_selrefs` | `0x57b8` | `0x5898` | **`+0xe0`** |
| `__DATA_CONST.__got` | `0x710` | `0x7c0` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x54f0` | `0x5580` | **`+0x90`** |
| `__DATA.__data` | `0x2eaf0` | `0x2eb78` | **`+0x88`** |
| `__AUTH_CONST.__const` | `0x3d90` | `0x3dc8` | **`+0x38`** |
| `__DATA.__bss` | `0x6690` | `0x66c0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2e98` | `0x2ec0` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x16c4` | `0x16e0` | **`+0x1c`** |
| `__DATA_DIRTY.__bss` | `0x90` | `0xa0` | **`+0x10`** |
| `__TEXT.__const` | `0x16a08` | `0x169f8` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2758` | `0x2768` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0xa4e` | `0xa44` | **`-0xa`** |
| `__DATA_CONST.__objc_protolist` | `0x360` | `0x368` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xeb5` | `0xeb0` | **`-0x5`** |

### Other Changes

```diff

-2300.0.0.502.1
+2300.0.10.0.1

-  Functions: 8593
-  Symbols:   10038
-  CStrings:  4647
+  Functions: 8675
+  Symbols:   10075
+  CStrings:  4670
Symbols:
+ +[CBDisplayHandle handleForUniqueID:]
+ +[CBDisplayHandle handleWithDisplayID:andUUID:andUniqueID:]
+ -[AABRear checkSensorEnablementConditions]
+ -[AABRear getFrontLux]
+ -[AABRear isAODDisabled]
+ -[AABRear isFactorDisabled]
+ -[AABRear isFrontLuxSatisfied]
+ -[AABRear isGrimaldiLuxInUse]
+ -[AABRear isOtherALSDisabled]
+ -[AABRear isPropertyDisabled]
+ -[AABRear sensorIsSampling]
+ -[AABRear setAodDisabled:]
+ -[AABRear setFactorDisabled:]
+ -[AABRear setFrontLux:]
+ -[AABRear setGrimaldiLuxInUse:]
+ -[AABRear setOtherALSDisabled:]
+ -[AABRear setPropertyDisabled:]
+ -[AABRear shouldUseRLux:rLux:inUse:]
+ -[BrightnessSystemClientInternal setSyncProperty:forKey:error:]
+ -[CBALSNode getOcclusionDrivesGrimaldi]
+ -[CBALSNode occlusionDrivesGrimaldi]
+ -[CBClient newDisplayClientForUniqueID:withError:]
+ -[CBColorFilter acknowledgeEvent:]
+ -[CBColorFilter newColorSampleConditionWeightedForServices:]
+ -[CBColorFilter newColorSampleLogWeightedForServices:]
+ -[CBColorFilter newColorSampleWinnerTakesAllForServices:]
+ -[CBColorFilter selectedServices]
+ -[CBColorFilter selectionPolicy]
+ -[CBColorFilter setSelectionPolicy:]
+ -[CBDisplayContaineriOS handle]
+ -[CBDisplayHandle copyDescription]
+ -[CBDisplayHandle dealloc]
+ -[CBDisplayHandle description]
+ -[CBDisplayHandle initWithDisplayID:andUUID:andUniqueID:]
+ -[CBDisplayHandle initWithUniqueID:]
+ -[CBIndicatorBrightnessModule findContrastIndicatorNodeForContext:]
+ -[CBIndicatorBrightnessModule getDCPRoleIDFromContext:]
+ -[CBIndicatorBrightnessModule initWithContext:min:max:maxBoost:andFrameInfoProvider:]
+ -[CBJNDBasedContrastIndicatorPolicy description]
+ -[CBSBIM .cxx_destruct]
+ -[CBSBIM initialiseLimits:]
+ -[VMBLControl requestBrightnessTransactionForDisplayUUID:builtIn:]
+ GCC_except_table133
+ GCC_except_table190
+ _IORegistryEntryGetChildIterator
+ _IORegistryEntryGetName
+ _OBJC_CLASS_$_NSNull
+ _OBJC_IVAR_$_AABRear._aodDisabled
+ _OBJC_IVAR_$_AABRear._factorDisabled
+ _OBJC_IVAR_$_AABRear._frontLux
+ _OBJC_IVAR_$_AABRear._grimaldiLuxInUse
+ _OBJC_IVAR_$_AABRear._otherALSDisabled
+ _OBJC_IVAR_$_AABRear._propertyDisabled
+ _OBJC_IVAR_$_AABRear._sensorIsSampling
+ _OBJC_IVAR_$_CBALSNode._occlusionDrivesGrimaldi
+ _OBJC_IVAR_$_CBColorFilter._arrivedEvents
+ _OBJC_IVAR_$_CBColorFilter._selectionPolicy
+ _OBJC_IVAR_$_CBColorModuleShared._firstALSSelectionPolicy
+ _OBJC_IVAR_$_CBDisplayContaineriOS._handle
+ _OBJC_IVAR_$_CBDisplayHandle._cachedDescription
+ _OBJC_IVAR_$_CBSBIM._previousAccumulatedSBIM
+ __CFXLogHandle.log
+ __CFXLogHandle.once
+ __OBJC_$_INSTANCE_VARIABLES_CBDisplayHandle
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CBRearALSModuleProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CBRearALSModuleProtocol
+ __OBJC_$_PROTOCOL_REFS_CBRearALSModuleProtocol
+ __OBJC_LABEL_PROTOCOL_$_CBRearALSModuleProtocol
+ __OBJC_PROTOCOL_$_CBRearALSModuleProtocol
+ __ZN36PerceptualLuminanceThresholding_1nit15SetBoolPropertyEP8NSStringb
+ __ZN38PerceptualLuminanceThresholding_legacy15SetBoolPropertyEP8NSStringb
+ __ZN4AABC21_UpdateEsensorTrustedEfNSt3__18optionalIfEE
+ ___34-[CBColorFilter acknowledgeEvent:]_block_invoke
+ ___54-[CBColorFilter newColorSampleLogWeightedForServices:]_block_invoke
+ ___57-[CBColorFilter newColorSampleWinnerTakesAllForServices:]_block_invoke
+ ___60-[CBColorFilter newColorSampleConditionWeightedForServices:]_block_invoke
+ ___63-[BrightnessSystemClientInternal setSyncProperty:forKey:error:]_block_invoke
+ ____CFXLogHandle_block_invoke
+ _binFromAb
+ _kCBKeyDisplayUniqueID
+ _snprintf
+ _strcmp
- +[CBHandle globalHandle]
- -[AABRear checkSensorEnablementConditions:]
- -[AABRear evaluateSamplingFrequencyWithLux:andCap:]
- -[AABRear shouldUseRLux:rLux:]
- -[AABRear shouldUseRearLuxFrontLux:rearLux:andCap:]
- -[AABRear startSampling]
- -[AABRear started]
- -[BrightnessSystemClientInternal setProperty:forKey:error:]
- -[CBColorFilter acknowledgeHIDEvent:from:]
- -[CBColorFilter newColorSampleConditionWeighted]
- -[CBColorFilter newColorSampleLogWeighted]
- -[CBColorFilter newColorSampleWinnerTakesAll]
- -[CBDisplayContaineriOS initWithBacklightService:andSystemContext:]
- -[CBHandle initGlobal]
- -[CBIndicatorBrightnessModule getDCPRoleIDFromString]
- -[CBSBIM initialiseLimits]
- GCC_except_table135
- GCC_except_table139
- GCC_except_table142
- GCC_except_table191
- GCC_except_table42
- _OBJC_IVAR_$_AABRear._activationFLux
- _OBJC_IVAR_$_AABRear._lastFrequency
- _OBJC_IVAR_$_AABRear._sensorEnabled
- _OBJC_IVAR_$_AABRear._shouldUseRearLux
- _OBJC_IVAR_$_AABRear._started
- _OBJC_IVAR_$_CBColorModuleShared._alsSelectionPolicy
- _OBJC_IVAR_$_VMBLControl._cachedBrightnessTransactions
- __ZGVZ106-[CBSBIM updateMitigationStateWithData:andCurrentHeadroom:andRequestedHeadroom:andSDRBrightness:andReset:]E23previousAccumulatedSBIM
- __ZN4AABC21_UpdateEsensorTrustedEf
- __ZN4AABC25evaluateAABRearConditionsEv
- __ZNSt3__18valarrayIfEC2ERKfm
- __ZNSt3__18valarrayIfED1Ev
- __ZZ106-[CBSBIM updateMitigationStateWithData:andCurrentHeadroom:andRequestedHeadroom:andSDRBrightness:andReset:]E23previousAccumulatedSBIM
- ___42-[CBColorFilter acknowledgeHIDEvent:from:]_block_invoke
- ___42-[CBColorFilter newColorSampleLogWeighted]_block_invoke
- ___45-[CBColorFilter newColorSampleWinnerTakesAll]_block_invoke
- ___48-[CBColorFilter newColorSampleConditionWeighted]_block_invoke
- ___59-[BrightnessSystemClientInternal setProperty:forKey:error:]_block_invoke
- ___cxa_atexit
- ___cxa_guard_abort
- _get_type_metadata 15Synchronization5MutexVySo9CPMSAgentCG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
- _syslog
CStrings:
+ "%s failed to find matching display"
+ ", "
+ "<%@: sdrParams=(lux=%.4f, nits=%.4f, c=%.4f) hdrParams=(lux=%.4f, nits=%.4f, c=%.4f) lumFactor=%.4f maxBoost=%.1f boosting=%d>"
+ "Adjusting AAB curve for preference point: %s (pre-clamped lux: %f, unscaled nits: %f)"
+ "BrightnessTransactionRequest"
+ "Capabilities were likely late! Not restoring %@ property"
+ "ContentHeadroom"
+ "Created contrast indicator policy: %@"
+ "Display(%@)"
+ "Display(unknown)"
+ "Failed to get child iterator err = %#x (%s)"
+ "Failed to get child node's name err = %#x (%s)"
+ "Grimaldi conditions no longer satisfied, stopping sampling"
+ "Grimaldi conditions satisfied, requesting samples"
+ "Grimaldi conditions: AOD: %d, Factor: %d, Property: %d, other ALS: %d, Front Lux Satisfied: %d, luxInUse: %s"
+ "IODeviceTree:/exbright"
+ "Nits for clamped lux: %f is: %f (unscaled nits: %f)"
+ "ShouldUseRearLuxFrontLux(fLux:%.2f, rLux:%.2f) = %s -> %s"
+ "Using clamped lux = %f as input to AAB (pre-clamped lux = %f)"
+ "VM Requesting brightness transaction for displayUUID:%@ builtIn:%d"
+ "com.apple.CoreBrightness.CBALSSelectionPolicy.%@.%d"
+ "com.apple.CoreBrightness.ColorEffects"
+ "contrast-indicator"
+ "id: %lu"
+ "key=%@ value=%@ handle=%@"
+ "occlusion-drives-grimaldi"
+ "selection policy dropped sample; preserving last sample (mode %lu)"
+ "selectionPolicy refresh: service %lu event overridden with policy-provided cached event. Lux %.2f -> %.2f"
+ "uniqueID: %@"
+ "uniqueID: (null)"
+ "uniqueId"
+ "uuid: %@"
- "%s failed to find matching display, saving transaction"
- "Adjusting AAB curve for preference point: %s (uncapped lux: %f, unscaled nits: %f"
- "Grimaldi; { \"aod_forbidden\": %d, \"factor_forbidden\": %d, \"property_forbidden\": %d, \"isStarted\": %d, \"state_change\": \"%@\" }"
- "Nits for lux: %f is: %f (unscaled nits: %f"
- "ShouldUseRearLuxFrontLux(fLux:%.2f, rLux:%.2f, cap: %.2f) = %s"
- "ShouldUseRearLuxFrontLux(fLux:%.2f, rLux:%.2f, cap: %.2f) = %s -> %s"
- "com.apple.CoreBrightness.CBALSSelectionPolicy.%d"
- "starting"
- "stopping"
```
