## HealthMenstrualCycles

> `/System/Library/PrivateFrameworks/HealthMenstrualCycles.framework/HealthMenstrualCycles`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3fe6` | `0x4036` | **`+0x50`** |
| `__DATA_CONST.__const` | `0xfa8` | `0xfd0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x33e0` | `0x3400` | **`+0x20`** |
| `__TEXT.__text` | `0x2debc` | `0x2dec8` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x5d0` | `0x5c8` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2150` | `0x2148` | **`-0x8`** |

### Other Changes

```diff

-7027.0.67.2.1
+7027.0.72.2.5

-  Functions: 1337
-  Symbols:   2589
-  CStrings:  606
+  Functions: 1338
+  Symbols:   2590
+  CStrings:  608
Symbols:
+ ___62-[HKMCViewModelProvider _queue_runNotifyObserversOperationNow]_block_invoke
+ ___block_descriptor_40_e8_32s_e41_v16?0"<HKMCViewModelProviderObserver>"8ls32l8
- _OBJC_CLASS_$_NSHashTable
Functions:
~ -[HKMCViewModelProvider _initWithDataSource:cycleFactorsDataSource:analysisProvider:maximumActiveDuration:minimumBufferDuration:prefetchDuration:shouldFetchCycleFactors:calendarCache:queue:] : 724 -> 744
~ -[HKMCViewModelProvider registerObserver:] : 8 -> 100
~ -[HKMCViewModelProvider _queue_runNotifyObserversOperationNow] : 440 -> 328
+ ___62-[HKMCViewModelProvider _queue_runNotifyObserversOperationNow]_block_invoke
CStrings:
+ "HKMCViewModelProviderObservers"
+ "v16@?0@\"<HKMCViewModelProviderObserver>\"8"
```
