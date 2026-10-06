## GenerativeSearch

> `/System/Library/PrivateFrameworks/GenerativeSearch.framework/GenerativeSearch`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x45a334` | `0x46df28` | **`+0x13bf4`** |
| `__DATA.__bss` | `0x652a0` | `0x671a0` | **`+0x1f00`** |
| `__DATA_DIRTY.__bss` | `0x24380` | `0x22500` | **`-0x1e80`** |
| `__TEXT.__eh_frame` | `0x18d50` | `0x1a088` | **`+0x1338`** |
| `__AUTH_CONST.__const` | `0x3e1d0` | `0x3eb08` | **`+0x938`** |
| `__DATA.__data` | `0xa840` | `0xb0f8` | **`+0x8b8`** |
| `__TEXT.__unwind_info` | `0x12ac8` | `0x13110` | **`+0x648`** |
| `__TEXT.__const` | `0x4f340` | `0x4f920` | **`+0x5e0`** |
| `__AUTH.__data` | `0x7450` | `0x7950` | **`+0x500`** |
| `__TEXT.__swift5_typeref` | `0x106c8` | `0x10afe` | **`+0x436`** |
| `__DATA_DIRTY.__data` | `0x93d0` | `0x9040` | **`-0x390`** |
| `__TEXT.__cstring` | `0x69f3` | `0x6d23` | **`+0x330`** |
| `__TEXT.__swift5_reflstr` | `0x131a4` | `0x13494` | **`+0x2f0`** |
| `__TEXT.__swift5_fieldmd` | `0x16b2c` | `0x16e04` | **`+0x2d8`** |
| `__TEXT.__constg_swiftt` | `0xbd14` | `0xbf74` | **`+0x260`** |
| `__TEXT.__swift5_capture` | `0x42b0` | `0x444c` | **`+0x19c`** |
| `__AUTH_CONST.__auth_got` | `0x13d0` | `0x1560` | **`+0x190`** |
| `__AUTH_CONST.__objc_const` | `0x1b70` | `0x1cb0` | **`+0x140`** |
| `__DATA.__common` | `0x58` | `0xe8` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x1a7e` | `0x1b0e` | **`+0x90`** |
| `__TEXT.__swift_as_cont` | `0x9bc` | `0xa38` | **`+0x7c`** |
| `__DATA_CONST.__got` | `0x5c8` | `0x630` | **`+0x68`** |
| `__TEXT.__swift5_assocty` | `0x5b40` | `0x5ba0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x110` | `0x160` | **`+0x50`** |
| `__TEXT.__swift_as_entry` | `0x5dc` | `0x62c` | **`+0x50`** |
| `__TEXT.__swift_as_ret` | `0x59c` | `0x5e8` | **`+0x4c`** |
| `__DATA_CONST.__objc_selrefs` | `0x500` | `0x528` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x1344` | `0x1364` | **`+0x20`** |
| `__TEXT.__swift5_mpenum` | `0x1c4` | `0x1bc` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x3f0` | `0x3f4` | **`+0x4`** |
| `__TEXT.__swift5_proto` | `0x4774` | `0x4778` | **`+0x4`** |

### Other Changes

```diff

-53.0.0.0.0
+57.0.1.0.0

+  - /System/Library/PrivateFrameworks/InternalSwiftProtobuf.framework/InternalSwiftProtobuf

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 32657
-  Symbols:   276
-  CStrings:  1058
+  Functions: 33194
+  Symbols:   279
+  CStrings:  1095
Symbols:
+ _OBJC_CLASS_$_NSFileHandle
+ _OBJC_CLASS_$_NSPurgeableData
+ _swift_release_x15
+ _swift_retain_x12
- _objc_release_x9
CStrings:
+ "DateSuggestion"
+ "EmbeddingClient.rebind: %{public}s → %{public}s"
+ "EmbeddingClient.updateEmbeddings(byReference:)"
+ "InternalSearchClient.dump(ofType:)"
+ "attribute_name"
+ "content_creation_date"
+ "documentNotFound"
+ "entity_type_name"
+ "extended"
+ "fullContent"
+ "has_lexical"
+ "has_lexical_term_matches"
+ "has_vector_scores"
+ "hybrid_search_xpc.ResultBatchProto"
+ "hybrid_search_xpc.ResultMetadataProto"
+ "hybrid_search_xpc.RetrievalBatchProto"
+ "hybrid_search_xpc.RetrievalMetadataProto"
+ "hybrid_search_xpc.TermMatchProto"
+ "hybrid_search_xpc.TermScoreProto"
+ "id=%{name=requestId,public}s\noperation=%{name=operation,public}s"
+ "identifier_type_raw"
+ "json"
+ "jsonl"
+ "lexical_score"
+ "lexical_term_matches"
+ "payload_byte_count"
+ "results"
+ "retrieveDomain"
+ "runSingleFlight(key:produce:)"
+ "searchDomain"
+ "searchGlobal"
+ "short"
+ "stable_identifier"
+ "stateOnly"
+ "term"
+ "term_scores"
+ "term_type_raw"
+ "vector_scores"
+ "versioned_identifier"
+ "xpcDecodeBatch"
+ "xpcEncodeBatch"
+ "xpcSerialization"
- "SearchIngestionClient.reset()"
- "contentCreationDate"
- "lexicalTermMatches"
- "provenanceIdentity"
- "termScoresWireFormat"
```
