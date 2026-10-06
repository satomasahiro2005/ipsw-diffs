## EmbeddingCore

> `/System/Library/PrivateFrameworks/EmbeddingCore.framework/EmbeddingCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6bca0` | `0x6bd94` | **`+0xf4`** |
| `__TEXT.__oslogstring` | `0x191f` | `0x195f` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x7308` | `0x7330` | **`+0x28`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-460.8.2.0.0
+460.12.1.0.0

-  Functions: 2125
+  Functions: 2127

-  CStrings:  740
+  CStrings:  741
Functions:
~ -[MADCrossEncoder _processNextBatch:] : 1660 -> 1664
~ -[MADCrossEncoder _processQuery:documents:maxNumChunks:chunkOverlap:outputs:] : 1852 -> 1928
~ -[MADCrossEncoder _createBatchedInputIdsWithBatchSize:queryTokens:chunks:realCount:] : 1084 -> 1148
~ _OUTLINED_FUNCTION_7 : 24 -> 20
+ _OUTLINED_FUNCTION_8
~ __ZNKSt3__114default_deleteIN13sentencepiece4util6Status3RepEEclB9fqe220106EPS4_ : 92 -> 120
~ -[MADCrossEncoder _processQuery:documents:maxNumChunks:chunkOverlap:outputs:].cold.2 : 56 -> 64
~ -[MADCrossEncoder _processQuery:documents:maxNumChunks:chunkOverlap:outputs:].cold.3 : 60 -> 56
~ -[MADCrossEncoder _processQuery:documents:maxNumChunks:chunkOverlap:outputs:].cold.7 : 56 -> 60
~ -[MADCrossEncoder _processQuery:documents:maxNumChunks:chunkOverlap:outputs:].cold.8 : 80 -> 56
+ +[MADTextEmbeddingSafety createForEmbeddingVersion:].cold.1
CStrings:
+ "MADCrossEncoder: no room for document tokens (ctx %lu, query %lu)"
+ "cross_encoder_v140_ane_8bit_combined"
- "cross_encoder_v130_ane_8bit_combined"
```
