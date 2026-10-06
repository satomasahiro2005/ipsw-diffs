## CoreBrightness

> `/System/Library/PrivateFrameworks/CoreBrightness.framework/CoreBrightness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x171b9c` | `0x17b78c` | **`+0x9bf0`** |
| `__TEXT.__const` | `0x15828` | `0x1b6b8` | **`+0x5e90`** |
| `__AUTH_CONST.__objc_const` | `0x35760` | `0x38c38` | **`+0x34d8`** |
| `__TEXT.__oslogstring` | `0x19e7d` | `0x1ad8d` | **`+0xf10`** |
| `__TEXT.__objc_methlist` | `0xd60c` | `0xdc6c` | **`+0x660`** |
| `__AUTH_CONST.__cfstring` | `0xe840` | `0xed00` | **`+0x4c0`** |
| `__DATA.__bss` | `0x66f0` | `0x6b40` | **`+0x450`** |
| `__AUTH.__objc_data` | `0x2860` | `0x2c90` | **`+0x430`** |
| `__TEXT.__cstring` | `0xcf85` | `0xd2f5` | **`+0x370`** |
| `__DATA_CONST.__objc_selrefs` | `0x5a70` | `0x5c80` | **`+0x210`** |
| `__TEXT.__unwind_info` | `0x5708` | `0x58f0` | **`+0x1e8`** |
| `__AUTH_CONST.__const` | `0x3dc8` | `0x3fa0` | **`+0x1d8`** |
| `__DATA_CONST.__const` | `0x2ff0` | `0x31b8` | **`+0x1c8`** |
| `__AUTH.__data` | `0x640` | `0x788` | **`+0x148`** |
| `__DATA.__data` | `0x35018` | `0x35160` | **`+0x148`** |
| `__TEXT.__constg_swiftt` | `0xc34` | `0xd64` | **`+0x130`** |
| `__TEXT.__swift5_fieldmd` | `0x1018` | `0x10e8` | **`+0xd0`** |
| `__DATA.__objc_ivar` | `0x179c` | `0x1860` | **`+0xc4`** |
| `__TEXT.__swift5_reflstr` | `0xa4e` | `0xade` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0xeaf` | `0xf3b` | **`+0x8c`** |
| `__DATA_CONST.__objc_classlist` | `0x728` | `0x790` | **`+0x68`** |
| `__AUTH_CONST.__auth_got` | `0x1368` | `0x13b0` | **`+0x48`** |
| `__DATA_CONST.__objc_superrefs` | `0x5f0` | `0x638` | **`+0x48`** |
| `__TEXT.__swift5_builtin` | `0xdc` | `0x118` | **`+0x3c`** |
| `__DATA_CONST.__got` | `0x7b8` | `0x7e8` | **`+0x30`** |
| `__DATA_CONST.__objc_protolist` | `0x370` | `0x398` | **`+0x28`** |
| `__DATA_CONST.__objc_protorefs` | `0x138` | `0x158` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x308` | `0x328` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x120` | `0x138` | **`+0x18`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x70` | `0x80` | **`+0x10`** |
| `__AUTH_CONST.__objc_floatobj` | `0x1a0` | `0x1b0` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x28cc` | `0x28d4` | **`+0x8`** |

### Other Changes

```diff

+  - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

-  Functions: 8832
-  Symbols:   10316
-  CStrings:  4746
+  Functions: 9043
+  Symbols:   10659
+  CStrings:  4865
Symbols:
+ +[CBDisplayTransitionPolicy isBrightnessCommit:]
+ +[CBDisplayTransitionPolicy stringFromPropertyKey:]
+ +[CBDisplayTransitionPolicy stringFromState:]
+ -[CBALSEvent copyXTalkDataFromEvent:]
+ -[CBALSEvent setXtalkEstimates:]
+ -[CBALSEvent xtalkEstimates]
+ -[CBALSNode angleDependent]
+ -[CBALSNode getAngleDependent]
+ -[CBAODModule fadeInBrightnessBoost]
+ -[CBAODModule fadeOutBrightnessBoost]
+ -[CBAngleFilter coexState]
+ -[CBAngleFilter dealloc]
+ -[CBAngleFilter handleALSEvent:]
+ -[CBAngleFilter handleSourceEvent:]
+ -[CBAngleFilter initWithALS:andSource:andThreshold:]
+ -[CBAngleFilter source]
+ -[CBBottomPanelALSSelectionPolicy dealloc]
+ -[CBBottomPanelALSSelectionPolicy initWithLogCategory:displayId:]
+ -[CBBottomPanelALSSelectionPolicy initWithLogCategory:displayId:logTag:]
+ -[CBBottomPanelALSSelectionPolicy select:]
+ -[CBBottomPanelAngleDropPolicy select:]
+ -[CBCMAngleEvent conformsToEvent:]
+ -[CBCMAngleEvent dealloc]
+ -[CBCMAngleEvent eventType]
+ -[CBCMAngleEvent event]
+ -[CBCMAngleEvent getAngleDegrees]
+ -[CBCMAngleEvent getNode]
+ -[CBCMAngleEvent initWithCMAngle:andNode:]
+ -[CBCMAngleEvent service]
+ -[CBCMAngleService canPairWithALS:]
+ -[CBCMAngleService dealloc]
+ -[CBCMAngleService description]
+ -[CBCMAngleService getMaxAngleDegrees]
+ -[CBCMAngleService getMinAngleDegrees]
+ -[CBCMAngleService init]
+ -[CBCMAngleService isStarted]
+ -[CBCMAngleService newFiltersForALS:logCategory:]
+ -[CBCMAngleService startAngleUpdatesToQueue:handler:]
+ -[CBCMAngleService stop]
+ -[CBColorALSSelectionPolicy dealloc]
+ -[CBColorALSSelectionPolicy initWithLogCategory:displayId:coexTracker:]
+ -[CBColorALSSelectionPolicy select:]
+ -[CBColorFloorCoex canPairWithALS:]
+ -[CBColorFloorCoex coexState]
+ -[CBColorFloorCoex currentNits]
+ -[CBColorFloorCoex description]
+ -[CBColorFloorCoex handleALSEvent:]
+ -[CBColorFloorCoex handleSourceEvent:]
+ -[CBColorFloorCoex init]
+ -[CBColorFloorCoex newFiltersForALS:logCategory:]
+ -[CBColorFloorCoex setCurrentNits:]
+ -[CBColorFloorCoex source]
+ -[CBColorModuleShared initALSSelectionPolicy]
+ -[CBColorPolicyFilter computeBaselineStrengthForLux:andNits:andAngle:]
+ -[CBColorPolicyFilter currentAngleDegrees]
+ -[CBColorPolicyFilter setCurrentAngleDegrees:]
+ -[CBColorPolicyFilter setUseAngleDrivenMitigation:]
+ -[CBColorPolicyFilter useAngleDrivenMitigation]
+ -[CBDisplayALSSamplingPolicy adjustedInterval:forSensorPlacement:sensorOrientation:]
+ -[CBDisplayALSSamplingPolicy angleHysteresis]
+ -[CBDisplayALSSamplingPolicy angleThreshold]
+ -[CBDisplayALSSamplingPolicy aodMode]
+ -[CBDisplayALSSamplingPolicy displayOn]
+ -[CBDisplayALSSamplingPolicy initWithPanelPlacement:]
+ -[CBDisplayALSSamplingPolicy isDesignatedAODSensor:orientation:]
+ -[CBDisplayALSSamplingPolicy rearActive]
+ -[CBDisplayALSSamplingPolicy rearSensorInterval]
+ -[CBDisplayALSSamplingPolicy setAngleHysteresis:]
+ -[CBDisplayALSSamplingPolicy setAngleThreshold:]
+ -[CBDisplayALSSamplingPolicy setAodMode:]
+ -[CBDisplayALSSamplingPolicy setDisplayOn:]
+ -[CBDisplayALSSamplingPolicy updateAngle:]
+ -[CBDisplayCoex canPairWithALS:]
+ -[CBDisplayCoex coexState]
+ -[CBDisplayCoex currentNits]
+ -[CBDisplayCoex description]
+ -[CBDisplayCoex handleALSEvent:]
+ -[CBDisplayCoex handleSourceEvent:]
+ -[CBDisplayCoex initWithLogCategory:displayId:]
+ -[CBDisplayCoex newFiltersForALS:logCategory:]
+ -[CBDisplayCoex setCurrentNits:]
+ -[CBDisplayCoex source]
+ -[CBDisplayTransitionPolicy activeSyncLeader]
+ -[CBDisplayTransitionPolicy activeSyncedCount]
+ -[CBDisplayTransitionPolicy beginGracePeriod]
+ -[CBDisplayTransitionPolicy cancelGracePeriodInternal]
+ -[CBDisplayTransitionPolicy cancelGracePeriod]
+ -[CBDisplayTransitionPolicy cancel]
+ -[CBDisplayTransitionPolicy commitBrightnessToLeaderAndSync:]
+ -[CBDisplayTransitionPolicy containerDidAdd:]
+ -[CBDisplayTransitionPolicy containerWillRemove:]
+ -[CBDisplayTransitionPolicy copyPropertyForKey:]
+ -[CBDisplayTransitionPolicy copyStatusInfo]
+ -[CBDisplayTransitionPolicy dealloc]
+ -[CBDisplayTransitionPolicy gracePeriodDidExpire]
+ -[CBDisplayTransitionPolicy handleBrightnessCommit:forKey:]
+ -[CBDisplayTransitionPolicy handleDisplayActivation:forContainer:]
+ -[CBDisplayTransitionPolicy handleDisplayDeactivation:forContainer:]
+ -[CBDisplayTransitionPolicy handleDisplayModeChange:forContainer:]
+ -[CBDisplayTransitionPolicy initWithDelegate:queue:]
+ -[CBDisplayTransitionPolicy isSourceSettled:]
+ -[CBDisplayTransitionPolicy isSyncedContainer:]
+ -[CBDisplayTransitionPolicy performHandoffFromContainer:toContainer:]
+ -[CBDisplayTransitionPolicy prepareHandoffFromSource:toNewDisplay:]
+ -[CBDisplayTransitionPolicy processNotificationForKey:value:container:handle:]
+ -[CBDisplayTransitionPolicy reevaluateState]
+ -[CBDisplayTransitionPolicy setProperty:forKey:]
+ -[CBDisplayTransitionPolicy setProperty:forKey:forContainer:]
+ -[CBDisplayTransitionPolicy syncCurveFromContainer:]
+ -[CBDisplayTransitionPolicy syncedContainers]
+ -[CBTopPanelALSSelectionPolicy select:]
+ GCC_except_table100
+ GCC_except_table102
+ GCC_except_table110
+ GCC_except_table119
+ GCC_except_table123
+ GCC_except_table135
+ GCC_except_table139
+ GCC_except_table142
+ GCC_except_table194
+ GCC_except_table195
+ GCC_except_table232
+ GCC_except_table246
+ GCC_except_table55
+ GCC_except_table59
+ GCC_except_table77
+ _CBU_DeviceHasMultiSensorAODALSPolicy
+ _CGRectContainsPoint
+ _CGRectGetHeight
+ _CGRectGetMinX
+ _CGRectGetMinY
+ _CGRectGetWidth
+ _CGRectNull
+ _DisplaySetBoostFactorWithFade
+ _FEATURE_CNT_V5
+ _OBJC_CLASS_$_CBAngleFilter
+ _OBJC_CLASS_$_CBBottomPanelALSSelectionPolicy
+ _OBJC_CLASS_$_CBBottomPanelAngleDropPolicy
+ _OBJC_CLASS_$_CBCMAngleEvent
+ _OBJC_CLASS_$_CBCMAngleService
+ _OBJC_CLASS_$_CBColorALSSelectionPolicy
+ _OBJC_CLASS_$_CBColorFloorCoex
+ _OBJC_CLASS_$_CBDisplayALSSamplingPolicy
+ _OBJC_CLASS_$_CBDisplayCoex
+ _OBJC_CLASS_$_CBDisplayTransitionPolicy
+ _OBJC_CLASS_$_CBTopPanelALSSelectionPolicy
+ _OBJC_CLASS_$_CBXDXTOcclusionFilter
+ _OBJC_CLASS_$_CMAngleManager
+ _OBJC_CLASS_$_NSOperationQueue
+ _OBJC_IVAR_$_BLControl._angleService
+ _OBJC_IVAR_$_CBALSEvent._xtalkEstimates
+ _OBJC_IVAR_$_CBALSNode._angleDependent
+ _OBJC_IVAR_$_CBAODModule._alsPolicy
+ _OBJC_IVAR_$_CBAngleFilter._alsNode
+ _OBJC_IVAR_$_CBAngleFilter._angleThreshold
+ _OBJC_IVAR_$_CBAngleFilter._currentAngle
+ _OBJC_IVAR_$_CBAngleFilter._source
+ _OBJC_IVAR_$_CBBottomPanelALSSelectionPolicy._logTag
+ _OBJC_IVAR_$_CBCEModule._use35FeatureInput
+ _OBJC_IVAR_$_CBCMAngleEvent._cmAngle
+ _OBJC_IVAR_$_CBCMAngleEvent._node
+ _OBJC_IVAR_$_CBCMAngleEvent.event
+ _OBJC_IVAR_$_CBCMAngleEvent.eventType
+ _OBJC_IVAR_$_CBCMAngleEvent.service
+ _OBJC_IVAR_$_CBCMAngleService._cmManager
+ _OBJC_IVAR_$_CBCMAngleService._started
+ _OBJC_IVAR_$_CBColorALSSelectionPolicy._coexTracker
+ _OBJC_IVAR_$_CBColorALSSelectionPolicy._lastGoodCairns
+ _OBJC_IVAR_$_CBColorALSSelectionPolicy._lastGoodCairnsTimestamp
+ _OBJC_IVAR_$_CBColorFloorCoex._coexState
+ _OBJC_IVAR_$_CBColorFloorCoex._currentAngle
+ _OBJC_IVAR_$_CBColorFloorCoex._logHandle
+ _OBJC_IVAR_$_CBColorFloorCoex.currentNits
+ _OBJC_IVAR_$_CBColorModuleShared._angleService
+ _OBJC_IVAR_$_CBColorModuleShared._colorFloorCoex
+ _OBJC_IVAR_$_CBColorModuleShared._currentAngleDegrees
+ _OBJC_IVAR_$_CBColorModuleShared._displayCoex
+ _OBJC_IVAR_$_CBColorPolicyFilter._currentAngleDegrees
+ _OBJC_IVAR_$_CBColorPolicyFilter._useAngleDrivenMitigation
+ _OBJC_IVAR_$_CBDisplayALSSamplingPolicy._angleHysteresis
+ _OBJC_IVAR_$_CBDisplayALSSamplingPolicy._angleThreshold
+ _OBJC_IVAR_$_CBDisplayALSSamplingPolicy._aodMode
+ _OBJC_IVAR_$_CBDisplayALSSamplingPolicy._displayOn
+ _OBJC_IVAR_$_CBDisplayALSSamplingPolicy._panelPlacement
+ _OBJC_IVAR_$_CBDisplayALSSamplingPolicy._rearActive
+ _OBJC_IVAR_$_CBDisplayALSSamplingPolicy._rearSensorInterval
+ _OBJC_IVAR_$_CBDisplayCoex._coexState
+ _OBJC_IVAR_$_CBDisplayCoex._currentAngle
+ _OBJC_IVAR_$_CBDisplayCoex._logHandle
+ _OBJC_IVAR_$_CBDisplayCoex.currentNits
+ _OBJC_IVAR_$_CBDisplayTransitionPolicy._delegate
+ _OBJC_IVAR_$_CBDisplayTransitionPolicy._goingOffline
+ _OBJC_IVAR_$_CBDisplayTransitionPolicy._gracePeriodDuration
+ _OBJC_IVAR_$_CBDisplayTransitionPolicy._gracePeriodTimer
+ _OBJC_IVAR_$_CBDisplayTransitionPolicy._logHandle
+ _OBJC_IVAR_$_CBDisplayTransitionPolicy._queue
+ _OBJC_IVAR_$_CBDisplayTransitionPolicy._state
+ _OBJC_IVAR_$_CBDisplayTransitionPolicy._syncedKeys
+ _OBJC_METACLASS_$_CBAngleFilter
+ _OBJC_METACLASS_$_CBBottomPanelALSSelectionPolicy
+ _OBJC_METACLASS_$_CBBottomPanelAngleDropPolicy
+ _OBJC_METACLASS_$_CBCMAngleEvent
+ _OBJC_METACLASS_$_CBCMAngleService
+ _OBJC_METACLASS_$_CBColorALSSelectionPolicy
+ _OBJC_METACLASS_$_CBColorFloorCoex
+ _OBJC_METACLASS_$_CBDisplayALSSamplingPolicy
+ _OBJC_METACLASS_$_CBDisplayCoex
+ _OBJC_METACLASS_$_CBDisplayTransitionPolicy
+ _OBJC_METACLASS_$_CBTopPanelALSSelectionPolicy
+ _OBJC_METACLASS_$_CBXDXTOcclusionFilter
+ _XDXT_CH_CNT
+ __DATA_CBXDXTOcclusionFilter
+ __DATA__TtC14CoreBrightnessP33_CA60EA9F041518321383D5DF809F01DE25CBXDXTOcclusionFilterImpl
+ __DisplayGetDeviceBrightnessAfterBrightnessBoost
+ __DisplaySetBoostFactor
+ __INSTANCE_METHODS_CBXDXTOcclusionFilter
+ __IVARS_CBXDXTOcclusionFilter
+ __IVARS__TtC14CoreBrightnessP33_CA60EA9F041518321383D5DF809F01DE25CBXDXTOcclusionFilterImpl
+ __METACLASS_DATA_CBXDXTOcclusionFilter
+ __METACLASS_DATA__TtC14CoreBrightnessP33_CA60EA9F041518321383D5DF809F01DE25CBXDXTOcclusionFilterImpl
+ __OBJC_$_CLASS_METHODS_CBDisplayTransitionPolicy
+ __OBJC_$_INSTANCE_METHODS_CBAngleFilter
+ __OBJC_$_INSTANCE_METHODS_CBBottomPanelALSSelectionPolicy
+ __OBJC_$_INSTANCE_METHODS_CBBottomPanelAngleDropPolicy
+ __OBJC_$_INSTANCE_METHODS_CBCMAngleEvent
+ __OBJC_$_INSTANCE_METHODS_CBCMAngleService
+ __OBJC_$_INSTANCE_METHODS_CBColorALSSelectionPolicy
+ __OBJC_$_INSTANCE_METHODS_CBColorFloorCoex
+ __OBJC_$_INSTANCE_METHODS_CBDisplayALSSamplingPolicy
+ __OBJC_$_INSTANCE_METHODS_CBDisplayCoex
+ __OBJC_$_INSTANCE_METHODS_CBDisplayTransitionPolicy
+ __OBJC_$_INSTANCE_METHODS_CBTopPanelALSSelectionPolicy
+ __OBJC_$_INSTANCE_VARIABLES_CBAngleFilter
+ __OBJC_$_INSTANCE_VARIABLES_CBBottomPanelALSSelectionPolicy
+ __OBJC_$_INSTANCE_VARIABLES_CBCMAngleEvent
+ __OBJC_$_INSTANCE_VARIABLES_CBCMAngleService
+ __OBJC_$_INSTANCE_VARIABLES_CBColorALSSelectionPolicy
+ __OBJC_$_INSTANCE_VARIABLES_CBColorFloorCoex
+ __OBJC_$_INSTANCE_VARIABLES_CBDisplayALSSamplingPolicy
+ __OBJC_$_INSTANCE_VARIABLES_CBDisplayCoex
+ __OBJC_$_INSTANCE_VARIABLES_CBDisplayTransitionPolicy
+ __OBJC_$_PROP_LIST_CBAngleEventProtocol
+ __OBJC_$_PROP_LIST_CBAngleFilter
+ __OBJC_$_PROP_LIST_CBAngleServiceProtocol
+ __OBJC_$_PROP_LIST_CBBottomPanelALSSelectionPolicy
+ __OBJC_$_PROP_LIST_CBBottomPanelAngleDropPolicy
+ __OBJC_$_PROP_LIST_CBCMAngleEvent
+ __OBJC_$_PROP_LIST_CBCMAngleService
+ __OBJC_$_PROP_LIST_CBColorALSSelectionPolicy
+ __OBJC_$_PROP_LIST_CBColorFloorCoex
+ __OBJC_$_PROP_LIST_CBDisplayALSSamplingPolicy
+ __OBJC_$_PROP_LIST_CBDisplayCoex
+ __OBJC_$_PROP_LIST_CBTopPanelALSSelectionPolicy
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CBAngleEventProtocol
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CBAngleServiceProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CBAngleEventProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CBAngleServiceProtocol
+ __OBJC_$_PROTOCOL_REFS_CBAngleEventProtocol
+ __OBJC_$_PROTOCOL_REFS_CBAngleServiceProtocol
+ __OBJC_CLASS_PROTOCOLS_$_CBAngleFilter
+ __OBJC_CLASS_PROTOCOLS_$_CBBottomPanelALSSelectionPolicy
+ __OBJC_CLASS_PROTOCOLS_$_CBBottomPanelAngleDropPolicy
+ __OBJC_CLASS_PROTOCOLS_$_CBCMAngleEvent
+ __OBJC_CLASS_PROTOCOLS_$_CBCMAngleService
+ __OBJC_CLASS_PROTOCOLS_$_CBColorALSSelectionPolicy
+ __OBJC_CLASS_PROTOCOLS_$_CBColorFloorCoex
+ __OBJC_CLASS_PROTOCOLS_$_CBDisplayCoex
+ __OBJC_CLASS_PROTOCOLS_$_CBTopPanelALSSelectionPolicy
+ __OBJC_CLASS_RO_$_CBAngleFilter
+ __OBJC_CLASS_RO_$_CBBottomPanelALSSelectionPolicy
+ __OBJC_CLASS_RO_$_CBBottomPanelAngleDropPolicy
+ __OBJC_CLASS_RO_$_CBCMAngleEvent
+ __OBJC_CLASS_RO_$_CBCMAngleService
+ __OBJC_CLASS_RO_$_CBColorALSSelectionPolicy
+ __OBJC_CLASS_RO_$_CBColorFloorCoex
+ __OBJC_CLASS_RO_$_CBDisplayALSSamplingPolicy
+ __OBJC_CLASS_RO_$_CBDisplayCoex
+ __OBJC_CLASS_RO_$_CBDisplayTransitionPolicy
+ __OBJC_CLASS_RO_$_CBTopPanelALSSelectionPolicy
+ __OBJC_LABEL_PROTOCOL_$_CBAngleEventProtocol
+ __OBJC_LABEL_PROTOCOL_$_CBAngleServiceProtocol
+ __OBJC_METACLASS_RO_$_CBAngleFilter
+ __OBJC_METACLASS_RO_$_CBBottomPanelALSSelectionPolicy
+ __OBJC_METACLASS_RO_$_CBBottomPanelAngleDropPolicy
+ __OBJC_METACLASS_RO_$_CBCMAngleEvent
+ __OBJC_METACLASS_RO_$_CBCMAngleService
+ __OBJC_METACLASS_RO_$_CBColorALSSelectionPolicy
+ __OBJC_METACLASS_RO_$_CBColorFloorCoex
+ __OBJC_METACLASS_RO_$_CBDisplayALSSamplingPolicy
+ __OBJC_METACLASS_RO_$_CBDisplayCoex
+ __OBJC_METACLASS_RO_$_CBDisplayTransitionPolicy
+ __OBJC_METACLASS_RO_$_CBTopPanelALSSelectionPolicy
+ __OBJC_PROTOCOL_$_CBAngleEventProtocol
+ __OBJC_PROTOCOL_$_CBAngleServiceProtocol
+ __OBJC_PROTOCOL_REFERENCE_$_CBAngleEventProtocol
+ __PROPERTIES_CBXDXTOcclusionFilter
+ __PROTOCOLS_CBXDXTOcclusionFilter
+ __ZL19colorFloor_lux_AH70
+ __ZL19colorFloor_lux_AH90
+ __ZL20colorFloor_lux_AH110
+ __ZL20colorFloor_lux_AH125
+ __ZL20colorFloor_lux_AH180
+ __ZL20colorFloor_nits_AH70
+ __ZL20colorFloor_nits_AH90
+ __ZL21colorFloor_nits_AH110
+ __ZL21colorFloor_nits_AH125
+ __ZL21colorFloor_nits_AH180
+ __ZL24ceMitigationThr_lux_AH70
+ __ZL24ceMitigationThr_lux_AH90
+ __ZL25ceMitigationThr_lux_AH100
+ __ZL25ceMitigationThr_lux_AH110
+ __ZL25ceMitigationThr_lux_AH125
+ __ZL25ceMitigationThr_lux_AH180
+ __ZL25ceMitigationThr_nits_AH70
+ __ZL25ceMitigationThr_nits_AH90
+ __ZL26ceMitigationThr_nits_AH100
+ __ZL26ceMitigationThr_nits_AH110
+ __ZL26ceMitigationThr_nits_AH125
+ __ZL26ceMitigationThr_nits_AH180
+ __ZN14CoreBrightnessL13sbimLimitsV6xE
+ __ZN14CoreBrightnessL14sbimLimitsV68eE
+ __ZN14CoreBrightnessL14sbimLimitsV68iE
+ __ZN4AABC21UpdateTrustedLuxX3442EPK14__CFDictionary
+ __ZN4AABC27BrightnessBoostScalerForLuxEf
+ ___18-[BLControl start]_block_invoke_7
+ ___45-[CBDisplayTransitionPolicy beginGracePeriod]_block_invoke
+ ___53-[CBCMAngleService startAngleUpdatesToQueue:handler:]_block_invoke
+ ___DisplaySetBoostFactorWithFade_block_invoke
+ ___block_descriptor_40_e8_32o_e24_v16?0"CBCMAngleEvent"8ls32l8
+ ___block_descriptor_48_e8_32o40b_e17_v16?0"CMAngle"8ls40l8s32l8
+ _angleBaselineLux
+ _angleBaselineNits
+ _angle_baselineStrengthLUT
+ _associated conformance So21IOHIDServiceClientRefa14CoreFoundation9_CFObjectSCSH
+ _associated conformance So21IOHIDServiceClientRefaSHSCSQ
+ _ceMitigationThr_boundaries
+ _colorFloor_boundaries
+ _flat unique So23CBDigitizerNodeProtocol_p
+ _isColorFloorStable
+ _kCBDisplayTransitionGracePeriodDuration
+ _selectAngleBoundary_LuxNits
+ _selectAngleBoundary_Strength
+ _symbolic _____ 12CoreGraphics7CGFloatV
+ _symbolic _____ 14CoreBrightness25CBXDXTOcclusionFilterImpl33_CA60EA9F041518321383D5DF809F01DELLC
+ _symbolic _____ So6CGRectV
+ _symbolic _____ So6CGSizeV
+ _symbolic _____ So7CGPointV
+ _symbolic ______p So23CBDigitizerNodeProtocolP
+ _symbolic _____ySnySdG_____G s13KeyValuePairsV So6CGRectV
+ _symbolic _____ySnySdG______tG s23_ContiguousArrayStorageC So6CGRectV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So7CGPointV
+ _type_layout_string So6CGRectV
+ _type_layout_string So7CGPointV
- GCC_except_table101
- GCC_except_table109
- GCC_except_table118
- GCC_except_table122
- GCC_except_table133
- GCC_except_table192
- GCC_except_table228
- GCC_except_table242
- GCC_except_table74
- GCC_except_table99
CStrings:
+ "%s.CBDisplayCoex.%lu"
+ "(%.2f, %.2f) - (%.2f, %.2f)"
+ "AABAODState"
+ "AABCurveSync"
+ "AABFastRampActive"
+ "ALS transition suppression: %s"
+ "ActiveSyncedCount"
+ "All fronts unusable -> {Brisbane}"
+ "All sensors occluded -> dropping sample"
+ "Angle"
+ "BadCurves"
+ "Brightness Boost"
+ "Brightness Boost %4.2f * %1.2f -> %4.2f"
+ "Brightness Boost Inverse %f -> %f"
+ "Brisbane"
+ "CBBrightnessBoostFactor"
+ "CBCE5: refusing inference for NaN hingeAngle - returning nil"
+ "CBColorALSSelectionPolicy init returned nil; leaving _colorFilter without a selection policy."
+ "CBDisplayTransitionPolicy"
+ "CEOverride: extended input (xdxt: %@, hingeAngle: %f)"
+ "CEOverride: refusing 35-feature override — missing or invalid XDXT/hingeAngle"
+ "Cairns"
+ "Cairns occluded, Darwin clear -> %@"
+ "Cairns ok -> %@"
+ "Cairns+Darwin occluded, last Cairns fresh -> %@"
+ "CoreBrightness_Internal.CBXDXTOcclusionFilter"
+ "D908"
+ "Darwin"
+ "Display on under transition hold — skipping fast ramp"
+ "Display sync policy: %s"
+ "DisplayTransitionALSSuppression"
+ "DisplayTransitionGracePeriod"
+ "DisplayTransitionSyncMode"
+ "Failed to create color floor coex."
+ "Failed to create display coex."
+ "Failed to init CBColorALSSelectionPolicy, coexTracker is nil."
+ "GoodCurve"
+ "Ignore ALS with placement %d for panel with placement = %d"
+ "IgnoreAngle"
+ "LeaderBrightness"
+ "LeaderDisplayID"
+ "LeaderNits"
+ "MultiActive"
+ "PLT_UP_70"
+ "PLT_Z_70"
+ "Rear ALS sampling policy: angle=%.1f rearActive=%d"
+ "Rear ALS sampling policy: angleHysteresis=%.1f"
+ "Rear ALS sampling policy: angleThreshold=%.1f"
+ "RearALSSamplingPolicyAngleHysteresis"
+ "RearALSSamplingPolicyAngleThreshold"
+ "Received angle %f"
+ "Received ignore angle = %s"
+ "Received property %@ = %f"
+ "Restore brightness boost factor %@"
+ "Setting PLT angle to %f"
+ "SharedCurveState"
+ "Slider"
+ "SuppressedDisplayIDs"
+ "Transitioning"
+ "X3442"
+ "Xdxt"
+ "[%@] Selected %@: %@"
+ "[%@] angle %f < 20 -> dropping sample"
+ "[%@] angle=%f (20-70) -> {Darwin(%f), Cairns(%f), Brisbane(%f)}"
+ "[%@] angle=%f (20-70), Darwin(%f)<50 -> {Cairns(%f), Brisbane(%f)}"
+ "[%@] angle=%f, Brisbane dominates (%.1f > 2*%.1f) -> {Brisbane}"
+ "[%@] angle=%f, Darwin(%f)<50 -> {Cairns(%f), Brisbane(%f)}"
+ "[%@] angle=%f, inner=%.1f -> {Cairns(%f), Darwin(%f)}"
+ "[%u] Digitizer event arrived with %ld children, angle: %f, area: %s"
+ "[CE/Angle] computeBaselineStrengthForLux:andNits:andAngle: lux=%.1f nits=%.1f angle=%.1f -> AH%d luxIdx=[%u..%u] (%.1f..%.1f) nitsIdx=[%u..%u] (%.1f..%.1f) strength=%.2f"
+ "[CE/Angle] computeBaselineStrengthForLux:andNits:andAngle: no strength table for angle=%.1f -> falling back to default strength = %.2f"
+ "[CE/Angle] deviceID=5: using angle-dependent CE boundaries"
+ "[CE/Angle] sampleIsFromCERegion: lux=%.1f, nits=%.1f, angle=%.1f -> AH%d, inCERegion=%d"
+ "[CE/Angle] sampleIsFromCERegion: no boundary for angle=%.1f -> inCERegion=0"
+ "[Coex] Setting angle to %f"
+ "[Color Mitigation] angle=%.1f --> 1D mitigated"
+ "[Common controls] commit to leader displayID=%lu, then syncing"
+ "[Common controls] slider interaction detected, cancelling grace period"
+ "[Config] grace period duration set to %.1fs"
+ "[D908] First front Brisbane ALS -> selected (Lux = %f)"
+ "[Display Mode] first active synced display (all-off -> one-on), no handoff needed"
+ "[Display Mode] shouldn't happen (container (%lu) already active) - logical bug"
+ "[Display Transition] %@ -> %@ (%lu active, leader=%lu)"
+ "[Display Transition] all displays off during grace period, cancelling"
+ "[Handoff] %@ from displayID=%lu to displayID=%lu"
+ "[Handoff] curve sync from displayID=%lu to displayID=%lu"
+ "[Handoff] dropping brightness notification from going-offline displayID=%lu"
+ "[Handoff] grace period cancelled"
+ "[Handoff] grace period expired"
+ "[Handoff] no curve data available from displayID=%lu"
+ "[Handoff] pre-configuring displayID=%lu from source displayID=%lu"
+ "[Handoff] source exiting AOD, not settled"
+ "[Handoff] source in fast ramp, not settled"
+ "[Handoff] source not settled - skip grace period"
+ "[Handoff] starting grace period (%.1fs) for %lu container(s)"
+ "[Handoff] syncing curve from displayID=%lu to displayID=%lu"
+ "[X3442] angle %f < 20 -> dropping sample"
+ "[X3442][Darwin color floor] lux: %f, nits: %f, angle: %f, stable: %d"
+ "[X3442][Darwin stability] lux: %f, nits: %f, angle: %f, stability %u -> %u"
+ "angle-dependent"
+ "applying external curve sync"
+ "applying handed-over trusted lux %0.4f"
+ "boost-enabled"
+ "boost-pivot-ratio"
+ "coex"
+ "com.apple.CoreBrightness.CBColorFloorCoex"
+ "com.apple.CoreBrightness.CBXDXTOcclusionFilter"
+ "com.apple.CoreBrightness.DisplayTransitionPolicy"
+ "feature count mismatch (j=%d, expected=%d) - returning nil"
+ "hingeAngle"
+ "kAABStateTransitionHold"
+ "lux-sync"
+ "orientation = %d, placement = %d, color mitigation = %d, ce-model = %d, ce-threshold = %f, angle dependent = %d"
+ "tracking synced container displayID=%lu mode=%ld"
+ "trusted ALS stopped by sampling policy (placement:%d orientation:%d) -> clearing trusted ALS"
+ "unexpected ALS event = %@"
+ "untracking synced container displayID=%lu"
+ "v16@?0@\"CBCMAngleEvent\"8"
+ "v16@?0@\"CMAngle\"8"
+ "xdxt%d"
- "orientation = %d, placement = %d, color mitigation = %d, ce-model = %d, ce-threshold = %f"
```
