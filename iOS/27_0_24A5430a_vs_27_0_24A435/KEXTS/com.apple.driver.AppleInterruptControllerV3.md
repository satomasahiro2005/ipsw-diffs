## com.apple.driver.AppleInterruptControllerV3

> `com.apple.driver.AppleInterruptControllerV3`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x448c` | `0x4574` | **`+0xe8`** |

### Other Changes

```text
Functions:
~ sub_fffffff008fba1a0 -> sub_fffffff009016840 : 72 -> 76
~ sub_fffffff008fba1f0 -> sub_fffffff009016894 : 52 -> 56
~ sub_fffffff008fba224 -> sub_fffffff0090168cc : 52 -> 56
~ sub_fffffff008fba268 -> sub_fffffff009016914 : 68 -> 72
~ sub_fffffff008fba2d4 -> sub_fffffff009016984 : 72 -> 76
~ sub_fffffff008fba31c -> sub_fffffff0090169d0 : 104 -> 108
~ sub_fffffff008fba398 -> sub_fffffff009016a50 : 88 -> 92
~ sub_fffffff008fba3f0 -> sub_fffffff009016aac : 88 -> 92
~ __ZN34AppleInterruptControllerUserClient5startEP9IOService : 316 -> 320
~ sub_fffffff008fba744 -> sub_fffffff009016e08 : 88 -> 92
~ sub_fffffff008fba8b4 -> sub_fffffff009016f7c : 352 -> 356
~ sub_fffffff008fbaa14 -> sub_fffffff0090170e0 : 192 -> 196
~ sub_fffffff008fbab0c -> sub_fffffff0090171dc : 80 -> 84
~ sub_fffffff008fbab6c -> sub_fffffff009017240 : 72 -> 76
~ sub_fffffff008fbabbc -> sub_fffffff009017294 : 680 -> 684
~ sub_fffffff008fbae7c -> sub_fffffff009017558 : 68 -> 72
~ sub_fffffff008fbaee8 -> sub_fffffff0090175c8 : 72 -> 76
~ sub_fffffff008fbaf30 -> sub_fffffff009017614 : 52 -> 56
~ sub_fffffff008fbaf80 -> sub_fffffff009017668 : 716 -> 720
~ sub_fffffff008fbb24c -> sub_fffffff009017938 : 204 -> 208
~ sub_fffffff008fbb318 -> sub_fffffff009017a08 : 204 -> 208
~ _panic : 224 -> 228
~ __ZN26AppleInterruptControllerV317getAICBaseAddressEv : 392 -> 396
~ __ZN26AppleInterruptControllerV313GetAICNofDiesEv : 92 -> 96
~ sub_fffffff008fbb6a8 -> sub_fffffff009017da8 : 180 -> 184
~ __ZN26AppleInterruptControllerV35startEP9IOService : 2896 -> 2900
~ __ZN26AppleInterruptControllerV330_configureExternalInterruptMapEv : 468 -> 472
~ __ZN26AppleInterruptControllerV326_aicPlatformQuiesceActionsEv : 812 -> 816
~ __ZN26AppleInterruptControllerV325_aicPlatformActiveActionsEv : 740 -> 744
~ _IOLog : 744 -> 748
~ sub_fffffff008fbcdf4 -> sub_fffffff00901950c : 88 -> 92
~ __ZN26AppleInterruptControllerV316getInterruptTypeEP9IOServiceiPi : 192 -> 196
~ __ZN26AppleInterruptControllerV315handleInterruptEPvP9IOServicei : 696 -> 700
~ __ZN26AppleInterruptControllerV310initVectorEiP17IOInterruptVector : 228 -> 232
~ sub_fffffff008fbd3a4 -> sub_fffffff009019acc : 228 -> 232
~ sub_fffffff008fbd488 -> sub_fffffff009019bb4 : 228 -> 232
~ __ZN26AppleInterruptControllerV326startInterruptTimestampingEj : 492 -> 496
~ __ZN26AppleInterruptControllerV324SoftwareInterruptTriggerEib : 320 -> 324
~ __ZN26AppleInterruptControllerV325stopInterruptTimestampingEj : 304 -> 308
~ sub_fffffff008fbdc44 -> sub_fffffff00901a380 : 72 -> 76
~ sub_fffffff008fbdc94 -> sub_fffffff00901a3d4 : 52 -> 56
~ sub_fffffff008fbdcc8 -> sub_fffffff00901a40c : 52 -> 56
~ sub_fffffff008fbdd0c -> sub_fffffff00901a454 : 68 -> 72
~ sub_fffffff008fbdd78 -> sub_fffffff00901a4c4 : 72 -> 76
~ sub_fffffff008fbddc0 -> sub_fffffff00901a510 : 104 -> 108
~ sub_fffffff008fbde28 -> sub_fffffff00901a57c : 88 -> 92
~ sub_fffffff008fbde80 -> sub_fffffff00901a5d8 : 156 -> 160
~ __ZN29AICInterruptTimestampFunction12getTimestampEv : 376 -> 380
~ sub_fffffff008fbe320 -> sub_fffffff00901aa80 : 140 -> 144
~ sub_fffffff008fbe3ac -> sub_fffffff00901ab10 : 56 -> 60
~ __ZN26AppleInterruptControllerV315getDTProperty32EPKcP9IOServicePjj.cold.1 : 84 -> 88
~ sub_fffffff008fbe4bc -> sub_fffffff00901ac28 : 84 -> 88
~ __ZN26AppleInterruptControllerV314OverrideRegMapEP9IOService.cold.1 : 44 -> 48
~ __ZN26AppleInterruptControllerV317getAICBaseAddressEv.cold.1 : 44 -> 48
~ __ZN26AppleInterruptControllerV317getAICBaseAddressEv.cold.2 : 44 -> 48
~ __ZN26AppleInterruptControllerV313GetAICNofDiesEv.cold.1 : 44 -> 48
~ __ZN26AppleInterruptControllerV35startEP9IOService.cold.1 : 56 -> 60
~ __ZN29AICInterruptTimestampFunction12getTimestampEv.cold.1 : 52 -> 56
```
