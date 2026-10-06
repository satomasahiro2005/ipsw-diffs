## VisualGeneration

> `/System/Library/PrivateFrameworks/VisualGeneration.framework/VisualGeneration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2bee90` | `0x2c599c` | **`+0x6b0c`** |
| `__TEXT.__const` | `0x21dc8` | `0x21f78` | **`+0x1b0`** |
| `__TEXT.__swift5_reflstr` | `0x8d21` | `0x8e21` | **`+0x100`** |
| `__TEXT.__swift5_fieldmd` | `0x8e98` | `0x8f54` | **`+0xbc`** |
| `__AUTH_CONST.__objc_const` | `0x54d0` | `0x5588` | **`+0xb8`** |
| `__AUTH.__data` | `0x3df8` | `0x3ea8` | **`+0xb0`** |
| `__AUTH_CONST.__const` | `0x15428` | `0x154d0` | **`+0xa8`** |
| `__DATA_CONST.__got` | `0x1098` | `0x1140` | **`+0xa8`** |
| `__TEXT.__oslogstring` | `0x5829` | `0x58c9` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x179e8` | `0x17a80` | **`+0x98`** |
| `__DATA.__bss` | `0x266e0` | `0x26760` | **`+0x80`** |
| `__DATA.__data` | `0x4138` | `0x41b8` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x2dc0` | `0x2e38` | **`+0x78`** |
| `__TEXT.__cstring` | `0x7643` | `0x76b3` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x7f6e` | `0x7fd6` | **`+0x68`** |
| `__TEXT.__constg_swiftt` | `0x7adc` | `0x7b3c` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x92e0` | `0x9320` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x4e0` | `0x500` | **`+0x20`** |
| `__DATA.__common` | `0x128` | `0x138` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x2e0` | `0x2e8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x8b8` | `0x8c0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x9ec` | `0x9f4` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x1194` | `0x119c` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1b20` | `0x1b24` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x6c0` | `0x6c4` | **`+0x4`** |

### Other Changes

```diff

-132.0.0.0.0
+134.0.0.0.0

-  Functions: 11295
-  Symbols:   4070
-  CStrings:  1213
+  Functions: 11337
+  Symbols:   4086
+  CStrings:  1219
Symbols:
+ __DATA__TtCC16VisualGeneration19GenmojiCacheManagerP33_F885AFE56058A85CF9680E2643C5E36D7WeakRef
+ __IVARS__TtCC16VisualGeneration19GenmojiCacheManagerP33_F885AFE56058A85CF9680E2643C5E36D7WeakRef
+ __METACLASS_DATA__TtCC16VisualGeneration19GenmojiCacheManagerP33_F885AFE56058A85CF9680E2643C5E36D7WeakRef
+ ___swift_memcpy18_8
+ _objc_retain_x11
+ _symbolic _____ 16VisualGeneration0B12ErrorContextV
+ _symbolic _____ 16VisualGeneration19GenmojiCacheManagerC7WeakRef33_F885AFE56058A85CF9680E2643C5E36DLLC
+ _symbolic _____Sg 15ModelInterfaces32VisualGenerationInferenceRequestV6GenderO
+ _symbolic _____Sg 15ModelInterfaces32VisualGenerationInferenceRequestV8SkinToneO
+ _symbolic _____SgXw 16VisualGeneration19GenmojiCacheManagerC
+ _symbolic _____Sg_ABt 15ModelInterfaces12SafetyInputsV
+ _symbolic _____Sg_ABt 15ModelInterfaces30VisualGenerationInferenceImageV7PurposeO
+ _symbolic ______p 16VisualGeneration15CreationRequestP
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 15ModelInterfaces32VisualGenerationInferenceRequestV13PromptSegmentV9AttributeO
+ _symbolic _____y_____Sg_____G s13ManagedBufferCsRi__rlE 16VisualGeneration19GenmojiCacheManagerC7WeakRef33_F885AFE56058A85CF9680E2643C5E36DLLC So16os_unfair_lock_sV
+ _type_layout_string 16VisualGeneration0B12ErrorContextV
CStrings:
+ "FaceAttributes(gender:"
+ "MAD unified embedding is no longer supported for imageClipEncoderVersion:"
+ "Result %ld: promptUsed from protobuf = %{private}s"
+ "Safety-failed image could not be decoded: %@"
+ "Server log (result %ld): %{private}s"
+ "_loggingToSendBackToClient"
+ "safetyPreprocessOnly"
- "No VGMADUnifiedEmbeddingVersion for imageClipEncoderVersion:"
```
