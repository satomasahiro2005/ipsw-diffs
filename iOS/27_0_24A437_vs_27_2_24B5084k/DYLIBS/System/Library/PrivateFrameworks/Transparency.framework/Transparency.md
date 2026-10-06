## Transparency

> `/System/Library/PrivateFrameworks/Transparency.framework/Transparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7db84` | `0x81f00` | **`+0x437c`** |
| `__TEXT.__const` | `0x4a80` | `0x4ec0` | **`+0x440`** |
| `__DATA.__bss` | `0x7250` | `0x7600` | **`+0x3b0`** |
| `__TEXT.__eh_frame` | `0x35b0` | `0x3840` | **`+0x290`** |
| `__AUTH_CONST.__const` | `0x3df8` | `0x3ff8` | **`+0x200`** |
| `__TEXT.__oslogstring` | `0x1e5b` | `0x204b` | **`+0x1f0`** |
| `__TEXT.__unwind_info` | `0x2c00` | `0x2d18` | **`+0x118`** |
| `__TEXT.__swift5_fieldmd` | `0xcb0` | `0xd90` | **`+0xe0`** |
| `__AUTH.__data` | `0x548` | `0x5e8` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x303c` | `0x30dc` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x1050` | `0x10e4` | **`+0x94`** |
| `__TEXT.__swift5_reflstr` | `0x95a` | `0x9ca` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0xad8` | `0xb44` | **`+0x6c`** |
| `__TEXT.__swift5_acfuncs` | `0x168` | `0x1b8` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x200` | `0x248` | **`+0x48`** |
| `__DATA.__data` | `0x1090` | `0x10d0` | **`+0x40`** |
| `__TEXT.__swift_as_entry` | `0x120` | `0x148` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0xfc` | `0x11c` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x3a8` | `0x3c4` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0xc90` | `0xca0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x650` | `0x660` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x4a90` | `0x4aa0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2030` | `0x2038` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xf0` | `0xf8` | **`+0x8`** |

### Other Changes

```diff

-1766.0.60.0.0
+1766.40.47.0.0

-  Functions: 3793
-  Symbols:   3565
-  CStrings:  769
+  Functions: 3887
+  Symbols:   3579
+  CStrings:  783
Symbols:
+ -[TransparencyAnalytics fuzzyDaysSinceDate:]
+ GCC_except_table158
+ GCC_except_table186
+ GCC_except_table219
+ _NSInvalidArchiveOperationException
+ _OBJC_CLASS_$_NSException
+ ___27-[KTIDSData initWithCoder:]_block_invoke
+ ___29-[KTIDSData encodeWithCoder:]_block_invoke
+ ___30-[KTIDSDataURI initWithCoder:]_block_invoke
+ ___32-[KTIDSDataURI encodeWithCoder:]_block_invoke
+ ___43-[KTIDSDataURI initWithIDSData:ktResponse:]_block_invoke
+ _associated conformance 12Transparency15CKVLastRanEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOSHAASQ
+ _associated conformance 12Transparency15CKVLastRanEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 12Transparency15CKVLastRanEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _kTransparencyStaticKeyStoreContactExternalURI
+ _symbolic Say_____G 12Transparency15CKVLastRanEntryV
+ _symbolic _____ 12Transparency15CKVLastRanEntryV
+ _symbolic _____ 12Transparency15CKVLastRanEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12Transparency15CKVLastRanEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12Transparency15CKVLastRanEntryV10CodingKeys33_5CE8840853DFFCDC7F035A4955177193LLO
+ _symbolic xSay_____G______p_____Rz_____RzlIetMHgozo_ 12Transparency15CKVLastRanEntryV s5ErrorP 11Distributed01_F9ActorStubP AA21CKVDiagnosticsServiceP
+ _symbolic xSay_____G______p_____RzlIetWHgozo_ 12Transparency15CKVLastRanEntryV s5ErrorP AA21CKVDiagnosticsServiceP
- GCC_except_table154
- GCC_except_table182
- GCC_except_table215
- GCC_except_table88
- _KTIDStaticKeyStoreEntryChanged
- _KTIDStaticKeyStoreEntryIdentifier
- ___swift_get_extra_inhabitant_index.13Tm
- ___swift_store_extra_inhabitant_index.14Tm
CStrings:
+ "KTIDSData: decoded without application, dropping"
+ "KTIDSData: decoded without ktAccountKey for %@, dropping"
+ "KTIDSData: decoded without uri, dropping"
+ "KTIDSData: encoding without application for %@"
+ "KTIDSData: encoding without ktAccountKey for %@ %@"
+ "KTIDSData: encoding without uri"
+ "KTIDSDataURI has no idsData or ktResponse"
+ "KTIDSDataURI: created with idsData: %@ ktResponse: %@"
+ "KTIDSDataURI: decoded without idsData, dropping"
+ "KTIDSDataURI: decoded without ktResponse for %@, dropping"
+ "KTIDSDataURI: encoding with idsData: %@ ktResponse: %@"
+ "eventNotYetTransparent"
+ "kTransparencyStaticKeyStoreContactExternalURI"
+ "lastMilestoneFetch"
+ "lastRanFailures()"
+ "minimumIntervalSeconds"
- "KTIDStaticKeyStoreEntryIdentifier"
- "TransparancyKTIDStaticKeyStoreEntry"
```
