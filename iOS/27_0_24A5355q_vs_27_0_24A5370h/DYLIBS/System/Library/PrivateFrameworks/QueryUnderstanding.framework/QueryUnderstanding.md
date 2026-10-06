## QueryUnderstanding

> `/System/Library/PrivateFrameworks/QueryUnderstanding.framework/QueryUnderstanding`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6aa8` | `0x70a0` | **`+0x5f8`** |
| `__TEXT.__oslogstring` | `0x4e6` | `0x59a` | **`+0xb4`** |
| `__DATA_CONST.__objc_selrefs` | `0x5e8` | `0x650` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x72c` | `0x754` | **`+0x28`** |
| `__TEXT.__cstring` | `0xf2e` | `0xf55` | **`+0x27`** |
| `__AUTH_CONST.__cfstring` | `0x500` | `0x520` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x140` | `0x158` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x944` | `0x94c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2a8` | `0x2b0` | **`+0x8`** |

### Other Changes

```diff

-3600.26.10.1.2
+3600.31.9.1.1

-  Functions: 140
-  Symbols:   433
-  CStrings:  250
+  Functions: 143
+  Symbols:   438
+  CStrings:  255
Symbols:
+ +[U2OwlModel normalizeQueryForInference:offsetMap:]
+ -[QUModelFactory acquireTransaction]
+ -[QUModelFactory releaseTransaction]
+ _OBJC_CLASS_$_NSMutableString
+ _OBJC_CLASS_$_NSValue
+ _OBJC_IVAR_$_QUModelFactory._loadingTransaction
+ _OBJC_IVAR_$_QUModelFactory._preheatTransaction
+ __ZNSt12length_errorC1B9foe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9foe220106INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9foe220106EPKc
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE11__vallocateB9foe220106Em
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE16__init_with_sizeB9foe220106IPfS5_EEvT_T0_m
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9foe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9foe220106Em
+ __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9foe220106EmRKf
+ __ZSt28__throw_bad_array_new_lengthB9foe220106v
+ ___block_descriptor_96_e8_32s40s48s56s64s72bs_e41_v24?0"<QUEmbeddingOutput>"8"NSError"16ls72l8s32l8s40l8s48l8s56l8s64l8
+ ___kCFBooleanTrue
+ _objc_autorelease
- _OBJC_IVAR_$_QUModelFactory._releaseBlock
- _OBJC_IVAR_$_QUModelFactory._transaction
- __ZNSt12length_errorC1B9foe220100EPKc
- __ZNSt3__119__allocate_at_leastB9foe220100INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9foe220100EPKc
- __ZNSt3__16vectorIfNS_9allocatorIfEEE11__vallocateB9foe220100Em
- __ZNSt3__16vectorIfNS_9allocatorIfEEE16__init_with_sizeB9foe220100IPfS5_EEvT_T0_m
- __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9foe220100Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9foe220100Em
- __ZNSt3__16vectorIfNS_9allocatorIfEEEC2B9foe220100EmRKf
- __ZSt28__throw_bad_array_new_lengthB9foe220100v
- ___block_descriptor_88_e8_32s40s48s56s64bs_e41_v24?0"<QUEmbeddingOutput>"8"NSError"16ls64l8s32l8s40l8s48l8s56l8
- _dispatch_block_cancel
- _objc_retain_x28
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "HK"
+ "Hant"
+ "IN"
+ "NoOTA"
+ "TW"
+ "[QPNLU] Preheat transaction created"
+ "[QPNLU] Preheat transaction released"
+ "[QPNLU] U2 Model not available via UAF for locale %@ - falling back to system path"
+ "[QPNLU] U2 Model not found via UAF or system path for locale %@"
+ "com.apple.queryparser.queryunderstanding.loading"
+ "com.apple.queryparser.queryunderstanding.preheat"
+ "en"
+ "zh"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:413: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "[QPNLU] Failed to find U2 Model via UAF"
- "\\s+"
- "com.apple.queryparser.queryunderstanding"
- "en-IN"
- "zh-HK"
- "zh-Hant-HK"
- "zh-Hant-TW"
- "zh-TW"
```
