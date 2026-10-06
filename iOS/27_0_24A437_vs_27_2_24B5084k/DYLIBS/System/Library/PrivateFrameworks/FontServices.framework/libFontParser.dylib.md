## libFontParser.dylib

> `/System/Library/PrivateFrameworks/FontServices.framework/libFontParser.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c9198` | `0x1c966c` | **`+0x4d4`** |
| `__TEXT.__gcc_except_tab` | `0x79a8` | `0x7d04` | **`+0x35c`** |
| `__TEXT.__eh_frame` | `0x9d80` | `0x9dd8` | **`+0x58`** |
| `__TEXT.__lazy_helpers` | `0xfc` | `0x150` | **`+0x54`** |
| `__TEXT.__swift5_reflstr` | `0x4125` | `0x4165` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x948` | `0x980` | **`+0x38`** |
| `__AUTH.__objc_data` | `0x908` | `0x930` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x7530` | `0x7558` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x26d30` | `0x26d10` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x368c` | `0x36ac` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x53e4` | `0x53fc` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x730` | `0x740` | **`+0x10`** |
| `__TEXT.__cstring` | `0x16fd7` | `0x16fc9` | **`-0xe`** |
| `__AUTH_CONST.__auth_got` | `0x15d8` | `0x15d0` | **`-0x8`** |
| `__AUTH_CONST.__lazy_load_got` | `0x18` | `0x20` | **`+0x8`** |
| `__AUTH_CONST.__weak_auth_got` | `0x40` | `0x48` | **`+0x8`** |
| `__DATA.__data` | `0x2754` | `0x275c` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x468` | `0x470` | **`+0x8`** |

### Other Changes

```diff

-459.0.0.0.0
+462.0.0.0.0

-  Functions: 8397
-  Symbols:   6599
-  CStrings:  5507
+  Functions: 8405
+  Symbols:   6610
+  CStrings:  5506
Symbols:
+ _GSFontEnsureFontFileAccess$lazyAuthGOT_IA_0
+ _GSFontEnsureFontFileAccess$lazyAuthGOT_IA_0$loadHelper_x8
+ __PROPERTIES_STTInterpreter
+ __ZL22CheckedScanScratchSizeit
+ __ZL31CheckedScanScratchRowBaseOffsetit
+ __ZL34CheckedScanScratchOffsetWithinSizeitj
+ __ZN35TBufferedCharStringStreamingContext3PopEv
+ __ZN35TBufferedCharStringStreamingContext4PushEi
+ __ZN36TType1FontType2CFF2CharStringHandlerD2Ev
+ __ZN40TType1ToType2CharStringConversionContext15PopCounterValueEv
+ __ZN40TType1ToType2CharStringConversionContext3PopEv
+ __ZN40TType1ToType2CharStringConversionContext4PushEi
+ __ZNSt3__16vectorId22TInlineBufferAllocatorIdLm240ELm8EEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorId22TInlineBufferAllocatorIdLm240ELm8EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorId22TInlineBufferAllocatorIdLm240ELm8EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorId22TInlineBufferAllocatorIdLm240ELm8EEEC2B9fqe220106ILi0EEEmRKdRKS2_
+ __ZNSt3__16vectorIf22TInlineBufferAllocatorIfLm1248ELm4EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorIf22TInlineBufferAllocatorIfLm1248ELm4EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIi22TInlineBufferAllocatorIiLm120ELm4EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorIi22TInlineBufferAllocatorIiLm120ELm4EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIs22TInlineBufferAllocatorIsLm60ELm2EEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIs22TInlineBufferAllocatorIsLm60ELm2EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorIs22TInlineBufferAllocatorIsLm60ELm2EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIs22TInlineBufferAllocatorIsLm60ELm2EEE6resizeEm
+ __ZNSt3__16vectorIt22TInlineBufferAllocatorItLm208ELm2EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorIt22TInlineBufferAllocatorItLm208ELm2EEE20__throw_length_errorB9fqe220106Ev
+ __Znwm
+ ____Z15sc_FindExtrema4P15fnt_ElementTypeP13sc_BitMapDataiP13fsg_SplineKey_block_invoke_4
+ ___swift_memcpy209_8
+ ___swift_memcpy529_8
- __ZN22TInlineBufferAllocatorIdLm30EE8allocateEm
- __ZN22TInlineBufferAllocatorIsLm30EE8allocateEm
- __ZNSt3__16vectorId22TInlineBufferAllocatorIdLm30EEE11__vallocateB9fqe220106Em
- __ZNSt3__16vectorId22TInlineBufferAllocatorIdLm30EEE16__destroy_vectorclB9fqe220106Ev
- __ZNSt3__16vectorId22TInlineBufferAllocatorIdLm30EEE20__throw_length_errorB9fqe220106Ev
- __ZNSt3__16vectorId22TInlineBufferAllocatorIdLm30EEEC2B9fqe220106EmRKd
- __ZNSt3__16vectorIf22TInlineBufferAllocatorIfLm312EEE16__destroy_vectorclB9fqe220106Ev
- __ZNSt3__16vectorIf22TInlineBufferAllocatorIfLm312EEE20__throw_length_errorB9fqe220106Ev
- __ZNSt3__16vectorIi22TInlineBufferAllocatorIiLm30EEE16__destroy_vectorclB9fqe220106Ev
- __ZNSt3__16vectorIi22TInlineBufferAllocatorIiLm30EEE20__throw_length_errorB9fqe220106Ev
- __ZNSt3__16vectorIs22TInlineBufferAllocatorIsLm30EEE11__vallocateB9fqe220106Em
- __ZNSt3__16vectorIs22TInlineBufferAllocatorIsLm30EEE16__destroy_vectorclB9fqe220106Ev
- __ZNSt3__16vectorIs22TInlineBufferAllocatorIsLm30EEE20__throw_length_errorB9fqe220106Ev
- __ZNSt3__16vectorIs22TInlineBufferAllocatorIsLm30EEE6resizeEm
- __ZNSt3__16vectorIt22TInlineBufferAllocatorItLm104EEE16__destroy_vectorclB9fqe220106Ev
- __ZNSt3__16vectorIt22TInlineBufferAllocatorItLm104EEE20__throw_length_errorB9fqe220106Ev
- ____Z15sc_FindExtrema4P15fnt_ElementTypeP13sc_BitMapDataiP13fsg_SplineKey_block_invoke_2
- ___swift_memcpy208_8
- ___swift_memcpy521_8
CStrings:
- "B20@?0r^s8i16"
```
