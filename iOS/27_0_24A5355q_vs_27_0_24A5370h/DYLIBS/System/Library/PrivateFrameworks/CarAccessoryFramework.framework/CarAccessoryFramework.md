## CarAccessoryFramework

> `/System/Library/PrivateFrameworks/CarAccessoryFramework.framework/CarAccessoryFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10a210` | `0x10a3cc` | **`+0x1bc`** |
| `__AUTH_CONST.__objc_const` | `0x4f480` | `0x4f528` | **`+0xa8`** |
| `__AUTH.__objc_data` | `0x2d50` | `0x2da0` | **`+0x50`** |
| `__DATA_CONST.__objc_arraydata` | `0xbc48` | `0xbc98` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x18c04` | `0x18c44` | **`+0x40`** |
| `__AUTH_CONST.__objc_intobj` | `0x678` | `0x690` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x7cb8` | `0x7cc8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3b50` | `0x3b60` | **`+0x10`** |
| `__TEXT.__cstring` | `0x7e4e` | `0x7e43` | **`-0xb`** |
| `__DATA_CONST.__got` | `0xef0` | `0xef8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xdb0` | `0xdb8` | **`+0x8`** |

### Other Changes

```diff

-531.2.1.0.0
+534.3.0.0.0

-  Functions: 7686
-  Symbols:   13051
+  Functions: 7693
+  Symbols:   13066
Symbols:
+ +[CAFTemporaryContentChangedControl controlIdentifier]
+ -[CAFDimensionManager vehicleFuelVolumeUnit]
+ -[CAFRequestTemporaryContent hasTemporaryContentChanged]
+ -[CAFRequestTemporaryContent registeredForTemporaryContentChanged]
+ -[CAFRequestTemporaryContent temporaryContentChangedControl]
+ -[CAFRequestTemporaryContent temporaryContentChangedWithOn:temporaryContentURL:completion:]
+ -[CAFTemporaryContentChangedControl temporaryContentChangedWithOn:temporaryContentURL:completion:]
+ -[CAFTrip fuelConsumptionCharacteristic]
+ -[CAFTrip fuelConsumptionInvalid]
+ -[CAFTrip fuelConsumptionMeasurementRange]
+ -[CAFTrip fuelConsumptionRange]
+ -[CAFTrip fuelConsumption]
+ -[CAFTrip hasFuelConsumption]
+ -[CAFTrip registeredForFuelConsumption]
+ _CAFCharacteristicTypeFuelConsumption
+ _CAFControlTypeTemporaryContentChanged
+ _CARPKeyTemporaryContentChangedOn
+ _CARPKeyTemporaryContentChangedTemporaryContentURL
+ _OBJC_CLASS_$_CAFTemporaryContentChangedControl
+ _OBJC_METACLASS_$_CAFTemporaryContentChangedControl
+ __OBJC_$_CLASS_METHODS_CAFTemporaryContentChangedControl
+ __OBJC_$_INSTANCE_METHODS_CAFTemporaryContentChangedControl
+ __OBJC_CLASS_RO_$_CAFTemporaryContentChangedControl
+ __OBJC_METACLASS_RO_$_CAFTemporaryContentChangedControl
+ ___91-[CAFRequestTemporaryContent temporaryContentChangedWithOn:temporaryContentURL:completion:]_block_invoke
+ ___98-[CAFTemporaryContentChangedControl temporaryContentChangedWithOn:temporaryContentURL:completion:]_block_invoke
- -[CAFButtonSetting hasHeartbeatFrequency]
- -[CAFButtonSetting hasSupportsPressAndHold]
- -[CAFButtonSetting heartbeatFrequencyCharacteristic]
- -[CAFButtonSetting heartbeatFrequencyRange]
- -[CAFButtonSetting heartbeatFrequency]
- -[CAFButtonSetting registeredForSupportsPressAndHold]
- -[CAFButtonSetting registeredForheartbeatFrequency]
- -[CAFButtonSetting supportsPressAndHoldCharacteristic]
- -[CAFButtonSetting supportsPressAndHold]
- _CAFCharacteristicTypeSupportsPressAndHold
- _CAFCharacteristicTypeheartbeatFrequency
CStrings:
+ "0x0000000035000020"
+ "0x0000000037000016"
+ "TemporaryContentChanged"
+ "on"
+ "temporaryContentURL"
- "0x000000003600006E"
- "0x000000003600006F"
- "PressedAndHolding"
- "SupportsPressAndHold"
- "heartbeatFrequency"
```
