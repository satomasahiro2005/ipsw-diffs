## com.apple.driver.AppleEmbeddedTouchEEPROM

> `com.apple.driver.AppleEmbeddedTouchEEPROM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x383c` | `0x3900` | **`+0xc4`** |

### Other Changes

```text
Functions:
~ sub_fffffff008b38470 -> sub_fffffff008b89370 : 72 -> 76
~ sub_fffffff008b384c0 -> sub_fffffff008b893c4 : 52 -> 56
~ sub_fffffff008b384f4 -> sub_fffffff008b893fc : 52 -> 56
~ sub_fffffff008b38538 -> sub_fffffff008b89444 : 68 -> 72
~ sub_fffffff008b385a4 -> sub_fffffff008b894b4 : 72 -> 76
~ sub_fffffff008b385ec -> sub_fffffff008b89500 : 104 -> 108
~ sub_fffffff008b38668 -> sub_fffffff008b89580 : 88 -> 92
~ sub_fffffff008b386c0 -> sub_fffffff008b895dc : 88 -> 92
~ __ZN32AppleEmbeddedTouchEEPROMDriverUC11EEPROMWriteEP30AppleEmbeddedTouchEEPROMDriverPvP25IOExternalMethodArguments : 208 -> 212
~ __ZN32AppleEmbeddedTouchEEPROMDriverUC10EEPROMReadEP30AppleEmbeddedTouchEEPROMDriverPvP25IOExternalMethodArguments : 208 -> 212
~ __ZN32AppleEmbeddedTouchEEPROMDriverUC19EEPROMGetRegionSizeEP30AppleEmbeddedTouchEEPROMDriverPvP25IOExternalMethodArguments : 208 -> 212
~ __ZN32AppleEmbeddedTouchEEPROMDriverUC21EEPROMWriteToInstanceEP30AppleEmbeddedTouchEEPROMDriverPvP25IOExternalMethodArguments : 208 -> 212
~ __ZN32AppleEmbeddedTouchEEPROMDriverUC22EEPROMReadFromInstanceEP30AppleEmbeddedTouchEEPROMDriverPvP25IOExternalMethodArguments : 208 -> 212
~ __ZN32AppleEmbeddedTouchEEPROMDriverUC29EEPROMGetRegionSizeOfInstanceEP30AppleEmbeddedTouchEEPROMDriverPvP25IOExternalMethodArguments : 208 -> 212
~ __ZN32AppleEmbeddedTouchEEPROMDriverUC22EEPROMGetInstanceCountEP30AppleEmbeddedTouchEEPROMDriverPvP25IOExternalMethodArguments : 148 -> 152
~ __ZN32AppleEmbeddedTouchEEPROMDriverUC28EEPROMGetInstanceNameByIndexEP30AppleEmbeddedTouchEEPROMDriverPvP25IOExternalMethodArguments : 532 -> 536
~ __ZN32AppleEmbeddedTouchEEPROMDriverUC28EEPROMGetInstanceIndexByNameEP30AppleEmbeddedTouchEEPROMDriverPvP25IOExternalMethodArguments : 536 -> 540
~ __ZN32AppleEmbeddedTouchEEPROMDriverUC12initWithTaskEP4taskPvjP12OSDictionary : 416 -> 420
~ sub_fffffff008b39258 -> sub_fffffff008b8a1a0 : 64 -> 68
~ __ZN32AppleEmbeddedTouchEEPROMDriverUC5startEP9IOService : 268 -> 272
~ __ZN32AppleEmbeddedTouchEEPROMDriverUC14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 296 -> 300
~ __ZN32AppleEmbeddedTouchEEPROMDriverUC19writeRegionInternalEP30AppleEmbeddedTouchEEPROMDriverhhP25IOExternalMethodArguments : 656 -> 660
~ __ZN32AppleEmbeddedTouchEEPROMDriverUC18readRegionInternalEP30AppleEmbeddedTouchEEPROMDriverhhP25IOExternalMethodArguments : 720 -> 724
~ __ZN32AppleEmbeddedTouchEEPROMDriverUC21getRegionSizeInternalEP30AppleEmbeddedTouchEEPROMDriverhhP25IOExternalMethodArguments : 340 -> 344
~ sub_fffffff008b39bc4 -> sub_fffffff008b8ab24 : 80 -> 84
~ sub_fffffff008b39c24 -> sub_fffffff008b8ab88 : 72 -> 76
~ sub_fffffff008b39c74 -> sub_fffffff008b8abdc : 52 -> 56
~ sub_fffffff008b39ca8 -> sub_fffffff008b8ac14 : 52 -> 56
~ sub_fffffff008b39cec -> sub_fffffff008b8ac5c : 68 -> 72
~ sub_fffffff008b39d58 -> sub_fffffff008b8accc : 72 -> 76
~ sub_fffffff008b39da0 -> sub_fffffff008b8ad18 : 104 -> 108
~ sub_fffffff008b39e1c -> sub_fffffff008b8ad98 : 88 -> 92
~ sub_fffffff008b39e74 -> sub_fffffff008b8adf4 : 88 -> 92
~ __ZN30AppleEmbeddedTouchEEPROMDriver5startEP9IOService : 832 -> 836
~ __ZN30AppleEmbeddedTouchEEPROMDriver26publishNotificationHandlerEPS_PvP9IOService : 2052 -> 2056
~ __ZN30AppleEmbeddedTouchEEPROMDriver10readRegionEhhPKhPj : 628 -> 632
~ __ZN30AppleEmbeddedTouchEEPROMDriver24validateRegionParametersEhhPKhbPj : 328 -> 332
~ __ZN30AppleEmbeddedTouchEEPROMDriver11writeRegionEhhPKhj : 620 -> 624
~ __ZN30AppleEmbeddedTouchEEPROMDriver13getRegionSizeEhhPj : 496 -> 500
~ __ZN30AppleEmbeddedTouchEEPROMDriver22getEEPROMInstanceCountEPh : 160 -> 164
~ __ZN30AppleEmbeddedTouchEEPROMDriver28getEEPROMInstanceNameByIndexEhPcj : 384 -> 388
~ __ZN30AppleEmbeddedTouchEEPROMDriver28getEEPROMInstanceIndexByNameEPKcPh : 384 -> 388
~ sub_fffffff008b3b5c8 -> sub_fffffff008b8c570 : 148 -> 152
~ __ZN30AppleEmbeddedTouchEEPROMDriver22registerEEPROMInstanceEP22AppleARMNORFlashDevicePKch : 1272 -> 1276
~ sub_fffffff008b3bb5c -> sub_fffffff008b8cb0c : 80 -> 84
~ __ZN9os_detail21panic_trapping_policy4trapEPKc : 48 -> 52
~ __ZN30AppleEmbeddedTouchEEPROMDriver26publishNotificationHandlerEPS_PvP9IOService.cold.1 : 16 -> 20
~ __ZN30AppleEmbeddedTouchEEPROMDriver26publishNotificationHandlerEPS_PvP9IOService.cold.3 : 16 -> 20
~ __ZN9os_detail21panic_trapping_policy4trapEPKc : 16 -> 20
```
