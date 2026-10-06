## TextInput

> `/System/Library/PrivateFrameworks/TextInput.framework/TextInput`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x255300` | `0x255b20` | **`+0x820`** |
| `__DATA_CONST.__objc_arraydata` | `0x1015a8` | `0x101920` | **`+0x378`** |
| `__AUTH_CONST.__objc_dictobj` | `0xf028` | `0xf190` | **`+0x168`** |
| `__TEXT.__ustring` | `0xc8a84` | `0xc8bc8` | **`+0x144`** |
| `__TEXT.__text` | `0x80578` | `0x80670` | **`+0xf8`** |
| `__TEXT.__cstring` | `0x493fd` | `0x494a8` | **`+0xab`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x4fe0` | `0x5040` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x2068` | `0x20a0` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x5668` | `0x5678` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x2438` | `0x2440` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xb5b0` | `0xb5b8` | **`+0x8`** |

### Other Changes

```diff

-3557.12.1.0.0
+3557.15.100.0.0

-  Functions: 4000
-  Symbols:   7631
-  CStrings:  76723
+  Functions: 4001
+  Symbols:   7633
+  CStrings:  76788
Symbols:
+ -[NSString(TIExtras) _containsStronglyDirectionalCharacters]
+ _TIInputModeComponentsExtensionInputModeKey
+ __ZNKSt3__111__copy_implclB9fon220106IPNS_6vectorI18TIHandwritingPointNS_9allocatorIS3_EEEES7_S7_Li0EEENS_4pairIT_T1_EES9_T0_SA_
+ __ZNSt3__110unique_ptrINS_11__tree_nodeI8NSHolderI19TIInputContextEntryEPvEENS_22__tree_node_destructorINS_9allocatorIS6_EEEEED1B9fon220106Ev
+ __ZNSt3__119__allocate_at_leastB9fon220106INS_9allocatorI18TIHandwritingPointEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
+ __ZNSt3__119__allocate_at_leastB9fon220106INS_9allocatorINS_6vectorI18TIHandwritingPointNS1_IS3_EEEEEENS_16allocator_traitsIS6_EEEENS_19__allocation_resultINT0_7pointerENSA_9size_typeEEERT_m
+ __ZNSt3__13setI8NSHolderI19TIInputContextEntryENS_4lessIS3_EENS_9allocatorIS3_EEE6insertB9fon220106EOS3_
+ __ZNSt3__16__treeI8NSHolderI19TIInputContextEntryENS_4lessIS3_EENS_9allocatorIS3_EEE12__find_equalB9fon220106IS3_EENS_4pairIPNS_15__tree_end_nodeIPNS_16__tree_node_baseIPvEEEERSF_EERKT_
+ __ZNSt3__16__treeI8NSHolderI19TIInputContextEntryENS_4lessIS3_EENS_9allocatorIS3_EEE14__tree_deleterclB9fon220106EPNS_11__tree_nodeIS3_PvEE
+ __ZNSt3__16__treeI8NSHolderI19TIInputContextEntryENS_4lessIS3_EENS_9allocatorIS3_EEE18__assign_from_treeB9fon220106IZNS8_18__copy_assign_treeB9fon220106EPNS_11__tree_nodeIS3_PvEESD_EUlRS3_RKS3_E_ZNS8_18__copy_assign_treeB9fon220106ESD_SD_EUlSD_E_EESD_SD_SD_T_T0_
+ __ZNSt3__16__treeI8NSHolderI19TIInputContextEntryENS_4lessIS3_EENS_9allocatorIS3_EEE21__construct_from_treeB9fon220106IZNS8_21__copy_construct_treeB9fon220106EPNS_11__tree_nodeIS3_PvEEEUlRKS3_E_EESD_SD_T_
+ __ZNSt3__16vectorI18TIHandwritingPointNS_9allocatorIS1_EEE11__vallocateB9fon220106Em
+ __ZNSt3__16vectorI18TIHandwritingPointNS_9allocatorIS1_EEE20__throw_length_errorB9fon220106Ev
+ __ZNSt3__16vectorI18TIHandwritingPointNS_9allocatorIS1_EEEC2B9fon220106ERKS4_
+ __ZNSt3__16vectorINS0_I18TIHandwritingPointNS_9allocatorIS1_EEEENS2_IS4_EEE20__throw_length_errorB9fon220106Ev
+ __ZNSt3__16vectorINS0_I18TIHandwritingPointNS_9allocatorIS1_EEEENS2_IS4_EEE5clearB9fon220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fon220106v
- __ZNKSt3__111__copy_implclB9fon220100IPNS_6vectorI18TIHandwritingPointNS_9allocatorIS3_EEEES7_S7_Li0EEENS_4pairIT_T1_EES9_T0_SA_
- __ZNSt3__110unique_ptrINS_11__tree_nodeI8NSHolderI19TIInputContextEntryEPvEENS_22__tree_node_destructorINS_9allocatorIS6_EEEEED1B9fon220100Ev
- __ZNSt3__119__allocate_at_leastB9fon220100INS_9allocatorI18TIHandwritingPointEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fon220100INS_9allocatorINS_6vectorI18TIHandwritingPointNS1_IS3_EEEEEENS_16allocator_traitsIS6_EEEENS_19__allocation_resultINT0_7pointerENSA_9size_typeEEERT_m
- __ZNSt3__13setI8NSHolderI19TIInputContextEntryENS_4lessIS3_EENS_9allocatorIS3_EEE6insertB9fon220100EOS3_
- __ZNSt3__16__treeI8NSHolderI19TIInputContextEntryENS_4lessIS3_EENS_9allocatorIS3_EEE12__find_equalB9fon220100IS3_EENS_4pairIPNS_15__tree_end_nodeIPNS_16__tree_node_baseIPvEEEERSF_EERKT_
- __ZNSt3__16__treeI8NSHolderI19TIInputContextEntryENS_4lessIS3_EENS_9allocatorIS3_EEE14__tree_deleterclB9fon220100EPNS_11__tree_nodeIS3_PvEE
- __ZNSt3__16__treeI8NSHolderI19TIInputContextEntryENS_4lessIS3_EENS_9allocatorIS3_EEE18__assign_from_treeB9fon220100IZNS8_18__copy_assign_treeB9fon220100EPNS_11__tree_nodeIS3_PvEESD_EUlRS3_RKS3_E_ZNS8_18__copy_assign_treeB9fon220100ESD_SD_EUlSD_E_EESD_SD_SD_T_T0_
- __ZNSt3__16__treeI8NSHolderI19TIInputContextEntryENS_4lessIS3_EENS_9allocatorIS3_EEE21__construct_from_treeB9fon220100IZNS8_21__copy_construct_treeB9fon220100EPNS_11__tree_nodeIS3_PvEEEUlRKS3_E_EESD_SD_T_
- __ZNSt3__16vectorI18TIHandwritingPointNS_9allocatorIS1_EEE11__vallocateB9fon220100Em
- __ZNSt3__16vectorI18TIHandwritingPointNS_9allocatorIS1_EEE20__throw_length_errorB9fon220100Ev
- __ZNSt3__16vectorI18TIHandwritingPointNS_9allocatorIS1_EEEC2B9fon220100ERKS4_
- __ZNSt3__16vectorINS0_I18TIHandwritingPointNS_9allocatorIS1_EEEENS2_IS4_EEE20__throw_length_errorB9fon220100Ev
- __ZNSt3__16vectorINS0_I18TIHandwritingPointNS_9allocatorIS1_EEEENS2_IS4_EEE5clearB9fon220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fon220100v
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1161: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "Aʼ"
+ "Cʼ"
+ "C̓"
+ "Eʼ"
+ "InputMode_fla.plist"
+ "InputMode_kio.plist"
+ "Iʼ"
+ "Kiowa"
+ "Kʼ"
+ "K̓"
+ "Lʼ"
+ "L̓"
+ "Mʼ"
+ "M̓"
+ "Nʼ"
+ "N̓"
+ "Oʼ"
+ "Pʼ"
+ "P̓"
+ "QWERTY-Kiowa"
+ "QWERTY-Salish"
+ "Qʼ"
+ "Q̓"
+ "Salish-Alphabetic"
+ "Salish-QWERTY"
+ "Tʼ"
+ "T̓"
+ "UIKeyboardDefaultLanguageInputModes-XR"
+ "Uʼ"
+ "Wʼ"
+ "W̓"
+ "Yʼ"
+ "Y̓"
+ "aʼ"
+ "cʼ"
+ "c̓"
+ "extensionInputMode"
+ "eʼ"
+ "fla"
+ "iʼ"
+ "kʼ"
+ "k̓"
+ "lʼ"
+ "l̓"
+ "mʼ"
+ "m̓"
+ "nʼ"
+ "n̓"
+ "oʼ"
+ "pʼ"
+ "p̓"
+ "qʼ"
+ "q̓"
+ "tʼ"
+ "t̓"
+ "und"
+ "uʼ"
+ "wʼ"
+ "w̓"
+ "yʼ"
+ "y̓"
+ "Čʼ"
+ "Č̓"
+ "čʼ"
+ "č̓"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1146: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:413: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
```
