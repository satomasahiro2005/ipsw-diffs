## CoreMediaStream

> `/System/Library/PrivateFrameworks/CoreMediaStream.framework/CoreMediaStream`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcbad0` | `0xcd34c` | **`+0x187c`** |
| `__AUTH_CONST.__objc_const` | `0x97d8` | `0x9a58` | **`+0x280`** |
| `__TEXT.__objc_methlist` | `0x8110` | `0x82e0` | **`+0x1d0`** |
| `__AUTH_CONST.__cfstring` | `0x87c0` | `0x8880` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x26a8` | `0x2750` | **`+0xa8`** |
| `__TEXT.__cstring` | `0xa5f7` | `0xa658` | **`+0x61`** |
| `__TEXT.__oslogstring` | `0xef75` | `0xefd1` | **`+0x5c`** |
| `__DATA_CONST.__objc_selrefs` | `0x4150` | `0x4198` | **`+0x48`** |
| `__DATA.__objc_ivar` | `0x6ec` | `0x714` | **`+0x28`** |
| `__TEXT.__const` | `0x238` | `0x248` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2d90` | `0x2d80` | **`-0x10`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Functions: 3597
-  Symbols:   5772
-  CStrings:  2301
+  Functions: 3636
+  Symbols:   5821
+  CStrings:  2308
Symbols:
+ +[MSProtocolUtilities _errorForSCMigrationStatusCode:migrationSubstate:cloudDbErrorName:]
+ -[CancelSharedCollectionsMigrationResponse .cxx_destruct]
+ -[CancelSharedCollectionsMigrationResponse cloudDbErrorName]
+ -[CancelSharedCollectionsMigrationResponse hasCloudDbErrorName]
+ -[CancelSharedCollectionsMigrationResponse hasMigrationSubstate]
+ -[CancelSharedCollectionsMigrationResponse migrationSubstate]
+ -[CancelSharedCollectionsMigrationResponse setCloudDbErrorName:]
+ -[CancelSharedCollectionsMigrationResponse setHasMigrationSubstate:]
+ -[CancelSharedCollectionsMigrationResponse setMigrationSubstate:]
+ -[CompleteSharedCollectionsMigrationResponse .cxx_destruct]
+ -[CompleteSharedCollectionsMigrationResponse cloudDbErrorName]
+ -[CompleteSharedCollectionsMigrationResponse hasCloudDbErrorName]
+ -[CompleteSharedCollectionsMigrationResponse hasMigrationSubstate]
+ -[CompleteSharedCollectionsMigrationResponse migrationSubstate]
+ -[CompleteSharedCollectionsMigrationResponse setCloudDbErrorName:]
+ -[CompleteSharedCollectionsMigrationResponse setHasMigrationSubstate:]
+ -[CompleteSharedCollectionsMigrationResponse setMigrationSubstate:]
+ -[FailSharedCollectionsMigrationResponse .cxx_destruct]
+ -[FailSharedCollectionsMigrationResponse cloudDbErrorName]
+ -[FailSharedCollectionsMigrationResponse hasCloudDbErrorName]
+ -[FailSharedCollectionsMigrationResponse hasMigrationSubstate]
+ -[FailSharedCollectionsMigrationResponse migrationSubstate]
+ -[FailSharedCollectionsMigrationResponse setCloudDbErrorName:]
+ -[FailSharedCollectionsMigrationResponse setHasMigrationSubstate:]
+ -[FailSharedCollectionsMigrationResponse setMigrationSubstate:]
+ -[InitiateSharedCollectionsMigrationRequest archivedAlbumName]
+ -[InitiateSharedCollectionsMigrationRequest hasArchivedAlbumName]
+ -[InitiateSharedCollectionsMigrationRequest setArchivedAlbumName:]
+ -[InitiateSharedCollectionsMigrationResponse cloudDbErrorName]
+ -[InitiateSharedCollectionsMigrationResponse hasCloudDbErrorName]
+ -[InitiateSharedCollectionsMigrationResponse hasMigrationSubstate]
+ -[InitiateSharedCollectionsMigrationResponse migrationSubstate]
+ -[InitiateSharedCollectionsMigrationResponse setCloudDbErrorName:]
+ -[InitiateSharedCollectionsMigrationResponse setHasMigrationSubstate:]
+ -[InitiateSharedCollectionsMigrationResponse setMigrationSubstate:]
+ -[MSAlbumSharingDaemon updateOwnerReputationScoreForAlbum:withAddress:]
+ -[UnarchiveSharedCollectionsMigrationResponse .cxx_destruct]
+ -[UnarchiveSharedCollectionsMigrationResponse cloudDbErrorName]
+ -[UnarchiveSharedCollectionsMigrationResponse hasCloudDbErrorName]
+ -[UnarchiveSharedCollectionsMigrationResponse hasMigrationSubstate]
+ -[UnarchiveSharedCollectionsMigrationResponse migrationSubstate]
+ -[UnarchiveSharedCollectionsMigrationResponse setCloudDbErrorName:]
+ -[UnarchiveSharedCollectionsMigrationResponse setHasMigrationSubstate:]
+ -[UnarchiveSharedCollectionsMigrationResponse setMigrationSubstate:]
+ GCC_except_table1075
+ GCC_except_table1076
+ GCC_except_table1079
+ GCC_except_table1080
+ GCC_except_table1081
+ GCC_except_table1082
+ GCC_except_table1083
+ GCC_except_table1085
+ GCC_except_table1086
+ GCC_except_table1087
+ GCC_except_table1088
+ GCC_except_table1125
+ GCC_except_table1126
+ GCC_except_table1129
+ GCC_except_table1135
+ GCC_except_table1175
+ GCC_except_table1180
+ GCC_except_table1187
+ GCC_except_table1190
+ GCC_except_table1200
+ GCC_except_table1340
+ GCC_except_table1347
+ GCC_except_table1353
+ GCC_except_table1584
+ GCC_except_table1588
+ GCC_except_table1627
+ GCC_except_table1629
+ GCC_except_table1634
+ GCC_except_table1642
+ GCC_except_table1649
+ GCC_except_table1659
+ GCC_except_table1671
+ GCC_except_table1675
+ GCC_except_table1678
+ GCC_except_table1684
+ GCC_except_table1693
+ GCC_except_table1697
+ GCC_except_table1700
+ GCC_except_table1718
+ GCC_except_table1721
+ GCC_except_table1727
+ GCC_except_table1730
+ GCC_except_table1736
+ GCC_except_table1740
+ GCC_except_table1745
+ GCC_except_table1748
+ GCC_except_table1754
+ GCC_except_table1757
+ GCC_except_table1784
+ GCC_except_table1787
+ GCC_except_table1794
+ GCC_except_table1798
+ GCC_except_table1805
+ GCC_except_table1810
+ GCC_except_table1823
+ GCC_except_table1824
+ GCC_except_table1831
+ GCC_except_table1832
+ GCC_except_table1839
+ GCC_except_table1842
+ GCC_except_table1848
+ GCC_except_table1851
+ GCC_except_table1857
+ GCC_except_table1861
+ GCC_except_table1875
+ GCC_except_table1880
+ GCC_except_table1887
+ GCC_except_table1890
+ GCC_except_table1896
+ GCC_except_table1898
+ GCC_except_table1943
+ GCC_except_table1950
+ GCC_except_table1956
+ GCC_except_table1961
+ GCC_except_table1963
+ GCC_except_table1980
+ GCC_except_table1982
+ GCC_except_table2019
+ GCC_except_table2029
+ GCC_except_table2049
+ GCC_except_table2068
+ GCC_except_table2073
+ GCC_except_table2076
+ GCC_except_table2078
+ GCC_except_table2088
+ GCC_except_table2090
+ GCC_except_table2093
+ GCC_except_table2095
+ GCC_except_table2097
+ GCC_except_table2114
+ GCC_except_table2116
+ GCC_except_table2118
+ GCC_except_table2132
+ GCC_except_table2191
+ GCC_except_table2195
+ GCC_except_table2229
+ GCC_except_table2235
+ GCC_except_table2237
+ GCC_except_table2244
+ GCC_except_table2312
+ GCC_except_table2345
+ GCC_except_table2350
+ GCC_except_table2352
+ GCC_except_table2354
+ GCC_except_table2356
+ GCC_except_table2358
+ GCC_except_table2591
+ GCC_except_table2631
+ GCC_except_table2632
+ GCC_except_table2633
+ GCC_except_table2635
+ GCC_except_table2645
+ GCC_except_table2675
+ GCC_except_table2676
+ GCC_except_table2677
+ GCC_except_table2678
+ GCC_except_table2679
+ GCC_except_table2681
+ GCC_except_table2682
+ GCC_except_table2683
+ GCC_except_table2696
+ GCC_except_table2765
+ GCC_except_table2788
+ GCC_except_table2790
+ GCC_except_table2794
+ GCC_except_table2796
+ GCC_except_table2798
+ GCC_except_table2887
+ GCC_except_table2889
+ GCC_except_table2899
+ GCC_except_table2901
+ GCC_except_table2904
+ GCC_except_table2906
+ GCC_except_table3050
+ GCC_except_table3058
+ GCC_except_table3071
+ GCC_except_table3139
+ GCC_except_table3159
+ GCC_except_table3163
+ GCC_except_table3171
+ GCC_except_table3181
+ GCC_except_table3187
+ GCC_except_table3193
+ GCC_except_table3203
+ GCC_except_table3206
+ GCC_except_table3208
+ GCC_except_table3211
+ GCC_except_table3214
+ GCC_except_table3218
+ GCC_except_table3222
+ GCC_except_table3224
+ GCC_except_table3228
+ GCC_except_table3230
+ GCC_except_table3302
+ GCC_except_table3305
+ GCC_except_table3307
+ GCC_except_table3310
+ GCC_except_table3313
+ GCC_except_table3389
+ GCC_except_table3412
+ GCC_except_table3418
+ GCC_except_table3427
+ GCC_except_table3465
+ GCC_except_table3470
+ GCC_except_table3603
+ GCC_except_table3615
+ GCC_except_table3619
+ GCC_except_table3623
+ GCC_except_table739
+ GCC_except_table743
+ GCC_except_table861
+ GCC_except_table862
+ GCC_except_table863
+ GCC_except_table864
+ GCC_except_table865
+ GCC_except_table866
+ GCC_except_table954
+ OBJC_IVAR_$_CancelSharedCollectionsMigrationResponse._cloudDbErrorName
+ OBJC_IVAR_$_CancelSharedCollectionsMigrationResponse._migrationSubstate
+ OBJC_IVAR_$_CompleteSharedCollectionsMigrationResponse._cloudDbErrorName
+ OBJC_IVAR_$_CompleteSharedCollectionsMigrationResponse._migrationSubstate
+ OBJC_IVAR_$_FailSharedCollectionsMigrationResponse._cloudDbErrorName
+ OBJC_IVAR_$_FailSharedCollectionsMigrationResponse._migrationSubstate
+ OBJC_IVAR_$_InitiateSharedCollectionsMigrationRequest._archivedAlbumName
+ OBJC_IVAR_$_InitiateSharedCollectionsMigrationResponse._cloudDbErrorName
+ OBJC_IVAR_$_InitiateSharedCollectionsMigrationResponse._migrationSubstate
+ OBJC_IVAR_$_UnarchiveSharedCollectionsMigrationResponse._cloudDbErrorName
+ OBJC_IVAR_$_UnarchiveSharedCollectionsMigrationResponse._migrationSubstate
- +[MSProtocolUtilities _errorForSCMigrationStatusCode:]
- -[InitiateSharedCollectionsMigrationRequest archiveTitle]
- -[InitiateSharedCollectionsMigrationRequest hasArchiveTitle]
- -[InitiateSharedCollectionsMigrationRequest setArchiveTitle:]
- -[MSAlbumSharingDaemon updateOwnerReputationScoreForAlbum:]
- GCC_except_table1059
- GCC_except_table1060
- GCC_except_table1063
- GCC_except_table1064
- GCC_except_table1065
- GCC_except_table1066
- GCC_except_table1067
- GCC_except_table1069
- GCC_except_table1070
- GCC_except_table1071
- GCC_except_table1072
- GCC_except_table1109
- GCC_except_table1110
- GCC_except_table1113
- GCC_except_table1119
- GCC_except_table1159
- GCC_except_table1164
- GCC_except_table1171
- GCC_except_table1174
- GCC_except_table1184
- GCC_except_table1324
- GCC_except_table1331
- GCC_except_table1337
- GCC_except_table1553
- GCC_except_table1557
- GCC_except_table1596
- GCC_except_table1597
- GCC_except_table1598
- GCC_except_table1603
- GCC_except_table1607
- GCC_except_table1611
- GCC_except_table1618
- GCC_except_table1631
- GCC_except_table1640
- GCC_except_table1644
- GCC_except_table1647
- GCC_except_table1653
- GCC_except_table1656
- GCC_except_table1666
- GCC_except_table1690
- GCC_except_table1696
- GCC_except_table1699
- GCC_except_table1705
- GCC_except_table1709
- GCC_except_table1714
- GCC_except_table1717
- GCC_except_table1723
- GCC_except_table1726
- GCC_except_table1732
- GCC_except_table1743
- GCC_except_table1753
- GCC_except_table1756
- GCC_except_table1767
- GCC_except_table1770
- GCC_except_table1779
- GCC_except_table1792
- GCC_except_table1793
- GCC_except_table1800
- GCC_except_table1808
- GCC_except_table1811
- GCC_except_table1817
- GCC_except_table1820
- GCC_except_table1826
- GCC_except_table1830
- GCC_except_table1834
- GCC_except_table1844
- GCC_except_table1849
- GCC_except_table1856
- GCC_except_table1859
- GCC_except_table1867
- GCC_except_table1912
- GCC_except_table1919
- GCC_except_table1925
- GCC_except_table1930
- GCC_except_table1932
- GCC_except_table1949
- GCC_except_table1951
- GCC_except_table1988
- GCC_except_table1998
- GCC_except_table2011
- GCC_except_table2016
- GCC_except_table2018
- GCC_except_table2037
- GCC_except_table2045
- GCC_except_table2057
- GCC_except_table2059
- GCC_except_table2062
- GCC_except_table2064
- GCC_except_table2066
- GCC_except_table2070
- GCC_except_table2083
- GCC_except_table2085
- GCC_except_table2087
- GCC_except_table2152
- GCC_except_table2156
- GCC_except_table2190
- GCC_except_table2196
- GCC_except_table2198
- GCC_except_table2205
- GCC_except_table2273
- GCC_except_table2306
- GCC_except_table2311
- GCC_except_table2313
- GCC_except_table2315
- GCC_except_table2317
- GCC_except_table2319
- GCC_except_table2552
- GCC_except_table2592
- GCC_except_table2593
- GCC_except_table2594
- GCC_except_table2596
- GCC_except_table2598
- GCC_except_table2600
- GCC_except_table2601
- GCC_except_table2604
- GCC_except_table2606
- GCC_except_table2636
- GCC_except_table2638
- GCC_except_table2642
- GCC_except_table2644
- GCC_except_table2657
- GCC_except_table2726
- GCC_except_table2749
- GCC_except_table2751
- GCC_except_table2755
- GCC_except_table2757
- GCC_except_table2759
- GCC_except_table2848
- GCC_except_table2850
- GCC_except_table2860
- GCC_except_table2862
- GCC_except_table2865
- GCC_except_table2867
- GCC_except_table3011
- GCC_except_table3019
- GCC_except_table3032
- GCC_except_table3100
- GCC_except_table3103
- GCC_except_table3120
- GCC_except_table3124
- GCC_except_table3128
- GCC_except_table3132
- GCC_except_table3136
- GCC_except_table3140
- GCC_except_table3146
- GCC_except_table3148
- GCC_except_table3152
- GCC_except_table3154
- GCC_except_table3164
- GCC_except_table3169
- GCC_except_table3172
- GCC_except_table3183
- GCC_except_table3189
- GCC_except_table3227
- GCC_except_table3229
- GCC_except_table3263
- GCC_except_table3271
- GCC_except_table3274
- GCC_except_table3350
- GCC_except_table3373
- GCC_except_table3379
- GCC_except_table3388
- GCC_except_table3426
- GCC_except_table3431
- GCC_except_table3564
- GCC_except_table3576
- GCC_except_table3580
- GCC_except_table3584
- GCC_except_table723
- GCC_except_table727
- GCC_except_table845
- GCC_except_table846
- GCC_except_table847
- GCC_except_table848
- GCC_except_table849
- GCC_except_table850
- GCC_except_table938
- OBJC_IVAR_$_InitiateSharedCollectionsMigrationRequest._archiveTitle
CStrings:
+ "%{public}@: Unexpected nil album owner address"
+ "(none)"
+ "@"
+ "SC migration response: status=%{public}@ migrationSubstate=%d cloudDbErrorName=%{public}@"
+ "SC_MIGRATION_ERROR"
+ "SC_MIGRATION_GCBD_RESTRICTED"
+ "archivedAlbumName"
+ "cloudDbErrorName"
+ "migrationSubstate"
- "%{public}@: Unexpected nil album owner email"
- "archiveTitle"
```
