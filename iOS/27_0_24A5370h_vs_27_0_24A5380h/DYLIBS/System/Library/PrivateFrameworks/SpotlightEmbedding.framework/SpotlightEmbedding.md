## SpotlightEmbedding

> `/System/Library/PrivateFrameworks/SpotlightEmbedding.framework/SpotlightEmbedding`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5510` | `0x55d4` | **`+0xc4`** |
| `__TEXT.__oslogstring` | `0x5ee` | `0x61b` | **`+0x2d`** |
| `__DATA_CONST.__objc_selrefs` | `0x4a8` | `0x4b0` | **`+0x8`** |

### Other Changes

```diff

-2448.100.0.0.0
+2451.1.101.0.0

-  Symbols:   267
-  CStrings:  103
+  Symbols:   268
+  CStrings:  104
Symbols:
+ _objc_opt_respondsToSelector
Functions:
~ ___159-[SPEmbeddingModel generateEmbeddingForTextInputs:extendedContextLength:bundleID:queryID:clientBundleID:timeout:useCLIPSafety:computeThreshold:workCost:error:]_block_invoke : 1260 -> 1456
CStrings:
+ "[qid=%ld] requesting useCache=%d (client:%@)"
```
