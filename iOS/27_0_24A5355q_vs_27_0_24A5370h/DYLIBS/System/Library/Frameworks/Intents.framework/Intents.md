## Intents

> `/System/Library/Frameworks/Intents.framework/Intents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4606c8` | `0x45fbf8` | **`-0xad0`** |
| `__TEXT.__oslogstring` | `0x5a88` | `0x600d` | **`+0x585`** |
| `__TEXT.__cstring` | `0x478ce` | `0x479cd` | **`+0xff`** |
| `__TEXT.__gcc_except_tab` | `0x20d8` | `0x2164` | **`+0x8c`** |
| `__AUTH_CONST.__auth_got` | `0x800` | `0x838` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x42980` | `0x429a0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2898` | `0x28a8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x11a30` | `0x11a40` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x154a0` | `0x154a8` | **`+0x8`** |

### Other Changes

```diff

-4016.0.41.16.102
+4016.0.42.4.0

-  Functions: 30695
-  Symbols:   51816
-  CStrings:  9655
+  Functions: 30704
+  Symbols:   51835
+  CStrings:  9685
Symbols:
+ GCC_except_table10138
+ GCC_except_table10148
+ GCC_except_table10150
+ GCC_except_table10155
+ GCC_except_table10220
+ GCC_except_table10226
+ GCC_except_table10779
+ GCC_except_table10904
+ GCC_except_table10908
+ GCC_except_table11021
+ GCC_except_table11134
+ GCC_except_table11161
+ GCC_except_table11162
+ GCC_except_table11384
+ GCC_except_table11826
+ GCC_except_table12116
+ GCC_except_table1218
+ GCC_except_table12559
+ GCC_except_table12566
+ GCC_except_table12569
+ GCC_except_table12577
+ GCC_except_table12598
+ GCC_except_table1268
+ GCC_except_table13203
+ GCC_except_table1324
+ GCC_except_table1343
+ GCC_except_table1353
+ GCC_except_table13737
+ GCC_except_table13776
+ GCC_except_table13780
+ GCC_except_table14025
+ GCC_except_table14552
+ GCC_except_table15232
+ GCC_except_table15236
+ GCC_except_table1619
+ GCC_except_table16376
+ GCC_except_table16487
+ GCC_except_table16488
+ GCC_except_table16790
+ GCC_except_table18436
+ GCC_except_table19091
+ GCC_except_table19261
+ GCC_except_table19288
+ GCC_except_table19853
+ GCC_except_table19855
+ GCC_except_table19858
+ GCC_except_table19936
+ GCC_except_table20936
+ GCC_except_table21031
+ GCC_except_table21253
+ GCC_except_table22321
+ GCC_except_table22324
+ GCC_except_table22327
+ GCC_except_table22942
+ GCC_except_table22959
+ GCC_except_table23675
+ GCC_except_table2510
+ GCC_except_table25149
+ GCC_except_table25161
+ GCC_except_table2544
+ GCC_except_table27032
+ GCC_except_table27035
+ GCC_except_table27036
+ GCC_except_table27037
+ GCC_except_table27038
+ GCC_except_table2804
+ GCC_except_table2805
+ GCC_except_table28730
+ GCC_except_table28732
+ GCC_except_table28734
+ GCC_except_table28742
+ GCC_except_table28753
+ GCC_except_table2887
+ GCC_except_table2923
+ GCC_except_table2955
+ GCC_except_table29809
+ GCC_except_table29815
+ GCC_except_table29823
+ GCC_except_table29825
+ GCC_except_table29826
+ GCC_except_table29827
+ GCC_except_table29828
+ GCC_except_table29830
+ GCC_except_table30019
+ GCC_except_table3175
+ GCC_except_table3178
+ GCC_except_table3186
+ GCC_except_table3199
+ GCC_except_table4080
+ GCC_except_table4082
+ GCC_except_table4179
+ GCC_except_table4190
+ GCC_except_table4192
+ GCC_except_table4205
+ GCC_except_table4418
+ GCC_except_table5392
+ GCC_except_table5393
+ GCC_except_table5450
+ GCC_except_table5613
+ GCC_except_table5617
+ GCC_except_table5619
+ GCC_except_table5865
+ GCC_except_table6413
+ GCC_except_table6415
+ GCC_except_table6447
+ GCC_except_table6448
+ GCC_except_table6449
+ GCC_except_table6450
+ GCC_except_table6484
+ GCC_except_table7045
+ GCC_except_table7130
+ GCC_except_table7131
+ GCC_except_table7852
+ GCC_except_table8118
+ GCC_except_table815
+ GCC_except_table8463
+ GCC_except_table8467
+ GCC_except_table8715
+ GCC_except_table8717
+ GCC_except_table9394
+ GCC_except_table9950
+ _INSecurityScopeFlagsAreDefault
+ _INSecurityScopeHasValidSignature
+ _INSecurityScopeIsStructurallyWellFormed
+ _INSecurityScopeResolvedURL
+ _INSecurityScopeValidatedURL
+ __INFieldEquals
+ __INTokenField
+ __INTokenLengthFromScopeData
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE11INSystemAppEENS_19__map_value_compareIS7_NS_4pairIKS7_S8_EENS_4lessIS7_EEEENS5_ISD_EEE12__find_equalB9fqe220106IS7_EENSB_IPNS_15__tree_end_nodeIPNS_16__tree_node_baseIPvEEEERSO_EERKT_
+ __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE11INSystemAppEENS_19__map_value_compareIS7_NS_4pairIKS7_S8_EENS_4lessIS7_EEEENS5_ISD_EEE14__tree_deleterclB9fqe220106EPNS_11__tree_nodeIS9_PvEE
+ ___INSecurityScopeResolvedURL_block_invoke
+ ___memcpy_chk
+ _memchr
+ _memcpy
+ _pathconf
+ _sandbox_extension_consume
+ _sandbox_extension_release
+ _strcasecmp
+ _strcmp
+ _strtoull
- GCC_except_table10129
- GCC_except_table10139
- GCC_except_table10141
- GCC_except_table10146
- GCC_except_table10211
- GCC_except_table10217
- GCC_except_table10770
- GCC_except_table10895
- GCC_except_table10899
- GCC_except_table11012
- GCC_except_table11125
- GCC_except_table11152
- GCC_except_table11153
- GCC_except_table11375
- GCC_except_table11817
- GCC_except_table1209
- GCC_except_table12107
- GCC_except_table12550
- GCC_except_table12557
- GCC_except_table12560
- GCC_except_table12568
- GCC_except_table12589
- GCC_except_table1259
- GCC_except_table1315
- GCC_except_table13194
- GCC_except_table1334
- GCC_except_table1344
- GCC_except_table13728
- GCC_except_table13767
- GCC_except_table13771
- GCC_except_table14016
- GCC_except_table14543
- GCC_except_table15223
- GCC_except_table15227
- GCC_except_table1610
- GCC_except_table16367
- GCC_except_table16470
- GCC_except_table16478
- GCC_except_table16781
- GCC_except_table18427
- GCC_except_table19082
- GCC_except_table19252
- GCC_except_table19279
- GCC_except_table19844
- GCC_except_table19846
- GCC_except_table19849
- GCC_except_table19927
- GCC_except_table20927
- GCC_except_table21022
- GCC_except_table21244
- GCC_except_table22312
- GCC_except_table22315
- GCC_except_table22318
- GCC_except_table22933
- GCC_except_table22950
- GCC_except_table23666
- GCC_except_table2501
- GCC_except_table25140
- GCC_except_table25152
- GCC_except_table2535
- GCC_except_table27023
- GCC_except_table27026
- GCC_except_table27027
- GCC_except_table27028
- GCC_except_table27029
- GCC_except_table2795
- GCC_except_table2796
- GCC_except_table28721
- GCC_except_table28723
- GCC_except_table28725
- GCC_except_table28733
- GCC_except_table28735
- GCC_except_table2878
- GCC_except_table2914
- GCC_except_table2946
- GCC_except_table29792
- GCC_except_table29800
- GCC_except_table29805
- GCC_except_table29806
- GCC_except_table29807
- GCC_except_table29808
- GCC_except_table29818
- GCC_except_table29821
- GCC_except_table30010
- GCC_except_table3166
- GCC_except_table3169
- GCC_except_table3177
- GCC_except_table3190
- GCC_except_table4071
- GCC_except_table4073
- GCC_except_table4170
- GCC_except_table4174
- GCC_except_table4181
- GCC_except_table4196
- GCC_except_table4409
- GCC_except_table5383
- GCC_except_table5384
- GCC_except_table5441
- GCC_except_table5601
- GCC_except_table5604
- GCC_except_table5608
- GCC_except_table5847
- GCC_except_table6404
- GCC_except_table6406
- GCC_except_table6438
- GCC_except_table6439
- GCC_except_table6440
- GCC_except_table6441
- GCC_except_table6475
- GCC_except_table7036
- GCC_except_table7121
- GCC_except_table7122
- GCC_except_table7843
- GCC_except_table8109
- GCC_except_table8454
- GCC_except_table8458
- GCC_except_table8706
- GCC_except_table8708
- GCC_except_table9385
- GCC_except_table9941
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE11INSystemAppEENS_19__map_value_compareIS7_NS_4pairIKS7_S8_EENS_4lessIS7_EEEENS5_ISD_EEE12__find_equalB9fqe220100IS7_EENSB_IPNS_15__tree_end_nodeIPNS_16__tree_node_baseIPvEEEERSO_EERKT_
- __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE11INSystemAppEENS_19__map_value_compareIS7_NS_4pairIKS7_S8_EENS_4lessIS7_EEEENS5_ISD_EEE14__tree_deleterclB9fqe220100EPNS_11__tree_nodeIS9_PvEE
CStrings:
+ "%s Filesystem at '%{public}s' is case-%{public}s"
+ "%s Security scope flags check failed: disallowed bits 0x%llx set in '%{public}s'"
+ "%s Security scope flags check failed: missing or oversized flags field"
+ "%s Security scope flags check failed: non-hex flags field '%{public}s'"
+ "%s Security scope path check failed: cannot consume extension: %{public}s"
+ "%s Security scope path check failed: empty file URL path"
+ "%s Security scope path check failed: realpath failed for %{public}s: %{public}s"
+ "%s Security scope path check failed: token missing or empty path field"
+ "%s Security scope path mismatch: token issued for '%{public}s' but file URL resolves to '%{public}s'"
+ "%s Security scope signature check failed: %{public}s"
+ "%s Security scope structural check failed: HMAC prefix is not %zu hex chars"
+ "%s Security scope structural check failed: class '%{public}.*s' is not an app-sandbox file class"
+ "%s Security scope structural check failed: empty scope data"
+ "%s Security scope structural check failed: non-hex character in HMAC prefix"
+ "%s Security scope structural check failed: token exceeds MAX_TOKEN_SIZE (%zu > %zu)"
+ "%s Security scope structural check failed: token missing class field"
+ "%s Security scope structural check failed: token missing path field"
+ "%s Security scope structural check failed: type '%{public}.*s' is not EXTENSION_TYPE_FILE ('%{public}s')"
+ "%s Security scope validation failed: empty scope data or non-file URL"
+ "/.nofollow"
+ "00"
+ "INSecurityScopeFlagsAreDefault"
+ "INSecurityScopeHasValidSignature"
+ "INSecurityScopeIsStructurallyWellFormed"
+ "INSecurityScopeResolvedURL"
+ "INSecurityScopeValidatedURL"
+ "com.apple.app-sandbox.read"
+ "com.apple.app-sandbox.read-write"
+ "insensitive"
+ "sensitive"
```
