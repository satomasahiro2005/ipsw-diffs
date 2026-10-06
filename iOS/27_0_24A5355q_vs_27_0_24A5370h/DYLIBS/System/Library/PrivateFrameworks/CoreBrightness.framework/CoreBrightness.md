## CoreBrightness

> `/System/Library/PrivateFrameworks/CoreBrightness.framework/CoreBrightness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14d7b4` | `0x1681ec` | **`+0x1aa38`** |
| `__AUTH_CONST.__objc_const` | `0x30c98` | `0x331f0` | **`+0x2558`** |
| `__DATA.__bss` | `0x4890` | `0x6690` | **`+0x1e00`** |
| `__TEXT.__oslogstring` | `0x1775a` | `0x18fed` | **`+0x1893`** |
| `__TEXT.__const` | `0x15750` | `0x16a08` | **`+0x12b8`** |
| `__AUTH_CONST.__const` | `0x2d20` | `0x3d90` | **`+0x1070`** |
| `__AUTH_CONST.__cfstring` | `0xd620` | `0xe260` | **`+0xc40`** |
| `__TEXT.__cstring` | `0xc46a` | `0xcdf5` | **`+0x98b`** |
| `__TEXT.__objc_methlist` | `0xc704` | `0xcf0c` | **`+0x808`** |
| `__TEXT.__unwind_info` | `0x4d70` | `0x54f0` | **`+0x780`** |
| `__TEXT.__swift5_fieldmd` | `0xa0c` | `0x1018` | **`+0x60c`** |
| `__AUTH_CONST.__objc_intobj` | `0x960` | `0xd80` | **`+0x420`** |
| `__AUTH.__objc_data` | `0x1218` | `0x1630` | **`+0x418`** |
| `__DATA.__data` | `0x2e710` | `0x2eaf0` | **`+0x3e0`** |
| `__DATA_CONST.__objc_arraydata` | `0x908` | `0xcb8` | **`+0x3b0`** |
| `__TEXT.__swift5_reflstr` | `0x6fc` | `0xa4e` | **`+0x352`** |
| `__TEXT.__constg_swiftt` | `0x8f0` | `0xc2c` | **`+0x33c`** |
| `__TEXT.__swift5_typeref` | `0xb7a` | `0xeb5` | **`+0x33b`** |
| `__DATA_CONST.__objc_selrefs` | `0x5550` | `0x57b8` | **`+0x268`** |
| `__TEXT.__eh_frame` | `0x928` | `0xb90` | **`+0x268`** |
| `__TEXT.__gcc_except_tab` | `0x25b0` | `0x2758` | **`+0x1a8`** |
| `__DATA_CONST.__const` | `0x2d50` | `0x2e98` | **`+0x148`** |
| `__TEXT.__swift5_proto` | `0x210` | `0x308` | **`+0xf8`** |
| `__TEXT.__swift5_assocty` | `0x198` | `0x288` | **`+0xf0`** |
| `__AUTH.__data` | `0x708` | `0x7f0` | **`+0xe8`** |
| `__AUTH_CONST.__auth_got` | `0x1298` | `0x1370` | **`+0xd8`** |
| `__DATA.__objc_ivar` | `0x15f4` | `0x16c4` | **`+0xd0`** |
| `__AUTH_CONST.__objc_dictobj` | `0x4b0` | `0x550` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x3198` | `0x3238` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0x6a8` | `0x710` | **`+0x68`** |
| `__TEXT.__swift5_types` | `0xc4` | `0x120` | **`+0x5c`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x390` | `0x3d8` | **`+0x48`** |
| `__DATA_CONST.__objc_classlist` | `0x6a8` | `0x6f0` | **`+0x48`** |
| `__DATA_CONST.__objc_protolist` | `0x320` | `0x360` | **`+0x40`** |
| `__DATA_CONST.__objc_protorefs` | `0x110` | `0x138` | **`+0x28`** |
| `__AUTH_CONST.__objc_floatobj` | `0x180` | `0x1a0` | **`+0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0x5a0` | `0x5b8` | **`+0x18`** |
| `__TEXT.__swift5_mpenum` | `0x20` | `0x28` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x4` | `0x8` | **`+0x4`** |

### Other Changes

```diff

-2285.0.0.502.1
+2300.0.0.502.1

-  Functions: 7771
-  Symbols:   9647
-  CStrings:  4430
+  Functions: 8593
+  Symbols:   10038
+  CStrings:  4647
Symbols:
+ -[AABRear initWithDisplayContext:]
+ -[BLControl setupAABRear]
+ -[CBAABiOSCurveWrapper copyUserPrefState]
+ -[CBAABiOSCurveWrapper getNitsForLux:]
+ -[CBAABiOSCurveWrapper resetToDefaultState]
+ -[CBAABiOSCurveWrapper scaleFactor]
+ -[CBAABiOSCurveWrapper setSavedPreferences:]
+ -[CBAABiOSCurveWrapper setScaleFactor:]
+ -[CBAABiOSCurveWrapper updateALSParametersForNits:andLux:]
+ -[CBAABiOSCurveWrapper version]
+ -[CBALSSelectionPolicyBase dealloc]
+ -[CBALSSelectionPolicyBase initWithLogCategory:displayId:]
+ -[CBAODTransitionController indicator]
+ -[CBAODTransitionController setIndicator:]
+ -[CBAODTransitionController startEternalIndicatorRamp]
+ -[CBAODTransitionController stopEternalIndicatorRamp]
+ -[CBAODTransitionController updateIndicatorBrightness:andLimit:]
+ -[CBBrightnessProxyCA setIndicatorBrightness:]
+ -[CBBrightnessProxyCA setIndicatorBrightnessLimit:]
+ -[CBColorFilter initWithIdentifier:panelPlacement:]
+ -[CBColorFilter isFrontALS:]
+ -[CBColorFilter isRearALS:]
+ -[CBColorModuleShared handleCoexUpdates:]
+ -[CBColorModuleShared hasCoexForALS:]
+ -[CBColorModuleShared initCoexTracker]
+ -[CBColorModuleShared isRearALS:]
+ -[CBColorModuleShared uvThresholdPropertyHandler:forKey:]
+ -[CBDigitizerNode newFiltersForALS:logCategory:]
+ -[CBDisplayContext SILState]
+ -[CBDisplayContext initWithQueue:andSystemContext:andBrtCtl:andConfig:andTwilight:andAmmolite:andGCP:andCADisplay:andCBPM:andAODState:andSILState:andRingLight:]
+ -[CBDisplayPassthroughPolicy cancel]
+ -[CBDisplayPassthroughPolicy containerDidAdd:]
+ -[CBDisplayPassthroughPolicy containerWillRemove:]
+ -[CBDisplayPassthroughPolicy copyStatusInfo]
+ -[CBExternalDisplayKeyPolicy cancel]
+ -[CBExternalDisplayKeyPolicy containerDidAdd:]
+ -[CBExternalDisplayKeyPolicy containerWillRemove:]
+ -[CBExternalDisplayKeyPolicy copyStatusInfo]
+ -[CBIndicatorAnalyticsModule copyPropertyForKey:]
+ -[CBIndicatorAnalyticsModule copyPropertyForKey:withParameter:]
+ -[CBIndicatorAnalyticsModule dealloc]
+ -[CBIndicatorAnalyticsModule handleNotificationForKey:withProperty:]
+ -[CBIndicatorAnalyticsModule indicatorStatsTimerCallback]
+ -[CBIndicatorAnalyticsModule initWithQueue:andIndicatorModule:]
+ -[CBIndicatorAnalyticsModule initWithQueue:andIndicatorModule:andDDFactorMapping:andLuxMapping:andNitsMapping:andDDFactorEdges:andLuxEdges:andNitsEdges:andTimerIntervalMs:]
+ -[CBIndicatorAnalyticsModule setProperty:forKey:]
+ -[CBIndicatorAnalyticsModule startTimer]
+ -[CBIndicatorAnalyticsModule start]
+ -[CBIndicatorAnalyticsModule stopTimer]
+ -[CBIndicatorAnalyticsModule stop]
+ -[CBIndicatorAnalyticsModule submit]
+ -[CBIndicatorBrightnessModule SILState]
+ -[CBIndicatorBrightnessModule addHIDServiceClient:]
+ -[CBIndicatorBrightnessModule calculate20JNDContrastIndicatorForSDRBrightness:andLux:]
+ -[CBIndicatorBrightnessModule calculate22JNDContrastIndicatorForSDRBrightness:andLux:]
+ -[CBIndicatorBrightnessModule calculate60JNDContrastIndicatorForSDRBrightness:andLux:]
+ -[CBIndicatorBrightnessModule calculateJumpTargetForFastStart]
+ -[CBIndicatorBrightnessModule className]
+ -[CBIndicatorBrightnessModule copyPropertyForKey:]
+ -[CBIndicatorBrightnessModule copyPropertyForKey:withParameter:]
+ -[CBIndicatorBrightnessModule currentDigitalDimmingFactor]
+ -[CBIndicatorBrightnessModule currentIndicatorBrightness]
+ -[CBIndicatorBrightnessModule currentUIBrightness]
+ -[CBIndicatorBrightnessModule dcpRoleID]
+ -[CBIndicatorBrightnessModule dealloc]
+ -[CBIndicatorBrightnessModule determineJumpTarget]
+ -[CBIndicatorBrightnessModule endRamp]
+ -[CBIndicatorBrightnessModule forceBrightnessTransaction]
+ -[CBIndicatorBrightnessModule getDCPRoleIDFromString]
+ -[CBIndicatorBrightnessModule handleAODStateUpdate:transitionTime:context:]
+ -[CBIndicatorBrightnessModule handleEvent:]
+ -[CBIndicatorBrightnessModule handleNotificationForKey:withProperty:]
+ -[CBIndicatorBrightnessModule handleRampDecisionForTargetIB:indicatorUpdatedOutsideOfRamp:]
+ -[CBIndicatorBrightnessModule indicatorBrightnessFollowsMIB]
+ -[CBIndicatorBrightnessModule initWithContext:min:max:andContrastIndicatorPolicy:]
+ -[CBIndicatorBrightnessModule initWithContext:min:max:contrastIndicatorPolicy:andFrameInfoProvider:]
+ -[CBIndicatorBrightnessModule initWithContext:min:max:contrastIndicatorPolicy:frameInfoProvider:andCurrentTimeFunction:]
+ -[CBIndicatorBrightnessModule isEXBrightDispatching]
+ -[CBIndicatorBrightnessModule isRampRunning]
+ -[CBIndicatorBrightnessModule jumpTo:]
+ -[CBIndicatorBrightnessModule processTransaction]
+ -[CBIndicatorBrightnessModule rampTo:]
+ -[CBIndicatorBrightnessModule rampTo:indicatorUpdatedOutsideOfRamp:]
+ -[CBIndicatorBrightnessModule removeHIDServiceClient:]
+ -[CBIndicatorBrightnessModule sendRampFinishedNotificationAOD]
+ -[CBIndicatorBrightnessModule sendRampFinishedNotificationActive]
+ -[CBIndicatorBrightnessModule sendRampFinishedNotification]
+ -[CBIndicatorBrightnessModule sendRampIsRunningNotificationAOD]
+ -[CBIndicatorBrightnessModule sendRampIsRunningNotificationActive]
+ -[CBIndicatorBrightnessModule sendRampIsRunningNotification]
+ -[CBIndicatorBrightnessModule setAppliedHeadroom:]
+ -[CBIndicatorBrightnessModule setLux:]
+ -[CBIndicatorBrightnessModule setMinimumIndicatorBrightness:]
+ -[CBIndicatorBrightnessModule setProperty:forKey:]
+ -[CBIndicatorBrightnessModule setRampSpeed:]
+ -[CBIndicatorBrightnessModule setSDRBrightness:]
+ -[CBIndicatorBrightnessModule setSilEnabled:]
+ -[CBIndicatorBrightnessModule setSilState:]
+ -[CBIndicatorBrightnessModule shortcutRamp]
+ -[CBIndicatorBrightnessModule shouldJumpToMIB]
+ -[CBIndicatorBrightnessModule startMonitoringForRTPLC]
+ -[CBIndicatorBrightnessModule start]
+ -[CBIndicatorBrightnessModule stopMonitoringForRTPLC]
+ -[CBIndicatorBrightnessModule stop]
+ -[CBIndicatorBrightnessModule updateMaxContrastBoostedBrightness:]
+ -[CBIndicatorBrightnessModule updateMaxContrastBoostedBrightnessGated:]
+ -[CBIndicatorBrightnessModule updateRamp]
+ -[CBProxNode newFiltersForALS:logCategory:]
+ -[CBRearALSModule initWithConfig:]
+ -[CBRearALSModule startSamplingWithFrequency:forClient:]
+ -[CBRearALSModule stopSamplingForClient:]
+ -[CBSBIM initWithContext:andDisplayModule:andEDRModule:andEDRThreshold:]
+ -[CBSILState SILStateString]
+ -[CBSILState SILState]
+ -[CBSILState dealloc]
+ -[CBSILState init]
+ -[CBSILState isSILActive]
+ -[CBSILState setSILState:]
+ -[CBStandardALSSelectionPolicy select:]
+ -[CBSystemContext alsClientRegistry]
+ -[CBSystemContext rearALSModule]
+ -[CBSystemContext setAlsClientRegistry:]
+ -[CBSystemContext setRearALSModule:]
+ -[NSArray(PrimitiveDataProvider) maxFloatValue]
+ -[NSArray(PrimitiveDataProvider) maxInt32Value]
+ -[NSArray(PrimitiveDataProvider) maxUint32Value]
+ -[TMDisplayModule handleDisplayStateChange]
+ -[VMBLControl parseCacheKey:displayIdentifier:builtIn:]
+ GCC_except_table136
+ GCC_except_table138
+ GCC_except_table141
+ GCC_except_table144
+ GCC_except_table146
+ GCC_except_table149
+ GCC_except_table151
+ GCC_except_table154
+ GCC_except_table155
+ GCC_except_table156
+ GCC_except_table157
+ GCC_except_table191
+ GCC_except_table40
+ GCC_except_table42
+ GCC_except_table49
+ GCC_except_table50
+ GCC_except_table62
+ GCC_except_table64
+ GCC_except_table66
+ GCC_except_table67
+ GCC_except_table70
+ GCC_except_table74
+ GCC_except_table85
+ _CBU_DeviceHasDisplayRearALSSamplingPolicy
+ _CBU_IsContrastIndicatorEnabled
+ _CBU_IsContrastIndicatorEnabled.enabled
+ _CBU_IsContrastIndicatorEnabled.onceToken
+ _CBU_IsContrastIndicatorSupported
+ _CBU_IsContrastIndicatorSupported.onceToken
+ _CBU_IsContrastIndicatorSupported.supported
+ _CBU_IsDualColorRampThresholdingEnabled
+ _CBU_IsSecureIndicatorSupported
+ _CBU_IsSecureIndicatorSupported.onceToken
+ _CBU_IsSecureIndicatorSupported.supported
+ _CBU_IsTransitionPolicyEnabled
+ _CBU_IsTransitionPolicyEnabled.once
+ _CBU_IsTransitionPolicyEnabled.result
+ _CFNumberGetType
+ _CFXSetUVColorMitigatedTh1
+ _CFXSetUVColorMitigatedTh2
+ _CFXSetUVTh1
+ _CFXSetUVTh2
+ _OBJC_CLASS_$_ALSDefaultRateManager
+ _OBJC_CLASS_$_CBALSSelectionPolicyBase
+ _OBJC_CLASS_$_CBBrightnessBoost
+ _OBJC_CLASS_$_CBIndicatorAnalyticsModule
+ _OBJC_CLASS_$_CBIndicatorBrightnessModule
+ _OBJC_CLASS_$_CBSILState
+ _OBJC_CLASS_$_CBStandardALSSelectionPolicy
+ _OBJC_CLASS_$_CBThreeSegmentAABCurve
+ _OBJC_CLASS_$__TtC14CoreBrightness20ThreeSegmentAABCurve
+ _OBJC_CLASS_$__TtC14CoreBrightness31ThreeSegmentAABCurvePreferences
+ _OBJC_IVAR_$_AABRear._context
+ _OBJC_IVAR_$_AABRear._logHandle
+ _OBJC_IVAR_$_CBAABiOSCurveWrapper._scaleFactor
+ _OBJC_IVAR_$_CBALSSelectionPolicyBase._logHandle
+ _OBJC_IVAR_$_CBAODTransitionController._currentIndicatorBrightness
+ _OBJC_IVAR_$_CBAODTransitionController._currentIndicatorBrightnessLimit
+ _OBJC_IVAR_$_CBAODTransitionController._indicator
+ _OBJC_IVAR_$_CBCPMSModule._currentSDRNits
+ _OBJC_IVAR_$_CBColorFilter._panelPlacement
+ _OBJC_IVAR_$_CBColorModuleShared._alsSelectionPolicy
+ _OBJC_IVAR_$_CBColorModuleShared._coexTracker
+ _OBJC_IVAR_$_CBColorModuleShared._continueWithSelectedALSs
+ _OBJC_IVAR_$_CBColorModuleShared._panelPlacement
+ _OBJC_IVAR_$_CBDisplayContext._SILState
+ _OBJC_IVAR_$_CBDisplayModuleiOS._indicatorBrightnessModule
+ _OBJC_IVAR_$_CBIndicatorAnalyticsModule._ddFactorEdgeMapping
+ _OBJC_IVAR_$_CBIndicatorAnalyticsModule._displayID
+ _OBJC_IVAR_$_CBIndicatorAnalyticsModule._indicatorModule
+ _OBJC_IVAR_$_CBIndicatorAnalyticsModule._lastSessionDuration
+ _OBJC_IVAR_$_CBIndicatorAnalyticsModule._luxEdgeMapping
+ _OBJC_IVAR_$_CBIndicatorAnalyticsModule._nitsEdgeMapping
+ _OBJC_IVAR_$_CBIndicatorAnalyticsModule._sessionStart
+ _OBJC_IVAR_$_CBIndicatorAnalyticsModule._stats
+ _OBJC_IVAR_$_CBIndicatorAnalyticsModule._timer
+ _OBJC_IVAR_$_CBIndicatorAnalyticsModule._timerIntervalMs
+ _OBJC_IVAR_$_CBIndicatorAnalyticsModule._timerIsSuspended
+ _OBJC_IVAR_$_CBIndicatorAnalyticsModule._trustedLux
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._aodOn
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._contentHeadroom
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._context
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._contrastIndicatorPolicy
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._currentIndicatorBrightness
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._currentTimeFunction
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._dcpRoleID
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._enforceMIB
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._firstMIBReceived
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._forcedBrightnessUpdate
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._frameInfoProvider
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._hdrContent
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._indicatorBrightnessFollowsMIB
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._jumpOnRestart
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._lastAppliedDimmingFactor
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._lastReportedUIBrightness
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._lastSILOffTimestampUs
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._lastSILOnTimestampUs
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._logHandle
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._lux
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._maxBrightness
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._mib
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._mibAnalytics
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._mibCompensationFactor
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._mibServices
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._minBrightness
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._nextUpdate
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._notificationBlock
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._ramp
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._rampSpeed
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._rtplcApplied
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._rtplcCap
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._rtplcMonitoring
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._sdrBrightness
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._targetIndicatorBrightness
+ _OBJC_IVAR_$_CBRearALSModule._clientIntervals
+ _OBJC_IVAR_$_CBSILState._SILState
+ _OBJC_IVAR_$_CBSystemContext._alsClientRegistry
+ _OBJC_IVAR_$_CBSystemContext._rearALSModule
+ _OBJC_IVAR_$_VMBLControl._cachedHeadroomRequests
+ _OBJC_METACLASS_$_ALSDefaultRateManager
+ _OBJC_METACLASS_$_CBALSSelectionPolicyBase
+ _OBJC_METACLASS_$_CBBrightnessBoost
+ _OBJC_METACLASS_$_CBIndicatorAnalyticsModule
+ _OBJC_METACLASS_$_CBIndicatorBrightnessModule
+ _OBJC_METACLASS_$_CBSILState
+ _OBJC_METACLASS_$_CBStandardALSSelectionPolicy
+ _OBJC_METACLASS_$_CBThreeSegmentAABCurve
+ _OBJC_METACLASS_$__TtC14CoreBrightness20ThreeSegmentAABCurve
+ _OBJC_METACLASS_$__TtC14CoreBrightness31ThreeSegmentAABCurvePreferences
+ __DATA_ALSDefaultRateManager
+ __DATA_CBBrightnessBoost
+ __DATA_CBThreeSegmentAABCurve
+ __DATA__TtC14CoreBrightness20ThreeSegmentAABCurve
+ __DATA__TtC14CoreBrightness31ThreeSegmentAABCurvePreferences
+ __INSTANCE_METHODS_ALSDefaultRateManager
+ __INSTANCE_METHODS_CBBrightnessBoost
+ __INSTANCE_METHODS_CBThreeSegmentAABCurve
+ __INSTANCE_METHODS__TtC14CoreBrightness20ThreeSegmentAABCurve
+ __INSTANCE_METHODS__TtC14CoreBrightness31ThreeSegmentAABCurvePreferences
+ __IVARS_ALSDefaultRateManager
+ __IVARS_CBBrightnessBoost
+ __IVARS_CBThreeSegmentAABCurve
+ __IVARS__TtC14CoreBrightness20ThreeSegmentAABCurve
+ __IVARS__TtC14CoreBrightness31ThreeSegmentAABCurvePreferences
+ __METACLASS_DATA_ALSDefaultRateManager
+ __METACLASS_DATA_CBBrightnessBoost
+ __METACLASS_DATA_CBThreeSegmentAABCurve
+ __METACLASS_DATA__TtC14CoreBrightness20ThreeSegmentAABCurve
+ __METACLASS_DATA__TtC14CoreBrightness31ThreeSegmentAABCurvePreferences
+ __OBJC_$_INSTANCE_METHODS_CBALSSelectionPolicyBase
+ __OBJC_$_INSTANCE_METHODS_CBIndicatorAnalyticsModule
+ __OBJC_$_INSTANCE_METHODS_CBIndicatorBrightnessModule
+ __OBJC_$_INSTANCE_METHODS_CBSILState
+ __OBJC_$_INSTANCE_METHODS_CBStandardALSSelectionPolicy
+ __OBJC_$_INSTANCE_VARIABLES_CBALSSelectionPolicyBase
+ __OBJC_$_INSTANCE_VARIABLES_CBIndicatorAnalyticsModule
+ __OBJC_$_INSTANCE_VARIABLES_CBIndicatorBrightnessModule
+ __OBJC_$_INSTANCE_VARIABLES_CBSILState
+ __OBJC_$_PROP_LIST_ALSRateManagerProtocol
+ __OBJC_$_PROP_LIST_CBAABCurveProtocol
+ __OBJC_$_PROP_LIST_CBIndicatorAnalyticsModule
+ __OBJC_$_PROP_LIST_CBIndicatorBrightnessModule
+ __OBJC_$_PROP_LIST_CBSILState
+ __OBJC_$_PROP_LIST_CBStandardALSSelectionPolicy
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_ALSRateManagerDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_ALSRateManagerProtocol
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CBALSSelectionPolicyProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_ALSRateManagerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_ALSRateManagerProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CBALSSelectionPolicyProtocol
+ __OBJC_$_PROTOCOL_REFS_ALSRateManagerDelegate
+ __OBJC_$_PROTOCOL_REFS_ALSRateManagerProtocol
+ __OBJC_$_PROTOCOL_REFS_CBALSSelectionPolicyProtocol
+ __OBJC_CLASS_PROTOCOLS_$_CBIndicatorAnalyticsModule
+ __OBJC_CLASS_PROTOCOLS_$_CBIndicatorBrightnessModule
+ __OBJC_CLASS_PROTOCOLS_$_CBStandardALSSelectionPolicy
+ __OBJC_CLASS_RO_$_CBALSSelectionPolicyBase
+ __OBJC_CLASS_RO_$_CBIndicatorAnalyticsModule
+ __OBJC_CLASS_RO_$_CBIndicatorBrightnessModule
+ __OBJC_CLASS_RO_$_CBSILState
+ __OBJC_CLASS_RO_$_CBStandardALSSelectionPolicy
+ __OBJC_LABEL_PROTOCOL_$_ALSRateManagerDelegate
+ __OBJC_LABEL_PROTOCOL_$_ALSRateManagerProtocol
+ __OBJC_LABEL_PROTOCOL_$_CBALSSelectionPolicyProtocol
+ __OBJC_METACLASS_RO_$_CBALSSelectionPolicyBase
+ __OBJC_METACLASS_RO_$_CBIndicatorAnalyticsModule
+ __OBJC_METACLASS_RO_$_CBIndicatorBrightnessModule
+ __OBJC_METACLASS_RO_$_CBSILState
+ __OBJC_METACLASS_RO_$_CBStandardALSSelectionPolicy
+ __OBJC_PROTOCOL_$_ALSRateManagerDelegate
+ __OBJC_PROTOCOL_$_ALSRateManagerProtocol
+ __OBJC_PROTOCOL_$_CBALSSelectionPolicyProtocol
+ __PROPERTIES_ALSDefaultRateManager
+ __PROPERTIES_CBBrightnessBoost
+ __PROPERTIES_CBDynamicSliderUniversal
+ __PROPERTIES_CBThreeSegmentAABCurve
+ __PROPERTIES__TtC14CoreBrightness20ThreeSegmentAABCurve
+ __PROTOCOLS_ALSDefaultRateManager
+ __PROTOCOLS_CBThreeSegmentAABCurve
+ __PROTOCOLS__TtC14CoreBrightness20ThreeSegmentAABCurve
+ __PROTOCOLS__TtC14CoreBrightness31ThreeSegmentAABCurvePreferences
+ __Z22load_array_from_readerIjEmP18CBIORegistryReaderP8NSStringPPT_
+ __ZN10applesauce2CF10convert_asIbLi0EEENSt3__18optionalIT_EEPK10__CFNumber
+ __ZN10applesauce2CF10convert_asIfLi0EEENSt3__18optionalIT_EEPK10__CFNumber
+ __ZN10applesauce2CF10convert_asIiLi0EEENSt3__18optionalIT_EEPK10__CFNumber
+ __ZN10applesauce2CF10convert_asIjLi0EEENSt3__18optionalIT_EEPK10__CFNumber
+ __ZN10applesauce2CF7details17number_convert_asIbEENSt3__18optionalIT_EEPK10__CFNumber
+ __ZN10applesauce2CF7details17number_convert_asIfEENSt3__18optionalIT_EEPK10__CFNumber
+ __ZN10applesauce2CF7details17number_convert_asIiEENSt3__18optionalIT_EEPK10__CFNumber
+ __ZN10applesauce2CF7details17number_convert_asIjEENSt3__18optionalIT_EEPK10__CFNumber
+ __ZN10applesauce2CF7details20CFArray_get_value_asINSt3__16vectorIfNS3_9allocatorIfEEEEEENS3_8optionalIT_EEPK9__CFArray
+ __ZN10applesauce2CF7details20CFArray_get_value_asINSt3__16vectorIiNS3_9allocatorIiEEEEEENS3_8optionalIT_EEPK9__CFArray
+ __ZN10applesauce2CF7details20CFArray_get_value_asINSt3__16vectorIjNS3_9allocatorIjEEEEEENS3_8optionalIT_EEPK9__CFArray
+ __ZN10applesauce2CF9NumberRef8from_getEPK10__CFNumber
+ __ZN10applesauce2CF9NumberRefD1Ev
+ __ZN10applesauce2CF9ObjectRefIPK10__CFNumberED2Ev
+ __ZN4AABC12setALSClientEPU28objcproto17ALSClientProtocol11objc_object
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt12out_of_rangeC1B9fqe220106EPKc
+ __ZNSt13runtime_errorC1EPKc
+ __ZNSt13runtime_errorD1Ev
+ __ZNSt3__113__tree_removeB9fqe220106IPNS_16__tree_node_baseIPvEEEEvT_S5_
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__120__throw_out_of_rangeB9fqe220106EPKc
+ __ZNSt3__127__insertion_sort_incompleteB9fqe220106INS_17_ClassicAlgPolicyERZN7CBBOLTS13serializeBinsERKNS_6vectorINS2_3BinENS_9allocatorIS4_EEEEE3$_0PN3AAB11CurveUpdateEEEbT1_SF_T0_
+ __ZNSt3__127__tree_balance_after_insertB9fqe220106IPNS_16__tree_node_baseIPvEEEEvT_S5_
+ __ZNSt3__128__exception_guard_exceptionsIZNS_4listIN3AAB11CurveUpdateENS_9allocatorIS3_EEE22__insert_with_sentinelB9fqe220106INS_21__list_const_iteratorIS3_PvEESA_EENS_15__list_iteratorIS3_S9_EESA_T_T0_EUlvE_ED2B9fqe220106Ev
+ __ZNSt3__128__exception_guard_exceptionsIZNS_4listIN3AAB11CurveUpdateENS_9allocatorIS3_EEE22__insert_with_sentinelB9fqe220106IPKS3_S9_EENS_15__list_iteratorIS3_PvEENS_21__list_const_iteratorIS3_SB_EET_T0_EUlvE_ED2B9fqe220106Ev
+ __ZNSt3__134__uninitialized_allocator_relocateB9fqe220106INS_9allocatorIN7CBBOLTS3BinEEEPS3_EEvRT_T0_S8_S8_
+ __ZNSt3__14listIN3AAB11CurveUpdateENS_9allocatorIS2_EEE22__insert_with_sentinelB9fqe220106INS_21__list_const_iteratorIS2_PvEES9_EENS_15__list_iteratorIS2_S8_EES9_T_T0_
+ __ZNSt3__14listIN3AAB11CurveUpdateENS_9allocatorIS2_EEE22__insert_with_sentinelB9fqe220106IPKS2_S8_EENS_15__list_iteratorIS2_PvEENS_21__list_const_iteratorIS2_SA_EET_T0_
+ __ZNSt3__16__treeINS_12__value_typeIPvU13block_pointerFv17PMMitigationLevelEEENS_19__map_value_compareIS2_NS_4pairIKS2_S5_EENS_4lessIS2_EEEENS_9allocatorISA_EEE14__tree_deleterclB9fqe220106EPNS_11__tree_nodeIS6_S2_EE
+ __ZNSt3__16vectorI11FrameSampleNS_9allocatorIS1_EEE20__throw_out_of_rangeB9fqe220106Ev
+ __ZNSt3__16vectorIN3AAB11CurveUpdateENS_9allocatorIS2_EEE18__insert_with_sizeB9fqe220106INS_17_ClassicAlgPolicyENS_11__wrap_iterIPS2_EESA_EESA_NS8_IPKS2_EET0_T1_l
+ __ZNSt3__16vectorIN3AAB11CurveUpdateENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIN7CBBOLTS16BinConfigurationENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIN7CBBOLTS3BinENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIN7CBBOLTS3BinENS_9allocatorIS2_EEED1B9fqe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE18__assign_with_sizeB9fqe220106INS_17_ClassicAlgPolicyEPfS6_EEvT0_T1_l
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEEC1B9fqe220106ERKS3_
+ __ZNSt3__16vectorIiNS_9allocatorIiEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIiNS_9allocatorIiEEE24__emplace_back_slow_pathIJiEEEPiDpOT_
+ __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIjNS_9allocatorIjEEE24__emplace_back_slow_pathIJjEEEPjDpOT_
+ __ZNSt3__17__sort5B9fqe220106INS_17_ClassicAlgPolicyERZN7CBBOLTS13serializeBinsERKNS_6vectorINS2_3BinENS_9allocatorIS4_EEEEE3$_0PN3AAB11CurveUpdateELi0EEEvT1_SF_SF_SF_SF_T0_
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ __ZTISt13runtime_error
+ __ZZ49-[CBDisplayModeOneOf displayModeProvidersUpdate:]E13mode_priority
+ ___172-[CBIndicatorAnalyticsModule initWithQueue:andIndicatorModule:andDDFactorMapping:andLuxMapping:andNitsMapping:andDDFactorEdges:andLuxEdges:andNitsEdges:andTimerIntervalMs:]_block_invoke
+ ___18-[BLControl start]_block_invoke_6
+ ___23-[CBRearALSModule stop]_block_invoke
+ ___24-[CBRearALSModule start]_block_invoke
+ ___24-[CBRearALSModule start]_block_invoke_2
+ ___29-[CBRearALSModule copyParam:]_block_invoke
+ ___36-[CBIndicatorAnalyticsModule submit]_block_invoke
+ ___36-[CBIndicatorAnalyticsModule submit]_block_invoke_2
+ ___38-[CBRearALSModule copyPropertyForKey:]_block_invoke
+ ___38-[CBRearALSModule setProperty:forKey:]_block_invoke
+ ___45-[CBIndicatorBrightnessModule setSilEnabled:]_block_invoke
+ ___49-[CBIndicatorBrightnessModule processTransaction]_block_invoke
+ ___52-[CBIndicatorBrightnessModule isEXBrightDispatching]_block_invoke
+ ___53-[CBAODModule handleNotificationForKey:withProperty:]_block_invoke
+ ___53-[CBAODModule handleNotificationForKey:withProperty:]_block_invoke_2
+ ___54-[CBAODTransitionController startEternalIndicatorRamp]_block_invoke
+ ___54-[CBIndicatorBrightnessModule startMonitoringForRTPLC]_block_invoke
+ ___56-[CBRearALSModule startSamplingWithFrequency:forClient:]_block_invoke
+ ___66-[CBIndicatorBrightnessModule updateMaxContrastBoostedBrightness:]_block_invoke
+ ___CBU_IsContrastIndicatorEnabled_block_invoke
+ ___CBU_IsContrastIndicatorSupported_block_invoke
+ ___CBU_IsSecureIndicatorSupported_block_invoke
+ ___CBU_IsTransitionPolicyEnabled_block_invoke
+ ___block_descriptor_48_e8_32o40o_e66_v64?0Q8Q16Q24"NSString"32"NSString"40"NSString"48"NSNumber"56ls32l8s40l8
+ ___block_descriptor_52_e8_32o40o_e5_v8?0ls32l8s40l8
+ ___block_descriptor_56_e8_32o40o48r_e15_v32?08Q16^B24ls32l8r48l8s40l8
+ ___block_descriptor_56_e8_32o40r48r_e15_v32?08Q16^B24ls32l8r40l8r48l8
+ ___block_descriptor_80_e8_32o40o48o56o64o72o_e19_"NSDictionary"8?0ls32l8s40l8s48l8s56l8s64l8s72l8
+ ___block_descriptor_80_e8_32o40o48o56r_e5_v8?0ls32l8r56l8s40l8s48l8
+ ___block_descriptor_80_e8_32o40r_e5_v8?0lr40l8s32l8
+ ___swift_destroy_boxed_opaque_existential_1
+ ___swift_memcpy17_8
+ ___swift_memcpy25_8
+ ___swift_memcpy29_4
+ ___swift_memcpy32_4
+ ___swift_memcpy33_4
+ ___swift_memcpy36_4
+ ___swift_memcpy41_8
+ ___swift_memcpy9_4
+ ___swift_mutable_project_boxed_opaque_existential_1
+ _associated conformance 14CoreBrightness11CurveUpdateV10CodingKeys33_42516BEE8D90C15A4A1A8ED1DD2E2F3DLLOSHAASQ
+ _associated conformance 14CoreBrightness11CurveUpdateV10CodingKeys33_42516BEE8D90C15A4A1A8ED1DD2E2F3DLLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 14CoreBrightness11CurveUpdateV10CodingKeys33_42516BEE8D90C15A4A1A8ED1DD2E2F3DLLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14CoreBrightness11FitPriorityOSHAASQ
+ _associated conformance 14CoreBrightness12ABCurvePointV10CodingKeys33_4A39D4208AEC32D8E64F643932C9EA11LLOSHAASQ
+ _associated conformance 14CoreBrightness12ABCurvePointV10CodingKeys33_4A39D4208AEC32D8E64F643932C9EA11LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 14CoreBrightness12ABCurvePointV10CodingKeys33_4A39D4208AEC32D8E64F643932C9EA11LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14CoreBrightness13InnerPrefsKeyOSHAASQ
+ _associated conformance 14CoreBrightness13InnerPrefsKeyOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 14CoreBrightness13OuterPrefsKeyOSHAASQ
+ _associated conformance 14CoreBrightness13OuterPrefsKeyOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 14CoreBrightness13PreferenceAgeOSHAASQ
+ _associated conformance 14CoreBrightness13PreferenceAgeOSLAASQ
+ _associated conformance 14CoreBrightness16PreferenceRegionOSHAASQ
+ _associated conformance 14CoreBrightness16PreferenceRegionOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 14CoreBrightness36DSBucketedRatchetingAdjustmentConfigV10CodingKeys33_C330FD7761047F37E0F5715B981A595BLLOSHAASQ
+ _associated conformance 14CoreBrightness36DSBucketedRatchetingAdjustmentConfigV10CodingKeys33_C330FD7761047F37E0F5715B981A595BLLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 14CoreBrightness36DSBucketedRatchetingAdjustmentConfigV10CodingKeys33_C330FD7761047F37E0F5715B981A595BLLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14CoreBrightness36DSBucketedRatchetingPowerStateConfigV10CodingKeys33_C330FD7761047F37E0F5715B981A595BLLOSHAASQ
+ _associated conformance 14CoreBrightness36DSBucketedRatchetingPowerStateConfigV10CodingKeys33_C330FD7761047F37E0F5715B981A595BLLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 14CoreBrightness36DSBucketedRatchetingPowerStateConfigV10CodingKeys33_C330FD7761047F37E0F5715B981A595BLLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14CoreBrightness36DSBucketedRatchetingPowerStateConfigV15RangeCodingKeys33_C330FD7761047F37E0F5715B981A595BLLOSHAASQ
+ _associated conformance 14CoreBrightness36DSBucketedRatchetingPowerStateConfigV15RangeCodingKeys33_C330FD7761047F37E0F5715B981A595BLLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 14CoreBrightness36DSBucketedRatchetingPowerStateConfigV15RangeCodingKeys33_C330FD7761047F37E0F5715B981A595BLLOs0I3KeyAAs28CustomDebugStringConvertible
+ _dispatch_queue_attr_make_with_autorelease_frequency
+ _dispatch_suspend
+ _get_enum_tag_for_layout_string 14CoreBrightness29DynamicSliderAdjustmentPolicyO
+ _kCABrightnessNotificationSecureIndicatorActiveCount
+ _kCABrightnessNotificationSecureIndicatorOff
+ _kCABrightnessNotificationSecureIndicatorOn
+ _kCABrightnessNotificationSecureIndicatorType
+ _keypath_get_selector_boostEnd
+ _keypath_get_selector_boostFull
+ _keypath_get_selector_boostFullEnd
+ _keypath_get_selector_boostScaler
+ _keypath_get_selector_boostStart
+ _log2
+ _swift_getAtKeyPath
+ _swift_getKeyPath
+ _swift_makeBoxUnique
+ _swift_retain_x26
+ _swift_setAtReferenceWritableKeyPath
+ _symbolic $s14CoreBrightness22CBParsableFromProviderP
+ _symbolic SDySSypG
+ _symbolic SNySfGSg
+ _symbolic SS______ySo17CBBrightnessBoostCSfGt s24ReferenceWritableKeyPathC
+ _symbolic SaySNySfGG
+ _symbolic SaySiG
+ _symbolic Say_____G 14CoreBrightness11CurveUpdateV
+ _symbolic Say_____G 14CoreBrightness13InnerPrefsKeyO
+ _symbolic Say_____G 14CoreBrightness13OuterPrefsKeyO
+ _symbolic Say_____G 14CoreBrightness16PreferenceRegionO
+ _symbolic Say______pGIeghg_ So17CBALSNodeProtocolP
+ _symbolic Sd
+ _symbolic SiSg
+ _symbolic So17CBBrightnessBoostC
+ _symbolic So7NSArrayCIeyBhy_
+ _symbolic _____ 14CoreBrightness11CurveUpdateV
+ _symbolic _____ 14CoreBrightness11CurveUpdateV10CodingKeys33_42516BEE8D90C15A4A1A8ED1DD2E2F3DLLO
+ _symbolic _____ 14CoreBrightness11FitPriorityO
+ _symbolic _____ 14CoreBrightness12ABCurvePointV
+ _symbolic _____ 14CoreBrightness12ABCurvePointV10CodingKeys33_4A39D4208AEC32D8E64F643932C9EA11LLO
+ _symbolic _____ 14CoreBrightness13AABPreferenceV
+ _symbolic _____ 14CoreBrightness13InnerPrefsKeyO
+ _symbolic _____ 14CoreBrightness13OuterPrefsKeyO
+ _symbolic _____ 14CoreBrightness13PreferenceAgeO
+ _symbolic _____ 14CoreBrightness14FittedSegmentsV
+ _symbolic _____ 14CoreBrightness15PendingOverrideV
+ _symbolic _____ 14CoreBrightness15ReferencePointsV
+ _symbolic _____ 14CoreBrightness16PreferenceRegionO
+ _symbolic _____ 14CoreBrightness19PreferenceRegionMapV
+ _symbolic _____ 14CoreBrightness20ThreeSegmentAABCurveC
+ _symbolic _____ 14CoreBrightness26ThreeSegmentAABCurveConfigV
+ _symbolic _____ 14CoreBrightness31ThreeSegmentAABCurvePreferencesC
+ _symbolic _____ 14CoreBrightness33ThreeSegmentDefaultSegmentsConfigV
+ _symbolic _____ 14CoreBrightness36DSBucketedRatchetingAdjustmentConfigV
+ _symbolic _____ 14CoreBrightness36DSBucketedRatchetingAdjustmentConfigV10CodingKeys33_C330FD7761047F37E0F5715B981A595BLLO
+ _symbolic _____ 14CoreBrightness36DSBucketedRatchetingPowerStateConfigV
+ _symbolic _____ 14CoreBrightness36DSBucketedRatchetingPowerStateConfigV10CodingKeys33_C330FD7761047F37E0F5715B981A595BLLO
+ _symbolic _____ 14CoreBrightness36DSBucketedRatchetingPowerStateConfigV15RangeCodingKeys33_C330FD7761047F37E0F5715B981A595BLLO
+ _symbolic _____Sg 14CoreBrightness13AABPreferenceV
+ _symbolic _____Sg 14CoreBrightness15PendingOverrideV
+ _symbolic ______p6sensor_SiSg8intervalt So17CBALSNodeProtocolP
+ _symbolic _____ySNySfGG s23_ContiguousArrayStorageC
+ _symbolic _____ySS______ySo17CBBrightnessBoostCSfGtG s23_ContiguousArrayStorageC s24ReferenceWritableKeyPathC
+ _symbolic _____ySS_____ySo17CBBrightnessBoostCSfGG s18_DictionaryStorageC s24ReferenceWritableKeyPathC
+ _symbolic _____ySiG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14CoreBrightness11CurveUpdateV10CodingKeys33_42516BEE8D90C15A4A1A8ED1DD2E2F3DLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14CoreBrightness12ABCurvePointV10CodingKeys33_4A39D4208AEC32D8E64F643932C9EA11LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14CoreBrightness11CurveUpdateV10CodingKeys33_42516BEE8D90C15A4A1A8ED1DD2E2F3DLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14CoreBrightness12ABCurvePointV10CodingKeys33_4A39D4208AEC32D8E64F643932C9EA11LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14CoreBrightness36DSBucketedRatchetingAdjustmentConfigV10CodingKeys33_C330FD7761047F37E0F5715B981A595BLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14CoreBrightness36DSBucketedRatchetingPowerStateConfigV10CodingKeys33_C330FD7761047F37E0F5715B981A595BLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14CoreBrightness36DSBucketedRatchetingPowerStateConfigV15RangeCodingKeys33_C330FD7761047F37E0F5715B981A595BLLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 14CoreBrightness11CurveUpdateV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 14CoreBrightness13PreferenceAgeO
+ _symbolic _____y______p6sensor_SiSg8intervaltG s23_ContiguousArrayStorageC So17CBALSNodeProtocolP
+ _type_layout_string 14CoreBrightness11CurveUpdateV
+ _type_layout_string 14CoreBrightness12ABCurvePointV
+ _type_layout_string 14CoreBrightness13AABPreferenceV
+ _type_layout_string 14CoreBrightness14FittedSegmentsV
+ _type_layout_string 14CoreBrightness15PendingOverrideV
+ _type_layout_string 14CoreBrightness15ReferencePointsV
+ _type_layout_string 14CoreBrightness19PreferenceRegionMapV
+ _type_layout_string 14CoreBrightness26ThreeSegmentAABCurveConfigV
+ _type_layout_string 14CoreBrightness29DynamicSliderAdjustmentPolicyO
+ _type_layout_string 14CoreBrightness33ThreeSegmentDefaultSegmentsConfigV
+ _type_layout_string 14CoreBrightness36DSBucketedRatchetingAdjustmentConfigV
+ _type_layout_string 14CoreBrightness36DSBucketedRatchetingPowerStateConfigV
- +[CBSBIM needsSBIM]
- -[AABRear addHIDServiceClient:]
- -[AABRear copyPropertyForKey:]
- -[AABRear copyPropertyForKey:withParameter:]
- -[AABRear handleEvent:]
- -[AABRear handleNotificationForKey:withProperty:]
- -[AABRear initWithQueue:andGrimaldiFactory:]
- -[AABRear isRearALSSupported]
- -[AABRear removeHIDServiceClient:]
- -[AABRear setProperty:forKey:]
- -[AABRear start]
- -[CBAABiOSCurveWrapper reset]
- -[CBABCurve reset]
- -[CBABCurve transferStateFrom:]
- -[CBABCurveNitsBased reset]
- -[CBABModuleiOS newGrimaldiFactory:]
- -[CBCPMSModule rampCPMSNitsCap:withCurrentSDRNits:]
- -[CBColorModuleShared addProxFilterWithALSNode:]
- -[CBColorModuleShared handleFilterNotificationForKey:withProperty:]
- -[CBDigitizerNode newFilterForALS:logCategory:]
- -[CBDisplayContext initWithQueue:andSystemContext:andBrtCtl:andConfig:andTwilight:andAmmolite:andGCP:andCADisplay:andCBPM:andAODState:andRingLight:]
- -[CBGrimaldiFactory dealloc]
- -[CBGrimaldiFactory eventSource]
- -[CBGrimaldiFactory isReady]
- -[CBGrimaldiFactory newInstance]
- -[CBGrimaldiFactory queue]
- -[CBGrimaldiFactory samplingStrategy]
- -[CBGrimaldiFactory setEventSource:]
- -[CBGrimaldiFactory setQueue:]
- -[CBGrimaldiFactory setSamplingStrategy:]
- -[CBGrimaldiModule CBAPDSGetCoex]
- -[CBGrimaldiModule provideCoex]
- -[CBGrimaldiModule provideLux]
- -[CBGrimaldiModule registerNotificationBlock:]
- -[CBGrimaldiModule setProvideCoex:]
- -[CBGrimaldiModule setProvideLux:]
- -[CBGrimaldiModule unregisterNotificationBlock]
- -[CBProxNode newFilterForALS:logCategory:]
- -[CBRearALSModule AABSensorOverridePropertyHandler:]
- -[CBRearALSModule addHIDServiceClient:]
- -[CBRearALSModule copyRearLux]
- -[CBRearALSModule displayBrightnessFactorPropertyHandler:]
- -[CBRearALSModule handleEvent:]
- -[CBRearALSModule initWithQueue:andGrimaldiFactory:]
- -[CBRearALSModule isMitigationActive]
- -[CBRearALSModule isRearALSSupported]
- -[CBRearALSModule rLuxOverridePropertyHandler:]
- -[CBRearALSModule removeHIDServiceClient:]
- -[CBRearALSModule startSamplingWithFrequency:]
- -[CBRearALSModule stopSampling]
- -[CBSBIM initWithQueue:andDisplayModule:andEDRModule:andEDRThreshold:]
- -[VMBLControl cacheBrightnessTransaction:builtIn:displayIdentifier:]
- -[VMBLControl removeCachedBrightnessTransactionForDisplayIdentifier:builtIn:]
- GCC_except_table190
- GCC_except_table36
- GCC_except_table41
- GCC_except_table65
- GCC_except_table76
- GCC_except_table89
- _CFDictionaryRemoveAllValues
- _OBJC_CLASS_$_CBGrimaldiFactory
- _OBJC_CLASS_$_OS_dispatch_queue
- _OBJC_IVAR_$_CBGrimaldiFactory._eventSource
- _OBJC_IVAR_$_CBGrimaldiFactory._queue
- _OBJC_IVAR_$_CBGrimaldiFactory._samplingStrategy
- _OBJC_IVAR_$_CBGrimaldiModule._provideCoex
- _OBJC_IVAR_$_CBGrimaldiModule._provideLux
- _OBJC_IVAR_$_CBRearALSModule._displayOn
- _OBJC_IVAR_$_CBRearALSModule._enableIlluminanceOverride
- _OBJC_IVAR_$_CBRearALSModule._illuminanceOverride
- _OBJC_IVAR_$_CBRearALSModule._jasperCoex
- _OBJC_IVAR_$_CBRearALSModule._lastALSEvent
- _OBJC_IVAR_$_CBRearALSModule._lastLux
- _OBJC_IVAR_$_CBRearALSModule._providerType
- _OBJC_IVAR_$_CBRearALSModule._rearALS
- _OBJC_IVAR_$_CBRearALSModule._started
- _OBJC_IVAR_$_CBRearALSModule._strobeCoex
- _OBJC_METACLASS_$_CBGrimaldiFactory
- _OUTLINED_FUNCTION_35
- __OBJC_$_CLASS_METHODS_CBSBIM
- __OBJC_$_INSTANCE_METHODS_CBGrimaldiFactory
- __OBJC_$_INSTANCE_VARIABLES_CBGrimaldiFactory
- __OBJC_$_PROP_LIST_CBGrimaldiFactory
- __OBJC_CLASS_PROTOCOLS_$_AABRear
- __OBJC_CLASS_PROTOCOLS_$_CBABCurve
- __OBJC_CLASS_RO_$_CBGrimaldiFactory
- __OBJC_METACLASS_RO_$_CBGrimaldiFactory
- __ZN14CoreBrightness24create_array_from_cfdataIfEEmPKvPPT_
- __ZN14CoreBrightness24create_array_from_cfdataIiEEmPKvPPT_
- __ZN14CoreBrightness24create_array_from_cfdataIjEEmPKvPPT_
- __ZN14CoreBrightness24create_array_from_cfdataIsEEmPKvPPT_
- __ZN14CoreBrightness24create_array_from_cfdataItEEmPKvPPT_
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt12out_of_rangeC1B9fqe220100EPKc
- __ZNSt3__113__tree_removeB9fqe220100IPNS_16__tree_node_baseIPvEEEEvT_S5_
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__120__throw_out_of_rangeB9fqe220100EPKc
- __ZNSt3__127__insertion_sort_incompleteB9fqe220100INS_17_ClassicAlgPolicyERZN7CBBOLTS13serializeBinsERKNS_6vectorINS2_3BinENS_9allocatorIS4_EEEEE3$_0PN3AAB11CurveUpdateEEEbT1_SF_T0_
- __ZNSt3__127__tree_balance_after_insertB9fqe220100IPNS_16__tree_node_baseIPvEEEEvT_S5_
- __ZNSt3__128__exception_guard_exceptionsIZNS_4listIN3AAB11CurveUpdateENS_9allocatorIS3_EEE22__insert_with_sentinelB9fqe220100INS_21__list_const_iteratorIS3_PvEESA_EENS_15__list_iteratorIS3_S9_EESA_T_T0_EUlvE_ED2B9fqe220100Ev
- __ZNSt3__128__exception_guard_exceptionsIZNS_4listIN3AAB11CurveUpdateENS_9allocatorIS3_EEE22__insert_with_sentinelB9fqe220100IPKS3_S9_EENS_15__list_iteratorIS3_PvEENS_21__list_const_iteratorIS3_SB_EET_T0_EUlvE_ED2B9fqe220100Ev
- __ZNSt3__134__uninitialized_allocator_relocateB9fqe220100INS_9allocatorIN7CBBOLTS3BinEEEPS3_EEvRT_T0_S8_S8_
- __ZNSt3__14listIN3AAB11CurveUpdateENS_9allocatorIS2_EEE22__insert_with_sentinelB9fqe220100INS_21__list_const_iteratorIS2_PvEES9_EENS_15__list_iteratorIS2_S8_EES9_T_T0_
- __ZNSt3__14listIN3AAB11CurveUpdateENS_9allocatorIS2_EEE22__insert_with_sentinelB9fqe220100IPKS2_S8_EENS_15__list_iteratorIS2_PvEENS_21__list_const_iteratorIS2_SA_EET_T0_
- __ZNSt3__16__treeINS_12__value_typeIPvU13block_pointerFv17PMMitigationLevelEEENS_19__map_value_compareIS2_NS_4pairIKS2_S5_EENS_4lessIS2_EEEENS_9allocatorISA_EEE14__tree_deleterclB9fqe220100EPNS_11__tree_nodeIS6_S2_EE
- __ZNSt3__16vectorI11FrameSampleNS_9allocatorIS1_EEE20__throw_out_of_rangeB9fqe220100Ev
- __ZNSt3__16vectorIN3AAB11CurveUpdateENS_9allocatorIS2_EEE18__insert_with_sizeB9fqe220100INS_17_ClassicAlgPolicyENS_11__wrap_iterIPS2_EESA_EESA_NS8_IPKS2_EET0_T1_l
- __ZNSt3__16vectorIN3AAB11CurveUpdateENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIN7CBBOLTS16BinConfigurationENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIN7CBBOLTS3BinENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIN7CBBOLTS3BinENS_9allocatorIS2_EEED1B9fqe220100Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEE18__assign_with_sizeB9fqe220100INS_17_ClassicAlgPolicyEPfS6_EEvT0_T1_l
- __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEEC1B9fqe220100ERKS3_
- __ZNSt3__17__sort5B9fqe220100INS_17_ClassicAlgPolicyERZN7CBBOLTS13serializeBinsERKNS_6vectorINS2_3BinENS_9allocatorIS4_EEEEE3$_0PN3AAB11CurveUpdateELi0EEEvT1_SF_SF_SF_SF_T0_
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- ___29-[CBABModuleiOS setupAABRear]_block_invoke
- ___33-[BLControl startHIDSystemClient]_block_invoke_4
- ___33-[BLControl startHIDSystemClient]_block_invoke_5
- ___43-[CBColorModuleShared addHIDServiceClient:]_block_invoke
- ___44-[AABRear initWithQueue:andGrimaldiFactory:]_block_invoke
- ___48-[CBColorModuleShared addProxFilterWithALSNode:]_block_invoke
- ___51-[CBCPMSModule rampCPMSNitsCap:withCurrentSDRNits:]_block_invoke
- ___52-[CBRearALSModule initWithQueue:andGrimaldiFactory:]_block_invoke
- ___block_descriptor_40_e8_32o_e29_v16?0"<CBALSNodeProtocol>"8ls32l8
- ___block_descriptor_40_e8_32r_e19_f20?0f8"CBRamp"12lr32l8
- ___block_descriptor_72_e8_32o40o48o56r_e5_v8?0ls32l8r56l8s40l8s48l8
- ___swift_memcpy25_4
- _load_integer_array_from_edt
- _swift_release_x9
- _symbolic SDySSSiG
- _symbolic SS_Sit
- _symbolic Say_____G So17OS_dispatch_queueC8DispatchE10AttributesV
- _symbolic _____ySSSiG s18_DictionaryStorageC
- _symbolic _____ySS_SitG s23_ContiguousArrayStorageC
CStrings:
+ "%s IB = MIB (%f)"
+ "%s-%u"
+ "%s.AABRear.%u"
+ ".MIB"
+ "0-7"
+ "0-9"
+ "10-19"
+ "10-74"
+ "100-199"
+ "100-249"
+ "1000-1199"
+ "1000-1999"
+ "10000-19999"
+ "1200-1599"
+ "128-255"
+ "16-31"
+ "1600-1999"
+ "20-29"
+ "200-299"
+ "2000-2499"
+ "2000-4999"
+ "250-349"
+ "2500-2999"
+ "256-511"
+ "30-49"
+ "300-499"
+ "32-63"
+ "350-449"
+ "450-549"
+ "50-99"
+ "500-699"
+ "5000-9999"
+ "512-999"
+ "550-749"
+ "64-127"
+ "700-999"
+ "75-99"
+ "750-999"
+ "8-15"
+ ":"
+ ">=1000"
+ ">=20000"
+ ">=3000"
+ "AAB off factor not found"
+ "AABC"
+ "AABRear"
+ "ABCurvePoint: (lux: "
+ "ALSDefaultRateManager"
+ "ALSManager activation failed: %@"
+ "ALSSensorConfiguration: interval=none"
+ "Adjusting AAB curve for preference point: %s (uncapped lux: %f, unscaled nits: %f"
+ "Already at correct brightness %f with ramp not running"
+ "Already running ramp with the same target %f"
+ "Applied headroom is lower than 1 (%f), ignoring"
+ "Boosted %f * %f to %f at %flux"
+ "CBDisplayPassthroughPolicy"
+ "CBExternalDisplayKeyPolicy"
+ "CFXSetUVColorMitigatedTh1: invalid ref or harmony context"
+ "CFXSetUVColorMitigatedTh2: invalid ref or harmony context"
+ "CFXSetUVTh1: invalid ref or harmony context"
+ "CFXSetUVTh2: invalid ref or harmony context"
+ "CPMSCurrentSDRNits"
+ "CPMSSetNitsCapWithDuration"
+ "Caching headroom request:%@ from displayUUID:%@ builtIn:%d"
+ "Calculated contrast IB=%f, capped=%f, contentHeadroom=%f, HDR=%d"
+ "Can't ramp MIB target %f when SIL is off"
+ "Cannot create module without Grimaldi endpoint"
+ "Cannot work without rearALSModule"
+ "Client %{public}@ requesting frequency %.1f Hz"
+ "ColorUVColorMitigatedTh1"
+ "ColorUVColorMitigatedTh2"
+ "ColorUVTh1"
+ "ColorUVTh2"
+ "Contrast indicator enabled: %d"
+ "CoreBrightness.ThreeSegmentAABCurve"
+ "CoreBrightness.ThreeSegmentAABCurvePreferences"
+ "CoreBrightness_Internal.CBBrightnessBoost"
+ "CoreBrightness_Internal.CBThreeSegmentAABCurve"
+ "Could not construct"
+ "Could not create battery factor curve for max brightness restriction"
+ "Could not create charger factor curve for max brightness restriction"
+ "Could not fetch the minimum panel nits!"
+ "Created ramp %f -> %f @ %f"
+ "Curve segments before updating:\n    dark: (start: %s, end: %s)\n    mid: (start: %s, end: %s)\n    bright: slope: %f"
+ "DCPSEC"
+ "DarkLightThreshold"
+ "Device does not have Grimaldi capability"
+ "DisplayPowerStateEvent"
+ "EXBrightMIB"
+ "EXBrightSILEnabledTrusted"
+ "EXBrightSILStateUntrusted"
+ "EXBrightSILStateUntrustedDisplayID"
+ "EXBrightSILStateUntrustedEnable"
+ "EXBrightUIBrightness"
+ "EXBrightUIBrightnessDisplayID"
+ "EXBrightUIBrightnessValue"
+ "Enabling SIL after restart!"
+ "Ending ramp"
+ "Enforce MIB: %d"
+ "Failed to activate ALS client: %{public}@"
+ "Failed to clear ALS interval: %{public}@"
+ "Failed to copy property %s from MIB service (%lu)"
+ "Failed to create AABC ALS client"
+ "Failed to create CBIndicatorAnalyticsModule"
+ "Failed to create coex tracker."
+ "Failed to create frequency NSNumber, display might not ramp"
+ "Failed to create ramp %f -> %f @ %f"
+ "Failed to set ALS interval: %{public}@"
+ "Failed to set ALS test mode interval: %{public}@"
+ "Forced brightness transaction"
+ "Found %s : %d in backlight node"
+ "Found %s : %d in core-brightness node"
+ "INDICATOR_RAMP"
+ "Ignoring IB target (%f) that is different than current SDR brightness (%f)"
+ "Incorrect values in age array: %s"
+ "IndicatorBrightness"
+ "IndicatorBrightness.Cap"
+ "IndicatorBrightness.Limit"
+ "IndicatorBrightness.Nits"
+ "IndicatorBrightnessFollowsMIB"
+ "IndicatorBrightnessFollowsMIBEnable"
+ "IndicatorBrightnessFollowsMIBValue"
+ "IndicatorBrightnessModule Init | min: %f, max: %f, contrastBoostMax: %f, mibCompensationFactor: %f"
+ "IndicatorContrastEnabled"
+ "IndicatorModule"
+ "IndicatorRampFinishedAOD"
+ "IndicatorUpdateRampAOD"
+ "Initialized preferences for UUID %s:\n    dark segment: (start: %s, end: %s),\n    mid segment: (start: %s, end: %s),\n    brightSlope: %f,\n    preferences: %s,\n    pendingOverride: %s,\n    justOverridenBrightValue: %{bool}d,\n    updateTimestamp: %f,\n    curveUpdates: %s"
+ "Initializing AAB curve for curveName: %s with config:\n    minNits: %f, maxNits: %f,\n    slopeMin: %f, slopeMax: %f,\n    darkSlopeMax: %f, luxDarkLightThreshold: %f,\n    minMidEndLux: %f, maxLux: %f"
+ "Initializing AAB curve preferences for UUID: %s with AAB contraints dict: %s"
+ "Insufficient configuration to initialize bucketed ratcheting adjustment policy"
+ "Invalid prefs dictionary: %s"
+ "Invalid three-segment preferences dictionary: %s"
+ "Jumping to target indicator brightness: %f"
+ "MIB ramp speed can't be 0 seconds/stop, using default ramp speed"
+ "MIB ramp speed overriden to %f seconds/stop"
+ "Max nits not provided in configuration, can't create max brightness restriction"
+ "MaxSlope"
+ "Migration from legacy linear brightness single segment AAB curve not implemented yet, using default curve"
+ "Migration from linear brightness single segment AAB curve not implemented yet, using default curve"
+ "Migration from nits single segment AAB curve not implemented yet, using default curve"
+ "MinE2"
+ "MinSlope"
+ "MinimumIndicatorBrightness"
+ "MinimumIndicatorBrightnessCompensationFactor"
+ "MinimumIndicatorBrightnessEnforce"
+ "Misconfiguration in AAB curve config: darkStartLux cannot be equal to darkEndLux"
+ "Misconfiguration in AAB curve config: minSlope cannot be 0"
+ "Misconfiguration in preferences config: midEndLux cannot be 0"
+ "Misconfiguration in preferences config: midEndLux cannot be equal to darkEndLux"
+ "Negative MIB %f, ignoring"
+ "Negative SDR brightness %f, ignoring"
+ "Negative lux %f, ignoring"
+ "Nits for lux: %f is: %f (unscaled nits: %f"
+ "No AAB contraints dict, cannot initialize curve"
+ "Pivot nits for max restriction not provided"
+ "Policy"
+ "PreferenceRegionMap: [dark: "
+ "Preferences applied: %s (%s)"
+ "Preferences were not initialized, cannot initialize curve"
+ "PropertyPolicy"
+ "RTPLC Cap (%f) < MIB (%f), this should never happen!"
+ "Replaying %lu cached headroom request(s)"
+ "Resetting preferences to default state"
+ "Restoring cached MIB: %f"
+ "SBIM Initialization | SBIM supported (panel index: %d, fbname: %@)"
+ "SDR brightness is higher than current IB - something is probably off"
+ "SIL OFF @ %f us (was ON for %f us)"
+ "SIL ON @ %f us"
+ "Saved preferences could not be loaded, starting with default preferences from config"
+ "SecureIndicatorActiveCount"
+ "SecureIndicatorBrightnessRampSpeed"
+ "SecureIndicatorLightEnabled"
+ "SecureIndicatorState"
+ "Selected preference region: %s"
+ "Selected reference points:\n    dark: %s\n    bright: %s\n    priority: %s"
+ "Set %s to %f"
+ "Setting UV Color Mitigated Th1 (1D Harmony - start new ramp threshold) to: %f"
+ "Setting UV Color Mitigated Th2 (1D Harmony - interrupt ramp threshold) to: %f"
+ "Setting UV Th1 (1.5D Harmony - start new ramp threshold) to: %f"
+ "Setting UV Th2 (1.5D Harmony - interrupt ramp threshold) to: %f"
+ "Short-cutting ramp for contrast indicator %f -> %f"
+ "ShouldUseRearLuxFrontLux(fLux:%.2f, rLux:%.2f, cap: %.2f) = %s"
+ "ShouldUseRearLuxFrontLux(fLux:%.2f, rLux:%.2f, cap: %.2f) = %s -> %s"
+ "Some of the required keys to initialize curve are missing in capabilities"
+ "Some of the required keys to initialize preferences are missing in capabilities"
+ "SyncDBV Transaction | ID=%llu | SDR.Nits=%.3f | Applied.Compensation=%.3f | Nits.Cap=%0.3f | DynamicSlider.Cap=%0.3f | Brightness.Limit=%0.3f | Trusted.Lux=%.3f | HDR.Nits=%.3f | HDR.State=%s | Capped.Headroom.Current=%0.3f  | Aurora.Factor=%0.3f | Aurora.RampInProgress=%s | RTPLC.State=%s | RTPLC.Cap=%.3f | RTPLC.CapApplied=%s | PeakAPCE.Cap=%0.3f | IndicatorBrightness.Nits=%.3f | IndicatorBrightness.Cap=%.3f | Twilight.Strength=%0.3f | Ammolite.Strength=%0.3f | GCP.Strength=%0.3f | ContrastEnhancer.Strength=%.3f |"
+ "TargetIB(%f) < SDR(%f)"
+ "Transitioning to Flipbook, forcing NaN IB to CA!"
+ "Transitioning to flipbook with SIL state still ON, shortcutting..."
+ "Unknown DCP role %@, defaulting to id %u"
+ "Updated curve segments:\n    dark: (start: %s, end: %s)\n    mid: (start: %s, end: %s)\n    bright: (slope: %f"
+ "Updated ramp %f -> %f @ %f"
+ "Updating MIB compensation factor: %f"
+ "Updating current factor from %f to %f immediately"
+ "WARNING: Ramp was running while forced brightness transaction happened"
+ "Wrong value type for UV threshold property (%{public}@) %@"
+ "[AOD update][CA] Pushing sdrBrightness: %f, capped _appliedHeadroom: %f, brightnessLimit: %f, PCC: %f, Whitepoint: ( %f | %f ), TwilightStrength: %f, AmmoliteStrength: %f, GCPStrength: %f, IndicatorBrightness: %f, IndicatorBrightnessLimit: %f, Ambient: %f"
+ "[AOD] Already at correct brightness %f with ramp not running"
+ "[CBU_IsIndicatorSupported] supported=%d"
+ "[CPMS] Current SDR brightness updated: %f -> %f"
+ "[CPMS] Display turning on - sending immediate cap update to terminate active thermal ramp (cap=%f)"
+ "[CPMS] Sending nits cap ramp to display: target=%f duration=%fs"
+ "[CPMS] Using current SDR nits (%f) instead of cap (%f) for ramp duration calculation"
+ "[Coex] MITIGATION: Cancel color ramp, all ALSes with coex"
+ "[Coex] MITIGATION: coex detected on ALS[%@]"
+ "[Coex]: ALS discarded by coex [%@]"
+ "[Display] CPMS ramp request: target=%f duration=%f"
+ "[Display] Received CPMS ramp request: target=%f duration=%fs"
+ "[Harmony thresholds] 1.5D Harmony: uv_thr1(new_ramp)=%f, uv_thr2(interrupt)=%f Lux=%f"
+ "[Harmony thresholds] Interrupt ramp by forceUpdate =%d || deltauv=%f >= uv_thr2(interrupt)=%f Lux=%f"
+ "[Harmony thresholds] Mitigation triggered -> 1D Harmony: uv_thr1(new_ramp)=%f, uv_thr2(interrupt)=%f Lux=%f"
+ "[Harmony thresholds] Start new ramp by deltauv=%f >= uv_thr1(new_ramp)=%f Lux=%f"
+ "[Linear Weighted] xy= %f | %f ratio=%f"
+ "[Log Weighted] xy= %f | %f ratio=%f"
+ "[New Event] eventTimestamp=%llu (unknown payload)"
+ "[New Event] eventTimestamp=%llu MIBData.(ts=%fs mib=%f aggregatedLux=%f display=%u)\n"
+ "[New Event] unknown event type %u"
+ "[SIL Hint] Received MIB while SIL OFF, turning SIL ON..."
+ "[SIL Hint] now=%f motMet=%d shouldUseHint=%d"
+ "[dcpRoleID=%d] SIL=%d, monotonicTimeUS=%llu. Sending to EXBright: %@."
+ "[updateMaxContrastBoostedBrightness] maxContrastBoostedBrightness=%f"
+ "boostEnd"
+ "boostFull"
+ "boostFullEnd"
+ "boostScaler"
+ "boostStart"
+ "brightness.device.current %f -> factor %f"
+ "bucketedRatcheting"
+ "buckets"
+ "com.apple.CoreBrightness.ALSDefaultRateManager"
+ "com.apple.CoreBrightness.CBALSSelectionPolicy.%d"
+ "com.apple.CoreBrightness.CBBrightnessBoost"
+ "com.apple.CoreBrightness.CBRearALSModule"
+ "com.apple.CoreBrightness.GrimaldiQueue"
+ "com.apple.CoreBrightness.SBIM.%d"
+ "com.apple.CoreBrightness.ThreeSegmentAABCurve."
+ "com.apple.CoreBrightness.ThreeSegmentAABCurvePreferences."
+ "contrast_indicator"
+ "ddEdge"
+ "deadZone"
+ "displayID"
+ "enforce_mib"
+ "internal-0"
+ "lastAppliedInterval"
+ "lowerBound"
+ "matchBright"
+ "matchDark"
+ "max_factors_charger"
+ "max_thresholds_charger"
+ "nitsEdge"
+ "no-contrast-indicator"
+ "primary"
+ "sensor (p:%d|o:%d): interval %d -> %d ms"
+ "sessionID"
+ "sessionTime"
+ "setIndicatorBrightness:"
+ "setIndicatorBrightnessLimit:"
+ "sil-enabled"
+ "targetNits"
+ "updateRamp called, isRampRunning: %s, silState: %s, currentSDRBrightness: %f, currentIB: %f, targetIB: %f, MIB: %f"
+ "updateRamp finished, isRampRunning: %s, silState: %s, currentSDRBrightness: %f, currentIB: %f, targetIB: %f, MIB: %f"
+ "upperBound"
+ "v64@?0Q8Q16Q24@\"NSString\"32@\"NSString\"40@\"NSString\"48@\"NSNumber\"56"
- "AABRear: %suse rear Lux (fLux:%f, rLux:%f, cap: %f)"
- "AABRear: failed to create log handle"
- "AABRear: shouldUseRearLuxFrontLux called with (fLux:%f, rLux:%f, cap: %f)"
- "AABRear: using rear? %d"
- "APDSGetCoex: Strobe %s, Lidar %s"
- "AllowGrimaldi"
- "CPMSNitsCapStartRamp"
- "CPMSUpdateNitsCap"
- "CPMS_NITS_CAP_RAMP"
- "Copied ALS event %@"
- "Copy Grimaldi Lux = %@"
- "Copy overridden rear ALS Lux = %f"
- "Copy rear ALS Lux = %f"
- "Don't "
- "Failed to get coex flags using APDSGetCoexFunction."
- "Failed to initialize CBRearALSModule."
- "Found rear ALS sensor %@."
- "Grimaldi GetCoexFlags"
- "Handle rear ALS hid event %@."
- "MITIGATION: Cancel color ramp on prox mitigation"
- "MITIGATION: Cancel color ramp on touch mitigation"
- "Mitigation is active -> copy last valid rear ALS Lux = %f"
- "Nits cap transition %f -> %f"
- "Override rear ALS samples with value = %f %s."
- "Rear Lux Dictionary: lux = %f, gain = %f, numSamples= %d, absoluteTime = %ld, StrobeCoex = %d, JasperCoex = %d, GainChanged = %d (sample %d/%d)"
- "RearALS: obj (%@) initialized with ALS: %@"
- "Remove rear ALS sensor %@."
- "Requesting lux from APDS"
- "SBIM Initialization | SBIM supported"
- "SBIM Initialization | Unable to obtain SBIM tables"
- "Skipping Grimaldi check"
- "Stop sampling."
- "Strobe mitigation %s."
- "SyncDBV Transaction | ID=%llu | SDR.Nits=%.3f | Applied.Compensation=%.3f | Nits.Cap=%0.3f | DynamicSlider.Cap=%0.3f | Brightness.Limit=%0.3f | Trusted.Lux=%.3f | HDR.Nits=%.3f | HDR.State=%s | Capped.Headroom.Current=%0.3f  | Aurora.Factor=%0.3f | Aurora.RampInProgress=%s | RTPLC.State=%s | RTPLC.Cap=%.3f | RTPLC.CapApplied=%s | PeakAPCE.Cap=%0.3f | Twilight.Strength=%0.3f | Ammolite.Strength=%0.3f | GCP.Strength=%0.3f | ContrastEnhancer.Strength=%.3f |"
- "Touch state changed = %{public}@, orientation = %{public}@"
- "[AOD update][CA] Pushing sdrBrightness: %f, capped _appliedHeadroom: %f, brightnessLimit: %f, PCC: %f, Whitepoint: ( %f | %f ), TwilightStrength: %f, AmmoliteStrength: %f, GCPStrength: %f, Ambient: %f"
- "[CPMS Nits cap] cpms ramp update: %f"
- "[CPMS Nits cap] instant transition: %f -> %f"
- "[CPMS Nits cap] ramp clocked: %f -> %f - %f%%"
- "_ALSClient.handleSensorEvent: ignoreALS=%i | event=%@"
- "com.apple.CoreBrightness.AABRear"
- "com.apple.CoreBrightness.AABRear.CBRearALSModule"
- "handleEvent: %{public}@"
- "handleHIDEvent: %{public}@"
- "internal-%u"
- "v16@?0@\"<CBALSNodeProtocol>\"8"
- "xy= %f | %f ratio=%f"
```
