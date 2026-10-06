## TypingDESPlugin

> `/System/Library/DistributedEvaluation/Plugins/TypingDESPlugin.desPlugin/TypingDESPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xac10` | `0xac54` | **`+0x44`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__cstring`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3557.12.1.0.0
+3557.15.100.0.0
Functions:
~ __ZN2TI2CP44createAndLoadDictionaryContainerMultiLexiconEP8NSStringS2_fS2_ : 716 -> 740
~ __ZN2TI2CP35createAndLoadLanguageModelContainerEP8NSStringS2_fS2_ : 880 -> 904
~ sub_371c -> sub_374c : 160 -> 164
~ sub_41d8 -> sub_420c : 252 -> 236
~ sub_45b0 -> sub_45d4 : 176 -> 152
~ sub_46b4 -> sub_46c0 : 112 -> 132
~ sub_5698 -> sub_56b8 : 520 -> 532
~ sub_60c8 -> sub_60f4 : 708 -> 704
~ sub_64fc -> sub_6524 : 976 -> 972
~ sub_6b18 -> sub_6b3c : 764 -> 740
~ __ZNK2TI2CP6CPEval8is_matchERKN2KB9CandidateERKNS2_6StringE : 500 -> 504
~ __ZNK2TI2CP6CPEval16evaluate_recordsERKNSt3__16vectorINS0_22ContinuousPathTestCaseENS2_9allocatorIS4_EEEENS0_20TIPathRecognizerTypeERKNS0_14EnsembleConfigE : 828 -> 824
~ __ZNK2TI2CP6CPEval30compose_result_from_candidatesERKN2KB19CandidateCollectionERKNS0_22ContinuousPathTestCaseEj : 628 -> 644
~ sub_8c58 -> sub_8c74 : 304 -> 340
~ __ZNK2TI2CP17TestCaseConverter7convertEP18TIWordEntryAligned : 900 -> 896
~ sub_a1f4 -> sub_a230 : 228 -> 236
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:434: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:438: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:446: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:418: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:433: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:437: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:445: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
```
