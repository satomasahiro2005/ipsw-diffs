## CoreSuggestions

> `/System/Library/PrivateFrameworks/CoreSuggestions.framework/CoreSuggestions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8e458` | `0x8e4ac` | **`+0x54`** |
| `__AUTH_CONST.__cfstring` | `0xa780` | `0xa7a0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x7d94` | `0x7db2` | **`+0x1e`** |
| `__DATA.__bss` | `0x348` | `0x350` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x4198` | `0x41a0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xa09c` | `0xa0a4` | **`+0x8`** |

### Other Changes

```diff

-1337.0.0.0.0
+1341.0.0.0.0

-  Functions: 3431
-  Symbols:   6410
-  CStrings:  1658
+  Functions: 3432
+  Symbols:   6412
+  CStrings:  1659
Symbols:
+ +[SGEntityTag eventNotAutoAddableToCalendar]
+ GCC_except_table1010
+ GCC_except_table1014
+ GCC_except_table1018
+ GCC_except_table1264
+ GCC_except_table1418
+ GCC_except_table1514
+ GCC_except_table1517
+ GCC_except_table1519
+ GCC_except_table1847
+ GCC_except_table2299
+ GCC_except_table2325
+ GCC_except_table2327
+ GCC_except_table2363
+ GCC_except_table2418
+ GCC_except_table2819
+ GCC_except_table3323
+ GCC_except_table3340
+ GCC_except_table3347
+ GCC_except_table3361
+ GCC_except_table388
+ GCC_except_table491
+ GCC_except_table508
+ GCC_except_table513
+ GCC_except_table519
+ GCC_except_table521
+ GCC_except_table529
+ GCC_except_table609
+ GCC_except_table615
+ GCC_except_table618
+ GCC_except_table626
+ GCC_except_table819
+ GCC_except_table823
+ GCC_except_table826
+ GCC_except_table828
+ GCC_except_table833
+ GCC_except_table850
+ _eventNotAutoAddableToCalendar
- GCC_except_table1009
- GCC_except_table1013
- GCC_except_table1017
- GCC_except_table1263
- GCC_except_table1417
- GCC_except_table1513
- GCC_except_table1516
- GCC_except_table1518
- GCC_except_table1846
- GCC_except_table2298
- GCC_except_table2324
- GCC_except_table2326
- GCC_except_table2362
- GCC_except_table2417
- GCC_except_table2818
- GCC_except_table3322
- GCC_except_table3339
- GCC_except_table3346
- GCC_except_table3360
- GCC_except_table387
- GCC_except_table490
- GCC_except_table507
- GCC_except_table512
- GCC_except_table517
- GCC_except_table520
- GCC_except_table528
- GCC_except_table608
- GCC_except_table614
- GCC_except_table617
- GCC_except_table625
- GCC_except_table818
- GCC_except_table821
- GCC_except_table825
- GCC_except_table827
- GCC_except_table832
- GCC_except_table849
Functions:
~ +[SGEntityTag initialize] : 4892 -> 4964
+ +[SGEntityTag eventNotAutoAddableToCalendar]
CStrings:
+ "eventNotAutoAddableToCalendar"
```
