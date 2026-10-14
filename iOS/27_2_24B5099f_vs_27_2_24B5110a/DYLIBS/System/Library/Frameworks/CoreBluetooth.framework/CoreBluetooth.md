## CoreBluetooth

> `/System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd8624` | `0xd8870` | **`+0x24c`** |
| `__DATA_CONST.__const` | `0x6a78` | `0x6af0` | **`+0x78`** |
| `__TEXT.__cstring` | `0x1af54` | `0x1af85` | **`+0x31`** |
| `__AUTH_CONST.__objc_intobj` | `0x900` | `0x930` | **`+0x30`** |

### Other Changes

```diff

-2701.7.0.0.0
+2701.7.1.0.0

-  CStrings:  5132
+  CStrings:  5136
Functions:
~ _CBProductIDFromNSString : 1152 -> 1180
~ -[CBPowerSource description] : 3148 -> 3168
~ _CBProductIDToString : 940 -> 960
~ _CBProductIDToString : 940 -> 960
~ _CBProductIDToString : 956 -> 984
~ -[CBDevice _parseNearbyActionPtr:end:] : 2372 -> 2652
~ -[CBDeviceObjectDiscoveryData descriptionWithLevel:] : 1428 -> 1448
~ -[CBDeviceDataProximityService descriptionWithLevel:] : 2900 -> 2920
~ _CBNearbyActionTypeAllCases : 156 -> 228
~ _CBNearbyActionTypeFromString : 2116 -> 2196
CStrings:
+ "ATVRemote1,5"
+ "HomeAccessory"
+ "J490Setup"
+ "J491Setup"
+ "MobileBluetooth-2701.7.1"
- "MobileBluetooth-2701.7"
```
