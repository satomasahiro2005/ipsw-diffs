## SpotlightEmbedding

> `/System/Library/PrivateFrameworks/SpotlightEmbedding.framework/SpotlightEmbedding`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55d4` | `0x5600` | **`+0x2c`** |
| `__AUTH_CONST.__cfstring` | `0x6a0` | `0x6c0` | **`+0x20`** |
| `__AUTH_CONST.__objc_floatobj` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__cstring` | `0x563` | `0x572` | **`+0xf`** |
| `__TEXT.__const` | `0xd0` | `0xc8` | **`-0x8`** |

### Other Changes

```diff

-2451.1.101.0.0
+2454.100.0.0.0

-  Symbols:   268
-  CStrings:  104
+  Symbols:   269
+  CStrings:  105
Symbols:
+ _OBJC_CLASS_$_NSConstantFloatNumber
+ _objc_retain_x27
- _objc_retain_x26
Functions:
~ ___159-[SPEmbeddingModel generateEmbeddingForTextInputs:extendedContextLength:bundleID:queryID:clientBundleID:timeout:useCLIPSafety:computeThreshold:workCost:error:]_block_invoke.237 -> ___159-[SPEmbeddingModel generateEmbeddingForTextInputs:extendedContextLength:bundleID:queryID:clientBundleID:timeout:useCLIPSafety:computeThreshold:workCost:error:]_block_invoke.240 : 3148 -> 3192
CStrings:
+ "com.apple.Home"
```
