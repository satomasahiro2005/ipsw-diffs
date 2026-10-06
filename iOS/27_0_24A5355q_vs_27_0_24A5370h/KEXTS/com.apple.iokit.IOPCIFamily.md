## com.apple.iokit.IOPCIFamily

> `com.apple.iokit.IOPCIFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x950` | **`+0x950`** |
| `__TEXT_EXEC.__text` | `0x41a84` | `0x41a74` | **`-0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-762.0.0.0.0
+764.0.0.0.0
Functions:
~ __ZN11IOPCIBridge15saveDeviceStateEP11IOPCIDevicej_0 : 3488 -> 3492
~ sub_fffffff00a1b48c8 -> sub_fffffff00a23d59c : 76 -> 68
~ __ZN15IOPCI2PCIBridge9MetaClassC2Ev : 500 -> 508
~ __ZN15IOPCI2PCIBridge25_RESERVEDIOPCI2PCIBridge1Ev : 632 -> 620
~ __ZN11IOPCIBridge29childClientCrashRecoveryGatedEP11IOPCIDevice_0 : 5172 -> 5180
~ sub_fffffff00a1c4bb0 -> sub_fffffff00a24d880 : 136 -> 140
~ __ZN11IOPCIDevice4freeEv_0 : 628 -> 648
~ __ZN11IOPCIDevice19setLatencyToleranceEjy_0 : 568 -> 560
~ __ZN11IOPCIDevice19deviceMemoryWrite32Ehyjj : 1068 -> 1064
~ __ZN11IOPCIDevice18deviceMemoryRead32EhyPjj_0 : 1068 -> 1064
~ __ZN11IOPCIDevice18deviceMemoryRead16EhyPtj_0 : 1068 -> 1064
~ __ZN11IOPCIDevice13resetFunctionE24tIOPCIDeviceResetOptions : 1052 -> 1048
~ __ZN11IOPCIDevice19deviceMemoryWrite64Ehyyj_0 : 456 -> 452
~ __ZN11IOPCIDevice19deviceMemoryWrite32Ehyjj_0 : 456 -> 452
~ ____ZN11IOPCIDevice18SetProperties_ImplEP12OSDictionary_block_invoke : 456 -> 452
~ __ZN11IOPCIDevice18deviceMemoryWrite8Ehyhj_0 : 448 -> 444
~ __ZN17IOPCIConfigurator18findEntryByAddressEP15IORegistryEntryy : 1620 -> 1616
~ __ZN17IOPCIConfigurator13addHostBridgeEP15IOPCIHostBridge_0 : 2644 -> 2652
~ __ZN17IOPCIConfigurator20calculateTopologyMPSEP16IOPCIConfigEntry : 1316 -> 1308
~ __ZN17IOPCIConfigurator19constructPropertiesEP16IOPCIConfigEntry_0 : 2324 -> 2348
~ __ZN17IOPCIConfigurator13waitForLinkUpEP16IOPCIConfigEntry : 2196 -> 2204
~ __ZN17IOPCIConfigurator25bridgeConstructDeviceTreeEPvP16IOPCIConfigEntry_0 : 2940 -> 2920
~ __ZN17IOPCIConfigurator27bridgeDeallocateChildRangesEP16IOPCIConfigEntryS1__0 : 344 -> 328
~ __ZN17IOPCIConfigurator17deleteConfigEntryEP16IOPCIConfigEntry_0 : 836 -> 832
~ __ZN17IOPCIConfigurator17deviceProbeRangesEP16IOPCIConfigEntryj_0 : 440 -> 436
~ __ZN17IOPCIConfigurator20bridgeTotalResourcesEP16IOPCIConfigEntryj_0 : 2392 -> 2352
~ __ZN17IOPCIConfigurator17logAllocatorRangeEP16IOPCIConfigEntryP10IOPCIRangec : 6708 -> 6720
~ __ZN17IOPCIConfigurator17logAllocatorRangeEP16IOPCIConfigEntryP10IOPCIRangec_0 : 1092 -> 1080
~ __ZN17IOPCIConfigurator24deviceApplyConfigurationEP16IOPCIConfigEntryjb_0 : 1884 -> 1852
~ __ZN17IOPCIConfigurator24bridgeApplyConfigurationEP16IOPCIConfigEntryjb_0 : 7168 -> 7144
~ sub_fffffff00a1e74d8 -> sub_fffffff00a270128 : 200 -> 248
~ __ZN32IOPCIMessagedInterruptController24allocateDeviceInterruptsEP9IOServicejjPyPjjj_0 : 2320 -> 2316
~ sub_fffffff00a1e8584 -> sub_fffffff00a271200 : 348 -> 368
~ sub_fffffff00a1e8de8 -> sub_fffffff00a271a78 : 124 -> 148
~ sub_fffffff00a1e8e64 -> sub_fffffff00a271b0c : 164 -> 188
CStrings:
+ "19:34:25"
+ "Jun 18 2026"
- "22:46:03"
- "May 27 2026"
```
