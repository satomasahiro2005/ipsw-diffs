## com.apple.driver.AudioDMAFamily

> `com.apple.driver.AudioDMAFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x58e8` | `0x59ac` | **`+0xc4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ sub_fffffff009ad63d0 -> sub_fffffff009b62230 : 72 -> 76
~ sub_fffffff009ad6420 -> sub_fffffff009b62284 : 52 -> 56
~ sub_fffffff009ad646c -> sub_fffffff009b622d4 : 72 -> 76
~ __ZN17AudioDMAEvolution11ADMAChannel21InternalConfiguration3setERKNS0_18InputConfigurationE : 1880 -> 1884
~ __ZN17AudioDMAEvolution11ADMAChannel21InternalConfiguration18updateStreamConfigEjhh : 1204 -> 1208
~ sub_fffffff009ad719c -> sub_fffffff009b63010 : 148 -> 152
~ sub_fffffff009ad7230 -> sub_fffffff009b630a8 : 120 -> 124
~ sub_fffffff009ad72b0 -> sub_fffffff009b6312c : 80 -> 84
~ sub_fffffff009ad7310 -> sub_fffffff009b63190 : 72 -> 76
~ sub_fffffff009ad7360 -> sub_fffffff009b631e4 : 52 -> 56
~ sub_fffffff009ad7394 -> sub_fffffff009b6321c : 52 -> 56
~ sub_fffffff009ad73d8 -> sub_fffffff009b63264 : 68 -> 72
~ sub_fffffff009ad7444 -> sub_fffffff009b632d4 : 72 -> 76
~ sub_fffffff009ad748c -> sub_fffffff009b63320 : 104 -> 108
~ sub_fffffff009ad7508 -> sub_fffffff009b633a0 : 88 -> 92
~ sub_fffffff009ad7560 -> sub_fffffff009b633fc : 88 -> 92
~ __ZN17AudioDMAEvolution13parseBootArgsEPKcPNS_24ADMAChannelInterfaceImplE : 208 -> 212
~ __ZN17AudioDMAEvolution20ADMAChannelInterface17withRegistryEntryEP15IORegistryEntryP9IOService : 168 -> 172
~ __ZN17AudioDMAEvolution22fetchIndexAndDirectionEP15IORegistryEntryPNS_24ADMAChannelInterfaceImplEb : 1700 -> 1704
~ sub_fffffff009ad7dd4 -> sub_fffffff009b63c80 : 384 -> 388
~ __ZN17AudioDMAEvolution20ADMAChannelInterface5startEP9IOService : 3516 -> 3520
~ sub_fffffff009ad8d10 -> sub_fffffff009b64bc4 : 96 -> 100
~ sub_fffffff009ad8d80 -> sub_fffffff009b64c38 : 136 -> 140
~ sub_fffffff009ad8e08 -> sub_fffffff009b64cc4 : 200 -> 204
~ sub_fffffff009ad8ed0 -> sub_fffffff009b64d90 : 136 -> 140
~ ____ZN17AudioDMAEvolution20ADMAChannelInterface10deactivateEv_block_invoke : 552 -> 556
~ sub_fffffff009ad9180 -> sub_fffffff009b65048 : 140 -> 144
~ ____ZN17AudioDMAEvolution20ADMAChannelInterface25setAudioStreamDescriptionERNS_20ChannelConfiguration6StreamE_block_invoke : 1028 -> 1032
~ sub_fffffff009ad9610 -> sub_fffffff009b654e0 : 140 -> 144
~ sub_fffffff009ad969c -> sub_fffffff009b65570 : 476 -> 480
~ __ZNK17AudioDMAEvolution20ADMAChannelInterface28translateStreamConfigurationERKNS_20ChannelConfiguration6StreamEPS1_ : 924 -> 928
~ sub_fffffff009ad9c24 -> sub_fffffff009b65b00 : 140 -> 144
~ ____ZNK17AudioDMAEvolution20ADMAChannelInterface14getPathLatencyERj_block_invoke : 624 -> 628
~ sub_fffffff009ad9f20 -> sub_fffffff009b65e04 : 144 -> 148
~ ____ZN17AudioDMAEvolution20ADMAChannelInterface24transferMemoryDescriptorEP18IOMemoryDescriptorjjU13block_pointerFvRKNS0_25CompletionCallbackContextEE_block_invoke : 1720 -> 1724
~ sub_fffffff009ada68c -> sub_fffffff009b66578 : 144 -> 148
~ ____ZN17AudioDMAEvolution20ADMAChannelInterface24transferMemoryDescriptorEP18IOMemoryDescriptorjU13block_pointerFvRKNS0_25CompletionCallbackContextEE_block_invoke : 1232 -> 1236
~ sub_fffffff009adabec -> sub_fffffff009b66ae0 : 144 -> 148
~ ____ZN17AudioDMAEvolution20ADMAChannelInterface24transferMemoryDescriptorEP18IOMemoryDescriptorbU13block_pointerFvRKNS0_25CompletionCallbackContextEE_block_invoke : 1124 -> 1128
~ sub_fffffff009adb0e0 -> sub_fffffff009b66fdc : 144 -> 148
~ ____ZN17AudioDMAEvolution20ADMAChannelInterface24transferMemoryDescriptorEP18IOMemoryDescriptorU13block_pointerFvRKNS0_25CompletionCallbackContextEEj_block_invoke : 1168 -> 1172
~ sub_fffffff009adb600 -> sub_fffffff009b67504 : 136 -> 140
~ ____ZN17AudioDMAEvolution20ADMAChannelInterface14abortTransfersEv_block_invoke : 576 -> 580
~ sub_fffffff009adb8e0 -> sub_fffffff009b677ec : 80 -> 84
~ __ZN17AudioDMAEvolution22fetchIndexAndDirectionEP15IORegistryEntryPNS_24ADMAChannelInterfaceImplEb : 456 -> 460
~ __ZN9os_detail21panic_trapping_policy4trapEPKc : 48 -> 52
~ __ZN17AudioDMAEvolution13parseBootArgsEPKcPNS_24ADMAChannelInterfaceImplE.cold.1 : 24 -> 28
~ __ZN17AudioDMAEvolution13parseBootArgsEPKcPNS_24ADMAChannelInterfaceImplE.cold.2 : 24 -> 28
~ __ZN17AudioDMAEvolution20ADMAChannelInterface21initWithRegistryEntryEP15IORegistryEntryP9IOService.cold.1 : 188 -> 192
CStrings:
+ "21:41:26"
- "22:27:16"
```
