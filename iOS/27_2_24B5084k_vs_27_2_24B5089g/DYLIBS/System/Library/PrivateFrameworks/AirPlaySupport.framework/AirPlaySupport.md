## AirPlaySupport

> `/System/Library/PrivateFrameworks/AirPlaySupport.framework/AirPlaySupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcc71c` | `0xcc820` | **`+0x104`** |
| `__TEXT.__cstring` | `0x33f15` | `0x33f56` | **`+0x41`** |
| `__AUTH_CONST.__cfstring` | `0x72c0` | `0x72e0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x3c78` | `0x3c98` | **`+0x20`** |
| `__DATA.__bss` | `0xc00` | `0xc08` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x5f8` | `0x600` | **`+0x8`** |

### Other Changes

```diff

-1005.7.1.0.0
+1005.8.1.0.0

-  Functions: 2625
-  Symbols:   4969
-  CStrings:  4481
+  Functions: 2627
+  Symbols:   4973
+  CStrings:  4484
Symbols:
+ GCC_except_table1476
+ GCC_except_table1601
+ GCC_except_table1605
+ GCC_except_table1797
+ GCC_except_table1800
+ GCC_except_table1803
+ GCC_except_table1807
+ GCC_except_table1972
+ GCC_except_table2222
+ GCC_except_table2525
+ GCC_except_table2530
+ GCC_except_table2539
+ GCC_except_table2595
+ GCC_except_table2598
+ GCC_except_table2599
+ _APSIsUpdateInfoForwardingEnabled
+ _APSIsUpdateInfoForwardingEnabled.sOnce
+ _APSIsUpdateInfoForwardingEnabled.sUpdateInfoForwardingEnabled
+ ___APSIsUpdateInfoForwardingEnabled_block_invoke
- GCC_except_table1472
- GCC_except_table1599
- GCC_except_table1603
- GCC_except_table1795
- GCC_except_table1798
- GCC_except_table1801
- GCC_except_table1805
- GCC_except_table1970
- GCC_except_table2220
- GCC_except_table2523
- GCC_except_table2528
- GCC_except_table2537
- GCC_except_table2593
- GCC_except_table2596
- GCC_except_table2597
CStrings:
+ "[%{ptr}] Recorded %s range %u..<%u, EffectiveTUR: %u..<%u, flushed/pruned ranges: %@"
+ "flushed"
+ "pruned"
+ "updateInfoForwardEnabled"
- "[%{ptr}] Recorded flushed range %u..<%u, flushed ranges: %@"
```
