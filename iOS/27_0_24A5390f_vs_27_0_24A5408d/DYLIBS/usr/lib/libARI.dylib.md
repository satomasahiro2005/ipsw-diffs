## libARI.dylib

> `/usr/lib/libARI.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x206a84` | `0x2072b4` | **`+0x830`** |
| `__DATA_CONST.__const` | `0x46718` | `0x46888` | **`+0x170`** |
| `__AUTH_CONST.__const` | `0x2a3b0` | `0x2a450` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x3e38b` | `0x3e41a` | **`+0x8f`** |
| `__TEXT.__const` | `0x15290` | `0x15300` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x1ab64` | `0x1abd4` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0xdb68` | `0xdbb0` | **`+0x48`** |

### Other Changes

```diff

-1638.0.0.0.0
+1640.0.0.0.0

-  Functions: 17218
-  Symbols:   24239
-  CStrings:  9462
+  Functions: 17238
+  Symbols:   24271
+  CStrings:  9468
Symbols:
+ GCC_except_table319
+ GCC_except_table329
+ GCC_except_table402
+ GCC_except_table412
+ GCC_except_table424
+ GCC_except_table434
+ GCC_except_table514
+ GCC_except_table524
+ GCC_except_table534
+ GCC_except_table544
+ GCC_except_table597
+ GCC_except_table607
+ GCC_except_table617
+ GCC_except_table627
+ GCC_except_table637
+ GCC_except_table647
+ GCC_except_table657
+ GCC_except_table739
+ GCC_except_table749
+ GCC_except_table759
+ GCC_except_table769
+ GCC_except_table779
+ GCC_except_table789
+ GCC_except_table799
+ GCC_except_table809
+ GCC_except_table819
+ GCC_except_table850
+ GCC_except_table862
+ GCC_except_table870
+ __ZN6AriSdk38ARI_IBIStwServicePriorityUpdateReq_SDK4packEPP6AriMsg
+ __ZN6AriSdk38ARI_IBIStwServicePriorityUpdateReq_SDK6unpackEv
+ __ZN6AriSdk38ARI_IBIStwServicePriorityUpdateReq_SDKC1EPKhj
+ __ZN6AriSdk38ARI_IBIStwServicePriorityUpdateReq_SDKC1Ev
+ __ZN6AriSdk38ARI_IBIStwServicePriorityUpdateReq_SDKC2EPKhj
+ __ZN6AriSdk38ARI_IBIStwServicePriorityUpdateReq_SDKC2Ev
+ __ZN6AriSdk38ARI_IBIStwServicePriorityUpdateReq_SDKD0Ev
+ __ZN6AriSdk38ARI_IBIStwServicePriorityUpdateReq_SDKD1Ev
+ __ZN6AriSdk38ARI_IBIStwServicePriorityUpdateReq_SDKD2Ev
+ __ZN6AriSdk3TlvI17IBIStwQosPriorityEaSIRS1_vEERS2_OT_
+ __ZN6AriSdk3TlvI23IBIPlmnPriorityInfoTypeEaSIRS1_vEERS2_OT_
+ __ZN6AriSdk40ARI_IBIStwServicePriorityUpdateRspCb_SDK4packEPP6AriMsg
+ __ZN6AriSdk40ARI_IBIStwServicePriorityUpdateRspCb_SDK6unpackEv
+ __ZN6AriSdk40ARI_IBIStwServicePriorityUpdateRspCb_SDKC1EPKhj
+ __ZN6AriSdk40ARI_IBIStwServicePriorityUpdateRspCb_SDKC1Ev
+ __ZN6AriSdk40ARI_IBIStwServicePriorityUpdateRspCb_SDKC2EPKhj
+ __ZN6AriSdk40ARI_IBIStwServicePriorityUpdateRspCb_SDKC2Ev
+ __ZN6AriSdk40ARI_IBIStwServicePriorityUpdateRspCb_SDKD0Ev
+ __ZN6AriSdk40ARI_IBIStwServicePriorityUpdateRspCb_SDKD1Ev
+ __ZN6AriSdk40ARI_IBIStwServicePriorityUpdateRspCb_SDKD2Ev
+ __ZNK6AriSdk38ARI_IBIStwServicePriorityUpdateReq_SDK15hasDeclaredGmidEv
+ __ZNK6AriSdk40ARI_IBIStwServicePriorityUpdateRspCb_SDK15hasDeclaredGmidEv
+ __ZTIN6AriSdk38ARI_IBIStwServicePriorityUpdateReq_SDKE
+ __ZTIN6AriSdk40ARI_IBIStwServicePriorityUpdateRspCb_SDKE
+ __ZTSN6AriSdk38ARI_IBIStwServicePriorityUpdateReq_SDKE
+ __ZTSN6AriSdk40ARI_IBIStwServicePriorityUpdateRspCb_SDKE
+ __ZTVN6AriSdk38ARI_IBIStwServicePriorityUpdateReq_SDKE
+ __ZTVN6AriSdk40ARI_IBIStwServicePriorityUpdateRspCb_SDKE
- GCC_except_table318
- GCC_except_table328
- GCC_except_table339
- GCC_except_table349
- GCC_except_table379
- GCC_except_table401
- GCC_except_table411
- GCC_except_table453
- GCC_except_table463
- GCC_except_table473
- GCC_except_table493
- GCC_except_table503
- GCC_except_table513
- GCC_except_table523
- GCC_except_table533
- GCC_except_table543
- GCC_except_table666
- GCC_except_table676
- GCC_except_table707
- GCC_except_table818
- GCC_except_table828
- GCC_except_table838
- GCC_except_table848
- GCC_except_table858
- GCC_except_table869
CStrings:
+ "IBIStwServicePriorityUpdateReq"
+ "IBIStwServicePriorityUpdateRspCb"
+ "plmn_info_type_t4"
+ "service_priority_t11"
+ "service_priority_t2"
+ "service_priority_t5"
```
