## CDMFoundation

> `/System/Library/PrivateFrameworks/CDMFoundation.framework/CDMFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x274b10` | `0x274fcc` | **`+0x4bc`** |
| `__TEXT.__oslogstring` | `0x1dcdf` | `0x1dd56` | **`+0x77`** |
| `__TEXT.__cstring` | `0x1ba02` | `0x1ba45` | **`+0x43`** |
| `__TEXT.__objc_methlist` | `0x8654` | `0x8664` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x53f0` | `0x53f8` | **`+0x8`** |

### Other Changes

```diff

-3600.31.8.0.0
+3600.31.10.0.0

-  Functions: 12838
-  Symbols:   8865
-  CStrings:  4587
+  Functions: 12839
+  Symbols:   8866
+  CStrings:  4589
Symbols:
+ +[CDMBaseSpanMatchService trimTokenizerResponses:toMaxCharacters:]
+ GCC_except_table1056
+ GCC_except_table1062
+ GCC_except_table1066
+ GCC_except_table1069
+ GCC_except_table1089
+ GCC_except_table1102
+ GCC_except_table1107
+ GCC_except_table1118
+ GCC_except_table1125
+ GCC_except_table1129
+ GCC_except_table1132
+ GCC_except_table1152
+ GCC_except_table1157
+ GCC_except_table1162
+ GCC_except_table1165
+ GCC_except_table1193
+ GCC_except_table1253
+ GCC_except_table1281
+ GCC_except_table1307
+ GCC_except_table1326
+ GCC_except_table1344
+ GCC_except_table1354
+ GCC_except_table1394
+ GCC_except_table1403
+ GCC_except_table1424
+ GCC_except_table1449
+ GCC_except_table1452
+ GCC_except_table1646
+ GCC_except_table1674
+ GCC_except_table1678
+ GCC_except_table1694
+ GCC_except_table1696
+ GCC_except_table1727
+ GCC_except_table1744
+ GCC_except_table1749
+ GCC_except_table1765
+ GCC_except_table1770
+ GCC_except_table1773
+ GCC_except_table1795
+ GCC_except_table1806
+ GCC_except_table1811
+ GCC_except_table1815
+ GCC_except_table1826
+ GCC_except_table1863
+ GCC_except_table1867
+ GCC_except_table1869
+ GCC_except_table1890
+ GCC_except_table1935
+ GCC_except_table1942
+ GCC_except_table1946
+ GCC_except_table1955
+ GCC_except_table1969
+ GCC_except_table1976
+ GCC_except_table1986
+ GCC_except_table2000
+ GCC_except_table2008
+ GCC_except_table2026
+ GCC_except_table2030
+ GCC_except_table2037
+ GCC_except_table2048
+ GCC_except_table2149
+ GCC_except_table2153
+ GCC_except_table2156
+ GCC_except_table2163
+ GCC_except_table2172
+ GCC_except_table2178
+ GCC_except_table2182
+ GCC_except_table2185
+ GCC_except_table2189
+ GCC_except_table2191
+ GCC_except_table2207
+ GCC_except_table2210
+ GCC_except_table2213
+ GCC_except_table2296
+ GCC_except_table2331
+ GCC_except_table2336
+ GCC_except_table2356
+ GCC_except_table2445
+ GCC_except_table2447
+ GCC_except_table2467
+ GCC_except_table2492
+ GCC_except_table2503
+ GCC_except_table2533
+ GCC_except_table2535
+ GCC_except_table2538
+ GCC_except_table2566
+ GCC_except_table2593
+ GCC_except_table858
+ GCC_except_table863
+ GCC_except_table871
+ GCC_except_table878
+ GCC_except_table909
+ GCC_except_table924
+ GCC_except_table928
+ GCC_except_table932
+ GCC_except_table987
- GCC_except_table1055
- GCC_except_table1058
- GCC_except_table1064
- GCC_except_table1068
- GCC_except_table1087
- GCC_except_table1101
- GCC_except_table1106
- GCC_except_table1117
- GCC_except_table1124
- GCC_except_table1128
- GCC_except_table1131
- GCC_except_table1147
- GCC_except_table1155
- GCC_except_table1160
- GCC_except_table1164
- GCC_except_table1182
- GCC_except_table1250
- GCC_except_table1280
- GCC_except_table1288
- GCC_except_table1310
- GCC_except_table1343
- GCC_except_table1347
- GCC_except_table1393
- GCC_except_table1399
- GCC_except_table1423
- GCC_except_table1439
- GCC_except_table1450
- GCC_except_table1645
- GCC_except_table1673
- GCC_except_table1677
- GCC_except_table1693
- GCC_except_table1695
- GCC_except_table1722
- GCC_except_table1728
- GCC_except_table1747
- GCC_except_table1764
- GCC_except_table1769
- GCC_except_table1772
- GCC_except_table1775
- GCC_except_table1796
- GCC_except_table1810
- GCC_except_table1814
- GCC_except_table1823
- GCC_except_table1862
- GCC_except_table1866
- GCC_except_table1868
- GCC_except_table1889
- GCC_except_table1933
- GCC_except_table1938
- GCC_except_table1945
- GCC_except_table1952
- GCC_except_table1956
- GCC_except_table1975
- GCC_except_table1981
- GCC_except_table1999
- GCC_except_table2004
- GCC_except_table2025
- GCC_except_table2028
- GCC_except_table2036
- GCC_except_table2047
- GCC_except_table2144
- GCC_except_table2152
- GCC_except_table2154
- GCC_except_table2162
- GCC_except_table2170
- GCC_except_table2173
- GCC_except_table2179
- GCC_except_table2184
- GCC_except_table2188
- GCC_except_table2190
- GCC_except_table2201
- GCC_except_table2209
- GCC_except_table2211
- GCC_except_table2284
- GCC_except_table2330
- GCC_except_table2332
- GCC_except_table2337
- GCC_except_table2429
- GCC_except_table2446
- GCC_except_table2466
- GCC_except_table2489
- GCC_except_table2497
- GCC_except_table2532
- GCC_except_table2534
- GCC_except_table2537
- GCC_except_table2564
- GCC_except_table2592
- GCC_except_table857
- GCC_except_table862
- GCC_except_table865
- GCC_except_table872
- GCC_except_table908
- GCC_except_table918
- GCC_except_table925
- GCC_except_table930
- GCC_except_table975
Functions:
~ ___45-[CDMShortcutDetectorServiceGraph buildGraph]_block_invoke : 624 -> 704
+ +[CDMBaseSpanMatchService trimTokenizerResponses:toMaxCharacters:]
CStrings:
+ "%s Trimmed tokenizer response from %lu to %lu chars (limit=%lu) and from %lu to %lu tokens to bound span matching work"
+ "+[CDMBaseSpanMatchService trimTokenizerResponses:toMaxCharacters:]"
```
