## HealthBluetoothPeripheral

> `/System/Library/Health/Plugins/HealthBluetoothPeripheral.bundle/HealthBluetoothPeripheral`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e7b8` | `0x3e8c8` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x57dd` | `0x58a7` | **`+0xca`** |
| `__TEXT.__objc_methname` | `0x9b82` | `0x9c06` | **`+0x84`** |
| `__DATA_CONST.__cfstring` | `0x2260` | `0x22c0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x25e3` | `0x262c` | **`+0x49`** |
| `__TEXT.__objc_methtype` | `0x2e57` | `0x2e97` | **`+0x40`** |
| `__DATA.__objc_const` | `0x77e8` | `0x7810` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x6280` | `0x62a0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x3e44` | `0x3e5c` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x2260` | `0x2270` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x438` | `0x430` | **`-0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x90` | `0x98` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1088` | `0x1090` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x5a4` | `0x5a8` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0xad0` | `0xad4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  Functions: 1701
-  Symbols:   434
-  CStrings:  2649
+  Functions: 1704
+  Symbols:   433
+  CStrings:  2659
Symbols:
- _OBJC_CLASS_$_NSNotificationCenter
CStrings:
+ "%{public}@: Not enabling field detect"
+ "%{public}@: beginning field detect session"
+ "%{public}@: continuing with local pairing since device was ineligible for paired handoff. reason: %{public}@"
+ "%{public}@: enableFieldDetectSessionIfPermitted: _gymKitSettings.nfcPermission=%{public}@, isWorkoutAppAvailable:%{public}@"
+ "%{public}@: not permitting field detect events. Workout app not available"
+ "@\"NSNotificationCenter\""
+ "HBPNearFieldInterface+SupportsGymKit.m"
+ "_notificationCenter"
+ "appIsAvailable"
+ "apple-dev"
+ "initWithFirstPartyWorkoutAppAndLoggingCategory:"
+ "initWithNotificationCenter:"
+ "launchWorkoutAppIfNeededWithFitnessMachineSessionUUID:loggingCategory:"
+ "monitorDidDetectAppAvailabilityDidChange:appIsAvailable:"
+ "notificationCenter"
+ "notificationCenter != nil"
+ "v28@0:8@\"HDWorkoutAppStateMonitor\"16B24"
- "%{public}@: Not enabling field detect as it's not permitted: _gymKitSettings.nfcPermission=%{public}@"
- "%{public}@: device was ineligible for paired handoff. continuing with local pairing"
- "1"
- "defaultCenter"
- "initWithFirstPartyWorkoutApp"
- "launchWorkoutAppIfNeededWithFitnessMachineSessionUUID:"
- "removeObserver:name:object:"
```
