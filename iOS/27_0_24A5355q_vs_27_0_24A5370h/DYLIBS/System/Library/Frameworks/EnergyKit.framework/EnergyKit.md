## EnergyKit

> `/System/Library/Frameworks/EnergyKit.framework/EnergyKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc8580` | `0xc8b0c` | **`+0x58c`** |
| `__TEXT.__oslogstring` | `0xcac` | `0xcfc` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x7320` | `0x7348` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0xd48` | `0xd58` | **`+0x10`** |
| `__DATA.__data` | `0x2720` | `0x2730` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x13e4` | `0x13f4` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x38c8` | `0x38d8` | **`+0x10`** |

### Other Changes

```diff

-471.0.0.0.2
+481.0.0.0.0

-  Functions: 4916
-  Symbols:   12307
-  CStrings:  182
+  Functions: 4920
+  Symbols:   12315
+  CStrings:  183
Symbols:
+ _$s17EnergyKitInternal11RateLimiterV18defaultDailyBudgetSivgZ
+ _$sSo12NSUnitEnergyC0B3KitEACC14milliwattHoursABvgZTm
+ _$sSo12NSUnitEnergyC0B3KitEACC9wattHoursABvgZ
+ _$sSo12NSUnitEnergyC0B3KitEACC9wattHoursABvpZ
+ _$sSo12NSUnitEnergyC0B3KitEACC9wattHoursABvpZMV
+ _$sSo12NSUnitEnergyC0B3KitEACC9wattHours_WZ
+ _$sSo12NSUnitEnergyC0B3KitEACC9wattHours_Wz
+ ___swift_closure_destructor.12Tm
+ _swift_retain_x28
- ___swift_closure_destructor.10Tm
CStrings:
+ "[LoadEventOperations] Refusing batch of %ld events; exceeds daily budget"
```
