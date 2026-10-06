## powerexperienced

> `/usr/libexec/powerexperienced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a5b4` | `0x1a93c` | **`+0x388`** |
| `__TEXT.__oslogstring` | `0x2f7e` | `0x308e` | **`+0x110`** |
| `__TEXT.__objc_methname` | `0x4060` | `0x414c` | **`+0xec`** |
| `__TEXT.__objc_stubs` | `0x3820` | `0x38e0` | **`+0xc0`** |
| `__DATA.__objc_const` | `0x5680` | `0x56e0` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0x12e0` | `0x1340` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x2334` | `0x237c` | **`+0x48`** |
| `__TEXT.__cstring` | `0x12ab` | `0x12f1` | **`+0x46`** |
| `__TEXT.__unwind_info` | `0x710` | `0x748` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x1108` | `0x1138` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x178` | `0x188` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x260` | `0x268` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x8d0` | `0x8d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-166.0.0.0.0
+168.0.0.0.0

-  Functions: 829
+  Functions: 835

-  CStrings:  1399
+  CStrings:  1416
CStrings:
+ "AcceleratedCharging"
+ "AcceleratedChargingMode is active"
+ "C!R"
+ "Discharge in progress - not applying any power target mitigations"
+ "DischargeInProgress"
+ "Resetting Accelerated Charging Background and Utility Power Budgets"
+ "Setting Accelerated Charging Background and Utility Power Budgets %.2f and %.2f"
+ "Tf,V_acmBgPowerTarget"
+ "Tf,V_acmUtilityPowerTarget"
+ "_acmBgPowerTarget"
+ "_acmUtilityPowerTarget"
+ "acmBgPowerTarget"
+ "acmUtilityPowerTarget"
+ "evaluatePowerMode: %@: %d display %d, carPlaySession %d, nFCSession %d, audioSession %d, sleepInProgress %d, wakeInProgress %d, onenessSession %d, siriAudio %d, siriRemoteSession %d, siriLocalSession %d, assistantUI %d, fitnessIntelligence %d, dataMigrationInProgress %d, dischargeInProgress %d, usbDeviceMode %d, pluggedIn %d (allowOnCharger: %d)"
+ "isAcceleratedChargingActive"
+ "kTinkerExtendedBatteryContext"
+ "setAcmBgPowerTarget:"
+ "setAcmUtilityPowerTarget:"
+ "updateACMBGUtilityPowerTargets:"
- "3!R"
- "evaluatePowerMode: %@: %d display %d, carPlaySession %d, nFCSession %d, audioSession %d, sleepInProgress %d, wakeInProgress %d, onenessSession %d, siriAudio %d, siriRemoteSession %d, siriLocalSession %d, assistantUI %d, fitnessIntelligence %d, dataMigrationInProgress %d, usbDeviceMode %d, pluggedIn %d (allowOnCharger: %d)"
```
