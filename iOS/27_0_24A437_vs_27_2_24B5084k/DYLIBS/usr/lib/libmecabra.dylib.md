## libmecabra.dylib

> `/usr/lib/libmecabra.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26ca88` | `0x26d218` | **`+0x790`** |
| `__TEXT.__cstring` | `0x16b15` | `0x16ca3` | **`+0x18e`** |
| `__TEXT.__gcc_except_tab` | `0x1a848` | `0x1a908` | **`+0xc0`** |
| `__TEXT.__const` | `0x3004c` | `0x2ffdc` | **`-0x70`** |
| `__AUTH_CONST.__const` | `0x43620` | `0x435d0` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0xce90` | `0xcea8` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x4a59` | `0x4a70` | **`+0x17`** |
| `__AUTH_CONST.__auth_got` | `0x13f8` | `0x13e8` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x440` | `0x438` | **`-0x8`** |

### Other Changes

```diff

-1159.0.0.0.0
+1160.1.3.0.0

-  Functions: 11150
-  Symbols:   1095
-  CStrings:  4429
+  Functions: 11151
+  Symbols:   1092
+  CStrings:  4439
Symbols:
- _host_statistics
- _mach_host_self
- _vm_page_size
CStrings:
+ "!pieces_blob.empty()"
+ "(piece_offsets_[i]) < (pieces_blob.size())"
+ "(pieces_blob.back()) == ('\\0')"
+ "(unk_id_) < (GetPieceSize())"
+ "(unk_id_) >= (0)"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/src/mmap_model_proto.cc"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1161: exception: failed to insert key: negative value"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1163: exception: failed to insert key: zero-length key"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1177: exception: failed to insert key: invalid null character"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1182: exception: failed to insert key: wrong key order"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1394: exception: failed to modify unit: too large offset"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1730: exception: failed to build double-array: invalid null character"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1732: exception: failed to build double-array: negative value"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1747: exception: failed to build double-array: wrong key order"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:798: exception: failed to resize pool: std::bad_alloc"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:914: exception: failed to build rank index: std::bad_alloc"
+ "The trie of the pieces is invalid."
+ "The trie of the reserved ids is invalid."
+ "[E5Runner] Path %zu: surface='%s', originalCost=%f, e5RunnerProb=%f, geometryCost=%f, syllableMatchPenalty=%f, adaptationBoost=%f, readingMismatchPenalty=%f, dynamicWordReward=%f, wordStructureBonus=%f, finalScore=%f"
+ "pieces_.validate(GetPieceSize())"
+ "precompiled_charsmap is invalid."
+ "reserved_id_map_.validate(GetPieceSize())"
+ "v24@?0r^{mecab_node_t=^{mecab_node_t}^{mecab_node_t}^{mecab_node_t}^{mecab_node_t}**^{mecab_analysis_string_t}qIISSssSSSSSCCCCC}8^B16"
- "(num_nodes) < (trie_results.size())"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1111: exception: failed to insert key: negative value"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1113: exception: failed to insert key: zero-length key"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1127: exception: failed to insert key: invalid null character"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1132: exception: failed to insert key: wrong key order"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1344: exception: failed to modify unit: too large offset"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1680: exception: failed to build double-array: invalid null character"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1682: exception: failed to build double-array: negative value"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:1697: exception: failed to build double-array: wrong key order"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:748: exception: failed to resize pool: std::bad_alloc"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SentencePiece/third_party/darts_clone/darts.h:864: exception: failed to build rank index: std::bad_alloc"
- "[E5Runner] Path %zu: surface='%s', originalCost=%f, e5RunnerProb=%f, geometryCost=%f, syllableMatchPenalty=%f, adaptationBoost=%f, readingMismatchPenalty=%f, dynamicWordReward=%f, finalScore=%f"
- "v24@?0r^{mecab_node_t=^{mecab_node_t}^{mecab_node_t}^{mecab_node_t}^{mecab_node_t}^{mecab_path_t}^{mecab_path_t}**^{mecab_analysis_string_t}IIIssSSSSqSCCCCCc}8^B16"
```
