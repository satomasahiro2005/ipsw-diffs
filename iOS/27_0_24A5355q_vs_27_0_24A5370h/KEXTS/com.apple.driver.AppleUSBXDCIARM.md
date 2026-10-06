## com.apple.driver.AppleUSBXDCIARM

> `com.apple.driver.AppleUSBXDCIARM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x660` | **`+0x660`** |
| `__TEXT_EXEC.__text` | `0x3c240` | `0x3c23c` | **`-0x4`** |

### Other Changes

```diff

-891.0.0.0.0
+896.0.0.0.0
Functions:
~ __ZN15AppleUSBXDCIARM5startEP9IOService : 8152 -> 8148
~ sub_fffffff00a51c150 -> sub_fffffff00a5ad14c : 816 -> 796
~ __ZN15AppleUSBXDCIARM35waitCableChangeNotificationResourceEv : 1500 -> 1532
~ __ZN15AppleUSBXDCIARM30registerTransportNotificationsEv : 1048 -> 1044
~ __ZN15AppleUSBXDCIARM16transportCreatedEPvP9IOServiceP10IONotifier : 2048 -> 2040
```
