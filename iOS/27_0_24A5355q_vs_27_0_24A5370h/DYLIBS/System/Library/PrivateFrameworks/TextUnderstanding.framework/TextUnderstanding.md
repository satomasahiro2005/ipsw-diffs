## TextUnderstanding

> `/System/Library/PrivateFrameworks/TextUnderstanding.framework/TextUnderstanding`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x126d08` | `0x1321dc` | **`+0xb4d4`** |
| `__DATA.__bss` | `0x37580` | `0x3b600` | **`+0x4080`** |
| `__TEXT.__const` | `0x26350` | `0x27d20` | **`+0x19d0`** |
| `__TEXT.__swift5_typeref` | `0x6d71` | `0x73c5` | **`+0x654`** |
| `__DATA.__data` | `0x4448` | `0x4a90` | **`+0x648`** |
| `__AUTH_CONST.__const` | `0xf170` | `0xf708` | **`+0x598`** |
| `__TEXT.__constg_swiftt` | `0x5634` | `0x5b2c` | **`+0x4f8`** |
| `__TEXT.__swift5_fieldmd` | `0x7d40` | `0x81d0` | **`+0x490`** |
| `__TEXT.__unwind_info` | `0x6e20` | `0x7260` | **`+0x440`** |
| `__TEXT.__eh_frame` | `0x5a90` | `0x5e30` | **`+0x3a0`** |
| `__AUTH.__data` | `0x638` | `0x908` | **`+0x2d0`** |
| `__TEXT.__swift5_proto` | `0x252c` | `0x2730` | **`+0x204`** |
| `__TEXT.__oslogstring` | `0xe15` | `0xce5` | **`-0x130`** |
| `__AUTH_CONST.__auth_got` | `0xc98` | `0xc08` | **`-0x90`** |
| `__TEXT.__swift5_types` | `0x9bc` | `0xa44` | **`+0x88`** |
| `__TEXT.__swift5_reflstr` | `0x39c0` | `0x3a30` | **`+0x70`** |
| `__TEXT.__swift5_builtin` | `0x104` | `0xdc` | **`-0x28`** |
| `__DATA_DIRTY.__data` | `0x3b78` | `0x3b88` | **`+0x10`** |
| `__TEXT.__cstring` | `0x2b67` | `0x2b57` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x270` | `0x280` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x14` | `0x20` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x10` | `0x1c` | **`+0xc`** |
| `__AUTH_CONST.__objc_const` | `0x7a8` | `0x7b0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x258` | `0x260` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x120` | `0x118` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x8` | `0xc` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x4` | `0x8` | **`+0x4`** |

### Other Changes

```diff

-161.1.0.0.0
+167.1.0.0.0

-  Functions: 12405
-  Symbols:   170
-  CStrings:  384
+  Functions: 12948
+  Symbols:   169
+  CStrings:  379
Symbols:
+ _swift_unexpectedError
- _os_unfair_lock_lock
- _os_unfair_lock_unlock
CStrings:
+ "  renderedPrompt:\n"
+ "TextProcessingService: processingAvailability called for %s"
+ "TextProcessingService: processingAvailability failed with TextProcessingError: %@"
+ "TextProcessingService: processingAvailability failed with unknown error: %@"
+ "languageIdentificationTextChunks"
- "ModelVersionChecker: Failed to detect model prompt type: %@"
- "ModelVersionChecker: adapter asset has no promptPreprocessingTemplateVersion"
- "ModelVersionChecker: adapterMetadataOverride asset has no promptPreprocessingTemplateVersion"
- "ModelVersionChecker: bundle has no adapterMetadataOverride or adapter"
- "ModelVersionChecker: isV11 determination failed, using default value false"
- "ModelVersionChecker: isV11 successfully determined: %{bool}d"
- "ModelVersionChecker: resource bundle is not AssetBackedLLMBundle"
- "eventNotesProvider"
- "eventNotesTypeCarRentalAgency"
- "eventNotesTypeShowProvider"
```
