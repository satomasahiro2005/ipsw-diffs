## TextInput_fr

> `/System/Library/TextInput/TextInput_fr.bundle/TextInput_fr`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d4c` | `0x1d70` | **`+0x24`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3557.12.1.0.0
+3557.15.100.0.0
Symbols:
+ __ZNSt3__112__hash_tableINS_17__hash_value_typeIN2KB10ByteStringEN3WTF6RefPtrIN2TI8Favonius9LayoutKeyEEEEENS_22__unordered_map_hasherIS3_NS_4pairIKS3_S9_EENS_4hashIS3_EENS_8equal_toIS3_EEEENS_21__unordered_map_equalIS3_SE_SI_SG_EENS_9allocatorISE_EEE22__deallocate_node_listB9fon220106EPNS_16__hash_node_baseIPNS_11__hash_nodeISA_PvEEEE
+ __ZNSt3__119__shared_weak_count16__release_sharedB9fon220106Ev
+ __ZNSt3__16__treeINS_12__value_typeIfiEENS_19__map_value_compareIfNS_4pairIKfiEENS_4lessIfEEEENS_9allocatorIS6_EEE14__tree_deleterclB9fon220106EPNS_11__tree_nodeIS2_PvEE
+ __ZNSt3__16vectorIN3WTF6RefPtrIN2TI8Favonius9LayoutKeyEEENS_9allocatorIS6_EEE16__destroy_vectorclB9fon220106Ev
+ __ZNSt3__16vectorIN3WTF6RefPtrIN2TI8Favonius9LayoutKeyEEENS_9allocatorIS6_EEE5clearB9fon220106Ev
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE5clearB9fon220106Ev
+ __ZNSt3__19remove_ifB9fon220106INS_11__wrap_iterIPN2KB9CandidateEEEU13block_pointerFbRKS3_EEET_SA_SA_T0_
- __ZNSt3__112__hash_tableINS_17__hash_value_typeIN2KB10ByteStringEN3WTF6RefPtrIN2TI8Favonius9LayoutKeyEEEEENS_22__unordered_map_hasherIS3_NS_4pairIKS3_S9_EENS_4hashIS3_EENS_8equal_toIS3_EEEENS_21__unordered_map_equalIS3_SE_SI_SG_EENS_9allocatorISE_EEE22__deallocate_node_listB9fon220100EPNS_16__hash_node_baseIPNS_11__hash_nodeISA_PvEEEE
- __ZNSt3__119__shared_weak_count16__release_sharedB9fon220100Ev
- __ZNSt3__16__treeINS_12__value_typeIfiEENS_19__map_value_compareIfNS_4pairIKfiEENS_4lessIfEEEENS_9allocatorIS6_EEE14__tree_deleterclB9fon220100EPNS_11__tree_nodeIS2_PvEE
- __ZNSt3__16vectorIN3WTF6RefPtrIN2TI8Favonius9LayoutKeyEEENS_9allocatorIS6_EEE16__destroy_vectorclB9fon220100Ev
- __ZNSt3__16vectorIN3WTF6RefPtrIN2TI8Favonius9LayoutKeyEEENS_9allocatorIS6_EEE5clearB9fon220100Ev
- __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE5clearB9fon220100Ev
- __ZNSt3__19remove_ifB9fon220100INS_11__wrap_iterIPN2KB9CandidateEEEU13block_pointerFbRKS3_EEET_SA_SA_T0_
Functions:
~ __ZN3WTF12VectorBufferIN2KB4WordELm3EE4swapERS3_ : 304 -> 340
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1171: libc++ Hardening assertion __first <= __last failed: vector::erase(first, last) called with invalid range\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1156: libc++ Hardening assertion __first <= __last failed: vector::erase(first, last) called with invalid range\n"
```
