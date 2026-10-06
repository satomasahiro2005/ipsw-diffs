## dasd

> `/usr/libexec/dasd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17c52c` | `0x17c858` | **`+0x32c`** |
| `__TEXT.__objc_methname` | `0x2ed55` | `0x2ee35` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x172e9` | `0x17379` | **`+0x90`** |
| `__DATA_CONST.__cfstring` | `0x11c20` | `0x11ca0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x10806` | `0x10886` | **`+0x80`** |
| `__DATA.__objc_const` | `0x34420` | `0x34450` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x2250` | `0x2280` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x1343c` | `0x1346c` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x1b520` | `0x1b540` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x9e88` | `0x9ea0` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x1138` | `0x1150` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xe58` | `0xe50` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1650` | `0x1654` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2467.40.41.0.0
+2467.40.47.0.0

-  Functions: 8441
-  Symbols:   1020
-  CStrings:  12573
+  Functions: 8447
+  Symbols:   1023
+  CStrings:  12585
Symbols:
+ _IOIteratorNext
+ _IORegistryEntryCreateCFProperty
+ _IOServiceGetMatchingServices
CStrings:
+ "%s unavailable across all AppleSmartBatteryPack nodes"
+ "%{public}@: %{public}@ is not present in the list of %lu foregrounded applications: %@"
+ "(unknown)"
+ "AppleChargerData"
+ "AppleSmartBatteryPack"
+ "BatteryData"
+ "BatteryTemperatureReader returning value %ld (centi-C)"
+ "Foregrounded App Count"
+ "No match for AppleSmartBatteryPack IOService"
+ "TB,N,V_disableSpecialCasedThermalPolicyForDuo"
+ "Unable to get valid battery temperature from AppleSmartBattery"
+ "VirtualTemperature"
+ "_disableSpecialCasedThermalPolicyForDuo"
+ "batteryTemperatureReader"
+ "disableSpecialCasedThermalPolicyForDuo"
+ "maxBatteryTemperatureAcrossPacks"
+ "notChargingReasonUnionAcrossPacks"
+ "setDisableSpecialCasedThermalPolicyForDuo:"
- "%{public}@: Foregrounded apps (%@) don't include expected identifier: %@"
- "BatteryTemperatureReader returning value %@"
- "Foregrounded Apps"
- "Temperature"
- "Unable to get valid battery temperature: %@"
- "batteryTemperatureKey"
```
