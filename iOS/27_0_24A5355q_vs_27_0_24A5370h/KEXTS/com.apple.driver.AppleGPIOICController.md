## com.apple.driver.AppleGPIOICController

> `com.apple.driver.AppleGPIOICController`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x420` | **`+0x420`** |
| `__TEXT_EXEC.__text` | `0xbabc` | `0xb9f4` | **`-0xc8`** |

### Other Changes

```text
Functions:
~ __ZN16AppleT8006GPIOIC17initPinsAndGroupsEjj.cold.4 : 472 -> 464
~ __ZN16AppleT8006GPIOIC15claimWakeEventsEv : 2084 -> 2076
~ __ZN16AppleT8006GPIOIC15handleInterruptEPvP9IOServicei : 2196 -> 2176
~ __ZN16AppleT8006GPIOIC10initVectorEiP17IOInterruptVector : 624 -> 616
~ sub_fffffff008c1b0b0 -> sub_fffffff008c3b544 : 316 -> 312
~ sub_fffffff008c1b1ec -> sub_fffffff008c3b67c : 464 -> 460
~ sub_fffffff008c1b3bc -> sub_fffffff008c3b848 : 736 -> 728
~ sub_fffffff008c1b69c -> sub_fffffff008c3bb20 : 432 -> 428
~ sub_fffffff008c1b84c -> sub_fffffff008c3bccc : 336 -> 332
~ sub_fffffff008c1ba50 -> sub_fffffff008c3becc : 296 -> 292
~ sub_fffffff008c1c074 -> sub_fffffff008c3c4ec : 564 -> 556
~ sub_fffffff008c1c2e4 -> sub_fffffff008c3c754 : 2844 -> 2828
~ __ZN16AppleT8101GPIOIC15handleInterruptEPvP9IOServicei : 1804 -> 1792
~ sub_fffffff008c1d56c -> sub_fffffff008c3d9c0 : 624 -> 616
~ sub_fffffff008c1d7dc -> sub_fffffff008c3dc28 : 316 -> 312
~ sub_fffffff008c1d918 -> sub_fffffff008c3dd60 : 528 -> 524
~ sub_fffffff008c1db28 -> sub_fffffff008c3df6c : 800 -> 792
~ sub_fffffff008c1defc -> sub_fffffff008c3e338 : 356 -> 352
~ sub_fffffff008c1e0a0 -> sub_fffffff008c3e4d8 : 164 -> 160
~ sub_fffffff008c1e144 -> sub_fffffff008c3e578 : 448 -> 444
~ sub_fffffff008c1e304 -> sub_fffffff008c3e734 : 392 -> 388
~ __ZN21AppleGPIOICController5startEP9IOService : 4088 -> 4116
~ sub_fffffff008c2216c -> sub_fffffff008c425b4 : 472 -> 464
~ __ZN19AppleS5L8960XGPIOIC17initPinsAndGroupsEjj.cold.10 : 2844 -> 2828
~ sub_fffffff008c22edc -> sub_fffffff008c4330c : 1768 -> 1752
~ sub_fffffff008c235e4 -> sub_fffffff008c43a04 : 624 -> 616
~ sub_fffffff008c23854 -> sub_fffffff008c43c6c : 316 -> 312
~ sub_fffffff008c23990 -> sub_fffffff008c43da4 : 528 -> 524
~ sub_fffffff008c23ba0 -> sub_fffffff008c43fb0 : 724 -> 716
~ sub_fffffff008c23f28 -> sub_fffffff008c44330 : 296 -> 292
~ sub_fffffff008c24050 -> sub_fffffff008c44454 : 164 -> 160
~ sub_fffffff008c240f4 -> sub_fffffff008c444f4 : 448 -> 444
~ sub_fffffff008c242b4 -> sub_fffffff008c446b0 : 392 -> 388
```
