## UIAccessibility

> `/System/Library/PrivateFrameworks/UIAccessibility.framework/UIAccessibility`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6cd7c` | `0x6c9c8` | **`-0x3b4`** |
| `__AUTH_CONST.__cfstring` | `0x64a0` | `0x64e0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x6ba4` | `0x6bdc` | **`+0x38`** |
| `__TEXT.__cstring` | `0x70da` | `0x7101` | **`+0x27`** |
| `__AUTH_CONST.__objc_const` | `0x49f0` | `0x4a10` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x2cc3` | `0x2ca9` | **`-0x1a`** |
| `__DATA_CONST.__objc_selrefs` | `0x5708` | `0x5720` | **`+0x18`** |

### Other Changes

```diff

-3234.5.0.0.0
+3237.1.0.0.0

-  Functions: 2612
-  Symbols:   4575
+  Functions: 2616
+  Symbols:   4579
Symbols:
+ -[NSObject(AXPrivCategory) _accessibilityLineForIndex:]
+ -[UITextAttachmentAccessibilityElement accessibilityImageDataSize]
+ -[UITextAttachmentAccessibilityElement accessibilityImageDataWithParameters:]
+ GCC_except_table1009
+ GCC_except_table1020
+ GCC_except_table1053
+ GCC_except_table1061
+ GCC_except_table1066
+ GCC_except_table1102
+ GCC_except_table1119
+ GCC_except_table1225
+ GCC_except_table1328
+ GCC_except_table1336
+ GCC_except_table1338
+ GCC_except_table1340
+ GCC_except_table1351
+ GCC_except_table1363
+ GCC_except_table1396
+ GCC_except_table1406
+ GCC_except_table1408
+ GCC_except_table1483
+ GCC_except_table1486
+ GCC_except_table1551
+ GCC_except_table1554
+ GCC_except_table1576
+ GCC_except_table1615
+ GCC_except_table1627
+ GCC_except_table1630
+ GCC_except_table1644
+ GCC_except_table1680
+ GCC_except_table1710
+ GCC_except_table1722
+ GCC_except_table1724
+ GCC_except_table1728
+ GCC_except_table1732
+ GCC_except_table1754
+ GCC_except_table1757
+ GCC_except_table1759
+ GCC_except_table1764
+ GCC_except_table1767
+ GCC_except_table1771
+ GCC_except_table1866
+ GCC_except_table1927
+ GCC_except_table1982
+ GCC_except_table2000
+ GCC_except_table2154
+ GCC_except_table2201
+ GCC_except_table2207
+ GCC_except_table2215
+ GCC_except_table2216
+ GCC_except_table2430
+ GCC_except_table2449
+ GCC_except_table2539
+ GCC_except_table2550
+ GCC_except_table944
+ GCC_except_table978
+ __UIAXRetainedAttachmentElement
- GCC_except_table1008
- GCC_except_table1019
- GCC_except_table1052
- GCC_except_table1060
- GCC_except_table1065
- GCC_except_table1101
- GCC_except_table1118
- GCC_except_table1224
- GCC_except_table1327
- GCC_except_table1335
- GCC_except_table1337
- GCC_except_table1339
- GCC_except_table1350
- GCC_except_table1362
- GCC_except_table1395
- GCC_except_table1404
- GCC_except_table1407
- GCC_except_table1482
- GCC_except_table1485
- GCC_except_table1550
- GCC_except_table1553
- GCC_except_table1575
- GCC_except_table1614
- GCC_except_table1626
- GCC_except_table1629
- GCC_except_table1643
- GCC_except_table1679
- GCC_except_table1709
- GCC_except_table1721
- GCC_except_table1723
- GCC_except_table1727
- GCC_except_table1731
- GCC_except_table1753
- GCC_except_table1756
- GCC_except_table1758
- GCC_except_table1763
- GCC_except_table1766
- GCC_except_table1770
- GCC_except_table1865
- GCC_except_table1926
- GCC_except_table1981
- GCC_except_table1999
- GCC_except_table2151
- GCC_except_table2198
- GCC_except_table2203
- GCC_except_table2211
- GCC_except_table2212
- GCC_except_table2426
- GCC_except_table2445
- GCC_except_table2535
- GCC_except_table2546
- GCC_except_table943
- GCC_except_table977
CStrings:
+ "ImageAttachment-%lu"
+ "TextAttachment-%lu"
- "%ld"
- "RequestAttributeValue"
```
