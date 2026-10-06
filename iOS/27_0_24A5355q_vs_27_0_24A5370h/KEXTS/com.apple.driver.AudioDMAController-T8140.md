## com.apple.driver.AudioDMAController-T8140

> `com.apple.driver.AudioDMAController-T8140`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x6f0` | **`+0x6f0`** |
| `__TEXT_EXEC.__text` | `0x2a874` | `0x2ab30` | **`+0x2bc`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ __ZN15AudioDMAChannel19setDirectionAndRoleEjj : 1980 -> 1976
~ sub_fffffff009ad2428 -> sub_fffffff009b35d24 : 76 -> 72
~ sub_fffffff009ad2474 -> sub_fffffff009b35d6c : 528 -> 552
~ sub_fffffff009ad2684 -> sub_fffffff009b35f94 : 88 -> 112
~ sub_fffffff009ad2d0c -> sub_fffffff009b36634 : 440 -> 444
~ sub_fffffff009ad2ec4 -> sub_fffffff009b367f0 : 624 -> 628
~ __ZN15AudioDMAChannel25_buildTransferDescriptorsEP12IODMACommandyy : 3756 -> 3732
~ __ZN15AudioDMAChannel25_signalInterruptAvailableEP22IOInterruptEventSourcei : 2216 -> 2212
~ __ZN15AudioDMAChannel16_createReportersEv : 5460 -> 5468
~ __ZN15AudioDMAChannel23processChannelOperationEN27AudioDMAChannelStateMachine21ADMACChannelOperationEPvS2_S2_ : 6728 -> 6716
~ ____ZN15AudioDMAChannel8transferERKN17AudioDMAEvolution11ADMAChannel15TransferRequestE_block_invoke : 4048 -> 4040
~ __ZN36AudioDMAChannelSharedResourceManager38_allocateChannelBufferApertureInternalEjRjb : 296 -> 288
~ sub_fffffff009ade6f0 -> sub_fffffff009b41ff0 : 168 -> 264
~ sub_fffffff009adf140 -> sub_fffffff009b42aa0 : 268 -> 276
~ sub_fffffff009adf844 -> sub_fffffff009b431ac : 160 -> 188
~ __ZN18AudioDMAController5startEP9IOService : 13472 -> 13512
~ __ZN18AudioDMAController19_setPowerStateGatedENS_28AudioDMAControllerPowerStateEPS_ : 916 -> 908
~ __ZN18AudioDMAController30_programInterruptEnablesLegacyEv : 1840 -> 1832
~ __ZN18AudioDMAController10_gatePowerEmjb : 2356 -> 2360
~ __ZN18AudioDMAController12publishBelowEP15IORegistryEntry : 2760 -> 2768
~ ____ZN18AudioDMAController14initDMAChannelEP9IOServiceP16IODMAEventSourcePjj_block_invoke : 1184 -> 1208
~ __ZN18AudioDMAController20_initDMAChannelGatedEPN15DMAConfigurator21InputDMAConfigurationEP16IODMAEventSourcePj : 1652 -> 1648
~ __ZN18AudioDMAController15startDMACommandEjP12IODMACommandjyy : 1980 -> 2000
~ sub_fffffff009aeaa90 -> sub_fffffff009b4e460 : 100 -> 96
~ __ZN18AudioDMAController14stopDMACommandEjby : 1740 -> 1760
~ sub_fffffff009aeb1c0 -> sub_fffffff009b4eba0 : 484 -> 508
~ __ZN18AudioDMAController12getFIFODepthEjj : 1052 -> 1072
~ __ZN18AudioDMAController12setFIFODepthEjy : 1484 -> 1504
~ __ZN18AudioDMAController14validFIFODepthEjyj : 1124 -> 1144
~ sub_fffffff009aec1f0 -> sub_fffffff009b4fc24 : 480 -> 504
~ __ZN18AudioDMAController12setDMAConfigEjP9IOServicej : 1744 -> 1764
~ __ZN18AudioDMAController14validDMAConfigEjP9IOServicej : 1120 -> 1140
~ ____ZN18AudioDMAController20callPlatformFunctionEPK8OSSymbolbPvS3_S3_S3__block_invoke : 2396 -> 2476
~ __ZN18AudioDMAController20_admaInterruptActionEP22IOInterruptEventSourcei : 1572 -> 1612
~ __ZN18AudioDMAController22_filterInterruptActionEP28IOFilterInterruptEventSource : 384 -> 400
~ __ZN18AudioDMAController16_resumePostambleEv : 208 -> 288
~ ____ZN18AudioDMAController8_suspendEv_block_invoke_2 : 204 -> 200
~ __ZNK12ADMATransfer23AudioDMATransferCommand13logDescriptorEjj : 532 -> 544
~ __ZN27IOInterruptQueueEventSource23normalInterruptOccurredEPvP9IOServicei : 596 -> 620
~ sub_fffffff009af0ffc -> sub_fffffff009b54b68 : 468 -> 480
~ __ZN15AudioDMAChannel23setOperationalAperturesEPyj : 2164 -> 2160
~ sub_fffffff009af8c80 -> sub_fffffff009b5c7f4 : 156 -> 148
~ ____ZN18AudioDMAController8_suspendEv_block_invoke : 896 -> 976
CStrings:
+ "19:54:04"
+ "Jun 18 2026"
- "02:45:50"
- "Jun  5 2026"
```
