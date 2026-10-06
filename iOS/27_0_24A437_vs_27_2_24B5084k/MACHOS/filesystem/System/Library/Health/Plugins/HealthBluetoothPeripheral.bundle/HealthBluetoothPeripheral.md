## HealthBluetoothPeripheral

> `/System/Library/Health/Plugins/HealthBluetoothPeripheral.bundle/HealthBluetoothPeripheral`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3eda8` | `0x3eee4` | **`+0x13c`** |
| `__TEXT.__objc_methname` | `0x9c9d` | `0x9d18` | **`+0x7b`** |
| `__TEXT.__oslogstring` | `0x58e6` | `0x595f` | **`+0x79`** |
| `__TEXT.__objc_methlist` | `0x3e6c` | `0x3edc` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0x62e0` | `0x6340` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0xad4` | `0xaf8` | **`+0x24`** |
| `__DATA.__objc_const` | `0x7810` | `0x7830` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x2288` | `0x22a8` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x2e97` | `0x2ea8` | **`+0x11`** |
| `__TEXT.__auth_stubs` | `0x840` | `0x850` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x430` | `0x438` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x478` | `0x480` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

-  Functions: 1709
-  Symbols:   435
-  CStrings:  2666
+  Functions: 1714
+  Symbols:   437
+  CStrings:  2673
Symbols:
+ _HKConnectedGymIsMutedToday
+ _NSCalendarDayChangedNotification
CStrings:
+ "Calendar day changed. Updating NFC always on preference"
+ "GymKit muted for today; disabling always-on NFC until end of day"
+ "_calendarDayDidChange"
+ "assumeLowPowerModeOwnership"
+ "unitTest_ownsLowPowerMode"
+ "unitTest_setSystemLowPowerModeEnabledOverride:"
+ "v24@0:8@?<B@?>16"
```
