## HealthMenstrualCycles

> `/System/Library/PrivateFrameworks/HealthMenstrualCycles.framework/HealthMenstrualCycles`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f140` | `0x2f2f0` | **`+0x1b0`** |
| `__AUTH.__objc_data` | `0x550` | `0x460` | **`-0xf0`** |
| `__DATA_DIRTY.__objc_data` | `0x9b0` | `0xaa0` | **`+0xf0`** |
| `__AUTH_CONST.__objc_const` | `0x68c0` | `0x6920` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x37d4` | `0x380c` | **`+0x38`** |
| `__DATA.__data` | `0xbe8` | `0xbc0` | **`-0x28`** |
| `__DATA_DIRTY.__data` | `—` | `0x28` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x3420` | `0x3440` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x2580` | `0x259d` | **`+0x1d`** |
| `__DATA_CONST.__objc_selrefs` | `0x2160` | `0x2178` | **`+0x18`** |
| `__TEXT.__const` | `0x77c` | `0x78c` | **`+0x10`** |
| `__TEXT.__cstring` | `0x4046` | `0x4056` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x488` | `0x490` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd00` | `0xd08` | **`+0x8`** |

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

-  Functions: 1372
-  Symbols:   2621
-  CStrings:  609
+  Functions: 1377
+  Symbols:   2628
+  CStrings:  610
Symbols:
+ -[HKMCAnalysisQuery asOfDayIndex]
+ -[HKMCAnalysisQuery initWithAsOfDayIndex:needsCycles:updateHandler:]
+ -[HKMCAnalysisQueryConfiguration .cxx_destruct]
+ -[HKMCAnalysisQueryConfiguration asOfDayIndex]
+ -[HKMCAnalysisQueryConfiguration setAsOfDayIndex:]
+ _OBJC_IVAR_$_HKMCAnalysisQuery._asOfDayIndex
+ _OBJC_IVAR_$_HKMCAnalysisQueryConfiguration._asOfDayIndex
CStrings:
+ "AsOfDayIndex"
+ "[%{public}@:%{public}@] Configured with forced analysis: %{public}@, user initiated: %{public}@, needs initial result: %{public}@, needs cycles: %{public}@, as of day index: %{public}@"
- "[%{public}@:%{public}@] Configured with forced analysis: %{public}@, user initiated: %{public}@, needs initial result: %{public}@, needs cycles: %{public}@"
```
