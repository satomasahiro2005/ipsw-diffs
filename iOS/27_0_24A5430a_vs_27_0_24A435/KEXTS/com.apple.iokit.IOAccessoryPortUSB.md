## com.apple.iokit.IOAccessoryPortUSB

> `com.apple.iokit.IOAccessoryPortUSB`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x2524` | `0x2584` | **`+0x60`** |

### Other Changes

```text
Functions:
~ sub_fffffff009eee7b0 -> sub_fffffff009f80fa0 : 72 -> 76
~ sub_fffffff009eee800 -> sub_fffffff009f80ff4 : 52 -> 56
~ sub_fffffff009eee834 -> sub_fffffff009f8102c : 52 -> 56
~ sub_fffffff009eee878 -> sub_fffffff009f81074 : 68 -> 72
~ sub_fffffff009eee8e4 -> sub_fffffff009f810e4 : 72 -> 76
~ sub_fffffff009eee92c -> sub_fffffff009f81130 : 104 -> 108
~ sub_fffffff009eee9a8 -> sub_fffffff009f811b0 : 88 -> 92
~ sub_fffffff009eeea00 -> sub_fffffff009f8120c : 88 -> 92
~ __ZN18IOAccessoryPortUSB5startEP9IOService : 1656 -> 1660
~ __ZN18IOAccessoryPortUSB14controlRequestEP22IOUSBDeviceSetupPacketPiPP18IOMemoryDescriptorPyP28IOUSBDeviceControlCompletion : 1896 -> 1900
~ sub_fffffff009eef9fc -> sub_fffffff009f82214 : 168 -> 172
~ sub_fffffff009eefaa4 -> sub_fffffff009f822c0 : 336 -> 340
~ sub_fffffff009eefbf4 -> sub_fffffff009f82414 : 408 -> 412
~ __ZN18IOAccessoryPortUSB17transmitDataGatedEP18IOMemoryDescriptorj : 996 -> 1000
~ __ZN18IOAccessoryPortUSB12waitSendDoneEj : 96 -> 100
~ __ZN18IOAccessoryPortUSB19receiveNotificationEPvjP9IOServiceS0_m : 636 -> 640
~ __ZN18IOAccessoryPortUSB20setUSBRoleSwitchMaskEtt : 136 -> 140
~ __ZN18IOAccessoryPortUSB7messageEjP9IOServicePv : 268 -> 272
~ __GLOBAL__sub_I_IOAccessoryPortUSB.cpp : 120 -> 124
~ __ZN18IOAccessoryPortUSB23usbRoleSwitchThreadCallEPvS0_ : 184 -> 188
~ sub_fffffff009ef0980 -> sub_fffffff009f831c0 : 220 -> 224
~ __ZN18IOAccessoryPortUSB24controlReceiveCompletionEPviyP18IOMemoryDescriptor : 328 -> 332
~ __ZN18IOAccessoryPortUSB7messageEjP9IOServicePv.cold.1 : 172 -> 176
~ sub_fffffff009ef0c50 -> sub_fffffff009f8349c : 132 -> 136
```
