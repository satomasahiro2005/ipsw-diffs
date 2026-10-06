## Foundation

> `/System/Library/Frameworks/Foundation.framework/Foundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x33ddf3` | `0x407dc3` | **`+0xc9fd0`** |
| `__DATA_CONST.__const` | `0xa870` | `0xb6f8` | **`+0xe88`** |
| `__DATA_DIRTY.__bss` | `0x8158` | `0x8870` | **`+0x718`** |
| `__DATA.__bss` | `0x68fb8` | `0x688a8` | **`-0x710`** |
| `__DATA_DIRTY.__data` | `0x4d08` | `0x5158` | **`+0x450`** |
| `__AUTH.__objc_data` | `0x7b70` | `0x78b8` | **`-0x2b8`** |
| `__DATA.__data` | `0xd46c` | `0xd1b4` | **`-0x2b8`** |
| `__DATA_DIRTY.__objc_data` | `0x5fa0` | `0x6258` | **`+0x2b8`** |
| `__TEXT.__cstring` | `0x33b2e` | `0x33d92` | **`+0x264`** |
| `__AUTH.__data` | `0x6b68` | `0x69f0` | **`-0x178`** |
| `__TEXT.__text` | `0xc0a0a0` | `0xc0a210` | **`+0x170`** |
| `__DATA_DIRTY.__common` | `0x268` | `0x328` | **`+0xc0`** |
| `__DATA.__common` | `0x8a89` | `0x89d1` | **`-0xb8`** |
| `__AUTH_CONST.__cfstring` | `0x25e80` | `0x25f20` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x22520` | `0x22484` | **`-0x9c`** |
| `__TEXT.__unwind_info` | `0x1de10` | `0x1ddd0` | **`-0x40`** |
| `__AUTH_CONST.__const` | `0x377a0` | `0x377c0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x6010` | `0x601c` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x2a30` | `0x2a38` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xc940` | `0xc948` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2468c` | `0x24694` | **`+0x8`** |

### Other Changes

```diff

-5027.0.59.0.0
+5027.0.63.2.0

-  Functions: 43693
-  Symbols:   91747
-  CStrings:  7817
+  Functions: 43692
+  Symbols:   91748
+  CStrings:  7827
Symbols:
+ -[NSCoder _validateDictionary:forKey:matchesKeyClasses:valueClasses:strictModeEnabled:alwaysEnforceExplicitSubclasses:]
+ -[NSCoder(Exceptions) __decoderEnforceCollectionType]
+ _$s10Foundation13_CharacterSetC12charactersInACSS_tcfCTf4gd_n
+ _$s10Foundation13_CharacterSetC6removeys7UnicodeO6ScalarVSgAHF
+ _$s10Foundation13_CharacterSetC6update4withs7UnicodeO6ScalarVSgAI_tF
+ _$s10Foundation21__CharacterSetStorage33_45BFD3D387700B862E3A7353B97EF7EDLLC8containsySbs7UnicodeO6ScalarVF
+ _$s10Foundation23BuiltInUnicodeScalarSetV0F4TypeOwetTm
+ _$s10Foundation23BuiltInUnicodeScalarSetV0F4TypeOwstTm
+ _$s10Foundation23BuiltInUnicodeScalarSetV12isWhitespaceySbs0D0O0E0VFTf4nd_n
+ _$s10Foundation23BuiltInUnicodeScalarSetV18_bitmapPtrForPlaneys4SpanVys5UInt8VG4span_Sb12shouldInverttSgSiF
+ _$s10Foundation23BuiltInUnicodeScalarSetV9hasMember7inPlane10isInvertedSbs5UInt8V_SbtF
+ _$s10Foundation30_createCFStringFromASCIIBuffer8capacity21initializingASCIIWiths9UnmanagedVySo0C3RefaGSgSi_SiSrys5UInt8VGXEtFAjMXEfU_013$sSo5NSURLC10a31E25__copySwiftEncodedFSRPathys9i6VySo11c18RefaGSgSSFZAJSrys5K16VGXEfU_SiAMXEfU_AMSiTf1nnnc_n
+ _$s10Foundation30_createCFStringFromASCIIStringys9UnmanagedVySo0C3RefaGSgSSF
+ _$sSo5NSURLC10FoundationE25__copySwiftEncodedFSRPathys9UnmanagedVySo11CFStringRefaGSgSSFZAJSrys5UInt8VGXEfU_
+ _$sSo5NSURLC10FoundationE25__copySwiftEncodedFSRPathys9UnmanagedVySo11CFStringRefaGSgSSFZTf4nd_n
+ _$sSo5NSURLC10FoundationE25__copySwiftEncodedFSRPathys9UnmanagedVySo11CFStringRefaGSgSSFZTo
+ _$ss11InlineArrayV9repeatingAByxq_Gq__tcfC$15__s5UInt8VTt1g5
+ ___53-[NSCoder(Exceptions) __decoderEnforceCollectionType]_block_invoke
+ ___CFUniCharBitmapDataArray
+ ___SCR_NSKeyValueNestedProperty
+ ___block_descriptor_64_e8_32r40r_e12_v24?0Q8^B16lr32l8r40l8
- GCC_except_table98
- _$s10Foundation11JSONEncoderC19KeyEncodingStrategyO19_convertToSnakeCase33_12768CA107A31EF2DCE034FD75B541C9LLyS2SFZTf4nd_n
- _$s10Foundation12CharacterSetV6update4withs7UnicodeO6ScalarVSgAI_tFTm
- _$s10Foundation12CharacterSetVs0C7AlgebraAAsADP6removey7ElementQzSgAHFTWTm
- _$s10Foundation13_CharacterSetC11bmpContains33_D579BB95037134886C765EFA7998B711LLySbs7UnicodeO6ScalarVF
- _$s10Foundation13_CharacterSetC12charactersInACSS_tcfCTf4nd_n
- _$s10Foundation13_CharacterSetC12charactersInACSS_tcfcSbs7UnicodeO6ScalarVXEfU_
- _$s10Foundation13_CharacterSetC12charactersInACSS_tcfcSbs7UnicodeO6ScalarVXEfU_TA
- _$s10Foundation13_CharacterSetC8containsySbs7UnicodeO6ScalarVF
- _$s10Foundation21__CharacterSetStorage33_45BFD3D387700B862E3A7353B97EF7EDLLC6update4withs7UnicodeO6ScalarVSgAJ_tF
- _$s10Foundation23BuiltInUnicodeScalarSetV18_bitmapPtrForPlane33_EAEADB817D701D08BFCF242A1CEA685FLLys4SpanVys5UInt8VG4span_Sb12shouldInverttSgSiF
- _$s10Foundation23BuiltInUnicodeScalarSetVwetTm
- _$s10Foundation23BuiltInUnicodeScalarSetVwstTm
- _$sSmsE9removeAll5whereySb7ElementQzKXE_tKFSS17UnicodeScalarViewV_Tg5
- _$sSo5NSURLC10FoundationE24__copySwiftDecodedStringySSSgSSFZToTm
- _$sSo5NSURLC10FoundationE25__copySwiftEncodedFSRPathySSSgSSFZAESrys5UInt8VGXEfU_
- _$sSo5NSURLC10FoundationE25__copySwiftEncodedFSRPathySSSgSSFZAESrys5UInt8VGXEfU_AeHXEfU_
- _$sSo5NSURLC10FoundationE25__copySwiftEncodedFSRPathySSSgSSFZTf4nd_n
- _$sSo5NSURLC10FoundationE25__copySwiftEncodedFSRPathySSSgSSFZTo
- ___block_descriptor_56_e8_32r_e12_v24?0Q8^B16lr32l8
CStrings:
+ "\"Foundation\""
+ "\"NSXPCCoderEnforceDistantObjectType\""
+ "%@: Received a returned proxy object that does not conform to the protocol specified in the NSXPCInterface for this argument."
+ "NSKeyedUnarchiverEnforceCollectionType"
+ "_NSKeyValueObservationInfoGetObservances"
+ "dictionary for key '%@' contained a key of class '%@' which is not in the allowed key classes"
+ "dictionary for key '%@' contained a value of class '%@' which is not in the allowed object classes"
+ "nestedCount + unnestedCount + internalCount == observancesCount"
+ "value for key '%@' was not an NSArray (got %@)"
+ "value for key '%@' was not an NSDictionary (got %@)"
```
