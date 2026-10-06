## com.apple.DriverKit-AppleEthernetMLX5

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleEthernetMLX5.dext/com.apple.DriverKit-AppleEthernetMLX5`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1937c` | `0x19404` | **`+0x88`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-161.0.0.0.0
+168.0.0.0.0
Functions:
~ __ZN27DriverKit_AppleEthernetMLX510Start_ImplEP9IOService : 1640 -> 1652
~ __ZN27DriverKit_AppleEthernetMLX59Stop_ImplEP9IOService : 248 -> 256
~ __ZZN27DriverKit_AppleEthernetMLX510Start_ImplEP9IOServiceEN3$_08__invokeEv : 308 -> 324
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars16enqueueRxPacketsEPN4mlx55EthRQE : 2592 -> 2584
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars16dequeueRxPacketsEPN4mlx55EthRQE : 312 -> 328
~ __ZN4mlx59FlowGroup5allocEPh : 400 -> 424
~ __ZN4mlx517FlowRootNamespace12initRootTreeEP33DriverKit_AppleEthernetMLX5_IVarsiPNS_12InitTreeNodeEPNS_6FSBaseE : 148 -> 140
~ __ZN33DriverKit_AppleEthernetMLX5_IVars12reclaimPagesEjiPi : 384 -> 392
~ __ZNK23AppleEthernetMLX5DMABuf13fillPageArrayEPy : 64 -> 72
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars16dequeueTxPacketsEPN4mlx55EthSQE : 1016 -> 1012
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars10syncIfAddrEv : 148 -> 156
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars13fillAddrArrayEN4mlx59list_typeEPA6_hi : 196 -> 192
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars11applyIfAddrEv : 144 -> 136
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars12handleIfAddrEb : 168 -> 160
~ __ZN33DriverKit_AppleEthernetMLX5_IVars15portModuleEventERN4mlx53eqeE : 228 -> 224
~ __ZN19AppleEthernetMLX5EQC2ER33DriverKit_AppleEthernetMLX5_IVarshjyRN4mlx53UARE : 540 -> 552
~ __ZN27AppleEthernetMLX5CmdWorkEnt4dumpEb : 392 -> 388
~ __ZN27AppleEthernetMLX5CmdWorkEnt7waitForEv : 364 -> 360
~ __ZN20AppleEthernetMLX5Cmd11compHandlerEj : 624 -> 620
~ _radix_tree_lookup : 148 -> 140
~ _radix_tree_delete : 340 -> 344
~ _radix_tree_insert : 700 -> 684
~ __ZN33DriverKit_AppleEthernetMLX5_IVars19setNicVPortVlanListEtPti : 332 -> 352
~ __ZN33DriverKit_AppleEthernetMLX5_IVars17setNicVPortMcListEiPyi : 316 -> 332
~ __ZN33DriverKit_AppleEthernetMLX5_IVars20queryNicVPortMacListEtN4mlx59list_typeEPA6_hPi : 312 -> 332
~ __ZN33DriverKit_AppleEthernetMLX5_IVars21modifyNicVPortMacListEN4mlx59list_typeEPA6_hi : 316 -> 336
~ __ZN33DriverKit_AppleEthernetMLX5_IVars18queryNicVPortVlansEtPtRi : 276 -> 296
~ __ZN33DriverKit_AppleEthernetMLX5_IVars19modifyNicVPortVlansEPti : 308 -> 328
~ __ZN33DriverKit_AppleEthernetMLX5_IVars9createPSVEjiPj : 240 -> 248
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars13updateCarrierEv : 572 -> 568
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars12openChannelsEv : 192 -> 176
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars13closeChannelsEv : 232 -> 208
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars7openRQTEv : 208 -> 224
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars11activateRQTEv : 228 -> 232
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars13deactivateRQTEv : 200 -> 216
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars8openTIRsEv : 224 -> 204
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars14startInterfaceEv : 1736 -> 1720
~ __ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars22getSupportedMediaArrayEPjS0_ : 532 -> 540
~ __ZN33DriverKit_AppleEthernetMLX5_IVars12setPortProtoEjib : 128 -> 124
~ _ZN39DriverKit_AppleEthernetMLX5_NetIf_IVars10syncIfAddrEv.cold.1 : 100 -> 116
```
