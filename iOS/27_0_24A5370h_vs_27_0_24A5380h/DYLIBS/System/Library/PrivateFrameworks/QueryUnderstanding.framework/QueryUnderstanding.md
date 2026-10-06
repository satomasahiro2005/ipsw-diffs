## QueryUnderstanding

> `/System/Library/PrivateFrameworks/QueryUnderstanding.framework/QueryUnderstanding`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xf55` | `0xe22` | **`-0x133`** |
| `__TEXT.__text` | `0x70a0` | `0x6fcc` | **`-0xd4`** |
| `__TEXT.__const` | `0xb0` | `0xa8` | **`-0x8`** |

### Other Changes

```diff

-3600.31.9.1.1
+3600.31.13.0.0

-  CStrings:  255
+  CStrings:  254
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE16__init_with_sizeB9fqe220106IPfS5_EEvT_T0_m
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9fqe220106Em
+ __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9fqe220106EmRKf
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ _objc_retain_x28
- __ZNSt12length_errorC1B9foe220106EPKc
- __ZNSt3__119__allocate_at_leastB9foe220106INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9foe220106EPKc
- __ZNSt3__132__internal_log_hardening_failureEPKc
- __ZNSt3__16vectorIfNS_9allocatorIfEEE11__vallocateB9foe220106Em
- __ZNSt3__16vectorIfNS_9allocatorIfEEE16__init_with_sizeB9foe220106IPfS5_EEvT_T0_m
- __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9foe220106Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9foe220106Em
- __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9foe220106EmRKf
- __ZSt28__throw_bad_array_new_lengthB9foe220106v
Functions:
~ -[U2HeadWrapper getTokenScoresfromScoreTensor:intentIndex:tokens:subtokenLenForTokens:subtokens:scoreFromSubtokenScores:] : 1388 -> 1284
~ -[U2HeadWrapper mapLogitsToLabels:queryString:queryID:intentHint:tokens:subtokenLenForTokens:subtokens:] : 2360 -> 2252
CStrings:
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
```
