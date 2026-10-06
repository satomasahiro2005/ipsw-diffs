## CoreBluetooth

> `/System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd7a60` | `0xd7c3c` | **`+0x1dc`** |
| `__TEXT.__cstring` | `0x1ae30` | `0x1ae67` | **`+0x37`** |
| `__DATA_CONST.__const` | `0x68a0` | `0x68b8` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x3110` | `0x3124` | **`+0x14`** |
| `__TEXT.__gcc_except_tab` | `0x25ec` | `0x25f8` | **`+0xc`** |

### Other Changes

```diff

-2700.43.0.0.0
+2700.46.1.1.0

-  Functions: 5532
+  Functions: 5533

-  CStrings:  5108
+  CStrings:  5111
Functions:
~ -[CBDevice descriptionWithLevel:] : 8524 -> 8644
+ sub_20749fda0
~ -[CBDeviceDataProximityService descriptionWithLevel:] : 2692 -> 2648
~ -[CBDevice _parseProximityServiceSubType:src:end:dataChanged:] : 408 -> 428
~ -[CBDevice _parseProximityServiceHomeKitAccessoryControlPtr:end:] : 944 -> 1048
~ _CBProximityServiceSubTypeToString : 176 -> 188
~ -[CBSpatialInteractionSession _activateXPCCompleted:reactivate:] : 1092 -> 1152
CStrings:
+ "%{public}s - pairingcode:0x%{private}016llX -> str:%{private}@"
+ "%{public}s - str:%{private}@ -> pairingcode:0x%{private}016llX"
+ ", OTA <private>"
+ ", stID <private>"
+ "MobileBluetooth-2700.46.1.1"
+ "RemoteDiagnostics"
- "%{public}s - pairingcode:0x%016llX -> str:%{public}@"
- "%{public}s - str:%{public}@ -> pairingcode:0x%016llX"
- "MobileBluetooth-2700.43"
```
