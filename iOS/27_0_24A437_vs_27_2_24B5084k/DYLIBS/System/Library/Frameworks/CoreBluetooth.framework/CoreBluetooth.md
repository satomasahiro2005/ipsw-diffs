## CoreBluetooth

> `/System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd81d8` | `0xd855c` | **`+0x384`** |
| `__AUTH_CONST.__objc_const` | `0x1c580` | `0x1c630` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0xd6a4` | `0xd734` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x5cc8` | `0x5cf8` | **`+0x30`** |
| `__TEXT.__const` | `0x2d49` | `0x2d59` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x29e8` | `0x29f8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1374` | `0x1380` | **`+0xc`** |
| `__TEXT.__cstring` | `0x1af09` | `0x1af0c` | **`+0x3`** |

### Other Changes

```diff

-2700.51.1.3.0
+2701.3.0.0.0

-  Functions: 5534
-  Symbols:   8433
-  CStrings:  5124
+  Functions: 5546
+  Symbols:   8448
+  CStrings:  5126
Symbols:
+ -[CBDevice _clearProximityServiceAccessoryCategory]
+ -[CBDevice _clearProximityServiceColorCode]
+ -[CBDevice proximityServiceAccessoryCategory]
+ -[CBDevice proximityServiceColorCode]
+ -[CBDevice setProximityServiceAccessoryCategory:]
+ -[CBDevice setProximityServiceColorCode:]
+ -[CBDeviceDataProximityService proximityServiceAccessoryCategory]
+ -[CBDeviceDataProximityService proximityServiceColorCode]
+ -[CBDeviceDataProximityService setProximityServiceAccessoryCategory:]
+ -[CBDeviceDataProximityService setProximityServiceColorCode:]
+ -[CBHomeKitProxAccessoryMetadata accessoryCategory]
+ -[CBHomeKitProxAccessoryMetadata setAccessoryCategory:]
+ GCC_except_table533
+ GCC_except_table538
+ GCC_except_table553
+ GCC_except_table616
+ _CBAdvReportMetricHeySiri
+ _OBJC_IVAR_$_CBDeviceDataProximityService._proximityServiceAccessoryCategory
+ _OBJC_IVAR_$_CBDeviceDataProximityService._proximityServiceColorCode
+ _OBJC_IVAR_$_CBHomeKitProxAccessoryMetadata._accessoryCategory
- GCC_except_table527
- GCC_except_table532
- GCC_except_table547
- GCC_except_table610
- _CBManagerIsIOBluetoothShim
CStrings:
+ "MobileBluetooth-2701.3"
+ "kCBAdvReportMetricHeySiri"
+ "psAC"
+ "psCC"
- "MobileBluetooth-2700.51.1.3"
- "kCBManagerIsIOBluetoothShim"
```
