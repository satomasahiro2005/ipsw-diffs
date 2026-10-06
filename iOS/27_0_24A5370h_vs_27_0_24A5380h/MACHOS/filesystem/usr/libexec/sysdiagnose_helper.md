## sysdiagnose_helper

> `/usr/libexec/sysdiagnose_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23f30` | `0x24bec` | **`+0xcbc`** |
| `__TEXT.__cstring` | `0x91f6` | `0x972f` | **`+0x539`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1593.0.0.0.0
+1598.0.0.0.0

-  CStrings:  2121
+  CStrings:  2176
CStrings:
+ "AlignedFastReadDisturbs"
+ "AlignedRegularReadDisturbs"
+ "bandCyclesHisto"
+ "bandCyclesHistoStart"
+ "cbdrRefreshGradesHP"
+ "cbdrRefreshGradesMP"
+ "cbdrStatusHP"
+ "cbdrStatusMP"
+ "fairPurgeCompleteCount"
+ "fairPurgeStartCount"
+ "fairPurgeValidityDeltaSectors"
+ "fairPurgeValidityIncreasedCount"
+ "gcSlowInlineT0ReadLatencyHisto"
+ "gcSlowInlineT0Reads"
+ "gcSlowIsT0ReadLatencyHisto"
+ "gcSlowIsT0Reads"
+ "gcSlowT0ReadLatencyHisto"
+ "gcSlowT0Reads"
+ "hotBandsClass"
+ "idleStackAvgValidityAtSlowGC"
+ "idleStackCurrentUrgency"
+ "idleStackFullnessAtSlowGC"
+ "idleStackHighWritesDailyHisto"
+ "idleStackPhaseDurationAlignFast"
+ "idleStackPhaseDurationAlignRegular"
+ "idleStackPhaseDurationCbdr"
+ "idleStackPhaseDurationPurgeable"
+ "idleStackPhaseDurationSquareGC1"
+ "idleStackPhaseDurationSquareGC2"
+ "idleStackPhaseDurationSquareGC3"
+ "idleStackPhaseDurationWearlevel"
+ "idleStackSectorsToHigh"
+ "idleStackSectorsToSlowGC"
+ "idleStackSlowGCDailyHisto"
+ "idleStackSlowGCSrcRankHisto"
+ "idleStackTimeToSlowGC"
+ "idleStackValidityCurveAtIdleStackStart"
+ "istkHostWritesToHighUrgency"
+ "istkHostWritesToMedUrgency"
+ "istkHoursSinceAlignFast"
+ "istkHoursSinceAlignRegular"
+ "istkHoursSinceSquare"
+ "istkHoursSinceWearLevel"
+ "istkLastAlignFastHr"
+ "istkLastAlignRegularHr"
+ "istkLastFullDoneHostWrites"
+ "istkLastSquareHr"
+ "istkLastWearLevelHr"
+ "istkSecsSinceLastSidebarGen"
+ "istkValidLbasDeltaToHighUrgency"
+ "istkValidLbasDeltaToMedUrgency"
+ "massScanLastDebugInfo"
+ "massScanStatus"
+ "numIdleStackDays"
+ "progTempDeltaHisto"
+ "purgeableBandCyclesHisto"
+ "purgeableBandCyclesHistoStart"
+ "purgeableVcurve"
+ "purgeableVcurveAtIdleStackSquareUpEnd"
+ "purgeableVcurveAtSlowGC"
+ "qosEventHighLatency"
+ "qosEventSmallReadLatency"
+ "sidebarLastValidWallTime"
+ "slowGcMustReasons"
+ "totalReadAmpAtBoot"
+ "unalignedPageReads"
+ "vcurveAtSlowGC"
- "cbdrAborts"
- "cbdrInvalidGrade"
- "cbdrNeedToRefresh"
- "cbdrNoNeedToRefresh"
- "cbdrNotEnoughReads"
- "cbdrRefreshGrades"
- "idleStackNandWritesPerRoundHigh"
- "idleStackNandWritesPerRoundLow"
- "idleStackNandWritesPerRoundMed"
- "idleStackNandWritesRoundHighIdx"
- "idleStackNandWritesRoundLowIdx"
- "idleStackNandWritesRoundMedIdx"
```
