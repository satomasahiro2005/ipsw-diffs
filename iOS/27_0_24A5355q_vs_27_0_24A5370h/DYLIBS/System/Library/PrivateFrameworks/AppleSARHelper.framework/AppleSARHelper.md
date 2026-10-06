## AppleSARHelper

> `/System/Library/PrivateFrameworks/AppleSARHelper.framework/AppleSARHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0xa70` | `0xbd8` | **`+0x168`** |
| `__TEXT.__cstring` | `0x6ee` | `0x78f` | **`+0xa1`** |
| `__TEXT.__text` | `0x4b84` | `0x4c08` | **`+0x84`** |
| `__TEXT.__unwind_info` | `0x1e8` | `0x1e0` | **`-0x8`** |

### Other Changes

```diff

-1563.0.0.0.0
+1570.0.0.0.0

-  Functions: 99
-  Symbols:   223
-  CStrings:  160
+  Functions: 102
+  Symbols:   229
+  CStrings:  173
Symbols:
+ __ZN3sar8toStringENS_16DeltaAngleBucketE
+ __ZN3sar8toStringENS_17UEFacingDirectionE
+ __ZN3sar8toStringENS_21FDDistanceDeltaBucketE
+ __ZNKSt3__111__move_implINS_17_ClassicAlgPolicyEEclB9noe220106IPN14AppleSARHelper21PTDRegistrationConfigES6_S6_EENS_4pairIT_T1_EES8_T0_S9_
+ __ZNSt12length_errorC1B9noe220106EPKc
+ __ZNSt3__110shared_ptrI14AppleSARHelperED1B9noe220106Ev
+ __ZNSt3__110unique_ptrI14AppleSARHelperNS_14default_deleteIS1_EEED2B9noe220106Ev
+ __ZNSt3__110unique_ptrINS_11__hash_nodeINS_17__hash_value_typeIjNS_6vectorIN14AppleSARHelper21PTDRegistrationConfigENS_9allocatorIS5_EEEEEEPvEENS_22__hash_node_destructorINS6_ISB_EEEEED1B9noe220106Ev
+ __ZNSt3__112__destroy_atB9noe220106INS_4pairIKjNS_6vectorIN14AppleSARHelper21PTDRegistrationConfigENS_9allocatorIS5_EEEEEEEEvPT_
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9noe220106Ev
+ __ZNSt3__113unordered_mapIjNS_6vectorIN14AppleSARHelper21PTDRegistrationConfigENS_9allocatorIS3_EEEENS_4hashIjEENS_8equal_toIjEENS4_INS_4pairIKjS6_EEEEED2B9noe220106Ev
+ __ZNSt3__120__throw_length_errorB9noe220106EPKc
+ __ZNSt3__125__throw_bad_function_callB9noe220106Ev
+ __ZNSt3__16vectorIN14AppleSARHelper21PTDRegistrationConfigENS_9allocatorIS2_EEE20__throw_length_errorB9noe220106Ev
+ __ZNSt3__16vectorIN14AppleSARHelper21PTDRegistrationConfigENS_9allocatorIS2_EEED2B9noe220106Ev
+ __ZNSt3__16vectorIN8dispatch5blockIU13block_pointerFvPyjEEENS_9allocatorIS6_EEE20__throw_length_errorB9noe220106Ev
+ __ZNSt3__16vectorIN8dispatch5blockIU13block_pointerFvPyjEEENS_9allocatorIS6_EEED2B9noe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9noe220106v
+ __ZZN3sar8toStringENS_16DeltaAngleBucketEE7entries
+ __ZZN3sar8toStringENS_17UEFacingDirectionEE7entries
+ __ZZN3sar8toStringENS_21FDDistanceDeltaBucketEE7entries
- __ZNKSt3__111__move_implINS_17_ClassicAlgPolicyEEclB9noe220100IPN14AppleSARHelper21PTDRegistrationConfigES6_S6_EENS_4pairIT_T1_EES8_T0_S9_
- __ZNSt12length_errorC1B9noe220100EPKc
- __ZNSt3__110shared_ptrI14AppleSARHelperED1B9noe220100Ev
- __ZNSt3__110unique_ptrI14AppleSARHelperNS_14default_deleteIS1_EEED2B9noe220100Ev
- __ZNSt3__110unique_ptrINS_11__hash_nodeINS_17__hash_value_typeIjNS_6vectorIN14AppleSARHelper21PTDRegistrationConfigENS_9allocatorIS5_EEEEEEPvEENS_22__hash_node_destructorINS6_ISB_EEEEED1B9noe220100Ev
- __ZNSt3__112__destroy_atB9noe220100INS_4pairIKjNS_6vectorIN14AppleSARHelper21PTDRegistrationConfigENS_9allocatorIS5_EEEEEEEEvPT_
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9noe220100Ev
- __ZNSt3__113unordered_mapIjNS_6vectorIN14AppleSARHelper21PTDRegistrationConfigENS_9allocatorIS3_EEEENS_4hashIjEENS_8equal_toIjEENS4_INS_4pairIKjS6_EEEEED2B9noe220100Ev
- __ZNSt3__120__throw_length_errorB9noe220100EPKc
- __ZNSt3__125__throw_bad_function_callB9noe220100Ev
- __ZNSt3__16vectorIN14AppleSARHelper21PTDRegistrationConfigENS_9allocatorIS2_EEE20__throw_length_errorB9noe220100Ev
- __ZNSt3__16vectorIN14AppleSARHelper21PTDRegistrationConfigENS_9allocatorIS2_EEED2B9noe220100Ev
- __ZNSt3__16vectorIN8dispatch5blockIU13block_pointerFvPyjEEENS_9allocatorIS6_EEE20__throw_length_errorB9noe220100Ev
- __ZNSt3__16vectorIN8dispatch5blockIU13block_pointerFvPyjEEENS_9allocatorIS6_EEED2B9noe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9noe220100v
CStrings:
+ "-10..0 from Min"
+ "0-100mm Closer"
+ "0-100mm Further"
+ "0..+10 from Max"
+ "<-10 from Min"
+ ">+10 from Max"
+ ">100mm Closer"
+ ">100mm Further"
+ "Face Down"
+ "Face Up"
+ "Within Range"
+ "kMax"
+ "|MIC"
```
