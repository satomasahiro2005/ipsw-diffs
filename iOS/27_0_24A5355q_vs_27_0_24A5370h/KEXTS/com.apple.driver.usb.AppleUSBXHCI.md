## com.apple.driver.usb.AppleUSBXHCI

> `com.apple.driver.usb.AppleUSBXHCI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x720` | **`+0x720`** |
| `__TEXT_EXEC.__text` | `0x48084` | `0x484e4` | **`+0x460`** |
| `__TEXT.__os_log` | `0x50ea` | `0x50f0` | **`+0x6`** |
| `__TEXT.__cstring` | `0x5740` | `0x5744` | **`+0x4`** |

### Other Changes

```diff

-1616.0.0.0.0
+1617.0.1.0.0
Functions:
~ __ZN19AppleUSBXHCIRequest7prepareEv : 10652 -> 10492
~ __ZN19AppleUSBXHCIRequest6cancelEv : 1252 -> 1164
~ sub_fffffff00a698c00 -> sub_fffffff00a72c6f8 : 264 -> 300
~ sub_fffffff00a698d08 -> sub_fffffff00a72c824 : 168 -> 184
~ __ZN19AppleUSBXHCIRequest6updateEPN15StandardUSBXHCI18StandardUSBXHCITRBE : 4728 -> 4772
~ sub_fffffff00a69a0dc -> sub_fffffff00a72dc34 : 524 -> 548
~ __ZN19AppleUSBXHCIRequest8completeEv : 1380 -> 1320
~ sub_fffffff00a69a84c -> sub_fffffff00a72e380 : 60 -> 52
~ __ZN12AppleUSBXHCI5startEP9IOService : 12940 -> 13020
~ sub_fffffff00a69e50c -> sub_fffffff00a732088 : 608 -> 620
~ sub_fffffff00a69e984 -> sub_fffffff00a73250c : 268 -> 276
~ ____ZN12AppleUSBXHCI12createDeviceE31tInternalUSBHostConnectionSpeedjj_block_invoke : 6420 -> 6636
~ sub_fffffff00a6a15bc -> sub_fffffff00a735224 : 52 -> 64
~ sub_fffffff00a6a15f0 -> sub_fffffff00a735264 : 52 -> 68
~ __ZN12AppleUSBXHCI21getCompanionPortGatedEP16AppleUSBHostPortjRS1_ : 3156 -> 3196
~ __ZN12AppleUSBXHCI16registerHubGatedEP15IOUSBHostDevicePKN11StandardUSB13HubDescriptorE17tRegisterHubFlags : 1260 -> 1292
~ __ZN12AppleUSBXHCI26registerSuperSpeedHubGatedEP15IOUSBHostDevicePKN11StandardUSB23SuperSpeedHubDescriptorE : 1156 -> 1188
~ sub_fffffff00a6a2d5c -> sub_fffffff00a736a48 : 292 -> 324
~ sub_fffffff00a6a40e0 -> sub_fffffff00a737dec : 284 -> 316
~ __ZN12AppleUSBXHCI16resumePipesGatedEP15IOUSBHostDevice : 696 -> 728
~ sub_fffffff00a6a462c -> sub_fffffff00a738378 : 296 -> 328
~ __ZN12AppleUSBXHCI18enableStreamsGatedEP13IOUSBHostPipe : 2932 -> 3000
~ sub_fffffff00a6a58ac -> sub_fffffff00a73965c : 240 -> 252
~ sub_fffffff00a6a5c14 -> sub_fffffff00a7399d0 : 860 -> 868
~ __ZN12AppleUSBXHCI11ioInterruptEP22IOInterruptEventSourcei : 2160 -> 2164
~ __ZN12AppleUSBXHCI16primaryInterruptEP22IOInterruptEventSourcei : 5188 -> 5216
~ __ZN12AppleUSBXHCI13portInterruptEPKN15StandardUSBXHCI18StandardUSBXHCITRBE : 1412 -> 1420
~ __ZN12AppleUSBXHCI11createPortsEv : 5648 -> 5736
~ __ZN12AppleUSBXHCI20lowerOnePowerStateToEm : 3812 -> 3820
~ __ZN12AppleUSBXHCI20raiseOnePowerStateToEm : 6604 -> 6580
~ __ZN12AppleUSBXHCI9saveStateEv : 2164 -> 2168
~ __ZN12AppleUSBXHCI12restoreStateEv : 2380 -> 2384
~ __ZN12AppleUSBXHCI8testModeEjN15StandardUSBXHCI13tXHCITestModeE : 3360 -> 3352
~ __ZN12AppleUSBXHCI31adjustDeviceMaxExitLatencyGatedEP15IOUSBHostDevicej : 1776 -> 1796
~ __ZN12AppleUSBXHCI22executePendingCommandsEP18AppleUSBXHCIDevice : 892 -> 908
~ __ZN24AppleUSBXHCITransferRing17getDequeuePointerEv : 640 -> 664
~ __ZN30AppleUSBXHCIIsochronousRequest7prepareEv : 12272 -> 12496
~ __ZN30AppleUSBXHCIIsochronousRequest4linkEP14AppleUSBXHCITD : 3624 -> 3684
~ sub_fffffff00a6bd298 -> sub_fffffff00a751224 : 304 -> 336
~ __ZN23AppleUSBXHCICommandRing12abortCommandEPN15StandardUSBXHCI18StandardUSBXHCITRBE : 1548 -> 1544
~ __ZN23AppleUSBXHCICommandRing15waitForCommandsEv : 944 -> 968
~ __ZN23AppleUSBXHCICommandRing19waitForSlotCommandsEj : 1192 -> 1236
~ __ZN23AppleUSBXHCICommandRing23waitForEndpointCommandsEjj : 820 -> 872
~ __ZN16AppleUSBXHCIPort20initWithDeviceMemoryEP14IODeviceMemoryPN15StandardUSBXHCI33StandardUSBXHCIProtocolCapabilityEP15IORegistryEntry : 1524 -> 1516
~ sub_fffffff00a6c58f8 -> sub_fffffff00a759910 : 1136 -> 1128
~ sub_fffffff00a6c94b4 -> sub_fffffff00a75d4c4 : 324 -> 328
~ sub_fffffff00a6cd95c -> sub_fffffff00a761970 : 120 -> 144
~ sub_fffffff00a6d3854 -> sub_fffffff00a767880 : 784 -> 768
~ sub_fffffff00a6d8d24 -> sub_fffffff00a76cd40 : 440 -> 444
~ sub_fffffff00a6d8f48 -> sub_fffffff00a76cf68 : 520 -> 528
~ sub_fffffff00a6d9300 -> sub_fffffff00a76d328 : 92 -> 100
~ sub_fffffff00a6d935c -> sub_fffffff00a76d38c : 92 -> 100
~ sub_fffffff00a6d93b8 -> sub_fffffff00a76d3f0 : 312 -> 316
~ sub_fffffff00a6d94f0 -> sub_fffffff00a76d52c : 312 -> 316
~ sub_fffffff00a6d9fbc -> sub_fffffff00a76dffc : 112 -> 108
~ sub_fffffff00a6dae48 -> sub_fffffff00a76ee84 : 664 -> 684
CStrings:
+ "%s: %s::%s: device %d endpoint 0x%02x: DMA command operation failed\n"
+ "1211112111111121111111111111111222222222222222211111111111111112222221121121111221111211111221222"
+ "1211112111111121111111111111111222222222222222211111111111111112222221121121111221111211111221222222"
+ "12112112111211"
- "%s: %s::%s: device %d endpoint 0x%02x: failed to get DMA command\n"
- "1211112111111121111111111111111222222222222222211111111111111112222221121121111221111111111221222"
- "1211112111111121111111111111111222222222222222211111111111111112222221121121111221111111111221222222"
- "1211211211111"
```
