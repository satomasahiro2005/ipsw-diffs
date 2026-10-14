## AirPlaySupport

> `/System/Library/PrivateFrameworks/AirPlaySupport.framework/AirPlaySupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcc6ec` | `0xcccd8` | **`+0x5ec`** |
| `__AUTH_CONST.__cfstring` | `0x72e0` | `0x73a0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x33d5f` | `0x33e0f` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x3040` | `0x3070` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x3c98` | `0x3cb8` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x600` | `0x610` | **`+0x10`** |
| `__TEXT.__const` | `0xf38` | `0xf40` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1e00` | `0x1e08` | **`+0x8`** |

### Other Changes

```diff

-1005.12.1.0.0
+1005.13.1.1.0

-  Functions: 2628
-  Symbols:   4974
-  CStrings:  4463
+  Functions: 2630
+  Symbols:   4979
+  CStrings:  4471
Symbols:
+ GCC_except_table1478
+ GCC_except_table1603
+ GCC_except_table1607
+ GCC_except_table1799
+ GCC_except_table1802
+ GCC_except_table1805
+ GCC_except_table1809
+ GCC_except_table1974
+ GCC_except_table2224
+ GCC_except_table2527
+ GCC_except_table2532
+ GCC_except_table2541
+ GCC_except_table2598
+ GCC_except_table2601
+ GCC_except_table2602
+ _APSIsHomeAccessory
+ _APSIsHomeAccessory.sCheckOnce
+ _APSIsHomeAccessory.sIsAPHomeAccessory
+ ___APSIsHomeAccessory_block_invoke
+ _kAPSDynamicLatencyManagerVariantIdentifier_B525
- GCC_except_table1474
- GCC_except_table1601
- GCC_except_table1605
- GCC_except_table1797
- GCC_except_table1800
- GCC_except_table1803
- GCC_except_table1807
- GCC_except_table1972
- GCC_except_table2222
- GCC_except_table2525
- GCC_except_table2530
- GCC_except_table2539
- GCC_except_table2596
- GCC_except_table2599
- GCC_except_table2600
CStrings:
+ "1609528"
+ "1622524"
+ "AudioAccessory11,1"
+ "B525"
+ "Boolean APSIsHomeAccessory(void)_block_invoke"
+ "Pebble"
+ "Set APHomeAccessory behavior to %d because of defaults write\n"
+ "forceAPHomeAccessory"
```
