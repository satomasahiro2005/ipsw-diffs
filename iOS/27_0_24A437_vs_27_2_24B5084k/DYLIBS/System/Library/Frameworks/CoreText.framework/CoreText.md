## CoreText

> `/System/Library/Frameworks/CoreText.framework/CoreText`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15f0fc` | `0x15fd90` | **`+0xc94`** |
| `__AUTH_CONST.__cfstring` | `0x18420` | `0x184a0` | **`+0x80`** |
| `__DATA_CONST.__objc_arraydata` | `0x18400` | `0x18440` | **`+0x40`** |
| `__DATA_DIRTY.__bss` | `0xe60` | `0xe98` | **`+0x38`** |
| `__AUTH_CONST.__objc_dictobj` | `0x3930` | `0x3958` | **`+0x28`** |
| `__TEXT.__cstring` | `0xfaad` | `0xfac6` | **`+0x19`** |
| `__AUTH_CONST.__auth_got` | `0x1810` | `0x1820` | **`+0x10`** |
| `__TEXT.__const` | `0x51f94` | `0x51fa4` | **`+0x10`** |
| `__AUTH_CONST.__weak_auth_got` | `0x48` | `0x40` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x428` | `0x420` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xcd0` | `0xcd8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x54f0` | `0x54f8` | **`+0x8`** |

### Other Changes

```diff

-904.0.0.0.0
+906.0.0.0.0

-  Functions: 5462
-  Symbols:   7712
-  CStrings:  3347
+  Functions: 5464
+  Symbols:   7715
+  CStrings:  3351
Symbols:
+ __Z11TCFBase_NEWI16CTFontDescriptorJRPK9TBaseFont4$_36EE6TCFRefINT_7cf_typeEEDpOT0_
+ __Z11TCFBase_NEWI16CTFontDescriptorJRPK9TBaseFont4$_36PK14__CFDictionaryEE6TCFRefINT_7cf_typeEEDpOT0_
+ __ZN12_GLOBAL__N_120PostScriptNameSuffixEPK10__CFString
+ __ZN9TBaseFont32UnpackOpticalPointSizesAttributeEPK10__CFNumberPdS3_
+ __ZNSt3__114__split_bufferIN3OTL12GlyphLookups12LookupRangesER22TInlineBufferAllocatorIS3_Lm3360ELm8EEE5clearB9fqn220106Ev
+ __ZNSt3__116allocator_traitsINS_9allocatorIN12_GLOBAL__N_122TOpticalStyleCandidateEEEE7destroyB9fqn220106IS3_Li0EEEvRS4_PT_
+ __ZNSt3__16vectorI7CFRange22TInlineBufferAllocatorIS1_Lm64ELm8EEE16__destroy_vectorclB9fqn220106Ev
+ __ZNSt3__16vectorIN12_GLOBAL__N_122TOpticalStyleCandidateENS_9allocatorIS2_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorIN3OTL12GlyphLookups12LookupRangesE22TInlineBufferAllocatorIS3_Lm3360ELm8EEE5clearB9fqn220106Ev
+ __ZNSt3__18_IterOpsINS_17_ClassicAlgPolicyEE9iter_swapB9fqn220106IRPN3OTL12GlyphLookups12LookupRangesES8_EEvOT_OT0_
+ __ZZNSt3__16vectorIN12_GLOBAL__N_122TOpticalStyleCandidateENS_9allocatorIS2_EEE12emplace_backIJS2_EEERS2_DpOT_ENKUlvE0_clEv
+ __Znwm
+ _uloc_getCountry
+ _uloc_getVariant
- __Z11TCFBase_NEWI16CTFontDescriptorJRPK9TBaseFont4$_30EE6TCFRefINT_7cf_typeEEDpOT0_
- __Z11TCFBase_NEWI16CTFontDescriptorJRPK9TBaseFont4$_30PK14__CFDictionaryEE6TCFRefINT_7cf_typeEEDpOT0_
- __ZN18TInlineBufferArenaILm3360ELm8EE10deallocateEPSt4bytem
- __ZN18TInlineBufferArenaILm3360ELm8EE8allocateILm8EEEPSt4bytem
- __ZN18TInlineBufferArenaILm64ELm8EE10deallocateEPSt4bytem
- __ZN18TInlineBufferArenaILm64ELm8EE8allocateILm8EEEPSt4bytem
- __ZNSt3__112__destroy_atB9fqn220106IN3OTL12GlyphLookups12LookupRangesEEEvPT_
- __ZNSt3__14swapB9fqn220106IN3OTL12GlyphLookups12LookupRangesEEENS_9enable_ifIXaasr21is_move_constructibleIT_EE5valuesr18is_move_assignableIS5_EE5valueEvE4typeERS5_S8_
- __ZdlPvSt11align_val_t
- __ZnwmSt11align_val_t
- _kCFLocaleVariantCode
CStrings:
+ "FONIPA"
+ "FONNAPA"
+ "FONUPA"
+ "IPPA"
+ "IPPH"
+ "PGR "
+ "POLYTON"
+ "UPPH"
- "TH"
- "fonipa"
- "fonnapa"
- "fonupa"
```
