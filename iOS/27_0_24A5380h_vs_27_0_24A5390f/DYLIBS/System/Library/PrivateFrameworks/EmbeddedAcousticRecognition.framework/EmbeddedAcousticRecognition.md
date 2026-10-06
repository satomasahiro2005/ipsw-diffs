## EmbeddedAcousticRecognition

> `/System/Library/PrivateFrameworks/EmbeddedAcousticRecognition.framework/EmbeddedAcousticRecognition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb80ac4` | `0xb82720` | **`+0x1c5c`** |
| `__TEXT.__gcc_except_tab` | `0xc29b8` | `0xc2c6c` | **`+0x2b4`** |
| `__AUTH_CONST.__objc_const` | `0xe9d8` | `0xeb58` | **`+0x180`** |
| `__TEXT.__objc_methlist` | `0x6df4` | `0x6e6c` | **`+0x78`** |
| `__AUTH.__objc_data` | `0x240` | `0x290` | **`+0x50`** |
| `__TEXT.__cstring` | `0x80227` | `0x80267` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3c030` | `0x3c068` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x2500` | `0x2528` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0xa4c` | `0xa64` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3828` | `0x3840` | **`+0x18`** |
| `__TEXT.__const` | `0x5e9c8` | `0x5e9d8` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x3b4d` | `0x3b41` | **`-0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x580` | `0x588` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x3f8` | `0x400` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x43f` | `0x440` | **`+0x1`** |

### Other Changes

```diff

-3600.69.1.0.0
+3600.71.1.0.0

-  Functions: 40352
-  Symbols:   60543
-  CStrings:  20115
+  Functions: 40367
+  Symbols:   60576
+  CStrings:  20118
Symbols:
+ -[_EARTokenPostProcessor _tokenizer]
+ -[_EARTokenPostProcessor processTokens:donateEmojiUsage:usePersonalizedEmoji:requestContext:]
+ -[_EARTokenPostProcessor tokenizeLeftContext:]
+ -[_EARTokenPostProcessorRequestContext .cxx_destruct]
+ -[_EARTokenPostProcessorRequestContext initWithRelevantTextContext:]
+ -[_EARTokenPostProcessorRequestContext leftContext]
+ -[_EARTokenPostProcessorRequestContext rightContext]
+ -[_EARTokenPostProcessorRequestContext setLeftContext:]
+ -[_EARTokenPostProcessorRequestContext setRightContext:]
+ GCC_except_table994
+ GCC_except_table995
+ GCC_except_table997
+ _OBJC_CLASS_$__EARTokenPostProcessorRequestContext
+ _OBJC_IVAR_$__EARTokenPostProcessor._cachedLeftContext
+ _OBJC_IVAR_$__EARTokenPostProcessor._cachedLeftContextTokens
+ _OBJC_IVAR_$__EARTokenPostProcessor._casePredictor
+ _OBJC_IVAR_$__EARTokenPostProcessor._tokenizer
+ _OBJC_IVAR_$__EARTokenPostProcessorRequestContext._leftContext
+ _OBJC_IVAR_$__EARTokenPostProcessorRequestContext._rightContext
+ _OBJC_METACLASS_$__EARTokenPostProcessorRequestContext
+ __OBJC_$_INSTANCE_METHODS__EARTokenPostProcessorRequestContext
+ __OBJC_$_INSTANCE_VARIABLES__EARTokenPostProcessorRequestContext
+ __OBJC_$_PROP_LIST__EARTokenPostProcessorRequestContext
+ __OBJC_CLASS_RO_$__EARTokenPostProcessorRequestContext
+ __OBJC_METACLASS_RO_$__EARTokenPostProcessorRequestContext
+ __ZN6quasar13CasePredictor22predictFirstWordCasingERKNSt3__16vectorINS_5TokenENS1_9allocatorIS3_EEEERKNS2_INS1_12basic_stringIcNS1_11char_traitsIcEENS4_IcEEEENS4_ISD_EEEE
+ __ZN6quasar13CasePredictorC1ERNS_12SystemConfigE
+ __ZN6quasar13CasePredictorC2ERNS_12SystemConfigE
+ __ZN6quasar13CasePredictorC2Ev
+ __ZNSt3__110unique_ptrIN6quasar13CasePredictorENS_14default_deleteIS2_EEE5resetB9foe220106EPS2_
+ __ZNSt3__110unique_ptrIN6quasar7LexiconENS_14default_deleteIS2_EEED1B9foe220106Ev
+ ___68-[_EARTokenPostProcessorRequestContext initWithRelevantTextContext:]_block_invoke
+ ___block_descriptor_40_ea8_32s_e55_v40?0"NSString"8"NSString"16"NSArray"24"NSArray"32ls32l8
CStrings:
+ " ms"
+ "Failed to convert u32string "
+ "Tokenization duration: "
```
