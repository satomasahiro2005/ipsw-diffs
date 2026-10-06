## Charge

> `/Applications/Charge.app/Charge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fc04` | `0x24b44` | **`+0x4f40`** |
| `__TEXT.__const` | `0x2904` | `0x3494` | **`+0xb90`** |
| `__TEXT.__swift5_typeref` | `0x35b0` | `0x3c96` | **`+0x6e6`** |
| `__DATA.__data` | `0x1d08` | `0x20f8` | **`+0x3f0`** |
| `__DATA.__objc_data` | `0xcc0` | `0x938` | **`-0x388`** |
| `__DATA.__bss` | `0x18a0` | `0x1be0` | **`+0x340`** |
| `__TEXT.__constg_swiftt` | `0x116c` | `0xf14` | **`-0x258`** |
| `__DATA_CONST.__const` | `0xf68` | `0x11b8` | **`+0x250`** |
| `__TEXT.__objc_methname` | `0x209f` | `0x22e7` | **`+0x248`** |
| `__DATA.__objc_const` | `0x1630` | `0x1808` | **`+0x1d8`** |
| `__TEXT.__swift5_reflstr` | `0x7c8` | `0x998` | **`+0x1d0`** |
| `__TEXT.__swift5_fieldmd` | `0x8f4` | `0xa14` | **`+0x120`** |
| `__TEXT.__objc_stubs` | `0xc40` | `0xd40` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x708` | `0x7f8` | **`+0xf0`** |
| `__DATA_CONST.__got` | `0x420` | `0x500` | **`+0xe0`** |
| `__TEXT.__objc_classname` | `0x425` | `0x4b5` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x1530` | `0x15a0` | **`+0x70`** |
| `__DATA_CONST.__auth_ptr` | `0x688` | `0x6e8` | **`+0x60`** |
| `__TEXT.__swift5_assocty` | `0x240` | `0x2a0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x9b8` | `0xa08` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x768` | `0x7b0` | **`+0x48`** |
| `__DATA_CONST.__auth_got` | `0xaa0` | `0xad8` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x1224` | `0x1254` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0x78` | `0xa0` | **`+0x28`** |
| `__TEXT.__cstring` | `0x63f` | `0x657` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x84` | `0x98` | **`+0x14`** |
| `__DATA_CONST.__objc_protolist` | `0x128` | `0x138` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x9c` | `0xac` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0xb8` | `0xc4` | **`+0xc`** |
| `__TEXT.__oslogstring` | `0xc` | `0x15` | **`+0x9`** |
| `__DATA.__common` | `0x30` | `0x38` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x78` | `0x80` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x98` | `0xa0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-342.1.0.0.0
+351.2.0.0.0

-  Functions: 785
-  Symbols:   635
-  CStrings:  494
+  Functions: 977
+  Symbols:   653
+  CStrings:  531
Symbols:
+ _$s10Foundation4DateV1goiySbAC_ACtFZ
+ _$s10Foundation4DateVMn
+ _$s10Foundation8CalendarV4date8byAdding5value2to18wrappingComponentsAA4DateVSgAC9ComponentO_SiAJSbtF
+ _$s10Foundation8CalendarV9ComponentO3dayyA2EmFWC
+ _$s10Foundation8CalendarV9ComponentOMa
+ _$s7SwiftUI17VerticalAlignmentV3topACvgZ
+ _$s7SwiftUI18LocalizedStringKeyVMn
+ _$s7SwiftUI23_GeometryActionModifierVMn
+ _$s7SwiftUI23_GeometryActionModifierVyxGAA04ViewE0AAMc
+ _$s7SwiftUI4FontV15monospacedDigitACyF
+ _$s7SwiftUI4FontV4bodyACvgZ
+ _$s7SwiftUI4FontV6weightyA2C6WeightVF
+ _$sBi8_WV
+ _$sSiSHsWP
+ _$sSiSZsMc
+ _$sSiSxsWP
+ _$sSnyxGSksSxRzSZ6StrideRpzrlMc
+ _$sSo16CAFChargingStateV10CAFCombineE11descriptionSSvg
+ _$ss23CustomStringConvertibleP11descriptionSSvgTj
+ _$ss5UInt8VN
+ _$ss5UInt8Vs23CustomStringConvertiblesWP
+ _objc_retain_x25
+ _swift_cvw_enumFn_getEnumTag
+ _swift_retain_n
- _$s7SwiftUI13GeometryProxyVMa
- _$s7SwiftUI13GeometryProxyVMn
- _$s7SwiftUI4FontV8footnoteACvgZ
- _$s7SwiftUI4FontV8headlineACvgZ
- _OBJC_CLASS_$_CAFMinimumChargingLevel
- _swift_retain_x23
CStrings:
+ "Asset Library ChargeAssetConfig received "
+ "Asset Library received"
+ "CAFBatteryRemainingRangeObserver"
+ "CHARGE_LIMIT_LABEL"
+ "CHARGE_TIME_LABEL"
+ "CHARGING_POWER_LABEL"
+ "CURRENT_RANGE_LABEL"
+ "Charge.ChargeCoordinator"
+ "Charge1"
+ "Charge2"
+ "Charge3"
+ "Charge4"
+ "Charge5"
+ "Charge6"
+ "Charge7"
+ "Charge8"
+ "ChargeCAFManager deinitted"
+ "ChargeCAFManager init"
+ "ChargeCoordinator init"
+ "DISCHARGE_LIMIT_LABEL"
+ "DISCHARGE_POWER_LABEL"
+ "DISCHARGE_TIME_LABEL"
+ "[CHARGE] %s: %ld  %s"
+ "_TtC6Charge17ChargeAssetConfig"
+ "_TtC6Charge17ChargeCoordinator"
+ "_assetConfig"
+ "_batteryLevel"
+ "_batteryRangeText"
+ "_chargeCoordinator"
+ "_chargeTimeText"
+ "_chargingModeIdentifier"
+ "_chargingState"
+ "_chargingTime"
+ "_clusterTemplate"
+ "_completedFrom"
+ "_currentLevelText"
+ "_remainingTimeText"
+ "_state"
+ "_targetChargingLevel"
+ "assetConfigCancellables"
+ "batteryRemainingRange"
+ "batteryRemainingRangeService:didUpdateHidden:"
+ "carDidUpdateAccessories"
+ "chargeModel"
+ "connecting to battery level ..."
+ "connecting to battery remaining range ..."
+ "connecting to charging ..."
+ "connecting to minimum charging level ..."
+ "connecting to remaining range ..."
+ "connecting to target charging level ..."
+ "elapsedTime"
+ "elapsedTimeInvalid"
+ "hidden"
+ "initWithBackingStore:"
+ "initWithDomain:verb:parametersByName:"
+ "initWithIdentifier:backingStore:"
+ "initWithPropertiesByName:"
+ "lastEnergyFlowState"
+ "receivedAllValues false"
+ "receivedAllValues true"
+ "refresh chargingState="
+ "unexpected chargingState "
+ "v28@0:8@\"CAFBatteryRemainingRange\"16B24"
- "%s: %ld  %s"
- "Charge.ChargeModel"
- "SCHEDULE_SCHEDULED_DATE"
- "[CHARGE] - Asset Library ChargeAppConfig received "
- "[CHARGE] - Asset Library received"
- "[CHARGE] - ChargeCAFManager deinitted"
- "[CHARGE] - ChargeCAFManager init"
- "[CHARGE] - ChargeModel init"
- "[CHARGE] - Missing  batteryLevel current value"
- "[CHARGE] carDidUpdateAccessories"
- "[CHARGE] connecting to battery level ..."
- "[CHARGE] connecting to charging ..."
- "[CHARGE] connecting to minimum charging level ..."
- "[CHARGE] connecting to remaining range ..."
- "[CHARGE] connecting to target charging level ..."
- "[CHARGE] currentCar "
- "[CHARGE] receivedAllValues false"
- "[CHARGE] receivedAllValues true"
- "_TtC6Charge15ChargeAppConfig"
- "_appConfig"
- "_isCharging"
- "_mode"
- "_model"
- "_scheduleModel"
- "appConfigCancellables"
- "batteryLevelService(_:didUpdateBatteryLevel:)"
```
