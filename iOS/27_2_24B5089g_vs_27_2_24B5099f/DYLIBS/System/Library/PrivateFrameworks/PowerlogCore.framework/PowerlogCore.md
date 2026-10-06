## PowerlogCore

> `/System/Library/PrivateFrameworks/PowerlogCore.framework/PowerlogCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x6d120` | `0x6d320` | **`+0x200`** |
| `__DATA_CONST.__objc_arraydata` | `0x45f18` | `0x46078` | **`+0x160`** |
| `__TEXT.__cstring` | `0x43939` | `0x43a27` | **`+0xee`** |
| `__TEXT.__text` | `0xe9840` | `0xe98cc` | **`+0x8c`** |
| `__AUTH_CONST.__objc_dictobj` | `0xfd70` | `0xfd98` | **`+0x28`** |
| `__DATA.__bss` | `0x16a9` | `0x16b1` | **`+0x8`** |

### Other Changes

```diff

-3486.40.98.0.0
+3486.40.112.0.0

-  Functions: 4969
-  Symbols:   7274
-  CStrings:  15299
+  Functions: 4970
+  Symbols:   7276
+  CStrings:  15315
Symbols:
+ ___103-[PLEntryNotificationOperatorComposition initNotificationTimerWithWorkQueue:withMaxInterval:withBlock:]_block_invoke_2
+ _initNotificationTimerWithWorkQueue:withMaxInterval:withBlock:.onceToken
Functions:
~ -[PLEntryNotificationOperatorComposition initNotificationTimerWithWorkQueue:withMaxInterval:withBlock:] : 288 -> 236
~ ___103-[PLEntryNotificationOperatorComposition initNotificationTimerWithWorkQueue:withMaxInterval:withBlock:]_block_invoke : 84 -> 192
+ ___103-[PLEntryNotificationOperatorComposition initNotificationTimerWithWorkQueue:withMaxInterval:withBlock:]_block_invoke_2
CStrings:
+ "AccumSystemEffectiveTotalLoad"
+ "AccumSystemEffectiveTotalLoadCount"
+ "AccumulatedBatteryPower"
+ "BatteryPowerAccumulatorCount"
+ "DisplayID"
+ "PLAppTimeService_Aggregate_DisplayUsage"
+ "SystemEffectiveTotalLoad"
+ "ceH0"
+ "ceH2"
+ "ceHH"
+ "ceHL"
+ "ceHr"
+ "ceHy"
+ "ceHz"
+ "ceh4"
+ "ceh6"
```
