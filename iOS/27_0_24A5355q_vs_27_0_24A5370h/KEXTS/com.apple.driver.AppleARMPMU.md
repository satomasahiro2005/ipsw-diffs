## com.apple.driver.AppleARMPMU

> `com.apple.driver.AppleARMPMU`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x6e0` | **`+0x6e0`** |
| `__TEXT_EXEC.__text` | `0x14d54` | `0x14df0` | **`+0x9c`** |

### Other Changes

```diff

-1145.0.0.0.0
+1150.0.0.0.0
Functions:
~ __ZN18AppleARMPMUCharger42copyAndSetAdapterDetailFromChargerFunctionEP23AppleARMFunctionChargerPKc : 460 -> 468
~ __ZN18AppleARMPMUCharger18gatedSetPropertiesEP8OSObject : 12036 -> 12052
~ __ZN18AppleARMPMUCharger20DisplayCapacityCurve30createReplacementCapacityCurveEffbffb : 612 -> 608
~ sub_fffffff0085a9f28 -> sub_fffffff0085b75bc : 84 -> 112
~ __ZN18AppleARMPMUCharger14getChargeLimitEPj : 2536 -> 2544
~ __ZN18AppleARMPMUCharger17checkHvcSelectionEv : 676 -> 680
~ __ZN22AppleARMPMUPowerSource5startEP9IOService : 1756 -> 1752
~ __ZN22ApplePowerSourceMemLog4logEEPKcS1_tjjPv : 184 -> 336
~ __ZN22AppleARMPMUPowerSource16finishStartGatedEP7_IOLockPb : 1208 -> 1212
~ __ZN22AppleARMPMUPowerSource14updateRegistryEv : 700 -> 696
~ __ZN22AppleARMPMUPowerSource13setInputPowerEv : 3084 -> 3012
~ __ZN22AppleARMPMUPowerSource10setChargerEPb : 1048 -> 1068
```
