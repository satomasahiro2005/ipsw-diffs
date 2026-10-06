## HealthMenstrualCyclesDaemon

> `/System/Library/PrivateFrameworks/HealthMenstrualCyclesDaemon.framework/HealthMenstrualCyclesDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8d880` | `0x8dd24` | **`+0x4a4`** |
| `__DATA.__bss` | `0x1160` | `0x10e0` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x1180` | `0x1200` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0xcaa` | `0xd14` | **`+0x6a`** |
| `__TEXT.__objc_methlist` | `0x36cc` | `0x372c` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x68d0` | `0x6928` | **`+0x58`** |
| `__DATA_DIRTY.__data` | `0xc48` | `0xc90` | **`+0x48`** |
| `__AUTH_CONST.__objc_intobj` | `0x288` | `0x258` | **`-0x30`** |
| `__AUTH_CONST.__cfstring` | `0x2400` | `0x2420` | **`+0x20`** |
| `__DATA.__data` | `0x1758` | `0x1738` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2df8` | `0x2e18` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x17f8` | `0x17d8` | **`-0x20`** |
| `__TEXT.__cstring` | `0x38f1` | `0x3901` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xde0` | `0xdec` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xd30` | `0xd38` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x238` | `0x240` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x4b4` | `0x4b8` | **`+0x4`** |

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

+  - /System/Library/PrivateFrameworks/HealthUtilities.framework/HealthUtilities

-  Functions: 2352
-  Symbols:   2948
+  Functions: 2347
+  Symbols:   2958
Symbols:
+ -[HDMCAnalysisManager registerObserver:queue:userInitiated:needsCycles:]
+ -[HDMCDailyMetric hasBleedingPostMenopauseSamples]
+ -[HDMCDailyMetric logBleedingPostMenopauseEnabled]
+ -[HDMCDailyMetric setBleedingPostMenopauseSamples:]
+ -[HDMCDailyMetric setLogBleedingPostMenopauseEnabled:]
+ -[HDMCPluginServer remote_confirmAndSaveDeviationWithMenstrualFlowByDayIndex:intermenstrualBleedingByDayIndex:addedCycleFactors:deletedCycleFactors:initialAnalysisWindow:overridePerimenopauseContextState:overrideUserDeclinedMenopauseStage:completion:]
+ -[HDMCProfileExtension getMenopauseModelProvider]
+ GCC_except_table72
+ GCC_except_table82
+ _HKMCDisplayTypeIdentifierBleedingAfterMenopauseFlow
+ _HKMCPrivateMetadataKeyConfirmedDeviationUserDeclinedMenopauseStageAtConfirmation
+ _OBJC_IVAR_$_HDMCAnalysisManager._cyclesNeedingObservers
+ _OBJC_IVAR_$_HDMCDailyMetric._bleedingPostMenopauseSamples
+ _OBJC_IVAR_$_HDMCDailyMetric._logBleedingPostMenopauseEnabled
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HKMCMenopauseModelProvidingInterface
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HKMCMenopauseModelProvidingInterface
+ __OBJC_$_PROTOCOL_REFS_HKMCMenopauseModelProvidingInterface
+ __OBJC_LABEL_PROTOCOL_$_HKMCMenopauseModelProvidingInterface
+ __OBJC_PROTOCOL_$_HKMCMenopauseModelProvidingInterface
+ ___251-[HDMCPluginServer remote_confirmAndSaveDeviationWithMenstrualFlowByDayIndex:intermenstrualBleedingByDayIndex:addedCycleFactors:deletedCycleFactors:initialAnalysisWindow:overridePerimenopauseContextState:overrideUserDeclinedMenopauseStage:completion:]_block_invoke
+ ___251-[HDMCPluginServer remote_confirmAndSaveDeviationWithMenstrualFlowByDayIndex:intermenstrualBleedingByDayIndex:addedCycleFactors:deletedCycleFactors:initialAnalysisWindow:overridePerimenopauseContextState:overrideUserDeclinedMenopauseStage:completion:]_block_invoke_2
+ ___72-[HDMCAnalysisManager registerObserver:queue:userInitiated:needsCycles:]_block_invoke
+ ___block_descriptor_112_e8_32s40s48s56s64s72s80s88bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8
+ ___block_descriptor_166_e8_32s40s48s56s64s72s80r88r96r104r112r120r128r_e28_v24?0"HKMCDaySummary"8^B16lr80l8s32l8r88l8s40l8s48l8r96l8r104l8r112l8r120l8s56l8s64l8r128l8s72l8
+ ___block_descriptor_49_e8_32s_e34_16?0"HKMCUnconfirmedDeviation"8ls32l8
+ ___swift_closure_destructor.14Tm
+ _symbolic _____ySaySo15HKDeletedObjectCGSgG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____ySo39HDCodableMenstrualCyclesExperienceModelCG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 27HealthMenstrualCyclesDaemon20HDMCAnalysisExecutorC7PlannerC5State33_57580856FC49E16A24C9DF95B8FF534CLLV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 27HealthMenstrualCyclesDaemon20HDMCPregnancyManagerC5State33_865A72A9437EC0D5F8ABCC85373490A0LLV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 27HealthMenstrualCyclesDaemon25HDMCMenopauseStateManagerC0H0031_495C53339DF1A80222D5AF25A29592M0LLV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 27HealthMenstrualCyclesDaemon32HDMCAnalysisOrchestrationManagerC5State33_91BAC5C98FA3A8C6CB34E60FFD2D1508LLV
- -[HDMCDailyMetric hasBleedingAfterMenopauseSamples]
- -[HDMCDailyMetric logBleedingAfterMenopauseEnabled]
- -[HDMCDailyMetric setBleedingAfterMenopauseSamples:]
- -[HDMCDailyMetric setLogBleedingAfterMenopauseEnabled:]
- GCC_except_table71
- GCC_except_table81
- _OBJC_IVAR_$_HDMCDailyMetric._bleedingAfterMenopauseSamples
- _OBJC_IVAR_$_HDMCDailyMetric._logBleedingAfterMenopauseEnabled
- ___216-[HDMCPluginServer remote_confirmAndSaveDeviationWithMenstrualFlowByDayIndex:intermenstrualBleedingByDayIndex:addedCycleFactors:deletedCycleFactors:initialAnalysisWindow:overridePerimenopauseContextState:completion:]_block_invoke
- ___216-[HDMCPluginServer remote_confirmAndSaveDeviationWithMenstrualFlowByDayIndex:intermenstrualBleedingByDayIndex:addedCycleFactors:deletedCycleFactors:initialAnalysisWindow:overridePerimenopauseContextState:completion:]_block_invoke_2
- ___60-[HDMCAnalysisManager registerObserver:queue:userInitiated:]_block_invoke
- ___block_descriptor_104_e8_32s40s48s56s64s72s80bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8
- ___block_descriptor_163_e8_32s40s48s56s64s72s80r88r96r104r112r120r128r_e28_v24?0"HKMCDaySummary"8^B16ls32l8r80l8s40l8r88l8s48l8s56l8r96l8r104l8r112l8r120l8s64l8r128l8s72l8
- ___block_descriptor_48_e8_32s_e34_16?0"HKMCUnconfirmedDeviation"8ls32l8
- ___swift_closure_destructor.16Tm
- _get_type_metadata 15Synchronization5MutexVy27HealthMenstrualCyclesDaemon20HDMCAnalysisExecutorC7PlannerC5State33_57580856FC49E16A24C9DF95B8FF534CLLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy27HealthMenstrualCyclesDaemon20HDMCPregnancyManagerC5State33_865A72A9437EC0D5F8ABCC85373490A0LLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy27HealthMenstrualCyclesDaemon25HDMCMenopauseStateManagerC0H0031_495C53339DF1A80222D5AF25A29592M0LLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy27HealthMenstrualCyclesDaemon32HDMCAnalysisOrchestrationManagerC5State33_91BAC5C98FA3A8C6CB34E60FFD2D1508LLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVySaySo15HKDeletedObjectCGSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVySo39HDCodableMenstrualCyclesExperienceModelCG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "HKMCAnalysisManagerCyclesNeedingObservers"
+ "hasBleedingPostMenopauseSamples"
+ "settings_logBleedingPostMenopauseEnabled"
- "com.apple.Health"
- "hasBleedingAfterMenopauseSamples"
- "logBleedingAfterMenopauseEnabled"
```
