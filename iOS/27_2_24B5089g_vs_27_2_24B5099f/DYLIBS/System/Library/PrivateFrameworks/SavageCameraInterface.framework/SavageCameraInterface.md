## SavageCameraInterface

> `/System/Library/PrivateFrameworks/SavageCameraInterface.framework/SavageCameraInterface`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28c8` | `0x2a58` | **`+0x190`** |
| `__TEXT.__oslogstring` | `0x422` | `0x4a4` | **`+0x82`** |

### Other Changes

```diff

-10.60.0.0.0
+10.61.0.0.0

-  CStrings:  95
+  CStrings:  97
Functions:
~ __Z30sendSynchronousXpcMsgWithReplyP13xpcConnection25ISPServicesRemoteProperty29ISPServicesRemotePropertyTypeP28ISPServicesRemotePropertySet : 1332 -> 1416
~ _SavageCamInterfaceOpen : 800 -> 900
~ _SavageCamInterfaceGetSensorInfo : 680 -> 788
~ _SavageCamInterfaceColdBootPowerCycle : 452 -> 560
CStrings:
+ "%s: Missing ISP Driver version information in PropertyType Get, returning\n"
+ "%s: Missing ISP Driver version information, returning\n"
```
