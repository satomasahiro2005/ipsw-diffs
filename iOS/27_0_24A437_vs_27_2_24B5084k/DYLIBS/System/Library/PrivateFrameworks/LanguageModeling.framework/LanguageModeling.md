## LanguageModeling

> `/System/Library/PrivateFrameworks/LanguageModeling.framework/LanguageModeling`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x173654` | `0x174420` | **`+0xdcc`** |
| `__TEXT.__cstring` | `0xe12d` | `0xe2f7` | **`+0x1ca`** |
| `__TEXT.__gcc_except_tab` | `0x14d50` | `0x14e78` | **`+0x128`** |
| `__TEXT.__oslogstring` | `0x18ae` | `0x1929` | **`+0x7b`** |
| `__AUTH_CONST.__cfstring` | `0x3060` | `0x30a0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x78f8` | `0x7928` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2758` | `0x2778` | **`+0x20`** |

### Other Changes

```diff

-449.2.0.0.0
+449.3.0.0.0

-  Functions: 5792
+  Functions: 5797

-  CStrings:  2172
+  CStrings:  2186
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
+ "Dumping multilingual dynamic data from bundle %@ to %@"
+ "Skipping multilingual dynamic data dump: dynamic data is not loaded"
+ "The trie of the pieces is invalid."
+ "The trie of the reserved ids is invalid."
+ "lexicon-%@.plist"
+ "multilingual"
+ "pieces_.validate(GetPieceSize())"
+ "precompiled_charsmap is invalid."
+ "reserved_id_map_.validate(GetPieceSize())"
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
```
