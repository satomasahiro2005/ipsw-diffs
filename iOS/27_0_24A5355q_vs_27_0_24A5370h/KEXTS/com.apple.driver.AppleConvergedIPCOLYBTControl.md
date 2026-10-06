## com.apple.driver.AppleConvergedIPCOLYBTControl

> `com.apple.driver.AppleConvergedIPCOLYBTControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x5d0` | **`+0x5d0`** |
| `__TEXT_EXEC.__text` | `0x47128` | `0x4721c` | **`+0xf4`** |

### Other Changes

```diff

-194.0.0.0.0
+195.0.0.0.0
Functions:
~ __ZN26AppleConvergedIPCRTIDevice17setupDeviceParamsEP20acipcRTIDeviceParams : 5520 -> 5804
~ __ZN26AppleConvergedIPCRTIDevice17printDeviceParamsEP20acipcRTIDeviceParams : 2204 -> 2216
~ __ZN26AppleConvergedIPCRTIDevice19terminateInterfacesEv : 496 -> 484
~ __ZN26AppleConvergedIPCRTIDevice12triggerAsyncEbj : 360 -> 356
~ __ZN26AppleConvergedIPCRTIDevice25collectSnapshotOrCoredumpEP18IOMemoryDescriptorjP17IOACIPCCompletionb : 1440 -> 1444
~ __ZN33AppleConvergedIPCSkywalkInterface16dequeueTxPacketsEP26IOSkywalkTxSubmissionQueuePKP15IOSkywalkPacketjPv : 1084 -> 1080
~ __ZN33AppleConvergedIPCSkywalkInterface16dequeueRxPacketsEP26IOSkywalkRxSubmissionQueuePKP15IOSkywalkPacketjPv : 696 -> 700
~ __ZN33AppleConvergedIPCSkywalkInterface16enqueueRxPacketsEP26IOSkywalkRxCompletionQueuePP15IOSkywalkPacketjPv : 564 -> 560
~ __ZN14ACIPCRTIDevice10initializeEP20acipcRTIDeviceParams : 1476 -> 1520
~ __ZN14ACIPCRTIDevice13checkMSIRangeEv : 384 -> 392
~ __ZN14ACIPCRTIDevice7setupCREv : 1192 -> 1184
~ sub_fffffff008a01408 -> sub_fffffff008a18bac : 648 -> 644
~ __ZN14ACIPCRTIDevice21shadowDoorbellProcessEv : 452 -> 444
~ __ZN14ACIPCRTIDevice12msiInterruptEh : 1248 -> 1232
~ __ZN14ACIPCRTIDevice21processCompletionRingEjPb : 1088 -> 1084
~ __ZN14ACIPCRTIDevice17messageCompletionEP25acipcRTIMessagesStructurej24acipcRTICompletionStatus : 2036 -> 2028
~ __ZN14ACIPCRTIDevice19unQuiesceCompletionEv : 496 -> 492
~ __ZN14ACIPCRTIDevice12setupMessageE19acipcRTIMessageTypeP25acipcRTIMessagesStructuret : 832 -> 836
~ __ZN14ACIPCRTIDevice23hostExitSleepCompletionEv : 556 -> 552
~ __ZN14ACIPCRTIDevice15triggerRecoveryEv : 580 -> 576
~ __ZN14ACIPCRTIDevice15processRecoveryEv : 384 -> 380
~ __ZN14ACIPCRTIDevice17printScanHostMemsEv : 872 -> 860
~ __ZN14ACIPCRTIDevice9stateDumpEPcPj : 1912 -> 1892
~ __ZN38AppleConvergedIPCOLYBTCoreDumpProvider16readCoreDumpMMIOEP18IOMemoryDescriptorPN14BTDebugService18CoreDumpCompletionE : 3800 -> 3804
~ sub_fffffff008a16b84 -> sub_fffffff008a2e2d8 : 60 -> 56
~ __ZN33AppleConvergedIPCOLYBTLogProvider5startEP9IOService : 1768 -> 1772
```
