## CoreTelephony

> `/System/Library/Frameworks/CoreTelephony.framework/CoreTelephony`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d3220` | `0x1d38d4` | **`+0x6b4`** |
| `__TEXT.__gcc_except_tab` | `0x258a0` | `0x25910` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x10fd8` | `0x11020` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x1faac` | `0x1facc` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x168` | `0x15c` | **`-0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x88b8` | `0x88c0` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`
- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-13482.1.0.0.0
+13487.3.0.0.0

-  Functions: 13084
-  Symbols:   24164
+  Functions: 13094
+  Symbols:   24174
Symbols:
+ -[CTQuickSwitchInfo .cxx_destruct]
+ -[CoreTelephonyClient(QuickSwitch) isQuickSwitchPendingTwinningWithError:]
+ __ZNSt3__122__tree_node_destructorINS_9allocatorINS_11__tree_nodeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS1_IcEEEEyEEPvEEEEEclB9fqn220106EPSB_
+ __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEyEENS_19__map_value_compareIS7_NS_4pairIKS7_yEENS_4lessIS7_EEEENS5_ISC_EEE14__tree_deleterclB9fqn220106EPNS_11__tree_nodeIS8_PvEE
+ __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEyEENS_19__map_value_compareIS7_NS_4pairIKS7_yEENS_4lessIS7_EEEENS5_ISC_EEE16__construct_nodeIJRKSC_EEENS_10unique_ptrINS_11__tree_nodeIS8_PvEENS_22__tree_node_destructorINS5_ISO_EEEEEEDpOT_
+ __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEyEENS_19__map_value_compareIS7_NS_4pairIKS7_yEENS_4lessIS7_EEEENS5_ISC_EEE18__assign_from_treeB9fqn220106IZNSH_18__copy_assign_treeB9fqn220106EPNS_11__tree_nodeIS8_PvEESM_EUlRSC_RKSC_E_ZNSH_18__copy_assign_treeB9fqn220106ESM_SM_EUlSM_E_EESM_SM_SM_T_T0_
+ __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEyEENS_19__map_value_compareIS7_NS_4pairIKS7_yEENS_4lessIS7_EEEENS5_ISC_EEE21__construct_from_treeB9fqn220106IZNSH_21__copy_construct_treeB9fqn220106EPNS_11__tree_nodeIS8_PvEEEUlRKSC_E_EESM_SM_T_
+ __ZNSt3__16__treeINS_12__value_typeINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEyEENS_19__map_value_compareIS7_NS_4pairIKS7_yEENS_4lessIS7_EEEENS5_ISC_EEEaSERKSH_
+ ___74-[CoreTelephonyClient(QuickSwitch) isQuickSwitchPendingTwinningWithError:]_block_invoke
+ ___74-[CoreTelephonyClient(QuickSwitch) isQuickSwitchPendingTwinningWithError:]_block_invoke_2
CStrings:
+ "13487.3"
+ "13487.3~40"
+ "IPHONE_HANDOFF"
- "13482.1"
- "13482.1~1"
- "AUTOMATIC_NUMBER_SWITCHING"
```
