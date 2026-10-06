## AccessibilityUtilities

> `/System/Library/PrivateFrameworks/AccessibilityUtilities.framework/AccessibilityUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20952c` | `0x209d60` | **`+0x834`** |
| `__TEXT.__oslogstring` | `0x6c15` | `0x6d72` | **`+0x15d`** |
| `__AUTH_CONST.__cfstring` | `0x13820` | `0x13920` | **`+0x100`** |
| `__TEXT.__cstring` | `0x1daa3` | `0x1db2c` | **`+0x89`** |
| `__AUTH_CONST.__objc_const` | `0x1c058` | `0x1c0a8` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xfcf4` | `0xfd44` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xa208` | `0xa240` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x5ae0` | `0x5b10` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x99d8` | `0x99f0` | **`+0x18`** |
| `__TEXT.__const` | `0x8dd8` | `0x8de8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2de0` | `0x2de8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xbe0` | `0xbe8` | **`+0x8`** |

### Other Changes

```diff

-3240.3.0.0.0
+3240.8.0.0.0

-  Functions: 15379
-  Symbols:   10939
-  CStrings:  4418
+  Functions: 15388
+  Symbols:   10951
+  CStrings:  4430
Symbols:
+ -[AXEventTapManager _cacheCarPlayVerdictForService:]
+ -[AXEventTapManager _isCarPlayServiceCached:]
+ -[AXEventTapManager _registerCarPlayRemovalForService:]
+ -[AXEventTapManager _removeCachedCarPlayVerdictForRegistryID:]
+ -[AXEventTapManager _warmCarPlayVerdictAsynchronouslyForService:]
+ -[AXEventTapManager carPlayServiceVerdictCache]
+ -[AXEventTapManager setCarPlayServiceVerdictCache:]
+ GCC_except_table1004
+ GCC_except_table1139
+ GCC_except_table1247
+ GCC_except_table1338
+ GCC_except_table1361
+ GCC_except_table1396
+ GCC_except_table1441
+ GCC_except_table1470
+ GCC_except_table1533
+ GCC_except_table1561
+ GCC_except_table1566
+ GCC_except_table1572
+ GCC_except_table1662
+ GCC_except_table1670
+ GCC_except_table1677
+ GCC_except_table1681
+ GCC_except_table1697
+ GCC_except_table1700
+ GCC_except_table1702
+ GCC_except_table1836
+ GCC_except_table1851
+ GCC_except_table1872
+ GCC_except_table1873
+ GCC_except_table1874
+ GCC_except_table1876
+ GCC_except_table1877
+ GCC_except_table1878
+ GCC_except_table1879
+ GCC_except_table2208
+ GCC_except_table2214
+ GCC_except_table2216
+ GCC_except_table2218
+ GCC_except_table2220
+ GCC_except_table2222
+ GCC_except_table2310
+ GCC_except_table2348
+ GCC_except_table2424
+ GCC_except_table2450
+ GCC_except_table2495
+ GCC_except_table2510
+ GCC_except_table2537
+ GCC_except_table2677
+ GCC_except_table2736
+ GCC_except_table2757
+ GCC_except_table2911
+ GCC_except_table2981
+ GCC_except_table2994
+ GCC_except_table3001
+ GCC_except_table3115
+ GCC_except_table3127
+ GCC_except_table3459
+ GCC_except_table3463
+ GCC_except_table3492
+ GCC_except_table3496
+ GCC_except_table3605
+ GCC_except_table3618
+ GCC_except_table3628
+ GCC_except_table3733
+ GCC_except_table3738
+ GCC_except_table3824
+ GCC_except_table407
+ GCC_except_table4336
+ GCC_except_table4344
+ GCC_except_table4348
+ GCC_except_table4350
+ GCC_except_table4457
+ GCC_except_table4470
+ GCC_except_table4687
+ GCC_except_table4692
+ GCC_except_table4714
+ GCC_except_table4886
+ GCC_except_table4920
+ GCC_except_table4963
+ GCC_except_table4982
+ GCC_except_table655
+ GCC_except_table662
+ GCC_except_table665
+ GCC_except_table667
+ GCC_except_table696
+ GCC_except_table724
+ GCC_except_table741
+ GCC_except_table804
+ GCC_except_table810
+ GCC_except_table814
+ GCC_except_table863
+ GCC_except_table926
+ GCC_except_table975
+ GCC_except_table987
+ GCC_except_table991
+ _IOHIDServiceClientRegisterRemovalCallback
+ _OBJC_IVAR_$_AXEventTapManager._carPlayServiceVerdictCache
+ _OBJC_IVAR_$_AXEventTapManager._carPlayServiceVerdictCacheLock
+ ___65-[AXEventTapManager _warmCarPlayVerdictAsynchronouslyForService:]_block_invoke
+ ___block_descriptor_41_e8_32bs_e39_v32?0^v8^v16^{__IOHIDServiceClient=}24ls32l8
+ __axCarPlayServiceRemovedCallback
- GCC_except_table1130
- GCC_except_table1238
- GCC_except_table1329
- GCC_except_table1352
- GCC_except_table1387
- GCC_except_table1432
- GCC_except_table1461
- GCC_except_table1524
- GCC_except_table1548
- GCC_except_table1552
- GCC_except_table1554
- GCC_except_table1653
- GCC_except_table1661
- GCC_except_table1668
- GCC_except_table1672
- GCC_except_table1679
- GCC_except_table1682
- GCC_except_table1684
- GCC_except_table1827
- GCC_except_table1842
- GCC_except_table1863
- GCC_except_table1864
- GCC_except_table1865
- GCC_except_table1867
- GCC_except_table1868
- GCC_except_table1869
- GCC_except_table1870
- GCC_except_table2199
- GCC_except_table2202
- GCC_except_table2205
- GCC_except_table2207
- GCC_except_table2209
- GCC_except_table2213
- GCC_except_table2301
- GCC_except_table2339
- GCC_except_table2406
- GCC_except_table2441
- GCC_except_table2477
- GCC_except_table2501
- GCC_except_table2528
- GCC_except_table2668
- GCC_except_table2727
- GCC_except_table2748
- GCC_except_table2902
- GCC_except_table2972
- GCC_except_table2983
- GCC_except_table2985
- GCC_except_table3106
- GCC_except_table3118
- GCC_except_table3450
- GCC_except_table3454
- GCC_except_table3483
- GCC_except_table3487
- GCC_except_table3596
- GCC_except_table3609
- GCC_except_table3619
- GCC_except_table3724
- GCC_except_table3729
- GCC_except_table3815
- GCC_except_table398
- GCC_except_table4309
- GCC_except_table4317
- GCC_except_table4339
- GCC_except_table4341
- GCC_except_table4448
- GCC_except_table4461
- GCC_except_table4674
- GCC_except_table4678
- GCC_except_table4705
- GCC_except_table4877
- GCC_except_table4911
- GCC_except_table4954
- GCC_except_table4973
- GCC_except_table646
- GCC_except_table653
- GCC_except_table656
- GCC_except_table658
- GCC_except_table687
- GCC_except_table715
- GCC_except_table732
- GCC_except_table795
- GCC_except_table801
- GCC_except_table805
- GCC_except_table854
- GCC_except_table917
- GCC_except_table966
- GCC_except_table978
- GCC_except_table982
- GCC_except_table995
- ___block_descriptor_40_e8_32s_e39_v32?0^v8^v16^{__IOHIDServiceClient=}24ls32l8
CStrings:
+ "<nil>"
+ "CarPlay verdict cache: AirPlay transport but category lookup returned no value (registryID=%@)"
+ "CarPlay verdict cache: cannot warm — service %p has no registry ID"
+ "CarPlay verdict cache: evicted registryID=%@ (wasCached=%d, cache size %lu)"
+ "CarPlay verdict cache: warmed registryID=%@ result=%@ transport=%@ category=%@ isCarPlay=%d (cache size %lu)"
+ "category-not-automotive"
+ "is-carplay"
+ "no-category-value"
+ "no-service"
+ "no-transport-value"
+ "requiresAppleIntelligence"
+ "transport-not-airplay"
```
