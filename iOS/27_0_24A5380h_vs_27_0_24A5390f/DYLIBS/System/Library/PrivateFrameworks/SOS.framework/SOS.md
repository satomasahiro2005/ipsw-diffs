## SOS

> `/System/Library/PrivateFrameworks/SOS.framework/SOS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x640` | `—` | **`-0x640`** |
| `__DATA_DIRTY.__objc_data` | `0x500` | `0xb40` | **`+0x640`** |
| `__AUTH.__data` | `0x98` | `—` | **`-0x98`** |
| `__DATA_DIRTY.__data` | `0x1` | `0x99` | **`+0x98`** |
| `__DATA.__bss` | `0x268` | `0x218` | **`-0x50`** |
| `__DATA_DIRTY.__bss` | `0xe8` | `0x138` | **`+0x50`** |
| `__TEXT.__text` | `0x3609c` | `0x360d0` | **`+0x34`** |
| `__DATA_CONST.__got` | `0x380` | `0x398` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x1178` | `0x1180` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1008` | `0x1000` | **`-0x8`** |
| `__TEXT.__oslogstring` | `0x6670` | `0x6676` | **`+0x6`** |

### Other Changes

```diff

-669.100.1.0.0
+670.100.1.0.0

-  Symbols:   2441
+  Symbols:   2442
Symbols:
+ -[SOSCoordinator effectivePairedDeviceInDevices:]
+ _SOSCoordinatorErrorDomain
- -[SOSCoordinator _handleServiceUpdate:]
Functions:
~ -[SOSCoordinator SOSCoordinationMessageTypeForString:] -> -[SOSCoordinator effectivePairedDevice] : 208 -> 92
~ -[SOSCoordinator isPairedDeviceNearby] -> -[SOSCoordinator SOSCoordinationMessageTypeForString:] : 72 -> 208
~ -[SOSCoordinator service:nearbyDevicesChanged:] -> -[SOSCoordinator isPairedDeviceNearby] : 140 -> 72
~ -[SOSCoordinator _handleServiceUpdate:] -> -[SOSCoordinator service:nearbyDevicesChanged:] : 84 -> 184
CStrings:
+ "SOSCoordinator nearbyDevicesChanged (%tu)"
- "SOSCoordinator nearbyDevicesChanged"
```
