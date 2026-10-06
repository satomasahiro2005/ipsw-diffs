## com.apple.driver.AppleEmbeddedUSB

> `com.apple.driver.AppleEmbeddedUSB`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x3f0` | **`+0x3f0`** |
| `__TEXT_EXEC.__text` | `0x82c8` | `0x82e8` | **`+0x20`** |

### Other Changes

```diff

-714.0.0.0.0
+716.0.0.0.0
Functions:
~ __ZN11AppleUSBPhy5startEP9IOService : 1180 -> 1184
~ sub_fffffff008baa8f4 -> sub_fffffff008bc8808 : 248 -> 260
~ __ZN11AppleUSBPhy14enablePhyPowerEP8OSObjectj : 744 -> 748
~ sub_fffffff008bab020 -> sub_fffffff008bc8f44 : 324 -> 316
~ __ZN11AppleUSBPhy16applySDBTunablesEyPKNS_11tSDBTunableEm : 344 -> 340
~ sub_fffffff008bab678 -> sub_fffffff008bc9590 : 224 -> 228
~ sub_fffffff008bab758 -> sub_fffffff008bc9674 : 224 -> 228
~ __ZN26AppleEmbeddedUSBArbitrator5startEP9IOService : 2560 -> 2576
~ sub_fffffff008bae8f8 -> sub_fffffff008bcc828 : 236 -> 252
~ __ZN26AppleEmbeddedUSBArbitrator17enableDeviceClockEPK8OSObjectj : 796 -> 792
~ sub_fffffff008bafda4 -> sub_fffffff008bcdce0 : 324 -> 316
~ sub_fffffff008bafee8 -> sub_fffffff008bcde1c : 800 -> 796
```
