## com.apple.driver.AppleThunderboltUSBUpAdapter

> `com.apple.driver.AppleThunderboltUSBUpAdapter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x9708` | `0x97a0` | **`+0x98`** |

### Other Changes

```text
Functions:
~ sub_fffffff009901300 -> sub_fffffff009989d00 : 72 -> 76
~ sub_fffffff009901350 -> sub_fffffff009989d54 : 52 -> 56
~ sub_fffffff009901384 -> sub_fffffff009989d8c : 52 -> 56
~ sub_fffffff0099013c8 -> sub_fffffff009989dd4 : 68 -> 72
~ sub_fffffff009901434 -> sub_fffffff009989e44 : 72 -> 76
~ sub_fffffff00990147c -> sub_fffffff009989e90 : 104 -> 108
~ sub_fffffff0099014f8 -> sub_fffffff009989f10 : 88 -> 92
~ sub_fffffff009901550 -> sub_fffffff009989f6c : 88 -> 92
~ sub_fffffff0099015a8 -> sub_fffffff009989fc8 : 112 -> 116
~ __ZN28AppleThunderboltUSBUpAdapter5startEP9IOService : 7620 -> 7624
~ _panic : 748 -> 752
~ __ZN28AppleThunderboltUSBUpAdapter8finalizeEj : 1132 -> 1136
~ __ZN28AppleThunderboltUSBUpAdapter4freeEv : 332 -> 336
~ __ZN28AppleThunderboltUSBUpAdapter15createResourcesEv : 468 -> 472
~ sub_fffffff009903e54 -> sub_fffffff00998c88c : 212 -> 216
~ __ZN28AppleThunderboltUSBUpAdapter13activateAsyncEv : 1880 -> 1884
~ __ZN28AppleThunderboltUSBUpAdapter12activateSyncEv : 772 -> 776
~ __ZN28AppleThunderboltUSBUpAdapter16activateInternalEP28IOThunderboltDispatchContext : 5132 -> 5136
~ __ZN28AppleThunderboltUSBUpAdapter12suspendAsyncEv : 680 -> 684
~ __ZN28AppleThunderboltUSBUpAdapter11suspendSyncEv : 772 -> 776
~ __ZN28AppleThunderboltUSBUpAdapter15suspendInternalEP28IOThunderboltDispatchContext : 1252 -> 1256
~ __ZN28AppleThunderboltUSBUpAdapter15deactivateAsyncEv : 716 -> 720
~ __ZN28AppleThunderboltUSBUpAdapter14deactivateSyncEv : 772 -> 776
~ __ZN28AppleThunderboltUSBUpAdapter18deactivateInternalEP28IOThunderboltDispatchContext : 3896 -> 3900
~ __ZN28AppleThunderboltUSBUpAdapter11createPathsEv : 3800 -> 3804
~ __ZN28AppleThunderboltUSBUpAdapter12destroyPathsEv : 464 -> 468
~ __ZN28AppleThunderboltUSBUpAdapter13enableAdapterEb : 624 -> 628
~ __ZN28AppleThunderboltUSBUpAdapter20setupPowerManagementEv : 524 -> 528
~ __ZN28AppleThunderboltUSBUpAdapter22destroyPowerManagementEv : 344 -> 348
~ __ZN28AppleThunderboltUSBUpAdapter13setPowerStateEmP9IOService : 1820 -> 1824
~ __ZN28AppleThunderboltUSBUpAdapter4wakeEv : 384 -> 388
~ __ZN28AppleThunderboltUSBUpAdapter5sleepEv : 444 -> 448
~ __ZN28AppleThunderboltUSBUpAdapter9lateSleepEv : 548 -> 552
~ __ZN28AppleThunderboltUSBUpAdapter9earlyWakeEv : 796 -> 800
~ sub_fffffff00990a40c -> sub_fffffff009992e94 : 140 -> 144
~ __ZN28AppleThunderboltUSBUpAdapter7messageEjP9IOServicePv : 1140 -> 1144
~ sub_fffffff00990a920 -> sub_fffffff0099933b0 : 80 -> 84
~ __ZN28AppleThunderboltUSBUpAdapter16requestTerminateEP9IOServicej.cold.1 : 64 -> 68
```
