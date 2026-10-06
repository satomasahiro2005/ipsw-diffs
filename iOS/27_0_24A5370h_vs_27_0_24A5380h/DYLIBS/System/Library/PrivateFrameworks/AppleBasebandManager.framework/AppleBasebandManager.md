## AppleBasebandManager

> `/System/Library/PrivateFrameworks/AppleBasebandManager.framework/AppleBasebandManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28a60` | `0x289bc` | **`-0xa4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1570.0.0.0.0
+1576.0.0.0.0
Functions:
~ __ZN5boost8signals26detail11auto_bufferINS_10shared_ptrIvEENS1_15store_n_objectsILj10EEENS1_19default_grow_policyENSt3__19allocatorIS4_EEE9push_backERKS4_ : 504 -> 496
~ ____ZN20AppleBasebandManager5State4initEv_block_invoke : 5808 -> 5676
~ __ZN3abm5trace31extractSettingsTypeFromFileNameERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEE : 1016 -> 1032
~ __ZNK5boost8signals26detail20slot_call_iterator_tINS1_21variadic_slot_invokerINS1_9void_typeEJEEENSt3__115__list_iteratorINS_10shared_ptrINS1_15connection_bodyINS6_4pairINS1_15slot_meta_groupENS_8optionalIiEEEENS0_4slotIFvvENS_8functionISG_EEEENS0_5mutexEEEEEPvEESL_E18lock_next_callableEv : 2404 -> 2364
CStrings:
+ "AppleBasebandManager-AppleBasebandServices_Manager-1576"
+ "AppleBasebandServices_Manager-1576"
- "AppleBasebandManager-AppleBasebandServices_Manager-1570"
- "AppleBasebandServices_Manager-1570"
```
