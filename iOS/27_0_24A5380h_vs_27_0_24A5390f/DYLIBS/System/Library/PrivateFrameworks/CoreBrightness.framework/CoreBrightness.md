## CoreBrightness

> `/System/Library/PrivateFrameworks/CoreBrightness.framework/CoreBrightness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x2eb78` | `0x34fb8` | **`+0x6440`** |
| `__TEXT.__text` | `0x16a888` | `0x16c570` | **`+0x1ce8`** |
| `__AUTH_CONST.__objc_const` | `0x334e0` | `0x33890` | **`+0x3b0`** |
| `__TEXT.__oslogstring` | `0x1963d` | `0x1990d` | **`+0x2d0`** |
| `__AUTH_CONST.__cfstring` | `0xe380` | `0xe5c0` | **`+0x240`** |
| `__TEXT.__cstring` | `0xcb1a` | `0xcd15` | **`+0x1fb`** |
| `__TEXT.__objc_methlist` | `0xd08c` | `0xd1f4` | **`+0x168`** |
| `__DATA_CONST.__objc_selrefs` | `0x5898` | `0x5958` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x2ec0` | `0x2f60` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x2768` | `0x2804` | **`+0x9c`** |
| `__TEXT.__unwind_info` | `0x5580` | `0x55d8` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x2630` | `0x2680` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0x16e0` | `0x1718` | **`+0x38`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x3d8` | `0x408` | **`+0x30`** |
| `__AUTH_CONST.__objc_intobj` | `0xd80` | `0xdb0` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x7c0` | `0x7b0` | **`-0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0xcb8` | `0xcc8` | **`+0x10`** |
| `__TEXT.__const` | `0x169f8` | `0x16a08` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0xa44` | `0xa4e` | **`+0xa`** |
| `__DATA_CONST.__objc_catlist` | `0x10` | `0x18` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x6f0` | `0x6f8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x5b8` | `0x5c0` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xc2c` | `0xc34` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xeb0` | `0xeaf` | **`-0x1`** |

### Other Changes

```diff

-2300.0.10.0.1
+2300.0.18.502.1

-  Functions: 8675
-  Symbols:   10075
-  CStrings:  4670
+  Functions: 8711
+  Symbols:   10139
+  CStrings:  4696
Symbols:
+ +[NSError(BacklightdExportedObj) exportedObjError:]
+ -[BacklightdExportedObj wasDisconnected]
+ -[CBALSMitigationState alsNode]
+ -[CBALSMitigationState ceConfidenceThreshold]
+ -[CBALSMitigationState ceModelID]
+ -[CBALSMitigationState ceModule]
+ -[CBALSMitigationState dealloc]
+ -[CBALSMitigationState policyFilter]
+ -[CBALSMitigationState setAlsNode:]
+ -[CBALSMitigationState setCeConfidenceThreshold:]
+ -[CBALSMitigationState setCeModelID:]
+ -[CBALSMitigationState setCeModule:]
+ -[CBALSMitigationState setPolicyFilter:]
+ -[CBALSMitigationState setStats:]
+ -[CBALSMitigationState stats]
+ -[CBAODState fixedLuxBrightenThresholds]
+ -[CBAODState fixedLuxDimThresholds]
+ -[CBAODState initWithDisplayID:]
+ -[CBAODState isHighLuminanceAODActive]
+ -[CBAODThresholdModule applyFixedLuxThresholdsForLux:dimTarget:brightenTarget:]
+ -[CBAODThresholdModule initWithQueue:displayID:andAODState:]
+ -[CBBrightnessTransaction _completeWithError:]
+ -[CBBrightnessTransaction _setBrightness:withError:]
+ -[CBBrightnessTransaction complete]
+ -[CBBrightnessTransaction initWithClient:andHandle:commitType:timeout:]
+ -[CBColorModuleShared enableMitigationsForALSNode:]
+ -[CBColorModuleShared replaceEvent:withFilteredEvent:]
+ -[CBColorPolicyFilter initWithID:serviceID:]
+ -[CBDisplayBrightnessClient newBrightnessAdjustmentWithError:]
+ -[CBDisplayBrightnessClient setProperties:]
+ -[CBIndicatorBrightnessModule forceSILOff]
+ GCC_except_table101
+ GCC_except_table122
+ _A_SDRGF
+ _D_SDRGF
+ _L_SDRGF
+ _OBJC_CLASS_$_CBALSMitigationState
+ _OBJC_IVAR_$_BacklightdExportedObj._transactions
+ _OBJC_IVAR_$_CBALSMitigationState._alsNode
+ _OBJC_IVAR_$_CBALSMitigationState._ceConfidenceThreshold
+ _OBJC_IVAR_$_CBALSMitigationState._ceModelID
+ _OBJC_IVAR_$_CBALSMitigationState._ceModule
+ _OBJC_IVAR_$_CBALSMitigationState._policyFilter
+ _OBJC_IVAR_$_CBALSMitigationState._stats
+ _OBJC_IVAR_$_CBAODState._fixedLuxBrightenThresholds
+ _OBJC_IVAR_$_CBAODState._fixedLuxDimThresholds
+ _OBJC_IVAR_$_CBAODThresholdModule._lastPushedBrightenLuxThreshold
+ _OBJC_IVAR_$_CBAODThresholdModule._lastPushedDimLuxThreshold
+ _OBJC_IVAR_$_CBBrightnessTransaction._logHandle
+ _OBJC_IVAR_$_CBBrightnessTransaction._timeout
+ _OBJC_IVAR_$_CBBrightnessTransaction._timer
+ _OBJC_IVAR_$_CBColorModuleShared._alsMitigationState
+ _OBJC_IVAR_$_CBColorModuleShared._anyMitigationEnabled
+ _OBJC_IVAR_$_CBColorModuleShared._overrideFilters
+ _OBJC_IVAR_$_CBColorPolicyFilter._serviceID
+ _OBJC_IVAR_$_CBDisplayBrightnessClient._properties
+ _OBJC_METACLASS_$_CBALSMitigationState
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSError_$_BacklightdExportedObj
+ __OBJC_$_CATEGORY_NSError_$_BacklightdExportedObj
+ __OBJC_$_INSTANCE_METHODS_CBALSMitigationState
+ __OBJC_$_INSTANCE_VARIABLES_CBALSMitigationState
+ __OBJC_$_PROP_LIST_CBALSMitigationState
+ __OBJC_$_PROP_LIST_CBBrightnessAdjustment
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CBBrightnessAdjustment
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CBBrightnessAdjustment
+ __OBJC_$_PROTOCOL_REFS_CBBrightnessAdjustment
+ __OBJC_CLASS_PROTOCOLS_$_CBBrightnessTransaction
+ __OBJC_CLASS_RO_$_CBALSMitigationState
+ __OBJC_LABEL_PROTOCOL_$_CBBrightnessAdjustment
+ __OBJC_METACLASS_RO_$_CBALSMitigationState
+ __OBJC_PROTOCOL_$_CBBrightnessAdjustment
+ ___51-[CBColorModuleShared enableMitigationsForALSNode:]_block_invoke
+ ___52-[CBBrightnessTransaction _setBrightness:withError:]_block_invoke
+ ___59-[BrightnessSystemClientInternal copyPropertyForKey:error:]_block_invoke_2
+ ___66-[BrightnessSystemClientInternal copyPropertyForKey:handle:error:]_block_invoke_2
+ ___block_descriptor_64_e8_32o40o48r_e5_v8?0ls32l8s40l8r48l8
+ ___block_descriptor_72_e8_32o40o48o56r_e5_v8?0ls32l8s40l8s48l8r56l8
+ _kCBSPITransaction
+ _kCBSPITransactionCommit
+ _kCBSPITransactionHandle
+ _kCBSPITransactionKey
+ _kCBSPITransactionOnCommit
+ _kCBSPITransactionProperty
+ _kCBSPITransactionUUID
- -[CBABModuleiOS shouldMitigateHarmony:]
- -[CBAODThresholdModule initWithQueue:andAODState:]
- -[CBBrightnessTransaction initWithClient:andHandle:commitType:]
- -[CBColorModuleShared enableMitigations:]
- -[CBDisplayContaineriOS setColorMitigations]
- -[CBIndicatorBrightnessModule shortcutRamp]
- GCC_except_table108
- GCC_except_table85
- GCC_except_table87
- _OBJC_IVAR_$_CBColorModuleShared._ceConfidenceThreshold
- _OBJC_IVAR_$_CBColorModuleShared._ceModelID
- _OBJC_IVAR_$_CBColorModuleShared._ceModule
- _OBJC_IVAR_$_CBColorModuleShared._confidenceEstimatorStats
- _OBJC_IVAR_$_CBColorModuleShared._enableMitigations
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_ColorMitigationSupportProtocol
- __OBJC_$_PROTOCOL_METHOD_TYPES_ColorMitigationSupportProtocol
- __OBJC_$_PROTOCOL_REFS_ColorMitigationSupportProtocol
- __OBJC_LABEL_PROTOCOL_$_ColorMitigationSupportProtocol
- __OBJC_PROTOCOL_$_ColorMitigationSupportProtocol
- ___41-[CBColorModuleShared enableMitigations:]_block_invoke
CStrings:
+ "-[CBAODThresholdModule initWithQueue:displayID:andAODState:]"
+ "ALS event with orientation %d discarded by color filter."
+ "ALS event with orientation %d discarded by override filter."
+ "AODFixedLuxBrightenThresholds"
+ "AODFixedLuxDimThresholds"
+ "Brightness value outside of the valid range."
+ "Committing non-existing transaction."
+ "Error committing transaction %@"
+ "Fixed lux: brighten tightened %f -> %f"
+ "Fixed lux: dim tightened %f -> %f"
+ "IOReportCopyChannelsInGroup for group=%@ subgroup=%@ failed with error=%@"
+ "Invalid data type for Transaction. Commit is not an NSNumber."
+ "Invalid data type for Transaction. Expected dictionary."
+ "Invalid data type for Transaction. Missing uuid"
+ "Per-ALS CE: serviceID=%@ model=%u threshold=%f"
+ "Thermal Brightness"
+ "Transaction"
+ "Transaction already committed"
+ "Transaction committed successfully"
+ "Transaction is missing one of property/key/onCommit"
+ "Transaction was initiated with a different handle"
+ "[Color Mitigation] ALS event with orientation %d discarded by color mitigation filter."
+ "[Color Mitigation] ALS orientation=%d placement=%d triggered=%d filteredStrength=%f"
+ "[Color Mitigation] Aggregated mitigation: count=%lu anyTriggered=%d minFilteredStrength=%f"
+ "[Color Mitigation] CE stats collect: serviceID=%@ strengthCE=%f confidenceCE=%f"
+ "[New Event] MIB dcpRoleID mismatch! Expected: %d, Received: %d"
+ "com.apple.CoreBrightness.AOD.CBAODState.%lu"
+ "com.apple.CoreBrightness.AOD.ThresholdModule.%lu"
+ "com.apple.CoreBrightness.CBBrightnessTransaction"
+ "handle"
+ "key"
+ "onCommit"
+ "property"
+ "uuid"
- "-[CBAODThresholdModule initWithQueue:andAODState:]"
- "ALS event discarded."
- "Boosted %f * %f to %f at %flux"
- "CE Confidence threshold:%f"
- "CE Model being used:%d"
- "Thermal Brighntess"
- "com.apple.CoreBrightness.AOD.CBAODState"
- "com.apple.CoreBrightness.AOD.ThresholdModule"
```
