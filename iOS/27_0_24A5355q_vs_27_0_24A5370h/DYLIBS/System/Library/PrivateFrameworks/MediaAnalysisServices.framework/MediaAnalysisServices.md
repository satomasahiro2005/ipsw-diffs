## MediaAnalysisServices

> `/System/Library/PrivateFrameworks/MediaAnalysisServices.framework/MediaAnalysisServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3deb0` | `0x3d698` | **`-0x818`** |
| `__TEXT.__cstring` | `0x3c78` | `0x3ab9` | **`-0x1bf`** |
| `__AUTH_CONST.__cfstring` | `0x4e40` | `0x4cc0` | **`-0x180`** |
| `__TEXT.__gcc_except_tab` | `0x4578` | `0x43fc` | **`-0x17c`** |
| `__AUTH_CONST.__objc_const` | `0xa210` | `0xa248` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x4f78` | `0x4fa4` | **`+0x2c`** |
| `__AUTH_CONST.__const` | `0x318` | `0x338` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1988` | `0x1978` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1c58` | `0x1c60` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x5a0` | `0x5a4` | **`+0x4`** |

### Other Changes

```diff

-435.60.2.11.2
+435.65.2.0.0

-  Functions: 1732
-  Symbols:   3461
-  CStrings:  874
+  Functions: 1736
+  Symbols:   3465
+  CStrings:  862
Symbols:
+ -[MADService cancelAndAbandonRequestID:]
+ -[MADTextEmbeddingRequest setUseCache:]
+ -[MADTextEmbeddingRequest useCache]
+ GCC_except_table107
+ GCC_except_table118
+ GCC_except_table124
+ GCC_except_table132
+ GCC_except_table133
+ GCC_except_table136
+ GCC_except_table147
+ GCC_except_table148
+ GCC_except_table151
+ GCC_except_table164
+ GCC_except_table182
+ GCC_except_table183
+ GCC_except_table187
+ GCC_except_table190
+ GCC_except_table191
+ GCC_except_table86
+ _OBJC_CLASS_$_MADCrossEncoder
+ _OBJC_IVAR_$_MADTextEmbeddingRequest._useCache
+ ___40-[MADService cancelAndAbandonRequestID:]_block_invoke
- GCC_except_table111
- GCC_except_table120
- GCC_except_table126
- GCC_except_table134
- GCC_except_table144
- GCC_except_table145
- GCC_except_table149
- GCC_except_table152
- GCC_except_table163
- GCC_except_table166
- GCC_except_table173
- GCC_except_table185
- GCC_except_table186
- GCC_except_table189
- GCC_except_table76
- GCC_except_table77
- GCC_except_table83
- _OBJC_CLASS_$_NSJSONSerialization
CStrings:
+ "UseCache"
+ "useCache: %d, "
- "EmbeddingCore bundle not found"
- "EmbeddingCore bundle resourceURL is nil"
- "Failed to parse cross encoder metadata JSON (%@)"
- "Failed to read cross encoder metadata (%@)"
- "Unexpected cross encoder metadata JSON item type"
- "Unexpected cross encoder metadata JSON shape"
- "VersionString"
- "com.apple.EmbeddingCore"
- "cross encoder metadata missing VersionString"
- "cross encoder metadata missing userDefinedMetadata"
- "cross_encoder_v120_ane_8bit_combined"
- "metadata.json"
- "mlmodelc"
- "userDefinedMetadata"
```
