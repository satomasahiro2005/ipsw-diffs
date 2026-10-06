## TextInput_th

> `/System/Library/TextInput/TextInput_th.bundle/TextInput_th`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d44` | `0x3d60` | **`+0x1c`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3557.12.1.0.0
+3557.15.100.0.0
Symbols:
+ __ZNSt3__119__shared_weak_count16__release_sharedB9fon220106Ev
+ __ZNSt3__127__tree_balance_after_insertB9fon220106IPNS_16__tree_node_baseIPvEEEEvT_S5_
+ __ZNSt3__13setIN2KB6StringENS_4lessIS2_EENS_9allocatorIS2_EEE6insertB9fon220106EOS2_
+ __ZNSt3__16__treeIN2KB6StringENS_4lessIS2_EENS_9allocatorIS2_EEE12__find_equalB9fon220106IS2_EENS_4pairIPNS_15__tree_end_nodeIPNS_16__tree_node_baseIPvEEEERSE_EERKT_
+ __ZNSt3__16__treeIN2KB6StringENS_4lessIS2_EENS_9allocatorIS2_EEE14__tree_deleterclB9fon220106EPNS_11__tree_nodeIS2_PvEE
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE5clearB9fon220106Ev
+ __ZNSt3__19remove_ifB9fon220106INS_11__wrap_iterIPN2KB9CandidateEEEU13block_pointerFbRKS3_EEET_SA_SA_T0_
- __ZNSt3__119__shared_weak_count16__release_sharedB9fon220100Ev
- __ZNSt3__127__tree_balance_after_insertB9fon220100IPNS_16__tree_node_baseIPvEEEEvT_S5_
- __ZNSt3__13setIN2KB6StringENS_4lessIS2_EENS_9allocatorIS2_EEE6insertB9fon220100EOS2_
- __ZNSt3__16__treeIN2KB6StringENS_4lessIS2_EENS_9allocatorIS2_EEE12__find_equalB9fon220100IS2_EENS_4pairIPNS_15__tree_end_nodeIPNS_16__tree_node_baseIPvEEEERSE_EERKT_
- __ZNSt3__16__treeIN2KB6StringENS_4lessIS2_EENS_9allocatorIS2_EEE14__tree_deleterclB9fon220100EPNS_11__tree_nodeIS2_PvEE
- __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE5clearB9fon220100Ev
- __ZNSt3__19remove_ifB9fon220100INS_11__wrap_iterIPN2KB9CandidateEEEU13block_pointerFbRKS3_EEET_SA_SA_T0_
Functions:
~ -[TIKeyboardInputManager_th firstMecabraCandidateOccurranceFromLastAutocorrectionList] : 420 -> 416
~ -[TIKeyboardInputManager_th setInput:] : 372 -> 368
~ __ZN3WTF12VectorBufferIN2KB4WordELm3EE4swapERS3_ : 304 -> 340
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1171: libc++ Hardening assertion __first <= __last failed: vector::erase(first, last) called with invalid range\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1156: libc++ Hardening assertion __first <= __last failed: vector::erase(first, last) called with invalid range\n"
```
