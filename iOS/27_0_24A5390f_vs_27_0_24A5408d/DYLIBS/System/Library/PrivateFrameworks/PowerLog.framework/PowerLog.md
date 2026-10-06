## PowerLog

> `/System/Library/PrivateFrameworks/PowerLog.framework/PowerLog`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x23be` | `0x23f6` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x29a0` | `0x29c0` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x3a2d` | `0x3a4a` | **`+0x1d`** |
| `__TEXT.__const` | `0xf30` | `0xf28` | **`-0x8`** |
| `__TEXT.__text` | `0x1efa8` | `0x1efac` | **`+0x4`** |

### Other Changes

```diff

-3486.0.81.502.4
+3486.2.4.0.0

-  CStrings:  687
+  CStrings:  688
Functions:
~ sub_1b7fa1be8 -> sub_1b7f36be8 : 72 -> 76
~ _batteryUIIsEligibleForOptimizeBatteryPrompt : 424 -> 400
~ _PLBatteryUsageUIStringForResponseType : 548 -> 572
CStrings:
+ "OptimizeBatteryPromptEligibility"
+ "is Eligible for Optimize Battery Prompt: %d"
+ "optimizeBatteryPromptEligibility"
- "drainRate"
- "drainRate: %lf"
```
