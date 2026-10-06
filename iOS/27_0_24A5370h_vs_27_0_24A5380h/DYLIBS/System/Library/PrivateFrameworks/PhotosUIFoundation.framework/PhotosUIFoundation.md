## PhotosUIFoundation

> `/System/Library/PrivateFrameworks/PhotosUIFoundation.framework/PhotosUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf298c` | `0xf5080` | **`+0x26f4`** |
| `__TEXT.__const` | `0x6d80` | `0x70d0` | **`+0x350`** |
| `__DATA.__bss` | `0x6750` | `0x6a50` | **`+0x300`** |
| `__AUTH_CONST.__const` | `0x5c90` | `0x5f68` | **`+0x2d8`** |
| `__AUTH.__objc_data` | `0x4c10` | `0x49e0` | **`-0x230`** |
| `__DATA_DIRTY.__objc_data` | `0x460` | `0x690` | **`+0x230`** |
| `__DATA.__data` | `0x4658` | `0x4800` | **`+0x1a8`** |
| `__AUTH_CONST.__objc_const` | `0x1efb8` | `0x1f0c8` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x1936` | `0x1a3a` | **`+0x104`** |
| `__TEXT.__swift5_reflstr` | `0x16f7` | `0x17c7` | **`+0xd0`** |
| `__TEXT.__constg_swiftt` | `0x387c` | `0x3948` | **`+0xcc`** |
| `__TEXT.__unwind_info` | `0x5610` | `0x56d8` | **`+0xc8`** |
| `__TEXT.__swift5_typeref` | `0x2c74` | `0x2d34` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x1a98` | `0x1b50` | **`+0xb8`** |
| `__TEXT.__objc_methlist` | `0xfb64` | `0xfbe4` | **`+0x80`** |
| `__TEXT.__swift5_assocty` | `0x958` | `0x9b8` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0xd28` | `0xd84` | **`+0x5c`** |
| `__DATA_CONST.__const` | `0x3ee8` | `0x3f40` | **`+0x58`** |
| `__TEXT.__cstring` | `0xb9d6` | `0xba26` | **`+0x50`** |
| `__DATA_CONST.__got` | `0xe70` | `0xe90` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x77b0` | `0x77d0` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x394` | `0x3ac` | **`+0x18`** |
| `__AUTH.__data` | `0x1b80` | `0x1b70` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x250` | `0x260` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1930` | `0x1938` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x8` | `—` | **`-0x8`** |

### Other Changes

```diff

-910.21.101.0.0
+910.27.103.0.0

-  Functions: 9427
-  Symbols:   11079
-  CStrings:  1579
+  Functions: 9511
+  Symbols:   11102
+  CStrings:  1582
Symbols:
+ -[PXScrollViewController scrollViewSafeAreaInsetsDidChange]
+ -[PXScrollViewControllerExtendedTraitCollection scrollViewControllerSafeAreaInsetsDidChange:]
+ -[PXUIScrollViewController scrollViewSafeAreaInsetsDidChange:]
+ -[_PXUIScrollView safeAreaInsetsDidChange]
+ GCC_except_table1130
+ GCC_except_table1134
+ GCC_except_table1137
+ GCC_except_table1140
+ GCC_except_table1148
+ GCC_except_table1152
+ GCC_except_table1159
+ GCC_except_table1161
+ GCC_except_table1163
+ GCC_except_table1165
+ GCC_except_table1167
+ GCC_except_table1169
+ GCC_except_table1171
+ GCC_except_table1177
+ GCC_except_table1239
+ GCC_except_table1304
+ GCC_except_table1566
+ GCC_except_table1576
+ GCC_except_table1601
+ GCC_except_table1627
+ GCC_except_table1847
+ GCC_except_table1868
+ GCC_except_table1877
+ GCC_except_table1879
+ GCC_except_table1896
+ GCC_except_table1935
+ GCC_except_table1938
+ GCC_except_table2075
+ GCC_except_table2090
+ GCC_except_table2108
+ GCC_except_table2148
+ GCC_except_table2236
+ GCC_except_table2400
+ GCC_except_table2618
+ GCC_except_table2652
+ GCC_except_table2653
+ GCC_except_table2680
+ GCC_except_table2949
+ GCC_except_table3048
+ GCC_except_table3050
+ GCC_except_table3103
+ GCC_except_table3117
+ GCC_except_table3121
+ GCC_except_table3128
+ GCC_except_table3135
+ GCC_except_table3150
+ GCC_except_table3157
+ GCC_except_table3171
+ GCC_except_table3440
+ GCC_except_table3475
+ GCC_except_table3496
+ GCC_except_table3576
+ GCC_except_table3578
+ GCC_except_table3613
+ GCC_except_table3644
+ GCC_except_table3648
+ GCC_except_table3664
+ GCC_except_table3711
+ GCC_except_table3727
+ GCC_except_table4024
+ GCC_except_table4034
+ GCC_except_table4097
+ GCC_except_table4251
+ GCC_except_table4362
+ GCC_except_table4388
+ GCC_except_table4539
+ GCC_except_table4658
+ GCC_except_table4937
+ GCC_except_table4939
+ GCC_except_table4950
+ GCC_except_table4953
+ GCC_except_table4977
+ GCC_except_table4985
+ GCC_except_table4989
+ GCC_except_table4993
+ GCC_except_table5026
+ GCC_except_table5085
+ GCC_except_table5111
+ GCC_except_table5152
+ __INSTANCE_METHODS__TtC18PhotosUIFoundation29PXSectionedItemIndexPathStore
+ __IVARS__TtC18PhotosUIFoundation29PXSectionedItemIndexPathStore
+ ___93-[PXScrollViewControllerExtendedTraitCollection scrollViewControllerSafeAreaInsetsDidChange:]_block_invoke
+ ___unnamed_14
+ _associated conformance 18PhotosUIFoundation36PXSectionedItemIndexPathStoreChangedVs10SetAlgebraAASQ
+ _associated conformance 18PhotosUIFoundation36PXSectionedItemIndexPathStoreChangedVs10SetAlgebraAAs25ExpressibleByArrayLiteral
+ _associated conformance 18PhotosUIFoundation36PXSectionedItemIndexPathStoreChangedVs9OptionSetAASY
+ _associated conformance 18PhotosUIFoundation36PXSectionedItemIndexPathStoreChangedVs9OptionSetAAs0J7Algebra
+ _symbolic SDy_____xG So17PXSimpleIndexPathV
+ _symbolic So28PXSectionedDataSourceManagerC
+ _symbolic _____ 18PhotosUIFoundation29PXSectionedItemIndexPathStoreC
+ _symbolic _____ 18PhotosUIFoundation29PXSectionedItemIndexPathStoreC7MutableV
+ _symbolic _____ 18PhotosUIFoundation36PXSectionedItemIndexPathStoreChangedV
+ _symbolic _____ 18PhotosUIFoundation37PXSectionedItemIndexPathStoreSnapshotV
+ _symbolic _____yShyq_GG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____y_____yxq__GG 15Synchronization5MutexVAARi_zrlE 18PhotosUIFoundation0C23GroupingItemListManagerC10FetchState33_3A652BCC3445EDB1AAAB99EC2AE5C997LLV
+ _symbolic _____yxG 18PhotosUIFoundation29PXSectionedItemIndexPathStoreC
+ _symbolic _____yxG 18PhotosUIFoundation37PXSectionedItemIndexPathStoreSnapshotV
+ _symbolic _____yxGSgXw 18PhotosUIFoundation29PXSectionedItemIndexPathStoreC
+ _symbolic _____yxGSgXwz_x_lXX 18PhotosUIFoundation29PXSectionedItemIndexPathStoreC
+ _symbolic _____yx_G 18PhotosUIFoundation29PXSectionedItemIndexPathStoreC7MutableV
+ _symbolic _____yx_GIegn_ 18PhotosUIFoundation29PXSectionedItemIndexPathStoreC7MutableV
+ _type_layout_string 18PhotosUIFoundation36PXSectionedItemIndexPathStoreChangedV
+ _type_layout_string l18PhotosUIFoundation29PXSectionedItemIndexPathStoreC7MutableVyx_G
+ _type_layout_string l18PhotosUIFoundation37PXSectionedItemIndexPathStoreSnapshotVyxG
- GCC_except_table1129
- GCC_except_table1133
- GCC_except_table1136
- GCC_except_table1139
- GCC_except_table1147
- GCC_except_table1151
- GCC_except_table1158
- GCC_except_table1160
- GCC_except_table1162
- GCC_except_table1164
- GCC_except_table1166
- GCC_except_table1168
- GCC_except_table1170
- GCC_except_table1176
- GCC_except_table1238
- GCC_except_table1303
- GCC_except_table1565
- GCC_except_table1575
- GCC_except_table1600
- GCC_except_table1626
- GCC_except_table1846
- GCC_except_table1867
- GCC_except_table1876
- GCC_except_table1878
- GCC_except_table1895
- GCC_except_table1933
- GCC_except_table1937
- GCC_except_table2074
- GCC_except_table2089
- GCC_except_table2107
- GCC_except_table2147
- GCC_except_table2235
- GCC_except_table2399
- GCC_except_table2615
- GCC_except_table2649
- GCC_except_table2650
- GCC_except_table2677
- GCC_except_table2945
- GCC_except_table3043
- GCC_except_table3045
- GCC_except_table3098
- GCC_except_table3112
- GCC_except_table3116
- GCC_except_table3123
- GCC_except_table3130
- GCC_except_table3145
- GCC_except_table3152
- GCC_except_table3166
- GCC_except_table3435
- GCC_except_table3470
- GCC_except_table3491
- GCC_except_table3571
- GCC_except_table3573
- GCC_except_table3608
- GCC_except_table3639
- GCC_except_table3643
- GCC_except_table3659
- GCC_except_table3706
- GCC_except_table3722
- GCC_except_table4019
- GCC_except_table4029
- GCC_except_table4092
- GCC_except_table4246
- GCC_except_table4357
- GCC_except_table4378
- GCC_except_table4534
- GCC_except_table4653
- GCC_except_table4932
- GCC_except_table4934
- GCC_except_table4945
- GCC_except_table4948
- GCC_except_table4967
- GCC_except_table4980
- GCC_except_table4984
- GCC_except_table4988
- GCC_except_table5021
- GCC_except_table5080
- GCC_except_table5106
- GCC_except_table5147
- _get_type_metadata 11Observation10ObservableRzs16SendableMetatypeRzr0_l15Synchronization5MutexVySiG noncopyable
- _get_type_metadata 15Synchronization5MutexVySbG noncopyable
- _get_type_metadata 18PhotosUIFoundation0A15ItemListManagerRzs16SendableMetatypeRzAA0aC0R_10IdentifierQy_2IDRt_r0_l15Synchronization5MutexVyAA0a8GroupingcdE0C10FetchState33_3A652BCC3445EDB1AAAB99EC2AE5C997LLVyxq__GG noncopyable
- _get_type_metadata RlzCs16SendableMetatypeRz6TargetQy_Rsz18PhotosUIFoundation22ObservingUpdaterEntityR_r0_l15Synchronization5MutexVyShyq_GG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "PXSectionedItemIndexPathStore: data source changed from %ld to %ld without change details — dropping %ld entries"
+ "PXSectionedItemIndexPathStore: data source changed from %ld to %ld without incremental change details — dropping %ld entries"
+ "PhotosUIFoundation.PXSectionedItemIndexPathStore"
```
