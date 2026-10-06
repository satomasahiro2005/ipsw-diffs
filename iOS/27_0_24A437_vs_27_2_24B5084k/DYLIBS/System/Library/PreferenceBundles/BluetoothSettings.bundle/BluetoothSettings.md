## BluetoothSettings

> `/System/Library/PreferenceBundles/BluetoothSettings.bundle/BluetoothSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23f28` | `0x2402c` | **`+0x104`** |
| `__TEXT.__cstring` | `0x1a81` | `0x1af1` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x22c0` | `0x2320` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x6d8` | `0x6c0` | **`-0x18`** |

### Other Changes

```diff

-2700.17.1.1.0
+2701.2.0.0.0

-  CStrings:  511
+  CStrings:  516
Functions:
~ -[BTSDevicesController showPencilConnectionAttemptAlert:] : 476 -> 728
~ -[BTSDeviceLE isApplePencil:] : 144 -> 152
CStrings:
+ "CONNECT_APPLE_PENCIL_USBC_IPAD"
+ "CONNECT_APPLE_PENCIL_USBC_IPHONE"
+ "Devices-V68"
+ "ExperimentalUSBPencilSupport"
+ "PencilPairing"
```
