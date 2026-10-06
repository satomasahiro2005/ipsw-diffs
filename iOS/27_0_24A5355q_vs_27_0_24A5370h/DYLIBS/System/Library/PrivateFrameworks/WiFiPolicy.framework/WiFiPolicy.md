## WiFiPolicy

> `/System/Library/PrivateFrameworks/WiFiPolicy.framework/WiFiPolicy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe2f44` | `0xe2c04` | **`-0x340`** |
| `__AUTH_CONST.__cfstring` | `0x20ce0` | `0x20d20` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x29b8` | `0x29f0` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x25940` | `0x25970` | **`+0x30`** |
| `__TEXT.__cstring` | `0x25bfb` | `0x25c2b` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x13cd8` | `0x13cf0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xaef0` | `0xaf00` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2560` | `0x2564` | **`+0x4`** |

### Other Changes

```diff

-1070.52.0.0.0
+1070.55.0.0.0

-  Functions: 7202
-  Symbols:   11970
-  CStrings:  5313
+  Functions: 7203
+  Symbols:   11973
+  CStrings:  5315
Symbols:
+ -[WiFiUsageMonitor isP2PInRealTime]
+ -[WiFiUsageMonitor setIsP2PInRealTime:]
+ _OBJC_IVAR_$_WiFiUsageMonitor._isP2PInRealTime
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE15__init_buf_ptrsB9fqe220106Ev
+ __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B9fqe220106Ej
+ __ZNSt3__116__pad_and_outputB9fqe220106IcNS_11char_traitsIcEEEENS_19ostreambuf_iteratorIT_T0_EES6_PKS4_S8_S8_RNS_8ios_baseES4_
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIN6gloria6TileIdEEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
+ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220106Ev
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__124__put_character_sequenceB9fqe220106IcNS_11char_traitsIcEEEERNS_13basic_ostreamIT_T0_EES7_PKS4_m
+ __ZNSt3__127__tree_balance_after_insertB9fqe220106IPNS_16__tree_node_baseIPvEEEEvT_S5_
+ __ZNSt3__13setIN6gloria6TileIdENS_4lessIS2_EENS_9allocatorIS2_EEE6insertB9fqe220106ERKS2_
+ __ZNSt3__16__treeIN6gloria6TileIdENS_4lessIS2_EENS_9allocatorIS2_EEE14__tree_deleterclB9fqe220106EPNS_11__tree_nodeIS2_PvEE
+ __ZNSt3__16vectorIN6gloria6TileIdENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE15__init_buf_ptrsB9fqe220100Ev
- __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B9fqe220100Ej
- __ZNSt3__116__pad_and_outputB9fqe220100IcNS_11char_traitsIcEEEENS_19ostreambuf_iteratorIT_T0_EES6_PKS4_S8_S8_RNS_8ios_baseES4_
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIN6gloria6TileIdEEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
- __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220100Ev
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__124__put_character_sequenceB9fqe220100IcNS_11char_traitsIcEEEERNS_13basic_ostreamIT_T0_EES7_PKS4_m
- __ZNSt3__127__tree_balance_after_insertB9fqe220100IPNS_16__tree_node_baseIPvEEEEvT_S5_
- __ZNSt3__13setIN6gloria6TileIdENS_4lessIS2_EENS_9allocatorIS2_EEE6insertB9fqe220100ERKS2_
- __ZNSt3__16__treeIN6gloria6TileIdENS_4lessIS2_EENS_9allocatorIS2_EEE14__tree_deleterclB9fqe220100EPNS_11__tree_nodeIS2_PvEE
- __ZNSt3__16vectorIN6gloria6TileIdENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
CStrings:
+ "FlightMode"
+ "allSofTAPSTAsSupportLPEMLSR"
+ "isP2PRTG"
+ "numberOfSoftAPSTAsNOTSupportingLPEMLSR"
+ "numberOfSoftAPSTAsSupportingLPEMLSR"
+ "softAPnumberOfSTAs"
+ "time_since_FlightModeOff"
- "flightMode"
- "numOfHotspotClients"
- "numOfHotspotClientsLPEMLSR"
- "numOfHotspotClientsNonLPEMLSR"
- "time_since_flightmodeoff"
```
