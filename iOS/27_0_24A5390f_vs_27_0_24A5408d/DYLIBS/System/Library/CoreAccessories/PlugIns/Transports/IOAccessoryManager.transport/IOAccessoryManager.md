## IOAccessoryManager

> `/System/Library/CoreAccessories/PlugIns/Transports/IOAccessoryManager.transport/IOAccessoryManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5d488` | `0x5d73c` | **`+0x2b4`** |
| `__TEXT.__oslogstring` | `0xbc54` | `0xbcbc` | **`+0x68`** |
| `__AUTH_CONST.__cfstring` | `0x45a0` | `0x45c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x5fde` | `0x5ffa` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x2f7c` | `0x2f94` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xef8` | `0xf08` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f00` | `0x1f10` | **`+0x10`** |

### Other Changes

```diff

-1210.0.0.502.1
+1216.0.0.0.0

-  Functions: 1948
-  Symbols:   2842
-  CStrings:  1708
+  Functions: 1950
+  Symbols:   2846
+  CStrings:  1710
Symbols:
+ -[ACCTransportIOAccessoryManager _invalidateAllAccessoryInfoFields]
+ -[ACCTransportIOAccessoryManager _unregisterBatteryNotifications]
+ GCC_except_table64
+ _ACCUserDefaultsKey_BLEPairingAuthTimeoutValueS
+ _kCFACCUserDefaultsKey_BLEPairingAuthTimeoutValueS
- GCC_except_table62
Functions:
~ _IOAccMgrNotifyEvent : 7560 -> 7404
~ _OUTLINED_FUNCTION_20 : 12 -> 20
~ -[ACCTransportIOAccessoryManager _registerForBatteryNotifications] : 340 -> 344
+ -[ACCTransportIOAccessoryManager _unregisterBatteryNotifications]
+ -[ACCTransportIOAccessoryManager _invalidateAllAccessoryInfoFields]
~ -[ACCTransportPluginIOAccessoryManager authStatusDidChange:forConnectionWithUUID:previousAuthStatus:authType:connectionIsAuthenticated:connectionWasAuthenticated:] : 1644 -> 1852
~ _OUTLINED_FUNCTION_8 : 8 -> 12
~ _OUTLINED_FUNCTION_9 : 12 -> 28
~ _OUTLINED_FUNCTION_10 : 16 -> 8
~ _OUTLINED_FUNCTION_11 : 28 -> 16
~ _OUTLINED_FUNCTION_21 : 20 -> 12
~ _LibSer_SEPControl_Deserialize : 160 -> 200
~ _LibSer_SEPControlResponse_Deserialize : 64 -> 88
CStrings:
+ "BLEPairingAuthTimeoutValueS"
+ "Invalidating accessory info validity for manager %d to force inductiveDeviceType re-read"
+ "unregistering battery notifications for manager %d"
- "unregistering battery notifications"
```
