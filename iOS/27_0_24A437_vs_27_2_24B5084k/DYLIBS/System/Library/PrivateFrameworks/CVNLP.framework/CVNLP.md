## CVNLP

> `/System/Library/PrivateFrameworks/CVNLP.framework/CVNLP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcba24` | `0xcc0d4` | **`+0x6b0`** |
| `__TEXT.__cstring` | `0x6dda` | `0x6f7d` | **`+0x1a3`** |
| `__TEXT.__gcc_except_tab` | `0xdec0` | `0xdf1c` | **`+0x5c`** |
| `__TEXT.__const` | `0x1e38` | `0x1e30` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x41c0` | `0x41b8` | **`-0x8`** |

### Other Changes

```diff

-130.0.0.0.0
+131.0.0.0.0

-  Functions: 2684
+  Functions: 2678

-  CStrings:  813
+  CStrings:  823
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
