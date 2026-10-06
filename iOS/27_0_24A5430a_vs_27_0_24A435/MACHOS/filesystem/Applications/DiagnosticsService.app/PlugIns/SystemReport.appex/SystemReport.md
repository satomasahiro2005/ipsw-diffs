## SystemReport

> `/Applications/DiagnosticsService.app/PlugIns/SystemReport.appex/SystemReport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d99c` | `0x1f1d8` | **`+0x183c`** |
| `__DATA_CONST.__cfstring` | `0x5040` | `0x5700` | **`+0x6c0`** |
| `__DATA.__objc_const` | `0x2f58` | `0x35b0` | **`+0x658`** |
| `__TEXT.__cstring` | `0x3880` | `0x3cd4` | **`+0x454`** |
| `__DATA.__objc_data` | `0x14a0` | `0x1810` | **`+0x370`** |
| `__TEXT.__objc_methlist` | `0x1b44` | `0x1d4c` | **`+0x208`** |
| `__TEXT.__objc_stubs` | `0x4360` | `0x44e0` | **`+0x180`** |
| `__TEXT.__objc_classname` | `0x5c6` | `0x6de` | **`+0x118`** |
| `__TEXT.__objc_methname` | `0x3543` | `0x3659` | **`+0x116`** |
| `__TEXT.__oslogstring` | `0x2294` | `0x2358` | **`+0xc4`** |
| `__DATA.__objc_selrefs` | `0x12d0` | `0x1330` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x508` | `0x568` | **`+0x60`** |
| `__DATA_CONST.__objc_classlist` | `0x210` | `0x268` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x658` | `0x6a8` | **`+0x50`** |
| `__DATA_CONST.__objc_intobj` | `0x420` | `0x438` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xce0` | `0xcf0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x680` | `0x688` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x260` | `0x258` | **`-0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x120` | `0x128` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x98` | `0xa0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-  Functions: 615
-  Symbols:   327
-  CStrings:  1655
+  Functions: 656
+  Symbols:   336
+  CStrings:  1737
Symbols:
+ _IOMobileFramebufferGetMainDisplay
+ _IOMobileFramebufferGetSecondaryDisplay
+ _IOPSShippingChargeLimitGetState
+ _OBJC_CLASS_$_ComponentALS
+ _OBJC_CLASS_$_ComponentAccelerometer
+ _OBJC_CLASS_$_ComponentBatteryInternal
+ _OBJC_CLASS_$_ComponentDisplay
+ _OBJC_CLASS_$_ComponentGyro
+ _OBJC_METACLASS_$_ComponentALS
+ _OBJC_METACLASS_$_ComponentAccelerometer
+ _OBJC_METACLASS_$_ComponentBatteryInternal
+ _OBJC_METACLASS_$_ComponentDisplay
+ _OBJC_METACLASS_$_ComponentGyro
+ _objc_retain_x27
- _IOMobileFramebufferOpenByName
- _IOPSCopyPowerSourcesList
- _IOPSGetPowerSourceDescription
- _OBJC_CLASS_$_UIScreen
- _kAppleBatteryAuthClass
CStrings:
+ "AppleCamera"
+ "AppleChargerData"
+ "AppleSmartBatteryPack"
+ "Beta"
+ "Charger data is not serializable, omitting."
+ "ChargerAccumEfficiencyCount"
+ "ChargerAccumulatedEfficiency"
+ "ChargerData"
+ "ChargerEfficiency"
+ "ChargerHwIlimBackoffReason"
+ "ChargerIBUS"
+ "ChargerID"
+ "ChargerInhibitReason"
+ "ChargerPower"
+ "ChargerResetCounter"
+ "ChargerStatus"
+ "ChargerVBUS"
+ "ChargingCurrent"
+ "ChargingVoltage"
+ "ComponentALSInnerFirst"
+ "ComponentALSInnerSecond"
+ "ComponentALSPrimary"
+ "ComponentAccelerometerPrimary"
+ "ComponentAccelerometerSecondary"
+ "ComponentBatteryInternal2"
+ "ComponentCameraInnerFrontSuperWide"
+ "ComponentDisplayInner"
+ "ComponentDisplayPrimary"
+ "ComponentGyroPrimary"
+ "ComponentGyroSecondary"
+ "FrontCameraRenoModuleSerialNumString"
+ "ID"
+ "No charger data nodes published; skipping charger attributes."
+ "NotChargingReason"
+ "PMUConfiguration"
+ "PMUConfigured"
+ "RCAM"
+ "RebalanceHWBypassFETStatus"
+ "ReleaseType"
+ "ShipChargeLimitCompliant"
+ "ShipChargeLimitEnabled"
+ "ShipChargeLimitSupported"
+ "Shipping charge limit state not available (0x%x), skipping."
+ "SlowChargingReason"
+ "TimeChargingThermallyLimited"
+ "Tq,R,N"
+ "Unable to get physical presence state"
+ "VacVoltageLimit"
+ "_chargerDataNodes"
+ "_powerSourceNodePropertiesForBatteryIndex:"
+ "accel_1"
+ "addChargerDataToDictionary:"
+ "addShippingChargeLimitStateToDictionary:"
+ "aggregatedServiceBatteryFlags"
+ "aggregatedServiceBatteryWarning"
+ "als-md-mlb-serial-num"
+ "als-md-sensor-flex-serial-num"
+ "als-tb-sensor-flex-serial-num"
+ "als2a"
+ "als2b"
+ "authAncestorName"
+ "batteryAuthProperty:"
+ "batteryIndex"
+ "bml1"
+ "chargerCount"
+ "chargerIndex"
+ "chargers"
+ "compare:"
+ "control != kMesaFactoryPhysicalPresenceGetState || state"
+ "control < kMesaFactoryPhysicalPresenceCount"
+ "coverglass-serial-number-2"
+ "displayIndex"
+ "displays"
+ "getAuthProperty:"
+ "gyro_1"
+ "lowercaseString"
+ "mogul-display"
+ "mogul-display2"
+ "physicalPresenceState"
+ "q24@?0@\"NSDictionary\"8@\"NSDictionary\"16"
+ "raw-panel-serial-number-2"
+ "setPhysicalPresence -> err:0x%x\n"
+ "setPhysicalPresence(control:%d, state:%p)\n"
+ "shipChargeLimitCompliant"
+ "shipChargeLimitEnabled"
+ "shipChargeLimitSupported"
+ "sortUsingComparator:"
+ "substringFromIndex:"
+ "substringToIndex:"
- "Failed to retrieve power source description."
- "Failed to retrieve power sources list."
- "RawPanelSerialNumber"
- "deviceName"
- "displayConfiguration"
- "mainDisplay"
- "mainScreen"
```
