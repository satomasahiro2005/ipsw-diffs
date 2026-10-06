## com.apple.driver.AppleBluetoothModule

> `com.apple.driver.AppleBluetoothModule`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x3d0` | **`+0x3d0`** |
| `__TEXT_EXEC.__text` | `0x7880` | `0x7b94` | **`+0x314`** |
| `__TEXT.__cstring` | `0x25d5` | `0x26a4` | **`+0xcf`** |
| `__DATA_CONST.__auth_got` | `0x1c8` | `0x1e8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x80` | `0x90` | **`+0x10`** |

### Other Changes

```diff

-76.0.0.0.0
-  Functions: 146
+77.0.0.0.0
+  Functions: 147

-  CStrings:  234
+  CStrings:  242
Functions:
~ __ZN20AppleBluetoothModule18setPowerStateGatedEmP9IOService : 496 -> 504
+ __ZN20AppleBluetoothModule20claimAOTExitIfBTWakeEv
~ __ZN20AppleBluetoothModule13setPropertiesEP8OSObject : 1984 -> 1992
CStrings:
+ "ABTM::claimAOTExitIfBTWake: BT wake detected, claiming AOT exit\n"
+ "ABTM::claimAOTExitIfBTWake: bluetooth-pcie already has AOTExit (0x%x), skip\n"
+ "Flags"
+ "IOPMDriverWakeEvents"
+ "LPW.ABTM"
+ "Reason"
+ "bluetooth-pcie"
+ "wifibt"
```
