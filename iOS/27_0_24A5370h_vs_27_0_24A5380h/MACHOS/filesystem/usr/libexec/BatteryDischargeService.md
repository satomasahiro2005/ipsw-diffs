## BatteryDischargeService

> `/usr/libexec/BatteryDischargeService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ab8` | `0x65c4` | **`+0x1b0c`** |
| `__TEXT.__oslogstring` | `0x405` | `0x81e` | **`+0x419`** |
| `__TEXT.__objc_methname` | `0x493` | `0x5f5` | **`+0x162`** |
| `__TEXT.__objc_stubs` | `0x2a0` | `0x400` | **`+0x160`** |
| `__DATA.__bss` | `0x100` | `0x200` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x1d8` | `0x298` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0x720` | `0x7e0` | **`+0xc0`** |
| `__TEXT.__const` | `0x23a` | `0x2e2` | **`+0xa8`** |
| `__DATA.__objc_data` | `0x328` | `0x3c0` | **`+0x98`** |
| `__TEXT.__constg_swiftt` | `0x23c` | `0x2d4` | **`+0x98`** |
| `__TEXT.__cstring` | `0x1ba` | `0x24a` | **`+0x90`** |
| `__DATA.__objc_const` | `0x710` | `0x790` | **`+0x80`** |
| `__DATA_CONST.__auth_got` | `0x398` | `0x3f8` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x180` | `0x1d8` | **`+0x58`** |
| `__TEXT.__swift5_reflstr` | `0xfd` | `0x14f` | **`+0x52`** |
| `__DATA.__data` | `0x2b0` | `0x2f0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x150` | `0x188` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0xcc` | `0xfc` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0xf6` | `0x118` | **`+0x22`** |
| `__TEXT.__swift5_capture` | `0x34` | `0x54` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x18` | `0x30` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x100` | `0x110` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x90` | `0x98` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x1b5` | `0x1bb` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x10` | `0x14` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-9.0.0.0.0
+14.0.0.0.0

+  - /System/Library/PrivateFrameworks/LowPowerMode.framework/LowPowerMode
+  - /System/Library/PrivateFrameworks/OSIntelligence.framework/OSIntelligence
+  - /System/Library/PrivateFrameworks/PowerExperience.framework/PowerExperience
+  - /System/Library/PrivateFrameworks/PowerUI.framework/PowerUI

-  Functions: 85
-  Symbols:   176
-  CStrings:  127
+  Functions: 108
+  Symbols:   190
+  CStrings:  162
Symbols:
+ _$s10Foundation22_convertErrorToNSErrorySo0E0Cs0C0_pF
+ _$sSS10FoundationE36_unconditionallyBridgeFromObjectiveCySSSo8NSStringCSgFZ
+ _$ss5ErrorP10FoundationE20localizedDescriptionSSvg
+ _OBJC_CLASS_$_ResourceHint
+ _OBJC_CLASS_$__OSIBLMState
+ _OBJC_CLASS_$__PMLowPowerMode
+ _kPMLPMSourceSettings
+ _objc_release_x28
+ _objc_retain_x22
+ _objc_retain_x25
+ _objc_retain_x26
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_getErrorValue
+ _swift_release_x20
+ _swift_retain_x20
- _$sytN
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "Adaptive Power (IBLM) already off; nothing to disable"
+ "Adaptive Power (IBLM) not supported on this device; skipping"
+ "BatteryDischargeService: forcing discharge load onto the battery"
+ "Could not disable charger inflow; refusing to start discharge"
+ "Could not take inflow-disable assertion; refusing to start discharge"
+ "Created inflow-disable assertion (ID: %u); running off battery"
+ "Disabled Adaptive Power (IBLM) for discharge run (was on)"
+ "Failed to create ResourceHint — Hot in Pocket mitigation will not be toggled during discharge"
+ "Failed to create inflow-disable assertion: %d"
+ "Failed to force power mode to normal: %s (domain=%s code=%ld)"
+ "Failed to restore power mode to %ld: %s (domain=%s code=%ld)"
+ "Failed to update ResourceHint to active state"
+ "Failed to update ResourceHint to inactive state"
+ "Failed to update ResourceHint to inactive state during deinit"
+ "Forced power mode to normal for discharge run (was %ld)"
+ "Power mode already normal; nothing to disable"
+ "Released inflow-disable assertion (ID: %u); restored charger inflow"
+ "Restored Adaptive Power (IBLM) to on"
+ "Restored power mode to %ld"
+ "client:setIBLMState:"
+ "code"
+ "dischargeHint"
+ "domain"
+ "getPowerMode"
+ "inflowDisableAssertionID"
+ "initWithResourceType:andState:"
+ "isIBLMCurrentlyEnabled"
+ "isIBLMSupported"
+ "priorIBLMEnabled"
+ "priorPowerMode"
+ "processName"
+ "setPowerMode:fromSource:withCompletion:"
+ "sharedInstance"
+ "updateState:"
+ "v20@?0B8@\"NSError\"12"
```
