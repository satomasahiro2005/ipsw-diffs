## AirPlaySupport

> `/System/Library/PrivateFrameworks/AirPlaySupport.framework/AirPlaySupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcccd8` | `0xcced4` | **`+0x1fc`** |
| `__AUTH_CONST.__cfstring` | `0x73a0` | `0x7440` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x33e0f` | `0x33e8f` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x3cb8` | `0x3cf8` | **`+0x40`** |
| `__DATA_DIRTY.__bss` | `0x610` | `0x630` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1e08` | `0x1e18` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x3070` | `0x3078` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x698` | `0x6a0` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 2630
-  Symbols:   4979
-  CStrings:  4471
+  Functions: 2637
+  Symbols:   4991
+  CStrings:  4476
Symbols:
+ GCC_except_table1483
+ GCC_except_table1610
+ GCC_except_table1614
+ GCC_except_table1806
+ GCC_except_table1812
+ GCC_except_table1816
+ GCC_except_table1981
+ GCC_except_table2231
+ GCC_except_table2534
+ GCC_except_table2539
+ GCC_except_table2548
+ GCC_except_table2605
+ GCC_except_table2608
+ GCC_except_table2609
+ _APSGetClusterMemberIDForSurroundRole
+ _APSGetSurroundRoleFromClusterMemberID
+ _APSGetSurroundRoleFromClusterSummary
+ _APSIsHomeTheaterSurroundEnabled
+ _APSIsHomeTheaterSurroundEnabled.enabled
+ _APSIsHomeTheaterSurroundEnabled.onceToken
+ _APSSurroundToOdeonFallbackEnabled
+ _APSSurroundToOdeonFallbackEnabled.sFallbackOnce
+ _APSSurroundToOdeonFallbackEnabled.sIsFallbackEnabled
+ ___APSIsHomeTheaterSurroundEnabled_block_invoke
+ ___APSSurroundToOdeonFallbackEnabled_block_invoke
+ _kAPSEndpointStreamAudioHoseRegistrarRegistrationOption_SurroundRole
- GCC_except_table1476
- GCC_except_table1603
- GCC_except_table1607
- GCC_except_table1799
- GCC_except_table1802
- GCC_except_table1805
- GCC_except_table1974
- GCC_except_table2224
- GCC_except_table2527
- GCC_except_table2532
- GCC_except_table2541
- GCC_except_table2598
- GCC_except_table2601
- GCC_except_table2602
CStrings:
+ "APSEndpointStreamAudioHoseRegistrarRegistrationOption_SurroundRole"
+ "Home"
+ "HomeTheaterSurround"
+ "SurroundRole"
+ "disableSurroundToOdeon"
```
