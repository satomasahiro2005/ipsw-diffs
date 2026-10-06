## ASPCarryLog

> `/usr/libexec/ASPCarryLog`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26698` | `0x27354` | **`+0xcbc`** |
| `__TEXT.__cstring` | `0x8864` | `0x8d9d` | **`+0x539`** |
| `__DATA_CONST.__got` | `0x1b0` | `0x1c0` | **`+0x10`** |

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
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-843.0.0.0.0
+847.0.0.0.0

-  CStrings:  2471
+  CStrings:  2526
Functions:
~ sub_1000144f0 : 64440 -> 67716
~ sub_1000246d8 -> sub_1000253a4 : 2224 -> 2228
~ sub_100025384 -> sub_100026054 : 1084 -> 1064
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
