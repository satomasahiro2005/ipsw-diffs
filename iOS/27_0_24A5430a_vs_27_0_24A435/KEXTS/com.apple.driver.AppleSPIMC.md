## com.apple.driver.AppleSPIMC

> `com.apple.driver.AppleSPIMC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x7040` | `0x71a4` | **`+0x164`** |

### Other Changes

```text
Functions:
~ sub_fffffff0096040e0 -> sub_fffffff009685040 : 72 -> 76
~ sub_fffffff009604130 -> sub_fffffff009685094 : 52 -> 56
~ sub_fffffff009604164 -> sub_fffffff0096850cc : 52 -> 56
~ sub_fffffff0096041a8 -> sub_fffffff009685114 : 68 -> 72
~ sub_fffffff009604214 -> sub_fffffff009685184 : 72 -> 76
~ sub_fffffff00960425c -> sub_fffffff0096851d0 : 104 -> 108
~ sub_fffffff0096042d8 -> sub_fffffff009685250 : 88 -> 92
~ sub_fffffff009604330 -> sub_fffffff0096852ac : 88 -> 92
~ __ZN20AppleSPIMCController5startEP9IOService : 2664 -> 2668
~ sub_fffffff009604df0 -> sub_fffffff009685d74 : 136 -> 140
~ __ZN20AppleSPIMCController22_powerOffTimerCallbackEP18IOTimerEventSource : 200 -> 204
~ sub_fffffff009604fa8 -> sub_fffffff009685f34 : 320 -> 324
~ sub_fffffff0096050e8 -> sub_fffffff009686078 : 112 -> 116
~ __ZN20AppleSPIMCController22setSPIControllerActiveEb : 1200 -> 1204
~ sub_fffffff009605608 -> sub_fffffff0096865a0 : 300 -> 304
~ __ZN20AppleSPIMCController14validSPIConfigEP17AppleARMSPIConfig : 256 -> 260
~ __ZN20AppleSPIMCController17executeSPICommandEP18AppleARMSPICommand : 524 -> 528
~ sub_fffffff009605b50 -> sub_fffffff009686af4 : 132 -> 136
~ __ZN20AppleSPIMCController23_configureHardwareDelayEv : 1208 -> 1212
~ __ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand : 2380 -> 2384
~ sub_fffffff0096069d8 -> sub_fffffff009687988 : 84 -> 88
~ sub_fffffff009606a2c -> sub_fffffff0096879e0 : 140 -> 144
~ __ZN20AppleSPIMCController21_executeSPICommandPIOEP18AppleARMSPICommand : 3976 -> 3980
~ __ZN20AppleSPIMCController9_dmaAbortEP18AppleARMSPICommandiPKcS3_ : 428 -> 432
~ __ZN20AppleSPIMCController8_dmaStopEP16IODMAEventSourcePjyPKc : 528 -> 532
~ __ZN20AppleSPIMCController15_dmaEventActionEP16IODMAEventSourceP12IODMACommandiy : 716 -> 720
~ __ZN20AppleSPIMCController20_interruptActionSubrEv : 732 -> 736
~ sub_fffffff0096085c0 -> sub_fffffff00968958c : 404 -> 408
~ sub_fffffff009608754 -> sub_fffffff009689724 : 308 -> 312
~ __ZN20AppleSPIMCController14_interruptPollEj : 576 -> 580
~ sub_fffffff009608cf4 -> sub_fffffff009689ccc : 164 -> 168
~ __ZN20AppleSPIMCController18_enableDeviceClockEb : 320 -> 324
~ sub_fffffff009608ed8 -> sub_fffffff009689eb8 : 64 -> 68
~ sub_fffffff009608f18 -> sub_fffffff009689efc : 72 -> 76
~ sub_fffffff009608f60 -> sub_fffffff009689f48 : 64 -> 68
~ sub_fffffff009608fa0 -> sub_fffffff009689f8c : 72 -> 76
~ sub_fffffff009609008 -> sub_fffffff009689ff8 : 72 -> 76
~ sub_fffffff009609058 -> sub_fffffff00968a04c : 52 -> 56
~ sub_fffffff00960908c -> sub_fffffff00968a084 : 52 -> 56
~ sub_fffffff0096090d0 -> sub_fffffff00968a0cc : 68 -> 72
~ sub_fffffff00960913c -> sub_fffffff00968a13c : 72 -> 76
~ sub_fffffff009609184 -> sub_fffffff00968a188 : 104 -> 108
~ sub_fffffff009609200 -> sub_fffffff00968a208 : 88 -> 92
~ sub_fffffff009609258 -> sub_fffffff00968a264 : 88 -> 92
~ sub_fffffff0096092b0 -> sub_fffffff00968a2c0 : 152 -> 156
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize : 2488 -> 2492
~ sub_fffffff009609d10 -> sub_fffffff00968ad28 : 140 -> 144
~ sub_fffffff009609d9c -> sub_fffffff00968adb8 : 56 -> 60
~ __ZN20AppleSPIMCController5startEP9IOService.cold.1 : 116 -> 120
~ __ZN20AppleSPIMCController5startEP9IOService.cold.2 : 112 -> 116
~ __ZN20AppleSPIMCController5startEP9IOService.cold.3 : 116 -> 120
~ __ZN20AppleSPIMCController5startEP9IOService.cold.4 : 128 -> 132
~ sub_fffffff00960a0c0 -> sub_fffffff00968b0f0 : 36 -> 40
~ __ZN20AppleSPIMCController17executeSPICommandEP18AppleARMSPICommand.cold.1 : 112 -> 116
~ __ZN20AppleSPIMCController17executeSPICommandEP18AppleARMSPICommand.cold.2 : 112 -> 116
~ __ZN20AppleSPIMCController17executeSPICommandEP18AppleARMSPICommand.cold.3 : 112 -> 116
~ __ZN20AppleSPIMCController17executeSPICommandEP18AppleARMSPICommand.cold.4 : 112 -> 116
~ __ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand.cold.1 : 120 -> 124
~ __ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand.cold.2 : 132 -> 136
~ __ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand.cold.3 : 136 -> 140
~ __ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand.cold.4 : 136 -> 140
~ __ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand.cold.5 : 132 -> 136
~ __ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand.cold.6 : 120 -> 124
~ __ZN20AppleSPIMCController21_executeSPICommandDMAEP18AppleARMSPICommand.cold.7 : 120 -> 124
~ __ZN20AppleSPIMCController21_executeSPICommandPIOEP18AppleARMSPICommand.cold.1 : 128 -> 132
~ __ZN20AppleSPIMCController21_executeSPICommandPIOEP18AppleARMSPICommand.cold.2 : 128 -> 132
~ __ZN20AppleSPIMCController21_executeSPICommandPIOEP18AppleARMSPICommand.cold.3 : 96 -> 100
~ __ZN20AppleSPIMCController21_executeSPICommandPIOEP18AppleARMSPICommand.cold.4 : 96 -> 100
~ __ZN20AppleSPIMCController14_interruptPollEj.cold.1 : 96 -> 100
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.1 : 112 -> 116
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.2 : 112 -> 116
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.3 : 112 -> 116
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.4 : 112 -> 116
~ _OUTLINED_FUNCTION_2 : 112 -> 116
~ sub_fffffff00960aa74 -> sub_fffffff00968bafc : 112 -> 116
~ sub_fffffff00960aae4 -> sub_fffffff00968bb70 : 112 -> 116
~ sub_fffffff00960ab54 -> sub_fffffff00968bbe4 : 112 -> 116
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.9 : 108 -> 112
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.10 : 108 -> 112
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.11 : 108 -> 112
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.12 : 108 -> 112
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.13 : 112 -> 116
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.14 : 112 -> 116
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.15 : 112 -> 116
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.16 : 112 -> 116
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.17 : 112 -> 116
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.18 : 112 -> 116
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.19 : 156 -> 160
~ __ZNK25AppleSPIMCControllerStats9serializeEP11OSSerialize.cold.20 : 112 -> 116
```
