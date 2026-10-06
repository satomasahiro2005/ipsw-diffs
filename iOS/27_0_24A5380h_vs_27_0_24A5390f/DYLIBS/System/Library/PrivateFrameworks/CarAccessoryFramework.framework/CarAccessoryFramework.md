## CarAccessoryFramework

> `/System/Library/PrivateFrameworks/CarAccessoryFramework.framework/CarAccessoryFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10bed4` | `0x10cc10` | **`+0xd3c`** |
| `__AUTH_CONST.__objc_const` | `0x4fbe8` | `0x50188` | **`+0x5a0`** |
| `__TEXT.__objc_methlist` | `0x18e9c` | `0x1901c` | **`+0x180`** |
| `__AUTH_CONST.__cfstring` | `0xde00` | `0xdf20` | **`+0x120`** |
| `__DATA_CONST.__objc_arraydata` | `0xc168` | `0xc218` | **`+0xb0`** |
| `__AUTH.__objc_data` | `0x50` | `0xf0` | **`+0xa0`** |
| `__AUTH_CONST.__objc_dictobj` | `0x6630` | `0x66d0` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x7d18` | `0x7da0` | **`+0x88`** |
| `__TEXT.__cstring` | `0x7e6f` | `0x7ef1` | **`+0x82`** |
| `__TEXT.__oslogstring` | `0x3cb5` | `0x3d35` | **`+0x80`** |
| `__DATA.__data` | `0x4940` | `0x49a0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x26f8` | `0x2738` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3bb0` | `0x3bd0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xf00` | `0xf10` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xdc0` | `0xdd0` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x618` | `0x620` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x5b8` | `0x5c0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x7e8` | `0x7f0` | **`+0x8`** |

### Other Changes

```diff

-537.3.0.0.0
+540.1.0.0.0

-  Functions: 7734
-  Symbols:   13122
-  CStrings:  2178
+  Functions: 7764
+  Symbols:   13172
+  CStrings:  2188
Symbols:
+ +[CAFChargingSchedule observerProtocol]
+ +[CAFChargingSchedule serviceIdentifier]
+ +[CAFCurrentOwnerCharacteristic primaryCharacteristicFormat]
+ +[CAFCurrentOwnerCharacteristic secondaryCharacteristicFormats]
+ -[CAFCharging chargingScheduleService]
+ -[CAFCharging chargingSchedule]
+ -[CAFChargingSchedule _characteristicDidUpdate:fromGroupUpdate:]
+ -[CAFChargingSchedule addObserver:]
+ -[CAFChargingSchedule name]
+ -[CAFChargingSchedule registerObserver:]
+ -[CAFChargingSchedule registeredForTimeToStart]
+ -[CAFChargingSchedule removeObserver:]
+ -[CAFChargingSchedule timeToStartCharacteristic]
+ -[CAFChargingSchedule timeToStartInvalid]
+ -[CAFChargingSchedule timeToStartMeasurementRange]
+ -[CAFChargingSchedule timeToStartRange]
+ -[CAFChargingSchedule timeToStart]
+ -[CAFChargingSchedule unregisterObserver:]
+ -[CAFCurrentOwnerCharacteristic currentOwnerValue]
+ -[CAFCurrentOwnerCharacteristic formattedValue]
+ -[CAFCurrentOwnerCharacteristic setCurrentOwnerValue:]
+ -[CAFInteriorAmbientLights currentOwnerCharacteristic]
+ -[CAFInteriorAmbientLights currentOwner]
+ -[CAFInteriorAmbientLights hasCurrentOwner]
+ -[CAFInteriorAmbientLights registeredForCurrentOwner]
+ -[CAFInteriorAmbientLights setCurrentOwner:]
+ _CAFCharacteristicTypeCurrentOwner
+ _CAFCharacteristicTypeTimeToStart
+ _CAFServiceTypeChargingSchedule
+ _NSStringFromCurrentOwner
+ _OBJC_CLASS_$_CAFChargingSchedule
+ _OBJC_CLASS_$_CAFCurrentOwnerCharacteristic
+ _OBJC_METACLASS_$_CAFChargingSchedule
+ _OBJC_METACLASS_$_CAFCurrentOwnerCharacteristic
+ __OBJC_$_CLASS_METHODS_CAFChargingSchedule
+ __OBJC_$_CLASS_METHODS_CAFCurrentOwnerCharacteristic
+ __OBJC_$_INSTANCE_METHODS_CAFCar(CAFNowPlaying|Accessories)
+ __OBJC_$_INSTANCE_METHODS_CAFChargingSchedule
+ __OBJC_$_INSTANCE_METHODS_CAFCurrentOwnerCharacteristic
+ __OBJC_$_PROP_LIST_CAFChargingSchedule
+ __OBJC_$_PROP_LIST_CAFCurrentOwnerCharacteristic
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CAFChargingScheduleObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CAFChargingScheduleObserver
+ __OBJC_$_PROTOCOL_REFS_CAFChargingScheduleObserver
+ __OBJC_CLASS_RO_$_CAFChargingSchedule
+ __OBJC_CLASS_RO_$_CAFCurrentOwnerCharacteristic
+ __OBJC_LABEL_PROTOCOL_$_CAFChargingScheduleObserver
+ __OBJC_METACLASS_RO_$_CAFChargingSchedule
+ __OBJC_METACLASS_RO_$_CAFCurrentOwnerCharacteristic
+ __OBJC_PROTOCOL_$_CAFChargingScheduleObserver
+ __OBJC_PROTOCOL_REFERENCE_$_CAFChargingScheduleObserver
- __OBJC_$_INSTANCE_METHODS_CAFCar(Accessories|CAFNowPlaying)
CStrings:
+ "%{public}@ echo timeout after %.3fs: no confirming update received; discarding pending write, reverting to last confirmed value"
+ "0x000000001900000B"
+ "0x000000003600006E"
+ "0x000000004000000E"
+ "Accessory"
+ "ChargingSchedule"
+ "Controller"
+ "CurrentOwner"
+ "Scheduled"
+ "TimeToStart"
```
