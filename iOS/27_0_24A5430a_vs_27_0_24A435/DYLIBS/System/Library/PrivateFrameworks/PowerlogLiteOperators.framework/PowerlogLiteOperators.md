## PowerlogLiteOperators

> `/System/Library/PrivateFrameworks/PowerlogLiteOperators.framework/PowerlogLiteOperators`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4dcf2c` | `0x4f65e8` | **`+0x196bc`** |
| `__AUTH_CONST.__cfstring` | `0x75ba0` | `0x781a0` | **`+0x2600`** |
| `__TEXT.__cstring` | `0x5efd9` | `0x60733` | **`+0x175a`** |
| `__AUTH_CONST.__objc_const` | `0x373c8` | `0x38a50` | **`+0x1688`** |
| `__TEXT.__objc_methlist` | `0x2e594` | `0x2f71c` | **`+0x1188`** |
| `__TEXT.__oslogstring` | `0x15a25` | `0x167b9` | **`+0xd94`** |
| `__DATA_CONST.__objc_arraydata` | `0x16680` | `0x16d00` | **`+0x680`** |
| `__DATA_CONST.__objc_selrefs` | `0x14818` | `0x14da8` | **`+0x590`** |
| `__DATA_CONST.__const` | `0x9478` | `0x9730` | **`+0x2b8`** |
| `__AUTH.__objc_data` | `0x29e0` | `0x2c10` | **`+0x230`** |
| `__TEXT.__unwind_info` | `0x8248` | `0x8478` | **`+0x230`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x2fa0` | `0x30d8` | **`+0x138`** |
| `__DATA.__objc_ivar` | `0x1ed0` | `0x1f94` | **`+0xc4`** |
| `__DATA_DIRTY.__objc_data` | `0x3e68` | `0x3f08` | **`+0xa0`** |
| `__DATA_DIRTY.__bss` | `0x46e8` | `0x4778` | **`+0x90`** |
| `__DATA_DIRTY.__objc_ivar` | `0x1310` | `0x1388` | **`+0x78`** |
| `__DATA_CONST.__got` | `0x1b30` | `0x1b78` | **`+0x48`** |
| `__DATA_CONST.__objc_classlist` | `0xa28` | `0xa70` | **`+0x48`** |
| `__DATA_CONST.__objc_superrefs` | `0xb00` | `0xb48` | **`+0x48`** |
| `__AUTH_CONST.__objc_dictobj` | `0x50a0` | `0x50c8` | **`+0x28`** |
| `__AUTH_CONST.__objc_intobj` | `0x6e58` | `0x6e70` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1948` | `0x1958` | **`+0x10`** |
| `__TEXT.__const` | `0x2cc0` | `0x2cb0` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2d5c` | `0x2d68` | **`+0xc`** |

### Other Changes

```diff

-  Functions: 19473
-  Symbols:   25344
-  CStrings:  19489
+  Functions: 19875
+  Symbols:   25867
+  CStrings:  19863
Symbols:
+ +[AWDMETRICSKCellularPowerLogDcsPerfStates binType]
+ +[AWDMETRICSKCellularPowerLogNRAntennaElement antennaElementsType]
+ +[AWDMETRICSKCellularPowerLogNRmmWaveBeamID binType]
+ +[AWDMETRICSMetricLogPower kCellularPowerLogDcsPerfStatesType]
+ +[AWDMETRICSMetricLogPower kCellularPowerLogNRAntennaElementType]
+ +[AWDMETRICSMetricLogPower kCellularPowerLogNRDCEventType]
+ +[AWDMETRICSMetricLogPower kCellularPowerLogNRmmWaveBeamIDType]
+ +[PLBatteryAgent entryEventBackwardDefinitionShelfLifeModeAutoEntry]
+ +[PLBatteryAgent entryEventBackwardDefinitionShelfLifeModeExitCounters]
+ +[PLDisplayAgent entryEventBackwardDefinitionAPLStatsX]
+ +[PLDisplayAgent entryEventForwardDefinitionDisplayX]
+ +[PLDisplayAgent entryEventPointDefinitionDisplayX]
+ +[PLDisplayAgent secondaryCADisplay]
+ +[PLEventBackwardBatteryEntry entryKeyPack0]
+ +[PLEventBackwardBatteryEntry entryKeyPack1]
+ +[PLScreenStateAgent entryEventBackwardDefinitionBacklightStateChangeX]
+ +[PLScreenStateAgent entryEventForwardScreenStateX]
+ -[AWDMETRICSKCellularPlatformApBbSleepStatsPlatformState StringAsMode:]
+ -[AWDMETRICSKCellularPlatformApBbSleepStatsPlatformState hasMode]
+ -[AWDMETRICSKCellularPlatformApBbSleepStatsPlatformState modeAsString:]
+ -[AWDMETRICSKCellularPlatformApBbSleepStatsPlatformState mode]
+ -[AWDMETRICSKCellularPlatformApBbSleepStatsPlatformState setHasMode:]
+ -[AWDMETRICSKCellularPlatformApBbSleepStatsPlatformState setMode:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates .cxx_destruct]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates StringAsLastSdmState:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates addBin:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates binAtIndex:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates binsCount]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates bins]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates clearBins]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates copyTo:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates copyWithZone:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates description]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates dictionaryRepresentation]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates durationMs]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates hasDurationMs]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates hasLastSdmState]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates hasTimestamp]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates hash]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates isEqual:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates lastSdmStateAsString:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates lastSdmState]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates mergeFrom:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates readFrom:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates setBins:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates setDurationMs:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates setHasDurationMs:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates setHasLastSdmState:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates setHasTimestamp:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates setLastSdmState:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates setTimestamp:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates timestamp]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStates writeTo:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin StringAsBinId:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin binIdAsString:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin binId]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin copyTo:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin copyWithZone:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin count]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin description]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin dictionaryRepresentation]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin duration]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin hasBinId]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin hasCount]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin hasDuration]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin hash]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin isEqual:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin mergeFrom:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin readFrom:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin setBinId:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin setCount:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin setDuration:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin setHasBinId:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin setHasCount:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin setHasDuration:]
+ -[AWDMETRICSKCellularPowerLogDcsPerfStatesMBin writeTo:]
+ -[AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin StringAsCellGroup:]
+ -[AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin StringAsDeployment:]
+ -[AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin appliedDrxdMs]
+ -[AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin cellGroupAsString:]
+ -[AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin cellGroup]
+ -[AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin deploymentAsString:]
+ -[AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin deployment]
+ -[AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin hasAppliedDrxdMs]
+ -[AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin hasCellGroup]
+ -[AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin hasDeployment]
+ -[AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin setAppliedDrxdMs:]
+ -[AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin setCellGroup:]
+ -[AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin setDeployment:]
+ -[AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin setHasAppliedDrxdMs:]
+ -[AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin setHasCellGroup:]
+ -[AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin setHasDeployment:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement .cxx_destruct]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement addAntennaElements:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement antennaElementsAtIndex:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement antennaElementsCount]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement antennaElements]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement clearAntennaElements]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement copyTo:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement copyWithZone:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement description]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement dictionaryRepresentation]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement hasSubsId]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement hasTimestamp]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement hasTotalDurationMs]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement hash]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement isEqual:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement mergeFrom:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement readFrom:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement setAntennaElements:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement setHasSubsId:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement setHasTimestamp:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement setHasTotalDurationMs:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement setSubsId:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement setTimestamp:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement setTotalDurationMs:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement subsId]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement timestamp]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement totalDurationMs]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElement writeTo:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement StringAsDirection:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement StringAsElements:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement binDurationMs]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement copyTo:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement copyWithZone:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement description]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement dictionaryRepresentation]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement directionAsString:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement direction]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement elementsAsString:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement elements]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement hasBinDurationMs]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement hasDirection]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement hasElements]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement hash]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement isEqual:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement mergeFrom:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement readFrom:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement setBinDurationMs:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement setDirection:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement setElements:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement setHasBinDurationMs:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement setHasDirection:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement setHasElements:]
+ -[AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement writeTo:]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent StringAsEvent:]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent copyTo:]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent copyWithZone:]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent description]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent dictionaryRepresentation]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent eventAsString:]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent event]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent hasEvent]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent hasSubsId]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent hasTimestamp]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent hash]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent isEqual:]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent mergeFrom:]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent readFrom:]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent setEvent:]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent setHasEvent:]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent setHasSubsId:]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent setHasTimestamp:]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent setSubsId:]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent setTimestamp:]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent subsId]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent timestamp]
+ -[AWDMETRICSKCellularPowerLogNRDCEvent writeTo:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID .cxx_destruct]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID addBin:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID binAtIndex:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID binsCount]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID bins]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID clearBins]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID copyTo:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID copyWithZone:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID description]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID dictionaryRepresentation]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID durationMs]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID hasDurationMs]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID hasSubsId]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID hasTimestamp]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID hash]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID isEqual:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID mergeFrom:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID readFrom:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID setBins:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID setDurationMs:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID setHasDurationMs:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID setHasSubsId:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID setHasTimestamp:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID setSubsId:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID setTimestamp:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID subsId]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID timestamp]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamID writeTo:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin StringAsBinId:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin binIdAsString:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin binId]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin copyTo:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin copyWithZone:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin description]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin dictionaryRepresentation]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin duration]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin hasBinId]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin hasDuration]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin hash]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin isEqual:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin mergeFrom:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin readFrom:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin setBinId:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin setDuration:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin setHasBinId:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin setHasDuration:]
+ -[AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin writeTo:]
+ -[AWDMETRICSKCellularPowerLogNrCaConfigActivateStatsMBin areScellsScheduled]
+ -[AWDMETRICSKCellularPowerLogNrCaConfigActivateStatsMBin hasAreScellsScheduled]
+ -[AWDMETRICSKCellularPowerLogNrCaConfigActivateStatsMBin hasIsSpcellScheduled]
+ -[AWDMETRICSKCellularPowerLogNrCaConfigActivateStatsMBin hasScheduledScellCount]
+ -[AWDMETRICSKCellularPowerLogNrCaConfigActivateStatsMBin isSpcellScheduled]
+ -[AWDMETRICSKCellularPowerLogNrCaConfigActivateStatsMBin scheduledScellCount]
+ -[AWDMETRICSKCellularPowerLogNrCaConfigActivateStatsMBin setAreScellsScheduled:]
+ -[AWDMETRICSKCellularPowerLogNrCaConfigActivateStatsMBin setHasAreScellsScheduled:]
+ -[AWDMETRICSKCellularPowerLogNrCaConfigActivateStatsMBin setHasIsSpcellScheduled:]
+ -[AWDMETRICSKCellularPowerLogNrCaConfigActivateStatsMBin setHasScheduledScellCount:]
+ -[AWDMETRICSKCellularPowerLogNrCaConfigActivateStatsMBin setIsSpcellScheduled:]
+ -[AWDMETRICSKCellularPowerLogNrCaConfigActivateStatsMBin setScheduledScellCount:]
+ -[AWDMETRICSKCellularRfTunerHistTunerStateDuration StringAsDeviceMode:]
+ -[AWDMETRICSKCellularRfTunerHistTunerStateDuration deviceModeAsString:]
+ -[AWDMETRICSKCellularRfTunerHistTunerStateDuration deviceMode]
+ -[AWDMETRICSKCellularRfTunerHistTunerStateDuration hasDeviceMode]
+ -[AWDMETRICSKCellularRfTunerHistTunerStateDuration setDeviceMode:]
+ -[AWDMETRICSKCellularRfTunerHistTunerStateDuration setHasDeviceMode:]
+ -[AWDMETRICSMetricLogPower addKCellularPowerLogDcsPerfStates:]
+ -[AWDMETRICSMetricLogPower addKCellularPowerLogNRAntennaElement:]
+ -[AWDMETRICSMetricLogPower addKCellularPowerLogNRDCEvent:]
+ -[AWDMETRICSMetricLogPower addKCellularPowerLogNRmmWaveBeamID:]
+ -[AWDMETRICSMetricLogPower clearKCellularPowerLogDcsPerfStates]
+ -[AWDMETRICSMetricLogPower clearKCellularPowerLogNRAntennaElements]
+ -[AWDMETRICSMetricLogPower clearKCellularPowerLogNRDCEvents]
+ -[AWDMETRICSMetricLogPower clearKCellularPowerLogNRmmWaveBeamIDs]
+ -[AWDMETRICSMetricLogPower kCellularPowerLogDcsPerfStatesAtIndex:]
+ -[AWDMETRICSMetricLogPower kCellularPowerLogDcsPerfStatesCount]
+ -[AWDMETRICSMetricLogPower kCellularPowerLogDcsPerfStates]
+ -[AWDMETRICSMetricLogPower kCellularPowerLogNRAntennaElementAtIndex:]
+ -[AWDMETRICSMetricLogPower kCellularPowerLogNRAntennaElementsCount]
+ -[AWDMETRICSMetricLogPower kCellularPowerLogNRAntennaElements]
+ -[AWDMETRICSMetricLogPower kCellularPowerLogNRDCEventAtIndex:]
+ -[AWDMETRICSMetricLogPower kCellularPowerLogNRDCEventsCount]
+ -[AWDMETRICSMetricLogPower kCellularPowerLogNRDCEvents]
+ -[AWDMETRICSMetricLogPower kCellularPowerLogNRmmWaveBeamIDAtIndex:]
+ -[AWDMETRICSMetricLogPower kCellularPowerLogNRmmWaveBeamIDsCount]
+ -[AWDMETRICSMetricLogPower kCellularPowerLogNRmmWaveBeamIDs]
+ -[AWDMETRICSMetricLogPower setKCellularPowerLogDcsPerfStates:]
+ -[AWDMETRICSMetricLogPower setKCellularPowerLogNRAntennaElements:]
+ -[AWDMETRICSMetricLogPower setKCellularPowerLogNRDCEvents:]
+ -[AWDMETRICSMetricLogPower setKCellularPowerLogNRmmWaveBeamIDs:]
+ -[PLAppTimeService displayCallbackX]
+ -[PLAppTimeService screenstateCallbackX]
+ -[PLAppTimeService setDisplayCallbackX:]
+ -[PLAppTimeService setScreenstateCallbackX:]
+ -[PLBatteryAgent batteryPackConfigDataLogged]
+ -[PLBatteryAgent logEventBackwardRebalanceWithRawData:hwBypassByChargerID:]
+ -[PLBatteryAgent logShelfLifeModeFromBatteryData:autoEntryTableName:exitCountersTableName:]
+ -[PLBatteryAgent logShelfLifeModeWithRawData:]
+ -[PLBatteryAgent logTrustedBatteryHealthForPack:toTableName:]
+ -[PLBatteryAgent serialNumber2]
+ -[PLBatteryAgent setBatteryPackConfigDataLogged:]
+ -[PLBatteryAgent setSerialNumber2:]
+ -[PLBatteryAgent setShelfLifeModeLogged:]
+ -[PLBatteryAgent shelfLifeModeLogged]
+ -[PLDisplayAgent ApplicationNotificationX]
+ -[PLDisplayAgent HDRHeadroomX]
+ -[PLDisplayAgent afkEndpointsX]
+ -[PLDisplayAgent afkRoleForService:properties:]
+ -[PLDisplayAgent afkRoleIsDCPSEC:]
+ -[PLDisplayAgent backlightFilterTimerX]
+ -[PLDisplayAgent cbDisplayClientX]
+ -[PLDisplayAgent cleanUpAFKInterfacesX]
+ -[PLDisplayAgent copyCoreBrightnessPropertyForKeyX:]
+ -[PLDisplayAgent displayIdentifierX]
+ -[PLDisplayAgent displayIdentifier]
+ -[PLDisplayAgent displayLuxX]
+ -[PLDisplayAgent displaymNitsX]
+ -[PLDisplayAgent fillInBuiltinDisplayBrightnessParametersX:]
+ -[PLDisplayAgent handleAFKInterfaceIOServiceCallbackX:]
+ -[PLDisplayAgent handleAFKInterfaceMsgX:]
+ -[PLDisplayAgent handleBrightnessClientNotificationX:withValue:]
+ -[PLDisplayAgent iokitBacklightDCPSEC]
+ -[PLDisplayAgent isDisplayOnNowX]
+ -[PLDisplayAgent isSecondaryDisplayIdentifier:]
+ -[PLDisplayAgent lastBuiltinDisplayBrightnessX]
+ -[PLDisplayAgent lastBuiltinDisplayLuxX]
+ -[PLDisplayAgent lastBuiltinDisplaySliderValueX]
+ -[PLDisplayAgent lastBuiltinDisplayTimeX]
+ -[PLDisplayAgent lastForegroundAppAPLX]
+ -[PLDisplayAgent lastScreenStateDisplayX]
+ -[PLDisplayAgent lastmNitsValueX]
+ -[PLDisplayAgent logDisplayAPLX]
+ -[PLDisplayAgent logEventForwardDisplayXWithRawData:withDate:]
+ -[PLDisplayAgent modernDisplayObserverX]
+ -[PLDisplayAgent pendingBacklightEntryDateX]
+ -[PLDisplayAgent pendingBacklightEntryX]
+ -[PLDisplayAgent secondaryBacklightKey]
+ -[PLDisplayAgent secondaryDisplayRef]
+ -[PLDisplayAgent setAfkEndpointsX:]
+ -[PLDisplayAgent setApplicationNotificationX:]
+ -[PLDisplayAgent setBacklightFilterTimerX:]
+ -[PLDisplayAgent setCbDisplayClientX:]
+ -[PLDisplayAgent setDisplayIdentifier:]
+ -[PLDisplayAgent setDisplayIdentifierX:]
+ -[PLDisplayAgent setDisplayLuxX:]
+ -[PLDisplayAgent setDisplaymNitsX:]
+ -[PLDisplayAgent setHDRHeadroomX:]
+ -[PLDisplayAgent setIsDisplayOnNowX:]
+ -[PLDisplayAgent setLastBuiltinDisplayBrightnessX:]
+ -[PLDisplayAgent setLastBuiltinDisplayLuxX:]
+ -[PLDisplayAgent setLastBuiltinDisplaySliderValueX:]
+ -[PLDisplayAgent setLastBuiltinDisplayTimeX:]
+ -[PLDisplayAgent setLastForegroundAppAPLX:]
+ -[PLDisplayAgent setLastScreenStateDisplayX:]
+ -[PLDisplayAgent setLastmNitsValueX:]
+ -[PLDisplayAgent setModernDisplayObserverX:]
+ -[PLDisplayAgent setPendingBacklightEntryDateX:]
+ -[PLDisplayAgent setPendingBacklightEntryX:]
+ -[PLDisplayAgent setSecondaryBacklightKey:]
+ -[PLDisplayAgent setSecondaryDisplayRef:]
+ -[PLDisplayAgent setUAmpsEntryX:]
+ -[PLDisplayAgent setUAmpsFilterTimerX:]
+ -[PLDisplayAgent setupModernCoreBrightnessClientXForCADisplay:]
+ -[PLDisplayAgent uAmpsEntryX]
+ -[PLDisplayAgent uAmpsFilterTimerX]
+ -[PLDisplayAgent updateLastForegroundAppAPLX:]
+ -[PLDisplayIOReportAODStatsX init]
+ -[PLDisplayIOReportStatsX init]
+ -[PLScreenStateAgent accountForegroundWithMainPrecedence]
+ -[PLScreenStateAgent displayCallbackX]
+ -[PLScreenStateAgent displayStateX]
+ -[PLScreenStateAgent displayValueForLayout:]
+ -[PLScreenStateAgent handleDisplayCallbackX:]
+ -[PLScreenStateAgent isSecondaryDisplay:]
+ -[PLScreenStateAgent lastDisplayLayoutContainsLockScreenX]
+ -[PLScreenStateAgent lastDisplayLayoutX]
+ -[PLScreenStateAgent lastDisplayXLayoutEntries]
+ -[PLScreenStateAgent lastLayoutMonitorEntriesX]
+ -[PLScreenStateAgent lastMainLayoutEntries]
+ -[PLScreenStateAgent lastScreenStateEntriesX]
+ -[PLScreenStateAgent logEventBackwardBacklightStateChangeX:]
+ -[PLScreenStateAgent logEventForwardScreenStateX:]
+ -[PLScreenStateAgent primaryDisplayHWID]
+ -[PLScreenStateAgent secondaryDisplayHWID]
+ -[PLScreenStateAgent setDisplayCallbackX:]
+ -[PLScreenStateAgent setDisplayStateX:]
+ -[PLScreenStateAgent setLastDisplayLayoutContainsLockScreenX:]
+ -[PLScreenStateAgent setLastDisplayLayoutX:]
+ -[PLScreenStateAgent setLastDisplayXLayoutEntries:]
+ -[PLScreenStateAgent setLastLayoutMonitorEntriesX:]
+ -[PLScreenStateAgent setLastMainLayoutEntries:]
+ -[PLScreenStateAgent setLastScreenStateEntriesX:]
+ -[PLScreenStateAgent setPrimaryDisplayHWID:]
+ -[PLScreenStateAgent setSecondaryDisplayHWID:]
+ -[_PLDisplayCBPropertyObserver forDisplayX]
+ -[_PLDisplayCBPropertyObserver setForDisplayX:]
+ GCC_except_table138
+ GCC_except_table142
+ GCC_except_table170
+ GCC_except_table188
+ GCC_except_table195
+ GCC_except_table200
+ GCC_except_table261
+ GCC_except_table265
+ GCC_except_table267
+ GCC_except_table275
+ GCC_except_table281
+ GCC_except_table287
+ GCC_except_table298
+ GCC_except_table330
+ GCC_except_table333
+ GCC_except_table337
+ GCC_except_table62
+ OBJC_IVAR_$_AWDMETRICSKCellularPlatformApBbSleepStatsPlatformState._mode
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogDcsPerfStates._bins
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogDcsPerfStates._durationMs
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogDcsPerfStates._has
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogDcsPerfStates._lastSdmState
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogDcsPerfStates._timestamp
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogDcsPerfStatesMBin._binId
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogDcsPerfStatesMBin._count
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogDcsPerfStatesMBin._duration
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogDcsPerfStatesMBin._has
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin._appliedDrxdMs
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin._cellGroup
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogLteNrRxDiversityHistRxdBin._deployment
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRAntennaElement._antennaElements
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRAntennaElement._has
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRAntennaElement._subsId
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRAntennaElement._timestamp
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRAntennaElement._totalDurationMs
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement._binDurationMs
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement._direction
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement._elements
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement._has
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRDCEvent._event
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRDCEvent._has
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRDCEvent._subsId
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRDCEvent._timestamp
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamID._bins
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamID._durationMs
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamID._has
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamID._subsId
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamID._timestamp
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin._binId
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin._duration
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin._has
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNrCaConfigActivateStatsMBin._areScellsScheduled
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNrCaConfigActivateStatsMBin._isSpcellScheduled
+ OBJC_IVAR_$_AWDMETRICSKCellularPowerLogNrCaConfigActivateStatsMBin._scheduledScellCount
+ OBJC_IVAR_$_AWDMETRICSKCellularRfTunerHistTunerStateDuration._deviceMode
+ _AWDMETRICSKCellularPowerLogDcsPerfStatesMBinReadFrom
+ _AWDMETRICSKCellularPowerLogDcsPerfStatesReadFrom
+ _AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElementReadFrom
+ _AWDMETRICSKCellularPowerLogNRAntennaElementReadFrom
+ _AWDMETRICSKCellularPowerLogNRDCEventReadFrom
+ _AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBinReadFrom
+ _AWDMETRICSKCellularPowerLogNRmmWaveBeamIDReadFrom
+ _IORegistryEntryGetName
+ _OBJC_CLASS_$_AWDMETRICSKCellularPowerLogDcsPerfStates
+ _OBJC_CLASS_$_AWDMETRICSKCellularPowerLogDcsPerfStatesMBin
+ _OBJC_CLASS_$_AWDMETRICSKCellularPowerLogNRAntennaElement
+ _OBJC_CLASS_$_AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement
+ _OBJC_CLASS_$_AWDMETRICSKCellularPowerLogNRDCEvent
+ _OBJC_CLASS_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamID
+ _OBJC_CLASS_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin
+ _OBJC_CLASS_$_PLDisplayIOReportAODStatsX
+ _OBJC_CLASS_$_PLDisplayIOReportStatsX
+ _OBJC_IVAR_$_PLDisplayAgent._displayLuxX
+ _OBJC_IVAR_$_PLDisplayAgent._displaymNitsX
+ _OBJC_IVAR_$_PLDisplayAgent._isDisplayOnNowX
+ _OBJC_IVAR_$_PLDisplayAgent._lastBuiltinDisplayBrightnessX
+ _OBJC_IVAR_$_PLDisplayAgent._lastBuiltinDisplayLuxX
+ _OBJC_IVAR_$_PLDisplayAgent._lastBuiltinDisplaySliderValueX
+ _OBJC_IVAR_$_PLDisplayAgent._lastBuiltinDisplayTimeX
+ _OBJC_IVAR_$_PLDisplayAgent._lastScreenStateDisplayX
+ _OBJC_IVAR_$_PLScreenStateAgent._displayStateX
+ _OBJC_IVAR_$_PLScreenStateAgent._lastDisplayLayoutContainsLockScreenX
+ _OBJC_IVAR_$__PLDisplayCBPropertyObserver._forDisplayX
+ _OBJC_METACLASS_$_AWDMETRICSKCellularPowerLogDcsPerfStates
+ _OBJC_METACLASS_$_AWDMETRICSKCellularPowerLogDcsPerfStatesMBin
+ _OBJC_METACLASS_$_AWDMETRICSKCellularPowerLogNRAntennaElement
+ _OBJC_METACLASS_$_AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement
+ _OBJC_METACLASS_$_AWDMETRICSKCellularPowerLogNRDCEvent
+ _OBJC_METACLASS_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamID
+ _OBJC_METACLASS_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin
+ _OBJC_METACLASS_$_PLDisplayIOReportAODStatsX
+ _OBJC_METACLASS_$_PLDisplayIOReportStatsX
+ __OBJC_$_CLASS_METHODS_AWDMETRICSKCellularPowerLogDcsPerfStates
+ __OBJC_$_CLASS_METHODS_AWDMETRICSKCellularPowerLogNRAntennaElement
+ __OBJC_$_CLASS_METHODS_AWDMETRICSKCellularPowerLogNRmmWaveBeamID
+ __OBJC_$_INSTANCE_METHODS_AWDMETRICSKCellularPowerLogDcsPerfStates
+ __OBJC_$_INSTANCE_METHODS_AWDMETRICSKCellularPowerLogDcsPerfStatesMBin
+ __OBJC_$_INSTANCE_METHODS_AWDMETRICSKCellularPowerLogNRAntennaElement
+ __OBJC_$_INSTANCE_METHODS_AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement
+ __OBJC_$_INSTANCE_METHODS_AWDMETRICSKCellularPowerLogNRDCEvent
+ __OBJC_$_INSTANCE_METHODS_AWDMETRICSKCellularPowerLogNRmmWaveBeamID
+ __OBJC_$_INSTANCE_METHODS_AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin
+ __OBJC_$_INSTANCE_METHODS_PLDisplayIOReportAODStatsX
+ __OBJC_$_INSTANCE_METHODS_PLDisplayIOReportStatsX
+ __OBJC_$_INSTANCE_VARIABLES_AWDMETRICSKCellularPowerLogDcsPerfStates
+ __OBJC_$_INSTANCE_VARIABLES_AWDMETRICSKCellularPowerLogDcsPerfStatesMBin
+ __OBJC_$_INSTANCE_VARIABLES_AWDMETRICSKCellularPowerLogNRAntennaElement
+ __OBJC_$_INSTANCE_VARIABLES_AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement
+ __OBJC_$_INSTANCE_VARIABLES_AWDMETRICSKCellularPowerLogNRDCEvent
+ __OBJC_$_INSTANCE_VARIABLES_AWDMETRICSKCellularPowerLogNRmmWaveBeamID
+ __OBJC_$_INSTANCE_VARIABLES_AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin
+ __OBJC_$_PROP_LIST_AWDMETRICSKCellularPowerLogDcsPerfStates
+ __OBJC_$_PROP_LIST_AWDMETRICSKCellularPowerLogDcsPerfStatesMBin
+ __OBJC_$_PROP_LIST_AWDMETRICSKCellularPowerLogNRAntennaElement
+ __OBJC_$_PROP_LIST_AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement
+ __OBJC_$_PROP_LIST_AWDMETRICSKCellularPowerLogNRDCEvent
+ __OBJC_$_PROP_LIST_AWDMETRICSKCellularPowerLogNRmmWaveBeamID
+ __OBJC_$_PROP_LIST_AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin
+ __OBJC_CLASS_PROTOCOLS_$_AWDMETRICSKCellularPowerLogDcsPerfStates
+ __OBJC_CLASS_PROTOCOLS_$_AWDMETRICSKCellularPowerLogDcsPerfStatesMBin
+ __OBJC_CLASS_PROTOCOLS_$_AWDMETRICSKCellularPowerLogNRAntennaElement
+ __OBJC_CLASS_PROTOCOLS_$_AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement
+ __OBJC_CLASS_PROTOCOLS_$_AWDMETRICSKCellularPowerLogNRDCEvent
+ __OBJC_CLASS_PROTOCOLS_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamID
+ __OBJC_CLASS_PROTOCOLS_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin
+ __OBJC_CLASS_RO_$_AWDMETRICSKCellularPowerLogDcsPerfStates
+ __OBJC_CLASS_RO_$_AWDMETRICSKCellularPowerLogDcsPerfStatesMBin
+ __OBJC_CLASS_RO_$_AWDMETRICSKCellularPowerLogNRAntennaElement
+ __OBJC_CLASS_RO_$_AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement
+ __OBJC_CLASS_RO_$_AWDMETRICSKCellularPowerLogNRDCEvent
+ __OBJC_CLASS_RO_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamID
+ __OBJC_CLASS_RO_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin
+ __OBJC_CLASS_RO_$_PLDisplayIOReportAODStatsX
+ __OBJC_CLASS_RO_$_PLDisplayIOReportStatsX
+ __OBJC_METACLASS_RO_$_AWDMETRICSKCellularPowerLogDcsPerfStates
+ __OBJC_METACLASS_RO_$_AWDMETRICSKCellularPowerLogDcsPerfStatesMBin
+ __OBJC_METACLASS_RO_$_AWDMETRICSKCellularPowerLogNRAntennaElement
+ __OBJC_METACLASS_RO_$_AWDMETRICSKCellularPowerLogNRAntennaElementMNRAntennaElement
+ __OBJC_METACLASS_RO_$_AWDMETRICSKCellularPowerLogNRDCEvent
+ __OBJC_METACLASS_RO_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamID
+ __OBJC_METACLASS_RO_$_AWDMETRICSKCellularPowerLogNRmmWaveBeamIDMBin
+ __OBJC_METACLASS_RO_$_PLDisplayIOReportAODStatsX
+ __OBJC_METACLASS_RO_$_PLDisplayIOReportStatsX
+ ___22-[PLDisplayAgent init]_block_invoke_4
+ ___44-[PLAppTimeService initOperatorDependancies]_block_invoke_8
+ ___50-[PLScreenStateAgent logEventForwardScreenStateX:]_block_invoke
+ ___55-[PLDisplayAgent handleAFKInterfaceIOServiceCallbackX:]_block_invoke
+ ___64-[PLDisplayAgent handleBrightnessClientNotificationX:withValue:]_block_invoke
+ ___75-[PLBatteryAgent logEventBackwardRebalanceWithRawData:hwBypassByChargerID:]_block_invoke
+ ___block_descriptor_72_e8_32s40s48r56r64r_e5_v8?0lr48l8s32l8r56l8s40l8r64l8
+ ___block_descriptor_72_e8_32s40s48s56s64s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72s_e19_"NSDictionary"8?0ls32l8s40l8s48l8s56l8s64l8s72l8
+ _displaySync_block_invoke_2.screenStateEntriesCounterX
+ _kActiveMMW
+ _kPLBatteryAgentEventBackwardNameBatteryPack0
+ _kPLBatteryAgentEventBackwardNameBatteryPack1
+ _kPLBatteryAgentEventBackwardNameChargerData1
+ _kPLBatteryAgentEventBackwardNameRebalance
+ _kPLBatteryAgentEventBackwardNameShelfLifeModeAutoEntry
+ _kPLBatteryAgentEventBackwardNameShelfLifeModeAutoEntryX
+ _kPLBatteryAgentEventBackwardNameShelfLifeModeExitCounters
+ _kPLBatteryAgentEventBackwardNameShelfLifeModeExitCountersX
+ _kPLBatteryAgentEventBackwardNameTrustedBatteryHealth0
+ _kPLBatteryAgentEventBackwardNameTrustedBatteryHealth1
+ _kPLBatteryAgentEventNoneBatteryConfigPack0
+ _kPLBatteryAgentEventNoneBatteryConfigPack1
+ _kPLBatteryAgentEventPointNameBatteryShutdownPack1
+ _kPLBatteryAgentStringLastShutdownSystemTimestamp1
+ _kPLDisplayAgentEventBackwardNameAPLStatsX
+ _kPLDisplayAgentEventBackwardNameDCPAODstatsX
+ _kPLDisplayAgentEventForwardNameDisplayX
+ _kPLDisplayAgentEventPointNameDisplayX
+ _kPLIOReportAgentEventBackwardNameDCPXScanout
+ _kPLIOReportAgentEventBackwardNameDCPXScanoutStats
+ _kPLIOReportAgentEventBackwardNameDCPXSwap
+ _kPLIOReportAgentEventBackwardNameMultitouch2HighLevelStats
+ _kPLIOReportAgentEventBackwardNameMultitouch2Touch
+ _kPLScreenStateAgentEventBackwardNameBacklightStateChangeX
+ _kPLScreenStateAgentEventForwardNameScreenStateX
+ _objc_setProperty_atomic_copy
- GCC_except_table136
- GCC_except_table140
- GCC_except_table158
- GCC_except_table175
- GCC_except_table187
- GCC_except_table193
- GCC_except_table248
- GCC_except_table257
- GCC_except_table260
- GCC_except_table262
- GCC_except_table271
- GCC_except_table277
- GCC_except_table278
- GCC_except_table325
- GCC_except_table328
- GCC_except_table332
- GCC_except_table54
- ___26-[PLScreenStateAgent init]_block_invoke_5
- ___51-[PLBatteryAgent logCurrentAccumulatorWithRawData:]_block_invoke_2
- ___block_descriptor_64_e8_32s40s48r56r_e5_v8?0lr48l8s32l8r56l8s40l8
CStrings:
+ "#"
+ "%@-%llx"
+ "(nil)"
+ "/\n"
+ "APLStatsX"
+ "ActiveMMW"
+ "AutoEntryCounterCase2"
+ "AutoEntryCounterCase3"
+ "BacklightStateChangeX"
+ "BatteryConfigPack0"
+ "BatteryConfigPack1"
+ "BatteryPack0"
+ "BatteryPack1"
+ "BatteryShutdownPack1"
+ "ButtonPressExitCounter"
+ "CACHED_CSI_DUAL_ANTENNA_DURATION"
+ "CACHED_CSI_ENABLED_DURATION"
+ "CACHED_CSI_MAC_ACTIVE_DURATION"
+ "CBDisplayClient created for DisplayX, displayId=%u"
+ "CBDisplayClient: no CADisplay provided for DisplayX"
+ "CBDisplayClient: primary cbClient not yet initialized; DisplayX setup deferred"
+ "CSIDualAntennaDuration"
+ "CSIEnabledDuration"
+ "CSIMacActiveDuration"
+ "ChargerConnectExitCounter"
+ "ChargerData1"
+ "CurrentAccumulator: expected %u packs, gathered %lu; skipping sample"
+ "CurrentAccumulator: failed to match AppleSmartBatteryPack %x"
+ "DCPAODstatsX"
+ "DCPSEC"
+ "DCPSEC,scanout"
+ "DCPSEC,scanout stats"
+ "DCPSEC,swap"
+ "DCPSECscanout"
+ "DCPSECscanoutstats"
+ "DCPSECswap"
+ "DCS_PERF_STATE0_BYPASS"
+ "DCS_PERF_STATE1_WARM_BOOT0"
+ "DCS_PERF_STATE2_WARM_BOOT1"
+ "DCS_PERF_STATE3_F0"
+ "DCS_PERF_STATE4_F1"
+ "DCS_PERF_STATE5_F2"
+ "DCS_PERF_STATE6_F3"
+ "DCS_PERF_STATE7_F4"
+ "DCS_PERF_STATE8_F5"
+ "DEPLOYMENT_NSA_FR2"
+ "DEVICE_MODE_A"
+ "DEVICE_MODE_B"
+ "DEVICE_MODE_NOT_YET_UPDATED"
+ "DEVICE_MODE_UNKNOWN"
+ "DPL_NR1_NRDC"
+ "DPL_NR2_ENDC"
+ "DPL_NR2_NRDC"
+ "Detected aggregate display reference (ID: 0x%llx, name: %@), using primary display"
+ "Display reference matches known display but not in map: %@"
+ "DisplayDynamicX"
+ "DisplayX"
+ "DisplayX AFK Data: %@"
+ "DisplayX AFK Registry ID: %llu"
+ "DisplayX AFK input buffer is empty"
+ "DisplayX AFK match: registryID=%llu role='%{public}@'"
+ "DisplayX AFK matched role '%{public}@'"
+ "DisplayX AFK msg is not a dictionary"
+ "DisplayX AFK unserialize error: %@"
+ "DisplayX AFKInterface activated"
+ "DisplayX CBDisplayClient observer registered for %lu keys"
+ "DisplayX CBDisplayClient registerObserver failed: %{public}@; tearing down"
+ "DisplayX Reported mNits:%f brightness:%f %%:%f"
+ "DisplayX entry: %@"
+ "DisplayX final data to log: %@"
+ "DisplayX flush: writing pending entry: %@ date: %@"
+ "DisplayX received AFK msg at timestamp: %llu"
+ "DisplayX setup skipped: secondaryCADisplay returned the same displayId (%u) as the primary; refusing to double-bind"
+ "DisplayX: IO object property is not dictionary"
+ "DisplayX: Not logging brightness value: %{public}@"
+ "DisplayX: error getting AFK interface"
+ "DisplayX: error getting IO object properties"
+ "DisplayX: ignoring CB key %{public}@"
+ "DisplayX: received Brightness Notification: %@"
+ "E1P1"
+ "E1P2"
+ "E2P1"
+ "E2P2"
+ "E3P1"
+ "E3P2"
+ "E4P1"
+ "E4P2"
+ "E5P1"
+ "E5P2"
+ "ENDC_FR2"
+ "EPRole"
+ "EndpointName"
+ "Erronous spot that we find sth other than primary and secondary display"
+ "Failed to create reference for primary display"
+ "Failed to create reference for secondary display"
+ "Failed to get backlight for primary display"
+ "Failed to get backlight for secondary display"
+ "Failed to retrieve battery trusted dictionary for pack"
+ "Found %lu integrated displays"
+ "HOR_NR_BEAM_ID_1"
+ "HOR_NR_BEAM_ID_10"
+ "HOR_NR_BEAM_ID_11"
+ "HOR_NR_BEAM_ID_12"
+ "HOR_NR_BEAM_ID_13"
+ "HOR_NR_BEAM_ID_14"
+ "HOR_NR_BEAM_ID_15"
+ "HOR_NR_BEAM_ID_16"
+ "HOR_NR_BEAM_ID_17"
+ "HOR_NR_BEAM_ID_18"
+ "HOR_NR_BEAM_ID_19"
+ "HOR_NR_BEAM_ID_2"
+ "HOR_NR_BEAM_ID_20"
+ "HOR_NR_BEAM_ID_21"
+ "HOR_NR_BEAM_ID_22"
+ "HOR_NR_BEAM_ID_23"
+ "HOR_NR_BEAM_ID_24"
+ "HOR_NR_BEAM_ID_25"
+ "HOR_NR_BEAM_ID_26"
+ "HOR_NR_BEAM_ID_27"
+ "HOR_NR_BEAM_ID_28"
+ "HOR_NR_BEAM_ID_29"
+ "HOR_NR_BEAM_ID_3"
+ "HOR_NR_BEAM_ID_30"
+ "HOR_NR_BEAM_ID_31"
+ "HOR_NR_BEAM_ID_32"
+ "HOR_NR_BEAM_ID_33"
+ "HOR_NR_BEAM_ID_34"
+ "HOR_NR_BEAM_ID_35"
+ "HOR_NR_BEAM_ID_36"
+ "HOR_NR_BEAM_ID_37"
+ "HOR_NR_BEAM_ID_38"
+ "HOR_NR_BEAM_ID_39"
+ "HOR_NR_BEAM_ID_4"
+ "HOR_NR_BEAM_ID_40"
+ "HOR_NR_BEAM_ID_41"
+ "HOR_NR_BEAM_ID_42"
+ "HOR_NR_BEAM_ID_43"
+ "HOR_NR_BEAM_ID_44"
+ "HOR_NR_BEAM_ID_45"
+ "HOR_NR_BEAM_ID_46"
+ "HOR_NR_BEAM_ID_47"
+ "HOR_NR_BEAM_ID_48"
+ "HOR_NR_BEAM_ID_49"
+ "HOR_NR_BEAM_ID_5"
+ "HOR_NR_BEAM_ID_50"
+ "HOR_NR_BEAM_ID_51"
+ "HOR_NR_BEAM_ID_52"
+ "HOR_NR_BEAM_ID_53"
+ "HOR_NR_BEAM_ID_54"
+ "HOR_NR_BEAM_ID_55"
+ "HOR_NR_BEAM_ID_56"
+ "HOR_NR_BEAM_ID_57"
+ "HOR_NR_BEAM_ID_58"
+ "HOR_NR_BEAM_ID_59"
+ "HOR_NR_BEAM_ID_6"
+ "HOR_NR_BEAM_ID_60"
+ "HOR_NR_BEAM_ID_61"
+ "HOR_NR_BEAM_ID_62"
+ "HOR_NR_BEAM_ID_63"
+ "HOR_NR_BEAM_ID_64"
+ "HOR_NR_BEAM_ID_7"
+ "HOR_NR_BEAM_ID_8"
+ "HOR_NR_BEAM_ID_9"
+ "IDLE_SCENARIO"
+ "INSTANT_CSI_DUAL_ANTENNA_DURATION"
+ "INSTANT_CSI_ENABLED_DURATION"
+ "INSTANT_CSI_MAC_ACTIVE_DURATION"
+ "LTE_ONLY"
+ "LastSLMExitType"
+ "LastShutdownSystemTimestamp1"
+ "Layout HWID: %{public}@ (primary: %{public}@, secondary: %{public}@)"
+ "MCG"
+ "MODE_A"
+ "MODE_B"
+ "MODE_UNKNOWN"
+ "MULTI_BATTERY: Failed to get AppleChargerData with result=%x"
+ "MULTI_BATTERY: Failed to get AppleSmartBatteryPack data with result=%x"
+ "MULTI_BATTERY: Logging rebalance entry %@"
+ "MULTI_BATTERY: This device has %d batteries"
+ "MULTI_BATTERY: This device has %d chargers"
+ "MULTI_BATTERY: rawDataMultiBattery=%@"
+ "Multitouch2,Multitouch high level stats"
+ "Multitouch2,touch"
+ "Multitouch2Multitouchhighlevelstats"
+ "Multitouch2touch"
+ "NO_RX_NO_TX_NO_DCI_DECODING"
+ "NO_RX_NO_TX_WITHOUT_DCI"
+ "NR mmW 2nd: %d"
+ "NR mmW Active power coefficient: %f"
+ "NR mmW CA act power2: %f"
+ "NR mmW CA act power: %f"
+ "NR mmW CA config power: %f"
+ "NR mmW Tx power: %f"
+ "NR mmW nonCA Active power: %f"
+ "NR mmW nonCA Active2 power: %f"
+ "NR mmW prime: %d"
+ "NR nrmmWActivatedCAduration2: %f"
+ "NR nrmmWActivatedCAduration: %f"
+ "NR nrmmWConfiguredCAduration: %f"
+ "NRRC_CAUSE_REEST_INVALID_CSI_BWP_REF_CONFIG"
+ "NRRC_CAUSE_REEST_INVALID_PUCCH_SYMBOL_CONFIG"
+ "NRRC_CAUSE_REEST_INVALID_SCELL_UL_CONFIG"
+ "NRRC_CAUSE_REEST_INVALID_SRS_AS_PATTERN_CONFIG"
+ "NRRC_CAUSE_REEST_INVALID_TAG_ASSIGNMENT_CONFIG"
+ "NRRC_CAUSE_REEST_INVALID_UL_PATHLOSS_VALUE"
+ "NRRC_CAUSE_REEST_L1_CONFIG_VALIDATION_FAILED"
+ "NRRC_CAUSE_REL_INVALID_CSI_BWP_REF_CONFIG"
+ "NRRC_CAUSE_REL_INVALID_PUCCH_SYMBOL_CONFIG"
+ "NRRC_CAUSE_REL_INVALID_SCELL_UL_CONFIG"
+ "NRRC_CAUSE_REL_INVALID_SRS_AS_PATTERN_CONFIG"
+ "NRRC_CAUSE_REL_INVALID_TAG_ASSIGNMENT_CONFIG"
+ "NRRC_CAUSE_REL_INVALID_UL_PATHLOSS_VALUE"
+ "NRRC_CAUSE_REL_L1_CONFIG_VALIDATION_FAILED"
+ "NRSA"
+ "NR_FR2"
+ "NR_MMWAVE_ENDC_CONNECTED"
+ "NR_MMWAVE_NRDC_CONNECTED"
+ "Primary AFK match: registryID=%llu role='%{public}@'"
+ "Primary HWID: %{public}@, Secondary HWID: %{public}@"
+ "Primary display: %@, last state: %d"
+ "RebalanceData"
+ "RebalanceEnableStatus"
+ "RebalanceErrorFlags"
+ "RebalanceHWBypassFETStatus"
+ "RebalanceHWBypassFETStatus0"
+ "RebalanceHWBypassFETStatus1"
+ "RebalanceInrushCurrentDebug"
+ "RebalanceNotRebalancingReason"
+ "RebalanceOutputStruct"
+ "RebalanceTimeSeconds"
+ "Role"
+ "Routing to PRIMARY display logging"
+ "Routing to SECONDARY display logging"
+ "S1_MUTE"
+ "SCC9"
+ "SCENARIO_1_MODE_B"
+ "SCENARIO_2_MODE_B"
+ "SCENARIO_3_MODE_B"
+ "SCENARIO_4_MODE_B"
+ "SCENARIO_5_MODE_B"
+ "SCENARIO_6_MODE_B"
+ "SCENARIO_E85_MODE_B"
+ "SCENARIO_FREESPACE_MODE_B"
+ "SCENARIO_IDLE_MODE_B"
+ "SCENARIO_INVALID"
+ "SCENARIO_R5_MODE_B"
+ "SCG"
+ "SDM_TRIGGER_VONR"
+ "SECONDARY Display callback - userInfo=%@"
+ "SECONDARY: Display callback - userInfo=%@"
+ "SECONDARY: FBSDisplayLayoutElement currentEntry bundleID: %@"
+ "SECONDARY: LayoutEntries is empty"
+ "SECONDARY: LayoutEntries: %@"
+ "SECONDARY: Logged %d FBSDisplayLayoutElement entries"
+ "SECONDARY: Relogging screen state - displayStateX=%d, containsLockScreen=%d"
+ "SECONDARY: Screen State element's bundleID/identifier is nil"
+ "SECONDARY: calling logEventForwardScreenStateX with displayLayout=%@"
+ "SECONDARY: current FBSDisplayLayoutElement entry was already logged, skipping"
+ "SECONDARY: dts runtime ff enabled=%d, [PLPlatform hasAOD]=%d]"
+ "SECONDARY: element bundleID=%@, entry=%@, displayStateX=%d"
+ "SECONDARY: entry after transformation = %@"
+ "SECONDARY: self.displayStateX=%d, self.lastDisplayLayoutContainsLockScreenX=%d,  self.lastDisplayLayoutX=%@"
+ "SINOPE_HW_HIST_LTE_NR_RX_DIV: cellgroup_ = %d"
+ "SINOPE_HW_HIST_LTE_NR_RX_DIV: deployment_ = %d"
+ "SINOPE_HW_HIST_LTE_NR_RX_DIV: fastrxd_ = %d"
+ "SOCSLP_SLP_OFL"
+ "SUB6_NRDC_MMW_ON"
+ "ScreenStateX"
+ "Secondary display: %@, last state: %d"
+ "ShelfLifeMode: failed to match AppleSmartBatteryPack %x"
+ "ShelfLifeModeAutoEntry"
+ "ShelfLifeModeAutoEntryX"
+ "ShelfLifeModeExitCounters"
+ "ShelfLifeModeExitCountersX"
+ "Single integrated display, primary HWID: %{public}@"
+ "TrustedBatteryHealth0"
+ "TrustedBatteryHealth1"
+ "USLEEP_ALL"
+ "USLEEP_ANY"
+ "Unexpected integrated display count: %lu"
+ "Unexpected number of integrated displays: %d"
+ "VDD_SOC_PERFSTATE_7"
+ "VER_NR_BEAM_ID_1"
+ "VER_NR_BEAM_ID_10"
+ "VER_NR_BEAM_ID_11"
+ "VER_NR_BEAM_ID_12"
+ "VER_NR_BEAM_ID_13"
+ "VER_NR_BEAM_ID_14"
+ "VER_NR_BEAM_ID_15"
+ "VER_NR_BEAM_ID_16"
+ "VER_NR_BEAM_ID_17"
+ "VER_NR_BEAM_ID_18"
+ "VER_NR_BEAM_ID_19"
+ "VER_NR_BEAM_ID_2"
+ "VER_NR_BEAM_ID_20"
+ "VER_NR_BEAM_ID_21"
+ "VER_NR_BEAM_ID_22"
+ "VER_NR_BEAM_ID_23"
+ "VER_NR_BEAM_ID_24"
+ "VER_NR_BEAM_ID_25"
+ "VER_NR_BEAM_ID_26"
+ "VER_NR_BEAM_ID_27"
+ "VER_NR_BEAM_ID_28"
+ "VER_NR_BEAM_ID_29"
+ "VER_NR_BEAM_ID_3"
+ "VER_NR_BEAM_ID_30"
+ "VER_NR_BEAM_ID_31"
+ "VER_NR_BEAM_ID_32"
+ "VER_NR_BEAM_ID_33"
+ "VER_NR_BEAM_ID_34"
+ "VER_NR_BEAM_ID_35"
+ "VER_NR_BEAM_ID_36"
+ "VER_NR_BEAM_ID_37"
+ "VER_NR_BEAM_ID_38"
+ "VER_NR_BEAM_ID_39"
+ "VER_NR_BEAM_ID_4"
+ "VER_NR_BEAM_ID_40"
+ "VER_NR_BEAM_ID_41"
+ "VER_NR_BEAM_ID_42"
+ "VER_NR_BEAM_ID_43"
+ "VER_NR_BEAM_ID_44"
+ "VER_NR_BEAM_ID_45"
+ "VER_NR_BEAM_ID_46"
+ "VER_NR_BEAM_ID_47"
+ "VER_NR_BEAM_ID_48"
+ "VER_NR_BEAM_ID_49"
+ "VER_NR_BEAM_ID_5"
+ "VER_NR_BEAM_ID_50"
+ "VER_NR_BEAM_ID_51"
+ "VER_NR_BEAM_ID_52"
+ "VER_NR_BEAM_ID_53"
+ "VER_NR_BEAM_ID_54"
+ "VER_NR_BEAM_ID_55"
+ "VER_NR_BEAM_ID_56"
+ "VER_NR_BEAM_ID_57"
+ "VER_NR_BEAM_ID_58"
+ "VER_NR_BEAM_ID_59"
+ "VER_NR_BEAM_ID_6"
+ "VER_NR_BEAM_ID_60"
+ "VER_NR_BEAM_ID_61"
+ "VER_NR_BEAM_ID_62"
+ "VER_NR_BEAM_ID_63"
+ "VER_NR_BEAM_ID_64"
+ "VER_NR_BEAM_ID_7"
+ "VER_NR_BEAM_ID_8"
+ "VER_NR_BEAM_ID_9"
+ "actmmw"
+ "antenna_elements"
+ "applied_drxd_ms"
+ "applied_drxd_ms_%d"
+ "band_group_%d"
+ "bin_duration_ms"
+ "cell_group"
+ "cell_group_%d"
+ "cnfgmmw"
+ "com.apple.battery.RebalanceData"
+ "device_mode"
+ "displayIdentifier"
+ "elements"
+ "endpoint-name"
+ "kCellularPowerLogDcsPerfStates"
+ "kCellularPowerLogNRAntennaElement"
+ "kCellularPowerLogNRDCEvent"
+ "kCellularPowerLogNRmmWaveBeamID"
+ "logDisplayAPLX"
+ "mmw config : %f"
+ "newDisplayClientForID:%u failed for DisplayX: %{public}@"
+ "rebalance_enable_status"
+ "rebalance_error_flags"
+ "rebalance_hw_bypass_fet_status_0"
+ "rebalance_hw_bypass_fet_status_1"
+ "rebalance_not_rebalancing_reason"
+ "rebalance_time_seconds"
+ "role"
```
