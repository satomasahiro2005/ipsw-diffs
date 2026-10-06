## com.apple.driver.AppleHPM

> `com.apple.driver.AppleHPM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x9d0` | **`+0x9d0`** |
| `__TEXT_EXEC.__text` | `0x61eb8` | `0x61eb4` | **`-0x4`** |

### Other Changes

```diff

-647.0.0.0.0
+648.0.0.0.0
Functions:
~ __ZN15AppleHPMARMSPMI5startEP9IOService : 1624 -> 1620
~ sub_fffffff008f08b24 -> sub_fffffff008f334d0 : 472 -> 496
~ _fillBufferWithHex : 156 -> 164
~ __ZN17AppleHPMInterface13initSingleHPMEv : 2780 -> 2776
~ __ZN17AppleHPMInterface22processInterruptEventsEv : 2648 -> 2660
~ __ZN17AppleHPMInterface11disablePortEb : 768 -> 772
~ sub_fffffff008f19690 -> sub_fffffff008f44068 : 564 -> 576
~ __ZN17AppleHPMInterface19createTunnelManagerEv : 492 -> 488
~ __ZN17AppleHPMInterface28tunnelClientChangeWithParamsEP26IOTBTTunnelClientInterfacebj : 920 -> 916
~ sub_fffffff008f1d784 -> sub_fffffff008f48160 : 2332 -> 2308
~ sub_fffffff008f2dfe0 -> sub_fffffff008f589a4 : 604 -> 596
~ __ZN23AppleTCControllerType1019forcePortEvaluationEv : 720 -> 716
~ sub_fffffff008f3149c -> sub_fffffff008f5be54 : 212 -> 208
~ sub_fffffff008f31674 -> sub_fffffff008f5c028 : 212 -> 208
~ sub_fffffff008f31748 -> sub_fffffff008f5c0f8 : 212 -> 208
~ sub_fffffff008f3196c -> sub_fffffff008f5c318 : 648 -> 644
~ __ZN17AppleTCController13initSingleHPMEv : 2776 -> 2772
~ __ZN17AppleTCController11disablePortEb : 756 -> 760
~ sub_fffffff008f40d9c -> sub_fffffff008f6b744 : 408 -> 420
~ __ZN17AppleTCController19createTunnelManagerEv : 488 -> 484
~ __ZN17AppleTCController28tunnelClientChangeWithParamsEP26IOTBTTunnelClientInterfacebj : 760 -> 756
~ sub_fffffff008f4424c -> sub_fffffff008f6ebf8 : 2740 -> 2752
~ __ZN8AppleHPM9atomic4CCEhPhS0_S0_S0_S0_ttyyj : 3048 -> 3064
~ sub_fffffff008f5891c -> sub_fffffff008f832e4 : 4884 -> 4892
~ sub_fffffff008f59c30 -> sub_fffffff008f84600 : 3204 -> 3192
~ sub_fffffff008f5b208 -> sub_fffffff008f85bcc : 4428 -> 4408
~ sub_fffffff008f5c354 -> sub_fffffff008f86d04 : 2320 -> 2316
```
