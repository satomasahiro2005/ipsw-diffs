## libATCommandStudioDynamic.dylib

> `/usr/lib/libATCommandStudioDynamic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55a38` | `0x55b7c` | **`+0x144`** |
| `__TEXT.__gcc_except_tab` | `0x5884` | `0x58bc` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x2300` | `0x2308` | **`+0x8`** |

### Other Changes

```diff

-1570.0.0.0.0
+1576.0.0.0.0

-  Functions: 1434
-  Symbols:   2295
+  Functions: 1435
+  Symbols:   2296
Symbols:
+ __ZN6config2hw9deviceNEDEv
Functions:
~ __ZZN8dispatch5asyncIZNK3ctu20SharedSynchronizableIN3qmi6Client5StateEE15execute_wrappedIZNS5_16setIndShouldWakeEtbE3$_0EEvOT_EUlvE_EEvP16dispatch_queue_sNSt3__110unique_ptrIS9_NSE_14default_deleteIS9_EEEEENUlPvE_8__invokeESJ_ : 728 -> 704
~ __ZN19QMIServerConnection4initERKNSt3__16vectorINS0_10shared_ptrIN3qmi14ServerAccepterEEENS0_9allocatorIS5_EEEERKN3xpc10connectionE : 596 -> 584
~ __ZZN8dispatch5asyncIZNK3ctu20SharedSynchronizableI18BBServerConnectionE15execute_wrappedIZN19QMIServerConnection4initERKNSt3__16vectorINS7_10shared_ptrIN3qmi14ServerAccepterEEENS7_9allocatorISC_EEEERKN3xpc10connectionEE3$_0EEvOT_EUlvE_EEvP16dispatch_queue_sNS7_10unique_ptrISN_NS7_14default_deleteISN_EEEEENUlPvE_8__invokeESW_ : 1576 -> 1556
+ __ZN6config2hw9deviceNEDEv
~ __ZN3qmi6Server5State19handleClientMessageERKN3xpc10connectionERKNS2_4dictE : 1328 -> 1324
~ ____ZNK3ctu20SharedSynchronizableIN3qmi18QMuxServerAccepter5StateEE20execute_wrapped_syncIZNKS3_13getAllClientsEvE3$_0EEDTclsr8dispatchE4syncLDnEclsr3stdE7forwardIT_Efp_EEEOS7__block_invoke : 212 -> 200
~ __ZN10QMIControl16ClientIdRequests23removeRequestsForClientERKNSt3__110shared_ptrIN3qmi15QMuxClientIfaceEEE : 640 -> 628
~ __ZN10QMIControl16ClientIdRequests19popClientForSvcTypeEN3qmi11ServiceTypeE : 616 -> 608
```
