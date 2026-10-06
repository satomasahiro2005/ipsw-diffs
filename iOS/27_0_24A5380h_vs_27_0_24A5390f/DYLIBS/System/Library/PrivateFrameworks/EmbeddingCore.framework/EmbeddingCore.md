## EmbeddingCore

> `/System/Library/PrivateFrameworks/EmbeddingCore.framework/EmbeddingCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6ca30` | `0x6d880` | **`+0xe50`** |
| `__TEXT.__oslogstring` | `0x171f` | `0x19af` | **`+0x290`** |
| `__AUTH_CONST.__objc_const` | `0x3f08` | `0x4080` | **`+0x178`** |
| `__TEXT.__gcc_except_tab` | `0x7108` | `0x7260` | **`+0x158`** |
| `__AUTH_CONST.__cfstring` | `0x1b00` | `0x1ba0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x1c74` | `0x1d0c` | **`+0x98`** |
| `__TEXT.__cstring` | `0x5c86` | `0x5ce6` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x50` | `0xa0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x2a70` | `0x2ab0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xe88` | `0xec0` | **`+0x38`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x240` | `0x258` | **`+0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0x138` | `0x150` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x2a0` | `0x2b8` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x5a8` | `0x5b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x3d0` | `0x3d8` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x3a0` | `0x3a8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1a8` | `0x1b0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xc8` | `0xd0` | **`+0x8`** |

### Other Changes

```diff

-435.69.2.0.0
+435.73.2.0.0

-  Functions: 2177
-  Symbols:   3425
-  CStrings:  725
+  Functions: 2200
+  Symbols:   3452
+  CStrings:  743
Symbols:
+ +[MADSafariTextEmbeddingAdapter createForEmbeddingVersion:computeUnits:extendedContextLength:]
+ -[MADSafariTextEmbeddingAdapter .cxx_destruct]
+ -[MADSafariTextEmbeddingAdapter _loadResources]
+ -[MADSafariTextEmbeddingAdapter _runWithSpatial:eosPosition:output:]
+ -[MADSafariTextEmbeddingAdapter initWithComputeUnits:extendedContextLength:]
+ -[MADSafariTextEmbeddingAdapter loadResources]
+ -[MADSafariTextEmbeddingAdapter runWithSpatial:eosPosition:output:]
+ -[MADTextEncoderE5MLNetworkOutput eosPosition]
+ -[MADTextEncoderE5MLNetworkOutput setEosPosition:]
+ -[MADTextEncoderOutput eosPosition]
+ -[MADTextEncoderOutput setEosPosition:]
+ GCC_except_table146
+ _OBJC_CLASS_$_MADSafariTextEmbeddingAdapter
+ _OBJC_IVAR_$_MADSafariTextEmbeddingAdapter._computeUnits
+ _OBJC_IVAR_$_MADSafariTextEmbeddingAdapter._extendedContextLength
+ _OBJC_IVAR_$_MADSafariTextEmbeddingAdapter._inference
+ _OBJC_IVAR_$_MADSafariTextEmbeddingAdapter._queue
+ _OBJC_IVAR_$_MADTextEncoderE5MLNetworkOutput._eosPosition
+ _OBJC_IVAR_$_MADTextEncoderOutput._eosPosition
+ _OBJC_METACLASS_$_MADSafariTextEmbeddingAdapter
+ __OBJC_$_CLASS_METHODS_MADSafariTextEmbeddingAdapter
+ __OBJC_$_INSTANCE_METHODS_MADSafariTextEmbeddingAdapter
+ __OBJC_$_INSTANCE_VARIABLES_MADSafariTextEmbeddingAdapter
+ __OBJC_CLASS_RO_$_MADSafariTextEmbeddingAdapter
+ __OBJC_METACLASS_RO_$_MADSafariTextEmbeddingAdapter
+ ___46-[MADSafariTextEmbeddingAdapter loadResources]_block_invoke
+ ___67-[MADSafariTextEmbeddingAdapter runWithSpatial:eosPosition:output:]_block_invoke
CStrings:
+ "MADSafariTextEmbeddingAdapter"
+ "MADSafariTextEmbeddingAdapter_loadResources"
+ "MADSafariTextEmbeddingAdapter_run"
+ "MD8-Safari"
+ "SystemSearch/v8.0.0"
+ "[Text|SafariAdapter] Embedding version %d has no Safari head"
+ "[Text|SafariAdapter] adapter inference failed (%@)"
+ "[Text|SafariAdapter] adapter model not found in bundle"
+ "[Text|SafariAdapter] adapter produced no output"
+ "[Text|SafariAdapter] failed to create eos_pos input (%@)"
+ "[Text|SafariAdapter] failed to create spatial input (%@)"
+ "[Text|SafariAdapter] failed to load adapter model"
+ "[Text|SafariAdapter] failed to load adapter model (%@)"
+ "[Text|SafariAdapter] failed to set inputs (%@)"
+ "[Text|SafariAdapter] spatial length (%@) does not match the selected function's input (%@)"
+ "eos_pos"
+ "md8-safari-adapter"
+ "spatial"
```
