## UIAccessibility

> `/System/Library/PrivateFrameworks/UIAccessibility.framework/UIAccessibility`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6d2c4` | `0x6d3c8` | **`+0x104`** |
| `__AUTH.__objc_data` | `0xe60` | `0xe10` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x4b0` | `0x500` | **`+0x50`** |
| `__DATA.__bss` | `0x4d0` | `0x4c8` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x5760` | `0x5768` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x238` | `0x240` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x6c24` | `0x6c2c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1b48` | `0x1b50` | **`+0x8`** |

### Other Changes

```diff

-3245.7.1.0.0
+3245.8.2.0.0

-  Functions: 2626
-  Symbols:   4591
+  Functions: 2627
+  Symbols:   4593
Symbols:
+ -[UIWindowScene(UIAccessibilityElementTraversal) _accessibilityChildrenByAddingMultitaskingElements:]
+ GCC_except_table1014
+ GCC_except_table1025
+ GCC_except_table1060
+ GCC_except_table1068
+ GCC_except_table1073
+ GCC_except_table1109
+ GCC_except_table1126
+ GCC_except_table1233
+ GCC_except_table1336
+ GCC_except_table1344
+ GCC_except_table1346
+ GCC_except_table1348
+ GCC_except_table1359
+ GCC_except_table1371
+ GCC_except_table1404
+ GCC_except_table1414
+ GCC_except_table1416
+ GCC_except_table1491
+ GCC_except_table1494
+ GCC_except_table1559
+ GCC_except_table1562
+ GCC_except_table1584
+ GCC_except_table1624
+ GCC_except_table1636
+ GCC_except_table1639
+ GCC_except_table1653
+ GCC_except_table1689
+ GCC_except_table1719
+ GCC_except_table1731
+ GCC_except_table1733
+ GCC_except_table1737
+ GCC_except_table1741
+ GCC_except_table1763
+ GCC_except_table1766
+ GCC_except_table1768
+ GCC_except_table1773
+ GCC_except_table1776
+ GCC_except_table1780
+ GCC_except_table1876
+ GCC_except_table1938
+ GCC_except_table1993
+ GCC_except_table2011
+ GCC_except_table2165
+ GCC_except_table2212
+ GCC_except_table2218
+ GCC_except_table2227
+ GCC_except_table2441
+ GCC_except_table2460
+ GCC_except_table249
+ GCC_except_table2550
+ GCC_except_table2561
+ GCC_except_table276
+ GCC_except_table279
+ GCC_except_table294
+ GCC_except_table338
+ GCC_except_table352
+ GCC_except_table374
+ GCC_except_table382
+ GCC_except_table550
+ GCC_except_table677
+ GCC_except_table784
+ GCC_except_table949
+ GCC_except_table983
+ _AXUIKeyboardVisibleInputScreenFrame
- GCC_except_table1013
- GCC_except_table1024
- GCC_except_table1059
- GCC_except_table1067
- GCC_except_table1072
- GCC_except_table1108
- GCC_except_table1125
- GCC_except_table1232
- GCC_except_table1335
- GCC_except_table1343
- GCC_except_table1345
- GCC_except_table1347
- GCC_except_table1358
- GCC_except_table1370
- GCC_except_table1403
- GCC_except_table1412
- GCC_except_table1415
- GCC_except_table1490
- GCC_except_table1493
- GCC_except_table1558
- GCC_except_table1561
- GCC_except_table1583
- GCC_except_table1623
- GCC_except_table1635
- GCC_except_table1638
- GCC_except_table1652
- GCC_except_table1688
- GCC_except_table1718
- GCC_except_table1730
- GCC_except_table1732
- GCC_except_table1736
- GCC_except_table1740
- GCC_except_table1762
- GCC_except_table1765
- GCC_except_table1767
- GCC_except_table1772
- GCC_except_table1775
- GCC_except_table1779
- GCC_except_table1875
- GCC_except_table1937
- GCC_except_table1992
- GCC_except_table2010
- GCC_except_table2164
- GCC_except_table2211
- GCC_except_table2217
- GCC_except_table2225
- GCC_except_table2440
- GCC_except_table2459
- GCC_except_table248
- GCC_except_table2549
- GCC_except_table2560
- GCC_except_table275
- GCC_except_table278
- GCC_except_table293
- GCC_except_table337
- GCC_except_table351
- GCC_except_table373
- GCC_except_table381
- GCC_except_table549
- GCC_except_table676
- GCC_except_table783
- GCC_except_table948
- GCC_except_table982
Functions:
~ -[NSObject(UIAccessibilityElementTraversal) _accessibilityEnumerateSiblingsWithParent:options:usingBlock:] : 2888 -> 2928
~ -[UIWindowScene(UIAccessibilityElementTraversal) _accessibilityViewChildrenWithOptions:] : 872 -> 776
+ -[UIWindowScene(UIAccessibilityElementTraversal) _accessibilityChildrenByAddingMultitaskingElements:]
~ -[NSObject(AXPrivCategory) _accessibilityKeyboardFrame] : 56 -> 116
```
