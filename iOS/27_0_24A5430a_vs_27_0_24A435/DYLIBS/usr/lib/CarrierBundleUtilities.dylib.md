## CarrierBundleUtilities.dylib

> `/usr/lib/CarrierBundleUtilities.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd50c` | `0xddac` | **`+0x8a0`** |
| `__TEXT.__gcc_except_tab` | `0x1158` | `0x11ec` | **`+0x94`** |
| `__TEXT.__oslogstring` | `0x1027` | `0x1081` | **`+0x5a`** |
| `__TEXT.__unwind_info` | `0x7f8` | `0x828` | **`+0x30`** |
| `__TEXT.__cstring` | `0x18b` | `0x1b0` | **`+0x25`** |
| `__AUTH_CONST.__auth_got` | `0x350` | `0x358` | **`+0x8`** |
| `__TEXT.__const` | `0x5e9` | `0x5ea` | **`+0x1`** |

### Other Changes

```diff

-  Functions: 299
-  Symbols:   562
-  CStrings:  116
+  Functions: 305
+  Symbols:   572
+  CStrings:  121
Symbols:
+ GCC_except_table31
+ GCC_except_table34
+ GCC_except_table50
+ GCC_except_table53
+ GCC_except_table61
+ GCC_except_table64
+ GCC_except_table78
+ GCC_except_table79
+ GCC_except_table91
+ GCC_except_table93
+ GCC_except_table94
+ GCC_except_table96
+ __ZN13CarrierBundle24classifyeIMSIConfigFilesERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEERNS0_3mapIS6_NS0_4listIS6_NS4_IS6_EEEENS0_4lessIS6_EENS4_INS0_4pairIS7_SC_EEEEEE
+ __ZN13CarrierBundle29recursivelyClassifyeIMSIFilesERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEES8_RNS0_3mapIS6_NS0_4listIS6_NS4_IS6_EEEENS0_4lessIS6_EENS4_INS0_4pairIS7_SC_EEEEEE
+ __ZNKSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE4findB9fqe220106EPKcm
+ __ZNSt3__13mapINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_4listIS6_NS4_IS6_EEEENS_4lessIS6_EENS4_INS_4pairIKS6_S9_EEEEEixERSD_
+ __ZNSt3__14pairIKNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_4listIS6_NS4_IS6_EEEEEC1B9fqe220106IJRS7_EJEEENS_21piecewise_construct_tENS_5tupleIJDpT_EEENSF_IJDpT0_EEE
+ __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_4listIS7_NS5_IS7_EEEEEENS_19__map_value_compareIS7_NS_4pairIKS7_SA_EENS_4lessIS7_EEEENS5_ISF_EEE16__construct_nodeIJRKNS_21piecewise_construct_tENS_5tupleIJRSE_EEENSP_IJEEEEEENS_10unique_ptrINS_11__tree_nodeISB_PvEENS_22__tree_node_destructorINS5_ISW_EEEEEEDpOT_
+ __ZNSt3__1L19piecewise_constructE
+ _memchr
- GCC_except_table49
- GCC_except_table57
- GCC_except_table59
- GCC_except_table60
- GCC_except_table65
- GCC_except_table72
- GCC_except_table74
- GCC_except_table77
- GCC_except_table83
- GCC_except_table89
CStrings:
+ "Failed to classify eIMSI config structure at: %s"
+ "Unable to read directory contents at: %s"
+ "eIMSIConfig_"
+ "esimBootstrapConfig"
+ "tri"
```
