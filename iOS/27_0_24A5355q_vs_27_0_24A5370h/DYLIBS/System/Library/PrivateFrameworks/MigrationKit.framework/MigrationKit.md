## MigrationKit

> `/System/Library/PrivateFrameworks/MigrationKit.framework/MigrationKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70cbdc` | `0x70f2b4` | **`+0x26d8`** |
| `__TEXT.__const` | `0x3a3a0` | `0x39650` | **`-0xd50`** |
| `__TEXT.__unwind_info` | `0x17e20` | `0x186f0` | **`+0x8d0`** |
| `__AUTH_CONST.__const` | `0x1a760` | `0x1aa68` | **`+0x308`** |
| `__TEXT.__eh_frame` | `0x4514c` | `0x451ec` | **`+0xa0`** |
| `__DATA.__bss` | `0x3e950` | `0x3e9d0` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0xfcec` | `0xfd6c` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0xcb62` | `0xcbc2` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0xedf4` | `0xee40` | **`+0x4c`** |
| `__TEXT.__swift5_fieldmd` | `0xdcd4` | `0xdd20` | **`+0x4c`** |
| `__AUTH_CONST.__objc_const` | `0x1bda8` | `0x1bde8` | **`+0x40`** |
| `__AUTH.__data` | `0x16d80` | `0x16db0` | **`+0x30`** |
| `__DATA.__data` | `0xded8` | `0xdf08` | **`+0x30`** |
| `__TEXT.__cstring` | `0x194d1` | `0x19501` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x3c48` | `0x3c68` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x3478` | `0x3490` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x4cd8` | `0x4cf0` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0xbf0d` | `0xbf13` | **`+0x6`** |
| `__TEXT.__swift5_proto` | `0x23cc` | `0x23d0` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0xce8` | `0xcec` | **`+0x4`** |

### Other Changes

```diff

-1410.0.0.0.0
+1413.0.0.0.0

-  Functions: 24749
-  Symbols:   10157
-  CStrings:  4268
+  Functions: 24772
+  Symbols:   10161
+  CStrings:  4271
Symbols:
+ __ZNKSt3__113__string_hashIcNS_9allocatorIcEEEclB9fqe220106ERKNS_12basic_stringIcNS_11char_traitsIcEES2_EE
+ __ZNKSt3__121__murmur2_or_cityhashImLm64EEclB9fqe220106EPKvm
+ __ZNKSt3__18equal_toINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEEclB9fqe220106ERKS6_S9_
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__112__hash_tableINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE3sigEENS_22__unordered_map_hasherIS7_NS_4pairIKS7_S8_EENS_4hashIS7_EENS_8equal_toIS7_EEEENS_21__unordered_map_equalIS7_SD_SH_SF_EENS5_ISD_EEE17__deallocate_nodeB9fqe220106EPNS_11__hash_nodeIS9_PvEE
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__113unordered_mapINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE3sigNS_4hashIS6_EENS_8equal_toIS6_EENS4_INS_4pairIKS6_S7_EEEEED1B9fqe220106Ev
+ __ZNSt3__117__call_once_proxyB9fqe220106INS_5tupleIJOZN12migrationkit9signature14get_identifierEPKhmE3$_0EEEEEvPv
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__121__murmur2_or_cityhashImLm64EE18__hash_len_0_to_16B9fqe220106EPKcm
+ __ZNSt3__121__murmur2_or_cityhashImLm64EE19__hash_len_17_to_32B9fqe220106EPKcm
+ __ZNSt3__121__murmur2_or_cityhashImLm64EE19__hash_len_33_to_64B9fqe220106EPKcm
+ __ZNSt3__122__hash_node_destructorINS_9allocatorINS_11__hash_nodeINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS1_IcEEEE3sigEEPvEEEEEclB9fqe220106EPSC_
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ __ZZNSt3__112__hash_tableINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE3sigEENS_22__unordered_map_hasherIS7_NS_4pairIKS7_S8_EENS_4hashIS7_EENS_8equal_toIS7_EEEENS_21__unordered_map_equalIS7_SD_SH_SF_EENS5_ISD_EEE16__emplace_uniqueB9fqe220106IJRKSD_EEENSB_INS_15__hash_iteratorIPNS_11__hash_nodeIS9_PvEEEEbEEDpOT_ENKUlRSC_SP_E_clES10_SP_
+ ___swift_closure_destructor.94Tm
+ ___swift_memcpy3_1
+ _swift_release_x11
+ _symbolic _____ 12MigrationKit19WirelessFrequenciesV
+ _type_layout_string 12MigrationKit19WirelessFrequenciesV
- __ZNKSt3__113__string_hashIcNS_9allocatorIcEEEclB9fqe220100ERKNS_12basic_stringIcNS_11char_traitsIcEES2_EE
- __ZNKSt3__121__murmur2_or_cityhashImLm64EEclB9fqe220100EPKvm
- __ZNKSt3__18equal_toINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEEclB9fqe220100ERKS6_S9_
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__112__hash_tableINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE3sigEENS_22__unordered_map_hasherIS7_NS_4pairIKS7_S8_EENS_4hashIS7_EENS_8equal_toIS7_EEEENS_21__unordered_map_equalIS7_SD_SH_SF_EENS5_ISD_EEE17__deallocate_nodeB9fqe220100EPNS_11__hash_nodeIS9_PvEE
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__113unordered_mapINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE3sigNS_4hashIS6_EENS_8equal_toIS6_EENS4_INS_4pairIKS6_S7_EEEEED1B9fqe220100Ev
- __ZNSt3__117__call_once_proxyB9fqe220100INS_5tupleIJOZN12migrationkit9signature14get_identifierEPKhmE3$_0EEEEEvPv
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__121__murmur2_or_cityhashImLm64EE18__hash_len_0_to_16B9fqe220100EPKcm
- __ZNSt3__121__murmur2_or_cityhashImLm64EE19__hash_len_17_to_32B9fqe220100EPKcm
- __ZNSt3__121__murmur2_or_cityhashImLm64EE19__hash_len_33_to_64B9fqe220100EPKcm
- __ZNSt3__122__hash_node_destructorINS_9allocatorINS_11__hash_nodeINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS1_IcEEEE3sigEEPvEEEEEclB9fqe220100EPSC_
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- __ZZNSt3__112__hash_tableINS_17__hash_value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE3sigEENS_22__unordered_map_hasherIS7_NS_4pairIKS7_S8_EENS_4hashIS7_EENS_8equal_toIS7_EEEENS_21__unordered_map_equalIS7_SD_SH_SF_EENS5_ISD_EEE16__emplace_uniqueB9fqe220100IJRKSD_EEENSB_INS_15__hash_iteratorIPNS_11__hash_nodeIS9_PvEEEEbEEDpOT_ENKUlRSC_SP_E_clES10_SP_
- ___swift_closure_destructor.95Tm
CStrings:
+ "No common frequencies available\n\tLocal: "
+ "destination already exists, using suffixed name: %s"
+ "selectedCaptionStyleIndex"
+ "will replace top view controller. new_view_controller=%@"
- "No common frequencies available"
```
