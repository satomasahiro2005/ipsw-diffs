## UIAccessibility

> `/System/Library/PrivateFrameworks/UIAccessibility.framework/UIAccessibility`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6c9c8` | `0x6d22c` | **`+0x864`** |
| `__TEXT.__oslogstring` | `0x2ca9` | `0x2ce3` | **`+0x3a`** |
| `__AUTH_CONST.__const` | `0x1248` | `0x1268` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x5720` | `0x5738` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x6bdc` | `0x6bf4` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1b30` | `0x1b48` | **`+0x18`** |
| `__DATA.__bss` | `0x4c8` | `0x4d0` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xd90` | `0xd94` | **`+0x4`** |

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Functions: 2616
-  Symbols:   4579
-  CStrings:  1185
+  Functions: 2622
+  Symbols:   4586
+  CStrings:  1186
Symbols:
+ -[NSObject(AXPrivCategory) _accessibilityDeletableCharacterCountBeforeCursor]
+ -[NSObject(AXPrivCategory) _accessibilityReplacementForFocusedOpaqueElement]
+ GCC_except_table1013
+ GCC_except_table1024
+ GCC_except_table1057
+ GCC_except_table1065
+ GCC_except_table1070
+ GCC_except_table1106
+ GCC_except_table1123
+ GCC_except_table1230
+ GCC_except_table1333
+ GCC_except_table1341
+ GCC_except_table1343
+ GCC_except_table1345
+ GCC_except_table1356
+ GCC_except_table1368
+ GCC_except_table137
+ GCC_except_table140
+ GCC_except_table1401
+ GCC_except_table1410
+ GCC_except_table1411
+ GCC_except_table1413
+ GCC_except_table1488
+ GCC_except_table1491
+ GCC_except_table151
+ GCC_except_table1556
+ GCC_except_table1559
+ GCC_except_table1581
+ GCC_except_table1620
+ GCC_except_table1632
+ GCC_except_table1635
+ GCC_except_table1649
+ GCC_except_table1685
+ GCC_except_table1715
+ GCC_except_table1727
+ GCC_except_table1729
+ GCC_except_table1733
+ GCC_except_table1737
+ GCC_except_table1762
+ GCC_except_table1769
+ GCC_except_table1772
+ GCC_except_table1776
+ GCC_except_table1871
+ GCC_except_table1933
+ GCC_except_table1988
+ GCC_except_table2006
+ GCC_except_table2160
+ GCC_except_table2213
+ GCC_except_table2221
+ GCC_except_table2222
+ GCC_except_table2436
+ GCC_except_table2455
+ GCC_except_table248
+ GCC_except_table2545
+ GCC_except_table2556
+ GCC_except_table275
+ GCC_except_table278
+ GCC_except_table293
+ GCC_except_table337
+ GCC_except_table351
+ GCC_except_table373
+ GCC_except_table381
+ GCC_except_table549
+ GCC_except_table676
+ GCC_except_table783
+ GCC_except_table84
+ GCC_except_table948
+ GCC_except_table982
+ __AXUIElementCopyElementAtPositionInHostedCoordinatesWithParams
+ __UIAccessibilityElementBearingScreenChangePostCount
+ ___AXElementBearingScreenChangePostCount
+ __axModalViewContainsVisibleModalDescendant
+ __axModalViewHasAccessibleContent
- GCC_except_table1009
- GCC_except_table1020
- GCC_except_table1053
- GCC_except_table1061
- GCC_except_table1066
- GCC_except_table1102
- GCC_except_table1119
- GCC_except_table1225
- GCC_except_table1328
- GCC_except_table1336
- GCC_except_table1338
- GCC_except_table1340
- GCC_except_table135
- GCC_except_table1351
- GCC_except_table1363
- GCC_except_table138
- GCC_except_table1396
- GCC_except_table1405
- GCC_except_table1406
- GCC_except_table1408
- GCC_except_table1483
- GCC_except_table1486
- GCC_except_table150
- GCC_except_table1551
- GCC_except_table1554
- GCC_except_table1576
- GCC_except_table1615
- GCC_except_table1627
- GCC_except_table1630
- GCC_except_table1644
- GCC_except_table1680
- GCC_except_table1710
- GCC_except_table1722
- GCC_except_table1724
- GCC_except_table1728
- GCC_except_table1732
- GCC_except_table1754
- GCC_except_table1757
- GCC_except_table1767
- GCC_except_table1771
- GCC_except_table1866
- GCC_except_table1927
- GCC_except_table1982
- GCC_except_table2000
- GCC_except_table2154
- GCC_except_table2201
- GCC_except_table2215
- GCC_except_table2216
- GCC_except_table2430
- GCC_except_table2449
- GCC_except_table247
- GCC_except_table2539
- GCC_except_table2550
- GCC_except_table274
- GCC_except_table277
- GCC_except_table292
- GCC_except_table334
- GCC_except_table348
- GCC_except_table370
- GCC_except_table378
- GCC_except_table546
- GCC_except_table673
- GCC_except_table779
- GCC_except_table83
- GCC_except_table944
- GCC_except_table978
CStrings:
+ "Clamping replace-at-cursor delete count %lu to %lu for %@"
```
