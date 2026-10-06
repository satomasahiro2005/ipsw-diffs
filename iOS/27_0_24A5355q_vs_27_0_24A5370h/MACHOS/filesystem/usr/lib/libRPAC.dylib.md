## libRPAC.dylib

> `/usr/lib/libRPAC.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x92b08` | `0x92ac8` | **`-0x40`** |
| `__TEXT.__cstring` | `0x52ba` | `0x52bc` | **`+0x2`** |

### Same-size Content Changes

- `__AUTH_CONST.__interpose`
- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-105.0.0.0.0
+106.0.0.0.0
Symbols:
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIl10qos_info_tEENS_22__unordered_map_hasherIlNS_4pairIKlS2_EENS_4hashIlEENS_8equal_toIlEEEENS_21__unordered_map_equalIlS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9fqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS6_EEENSM_IJEEEEEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIl13hashed_addr_tEENS_22__unordered_map_hasherIlNS_4pairIKlS2_EENS_4hashIlEENS_8equal_toIlEEEENS_21__unordered_map_equalIlS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9fqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS6_EEENSM_IJEEEEEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeIl15sqliteDBState_tEENS_22__unordered_map_hasherIlNS_4pairIKlS2_EENS_4hashIlEENS_8equal_toIlEEEENS_21__unordered_map_equalIlS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9fqe220106IJRKNS_21piecewise_construct_tENS_5tupleIJRS6_EEENSM_IJEEEEEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeIl10qos_info_tEENS_22__unordered_map_hasherIlNS_4pairIKlS2_EENS_4hashIlEENS_8equal_toIlEEEENS_21__unordered_map_equalIlS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9fqe220100IJRKNS_21piecewise_construct_tENS_5tupleIJRS6_EEENSM_IJEEEEEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeIl13hashed_addr_tEENS_22__unordered_map_hasherIlNS_4pairIKlS2_EENS_4hashIlEENS_8equal_toIlEEEENS_21__unordered_map_equalIlS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9fqe220100IJRKNS_21piecewise_construct_tENS_5tupleIJRS6_EEENSM_IJEEEEEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeIl15sqliteDBState_tEENS_22__unordered_map_hasherIlNS_4pairIKlS2_EENS_4hashIlEENS_8equal_toIlEEEENS_21__unordered_map_equalIlS7_SB_S9_EENS_9allocatorIS7_EEE16__emplace_uniqueB9fqe220100IJRKNS_21piecewise_construct_tENS_5tupleIJRS6_EEENSM_IJEEEEEENS5_INS_15__hash_iteratorIPNS_11__hash_nodeIS3_PvEEEEbEEDpOT_ENKUlSN_SL_OSO_OSP_E_clESN_SL_S10_S11_
Functions:
~ _initializeSwizzlers : 1048 -> 1052
~ _isExplicitVacuumStatement : 340 -> 348
~ _isWriteStatement : 364 -> 372
~ _isBulkReadStatement : 364 -> 372
~ _isBulkWriteStatement : 364 -> 372
~ _updateStmt : 788 -> 808
~ _deleteTrackingStmt : 516 -> 524
~ _deleteDatabaseTracker : 676 -> 692
~ ____ZL31initializeSQLiteDBTrackingTablev_block_invoke : 112 -> 120
~ _logCategoryFromString : 696 -> 700
~ _logSubCategoryFromString : 824 -> 828
~ _resetDyldInsertLibraries : 460 -> 436
~ _subCategoryType : 456 -> 460
~ _issueType : 208 -> 216
~ _printStatistics : 384 -> 348
~ _addStringToSum : 132 -> 128
~ _swizzleAPIsForHangDetection : 5792 -> 5688
~ _swizzleMethods : 752 -> 748
~ _swizzleAllMethods : 1152 -> 1132
~ ____Z22initializePrimitiveMapv_block_invoke : 172 -> 184
~ _createPrimitiveEntry : 232 -> 228
~ _updatePrimitiveWaiterQoSInfoUnconditionally : 228 -> 224
~ _updateWaiterCountValueUnconditionally : 120 -> 116
~ _getWaiterCountValue : 112 -> 108
~ _qosWaiterSignallerInvariantCheck : 2520 -> 2512
~ ___generateCulledBacktrace_block_invoke_2 : 5060 -> 5092
~ _adjustFrameNumber : 392 -> 396
~ _parseUserSuppressionFile : 872 -> 868
CStrings:
+ "libRPAC.dylib: interposed_dlclose invoked\n"
+ "libRPAC.dylib: interposed_dlopen invoked\n"
- "libRPAC.dylib: interposed_dlclose invoked"
- "libRPAC.dylib: interposed_dlopen invoked"
```
