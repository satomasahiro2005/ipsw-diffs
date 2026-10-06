## com.apple.driver.AppleThunderboltUSBType2UpAdapter

> `com.apple.driver.AppleThunderboltUSBType2UpAdapter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0xabbc` | `0xac68` | **`+0xac`** |

### Other Changes

```text
Functions:
~ sub_fffffff0098f6590 -> sub_fffffff00997eee0 : 72 -> 76
~ sub_fffffff0098f65e0 -> sub_fffffff00997ef34 : 52 -> 56
~ sub_fffffff0098f6614 -> sub_fffffff00997ef6c : 52 -> 56
~ sub_fffffff0098f6658 -> sub_fffffff00997efb4 : 68 -> 72
~ sub_fffffff0098f66c4 -> sub_fffffff00997f024 : 72 -> 76
~ sub_fffffff0098f670c -> sub_fffffff00997f070 : 104 -> 108
~ sub_fffffff0098f6788 -> sub_fffffff00997f0f0 : 88 -> 92
~ sub_fffffff0098f67e0 -> sub_fffffff00997f14c : 88 -> 92
~ sub_fffffff0098f6838 -> sub_fffffff00997f1a8 : 112 -> 116
~ __ZN33AppleThunderboltUSBType2UpAdapter5startEP9IOService : 4820 -> 4824
~ _panic : 748 -> 752
~ __ZN33AppleThunderboltUSBType2UpAdapter8finalizeEj : 1060 -> 1064
~ __ZN33AppleThunderboltUSBType2UpAdapter4freeEv : 332 -> 336
~ __ZN33AppleThunderboltUSBType2UpAdapter15createResourcesEv : 468 -> 472
~ sub_fffffff0098f85ac -> sub_fffffff009980f34 : 212 -> 216
~ __ZN33AppleThunderboltUSBType2UpAdapter13activateAsyncEv : 988 -> 992
~ __ZN33AppleThunderboltUSBType2UpAdapter12activateSyncEv : 772 -> 776
~ __ZN33AppleThunderboltUSBType2UpAdapter16activateInternalEP28IOThunderboltDispatchContext : 6976 -> 6980
~ __ZN33AppleThunderboltUSBType2UpAdapter12suspendAsyncEv : 680 -> 684
~ __ZN33AppleThunderboltUSBType2UpAdapter11suspendSyncEv : 772 -> 776
~ __ZN33AppleThunderboltUSBType2UpAdapter15suspendInternalEP28IOThunderboltDispatchContext : 1252 -> 1256
~ __ZN33AppleThunderboltUSBType2UpAdapter15deactivateAsyncEv : 680 -> 684
~ __ZN33AppleThunderboltUSBType2UpAdapter14deactivateSyncEv : 772 -> 776
~ __ZN33AppleThunderboltUSBType2UpAdapter18deactivateInternalEP28IOThunderboltDispatchContext : 4036 -> 4040
~ __ZN33AppleThunderboltUSBType2UpAdapter11createPathsEv : 5000 -> 5004
~ __ZN33AppleThunderboltUSBType2UpAdapter12destroyPathsEv : 464 -> 468
~ __ZN33AppleThunderboltUSBType2UpAdapter32configureLinkCommandsAggregationEv : 1452 -> 1456
~ __ZN33AppleThunderboltUSBType2UpAdapter13enableAdapterEb : 1116 -> 1120
~ sub_fffffff0098fe89c -> sub_fffffff00998725c : 1148 -> 1152
~ __ZN33AppleThunderboltUSBType2UpAdapter12getPortCountEv : 1132 -> 1136
~ __ZN33AppleThunderboltUSBType2UpAdapter15setBundleWeightEv : 824 -> 828
~ __ZN33AppleThunderboltUSBType2UpAdapter20setupPowerManagementEv : 524 -> 528
~ __ZN33AppleThunderboltUSBType2UpAdapter22destroyPowerManagementEv : 344 -> 348
~ __ZN33AppleThunderboltUSBType2UpAdapter13setPowerStateEmP9IOService : 1820 -> 1824
~ __ZN33AppleThunderboltUSBType2UpAdapter4wakeEv : 316 -> 320
~ __ZN33AppleThunderboltUSBType2UpAdapter5sleepEv : 380 -> 384
~ __ZN33AppleThunderboltUSBType2UpAdapter9lateSleepEv : 548 -> 552
~ __ZN33AppleThunderboltUSBType2UpAdapter9earlyWakeEv : 1648 -> 1652
~ sub_fffffff009900abc -> sub_fffffff0099894a4 : 140 -> 144
~ __ZN33AppleThunderboltUSBType2UpAdapter7messageEjP9IOServicePv : 1116 -> 1120
~ sub_fffffff009900fb0 -> sub_fffffff0099899a0 : 172 -> 176
~ sub_fffffff009901064 -> sub_fffffff009989a58 : 80 -> 84
~ __ZN33AppleThunderboltUSBType2UpAdapter16requestTerminateEP9IOServicej.cold.1 : 64 -> 68
```
