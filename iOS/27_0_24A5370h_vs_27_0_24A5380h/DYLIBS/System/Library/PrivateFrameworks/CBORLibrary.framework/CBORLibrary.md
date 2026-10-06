## CBORLibrary

> `/System/Library/PrivateFrameworks/CBORLibrary.framework/CBORLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28814` | `0x2b444` | **`+0x2c30`** |
| `__TEXT.__oslogstring` | `0x75` | `0x9a2` | **`+0x92d`** |
| `__TEXT.__cstring` | `0xab1` | `0xc6d` | **`+0x1bc`** |
| `__AUTH.__objc_data` | `—` | `0x98` | **`+0x98`** |
| `__DATA_DIRTY.__objc_data` | `0x2b8` | `0x220` | **`-0x98`** |
| `__AUTH_CONST.__auth_got` | `0x9f8` | `0xa40` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x938` | `0x978` | **`+0x40`** |
| `__DATA_CONST.__const` | `0xc0` | `0x100` | **`+0x40`** |
| `__TEXT.__const` | `0x1848` | `0x1878` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x1c40` | `0x1c70` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x590` | `0x5b0` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x458` | `0x474` | **`+0x1c`** |
| `__DATA.__data` | `0x2e0` | `0x2f8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x238` | `0x250` | **`+0x18`** |
| `__DATA.__common` | `0x18` | `0x28` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x100` | `0x110` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xa38` | `0xa40` | **`+0x8`** |

### Other Changes

```diff

-6.0.4.0.0
+6.0.5.0.0

-  Functions: 912
-  Symbols:   563
-  CStrings:  116
+  Functions: 914
+  Symbols:   587
+  CStrings:  189
Symbols:
+ _OBJC_CLASS_$_NSMutableSet
+ __NSConcreteGlobalBlock
+ ___38-[CBOR _calculateDictionaryHash:hash:]_block_invoke
+ ____randomHashSeed_block_invoke
+ ___block_descriptor_32_e15_i24?0r^v8r^v16l
+ ___block_descriptor_tmp
+ ___block_literal_global
+ ___unnamed_35
+ __os_log_impl
+ __randomHashSeed.once
+ __randomHashSeed.seed
+ _abort
+ _arc4random_buf
+ _cbor_fnv1a_hash
+ _cbor_fnv1a_hash_64
+ _cbor_fnv1a_hash_with_offsetBasis
+ _cbor_fnv1a_hash_with_offsetBasis_64
+ _dispatch_once
+ _free
+ _malloc_type_calloc
+ _qsort_b
+ _swift_getAssociatedConformanceWitness
+ _swift_getAssociatedTypeWitness
+ _swift_release_x24
+ _swift_unknownObjectRelease_n
+ _symbolic SDy_____SE_pG s11AnyHashableV
+ _symbolic Sz_p
+ _symbolic _____3key_SE_p5valuet s11AnyHashableV
- ___30-[COSE _searchForHeaderLabel:]_block_invoke_2
- ___unnamed_34
- _swift_release_x28
- _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
CStrings:
+ "%s: Algorithm %@ not implemented."
+ "%s: Allocation failure"
+ "%s: COSEContentType %ld does not match tag %{private}@"
+ "%s: Duplicated key found, %{private}@"
+ "%s: Encoded item is not well-formed, header=0x%02X"
+ "%s: Error interpreting date time string: %{private}@"
+ "%s: Error interpreting date time string: %{public}@"
+ "%s: Failure decoding infinite item list"
+ "%s: Indefinite-length string violates internal invariant"
+ "%s: Insufficient data"
+ "%s: Invalid CBOR data type in indefinite-length string"
+ "%s: Invalid COSE data type: %{private}@"
+ "%s: Invalid COSE tag for message identification: %ld"
+ "%s: Invalid COSE_Sign1 data type: %lu"
+ "%s: Invalid UTF8 string"
+ "%s: Invalid data length!  Dropping rest of data as CBOR is invalid"
+ "%s: Invalid data marked by Tag 24"
+ "%s: Invalid format string, %{private}@"
+ "%s: Invalid fractional digits, %{private}@"
+ "%s: Invalid payload type: %lu"
+ "%s: Invalid protected header: %{private}@"
+ "%s: Invalid string length, %{private}@"
+ "%s: Invalid time string, %{private}@"
+ "%s: Invalid timezone format, %{private}@"
+ "%s: Invalid timezone specifier, %{private}@"
+ "%s: Major type 1 negative int64 underflow"
+ "%s: Malformed chunk found in indefinite-length string"
+ "%s: Malformed map; mismatch in expected entries"
+ "%s: Missing data length"
+ "%s: Missing termination break in indefinite-length string"
+ "%s: Missing unprotected header"
+ "%s: Nested indefinite-length string found"
+ "%s: No chunks found; creates empty string"
+ "%s: Not implemented counter signature parsing"
+ "%s: Number of items is greater than buffer size"
+ "%s: Only %zu fractional digits is supported"
+ "%s: ParseHeader: COSE Header-IV"
+ "%s: ParseHeader: COSE Header-algo"
+ "%s: ParseHeader: COSE Header-contentType"
+ "%s: ParseHeader: COSE Header-counter signature"
+ "%s: ParseHeader: COSE Header-crit"
+ "%s: ParseHeader: COSE Header-kid"
+ "%s: ParseHeader: COSE Header-partial IV"
+ "%s: Protected header decode failure"
+ "%s: RSA key support not implemented."
+ "%s: Skipping unexpected label: %{private}@"
+ "%s: Unexpected # of elements in COS structure: %lu"
+ "%s: Unexpected COSE key type: %lu"
+ "%s: Unexpected KTY type: %lu"
+ "%s: Unexpected characters after timezone, %{private}@"
+ "%s: Unexpected data chunk"
+ "%s: Unexpected key type: %{private}@, value: %{private}@"
+ "%s: Unexpected payload: %{private}@"
+ "%s: Unexpected signature: %{private}@"
+ "%s: Unexpected tag type: %{private}@"
+ "%s: Unexpected tag: %{private}@"
+ "%s: Unexpected type: %{private}@"
+ "%s: key is nil"
+ "-[CBOR _calculateDictionaryHash:hash:]"
+ "-[CBOR(Decoder) asJSON]"
+ "-[COSE _getProtectedHeadererDictionary:]"
+ "-[COSE _parseCommonHeaderParameters:]"
+ "-[COSE _parseCommonStructure:]"
+ "-[COSE _searchForHeaderLabel:]_block_invoke"
+ "-[COSE initWithCBOR:]"
+ "-[COSE initWithData:type:]"
+ "-[COSEKey initWithCBOR:]"
+ "-[COSE_Mac0 initWithCBOR:]"
+ "-[COSE_Sign1 initWithCBOR:]"
+ "NSDate *parseDateString(NSString *__strong)"
+ "Unsupported type for CodingKey "
+ "i24@?0r^v8r^v16"
+ "v8@?0"
```
