## PowerUI

> `/System/Library/PrivateFrameworks/PowerUI.framework/PowerUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd980c` | `0xd99d0` | **`+0x1c4`** |
| `__AUTH.__objc_data` | `0x1bd0` | `0x1b30` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0xaa0` | `0xb40` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0x598` | `0x5e0` | **`+0x48`** |
| `__TEXT.__cstring` | `0xf733` | `0xf77a` | **`+0x47`** |
| `__AUTH_CONST.__cfstring` | `0xdb60` | `0xdba0` | **`+0x40`** |
| `__DATA.__bss` | `0xf8` | `0xc8` | **`-0x30`** |
| `__DATA_DIRTY.__bss` | `0x208` | `0x238` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1700` | `0x1720` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2200` | `0x2208` | **`+0x8`** |

### Other Changes

```diff

-753.0.5.0.0
+753.0.10.0.0

-  Functions: 10641
-  Symbols:   15757
-  CStrings:  3200
+  Functions: 10642
+  Symbols:   15759
+  CStrings:  3202
Symbols:
+ ___94-[PowerUIRuntimeAwarenessNotifier reportPredictionResultWithPrediction:triggered:modelTypeID:]_block_invoke
+ ___block_descriptor_57_e19_"NSDictionary"8?0l
Functions:
~ -[PowerUIDemoCECManager handlePauseChargingAboveMaxSOC:] : 444 -> 440
~ -[PowerUIRuntimeAwarenessNotifier reportPredictionResultWithPrediction:triggered:modelTypeID:] : 316 -> 456
+ ___94-[PowerUIRuntimeAwarenessNotifier reportPredictionResultWithPrediction:triggered:modelTypeID:]_block_invoke
CStrings:
+ "BatteryLevel"
+ "com.apple.das.smartcharging.runtimeawarenessnotifications"
```
