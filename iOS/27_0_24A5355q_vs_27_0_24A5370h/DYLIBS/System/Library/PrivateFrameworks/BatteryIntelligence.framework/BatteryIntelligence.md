## BatteryIntelligence

> `/System/Library/PrivateFrameworks/BatteryIntelligence.framework/BatteryIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5be4` | `0x5bcc` | **`-0x18`** |

### Other Changes

```diff

-208.0.0.0.0
+214.0.0.0.1
Functions:
~ -[BIBatteryAnalysisClient initWithTargets:trackAccessoryEstimates:] : 1616 -> 1612
~ ___51-[BIBatteryAnalysisClient updateAccessoryEstimates]_block_invoke.117 : 468 -> 464
~ -[BIBatteryAnalysisClient accessoryEstimatesWithError:] : 1300 -> 1296
~ -[BIBatteryAnalysisClient accessoryEstimatesFromCache:] : 1248 -> 1244
~ -[BIBatteryAnalysisClient dealloc] : 480 -> 476
~ +[BIBatteryAnalysisSharedResources areTargetsValid:] : 292 -> 288
```
