## libsat

> `/System/Library/PrivateFrameworks/libsat.framework/libsat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x79f4` | `0x81fc` | **`+0x808`** |
| `__TEXT.__gcc_except_tab` | `0x68` | `0xcc` | **`+0x64`** |
| `__TEXT.__unwind_info` | `0x390` | `0x3e0` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x6c0` | `0x6c8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-109.0.0.0.1
+112.0.0.0.0

-  Functions: 290
-  Symbols:   396
-  CStrings:  46
+  Functions: 305
+  Symbols:   416
+  CStrings:  45
Symbols:
+ GCC_except_table12
+ GCC_except_table14
+ GCC_except_table19
+ GCC_except_table32
+ GCC_except_table33
+ GCC_except_table5
+ GCC_except_table7
+ _IOConnectCallMethod
+ __Z19SAT_ClearMsgsToUserRKj
+ __Z19sat_clear_kext_msgsv
+ __Z20sat_get_msgs_to_userPj
+ __Z22SAT_GetMsgsToUserCountRKjR21sat_msg_to_user_count
+ __Z23SAT_GetMsgToUserByIndexRKjjR15sat_msg_to_user
+ __ZNSt3__114__split_bufferINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEERNS4_IS6_EEE17__destruct_at_endB9fqe220106EPS6_
+ __ZNSt3__114__split_bufferINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEERNS4_IS6_EEED2Ev
+ __ZNSt3__116__if_likely_elseB9fqe220106IZNS_6vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS5_IS7_EEE12emplace_backIJRA256_cEEERS7_DpOT_EUlvE_ZNSA_IJSC_EEESD_SG_EUlvE0_EEvbT_T0_
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorINS_12basic_stringIcNS_11char_traitsIcEENS1_IcEEEEEENS_16allocator_traitsIS7_EEEENS_19__allocation_resultINT0_7pointerENSB_9size_typeEEERT_m
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE24__emplace_back_slow_pathIJRA256_cEEEPS6_DpOT_
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE30__emplace_back_assume_capacityB9fqe220106IJRA256_cEEEvDpOT_
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE5clearB9fqe220106Ev
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE7reserveEm
- GCC_except_table11
- GCC_except_table16
- GCC_except_table9
CStrings:
- "109.0.0.0.1"
```
