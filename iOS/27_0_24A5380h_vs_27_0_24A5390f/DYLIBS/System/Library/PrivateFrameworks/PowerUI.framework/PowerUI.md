## PowerUI

> `/System/Library/PrivateFrameworks/PowerUI.framework/PowerUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd99d0` | `0xd9c7c` | **`+0x2ac`** |
| `__TEXT.__objc_methlist` | `0x1d6d4` | `0x1d71c` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0xf09d` | `0xf0da` | **`+0x3d`** |
| `__DATA_CONST.__objc_selrefs` | `0x5e40` | `0x5e78` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x39f68` | `0x39f98` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xdba0` | `0xdbc0` | **`+0x20`** |
| `__TEXT.__cstring` | `0xf77a` | `0xf790` | **`+0x16`** |
| `__TEXT.__const` | `0x6c0` | `0x6d0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x3ecc` | `0x3ed0` | **`+0x4`** |

### Other Changes

```diff

-753.0.10.0.0
+753.0.15.0.0

-  Functions: 10642
-  Symbols:   15759
-  CStrings:  3202
+  Functions: 10650
+  Symbols:   15768
+  CStrings:  3204
Symbols:
+ +[PowerUIRuntimeAwarenessNotifier _ppsMaxRetryAttempts]
+ +[PowerUISmartChargeUtilities batteryStateAvailableWithContext:]
+ -[PowerUICECAlgoControlManager clearChargePolicy]
+ -[PowerUIDemoCECManager batteryContextRetryPending]
+ -[PowerUIDemoCECManager scheduleBatteryContextRetry]
+ -[PowerUIDemoCECManager setBatteryContextRetryPending:]
+ GCC_except_table38
+ GCC_except_table42
+ GCC_except_table48
+ GCC_except_table53
+ GCC_except_table57
+ GCC_except_table80
+ _OBJC_IVAR_$_PowerUIDemoCECManager._batteryContextRetryPending
+ ___52-[PowerUIDemoCECManager scheduleBatteryContextRetry]_block_invoke
- GCC_except_table37
- GCC_except_table56
- GCC_except_table79
- GCC_except_table85
- GCC_except_table89
CStrings:
+ "Battery context retry"
+ "Battery-state context not available yet; skipping evaluation for trigger: %@"
+ "Total time computed (%.0f hrs) is below the %.0f hr minimum coverage. Data may be incomplete or corrupted."
- "Total time computed (%.0f hrs) differs from expected 24 hours by %.0f hrs (>2 hours). Data may be incomplete or corrupted."
```
