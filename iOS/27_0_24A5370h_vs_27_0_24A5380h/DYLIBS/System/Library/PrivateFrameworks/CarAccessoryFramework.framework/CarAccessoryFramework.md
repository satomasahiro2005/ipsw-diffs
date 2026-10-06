## CarAccessoryFramework

> `/System/Library/PrivateFrameworks/CarAccessoryFramework.framework/CarAccessoryFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__objc_data` | `0x5b90` | `0x8930` | **`+0x2da0`** |
| `__AUTH.__objc_data` | `0x2da0` | `0x50` | **`-0x2d50`** |
| `__TEXT.__text` | `0x10a3cc` | `0x10bed4` | **`+0x1b08`** |
| `__AUTH_CONST.__objc_const` | `0x4f528` | `0x4fbe8` | **`+0x6c0`** |
| `__DATA_CONST.__objc_arraydata` | `0xbc98` | `0xc168` | **`+0x4d0`** |
| `__TEXT.__objc_methlist` | `0x18c44` | `0x18e9c` | **`+0x258`** |
| `__AUTH_CONST.__objc_dictobj` | `0x64a0` | `0x6630` | **`+0x190`** |
| `__DATA.__data` | `0x48e0` | `0x4940` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x7cc8` | `0x7d18` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x3b60` | `0x3bb0` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0xddc0` | `0xde00` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x3c7c` | `0x3cb5` | **`+0x39`** |
| `__DATA_CONST.__const` | `0x26c8` | `0x26f8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x7e43` | `0x7e6f` | **`+0x2c`** |
| `__DATA.__bss` | `0x3e0` | `0x3d0` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x118` | `0x128` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xef8` | `0xf00` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xdb8` | `0xdc0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x610` | `0x618` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x5b0` | `0x5b8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x7e0` | `0x7e8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x680` | `0x684` | **`+0x4`** |

### Other Changes

```diff

-534.3.0.0.0
+537.3.0.0.0

-  Functions: 7693
-  Symbols:   13066
-  CStrings:  2175
+  Functions: 7734
+  Symbols:   13122
+  CStrings:  2178
Symbols:
+ +[CAFButtonActionStatusItem observerProtocol]
+ +[CAFButtonActionStatusItem serviceIdentifier]
+ -[CAFASCTree nightModeByDisplayID]
+ -[CAFBluetoothStatus buttonActionCharacteristic]
+ -[CAFBluetoothStatus buttonAction]
+ -[CAFBluetoothStatus hasButtonAction]
+ -[CAFBluetoothStatus registeredForButtonAction]
+ -[CAFBluetoothStatus setButtonAction:]
+ -[CAFButtonActionStatusItem _characteristicDidUpdate:fromGroupUpdate:]
+ -[CAFButtonActionStatusItem addObserver:]
+ -[CAFButtonActionStatusItem buttonActionCharacteristic]
+ -[CAFButtonActionStatusItem buttonAction]
+ -[CAFButtonActionStatusItem name]
+ -[CAFButtonActionStatusItem registerObserver:]
+ -[CAFButtonActionStatusItem registeredForButtonAction]
+ -[CAFButtonActionStatusItem removeObserver:]
+ -[CAFButtonActionStatusItem setButtonAction:]
+ -[CAFButtonActionStatusItem unregisterObserver:]
+ -[CAFCellularStatus buttonActionCharacteristic]
+ -[CAFCellularStatus buttonAction]
+ -[CAFCellularStatus hasButtonAction]
+ -[CAFCellularStatus registeredForButtonAction]
+ -[CAFCellularStatus setButtonAction:]
+ -[CAFCurrentUserStatus buttonActionCharacteristic]
+ -[CAFCurrentUserStatus buttonAction]
+ -[CAFCurrentUserStatus hasButtonAction]
+ -[CAFCurrentUserStatus registeredForButtonAction]
+ -[CAFCurrentUserStatus setButtonAction:]
+ -[CAFStatusIndicators buttonActionStatusItemServices]
+ -[CAFStatusIndicators buttonActionStatusItems]
+ -[CAFWiFiStatus buttonActionCharacteristic]
+ -[CAFWiFiStatus buttonAction]
+ -[CAFWiFiStatus hasButtonAction]
+ -[CAFWiFiStatus registeredForButtonAction]
+ -[CAFWiFiStatus setButtonAction:]
+ -[CAFWirelessChargerStatus buttonActionCharacteristic]
+ -[CAFWirelessChargerStatus buttonAction]
+ -[CAFWirelessChargerStatus hasButtonAction]
+ -[CAFWirelessChargerStatus registeredForButtonAction]
+ -[CAFWirelessChargerStatus setButtonAction:]
+ _CAFServiceTypeButtonActionStatusItem
+ _OBJC_CLASS_$_CAFButtonActionStatusItem
+ _OBJC_IVAR_$_CAFASCTree._nightModeByDisplayID
+ _OBJC_METACLASS_$_CAFButtonActionStatusItem
+ __OBJC_$_CLASS_METHODS_CAFButtonActionStatusItem
+ __OBJC_$_INSTANCE_METHODS_CAFButtonActionStatusItem
+ __OBJC_$_PROP_LIST_CAFButtonActionStatusItem
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CAFButtonActionStatusItemObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CAFButtonActionStatusItemObserver
+ __OBJC_$_PROTOCOL_REFS_CAFButtonActionStatusItemObserver
+ __OBJC_CLASS_RO_$_CAFButtonActionStatusItem
+ __OBJC_LABEL_PROTOCOL_$_CAFButtonActionStatusItemObserver
+ __OBJC_METACLASS_RO_$_CAFButtonActionStatusItem
+ __OBJC_PROTOCOL_$_CAFButtonActionStatusItemObserver
+ __OBJC_PROTOCOL_REFERENCE_$_CAFButtonActionStatusItemObserver
+ ___block_descriptor_80_e8_32s40s48s56s64s72s_e15_v32?08Q16^B24ls32l8s40l8s48l8s56l8s64l8s72l8
CStrings:
+ "0x0000000016100009"
+ "ButtonActionStatusItem"
+ "[NightModeSeed] parsed displayID=%{public}@ nightMode=%@"
```
